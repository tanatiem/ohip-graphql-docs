# FinancialTransactionDetails
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `financialTransactionDetails`
> Detailed information on all posted transactions including net and gross amounts currency calendar and financial period market and rate code
  
**Return:** [`[FinancialTransactionDetailsType]`](#financialtransactiondetailstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`FinancialTransactionDetailsQueryArgumentsType!`](#financialtransactiondetailsqueryargumentstype) |  |

## Object Types

### FinancialTransactionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| financialTransactionDetails | [`FinancialTransactionDetailsFinancialTransactionDetailsType`](#financialtransactiondetailsfinancialtransactiondetailstype) | Financial Transaction |
| eventPostingDetails | [`FinancialTransactionDetailsEventPostingDetailsType`](#financialtransactiondetailseventpostingdetailstype) | Event Posting Details |
| propertyBudgetForecastDetails | [`FinancialTransactionDetailsPropertyBudgetForecastDetailsType`](#financialtransactiondetailspropertybudgetforecastdetailstype) | Property Budget Forecast |
| exportMapFintrxcodesDetails | [`FinancialTransactionDetailsExportMapFintrxcodesDetailsType`](#financialtransactiondetailsexportmapfintrxcodesdetailstype) | Export Map Fintrxcodes |
| exportMapPayMethDetails | [`FinancialTransactionDetailsExportMapPayMethDetailsType`](#financialtransactiondetailsexportmappaymethdetailstype) | Export Map Pay Meth |
| propertyPropertyDetails | [`FinancialTransactionDetailsPropertyPropertyDetailsType`](#financialtransactiondetailspropertypropertydetailstype) | Resort Details |
| accountDetails | [`FinancialTransactionDetailsAccountDetailsType`](#financialtransactiondetailsaccountdetailstype) | Account Details |
| articleDetails | [`FinancialTransactionDetailsArticleDetailsType`](#financialtransactiondetailsarticledetailstype) | Article Details |
| calendarPeriodDetails | [`FinancialTransactionDetailsCalendarPeriodDetailsType`](#financialtransactiondetailscalendarperioddetailstype) | Calendar Period Details |
| cashierDetails | [`FinancialTransactionDetailsCashierDetailsType`](#financialtransactiondetailscashierdetailstype) | Cashier Details |
| employeeDetails | [`FinancialTransactionDetailsEmployeeDetailsType`](#financialtransactiondetailsemployeedetailstype) | Employee Details |
| exportMapPackagecodesDetails | [`FinancialTransactionDetailsExportMapPackagecodesDetailsType`](#financialtransactiondetailsexportmappackagecodesdetailstype) | Export Map Packagecodes |
| financialPeriodDetails | [`FinancialTransactionDetailsFinancialPeriodDetailsType`](#financialtransactiondetailsfinancialperioddetailstype) | Financial Period Details |
| folioTaxDetails | [`FinancialTransactionDetailsFolioTaxDetailsType`](#financialtransactiondetailsfoliotaxdetailstype) | Folio Tax Details |
| foreignCurrencyDetails | [`FinancialTransactionDetailsForeignCurrencyDetailsType`](#financialtransactiondetailsforeigncurrencydetailstype) | Foreign Currency Details |
| invoicePaymentDetails | [`FinancialTransactionDetailsInvoicePaymentDetailsType`](#financialtransactiondetailsinvoicepaymentdetailstype) | Invoice Payment Details |
| profileAllInformationDetails | [`FinancialTransactionDetailsProfileAllInformationDetailsType`](#financialtransactiondetailsprofileallinformationdetailstype) | Profile All Details |
| rateCodeDetails | [`FinancialTransactionDetailsRateCodeDetailsType`](#financialtransactiondetailsratecodedetailstype) | Rate Code Details |
| rateSeasonDetails | [`FinancialTransactionDetailsRateSeasonDetailsType`](#financialtransactiondetailsrateseasondetailstype) | Rate Season Details |
| reportCalendarDetails | [`FinancialTransactionDetailsReportCalendarDetailsType`](#financialtransactiondetailsreportcalendardetailstype) | Report Calendar |
| reservationDetails | [`FinancialTransactionDetailsReservationDetailsType`](#financialtransactiondetailsreservationdetailstype) | Reservation Details |
| revenuePackagesDetails | [`FinancialTransactionDetailsRevenuePackagesDetailsType`](#financialtransactiondetailsrevenuepackagesdetailstype) | Revenue Packages Details |
| roomDetails | [`FinancialTransactionDetailsRoomDetailsType`](#financialtransactiondetailsroomdetailstype) | Room Details |
| routingInstructionDetails | [`FinancialTransactionDetailsRoutingInstructionDetailsType`](#financialtransactiondetailsroutinginstructiondetailstype) | Routing Instruction Details |
| transactionCodeDetails | [`FinancialTransactionDetailsTransactionCodeDetailsType`](#financialtransactiondetailstransactioncodedetailstype) | Transaction Code |
| transactionCodeArrangmentDetails | [`FinancialTransactionDetailsTransactionCodeArrangmentDetailsType`](#financialtransactiondetailstransactioncodearrangmentdetailstype) | Transaction Code Arrangment |
| fromReservationDetails | [`FinancialTransactionDetailsFromReservationDetailsType`](#financialtransactiondetailsfromreservationdetailstype) | From Reservation Details |
| toReservationDetails | [`FinancialTransactionDetailsToReservationDetailsType`](#financialtransactiondetailstoreservationdetailstype) | To Reservation Details |
| financialTransactionDetailsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsFinancialTransactionDetailsType

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

### FinancialTransactionDetailsEventPostingDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentid | `Float` | Block ID |
| blockBeginDate | `Date` | Block Begin Date |
| blockEndDate | `Date` | Block End Date |
| bookId | `Float` | Book ID |
| businessDate | `DateTime` | Business Date |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cPostedToExtra | `Float` | Central Posted To Extra |
| cPostedToIncl | `Float` | Central Posted To Incl |
| cSvcTaxExtra | `Float` | Central Svc Tax Extra |
| cSvcTaxInclude | `Float` | Central Svc Tax Include |
| cTaxExtra | `Float` | Central Tax Extra |
| cTaxIncl | `Float` | Central Tax Incl |
| cTransactionExtra | `Float` | Central Trx Extra |
| cTransactionIncl | `Float` | Central Trx Incl |
| calculationRuleExtra | `String` | Service Charge is calculated [NET] or [GROSS] for Extra Revenue ? |
| calculationRuleIncluded | `String` | Service Charge is calculated [NET] or [GROSS] for Included Revenue ? |
| centralPostingRevenueExtra | `Float` | Central Posting - Revenue Extra |
| centralRevenueIncluded | `Float` | Central Revenue Included |
| centralServiceChargeIncluded | `Float` | Central Service Charge - Included |
| centralServiceChargeExtra | `Float` | Central Service Charge- Extra |
| centralTaxType | `String` | Central Tax Type |
| centralTaxTypeDescription | `String` | Central Tax Type Description |
| centralUnitPrice | `Float` | Central Unit Price |
| checkNumber | `String` | Check Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| evPostId | `Float` | Event Post ID Primary Key |
| eventId | `Float` | Event ID |
| eventpostingid | `Float` | Eventpostingid |
| extraallotmentid | `Float` | Extraallotmentid |
| extraforresvid | `Float` | Extraforresvid |
| extratranscodeid | `String` | Extratranscodeid |
| includedallotmentid | `Float` | Includedallotmentid |
| includedforresvid | `Float` | Includedforresvid |
| includedtranscodeid | `String` | Includedtranscodeid |
| insertUser | `Float` | Insert User |
| internalEventid | `Float` | Eventid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| postedById | `Float` | Posted By ID |
| postedByUserName | `String` | The User ID who posted the message. |
| postedDateExtra | `Date` | Posted Date Extra |
| postedDateIncluded | `Date` | Posted Date Included |
| postedToExtra | `Float` | Posted To Extra |
| postedToIncl | `Float` | Posted To Incl |
| postedYN | `String` | Posted YN |
| postedByProperty | `String` | Posted by Property |
| postedToRoomExtra | `String` | Posted to Room - Extra |
| postedToRoomIncluded | `String` | Posted to Room - Included |
| postingRevenueExtra | `Float` | Extra Revenue Amount |
| postinglocationid | `String` | Postinglocationid |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| resourceName | `String` | Resource Name |
| resourceType | `String` | Resource Type |
| revenueIncluded | `Float` | Included Revenue Amount |
| revenueType | `String` | Revenue Type |
| revenuetypeid | `String` | Revenuetypeid |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| serviceChargeIncluded | `Float` | Service Charge - Included |
| serviceChargePercentExtra | `Float` | Service Charge Percentage for Extra Revenue. |
| serviceChargePercentIncluded | `Float` | Service Charge Percentage for Included Revenue. |
| serviceChargeTransactionCode | `String` | Service Charge Transaction Code for Included Revenue. |
| serviceChargeExtra | `Float` | Service Charge- Extra |
| svcTaxExtra | `Float` | Svc Tax Extra |
| svcTaxInclude | `Float` | Svc Tax Include |
| svcTrxCodeExtra | `String` | Service Charge Transaction Code for Extra Revenue. |
| svcTrxNumberExtra | `Float` | Transaction ID for Service Charge included Revenue. |
| svcTrxNumberIncl | `Float` | Transaction ID for Service Charge extra Revenue. |
| taxExtra | `Float` | Tax Extra |
| taxIncl | `Float` | Tax Incl |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| transactionCodeExtraRevenue | `String` | Transactioncode for Extra Revenue |
| transactionCodeIncludedRevenue | `String` | Transactioncode for Included Revenue |
| trxExtra | `Float` | Transaction Extra |
| trxIncl | `Float` | Transaction Incl |
| trxNumberExtra | `Float` | Transaction No Extra |
| trxNumberIncl | `Float` | Transaction No Incl |
| unitPrice | `Float` | Unit Price |
| units | `Float` | Number of units which will be used to calculate the total revenue to be posted. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsPropertyBudgetForecastDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountingType | `String` | Accounting Period used by the Property. Valid Values are : CALENDAR or FISCAL. |
| accountingYear | `Float` | Accounting Year. |
| budgetCode | `String` | Budget Code |
| budgetCodeDescription | `String` | Budget Code Description |
| budgetType | `String` | Budget Type |
| budgetValue | `String` | Budget Code. Can be either Market Code Transaction Code or Custom Code. Depends on field Budget Code Type. |
| budgetValueDescription | `String` | Budget Value Description |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| centralRevenue | `Float` | Central Revenue |
| covers | `Float` | Covers |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| endDate | `Date` | End Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| lockedYN | `String` | Locked YN |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| periodType | `String` | Period Type |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| revenue | `Float` | Revenue |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomNights | `Float` | Room Nights |
| startDate | `Date` | Start Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsExportMapFintrxcodesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| codeCanDeleteYn | `String` | Code Can Delete Y/N |
| codeInsertDate | `DateTime` | Code Insert Date |
| codeInsertUser | `Float` | Code Insert User |
| codeInsertUserName | `String` | Code Insert User Name |
| codeUpdateDate | `DateTime` | Code Update Date |
| codeUpdateUser | `Float` | Code Update User |
| codeUpdateUserName | `String` | Code Update User Name |
| combinedMappingYn | `String` | Types configured with Y can be mapped via the Combined Export Mapping screen in OPERA.  User will be presented with a consolidated view of all codes. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dataType | `String` | Data Type |
| deletedFlag | `String` | Deleted Flag |
| exportMappingId | `Float` | Exp Mapping ID |
| exportValue | `String` | Code to be sent in the export. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| linkInsertDate | `DateTime` | Link Insert Date |
| linkInsertUser | `Float` | Link Insert User |
| linkInsertUserName | `String` | Link Insert User Name |
| linkUpdateDate | `DateTime` | Link Update Date |
| linkUpdateUser | `Float` | Link Update User |
| linkUpdateUserName | `String` | Link Update User Name |
| linkedCode | `String` | Code of the configuration item to which this mapping type is linked e.g. financial transaction code. |
| linkedDescription | `String` | Linked Description |
| locationID | `String` | Internal ID to uniquely identify the Property |
| lovName | `String` | Name of the LOV group to be used (from Screen Design) |
| mappedToCode | `String` | Mapped To Code |
| mappedToDescription | `String` | Mapped To Description |
| mappingCode | `String` | Code for the mapping code. |
| mappingCodeDescription | `String` | Description for the mapping code. |
| mappingTypeCode | `String` | Mapping Type Code |
| mappingTypeDescription | `String` | Mapping Type Description |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| requiredYn | `String` | Required Y/N |
| seqNumber | `Float` | Sequence No |
| shortColumnTitle | `String` | Short text for column headers while configuring consolidated export mapping. |
| trxCode | `String` | Transaction Code |
| typeCanDeleteYn | `String` | Type Can Delete Y/N |
| typeInsertDate | `DateTime` | Type Insert Date |
| typeInsertUser | `Float` | Type Insert User |
| typeInsertUserName | `String` | Type Insert User Name |
| typeUpdateDate | `DateTime` | Type Update Date |
| typeUpdateUser | `Float` | Type Update User |
| typeUpdateUserName | `String` | Type Update User Name |
| useLovYn | `String` | Show LOV button when linking this mapping code to the configuration item. |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsExportMapPayMethDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| codeCanDeleteYn | `String` | Code Can Delete Y/N |
| codeInsertDate | `DateTime` | Code Insert Date |
| codeInsertUser | `Float` | Code Insert User |
| codeInsertUserName | `String` | Code Insert User Name |
| codeUpdateDate | `DateTime` | Code Update Date |
| codeUpdateUser | `Float` | Code Update User |
| codeUpdateUserName | `String` | Code Update User Name |
| combinedMappingYn | `String` | Types configured with Y can be mapped via the Combined Export Mapping screen in OPERA.  User will be presented with a consolidated view of all codes. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dataType | `String` | Data Type |
| deletedFlag | `String` | Deleted Flag |
| exportMappingId | `Float` | Exp Mapping ID |
| exportValue | `String` | Code to be sent in the export. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| linkInsertDate | `DateTime` | Link Insert Date |
| linkInsertUser | `Float` | Link Insert User |
| linkInsertUserName | `String` | Link Insert User Name |
| linkUpdateDate | `DateTime` | Link Update Date |
| linkUpdateUser | `Float` | Link Update User |
| linkUpdateUserName | `String` | Link Update User Name |
| linkedCode | `String` | Code of the configuration item to which this mapping type is linked e.g. financial transaction code. |
| linkedDescription | `String` | Linked Description |
| locationID | `String` | Internal ID to uniquely identify the Property |
| lovName | `String` | Name of the LOV group to be used (from Screen Design) |
| mappedToCode | `String` | Mapped To Code |
| mappedToDescription | `String` | Mapped To Description |
| mappingCode | `String` | Code for the mapping code. |
| mappingCodeDescription | `String` | Description for the mapping code. |
| mappingTypeCode | `String` | Mapping Type Code |
| mappingTypeDescription | `String` | Mapping Type Description |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| requiredYn | `String` | Required Y/N |
| seqNumber | `Float` | Sequence No |
| shortColumnTitle | `String` | Short text for column headers while configuring consolidated export mapping. |
| trxCode | `String` | Transaction Code |
| typeCanDeleteYn | `String` | Type Can Delete Y/N |
| typeInsertDate | `DateTime` | Type Insert Date |
| typeInsertUser | `Float` | Type Insert User |
| typeInsertUserName | `String` | Type Insert User Name |
| typeUpdateDate | `DateTime` | Type Update Date |
| typeUpdateUser | `Float` | Type Update User |
| typeUpdateUserName | `String` | Type Update User Name |
| useLovYn | `String` | Show LOV button when linking this mapping code to the configuration item. |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsPropertyPropertyDetailsType

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

### FinancialTransactionDetailsAccountDetailsType

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

### FinancialTransactionDetailsArticleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activeYN | `String` | Active YN |
| articleCode | `String` | Article Code |
| articleDescription | `String` | Article Description |
| articleId | `Float` | Article ID |
| availableInPostItYN | `String` | Available in Post It YN |
| cDefaultPrice | `Float` | Central Default Price |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| centralArticleCode | `String` | Central Article Code |
| centralArticleDescription | `String` | Central Article Description |
| centralSequence | `Float` | Central Sequence |
| centralTransactionCode | `String` | Central Transaction Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultPrice | `Float` | Default Price |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | The button colour used in the Postit screen for this article. |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalArticleid | `Float` | Articleid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| transactionCode | `String` | Transaction Code |
| transcodeid | `String` | Transcodeid |
| uPC | `String` | UPC |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsCalendarPeriodDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
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

### FinancialTransactionDetailsCashierDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activeYN | `String` | Active YN |
| amtDifferenceInitial | `Float` | The difference in cash the cashier must pay or receive when the cashier is set up. |
| attachedToUser | `String` | Application User Name |
| cAmountDifferenceInitial | `Float` | Central Amt Diff Initial |
| cAmountFloat | `Float` | Central Amt Float |
| cCashierBalance | `Float` | Central Cashier Bal |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cashierBal | `Float` | At the time he closes his account on that day after drop off the difference in cash he has to pay or has to be paid. |
| cashierid | `Float` | Cashierid |
| chainCode | `String` | Chain Code |
| closureInProgressYn | `String` | Indicates if the cashier is in progress to be closed. |
| closureNo | `Float` | Closure Number |
| csrTrxNumber | `Float` | CSR Trx No. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateoflastuse | `Date` | Date of last use. |
| deletedflag | `String` | Deleted Flag |
| floatOverShort | `String` | Parameter to set up whether the cashier has to drop the whole cash including the float or just the amt excess of float. |
| generalCashierYN | `String` | Determines whether the cashier is a General cashier. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| interfaceCashierYN | `String` | Decides whether the cashier number is used in interfaces or not. The interface cashiers cannot have numbers more than 999. |
| internalUpdateYn | `String` | Internally used. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| kioskCashierYN | `String` | Identifies if the cashier is used by KIOSK interfaces. Only one KIOSK cashier is allowed. |
| lastOpened | `Date` | Date Last Opened. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| maximumDailyUses | `Float` | The no. of times cashier is allowed to open per day. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentsCashierCode | `Float` | Payments-Cashier Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| reservedResort | `String` | Property that this cashier is reserved for. Used for floating cashier functionality. |
| reservedYn | `String` | Identifies if this cashier is currently being used as a floating cashier. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| startingAmount | `Float` | The initial amount the cashier should have every day. |
| state | `String` | State |
| timeoffirstopen | `Date` | Time first time he opened on that day. |
| timeoflastclose | `Date` | Time cashier last closed on that day. |
| timesOpened | `Float` | The no. of times the cashier opened his account today. |
| tranActionId | `Float` | Tran Action ID |
| transactionsCashierName | `String` | Transactions-Cashier Name |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsEmployeeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accessConfig | `String` | Allow user access to Configuration. |
| accessEod | `String` | Allow user access to End of Day. |
| accessObi | `String` | Allow user access to Opera BI. |
| accessOcis | `String` | Allow user access to OCIS. |
| accessOcm | `String` | Allow user access to Channel Mangement. |
| accessOcrm | `String` | Allow user access to OCRM. |
| accessOrms | `String` | Allow user access to Opera Revenue Management System. |
| accessOrs | `String` | Allow user access to ORS. |
| accessOxi | `String` | Allow user access to OXI. |
| accessOxihub | `String` | Allow user access to OXIHUB. |
| accessPms | `String` | Allow user access to PMS. |
| accessSc | `String` | Allow user access to SC. |
| accessScbi | `String` | Allow user access to OPERA S&C Analytics. |
| accessSfa | `String` | Allow user access to SFA. |
| accessUtil | `String` | Allow user access to Utilities. |
| accountLockedOutYn | `String` | Indicates if user is allowed to login in the application. |
| agent | `String` | Agent |
| appUserType | `String` | Defines the type of user.Valid values: U and G U-->User :: G-->Group |
| authorizerInactiveDate | `DateTime` | Date the authorizer became inactive |
| authorizerRateCode | `String` | Default rate code for this authorizer. |
| authorizerYn | `String` | Denotes if this user is an authorizer. Allowable values are 'Y' and 'N' |
| birthDate | `Date` | Birth Date |
| businessTitle | `String` | Business Title |
| businessTitleDescription | `String` | Business Title Description |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cHourlyRate | `Float` | Central Hourly Rate |
| cWeeklySalary | `Float` | Central Weekly Salary |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateHired | `Date` | Date employee was hired |
| defCashierId | `Float` | Cashier ID for the User |
| defaultForm | `String` | Not Used |
| defaultMfnResort | `String` | Not used. |
| defaultReportgroup | `String` | Defaults the Report Module to this Report Group |
| defaultResort | `String` | Stores resort name to which user will log in every time |
| deletedflag | `String` | Deleted Flag |
| departmentid | `String` | Departmentid |
| deptEmail | `String` | Department E-Mail Address. |
| deptId | `String` | Dept ID |
| deptManagerPager | `String` | Pager number of department manager |
| deptName | `String` | Description of the department |
| deptOrderBy | `Float` | Dept Order By |
| disabledUntil | `Date` | When account is disabled this date is set to date when account should be enabled again |
| eMail | `String` | E Mail |
| empExtension | `String` | Employee Extension Number |
| empStatus | `String` | Emp Status |
| employeeIncentiveNumber | `String` | Identifies a hotel employee for incentive programs. |
| employeeNumber | `String` | This column is used by Starwood Hotels for Storing their internal employee number |
| employeeid | `Float` | Employeeid |
| expiresOn | `Date` | Date on which user ID will be disabled. |
| first | `String` | First |
| forcePasswordChangeYn | `String` | Requires the user to change the password at login. |
| fridayMax | `Float` | Max hours for Friday |
| fridayMin | `Float` | Min hours for Friday |
| generalFilepath | `String` | Stores General File path for Mailmerge |
| graceLogin | `Float` | Number of Logins allowed after password has expired |
| hireType | `String` | Type of hire: F-Full Time P-Part Time |
| hourlyRate | `Float` | If RATE_TYPE=H: hourly employee rate |
| hoursPerWeek | `Float` | Hours Per Week |
| inactiveDesc | `String` | Inactive Description |
| inactiveFrom | `Date` | Inactive Start Date |
| inactiveReasonCode | `String` | Reason Code for inactive status from REASON table |
| inactiveTo | `Date` | Inactive End Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopId | `Float` | Laptop ID |
| last | `String` | Last |
| leadAddress | `String` | Lead Address Code determines primary receipient |
| leadAddressDet | `String` | Lead Address (email/fax no) |
| leadComm | `String` | Lead Communication Type |
| locationID | `String` | Internal ID to uniquely identify the Property |
| lockoutDate | `DateTime` | Timestamp with the useraccount was locked out. |
| loginCro | `String` | Login Cro |
| loginDomain | `String` | Login Domain |
| maleFemale | `String` | Employee Gender |
| maxCheckoutDays | `Float` | Maximum number of days allowed for checkout in Laptop Module |
| maxUserSessions | `Float` | Maximum number of Opera Sessions allowed at single point of time. |
| mfnUserType | `String` | User type for OCM mode: [C]orporate User |
| middle | `String` | Middle |
| mobileAlertsYn | `String` | Indiciates if alerts are send to mobile registered guests for required action and manual checkout.. |
| mondayMax | `Float` | Max hours for Monday |
| mondayMin | `Float` | Min hours for Monday |
| nameNotes | `String` | Name Notes |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| otMultiplier | `Float` | Overtime Multiplier |
| passwordChangeDays | `Float` | Period of Days the Password expires |
| passwordLastChange | `Date` | TimeStamp of last Password Change |
| personNameId | `Float` | Foreign key to NAME table that links this USER to an Employee |
| phoneNo | `String` | Phone no. |
| phoneNumber | `String` | Phone Number |
| preventAccountLockout | `String` | Indicates if this user can be excluded from user account lock. |
| primaryBlockOwnerName | `String` | Primary Block Owner Name |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryRoomsOwnerCode | `String` | Primary Rooms Owner Code |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateType | `String` | Rate Type |
| receiveBroadcastMsg | `String` | Receive Broadcast Msg |
| rehireYn | `String` | Indicates if a terminated employee shall be rehired |
| salaryInterval | `String` | Salary Interval: M-Monthly W-Weekly |
| saturdayMax | `Float` | Max hours for Saturday |
| saturdayMin | `Float` | Min hours for Saturday |
| serviceRequestAlertsYn | `String` | Indicates if this Application User can receive Alerts related to Service Requests. |
| sfaName | `String` | Sfa Name |
| srepGroup | `String` | Assigned Sales Manager Group(s) |
| sundayMax | `Float` | Max hours for Sunday |
| sundayMin | `Float` | Min hours for Sunday |
| termReason | `String` | Termination Reason |
| terminatedDate | `Date` | Termination Date |
| territory | `String` | Territory |
| thursdayMax | `Float` | Max hours for Thursday |
| thursdayMin | `Float` | Min hours for Thursday |
| timezoneRegion | `String` | Time zone region selected by the employee. |
| tuesdayMax | `Float` | Max hours for Tuesday |
| tuesdayMin | `Float` | Min hours for Tuesday |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| userFilepath | `String` | Store User File path. for Mailmerge |
| userID | `Float` | User ID |
| userPbxId | `Float` | PBX ID - referred as password to access PBX system |
| wednesdayMax | `Float` | Max hours for Wednesday |
| wednesdayMin | `Float` | Min hours for Wednesday |
| weekMax | `Float` | Maximum total hours this employee can work per week |
| weekMin | `Float` | Minimum total hours this employee can work per week |
| weeklySalary | `Float` | Weekly Salary |
| workPermitExpdate | `Date` | Workpermit Expiration date |
| workPermitNo | `String` | Working Permit Number |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsExportMapPackagecodesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| codeCanDeleteYn | `String` | Code Can Delete Y/N |
| codeInsertDate | `DateTime` | Code Insert Date |
| codeInsertUser | `Float` | Code Insert User |
| codeInsertUserName | `String` | Code Insert User Name |
| codeUpdateDate | `DateTime` | Code Update Date |
| codeUpdateUser | `Float` | Code Update User |
| codeUpdateUserName | `String` | Code Update User Name |
| combinedMappingYn | `String` | Types configured with Y can be mapped via the Combined Export Mapping screen in OPERA.  User will be presented with a consolidated view of all codes. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dataType | `String` | Data Type |
| deletedFlag | `String` | Deleted Flag |
| exportMappingId | `Float` | Exp Mapping ID |
| exportValue | `String` | Code to be sent in the export. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| linkInsertDate | `DateTime` | Link Insert Date |
| linkInsertUser | `Float` | Link Insert User |
| linkInsertUserName | `String` | Link Insert User Name |
| linkUpdateDate | `DateTime` | Link Update Date |
| linkUpdateUser | `Float` | Link Update User |
| linkUpdateUserName | `String` | Link Update User Name |
| linkedCode | `String` | Code of the configuration item to which this mapping type is linked e.g. financial transaction code. |
| linkedDescription | `String` | Linked Description |
| locationID | `String` | Internal ID to uniquely identify the Property |
| lovName | `String` | Name of the LOV group to be used (from Screen Design) |
| mappedToCode | `String` | Mapped To Code |
| mappedToDescription | `String` | Mapped To Description |
| mappingCode | `String` | Code for the mapping code. |
| mappingCodeDescription | `String` | Description for the mapping code. |
| mappingTypeCode | `String` | Mapping Type Code |
| mappingTypeDescription | `String` | Mapping Type Description |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| product | `String` | Product |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| requiredYn | `String` | Required Y/N |
| seqNumber | `Float` | Sequence No |
| shortColumnTitle | `String` | Short text for column headers while configuring consolidated export mapping. |
| typeCanDeleteYn | `String` | Type Can Delete Y/N |
| typeInsertDate | `DateTime` | Type Insert Date |
| typeInsertUser | `Float` | Type Insert User |
| typeInsertUserName | `String` | Type Insert User Name |
| typeUpdateDate | `DateTime` | Type Update Date |
| typeUpdateUser | `Float` | Type Update User |
| typeUpdateUserName | `String` | Type Update User Name |
| useLovYn | `String` | Show LOV button when linking this mapping code to the configuration item. |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsFinancialPeriodDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
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

### FinancialTransactionDetailsFolioTaxDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountCode | `Float` | Account Code |
| addresseeNameId | `Float` | Addressee Name ID |
| amountPostedFromAR | `Float` | This is to store amount posted from AR for a bill. In this case CLPAY will not have value if the bill is generated in AR |
| amountFromDirectBill | `Float` | The amount that has been paid using direct bill. |
| associatedBillDate | `Date` | Date on which the Original Bill was generated. This is used in case of Credit Bill. |
| associatedBillNumber | `String` | Associated Bill Number |
| associatedFiscalBillDate | `Date` | Associated Fiscal Bill number generation date. |
| associatedFiscalBillNumber | `String` | Associated Fiscal Bill number. |
| associatedFiscalBillNumberGenerationTime | `String` | Associated Fiscal Bill number generation time. |
| associatedSeqNumber | `Float` | Self referencing sequence number to gather information for other operations. |
| billGenerationDate | `Date` | Bill Generation Date |
| billNumber | `Float` | Bill Number |
| billPaymentTrxNumber | `Float` | Bill Payment Transaction No |
| billPrefix | `String` | Bill Prefix |
| billSequenceNumber | `Float` | Bill Sequence Number |
| billStartDate | `Date` | Date of the first charge in the bill. |
| billStatus | `String` | Bill Status |
| businessDate | `Date` | Business Date |
| businessId | `String` | Business ID |
| cCashpay | `Float` | Central Cashpay |
| cCcpay | `Float` | Central Ccpay |
| cClarpay | `Float` | Central Clarpay |
| cClpay | `Float` | Central Clpay |
| cCollectionTax1 | `Float` | Central Coll Tax1 |
| cCollectionTax2 | `Float` | Central Coll Tax2 |
| cCollectionTax3 | `Float` | Central Coll Tax3 |
| cCollectionTax4 | `Float` | Central Coll Tax4 |
| cCollectionTax5 | `Float` | Central Coll Tax5 |
| cDailyRunningTotal | `Float` | Central Daily Running Total |
| cDeposit | `Float` | Central Deposit |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFiscalInvoiceCurrencyRate | `Float` | Central Fiscal Invoice Currency Rate |
| cNet1Amount | `Float` | Central Net1 Amt |
| cNet10Amount | `Float` | Central Net10 Amt |
| cNet11Amount | `Float` | Central Net11 Amt |
| cNet12Amount | `Float` | Central Net12 Amt |
| cNet13Amount | `Float` | Central Net13 Amt |
| cNet14Amount | `Float` | Central Net14 Amt |
| cNet15Amount | `Float` | Central Net15 Amt |
| cNet16Amount | `Float` | Central Net16 Amt |
| cNet17Amount | `Float` | Central Net17 Amt |
| cNet18Amount | `Float` | Central Net18 Amt |
| cNet19Amount | `Float` | Central Net19 Amt |
| cNet2Amount | `Float` | Central Net2 Amt |
| cNet20Amount | `Float` | Central Net20 Amt |
| cNet3Amount | `Float` | Central Net3 Amt |
| cNet4Amount | `Float` | Central Net4 Amt |
| cNet5Amount | `Float` | Central Net5 Amt |
| cNet6Amount | `Float` | Central Net6 Amt |
| cNet7Amount | `Float` | Central Net7 Amt |
| cNet8Amount | `Float` | Central Net8 Amt |
| cNet9Amount | `Float` | Central Net9 Amt |
| cPaidout | `Float` | Central Paidout |
| cPerpetualAmount | `Float` | Central Perpetual Amount |
| cPnet1Amount | `Float` | Central Pnet1 Amt |
| cPnet10Amount | `Float` | Central Pnet10 Amt |
| cPnet11Amount | `Float` | Central Pnet11 Amt |
| cPnet12Amount | `Float` | Central Pnet12 Amt |
| cPnet13Amount | `Float` | Central Pnet13 Amt |
| cPnet14Amount | `Float` | Central Pnet14 Amt |
| cPnet15Amount | `Float` | Central Pnet15 Amt |
| cPnet16Amount | `Float` | Central Pnet16 Amt |
| cPnet17Amount | `Float` | Central Pnet17 Amt |
| cPnet18Amount | `Float` | Central Pnet18 Amt |
| cPnet19Amount | `Float` | Central Pnet19 Amt |
| cPnet2Amount | `Float` | Central Pnet2 Amt |
| cPnet20Amount | `Float` | Central Pnet20 Amt |
| cPnet3Amount | `Float` | Central Pnet3 Amt |
| cPnet4Amount | `Float` | Central Pnet4 Amt |
| cPnet5Amount | `Float` | Central Pnet5 Amt |
| cPnet6Amount | `Float` | Central Pnet6 Amt |
| cPnet7Amount | `Float` | Central Pnet7 Amt |
| cPnet8Amount | `Float` | Central Pnet8 Amt |
| cPnet9Amount | `Float` | Central Pnet9 Amt |
| cPtax1Amount | `Float` | Central Ptax1 Amt |
| cPtax10Amount | `Float` | Central Ptax10 Amt |
| cPtax11Amount | `Float` | Central Ptax11 Amt |
| cPtax12Amount | `Float` | Central Ptax12 Amt |
| cPtax13Amount | `Float` | Central Ptax13 Amt |
| cPtax14Amount | `Float` | Central Ptax14 Amt |
| cPtax15Amount | `Float` | Central Ptax15 Amt |
| cPtax16Amount | `Float` | Central Ptax16 Amt |
| cPtax17Amount | `Float` | Central Ptax17 Amt |
| cPtax18Amount | `Float` | Central Ptax18 Amt |
| cPtax19Amount | `Float` | Central Ptax19 Amt |
| cPtax2Amount | `Float` | Central Ptax2 Amt |
| cPtax20Amount | `Float` | Central Ptax20 Amt |
| cPtax3Amount | `Float` | Central Ptax3 Amt |
| cPtax4Amount | `Float` | Central Ptax4 Amt |
| cPtax5Amount | `Float` | Central Ptax5 Amt |
| cPtax6Amount | `Float` | Central Ptax6 Amt |
| cPtax7Amount | `Float` | Central Ptax7 Amt |
| cPtax8Amount | `Float` | Central Ptax8 Amt |
| cPtax9Amount | `Float` | Central Ptax9 Amt |
| cPtotNonrevNonTaxable | `Float` | Central Ptot Nonrev Nontaxable |
| cPtotNonrevTaxable | `Float` | Central Ptot Nonrev Taxable |
| cPtotRevenueNonTaxable | `Float` | Central Ptot Rev Nontaxable |
| cPtotRevenueTaxable | `Float` | Central Ptot Rev Taxable |
| cRealPerpetualAmount | `Float` | Central Real Perpetual Amount |
| cTax1Amount | `Float` | Central Tax1 Amt |
| cTax2Amount | `Float` | Central Tax2 Amt |
| cTaxCode1 | `String` | Central Tax Code 1 |
| cTaxCode10 | `String` | Central Tax Code 10 |
| cTaxCode11 | `String` | Central Tax Code 11 |
| cTaxCode12 | `String` | Central Tax Code 12 |
| cTaxCode13 | `String` | Central Tax Code 13 |
| cTaxCode14 | `String` | Central Tax Code 14 |
| cTaxCode15 | `String` | Central Tax Code 15 |
| cTaxCode16 | `String` | Central Tax Code 16 |
| cTaxCode17 | `String` | Central Tax Code 17 |
| cTaxCode18 | `String` | Central Tax Code 18 |
| cTaxCode19 | `String` | Central Tax Code 19 |
| cTaxCode2 | `String` | Central Tax Code 2 |
| cTaxCode20 | `String` | Central Tax Code 20 |
| cTaxCode3 | `String` | Central Tax Code 3 |
| cTaxCode4 | `String` | Central Tax Code 4 |
| cTaxCode5 | `String` | Central Tax Code 5 |
| cTaxCode6 | `String` | Central Tax Code 6 |
| cTaxCode7 | `String` | Central Tax Code 7 |
| cTaxCode8 | `String` | Central Tax Code 8 |
| cTaxCode9 | `String` | Central Tax Code 9 |
| cTaxCodeDescription1 | `String` | Central Tax Code Desc 1 |
| cTaxCodeDescription10 | `String` | Central Tax Code Desc 10 |
| cTaxCodeDescription11 | `String` | Central Tax Code Desc 11 |
| cTaxCodeDescription12 | `String` | Central Tax Code Desc 12 |
| cTaxCodeDescription13 | `String` | Central Tax Code Desc 13 |
| cTaxCodeDescription14 | `String` | Central Tax Code Desc 14 |
| cTaxCodeDescription15 | `String` | Central Tax Code Desc 15 |
| cTaxCodeDescription16 | `String` | Central Tax Code Desc 16 |
| cTaxCodeDescription17 | `String` | Central Tax Code Desc 17 |
| cTaxCodeDescription18 | `String` | Central Tax Code Desc 18 |
| cTaxCodeDescription19 | `String` | Central Tax Code Desc 19 |
| cTaxCodeDescription2 | `String` | Central Tax Code Desc 2 |
| cTaxCodeDescription20 | `String` | Central Tax Code Desc 20 |
| cTaxCodeDescription3 | `String` | Central Tax Code Desc 3 |
| cTaxCodeDescription4 | `String` | Central Tax Code Desc 4 |
| cTaxCodeDescription5 | `String` | Central Tax Code Desc 5 |
| cTaxCodeDescription6 | `String` | Central Tax Code Desc 6 |
| cTaxCodeDescription7 | `String` | Central Tax Code Desc 7 |
| cTaxCodeDescription8 | `String` | Central Tax Code Desc 8 |
| cTaxCodeDescription9 | `String` | Central Tax Code Desc 9 |
| cTax10Amount | `Float` | Central Tax10 Amt |
| cTax11Amount | `Float` | Central Tax11 Amt |
| cTax12Amount | `Float` | Central Tax12 Amt |
| cTax13Amount | `Float` | Central Tax13 Amt |
| cTax14Amount | `Float` | Central Tax14 Amt |
| cTax15Amount | `Float` | Central Tax15 Amt |
| cTax16Amount | `Float` | Central Tax16 Amt |
| cTax17Amount | `Float` | Central Tax17 Amt |
| cTax18Amount | `Float` | Central Tax18 Amt |
| cTax19Amount | `Float` | Central Tax19 Amt |
| cTax20Amount | `Float` | Central Tax20 Amt |
| cTax3Amount | `Float` | Central Tax3 Amt |
| cTax4Amount | `Float` | Central Tax4 Amt |
| cTax5Amount | `Float` | Central Tax5 Amt |
| cTax6Amount | `Float` | Central Tax6 Amt |
| cTax7Amount | `Float` | Central Tax7 Amt |
| cTax8Amount | `Float` | Central Tax8 Amt |
| cTax9Amount | `Float` | Central Tax9 Amt |
| cTotalGross | `Float` | Central Total Gross |
| cTotalNet | `Float` | Central Total Net |
| cTotalNonTaxable | `Float` | Central Total Nontaxable |
| cTotalNonrevNonTaxable | `Float` | Central Tot Nonrev Nontaxable |
| cTotalNonrevTaxable | `Float` | Central Tot Nonrev Taxable |
| cTotalRevenueNonTaxable | `Float` | Central Tot Rev Nontaxable |
| cTotalRevenueTaxable | `Float` | Central Tot Rev Taxable |
| cTotalTax | `Float` | Central Total Tax |
| cXnet1Amount | `Float` | Central Xnet1 Amt |
| cXnet10Amount | `Float` | Central Xnet10 Amt |
| cXnet11Amount | `Float` | Central Xnet11 Amt |
| cXnet12Amount | `Float` | Central Xnet12 Amt |
| cXnet13Amount | `Float` | Central Xnet13 Amt |
| cXnet14Amount | `Float` | Central Xnet14 Amt |
| cXnet15Amount | `Float` | Central Xnet15 Amt |
| cXnet16Amount | `Float` | Central Xnet16 Amt |
| cXnet17Amount | `Float` | Central Xnet17 Amt |
| cXnet18Amount | `Float` | Central Xnet18 Amt |
| cXnet19Amount | `Float` | Central Xnet19 Amt |
| cXnet2Amount | `Float` | Central Xnet2 Amt |
| cXnet20Amount | `Float` | Central Xnet20 Amt |
| cXnet3Amount | `Float` | Central Xnet3 Amt |
| cXnet4Amount | `Float` | Central Xnet4 Amt |
| cXnet5Amount | `Float` | Central Xnet5 Amt |
| cXnet6Amount | `Float` | Central Xnet6 Amt |
| cXnet7Amount | `Float` | Central Xnet7 Amt |
| cXnet8Amount | `Float` | Central Xnet8 Amt |
| cXnet9Amount | `Float` | Central Xnet9 Amt |
| cXtax1Amount | `Float` | Central Xtax1 Amt |
| cXtax10Amount | `Float` | Central Xtax10 Amt |
| cXtax11Amount | `Float` | Central Xtax11 Amt |
| cXtax12Amount | `Float` | Central Xtax12 Amt |
| cXtax13Amount | `Float` | Central Xtax13 Amt |
| cXtax14Amount | `Float` | Central Xtax14 Amt |
| cXtax15Amount | `Float` | Central Xtax15 Amt |
| cXtax16Amount | `Float` | Central Xtax16 Amt |
| cXtax17Amount | `Float` | Central Xtax17 Amt |
| cXtax18Amount | `Float` | Central Xtax18 Amt |
| cXtax19Amount | `Float` | Central Xtax19 Amt |
| cXtax2Amount | `Float` | Central Xtax2 Amt |
| cXtax20Amount | `Float` | Central Xtax20 Amt |
| cXtax3Amount | `Float` | Central Xtax3 Amt |
| cXtax4Amount | `Float` | Central Xtax4 Amt |
| cXtax5Amount | `Float` | Central Xtax5 Amt |
| cXtax6Amount | `Float` | Central Xtax6 Amt |
| cXtax7Amount | `Float` | Central Xtax7 Amt |
| cXtax8Amount | `Float` | Central Xtax8 Amt |
| cXtax9Amount | `Float` | Central Xtax9 Amt |
| cashRegisterId | `String` | Cash Register ID |
| cashRegisterInvNumber | `Float` | Internal sequence number for the Cash Register ID. |
| cashTotal | `Float` | Total paid in cash |
| cashierID | `Float` | Cashier ID |
| centralTaxRate1 | `Float` | Central Tax Rate 1 |
| centralTaxRate10 | `Float` | Central Tax Rate 10 |
| centralTaxRate11 | `Float` | Central Tax Rate 11 |
| centralTaxRate12 | `Float` | Central Tax Rate 12 |
| centralTaxRate13 | `Float` | Central Tax Rate 13 |
| centralTaxRate14 | `Float` | Central Tax Rate 14 |
| centralTaxRate15 | `Float` | Central Tax Rate 15 |
| centralTaxRate16 | `Float` | Central Tax Rate 16 |
| centralTaxRate17 | `Float` | Central Tax Rate 17 |
| centralTaxRate18 | `Float` | Central Tax Rate 18 |
| centralTaxRate19 | `Float` | Central Tax Rate 19 |
| centralTaxRate2 | `Float` | Central Tax Rate 2 |
| centralTaxRate20 | `Float` | Central Tax Rate 20 |
| centralTaxRate3 | `Float` | Central Tax Rate 3 |
| centralTaxRate4 | `Float` | Central Tax Rate 4 |
| centralTaxRate5 | `Float` | Central Tax Rate 5 |
| centralTaxRate6 | `Float` | Central Tax Rate 6 |
| centralTaxRate7 | `Float` | Central Tax Rate 7 |
| centralTaxRate8 | `Float` | Central Tax Rate 8 |
| centralTaxRate9 | `Float` | Central Tax Rate 9 |
| city | `String` | City |
| cityLedgerYN | `String` | City Ledger YN |
| clTrxNumber | `Float` | Internal number given to the direct bill payment in financial_transactions. |
| collectionAgentTotalTax1 | `Float` | Collection Agent Total Tax 1 |
| collectionAgentTotalTax2 | `Float` | Collection Agent Total Tax 2 |
| collectionAgentTotalTax3 | `Float` | Collection Agent Total Tax 3 |
| collectionAgentTotalTax4 | `Float` | Collection Agent Total Tax 4 |
| collectionAgentTotalTax5 | `Float` | Collection Agent Total Tax 5 |
| companyFinancialValue | `String` | The financial value of the company. |
| companyName | `String` | Company Name |
| companyType | `String` | The type of legal entity / company e.g. Individual Micro enterprise etc. |
| compressBillNo | `String` | To store the Compressed Bill No. and Converted Bill number information |
| creditBillGeneratedYN | `String` | Indicates if a credit bill has been generated for this folio. |
| creditBillNumber | `Float` | Credit Bill Number |
| creditCardTotal | `Float` | Total paid in the form of credit cards. |
| customNumber1 | `String` | Custom Number 1 |
| customNumber2 | `String` | Custom Number 2 |
| customNumber3 | `String` | Custom Number 3 |
| customNumber4 | `String` | Custom Number 4 |
| customNumber5 | `String` | Custom Number 5 |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyRunningTotal | `Float` | Daily running total. |
| deletedFlag | `String` | Deleted Flag |
| deposit | `Float` | Total deposits. |
| depositReqReceiptNumber | `Float` | Deposit Req Receipt Number |
| documentCode | `String` | Unique Document Code |
| documentType | `String` | Document Type |
| eArchiveEttnNumber | `String` | Unique ETTN number for an E Archive invoice. |
| eArchiveNumber | `String` | E Archive number. |
| eArchiveReportNo | `String` | E Archive report number provided by external system e.g. PROTEL. |
| eArchiveStatus | `String` | E Archive status. |
| eInvoiceNumber | `String` | E-Invoice Number |
| eInvoiceStatus | `String` | E-Invoice number received from Portal+. This number be updated via Web Service call from Portal+. |
| fiscalBillCheckDigit | `Float` | Fiscal Bill Check Digit |
| fiscalBillGenerationDate | `Date` | Fiscal Bill Generation Date |
| fiscalBillGenerationTime | `String` | Fiscal Bill Generation Time |
| fiscalBillNumber | `String` | Fiscal Bill Number |
| fiscalInvoiceCurrency | `String` | Currency Code used by and sent to the Fiscal Service. |
| fiscalInvoiceCurrencyRate | `Float` | Exchange Rate of the Fiscal Invoice currency for settlement on the bill generation date. |
| fiscalSessionNo | `String` | Session number generated by the fiscal printer. This numbers gets reset during EOD. |
| fiscalUnitControlCode | `String` | Fiscal Unit Control Code |
| folioAddress | `String` | Folio Full Address. |
| folioAddressCorrectedYn | `String` | Indicates if the folio header was corrected. |
| folioAttachmentLinkId | `Float` | Folio Attachment Link ID |
| folioAttachmentStatus | `Float` | Folio Attachment Status |
| folioNo | `Float` | Folio Number |
| folioStyle | `String` | Folio Style |
| folioTaxSeqNumber | `Float` | Folio Tax Sequence No |
| folioTime | `String` | Folio Time |
| folioType | `String` | Folio Type |
| folioType1 | `String` | Folio Type 1 |
| folioTypeJoin | `String` | Folio Type Join |
| folioView | `Float` | Folio View |
| forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| fullFolioNo | `String` | Full Folio Number |
| hasWatermarkYn | `String` | If PERMANENT FOLIO STORAGE is active this flag indicates whether the PDF file has the "Copy" watermark. |
| hotelName | `String` | Hotel name of the property at the time of bill generation. |
| insTimestamp | `DateTime` | Timestamp to capture the exact order of inserts. |
| insertDate | `DateTime` | Insert Date |
| invoiceNumber | `Float` | Invoice Number |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lastSignature | `String` | Last Signature |
| locationID | `String` | Internal ID to uniquely identify the Property |
| nRBusinessID | `String` | Business ID |
| nafApeHotelCode | `String` | NAF/APE code of the hotel at the time of bill generation. |
| nameId | `Float` | Name ID |
| nameTaxType | `String` | Name Tax Type |
| netAmount1 | `Float` | Net Amount 1 |
| netAmount10 | `Float` | Net Amount 10 |
| netAmount11 | `Float` | Net Amount 11 |
| netAmount12 | `Float` | Net Amount 12 |
| netAmount13 | `Float` | Net Amount 13 |
| netAmount14 | `Float` | Net Amount 14 |
| netAmount15 | `Float` | Net Amount 15 |
| netAmount16 | `Float` | Net Amount 16 |
| netAmount17 | `Float` | Net Amount 17 |
| netAmount18 | `Float` | Net Amount 18 |
| netAmount19 | `Float` | Net Amount 19 |
| netAmount2 | `Float` | Net Amount 2 |
| netAmount20 | `Float` | Net Amount 20 |
| netAmount3 | `Float` | Net Amount 3 |
| netAmount4 | `Float` | Net Amount 4 |
| netAmount5 | `Float` | Net Amount 5 |
| netAmount6 | `Float` | Net Amount 6 |
| netAmount7 | `Float` | Net Amount 7 |
| netAmount8 | `Float` | Net Amount 8 |
| netAmount9 | `Float` | Net Amount 9 |
| numberOfPages | `Float` | Number of pages for a given bill. |
| operaFiscalFolioStatus | `String` | This coulumn is used to store the status of Fiscal Folio /Payload Generation. The values will be SUCCESS - Payload has been sent successfully OFFLINE - User confirmed to generate Offline Folio i.e. Folio will be generated but Fiscal Folio/Payload not generated FAILURE - User do not want to create OFFLINE FOLIO but as FISCAL service is not available so the status is FAILURE i.e. in this case VOID Folio generated with FAILURE Fiscal Folio Status BLANK/NULL - Fiscal Printing is turned off or Past data after the upgrade. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pageNumber | `Float` | Stores the page number within the bill generation. |
| palmVideoFlag | `String` | Indicator to identify if the bill was generated from Video checkout or PALM.  (V->Video  P->PALM). |
| partnerFiscalFolioStatus | `String` | Partner Fiscal Folio Status |
| payeeAddress | `String` | Payee Address |
| payeeCountry | `String` | Payee Country |
| payeeFirstName | `String` | Payee First Name |
| payeeLastName | `String` | Payee Last Name |
| payeeName | `String` | Payee Name used for signature generation. |
| payeeNameID | `Float` | Payee Name ID |
| payeePostalCode | `String` | Payee Postal Code |
| payeeTaxID1 | `String` | Payee Tax ID 1 |
| payeeTaxID2 | `String` | Payee Tax ID 2 |
| payeeZipCode | `String` | Payee Zip Code used for signature generation. |
| paymentDate | `Date` | Payment Date |
| perpetualAmount | `Float` | Perpetual Amount. |
| pnet1Amt | `Float` | Parallel Net1 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| pnet10Amt | `Float` | Parallel Net10 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| pnet11Amt | `Float` | Parallel Net11 extension to the existing pnet amount. |
| pnet12Amt | `Float` | Parallel Net12 extension to the existing pnet amount. |
| pnet13Amt | `Float` | Parallel Net13 extension to the existing pnet amount. |
| pnet14Amt | `Float` | Parallel Net14 extension to the existing pnet amount. |
| pnet15Amt | `Float` | Parallel Net15 extension to the existing pnet amount. |
| pnet16Amt | `Float` | Parallel Net16 extension to the existing pnet amount. |
| pnet17Amt | `Float` | Parallel Net17 extension to the existing pnet amount. |
| pnet18Amt | `Float` | Parallel Net18 extension to the existing pnet amount. |
| pnet19Amt | `Float` | Parallel Net19 extension to the existing pnet amount. |
| pnet2Amt | `Float` | Parallel Net2 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| pnet20Amt | `Float` | Parallel Net20 extension to the existing pnet amount. |
| pnet3Amt | `Float` | Parallel Net3 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| pnet4Amt | `Float` | Parallel Net4 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| pnet5Amt | `Float` | Parallel Net5 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| pnet6Amt | `Float` | Parallel Net6 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| pnet7Amt | `Float` | Parallel Net7 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| pnet8Amt | `Float` | Parallel Net8 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| pnet9Amt | `Float` | Parallel Net9 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| postitSequenceNumber | `Float` | Postit Sequence Number |
| postitYN | `String` | Postit YN |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printerQueueName | `String` | Printer Queue Name |
| profileTypeCode | `String` | Profile Type Code |
| promotionalText1 | `String` | Text returned by the credit card company |
| promotionalText2 | `String` | Text returned by the credit card company |
| property | `String` | Code to uniquely identify the Property |
| propertyBillPrefix | `String` | Property Bill Prefix |
| propertyTaxNumber | `String` | Property Tax Number |
| ptax1Amt | `Float` | Parallel Total tax1 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| ptax10Amt | `Float` | Parallel Total tax10 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| ptax11Amt | `Float` | Parallel Total tax11 amount extension to the existing ptax amounts. |
| ptax12Amt | `Float` | Parallel Total tax12 amount extension to the existing ptax amounts. |
| ptax13Amt | `Float` | Parallel Total tax13 amount extension to the existing ptax amounts. |
| ptax14Amt | `Float` | Parallel Total tax14 amount extension to the existing ptax amounts. |
| ptax15Amt | `Float` | Parallel Total tax15 amount extension to the existing ptax amounts. |
| ptax16Amt | `Float` | Parallel Total tax16 amount extension to the existing ptax amounts. |
| ptax17Amt | `Float` | Parallel Total tax17 amount extension to the existing ptax amounts. |
| ptax18Amt | `Float` | Parallel Total tax18 amount extension to the existing ptax amounts. |
| ptax19Amt | `Float` | Parallel Total tax19 amount extension to the existing ptax amounts. |
| ptax2Amt | `Float` | Parallel Total tax2 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| ptax20Amt | `Float` | Parallel Total tax20 amount extension to the existing ptax amounts. |
| ptax3Amt | `Float` | Parallel Total tax3 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| ptax4Amt | `Float` | Parallel Total tax4 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| ptax5Amt | `Float` | Parallel Total tax5 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| ptax6Amt | `Float` | Parallel Total tax6 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| ptax7Amt | `Float` | Parallel Total tax7 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| ptax8Amt | `Float` | Parallel Total tax8 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| ptax9Amt | `Float` | Parallel Total tax9 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| ptotNonrevNonTaxable | `Float` | Parallel total non revenue amount that is not taxable. |
| ptotNonrevTaxable | `Float` | Parallel total non revenue amount that is taxable. |
| ptotRevNonTaxable | `Float` | Parallel total revenue amount that is not taxable. |
| ptotRevTaxable | `Float` | Parallel total revenue amount that is taxable. |
| realPerpetualAmount | `Float` | Real perpetual amount at the time of generating the bill. |
| reservationNameId | `Float` | Resv Name ID |
| resortCity | `String` | City of the hotel at the time of bill generation. |
| resortCountry | `String` | Country of the hotel at the time of bill generation. |
| resortFullAddress | `String` | Property Full Address |
| resortZipcodeCode | `String` | Zipcode of the hotel at the time of bill generation. |
| revisionNo | `Float` | Revision Number |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomNumber | `String` | Room Number |
| seqNumber | `Float` | Sequence No |
| signature | `String` | Signature |
| signatureKeyVersion | `String` | Signature Key Version |
| softwareVersion | `String` | OPERA software version at the time of bill generation. |
| tax1RateType | `String` | Tax Rate Type 1 of the bill for which Tax Code 1 is attached as one of the taxes. |
| tax2RateType | `String` | Tax Rate Type 2 of the bill for which Tax Code 2 is attached as one of the taxes. |
| taxAmount1 | `Float` | Tax Amount 1 |
| taxAmount10 | `Float` | Tax Amount 10 |
| taxAmount11 | `Float` | Tax Amount 11 |
| taxAmount12 | `Float` | Tax Amount 12 |
| taxAmount13 | `Float` | Tax Amount 13 |
| taxAmount14 | `Float` | Tax Amount 14 |
| taxAmount15 | `Float` | Tax Amount 15 |
| taxAmount16 | `Float` | Tax Amount 16 |
| taxAmount17 | `Float` | Tax Amount 17 |
| taxAmount18 | `Float` | Tax Amount 18 |
| taxAmount19 | `Float` | Tax Amount 19 |
| taxAmount2 | `Float` | Tax Amount 2 |
| taxAmount20 | `Float` | Tax Amount 20 |
| taxAmount3 | `Float` | Tax Amount 3 |
| taxAmount4 | `Float` | Tax Amount 4 |
| taxAmount5 | `Float` | Tax Amount 5 |
| taxAmount6 | `Float` | Tax Amount 6 |
| taxAmount7 | `Float` | Tax Amount 7 |
| taxAmount8 | `Float` | Tax Amount 8 |
| taxAmount9 | `Float` | Tax Amount 9 |
| taxCode1 | `String` | Tax Code 1 |
| taxCode10 | `String` | Tax Code 10 |
| taxCode11 | `String` | Tax Code 11 |
| taxCode12 | `String` | Tax Code 12 |
| taxCode13 | `String` | Tax Code 13 |
| taxCode14 | `String` | Tax Code 14 |
| taxCode15 | `String` | Tax Code 15 |
| taxCode16 | `String` | Tax Code 16 |
| taxCode17 | `String` | Tax Code 17 |
| taxCode18 | `String` | Tax Code 18 |
| taxCode19 | `String` | Tax Code 19 |
| taxCode2 | `String` | Tax Code 2 |
| taxCode20 | `String` | Tax Code 20 |
| taxCode3 | `String` | Tax Code 3 |
| taxCode4 | `String` | Tax Code 4 |
| taxCode5 | `String` | Tax Code 5 |
| taxCode6 | `String` | Tax Code 6 |
| taxCode7 | `String` | Tax Code 7 |
| taxCode8 | `String` | Tax Code 8 |
| taxCode9 | `String` | Tax Code 9 |
| taxCodeDesc1 | `String` | Tax Code Description 1 |
| taxCodeDesc10 | `String` | Tax Code Description 10 |
| taxCodeDesc11 | `String` | Tax Code Description 11 |
| taxCodeDesc12 | `String` | Tax Code Description 12 |
| taxCodeDesc13 | `String` | Tax Code Description 13 |
| taxCodeDesc14 | `String` | Tax Code Description 14 |
| taxCodeDesc15 | `String` | Tax Code Description 15 |
| taxCodeDesc16 | `String` | Tax Code Description 16 |
| taxCodeDesc17 | `String` | Tax Code Description 17 |
| taxCodeDesc18 | `String` | Tax Code Description 18 |
| taxCodeDesc19 | `String` | Tax Code Description 19 |
| taxCodeDesc2 | `String` | Tax Code Description 2 |
| taxCodeDesc20 | `String` | Tax Code Description 20 |
| taxCodeDesc3 | `String` | Tax Code Description 3 |
| taxCodeDesc4 | `String` | Tax Code Description 4 |
| taxCodeDesc5 | `String` | Tax Code Description 5 |
| taxCodeDesc6 | `String` | Tax Code Description 6 |
| taxCodeDesc7 | `String` | Tax Code Description 7 |
| taxCodeDesc8 | `String` | Tax Code Description 8 |
| taxCodeDesc9 | `String` | Tax Code Description 9 |
| taxId | `String` | Tax ID |
| taxRate1 | `Float` | Tax Rate 1 amount of the bill for which Tax Code 1 is attached as one of the taxes. |
| taxRate10 | `Float` | Tax Rate 10 amount of the bill for which Tax Code 10  is attached as one of the taxes. |
| taxRate11 | `Float` | Tax Rate 11 amount of the bill for which Tax Code 11  is attached as one of the taxes. |
| taxRate12 | `Float` | Tax Rate 12 amount of the bill for which Tax Code 12 is attached as one of the taxes. |
| taxRate13 | `Float` | Tax Rate 13 amount of the bill for which Tax Code 13 is attached as one of the taxes. |
| taxRate14 | `Float` | Tax Rate 14 amount of the bill for which Tax Code 14 is attached as one of the taxes. |
| taxRate15 | `Float` | Tax Rate 15 amount of the bill for which Tax Code 15 is attached as one of the taxes. |
| taxRate16 | `Float` | Tax Rate 16 amount of the bill for which Tax Code 16 is attached as one of the taxes. |
| taxRate17 | `Float` | Tax Rate 17 amount of the bill for which Tax Code 17 is attached as one of the taxes. |
| taxRate18 | `Float` | Tax Rate 18 amount of the bill for which Tax Code 18 is attached as one of the taxes. |
| taxRate19 | `Float` | Tax Rate 19 amount of the bill for which Tax Code 19 is attached as one of the taxes. |
| taxRate2 | `Float` | Tax Rate 2 amount of the bill for which Tax Code 2 is attached as one of the taxes. |
| taxRate20 | `Float` | Tax Rate 20 amount of the bill for which Tax Code 20 is attached as one of the taxes. |
| taxRate3 | `Float` | Tax Rate 3 amount of the bill for which Tax Code 3 is attached as one of the taxes. |
| taxRate4 | `Float` | Tax Rate 4 amount of the bill for which Tax Code 4 is attached as one of the taxes. |
| taxRate5 | `Float` | Tax Rate 5 amount of the bill for which Tax Code 5 is attached as one of the taxes. |
| taxRate6 | `Float` | Tax Rate 6 amount of the bill for which Tax Code 6 is attached as one of the taxes. |
| taxRate7 | `Float` | Tax Rate 7 amount of the bill for which Tax Code 7 is attached as one of the taxes. |
| taxRate8 | `Float` | Tax Rate 8 amount of the bill for which Tax Code 8 is attached as one of the taxes. |
| taxRate9 | `Float` | Tax Rate 9 amount of the bill for which Tax Code 9 is attached as one of the taxes. |
| tax10RateType | `String` | Tax Rate Type 10 of the bill for which Tax Code 10 is attached as one of the taxes. |
| tax11RateType | `String` | Tax Rate Type 11 of the bill for which Tax Code 11 is attached as one of the taxes. |
| tax12RateType | `String` | Tax Rate Type 12 of the bill for which Tax Code 12 is attached as one of the taxes. |
| tax13RateType | `String` | Tax Rate Type 13 of the bill for which Tax Code 13 is attached as one of the taxes. |
| tax14RateType | `String` | Tax Rate Type 14 of the bill for which Tax Code 14 is attached as one of the taxes. |
| tax15RateType | `String` | Tax Rate Type 15 of the bill for which Tax Code 15 is attached as one of the taxes. |
| tax16RateType | `String` | Tax Rate Type 16 of the bill for which Tax Code 16 is attached as one of the taxes. |
| tax17RateType | `String` | Tax Rate Type 17 of the bill for which Tax Code 17 is attached as one of the taxes. |
| tax18RateType | `String` | Tax Rate Type 18 of the bill for which Tax Code 18 is attached as one of the taxes. |
| tax19RateType | `String` | Tax Rate Type 19 of the bill for which Tax Code 19 is attached as one of the taxes. |
| tax20RateType | `String` | Tax Rate Type 20 of the bill for which Tax Code 20 is attached as one of the taxes. |
| tax3RateType | `String` | Tax Rate Type 3 of the bill for which Tax Code 3 is attached as one of the taxes. |
| tax4RateType | `String` | Tax Rate Type 4 of the bill for which Tax Code 4 is attached as one of the taxes. |
| tax5RateType | `String` | Tax Rate Type 5 of the bill for which Tax Code 5 is attached as one of the taxes. |
| tax6RateType | `String` | Tax Rate Type 6 of the bill for which Tax Code 6 is attached as one of the taxes. |
| tax7RateType | `String` | Tax Rate Type 7 of the bill for which Tax Code 7 is attached as one of the taxes. |
| tax8RateType | `String` | Tax Rate Type 8 of the bill for which Tax Code 8 is attached as one of the taxes. |
| tax9RateType | `String` | Tax Rate Type 9 of the bill for which Tax Code 9 is attached as one of the taxes. |
| terminal | `String` | Terminal |
| totalGrossAmount | `Float` | Total Gross Amount |
| totalNetAmount | `Float` | Total Net Amount |
| totalNonRevenueNonTaxableAmount | `Float` | Total non revenue amount that is non taxable. |
| totalNonRevenueTaxableAmount | `Float` | Total non revenue amount that is not taxable. |
| totalNonTaxableAmount | `Float` | Total non taxable amount. |
| totalNonTaxableRevenue | `Float` | Total revenue amount that is non taxable. |
| totalPaidOuts | `Float` | Total paid outs. |
| totalTax | `Float` | Total Tax |
| totalTaxableRevenue | `Float` | Total revenue amount that is taxable. |
| transactLastSignatureHash | `String` | Last Signature for Transaction Totals. |
| transactSignatureHash | `String` | Signature hash for Transaction Totals. |
| transactSignatureKeyVersion | `String` | Signature key version for Transaction Totals. |
| transactionSignature | `String` | Transaction Signature Value. |
| trxServiceType | `String` | Transaction Service Type |
| uDFC01 | `String` | UDFC01 |
| uDFC02 | `String` | UDFC02 |
| uDFC03 | `String` | UDFC03 |
| uDFC04 | `String` | UDFC04 |
| uDFC05 | `String` | UDFC05 |
| uDFC06 | `String` | UDFC06 |
| uDFC07 | `String` | UDFC07 |
| uDFC08 | `String` | UDFC08 |
| uDFC09 | `String` | UDFC09 |
| uDFC10 | `String` | UDFC10 |
| uDFC11 | `String` | UDFC11 |
| uDFC12 | `String` | UDFC12 |
| uDFC13 | `String` | UDFC13 |
| uDFC14 | `String` | UDFC14 |
| uDFC15 | `String` | UDFC15 |
| uDFC16 | `String` | UDFC16 |
| uDFC17 | `String` | UDFC17 |
| uDFC18 | `String` | UDFC18 |
| uDFC19 | `String` | UDFC19 |
| uDFC20 | `String` | UDFC20 |
| uDFC21 | `String` | UDFC21 |
| uDFC22 | `String` | UDFC22 |
| uDFC23 | `String` | UDFC23 |
| uDFC24 | `String` | UDFC24 |
| uDFC25 | `String` | UDFC25 |
| uDFC26 | `String` | UDFC26 |
| uDFC27 | `String` | UDFC27 |
| uDFC28 | `String` | UDFC28 |
| uDFC29 | `String` | UDFC29 |
| uDFC30 | `String` | UDFC30 |
| uDFC31 | `String` | UDFC31 |
| uDFC32 | `String` | UDFC32 |
| uDFC33 | `String` | UDFC33 |
| uDFC34 | `String` | UDFC34 |
| uDFC35 | `String` | UDFC35 |
| uDFC36 | `String` | UDFC36 |
| uDFC37 | `String` | UDFC37 |
| uDFC38 | `String` | UDFC38 |
| uDFC39 | `String` | UDFC39 |
| uDFC40 | `String` | UDFC40 |
| uDFD01 | `Date` | UDFD01 |
| uDFD02 | `Date` | UDFD02 |
| uDFD03 | `Date` | UDFD03 |
| uDFD04 | `Date` | UDFD04 |
| uDFD05 | `Date` | UDFD05 |
| uDFD06 | `Date` | UDFD06 |
| uDFD07 | `Date` | UDFD07 |
| uDFD08 | `Date` | UDFD08 |
| uDFD09 | `Date` | UDFD09 |
| uDFD10 | `Date` | UDFD10 |
| uDFD11 | `Date` | UDFD11 |
| uDFD12 | `Date` | UDFD12 |
| uDFD13 | `Date` | UDFD13 |
| uDFD14 | `Date` | UDFD14 |
| uDFD15 | `Date` | UDFD15 |
| uDFD16 | `Date` | UDFD16 |
| uDFD17 | `Date` | UDFD17 |
| uDFD18 | `Date` | UDFD18 |
| uDFD19 | `Date` | UDFD19 |
| uDFD20 | `Date` | UDFD20 |
| uDFN01 | `Float` | UDFN01 |
| uDFN02 | `Float` | UDFN02 |
| uDFN03 | `Float` | UDFN03 |
| uDFN04 | `Float` | UDFN04 |
| uDFN05 | `Float` | UDFN05 |
| uDFN06 | `Float` | UDFN06 |
| uDFN07 | `Float` | UDFN07 |
| uDFN08 | `Float` | UDFN08 |
| uDFN09 | `Float` | UDFN09 |
| uDFN10 | `Float` | UDFN10 |
| uDFN11 | `Float` | UDFN11 |
| uDFN12 | `Float` | UDFN12 |
| uDFN13 | `Float` | UDFN13 |
| uDFN14 | `Float` | UDFN14 |
| uDFN15 | `Float` | UDFN15 |
| uDFN16 | `Float` | UDFN16 |
| uDFN17 | `Float` | UDFN17 |
| uDFN18 | `Float` | UDFN18 |
| uDFN19 | `Float` | UDFN19 |
| uDFN20 | `Float` | UDFN20 |
| uDFN21 | `Float` | UDFN21 |
| uDFN22 | `Float` | UDFN22 |
| uDFN23 | `Float` | UDFN23 |
| uDFN24 | `Float` | UDFN24 |
| uDFN25 | `Float` | UDFN25 |
| uDFN26 | `Float` | UDFN26 |
| uDFN27 | `Float` | UDFN27 |
| uDFN28 | `Float` | UDFN28 |
| uDFN29 | `Float` | UDFN29 |
| uDFN30 | `Float` | UDFN30 |
| uDFN31 | `Float` | UDFN31 |
| uDFN32 | `Float` | UDFN32 |
| uDFN33 | `Float` | UDFN33 |
| uDFN34 | `Float` | UDFN34 |
| uDFN35 | `Float` | UDFN35 |
| uDFN36 | `Float` | UDFN36 |
| uDFN37 | `Float` | UDFN37 |
| uDFN38 | `Float` | UDFN38 |
| uDFN39 | `Float` | UDFN39 |
| uDFN40 | `Float` | UDFN40 |
| updTimestamp | `DateTime` | Timestamp to capture the exact order of updates. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| userID | `Float` | User ID |
| userName | `String` | The name of the user who created the record. |
| voidNumber | `Float` | Void Number |
| voidReason | `String` | This column will store the reason for voiding the folio. |
| workingDocId | `Float` | Working Doc ID |
| xnet1Amt | `Float` | Xnet1 Amount |
| xnet10Amt | `Float` | Xnet10 Amount |
| xnet11Amt | `Float` | Xnet11 Amount |
| xnet12Amt | `Float` | Xnet12 Amount |
| xnet13Amt | `Float` | Xnet13 Amount |
| xnet14Amt | `Float` | Xnet14 Amount |
| xnet15Amt | `Float` | Xnet15 Amount |
| xnet16Amt | `Float` | Xnet16 Amount |
| xnet17Amt | `Float` | Xnet17 Amount |
| xnet18Amt | `Float` | Xnet18 Amount |
| xnet19Amt | `Float` | Xnet19 Amount |
| xnet2Amt | `Float` | Xnet2 Amount |
| xnet20Amt | `Float` | Xnet20 Amount |
| xnet3Amt | `Float` | Xnet3 Amount |
| xnet4Amt | `Float` | Xnet4 Amount |
| xnet5Amt | `Float` | Xnet5 Amount |
| xnet6Amt | `Float` | Xnet6 Amount |
| xnet7Amt | `Float` | Xnet7 Amount |
| xnet8Amt | `Float` | Xnet8 Amount |
| xnet9Amt | `Float` | Xnet9 Amount |
| xtax1Amt | `Float` | Total tax1 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| xtax10Amt | `Float` | Total tax10 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| xtax11Amt | `Float` | Total tax11 amount extension to the existing xtax amounts. |
| xtax12Amt | `Float` | Total tax12 amount extension to the existing xtax amounts. |
| xtax13Amt | `Float` | Total tax13 amount extension to the existing xtax amounts. |
| xtax14Amt | `Float` | Total tax14 amount extension to the existing xtax amounts. |
| xtax15Amt | `Float` | Total tax15 amount extension to the existing xtax amounts. |
| xtax16Amt | `Float` | Total tax16 amount extension to the existing xtax amounts. |
| xtax17Amt | `Float` | Total tax17 amount extension to the existing xtax amounts. |
| xtax18Amt | `Float` | Total tax18 amount extension to the existing xtax amounts. |
| xtax19Amt | `Float` | Total tax19 amount extension to the existing xtax amounts. |
| xtax2Amt | `Float` | Total tax2 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| xtax20Amt | `Float` | Total tax20 amount extension to the existing xtax amounts. |
| xtax3Amt | `Float` | Total tax3 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| xtax4Amt | `Float` | Total tax4 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| xtax5Amt | `Float` | Total tax5 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| xtax6Amt | `Float` | Total tax6 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| xtax7Amt | `Float` | Total tax7 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| xtax8Amt | `Float` | Total tax8 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| xtax9Amt | `Float` | Total tax9 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsForeignCurrencyDetailsType

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

### FinancialTransactionDetailsInvoicePaymentDetailsType

| Field | Type | Description |
| --- | --- | --- |
| appliedAmount | `Float` | Amount Applied. you can apply one payment partially to one transactions and partially to another transaction. |
| businessDate | `Date` | Date on which the payment was applied. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cashierId | `Float` | Cashier ID |
| centralAppliedAmount | `Float` | Central Applied Amount |
| chainCode | `String` | Chain Code |
| consumptionTransactionNumber | `Float` | Consumption Transaction Number |
| consumptionTrx | `Float` | Transaction no for which you are applying to other transactions. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| invoicepaymentid | `Float` | Invoicepaymentid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentApplicationId | `Float` | Unique Sequence id for each payment applications. |
| paymentTransactionNumber | `Float` | Payment Transaction Number |
| paymentTrx | `Float` | Transaction no for which you want to pay for the other transactions. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsProfileAllInformationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| guestProfileID | `Float` | The primary key for this table. |
| aRNumber | `String` | Account number. |
| aRNumberCentral | `String` | Account Receivable No. of this profile. |
| aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountBillingContact | `String` | Billing contact person in company. |
| accountSource | `String` | Used in S&C Module. |
| accountType | `String` | Account Type of this Profile |
| accountTypeDescription | `String` | The description of this value. |
| accountsourceDesc | `String` | The description of this value. |
| actionCode | `String` | Mailing action codes. |
| activeYN | `String` | Profile is active or not. |
| address1 | `String` | The first line of street address. |
| address2 | `String` | The second line of street address. |
| address3 | `String` | The third line of street address. |
| address4 | `String` | The fourth line of street address. |
| addressId | `Float` | The primary key for this table. |
| addressLangCodeDesc | `String` | Description for each language code. |
| addressLanguageCode | `String` | Address Language Code |
| addressType | `String` | The type of address. |
| alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| allResorts | `String` | All Resorts |
| alternateEnvelopeGreeting | `String` | Field which stores the multibyte envelop greeting used in S&C |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Description for each language code. |
| alternateSalutation | `String` | Alternate Salutation |
| autoEnrollMemberYN | `String` | Auto-Enroll Member YN |
| availabilityOverride | `String` | Does profile have Availability Override Y/N |
| billingCode | `String` | The billing code for this name record. |
| billingInstruction | `String` | Billing Instruction |
| billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| birthCountry | `String` | Country of Birth |
| birthDate | `Date` | Date of Birth of the Individual Profiles. |
| birthDateStr | `String` | Stores the encrypted birth date. |
| birthPlace | `String` | Place of Birth |
| blMsg | `String` | Any Message for the Restricted profile. |
| businessSegment | `String` | Used in S&C Module. |
| businessSegmentDescription | `String` | The description of this value. |
| businessTitle | `String` | The business title for this individual. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| cRSNameid | `Float` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |
| ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| centralAccountType | `String` | Central Account Type |
| centralBusinessSegment | `String` | Central Business Segment |
| centralBusinessSegmentDescription | `String` | Central Business Segment Description |
| centralCorporateIDType | `String` | Central Corporate ID Type |
| centralDefaultKeyword | `String` | The keyword to search on. |
| centralGuestTitleCode | `String` | Central Guest Title Code |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralMailActionDescription | `String` | Central Mail Action Description |
| centralMailingActionCode | `String` | Central Mailing Action Code |
| centralPriority | `String` | Central Priority |
| centralStateCode | `String` | Central State Code |
| centralTerritory | `String` | Central Territory |
| centralVIPCode | `String` | Central VIP Code |
| centralVIPDescription | `String` | Central VIP Description |
| chainCode | `String` | Chain Code |
| city | `String` | The city for this address. |
| clientID | `String` | The unique key of this name stores IATA# Company # etc. |
| collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| combinedName | `String` | Combined Name |
| commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| comments | `String` | Not Used. |
| commissionCode | `String` | Commission Code for the Commission Percentage. |
| commissionCodes | `String` | Code for the commission for Travel Agent |
| commissionCurrencyId | `String` | Comm Curr ID |
| commissionid | `String` | Commission Code for the Commission Percentage. |
| communicationRole1 | `String` | Role in which this phone type belongs to. |
| communicationRole2 | `String` | Role in which this phone type belongs to. |
| communicationRole3 | `String` | Role in which this phone type belongs to. |
| communicationType1 | `String` | The type of this phone number. |
| communicationType2 | `String` | The type of this phone number. |
| communicationType3 | `String` | The type of this phone number. |
| communicationValue1 | `String` | The phone number for this record |
| communicationValue2 | `String` | The phone number for this record |
| communicationValue3 | `String` | The phone number for this record |
| companyAlternate | `String` | Extended Byte Company Name |
| companyGroupId | `String` | The company group or company group user ID in hierarchical format |
| companyNameId | `Float` | Not used. |
| competition | `String` | Competaion code . |
| competitionDesc | `String` | The description of this value. |
| contactYN | `String` | Used in S&C Module. |
| contractNo | `String` | Group Contract number. |
| contractRecvDate | `Date` | The date the group contract was received. |
| corpTypeDesc | `String` | Corp Type Description |
| corporateIDType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| country | `String` | Country name. |
| countryCode | `String` | Country . |
| createdByUser | `String` | The user that created the record |
| createdOnDate | `DateTime` | The date the record was created |
| creditRating | `String` | Credit rating. |
| currencyCode | `String` | Currency Code |
| currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| debtorName | `String` | Debtor Name |
| decimalPositions | `Float` | The number of digits after the decimal to allow for this currency. |
| defaultKeyword | `String` | The keyword to search on. |
| deletedFlag | `String` | Deleted Flag |
| department | `String` | Used in S&C Module. |
| deptId | `String` | Used in S&C Module. |
| description | `String` | Used in QMS Module |
| directBillBatchType | `String` | Direct Bill Batch Type |
| displayName | `String` | Display Name |
| downloadDate | `Date` | Date on which the record is downloaded to laptop. |
| downloadResort | `String` | REsort name which has downloaded on the laptop. |
| downloadSrep | `Float` | Owner of the record who downloaded on to laptop. |
| eInvLiableLastUpdated | `DateTime` | The date when the E-Invoice liable flag was updated for this profile. |
| eInvoiceLiableYn | `String` | Turkey Country requirement: Indicated if this profile e-Invoice liable. Folios generated for this profile will be directly sent to an external system. |
| email | `String` | The phone number for this record |
| emailYN | `String` | Email YN |
| envelopeGreeting | `String` | Field which stores the envelop greeting used in S&C |
| externalDisplayName | `String` | External Display Name |
| externalFirstName | `String` | The first name of an individual. |
| externalId | `String` | External ID used for V6 Interface stores the PMS guest number |
| externalName | `String` | The last name of the individual profile. |
| externalReferenceRequ | `String` | Not Used. |
| externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| fMembershipCardNumbers | `String` | Membership Card Number. |
| fMembershipClassDesc | `String` | Descripion of membership class |
| fMembershipClasses | `String` | F Membership Classes |
| fMembershipCodes | `String` | F Membership Codes |
| fMembershipDescriptions | `String` | F Membership Descriptions |
| fMembershipIds | `String` | Primary Key for this table. |
| fMembershipType | `String` | Type of the Membership. |
| fSubscriptionDb | `String` | The ID of the external Database. |
| fSubscriptionYn | `String` | The ID of the external Database. |
| faxNumber | `String` | The phone number for this record |
| firstName | `String` | The first name of an individual name. |
| firstNameAlternate | `String` | First Name Alternate |
| firstNameIncognito | `String` | The keyword to search on. |
| followOn | `String` | The follow on for this individual (I.E: III etc). |
| gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| gDSTransactionNo | `String` | Not used. |
| gender | `String` | Indicates gender of Individual profile. Either (M)ale or F(emale) |
| geographicRegion | `String` | Not used. |
| guestClassification | `String` | Not used. |
| guestCountry | `String` | Country name. |
| guestCurrencyCode | `String` | Currency code for the Commission payment. |
| guestLanguageCode | `String` | Description for each language code. |
| guestLastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| guestMiddleName | `String` | The middle name of this individual. |
| guestNameSuffix | `String` | Guest Name Suffix |
| guestPrivilegeYN | `String` | Guest Privilege YN |
| guestTitleCode | `String` | The title of the individual. |
| hasRequestedMailYN | `String` | Has Requested Mail YN |
| historyYN | `String` | Keep guest in history Y/N |
| holdCode | `String` | Hold code for the Commission handling purposes. |
| iataConsortia | `String` | Consortia for the IATA number. |
| idCountry | `String` | The country where ID was issued |
| idDate | `Date` | Issued date of Identification |
| idDocumentAttachId | `Float` | This will store the value of LINKED_ATTACHMENTS.ATTACH_ID (Which maps to the physical table WORK_ORDERS.WO_NUMBER) |
| idPlace | `String` | The place where ID was issued |
| idType | `String` | Identification Type. Eg Passport Driving License etc |
| immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| inactiveDate | `DateTime` | The date the record was marked as inactive |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReason | `String` | Reason why record was inactivated. |
| inactiveReasonDescription | `String` | The description of this value. |
| includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| indexName | `String` | Index Name |
| industryCode | `String` | The Industry this profile belongs to. Used only for the Non-Individual Profiles. |
| industryDesc | `String` | The description of this value. |
| influence | `String` | Used in S&C Module. |
| influenceDesc | `String` | The description of this value. |
| interest | `String` | Interest Code. |
| internalBillYn | `String` | Indicates that this profile should be generating an internal bill instead of a regular bill during settlement. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Primary language used for the profile. |
| laptopChange | `Float` | Code to synchronize to Laptop values are 012. |
| lastGroup | `String` | Last Group |
| lastNameAlternate | `String` | Last Name Alternate |
| lastNameIncognito | `String` | The keyword to search on. |
| lastRate | `Float` | Last Rate |
| lastRateCode | `String` | Last Rate Code |
| lastRoom | `String` | The room that is booked for this reservation leg. |
| lastRoomProperty | `String` | Last Room Property |
| lastSource | `String` | Last Source |
| lastStay | `Date` | This contains the truncated component of end_date (i.e without timecomponent) |
| lastUpdatedResort | `String` | Last property that updated this record. |
| legalCompany | `String` | The legal company name for this company. |
| letterGreeting | `String` | Used in S&C Module. |
| mailActionDescription | `String` | The description of this value. |
| mailList | `String` | This indicates whether the mailing list must be sent to the guest. |
| mailType | `String` | The type of mail this user should be sent. |
| mailingActionCode | `String` | Mailing action codes. |
| marketResearchYN | `String` | Market Research YN |
| masterAccountYn | `String` | Is this account a master account (Y/N)? |
| nameTaxType | `String` | Not used. |
| nameType | `String` | The type of Profile. |
| nameTypeDescription | `String` | The description of this value. |
| name2 | `String` | Not Used. |
| name3 | `String` | Not used. |
| nationality | `String` | Nationality |
| nationalityCode | `String` | Nationality of the individual. |
| negotiatedRateCodes | `String` | The rate code for which this record applies. |
| nextStay | `Date` | This is a begin_date  with no  time component. |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| phone | `String` | The phone number for this record |
| phoneWeb | `String` | The phone number for this record |
| phoneYN | `String` | Phone YN |
| postalCode | `String` | The postal code of this address. |
| postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| preferredRoomNo | `String` | Preferred Room Number |
| primaryAddressId | `Float` | Not used. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryNameId | `Float` | Not Used. |
| primaryOwner | `String` | Primary Owner |
| primaryOwnerCode | `String` | Primary Owner Code |
| primaryPhoneId | `Float` | Not used. |
| priority | `String` | Priority of the account |
| priorityDesc | `String` | The description of this value. |
| privacyFlagYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| productInterest | `String` | Preference Code. Part of the Primary Key. |
| profession | `String` | The profession of the Individual |
| profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| profileId | `Float` | The primary key for this table. |
| profileType | `String` | The type of Profile. |
| propertyRegistered | `String` | Resort for which Job is registered. |
| protected | `String` | Protected |
| psuedoProfileYn | `String` | Psuedo Profile Y/N |
| rateStructure | `String` | The default rate structure for this name. |
| region | `String` | The region for this name. |
| regionid | `String` | The region for this name. |
| repAccountTypeDescription | `String` | Reporting Account Type Description |
| repAccountsource | `String` | Reporting Accountsource |
| repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| repCompetitionCode | `String` | Reporting Competition Code |
| repCompetitionDescription | `String` | Reporting Competition Desc |
| repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| repIndustryCode | `String` | Reporting Industry Code |
| repIndustryDescription | `String` | Reporting Industry Desc |
| repInfluence | `String` | Reporting Influence |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repNameType | `String` | Reporting Name Type |
| repNameTypeDescription | `String` | Reporting Name Type Description |
| repNationalityCode | `String` | Rep Nationality Code |
| repNationalityDescription | `String` | Rep Nationality Description |
| repPriorityDescription | `String` | Reporting Priority Desc |
| repRoomsPotential | `String` | Reporting Rooms Potential |
| repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| repScope | `String` | Reporting Scope |
| repScopeCity | `String` | Reporting Scope City |
| repScopeCityDescription | `String` | Reporting Scope City Desc |
| repScopeDescription | `String` | Reporting Scope Desc |
| repStateDescription | `String` | Reporting State Desc |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTerritoryDescription | `String` | Reporting Territory Desc |
| repTitleName | `String` | Reporting Title Name |
| repeatGuestId | `String` | The primary membership # for this guest. |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| requestType | `String` | This column store the Name of the Company Profiles. |
| restricted | `String` | Normal Restricted and Cash Only informations are stored in this column. |
| restrictedRule | `String` | The description of this value. |
| resvContact | `String` | Reservation Contact person. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomsPotential | `String` | Potential no of rooms per year for a account |
| roomsPotentialDesc | `String` | The description of this value. |
| sMSYN | `String` | Use this alert to text a notification. |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope of the account |
| scopeCity | `String` | Scope City |
| scopeCityDesc | `String` | The description of this value. |
| scopeDesc | `String` | The description of this value. |
| searchName | `String` | The Uppercase value of Last or Company. |
| searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| sfirst | `String` | Uppercase value of First Name. |
| soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| srepCode | `String` | Used in QMS Module |
| state | `String` | The state of this address. |
| stateCode | `String` | State Code |
| stateDescription | `String` | Description of the state. |
| summRefCc | `String` | Summary Reference Currency for the Folio Generation. |
| summRefCurrencyId | `String` | Summary Reference Currency for the Folio Generation. |
| superSearchIndexText | `String` | Used in Oracle Text Index. |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| taxCategory | `String` | Tax Category |
| taxExemptStatus | `String` | Not used. |
| taxID1 | `String` | The tax id of this name.  Usually issued by a government agency.  Used by 1099 printing. |
| taxID2 | `String` | Tax No |
| taxOffice | `String` | Tax Office Name |
| taxType | `String` | Tax Type |
| territory | `String` | TERRITORY of  a account |
| territoryDesc | `String` | The description of this value. |
| thirdPartyYN | `String` | Third Party YN |
| titleAlternate | `String` | Title Alternate |
| titleName | `String` | The description of this value. |
| titleSuffix | `Float` | Stores the suffix value of the selected title code.  This will be used for Processing to External System. |
| totalStay | `Float` | Sum of total number of stays on stay records for the time period. |
| tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| traceCode | `String` | Code to Trace a record for all Triggered actions. |
| tracecodeDesc | `String` | Description |
| typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| uDFC01 | `String` | User defined character field. |
| uDFC02 | `String` | User defined character field. |
| uDFC03 | `String` | User defined character field. |
| uDFC04 | `String` | User defined character field. |
| uDFC05 | `String` | User defined character field. |
| uDFC06 | `String` | User defined character field. |
| uDFC07 | `String` | User defined character field. |
| uDFC08 | `String` | User defined character field. |
| uDFC09 | `String` | User defined character field. |
| uDFC10 | `String` | User defined character field. |
| uDFC11 | `String` | User defined character field. |
| uDFC12 | `String` | User defined character field. |
| uDFC13 | `String` | User defined character field. |
| uDFC14 | `String` | User defined character field. |
| uDFC15 | `String` | User defined character field. |
| uDFC16 | `String` | User defined character field. |
| uDFC17 | `String` | User defined character field. |
| uDFC18 | `String` | User defined character field. |
| uDFC19 | `String` | User defined character field. |
| uDFC20 | `String` | User defined character field. |
| uDFC21 | `String` | User defined character field. |
| uDFC22 | `String` | User defined character field. |
| uDFC23 | `String` | User defined character field. |
| uDFC24 | `String` | User defined character field. |
| uDFC25 | `String` | User defined character field. |
| uDFC26 | `String` | User defined character field. |
| uDFC27 | `String` | User defined character field. |
| uDFC28 | `String` | User defined character field. |
| uDFC29 | `String` | User defined character field. |
| uDFC30 | `String` | User defined character field. |
| uDFC31 | `String` | User defined character field. |
| uDFC32 | `String` | User defined character field. |
| uDFC33 | `String` | User defined character field. |
| uDFC34 | `String` | User defined character field. |
| uDFC35 | `String` | User defined character field. |
| uDFC36 | `String` | User defined character field. |
| uDFC37 | `String` | User defined character field. |
| uDFC38 | `String` | User defined character field. |
| uDFC39 | `String` | User defined character field. |
| uDFC40 | `String` | User defined character field. |
| uDFD01 | `Date` | User defined date field. |
| uDFD02 | `Date` | User defined date field. |
| uDFD03 | `Date` | User defined date field. |
| uDFD04 | `Date` | User defined date field. |
| uDFD05 | `Date` | User defined date field. |
| uDFD06 | `Date` | User defined date field. |
| uDFD07 | `Date` | User defined date field. |
| uDFD08 | `Date` | User defined date field. |
| uDFD09 | `Date` | User defined date field. |
| uDFD10 | `Date` | User defined date field. |
| uDFD11 | `Date` | User defined date field. |
| uDFD12 | `Date` | User defined date field. |
| uDFD13 | `Date` | User defined date field. |
| uDFD14 | `Date` | User defined date field. |
| uDFD15 | `Date` | User defined date field. |
| uDFD16 | `Date` | User defined date field. |
| uDFD17 | `Date` | User defined date field. |
| uDFD18 | `Date` | User defined date field. |
| uDFD19 | `Date` | User defined date field. |
| uDFD20 | `Date` | User defined date field. |
| uDFN01 | `Float` | User defined number field. |
| uDFN02 | `Float` | User defined number field. |
| uDFN03 | `Float` | User defined number field. |
| uDFN04 | `Float` | User defined number field. |
| uDFN05 | `Float` | User defined number field. |
| uDFN06 | `Float` | User defined number field. |
| uDFN07 | `Float` | User defined number field. |
| uDFN08 | `Float` | User defined number field. |
| uDFN09 | `Float` | User defined number field. |
| uDFN10 | `Float` | User defined number field. |
| uDFN11 | `Float` | User defined number field. |
| uDFN12 | `Float` | User defined number field. |
| uDFN13 | `Float` | User defined number field. |
| uDFN14 | `Float` | User defined number field. |
| uDFN15 | `Float` | User defined number field. |
| uDFN16 | `Float` | User defined number field. |
| uDFN17 | `Float` | User defined number field. |
| uDFN18 | `Float` | User defined number field. |
| uDFN19 | `Float` | User defined number field. |
| uDFN20 | `Float` | User defined number field. |
| uDFN21 | `Float` | User defined number field. |
| uDFN22 | `Float` | User defined number field. |
| uDFN23 | `Float` | User defined number field. |
| uDFN24 | `Float` | User defined number field. |
| uDFN25 | `Float` | User defined number field. |
| uDFN26 | `Float` | User defined number field. |
| uDFN27 | `Float` | User defined number field. |
| uDFN28 | `Float` | User defined number field. |
| uDFN29 | `Float` | User defined number field. |
| uDFN30 | `Float` | User defined number field. |
| uDFN31 | `Float` | User defined number field. |
| uDFN32 | `Float` | User defined number field. |
| uDFN33 | `Float` | User defined number field. |
| uDFN34 | `Float` | User defined number field. |
| uDFN35 | `Float` | User defined number field. |
| uDFN36 | `Float` | User defined number field. |
| uDFN37 | `Float` | User defined number field. |
| uDFN38 | `Float` | User defined number field. |
| uDFN39 | `Float` | User defined number field. |
| uDFN40 | `Float` | User defined number field. |
| updateDate | `DateTime` | The date the record was modified |
| updateFaxDate | `Date` | The last date this record's fax # was updated. |
| updateUser | `String` | The user that modified the record |
| uploadDate | `Date` | Date on which the record is uploaded to laptop. |
| vIPCode | `String` | VIP Status of the Individual. |
| vIPDescription | `String` | The description of this value. |
| vendorId | `Float` | The Oracle Financials vendor id for this record.  Used with the Oracle Financials A/P interface. |
| vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| vipAuthorization | `String` | Not Used. |
| visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| xdisplayName | `String` | Xdisplay Name |
| xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsRateCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aSBRateCycle | `String` | Not null value in this column indicates that this is ASB Rate. This column also specifies the cycle of ASB rate. MC=Fixed Calendar Month Cycle WC=Fixed Calendar Week Cycle MF= Floating Monthly Cycle WF=Floating Weekly Cycle. |
| addition | `String` | Amount to be added to the base rate when shown on rate query |
| advBaseRateCode | `String` | With Advanced Base Rate Parameter ON this field stores the rate code on which this rate schedule is dynamically based on. |
| advBaseRounding | `String` | Indicates how rounding of advanced dynamic rate calculation is performed.[U]p  [D]own [N]one [C] -Up - keep decimal [F] -Down - keep decimal. |
| advanceBaseCompareYN | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BAR rate code. |
| advanceDailyBaseYN | `String` | Indicates if this rate code is an Advanced Daily Base Rate. |
| advanceDailyRateYN | `String` | Indicates if this rate code is an Advanced Daily Rate. |
| alternateRateCode | `String` | Alternative rate code if current rate is not available |
| availabilityUpdateYn | `String` | Flag to indicate whether to send Rate code to AVH or not. |
| backToBackYN | `String` | Back To Back YN |
| baseAmount | `Float` | Base Amount |
| baseFltPct | `String` | Flat or Percentage of the Base Rate |
| baseRateCode | `String` | Base Rate Code |
| baseRounding | `String` | Indicates if rounding of rate is required |
| baseType | `String` | Indicating a rate type such as flat rate or percentage rate. Possible values are: FLAT DIFFERENTIAL and NULL. |
| bbarBaseAmount | `Float` | This column use to store Percentage or Amount difference between BAR Rate code and this Rate Code. |
| bbarBaseFltPct | `String` | This flag column identify that amount column represent Flat or Percentage value. |
| bbarBaseRounding | `String` | This column identify the rounding formula for the BBAR Rate calculation. |
| bbarBasedYn | `String` | This column will identify that Rate Code is Best BAR based rate code or not. Possible values are Y/N. |
| bbarCompareYn | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BBAR rate code. |
| bbarYn | `String` | Bbar Y/N |
| blockName | `String` | Block Name |
| breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| breakfastPrice | `Float` | Breakfast Price |
| businessDate | `Date` | Business Date |
| bypassHurdleYn | `String` | In case of ORMS when this flag is Y system ignore this rate code from Hurdle Check. |
| bypassRankCheckYn | `String` | Indicates that this rate code will not go through rank validations if value is 'Y'. |
| cBaseAmount | `Float` | Central Base Amount |
| cBbarBaseAmount | `Float` | Central Bbar Base Amount |
| cBreakfastPrice | `Float` | Central Bfst Price |
| cDbaseAmount | `Float` | Central Dbase Amount |
| cDiscountRateAmount | `Float` | Central Discount Rate Amount |
| cDoubleRoomSupplementPrice | `Float` | Central Dbl Rm Supplement Price |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRateFloor | `Float` | Central Rate Floor |
| cRateLevel | `Float` | Central Rate Level |
| cRodBaseAmount | `Float` | Central Rod Base Amount |
| cRoomAssignmentValue | `Float` | Central Room Assignment Value |
| catPackageCode | `String` | Stores the catering package code linked to this rate code. |
| cateringPackageYN | `String` | Specifies if a catering package is linked to this rate code. |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| centralRateBucket | `String` | Central Rate Bucket |
| centralRateBucketDescription | `String` | Central Rate Bucket Description |
| centralRateCategory | `String` | Central Rate Category |
| centralRateCategoryDescription | `String` | Central Rate Category Description |
| centralRateClass | `String` | Central Rate Class |
| centralRateClassDescription | `String` | Central Rate Class Description |
| centralRoomType | `String` | Central Room Type |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| centralSourceCode | `String` | Central Source Code |
| centralSourceDescription | `String` | Central Source Description |
| centralSourceGroupCode | `String` | Central Source Group Code |
| centralSourceGroupDescription | `String` | Central Source Group Description |
| changeState | `String` | Indicates the state of chaange of the rate code with values null=enabled D=disabled P=changes pending of approval |
| commissionPercent | `Float` | This field is used to populate rate code commission percentage for informational purposes for GDS and ORS reservation agents |
| commissionCode | `String` | Commission Code |
| commissionYn | `String` | Are commissions allowed for this rate code? Y/N |
| commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| commissionableYn | `String` | Commissionable Y/N |
| complimentaryYN | `String` | Complimentary YN |
| currCodeDecimalPos | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating the decimal position specific to the received the currency code. |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyRatesYn | `String` | Daily Rates Y/N |
| dayUseYN | `String` | Day use reservation Y/N. |
| daysWhenClosedToArrival | `String` | Days the rate restriction is not available for arrival |
| dbaseAmount | `Float` | Indicates either Flat amount or Percentage increase or decrease from the dynamic base rate. |
| dbaseCompareYn | `String` | This flag identify that while checking availability calculated based amount should be compared to rate detail of rate code or not. |
| dbaseFltPct | `String` | Flat or Percentage of the dynamic base rate code. |
| dbaseRateCode | `String` | The rate code on which this rate shedule is dynamically based on. |
| dbaseRounding | `String` | Indicates if rounding of dynamic rate calculation is required. |
| dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| defaultToHighestBarYn | `String` | For BAR dependent Rate Code this flag indicates that when all BAR Rates are closed the Rate Amount should be calculated based on the highest BAR Rate Amount instead of based on its own Rate Detail. |
| deletedFlag | `String` | Deleted Flag |
| depositMaturityPreference | `String` | Stores the Deposit maturity preference. |
| deptCode | `String` | Department code for the transaction. |
| discountRateAmount | `Float` | Discount rate amount value. |
| discountRatePercentageYn | `String` | Indicates if discount rate amount is a percentage value. |
| discountYN | `String` | Discount Flag. |
| displaySequence | `Float` | Display Sequence |
| displaySet | `String` | Display Set |
| distributeYn | `String` | Indicates if the profile should be distributed to the external database. |
| doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| endDate | `Date` | End Date |
| eventProperty | `String` | Indicates if the value set for the specific property. |
| exchangeType | `String` | Exchange Type |
| externallyControlledYN | `String` | Externally Controlled YN |
| extraPersonChargeBegins | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating at person level the extra charge begins. |
| fitDiscountLevel | `Float` | Fit Discount Level. |
| fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| flatYN | `String` | Flat YN |
| folioText | `String` | Text displayed on the Folio |
| frequentFlyerYN | `String` | Frequent Flyer YN |
| gDSAllowedYN | `String` | Is this rate code available for GDS |
| groupCode | `String` | Group Code |
| highlightRateAmountYn | `String` | To highlight on the rate query |
| houseUseYN | `String` | House-Use YN |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalLocationId | `String` | Location ID |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| longInfo | `String` | Long Info |
| loyaltyProgramYN | `String` | Flag to indicate if this is a loyalty program |
| mandateResvProfiles | `String` | Indicates mandatory reservation profiles. This is used to force entry of profiles on the reservation header if this rate is picked. |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketGroupCode | `String` | Market Group Code |
| marketGroupDescription | `String` | Market Group Description |
| marshaRateProgram | `String` | Contains the rate program information from the MARSHA interface. |
| maximumDaysAdvanceBooking | `Float` | Maximum Days Advance Booking |
| maximumLengthOfStay | `Float` | Maximum Length of Stay |
| maximumOccupancy | `Float` | Maximum Occupancy |
| mfnUploadYn | `String` | Flag used to determine if the rate code is to be sent to MyFidelio.net if the rate is being received from a V6 V7 V8 or OPMS on a lower version on which flag used to determine if the rate code is to be sent to MyFidelio.net does not exist on the rate header. |
| minimumDaysAdvanceBooking | `Float` | Minimum Days Advance Booking |
| minimumOccupancy | `Float` | Minimum Occupancy |
| mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| multiplication | `String` | Amount to be multiplied to the base rate when shown on rate query |
| myFidelioUploadYN | `String` | MyFidelio Upload YN |
| negotiatedYN | `String` | Property is negotiated of search criteria or not. |
| occupancyBasedYn | `String` | Indicates if the rate code is occupancy based. |
| occupancyLevel | `Float` | Indicates the occupancy level for hurdle evaluation. |
| operatorType | `String` | The operator type to use during the calculation of base rates. (ADD_TO SUBTRACT) |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalRateCode | `String` | Original Rate Code |
| orsSellSequence | `Float` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| overridePackageYn | `String` | Indicates if we need to override package for hurdle evaluation. |
| ownerRateYN | `String` | Indicates Owners Rate Code. This is used to perform rolling noshow. |
| packageTransactionCode | `String` | Package Transaction Code |
| packageTransactionCodeWeekend | `String` | Package Transaction Code Weekend |
| packageTransactionTaxInclYN | `String` | Wrapper transaction code tax inclusive Y/N |
| packageTransactionTaxIncludedYN | `String` | Transaction code is inclusive of tax Y/N |
| packageTransactionWkTaxInclYN | `String` | Wrapper transaction code tax inclusive for weekend days Y/N |
| packageYN | `String` | Package YN |
| packages | `String` | Packages |
| pendingApprovalYn | `String` | Indicates whether the rate code is pending for approval or not |
| postingRhythm | `String` | Posting Rhythm |
| postingRhythmNights | `Float` | Number of nights for posting rhythm. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printRateYn | `String` | Print Rate Y/N |
| privilegedRestrictionYn | `String` | Indicates if restriction for rate is privileged or not. |
| privilegedYn | `String` | Indicates if rate is privileged or not. |
| profitTransactionCode | `String` | Profit Transaction Code |
| property | `String` | Code to uniquely identify the Property |
| propertyName | `String` | Property Name |
| rankAdjustmentFactor | `Float` | Any number between -10 and +10. This adjustment factor will be applied to the daily ranking value of table RESORT_DAY_TYPE_DATES for the stay date to determine the Rate code rank value. |
| rankValue | `Float` | Rank Value |
| rateBucket | `String` | Yield rate bucket |
| rateBucketDescription | `String` | Rate Bucket Description |
| rateCalendarYn | `String` | Indicates if rate Calendar factors such as adder/multiplier should be used for price calculation. |
| rateCategory | `String` | Rate Category |
| rateCategoryDescription | `String` | Rate Category Description |
| rateClass | `String` | Rate Class |
| rateClassDescription | `String` | Rate Class Description |
| rateCodeId | `String` | Rate Code ID |
| rateCodeLockedYn | `String` | Rate Code Locked Y/N |
| rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| rateFloorOverrideYn | `String` | This flag indicates if the Rate Floor Rate is overridden for a particular Rate Code. |
| rateIncludesTaxYn | `String` | Does this rate include tax? Y/N |
| rateLabel | `String` | Rate Label |
| rateLevel | `Float` | Rate Level this rate code belongs to. |
| rateUpdateYN | `String` | Needs to send this rate to GDS or not. |
| rateinfoUrl | `String` | Rateinfo Url |
| redemptionRateYN | `String` | Redemption Rate YN |
| regionalAvailabilityYN | `String` | Regional Availability YN |
| repeatPostingRhythmYn | `String` | Indicates if the posting rhythm on the rate code is repeated until the end of the stay otherwise the posting rhythm is applied only once. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| rodBaseAmount | `Float` | Rod Base Amount |
| rodBaseFltPct | `String` | Rod Base Flt Pct |
| rodBaseRounding | `String` | Rod Base Rounding |
| rodBasedYn | `String` | Is the group code rate of day based |
| rodYn | `String` | Rod Y/N |
| roomAssignmentValue | `Float` | Room Assignment Value |
| roomType | `String` | Room Type |
| roomTypeDescription | `String` | Room Type Description |
| sdowBeginBookingDate | `Date` | Holds a copy of the column begin_booking_date while the rate code is disabled or with changes pending of approval |
| sdowEndBookingDate | `Date` | Holds a copy of the column end_booking_date while the rate code is disabled or with changes pending of approval |
| serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| servicePerc | `Float` | Service Percentage included. |
| shortInfo | `String` | Information to be used in the rate query |
| showRateAmountYn | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| sourceCode | `String` | Source Code |
| sourceDescription | `String` | Source Description |
| sourceGroupCode | `String` | Source Group Code |
| sourceGroupDescription | `String` | Source Group Description |
| taxIncludedPerc | `Float` | Percentage of included Tax. |
| taxIncludedYn | `String` | Tax is included in this rate. |
| tieredYN | `String` | Indicates if the rate is a tiered rate. |
| transactionCode | `String` | Rate transaction code |
| transactionCodeWeekend | `String` | Transaction Code Weekend |
| transactionTaxWeekendIncludedYN | `String` | Transaction code is inclusive of tax for weekend days Y/N |
| unitOfLengthOfStay | `Float` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellYn | `String` | Indicates if the rate code can be upsold |
| voucherBenefitRateYn | `String` | Flag to indicate if this is a voucher benefit rate code. |
| weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| wkDeptCode | `String` | Wk Dept Code |
| yieldAs | `String` | Yield As |
| yieldableYN | `String` | Yieldable YN |
| ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsRateSeasonDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralSeasonCode | `String` | Central Season Code |
| centralSeasonDescription | `String` | Central Season Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| displayColor | `String` | Display Color |
| endDate | `Date` | End Date |
| inactiveDate | `Date` | Inactive Date |
| inactiveYn | `String` | Inactive Y/N |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rateCode | `String` | Rate Code |
| ratecodeid | `String` | Ratecodeid |
| rateseasonid | `String` | Rateseasonid |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| seasonCode | `String` | Season Code |
| seasonDescription | `String` | Season Description |
| startDate | `Date` | Start Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsReportCalendarDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessDate | `Date` | Business Date |
| calendar | `String` | Calendar |
| calendarDescription | `String` | Calendar Description |
| calendarpkid | `Float` | Calendarpkid |
| calendartype | `String` | Calendartype |
| daydesc | `String` | Daydesc |
| dayenddate | `Date` | Dayenddate |
| daytimespan | `Float` | Daytimespan |
| defaultCalendarYn | `String` | Default Calendar Y/N |
| monthDescription | `String` | Month Description |
| period | `String` | Period |
| periodEndDate | `Date` | Period End Date |
| periodStartDate | `Date` | Period Start Date |
| periodpkid | `Float` | Periodpkid |
| periodtimespan | `Float` | Periodtimespan |
| quarter | `String` | Quarter |
| quarterDescription | `String` | Quarter Description |
| quarterEndDate | `Date` | Quarter End Date |
| quarterStartDate | `Date` | Quarter Start Date |
| quarterpkid | `Float` | Quarterpkid |
| quartertimespan | `Float` | Quartertimespan |
| weekcode | `String` | Weekcode |
| weekdesc | `String` | Weekdesc |
| weekenddate | `Date` | Weekenddate |
| weekkey | `String` | Weekkey |
| weekstartdate | `Date` | Weekstartdate |
| weektimespan | `Float` | Weektimespan |
| year | `Float` | Year |
| yearDescription | `String` | Year Description |
| yearEndDate | `Date` | Year End Date |
| yearStartDate | `Date` | Year Start Date |
| yearpkid | `Float` | Yearpkid |
| yeartimespan | `Float` | Yeartimespan |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsReservationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| accompaniedYN | `String` | Accompanied YN |
| accompanyingName | `String` | Accompanying guest names. |
| actualCheckInDateTime | `DateTime` | Actual Check In Date Time |
| actualCheckOutDateTime | `DateTime` | Actual Check Out Date Time |
| actualCheckInDate | `Date` | Actual Check-In Date |
| actualCheckInTime | `String` | Actual Check-In Time |
| actualCheckOutDate | `Date` | Actual Check-Out Date |
| actualCheckOutTime | `String` | Actual Check-Out Time |
| addressId | `Float` | Address ID |
| addresseeNameId | `Float` | Addressee Name ID |
| adults | `Float` | Adults |
| adultsTaxFree | `Float` | Adults Tax Free |
| advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| agencyprofileid | `Float` | Agencyprofileid |
| allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| allotmentid | `Float` | Block ID |
| amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| amenityLevelCode | `String` | Amenity Level Code |
| amountPercent | `Float` | Amount Percent |
| approvalAmount | `Float` | Approval Amount |
| approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| approvalCode | `String` | Approval Code |
| arrivalComments | `String` | Arrival Comments |
| arrivalDate | `Date` | Arrival Date |
| arrivalDateTime | `DateTime` | Arrival Date Time |
| arrivalEstimateTime | `Date` | Arrival Estimate Time |
| arrivalTime | `String` | Activity begin time |
| arrivaltransportid | `String` | Arrivaltransportid |
| attachedDate | `Date` | Attached Date |
| authorizedBillingYN | `String` | Not used. |
| authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| authorizerId | `Float` | Authorizer ID |
| autoCheckinYn | `String` | Auto Checkin Y/N |
| autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| autoSettleDays | `Float` | Auto Settle Days |
| autoSettleType | `String` | Auto Settle Type |
| autoSettleYN | `String` | Auto Settle YN |
| awardCode | `String` | Award Code |
| awardCode1 | `String` | Award code 1 |
| awardCode2 | `String` | Award code 2 |
| awardCode3 | `String` | Award code 3 |
| awardCode4 | `String` | Award Code 4 |
| awardCode5 | `String` | Award code 5 |
| awardMembershipID | `Float` | Award Membership ID |
| awardVoucher1 | `String` | Award Voucher number 1 |
| awardVoucher2 | `String` | Award Voucher number 2 |
| awardVoucher3 | `String` | Award Voucher number 3 |
| awardVoucher4 | `String` | Award Voucher number 4 |
| awardVoucher5 | `String` | Award Voucher number 5 |
| awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| awdUpgrTo | `String` | Room Type after the Upgrade Award |
| backToBackYN | `String` | Back To Back YN |
| balance | `Float` | Balance on the account. |
| baseRateAmount | `Float` | Base Rate Amount |
| baseRateCode | `String` | Base Rate Code |
| baseRateCurrencyCode | `String` | Base Rate Currency Code |
| basedOnRule | `String` | Based On Rule |
| baseratecurrencyid | `String` | Baseratecurrencyid |
| beginCity | `String` | Begin City |
| beginDatetime | `DateTime` | Begin Datetime |
| beginDistrict | `String` | Begin District |
| beginState | `String` | Begin State |
| beginSystemDateTime | `DateTime` | Stores the actual guest check in date and time. |
| billNumber | `String` | Bill Number |
| billingContact | `String` | Billing Contact |
| billingContactDisplayName | `String` | Billing Contact Display Name |
| billingContactId | `Float` | Billing Contact ID |
| billingContactName | `String` | Billing Contact Name |
| billingcontactprofileid | `Float` | Billing Contact Profile ID |
| blockCode | `String` | Block Code |
| blockCreateDate | `DateTime` | Block Create Date |
| blockID | `Float` | Block ID |
| blockName | `String` | Block Name |
| blockResort | `String` | Property this block belongs to. |
| blockStatus | `String` | Block Status |
| bonusCheckId | `Float` | Bonus Check ID |
| bookedRoomCategory | `String` | Booked Room Category |
| bookedroomcategoryid | `String` | Bookedroomcategoryid |
| businessDateCreated | `Date` | Business Date Created |
| businessDatetimeCreated | `DateTime` | Business Datetime Created |
| bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| cAutoPostAmount | `Float` | Central Auto Post Amount |
| cBaseRateAmount | `Float` | Central Base Rate Amount |
| cDiscountAmount | `Float` | C Discount Amount |
| cDiscountAmt | `Float` | C Discount Amt |
| cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFixedCharge | `Float` | Central Fixed Charge |
| cGrossRateAmount | `Float` | Central Gross Rate Amt |
| cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| cNetRoomAmount | `Float` | Central Net Room Amt |
| cOriginalBaseRate | `Float` | Central Original Base Rate |
| cPackageAmount | `Float` | Central Pkg Amt |
| cPackageTax | `Float` | Central Pkg Tax |
| cRateAmount | `Float` | C Rate Amount |
| cRoomCost | `Float` | Central Room Cost |
| cRoomTax | `Float` | Central Room Tax |
| cShareAmountOriginal | `Float` | Central Share Amount Original |
| cUpsellCharge | `Float` | Central Upsell Charge |
| cancelDate | `Date` | Cancel Date |
| cancelReason | `String` | Cancel Reason |
| cancelTime | `String` | Cancel Time |
| cancellationDate | `DateTime` | Cancellation Date |
| cancellationDatetime | `DateTime` | Cancellation Datetime |
| cancellationNumber | `String` | Cancellation Number |
| cancellationReasonDescription | `String` | Cancellation Reason Description |
| cancellationreasonid | `String` | Cancellationreasonid |
| cancelledBy | `String` | The user who canceled this Reservation. |
| cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| cardNumberByMembershipType | `String` | Card Number by Membership Type |
| centralApprovalAmount | `Float` | Central Approval Amount |
| centralCancelReason | `String` | Central Cancel Reason |
| centralCommissionCode | `String` | Central Commission Code |
| centralCommissionDescription | `String` | Central Commission Description |
| centralCreditLimit | `Float` | Central Credit Limit |
| centralDiscountReason | `String` | Central Discount Reason |
| centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| centralFBRevenue | `Float` | Central FB Revenue |
| centralGuestType | `String` | Central Guest Type |
| centralHurdle | `Float` | Central Hurdle |
| centralPackageCode | `String` | Central Package Code |
| centralPackageCodeDescription | `String` | Central Package Code Description |
| centralPackageForecastGroup | `String` | Central Package Forecast Group |
| centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| centralPaymentAmount | `Float` | Central Payment Amount |
| centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| centralPromotionDescription | `String` | Central Promotion Description |
| centralRateableValue | `Float` | Central Rateable Value |
| centralReservationType | `String` | Central Reservation Type |
| centralReservationTypeDescription | `String` | Central Reservation Type Description |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralRoomTypeCode | `String` | Central Room Type Code |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| centralSharedRoomRate | `Float` | Central Shared Room Rate |
| centralSpecialRequestDescription | `String` | Central Special Request Description |
| centralTaxType | `String` | Central Tax Type |
| centralTaxTypeDescription | `String` | Central Tax Type Description |
| centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| centralTotalRevenue | `Float` | Central Total Revenue |
| centralTotalRoomRate | `Float` | Central Total Room Rate |
| centralWaitlistPriority | `String` | Central Waitlist Priority |
| centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| centralWaitlistReason | `String` | Central Waitlist Reason |
| centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| chainCode | `String` | Chain Code |
| channelDescription | `String` | Channel Description |
| channelOrderBy | `Float` | Channel Order By |
| channelid | `String` | Channelid |
| checkInInitiatedBy | `String` | Check In Initiated By |
| checkinDuration | `Float` | Duration in seconds to complete Check-In |
| childBucket1 | `Float` | Child Bucket 1 |
| childBucket4 | `Float` | Child Bucket 4 |
| childBucket5 | `Float` | Child Bucket 5 |
| children | `Float` | Children |
| childrenAgeGroup2 | `Float` | Children Age Group 2) |
| childrenAgeGroup3 | `Float` | Children Age Group 3) |
| childrenAges | `String` | Children Ages |
| commissionCode | `String` | Commission Code |
| commissionDescription | `String` | Commission Description |
| commissionHoldCode | `String` | Commission Hold Code |
| commissionPaid | `Float` | Commission Paid |
| commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| commissionableYN | `String` | Commissionable YN |
| commissionid | `String` | Commissionid |
| compHouse | `String` | Comp House |
| compTypeCode | `String` | Comp Type Code |
| companyCity | `String` | Company City |
| companyCountry | `String` | Company Country |
| companyID | `Float` | Company ID |
| companyName | `String` | Company Name |
| companyProfileCorporateID | `String` | Company Profile Corporate ID |
| companyProfileID | `Float` | Company Profile ID |
| complimentaryYN | `String` | Complimentary YN |
| compreasonid | `String` | Compreasonid |
| computedResvStatus | `String` | Calculated reservation status. |
| confirmationLegNumber | `Float` | Confirmation Leg Number. |
| confirmationNo | `String` | Shared Confirmation Number |
| consumerYn | `String` | Consumer Y/N |
| contactName | `String` | Contact Name; UDFC02 on reservation. |
| contactProfileID | `Float` | Contact Profile ID |
| contactProfileName | `String` | Contact Profile Name |
| createdBy | `String` | The name of the user who created the record. |
| createdByDefaultResort | `String` | Created By Default Property |
| createdDate | `Date` | Created Date |
| createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| creditCardAuthDate | `Date` | Credit Card Auth Date |
| creditCardId | `Float` | Credit Card ID |
| creditLimit | `Float` | Credit Limit |
| creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| cribs | `Float` | Cribs |
| currencyCode | `String` | Currency Code |
| customReferenceNumber | `String` | Custom Reference Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| deletedFlag | `String` | Deleted Flag |
| departtransportid | `String` | Departtransportid |
| departureComments | `String` | Departure Comments |
| departureDate | `Date` | Departure Date |
| departureDateTime | `Date` | Departure Date Time |
| departureTime | `String` | Departure Time |
| departureTransportCode | `String` | Departure Transport Code |
| departureTransportationYN | `String` | Departure Transportation YN |
| depositMaturityType | `String` | Stores the Deposit maturity preference. |
| detatchedDate | `Date` | Detatched Date |
| detatchedYN | `String` | Detatched YN |
| directBillVerifyResponse | `String` | Direct Bill Verify Response |
| directbillauthby | `Float` | Directbillauthby |
| discountAmount | `Float` | Discount Amount |
| discountAmt | `Float` | Discount Amount |
| discountPercent | `Float` | Discount Percentage. |
| discountPrcnt | `Float` | Discount Prcnt |
| discountReason | `String` | Discount Reason |
| discountReasonDescription | `String` | Discount Reason Description |
| discountreasonid | `String` | Discountreasonid |
| displayColor | `String` | Display Color |
| dmlSeqNumber | `Float` | Dml Sequence No |
| doNotMoveRoom | `String` | Do Not Move Room |
| doNotMoveYN | `String` | Do not move room flag. |
| dropOffCarrierCode | `String` | Drop Off Carrier Code |
| dropOffDate | `Date` | Drop Off Date |
| dropOffStation | `String` | Drop Off Station |
| dropOffTime | `String` | Drop Off Time |
| dropOffType | `String` | Drop Off Type |
| dropOffTypeDescription | `String` | Drop Off Type Description |
| eTRComments | `String` | Comments related to Estimated Time of Return. |
| effectiveRateAmount | `Float` | Not used. |
| eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| emailAddress | `String` | Email Address |
| emailFolioYn | `String` | Email Folio Y/N |
| emailId | `Float` | Email ID |
| emailYn | `String` | Email Y/N |
| endCity | `String` | End City |
| endDatetime | `DateTime` | End Datetime |
| endDistrict | `String` | End District |
| endState | `String` | End State |
| endbusinessdate | `Date` | Endbusinessdate |
| entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| estimatedDepartureTime | `Date` | Estimated Departure Time |
| eventId | `Float` | Event ID |
| exchangePostingType | `String` | Exchange Posting Type |
| exchangeRate | `Float` | Exchange Rate |
| excludeFromAutoAuthorizationYN | `String` | Exclude From Auto Authorization YN |
| expectedTimeOfReturnETR | `DateTime` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| extSegNo | `Float` | Not used |
| extSeqNumber | `Float` | Not used |
| extensionId | `Float` | Internal extension number for the main reservation |
| externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| externalReference | `String` | External Reference |
| externalReferencesList | `String` | External References List |
| extraBeds | `Float` | Extra Beds |
| fBRevenue | `Float` | FB Revenue |
| fBRevenueRemaining | `Float` | F&B Revenue Remaining |
| faxId | `Float` | Fax ID |
| faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| feature | `String` | This stores the codes for the rooms features. Currently not used |
| financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| fixedCharge | `Float` | Not used. |
| fixedRateYN | `String` | Fixed Rate YN |
| folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| folioCloseDate | `Date` | Date the folio was changed to closed. |
| folioNumber | `String` | Folio Number |
| folioText1 | `String` | Folio Text1 |
| folioText2 | `String` | Folio Text2 |
| foreignCurrencyID | `String` | Foreign Currency ID |
| freeChild | `Float` | Free Child |
| frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| grossRateFuture | `Float` | Gross Rate Future |
| grossRatePast | `Float` | Gross Rate Past |
| groupName | `String` | Group Name |
| groupProfileARNumber | `Float` | Group Profile AR Number |
| groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| groupProfileClientID | `String` | Group Profile Client ID |
| groupProfileID | `Float` | Group Profile ID |
| groupProfileName | `String` | Group Profile Name |
| guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| guaranteecodeid | `String` | Guaranteecodeid |
| guestFirstName | `String` | Guest First Name |
| guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| guestSignature | `String` | Signature of the guest |
| guestStatus | `String` | Used for Police/Tourist Export |
| guestType | `String` | Guest Type |
| guestprofileid | `Float` | Guestprofileid |
| gueststatusid | `String` | Gueststatusid |
| guesttypeid | `String` | Guesttypeid |
| housekeepingServiceTime | `String` | Housekeeping Service Time |
| hurdle | `Float` | Hurdle |
| hurdleOverride | `String` | Hurdle Override |
| iDByMembershipClass | `String` | ID by Membership Class |
| iDByMembershipType | `String` | ID by Membership Type |
| individualCity | `String` | Guest Address. |
| individualCountry | `String` | Country of the guest |
| individualFirstName | `String` | Individual First Name |
| individualLastName | `String` | Individual Last Name |
| insertActionInstanceId | `Float` | Insert Action Instance ID |
| insertDate | `DateTime` | Insert Date |
| insertDateTime | `DateTime` | Insert DateTime |
| insertUser | `Float` | Insert User |
| intermediaryYn | `String` | Intermediary Y/N |
| internalAwardMembershipId | `Float` | Award Membership ID |
| internalBaseratecode | `String` | Baseratecode |
| internalBlockId | `Float` | Block ID. |
| internalCompanyprofileid | `Float` | Companyprofileid |
| internalGroupprofileid | `Float` | Groupprofileid |
| internalSourceprofileid | `Float` | Sourceprofileid |
| itemsQuantities | `String` | Items and Quantities |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyValidUntil | `Date` | Key Valid Until |
| lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| lastRoomNumber | `String` | Not used. |
| lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| leadTimeDays | `Float` | Lead Time for ordering |
| lengthOfStay | `Float` | Length of Stay |
| linkedArrivalDate | `DateTime` | Linked Arrival Date |
| linkedDepartureDate | `DateTime` | Linked Departure Date |
| linkedRoomType | `String` | Linked Room Type |
| listOfMembershipID | `String` | Membership ID |
| localBaseRateAmount | `Float` | Local Base Rate Amount |
| locationID | `String` | Internal ID to uniquely identify the Property |
| loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| mailYn | `String` | Mail Y/N |
| manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| marketCode | `String` | Market Code |
| marketid | `String` | Marketid |
| mcGenBeginDistrict | `String` | Mc Gen Begin District |
| mcGenBeginState | `String` | Mc Gen Begin State |
| mcGenEndDistrict | `String` | Mc Gen End District |
| mcGenEndState | `String` | Mc Gen End State |
| mcGenNextCountry | `String` | Mc Gen Next Country |
| mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| memberDescription | `String` | Member Description |
| memberLevel | `String` | Member Level |
| memberNumber | `String` | Member Number |
| membershipClass | `String` | Membership Class |
| membershipClassDescription | `String` | Membership Class Description |
| membershipCode | `String` | Membership Code |
| membershipId | `Float` | Membership ID |
| membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| name | `String` | Name |
| nameUsageType | `String` | Name Usage Type |
| nextCountry | `String` | Next Country |
| nextDestination | `String` | Country Specific Requirement for Nigeria. |
| numberOfRooms | `Float` | No of Rooms |
| operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| originOfBooking | `String` | Origin Of Booking |
| originalBaseRate | `Float` | Not used. |
| originalEndDate | `Date` | Original End Date |
| originalStartDate | `Date` | Original Start Date |
| ownerFfFlag | `String` | Owner Ff Flag |
| ownerOrFriendsFamily | `String` | Owner or Friends/Family |
| packageCode | `String` | Package Code |
| packageCodeDescription | `String` | Package Code Description |
| packageForecastGroup | `String` | Package Forecast Group |
| packageForecastGroupDescription | `String` | Package Forecast Group Description |
| parentReservationNameId | `Float` | Parent Resv Name ID |
| parentreservationid | `Float` | Parentreservationid |
| partAllotment | `String` | Part Allotment |
| partyCode | `String` | Party Code |
| paxNo | `Float` | Pax Number |
| paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| paymentMethod | `String` | Payment Method |
| paymentmethodid | `String` | Paymentmethodid |
| periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| phoneId | `Float` | Phone ID |
| physicalQuantity | `Float` | Physical Quantity |
| pickUpCarrierCode | `String` | Pick Up Carrier Code |
| pickUpDate | `Date` | Pick Up Date |
| pickUpStation | `String` | Pick Up Station |
| pickUpTransportNumber | `String` | Pick Up Transport Number |
| pickUpType | `String` | Pick Up Type |
| pickUpTypeDescription | `String` | Pick Up Type Description |
| pickUpTime | `String` | Pick-Up Time |
| pickupRequiredYN | `String` | Pickup Required YN |
| points | `Float` | Points |
| pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| postingAllowedYN | `String` | Posting Allowed YN |
| preArrReviewedDt | `DateTime` | This date flags if and when the record was reviewed from pre-arrival screen. |
| preArrReviewedUser | `Float` | User id who reviewed the record. |
| preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| preference | `String` | Preference |
| preferenceType | `String` | Preference Type |
| preferredRoomType | `String` | Preferred Room Type |
| previousCountry | `String` | Previous Country |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryShare | `String` | Primary Share |
| printRateYN | `String` | Print Rate YN |
| projectedFBRevenue | `Float` | Projected FB Revenue |
| projectedRoomRevenue | `Float` | Projected Room Revenue |
| projectedTotalRevenue | `Float` | Projected Total Revenue |
| promotionCode | `String` | Promotion Code |
| promotionDescription | `String` | Promotion Description |
| property | `String` | Indicates if the value set for the specific property. |
| pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| purgeDate | `DateTime` | Purge Date |
| purposeOfStay | `String` | Purpose of stay. |
| quantity | `Float` | Number of Rooms |
| queuePriority | `Float` | Queue priority of the reservation. |
| queueWaitTime | `Float` | Queue Wait Time |
| quoteId | `String` | Quote ID provided by external system. |
| rateAmount | `Float` | Rate Amount |
| rateCode | `String` | Rate Code |
| rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| rateTier | `Float` | Tier ID for the Rate Detail. |
| rateableValue | `Float` | Stay rateable value. |
| ratecodeid | `String` | Ratecodeid |
| rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| rdResvStatus | `String` | Rd Reservation Status |
| rdenBillingContactId | `Float` | Rden Billing Contact ID |
| rdenReservationContactId | `Float` | Rden Resv Contact ID |
| rdenReservationDate | `Date` | Rden Reservation Date |
| rdenResort | `String` | Rden Property |
| referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| registrationCardNo | `String` | Registration Card Number |
| registrationNumber | `Float` | Registration Number |
| reinstateDate | `DateTime` | Reinstate Date |
| repChannel | `String` | Reporting Channel |
| repChannelDescription | `String` | Reporting Channel Description |
| reportId | `String` | Report ID |
| resInsertSource | `String` | Reservation Insert Source |
| resInsertSourceType | `String` | Reservation Insert Source Type |
| reservationContactId | `Float` | Resv Contact ID |
| reservationDate | `DateTime` | Reservation Date |
| reservationNameID | `Float` | Reservation Name ID |
| reservationStatus | `String` | Reservation Status |
| reservationType | `String` | Reservation Type |
| reservationTypeDescription | `String` | Reservation Type Description |
| reservationid | `Float` | Reservationid |
| resort | `String` | Property |
| resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| restrictionOverride | `String` | Restriction Override |
| resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| resvNameid | `Float` | Reservation Nameid |
| resvNumber | `Float` | Not used in PMS currently. |
| resvcontactprofileid | `Float` | Resvcontactprofileid |
| revenueTypeCode | `String` | Revenue type (catering/rooms) |
| rhBillingContactId | `Float` | Rh Billing Contact ID |
| rhReservationContactId | `Float` | Rh Resv Contact ID |
| rhRoomFeatures | `String` | Rh Room Features |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| room | `String` | Room |
| roomCategory | `String` | Room Category |
| roomClass | `String` | Room Class |
| roomCost | `Float` | Room Cost |
| roomInstructions | `String` | Room Instructions |
| roomResort | `String` | Meeting Room Property |
| roomRevenue | `Float` | Room Revenue |
| roomRevenueRemaining | `Float` | Room Revenue Remaining |
| roomServiceTime | `String` | This is the Turndown room service time. |
| roomTypeDescription | `String` | Room Type Description |
| roomTypeToChargeCode | `String` | Room Type To Charge Code |
| roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| roomcategoryid | `String` | Roomcategoryid |
| roomid | `String` | Roomid |
| routingYN | `String` | Routing YN |
| scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| sguestName | `String` | Sguest Name |
| shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| shareId | `Float` | Share ID. |
| shareName | `String` | Share Name |
| sharePrcnt | `Float` | Not used. |
| shareSeqNumber | `Float` | Type of revenue |
| shareOfRateAmount | `Float` | Share of Rate Amount |
| sharedGuestName | `String` | Shared Guest Name |
| sharedProfileID | `Float` | Shared Profile ID |
| sharedReservationStatus | `String` | Shared Reservation Status |
| sharingYN | `String` | Sharing YN |
| sourceCity | `String` | Source City |
| sourceCode | `String` | Source Code |
| sourceCountry | `String` | Source Country |
| sourceName | `String` | Source Name |
| sourceProfileARNumber | `Float` | Source Profile AR Number |
| sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| sourceProfileIATANumber | `String` | Source Profile IATA Number |
| sourceProfileID | `Float` | Source Profile ID |
| sourceProfileName | `String` | Source Profile Name |
| sourceid | `String` | Sourceid |
| specialRequest | `String` | Special Request |
| specialRequestDescription | `String` | Special Request Description |
| spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| splitfromreservationid | `Float` | Splitfromreservationid |
| statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| stayRecordId | `Float` | Stay Record ID |
| suiteNumber | `String` | Suite Number |
| superSearchIndexText | `String` | Super Search Index Text |
| taRecordLocator | `String` | Ta Record Locator |
| taxExemptNumber | `String` | Tax exempt number on the profile |
| taxNumberOfStays | `Float` | Tax No of Stays |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| taxtypeid | `String` | Taxtypeid |
| tiad | `String` | Tiad |
| ticketNos | `String` | Ticket Nos |
| totalCostOfStay | `Float` | Total Cost of Stay |
| totalRevenue | `Float` | Total Revenue |
| totalRevenueRemaining | `Float` | Total Revenue Remaining |
| totalRoomRate | `Float` | Total Room Rate |
| trackItGroups | `String` | Track It Groups |
| trackItTypes | `String` | Track It Types |
| transactionid | `Float` | Transactionid |
| travelAgentCity | `String` | Travel Agent Address. |
| travelAgentCountry | `String` | Travel Agent Country |
| travelAgentID | `Float` | Travel Agent ID |
| travelAgentName | `String` | Travel Agent Name |
| travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| travelAgentProfileID | `Float` | Travel Agent Profile ID |
| travelAgentProfileName | `String` | Travel Agent Profile Name |
| truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| uDFC01 | `String` | UDFC01 |
| uDFC02 | `String` | UDFC02 |
| uDFC03 | `String` | UDFC03 |
| uDFC04 | `String` | UDFC04 |
| uDFC05 | `String` | UDFC05 |
| uDFC06 | `String` | UDFC06 |
| uDFC07 | `String` | UDFC07 |
| uDFC08 | `String` | UDFC08 |
| uDFC09 | `String` | UDFC09 |
| uDFC10 | `String` | UDFC10 |
| uDFC11 | `String` | UDFC11 |
| uDFC12 | `String` | UDFC12 |
| uDFC13 | `String` | UDFC13 |
| uDFC14 | `String` | UDFC14 |
| uDFC15 | `String` | UDFC15 |
| uDFC16 | `String` | UDFC16 |
| uDFC17 | `String` | UDFC17 |
| uDFC18 | `String` | UDFC18 |
| uDFC19 | `String` | UDFC19 |
| uDFC20 | `String` | UDFC20 |
| uDFC21 | `String` | UDFC21 |
| uDFC22 | `String` | UDFC22 |
| uDFC23 | `String` | UDFC23 |
| uDFC24 | `String` | UDFC24 |
| uDFC25 | `String` | UDFC25 |
| uDFC26 | `String` | UDFC26 |
| uDFC27 | `String` | UDFC27 |
| uDFC28 | `String` | UDFC28 |
| uDFC29 | `String` | UDFC29 |
| uDFC30 | `String` | UDFC30 |
| uDFC31 | `String` | UDFC31 |
| uDFC32 | `String` | UDFC32 |
| uDFC33 | `String` | UDFC33 |
| uDFC34 | `String` | UDFC34 |
| uDFC35 | `String` | UDFC35 |
| uDFC36 | `String` | UDFC36 |
| uDFC37 | `String` | UDFC37 |
| uDFC38 | `String` | UDFC38 |
| uDFC39 | `String` | UDFC39 |
| uDFC40 | `String` | UDFC40 |
| uDFD01 | `Date` | UDFD01 |
| uDFD02 | `Date` | UDFD02 |
| uDFD03 | `Date` | UDFD03 |
| uDFD04 | `Date` | UDFD04 |
| uDFD05 | `Date` | UDFD05 |
| uDFD06 | `Date` | UDFD06 |
| uDFD07 | `Date` | UDFD07 |
| uDFD08 | `Date` | UDFD08 |
| uDFD09 | `Date` | UDFD09 |
| uDFD10 | `Date` | UDFD10 |
| uDFD11 | `Date` | UDFD11 |
| uDFD12 | `Date` | UDFD12 |
| uDFD13 | `Date` | UDFD13 |
| uDFD14 | `Date` | UDFD14 |
| uDFD15 | `Date` | UDFD15 |
| uDFD16 | `Date` | UDFD16 |
| uDFD17 | `Date` | UDFD17 |
| uDFD18 | `Date` | UDFD18 |
| uDFD19 | `Date` | UDFD19 |
| uDFD20 | `Date` | UDFD20 |
| uDFN01 | `Float` | UDFN01 |
| uDFN02 | `Float` | UDFN02 |
| uDFN03 | `Float` | UDFN03 |
| uDFN04 | `Float` | UDFN04 |
| uDFN05 | `Float` | UDFN05 |
| uDFN06 | `Float` | UDFN06 |
| uDFN07 | `Float` | UDFN07 |
| uDFN08 | `Float` | UDFN08 |
| uDFN09 | `Float` | UDFN09 |
| uDFN10 | `Float` | UDFN10 |
| uDFN11 | `Float` | UDFN11 |
| uDFN12 | `Float` | UDFN12 |
| uDFN13 | `Float` | UDFN13 |
| uDFN14 | `Float` | UDFN14 |
| uDFN15 | `Float` | UDFN15 |
| uDFN16 | `Float` | UDFN16 |
| uDFN17 | `Float` | UDFN17 |
| uDFN18 | `Float` | UDFN18 |
| uDFN19 | `Float` | UDFN19 |
| uDFN20 | `Float` | UDFN20 |
| uDFN21 | `Float` | UDFN21 |
| uDFN22 | `Float` | UDFN22 |
| uDFN23 | `Float` | UDFN23 |
| uDFN24 | `Float` | UDFN24 |
| uDFN25 | `Float` | UDFN25 |
| uDFN26 | `Float` | UDFN26 |
| uDFN27 | `Float` | UDFN27 |
| uDFN28 | `Float` | UDFN28 |
| uDFN29 | `Float` | UDFN29 |
| uDFN30 | `Float` | UDFN30 |
| uDFN31 | `Float` | UDFN31 |
| uDFN32 | `Float` | UDFN32 |
| uDFN33 | `Float` | UDFN33 |
| uDFN34 | `Float` | UDFN34 |
| uDFN35 | `Float` | UDFN35 |
| uDFN36 | `Float` | UDFN36 |
| uDFN37 | `Float` | UDFN37 |
| uDFN38 | `Float` | UDFN38 |
| uDFN39 | `Float` | UDFN39 |
| uDFN40 | `Float` | UDFN40 |
| uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| updateDate | `DateTime` | Update Date |
| updateDatetime | `DateTime` | Update Datetime |
| updateUser | `Float` | Update User |
| updatedBy | `String` | Updated By |
| updatedByDefaultResort | `String` | Updated By Default Property |
| updatedDate | `Date` | Updated Date |
| updatedTime | `String` | Updated Time |
| upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| visaExpiryDate | `Date` | Visa Expiry Date |
| visaIssueDate | `Date` | Visa Issue Date |
| visaNumber | `String` | Visa Number |
| waitlistComment | `String` | Waitlist Comment |
| waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| waitlistPriority | `String` | Waitlist Priority |
| waitlistPriorityDescription | `String` | Waitlist Priority Description |
| waitlistReason | `String` | Waitlist Reason |
| waitlistReasonDescription | `String` | Waitlist Reason Description |
| waitlistpriorityid | `String` | Waitlistpriorityid |
| waitlistreasonid | `String` | Waitlistreasonid |
| walkInYN | `String` | Walk-In YN |
| yieldableYn | `String` | Yieldable Y/N |
| ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsRevenuePackagesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| addToRateYN | `String` | Add To Rate YN |
| arrangementCode | `String` | Arrangement Code |
| beginBookingDate | `Date` | Begin Booking Date |
| bookingDuration | `Float` | Not used |
| calculationRule | `String` | Calculation Rule |
| cateringYn | `String` | Catering Y/N |
| centralPackageCode | `String` | Central Package Code |
| centralPackageCodeDescription | `String` | Central Package Code Description |
| centralPackageForecastGroup | `String` | Central Package Forecast Group |
| centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| currencyCode | `String` | Currency Code |
| currencyDesc | `String` | Currency Desc |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| deliveryTimeReqrdYn | `String` | Indicates if a Delivery Time is required. |
| endBookingDate | `Date` | End Booking Date |
| externalLocked | `String` | External Locked |
| flexibleDurationYN | `String` | Flexible Duration YN |
| forecastGroupCode | `String` | Not used |
| forecastNextDayYN | `String` | Forecast Next Day YN |
| formula | `String` | Formula |
| genPlAtEodOfCoDate | `String` | Gen Pl At Eod of Co Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalPostingrhythm | `String` | Postingrhythm |
| inventoriedYN | `String` | Inventoried YN |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| longInfo | `String` | Long Info |
| maxPersons | `String` | Maximum number of persons |
| maximumPersons | `String` | Maximum Persons |
| minimumAdvBookDays | `Float` | Minimum Advance Booking Days required for the product. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| outletCode | `String` | Outlet Code |
| overrideFixedRateYn | `String` | Override Fixed Rate Y/N |
| pOSAccountYN | `String` | POS Account YN |
| pOSNextDayYN | `String` | POS Next Day YN |
| packageCode | `String` | Package Code |
| packageCodeDescription | `String` | Package Code Description |
| packageCodeShortDescription | `String` | Package Code Short Description |
| packageForecastGroup | `String` | Package Forecast Group |
| packageForecastGroupDescription | `String` | Package Forecast Group Description |
| pkgForcastGroup | `String` | Package forcast group code |
| pkgforecastgrpid | `String` | Pkgforecastgrpid |
| postingRhythm | `String` | Posting Rhythm |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printSeparateYN | `String` | Print Separate YN |
| product | `String` | Product |
| productType | `String` | Product Type |
| productid | `String` | Productid |
| property | `String` | Code to uniquely identify the Property |
| redemptionProductYN | `String` | Redemption Product YN |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| separatelySoldYN | `String` | Separately Sold YN |
| standardDuration | `Float` | Not used |
| standardPersons | `String` | Not used |
| ticketsYn | `String` | Indicates a Reservation Ticket Package. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| validFromTime | `Date` | Valid From Time |
| validToTime | `Date` | Valid To Time |
| webBookableYN | `String` | Web Bookable YN |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsRoomDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accessible | `String` | Accessible |
| areaF | `Float` | Area in sqft |
| areaM | `Float` | Area in sqm |
| assignAssignStatus | `String` | Assign Assign Status |
| assignDate | `DateTime` | Room assignment date |
| assignReasonDesc | `String` | Assign Reason Desc |
| assignType | `String` | Assign Type |
| assignemployeeid | `Float` | Assignemployeeid |
| assignreasonid | `String` | Assignreasonid |
| bedType | `String` | Bed Type |
| building | `String` | Building |
| buildingGroup | `String` | Building Group |
| businessDate | `Date` | Business Date |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cMinimumRevenue | `Float` | Central Minimum Revenue |
| cRackRate | `Float` | Central Rack Rate |
| centralMeetingRoomType | `String` | Central Meeting Room Type |
| centralRoomClass | `String` | Central Room Class |
| centralRoomType | `String` | Central Room Type |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| combinationRoomYN | `String` | Combination Room YN |
| comments | `String` | Comments |
| componentRoom | `String` | Suite component room numbers |
| connectingRoomNumber | `String` | Connecting Room Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| daySection | `String` | Indicates the section to which employee belongs. |
| deductYN | `String` | Deduct YN |
| defatulratecodeid | `String` | Defatulratecodeid |
| defaultRateDesc | `String` | Default Rate Description |
| deletedflag | `String` | Deleted Flag |
| departureCredits | `Float` | Credits associated with the task after departure. |
| description | `String` | Description |
| diaryName | `String` | Diary name to show room in |
| diarydisplayflag | `String` | Diarydisplayflag |
| discrepancy | `String` | Discrepancy |
| doors | `String` | Number of doors |
| eveningSection | `String` | Section the room belongs to for evening housekeeping |
| evisitorFacilityId | `String` | Facility ID for eVisitor. |
| excludedEventTypes | `String` | Stores event types which do not require alternate spaces. |
| facing | `String` | Direction room faces |
| floor | `String` | Floor |
| foPers | `Float` | The persons staying in room according to Front office. |
| forceAlternateYn | `String` | Defines if the function space needs an alternate space when booked. |
| frontDeskLocation | `String` | The front desk location this room should check in to. |
| frontOfficeStatus | `String` | Front Office Status of the room i.e.: Vacant or Occupied. |
| fullUtilizationTime | `Float` | Minutes occupied that define the room as 100% utilized. Maximum is 1440 minutes. |
| genericYN | `String` | Generic YN |
| handicapflag | `String` | Handicapflag |
| heightmaxF | `Float` | Max Height in ft |
| heightmaxM | `Float` | Max Height in m |
| heightminF | `Float` | Minumum heigth of room (feet) |
| heightminM | `Float` | Minumum heigth of room (meters) |
| holdDateTime | `DateTime` | Date and time when room will be released from hold. |
| holdType | `String` | Hold type from resort_assignment_reasons table. |
| holdUser | `Float` | User that is holding the room. |
| housekeepingAssignmentOrderBy | `Float` | Sequence for automatically generated task assignment. |
| housekeepingInspDate | `Date` | Housekeeping Inspected date |
| housekeepingInspEmpId | `String` | Houskeeping inspected employee id |
| housekeepingPers | `Float` | The number of persons staying in the room according to housekeeping |
| housekeepingStatus | `String` | The status of this room according to housekeeping |
| imageId | `Float` | Image ID |
| inactiveflag | `String` | Inactive Flag |
| includeInStatisticsYN | `String` | Include in Statistics YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalTempflag | `String` | Tempflag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyCode | `String` | The current key code for this room.  Used to create keys for a room. |
| keyOptions | `String` | Privileges available for this key |
| lastCheckOutDate | `Date` | The last check out date for this room. |
| lastMeterReading | `Float` | The last meter reading for condos that track electrical usage of rented rooms. |
| lengthF | `Float` | Length (feet) |
| lengthM | `Float` | Length (meters) |
| light | `String` | Number of lights in the room |
| locationID | `String` | Internal ID to uniquely identify the Property |
| loudspeakersflag | `String` | Loudspeakersflag |
| maxAdvance | `Float` | Maximum number of days before the catering event date  that the space can be booked on the web. |
| maxCapacity | `Float` | Function Space Maximum Capacity. |
| maxSharedGroups | `Float` | Maximum number of groups for a Shared function space allowed. |
| maximumOccupancy | `Float` | Maximum Occupancy |
| measurement | `String` | The unit of measurement for this square units (IE: Feet Meters etc) |
| meetingRoomType | `String` | Type of meeting room |
| meetingRoomYN | `String` | Meeting Room YN |
| meetingroomTypeDesc | `String` | Meetingroom Type Description |
| meetingroomTypeSeq | `Float` | Meetingroom Type Sequence |
| microphoneSocketTypes | `String` | Type of microphone sockets |
| microphoneSockets | `Float` | Number of microphone sockets |
| minAdvance | `Float` | Minimum number of days before the catering event date that the space can be booked on the web. |
| minCapacity | `Float` | Minimum Capacity |
| minimumRevenue | `Float` | Minimum Revenue |
| numberOfBeds | `Float` | Specifies the number of beds in this room. |
| occupancyCondition | `String` | Current room condition updated daily.(ie StayOverDueOutExpected etc) |
| occupantDiscrepancy | `Float` | Discrepancy between front desk and housekeeping |
| onlinePrintingYn | `String` | Used for pseudo rooms. If Y then this pseudo room will be included in Online Printing for reservation changes. |
| orderBy2 | `Float` | Display sequence 2 |
| orderBy3 | `Float` | Display sequence 3 |
| orderBy4 | `Float` | Display sequence 4 |
| orderBy5 | `Float` | Display sequence 5 |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ovosGradeCode | `String` | Stores a Grade associated with a unit to determine the room display order in Room Assignment and Room Plan screens. |
| ovosUnitYn | `String` | Room can be OVOS unit. |
| pcode | `String` | Not used |
| personDiscrepancy | `Float` | Person discrepancy between front desk and houskeeping |
| phoneNumber | `String` | Phone Number |
| physicalNumberOfRooms | `Float` | Physical Number of Rooms |
| pickupCredits | `Float` | Houskeeping credits for cleaning room in pickup status |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| pseudoRoomYN | `String` | Pseudo Room YN |
| publishedRateAmount | `Float` | Default rate for the room |
| publishedRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rating | `String` | Rating |
| repAssignReasonDescription | `String` | Reporting Assign Reason Desc |
| repBedTypeDescription | `String` | Reporting Bed Type Desc |
| repMeetingroomTypeDescription | `String` | Reporting Meetingroom Type Desc |
| repMeetingroomTypeSequence | `Float` | Reporting Meetingroom Type Seq |
| repRoomClassSellSequence | `Float` | Reporting Room Class Sell Seq |
| repRoomFeaturesDescs | `String` | Reporting Room Features Descs |
| repRoomStatusReason | `String` | Reporting Room Status Reason |
| repRoomStatusReasonDescription | `String` | Reporting Room Status Reason Desc |
| returnStatus | `String` | Room return status |
| room | `String` | Room |
| roomAssignmentRating | `Float` | Room Assignment Rating. |
| roomCategoryBedtype | `String` | Room Category Bedtype |
| roomCategoryDesc | `String` | Room Category Desc |
| roomClass | `String` | Room Class |
| roomClassCentralDescription | `String` | Room Class Central Description |
| roomClassDescription | `String` | Room Class Description |
| roomClassSequence | `Float` | Room Class Sequence |
| roomCondition | `String` | Room Condition |
| roomFeatureDescription | `String` | Room Feature Description |
| roomFeatures | `String` | This stores the codes for the rooms features. Currently not used |
| roomNumber | `String` | Room Number |
| roomParity | `String` | Room Parity |
| roomStatus | `String` | Room Status |
| roomStatusDescription | `String` | Room Status Description |
| roomStatusFromDate | `Date` | The date as of which the room_status is valid. |
| roomStatusReason | `String` | Room Status Reason |
| roomStatusReasonDesc | `String` | Room Status Reason Description |
| roomStatusRemarks | `String` | Room status remarks |
| roomStatusToDate | `Date` | The date till which the room_status is valid.(Used during OO and OS status of rooms ) |
| roomType | `String` | Room Type |
| roomUseCount | `Float` | Total Count of the number of days the room was used. |
| roomcategoryid | `String` | Roomcategoryid |
| roomclassid | `String` | Roomclassid |
| roomid | `String` | Roomid |
| roomstatusreasonid | `String` | Roomstatusreasonid |
| sequence | `Float` | Sequence |
| serviceStatus | `String` | Current guest service status code for this room. Example: Service status can be DND (Do Not Disturb) or MUP (Make Up Room) |
| setupNotes | `String` | Notes for the setup of the room |
| shareableflag | `String` | Shareableflag |
| smoking | `String` | Smoking |
| smokingPreferences | `String` | Smoking Preferences |
| squareUnits | `Float` | The square units for this room (IE: if a condo in the US likely the square feet of this room) |
| stayoverCredits | `Float` | Stayover Credits |
| suiteType | `String` | Standard or Suite |
| suiteYN | `String` | Suite YN |
| supplement | `String` | Supplement |
| tempFlag | `String` | Temp Flag |
| translationboothNum | `Float` | Number for the booth |
| turnDown | `String` | Turn Down |
| turndownCredits | `Float` | Houskeeping credits for Turndown. |
| tvRadioSockets | `Float` | Number of TV or radio sockets |
| unit | `String` | Unit |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| visibleOnWebYn | `String` | Flag makes a Function Space visible on the web. |
| webBookingYn | `String` | Web Booking Y/N |
| weightF | `Float` | Room weigth (feet) |
| weightM | `Float` | Room weigth (meters) |
| widthF | `Float` | Width (feet) |
| widthM | `Float` | Width (meters) |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsRoutingInstructionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountCode | `String` | Account Code |
| addTransactionYN | `String` | Add Trx Y/N |
| addressId | `Float` | Address ID |
| authemployeeid | `Float` | Authemployeeid |
| authorizerId | `Float` | Authorizer ID |
| basedOnRate | `String` | Rate Code that is the source for this routing instruction. |
| billingInstrnCode | `Float` | Billing Instruction Code. |
| billtoprofileid | `Float` | Billtoprofileid |
| cCompPreApprovalAmount | `Float` | Central Comp Pre Approval Amt |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| centralExtendedInstructionSummary | `String` | Central Extended Instruction Summary |
| centralInstructionSummary | `String` | Central Instruction Summary |
| centralRoutingAmountLimit | `Float` | Central Routing Amount Limit |
| centralRoutingLimitUsed | `Float` | Central Routing Limit Used |
| centralRoutingTransactionCode | `String` | Central Routing Transaction Code |
| centralRoutingTransactionCodeDescription | `String` | Central Routing Transaction Code Description |
| comments | `String` | Comments |
| compAuthorizer | `String` | Comp Authorizer |
| compPreApprovalAmt | `Float` | Amount for which the comp pre approval is sought. |
| compPreApprovalCode | `String` | Approval Code from PTS system. |
| compPreApprovalDate | `Date` | Approval Date from PTS system. |
| compPreApprovalRequiredYn | `String` | Comp Pre Approval Required Y/N |
| compTypeCode | `String` | Comp Type Code |
| compVoucherNo | `String` | Comp Voucher Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyYn | `String` | Daily Y/N |
| dayString | `String` | Concatenated string of all the days. This is also used part of the unique key. |
| declinedBy | `Float` | User ID of user that declined comp routing request |
| declinedYn | `String` | Used to decline comp routing requests |
| deletedFlag | `String` | Deleted Flag |
| endDate | `DateTime` | End Date |
| extendedInstructionSummary | `String` | Extended Instruction Summary |
| folio | `Float` | Folio |
| fridayYN | `String` | Friday YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| instructionSummary | `String` | Instruction Summary |
| internalDeletedflag | `String` | Deleted Flag |
| internalMembershipid | `Float` | Membershipid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| membershipId | `Float` | Membership ID |
| mondayYN | `String` | Monday YN |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| payeeFirstName | `String` | First name of the guest paying the bill |
| payeeLastName | `String` | Nirst name of the guest paying the bill |
| payeeNameID | `Float` | Name Id to which it should be routed. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printReceiptYn | `String` | Flag to indicate if a receipt has to be printed on posting the transaction used in Opera 9. |
| property | `String` | Code to uniquely identify the Property |
| requestedBy | `String` | Application user who requested the report. |
| reservationNameId | `Float` | Resv Name ID |
| reservationid | `Float` | Reservationid |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| routedToRoomNo | `String` | Routed To Room Number |
| routingAmountLimit | `Float` | Routing Amount Limit |
| routingBeginDate | `DateTime` | Routing Begin Date |
| routingCode | `String` | Routing Code |
| routingCodeDescription | `String` | Routing Code Description |
| routingCoversLimit | `Float` | No. of covers for this routing instruction. |
| routingDateRange | `String` | Routing Date Range |
| routingDaysOfWeek | `String` | Routing Days of Week |
| routingInstructionsId | `Float` | Number to identify the entry. |
| routingLimitType | `String` | Identifies whether this routing instruction has a limit amount or limit percent. |
| routingLimitUsed | `Float` | Amount of credit used for this routing instruction |
| routingLinkId | `Float` | Value used to group routing instructions. Taken from Sequence ROUTING_LINK_ID_SEQ. |
| routingPercentageLimit | `Float` | Routing Percentage Limit |
| routingTransactionCode | `String` | Routing Transaction Code |
| routingTransactionCodeDescription | `String` | Routing Transaction Code Description |
| routingType | `String` | To specify whether it is a package routing or not |
| routingTypeDesc | `String` | Routing Type Desc |
| routinginstructid | `Float` | Routinginstructid |
| saturdayYN | `String` | Saturday YN |
| sundayYN | `String` | Sunday YN |
| tcGroup | `String` | Transaction Code Group |
| tcSubgroup | `String` | Transaction Code Subgroup |
| thursdayYN | `String` | Thursday YN |
| toReservationNameId | `Float` | To Resv Name ID |
| toreservationid | `Float` | Toreservationid |
| transcodearrangementid | `Float` | Transcodearrangementid |
| transcodeid | `String` | Transcodeid |
| transgroupid | `String` | Transgroupid |
| transsubgroupid | `String` | Transsubgroupid |
| trxServiceType | `String` | Transaction Service Type |
| tuesdayYN | `String` | Tuesday YN |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| wednesdayYN | `String` | Wednesday YN |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsTransactionCodeDetailsType

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

### FinancialTransactionDetailsTransactionCodeArrangmentDetailsType

| Field | Type | Description |
| --- | --- | --- |
| arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| arrangementCode | `String` | Arrangement Code |
| arrangementDescription | `String` | Arrangement Description for the Transaction Code. |
| arrangementId | `Float` | Arrangement ID |
| arrangementType | `String` | Arrangement Type |
| bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRoutingAmount | `Float` | Central Routing Amount |
| centralTransactionCode | `String` | Central Transaction Code |
| centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| compYn | `String` | Comp Y/N |
| complimentaryYN | `String` | Complimentary YN |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyYn | `String` | Daily Y/N |
| day1 | `String` | Day1 |
| day2 | `String` | Day2 |
| day3 | `String` | Day3 |
| day4 | `String` | Day4 |
| day5 | `String` | Day5 |
| day6 | `String` | Day6 |
| day7 | `String` | Day7 |
| deletedFlag | `String` | Deleted Flag |
| eligibleYn | `String` | Specifies the Eligibility to calculate membership points. |
| exportBucketType | `String` | User defined Export Bucket type. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `Date` | Inactive Flag |
| inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| revenueflag | `String` | Revenueflag |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| routingPercent | `Float` | Routing Percent |
| transactionCode | `String` | Transaction Code |
| transactionCodeDescription | `String` | Transaction Code Description |
| transcodearrangementid | `Float` | Transcodearrangementid |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsFromReservationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| accompaniedYN | `String` | Accompanied YN |
| accompanyingName | `String` | Accompanying guest names. |
| actualCheckInDateTime | `DateTime` | Actual Check In Date Time |
| actualCheckOutDateTime | `DateTime` | Actual Check Out Date Time |
| actualCheckInDate | `Date` | Actual Check-In Date |
| actualCheckInTime | `String` | Actual Check-In Time |
| actualCheckOutDate | `Date` | Actual Check-Out Date |
| actualCheckOutTime | `String` | Actual Check-Out Time |
| addressId | `Float` | Address ID |
| addresseeNameId | `Float` | Addressee Name ID |
| adults | `Float` | Adults |
| adultsTaxFree | `Float` | Adults Tax Free |
| advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| agencyprofileid | `Float` | Agencyprofileid |
| allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| allotmentid | `Float` | Block ID |
| amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| amenityLevelCode | `String` | Amenity Level Code |
| amountPercent | `Float` | Amount Percent |
| approvalAmount | `Float` | Approval Amount |
| approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| approvalCode | `String` | Approval Code |
| arrivalComments | `String` | Arrival Comments |
| arrivalDate | `Date` | Arrival Date |
| arrivalDateTime | `DateTime` | Arrival Date Time |
| arrivalEstimateTime | `Date` | Arrival Estimate Time |
| arrivalTime | `String` | Activity begin time |
| arrivaltransportid | `String` | Arrivaltransportid |
| attachedDate | `Date` | Attached Date |
| authorizedBillingYN | `String` | Not used. |
| authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| authorizerId | `Float` | Authorizer ID |
| autoCheckinYn | `String` | Auto Checkin Y/N |
| autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| autoSettleDays | `Float` | Auto Settle Days |
| autoSettleType | `String` | Auto Settle Type |
| autoSettleYN | `String` | Auto Settle YN |
| awardCode | `String` | Award Code |
| awardCode1 | `String` | Award code 1 |
| awardCode2 | `String` | Award code 2 |
| awardCode3 | `String` | Award code 3 |
| awardCode4 | `String` | Award Code 4 |
| awardCode5 | `String` | Award code 5 |
| awardMembershipID | `Float` | Award Membership ID |
| awardVoucher1 | `String` | Award Voucher number 1 |
| awardVoucher2 | `String` | Award Voucher number 2 |
| awardVoucher3 | `String` | Award Voucher number 3 |
| awardVoucher4 | `String` | Award Voucher number 4 |
| awardVoucher5 | `String` | Award Voucher number 5 |
| awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| awdUpgrTo | `String` | Room Type after the Upgrade Award |
| backToBackYN | `String` | Back To Back YN |
| balance | `Float` | Balance on the account. |
| baseRateAmount | `Float` | Base Rate Amount |
| baseRateCode | `String` | Base Rate Code |
| baseRateCurrencyCode | `String` | Base Rate Currency Code |
| basedOnRule | `String` | Based On Rule |
| baseratecurrencyid | `String` | Baseratecurrencyid |
| beginCity | `String` | Begin City |
| beginDatetime | `DateTime` | Begin Datetime |
| beginDistrict | `String` | Begin District |
| beginState | `String` | Begin State |
| beginSystemDateTime | `DateTime` | Stores the actual guest check in date and time. |
| billNumber | `String` | Bill Number |
| billingContact | `String` | Billing Contact |
| billingContactDisplayName | `String` | Billing Contact Display Name |
| billingContactId | `Float` | Billing Contact ID |
| billingContactName | `String` | Billing Contact Name |
| billingcontactprofileid | `Float` | Billing Contact Profile ID |
| blockCode | `String` | Block Code |
| blockCreateDate | `DateTime` | Block Create Date |
| blockID | `Float` | Block ID |
| blockName | `String` | Block Name |
| blockResort | `String` | Property this block belongs to. |
| blockStatus | `String` | Block Status |
| bonusCheckId | `Float` | Bonus Check ID |
| bookedRoomCategory | `String` | Booked Room Category |
| bookedroomcategoryid | `String` | Bookedroomcategoryid |
| businessDateCreated | `Date` | Business Date Created |
| businessDatetimeCreated | `DateTime` | Business Datetime Created |
| bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| cAutoPostAmount | `Float` | Central Auto Post Amount |
| cBaseRateAmount | `Float` | Central Base Rate Amount |
| cDiscountAmount | `Float` | C Discount Amount |
| cDiscountAmt | `Float` | C Discount Amt |
| cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFixedCharge | `Float` | Central Fixed Charge |
| cGrossRateAmount | `Float` | Central Gross Rate Amt |
| cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| cNetRoomAmount | `Float` | Central Net Room Amt |
| cOriginalBaseRate | `Float` | Central Original Base Rate |
| cPackageAmount | `Float` | Central Pkg Amt |
| cPackageTax | `Float` | Central Pkg Tax |
| cRateAmount | `Float` | C Rate Amount |
| cRoomCost | `Float` | Central Room Cost |
| cRoomTax | `Float` | Central Room Tax |
| cShareAmountOriginal | `Float` | Central Share Amount Original |
| cUpsellCharge | `Float` | Central Upsell Charge |
| cancelDate | `Date` | Cancel Date |
| cancelReason | `String` | Cancel Reason |
| cancelTime | `String` | Cancel Time |
| cancellationDate | `DateTime` | Cancellation Date |
| cancellationDatetime | `DateTime` | Cancellation Datetime |
| cancellationNumber | `String` | Cancellation Number |
| cancellationReasonDescription | `String` | Cancellation Reason Description |
| cancellationreasonid | `String` | Cancellationreasonid |
| cancelledBy | `String` | The user who canceled this Reservation. |
| cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| cardNumberByMembershipType | `String` | Card Number by Membership Type |
| centralApprovalAmount | `Float` | Central Approval Amount |
| centralCancelReason | `String` | Central Cancel Reason |
| centralCommissionCode | `String` | Central Commission Code |
| centralCommissionDescription | `String` | Central Commission Description |
| centralCreditLimit | `Float` | Central Credit Limit |
| centralDiscountReason | `String` | Central Discount Reason |
| centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| centralFBRevenue | `Float` | Central FB Revenue |
| centralGuestType | `String` | Central Guest Type |
| centralHurdle | `Float` | Central Hurdle |
| centralPackageCode | `String` | Central Package Code |
| centralPackageCodeDescription | `String` | Central Package Code Description |
| centralPackageForecastGroup | `String` | Central Package Forecast Group |
| centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| centralPaymentAmount | `Float` | Central Payment Amount |
| centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| centralPromotionDescription | `String` | Central Promotion Description |
| centralRateableValue | `Float` | Central Rateable Value |
| centralReservationType | `String` | Central Reservation Type |
| centralReservationTypeDescription | `String` | Central Reservation Type Description |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralRoomTypeCode | `String` | Central Room Type Code |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| centralSharedRoomRate | `Float` | Central Shared Room Rate |
| centralSpecialRequestDescription | `String` | Central Special Request Description |
| centralTaxType | `String` | Central Tax Type |
| centralTaxTypeDescription | `String` | Central Tax Type Description |
| centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| centralTotalRevenue | `Float` | Central Total Revenue |
| centralTotalRoomRate | `Float` | Central Total Room Rate |
| centralWaitlistPriority | `String` | Central Waitlist Priority |
| centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| centralWaitlistReason | `String` | Central Waitlist Reason |
| centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| channelDescription | `String` | Channel Description |
| channelOrderBy | `Float` | Channel Order By |
| channelid | `String` | Channelid |
| checkInInitiatedBy | `String` | Check In Initiated By |
| checkinDuration | `Float` | Duration in seconds to complete Check-In |
| childBucket1 | `Float` | Child Bucket 1 |
| childBucket4 | `Float` | Child Bucket 4 |
| childBucket5 | `Float` | Child Bucket 5 |
| children | `Float` | Children |
| childrenAgeGroup2 | `Float` | Children Age Group 2) |
| childrenAgeGroup3 | `Float` | Children Age Group 3) |
| childrenAges | `String` | Children Ages |
| commissionCode | `String` | Commission Code |
| commissionDescription | `String` | Commission Description |
| commissionHoldCode | `String` | Commission Hold Code |
| commissionPaid | `Float` | Commission Paid |
| commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| commissionableYN | `String` | Commissionable YN |
| commissionid | `String` | Commissionid |
| compHouse | `String` | Comp House |
| compTypeCode | `String` | Comp Type Code |
| companyCity | `String` | Company City |
| companyCountry | `String` | Company Country |
| companyID | `Float` | Company ID |
| companyName | `String` | Company Name |
| companyProfileCorporateID | `String` | Company Profile Corporate ID |
| companyProfileID | `Float` | Company Profile ID |
| complimentaryYN | `String` | Complimentary YN |
| compreasonid | `String` | Compreasonid |
| computedResvStatus | `String` | Calculated reservation status. |
| confirmationLegNumber | `Float` | Confirmation Leg Number. |
| confirmationNo | `String` | Shared Confirmation Number |
| consumerYn | `String` | Consumer Y/N |
| contactName | `String` | Contact Name; UDFC02 on reservation. |
| contactProfileID | `Float` | Contact Profile ID |
| contactProfileName | `String` | Contact Profile Name |
| createdBy | `String` | The name of the user who created the record. |
| createdByDefaultResort | `String` | Created By Default Property |
| createdDate | `Date` | Created Date |
| createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| creditCardAuthDate | `Date` | Credit Card Auth Date |
| creditCardId | `Float` | Credit Card ID |
| creditLimit | `Float` | Credit Limit |
| creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| cribs | `Float` | Cribs |
| currencyCode | `String` | Currency Code |
| customReferenceNumber | `String` | Custom Reference Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| deletedFlag | `String` | Deleted Flag |
| departtransportid | `String` | Departtransportid |
| departureComments | `String` | Departure Comments |
| departureDate | `Date` | Departure Date |
| departureDateTime | `Date` | Departure Date Time |
| departureTime | `String` | Departure Time |
| departureTransportCode | `String` | Departure Transport Code |
| departureTransportationYN | `String` | Departure Transportation YN |
| depositMaturityType | `String` | Stores the Deposit maturity preference. |
| detatchedDate | `Date` | Detatched Date |
| detatchedYN | `String` | Detatched YN |
| directBillVerifyResponse | `String` | Direct Bill Verify Response |
| directbillauthby | `Float` | Directbillauthby |
| discountAmount | `Float` | Discount Amount |
| discountAmt | `Float` | Discount Amount |
| discountPercent | `Float` | Discount Percentage. |
| discountPrcnt | `Float` | Discount Prcnt |
| discountReason | `String` | Discount Reason |
| discountReasonDescription | `String` | Discount Reason Description |
| discountreasonid | `String` | Discountreasonid |
| displayColor | `String` | Display Color |
| dmlSeqNumber | `Float` | Dml Sequence No |
| doNotMoveRoom | `String` | Do Not Move Room |
| doNotMoveYN | `String` | Do not move room flag. |
| dropOffCarrierCode | `String` | Drop Off Carrier Code |
| dropOffDate | `Date` | Drop Off Date |
| dropOffStation | `String` | Drop Off Station |
| dropOffTime | `String` | Drop Off Time |
| dropOffType | `String` | Drop Off Type |
| dropOffTypeDescription | `String` | Drop Off Type Description |
| eTRComments | `String` | Comments related to Estimated Time of Return. |
| effectiveRateAmount | `Float` | Not used. |
| eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| emailAddress | `String` | Email Address |
| emailFolioYn | `String` | Email Folio Y/N |
| emailId | `Float` | Email ID |
| emailYn | `String` | Email Y/N |
| endCity | `String` | End City |
| endDatetime | `DateTime` | End Datetime |
| endDistrict | `String` | End District |
| endState | `String` | End State |
| endbusinessdate | `Date` | Endbusinessdate |
| entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| estimatedDepartureTime | `Date` | Estimated Departure Time |
| eventId | `Float` | Event ID |
| exchangePostingType | `String` | Exchange Posting Type |
| exchangeRate | `Float` | Exchange Rate |
| excludeFromAutoAuthorizationYN | `String` | Exclude From Auto Authorization YN |
| expectedTimeOfReturnETR | `DateTime` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| extSegNo | `Float` | Not used |
| extSeqNumber | `Float` | Not used |
| extensionId | `Float` | Internal extension number for the main reservation |
| externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| externalReference | `String` | External Reference |
| externalReferencesList | `String` | External References List |
| extraBeds | `Float` | Extra Beds |
| fBRevenue | `Float` | FB Revenue |
| fBRevenueRemaining | `Float` | F&B Revenue Remaining |
| faxId | `Float` | Fax ID |
| faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| feature | `String` | This stores the codes for the rooms features. Currently not used |
| financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| fixedCharge | `Float` | Not used. |
| fixedRateYN | `String` | Fixed Rate YN |
| folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| folioCloseDate | `Date` | Date the folio was changed to closed. |
| folioNumber | `String` | Folio Number |
| folioText1 | `String` | Folio Text1 |
| folioText2 | `String` | Folio Text2 |
| foreignCurrencyID | `String` | Foreign Currency ID |
| freeChild | `Float` | Free Child |
| frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| grossRateFuture | `Float` | Gross Rate Future |
| grossRatePast | `Float` | Gross Rate Past |
| groupName | `String` | Group Name |
| groupProfileARNumber | `Float` | Group Profile AR Number |
| groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| groupProfileClientID | `String` | Group Profile Client ID |
| groupProfileID | `Float` | Group Profile ID |
| groupProfileName | `String` | Group Profile Name |
| guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| guaranteecodeid | `String` | Guaranteecodeid |
| guestFirstName | `String` | Guest First Name |
| guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| guestSignature | `String` | Signature of the guest |
| guestStatus | `String` | Used for Police/Tourist Export |
| guestType | `String` | Guest Type |
| guestprofileid | `Float` | Guestprofileid |
| gueststatusid | `String` | Gueststatusid |
| guesttypeid | `String` | Guesttypeid |
| housekeepingServiceTime | `String` | Housekeeping Service Time |
| hurdle | `Float` | Hurdle |
| hurdleOverride | `String` | Hurdle Override |
| iDByMembershipClass | `String` | ID by Membership Class |
| iDByMembershipType | `String` | ID by Membership Type |
| individualCity | `String` | Guest Address. |
| individualCountry | `String` | Country of the guest |
| individualFirstName | `String` | Individual First Name |
| individualLastName | `String` | Individual Last Name |
| insertActionInstanceId | `Float` | Insert Action Instance ID |
| insertDate | `DateTime` | Insert Date |
| insertDateTime | `DateTime` | Insert DateTime |
| insertUser | `Float` | Insert User |
| intermediaryYn | `String` | Intermediary Y/N |
| internalAwardMembershipId | `Float` | Award Membership ID |
| internalBaseratecode | `String` | Baseratecode |
| internalBlockId | `Float` | Block ID. |
| internalCompanyprofileid | `Float` | Companyprofileid |
| internalGroupprofileid | `Float` | Groupprofileid |
| internalSourceprofileid | `Float` | Sourceprofileid |
| itemsQuantities | `String` | Items and Quantities |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyValidUntil | `Date` | Key Valid Until |
| lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| lastRoomNumber | `String` | Not used. |
| lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| leadTimeDays | `Float` | Lead Time for ordering |
| lengthOfStay | `Float` | Length of Stay |
| linkedArrivalDate | `DateTime` | Linked Arrival Date |
| linkedDepartureDate | `DateTime` | Linked Departure Date |
| linkedRoomType | `String` | Linked Room Type |
| listOfMembershipID | `String` | Membership ID |
| localBaseRateAmount | `Float` | Local Base Rate Amount |
| locationID | `String` | Internal ID to uniquely identify the Property |
| loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| mailYn | `String` | Mail Y/N |
| manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| marketCode | `String` | Market Code |
| marketid | `String` | Marketid |
| mcGenBeginDistrict | `String` | Mc Gen Begin District |
| mcGenBeginState | `String` | Mc Gen Begin State |
| mcGenEndDistrict | `String` | Mc Gen End District |
| mcGenEndState | `String` | Mc Gen End State |
| mcGenNextCountry | `String` | Mc Gen Next Country |
| mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| memberDescription | `String` | Member Description |
| memberLevel | `String` | Member Level |
| memberNumber | `String` | Member Number |
| membershipClass | `String` | Membership Class |
| membershipClassDescription | `String` | Membership Class Description |
| membershipCode | `String` | Membership Code |
| membershipId | `Float` | Membership ID |
| membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| name | `String` | Name |
| nameUsageType | `String` | Name Usage Type |
| nextCountry | `String` | Next Country |
| nextDestination | `String` | Country Specific Requirement for Nigeria. |
| numberOfRooms | `Float` | No of Rooms |
| operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| originOfBooking | `String` | Origin Of Booking |
| originalBaseRate | `Float` | Not used. |
| originalEndDate | `Date` | Original End Date |
| originalStartDate | `Date` | Original Start Date |
| ownerFfFlag | `String` | Owner Ff Flag |
| ownerOrFriendsFamily | `String` | Owner or Friends/Family |
| packageCode | `String` | Package Code |
| packageCodeDescription | `String` | Package Code Description |
| packageForecastGroup | `String` | Package Forecast Group |
| packageForecastGroupDescription | `String` | Package Forecast Group Description |
| parentReservationNameId | `Float` | Parent Resv Name ID |
| parentreservationid | `Float` | Parentreservationid |
| partAllotment | `String` | Part Allotment |
| partyCode | `String` | Party Code |
| paxNo | `Float` | Pax Number |
| paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| paymentMethod | `String` | Payment Method |
| paymentmethodid | `String` | Paymentmethodid |
| periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| phoneId | `Float` | Phone ID |
| physicalQuantity | `Float` | Physical Quantity |
| pickUpCarrierCode | `String` | Pick Up Carrier Code |
| pickUpDate | `Date` | Pick Up Date |
| pickUpStation | `String` | Pick Up Station |
| pickUpTransportNumber | `String` | Pick Up Transport Number |
| pickUpType | `String` | Pick Up Type |
| pickUpTypeDescription | `String` | Pick Up Type Description |
| pickUpTime | `String` | Pick-Up Time |
| pickupRequiredYN | `String` | Pickup Required YN |
| points | `Float` | Points |
| pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| postingAllowedYN | `String` | Posting Allowed YN |
| preArrReviewedDt | `DateTime` | This date flags if and when the record was reviewed from pre-arrival screen. |
| preArrReviewedUser | `Float` | User id who reviewed the record. |
| preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| preference | `String` | Preference |
| preferenceType | `String` | Preference Type |
| preferredRoomType | `String` | Preferred Room Type |
| previousCountry | `String` | Previous Country |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryShare | `String` | Primary Share |
| printRateYN | `String` | Print Rate YN |
| projectedFBRevenue | `Float` | Projected FB Revenue |
| projectedRoomRevenue | `Float` | Projected Room Revenue |
| projectedTotalRevenue | `Float` | Projected Total Revenue |
| promotionCode | `String` | Promotion Code |
| promotionDescription | `String` | Promotion Description |
| property | `String` | Indicates if the value set for the specific property. |
| pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| purgeDate | `DateTime` | Purge Date |
| purposeOfStay | `String` | Purpose of stay. |
| quantity | `Float` | Number of Rooms |
| queuePriority | `Float` | Queue priority of the reservation. |
| queueWaitTime | `Float` | Queue Wait Time |
| quoteId | `String` | Quote ID provided by external system. |
| rateAmount | `Float` | Rate Amount |
| rateCode | `String` | Rate Code |
| rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| rateTier | `Float` | Tier ID for the Rate Detail. |
| rateableValue | `Float` | Stay rateable value. |
| ratecodeid | `String` | Ratecodeid |
| rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| rdResvStatus | `String` | Rd Reservation Status |
| rdenBillingContactId | `Float` | Rden Billing Contact ID |
| rdenReservationContactId | `Float` | Rden Resv Contact ID |
| rdenReservationDate | `Date` | Rden Reservation Date |
| rdenResort | `String` | Rden Property |
| referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| registrationCardNo | `String` | Registration Card Number |
| registrationNumber | `Float` | Registration Number |
| reinstateDate | `DateTime` | Reinstate Date |
| repChannel | `String` | Reporting Channel |
| repChannelDescription | `String` | Reporting Channel Description |
| reportId | `String` | Report ID |
| resInsertSource | `String` | Reservation Insert Source |
| resInsertSourceType | `String` | Reservation Insert Source Type |
| reservationContactId | `Float` | Resv Contact ID |
| reservationDate | `DateTime` | Reservation Date |
| reservationNameID | `Float` | Reservation Name ID |
| reservationStatus | `String` | Reservation Status |
| reservationType | `String` | Reservation Type |
| reservationTypeDescription | `String` | Reservation Type Description |
| reservationid | `Float` | Reservationid |
| resort | `String` | Property |
| resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| restrictionOverride | `String` | Restriction Override |
| resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| resvNameid | `Float` | Reservation Nameid |
| resvNumber | `Float` | Not used in PMS currently. |
| resvcontactprofileid | `Float` | Resvcontactprofileid |
| revenueTypeCode | `String` | Revenue type (catering/rooms) |
| rhBillingContactId | `Float` | Rh Billing Contact ID |
| rhReservationContactId | `Float` | Rh Resv Contact ID |
| rhRoomFeatures | `String` | Rh Room Features |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| room | `String` | Room |
| roomCategory | `String` | Room Category |
| roomClass | `String` | Room Class |
| roomCost | `Float` | Room Cost |
| roomInstructions | `String` | Room Instructions |
| roomResort | `String` | Meeting Room Property |
| roomRevenue | `Float` | Room Revenue |
| roomRevenueRemaining | `Float` | Room Revenue Remaining |
| roomServiceTime | `String` | This is the Turndown room service time. |
| roomTypeDescription | `String` | Room Type Description |
| roomTypeToChargeCode | `String` | Room Type To Charge Code |
| roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| roomcategoryid | `String` | Roomcategoryid |
| roomid | `String` | Roomid |
| routingYN | `String` | Routing YN |
| scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| sguestName | `String` | Sguest Name |
| shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| shareId | `Float` | Share ID. |
| shareName | `String` | Share Name |
| sharePrcnt | `Float` | Not used. |
| shareSeqNumber | `Float` | Type of revenue |
| shareOfRateAmount | `Float` | Share of Rate Amount |
| sharedGuestName | `String` | Shared Guest Name |
| sharedProfileID | `Float` | Shared Profile ID |
| sharedReservationStatus | `String` | Shared Reservation Status |
| sharingYN | `String` | Sharing YN |
| sourceCity | `String` | Source City |
| sourceCode | `String` | Source Code |
| sourceCountry | `String` | Source Country |
| sourceName | `String` | Source Name |
| sourceProfileARNumber | `Float` | Source Profile AR Number |
| sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| sourceProfileIATANumber | `String` | Source Profile IATA Number |
| sourceProfileID | `Float` | Source Profile ID |
| sourceProfileName | `String` | Source Profile Name |
| sourceid | `String` | Sourceid |
| specialRequest | `String` | Special Request |
| specialRequestDescription | `String` | Special Request Description |
| spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| splitfromreservationid | `Float` | Splitfromreservationid |
| statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| stayRecordId | `Float` | Stay Record ID |
| suiteNumber | `String` | Suite Number |
| superSearchIndexText | `String` | Super Search Index Text |
| taRecordLocator | `String` | Ta Record Locator |
| taxExemptNumber | `String` | Tax exempt number on the profile |
| taxNumberOfStays | `Float` | Tax No of Stays |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| taxtypeid | `String` | Taxtypeid |
| tiad | `String` | Tiad |
| ticketNos | `String` | Ticket Nos |
| totalCostOfStay | `Float` | Total Cost of Stay |
| totalRevenue | `Float` | Total Revenue |
| totalRevenueRemaining | `Float` | Total Revenue Remaining |
| totalRoomRate | `Float` | Total Room Rate |
| trackItGroups | `String` | Track It Groups |
| trackItTypes | `String` | Track It Types |
| transactionid | `Float` | Transactionid |
| travelAgentCity | `String` | Travel Agent Address. |
| travelAgentCountry | `String` | Travel Agent Country |
| travelAgentID | `Float` | Travel Agent ID |
| travelAgentName | `String` | Travel Agent Name |
| travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| travelAgentProfileID | `Float` | Travel Agent Profile ID |
| travelAgentProfileName | `String` | Travel Agent Profile Name |
| truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| uDFC01 | `String` | UDFC01 |
| uDFC02 | `String` | UDFC02 |
| uDFC03 | `String` | UDFC03 |
| uDFC04 | `String` | UDFC04 |
| uDFC05 | `String` | UDFC05 |
| uDFC06 | `String` | UDFC06 |
| uDFC07 | `String` | UDFC07 |
| uDFC08 | `String` | UDFC08 |
| uDFC09 | `String` | UDFC09 |
| uDFC10 | `String` | UDFC10 |
| uDFC11 | `String` | UDFC11 |
| uDFC12 | `String` | UDFC12 |
| uDFC13 | `String` | UDFC13 |
| uDFC14 | `String` | UDFC14 |
| uDFC15 | `String` | UDFC15 |
| uDFC16 | `String` | UDFC16 |
| uDFC17 | `String` | UDFC17 |
| uDFC18 | `String` | UDFC18 |
| uDFC19 | `String` | UDFC19 |
| uDFC20 | `String` | UDFC20 |
| uDFC21 | `String` | UDFC21 |
| uDFC22 | `String` | UDFC22 |
| uDFC23 | `String` | UDFC23 |
| uDFC24 | `String` | UDFC24 |
| uDFC25 | `String` | UDFC25 |
| uDFC26 | `String` | UDFC26 |
| uDFC27 | `String` | UDFC27 |
| uDFC28 | `String` | UDFC28 |
| uDFC29 | `String` | UDFC29 |
| uDFC30 | `String` | UDFC30 |
| uDFC31 | `String` | UDFC31 |
| uDFC32 | `String` | UDFC32 |
| uDFC33 | `String` | UDFC33 |
| uDFC34 | `String` | UDFC34 |
| uDFC35 | `String` | UDFC35 |
| uDFC36 | `String` | UDFC36 |
| uDFC37 | `String` | UDFC37 |
| uDFC38 | `String` | UDFC38 |
| uDFC39 | `String` | UDFC39 |
| uDFC40 | `String` | UDFC40 |
| uDFD01 | `Date` | UDFD01 |
| uDFD02 | `Date` | UDFD02 |
| uDFD03 | `Date` | UDFD03 |
| uDFD04 | `Date` | UDFD04 |
| uDFD05 | `Date` | UDFD05 |
| uDFD06 | `Date` | UDFD06 |
| uDFD07 | `Date` | UDFD07 |
| uDFD08 | `Date` | UDFD08 |
| uDFD09 | `Date` | UDFD09 |
| uDFD10 | `Date` | UDFD10 |
| uDFD11 | `Date` | UDFD11 |
| uDFD12 | `Date` | UDFD12 |
| uDFD13 | `Date` | UDFD13 |
| uDFD14 | `Date` | UDFD14 |
| uDFD15 | `Date` | UDFD15 |
| uDFD16 | `Date` | UDFD16 |
| uDFD17 | `Date` | UDFD17 |
| uDFD18 | `Date` | UDFD18 |
| uDFD19 | `Date` | UDFD19 |
| uDFD20 | `Date` | UDFD20 |
| uDFN01 | `Float` | UDFN01 |
| uDFN02 | `Float` | UDFN02 |
| uDFN03 | `Float` | UDFN03 |
| uDFN04 | `Float` | UDFN04 |
| uDFN05 | `Float` | UDFN05 |
| uDFN06 | `Float` | UDFN06 |
| uDFN07 | `Float` | UDFN07 |
| uDFN08 | `Float` | UDFN08 |
| uDFN09 | `Float` | UDFN09 |
| uDFN10 | `Float` | UDFN10 |
| uDFN11 | `Float` | UDFN11 |
| uDFN12 | `Float` | UDFN12 |
| uDFN13 | `Float` | UDFN13 |
| uDFN14 | `Float` | UDFN14 |
| uDFN15 | `Float` | UDFN15 |
| uDFN16 | `Float` | UDFN16 |
| uDFN17 | `Float` | UDFN17 |
| uDFN18 | `Float` | UDFN18 |
| uDFN19 | `Float` | UDFN19 |
| uDFN20 | `Float` | UDFN20 |
| uDFN21 | `Float` | UDFN21 |
| uDFN22 | `Float` | UDFN22 |
| uDFN23 | `Float` | UDFN23 |
| uDFN24 | `Float` | UDFN24 |
| uDFN25 | `Float` | UDFN25 |
| uDFN26 | `Float` | UDFN26 |
| uDFN27 | `Float` | UDFN27 |
| uDFN28 | `Float` | UDFN28 |
| uDFN29 | `Float` | UDFN29 |
| uDFN30 | `Float` | UDFN30 |
| uDFN31 | `Float` | UDFN31 |
| uDFN32 | `Float` | UDFN32 |
| uDFN33 | `Float` | UDFN33 |
| uDFN34 | `Float` | UDFN34 |
| uDFN35 | `Float` | UDFN35 |
| uDFN36 | `Float` | UDFN36 |
| uDFN37 | `Float` | UDFN37 |
| uDFN38 | `Float` | UDFN38 |
| uDFN39 | `Float` | UDFN39 |
| uDFN40 | `Float` | UDFN40 |
| uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| updateDate | `DateTime` | Update Date |
| updateDatetime | `DateTime` | Update Datetime |
| updateUser | `Float` | Update User |
| updatedBy | `String` | Updated By |
| updatedByDefaultResort | `String` | Updated By Default Property |
| updatedDate | `Date` | Updated Date |
| updatedTime | `String` | Updated Time |
| upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| visaExpiryDate | `Date` | Visa Expiry Date |
| visaIssueDate | `Date` | Visa Issue Date |
| visaNumber | `String` | Visa Number |
| waitlistComment | `String` | Waitlist Comment |
| waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| waitlistPriority | `String` | Waitlist Priority |
| waitlistPriorityDescription | `String` | Waitlist Priority Description |
| waitlistReason | `String` | Waitlist Reason |
| waitlistReasonDescription | `String` | Waitlist Reason Description |
| waitlistpriorityid | `String` | Waitlistpriorityid |
| waitlistreasonid | `String` | Waitlistreasonid |
| walkInYN | `String` | Walk-In YN |
| yieldableYn | `String` | Yieldable Y/N |
| ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsToReservationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| accompaniedYN | `String` | Accompanied YN |
| accompanyingName | `String` | Accompanying guest names. |
| actualCheckInDateTime | `DateTime` | Actual Check In Date Time |
| actualCheckOutDateTime | `DateTime` | Actual Check Out Date Time |
| actualCheckInDate | `Date` | Actual Check-In Date |
| actualCheckInTime | `String` | Actual Check-In Time |
| actualCheckOutDate | `Date` | Actual Check-Out Date |
| actualCheckOutTime | `String` | Actual Check-Out Time |
| addressId | `Float` | Address ID |
| addresseeNameId | `Float` | Addressee Name ID |
| adults | `Float` | Adults |
| adultsTaxFree | `Float` | Adults Tax Free |
| advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| agencyprofileid | `Float` | Agencyprofileid |
| allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| allotmentid | `Float` | Block ID |
| amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| amenityLevelCode | `String` | Amenity Level Code |
| amountPercent | `Float` | Amount Percent |
| approvalAmount | `Float` | Approval Amount |
| approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| approvalCode | `String` | Approval Code |
| arrivalComments | `String` | Arrival Comments |
| arrivalDate | `Date` | Arrival Date |
| arrivalDateTime | `DateTime` | Arrival Date Time |
| arrivalEstimateTime | `Date` | Arrival Estimate Time |
| arrivalTime | `String` | Activity begin time |
| arrivaltransportid | `String` | Arrivaltransportid |
| attachedDate | `Date` | Attached Date |
| authorizedBillingYN | `String` | Not used. |
| authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| authorizerId | `Float` | Authorizer ID |
| autoCheckinYn | `String` | Auto Checkin Y/N |
| autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| autoSettleDays | `Float` | Auto Settle Days |
| autoSettleType | `String` | Auto Settle Type |
| autoSettleYN | `String` | Auto Settle YN |
| awardCode | `String` | Award Code |
| awardCode1 | `String` | Award code 1 |
| awardCode2 | `String` | Award code 2 |
| awardCode3 | `String` | Award code 3 |
| awardCode4 | `String` | Award Code 4 |
| awardCode5 | `String` | Award code 5 |
| awardMembershipID | `Float` | Award Membership ID |
| awardVoucher1 | `String` | Award Voucher number 1 |
| awardVoucher2 | `String` | Award Voucher number 2 |
| awardVoucher3 | `String` | Award Voucher number 3 |
| awardVoucher4 | `String` | Award Voucher number 4 |
| awardVoucher5 | `String` | Award Voucher number 5 |
| awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| awdUpgrTo | `String` | Room Type after the Upgrade Award |
| backToBackYN | `String` | Back To Back YN |
| balance | `Float` | Balance on the account. |
| baseRateAmount | `Float` | Base Rate Amount |
| baseRateCode | `String` | Base Rate Code |
| baseRateCurrencyCode | `String` | Base Rate Currency Code |
| basedOnRule | `String` | Based On Rule |
| baseratecurrencyid | `String` | Baseratecurrencyid |
| beginCity | `String` | Begin City |
| beginDatetime | `DateTime` | Begin Datetime |
| beginDistrict | `String` | Begin District |
| beginState | `String` | Begin State |
| beginSystemDateTime | `DateTime` | Stores the actual guest check in date and time. |
| billNumber | `String` | Bill Number |
| billingContact | `String` | Billing Contact |
| billingContactDisplayName | `String` | Billing Contact Display Name |
| billingContactId | `Float` | Billing Contact ID |
| billingContactName | `String` | Billing Contact Name |
| billingcontactprofileid | `Float` | Billing Contact Profile ID |
| blockCode | `String` | Block Code |
| blockCreateDate | `DateTime` | Block Create Date |
| blockID | `Float` | Block ID |
| blockName | `String` | Block Name |
| blockResort | `String` | Property this block belongs to. |
| blockStatus | `String` | Block Status |
| bonusCheckId | `Float` | Bonus Check ID |
| bookedRoomCategory | `String` | Booked Room Category |
| bookedroomcategoryid | `String` | Bookedroomcategoryid |
| businessDateCreated | `Date` | Business Date Created |
| businessDatetimeCreated | `DateTime` | Business Datetime Created |
| bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| cAutoPostAmount | `Float` | Central Auto Post Amount |
| cBaseRateAmount | `Float` | Central Base Rate Amount |
| cDiscountAmount | `Float` | C Discount Amount |
| cDiscountAmt | `Float` | C Discount Amt |
| cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFixedCharge | `Float` | Central Fixed Charge |
| cGrossRateAmount | `Float` | Central Gross Rate Amt |
| cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| cNetRoomAmount | `Float` | Central Net Room Amt |
| cOriginalBaseRate | `Float` | Central Original Base Rate |
| cPackageAmount | `Float` | Central Pkg Amt |
| cPackageTax | `Float` | Central Pkg Tax |
| cRateAmount | `Float` | C Rate Amount |
| cRoomCost | `Float` | Central Room Cost |
| cRoomTax | `Float` | Central Room Tax |
| cShareAmountOriginal | `Float` | Central Share Amount Original |
| cUpsellCharge | `Float` | Central Upsell Charge |
| cancelDate | `Date` | Cancel Date |
| cancelReason | `String` | Cancel Reason |
| cancelTime | `String` | Cancel Time |
| cancellationDate | `DateTime` | Cancellation Date |
| cancellationDatetime | `DateTime` | Cancellation Datetime |
| cancellationNumber | `String` | Cancellation Number |
| cancellationReasonDescription | `String` | Cancellation Reason Description |
| cancellationreasonid | `String` | Cancellationreasonid |
| cancelledBy | `String` | The user who canceled this Reservation. |
| cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| cardNumberByMembershipType | `String` | Card Number by Membership Type |
| centralApprovalAmount | `Float` | Central Approval Amount |
| centralCancelReason | `String` | Central Cancel Reason |
| centralCommissionCode | `String` | Central Commission Code |
| centralCommissionDescription | `String` | Central Commission Description |
| centralCreditLimit | `Float` | Central Credit Limit |
| centralDiscountReason | `String` | Central Discount Reason |
| centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| centralFBRevenue | `Float` | Central FB Revenue |
| centralGuestType | `String` | Central Guest Type |
| centralHurdle | `Float` | Central Hurdle |
| centralPackageCode | `String` | Central Package Code |
| centralPackageCodeDescription | `String` | Central Package Code Description |
| centralPackageForecastGroup | `String` | Central Package Forecast Group |
| centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| centralPaymentAmount | `Float` | Central Payment Amount |
| centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| centralPromotionDescription | `String` | Central Promotion Description |
| centralRateableValue | `Float` | Central Rateable Value |
| centralReservationType | `String` | Central Reservation Type |
| centralReservationTypeDescription | `String` | Central Reservation Type Description |
| centralRoomRevenue | `Float` | Central Room Revenue |
| centralRoomTypeCode | `String` | Central Room Type Code |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| centralSharedRoomRate | `Float` | Central Shared Room Rate |
| centralSpecialRequestDescription | `String` | Central Special Request Description |
| centralTaxType | `String` | Central Tax Type |
| centralTaxTypeDescription | `String` | Central Tax Type Description |
| centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| centralTotalRevenue | `Float` | Central Total Revenue |
| centralTotalRoomRate | `Float` | Central Total Room Rate |
| centralWaitlistPriority | `String` | Central Waitlist Priority |
| centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| centralWaitlistReason | `String` | Central Waitlist Reason |
| centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| channelDescription | `String` | Channel Description |
| channelOrderBy | `Float` | Channel Order By |
| channelid | `String` | Channelid |
| checkInInitiatedBy | `String` | Check In Initiated By |
| checkinDuration | `Float` | Duration in seconds to complete Check-In |
| childBucket1 | `Float` | Child Bucket 1 |
| childBucket4 | `Float` | Child Bucket 4 |
| childBucket5 | `Float` | Child Bucket 5 |
| children | `Float` | Children |
| childrenAgeGroup2 | `Float` | Children Age Group 2) |
| childrenAgeGroup3 | `Float` | Children Age Group 3) |
| childrenAges | `String` | Children Ages |
| commissionCode | `String` | Commission Code |
| commissionDescription | `String` | Commission Description |
| commissionHoldCode | `String` | Commission Hold Code |
| commissionPaid | `Float` | Commission Paid |
| commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| commissionableYN | `String` | Commissionable YN |
| commissionid | `String` | Commissionid |
| compHouse | `String` | Comp House |
| compTypeCode | `String` | Comp Type Code |
| companyCity | `String` | Company City |
| companyCountry | `String` | Company Country |
| companyID | `Float` | Company ID |
| companyName | `String` | Company Name |
| companyProfileCorporateID | `String` | Company Profile Corporate ID |
| companyProfileID | `Float` | Company Profile ID |
| complimentaryYN | `String` | Complimentary YN |
| compreasonid | `String` | Compreasonid |
| computedResvStatus | `String` | Calculated reservation status. |
| confirmationLegNumber | `Float` | Confirmation Leg Number. |
| confirmationNo | `String` | Shared Confirmation Number |
| consumerYn | `String` | Consumer Y/N |
| contactName | `String` | Contact Name; UDFC02 on reservation. |
| contactProfileID | `Float` | Contact Profile ID |
| contactProfileName | `String` | Contact Profile Name |
| createdBy | `String` | The name of the user who created the record. |
| createdByDefaultResort | `String` | Created By Default Property |
| createdDate | `Date` | Created Date |
| createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| creditCardAuthDate | `Date` | Credit Card Auth Date |
| creditCardId | `Float` | Credit Card ID |
| creditLimit | `Float` | Credit Limit |
| creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| cribs | `Float` | Cribs |
| currencyCode | `String` | Currency Code |
| customReferenceNumber | `String` | Custom Reference Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| deletedFlag | `String` | Deleted Flag |
| departtransportid | `String` | Departtransportid |
| departureComments | `String` | Departure Comments |
| departureDate | `Date` | Departure Date |
| departureDateTime | `Date` | Departure Date Time |
| departureTime | `String` | Departure Time |
| departureTransportCode | `String` | Departure Transport Code |
| departureTransportationYN | `String` | Departure Transportation YN |
| depositMaturityType | `String` | Stores the Deposit maturity preference. |
| detatchedDate | `Date` | Detatched Date |
| detatchedYN | `String` | Detatched YN |
| directBillVerifyResponse | `String` | Direct Bill Verify Response |
| directbillauthby | `Float` | Directbillauthby |
| discountAmount | `Float` | Discount Amount |
| discountAmt | `Float` | Discount Amount |
| discountPercent | `Float` | Discount Percentage. |
| discountPrcnt | `Float` | Discount Prcnt |
| discountReason | `String` | Discount Reason |
| discountReasonDescription | `String` | Discount Reason Description |
| discountreasonid | `String` | Discountreasonid |
| displayColor | `String` | Display Color |
| dmlSeqNumber | `Float` | Dml Sequence No |
| doNotMoveRoom | `String` | Do Not Move Room |
| doNotMoveYN | `String` | Do not move room flag. |
| dropOffCarrierCode | `String` | Drop Off Carrier Code |
| dropOffDate | `Date` | Drop Off Date |
| dropOffStation | `String` | Drop Off Station |
| dropOffTime | `String` | Drop Off Time |
| dropOffType | `String` | Drop Off Type |
| dropOffTypeDescription | `String` | Drop Off Type Description |
| eTRComments | `String` | Comments related to Estimated Time of Return. |
| effectiveRateAmount | `Float` | Not used. |
| eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| emailAddress | `String` | Email Address |
| emailFolioYn | `String` | Email Folio Y/N |
| emailId | `Float` | Email ID |
| emailYn | `String` | Email Y/N |
| endCity | `String` | End City |
| endDatetime | `DateTime` | End Datetime |
| endDistrict | `String` | End District |
| endState | `String` | End State |
| endbusinessdate | `Date` | Endbusinessdate |
| entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| estimatedDepartureTime | `Date` | Estimated Departure Time |
| eventId | `Float` | Event ID |
| exchangePostingType | `String` | Exchange Posting Type |
| exchangeRate | `Float` | Exchange Rate |
| excludeFromAutoAuthorizationYN | `String` | Exclude From Auto Authorization YN |
| expectedTimeOfReturnETR | `DateTime` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| extSegNo | `Float` | Not used |
| extSeqNumber | `Float` | Not used |
| extensionId | `Float` | Internal extension number for the main reservation |
| externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| externalReference | `String` | External Reference |
| externalReferencesList | `String` | External References List |
| extraBeds | `Float` | Extra Beds |
| fBRevenue | `Float` | FB Revenue |
| fBRevenueRemaining | `Float` | F&B Revenue Remaining |
| faxId | `Float` | Fax ID |
| faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| feature | `String` | This stores the codes for the rooms features. Currently not used |
| financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| fixedCharge | `Float` | Not used. |
| fixedRateYN | `String` | Fixed Rate YN |
| folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| folioCloseDate | `Date` | Date the folio was changed to closed. |
| folioNumber | `String` | Folio Number |
| folioText1 | `String` | Folio Text1 |
| folioText2 | `String` | Folio Text2 |
| foreignCurrencyID | `String` | Foreign Currency ID |
| freeChild | `Float` | Free Child |
| frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| grossRateFuture | `Float` | Gross Rate Future |
| grossRatePast | `Float` | Gross Rate Past |
| groupName | `String` | Group Name |
| groupProfileARNumber | `Float` | Group Profile AR Number |
| groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| groupProfileClientID | `String` | Group Profile Client ID |
| groupProfileID | `Float` | Group Profile ID |
| groupProfileName | `String` | Group Profile Name |
| guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| guaranteecodeid | `String` | Guaranteecodeid |
| guestFirstName | `String` | Guest First Name |
| guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| guestSignature | `String` | Signature of the guest |
| guestStatus | `String` | Used for Police/Tourist Export |
| guestType | `String` | Guest Type |
| guestprofileid | `Float` | Guestprofileid |
| gueststatusid | `String` | Gueststatusid |
| guesttypeid | `String` | Guesttypeid |
| housekeepingServiceTime | `String` | Housekeeping Service Time |
| hurdle | `Float` | Hurdle |
| hurdleOverride | `String` | Hurdle Override |
| iDByMembershipClass | `String` | ID by Membership Class |
| iDByMembershipType | `String` | ID by Membership Type |
| individualCity | `String` | Guest Address. |
| individualCountry | `String` | Country of the guest |
| individualFirstName | `String` | Individual First Name |
| individualLastName | `String` | Individual Last Name |
| insertActionInstanceId | `Float` | Insert Action Instance ID |
| insertDate | `DateTime` | Insert Date |
| insertDateTime | `DateTime` | Insert DateTime |
| insertUser | `Float` | Insert User |
| intermediaryYn | `String` | Intermediary Y/N |
| internalAwardMembershipId | `Float` | Award Membership ID |
| internalBaseratecode | `String` | Baseratecode |
| internalBlockId | `Float` | Block ID. |
| internalCompanyprofileid | `Float` | Companyprofileid |
| internalGroupprofileid | `Float` | Groupprofileid |
| internalSourceprofileid | `Float` | Sourceprofileid |
| itemsQuantities | `String` | Items and Quantities |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyValidUntil | `Date` | Key Valid Until |
| lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| lastRoomNumber | `String` | Not used. |
| lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| leadTimeDays | `Float` | Lead Time for ordering |
| lengthOfStay | `Float` | Length of Stay |
| linkedArrivalDate | `DateTime` | Linked Arrival Date |
| linkedDepartureDate | `DateTime` | Linked Departure Date |
| linkedRoomType | `String` | Linked Room Type |
| listOfMembershipID | `String` | Membership ID |
| localBaseRateAmount | `Float` | Local Base Rate Amount |
| locationID | `String` | Internal ID to uniquely identify the Property |
| loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| mailYn | `String` | Mail Y/N |
| manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| marketCode | `String` | Market Code |
| marketid | `String` | Marketid |
| mcGenBeginDistrict | `String` | Mc Gen Begin District |
| mcGenBeginState | `String` | Mc Gen Begin State |
| mcGenEndDistrict | `String` | Mc Gen End District |
| mcGenEndState | `String` | Mc Gen End State |
| mcGenNextCountry | `String` | Mc Gen Next Country |
| mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| memberDescription | `String` | Member Description |
| memberLevel | `String` | Member Level |
| memberNumber | `String` | Member Number |
| membershipClass | `String` | Membership Class |
| membershipClassDescription | `String` | Membership Class Description |
| membershipCode | `String` | Membership Code |
| membershipId | `Float` | Membership ID |
| membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| name | `String` | Name |
| nameUsageType | `String` | Name Usage Type |
| nextCountry | `String` | Next Country |
| nextDestination | `String` | Country Specific Requirement for Nigeria. |
| numberOfRooms | `Float` | No of Rooms |
| operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| originOfBooking | `String` | Origin Of Booking |
| originalBaseRate | `Float` | Not used. |
| originalEndDate | `Date` | Original End Date |
| originalStartDate | `Date` | Original Start Date |
| ownerFfFlag | `String` | Owner Ff Flag |
| ownerOrFriendsFamily | `String` | Owner or Friends/Family |
| packageCode | `String` | Package Code |
| packageCodeDescription | `String` | Package Code Description |
| packageForecastGroup | `String` | Package Forecast Group |
| packageForecastGroupDescription | `String` | Package Forecast Group Description |
| parentReservationNameId | `Float` | Parent Resv Name ID |
| parentreservationid | `Float` | Parentreservationid |
| partAllotment | `String` | Part Allotment |
| partyCode | `String` | Party Code |
| paxNo | `Float` | Pax Number |
| paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| paymentMethod | `String` | Payment Method |
| paymentmethodid | `String` | Paymentmethodid |
| periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| phoneId | `Float` | Phone ID |
| physicalQuantity | `Float` | Physical Quantity |
| pickUpCarrierCode | `String` | Pick Up Carrier Code |
| pickUpDate | `Date` | Pick Up Date |
| pickUpStation | `String` | Pick Up Station |
| pickUpTransportNumber | `String` | Pick Up Transport Number |
| pickUpType | `String` | Pick Up Type |
| pickUpTypeDescription | `String` | Pick Up Type Description |
| pickUpTime | `String` | Pick-Up Time |
| pickupRequiredYN | `String` | Pickup Required YN |
| points | `Float` | Points |
| pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| postingAllowedYN | `String` | Posting Allowed YN |
| preArrReviewedDt | `DateTime` | This date flags if and when the record was reviewed from pre-arrival screen. |
| preArrReviewedUser | `Float` | User id who reviewed the record. |
| preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| preference | `String` | Preference |
| preferenceType | `String` | Preference Type |
| preferredRoomType | `String` | Preferred Room Type |
| previousCountry | `String` | Previous Country |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryShare | `String` | Primary Share |
| printRateYN | `String` | Print Rate YN |
| projectedFBRevenue | `Float` | Projected FB Revenue |
| projectedRoomRevenue | `Float` | Projected Room Revenue |
| projectedTotalRevenue | `Float` | Projected Total Revenue |
| promotionCode | `String` | Promotion Code |
| promotionDescription | `String` | Promotion Description |
| property | `String` | Indicates if the value set for the specific property. |
| pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| purgeDate | `DateTime` | Purge Date |
| purposeOfStay | `String` | Purpose of stay. |
| quantity | `Float` | Number of Rooms |
| queuePriority | `Float` | Queue priority of the reservation. |
| queueWaitTime | `Float` | Queue Wait Time |
| quoteId | `String` | Quote ID provided by external system. |
| rateAmount | `Float` | Rate Amount |
| rateCode | `String` | Rate Code |
| rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| rateTier | `Float` | Tier ID for the Rate Detail. |
| rateableValue | `Float` | Stay rateable value. |
| ratecodeid | `String` | Ratecodeid |
| rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| rdResvStatus | `String` | Rd Reservation Status |
| rdenBillingContactId | `Float` | Rden Billing Contact ID |
| rdenReservationContactId | `Float` | Rden Resv Contact ID |
| rdenReservationDate | `Date` | Rden Reservation Date |
| rdenResort | `String` | Rden Property |
| referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| registrationCardNo | `String` | Registration Card Number |
| registrationNumber | `Float` | Registration Number |
| reinstateDate | `DateTime` | Reinstate Date |
| repChannel | `String` | Reporting Channel |
| repChannelDescription | `String` | Reporting Channel Description |
| reportId | `String` | Report ID |
| resInsertSource | `String` | Reservation Insert Source |
| resInsertSourceType | `String` | Reservation Insert Source Type |
| reservationContactId | `Float` | Resv Contact ID |
| reservationDate | `DateTime` | Reservation Date |
| reservationNameID | `Float` | Reservation Name ID |
| reservationStatus | `String` | Reservation Status |
| reservationType | `String` | Reservation Type |
| reservationTypeDescription | `String` | Reservation Type Description |
| reservationid | `Float` | Reservationid |
| resort | `String` | Property |
| resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| restrictionOverride | `String` | Restriction Override |
| resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| resvNameid | `Float` | Reservation Nameid |
| resvNumber | `Float` | Not used in PMS currently. |
| resvcontactprofileid | `Float` | Resvcontactprofileid |
| revenueTypeCode | `String` | Revenue type (catering/rooms) |
| rhBillingContactId | `Float` | Rh Billing Contact ID |
| rhReservationContactId | `Float` | Rh Resv Contact ID |
| rhRoomFeatures | `String` | Rh Room Features |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| room | `String` | Room |
| roomCategory | `String` | Room Category |
| roomClass | `String` | Room Class |
| roomCost | `Float` | Room Cost |
| roomInstructions | `String` | Room Instructions |
| roomResort | `String` | Meeting Room Property |
| roomRevenue | `Float` | Room Revenue |
| roomRevenueRemaining | `Float` | Room Revenue Remaining |
| roomServiceTime | `String` | This is the Turndown room service time. |
| roomTypeDescription | `String` | Room Type Description |
| roomTypeToChargeCode | `String` | Room Type To Charge Code |
| roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| roomcategoryid | `String` | Roomcategoryid |
| roomid | `String` | Roomid |
| routingYN | `String` | Routing YN |
| scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| sguestName | `String` | Sguest Name |
| shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| shareId | `Float` | Share ID. |
| shareName | `String` | Share Name |
| sharePrcnt | `Float` | Not used. |
| shareSeqNumber | `Float` | Type of revenue |
| shareOfRateAmount | `Float` | Share of Rate Amount |
| sharedGuestName | `String` | Shared Guest Name |
| sharedProfileID | `Float` | Shared Profile ID |
| sharedReservationStatus | `String` | Shared Reservation Status |
| sharingYN | `String` | Sharing YN |
| sourceCity | `String` | Source City |
| sourceCode | `String` | Source Code |
| sourceCountry | `String` | Source Country |
| sourceName | `String` | Source Name |
| sourceProfileARNumber | `Float` | Source Profile AR Number |
| sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| sourceProfileIATANumber | `String` | Source Profile IATA Number |
| sourceProfileID | `Float` | Source Profile ID |
| sourceProfileName | `String` | Source Profile Name |
| sourceid | `String` | Sourceid |
| specialRequest | `String` | Special Request |
| specialRequestDescription | `String` | Special Request Description |
| spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| splitfromreservationid | `Float` | Splitfromreservationid |
| statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| stayRecordId | `Float` | Stay Record ID |
| suiteNumber | `String` | Suite Number |
| superSearchIndexText | `String` | Super Search Index Text |
| taRecordLocator | `String` | Ta Record Locator |
| taxExemptNumber | `String` | Tax exempt number on the profile |
| taxNumberOfStays | `Float` | Tax No of Stays |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| taxtypeid | `String` | Taxtypeid |
| tiad | `String` | Tiad |
| ticketNos | `String` | Ticket Nos |
| totalCostOfStay | `Float` | Total Cost of Stay |
| totalRevenue | `Float` | Total Revenue |
| totalRevenueRemaining | `Float` | Total Revenue Remaining |
| totalRoomRate | `Float` | Total Room Rate |
| trackItGroups | `String` | Track It Groups |
| trackItTypes | `String` | Track It Types |
| transactionid | `Float` | Transactionid |
| travelAgentCity | `String` | Travel Agent Address. |
| travelAgentCountry | `String` | Travel Agent Country |
| travelAgentID | `Float` | Travel Agent ID |
| travelAgentName | `String` | Travel Agent Name |
| travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| travelAgentProfileID | `Float` | Travel Agent Profile ID |
| travelAgentProfileName | `String` | Travel Agent Profile Name |
| truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| uDFC01 | `String` | UDFC01 |
| uDFC02 | `String` | UDFC02 |
| uDFC03 | `String` | UDFC03 |
| uDFC04 | `String` | UDFC04 |
| uDFC05 | `String` | UDFC05 |
| uDFC06 | `String` | UDFC06 |
| uDFC07 | `String` | UDFC07 |
| uDFC08 | `String` | UDFC08 |
| uDFC09 | `String` | UDFC09 |
| uDFC10 | `String` | UDFC10 |
| uDFC11 | `String` | UDFC11 |
| uDFC12 | `String` | UDFC12 |
| uDFC13 | `String` | UDFC13 |
| uDFC14 | `String` | UDFC14 |
| uDFC15 | `String` | UDFC15 |
| uDFC16 | `String` | UDFC16 |
| uDFC17 | `String` | UDFC17 |
| uDFC18 | `String` | UDFC18 |
| uDFC19 | `String` | UDFC19 |
| uDFC20 | `String` | UDFC20 |
| uDFC21 | `String` | UDFC21 |
| uDFC22 | `String` | UDFC22 |
| uDFC23 | `String` | UDFC23 |
| uDFC24 | `String` | UDFC24 |
| uDFC25 | `String` | UDFC25 |
| uDFC26 | `String` | UDFC26 |
| uDFC27 | `String` | UDFC27 |
| uDFC28 | `String` | UDFC28 |
| uDFC29 | `String` | UDFC29 |
| uDFC30 | `String` | UDFC30 |
| uDFC31 | `String` | UDFC31 |
| uDFC32 | `String` | UDFC32 |
| uDFC33 | `String` | UDFC33 |
| uDFC34 | `String` | UDFC34 |
| uDFC35 | `String` | UDFC35 |
| uDFC36 | `String` | UDFC36 |
| uDFC37 | `String` | UDFC37 |
| uDFC38 | `String` | UDFC38 |
| uDFC39 | `String` | UDFC39 |
| uDFC40 | `String` | UDFC40 |
| uDFD01 | `Date` | UDFD01 |
| uDFD02 | `Date` | UDFD02 |
| uDFD03 | `Date` | UDFD03 |
| uDFD04 | `Date` | UDFD04 |
| uDFD05 | `Date` | UDFD05 |
| uDFD06 | `Date` | UDFD06 |
| uDFD07 | `Date` | UDFD07 |
| uDFD08 | `Date` | UDFD08 |
| uDFD09 | `Date` | UDFD09 |
| uDFD10 | `Date` | UDFD10 |
| uDFD11 | `Date` | UDFD11 |
| uDFD12 | `Date` | UDFD12 |
| uDFD13 | `Date` | UDFD13 |
| uDFD14 | `Date` | UDFD14 |
| uDFD15 | `Date` | UDFD15 |
| uDFD16 | `Date` | UDFD16 |
| uDFD17 | `Date` | UDFD17 |
| uDFD18 | `Date` | UDFD18 |
| uDFD19 | `Date` | UDFD19 |
| uDFD20 | `Date` | UDFD20 |
| uDFN01 | `Float` | UDFN01 |
| uDFN02 | `Float` | UDFN02 |
| uDFN03 | `Float` | UDFN03 |
| uDFN04 | `Float` | UDFN04 |
| uDFN05 | `Float` | UDFN05 |
| uDFN06 | `Float` | UDFN06 |
| uDFN07 | `Float` | UDFN07 |
| uDFN08 | `Float` | UDFN08 |
| uDFN09 | `Float` | UDFN09 |
| uDFN10 | `Float` | UDFN10 |
| uDFN11 | `Float` | UDFN11 |
| uDFN12 | `Float` | UDFN12 |
| uDFN13 | `Float` | UDFN13 |
| uDFN14 | `Float` | UDFN14 |
| uDFN15 | `Float` | UDFN15 |
| uDFN16 | `Float` | UDFN16 |
| uDFN17 | `Float` | UDFN17 |
| uDFN18 | `Float` | UDFN18 |
| uDFN19 | `Float` | UDFN19 |
| uDFN20 | `Float` | UDFN20 |
| uDFN21 | `Float` | UDFN21 |
| uDFN22 | `Float` | UDFN22 |
| uDFN23 | `Float` | UDFN23 |
| uDFN24 | `Float` | UDFN24 |
| uDFN25 | `Float` | UDFN25 |
| uDFN26 | `Float` | UDFN26 |
| uDFN27 | `Float` | UDFN27 |
| uDFN28 | `Float` | UDFN28 |
| uDFN29 | `Float` | UDFN29 |
| uDFN30 | `Float` | UDFN30 |
| uDFN31 | `Float` | UDFN31 |
| uDFN32 | `Float` | UDFN32 |
| uDFN33 | `Float` | UDFN33 |
| uDFN34 | `Float` | UDFN34 |
| uDFN35 | `Float` | UDFN35 |
| uDFN36 | `Float` | UDFN36 |
| uDFN37 | `Float` | UDFN37 |
| uDFN38 | `Float` | UDFN38 |
| uDFN39 | `Float` | UDFN39 |
| uDFN40 | `Float` | UDFN40 |
| uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| updateDate | `DateTime` | Update Date |
| updateDatetime | `DateTime` | Update Datetime |
| updateUser | `Float` | Update User |
| updatedBy | `String` | Updated By |
| updatedByDefaultResort | `String` | Updated By Default Property |
| updatedDate | `Date` | Updated Date |
| updatedTime | `String` | Updated Time |
| upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| visaExpiryDate | `Date` | Visa Expiry Date |
| visaIssueDate | `Date` | Visa Issue Date |
| visaNumber | `String` | Visa Number |
| waitlistComment | `String` | Waitlist Comment |
| waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| waitlistPriority | `String` | Waitlist Priority |
| waitlistPriorityDescription | `String` | Waitlist Priority Description |
| waitlistReason | `String` | Waitlist Reason |
| waitlistReasonDescription | `String` | Waitlist Reason Description |
| waitlistpriorityid | `String` | Waitlistpriorityid |
| waitlistreasonid | `String` | Waitlistreasonid |
| walkInYN | `String` | Walk-In YN |
| yieldableYn | `String` | Yieldable Y/N |
| ymCode | `String` | Ym Code |

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

### FinancialTransactionDetailsQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| financialtransDetailsArLedCredit | `FloatInput` | AR Ledger Credit<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsArLedDebit | `FloatInput` | AR Ledger Debit<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsArState | `StringInput` | AR State |
| financialtransDetailsArNumber | `FloatInput` | Account Code<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsAccountid | `FloatInput` | Accountid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsArticleId | `FloatInput` | Article ID<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsAuthemployeeid | `FloatInput` | Authemployeeid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsBonusCheckId | `FloatInput` | Bonus Check ID<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsBusinessDate | `DateInput` | Business Date<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsCXchangeDate | `DateInput` | Central Xchange Date<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsCXchangeRate | `FloatInput` | Central Xchange Rate<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsCashierId | `FloatInput` | Cashier ID<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsChainCode | `StringInput` | Chain Code<br>`@conditionalInputPair(pair: 1)` |
| financialtransDetailsChequeNumber | `StringInput` | Check Number<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsClosureNo | `FloatInput` | Closure Number<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsComplinktranscodeid | `StringInput` | Complinktranscodeid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| financialtransDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference.<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence.<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsFintransactionid | `FloatInput` | Fintransactionid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsFintransid | `FloatInput` | Fintransid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsBillNo | `FloatInput` | Folio Number<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsFolioView | `FloatInput` | Folio View<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsFolioid | `FloatInput` | Folioid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsFromResvId | `FloatInput` | From Resv ID<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsFtSubtype | `StringInput` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| financialtransDetailsGuestAccountCredit | `FloatInput` | Guest Account Ledger Credit<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted.<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsInsertDate | `DateTimeInput` | Insert Date<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsArticleid | `FloatInput` | Articleid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsBusinessdate | `DateInput` | Businessdate<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsCashierid | `FloatInput` | Cashierid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsFolioNo | `FloatInput` | Internal Window ID<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsInvoiceNo | `FloatInput` | Invoice Number<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsLinkTrxNo | `FloatInput` | Link Transaction No<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsNameId | `FloatInput` | Name ID<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| financialtransDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsOriginalRoom | `StringInput` | Original Room<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsOriginalresvid | `FloatInput` | Originalresvid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsProduct | `StringInput` | Package<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsPackageCredit | `FloatInput` | Credit amount on the guest package account. |
| financialtransDetailsPackageDebit | `FloatInput` | Debit amount on the guest package account |
| financialtransDetailsPackagelinkfintransid | `FloatInput` | Packagelinkfintransid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsParentfintransid | `FloatInput` | Parentfintransid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsPostitNo | `FloatInput` | Postit Number<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsProductid | `StringInput` | Productid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsProfileid | `FloatInput` | Profileid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsResort | `StringInput` | Code to uniquely identify the Property<br>`@conditionalInputPair(pair: 1)` |
| financialtransDetailsRateCode | `StringInput` | Rate Code<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsRatecodeid | `StringInput` | Ratecodeid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| financialtransDetailsReservationid | `FloatInput` | Reservationid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsRoom | `StringInput` | Room Number<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsRoomid | `StringInput` | Roomid<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting.<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests.<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsTaxElements | `StringInput` | Tax Elements |
| financialtransDetailsTcGroup | `StringInput` | Transaction Code Group |
| financialtransDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| financialtransDetailsTranActionId | `FloatInput` | Tran Action ID<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsTranscodeid | `StringInput` | Transaction Code<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsTrxDate | `DateInput` | Transaction Date<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsTrxNoAddedBy | `FloatInput` | Transaction Number Added By<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsResvNameId | `FloatInput` | Transaction Reservation Name ID<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsTrxCode | `StringInput` | Transaction Code |
| financialtransDetailsTrxNo | `FloatInput` | Trx Number<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsTrxNoAgainstPackage | `FloatInput` | Trx Number Against Package<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted.<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsTrxNoHeader | `FloatInput` | Transaction No Header<br>`@conditionalInputPair(pair: 2)` |
| financialtransDetailsAuthorizerId | `FloatInput` | User ID<br>`@conditionalInputPair(pair: 2)` |
| eventpostingDetailsBookId | `FloatInput` | Book ID |
| eventpostingDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| eventpostingDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| eventpostingDetailsEvPostId | `FloatInput` | Event Post ID Primary Key |
| eventpostingDetailsEventId | `FloatInput` | Event ID |
| eventpostingDetailsEventpostingid | `FloatInput` | Eventpostingid |
| eventpostingDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| eventpostingDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| eventpostingDetailsPostedById | `FloatInput` | Posted By ID |
| eventpostingDetailsResort | `StringInput` | Code to uniquely identify the Property |
| eventpostingDetailsPostedBy | `StringInput` | Resource Type |
| eventpostingDetailsRevenueType | `StringInput` | Revenue Type |
| resortbudgetforecastDetailsAccountingYear | `FloatInput` | Accounting Year. |
| resortbudgetforecastDetailsBudgetCodeType | `StringInput` | Budget Code |
| resortbudgetforecastDetailsBudgetType | `StringInput` | Budget Type |
| resortbudgetforecastDetailsBudgetCodeValue | `StringInput` | Budget Code. Can be either Market Code Transaction Code or Custom Code. Depends on field Budget Code Type. |
| resortbudgetforecastDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortbudgetforecastDetailsEndDate | `DateInput` | End Date |
| resortbudgetforecastDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortbudgetforecastDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| resortbudgetforecastDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortbudgetforecastDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resortbudgetforecastDetailsStartDate | `DateInput` | Start Date |
| expmapfintrxcodesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| expmapfintrxcodesDetailsExpMappingId | `FloatInput` | Exp Mapping ID |
| expmapfintrxcodesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| expmapfintrxcodesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| expmapfintrxcodesDetailsMappingCode | `StringInput` | Code for the mapping code. |
| expmapfintrxcodesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| expmapfintrxcodesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| expmappaymethDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| expmappaymethDetailsExpMappingId | `FloatInput` | Exp Mapping ID |
| expmappaymethDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| expmappaymethDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| expmappaymethDetailsMappingCode | `StringInput` | Code for the mapping code. |
| expmappaymethDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| expmappaymethDetailsResort | `StringInput` | Code to uniquely identify the Property |
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
| articleDetailsArticleId | `FloatInput` | Article ID |
| articleDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| articleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| articleDetailsArticleid | `FloatInput` | Articleid |
| articleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| articleDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| articleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| articleDetailsResort | `StringInput` | Property |
| calendarperiodDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| calendarperiodDetailsEndDate | `DateInput` | End Date |
| calendarperiodDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| calendarperiodDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| calendarperiodDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| calendarperiodDetailsCode | `StringInput` | Period Code |
| calendarperiodDetailsPeriodScope | `StringInput` | Indicates Scope of the period. Eg. QUARTER - MONTH -WEEK. Used primarily in OBI. |
| calendarperiodDetailsPeriodTypeDesc | `StringInput` | Period Type Description |
| calendarperiodDetailsResort | `StringInput` | Code to uniquely identify the Property |
| calendarperiodDetailsStartDate | `DateInput` | Start Date |
| calendarperiodDetailsYearId | `FloatInput` | Year ID |
| calendarperiodDetailsYearsetupid | `FloatInput` | Yearsetupid |
| cashierDetailsInactiveflag | `StringInput` | Active YN |
| cashierDetailsCashierid | `FloatInput` | Cashierid |
| cashierDetailsChainCode | `StringInput` | Chain Code |
| cashierDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| cashierDetailsInterfaceCashierYn | `StringInput` | Decides whether the cashier number is used in interfaces or not. The interface cashiers cannot have numbers more than 999. |
| cashierDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| cashierDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| cashierDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| cashierDetailsCashierId | `FloatInput` | Payments-Cashier Code |
| cashierDetailsResort | `StringInput` | Property |
| employeeDetailsAppUser | `StringInput` | Agent |
| employeeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| employeeDetailsDefCashierId | `FloatInput` | Cashier ID for the User |
| employeeDetailsDefaultResort | `StringInput` | Stores resort name to which user will log in every time |
| employeeDetailsEmployeeid | `FloatInput` | Employeeid |
| employeeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| employeeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| employeeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| employeeDetailsPersonNameId | `FloatInput` | Foreign key to NAME table that links this USER to an Employee |
| employeeDetailsSrepCode | `StringInput` | Primary Rooms Owner Code |
| employeeDetailsAppUserId | `FloatInput` | User ID |
| expmappackagecodesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| expmappackagecodesDetailsExpMappingId | `FloatInput` | Exp Mapping ID |
| expmappackagecodesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| expmappackagecodesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| expmappackagecodesDetailsMappingCode | `StringInput` | Code for the mapping code. |
| expmappackagecodesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| expmappackagecodesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| financialperiodDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| financialperiodDetailsEndDate | `DateInput` | End Date |
| financialperiodDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| financialperiodDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| financialperiodDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| financialperiodDetailsCode | `StringInput` | Period Code |
| financialperiodDetailsPeriodScope | `StringInput` | Indicates Scope of the period. Eg. QUARTER - MONTH -WEEK. Used primarily in OBI. |
| financialperiodDetailsPeriodType | `StringInput` | Period Type |
| financialperiodDetailsPeriodsetupid | `FloatInput` | Periodsetupid |
| financialperiodDetailsResort | `StringInput` | Code to uniquely identify the Property |
| financialperiodDetailsStartDate | `DateInput` | Start Date |
| financialperiodDetailsYearId | `FloatInput` | Year ID |
| foliotaxDetailsAccountCode | `FloatInput` | Account Code |
| foliotaxDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| foliotaxDetailsAssociatedBillNo | `StringInput` | Associated Bill Number |
| foliotaxDetailsAssociatedSeqNo | `FloatInput` | Self referencing sequence number to gather information for other operations. |
| foliotaxDetailsBillGenerationDate | `DateInput` | Bill Generation Date |
| foliotaxDetailsBillNo | `FloatInput` | Bill Number |
| foliotaxDetailsBillPaymentTrxNo | `FloatInput` | Bill Payment Transaction No |
| foliotaxDetailsBillPrefix | `StringInput` | Bill Prefix |
| foliotaxDetailsBillSeqNo | `FloatInput` | Bill Sequence Number |
| foliotaxDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| foliotaxDetailsClTrxNo | `FloatInput` | Internal number given to the direct bill payment in financial_transactions. |
| foliotaxDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| foliotaxDetailsFolioAttachmentLinkId | `FloatInput` | Folio Attachment Link ID |
| foliotaxDetailsFolioNo | `FloatInput` | Folio Number |
| foliotaxDetailsFolioType | `StringInput` | Folio Type |
| foliotaxDetailsInsTimestamp | `DateTimeInput` | Timestamp to capture the exact order of inserts. |
| foliotaxDetailsInsertDate | `DateTimeInput` | Insert Date |
| foliotaxDetailsInvoiceNo | `FloatInput` | Invoice Number |
| foliotaxDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| foliotaxDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| foliotaxDetailsNameId | `FloatInput` | Name ID |
| foliotaxDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| foliotaxDetailsPayeeName | `StringInput` | Payee Name used for signature generation. |
| foliotaxDetailsPostitNo | `FloatInput` | Postit Sequence Number |
| foliotaxDetailsResort | `StringInput` | Code to uniquely identify the Property |
| foliotaxDetailsResvNameId | `FloatInput` | Resv Name ID |
| foliotaxDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| foliotaxDetailsSeqNo | `FloatInput` | Sequence No |
| foreigncurrencyDetailsCurrencyCode | `StringInput` | Currency Code |
| foreigncurrencyDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| foreigncurrencyDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| foreigncurrencyDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| invoicepaymentDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| invoicepaymentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| invoicepaymentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| invoicepaymentDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| invoicepaymentDetailsPaymentApplicationId | `FloatInput` | Unique Sequence id for each payment applications. |
| invoicepaymentDetailsResort | `StringInput` | Code to uniquely identify the Property |
| profileallDetailsNameId | `FloatInput` | The primary key for this table. |
| profileallDetailsActiveYn | `StringInput` | Profile is active or not. |
| profileallDetailsCrsNameid | `FloatInput` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |
| profileallDetailsChainCode | `StringInput` | Chain Code |
| profileallDetailsNameCode | `StringInput` | The unique key of this name stores IATA# Company # etc. |
| profileallDetailsCompanyGroupId | `StringInput` | The company group or company group user ID in hierarchical format |
| profileallDetailsContactFlag | `StringInput` | Used in S&C Module. |
| profileallDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileallDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |
| profileallDetailsLast | `StringInput` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| profileallDetailsHistoryYn | `StringInput` | Keep guest in history Y/N |
| profileallDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |
| profileallDetailsIndexName | `StringInput` | Index Name |
| profileallDetailsOrganizationId | `FloatInput` | Organization ID |
| profileallDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileallDetailsNameType | `StringInput` | The type of Profile. |
| profileallDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileallDetailsProfileId | `FloatInput` | The primary key for this table. |
| profileallDetailsProfileType | `StringInput` | The type of Profile. |
| profileallDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileallDetailsCompany | `StringInput` | This column store the Name of the Company Profiles. |
| profileallDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileallDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileallDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileallDetailsSrepCode | `StringInput` | Used in QMS Module |
| profileallDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileallDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| ratecodeDetailsBaseRateCode | `StringInput` | Base Rate Code |
| ratecodeDetailsBeginBookingDate | `DateInput` | Business Date |
| ratecodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| ratecodeDetailsCommissionCode | `StringInput` | Commission Code |
| ratecodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| ratecodeDetailsDailyRatesYn | `StringInput` | Daily Rates Y/N |
| ratecodeDetailsDbaseRateCode | `StringInput` | The rate code on which this rate shedule is dynamically based on. |
| ratecodeDetailsSellSequence | `FloatInput` | Display Sequence |
| ratecodeDetailsEndBookingDate | `DateInput` | End Date |
| ratecodeDetailsGroupCode | `StringInput` | Group Code |
| ratecodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| ratecodeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| ratecodeDetailsMarketCode | `StringInput` | Market Code |
| ratecodeDetailsMaxDvanceBooking | `FloatInput` | Maximum Days Advance Booking |
| ratecodeDetailsMaxLos | `FloatInput` | Maximum Length of Stay |
| ratecodeDetailsMaxOccupancy | `FloatInput` | Maximum Occupancy |
| ratecodeDetailsMinAdvanceBooking | `FloatInput` | Minimum Days Advance Booking |
| ratecodeDetailsMinOccupancy | `FloatInput` | Minimum Occupancy |
| ratecodeDetailsOrderBy | `FloatInput` | Order By |
| ratecodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| ratecodeDetailsRateCode | `StringInput` | Original Rate Code |
| ratecodeDetailsOrsSellSequence | `FloatInput` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| ratecodeDetailsPendingApprovalYn | `StringInput` | Indicates whether the rate code is pending for approval or not |
| ratecodeDetailsResort | `StringInput` | Code to uniquely identify the Property |
| ratecodeDetailsRateBucket | `StringInput` | Yield rate bucket |
| ratecodeDetailsRateCodeId | `StringInput` | Rate Code ID |
| ratecodeDetailsRateLevel | `FloatInput` | Rate Level this rate code belongs to. |
| ratecodeDetailsSourceCode | `StringInput` | Source Code |
| ratecodeDetailsTransactionCode | `StringInput` | Rate transaction code |
| ratecodeDetailsLosUnit | `FloatInput` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| rateseasonDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| rateseasonDetailsEndDate | `DateInput` | End Date |
| rateseasonDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| rateseasonDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| rateseasonDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| rateseasonDetailsResort | `StringInput` | Code to uniquely identify the Property |
| rateseasonDetailsRateCode | `StringInput` | Rate Code |
| rateseasonDetailsRateseasonid | `StringInput` | Rateseasonid |
| rateseasonDetailsSeason | `StringInput` | Season Code |
| rateseasonDetailsBeginDate | `DateInput` | Start Date |
| repcalendarDetailsDaykey | `DateInput` | Business Date |
| repcalendarDetailsCalendarcode | `StringInput` | Calendar |
| repcalendarDetailsCalendarpkid | `FloatInput` | Calendarpkid |
| repcalendarDetailsPeriodpkid | `FloatInput` | Periodpkid |
| repcalendarDetailsQuartercode | `StringInput` | Quarter |
| repcalendarDetailsQuarterpkid | `FloatInput` | Quarterpkid |
| repcalendarDetailsYearcode | `FloatInput` | Year |
| repcalendarDetailsYearpkid | `FloatInput` | Yearpkid |
| reservationDetailsActualCheckInDateTime | `DateTimeInput` | Actual Check In Date Time |
| reservationDetailsActualCheckOutDateTime | `DateTimeInput` | Actual Check Out Date Time |
| reservationDetailsActualCheckOutDate | `DateInput` | Actual Check-Out Date |
| reservationDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| reservationDetailsAllotmentid | `FloatInput` | Block ID |
| reservationDetailsTruncBeginDate | `DateInput` | Arrival Date |
| reservationDetailsBillingContactId | `FloatInput` | Billing Contact ID |
| reservationDetailsBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID |
| reservationDetailsAllotmentHeaderId | `FloatInput` | Block ID |
| reservationDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| reservationDetailsBusinessDateCreated | `DateInput` | Business Date Created |
| reservationDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| reservationDetailsCancellationDate | `DateTimeInput` | Cancellation Date |
| reservationDetailsCancellationNo | `StringInput` | Cancellation Number |
| reservationDetailsChainCode | `StringInput` | Chain Code |
| reservationDetailsConfirmationNo | `StringInput` | Shared Confirmation Number |
| reservationDetailsCreditCardId | `FloatInput` | Credit Card ID |
| reservationDetailsCustomReference | `StringInput` | Custom Reference Number |
| reservationDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationDetailsTruncEndDate | `DateInput` | Departure Date |
| reservationDetailsEnddatetime | `DateTimeInput` | End Datetime |
| reservationDetailsEndbusinessdate | `DateInput` | Endbusinessdate |
| reservationDetailsEventId | `FloatInput` | Event ID |
| reservationDetailsFolioCloseDate | `DateInput` | Date the folio was changed to closed. |
| reservationDetailsGuaranteecodeid | `StringInput` | Guaranteecodeid |
| reservationDetailsGuestprofileid | `FloatInput` | Guestprofileid |
| reservationDetailsInsertActionInstanceId | `FloatInput` | Insert Action Instance ID |
| reservationDetailsInsertDate | `DateTimeInput` | Insert Date |
| reservationDetailsInsertdatetime | `DateTimeInput` | Insert DateTime |
| reservationDetailsInsertUser | `FloatInput` | Insert User |
| reservationDetailsAwardMembershipId | `FloatInput` | Award Membership ID |
| reservationDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationDetailsEndDate | `DateTimeInput` | Linked Departure Date |
| reservationDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| reservationDetailsNameUsageType | `StringInput` | Name Usage Type |
| reservationDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationDetailsOriginalEndDate | `DateInput` | Original End Date |
| reservationDetailsParentResvNameId | `FloatInput` | Parent Resv Name ID |
| reservationDetailsParentreservationid | `FloatInput` | Parentreservationid |
| reservationDetailsPostCoFlag | `StringInput` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| reservationDetailsQuoteId | `StringInput` | Quote ID provided by external system. |
| reservationDetailsResvContactId | `FloatInput` | Resv Contact ID |
| reservationDetailsResvNameId | `FloatInput` | Reservation Name ID |
| reservationDetailsResvStatus | `StringInput` | Reservation Status |
| reservationDetailsGuaranteeCode | `StringInput` | Reservation Type |
| reservationDetailsReservationid | `FloatInput` | Reservationid |
| reservationDetailsResort | `StringInput` | Property |
| reservationDetailsResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| reservationDetailsResvNameid | `FloatInput` | Reservation Nameid |
| reservationDetailsResvcontactprofileid | `FloatInput` | Resvcontactprofileid |
| reservationDetailsRhBillingContactId | `FloatInput` | Rh Billing Contact ID |
| reservationDetailsRhResvContactId | `FloatInput` | Rh Resv Contact ID |
| reservationDetailsRoomCategory | `StringInput` | Room Category |
| reservationDetailsRoomcategoryid | `StringInput` | Roomcategoryid |
| reservationDetailsScheduleCheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| reservationDetailsSguestFirstname | `StringInput` | This is CAPITOL version of guest_first_name |
| reservationDetailsSguestName | `StringInput` | Sguest Name |
| reservationDetailsNameId | `FloatInput` | Shared Profile ID |
| reservationDetailsReservationStatus | `StringInput` | Shared Reservation Status |
| reservationDetailsSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| reservationDetailsSplitfromreservationid | `FloatInput` | Splitfromreservationid |
| reservationDetailsTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component. |
| reservationDetailsUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes. |
| reservationDetailsUpdateDate | `DateTimeInput` | Update Date |
| reservationDetailsUpdatedatetime | `DateTimeInput` | Update Datetime |
| revenuepackagesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| revenuepackagesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| revenuepackagesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| revenuepackagesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| revenuepackagesDetailsProductpmsref | `StringInput` | Package Code |
| revenuepackagesDetailsProduct | `StringInput` | Product |
| revenuepackagesDetailsProductid | `StringInput` | Productid |
| revenuepackagesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| revenuepackagesDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| roomDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| roomDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| roomDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| roomDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomDetailsResort | `StringInput` | Code to uniquely identify the Property |
| roomDetailsRoompmsref | `StringInput` | Room |
| roomDetailsRoom | `StringInput` | Room Number |
| roomDetailsRoomid | `StringInput` | Roomid |
| routinginstructionDetailsAuthemployeeid | `FloatInput` | Authemployeeid |
| routinginstructionDetailsAuthorizerId | `FloatInput` | Authorizer ID |
| routinginstructionDetailsBillingInstrnCode | `FloatInput` | Billing Instruction Code. |
| routinginstructionDetailsBilltoprofileid | `FloatInput` | Billtoprofileid |
| routinginstructionDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| routinginstructionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| routinginstructionDetailsDayString | `StringInput` | Concatenated string of all the days. This is also used part of the unique key. |
| routinginstructionDetailsFolioView | `FloatInput` | Folio |
| routinginstructionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| routinginstructionDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| routinginstructionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| routinginstructionDetailsBillToNameId | `FloatInput` | Name Id to which it should be routed. |
| routinginstructionDetailsRequestedBy | `StringInput` | Application user who requested the report. |
| routinginstructionDetailsResvNameId | `FloatInput` | Resv Name ID |
| routinginstructionDetailsReservationid | `FloatInput` | Reservationid |
| routinginstructionDetailsRoutingInstructionsId | `FloatInput` | Number to identify the entry. |
| routinginstructionDetailsTrxCode | `StringInput` | Routing Transaction Code |
| routinginstructionDetailsRoutinginstructid | `FloatInput` | Routinginstructid |
| routinginstructionDetailsTcGroup | `StringInput` | Transaction Code Group |
| routinginstructionDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| routinginstructionDetailsToResvNameId | `FloatInput` | To Resv Name ID |
| routinginstructionDetailsToreservationid | `FloatInput` | Toreservationid |
| routinginstructionDetailsTranscodearrangementid | `FloatInput` | Transcodearrangementid |
| routinginstructionDetailsTranscodeid | `StringInput` | Transcodeid |
| routinginstructionDetailsTransgroupid | `StringInput` | Transgroupid |
| routinginstructionDetailsTranssubgroupid | `StringInput` | Transsubgroupid |
| transcodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| transcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| transcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| transcodeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| transcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| transcodeDetailsResort | `StringInput` | Property |
| transcodeDetailsTranscodeid | `StringInput` | Transcodeid |
| transcodeDetailsTrxCode | `StringInput` | Trx Code |
| transcodearrangmentDetailsArrangementCode | `StringInput` | Arrangement Code |
| transcodearrangmentDetailsArrangementId | `FloatInput` | Arrangement ID |
| transcodearrangmentDetailsType | `StringInput` | Arrangement Type |
| transcodearrangmentDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| transcodearrangmentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| transcodearrangmentDetailsExportBucketType | `StringInput` | User defined Export Bucket type. |
| transcodearrangmentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| transcodearrangmentDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| transcodearrangmentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| transcodearrangmentDetailsResort | `StringInput` | Code to uniquely identify the Property |
| transcodearrangmentDetailsTranscodearrangementid | `FloatInput` | Transcodearrangementid |
| fromReservationDetailsActualCheckInDateTime | `DateTimeInput` | Actual Check In Date Time |
| fromReservationDetailsActualCheckOutDateTime | `DateTimeInput` | Actual Check Out Date Time |
| fromReservationDetailsActualCheckOutDate | `DateInput` | Actual Check-Out Date |
| fromReservationDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| fromReservationDetailsAllotmentid | `FloatInput` | Block ID |
| fromReservationDetailsTruncBeginDate | `DateInput` | Arrival Date |
| fromReservationDetailsBillingContactId | `FloatInput` | Billing Contact ID |
| fromReservationDetailsBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID |
| fromReservationDetailsAllotmentHeaderId | `FloatInput` | Block ID |
| fromReservationDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| fromReservationDetailsBusinessDateCreated | `DateInput` | Business Date Created |
| fromReservationDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| fromReservationDetailsCancellationDate | `DateTimeInput` | Cancellation Date |
| fromReservationDetailsCancellationNo | `StringInput` | Cancellation Number |
| fromReservationDetailsConfirmationNo | `StringInput` | Shared Confirmation Number |
| fromReservationDetailsCreditCardId | `FloatInput` | Credit Card ID |
| fromReservationDetailsCustomReference | `StringInput` | Custom Reference Number |
| fromReservationDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| fromReservationDetailsTruncEndDate | `DateInput` | Departure Date |
| fromReservationDetailsEnddatetime | `DateTimeInput` | End Datetime |
| fromReservationDetailsEndbusinessdate | `DateInput` | Endbusinessdate |
| fromReservationDetailsEventId | `FloatInput` | Event ID |
| fromReservationDetailsFolioCloseDate | `DateInput` | Date the folio was changed to closed. |
| fromReservationDetailsGuaranteecodeid | `StringInput` | Guaranteecodeid |
| fromReservationDetailsGuestprofileid | `FloatInput` | Guestprofileid |
| fromReservationDetailsInsertActionInstanceId | `FloatInput` | Insert Action Instance ID |
| fromReservationDetailsInsertDate | `DateTimeInput` | Insert Date |
| fromReservationDetailsInsertdatetime | `DateTimeInput` | Insert DateTime |
| fromReservationDetailsInsertUser | `FloatInput` | Insert User |
| fromReservationDetailsAwardMembershipId | `FloatInput` | Award Membership ID |
| fromReservationDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| fromReservationDetailsEndDate | `DateTimeInput` | Linked Departure Date |
| fromReservationDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| fromReservationDetailsNameUsageType | `StringInput` | Name Usage Type |
| fromReservationDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| fromReservationDetailsOriginalEndDate | `DateInput` | Original End Date |
| fromReservationDetailsParentResvNameId | `FloatInput` | Parent Resv Name ID |
| fromReservationDetailsParentreservationid | `FloatInput` | Parentreservationid |
| fromReservationDetailsPostCoFlag | `StringInput` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| fromReservationDetailsQuoteId | `StringInput` | Quote ID provided by external system. |
| fromReservationDetailsResvContactId | `FloatInput` | Resv Contact ID |
| fromReservationDetailsResvNameId | `FloatInput` | Reservation Name ID |
| fromReservationDetailsResvStatus | `StringInput` | Reservation Status |
| fromReservationDetailsGuaranteeCode | `StringInput` | Reservation Type |
| fromReservationDetailsReservationid | `FloatInput` | Reservationid |
| fromReservationDetailsResort | `StringInput` | Property |
| fromReservationDetailsResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| fromReservationDetailsResvNameid | `FloatInput` | Reservation Nameid |
| fromReservationDetailsResvcontactprofileid | `FloatInput` | Resvcontactprofileid |
| fromReservationDetailsRhBillingContactId | `FloatInput` | Rh Billing Contact ID |
| fromReservationDetailsRhResvContactId | `FloatInput` | Rh Resv Contact ID |
| fromReservationDetailsRoomCategory | `StringInput` | Room Category |
| fromReservationDetailsRoomcategoryid | `StringInput` | Roomcategoryid |
| fromReservationDetailsScheduleCheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| fromReservationDetailsSguestFirstname | `StringInput` | This is CAPITOL version of guest_first_name |
| fromReservationDetailsSguestName | `StringInput` | Sguest Name |
| fromReservationDetailsNameId | `FloatInput` | Shared Profile ID |
| fromReservationDetailsReservationStatus | `StringInput` | Shared Reservation Status |
| fromReservationDetailsSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| fromReservationDetailsSplitfromreservationid | `FloatInput` | Splitfromreservationid |
| fromReservationDetailsTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component. |
| fromReservationDetailsUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes. |
| fromReservationDetailsUpdateDate | `DateTimeInput` | Update Date |
| fromReservationDetailsUpdatedatetime | `DateTimeInput` | Update Datetime |
| toReservationDetailsActualCheckInDateTime | `DateTimeInput` | Actual Check In Date Time |
| toReservationDetailsActualCheckOutDateTime | `DateTimeInput` | Actual Check Out Date Time |
| toReservationDetailsActualCheckOutDate | `DateInput` | Actual Check-Out Date |
| toReservationDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| toReservationDetailsAllotmentid | `FloatInput` | Block ID |
| toReservationDetailsTruncBeginDate | `DateInput` | Arrival Date |
| toReservationDetailsBillingContactId | `FloatInput` | Billing Contact ID |
| toReservationDetailsBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID |
| toReservationDetailsAllotmentHeaderId | `FloatInput` | Block ID |
| toReservationDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| toReservationDetailsBusinessDateCreated | `DateInput` | Business Date Created |
| toReservationDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| toReservationDetailsCancellationDate | `DateTimeInput` | Cancellation Date |
| toReservationDetailsCancellationNo | `StringInput` | Cancellation Number |
| toReservationDetailsConfirmationNo | `StringInput` | Shared Confirmation Number |
| toReservationDetailsCreditCardId | `FloatInput` | Credit Card ID |
| toReservationDetailsCustomReference | `StringInput` | Custom Reference Number |
| toReservationDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| toReservationDetailsTruncEndDate | `DateInput` | Departure Date |
| toReservationDetailsEnddatetime | `DateTimeInput` | End Datetime |
| toReservationDetailsEndbusinessdate | `DateInput` | Endbusinessdate |
| toReservationDetailsEventId | `FloatInput` | Event ID |
| toReservationDetailsFolioCloseDate | `DateInput` | Date the folio was changed to closed. |
| toReservationDetailsGuaranteecodeid | `StringInput` | Guaranteecodeid |
| toReservationDetailsGuestprofileid | `FloatInput` | Guestprofileid |
| toReservationDetailsInsertActionInstanceId | `FloatInput` | Insert Action Instance ID |
| toReservationDetailsInsertDate | `DateTimeInput` | Insert Date |
| toReservationDetailsInsertdatetime | `DateTimeInput` | Insert DateTime |
| toReservationDetailsInsertUser | `FloatInput` | Insert User |
| toReservationDetailsAwardMembershipId | `FloatInput` | Award Membership ID |
| toReservationDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| toReservationDetailsEndDate | `DateTimeInput` | Linked Departure Date |
| toReservationDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| toReservationDetailsNameUsageType | `StringInput` | Name Usage Type |
| toReservationDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| toReservationDetailsOriginalEndDate | `DateInput` | Original End Date |
| toReservationDetailsParentResvNameId | `FloatInput` | Parent Resv Name ID |
| toReservationDetailsParentreservationid | `FloatInput` | Parentreservationid |
| toReservationDetailsPostCoFlag | `StringInput` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| toReservationDetailsQuoteId | `StringInput` | Quote ID provided by external system. |
| toReservationDetailsResvContactId | `FloatInput` | Resv Contact ID |
| toReservationDetailsResvNameId | `FloatInput` | Reservation Name ID |
| toReservationDetailsResvStatus | `StringInput` | Reservation Status |
| toReservationDetailsGuaranteeCode | `StringInput` | Reservation Type |
| toReservationDetailsReservationid | `FloatInput` | Reservationid |
| toReservationDetailsResort | `StringInput` | Property |
| toReservationDetailsResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| toReservationDetailsResvNameid | `FloatInput` | Reservation Nameid |
| toReservationDetailsResvcontactprofileid | `FloatInput` | Resvcontactprofileid |
| toReservationDetailsRhBillingContactId | `FloatInput` | Rh Billing Contact ID |
| toReservationDetailsRhResvContactId | `FloatInput` | Rh Resv Contact ID |
| toReservationDetailsRoomCategory | `StringInput` | Room Category |
| toReservationDetailsRoomcategoryid | `StringInput` | Roomcategoryid |
| toReservationDetailsScheduleCheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| toReservationDetailsSguestFirstname | `StringInput` | This is CAPITOL version of guest_first_name |
| toReservationDetailsSguestName | `StringInput` | Sguest Name |
| toReservationDetailsNameId | `FloatInput` | Shared Profile ID |
| toReservationDetailsReservationStatus | `StringInput` | Shared Reservation Status |
| toReservationDetailsSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| toReservationDetailsSplitfromreservationid | `FloatInput` | Splitfromreservationid |
| toReservationDetailsTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component. |
| toReservationDetailsUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes. |
| toReservationDetailsUpdateDate | `DateTimeInput` | Update Date |
| toReservationDetailsUpdatedatetime | `DateTimeInput` | Update Datetime |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query financialTransactionDetails($input: FinancialTransactionDetailsQueryArgumentsType!) {
  financialTransactionDetails(input: $input) @stream {
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
    eventPostingDetails {
      allotmentid
      blockBeginDate
      blockEndDate
      bookId
      businessDate
      cExchangeDate
      cExchangeRate
      cPostedToExtra
      cPostedToIncl
      cSvcTaxExtra
      cSvcTaxInclude
      cTaxExtra
      cTaxIncl
      cTransactionExtra
      cTransactionIncl
      calculationRuleExtra
      calculationRuleIncluded
      centralPostingRevenueExtra
      centralRevenueIncluded
      centralServiceChargeIncluded
      centralServiceChargeExtra
      centralTaxType
      centralTaxTypeDescription
      centralUnitPrice
      checkNumber
      dSI
      deletedFlag
      evPostId
      eventId
      eventpostingid
      extraallotmentid
      extraforresvid
      extratranscodeid
      includedallotmentid
      includedforresvid
      includedtranscodeid
      insertUser
      internalEventid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      postedById
      postedByUserName
      postedDateExtra
      postedDateIncluded
      postedToExtra
      postedToIncl
      postedYN
      postedByProperty
      postedToRoomExtra
      postedToRoomIncluded
      postingRevenueExtra
      postinglocationid
      primaryKeyID
      property
      resourceName
      resourceType
      revenueIncluded
      revenueType
      revenuetypeid
      rnaInsertDate
      rnaUpdateDate
      serviceChargeIncluded
      serviceChargePercentExtra
      serviceChargePercentIncluded
      serviceChargeTransactionCode
      serviceChargeExtra
      svcTaxExtra
      svcTaxInclude
      svcTrxCodeExtra
      svcTrxNumberExtra
      svcTrxNumberIncl
      taxExtra
      taxIncl
      taxType
      taxTypeDescription
      transactionCodeExtraRevenue
      transactionCodeIncludedRevenue
      trxExtra
      trxIncl
      trxNumberExtra
      trxNumberIncl
      unitPrice
      units
      updateDate
      updateUser
    }
    propertyBudgetForecastDetails {
      accountingType
      accountingYear
      budgetCode
      budgetCodeDescription
      budgetType
      budgetValue
      budgetValueDescription
      cExchangeDate
      cExchangeRate
      centralRevenue
      covers
      dSI
      deletedFlag
      endDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      lockedYN
      organizationID
      periodType
      primaryKeyID
      property
      revenue
      rnaInsertDate
      rnaUpdateDate
      roomNights
      startDate
      updateDate
      updateUser
    }
    exportMapFintrxcodesDetails {
      chainCode
      codeCanDeleteYn
      codeInsertDate
      codeInsertUser
      codeInsertUserName
      codeUpdateDate
      codeUpdateUser
      codeUpdateUserName
      combinedMappingYn
      dSI
      dataType
      deletedFlag
      exportMappingId
      exportValue
      jRNUpdateDate
      jRNUpdateDateAndTime
      linkInsertDate
      linkInsertUser
      linkInsertUserName
      linkUpdateDate
      linkUpdateUser
      linkUpdateUserName
      linkedCode
      linkedDescription
      locationID
      lovName
      mappedToCode
      mappedToDescription
      mappingCode
      mappingCodeDescription
      mappingTypeCode
      mappingTypeDescription
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      requiredYn
      seqNumber
      shortColumnTitle
      trxCode
      typeCanDeleteYn
      typeInsertDate
      typeInsertUser
      typeInsertUserName
      typeUpdateDate
      typeUpdateUser
      typeUpdateUserName
      useLovYn
    }
    exportMapPayMethDetails {
      chainCode
      codeCanDeleteYn
      codeInsertDate
      codeInsertUser
      codeInsertUserName
      codeUpdateDate
      codeUpdateUser
      codeUpdateUserName
      combinedMappingYn
      dSI
      dataType
      deletedFlag
      exportMappingId
      exportValue
      jRNUpdateDate
      jRNUpdateDateAndTime
      linkInsertDate
      linkInsertUser
      linkInsertUserName
      linkUpdateDate
      linkUpdateUser
      linkUpdateUserName
      linkedCode
      linkedDescription
      locationID
      lovName
      mappedToCode
      mappedToDescription
      mappingCode
      mappingCodeDescription
      mappingTypeCode
      mappingTypeDescription
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      requiredYn
      seqNumber
      shortColumnTitle
      trxCode
      typeCanDeleteYn
      typeInsertDate
      typeInsertUser
      typeInsertUserName
      typeUpdateDate
      typeUpdateUser
      typeUpdateUserName
      useLovYn
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
    articleDetails {
      activeYN
      articleCode
      articleDescription
      articleId
      availableInPostItYN
      cDefaultPrice
      cExchangeDate
      cExchangeRate
      centralArticleCode
      centralArticleDescription
      centralSequence
      centralTransactionCode
      dSI
      defaultPrice
      deletedflag
      description
      displayColor
      inactiveDate
      insertDate
      insertUser
      internalArticleid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      transactionCode
      transcodeid
      uPC
      updateDate
      updateUser
    }
    calendarPeriodDetails {
      chainCode
      dSI
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
    cashierDetails {
      activeYN
      amtDifferenceInitial
      attachedToUser
      cAmountDifferenceInitial
      cAmountFloat
      cCashierBalance
      cExchangeDate
      cExchangeRate
      cashierBal
      cashierid
      chainCode
      closureInProgressYn
      closureNo
      csrTrxNumber
      dSI
      dateoflastuse
      deletedflag
      floatOverShort
      generalCashierYN
      insertDate
      insertUser
      interfaceCashierYN
      internalUpdateYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      kioskCashierYN
      lastOpened
      locationID
      maximumDailyUses
      organizationID
      paymentsCashierCode
      primaryKeyID
      property
      reservedResort
      reservedYn
      rnaInsertDate
      rnaUpdateDate
      startingAmount
      state
      timeoffirstopen
      timeoflastclose
      timesOpened
      tranActionId
      transactionsCashierName
      updateDate
      updateUser
    }
    employeeDetails {
      accessConfig
      accessEod
      accessObi
      accessOcis
      accessOcm
      accessOcrm
      accessOrms
      accessOrs
      accessOxi
      accessOxihub
      accessPms
      accessSc
      accessScbi
      accessSfa
      accessUtil
      accountLockedOutYn
      agent
      appUserType
      authorizerInactiveDate
      authorizerRateCode
      authorizerYn
      birthDate
      businessTitle
      businessTitleDescription
      cExchangeDate
      cExchangeRate
      cHourlyRate
      cWeeklySalary
      dSI
      dateHired
      defCashierId
      defaultForm
      defaultMfnResort
      defaultReportgroup
      defaultResort
      deletedflag
      departmentid
      deptEmail
      deptId
      deptManagerPager
      deptName
      deptOrderBy
      disabledUntil
      eMail
      empExtension
      empStatus
      employeeIncentiveNumber
      employeeNumber
      employeeid
      expiresOn
      first
      forcePasswordChangeYn
      fridayMax
      fridayMin
      generalFilepath
      graceLogin
      hireType
      hourlyRate
      hoursPerWeek
      inactiveDesc
      inactiveFrom
      inactiveReasonCode
      inactiveTo
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopId
      last
      leadAddress
      leadAddressDet
      leadComm
      locationID
      lockoutDate
      loginCro
      loginDomain
      maleFemale
      maxCheckoutDays
      maxUserSessions
      mfnUserType
      middle
      mobileAlertsYn
      mondayMax
      mondayMin
      nameNotes
      organizationID
      otMultiplier
      passwordChangeDays
      passwordLastChange
      personNameId
      phoneNo
      phoneNumber
      preventAccountLockout
      primaryBlockOwnerName
      primaryKeyID
      primaryRoomsOwnerCode
      rNAInsertDate
      rNAUpdateDate
      rateType
      receiveBroadcastMsg
      rehireYn
      salaryInterval
      saturdayMax
      saturdayMin
      serviceRequestAlertsYn
      sfaName
      srepGroup
      sundayMax
      sundayMin
      termReason
      terminatedDate
      territory
      thursdayMax
      thursdayMin
      timezoneRegion
      tuesdayMax
      tuesdayMin
      updateDate
      updateUser
      userFilepath
      userID
      userPbxId
      wednesdayMax
      wednesdayMin
      weekMax
      weekMin
      weeklySalary
      workPermitExpdate
      workPermitNo
    }
    exportMapPackagecodesDetails {
      chainCode
      codeCanDeleteYn
      codeInsertDate
      codeInsertUser
      codeInsertUserName
      codeUpdateDate
      codeUpdateUser
      codeUpdateUserName
      combinedMappingYn
      dSI
      dataType
      deletedFlag
      exportMappingId
      exportValue
      jRNUpdateDate
      jRNUpdateDateAndTime
      linkInsertDate
      linkInsertUser
      linkInsertUserName
      linkUpdateDate
      linkUpdateUser
      linkUpdateUserName
      linkedCode
      linkedDescription
      locationID
      lovName
      mappedToCode
      mappedToDescription
      mappingCode
      mappingCodeDescription
      mappingTypeCode
      mappingTypeDescription
      organizationID
      primaryKeyID
      product
      property
      rNAInsertDate
      rNAUpdateDate
      requiredYn
      seqNumber
      shortColumnTitle
      typeCanDeleteYn
      typeInsertDate
      typeInsertUser
      typeInsertUserName
      typeUpdateDate
      typeUpdateUser
      typeUpdateUserName
      useLovYn
    }
    financialPeriodDetails {
      chainCode
      dSI
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
    folioTaxDetails {
      accountCode
      addresseeNameId
      amountPostedFromAR
      amountFromDirectBill
      associatedBillDate
      associatedBillNumber
      associatedFiscalBillDate
      associatedFiscalBillNumber
      associatedFiscalBillNumberGenerationTime
      associatedSeqNumber
      billGenerationDate
      billNumber
      billPaymentTrxNumber
      billPrefix
      billSequenceNumber
      billStartDate
      billStatus
      businessDate
      businessId
      cCashpay
      cCcpay
      cClarpay
      cClpay
      cCollectionTax1
      cCollectionTax2
      cCollectionTax3
      cCollectionTax4
      cCollectionTax5
      cDailyRunningTotal
      cDeposit
      cExchangeDate
      cExchangeRate
      cFiscalInvoiceCurrencyRate
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
      cPaidout
      cPerpetualAmount
      cPnet1Amount
      cPnet10Amount
      cPnet11Amount
      cPnet12Amount
      cPnet13Amount
      cPnet14Amount
      cPnet15Amount
      cPnet16Amount
      cPnet17Amount
      cPnet18Amount
      cPnet19Amount
      cPnet2Amount
      cPnet20Amount
      cPnet3Amount
      cPnet4Amount
      cPnet5Amount
      cPnet6Amount
      cPnet7Amount
      cPnet8Amount
      cPnet9Amount
      cPtax1Amount
      cPtax10Amount
      cPtax11Amount
      cPtax12Amount
      cPtax13Amount
      cPtax14Amount
      cPtax15Amount
      cPtax16Amount
      cPtax17Amount
      cPtax18Amount
      cPtax19Amount
      cPtax2Amount
      cPtax20Amount
      cPtax3Amount
      cPtax4Amount
      cPtax5Amount
      cPtax6Amount
      cPtax7Amount
      cPtax8Amount
      cPtax9Amount
      cPtotNonrevNonTaxable
      cPtotNonrevTaxable
      cPtotRevenueNonTaxable
      cPtotRevenueTaxable
      cRealPerpetualAmount
      cTax1Amount
      cTax2Amount
      cTaxCode1
      cTaxCode10
      cTaxCode11
      cTaxCode12
      cTaxCode13
      cTaxCode14
      cTaxCode15
      cTaxCode16
      cTaxCode17
      cTaxCode18
      cTaxCode19
      cTaxCode2
      cTaxCode20
      cTaxCode3
      cTaxCode4
      cTaxCode5
      cTaxCode6
      cTaxCode7
      cTaxCode8
      cTaxCode9
      cTaxCodeDescription1
      cTaxCodeDescription10
      cTaxCodeDescription11
      cTaxCodeDescription12
      cTaxCodeDescription13
      cTaxCodeDescription14
      cTaxCodeDescription15
      cTaxCodeDescription16
      cTaxCodeDescription17
      cTaxCodeDescription18
      cTaxCodeDescription19
      cTaxCodeDescription2
      cTaxCodeDescription20
      cTaxCodeDescription3
      cTaxCodeDescription4
      cTaxCodeDescription5
      cTaxCodeDescription6
      cTaxCodeDescription7
      cTaxCodeDescription8
      cTaxCodeDescription9
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
      cTotalGross
      cTotalNet
      cTotalNonTaxable
      cTotalNonrevNonTaxable
      cTotalNonrevTaxable
      cTotalRevenueNonTaxable
      cTotalRevenueTaxable
      cTotalTax
      cXnet1Amount
      cXnet10Amount
      cXnet11Amount
      cXnet12Amount
      cXnet13Amount
      cXnet14Amount
      cXnet15Amount
      cXnet16Amount
      cXnet17Amount
      cXnet18Amount
      cXnet19Amount
      cXnet2Amount
      cXnet20Amount
      cXnet3Amount
      cXnet4Amount
      cXnet5Amount
      cXnet6Amount
      cXnet7Amount
      cXnet8Amount
      cXnet9Amount
      cXtax1Amount
      cXtax10Amount
      cXtax11Amount
      cXtax12Amount
      cXtax13Amount
      cXtax14Amount
      cXtax15Amount
      cXtax16Amount
      cXtax17Amount
      cXtax18Amount
      cXtax19Amount
      cXtax2Amount
      cXtax20Amount
      cXtax3Amount
      cXtax4Amount
      cXtax5Amount
      cXtax6Amount
      cXtax7Amount
      cXtax8Amount
      cXtax9Amount
      cashRegisterId
      cashRegisterInvNumber
      cashTotal
      cashierID
      centralTaxRate1
      centralTaxRate10
      centralTaxRate11
      centralTaxRate12
      centralTaxRate13
      centralTaxRate14
      centralTaxRate15
      centralTaxRate16
      centralTaxRate17
      centralTaxRate18
      centralTaxRate19
      centralTaxRate2
      centralTaxRate20
      centralTaxRate3
      centralTaxRate4
      centralTaxRate5
      centralTaxRate6
      centralTaxRate7
      centralTaxRate8
      centralTaxRate9
      city
      cityLedgerYN
      clTrxNumber
      collectionAgentTotalTax1
      collectionAgentTotalTax2
      collectionAgentTotalTax3
      collectionAgentTotalTax4
      collectionAgentTotalTax5
      companyFinancialValue
      companyName
      companyType
      compressBillNo
      creditBillGeneratedYN
      creditBillNumber
      creditCardTotal
      customNumber1
      customNumber2
      customNumber3
      customNumber4
      customNumber5
      dSI
      dailyRunningTotal
      deletedFlag
      deposit
      depositReqReceiptNumber
      documentCode
      documentType
      eArchiveEttnNumber
      eArchiveNumber
      eArchiveReportNo
      eArchiveStatus
      eInvoiceNumber
      eInvoiceStatus
      fiscalBillCheckDigit
      fiscalBillGenerationDate
      fiscalBillGenerationTime
      fiscalBillNumber
      fiscalInvoiceCurrency
      fiscalInvoiceCurrencyRate
      fiscalSessionNo
      fiscalUnitControlCode
      folioAddress
      folioAddressCorrectedYn
      folioAttachmentLinkId
      folioAttachmentStatus
      folioNo
      folioStyle
      folioTaxSeqNumber
      folioTime
      folioType
      folioType1
      folioTypeJoin
      folioView
      forexTaxYn
      fullFolioNo
      hasWatermarkYn
      hotelName
      insTimestamp
      insertDate
      invoiceNumber
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastSignature
      locationID
      nRBusinessID
      nafApeHotelCode
      nameId
      nameTaxType
      netAmount1
      netAmount10
      netAmount11
      netAmount12
      netAmount13
      netAmount14
      netAmount15
      netAmount16
      netAmount17
      netAmount18
      netAmount19
      netAmount2
      netAmount20
      netAmount3
      netAmount4
      netAmount5
      netAmount6
      netAmount7
      netAmount8
      netAmount9
      numberOfPages
      operaFiscalFolioStatus
      organizationID
      pageNumber
      palmVideoFlag
      partnerFiscalFolioStatus
      payeeAddress
      payeeCountry
      payeeFirstName
      payeeLastName
      payeeName
      payeeNameID
      payeePostalCode
      payeeTaxID1
      payeeTaxID2
      payeeZipCode
      paymentDate
      perpetualAmount
      pnet1Amt
      pnet10Amt
      pnet11Amt
      pnet12Amt
      pnet13Amt
      pnet14Amt
      pnet15Amt
      pnet16Amt
      pnet17Amt
      pnet18Amt
      pnet19Amt
      pnet2Amt
      pnet20Amt
      pnet3Amt
      pnet4Amt
      pnet5Amt
      pnet6Amt
      pnet7Amt
      pnet8Amt
      pnet9Amt
      postitSequenceNumber
      postitYN
      primaryKeyID
      printerQueueName
      profileTypeCode
      promotionalText1
      promotionalText2
      property
      propertyBillPrefix
      propertyTaxNumber
      ptax1Amt
      ptax10Amt
      ptax11Amt
      ptax12Amt
      ptax13Amt
      ptax14Amt
      ptax15Amt
      ptax16Amt
      ptax17Amt
      ptax18Amt
      ptax19Amt
      ptax2Amt
      ptax20Amt
      ptax3Amt
      ptax4Amt
      ptax5Amt
      ptax6Amt
      ptax7Amt
      ptax8Amt
      ptax9Amt
      ptotNonrevNonTaxable
      ptotNonrevTaxable
      ptotRevNonTaxable
      ptotRevTaxable
      realPerpetualAmount
      reservationNameId
      resortCity
      resortCountry
      resortFullAddress
      resortZipcodeCode
      revisionNo
      rnaInsertDate
      rnaUpdateDate
      roomNumber
      seqNumber
      signature
      signatureKeyVersion
      softwareVersion
      tax1RateType
      tax2RateType
      taxAmount1
      taxAmount10
      taxAmount11
      taxAmount12
      taxAmount13
      taxAmount14
      taxAmount15
      taxAmount16
      taxAmount17
      taxAmount18
      taxAmount19
      taxAmount2
      taxAmount20
      taxAmount3
      taxAmount4
      taxAmount5
      taxAmount6
      taxAmount7
      taxAmount8
      taxAmount9
      taxCode1
      taxCode10
      taxCode11
      taxCode12
      taxCode13
      taxCode14
      taxCode15
      taxCode16
      taxCode17
      taxCode18
      taxCode19
      taxCode2
      taxCode20
      taxCode3
      taxCode4
      taxCode5
      taxCode6
      taxCode7
      taxCode8
      taxCode9
      taxCodeDesc1
      taxCodeDesc10
      taxCodeDesc11
      taxCodeDesc12
      taxCodeDesc13
      taxCodeDesc14
      taxCodeDesc15
      taxCodeDesc16
      taxCodeDesc17
      taxCodeDesc18
      taxCodeDesc19
      taxCodeDesc2
      taxCodeDesc20
      taxCodeDesc3
      taxCodeDesc4
      taxCodeDesc5
      taxCodeDesc6
      taxCodeDesc7
      taxCodeDesc8
      taxCodeDesc9
      taxId
      taxRate1
      taxRate10
      taxRate11
      taxRate12
      taxRate13
      taxRate14
      taxRate15
      taxRate16
      taxRate17
      taxRate18
      taxRate19
      taxRate2
      taxRate20
      taxRate3
      taxRate4
      taxRate5
      taxRate6
      taxRate7
      taxRate8
      taxRate9
      tax10RateType
      tax11RateType
      tax12RateType
      tax13RateType
      tax14RateType
      tax15RateType
      tax16RateType
      tax17RateType
      tax18RateType
      tax19RateType
      tax20RateType
      tax3RateType
      tax4RateType
      tax5RateType
      tax6RateType
      tax7RateType
      tax8RateType
      tax9RateType
      terminal
      totalGrossAmount
      totalNetAmount
      totalNonRevenueNonTaxableAmount
      totalNonRevenueTaxableAmount
      totalNonTaxableAmount
      totalNonTaxableRevenue
      totalPaidOuts
      totalTax
      totalTaxableRevenue
      transactLastSignatureHash
      transactSignatureHash
      transactSignatureKeyVersion
      transactionSignature
      trxServiceType
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
      uDFC11
      uDFC12
      uDFC13
      uDFC14
      uDFC15
      uDFC16
      uDFC17
      uDFC18
      uDFC19
      uDFC20
      uDFC21
      uDFC22
      uDFC23
      uDFC24
      uDFC25
      uDFC26
      uDFC27
      uDFC28
      uDFC29
      uDFC30
      uDFC31
      uDFC32
      uDFC33
      uDFC34
      uDFC35
      uDFC36
      uDFC37
      uDFC38
      uDFC39
      uDFC40
      uDFD01
      uDFD02
      uDFD03
      uDFD04
      uDFD05
      uDFD06
      uDFD07
      uDFD08
      uDFD09
      uDFD10
      uDFD11
      uDFD12
      uDFD13
      uDFD14
      uDFD15
      uDFD16
      uDFD17
      uDFD18
      uDFD19
      uDFD20
      uDFN01
      uDFN02
      uDFN03
      uDFN04
      uDFN05
      uDFN06
      uDFN07
      uDFN08
      uDFN09
      uDFN10
      uDFN11
      uDFN12
      uDFN13
      uDFN14
      uDFN15
      uDFN16
      uDFN17
      uDFN18
      uDFN19
      uDFN20
      uDFN21
      uDFN22
      uDFN23
      uDFN24
      uDFN25
      uDFN26
      uDFN27
      uDFN28
      uDFN29
      uDFN30
      uDFN31
      uDFN32
      uDFN33
      uDFN34
      uDFN35
      uDFN36
      uDFN37
      uDFN38
      uDFN39
      uDFN40
      updTimestamp
      updateDate
      updateUser
      userID
      userName
      voidNumber
      voidReason
      workingDocId
      xnet1Amt
      xnet10Amt
      xnet11Amt
      xnet12Amt
      xnet13Amt
      xnet14Amt
      xnet15Amt
      xnet16Amt
      xnet17Amt
      xnet18Amt
      xnet19Amt
      xnet2Amt
      xnet20Amt
      xnet3Amt
      xnet4Amt
      xnet5Amt
      xnet6Amt
      xnet7Amt
      xnet8Amt
      xnet9Amt
      xtax1Amt
      xtax10Amt
      xtax11Amt
      xtax12Amt
      xtax13Amt
      xtax14Amt
      xtax15Amt
      xtax16Amt
      xtax17Amt
      xtax18Amt
      xtax19Amt
      xtax2Amt
      xtax20Amt
      xtax3Amt
      xtax4Amt
      xtax5Amt
      xtax6Amt
      xtax7Amt
      xtax8Amt
      xtax9Amt
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
    invoicePaymentDetails {
      appliedAmount
      businessDate
      cExchangeDate
      cExchangeRate
      cashierId
      centralAppliedAmount
      chainCode
      consumptionTransactionNumber
      consumptionTrx
      dSI
      deletedFlag
      insertDate
      insertUser
      invoicepaymentid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      paymentApplicationId
      paymentTransactionNumber
      paymentTrx
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
    profileAllInformationDetails {
      guestProfileID
      aRNumber
      aRNumberCentral
      aRCreditLimitYN
      aRCMailFlag
      aRCOfficeType
      aRCUpdateDate
      accountBillingContact
      accountSource
      accountType
      accountTypeDescription
      accountsourceDesc
      actionCode
      activeYN
      address1
      address2
      address3
      address4
      addressId
      addressLangCodeDesc
      addressLanguageCode
      addressType
      alienRegistrationNo
      allResorts
      alternateEnvelopeGreeting
      alternateLanguage
      alternateLanguageDescription
      alternateSalutation
      autoEnrollMemberYN
      availabilityOverride
      billingCode
      billingInstruction
      billingProfileCode
      birthCountry
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessSegment
      businessSegmentDescription
      businessTitle
      cExchangeDate
      cExchangeRate
      cProfileCreditLimit
      cRSNameid
      ccProfileYn
      centralAccountType
      centralBusinessSegment
      centralBusinessSegmentDescription
      centralCorporateIDType
      centralDefaultKeyword
      centralGuestTitleCode
      centralInactiveReason
      centralInactiveReasonDescription
      centralMailActionDescription
      centralMailingActionCode
      centralPriority
      centralStateCode
      centralTerritory
      centralVIPCode
      centralVIPDescription
      chainCode
      city
      clientID
      collectionUserId
      combinedName
      commPayCentral
      comments
      commissionCode
      commissionCodes
      commissionCurrencyId
      commissionid
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      companyAlternate
      companyGroupId
      companyNameId
      competition
      competitionDesc
      contactYN
      contractNo
      contractRecvDate
      corpTypeDesc
      corporateIDType
      country
      countryCode
      createdByUser
      createdOnDate
      creditRating
      currencyCode
      currencySymbol
      dOptInAutoenrollMemberFlg
      dOptInEmailFlg
      dOptInGuestPrivFlg
      dOptInMailListFlg
      dOptInMarketResearchFlg
      dOptInPhoneFlg
      dOptInSmsFlg
      dOptInThirdPartyFlg
      dSI
      debtorName
      decimalPositions
      defaultKeyword
      deletedFlag
      department
      deptId
      description
      directBillBatchType
      displayName
      downloadDate
      downloadResort
      downloadSrep
      eInvLiableLastUpdated
      eInvoiceLiableYn
      email
      emailYN
      envelopeGreeting
      externalDisplayName
      externalFirstName
      externalId
      externalName
      externalReferenceRequ
      externalReferenceRequired
      fMembershipCardNumbers
      fMembershipClassDesc
      fMembershipClasses
      fMembershipCodes
      fMembershipDescriptions
      fMembershipIds
      fMembershipType
      fSubscriptionDb
      fSubscriptionYn
      faxNumber
      firstName
      firstNameAlternate
      firstNameIncognito
      followOn
      gDSName
      gDSTransactionNo
      gender
      geographicRegion
      guestClassification
      guestCountry
      guestCurrencyCode
      guestLanguageCode
      guestLastName
      guestMiddleName
      guestNameSuffix
      guestPrivilegeYN
      guestTitleCode
      hasRequestedMailYN
      historyYN
      holdCode
      iataConsortia
      idCountry
      idDate
      idDocumentAttachId
      idPlace
      idType
      immigrationStatus
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      includeInTax1099Yn
      indexName
      industryCode
      industryDesc
      influence
      influenceDesc
      interest
      internalBillYn
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      laptopChange
      lastGroup
      lastNameAlternate
      lastNameIncognito
      lastRate
      lastRateCode
      lastRoom
      lastRoomProperty
      lastSource
      lastStay
      lastUpdatedResort
      legalCompany
      letterGreeting
      mailActionDescription
      mailList
      mailType
      mailingActionCode
      marketResearchYN
      masterAccountYn
      nameTaxType
      nameType
      nameTypeDescription
      name2
      name3
      nationality
      nationalityCode
      negotiatedRateCodes
      nextStay
      nickname
      organizationID
      origNameId
      paymentDueDays
      phone
      phoneWeb
      phoneYN
      postalCode
      postalCodeExtension
      preferredRoomNo
      primaryAddressId
      primaryKeyID
      primaryNameId
      primaryOwner
      primaryOwnerCode
      primaryPhoneId
      priority
      priorityDesc
      privacyFlagYN
      productInterest
      profession
      profileCreditLimit
      profileId
      profileType
      propertyRegistered
      protected
      psuedoProfileYn
      rateStructure
      region
      regionid
      repAccountTypeDescription
      repAccountsource
      repAccountsourceDescription
      repCompetitionCode
      repCompetitionDescription
      repCorpTypeDescription
      repIndustryCode
      repIndustryDescription
      repInfluence
      repInfluenceDescription
      repNameType
      repNameTypeDescription
      repNationalityCode
      repNationalityDescription
      repPriorityDescription
      repRoomsPotential
      repRoomsPotentialDescription
      repScope
      repScopeCity
      repScopeCityDescription
      repScopeDescription
      repStateDescription
      repTaxTypeDescription
      repTerritoryDescription
      repTitleName
      repeatGuestId
      replaceAddress
      requestType
      restricted
      restrictedRule
      resvContact
      rnaInsertDate
      rnaUpdateDate
      roomsPotential
      roomsPotentialDesc
      sMSYN
      salutation
      scope
      scopeCity
      scopeCityDesc
      scopeDesc
      searchName
      searchNameAlternate
      sfirst
      soundExCompany
      soundExLast
      srepCode
      state
      stateCode
      stateDescription
      summRefCc
      summRefCurrencyId
      superSearchIndexText
      sxfirstName
      taxCategory
      taxExemptStatus
      taxID1
      taxID2
      taxOffice
      taxType
      territory
      territoryDesc
      thirdPartyYN
      titleAlternate
      titleName
      titleSuffix
      totalStay
      tourOperatorType
      traceCode
      tracecodeDesc
      typeOfTax1099
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
      uDFC11
      uDFC12
      uDFC13
      uDFC14
      uDFC15
      uDFC16
      uDFC17
      uDFC18
      uDFC19
      uDFC20
      uDFC21
      uDFC22
      uDFC23
      uDFC24
      uDFC25
      uDFC26
      uDFC27
      uDFC28
      uDFC29
      uDFC30
      uDFC31
      uDFC32
      uDFC33
      uDFC34
      uDFC35
      uDFC36
      uDFC37
      uDFC38
      uDFC39
      uDFC40
      uDFD01
      uDFD02
      uDFD03
      uDFD04
      uDFD05
      uDFD06
      uDFD07
      uDFD08
      uDFD09
      uDFD10
      uDFD11
      uDFD12
      uDFD13
      uDFD14
      uDFD15
      uDFD16
      uDFD17
      uDFD18
      uDFD19
      uDFD20
      uDFN01
      uDFN02
      uDFN03
      uDFN04
      uDFN05
      uDFN06
      uDFN07
      uDFN08
      uDFN09
      uDFN10
      uDFN11
      uDFN12
      uDFN13
      uDFN14
      uDFN15
      uDFN16
      uDFN17
      uDFN18
      uDFN19
      uDFN20
      uDFN21
      uDFN22
      uDFN23
      uDFN24
      uDFN25
      uDFN26
      uDFN27
      uDFN28
      uDFN29
      uDFN30
      uDFN31
      uDFN32
      uDFN33
      uDFN34
      uDFN35
      uDFN36
      uDFN37
      uDFN38
      uDFN39
      uDFN40
      updateDate
      updateFaxDate
      updateUser
      uploadDate
      vIPCode
      vIPDescription
      vendorId
      vendorSiteId
      vipAuthorization
      visaValidityType
      xdisplayName
      xmiddleName
    }
    rateCodeDetails {
      aSBRateCycle
      addition
      advBaseRateCode
      advBaseRounding
      advanceBaseCompareYN
      advanceDailyBaseYN
      advanceDailyRateYN
      alternateRateCode
      availabilityUpdateYn
      backToBackYN
      baseAmount
      baseFltPct
      baseRateCode
      baseRounding
      baseType
      bbarBaseAmount
      bbarBaseFltPct
      bbarBaseRounding
      bbarBasedYn
      bbarCompareYn
      bbarYn
      blockName
      breakfastInclYn
      breakfastPrice
      businessDate
      bypassHurdleYn
      bypassRankCheckYn
      cBaseAmount
      cBbarBaseAmount
      cBreakfastPrice
      cDbaseAmount
      cDiscountRateAmount
      cDoubleRoomSupplementPrice
      cExchangeDate
      cExchangeRate
      cRateFloor
      cRateLevel
      cRodBaseAmount
      cRoomAssignmentValue
      catPackageCode
      cateringPackageYN
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      centralRateBucket
      centralRateBucketDescription
      centralRateCategory
      centralRateCategoryDescription
      centralRateClass
      centralRateClassDescription
      centralRoomType
      centralRoomTypeDescription
      centralSourceCode
      centralSourceDescription
      centralSourceGroupCode
      centralSourceGroupDescription
      changeState
      commissionPercent
      commissionCode
      commissionYn
      commissionablePerc
      commissionableYn
      complimentaryYN
      currCodeDecimalPos
      currencyCode
      dSI
      dailyRatesYn
      dayUseYN
      daysWhenClosedToArrival
      dbaseAmount
      dbaseCompareYn
      dbaseFltPct
      dbaseRateCode
      dbaseRounding
      dblRoomSupplementPrice
      defaultToHighestBarYn
      deletedFlag
      depositMaturityPreference
      deptCode
      discountRateAmount
      discountRatePercentageYn
      discountYN
      displaySequence
      displaySet
      distributeYn
      doubleRoomSupplementYN
      endDate
      eventProperty
      exchangeType
      externallyControlledYN
      extraPersonChargeBegins
      fitDiscountLevel
      fitDiscountPerc
      flatYN
      folioText
      frequentFlyerYN
      gDSAllowedYN
      groupCode
      highlightRateAmountYn
      houseUseYN
      inactiveDate
      insertDate
      insertUser
      internalLocationId
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      longInfo
      loyaltyProgramYN
      mandateResvProfiles
      marketCode
      marketDescription
      marketGroupCode
      marketGroupDescription
      marshaRateProgram
      maximumDaysAdvanceBooking
      maximumLengthOfStay
      maximumOccupancy
      mfnUploadYn
      minimumDaysAdvanceBooking
      minimumOccupancy
      mobileCheckinAllowedYn
      mobileChkoutAllowed
      multiplication
      myFidelioUploadYN
      negotiatedYN
      occupancyBasedYn
      occupancyLevel
      operatorType
      orderBy
      organizationID
      originalRateCode
      orsSellSequence
      overridePackageYn
      ownerRateYN
      packageTransactionCode
      packageTransactionCodeWeekend
      packageTransactionTaxInclYN
      packageTransactionTaxIncludedYN
      packageTransactionWkTaxInclYN
      packageYN
      packages
      pendingApprovalYn
      postingRhythm
      postingRhythmNights
      primaryKeyID
      printRateYn
      privilegedRestrictionYn
      privilegedYn
      profitTransactionCode
      property
      propertyName
      rankAdjustmentFactor
      rankValue
      rateBucket
      rateBucketDescription
      rateCalendarYn
      rateCategory
      rateCategoryDescription
      rateClass
      rateClassDescription
      rateCodeId
      rateCodeLockedYn
      rateFloor
      rateFloorOverrideYn
      rateIncludesTaxYn
      rateLabel
      rateLevel
      rateUpdateYN
      rateinfoUrl
      redemptionRateYN
      regionalAvailabilityYN
      repeatPostingRhythmYn
      rnaInsertDate
      rnaUpdateDate
      rodBaseAmount
      rodBaseFltPct
      rodBaseRounding
      rodBasedYn
      rodYn
      roomAssignmentValue
      roomType
      roomTypeDescription
      sdowBeginBookingDate
      sdowEndBookingDate
      serviceInclYn
      servicePerc
      shortInfo
      showRateAmountYn
      sourceCode
      sourceDescription
      sourceGroupCode
      sourceGroupDescription
      taxIncludedPerc
      taxIncludedYn
      tieredYN
      transactionCode
      transactionCodeWeekend
      transactionTaxWeekendIncludedYN
      unitOfLengthOfStay
      updateDate
      updateUser
      upsellYn
      voucherBenefitRateYn
      weekendDays
      wkDeptCode
      yieldAs
      yieldableYN
      ymCode
    }
    rateSeasonDetails {
      centralSeasonCode
      centralSeasonDescription
      dSI
      deletedYn
      displayColor
      endDate
      inactiveDate
      inactiveYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      rateCode
      ratecodeid
      rateseasonid
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      seasonCode
      seasonDescription
      startDate
      updateDate
      updateUser
    }
    reportCalendarDetails {
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
    reservationDetails {
      aSBProratedYn
      accompaniedYN
      accompanyingName
      actualCheckInDateTime
      actualCheckOutDateTime
      actualCheckInDate
      actualCheckInTime
      actualCheckOutDate
      actualCheckOutTime
      addressId
      addresseeNameId
      adults
      adultsTaxFree
      advanceCheckedInYn
      agencyprofileid
      allotmentRecordType
      allotmentid
      amenityEligibleYn
      amenityLevelCode
      amountPercent
      approvalAmount
      approvalAmountCalcMethod
      approvalCode
      arrivalComments
      arrivalDate
      arrivalDateTime
      arrivalEstimateTime
      arrivalTime
      arrivaltransportid
      attachedDate
      authorizedBillingYN
      authorizedBy
      authorizerId
      autoCheckinYn
      autoPopulateRoutingYn
      autoSettleDays
      autoSettleType
      autoSettleYN
      awardCode
      awardCode1
      awardCode2
      awardCode3
      awardCode4
      awardCode5
      awardMembershipID
      awardVoucher1
      awardVoucher2
      awardVoucher3
      awardVoucher4
      awardVoucher5
      awdUpgrFrom
      awdUpgrTo
      backToBackYN
      balance
      baseRateAmount
      baseRateCode
      baseRateCurrencyCode
      basedOnRule
      baseratecurrencyid
      beginCity
      beginDatetime
      beginDistrict
      beginState
      beginSystemDateTime
      billNumber
      billingContact
      billingContactDisplayName
      billingContactId
      billingContactName
      billingcontactprofileid
      blockCode
      blockCreateDate
      blockID
      blockName
      blockResort
      blockStatus
      bonusCheckId
      bookedRoomCategory
      bookedroomcategoryid
      businessDateCreated
      businessDatetimeCreated
      bxgyDiscountYn
      cAutoPostAmount
      cBaseRateAmount
      cDiscountAmount
      cDiscountAmt
      cEffectiveRateAmount
      cExchangeDate
      cExchangeRate
      cFixedCharge
      cGrossRateAmount
      cLocalBaseRateAmount
      cNetRoomAmount
      cOriginalBaseRate
      cPackageAmount
      cPackageTax
      cRateAmount
      cRoomCost
      cRoomTax
      cShareAmountOriginal
      cUpsellCharge
      cancelDate
      cancelReason
      cancelTime
      cancellationDate
      cancellationDatetime
      cancellationNumber
      cancellationReasonDescription
      cancellationreasonid
      cancelledBy
      cardNumberByMembershipClass
      cardNumberByMembershipType
      centralApprovalAmount
      centralCancelReason
      centralCommissionCode
      centralCommissionDescription
      centralCreditLimit
      centralDiscountReason
      centralDiscountReasonDescription
      centralFBRevenue
      centralGuestType
      centralHurdle
      centralPackageCode
      centralPackageCodeDescription
      centralPackageForecastGroup
      centralPackageForecastGroupDescription
      centralPaymentAmount
      centralProjectedFBRevenue
      centralProjectedRoomRevenue
      centralProjectedTotalRevenue
      centralPromotionDescription
      centralRateableValue
      centralReservationType
      centralReservationTypeDescription
      centralRoomRevenue
      centralRoomTypeCode
      centralRoomTypeDescription
      centralRoomTypeToChargeCode
      centralRoomTypeToChargeDescription
      centralSharedRoomRate
      centralSpecialRequestDescription
      centralTaxType
      centralTaxTypeDescription
      centralTotalCostOfStay
      centralTotalRevenue
      centralTotalRoomRate
      centralWaitlistPriority
      centralWaitlistPriorityDescription
      centralWaitlistReason
      centralWaitlistReasonDescription
      chainCode
      channelDescription
      channelOrderBy
      channelid
      checkInInitiatedBy
      checkinDuration
      childBucket1
      childBucket4
      childBucket5
      children
      childrenAgeGroup2
      childrenAgeGroup3
      childrenAges
      commissionCode
      commissionDescription
      commissionHoldCode
      commissionPaid
      commissionPayoutTo
      commissionableYN
      commissionid
      compHouse
      compTypeCode
      companyCity
      companyCountry
      companyID
      companyName
      companyProfileCorporateID
      companyProfileID
      complimentaryYN
      compreasonid
      computedResvStatus
      confirmationLegNumber
      confirmationNo
      consumerYn
      contactName
      contactProfileID
      contactProfileName
      createdBy
      createdByDefaultResort
      createdDate
      createdTime
      creditCardAuthDate
      creditCardId
      creditLimit
      creditLimitAutoPayAllowYn
      cribs
      currencyCode
      customReferenceNumber
      dSI
      dateOfArrivalInCountry
      deletedFlag
      departtransportid
      departureComments
      departureDate
      departureDateTime
      departureTime
      departureTransportCode
      departureTransportationYN
      depositMaturityType
      detatchedDate
      detatchedYN
      directBillVerifyResponse
      directbillauthby
      discountAmount
      discountAmt
      discountPercent
      discountPrcnt
      discountReason
      discountReasonDescription
      discountreasonid
      displayColor
      dmlSeqNumber
      doNotMoveRoom
      doNotMoveYN
      dropOffCarrierCode
      dropOffDate
      dropOffStation
      dropOffTime
      dropOffType
      dropOffTypeDescription
      eTRComments
      effectiveRateAmount
      eligibleForUpgradeYn
      emailAddress
      emailFolioYn
      emailId
      emailYn
      endCity
      endDatetime
      endDistrict
      endState
      endbusinessdate
      entryDate
      entryPoint
      esignedRegCardName
      estimatedDepartureTime
      eventId
      exchangePostingType
      exchangeRate
      excludeFromAutoAuthorizationYN
      expectedTimeOfReturnETR
      exportCheckinresId
      extSegNo
      extSeqNumber
      extensionId
      externalEfolioYn
      externalReference
      externalReferencesList
      extraBeds
      fBRevenue
      fBRevenueRemaining
      faxId
      faxYn
      feature
      financiallyResponsibleYn
      fixedCharge
      fixedRateYN
      folioAddrElementId
      folioCloseDate
      folioNumber
      folioText1
      folioText2
      foreignCurrencyID
      freeChild
      frequentFlyerMembershipYN
      grossRateFuture
      grossRatePast
      groupName
      groupProfileARNumber
      groupProfileARNumberCentral
      groupProfileClientID
      groupProfileID
      groupProfileName
      guaranteeCodePreCi
      guaranteecodeid
      guestFirstName
      guestFirstNameSdx
      guestLastNameSdx
      guestSignature
      guestStatus
      guestType
      guestprofileid
      gueststatusid
      guesttypeid
      housekeepingServiceTime
      hurdle
      hurdleOverride
      iDByMembershipClass
      iDByMembershipType
      individualCity
      individualCountry
      individualFirstName
      individualLastName
      insertActionInstanceId
      insertDate
      insertDateTime
      insertUser
      intermediaryYn
      internalAwardMembershipId
      internalBaseratecode
      internalBlockId
      internalCompanyprofileid
      internalGroupprofileid
      internalSourceprofileid
      itemsQuantities
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyValidUntil
      lastOnlinePrintSeq
      lastPeriodicFolioDate
      lastRoomNumber
      lastSettleDate
      leadTimeDays
      lengthOfStay
      linkedArrivalDate
      linkedDepartureDate
      linkedRoomType
      listOfMembershipID
      localBaseRateAmount
      locationID
      loyaltySchemeMembershipYN
      mailYn
      manualCheckoutStatus
      marketCode
      marketid
      mcGenBeginDistrict
      mcGenBeginState
      mcGenEndDistrict
      mcGenEndState
      mcGenNextCountry
      mcGenPreviousCountry
      memberDescription
      memberLevel
      memberNumber
      membershipClass
      membershipClassDescription
      membershipCode
      membershipId
      membershipLevelByMembershipClass
      membershipTypeByMembershipClass
      mobileActionAlertIssued
      mobileAudioKeyYn
      mobileCheckinAllowedYn
      mobileChkoutAllowed
      mobilePreferredCurrency
      mobileViewFolioAllowed
      name
      nameUsageType
      nextCountry
      nextDestination
      numberOfRooms
      operaEsignedRegCardYn
      optInBatchFolYn
      optedForCommissionYN
      organizationID
      originCode
      originOfBooking
      originalBaseRate
      originalEndDate
      originalStartDate
      ownerFfFlag
      ownerOrFriendsFamily
      packageCode
      packageCodeDescription
      packageForecastGroup
      packageForecastGroupDescription
      parentReservationNameId
      parentreservationid
      partAllotment
      partyCode
      paxNo
      paymentAmount
      paymentMethod
      paymentmethodid
      periodicFolioFreq
      phoneDisplayNameYn
      phoneId
      physicalQuantity
      pickUpCarrierCode
      pickUpDate
      pickUpStation
      pickUpTransportNumber
      pickUpType
      pickUpTypeDescription
      pickUpTime
      pickupRequiredYN
      points
      pointsEligibilityCode
      postCoFlag
      postStayChargingYN
      postingAllowedYN
      preArrReviewedDt
      preArrReviewedUser
      preChargingYn
      preRegisteredYn
      preference
      preferenceType
      preferredRoomType
      previousCountry
      primaryKeyID
      primaryShare
      printRateYN
      projectedFBRevenue
      projectedRoomRevenue
      projectedTotalRevenue
      promotionCode
      promotionDescription
      property
      pseudoMemTotalPoints
      pseudoMemType
      purgeDate
      purposeOfStay
      quantity
      queuePriority
      queueWaitTime
      quoteId
      rateAmount
      rateCode
      rateCodeDescriptions
      rateTier
      rateableValue
      ratecodeid
      rdHousekeepingExpectedServiceTime
      rdResvStatus
      rdenBillingContactId
      rdenReservationContactId
      rdenReservationDate
      rdenResort
      referralYn
      registrationCardNo
      registrationNumber
      reinstateDate
      repChannel
      repChannelDescription
      reportId
      resInsertSource
      resInsertSourceType
      reservationContactId
      reservationDate
      reservationNameID
      reservationStatus
      reservationType
      reservationTypeDescription
      reservationid
      resort
      resortChargeNumber
      restrictionOverride
      resvGuid
      resvNameid
      resvNumber
      resvcontactprofileid
      revenueTypeCode
      rhBillingContactId
      rhReservationContactId
      rhRoomFeatures
      rnaInsertDate
      rnaUpdateDate
      room
      roomCategory
      roomClass
      roomCost
      roomInstructions
      roomResort
      roomRevenue
      roomRevenueRemaining
      roomServiceTime
      roomTypeDescription
      roomTypeToChargeCode
      roomTypeToChargeDescription
      roomcategoryid
      roomid
      routingYN
      scheduleCheckoutYn
      sguestFirstname
      sguestName
      shareConfirmationNumbers
      shareId
      shareName
      sharePrcnt
      shareSeqNumber
      shareOfRateAmount
      sharedGuestName
      sharedProfileID
      sharedReservationStatus
      sharingYN
      sourceCity
      sourceCode
      sourceCountry
      sourceName
      sourceProfileARNumber
      sourceProfileARNumberCentral
      sourceProfileIATANumber
      sourceProfileID
      sourceProfileName
      sourceid
      specialRequest
      specialRequestDescription
      spgDiscloseRoomTypeYn
      spgSuiteNightAwardStatus
      spgUpgradeConfirmedRoomtype
      spgUpgradeReasonCode
      splitFromReservationNameId
      splitfromreservationid
      statisticalRateTier
      statisticalRoomType
      stayRecordId
      suiteNumber
      superSearchIndexText
      taRecordLocator
      taxExemptNumber
      taxNumberOfStays
      taxType
      taxTypeDescription
      taxtypeid
      tiad
      ticketNos
      totalCostOfStay
      totalRevenue
      totalRevenueRemaining
      totalRoomRate
      trackItGroups
      trackItTypes
      transactionid
      travelAgentCity
      travelAgentCountry
      travelAgentID
      travelAgentName
      travelAgentProfileARNumber
      travelAgentProfileARNumberCentral
      travelAgentProfileIATANumber
      travelAgentProfileID
      travelAgentProfileName
      truncActualCheckOutDate
      turndownStatus
      turndownYN
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
      uDFC11
      uDFC12
      uDFC13
      uDFC14
      uDFC15
      uDFC16
      uDFC17
      uDFC18
      uDFC19
      uDFC20
      uDFC21
      uDFC22
      uDFC23
      uDFC24
      uDFC25
      uDFC26
      uDFC27
      uDFC28
      uDFC29
      uDFC30
      uDFC31
      uDFC32
      uDFC33
      uDFC34
      uDFC35
      uDFC36
      uDFC37
      uDFC38
      uDFC39
      uDFC40
      uDFD01
      uDFD02
      uDFD03
      uDFD04
      uDFD05
      uDFD06
      uDFD07
      uDFD08
      uDFD09
      uDFD10
      uDFD11
      uDFD12
      uDFD13
      uDFD14
      uDFD15
      uDFD16
      uDFD17
      uDFD18
      uDFD19
      uDFD20
      uDFN01
      uDFN02
      uDFN03
      uDFN04
      uDFN05
      uDFN06
      uDFN07
      uDFN08
      uDFN09
      uDFN10
      uDFN11
      uDFN12
      uDFN13
      uDFN14
      uDFN15
      uDFN16
      uDFN17
      uDFN18
      uDFN19
      uDFN20
      uDFN21
      uDFN22
      uDFN23
      uDFN24
      uDFN25
      uDFN26
      uDFN27
      uDFN28
      uDFN29
      uDFN30
      uDFN31
      uDFN32
      uDFN33
      uDFN34
      uDFN35
      uDFN36
      uDFN37
      uDFN38
      uDFN39
      uDFN40
      uniCardId
      updateDate
      updateDatetime
      updateUser
      updatedBy
      updatedByDefaultResort
      updatedDate
      updatedTime
      upsellCharge
      videoCheckoutYN
      visaExpiryDate
      visaIssueDate
      visaNumber
      waitlistComment
      waitlistPhoneNumber
      waitlistPriority
      waitlistPriorityDescription
      waitlistReason
      waitlistReasonDescription
      waitlistpriorityid
      waitlistreasonid
      walkInYN
      yieldableYn
      ymCode
    }
    revenuePackagesDetails {
      addToRateYN
      arrangementCode
      beginBookingDate
      bookingDuration
      calculationRule
      cateringYn
      centralPackageCode
      centralPackageCodeDescription
      centralPackageForecastGroup
      centralPackageForecastGroupDescription
      currencyCode
      currencyDesc
      dSI
      deletedYn
      deliveryTimeReqrdYn
      endBookingDate
      externalLocked
      flexibleDurationYN
      forecastGroupCode
      forecastNextDayYN
      formula
      genPlAtEodOfCoDate
      insertDate
      insertUser
      internalPostingrhythm
      inventoriedYN
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      longInfo
      maxPersons
      maximumPersons
      minimumAdvBookDays
      organizationID
      outletCode
      overrideFixedRateYn
      pOSAccountYN
      pOSNextDayYN
      packageCode
      packageCodeDescription
      packageCodeShortDescription
      packageForecastGroup
      packageForecastGroupDescription
      pkgForcastGroup
      pkgforecastgrpid
      postingRhythm
      primaryKeyID
      printSeparateYN
      product
      productType
      productid
      property
      redemptionProductYN
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      separatelySoldYN
      standardDuration
      standardPersons
      ticketsYn
      updateDate
      updateUser
      validFromTime
      validToTime
      webBookableYN
    }
    roomDetails {
      accessible
      areaF
      areaM
      assignAssignStatus
      assignDate
      assignReasonDesc
      assignType
      assignemployeeid
      assignreasonid
      bedType
      building
      buildingGroup
      businessDate
      cExchangeDate
      cExchangeRate
      cMinimumRevenue
      cRackRate
      centralMeetingRoomType
      centralRoomClass
      centralRoomType
      centralRoomTypeDescription
      combinationRoomYN
      comments
      componentRoom
      connectingRoomNumber
      dSI
      daySection
      deductYN
      defatulratecodeid
      defaultRateDesc
      deletedflag
      departureCredits
      description
      diaryName
      diarydisplayflag
      discrepancy
      doors
      eveningSection
      evisitorFacilityId
      excludedEventTypes
      facing
      floor
      foPers
      forceAlternateYn
      frontDeskLocation
      frontOfficeStatus
      fullUtilizationTime
      genericYN
      handicapflag
      heightmaxF
      heightmaxM
      heightminF
      heightminM
      holdDateTime
      holdType
      holdUser
      housekeepingAssignmentOrderBy
      housekeepingInspDate
      housekeepingInspEmpId
      housekeepingPers
      housekeepingStatus
      imageId
      inactiveflag
      includeInStatisticsYN
      insertDate
      insertUser
      internalTempflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyCode
      keyOptions
      lastCheckOutDate
      lastMeterReading
      lengthF
      lengthM
      light
      locationID
      loudspeakersflag
      maxAdvance
      maxCapacity
      maxSharedGroups
      maximumOccupancy
      measurement
      meetingRoomType
      meetingRoomYN
      meetingroomTypeDesc
      meetingroomTypeSeq
      microphoneSocketTypes
      microphoneSockets
      minAdvance
      minCapacity
      minimumRevenue
      numberOfBeds
      occupancyCondition
      occupantDiscrepancy
      onlinePrintingYn
      orderBy2
      orderBy3
      orderBy4
      orderBy5
      organizationID
      ovosGradeCode
      ovosUnitYn
      pcode
      personDiscrepancy
      phoneNumber
      physicalNumberOfRooms
      pickupCredits
      primaryKeyID
      property
      pseudoRoomYN
      publishedRateAmount
      publishedRateCode
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rating
      repAssignReasonDescription
      repBedTypeDescription
      repMeetingroomTypeDescription
      repMeetingroomTypeSequence
      repRoomClassSellSequence
      repRoomFeaturesDescs
      repRoomStatusReason
      repRoomStatusReasonDescription
      returnStatus
      room
      roomAssignmentRating
      roomCategoryBedtype
      roomCategoryDesc
      roomClass
      roomClassCentralDescription
      roomClassDescription
      roomClassSequence
      roomCondition
      roomFeatureDescription
      roomFeatures
      roomNumber
      roomParity
      roomStatus
      roomStatusDescription
      roomStatusFromDate
      roomStatusReason
      roomStatusReasonDesc
      roomStatusRemarks
      roomStatusToDate
      roomType
      roomUseCount
      roomcategoryid
      roomclassid
      roomid
      roomstatusreasonid
      sequence
      serviceStatus
      setupNotes
      shareableflag
      smoking
      smokingPreferences
      squareUnits
      stayoverCredits
      suiteType
      suiteYN
      supplement
      tempFlag
      translationboothNum
      turnDown
      turndownCredits
      tvRadioSockets
      unit
      updateDate
      updateUser
      visibleOnWebYn
      webBookingYn
      weightF
      weightM
      widthF
      widthM
    }
    routingInstructionDetails {
      accountCode
      addTransactionYN
      addressId
      authemployeeid
      authorizerId
      basedOnRate
      billingInstrnCode
      billtoprofileid
      cCompPreApprovalAmount
      cExchangeDate
      cExchangeRate
      centralExtendedInstructionSummary
      centralInstructionSummary
      centralRoutingAmountLimit
      centralRoutingLimitUsed
      centralRoutingTransactionCode
      centralRoutingTransactionCodeDescription
      comments
      compAuthorizer
      compPreApprovalAmt
      compPreApprovalCode
      compPreApprovalDate
      compPreApprovalRequiredYn
      compTypeCode
      compVoucherNo
      dSI
      dailyYn
      dayString
      declinedBy
      declinedYn
      deletedFlag
      endDate
      extendedInstructionSummary
      folio
      fridayYN
      insertDate
      insertUser
      instructionSummary
      internalDeletedflag
      internalMembershipid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      membershipId
      mondayYN
      organizationID
      payeeFirstName
      payeeLastName
      payeeNameID
      primaryKeyID
      printReceiptYn
      property
      requestedBy
      reservationNameId
      reservationid
      rnaInsertDate
      rnaUpdateDate
      routedToRoomNo
      routingAmountLimit
      routingBeginDate
      routingCode
      routingCodeDescription
      routingCoversLimit
      routingDateRange
      routingDaysOfWeek
      routingInstructionsId
      routingLimitType
      routingLimitUsed
      routingLinkId
      routingPercentageLimit
      routingTransactionCode
      routingTransactionCodeDescription
      routingType
      routingTypeDesc
      routinginstructid
      saturdayYN
      sundayYN
      tcGroup
      tcSubgroup
      thursdayYN
      toReservationNameId
      toreservationid
      transcodearrangementid
      transcodeid
      transgroupid
      transsubgroupid
      trxServiceType
      tuesdayYN
      updateDate
      updateUser
      wednesdayYN
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
    transactionCodeArrangmentDetails {
      arrTaxTypeCode
      arrangementCode
      arrangementDescription
      arrangementId
      arrangementType
      bucketValue
      cExchangeDate
      cExchangeRate
      cRoutingAmount
      centralTransactionCode
      centralTransactionCodeDescription
      compYn
      complimentaryYN
      dSI
      dailyYn
      day1
      day2
      day3
      day4
      day5
      day6
      day7
      deletedFlag
      eligibleYn
      exportBucketType
      inactiveDate
      inactiveflag
      inheritAuthRatecodeYn
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      revenueYn
      revenueflag
      rnaInsertDate
      rnaUpdateDate
      routingAmount
      routingCovers
      routingPercent
      transactionCode
      transactionCodeDescription
      transcodearrangementid
      updateDate
      updateUser
    }
    fromReservationDetails {
      aSBProratedYn
      accompaniedYN
      accompanyingName
      actualCheckInDateTime
      actualCheckOutDateTime
      actualCheckInDate
      actualCheckInTime
      actualCheckOutDate
      actualCheckOutTime
      addressId
      addresseeNameId
      adults
      adultsTaxFree
      advanceCheckedInYn
      agencyprofileid
      allotmentRecordType
      allotmentid
      amenityEligibleYn
      amenityLevelCode
      amountPercent
      approvalAmount
      approvalAmountCalcMethod
      approvalCode
      arrivalComments
      arrivalDate
      arrivalDateTime
      arrivalEstimateTime
      arrivalTime
      arrivaltransportid
      attachedDate
      authorizedBillingYN
      authorizedBy
      authorizerId
      autoCheckinYn
      autoPopulateRoutingYn
      autoSettleDays
      autoSettleType
      autoSettleYN
      awardCode
      awardCode1
      awardCode2
      awardCode3
      awardCode4
      awardCode5
      awardMembershipID
      awardVoucher1
      awardVoucher2
      awardVoucher3
      awardVoucher4
      awardVoucher5
      awdUpgrFrom
      awdUpgrTo
      backToBackYN
      balance
      baseRateAmount
      baseRateCode
      baseRateCurrencyCode
      basedOnRule
      baseratecurrencyid
      beginCity
      beginDatetime
      beginDistrict
      beginState
      beginSystemDateTime
      billNumber
      billingContact
      billingContactDisplayName
      billingContactId
      billingContactName
      billingcontactprofileid
      blockCode
      blockCreateDate
      blockID
      blockName
      blockResort
      blockStatus
      bonusCheckId
      bookedRoomCategory
      bookedroomcategoryid
      businessDateCreated
      businessDatetimeCreated
      bxgyDiscountYn
      cAutoPostAmount
      cBaseRateAmount
      cDiscountAmount
      cDiscountAmt
      cEffectiveRateAmount
      cExchangeDate
      cExchangeRate
      cFixedCharge
      cGrossRateAmount
      cLocalBaseRateAmount
      cNetRoomAmount
      cOriginalBaseRate
      cPackageAmount
      cPackageTax
      cRateAmount
      cRoomCost
      cRoomTax
      cShareAmountOriginal
      cUpsellCharge
      cancelDate
      cancelReason
      cancelTime
      cancellationDate
      cancellationDatetime
      cancellationNumber
      cancellationReasonDescription
      cancellationreasonid
      cancelledBy
      cardNumberByMembershipClass
      cardNumberByMembershipType
      centralApprovalAmount
      centralCancelReason
      centralCommissionCode
      centralCommissionDescription
      centralCreditLimit
      centralDiscountReason
      centralDiscountReasonDescription
      centralFBRevenue
      centralGuestType
      centralHurdle
      centralPackageCode
      centralPackageCodeDescription
      centralPackageForecastGroup
      centralPackageForecastGroupDescription
      centralPaymentAmount
      centralProjectedFBRevenue
      centralProjectedRoomRevenue
      centralProjectedTotalRevenue
      centralPromotionDescription
      centralRateableValue
      centralReservationType
      centralReservationTypeDescription
      centralRoomRevenue
      centralRoomTypeCode
      centralRoomTypeDescription
      centralRoomTypeToChargeCode
      centralRoomTypeToChargeDescription
      centralSharedRoomRate
      centralSpecialRequestDescription
      centralTaxType
      centralTaxTypeDescription
      centralTotalCostOfStay
      centralTotalRevenue
      centralTotalRoomRate
      centralWaitlistPriority
      centralWaitlistPriorityDescription
      centralWaitlistReason
      centralWaitlistReasonDescription
      channelDescription
      channelOrderBy
      channelid
      checkInInitiatedBy
      checkinDuration
      childBucket1
      childBucket4
      childBucket5
      children
      childrenAgeGroup2
      childrenAgeGroup3
      childrenAges
      commissionCode
      commissionDescription
      commissionHoldCode
      commissionPaid
      commissionPayoutTo
      commissionableYN
      commissionid
      compHouse
      compTypeCode
      companyCity
      companyCountry
      companyID
      companyName
      companyProfileCorporateID
      companyProfileID
      complimentaryYN
      compreasonid
      computedResvStatus
      confirmationLegNumber
      confirmationNo
      consumerYn
      contactName
      contactProfileID
      contactProfileName
      createdBy
      createdByDefaultResort
      createdDate
      createdTime
      creditCardAuthDate
      creditCardId
      creditLimit
      creditLimitAutoPayAllowYn
      cribs
      currencyCode
      customReferenceNumber
      dSI
      dateOfArrivalInCountry
      deletedFlag
      departtransportid
      departureComments
      departureDate
      departureDateTime
      departureTime
      departureTransportCode
      departureTransportationYN
      depositMaturityType
      detatchedDate
      detatchedYN
      directBillVerifyResponse
      directbillauthby
      discountAmount
      discountAmt
      discountPercent
      discountPrcnt
      discountReason
      discountReasonDescription
      discountreasonid
      displayColor
      dmlSeqNumber
      doNotMoveRoom
      doNotMoveYN
      dropOffCarrierCode
      dropOffDate
      dropOffStation
      dropOffTime
      dropOffType
      dropOffTypeDescription
      eTRComments
      effectiveRateAmount
      eligibleForUpgradeYn
      emailAddress
      emailFolioYn
      emailId
      emailYn
      endCity
      endDatetime
      endDistrict
      endState
      endbusinessdate
      entryDate
      entryPoint
      esignedRegCardName
      estimatedDepartureTime
      eventId
      exchangePostingType
      exchangeRate
      excludeFromAutoAuthorizationYN
      expectedTimeOfReturnETR
      exportCheckinresId
      extSegNo
      extSeqNumber
      extensionId
      externalEfolioYn
      externalReference
      externalReferencesList
      extraBeds
      fBRevenue
      fBRevenueRemaining
      faxId
      faxYn
      feature
      financiallyResponsibleYn
      fixedCharge
      fixedRateYN
      folioAddrElementId
      folioCloseDate
      folioNumber
      folioText1
      folioText2
      foreignCurrencyID
      freeChild
      frequentFlyerMembershipYN
      grossRateFuture
      grossRatePast
      groupName
      groupProfileARNumber
      groupProfileARNumberCentral
      groupProfileClientID
      groupProfileID
      groupProfileName
      guaranteeCodePreCi
      guaranteecodeid
      guestFirstName
      guestFirstNameSdx
      guestLastNameSdx
      guestSignature
      guestStatus
      guestType
      guestprofileid
      gueststatusid
      guesttypeid
      housekeepingServiceTime
      hurdle
      hurdleOverride
      iDByMembershipClass
      iDByMembershipType
      individualCity
      individualCountry
      individualFirstName
      individualLastName
      insertActionInstanceId
      insertDate
      insertDateTime
      insertUser
      intermediaryYn
      internalAwardMembershipId
      internalBaseratecode
      internalBlockId
      internalCompanyprofileid
      internalGroupprofileid
      internalSourceprofileid
      itemsQuantities
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyValidUntil
      lastOnlinePrintSeq
      lastPeriodicFolioDate
      lastRoomNumber
      lastSettleDate
      leadTimeDays
      lengthOfStay
      linkedArrivalDate
      linkedDepartureDate
      linkedRoomType
      listOfMembershipID
      localBaseRateAmount
      locationID
      loyaltySchemeMembershipYN
      mailYn
      manualCheckoutStatus
      marketCode
      marketid
      mcGenBeginDistrict
      mcGenBeginState
      mcGenEndDistrict
      mcGenEndState
      mcGenNextCountry
      mcGenPreviousCountry
      memberDescription
      memberLevel
      memberNumber
      membershipClass
      membershipClassDescription
      membershipCode
      membershipId
      membershipLevelByMembershipClass
      membershipTypeByMembershipClass
      mobileActionAlertIssued
      mobileAudioKeyYn
      mobileCheckinAllowedYn
      mobileChkoutAllowed
      mobilePreferredCurrency
      mobileViewFolioAllowed
      name
      nameUsageType
      nextCountry
      nextDestination
      numberOfRooms
      operaEsignedRegCardYn
      optInBatchFolYn
      optedForCommissionYN
      organizationID
      originCode
      originOfBooking
      originalBaseRate
      originalEndDate
      originalStartDate
      ownerFfFlag
      ownerOrFriendsFamily
      packageCode
      packageCodeDescription
      packageForecastGroup
      packageForecastGroupDescription
      parentReservationNameId
      parentreservationid
      partAllotment
      partyCode
      paxNo
      paymentAmount
      paymentMethod
      paymentmethodid
      periodicFolioFreq
      phoneDisplayNameYn
      phoneId
      physicalQuantity
      pickUpCarrierCode
      pickUpDate
      pickUpStation
      pickUpTransportNumber
      pickUpType
      pickUpTypeDescription
      pickUpTime
      pickupRequiredYN
      points
      pointsEligibilityCode
      postCoFlag
      postStayChargingYN
      postingAllowedYN
      preArrReviewedDt
      preArrReviewedUser
      preChargingYn
      preRegisteredYn
      preference
      preferenceType
      preferredRoomType
      previousCountry
      primaryKeyID
      primaryShare
      printRateYN
      projectedFBRevenue
      projectedRoomRevenue
      projectedTotalRevenue
      promotionCode
      promotionDescription
      property
      pseudoMemTotalPoints
      pseudoMemType
      purgeDate
      purposeOfStay
      quantity
      queuePriority
      queueWaitTime
      quoteId
      rateAmount
      rateCode
      rateCodeDescriptions
      rateTier
      rateableValue
      ratecodeid
      rdHousekeepingExpectedServiceTime
      rdResvStatus
      rdenBillingContactId
      rdenReservationContactId
      rdenReservationDate
      rdenResort
      referralYn
      registrationCardNo
      registrationNumber
      reinstateDate
      repChannel
      repChannelDescription
      reportId
      resInsertSource
      resInsertSourceType
      reservationContactId
      reservationDate
      reservationNameID
      reservationStatus
      reservationType
      reservationTypeDescription
      reservationid
      resort
      resortChargeNumber
      restrictionOverride
      resvGuid
      resvNameid
      resvNumber
      resvcontactprofileid
      revenueTypeCode
      rhBillingContactId
      rhReservationContactId
      rhRoomFeatures
      rnaInsertDate
      rnaUpdateDate
      room
      roomCategory
      roomClass
      roomCost
      roomInstructions
      roomResort
      roomRevenue
      roomRevenueRemaining
      roomServiceTime
      roomTypeDescription
      roomTypeToChargeCode
      roomTypeToChargeDescription
      roomcategoryid
      roomid
      routingYN
      scheduleCheckoutYn
      sguestFirstname
      sguestName
      shareConfirmationNumbers
      shareId
      shareName
      sharePrcnt
      shareSeqNumber
      shareOfRateAmount
      sharedGuestName
      sharedProfileID
      sharedReservationStatus
      sharingYN
      sourceCity
      sourceCode
      sourceCountry
      sourceName
      sourceProfileARNumber
      sourceProfileARNumberCentral
      sourceProfileIATANumber
      sourceProfileID
      sourceProfileName
      sourceid
      specialRequest
      specialRequestDescription
      spgDiscloseRoomTypeYn
      spgSuiteNightAwardStatus
      spgUpgradeConfirmedRoomtype
      spgUpgradeReasonCode
      splitFromReservationNameId
      splitfromreservationid
      statisticalRateTier
      statisticalRoomType
      stayRecordId
      suiteNumber
      superSearchIndexText
      taRecordLocator
      taxExemptNumber
      taxNumberOfStays
      taxType
      taxTypeDescription
      taxtypeid
      tiad
      ticketNos
      totalCostOfStay
      totalRevenue
      totalRevenueRemaining
      totalRoomRate
      trackItGroups
      trackItTypes
      transactionid
      travelAgentCity
      travelAgentCountry
      travelAgentID
      travelAgentName
      travelAgentProfileARNumber
      travelAgentProfileARNumberCentral
      travelAgentProfileIATANumber
      travelAgentProfileID
      travelAgentProfileName
      truncActualCheckOutDate
      turndownStatus
      turndownYN
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
      uDFC11
      uDFC12
      uDFC13
      uDFC14
      uDFC15
      uDFC16
      uDFC17
      uDFC18
      uDFC19
      uDFC20
      uDFC21
      uDFC22
      uDFC23
      uDFC24
      uDFC25
      uDFC26
      uDFC27
      uDFC28
      uDFC29
      uDFC30
      uDFC31
      uDFC32
      uDFC33
      uDFC34
      uDFC35
      uDFC36
      uDFC37
      uDFC38
      uDFC39
      uDFC40
      uDFD01
      uDFD02
      uDFD03
      uDFD04
      uDFD05
      uDFD06
      uDFD07
      uDFD08
      uDFD09
      uDFD10
      uDFD11
      uDFD12
      uDFD13
      uDFD14
      uDFD15
      uDFD16
      uDFD17
      uDFD18
      uDFD19
      uDFD20
      uDFN01
      uDFN02
      uDFN03
      uDFN04
      uDFN05
      uDFN06
      uDFN07
      uDFN08
      uDFN09
      uDFN10
      uDFN11
      uDFN12
      uDFN13
      uDFN14
      uDFN15
      uDFN16
      uDFN17
      uDFN18
      uDFN19
      uDFN20
      uDFN21
      uDFN22
      uDFN23
      uDFN24
      uDFN25
      uDFN26
      uDFN27
      uDFN28
      uDFN29
      uDFN30
      uDFN31
      uDFN32
      uDFN33
      uDFN34
      uDFN35
      uDFN36
      uDFN37
      uDFN38
      uDFN39
      uDFN40
      uniCardId
      updateDate
      updateDatetime
      updateUser
      updatedBy
      updatedByDefaultResort
      updatedDate
      updatedTime
      upsellCharge
      videoCheckoutYN
      visaExpiryDate
      visaIssueDate
      visaNumber
      waitlistComment
      waitlistPhoneNumber
      waitlistPriority
      waitlistPriorityDescription
      waitlistReason
      waitlistReasonDescription
      waitlistpriorityid
      waitlistreasonid
      walkInYN
      yieldableYn
      ymCode
    }
    toReservationDetails {
      aSBProratedYn
      accompaniedYN
      accompanyingName
      actualCheckInDateTime
      actualCheckOutDateTime
      actualCheckInDate
      actualCheckInTime
      actualCheckOutDate
      actualCheckOutTime
      addressId
      addresseeNameId
      adults
      adultsTaxFree
      advanceCheckedInYn
      agencyprofileid
      allotmentRecordType
      allotmentid
      amenityEligibleYn
      amenityLevelCode
      amountPercent
      approvalAmount
      approvalAmountCalcMethod
      approvalCode
      arrivalComments
      arrivalDate
      arrivalDateTime
      arrivalEstimateTime
      arrivalTime
      arrivaltransportid
      attachedDate
      authorizedBillingYN
      authorizedBy
      authorizerId
      autoCheckinYn
      autoPopulateRoutingYn
      autoSettleDays
      autoSettleType
      autoSettleYN
      awardCode
      awardCode1
      awardCode2
      awardCode3
      awardCode4
      awardCode5
      awardMembershipID
      awardVoucher1
      awardVoucher2
      awardVoucher3
      awardVoucher4
      awardVoucher5
      awdUpgrFrom
      awdUpgrTo
      backToBackYN
      balance
      baseRateAmount
      baseRateCode
      baseRateCurrencyCode
      basedOnRule
      baseratecurrencyid
      beginCity
      beginDatetime
      beginDistrict
      beginState
      beginSystemDateTime
      billNumber
      billingContact
      billingContactDisplayName
      billingContactId
      billingContactName
      billingcontactprofileid
      blockCode
      blockCreateDate
      blockID
      blockName
      blockResort
      blockStatus
      bonusCheckId
      bookedRoomCategory
      bookedroomcategoryid
      businessDateCreated
      businessDatetimeCreated
      bxgyDiscountYn
      cAutoPostAmount
      cBaseRateAmount
      cDiscountAmount
      cDiscountAmt
      cEffectiveRateAmount
      cExchangeDate
      cExchangeRate
      cFixedCharge
      cGrossRateAmount
      cLocalBaseRateAmount
      cNetRoomAmount
      cOriginalBaseRate
      cPackageAmount
      cPackageTax
      cRateAmount
      cRoomCost
      cRoomTax
      cShareAmountOriginal
      cUpsellCharge
      cancelDate
      cancelReason
      cancelTime
      cancellationDate
      cancellationDatetime
      cancellationNumber
      cancellationReasonDescription
      cancellationreasonid
      cancelledBy
      cardNumberByMembershipClass
      cardNumberByMembershipType
      centralApprovalAmount
      centralCancelReason
      centralCommissionCode
      centralCommissionDescription
      centralCreditLimit
      centralDiscountReason
      centralDiscountReasonDescription
      centralFBRevenue
      centralGuestType
      centralHurdle
      centralPackageCode
      centralPackageCodeDescription
      centralPackageForecastGroup
      centralPackageForecastGroupDescription
      centralPaymentAmount
      centralProjectedFBRevenue
      centralProjectedRoomRevenue
      centralProjectedTotalRevenue
      centralPromotionDescription
      centralRateableValue
      centralReservationType
      centralReservationTypeDescription
      centralRoomRevenue
      centralRoomTypeCode
      centralRoomTypeDescription
      centralRoomTypeToChargeCode
      centralRoomTypeToChargeDescription
      centralSharedRoomRate
      centralSpecialRequestDescription
      centralTaxType
      centralTaxTypeDescription
      centralTotalCostOfStay
      centralTotalRevenue
      centralTotalRoomRate
      centralWaitlistPriority
      centralWaitlistPriorityDescription
      centralWaitlistReason
      centralWaitlistReasonDescription
      channelDescription
      channelOrderBy
      channelid
      checkInInitiatedBy
      checkinDuration
      childBucket1
      childBucket4
      childBucket5
      children
      childrenAgeGroup2
      childrenAgeGroup3
      childrenAges
      commissionCode
      commissionDescription
      commissionHoldCode
      commissionPaid
      commissionPayoutTo
      commissionableYN
      commissionid
      compHouse
      compTypeCode
      companyCity
      companyCountry
      companyID
      companyName
      companyProfileCorporateID
      companyProfileID
      complimentaryYN
      compreasonid
      computedResvStatus
      confirmationLegNumber
      confirmationNo
      consumerYn
      contactName
      contactProfileID
      contactProfileName
      createdBy
      createdByDefaultResort
      createdDate
      createdTime
      creditCardAuthDate
      creditCardId
      creditLimit
      creditLimitAutoPayAllowYn
      cribs
      currencyCode
      customReferenceNumber
      dSI
      dateOfArrivalInCountry
      deletedFlag
      departtransportid
      departureComments
      departureDate
      departureDateTime
      departureTime
      departureTransportCode
      departureTransportationYN
      depositMaturityType
      detatchedDate
      detatchedYN
      directBillVerifyResponse
      directbillauthby
      discountAmount
      discountAmt
      discountPercent
      discountPrcnt
      discountReason
      discountReasonDescription
      discountreasonid
      displayColor
      dmlSeqNumber
      doNotMoveRoom
      doNotMoveYN
      dropOffCarrierCode
      dropOffDate
      dropOffStation
      dropOffTime
      dropOffType
      dropOffTypeDescription
      eTRComments
      effectiveRateAmount
      eligibleForUpgradeYn
      emailAddress
      emailFolioYn
      emailId
      emailYn
      endCity
      endDatetime
      endDistrict
      endState
      endbusinessdate
      entryDate
      entryPoint
      esignedRegCardName
      estimatedDepartureTime
      eventId
      exchangePostingType
      exchangeRate
      excludeFromAutoAuthorizationYN
      expectedTimeOfReturnETR
      exportCheckinresId
      extSegNo
      extSeqNumber
      extensionId
      externalEfolioYn
      externalReference
      externalReferencesList
      extraBeds
      fBRevenue
      fBRevenueRemaining
      faxId
      faxYn
      feature
      financiallyResponsibleYn
      fixedCharge
      fixedRateYN
      folioAddrElementId
      folioCloseDate
      folioNumber
      folioText1
      folioText2
      foreignCurrencyID
      freeChild
      frequentFlyerMembershipYN
      grossRateFuture
      grossRatePast
      groupName
      groupProfileARNumber
      groupProfileARNumberCentral
      groupProfileClientID
      groupProfileID
      groupProfileName
      guaranteeCodePreCi
      guaranteecodeid
      guestFirstName
      guestFirstNameSdx
      guestLastNameSdx
      guestSignature
      guestStatus
      guestType
      guestprofileid
      gueststatusid
      guesttypeid
      housekeepingServiceTime
      hurdle
      hurdleOverride
      iDByMembershipClass
      iDByMembershipType
      individualCity
      individualCountry
      individualFirstName
      individualLastName
      insertActionInstanceId
      insertDate
      insertDateTime
      insertUser
      intermediaryYn
      internalAwardMembershipId
      internalBaseratecode
      internalBlockId
      internalCompanyprofileid
      internalGroupprofileid
      internalSourceprofileid
      itemsQuantities
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyValidUntil
      lastOnlinePrintSeq
      lastPeriodicFolioDate
      lastRoomNumber
      lastSettleDate
      leadTimeDays
      lengthOfStay
      linkedArrivalDate
      linkedDepartureDate
      linkedRoomType
      listOfMembershipID
      localBaseRateAmount
      locationID
      loyaltySchemeMembershipYN
      mailYn
      manualCheckoutStatus
      marketCode
      marketid
      mcGenBeginDistrict
      mcGenBeginState
      mcGenEndDistrict
      mcGenEndState
      mcGenNextCountry
      mcGenPreviousCountry
      memberDescription
      memberLevel
      memberNumber
      membershipClass
      membershipClassDescription
      membershipCode
      membershipId
      membershipLevelByMembershipClass
      membershipTypeByMembershipClass
      mobileActionAlertIssued
      mobileAudioKeyYn
      mobileCheckinAllowedYn
      mobileChkoutAllowed
      mobilePreferredCurrency
      mobileViewFolioAllowed
      name
      nameUsageType
      nextCountry
      nextDestination
      numberOfRooms
      operaEsignedRegCardYn
      optInBatchFolYn
      optedForCommissionYN
      organizationID
      originCode
      originOfBooking
      originalBaseRate
      originalEndDate
      originalStartDate
      ownerFfFlag
      ownerOrFriendsFamily
      packageCode
      packageCodeDescription
      packageForecastGroup
      packageForecastGroupDescription
      parentReservationNameId
      parentreservationid
      partAllotment
      partyCode
      paxNo
      paymentAmount
      paymentMethod
      paymentmethodid
      periodicFolioFreq
      phoneDisplayNameYn
      phoneId
      physicalQuantity
      pickUpCarrierCode
      pickUpDate
      pickUpStation
      pickUpTransportNumber
      pickUpType
      pickUpTypeDescription
      pickUpTime
      pickupRequiredYN
      points
      pointsEligibilityCode
      postCoFlag
      postStayChargingYN
      postingAllowedYN
      preArrReviewedDt
      preArrReviewedUser
      preChargingYn
      preRegisteredYn
      preference
      preferenceType
      preferredRoomType
      previousCountry
      primaryKeyID
      primaryShare
      printRateYN
      projectedFBRevenue
      projectedRoomRevenue
      projectedTotalRevenue
      promotionCode
      promotionDescription
      property
      pseudoMemTotalPoints
      pseudoMemType
      purgeDate
      purposeOfStay
      quantity
      queuePriority
      queueWaitTime
      quoteId
      rateAmount
      rateCode
      rateCodeDescriptions
      rateTier
      rateableValue
      ratecodeid
      rdHousekeepingExpectedServiceTime
      rdResvStatus
      rdenBillingContactId
      rdenReservationContactId
      rdenReservationDate
      rdenResort
      referralYn
      registrationCardNo
      registrationNumber
      reinstateDate
      repChannel
      repChannelDescription
      reportId
      resInsertSource
      resInsertSourceType
      reservationContactId
      reservationDate
      reservationNameID
      reservationStatus
      reservationType
      reservationTypeDescription
      reservationid
      resort
      resortChargeNumber
      restrictionOverride
      resvGuid
      resvNameid
      resvNumber
      resvcontactprofileid
      revenueTypeCode
      rhBillingContactId
      rhReservationContactId
      rhRoomFeatures
      rnaInsertDate
      rnaUpdateDate
      room
      roomCategory
      roomClass
      roomCost
      roomInstructions
      roomResort
      roomRevenue
      roomRevenueRemaining
      roomServiceTime
      roomTypeDescription
      roomTypeToChargeCode
      roomTypeToChargeDescription
      roomcategoryid
      roomid
      routingYN
      scheduleCheckoutYn
      sguestFirstname
      sguestName
      shareConfirmationNumbers
      shareId
      shareName
      sharePrcnt
      shareSeqNumber
      shareOfRateAmount
      sharedGuestName
      sharedProfileID
      sharedReservationStatus
      sharingYN
      sourceCity
      sourceCode
      sourceCountry
      sourceName
      sourceProfileARNumber
      sourceProfileARNumberCentral
      sourceProfileIATANumber
      sourceProfileID
      sourceProfileName
      sourceid
      specialRequest
      specialRequestDescription
      spgDiscloseRoomTypeYn
      spgSuiteNightAwardStatus
      spgUpgradeConfirmedRoomtype
      spgUpgradeReasonCode
      splitFromReservationNameId
      splitfromreservationid
      statisticalRateTier
      statisticalRoomType
      stayRecordId
      suiteNumber
      superSearchIndexText
      taRecordLocator
      taxExemptNumber
      taxNumberOfStays
      taxType
      taxTypeDescription
      taxtypeid
      tiad
      ticketNos
      totalCostOfStay
      totalRevenue
      totalRevenueRemaining
      totalRoomRate
      trackItGroups
      trackItTypes
      transactionid
      travelAgentCity
      travelAgentCountry
      travelAgentID
      travelAgentName
      travelAgentProfileARNumber
      travelAgentProfileARNumberCentral
      travelAgentProfileIATANumber
      travelAgentProfileID
      travelAgentProfileName
      truncActualCheckOutDate
      turndownStatus
      turndownYN
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
      uDFC11
      uDFC12
      uDFC13
      uDFC14
      uDFC15
      uDFC16
      uDFC17
      uDFC18
      uDFC19
      uDFC20
      uDFC21
      uDFC22
      uDFC23
      uDFC24
      uDFC25
      uDFC26
      uDFC27
      uDFC28
      uDFC29
      uDFC30
      uDFC31
      uDFC32
      uDFC33
      uDFC34
      uDFC35
      uDFC36
      uDFC37
      uDFC38
      uDFC39
      uDFC40
      uDFD01
      uDFD02
      uDFD03
      uDFD04
      uDFD05
      uDFD06
      uDFD07
      uDFD08
      uDFD09
      uDFD10
      uDFD11
      uDFD12
      uDFD13
      uDFD14
      uDFD15
      uDFD16
      uDFD17
      uDFD18
      uDFD19
      uDFD20
      uDFN01
      uDFN02
      uDFN03
      uDFN04
      uDFN05
      uDFN06
      uDFN07
      uDFN08
      uDFN09
      uDFN10
      uDFN11
      uDFN12
      uDFN13
      uDFN14
      uDFN15
      uDFN16
      uDFN17
      uDFN18
      uDFN19
      uDFN20
      uDFN21
      uDFN22
      uDFN23
      uDFN24
      uDFN25
      uDFN26
      uDFN27
      uDFN28
      uDFN29
      uDFN30
      uDFN31
      uDFN32
      uDFN33
      uDFN34
      uDFN35
      uDFN36
      uDFN37
      uDFN38
      uDFN39
      uDFN40
      uniCardId
      updateDate
      updateDatetime
      updateUser
      updatedBy
      updatedByDefaultResort
      updatedDate
      updatedTime
      upsellCharge
      videoCheckoutYN
      visaExpiryDate
      visaIssueDate
      visaNumber
      waitlistComment
      waitlistPhoneNumber
      waitlistPriority
      waitlistPriorityDescription
      waitlistReason
      waitlistReasonDescription
      waitlistpriorityid
      waitlistreasonid
      walkInYN
      yieldableYn
      ymCode
    }
  }
}
```

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
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
event_posting_details_schema = {
    'allotmentid': pl.Float64,
    'blockBeginDate': pl.Utf8,
    'blockEndDate': pl.Utf8,
    'bookId': pl.Float64,
    'businessDate': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cPostedToExtra': pl.Float64,
    'cPostedToIncl': pl.Float64,
    'cSvcTaxExtra': pl.Float64,
    'cSvcTaxInclude': pl.Float64,
    'cTaxExtra': pl.Float64,
    'cTaxIncl': pl.Float64,
    'cTransactionExtra': pl.Float64,
    'cTransactionIncl': pl.Float64,
    'calculationRuleExtra': pl.Utf8,
    'calculationRuleIncluded': pl.Utf8,
    'centralPostingRevenueExtra': pl.Float64,
    'centralRevenueIncluded': pl.Float64,
    'centralServiceChargeIncluded': pl.Float64,
    'centralServiceChargeExtra': pl.Float64,
    'centralTaxType': pl.Utf8,
    'centralTaxTypeDescription': pl.Utf8,
    'centralUnitPrice': pl.Float64,
    'checkNumber': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'evPostId': pl.Float64,
    'eventId': pl.Float64,
    'eventpostingid': pl.Float64,
    'extraallotmentid': pl.Float64,
    'extraforresvid': pl.Float64,
    'extratranscodeid': pl.Utf8,
    'includedallotmentid': pl.Float64,
    'includedforresvid': pl.Float64,
    'includedtranscodeid': pl.Utf8,
    'insertUser': pl.Int64,
    'internalEventid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'postedById': pl.Float64,
    'postedByUserName': pl.Utf8,
    'postedDateExtra': pl.Utf8,
    'postedDateIncluded': pl.Utf8,
    'postedToExtra': pl.Float64,
    'postedToIncl': pl.Float64,
    'postedYN': pl.Utf8,
    'postedByProperty': pl.Utf8,
    'postedToRoomExtra': pl.Utf8,
    'postedToRoomIncluded': pl.Utf8,
    'postingRevenueExtra': pl.Float64,
    'postinglocationid': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'resourceName': pl.Utf8,
    'resourceType': pl.Utf8,
    'revenueIncluded': pl.Float64,
    'revenueType': pl.Utf8,
    'revenuetypeid': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'serviceChargeIncluded': pl.Float64,
    'serviceChargePercentExtra': pl.Float64,
    'serviceChargePercentIncluded': pl.Float64,
    'serviceChargeTransactionCode': pl.Utf8,
    'serviceChargeExtra': pl.Float64,
    'svcTaxExtra': pl.Float64,
    'svcTaxInclude': pl.Float64,
    'svcTrxCodeExtra': pl.Utf8,
    'svcTrxNumberExtra': pl.Float64,
    'svcTrxNumberIncl': pl.Float64,
    'taxExtra': pl.Float64,
    'taxIncl': pl.Float64,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'transactionCodeExtraRevenue': pl.Utf8,
    'transactionCodeIncludedRevenue': pl.Utf8,
    'trxExtra': pl.Float64,
    'trxIncl': pl.Float64,
    'trxNumberExtra': pl.Float64,
    'trxNumberIncl': pl.Float64,
    'unitPrice': pl.Float64,
    'units': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
property_budget_forecast_details_schema = {
    'accountingType': pl.Utf8,
    'accountingYear': pl.Float64,
    'budgetCode': pl.Utf8,
    'budgetCodeDescription': pl.Utf8,
    'budgetType': pl.Utf8,
    'budgetValue': pl.Utf8,
    'budgetValueDescription': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralRevenue': pl.Float64,
    'covers': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'lockedYN': pl.Utf8,
    'organizationID': pl.Int64,
    'periodType': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'revenue': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomNights': pl.Float64,
    'startDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
export_map_fintrxcodes_details_schema = {
    'chainCode': pl.Utf8,
    'codeCanDeleteYn': pl.Utf8,
    'codeInsertDate': pl.Utf8,
    'codeInsertUser': pl.Float64,
    'codeInsertUserName': pl.Utf8,
    'codeUpdateDate': pl.Utf8,
    'codeUpdateUser': pl.Float64,
    'codeUpdateUserName': pl.Utf8,
    'combinedMappingYn': pl.Utf8,
    'dSI': pl.Int64,
    'dataType': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'exportMappingId': pl.Float64,
    'exportValue': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'linkInsertDate': pl.Utf8,
    'linkInsertUser': pl.Float64,
    'linkInsertUserName': pl.Utf8,
    'linkUpdateDate': pl.Utf8,
    'linkUpdateUser': pl.Float64,
    'linkUpdateUserName': pl.Utf8,
    'linkedCode': pl.Utf8,
    'linkedDescription': pl.Utf8,
    'locationID': pl.Utf8,
    'lovName': pl.Utf8,
    'mappedToCode': pl.Utf8,
    'mappedToDescription': pl.Utf8,
    'mappingCode': pl.Utf8,
    'mappingCodeDescription': pl.Utf8,
    'mappingTypeCode': pl.Utf8,
    'mappingTypeDescription': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'requiredYn': pl.Utf8,
    'seqNumber': pl.Float64,
    'shortColumnTitle': pl.Utf8,
    'trxCode': pl.Utf8,
    'typeCanDeleteYn': pl.Utf8,
    'typeInsertDate': pl.Utf8,
    'typeInsertUser': pl.Float64,
    'typeInsertUserName': pl.Utf8,
    'typeUpdateDate': pl.Utf8,
    'typeUpdateUser': pl.Float64,
    'typeUpdateUserName': pl.Utf8,
    'useLovYn': pl.Utf8,
}
```
```python
export_map_pay_meth_details_schema = {
    'chainCode': pl.Utf8,
    'codeCanDeleteYn': pl.Utf8,
    'codeInsertDate': pl.Utf8,
    'codeInsertUser': pl.Float64,
    'codeInsertUserName': pl.Utf8,
    'codeUpdateDate': pl.Utf8,
    'codeUpdateUser': pl.Float64,
    'codeUpdateUserName': pl.Utf8,
    'combinedMappingYn': pl.Utf8,
    'dSI': pl.Int64,
    'dataType': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'exportMappingId': pl.Float64,
    'exportValue': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'linkInsertDate': pl.Utf8,
    'linkInsertUser': pl.Float64,
    'linkInsertUserName': pl.Utf8,
    'linkUpdateDate': pl.Utf8,
    'linkUpdateUser': pl.Float64,
    'linkUpdateUserName': pl.Utf8,
    'linkedCode': pl.Utf8,
    'linkedDescription': pl.Utf8,
    'locationID': pl.Utf8,
    'lovName': pl.Utf8,
    'mappedToCode': pl.Utf8,
    'mappedToDescription': pl.Utf8,
    'mappingCode': pl.Utf8,
    'mappingCodeDescription': pl.Utf8,
    'mappingTypeCode': pl.Utf8,
    'mappingTypeDescription': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'requiredYn': pl.Utf8,
    'seqNumber': pl.Float64,
    'shortColumnTitle': pl.Utf8,
    'trxCode': pl.Utf8,
    'typeCanDeleteYn': pl.Utf8,
    'typeInsertDate': pl.Utf8,
    'typeInsertUser': pl.Float64,
    'typeInsertUserName': pl.Utf8,
    'typeUpdateDate': pl.Utf8,
    'typeUpdateUser': pl.Float64,
    'typeUpdateUserName': pl.Utf8,
    'useLovYn': pl.Utf8,
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
article_details_schema = {
    'activeYN': pl.Utf8,
    'articleCode': pl.Utf8,
    'articleDescription': pl.Utf8,
    'articleId': pl.Float64,
    'availableInPostItYN': pl.Utf8,
    'cDefaultPrice': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralArticleCode': pl.Utf8,
    'centralArticleDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'centralTransactionCode': pl.Utf8,
    'dSI': pl.Int64,
    'defaultPrice': pl.Float64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalArticleid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'transactionCode': pl.Utf8,
    'transcodeid': pl.Utf8,
    'uPC': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
calendar_period_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
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
cashier_details_schema = {
    'activeYN': pl.Utf8,
    'amtDifferenceInitial': pl.Float64,
    'attachedToUser': pl.Utf8,
    'cAmountDifferenceInitial': pl.Float64,
    'cAmountFloat': pl.Float64,
    'cCashierBalance': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cashierBal': pl.Float64,
    'cashierid': pl.Float64,
    'chainCode': pl.Utf8,
    'closureInProgressYn': pl.Utf8,
    'closureNo': pl.Float64,
    'csrTrxNumber': pl.Float64,
    'dSI': pl.Int64,
    'dateoflastuse': pl.Utf8,
    'deletedflag': pl.Utf8,
    'floatOverShort': pl.Utf8,
    'generalCashierYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'interfaceCashierYN': pl.Utf8,
    'internalUpdateYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'kioskCashierYN': pl.Utf8,
    'lastOpened': pl.Utf8,
    'locationID': pl.Utf8,
    'maximumDailyUses': pl.Float64,
    'organizationID': pl.Int64,
    'paymentsCashierCode': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'reservedResort': pl.Utf8,
    'reservedYn': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'startingAmount': pl.Float64,
    'state': pl.Utf8,
    'timeoffirstopen': pl.Utf8,
    'timeoflastclose': pl.Utf8,
    'timesOpened': pl.Float64,
    'tranActionId': pl.Float64,
    'transactionsCashierName': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
employee_details_schema = {
    'accessConfig': pl.Utf8,
    'accessEod': pl.Utf8,
    'accessObi': pl.Utf8,
    'accessOcis': pl.Utf8,
    'accessOcm': pl.Utf8,
    'accessOcrm': pl.Utf8,
    'accessOrms': pl.Utf8,
    'accessOrs': pl.Utf8,
    'accessOxi': pl.Utf8,
    'accessOxihub': pl.Utf8,
    'accessPms': pl.Utf8,
    'accessSc': pl.Utf8,
    'accessScbi': pl.Utf8,
    'accessSfa': pl.Utf8,
    'accessUtil': pl.Utf8,
    'accountLockedOutYn': pl.Utf8,
    'agent': pl.Utf8,
    'appUserType': pl.Utf8,
    'authorizerInactiveDate': pl.Utf8,
    'authorizerRateCode': pl.Utf8,
    'authorizerYn': pl.Utf8,
    'birthDate': pl.Utf8,
    'businessTitle': pl.Utf8,
    'businessTitleDescription': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cHourlyRate': pl.Float64,
    'cWeeklySalary': pl.Float64,
    'dSI': pl.Int64,
    'dateHired': pl.Utf8,
    'defCashierId': pl.Float64,
    'defaultForm': pl.Utf8,
    'defaultMfnResort': pl.Utf8,
    'defaultReportgroup': pl.Utf8,
    'defaultResort': pl.Utf8,
    'deletedflag': pl.Utf8,
    'departmentid': pl.Utf8,
    'deptEmail': pl.Utf8,
    'deptId': pl.Utf8,
    'deptManagerPager': pl.Utf8,
    'deptName': pl.Utf8,
    'deptOrderBy': pl.Float64,
    'disabledUntil': pl.Utf8,
    'eMail': pl.Utf8,
    'empExtension': pl.Utf8,
    'empStatus': pl.Utf8,
    'employeeIncentiveNumber': pl.Utf8,
    'employeeNumber': pl.Utf8,
    'employeeid': pl.Float64,
    'expiresOn': pl.Utf8,
    'first': pl.Utf8,
    'forcePasswordChangeYn': pl.Utf8,
    'fridayMax': pl.Float64,
    'fridayMin': pl.Float64,
    'generalFilepath': pl.Utf8,
    'graceLogin': pl.Float64,
    'hireType': pl.Utf8,
    'hourlyRate': pl.Float64,
    'hoursPerWeek': pl.Float64,
    'inactiveDesc': pl.Utf8,
    'inactiveFrom': pl.Utf8,
    'inactiveReasonCode': pl.Utf8,
    'inactiveTo': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopId': pl.Float64,
    'last': pl.Utf8,
    'leadAddress': pl.Utf8,
    'leadAddressDet': pl.Utf8,
    'leadComm': pl.Utf8,
    'locationID': pl.Utf8,
    'lockoutDate': pl.Utf8,
    'loginCro': pl.Utf8,
    'loginDomain': pl.Utf8,
    'maleFemale': pl.Utf8,
    'maxCheckoutDays': pl.Float64,
    'maxUserSessions': pl.Float64,
    'mfnUserType': pl.Utf8,
    'middle': pl.Utf8,
    'mobileAlertsYn': pl.Utf8,
    'mondayMax': pl.Float64,
    'mondayMin': pl.Float64,
    'nameNotes': pl.Utf8,
    'organizationID': pl.Int64,
    'otMultiplier': pl.Float64,
    'passwordChangeDays': pl.Float64,
    'passwordLastChange': pl.Utf8,
    'personNameId': pl.Float64,
    'phoneNo': pl.Utf8,
    'phoneNumber': pl.Utf8,
    'preventAccountLockout': pl.Utf8,
    'primaryBlockOwnerName': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryRoomsOwnerCode': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateType': pl.Utf8,
    'receiveBroadcastMsg': pl.Utf8,
    'rehireYn': pl.Utf8,
    'salaryInterval': pl.Utf8,
    'saturdayMax': pl.Float64,
    'saturdayMin': pl.Float64,
    'serviceRequestAlertsYn': pl.Utf8,
    'sfaName': pl.Utf8,
    'srepGroup': pl.Utf8,
    'sundayMax': pl.Float64,
    'sundayMin': pl.Float64,
    'termReason': pl.Utf8,
    'terminatedDate': pl.Utf8,
    'territory': pl.Utf8,
    'thursdayMax': pl.Float64,
    'thursdayMin': pl.Float64,
    'timezoneRegion': pl.Utf8,
    'tuesdayMax': pl.Float64,
    'tuesdayMin': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'userFilepath': pl.Utf8,
    'userID': pl.Float64,
    'userPbxId': pl.Float64,
    'wednesdayMax': pl.Float64,
    'wednesdayMin': pl.Float64,
    'weekMax': pl.Float64,
    'weekMin': pl.Float64,
    'weeklySalary': pl.Float64,
    'workPermitExpdate': pl.Utf8,
    'workPermitNo': pl.Utf8,
}
```
```python
export_map_packagecodes_details_schema = {
    'chainCode': pl.Utf8,
    'codeCanDeleteYn': pl.Utf8,
    'codeInsertDate': pl.Utf8,
    'codeInsertUser': pl.Float64,
    'codeInsertUserName': pl.Utf8,
    'codeUpdateDate': pl.Utf8,
    'codeUpdateUser': pl.Float64,
    'codeUpdateUserName': pl.Utf8,
    'combinedMappingYn': pl.Utf8,
    'dSI': pl.Int64,
    'dataType': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'exportMappingId': pl.Float64,
    'exportValue': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'linkInsertDate': pl.Utf8,
    'linkInsertUser': pl.Float64,
    'linkInsertUserName': pl.Utf8,
    'linkUpdateDate': pl.Utf8,
    'linkUpdateUser': pl.Float64,
    'linkUpdateUserName': pl.Utf8,
    'linkedCode': pl.Utf8,
    'linkedDescription': pl.Utf8,
    'locationID': pl.Utf8,
    'lovName': pl.Utf8,
    'mappedToCode': pl.Utf8,
    'mappedToDescription': pl.Utf8,
    'mappingCode': pl.Utf8,
    'mappingCodeDescription': pl.Utf8,
    'mappingTypeCode': pl.Utf8,
    'mappingTypeDescription': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'product': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'requiredYn': pl.Utf8,
    'seqNumber': pl.Float64,
    'shortColumnTitle': pl.Utf8,
    'typeCanDeleteYn': pl.Utf8,
    'typeInsertDate': pl.Utf8,
    'typeInsertUser': pl.Float64,
    'typeInsertUserName': pl.Utf8,
    'typeUpdateDate': pl.Utf8,
    'typeUpdateUser': pl.Float64,
    'typeUpdateUserName': pl.Utf8,
    'useLovYn': pl.Utf8,
}
```
```python
financial_period_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
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
folio_tax_details_schema = {
    'accountCode': pl.Float64,
    'addresseeNameId': pl.Float64,
    'amountPostedFromAR': pl.Float64,
    'amountFromDirectBill': pl.Float64,
    'associatedBillDate': pl.Utf8,
    'associatedBillNumber': pl.Utf8,
    'associatedFiscalBillDate': pl.Utf8,
    'associatedFiscalBillNumber': pl.Utf8,
    'associatedFiscalBillNumberGenerationTime': pl.Utf8,
    'associatedSeqNumber': pl.Float64,
    'billGenerationDate': pl.Utf8,
    'billNumber': pl.Float64,
    'billPaymentTrxNumber': pl.Float64,
    'billPrefix': pl.Utf8,
    'billSequenceNumber': pl.Float64,
    'billStartDate': pl.Utf8,
    'billStatus': pl.Utf8,
    'businessDate': pl.Utf8,
    'businessId': pl.Utf8,
    'cCashpay': pl.Float64,
    'cCcpay': pl.Float64,
    'cClarpay': pl.Float64,
    'cClpay': pl.Float64,
    'cCollectionTax1': pl.Float64,
    'cCollectionTax2': pl.Float64,
    'cCollectionTax3': pl.Float64,
    'cCollectionTax4': pl.Float64,
    'cCollectionTax5': pl.Float64,
    'cDailyRunningTotal': pl.Float64,
    'cDeposit': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFiscalInvoiceCurrencyRate': pl.Float64,
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
    'cPaidout': pl.Float64,
    'cPerpetualAmount': pl.Float64,
    'cPnet1Amount': pl.Float64,
    'cPnet10Amount': pl.Float64,
    'cPnet11Amount': pl.Float64,
    'cPnet12Amount': pl.Float64,
    'cPnet13Amount': pl.Float64,
    'cPnet14Amount': pl.Float64,
    'cPnet15Amount': pl.Float64,
    'cPnet16Amount': pl.Float64,
    'cPnet17Amount': pl.Float64,
    'cPnet18Amount': pl.Float64,
    'cPnet19Amount': pl.Float64,
    'cPnet2Amount': pl.Float64,
    'cPnet20Amount': pl.Float64,
    'cPnet3Amount': pl.Float64,
    'cPnet4Amount': pl.Float64,
    'cPnet5Amount': pl.Float64,
    'cPnet6Amount': pl.Float64,
    'cPnet7Amount': pl.Float64,
    'cPnet8Amount': pl.Float64,
    'cPnet9Amount': pl.Float64,
    'cPtax1Amount': pl.Float64,
    'cPtax10Amount': pl.Float64,
    'cPtax11Amount': pl.Float64,
    'cPtax12Amount': pl.Float64,
    'cPtax13Amount': pl.Float64,
    'cPtax14Amount': pl.Float64,
    'cPtax15Amount': pl.Float64,
    'cPtax16Amount': pl.Float64,
    'cPtax17Amount': pl.Float64,
    'cPtax18Amount': pl.Float64,
    'cPtax19Amount': pl.Float64,
    'cPtax2Amount': pl.Float64,
    'cPtax20Amount': pl.Float64,
    'cPtax3Amount': pl.Float64,
    'cPtax4Amount': pl.Float64,
    'cPtax5Amount': pl.Float64,
    'cPtax6Amount': pl.Float64,
    'cPtax7Amount': pl.Float64,
    'cPtax8Amount': pl.Float64,
    'cPtax9Amount': pl.Float64,
    'cPtotNonrevNonTaxable': pl.Float64,
    'cPtotNonrevTaxable': pl.Float64,
    'cPtotRevenueNonTaxable': pl.Float64,
    'cPtotRevenueTaxable': pl.Float64,
    'cRealPerpetualAmount': pl.Float64,
    'cTax1Amount': pl.Float64,
    'cTax2Amount': pl.Float64,
    'cTaxCode1': pl.Utf8,
    'cTaxCode10': pl.Utf8,
    'cTaxCode11': pl.Utf8,
    'cTaxCode12': pl.Utf8,
    'cTaxCode13': pl.Utf8,
    'cTaxCode14': pl.Utf8,
    'cTaxCode15': pl.Utf8,
    'cTaxCode16': pl.Utf8,
    'cTaxCode17': pl.Utf8,
    'cTaxCode18': pl.Utf8,
    'cTaxCode19': pl.Utf8,
    'cTaxCode2': pl.Utf8,
    'cTaxCode20': pl.Utf8,
    'cTaxCode3': pl.Utf8,
    'cTaxCode4': pl.Utf8,
    'cTaxCode5': pl.Utf8,
    'cTaxCode6': pl.Utf8,
    'cTaxCode7': pl.Utf8,
    'cTaxCode8': pl.Utf8,
    'cTaxCode9': pl.Utf8,
    'cTaxCodeDescription1': pl.Utf8,
    'cTaxCodeDescription10': pl.Utf8,
    'cTaxCodeDescription11': pl.Utf8,
    'cTaxCodeDescription12': pl.Utf8,
    'cTaxCodeDescription13': pl.Utf8,
    'cTaxCodeDescription14': pl.Utf8,
    'cTaxCodeDescription15': pl.Utf8,
    'cTaxCodeDescription16': pl.Utf8,
    'cTaxCodeDescription17': pl.Utf8,
    'cTaxCodeDescription18': pl.Utf8,
    'cTaxCodeDescription19': pl.Utf8,
    'cTaxCodeDescription2': pl.Utf8,
    'cTaxCodeDescription20': pl.Utf8,
    'cTaxCodeDescription3': pl.Utf8,
    'cTaxCodeDescription4': pl.Utf8,
    'cTaxCodeDescription5': pl.Utf8,
    'cTaxCodeDescription6': pl.Utf8,
    'cTaxCodeDescription7': pl.Utf8,
    'cTaxCodeDescription8': pl.Utf8,
    'cTaxCodeDescription9': pl.Utf8,
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
    'cTotalGross': pl.Float64,
    'cTotalNet': pl.Float64,
    'cTotalNonTaxable': pl.Float64,
    'cTotalNonrevNonTaxable': pl.Float64,
    'cTotalNonrevTaxable': pl.Float64,
    'cTotalRevenueNonTaxable': pl.Float64,
    'cTotalRevenueTaxable': pl.Float64,
    'cTotalTax': pl.Float64,
    'cXnet1Amount': pl.Float64,
    'cXnet10Amount': pl.Float64,
    'cXnet11Amount': pl.Float64,
    'cXnet12Amount': pl.Float64,
    'cXnet13Amount': pl.Float64,
    'cXnet14Amount': pl.Float64,
    'cXnet15Amount': pl.Float64,
    'cXnet16Amount': pl.Float64,
    'cXnet17Amount': pl.Float64,
    'cXnet18Amount': pl.Float64,
    'cXnet19Amount': pl.Float64,
    'cXnet2Amount': pl.Float64,
    'cXnet20Amount': pl.Float64,
    'cXnet3Amount': pl.Float64,
    'cXnet4Amount': pl.Float64,
    'cXnet5Amount': pl.Float64,
    'cXnet6Amount': pl.Float64,
    'cXnet7Amount': pl.Float64,
    'cXnet8Amount': pl.Float64,
    'cXnet9Amount': pl.Float64,
    'cXtax1Amount': pl.Float64,
    'cXtax10Amount': pl.Float64,
    'cXtax11Amount': pl.Float64,
    'cXtax12Amount': pl.Float64,
    'cXtax13Amount': pl.Float64,
    'cXtax14Amount': pl.Float64,
    'cXtax15Amount': pl.Float64,
    'cXtax16Amount': pl.Float64,
    'cXtax17Amount': pl.Float64,
    'cXtax18Amount': pl.Float64,
    'cXtax19Amount': pl.Float64,
    'cXtax2Amount': pl.Float64,
    'cXtax20Amount': pl.Float64,
    'cXtax3Amount': pl.Float64,
    'cXtax4Amount': pl.Float64,
    'cXtax5Amount': pl.Float64,
    'cXtax6Amount': pl.Float64,
    'cXtax7Amount': pl.Float64,
    'cXtax8Amount': pl.Float64,
    'cXtax9Amount': pl.Float64,
    'cashRegisterId': pl.Utf8,
    'cashRegisterInvNumber': pl.Float64,
    'cashTotal': pl.Float64,
    'cashierID': pl.Float64,
    'centralTaxRate1': pl.Float64,
    'centralTaxRate10': pl.Float64,
    'centralTaxRate11': pl.Float64,
    'centralTaxRate12': pl.Float64,
    'centralTaxRate13': pl.Float64,
    'centralTaxRate14': pl.Float64,
    'centralTaxRate15': pl.Float64,
    'centralTaxRate16': pl.Float64,
    'centralTaxRate17': pl.Float64,
    'centralTaxRate18': pl.Float64,
    'centralTaxRate19': pl.Float64,
    'centralTaxRate2': pl.Float64,
    'centralTaxRate20': pl.Float64,
    'centralTaxRate3': pl.Float64,
    'centralTaxRate4': pl.Float64,
    'centralTaxRate5': pl.Float64,
    'centralTaxRate6': pl.Float64,
    'centralTaxRate7': pl.Float64,
    'centralTaxRate8': pl.Float64,
    'centralTaxRate9': pl.Float64,
    'city': pl.Utf8,
    'cityLedgerYN': pl.Utf8,
    'clTrxNumber': pl.Float64,
    'collectionAgentTotalTax1': pl.Float64,
    'collectionAgentTotalTax2': pl.Float64,
    'collectionAgentTotalTax3': pl.Float64,
    'collectionAgentTotalTax4': pl.Float64,
    'collectionAgentTotalTax5': pl.Float64,
    'companyFinancialValue': pl.Utf8,
    'companyName': pl.Utf8,
    'companyType': pl.Utf8,
    'compressBillNo': pl.Utf8,
    'creditBillGeneratedYN': pl.Utf8,
    'creditBillNumber': pl.Float64,
    'creditCardTotal': pl.Float64,
    'customNumber1': pl.Utf8,
    'customNumber2': pl.Utf8,
    'customNumber3': pl.Utf8,
    'customNumber4': pl.Utf8,
    'customNumber5': pl.Utf8,
    'dSI': pl.Int64,
    'dailyRunningTotal': pl.Float64,
    'deletedFlag': pl.Utf8,
    'deposit': pl.Float64,
    'depositReqReceiptNumber': pl.Float64,
    'documentCode': pl.Utf8,
    'documentType': pl.Utf8,
    'eArchiveEttnNumber': pl.Utf8,
    'eArchiveNumber': pl.Utf8,
    'eArchiveReportNo': pl.Utf8,
    'eArchiveStatus': pl.Utf8,
    'eInvoiceNumber': pl.Utf8,
    'eInvoiceStatus': pl.Utf8,
    'fiscalBillCheckDigit': pl.Float64,
    'fiscalBillGenerationDate': pl.Utf8,
    'fiscalBillGenerationTime': pl.Utf8,
    'fiscalBillNumber': pl.Utf8,
    'fiscalInvoiceCurrency': pl.Utf8,
    'fiscalInvoiceCurrencyRate': pl.Float64,
    'fiscalSessionNo': pl.Utf8,
    'fiscalUnitControlCode': pl.Utf8,
    'folioAddress': pl.Utf8,
    'folioAddressCorrectedYn': pl.Utf8,
    'folioAttachmentLinkId': pl.Float64,
    'folioAttachmentStatus': pl.Float64,
    'folioNo': pl.Float64,
    'folioStyle': pl.Utf8,
    'folioTaxSeqNumber': pl.Float64,
    'folioTime': pl.Utf8,
    'folioType': pl.Utf8,
    'folioType1': pl.Utf8,
    'folioTypeJoin': pl.Utf8,
    'folioView': pl.Float64,
    'forexTaxYn': pl.Utf8,
    'fullFolioNo': pl.Utf8,
    'hasWatermarkYn': pl.Utf8,
    'hotelName': pl.Utf8,
    'insTimestamp': pl.Utf8,
    'insertDate': pl.Utf8,
    'invoiceNumber': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastSignature': pl.Utf8,
    'locationID': pl.Utf8,
    'nRBusinessID': pl.Utf8,
    'nafApeHotelCode': pl.Utf8,
    'nameId': pl.Float64,
    'nameTaxType': pl.Utf8,
    'netAmount1': pl.Float64,
    'netAmount10': pl.Float64,
    'netAmount11': pl.Float64,
    'netAmount12': pl.Float64,
    'netAmount13': pl.Float64,
    'netAmount14': pl.Float64,
    'netAmount15': pl.Float64,
    'netAmount16': pl.Float64,
    'netAmount17': pl.Float64,
    'netAmount18': pl.Float64,
    'netAmount19': pl.Float64,
    'netAmount2': pl.Float64,
    'netAmount20': pl.Float64,
    'netAmount3': pl.Float64,
    'netAmount4': pl.Float64,
    'netAmount5': pl.Float64,
    'netAmount6': pl.Float64,
    'netAmount7': pl.Float64,
    'netAmount8': pl.Float64,
    'netAmount9': pl.Float64,
    'numberOfPages': pl.Float64,
    'operaFiscalFolioStatus': pl.Utf8,
    'organizationID': pl.Int64,
    'pageNumber': pl.Float64,
    'palmVideoFlag': pl.Utf8,
    'partnerFiscalFolioStatus': pl.Utf8,
    'payeeAddress': pl.Utf8,
    'payeeCountry': pl.Utf8,
    'payeeFirstName': pl.Utf8,
    'payeeLastName': pl.Utf8,
    'payeeName': pl.Utf8,
    'payeeNameID': pl.Float64,
    'payeePostalCode': pl.Utf8,
    'payeeTaxID1': pl.Utf8,
    'payeeTaxID2': pl.Utf8,
    'payeeZipCode': pl.Utf8,
    'paymentDate': pl.Utf8,
    'perpetualAmount': pl.Float64,
    'pnet1Amt': pl.Float64,
    'pnet10Amt': pl.Float64,
    'pnet11Amt': pl.Float64,
    'pnet12Amt': pl.Float64,
    'pnet13Amt': pl.Float64,
    'pnet14Amt': pl.Float64,
    'pnet15Amt': pl.Float64,
    'pnet16Amt': pl.Float64,
    'pnet17Amt': pl.Float64,
    'pnet18Amt': pl.Float64,
    'pnet19Amt': pl.Float64,
    'pnet2Amt': pl.Float64,
    'pnet20Amt': pl.Float64,
    'pnet3Amt': pl.Float64,
    'pnet4Amt': pl.Float64,
    'pnet5Amt': pl.Float64,
    'pnet6Amt': pl.Float64,
    'pnet7Amt': pl.Float64,
    'pnet8Amt': pl.Float64,
    'pnet9Amt': pl.Float64,
    'postitSequenceNumber': pl.Float64,
    'postitYN': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'printerQueueName': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'promotionalText1': pl.Utf8,
    'promotionalText2': pl.Utf8,
    'property': pl.Utf8,
    'propertyBillPrefix': pl.Utf8,
    'propertyTaxNumber': pl.Utf8,
    'ptax1Amt': pl.Float64,
    'ptax10Amt': pl.Float64,
    'ptax11Amt': pl.Float64,
    'ptax12Amt': pl.Float64,
    'ptax13Amt': pl.Float64,
    'ptax14Amt': pl.Float64,
    'ptax15Amt': pl.Float64,
    'ptax16Amt': pl.Float64,
    'ptax17Amt': pl.Float64,
    'ptax18Amt': pl.Float64,
    'ptax19Amt': pl.Float64,
    'ptax2Amt': pl.Float64,
    'ptax20Amt': pl.Float64,
    'ptax3Amt': pl.Float64,
    'ptax4Amt': pl.Float64,
    'ptax5Amt': pl.Float64,
    'ptax6Amt': pl.Float64,
    'ptax7Amt': pl.Float64,
    'ptax8Amt': pl.Float64,
    'ptax9Amt': pl.Float64,
    'ptotNonrevNonTaxable': pl.Float64,
    'ptotNonrevTaxable': pl.Float64,
    'ptotRevNonTaxable': pl.Float64,
    'ptotRevTaxable': pl.Float64,
    'realPerpetualAmount': pl.Float64,
    'reservationNameId': pl.Float64,
    'resortCity': pl.Utf8,
    'resortCountry': pl.Utf8,
    'resortFullAddress': pl.Utf8,
    'resortZipcodeCode': pl.Utf8,
    'revisionNo': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomNumber': pl.Utf8,
    'seqNumber': pl.Float64,
    'signature': pl.Utf8,
    'signatureKeyVersion': pl.Utf8,
    'softwareVersion': pl.Utf8,
    'tax1RateType': pl.Utf8,
    'tax2RateType': pl.Utf8,
    'taxAmount1': pl.Float64,
    'taxAmount10': pl.Float64,
    'taxAmount11': pl.Float64,
    'taxAmount12': pl.Float64,
    'taxAmount13': pl.Float64,
    'taxAmount14': pl.Float64,
    'taxAmount15': pl.Float64,
    'taxAmount16': pl.Float64,
    'taxAmount17': pl.Float64,
    'taxAmount18': pl.Float64,
    'taxAmount19': pl.Float64,
    'taxAmount2': pl.Float64,
    'taxAmount20': pl.Float64,
    'taxAmount3': pl.Float64,
    'taxAmount4': pl.Float64,
    'taxAmount5': pl.Float64,
    'taxAmount6': pl.Float64,
    'taxAmount7': pl.Float64,
    'taxAmount8': pl.Float64,
    'taxAmount9': pl.Float64,
    'taxCode1': pl.Utf8,
    'taxCode10': pl.Utf8,
    'taxCode11': pl.Utf8,
    'taxCode12': pl.Utf8,
    'taxCode13': pl.Utf8,
    'taxCode14': pl.Utf8,
    'taxCode15': pl.Utf8,
    'taxCode16': pl.Utf8,
    'taxCode17': pl.Utf8,
    'taxCode18': pl.Utf8,
    'taxCode19': pl.Utf8,
    'taxCode2': pl.Utf8,
    'taxCode20': pl.Utf8,
    'taxCode3': pl.Utf8,
    'taxCode4': pl.Utf8,
    'taxCode5': pl.Utf8,
    'taxCode6': pl.Utf8,
    'taxCode7': pl.Utf8,
    'taxCode8': pl.Utf8,
    'taxCode9': pl.Utf8,
    'taxCodeDesc1': pl.Utf8,
    'taxCodeDesc10': pl.Utf8,
    'taxCodeDesc11': pl.Utf8,
    'taxCodeDesc12': pl.Utf8,
    'taxCodeDesc13': pl.Utf8,
    'taxCodeDesc14': pl.Utf8,
    'taxCodeDesc15': pl.Utf8,
    'taxCodeDesc16': pl.Utf8,
    'taxCodeDesc17': pl.Utf8,
    'taxCodeDesc18': pl.Utf8,
    'taxCodeDesc19': pl.Utf8,
    'taxCodeDesc2': pl.Utf8,
    'taxCodeDesc20': pl.Utf8,
    'taxCodeDesc3': pl.Utf8,
    'taxCodeDesc4': pl.Utf8,
    'taxCodeDesc5': pl.Utf8,
    'taxCodeDesc6': pl.Utf8,
    'taxCodeDesc7': pl.Utf8,
    'taxCodeDesc8': pl.Utf8,
    'taxCodeDesc9': pl.Utf8,
    'taxId': pl.Utf8,
    'taxRate1': pl.Float64,
    'taxRate10': pl.Float64,
    'taxRate11': pl.Float64,
    'taxRate12': pl.Float64,
    'taxRate13': pl.Float64,
    'taxRate14': pl.Float64,
    'taxRate15': pl.Float64,
    'taxRate16': pl.Float64,
    'taxRate17': pl.Float64,
    'taxRate18': pl.Float64,
    'taxRate19': pl.Float64,
    'taxRate2': pl.Float64,
    'taxRate20': pl.Float64,
    'taxRate3': pl.Float64,
    'taxRate4': pl.Float64,
    'taxRate5': pl.Float64,
    'taxRate6': pl.Float64,
    'taxRate7': pl.Float64,
    'taxRate8': pl.Float64,
    'taxRate9': pl.Float64,
    'tax10RateType': pl.Utf8,
    'tax11RateType': pl.Utf8,
    'tax12RateType': pl.Utf8,
    'tax13RateType': pl.Utf8,
    'tax14RateType': pl.Utf8,
    'tax15RateType': pl.Utf8,
    'tax16RateType': pl.Utf8,
    'tax17RateType': pl.Utf8,
    'tax18RateType': pl.Utf8,
    'tax19RateType': pl.Utf8,
    'tax20RateType': pl.Utf8,
    'tax3RateType': pl.Utf8,
    'tax4RateType': pl.Utf8,
    'tax5RateType': pl.Utf8,
    'tax6RateType': pl.Utf8,
    'tax7RateType': pl.Utf8,
    'tax8RateType': pl.Utf8,
    'tax9RateType': pl.Utf8,
    'terminal': pl.Utf8,
    'totalGrossAmount': pl.Float64,
    'totalNetAmount': pl.Float64,
    'totalNonRevenueNonTaxableAmount': pl.Float64,
    'totalNonRevenueTaxableAmount': pl.Float64,
    'totalNonTaxableAmount': pl.Float64,
    'totalNonTaxableRevenue': pl.Float64,
    'totalPaidOuts': pl.Float64,
    'totalTax': pl.Float64,
    'totalTaxableRevenue': pl.Float64,
    'transactLastSignatureHash': pl.Utf8,
    'transactSignatureHash': pl.Utf8,
    'transactSignatureKeyVersion': pl.Utf8,
    'transactionSignature': pl.Utf8,
    'trxServiceType': pl.Utf8,
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
    'uDFC11': pl.Utf8,
    'uDFC12': pl.Utf8,
    'uDFC13': pl.Utf8,
    'uDFC14': pl.Utf8,
    'uDFC15': pl.Utf8,
    'uDFC16': pl.Utf8,
    'uDFC17': pl.Utf8,
    'uDFC18': pl.Utf8,
    'uDFC19': pl.Utf8,
    'uDFC20': pl.Utf8,
    'uDFC21': pl.Utf8,
    'uDFC22': pl.Utf8,
    'uDFC23': pl.Utf8,
    'uDFC24': pl.Utf8,
    'uDFC25': pl.Utf8,
    'uDFC26': pl.Utf8,
    'uDFC27': pl.Utf8,
    'uDFC28': pl.Utf8,
    'uDFC29': pl.Utf8,
    'uDFC30': pl.Utf8,
    'uDFC31': pl.Utf8,
    'uDFC32': pl.Utf8,
    'uDFC33': pl.Utf8,
    'uDFC34': pl.Utf8,
    'uDFC35': pl.Utf8,
    'uDFC36': pl.Utf8,
    'uDFC37': pl.Utf8,
    'uDFC38': pl.Utf8,
    'uDFC39': pl.Utf8,
    'uDFC40': pl.Utf8,
    'uDFD01': pl.Utf8,
    'uDFD02': pl.Utf8,
    'uDFD03': pl.Utf8,
    'uDFD04': pl.Utf8,
    'uDFD05': pl.Utf8,
    'uDFD06': pl.Utf8,
    'uDFD07': pl.Utf8,
    'uDFD08': pl.Utf8,
    'uDFD09': pl.Utf8,
    'uDFD10': pl.Utf8,
    'uDFD11': pl.Utf8,
    'uDFD12': pl.Utf8,
    'uDFD13': pl.Utf8,
    'uDFD14': pl.Utf8,
    'uDFD15': pl.Utf8,
    'uDFD16': pl.Utf8,
    'uDFD17': pl.Utf8,
    'uDFD18': pl.Utf8,
    'uDFD19': pl.Utf8,
    'uDFD20': pl.Utf8,
    'uDFN01': pl.Float64,
    'uDFN02': pl.Float64,
    'uDFN03': pl.Float64,
    'uDFN04': pl.Float64,
    'uDFN05': pl.Float64,
    'uDFN06': pl.Float64,
    'uDFN07': pl.Float64,
    'uDFN08': pl.Float64,
    'uDFN09': pl.Float64,
    'uDFN10': pl.Float64,
    'uDFN11': pl.Float64,
    'uDFN12': pl.Float64,
    'uDFN13': pl.Float64,
    'uDFN14': pl.Float64,
    'uDFN15': pl.Float64,
    'uDFN16': pl.Float64,
    'uDFN17': pl.Float64,
    'uDFN18': pl.Float64,
    'uDFN19': pl.Float64,
    'uDFN20': pl.Float64,
    'uDFN21': pl.Float64,
    'uDFN22': pl.Float64,
    'uDFN23': pl.Float64,
    'uDFN24': pl.Float64,
    'uDFN25': pl.Float64,
    'uDFN26': pl.Float64,
    'uDFN27': pl.Float64,
    'uDFN28': pl.Float64,
    'uDFN29': pl.Float64,
    'uDFN30': pl.Float64,
    'uDFN31': pl.Float64,
    'uDFN32': pl.Float64,
    'uDFN33': pl.Float64,
    'uDFN34': pl.Float64,
    'uDFN35': pl.Float64,
    'uDFN36': pl.Float64,
    'uDFN37': pl.Float64,
    'uDFN38': pl.Float64,
    'uDFN39': pl.Float64,
    'uDFN40': pl.Float64,
    'updTimestamp': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'userID': pl.Float64,
    'userName': pl.Utf8,
    'voidNumber': pl.Float64,
    'voidReason': pl.Utf8,
    'workingDocId': pl.Float64,
    'xnet1Amt': pl.Float64,
    'xnet10Amt': pl.Float64,
    'xnet11Amt': pl.Float64,
    'xnet12Amt': pl.Float64,
    'xnet13Amt': pl.Float64,
    'xnet14Amt': pl.Float64,
    'xnet15Amt': pl.Float64,
    'xnet16Amt': pl.Float64,
    'xnet17Amt': pl.Float64,
    'xnet18Amt': pl.Float64,
    'xnet19Amt': pl.Float64,
    'xnet2Amt': pl.Float64,
    'xnet20Amt': pl.Float64,
    'xnet3Amt': pl.Float64,
    'xnet4Amt': pl.Float64,
    'xnet5Amt': pl.Float64,
    'xnet6Amt': pl.Float64,
    'xnet7Amt': pl.Float64,
    'xnet8Amt': pl.Float64,
    'xnet9Amt': pl.Float64,
    'xtax1Amt': pl.Float64,
    'xtax10Amt': pl.Float64,
    'xtax11Amt': pl.Float64,
    'xtax12Amt': pl.Float64,
    'xtax13Amt': pl.Float64,
    'xtax14Amt': pl.Float64,
    'xtax15Amt': pl.Float64,
    'xtax16Amt': pl.Float64,
    'xtax17Amt': pl.Float64,
    'xtax18Amt': pl.Float64,
    'xtax19Amt': pl.Float64,
    'xtax2Amt': pl.Float64,
    'xtax20Amt': pl.Float64,
    'xtax3Amt': pl.Float64,
    'xtax4Amt': pl.Float64,
    'xtax5Amt': pl.Float64,
    'xtax6Amt': pl.Float64,
    'xtax7Amt': pl.Float64,
    'xtax8Amt': pl.Float64,
    'xtax9Amt': pl.Float64,
}
```
```python
foreign_currency_details_schema = {
    'abbreviation': pl.Utf8,
    'activeYN': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'currencyActionId': pl.Float64,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'currencySymbol': pl.Utf8,
    'dSI': pl.Int64,
    'decimals': pl.Float64,
    'deletedFlag': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'formatMask': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'mobileYn': pl.Utf8,
    'multiply': pl.Float64,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'previousLocalCurrencyYn': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sellCurrency': pl.Utf8,
    'trianMethodYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'usedForCcPaymentsYn': pl.Utf8,
}
```
```python
invoice_payment_details_schema = {
    'appliedAmount': pl.Float64,
    'businessDate': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cashierId': pl.Float64,
    'centralAppliedAmount': pl.Float64,
    'chainCode': pl.Utf8,
    'consumptionTransactionNumber': pl.Float64,
    'consumptionTrx': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'invoicepaymentid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'paymentApplicationId': pl.Float64,
    'paymentTransactionNumber': pl.Float64,
    'paymentTrx': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_all_information_details_schema = {
    'guestProfileID': pl.Float64,
    'aRNumber': pl.Utf8,
    'aRNumberCentral': pl.Utf8,
    'aRCreditLimitYN': pl.Utf8,
    'aRCMailFlag': pl.Utf8,
    'aRCOfficeType': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountBillingContact': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'accountsourceDesc': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeYN': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressId': pl.Float64,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'alienRegistrationNo': pl.Utf8,
    'allResorts': pl.Utf8,
    'alternateEnvelopeGreeting': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'autoEnrollMemberYN': pl.Utf8,
    'availabilityOverride': pl.Utf8,
    'billingCode': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthCountry': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessSegment': pl.Utf8,
    'businessSegmentDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cProfileCreditLimit': pl.Float64,
    'cRSNameid': pl.Float64,
    'ccProfileYn': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralBusinessSegmentDescription': pl.Utf8,
    'centralCorporateIDType': pl.Utf8,
    'centralDefaultKeyword': pl.Utf8,
    'centralGuestTitleCode': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralMailActionDescription': pl.Utf8,
    'centralMailingActionCode': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralStateCode': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralVIPCode': pl.Utf8,
    'centralVIPDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'clientID': pl.Utf8,
    'collectionUserId': pl.Float64,
    'combinedName': pl.Utf8,
    'commPayCentral': pl.Utf8,
    'comments': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodes': pl.Utf8,
    'commissionCurrencyId': pl.Utf8,
    'commissionid': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'companyAlternate': pl.Utf8,
    'companyGroupId': pl.Utf8,
    'companyNameId': pl.Float64,
    'competition': pl.Utf8,
    'competitionDesc': pl.Utf8,
    'contactYN': pl.Utf8,
    'contractNo': pl.Utf8,
    'contractRecvDate': pl.Utf8,
    'corpTypeDesc': pl.Utf8,
    'corporateIDType': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencySymbol': pl.Utf8,
    'dOptInAutoenrollMemberFlg': pl.Utf8,
    'dOptInEmailFlg': pl.Utf8,
    'dOptInGuestPrivFlg': pl.Utf8,
    'dOptInMailListFlg': pl.Utf8,
    'dOptInMarketResearchFlg': pl.Utf8,
    'dOptInPhoneFlg': pl.Utf8,
    'dOptInSmsFlg': pl.Utf8,
    'dOptInThirdPartyFlg': pl.Utf8,
    'dSI': pl.Int64,
    'debtorName': pl.Utf8,
    'decimalPositions': pl.Float64,
    'defaultKeyword': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'deptId': pl.Utf8,
    'description': pl.Utf8,
    'directBillBatchType': pl.Utf8,
    'displayName': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'eInvLiableLastUpdated': pl.Utf8,
    'eInvoiceLiableYn': pl.Utf8,
    'email': pl.Utf8,
    'emailYN': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalDisplayName': pl.Utf8,
    'externalFirstName': pl.Utf8,
    'externalId': pl.Utf8,
    'externalName': pl.Utf8,
    'externalReferenceRequ': pl.Utf8,
    'externalReferenceRequired': pl.Utf8,
    'fMembershipCardNumbers': pl.Utf8,
    'fMembershipClassDesc': pl.Utf8,
    'fMembershipClasses': pl.Utf8,
    'fMembershipCodes': pl.Utf8,
    'fMembershipDescriptions': pl.Utf8,
    'fMembershipIds': pl.Utf8,
    'fMembershipType': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNumber': pl.Utf8,
    'firstName': pl.Utf8,
    'firstNameAlternate': pl.Utf8,
    'firstNameIncognito': pl.Utf8,
    'followOn': pl.Utf8,
    'gDSName': pl.Utf8,
    'gDSTransactionNo': pl.Utf8,
    'gender': pl.Utf8,
    'geographicRegion': pl.Utf8,
    'guestClassification': pl.Utf8,
    'guestCountry': pl.Utf8,
    'guestCurrencyCode': pl.Utf8,
    'guestLanguageCode': pl.Utf8,
    'guestLastName': pl.Utf8,
    'guestMiddleName': pl.Utf8,
    'guestNameSuffix': pl.Utf8,
    'guestPrivilegeYN': pl.Utf8,
    'guestTitleCode': pl.Utf8,
    'hasRequestedMailYN': pl.Utf8,
    'historyYN': pl.Utf8,
    'holdCode': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'idCountry': pl.Utf8,
    'idDate': pl.Utf8,
    'idDocumentAttachId': pl.Float64,
    'idPlace': pl.Utf8,
    'idType': pl.Utf8,
    'immigrationStatus': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'includeInTax1099Yn': pl.Utf8,
    'indexName': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryDesc': pl.Utf8,
    'influence': pl.Utf8,
    'influenceDesc': pl.Utf8,
    'interest': pl.Utf8,
    'internalBillYn': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastGroup': pl.Utf8,
    'lastNameAlternate': pl.Utf8,
    'lastNameIncognito': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRateCode': pl.Utf8,
    'lastRoom': pl.Utf8,
    'lastRoomProperty': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'lastUpdatedResort': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailingActionCode': pl.Utf8,
    'marketResearchYN': pl.Utf8,
    'masterAccountYn': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'nameType': pl.Utf8,
    'nameTypeDescription': pl.Utf8,
    'name2': pl.Utf8,
    'name3': pl.Utf8,
    'nationality': pl.Utf8,
    'nationalityCode': pl.Utf8,
    'negotiatedRateCodes': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Int64,
    'origNameId': pl.Float64,
    'paymentDueDays': pl.Float64,
    'phone': pl.Utf8,
    'phoneWeb': pl.Utf8,
    'phoneYN': pl.Utf8,
    'postalCode': pl.Utf8,
    'postalCodeExtension': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'primaryAddressId': pl.Float64,
    'primaryKeyID': pl.Int64,
    'primaryNameId': pl.Float64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'primaryPhoneId': pl.Float64,
    'priority': pl.Utf8,
    'priorityDesc': pl.Utf8,
    'privacyFlagYN': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileCreditLimit': pl.Float64,
    'profileId': pl.Float64,
    'profileType': pl.Utf8,
    'propertyRegistered': pl.Utf8,
    'protected': pl.Utf8,
    'psuedoProfileYn': pl.Utf8,
    'rateStructure': pl.Utf8,
    'region': pl.Utf8,
    'regionid': pl.Utf8,
    'repAccountTypeDescription': pl.Utf8,
    'repAccountsource': pl.Utf8,
    'repAccountsourceDescription': pl.Utf8,
    'repCompetitionCode': pl.Utf8,
    'repCompetitionDescription': pl.Utf8,
    'repCorpTypeDescription': pl.Utf8,
    'repIndustryCode': pl.Utf8,
    'repIndustryDescription': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repNameType': pl.Utf8,
    'repNameTypeDescription': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repPriorityDescription': pl.Utf8,
    'repRoomsPotential': pl.Utf8,
    'repRoomsPotentialDescription': pl.Utf8,
    'repScope': pl.Utf8,
    'repScopeCity': pl.Utf8,
    'repScopeCityDescription': pl.Utf8,
    'repScopeDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTerritoryDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repeatGuestId': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'requestType': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'resvContact': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomsPotential': pl.Utf8,
    'roomsPotentialDesc': pl.Utf8,
    'sMSYN': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDesc': pl.Utf8,
    'scopeDesc': pl.Utf8,
    'searchName': pl.Utf8,
    'searchNameAlternate': pl.Utf8,
    'sfirst': pl.Utf8,
    'soundExCompany': pl.Utf8,
    'soundExLast': pl.Utf8,
    'srepCode': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDescription': pl.Utf8,
    'summRefCc': pl.Utf8,
    'summRefCurrencyId': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxExemptStatus': pl.Utf8,
    'taxID1': pl.Utf8,
    'taxID2': pl.Utf8,
    'taxOffice': pl.Utf8,
    'taxType': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDesc': pl.Utf8,
    'thirdPartyYN': pl.Utf8,
    'titleAlternate': pl.Utf8,
    'titleName': pl.Utf8,
    'titleSuffix': pl.Float64,
    'totalStay': pl.Float64,
    'tourOperatorType': pl.Utf8,
    'traceCode': pl.Utf8,
    'tracecodeDesc': pl.Utf8,
    'typeOfTax1099': pl.Utf8,
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
    'uDFC11': pl.Utf8,
    'uDFC12': pl.Utf8,
    'uDFC13': pl.Utf8,
    'uDFC14': pl.Utf8,
    'uDFC15': pl.Utf8,
    'uDFC16': pl.Utf8,
    'uDFC17': pl.Utf8,
    'uDFC18': pl.Utf8,
    'uDFC19': pl.Utf8,
    'uDFC20': pl.Utf8,
    'uDFC21': pl.Utf8,
    'uDFC22': pl.Utf8,
    'uDFC23': pl.Utf8,
    'uDFC24': pl.Utf8,
    'uDFC25': pl.Utf8,
    'uDFC26': pl.Utf8,
    'uDFC27': pl.Utf8,
    'uDFC28': pl.Utf8,
    'uDFC29': pl.Utf8,
    'uDFC30': pl.Utf8,
    'uDFC31': pl.Utf8,
    'uDFC32': pl.Utf8,
    'uDFC33': pl.Utf8,
    'uDFC34': pl.Utf8,
    'uDFC35': pl.Utf8,
    'uDFC36': pl.Utf8,
    'uDFC37': pl.Utf8,
    'uDFC38': pl.Utf8,
    'uDFC39': pl.Utf8,
    'uDFC40': pl.Utf8,
    'uDFD01': pl.Utf8,
    'uDFD02': pl.Utf8,
    'uDFD03': pl.Utf8,
    'uDFD04': pl.Utf8,
    'uDFD05': pl.Utf8,
    'uDFD06': pl.Utf8,
    'uDFD07': pl.Utf8,
    'uDFD08': pl.Utf8,
    'uDFD09': pl.Utf8,
    'uDFD10': pl.Utf8,
    'uDFD11': pl.Utf8,
    'uDFD12': pl.Utf8,
    'uDFD13': pl.Utf8,
    'uDFD14': pl.Utf8,
    'uDFD15': pl.Utf8,
    'uDFD16': pl.Utf8,
    'uDFD17': pl.Utf8,
    'uDFD18': pl.Utf8,
    'uDFD19': pl.Utf8,
    'uDFD20': pl.Utf8,
    'uDFN01': pl.Float64,
    'uDFN02': pl.Float64,
    'uDFN03': pl.Float64,
    'uDFN04': pl.Float64,
    'uDFN05': pl.Float64,
    'uDFN06': pl.Float64,
    'uDFN07': pl.Float64,
    'uDFN08': pl.Float64,
    'uDFN09': pl.Float64,
    'uDFN10': pl.Float64,
    'uDFN11': pl.Float64,
    'uDFN12': pl.Float64,
    'uDFN13': pl.Float64,
    'uDFN14': pl.Float64,
    'uDFN15': pl.Float64,
    'uDFN16': pl.Float64,
    'uDFN17': pl.Float64,
    'uDFN18': pl.Float64,
    'uDFN19': pl.Float64,
    'uDFN20': pl.Float64,
    'uDFN21': pl.Float64,
    'uDFN22': pl.Float64,
    'uDFN23': pl.Float64,
    'uDFN24': pl.Float64,
    'uDFN25': pl.Float64,
    'uDFN26': pl.Float64,
    'uDFN27': pl.Float64,
    'uDFN28': pl.Float64,
    'uDFN29': pl.Float64,
    'uDFN30': pl.Float64,
    'uDFN31': pl.Float64,
    'uDFN32': pl.Float64,
    'uDFN33': pl.Float64,
    'uDFN34': pl.Float64,
    'uDFN35': pl.Float64,
    'uDFN36': pl.Float64,
    'uDFN37': pl.Float64,
    'uDFN38': pl.Float64,
    'uDFN39': pl.Float64,
    'uDFN40': pl.Float64,
    'updateDate': pl.Utf8,
    'updateFaxDate': pl.Utf8,
    'updateUser': pl.Int64,
    'uploadDate': pl.Utf8,
    'vIPCode': pl.Utf8,
    'vIPDescription': pl.Utf8,
    'vendorId': pl.Float64,
    'vendorSiteId': pl.Float64,
    'vipAuthorization': pl.Utf8,
    'visaValidityType': pl.Utf8,
    'xdisplayName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}
```
```python
rate_code_details_schema = {
    'aSBRateCycle': pl.Utf8,
    'addition': pl.Utf8,
    'advBaseRateCode': pl.Utf8,
    'advBaseRounding': pl.Utf8,
    'advanceBaseCompareYN': pl.Utf8,
    'advanceDailyBaseYN': pl.Utf8,
    'advanceDailyRateYN': pl.Utf8,
    'alternateRateCode': pl.Utf8,
    'availabilityUpdateYn': pl.Utf8,
    'backToBackYN': pl.Utf8,
    'baseAmount': pl.Float64,
    'baseFltPct': pl.Utf8,
    'baseRateCode': pl.Utf8,
    'baseRounding': pl.Utf8,
    'baseType': pl.Utf8,
    'bbarBaseAmount': pl.Float64,
    'bbarBaseFltPct': pl.Utf8,
    'bbarBaseRounding': pl.Utf8,
    'bbarBasedYn': pl.Utf8,
    'bbarCompareYn': pl.Utf8,
    'bbarYn': pl.Utf8,
    'blockName': pl.Utf8,
    'breakfastInclYn': pl.Utf8,
    'breakfastPrice': pl.Float64,
    'businessDate': pl.Utf8,
    'bypassHurdleYn': pl.Utf8,
    'bypassRankCheckYn': pl.Utf8,
    'cBaseAmount': pl.Float64,
    'cBbarBaseAmount': pl.Float64,
    'cBreakfastPrice': pl.Float64,
    'cDbaseAmount': pl.Float64,
    'cDiscountRateAmount': pl.Float64,
    'cDoubleRoomSupplementPrice': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRateFloor': pl.Float64,
    'cRateLevel': pl.Float64,
    'cRodBaseAmount': pl.Float64,
    'cRoomAssignmentValue': pl.Float64,
    'catPackageCode': pl.Utf8,
    'cateringPackageYN': pl.Utf8,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'centralRateBucket': pl.Utf8,
    'centralRateBucketDescription': pl.Utf8,
    'centralRateCategory': pl.Utf8,
    'centralRateCategoryDescription': pl.Utf8,
    'centralRateClass': pl.Utf8,
    'centralRateClassDescription': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralSourceCode': pl.Utf8,
    'centralSourceDescription': pl.Utf8,
    'centralSourceGroupCode': pl.Utf8,
    'centralSourceGroupDescription': pl.Utf8,
    'changeState': pl.Utf8,
    'commissionPercent': pl.Float64,
    'commissionCode': pl.Utf8,
    'commissionYn': pl.Utf8,
    'commissionablePerc': pl.Float64,
    'commissionableYn': pl.Utf8,
    'complimentaryYN': pl.Utf8,
    'currCodeDecimalPos': pl.Float64,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'dailyRatesYn': pl.Utf8,
    'dayUseYN': pl.Utf8,
    'daysWhenClosedToArrival': pl.Utf8,
    'dbaseAmount': pl.Float64,
    'dbaseCompareYn': pl.Utf8,
    'dbaseFltPct': pl.Utf8,
    'dbaseRateCode': pl.Utf8,
    'dbaseRounding': pl.Utf8,
    'dblRoomSupplementPrice': pl.Float64,
    'defaultToHighestBarYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depositMaturityPreference': pl.Utf8,
    'deptCode': pl.Utf8,
    'discountRateAmount': pl.Float64,
    'discountRatePercentageYn': pl.Utf8,
    'discountYN': pl.Utf8,
    'displaySequence': pl.Float64,
    'displaySet': pl.Utf8,
    'distributeYn': pl.Utf8,
    'doubleRoomSupplementYN': pl.Utf8,
    'endDate': pl.Utf8,
    'eventProperty': pl.Utf8,
    'exchangeType': pl.Utf8,
    'externallyControlledYN': pl.Utf8,
    'extraPersonChargeBegins': pl.Float64,
    'fitDiscountLevel': pl.Float64,
    'fitDiscountPerc': pl.Float64,
    'flatYN': pl.Utf8,
    'folioText': pl.Utf8,
    'frequentFlyerYN': pl.Utf8,
    'gDSAllowedYN': pl.Utf8,
    'groupCode': pl.Utf8,
    'highlightRateAmountYn': pl.Utf8,
    'houseUseYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'longInfo': pl.Utf8,
    'loyaltyProgramYN': pl.Utf8,
    'mandateResvProfiles': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'marshaRateProgram': pl.Utf8,
    'maximumDaysAdvanceBooking': pl.Float64,
    'maximumLengthOfStay': pl.Float64,
    'maximumOccupancy': pl.Float64,
    'mfnUploadYn': pl.Utf8,
    'minimumDaysAdvanceBooking': pl.Float64,
    'minimumOccupancy': pl.Float64,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'multiplication': pl.Utf8,
    'myFidelioUploadYN': pl.Utf8,
    'negotiatedYN': pl.Utf8,
    'occupancyBasedYn': pl.Utf8,
    'occupancyLevel': pl.Float64,
    'operatorType': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'originalRateCode': pl.Utf8,
    'orsSellSequence': pl.Float64,
    'overridePackageYn': pl.Utf8,
    'ownerRateYN': pl.Utf8,
    'packageTransactionCode': pl.Utf8,
    'packageTransactionCodeWeekend': pl.Utf8,
    'packageTransactionTaxInclYN': pl.Utf8,
    'packageTransactionTaxIncludedYN': pl.Utf8,
    'packageTransactionWkTaxInclYN': pl.Utf8,
    'packageYN': pl.Utf8,
    'packages': pl.Utf8,
    'pendingApprovalYn': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingRhythmNights': pl.Float64,
    'primaryKeyID': pl.Int64,
    'printRateYn': pl.Utf8,
    'privilegedRestrictionYn': pl.Utf8,
    'privilegedYn': pl.Utf8,
    'profitTransactionCode': pl.Utf8,
    'property': pl.Utf8,
    'propertyName': pl.Utf8,
    'rankAdjustmentFactor': pl.Float64,
    'rankValue': pl.Float64,
    'rateBucket': pl.Utf8,
    'rateBucketDescription': pl.Utf8,
    'rateCalendarYn': pl.Utf8,
    'rateCategory': pl.Utf8,
    'rateCategoryDescription': pl.Utf8,
    'rateClass': pl.Utf8,
    'rateClassDescription': pl.Utf8,
    'rateCodeId': pl.Utf8,
    'rateCodeLockedYn': pl.Utf8,
    'rateFloor': pl.Float64,
    'rateFloorOverrideYn': pl.Utf8,
    'rateIncludesTaxYn': pl.Utf8,
    'rateLabel': pl.Utf8,
    'rateLevel': pl.Float64,
    'rateUpdateYN': pl.Utf8,
    'rateinfoUrl': pl.Utf8,
    'redemptionRateYN': pl.Utf8,
    'regionalAvailabilityYN': pl.Utf8,
    'repeatPostingRhythmYn': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'rodBaseAmount': pl.Float64,
    'rodBaseFltPct': pl.Utf8,
    'rodBaseRounding': pl.Utf8,
    'rodBasedYn': pl.Utf8,
    'rodYn': pl.Utf8,
    'roomAssignmentValue': pl.Float64,
    'roomType': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'sdowBeginBookingDate': pl.Utf8,
    'sdowEndBookingDate': pl.Utf8,
    'serviceInclYn': pl.Utf8,
    'servicePerc': pl.Float64,
    'shortInfo': pl.Utf8,
    'showRateAmountYn': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'taxIncludedPerc': pl.Float64,
    'taxIncludedYn': pl.Utf8,
    'tieredYN': pl.Utf8,
    'transactionCode': pl.Utf8,
    'transactionCodeWeekend': pl.Utf8,
    'transactionTaxWeekendIncludedYN': pl.Utf8,
    'unitOfLengthOfStay': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellYn': pl.Utf8,
    'voucherBenefitRateYn': pl.Utf8,
    'weekendDays': pl.Utf8,
    'wkDeptCode': pl.Utf8,
    'yieldAs': pl.Utf8,
    'yieldableYN': pl.Utf8,
    'ymCode': pl.Utf8,
}
```
```python
rate_season_details_schema = {
    'centralSeasonCode': pl.Utf8,
    'centralSeasonDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedYn': pl.Utf8,
    'displayColor': pl.Utf8,
    'endDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'rateseasonid': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'seasonCode': pl.Utf8,
    'seasonDescription': pl.Utf8,
    'startDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
report_calendar_details_schema = {
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
reservation_details_schema = {
    'aSBProratedYn': pl.Utf8,
    'accompaniedYN': pl.Utf8,
    'accompanyingName': pl.Utf8,
    'actualCheckInDateTime': pl.Utf8,
    'actualCheckOutDateTime': pl.Utf8,
    'actualCheckInDate': pl.Utf8,
    'actualCheckInTime': pl.Utf8,
    'actualCheckOutDate': pl.Utf8,
    'actualCheckOutTime': pl.Utf8,
    'addressId': pl.Float64,
    'addresseeNameId': pl.Float64,
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'advanceCheckedInYn': pl.Utf8,
    'agencyprofileid': pl.Float64,
    'allotmentRecordType': pl.Utf8,
    'allotmentid': pl.Float64,
    'amenityEligibleYn': pl.Utf8,
    'amenityLevelCode': pl.Utf8,
    'amountPercent': pl.Float64,
    'approvalAmount': pl.Float64,
    'approvalAmountCalcMethod': pl.Float64,
    'approvalCode': pl.Utf8,
    'arrivalComments': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'arrivalDateTime': pl.Utf8,
    'arrivalEstimateTime': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'arrivaltransportid': pl.Utf8,
    'attachedDate': pl.Utf8,
    'authorizedBillingYN': pl.Utf8,
    'authorizedBy': pl.Float64,
    'authorizerId': pl.Float64,
    'autoCheckinYn': pl.Utf8,
    'autoPopulateRoutingYn': pl.Utf8,
    'autoSettleDays': pl.Float64,
    'autoSettleType': pl.Utf8,
    'autoSettleYN': pl.Utf8,
    'awardCode': pl.Utf8,
    'awardCode1': pl.Utf8,
    'awardCode2': pl.Utf8,
    'awardCode3': pl.Utf8,
    'awardCode4': pl.Utf8,
    'awardCode5': pl.Utf8,
    'awardMembershipID': pl.Float64,
    'awardVoucher1': pl.Utf8,
    'awardVoucher2': pl.Utf8,
    'awardVoucher3': pl.Utf8,
    'awardVoucher4': pl.Utf8,
    'awardVoucher5': pl.Utf8,
    'awdUpgrFrom': pl.Utf8,
    'awdUpgrTo': pl.Utf8,
    'backToBackYN': pl.Utf8,
    'balance': pl.Float64,
    'baseRateAmount': pl.Float64,
    'baseRateCode': pl.Utf8,
    'baseRateCurrencyCode': pl.Utf8,
    'basedOnRule': pl.Utf8,
    'baseratecurrencyid': pl.Utf8,
    'beginCity': pl.Utf8,
    'beginDatetime': pl.Utf8,
    'beginDistrict': pl.Utf8,
    'beginState': pl.Utf8,
    'beginSystemDateTime': pl.Utf8,
    'billNumber': pl.Utf8,
    'billingContact': pl.Utf8,
    'billingContactDisplayName': pl.Utf8,
    'billingContactId': pl.Float64,
    'billingContactName': pl.Utf8,
    'billingcontactprofileid': pl.Float64,
    'blockCode': pl.Utf8,
    'blockCreateDate': pl.Utf8,
    'blockID': pl.Float64,
    'blockName': pl.Utf8,
    'blockResort': pl.Utf8,
    'blockStatus': pl.Utf8,
    'bonusCheckId': pl.Float64,
    'bookedRoomCategory': pl.Utf8,
    'bookedroomcategoryid': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'businessDatetimeCreated': pl.Utf8,
    'bxgyDiscountYn': pl.Utf8,
    'cAutoPostAmount': pl.Float64,
    'cBaseRateAmount': pl.Float64,
    'cDiscountAmount': pl.Float64,
    'cDiscountAmt': pl.Float64,
    'cEffectiveRateAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFixedCharge': pl.Float64,
    'cGrossRateAmount': pl.Float64,
    'cLocalBaseRateAmount': pl.Float64,
    'cNetRoomAmount': pl.Float64,
    'cOriginalBaseRate': pl.Float64,
    'cPackageAmount': pl.Float64,
    'cPackageTax': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRoomCost': pl.Float64,
    'cRoomTax': pl.Float64,
    'cShareAmountOriginal': pl.Float64,
    'cUpsellCharge': pl.Float64,
    'cancelDate': pl.Utf8,
    'cancelReason': pl.Utf8,
    'cancelTime': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationDatetime': pl.Utf8,
    'cancellationNumber': pl.Utf8,
    'cancellationReasonDescription': pl.Utf8,
    'cancellationreasonid': pl.Utf8,
    'cancelledBy': pl.Utf8,
    'cardNumberByMembershipClass': pl.Utf8,
    'cardNumberByMembershipType': pl.Utf8,
    'centralApprovalAmount': pl.Float64,
    'centralCancelReason': pl.Utf8,
    'centralCommissionCode': pl.Utf8,
    'centralCommissionDescription': pl.Utf8,
    'centralCreditLimit': pl.Float64,
    'centralDiscountReason': pl.Utf8,
    'centralDiscountReasonDescription': pl.Utf8,
    'centralFBRevenue': pl.Float64,
    'centralGuestType': pl.Utf8,
    'centralHurdle': pl.Float64,
    'centralPackageCode': pl.Utf8,
    'centralPackageCodeDescription': pl.Utf8,
    'centralPackageForecastGroup': pl.Utf8,
    'centralPackageForecastGroupDescription': pl.Utf8,
    'centralPaymentAmount': pl.Float64,
    'centralProjectedFBRevenue': pl.Float64,
    'centralProjectedRoomRevenue': pl.Float64,
    'centralProjectedTotalRevenue': pl.Float64,
    'centralPromotionDescription': pl.Utf8,
    'centralRateableValue': pl.Float64,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralRoomTypeCode': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralRoomTypeToChargeCode': pl.Utf8,
    'centralRoomTypeToChargeDescription': pl.Utf8,
    'centralSharedRoomRate': pl.Float64,
    'centralSpecialRequestDescription': pl.Utf8,
    'centralTaxType': pl.Utf8,
    'centralTaxTypeDescription': pl.Utf8,
    'centralTotalCostOfStay': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralTotalRoomRate': pl.Float64,
    'centralWaitlistPriority': pl.Utf8,
    'centralWaitlistPriorityDescription': pl.Utf8,
    'centralWaitlistReason': pl.Utf8,
    'centralWaitlistReasonDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'channelDescription': pl.Utf8,
    'channelOrderBy': pl.Float64,
    'channelid': pl.Utf8,
    'checkInInitiatedBy': pl.Utf8,
    'checkinDuration': pl.Float64,
    'childBucket1': pl.Float64,
    'childBucket4': pl.Float64,
    'childBucket5': pl.Float64,
    'children': pl.Float64,
    'childrenAgeGroup2': pl.Float64,
    'childrenAgeGroup3': pl.Float64,
    'childrenAges': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionDescription': pl.Utf8,
    'commissionHoldCode': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionPayoutTo': pl.Utf8,
    'commissionableYN': pl.Utf8,
    'commissionid': pl.Utf8,
    'compHouse': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'companyCity': pl.Utf8,
    'companyCountry': pl.Utf8,
    'companyID': pl.Float64,
    'companyName': pl.Utf8,
    'companyProfileCorporateID': pl.Utf8,
    'companyProfileID': pl.Float64,
    'complimentaryYN': pl.Utf8,
    'compreasonid': pl.Utf8,
    'computedResvStatus': pl.Utf8,
    'confirmationLegNumber': pl.Float64,
    'confirmationNo': pl.Utf8,
    'consumerYn': pl.Utf8,
    'contactName': pl.Utf8,
    'contactProfileID': pl.Float64,
    'contactProfileName': pl.Utf8,
    'createdBy': pl.Utf8,
    'createdByDefaultResort': pl.Utf8,
    'createdDate': pl.Utf8,
    'createdTime': pl.Utf8,
    'creditCardAuthDate': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditLimit': pl.Float64,
    'creditLimitAutoPayAllowYn': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'customReferenceNumber': pl.Utf8,
    'dSI': pl.Int64,
    'dateOfArrivalInCountry': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'departtransportid': pl.Utf8,
    'departureComments': pl.Utf8,
    'departureDate': pl.Utf8,
    'departureDateTime': pl.Utf8,
    'departureTime': pl.Utf8,
    'departureTransportCode': pl.Utf8,
    'departureTransportationYN': pl.Utf8,
    'depositMaturityType': pl.Utf8,
    'detatchedDate': pl.Utf8,
    'detatchedYN': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'directbillauthby': pl.Float64,
    'discountAmount': pl.Float64,
    'discountAmt': pl.Float64,
    'discountPercent': pl.Float64,
    'discountPrcnt': pl.Float64,
    'discountReason': pl.Utf8,
    'discountReasonDescription': pl.Utf8,
    'discountreasonid': pl.Utf8,
    'displayColor': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doNotMoveRoom': pl.Utf8,
    'doNotMoveYN': pl.Utf8,
    'dropOffCarrierCode': pl.Utf8,
    'dropOffDate': pl.Utf8,
    'dropOffStation': pl.Utf8,
    'dropOffTime': pl.Utf8,
    'dropOffType': pl.Utf8,
    'dropOffTypeDescription': pl.Utf8,
    'eTRComments': pl.Utf8,
    'effectiveRateAmount': pl.Float64,
    'eligibleForUpgradeYn': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'emailId': pl.Float64,
    'emailYn': pl.Utf8,
    'endCity': pl.Utf8,
    'endDatetime': pl.Utf8,
    'endDistrict': pl.Utf8,
    'endState': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'entryDate': pl.Utf8,
    'entryPoint': pl.Utf8,
    'esignedRegCardName': pl.Utf8,
    'estimatedDepartureTime': pl.Utf8,
    'eventId': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'excludeFromAutoAuthorizationYN': pl.Utf8,
    'expectedTimeOfReturnETR': pl.Utf8,
    'exportCheckinresId': pl.Float64,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'extensionId': pl.Float64,
    'externalEfolioYn': pl.Utf8,
    'externalReference': pl.Utf8,
    'externalReferencesList': pl.Utf8,
    'extraBeds': pl.Float64,
    'fBRevenue': pl.Float64,
    'fBRevenueRemaining': pl.Float64,
    'faxId': pl.Float64,
    'faxYn': pl.Utf8,
    'feature': pl.Utf8,
    'financiallyResponsibleYn': pl.Utf8,
    'fixedCharge': pl.Float64,
    'fixedRateYN': pl.Utf8,
    'folioAddrElementId': pl.Float64,
    'folioCloseDate': pl.Utf8,
    'folioNumber': pl.Utf8,
    'folioText1': pl.Utf8,
    'folioText2': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'freeChild': pl.Float64,
    'frequentFlyerMembershipYN': pl.Utf8,
    'grossRateFuture': pl.Float64,
    'grossRatePast': pl.Float64,
    'groupName': pl.Utf8,
    'groupProfileARNumber': pl.Float64,
    'groupProfileARNumberCentral': pl.Utf8,
    'groupProfileClientID': pl.Utf8,
    'groupProfileID': pl.Float64,
    'groupProfileName': pl.Utf8,
    'guaranteeCodePreCi': pl.Utf8,
    'guaranteecodeid': pl.Utf8,
    'guestFirstName': pl.Utf8,
    'guestFirstNameSdx': pl.Utf8,
    'guestLastNameSdx': pl.Utf8,
    'guestSignature': pl.Utf8,
    'guestStatus': pl.Utf8,
    'guestType': pl.Utf8,
    'guestprofileid': pl.Float64,
    'gueststatusid': pl.Utf8,
    'guesttypeid': pl.Utf8,
    'housekeepingServiceTime': pl.Utf8,
    'hurdle': pl.Float64,
    'hurdleOverride': pl.Utf8,
    'iDByMembershipClass': pl.Utf8,
    'iDByMembershipType': pl.Utf8,
    'individualCity': pl.Utf8,
    'individualCountry': pl.Utf8,
    'individualFirstName': pl.Utf8,
    'individualLastName': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertDateTime': pl.Utf8,
    'insertUser': pl.Int64,
    'intermediaryYn': pl.Utf8,
    'internalAwardMembershipId': pl.Float64,
    'internalBaseratecode': pl.Utf8,
    'internalBlockId': pl.Float64,
    'internalCompanyprofileid': pl.Float64,
    'internalGroupprofileid': pl.Float64,
    'internalSourceprofileid': pl.Float64,
    'itemsQuantities': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyValidUntil': pl.Utf8,
    'lastOnlinePrintSeq': pl.Float64,
    'lastPeriodicFolioDate': pl.Utf8,
    'lastRoomNumber': pl.Utf8,
    'lastSettleDate': pl.Utf8,
    'leadTimeDays': pl.Float64,
    'lengthOfStay': pl.Float64,
    'linkedArrivalDate': pl.Utf8,
    'linkedDepartureDate': pl.Utf8,
    'linkedRoomType': pl.Utf8,
    'listOfMembershipID': pl.Utf8,
    'localBaseRateAmount': pl.Float64,
    'locationID': pl.Utf8,
    'loyaltySchemeMembershipYN': pl.Utf8,
    'mailYn': pl.Utf8,
    'manualCheckoutStatus': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketid': pl.Utf8,
    'mcGenBeginDistrict': pl.Utf8,
    'mcGenBeginState': pl.Utf8,
    'mcGenEndDistrict': pl.Utf8,
    'mcGenEndState': pl.Utf8,
    'mcGenNextCountry': pl.Utf8,
    'mcGenPreviousCountry': pl.Utf8,
    'memberDescription': pl.Utf8,
    'memberLevel': pl.Utf8,
    'memberNumber': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipClassDescription': pl.Utf8,
    'membershipCode': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevelByMembershipClass': pl.Utf8,
    'membershipTypeByMembershipClass': pl.Utf8,
    'mobileActionAlertIssued': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'mobilePreferredCurrency': pl.Utf8,
    'mobileViewFolioAllowed': pl.Utf8,
    'name': pl.Utf8,
    'nameUsageType': pl.Utf8,
    'nextCountry': pl.Utf8,
    'nextDestination': pl.Utf8,
    'numberOfRooms': pl.Float64,
    'operaEsignedRegCardYn': pl.Utf8,
    'optInBatchFolYn': pl.Utf8,
    'optedForCommissionYN': pl.Utf8,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originOfBooking': pl.Utf8,
    'originalBaseRate': pl.Float64,
    'originalEndDate': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'ownerFfFlag': pl.Utf8,
    'ownerOrFriendsFamily': pl.Utf8,
    'packageCode': pl.Utf8,
    'packageCodeDescription': pl.Utf8,
    'packageForecastGroup': pl.Utf8,
    'packageForecastGroupDescription': pl.Utf8,
    'parentReservationNameId': pl.Float64,
    'parentreservationid': pl.Float64,
    'partAllotment': pl.Utf8,
    'partyCode': pl.Utf8,
    'paxNo': pl.Float64,
    'paymentAmount': pl.Float64,
    'paymentMethod': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'periodicFolioFreq': pl.Float64,
    'phoneDisplayNameYn': pl.Utf8,
    'phoneId': pl.Float64,
    'physicalQuantity': pl.Float64,
    'pickUpCarrierCode': pl.Utf8,
    'pickUpDate': pl.Utf8,
    'pickUpStation': pl.Utf8,
    'pickUpTransportNumber': pl.Utf8,
    'pickUpType': pl.Utf8,
    'pickUpTypeDescription': pl.Utf8,
    'pickUpTime': pl.Utf8,
    'pickupRequiredYN': pl.Utf8,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'postCoFlag': pl.Utf8,
    'postStayChargingYN': pl.Utf8,
    'postingAllowedYN': pl.Utf8,
    'preArrReviewedDt': pl.Utf8,
    'preArrReviewedUser': pl.Float64,
    'preChargingYn': pl.Utf8,
    'preRegisteredYn': pl.Utf8,
    'preference': pl.Utf8,
    'preferenceType': pl.Utf8,
    'preferredRoomType': pl.Utf8,
    'previousCountry': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryShare': pl.Utf8,
    'printRateYN': pl.Utf8,
    'projectedFBRevenue': pl.Float64,
    'projectedRoomRevenue': pl.Float64,
    'projectedTotalRevenue': pl.Float64,
    'promotionCode': pl.Utf8,
    'promotionDescription': pl.Utf8,
    'property': pl.Utf8,
    'pseudoMemTotalPoints': pl.Float64,
    'pseudoMemType': pl.Utf8,
    'purgeDate': pl.Utf8,
    'purposeOfStay': pl.Utf8,
    'quantity': pl.Float64,
    'queuePriority': pl.Float64,
    'queueWaitTime': pl.Float64,
    'quoteId': pl.Utf8,
    'rateAmount': pl.Float64,
    'rateCode': pl.Utf8,
    'rateCodeDescriptions': pl.Utf8,
    'rateTier': pl.Float64,
    'rateableValue': pl.Float64,
    'ratecodeid': pl.Utf8,
    'rdHousekeepingExpectedServiceTime': pl.Utf8,
    'rdResvStatus': pl.Utf8,
    'rdenBillingContactId': pl.Float64,
    'rdenReservationContactId': pl.Float64,
    'rdenReservationDate': pl.Utf8,
    'rdenResort': pl.Utf8,
    'referralYn': pl.Utf8,
    'registrationCardNo': pl.Utf8,
    'registrationNumber': pl.Float64,
    'reinstateDate': pl.Utf8,
    'repChannel': pl.Utf8,
    'repChannelDescription': pl.Utf8,
    'reportId': pl.Utf8,
    'resInsertSource': pl.Utf8,
    'resInsertSourceType': pl.Utf8,
    'reservationContactId': pl.Float64,
    'reservationDate': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reservationid': pl.Float64,
    'resort': pl.Utf8,
    'resortChargeNumber': pl.Utf8,
    'restrictionOverride': pl.Utf8,
    'resvGuid': pl.Utf8,
    'resvNameid': pl.Float64,
    'resvNumber': pl.Float64,
    'resvcontactprofileid': pl.Float64,
    'revenueTypeCode': pl.Utf8,
    'rhBillingContactId': pl.Float64,
    'rhReservationContactId': pl.Float64,
    'rhRoomFeatures': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomCost': pl.Float64,
    'roomInstructions': pl.Utf8,
    'roomResort': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueRemaining': pl.Float64,
    'roomServiceTime': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomTypeToChargeCode': pl.Utf8,
    'roomTypeToChargeDescription': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomid': pl.Utf8,
    'routingYN': pl.Utf8,
    'scheduleCheckoutYn': pl.Utf8,
    'sguestFirstname': pl.Utf8,
    'sguestName': pl.Utf8,
    'shareConfirmationNumbers': pl.Utf8,
    'shareId': pl.Float64,
    'shareName': pl.Utf8,
    'sharePrcnt': pl.Float64,
    'shareSeqNumber': pl.Float64,
    'shareOfRateAmount': pl.Float64,
    'sharedGuestName': pl.Utf8,
    'sharedProfileID': pl.Float64,
    'sharedReservationStatus': pl.Utf8,
    'sharingYN': pl.Utf8,
    'sourceCity': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCountry': pl.Utf8,
    'sourceName': pl.Utf8,
    'sourceProfileARNumber': pl.Float64,
    'sourceProfileARNumberCentral': pl.Utf8,
    'sourceProfileIATANumber': pl.Utf8,
    'sourceProfileID': pl.Float64,
    'sourceProfileName': pl.Utf8,
    'sourceid': pl.Utf8,
    'specialRequest': pl.Utf8,
    'specialRequestDescription': pl.Utf8,
    'spgDiscloseRoomTypeYn': pl.Utf8,
    'spgSuiteNightAwardStatus': pl.Utf8,
    'spgUpgradeConfirmedRoomtype': pl.Utf8,
    'spgUpgradeReasonCode': pl.Utf8,
    'splitFromReservationNameId': pl.Float64,
    'splitfromreservationid': pl.Float64,
    'statisticalRateTier': pl.Float64,
    'statisticalRoomType': pl.Float64,
    'stayRecordId': pl.Float64,
    'suiteNumber': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'taRecordLocator': pl.Utf8,
    'taxExemptNumber': pl.Utf8,
    'taxNumberOfStays': pl.Float64,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tiad': pl.Utf8,
    'ticketNos': pl.Utf8,
    'totalCostOfStay': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueRemaining': pl.Float64,
    'totalRoomRate': pl.Float64,
    'trackItGroups': pl.Utf8,
    'trackItTypes': pl.Utf8,
    'transactionid': pl.Float64,
    'travelAgentCity': pl.Utf8,
    'travelAgentCountry': pl.Utf8,
    'travelAgentID': pl.Float64,
    'travelAgentName': pl.Utf8,
    'travelAgentProfileARNumber': pl.Float64,
    'travelAgentProfileARNumberCentral': pl.Utf8,
    'travelAgentProfileIATANumber': pl.Utf8,
    'travelAgentProfileID': pl.Float64,
    'travelAgentProfileName': pl.Utf8,
    'truncActualCheckOutDate': pl.Utf8,
    'turndownStatus': pl.Utf8,
    'turndownYN': pl.Utf8,
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
    'uDFC11': pl.Utf8,
    'uDFC12': pl.Utf8,
    'uDFC13': pl.Utf8,
    'uDFC14': pl.Utf8,
    'uDFC15': pl.Utf8,
    'uDFC16': pl.Utf8,
    'uDFC17': pl.Utf8,
    'uDFC18': pl.Utf8,
    'uDFC19': pl.Utf8,
    'uDFC20': pl.Utf8,
    'uDFC21': pl.Utf8,
    'uDFC22': pl.Utf8,
    'uDFC23': pl.Utf8,
    'uDFC24': pl.Utf8,
    'uDFC25': pl.Utf8,
    'uDFC26': pl.Utf8,
    'uDFC27': pl.Utf8,
    'uDFC28': pl.Utf8,
    'uDFC29': pl.Utf8,
    'uDFC30': pl.Utf8,
    'uDFC31': pl.Utf8,
    'uDFC32': pl.Utf8,
    'uDFC33': pl.Utf8,
    'uDFC34': pl.Utf8,
    'uDFC35': pl.Utf8,
    'uDFC36': pl.Utf8,
    'uDFC37': pl.Utf8,
    'uDFC38': pl.Utf8,
    'uDFC39': pl.Utf8,
    'uDFC40': pl.Utf8,
    'uDFD01': pl.Utf8,
    'uDFD02': pl.Utf8,
    'uDFD03': pl.Utf8,
    'uDFD04': pl.Utf8,
    'uDFD05': pl.Utf8,
    'uDFD06': pl.Utf8,
    'uDFD07': pl.Utf8,
    'uDFD08': pl.Utf8,
    'uDFD09': pl.Utf8,
    'uDFD10': pl.Utf8,
    'uDFD11': pl.Utf8,
    'uDFD12': pl.Utf8,
    'uDFD13': pl.Utf8,
    'uDFD14': pl.Utf8,
    'uDFD15': pl.Utf8,
    'uDFD16': pl.Utf8,
    'uDFD17': pl.Utf8,
    'uDFD18': pl.Utf8,
    'uDFD19': pl.Utf8,
    'uDFD20': pl.Utf8,
    'uDFN01': pl.Float64,
    'uDFN02': pl.Float64,
    'uDFN03': pl.Float64,
    'uDFN04': pl.Float64,
    'uDFN05': pl.Float64,
    'uDFN06': pl.Float64,
    'uDFN07': pl.Float64,
    'uDFN08': pl.Float64,
    'uDFN09': pl.Float64,
    'uDFN10': pl.Float64,
    'uDFN11': pl.Float64,
    'uDFN12': pl.Float64,
    'uDFN13': pl.Float64,
    'uDFN14': pl.Float64,
    'uDFN15': pl.Float64,
    'uDFN16': pl.Float64,
    'uDFN17': pl.Float64,
    'uDFN18': pl.Float64,
    'uDFN19': pl.Float64,
    'uDFN20': pl.Float64,
    'uDFN21': pl.Float64,
    'uDFN22': pl.Float64,
    'uDFN23': pl.Float64,
    'uDFN24': pl.Float64,
    'uDFN25': pl.Float64,
    'uDFN26': pl.Float64,
    'uDFN27': pl.Float64,
    'uDFN28': pl.Float64,
    'uDFN29': pl.Float64,
    'uDFN30': pl.Float64,
    'uDFN31': pl.Float64,
    'uDFN32': pl.Float64,
    'uDFN33': pl.Float64,
    'uDFN34': pl.Float64,
    'uDFN35': pl.Float64,
    'uDFN36': pl.Float64,
    'uDFN37': pl.Float64,
    'uDFN38': pl.Float64,
    'uDFN39': pl.Float64,
    'uDFN40': pl.Float64,
    'uniCardId': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateDatetime': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedByDefaultResort': pl.Utf8,
    'updatedDate': pl.Utf8,
    'updatedTime': pl.Utf8,
    'upsellCharge': pl.Float64,
    'videoCheckoutYN': pl.Utf8,
    'visaExpiryDate': pl.Utf8,
    'visaIssueDate': pl.Utf8,
    'visaNumber': pl.Utf8,
    'waitlistComment': pl.Utf8,
    'waitlistPhoneNumber': pl.Utf8,
    'waitlistPriority': pl.Utf8,
    'waitlistPriorityDescription': pl.Utf8,
    'waitlistReason': pl.Utf8,
    'waitlistReasonDescription': pl.Utf8,
    'waitlistpriorityid': pl.Utf8,
    'waitlistreasonid': pl.Utf8,
    'walkInYN': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Utf8,
}
```
```python
revenue_packages_details_schema = {
    'addToRateYN': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'beginBookingDate': pl.Utf8,
    'bookingDuration': pl.Float64,
    'calculationRule': pl.Utf8,
    'cateringYn': pl.Utf8,
    'centralPackageCode': pl.Utf8,
    'centralPackageCodeDescription': pl.Utf8,
    'centralPackageForecastGroup': pl.Utf8,
    'centralPackageForecastGroupDescription': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDesc': pl.Utf8,
    'dSI': pl.Int64,
    'deletedYn': pl.Utf8,
    'deliveryTimeReqrdYn': pl.Utf8,
    'endBookingDate': pl.Utf8,
    'externalLocked': pl.Utf8,
    'flexibleDurationYN': pl.Utf8,
    'forecastGroupCode': pl.Utf8,
    'forecastNextDayYN': pl.Utf8,
    'formula': pl.Utf8,
    'genPlAtEodOfCoDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalPostingrhythm': pl.Utf8,
    'inventoriedYN': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'longInfo': pl.Utf8,
    'maxPersons': pl.Utf8,
    'maximumPersons': pl.Utf8,
    'minimumAdvBookDays': pl.Float64,
    'organizationID': pl.Int64,
    'outletCode': pl.Utf8,
    'overrideFixedRateYn': pl.Utf8,
    'pOSAccountYN': pl.Utf8,
    'pOSNextDayYN': pl.Utf8,
    'packageCode': pl.Utf8,
    'packageCodeDescription': pl.Utf8,
    'packageCodeShortDescription': pl.Utf8,
    'packageForecastGroup': pl.Utf8,
    'packageForecastGroupDescription': pl.Utf8,
    'pkgForcastGroup': pl.Utf8,
    'pkgforecastgrpid': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'printSeparateYN': pl.Utf8,
    'product': pl.Utf8,
    'productType': pl.Utf8,
    'productid': pl.Utf8,
    'property': pl.Utf8,
    'redemptionProductYN': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'separatelySoldYN': pl.Utf8,
    'standardDuration': pl.Float64,
    'standardPersons': pl.Utf8,
    'ticketsYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'validFromTime': pl.Utf8,
    'validToTime': pl.Utf8,
    'webBookableYN': pl.Utf8,
}
```
```python
room_details_schema = {
    'accessible': pl.Utf8,
    'areaF': pl.Float64,
    'areaM': pl.Float64,
    'assignAssignStatus': pl.Utf8,
    'assignDate': pl.Utf8,
    'assignReasonDesc': pl.Utf8,
    'assignType': pl.Utf8,
    'assignemployeeid': pl.Float64,
    'assignreasonid': pl.Utf8,
    'bedType': pl.Utf8,
    'building': pl.Utf8,
    'buildingGroup': pl.Utf8,
    'businessDate': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cMinimumRevenue': pl.Float64,
    'cRackRate': pl.Float64,
    'centralMeetingRoomType': pl.Utf8,
    'centralRoomClass': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'combinationRoomYN': pl.Utf8,
    'comments': pl.Utf8,
    'componentRoom': pl.Utf8,
    'connectingRoomNumber': pl.Utf8,
    'dSI': pl.Int64,
    'daySection': pl.Utf8,
    'deductYN': pl.Utf8,
    'defatulratecodeid': pl.Utf8,
    'defaultRateDesc': pl.Utf8,
    'deletedflag': pl.Utf8,
    'departureCredits': pl.Float64,
    'description': pl.Utf8,
    'diaryName': pl.Utf8,
    'diarydisplayflag': pl.Utf8,
    'discrepancy': pl.Utf8,
    'doors': pl.Utf8,
    'eveningSection': pl.Utf8,
    'evisitorFacilityId': pl.Utf8,
    'excludedEventTypes': pl.Utf8,
    'facing': pl.Utf8,
    'floor': pl.Utf8,
    'foPers': pl.Float64,
    'forceAlternateYn': pl.Utf8,
    'frontDeskLocation': pl.Utf8,
    'frontOfficeStatus': pl.Utf8,
    'fullUtilizationTime': pl.Float64,
    'genericYN': pl.Utf8,
    'handicapflag': pl.Utf8,
    'heightmaxF': pl.Float64,
    'heightmaxM': pl.Float64,
    'heightminF': pl.Float64,
    'heightminM': pl.Float64,
    'holdDateTime': pl.Utf8,
    'holdType': pl.Utf8,
    'holdUser': pl.Float64,
    'housekeepingAssignmentOrderBy': pl.Float64,
    'housekeepingInspDate': pl.Utf8,
    'housekeepingInspEmpId': pl.Utf8,
    'housekeepingPers': pl.Float64,
    'housekeepingStatus': pl.Utf8,
    'imageId': pl.Float64,
    'inactiveflag': pl.Utf8,
    'includeInStatisticsYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalTempflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyCode': pl.Utf8,
    'keyOptions': pl.Utf8,
    'lastCheckOutDate': pl.Utf8,
    'lastMeterReading': pl.Float64,
    'lengthF': pl.Float64,
    'lengthM': pl.Float64,
    'light': pl.Utf8,
    'locationID': pl.Utf8,
    'loudspeakersflag': pl.Utf8,
    'maxAdvance': pl.Float64,
    'maxCapacity': pl.Float64,
    'maxSharedGroups': pl.Float64,
    'maximumOccupancy': pl.Float64,
    'measurement': pl.Utf8,
    'meetingRoomType': pl.Utf8,
    'meetingRoomYN': pl.Utf8,
    'meetingroomTypeDesc': pl.Utf8,
    'meetingroomTypeSeq': pl.Float64,
    'microphoneSocketTypes': pl.Utf8,
    'microphoneSockets': pl.Float64,
    'minAdvance': pl.Float64,
    'minCapacity': pl.Float64,
    'minimumRevenue': pl.Float64,
    'numberOfBeds': pl.Float64,
    'occupancyCondition': pl.Utf8,
    'occupantDiscrepancy': pl.Float64,
    'onlinePrintingYn': pl.Utf8,
    'orderBy2': pl.Float64,
    'orderBy3': pl.Float64,
    'orderBy4': pl.Float64,
    'orderBy5': pl.Float64,
    'organizationID': pl.Int64,
    'ovosGradeCode': pl.Utf8,
    'ovosUnitYn': pl.Utf8,
    'pcode': pl.Utf8,
    'personDiscrepancy': pl.Float64,
    'phoneNumber': pl.Utf8,
    'physicalNumberOfRooms': pl.Float64,
    'pickupCredits': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'pseudoRoomYN': pl.Utf8,
    'publishedRateAmount': pl.Float64,
    'publishedRateCode': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rating': pl.Utf8,
    'repAssignReasonDescription': pl.Utf8,
    'repBedTypeDescription': pl.Utf8,
    'repMeetingroomTypeDescription': pl.Utf8,
    'repMeetingroomTypeSequence': pl.Float64,
    'repRoomClassSellSequence': pl.Float64,
    'repRoomFeaturesDescs': pl.Utf8,
    'repRoomStatusReason': pl.Utf8,
    'repRoomStatusReasonDescription': pl.Utf8,
    'returnStatus': pl.Utf8,
    'room': pl.Utf8,
    'roomAssignmentRating': pl.Float64,
    'roomCategoryBedtype': pl.Utf8,
    'roomCategoryDesc': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomClassCentralDescription': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomClassSequence': pl.Float64,
    'roomCondition': pl.Utf8,
    'roomFeatureDescription': pl.Utf8,
    'roomFeatures': pl.Utf8,
    'roomNumber': pl.Utf8,
    'roomParity': pl.Utf8,
    'roomStatus': pl.Utf8,
    'roomStatusDescription': pl.Utf8,
    'roomStatusFromDate': pl.Utf8,
    'roomStatusReason': pl.Utf8,
    'roomStatusReasonDesc': pl.Utf8,
    'roomStatusRemarks': pl.Utf8,
    'roomStatusToDate': pl.Utf8,
    'roomType': pl.Utf8,
    'roomUseCount': pl.Float64,
    'roomcategoryid': pl.Utf8,
    'roomclassid': pl.Utf8,
    'roomid': pl.Utf8,
    'roomstatusreasonid': pl.Utf8,
    'sequence': pl.Float64,
    'serviceStatus': pl.Utf8,
    'setupNotes': pl.Utf8,
    'shareableflag': pl.Utf8,
    'smoking': pl.Utf8,
    'smokingPreferences': pl.Utf8,
    'squareUnits': pl.Float64,
    'stayoverCredits': pl.Float64,
    'suiteType': pl.Utf8,
    'suiteYN': pl.Utf8,
    'supplement': pl.Utf8,
    'tempFlag': pl.Utf8,
    'translationboothNum': pl.Float64,
    'turnDown': pl.Utf8,
    'turndownCredits': pl.Float64,
    'tvRadioSockets': pl.Float64,
    'unit': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'visibleOnWebYn': pl.Utf8,
    'webBookingYn': pl.Utf8,
    'weightF': pl.Float64,
    'weightM': pl.Float64,
    'widthF': pl.Float64,
    'widthM': pl.Float64,
}
```
```python
routing_instruction_details_schema = {
    'accountCode': pl.Utf8,
    'addTransactionYN': pl.Utf8,
    'addressId': pl.Float64,
    'authemployeeid': pl.Float64,
    'authorizerId': pl.Float64,
    'basedOnRate': pl.Utf8,
    'billingInstrnCode': pl.Float64,
    'billtoprofileid': pl.Float64,
    'cCompPreApprovalAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralExtendedInstructionSummary': pl.Utf8,
    'centralInstructionSummary': pl.Utf8,
    'centralRoutingAmountLimit': pl.Float64,
    'centralRoutingLimitUsed': pl.Float64,
    'centralRoutingTransactionCode': pl.Utf8,
    'centralRoutingTransactionCodeDescription': pl.Utf8,
    'comments': pl.Utf8,
    'compAuthorizer': pl.Utf8,
    'compPreApprovalAmt': pl.Float64,
    'compPreApprovalCode': pl.Utf8,
    'compPreApprovalDate': pl.Utf8,
    'compPreApprovalRequiredYn': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'compVoucherNo': pl.Utf8,
    'dSI': pl.Int64,
    'dailyYn': pl.Utf8,
    'dayString': pl.Utf8,
    'declinedBy': pl.Float64,
    'declinedYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'extendedInstructionSummary': pl.Utf8,
    'folio': pl.Float64,
    'fridayYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'instructionSummary': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalMembershipid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'membershipId': pl.Float64,
    'mondayYN': pl.Utf8,
    'organizationID': pl.Int64,
    'payeeFirstName': pl.Utf8,
    'payeeLastName': pl.Utf8,
    'payeeNameID': pl.Float64,
    'primaryKeyID': pl.Int64,
    'printReceiptYn': pl.Utf8,
    'property': pl.Utf8,
    'requestedBy': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'routedToRoomNo': pl.Utf8,
    'routingAmountLimit': pl.Float64,
    'routingBeginDate': pl.Utf8,
    'routingCode': pl.Utf8,
    'routingCodeDescription': pl.Utf8,
    'routingCoversLimit': pl.Float64,
    'routingDateRange': pl.Utf8,
    'routingDaysOfWeek': pl.Utf8,
    'routingInstructionsId': pl.Float64,
    'routingLimitType': pl.Utf8,
    'routingLimitUsed': pl.Float64,
    'routingLinkId': pl.Float64,
    'routingPercentageLimit': pl.Float64,
    'routingTransactionCode': pl.Utf8,
    'routingTransactionCodeDescription': pl.Utf8,
    'routingType': pl.Utf8,
    'routingTypeDesc': pl.Utf8,
    'routinginstructid': pl.Float64,
    'saturdayYN': pl.Utf8,
    'sundayYN': pl.Utf8,
    'tcGroup': pl.Utf8,
    'tcSubgroup': pl.Utf8,
    'thursdayYN': pl.Utf8,
    'toReservationNameId': pl.Float64,
    'toreservationid': pl.Float64,
    'transcodearrangementid': pl.Float64,
    'transcodeid': pl.Utf8,
    'transgroupid': pl.Utf8,
    'transsubgroupid': pl.Utf8,
    'trxServiceType': pl.Utf8,
    'tuesdayYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'wednesdayYN': pl.Utf8,
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
transaction_code_arrangment_details_schema = {
    'arrTaxTypeCode': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'arrangementDescription': pl.Utf8,
    'arrangementId': pl.Float64,
    'arrangementType': pl.Utf8,
    'bucketValue': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRoutingAmount': pl.Float64,
    'centralTransactionCode': pl.Utf8,
    'centralTransactionCodeDescription': pl.Utf8,
    'compYn': pl.Utf8,
    'complimentaryYN': pl.Utf8,
    'dSI': pl.Int64,
    'dailyYn': pl.Utf8,
    'day1': pl.Utf8,
    'day2': pl.Utf8,
    'day3': pl.Utf8,
    'day4': pl.Utf8,
    'day5': pl.Utf8,
    'day6': pl.Utf8,
    'day7': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'eligibleYn': pl.Utf8,
    'exportBucketType': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'inheritAuthRatecodeYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'revenueYn': pl.Utf8,
    'revenueflag': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'routingAmount': pl.Float64,
    'routingCovers': pl.Float64,
    'routingPercent': pl.Float64,
    'transactionCode': pl.Utf8,
    'transactionCodeDescription': pl.Utf8,
    'transcodearrangementid': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
from_reservation_details_schema = {
    'aSBProratedYn': pl.Utf8,
    'accompaniedYN': pl.Utf8,
    'accompanyingName': pl.Utf8,
    'actualCheckInDateTime': pl.Utf8,
    'actualCheckOutDateTime': pl.Utf8,
    'actualCheckInDate': pl.Utf8,
    'actualCheckInTime': pl.Utf8,
    'actualCheckOutDate': pl.Utf8,
    'actualCheckOutTime': pl.Utf8,
    'addressId': pl.Float64,
    'addresseeNameId': pl.Float64,
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'advanceCheckedInYn': pl.Utf8,
    'agencyprofileid': pl.Float64,
    'allotmentRecordType': pl.Utf8,
    'allotmentid': pl.Float64,
    'amenityEligibleYn': pl.Utf8,
    'amenityLevelCode': pl.Utf8,
    'amountPercent': pl.Float64,
    'approvalAmount': pl.Float64,
    'approvalAmountCalcMethod': pl.Float64,
    'approvalCode': pl.Utf8,
    'arrivalComments': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'arrivalDateTime': pl.Utf8,
    'arrivalEstimateTime': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'arrivaltransportid': pl.Utf8,
    'attachedDate': pl.Utf8,
    'authorizedBillingYN': pl.Utf8,
    'authorizedBy': pl.Float64,
    'authorizerId': pl.Float64,
    'autoCheckinYn': pl.Utf8,
    'autoPopulateRoutingYn': pl.Utf8,
    'autoSettleDays': pl.Float64,
    'autoSettleType': pl.Utf8,
    'autoSettleYN': pl.Utf8,
    'awardCode': pl.Utf8,
    'awardCode1': pl.Utf8,
    'awardCode2': pl.Utf8,
    'awardCode3': pl.Utf8,
    'awardCode4': pl.Utf8,
    'awardCode5': pl.Utf8,
    'awardMembershipID': pl.Float64,
    'awardVoucher1': pl.Utf8,
    'awardVoucher2': pl.Utf8,
    'awardVoucher3': pl.Utf8,
    'awardVoucher4': pl.Utf8,
    'awardVoucher5': pl.Utf8,
    'awdUpgrFrom': pl.Utf8,
    'awdUpgrTo': pl.Utf8,
    'backToBackYN': pl.Utf8,
    'balance': pl.Float64,
    'baseRateAmount': pl.Float64,
    'baseRateCode': pl.Utf8,
    'baseRateCurrencyCode': pl.Utf8,
    'basedOnRule': pl.Utf8,
    'baseratecurrencyid': pl.Utf8,
    'beginCity': pl.Utf8,
    'beginDatetime': pl.Utf8,
    'beginDistrict': pl.Utf8,
    'beginState': pl.Utf8,
    'beginSystemDateTime': pl.Utf8,
    'billNumber': pl.Utf8,
    'billingContact': pl.Utf8,
    'billingContactDisplayName': pl.Utf8,
    'billingContactId': pl.Float64,
    'billingContactName': pl.Utf8,
    'billingcontactprofileid': pl.Float64,
    'blockCode': pl.Utf8,
    'blockCreateDate': pl.Utf8,
    'blockID': pl.Float64,
    'blockName': pl.Utf8,
    'blockResort': pl.Utf8,
    'blockStatus': pl.Utf8,
    'bonusCheckId': pl.Float64,
    'bookedRoomCategory': pl.Utf8,
    'bookedroomcategoryid': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'businessDatetimeCreated': pl.Utf8,
    'bxgyDiscountYn': pl.Utf8,
    'cAutoPostAmount': pl.Float64,
    'cBaseRateAmount': pl.Float64,
    'cDiscountAmount': pl.Float64,
    'cDiscountAmt': pl.Float64,
    'cEffectiveRateAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFixedCharge': pl.Float64,
    'cGrossRateAmount': pl.Float64,
    'cLocalBaseRateAmount': pl.Float64,
    'cNetRoomAmount': pl.Float64,
    'cOriginalBaseRate': pl.Float64,
    'cPackageAmount': pl.Float64,
    'cPackageTax': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRoomCost': pl.Float64,
    'cRoomTax': pl.Float64,
    'cShareAmountOriginal': pl.Float64,
    'cUpsellCharge': pl.Float64,
    'cancelDate': pl.Utf8,
    'cancelReason': pl.Utf8,
    'cancelTime': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationDatetime': pl.Utf8,
    'cancellationNumber': pl.Utf8,
    'cancellationReasonDescription': pl.Utf8,
    'cancellationreasonid': pl.Utf8,
    'cancelledBy': pl.Utf8,
    'cardNumberByMembershipClass': pl.Utf8,
    'cardNumberByMembershipType': pl.Utf8,
    'centralApprovalAmount': pl.Float64,
    'centralCancelReason': pl.Utf8,
    'centralCommissionCode': pl.Utf8,
    'centralCommissionDescription': pl.Utf8,
    'centralCreditLimit': pl.Float64,
    'centralDiscountReason': pl.Utf8,
    'centralDiscountReasonDescription': pl.Utf8,
    'centralFBRevenue': pl.Float64,
    'centralGuestType': pl.Utf8,
    'centralHurdle': pl.Float64,
    'centralPackageCode': pl.Utf8,
    'centralPackageCodeDescription': pl.Utf8,
    'centralPackageForecastGroup': pl.Utf8,
    'centralPackageForecastGroupDescription': pl.Utf8,
    'centralPaymentAmount': pl.Float64,
    'centralProjectedFBRevenue': pl.Float64,
    'centralProjectedRoomRevenue': pl.Float64,
    'centralProjectedTotalRevenue': pl.Float64,
    'centralPromotionDescription': pl.Utf8,
    'centralRateableValue': pl.Float64,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralRoomTypeCode': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralRoomTypeToChargeCode': pl.Utf8,
    'centralRoomTypeToChargeDescription': pl.Utf8,
    'centralSharedRoomRate': pl.Float64,
    'centralSpecialRequestDescription': pl.Utf8,
    'centralTaxType': pl.Utf8,
    'centralTaxTypeDescription': pl.Utf8,
    'centralTotalCostOfStay': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralTotalRoomRate': pl.Float64,
    'centralWaitlistPriority': pl.Utf8,
    'centralWaitlistPriorityDescription': pl.Utf8,
    'centralWaitlistReason': pl.Utf8,
    'centralWaitlistReasonDescription': pl.Utf8,
    'channelDescription': pl.Utf8,
    'channelOrderBy': pl.Float64,
    'channelid': pl.Utf8,
    'checkInInitiatedBy': pl.Utf8,
    'checkinDuration': pl.Float64,
    'childBucket1': pl.Float64,
    'childBucket4': pl.Float64,
    'childBucket5': pl.Float64,
    'children': pl.Float64,
    'childrenAgeGroup2': pl.Float64,
    'childrenAgeGroup3': pl.Float64,
    'childrenAges': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionDescription': pl.Utf8,
    'commissionHoldCode': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionPayoutTo': pl.Utf8,
    'commissionableYN': pl.Utf8,
    'commissionid': pl.Utf8,
    'compHouse': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'companyCity': pl.Utf8,
    'companyCountry': pl.Utf8,
    'companyID': pl.Float64,
    'companyName': pl.Utf8,
    'companyProfileCorporateID': pl.Utf8,
    'companyProfileID': pl.Float64,
    'complimentaryYN': pl.Utf8,
    'compreasonid': pl.Utf8,
    'computedResvStatus': pl.Utf8,
    'confirmationLegNumber': pl.Float64,
    'confirmationNo': pl.Utf8,
    'consumerYn': pl.Utf8,
    'contactName': pl.Utf8,
    'contactProfileID': pl.Float64,
    'contactProfileName': pl.Utf8,
    'createdBy': pl.Utf8,
    'createdByDefaultResort': pl.Utf8,
    'createdDate': pl.Utf8,
    'createdTime': pl.Utf8,
    'creditCardAuthDate': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditLimit': pl.Float64,
    'creditLimitAutoPayAllowYn': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'customReferenceNumber': pl.Utf8,
    'dSI': pl.Int64,
    'dateOfArrivalInCountry': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'departtransportid': pl.Utf8,
    'departureComments': pl.Utf8,
    'departureDate': pl.Utf8,
    'departureDateTime': pl.Utf8,
    'departureTime': pl.Utf8,
    'departureTransportCode': pl.Utf8,
    'departureTransportationYN': pl.Utf8,
    'depositMaturityType': pl.Utf8,
    'detatchedDate': pl.Utf8,
    'detatchedYN': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'directbillauthby': pl.Float64,
    'discountAmount': pl.Float64,
    'discountAmt': pl.Float64,
    'discountPercent': pl.Float64,
    'discountPrcnt': pl.Float64,
    'discountReason': pl.Utf8,
    'discountReasonDescription': pl.Utf8,
    'discountreasonid': pl.Utf8,
    'displayColor': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doNotMoveRoom': pl.Utf8,
    'doNotMoveYN': pl.Utf8,
    'dropOffCarrierCode': pl.Utf8,
    'dropOffDate': pl.Utf8,
    'dropOffStation': pl.Utf8,
    'dropOffTime': pl.Utf8,
    'dropOffType': pl.Utf8,
    'dropOffTypeDescription': pl.Utf8,
    'eTRComments': pl.Utf8,
    'effectiveRateAmount': pl.Float64,
    'eligibleForUpgradeYn': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'emailId': pl.Float64,
    'emailYn': pl.Utf8,
    'endCity': pl.Utf8,
    'endDatetime': pl.Utf8,
    'endDistrict': pl.Utf8,
    'endState': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'entryDate': pl.Utf8,
    'entryPoint': pl.Utf8,
    'esignedRegCardName': pl.Utf8,
    'estimatedDepartureTime': pl.Utf8,
    'eventId': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'excludeFromAutoAuthorizationYN': pl.Utf8,
    'expectedTimeOfReturnETR': pl.Utf8,
    'exportCheckinresId': pl.Float64,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'extensionId': pl.Float64,
    'externalEfolioYn': pl.Utf8,
    'externalReference': pl.Utf8,
    'externalReferencesList': pl.Utf8,
    'extraBeds': pl.Float64,
    'fBRevenue': pl.Float64,
    'fBRevenueRemaining': pl.Float64,
    'faxId': pl.Float64,
    'faxYn': pl.Utf8,
    'feature': pl.Utf8,
    'financiallyResponsibleYn': pl.Utf8,
    'fixedCharge': pl.Float64,
    'fixedRateYN': pl.Utf8,
    'folioAddrElementId': pl.Float64,
    'folioCloseDate': pl.Utf8,
    'folioNumber': pl.Utf8,
    'folioText1': pl.Utf8,
    'folioText2': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'freeChild': pl.Float64,
    'frequentFlyerMembershipYN': pl.Utf8,
    'grossRateFuture': pl.Float64,
    'grossRatePast': pl.Float64,
    'groupName': pl.Utf8,
    'groupProfileARNumber': pl.Float64,
    'groupProfileARNumberCentral': pl.Utf8,
    'groupProfileClientID': pl.Utf8,
    'groupProfileID': pl.Float64,
    'groupProfileName': pl.Utf8,
    'guaranteeCodePreCi': pl.Utf8,
    'guaranteecodeid': pl.Utf8,
    'guestFirstName': pl.Utf8,
    'guestFirstNameSdx': pl.Utf8,
    'guestLastNameSdx': pl.Utf8,
    'guestSignature': pl.Utf8,
    'guestStatus': pl.Utf8,
    'guestType': pl.Utf8,
    'guestprofileid': pl.Float64,
    'gueststatusid': pl.Utf8,
    'guesttypeid': pl.Utf8,
    'housekeepingServiceTime': pl.Utf8,
    'hurdle': pl.Float64,
    'hurdleOverride': pl.Utf8,
    'iDByMembershipClass': pl.Utf8,
    'iDByMembershipType': pl.Utf8,
    'individualCity': pl.Utf8,
    'individualCountry': pl.Utf8,
    'individualFirstName': pl.Utf8,
    'individualLastName': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertDateTime': pl.Utf8,
    'insertUser': pl.Int64,
    'intermediaryYn': pl.Utf8,
    'internalAwardMembershipId': pl.Float64,
    'internalBaseratecode': pl.Utf8,
    'internalBlockId': pl.Float64,
    'internalCompanyprofileid': pl.Float64,
    'internalGroupprofileid': pl.Float64,
    'internalSourceprofileid': pl.Float64,
    'itemsQuantities': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyValidUntil': pl.Utf8,
    'lastOnlinePrintSeq': pl.Float64,
    'lastPeriodicFolioDate': pl.Utf8,
    'lastRoomNumber': pl.Utf8,
    'lastSettleDate': pl.Utf8,
    'leadTimeDays': pl.Float64,
    'lengthOfStay': pl.Float64,
    'linkedArrivalDate': pl.Utf8,
    'linkedDepartureDate': pl.Utf8,
    'linkedRoomType': pl.Utf8,
    'listOfMembershipID': pl.Utf8,
    'localBaseRateAmount': pl.Float64,
    'locationID': pl.Utf8,
    'loyaltySchemeMembershipYN': pl.Utf8,
    'mailYn': pl.Utf8,
    'manualCheckoutStatus': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketid': pl.Utf8,
    'mcGenBeginDistrict': pl.Utf8,
    'mcGenBeginState': pl.Utf8,
    'mcGenEndDistrict': pl.Utf8,
    'mcGenEndState': pl.Utf8,
    'mcGenNextCountry': pl.Utf8,
    'mcGenPreviousCountry': pl.Utf8,
    'memberDescription': pl.Utf8,
    'memberLevel': pl.Utf8,
    'memberNumber': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipClassDescription': pl.Utf8,
    'membershipCode': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevelByMembershipClass': pl.Utf8,
    'membershipTypeByMembershipClass': pl.Utf8,
    'mobileActionAlertIssued': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'mobilePreferredCurrency': pl.Utf8,
    'mobileViewFolioAllowed': pl.Utf8,
    'name': pl.Utf8,
    'nameUsageType': pl.Utf8,
    'nextCountry': pl.Utf8,
    'nextDestination': pl.Utf8,
    'numberOfRooms': pl.Float64,
    'operaEsignedRegCardYn': pl.Utf8,
    'optInBatchFolYn': pl.Utf8,
    'optedForCommissionYN': pl.Utf8,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originOfBooking': pl.Utf8,
    'originalBaseRate': pl.Float64,
    'originalEndDate': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'ownerFfFlag': pl.Utf8,
    'ownerOrFriendsFamily': pl.Utf8,
    'packageCode': pl.Utf8,
    'packageCodeDescription': pl.Utf8,
    'packageForecastGroup': pl.Utf8,
    'packageForecastGroupDescription': pl.Utf8,
    'parentReservationNameId': pl.Float64,
    'parentreservationid': pl.Float64,
    'partAllotment': pl.Utf8,
    'partyCode': pl.Utf8,
    'paxNo': pl.Float64,
    'paymentAmount': pl.Float64,
    'paymentMethod': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'periodicFolioFreq': pl.Float64,
    'phoneDisplayNameYn': pl.Utf8,
    'phoneId': pl.Float64,
    'physicalQuantity': pl.Float64,
    'pickUpCarrierCode': pl.Utf8,
    'pickUpDate': pl.Utf8,
    'pickUpStation': pl.Utf8,
    'pickUpTransportNumber': pl.Utf8,
    'pickUpType': pl.Utf8,
    'pickUpTypeDescription': pl.Utf8,
    'pickUpTime': pl.Utf8,
    'pickupRequiredYN': pl.Utf8,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'postCoFlag': pl.Utf8,
    'postStayChargingYN': pl.Utf8,
    'postingAllowedYN': pl.Utf8,
    'preArrReviewedDt': pl.Utf8,
    'preArrReviewedUser': pl.Float64,
    'preChargingYn': pl.Utf8,
    'preRegisteredYn': pl.Utf8,
    'preference': pl.Utf8,
    'preferenceType': pl.Utf8,
    'preferredRoomType': pl.Utf8,
    'previousCountry': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryShare': pl.Utf8,
    'printRateYN': pl.Utf8,
    'projectedFBRevenue': pl.Float64,
    'projectedRoomRevenue': pl.Float64,
    'projectedTotalRevenue': pl.Float64,
    'promotionCode': pl.Utf8,
    'promotionDescription': pl.Utf8,
    'property': pl.Utf8,
    'pseudoMemTotalPoints': pl.Float64,
    'pseudoMemType': pl.Utf8,
    'purgeDate': pl.Utf8,
    'purposeOfStay': pl.Utf8,
    'quantity': pl.Float64,
    'queuePriority': pl.Float64,
    'queueWaitTime': pl.Float64,
    'quoteId': pl.Utf8,
    'rateAmount': pl.Float64,
    'rateCode': pl.Utf8,
    'rateCodeDescriptions': pl.Utf8,
    'rateTier': pl.Float64,
    'rateableValue': pl.Float64,
    'ratecodeid': pl.Utf8,
    'rdHousekeepingExpectedServiceTime': pl.Utf8,
    'rdResvStatus': pl.Utf8,
    'rdenBillingContactId': pl.Float64,
    'rdenReservationContactId': pl.Float64,
    'rdenReservationDate': pl.Utf8,
    'rdenResort': pl.Utf8,
    'referralYn': pl.Utf8,
    'registrationCardNo': pl.Utf8,
    'registrationNumber': pl.Float64,
    'reinstateDate': pl.Utf8,
    'repChannel': pl.Utf8,
    'repChannelDescription': pl.Utf8,
    'reportId': pl.Utf8,
    'resInsertSource': pl.Utf8,
    'resInsertSourceType': pl.Utf8,
    'reservationContactId': pl.Float64,
    'reservationDate': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reservationid': pl.Float64,
    'resort': pl.Utf8,
    'resortChargeNumber': pl.Utf8,
    'restrictionOverride': pl.Utf8,
    'resvGuid': pl.Utf8,
    'resvNameid': pl.Float64,
    'resvNumber': pl.Float64,
    'resvcontactprofileid': pl.Float64,
    'revenueTypeCode': pl.Utf8,
    'rhBillingContactId': pl.Float64,
    'rhReservationContactId': pl.Float64,
    'rhRoomFeatures': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomCost': pl.Float64,
    'roomInstructions': pl.Utf8,
    'roomResort': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueRemaining': pl.Float64,
    'roomServiceTime': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomTypeToChargeCode': pl.Utf8,
    'roomTypeToChargeDescription': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomid': pl.Utf8,
    'routingYN': pl.Utf8,
    'scheduleCheckoutYn': pl.Utf8,
    'sguestFirstname': pl.Utf8,
    'sguestName': pl.Utf8,
    'shareConfirmationNumbers': pl.Utf8,
    'shareId': pl.Float64,
    'shareName': pl.Utf8,
    'sharePrcnt': pl.Float64,
    'shareSeqNumber': pl.Float64,
    'shareOfRateAmount': pl.Float64,
    'sharedGuestName': pl.Utf8,
    'sharedProfileID': pl.Float64,
    'sharedReservationStatus': pl.Utf8,
    'sharingYN': pl.Utf8,
    'sourceCity': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCountry': pl.Utf8,
    'sourceName': pl.Utf8,
    'sourceProfileARNumber': pl.Float64,
    'sourceProfileARNumberCentral': pl.Utf8,
    'sourceProfileIATANumber': pl.Utf8,
    'sourceProfileID': pl.Float64,
    'sourceProfileName': pl.Utf8,
    'sourceid': pl.Utf8,
    'specialRequest': pl.Utf8,
    'specialRequestDescription': pl.Utf8,
    'spgDiscloseRoomTypeYn': pl.Utf8,
    'spgSuiteNightAwardStatus': pl.Utf8,
    'spgUpgradeConfirmedRoomtype': pl.Utf8,
    'spgUpgradeReasonCode': pl.Utf8,
    'splitFromReservationNameId': pl.Float64,
    'splitfromreservationid': pl.Float64,
    'statisticalRateTier': pl.Float64,
    'statisticalRoomType': pl.Float64,
    'stayRecordId': pl.Float64,
    'suiteNumber': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'taRecordLocator': pl.Utf8,
    'taxExemptNumber': pl.Utf8,
    'taxNumberOfStays': pl.Float64,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tiad': pl.Utf8,
    'ticketNos': pl.Utf8,
    'totalCostOfStay': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueRemaining': pl.Float64,
    'totalRoomRate': pl.Float64,
    'trackItGroups': pl.Utf8,
    'trackItTypes': pl.Utf8,
    'transactionid': pl.Float64,
    'travelAgentCity': pl.Utf8,
    'travelAgentCountry': pl.Utf8,
    'travelAgentID': pl.Float64,
    'travelAgentName': pl.Utf8,
    'travelAgentProfileARNumber': pl.Float64,
    'travelAgentProfileARNumberCentral': pl.Utf8,
    'travelAgentProfileIATANumber': pl.Utf8,
    'travelAgentProfileID': pl.Float64,
    'travelAgentProfileName': pl.Utf8,
    'truncActualCheckOutDate': pl.Utf8,
    'turndownStatus': pl.Utf8,
    'turndownYN': pl.Utf8,
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
    'uDFC11': pl.Utf8,
    'uDFC12': pl.Utf8,
    'uDFC13': pl.Utf8,
    'uDFC14': pl.Utf8,
    'uDFC15': pl.Utf8,
    'uDFC16': pl.Utf8,
    'uDFC17': pl.Utf8,
    'uDFC18': pl.Utf8,
    'uDFC19': pl.Utf8,
    'uDFC20': pl.Utf8,
    'uDFC21': pl.Utf8,
    'uDFC22': pl.Utf8,
    'uDFC23': pl.Utf8,
    'uDFC24': pl.Utf8,
    'uDFC25': pl.Utf8,
    'uDFC26': pl.Utf8,
    'uDFC27': pl.Utf8,
    'uDFC28': pl.Utf8,
    'uDFC29': pl.Utf8,
    'uDFC30': pl.Utf8,
    'uDFC31': pl.Utf8,
    'uDFC32': pl.Utf8,
    'uDFC33': pl.Utf8,
    'uDFC34': pl.Utf8,
    'uDFC35': pl.Utf8,
    'uDFC36': pl.Utf8,
    'uDFC37': pl.Utf8,
    'uDFC38': pl.Utf8,
    'uDFC39': pl.Utf8,
    'uDFC40': pl.Utf8,
    'uDFD01': pl.Utf8,
    'uDFD02': pl.Utf8,
    'uDFD03': pl.Utf8,
    'uDFD04': pl.Utf8,
    'uDFD05': pl.Utf8,
    'uDFD06': pl.Utf8,
    'uDFD07': pl.Utf8,
    'uDFD08': pl.Utf8,
    'uDFD09': pl.Utf8,
    'uDFD10': pl.Utf8,
    'uDFD11': pl.Utf8,
    'uDFD12': pl.Utf8,
    'uDFD13': pl.Utf8,
    'uDFD14': pl.Utf8,
    'uDFD15': pl.Utf8,
    'uDFD16': pl.Utf8,
    'uDFD17': pl.Utf8,
    'uDFD18': pl.Utf8,
    'uDFD19': pl.Utf8,
    'uDFD20': pl.Utf8,
    'uDFN01': pl.Float64,
    'uDFN02': pl.Float64,
    'uDFN03': pl.Float64,
    'uDFN04': pl.Float64,
    'uDFN05': pl.Float64,
    'uDFN06': pl.Float64,
    'uDFN07': pl.Float64,
    'uDFN08': pl.Float64,
    'uDFN09': pl.Float64,
    'uDFN10': pl.Float64,
    'uDFN11': pl.Float64,
    'uDFN12': pl.Float64,
    'uDFN13': pl.Float64,
    'uDFN14': pl.Float64,
    'uDFN15': pl.Float64,
    'uDFN16': pl.Float64,
    'uDFN17': pl.Float64,
    'uDFN18': pl.Float64,
    'uDFN19': pl.Float64,
    'uDFN20': pl.Float64,
    'uDFN21': pl.Float64,
    'uDFN22': pl.Float64,
    'uDFN23': pl.Float64,
    'uDFN24': pl.Float64,
    'uDFN25': pl.Float64,
    'uDFN26': pl.Float64,
    'uDFN27': pl.Float64,
    'uDFN28': pl.Float64,
    'uDFN29': pl.Float64,
    'uDFN30': pl.Float64,
    'uDFN31': pl.Float64,
    'uDFN32': pl.Float64,
    'uDFN33': pl.Float64,
    'uDFN34': pl.Float64,
    'uDFN35': pl.Float64,
    'uDFN36': pl.Float64,
    'uDFN37': pl.Float64,
    'uDFN38': pl.Float64,
    'uDFN39': pl.Float64,
    'uDFN40': pl.Float64,
    'uniCardId': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateDatetime': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedByDefaultResort': pl.Utf8,
    'updatedDate': pl.Utf8,
    'updatedTime': pl.Utf8,
    'upsellCharge': pl.Float64,
    'videoCheckoutYN': pl.Utf8,
    'visaExpiryDate': pl.Utf8,
    'visaIssueDate': pl.Utf8,
    'visaNumber': pl.Utf8,
    'waitlistComment': pl.Utf8,
    'waitlistPhoneNumber': pl.Utf8,
    'waitlistPriority': pl.Utf8,
    'waitlistPriorityDescription': pl.Utf8,
    'waitlistReason': pl.Utf8,
    'waitlistReasonDescription': pl.Utf8,
    'waitlistpriorityid': pl.Utf8,
    'waitlistreasonid': pl.Utf8,
    'walkInYN': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Utf8,
}
```
```python
to_reservation_details_schema = {
    'aSBProratedYn': pl.Utf8,
    'accompaniedYN': pl.Utf8,
    'accompanyingName': pl.Utf8,
    'actualCheckInDateTime': pl.Utf8,
    'actualCheckOutDateTime': pl.Utf8,
    'actualCheckInDate': pl.Utf8,
    'actualCheckInTime': pl.Utf8,
    'actualCheckOutDate': pl.Utf8,
    'actualCheckOutTime': pl.Utf8,
    'addressId': pl.Float64,
    'addresseeNameId': pl.Float64,
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'advanceCheckedInYn': pl.Utf8,
    'agencyprofileid': pl.Float64,
    'allotmentRecordType': pl.Utf8,
    'allotmentid': pl.Float64,
    'amenityEligibleYn': pl.Utf8,
    'amenityLevelCode': pl.Utf8,
    'amountPercent': pl.Float64,
    'approvalAmount': pl.Float64,
    'approvalAmountCalcMethod': pl.Float64,
    'approvalCode': pl.Utf8,
    'arrivalComments': pl.Utf8,
    'arrivalDate': pl.Utf8,
    'arrivalDateTime': pl.Utf8,
    'arrivalEstimateTime': pl.Utf8,
    'arrivalTime': pl.Utf8,
    'arrivaltransportid': pl.Utf8,
    'attachedDate': pl.Utf8,
    'authorizedBillingYN': pl.Utf8,
    'authorizedBy': pl.Float64,
    'authorizerId': pl.Float64,
    'autoCheckinYn': pl.Utf8,
    'autoPopulateRoutingYn': pl.Utf8,
    'autoSettleDays': pl.Float64,
    'autoSettleType': pl.Utf8,
    'autoSettleYN': pl.Utf8,
    'awardCode': pl.Utf8,
    'awardCode1': pl.Utf8,
    'awardCode2': pl.Utf8,
    'awardCode3': pl.Utf8,
    'awardCode4': pl.Utf8,
    'awardCode5': pl.Utf8,
    'awardMembershipID': pl.Float64,
    'awardVoucher1': pl.Utf8,
    'awardVoucher2': pl.Utf8,
    'awardVoucher3': pl.Utf8,
    'awardVoucher4': pl.Utf8,
    'awardVoucher5': pl.Utf8,
    'awdUpgrFrom': pl.Utf8,
    'awdUpgrTo': pl.Utf8,
    'backToBackYN': pl.Utf8,
    'balance': pl.Float64,
    'baseRateAmount': pl.Float64,
    'baseRateCode': pl.Utf8,
    'baseRateCurrencyCode': pl.Utf8,
    'basedOnRule': pl.Utf8,
    'baseratecurrencyid': pl.Utf8,
    'beginCity': pl.Utf8,
    'beginDatetime': pl.Utf8,
    'beginDistrict': pl.Utf8,
    'beginState': pl.Utf8,
    'beginSystemDateTime': pl.Utf8,
    'billNumber': pl.Utf8,
    'billingContact': pl.Utf8,
    'billingContactDisplayName': pl.Utf8,
    'billingContactId': pl.Float64,
    'billingContactName': pl.Utf8,
    'billingcontactprofileid': pl.Float64,
    'blockCode': pl.Utf8,
    'blockCreateDate': pl.Utf8,
    'blockID': pl.Float64,
    'blockName': pl.Utf8,
    'blockResort': pl.Utf8,
    'blockStatus': pl.Utf8,
    'bonusCheckId': pl.Float64,
    'bookedRoomCategory': pl.Utf8,
    'bookedroomcategoryid': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'businessDatetimeCreated': pl.Utf8,
    'bxgyDiscountYn': pl.Utf8,
    'cAutoPostAmount': pl.Float64,
    'cBaseRateAmount': pl.Float64,
    'cDiscountAmount': pl.Float64,
    'cDiscountAmt': pl.Float64,
    'cEffectiveRateAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFixedCharge': pl.Float64,
    'cGrossRateAmount': pl.Float64,
    'cLocalBaseRateAmount': pl.Float64,
    'cNetRoomAmount': pl.Float64,
    'cOriginalBaseRate': pl.Float64,
    'cPackageAmount': pl.Float64,
    'cPackageTax': pl.Float64,
    'cRateAmount': pl.Float64,
    'cRoomCost': pl.Float64,
    'cRoomTax': pl.Float64,
    'cShareAmountOriginal': pl.Float64,
    'cUpsellCharge': pl.Float64,
    'cancelDate': pl.Utf8,
    'cancelReason': pl.Utf8,
    'cancelTime': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationDatetime': pl.Utf8,
    'cancellationNumber': pl.Utf8,
    'cancellationReasonDescription': pl.Utf8,
    'cancellationreasonid': pl.Utf8,
    'cancelledBy': pl.Utf8,
    'cardNumberByMembershipClass': pl.Utf8,
    'cardNumberByMembershipType': pl.Utf8,
    'centralApprovalAmount': pl.Float64,
    'centralCancelReason': pl.Utf8,
    'centralCommissionCode': pl.Utf8,
    'centralCommissionDescription': pl.Utf8,
    'centralCreditLimit': pl.Float64,
    'centralDiscountReason': pl.Utf8,
    'centralDiscountReasonDescription': pl.Utf8,
    'centralFBRevenue': pl.Float64,
    'centralGuestType': pl.Utf8,
    'centralHurdle': pl.Float64,
    'centralPackageCode': pl.Utf8,
    'centralPackageCodeDescription': pl.Utf8,
    'centralPackageForecastGroup': pl.Utf8,
    'centralPackageForecastGroupDescription': pl.Utf8,
    'centralPaymentAmount': pl.Float64,
    'centralProjectedFBRevenue': pl.Float64,
    'centralProjectedRoomRevenue': pl.Float64,
    'centralProjectedTotalRevenue': pl.Float64,
    'centralPromotionDescription': pl.Utf8,
    'centralRateableValue': pl.Float64,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'centralRoomRevenue': pl.Float64,
    'centralRoomTypeCode': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralRoomTypeToChargeCode': pl.Utf8,
    'centralRoomTypeToChargeDescription': pl.Utf8,
    'centralSharedRoomRate': pl.Float64,
    'centralSpecialRequestDescription': pl.Utf8,
    'centralTaxType': pl.Utf8,
    'centralTaxTypeDescription': pl.Utf8,
    'centralTotalCostOfStay': pl.Float64,
    'centralTotalRevenue': pl.Float64,
    'centralTotalRoomRate': pl.Float64,
    'centralWaitlistPriority': pl.Utf8,
    'centralWaitlistPriorityDescription': pl.Utf8,
    'centralWaitlistReason': pl.Utf8,
    'centralWaitlistReasonDescription': pl.Utf8,
    'channelDescription': pl.Utf8,
    'channelOrderBy': pl.Float64,
    'channelid': pl.Utf8,
    'checkInInitiatedBy': pl.Utf8,
    'checkinDuration': pl.Float64,
    'childBucket1': pl.Float64,
    'childBucket4': pl.Float64,
    'childBucket5': pl.Float64,
    'children': pl.Float64,
    'childrenAgeGroup2': pl.Float64,
    'childrenAgeGroup3': pl.Float64,
    'childrenAges': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionDescription': pl.Utf8,
    'commissionHoldCode': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionPayoutTo': pl.Utf8,
    'commissionableYN': pl.Utf8,
    'commissionid': pl.Utf8,
    'compHouse': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'companyCity': pl.Utf8,
    'companyCountry': pl.Utf8,
    'companyID': pl.Float64,
    'companyName': pl.Utf8,
    'companyProfileCorporateID': pl.Utf8,
    'companyProfileID': pl.Float64,
    'complimentaryYN': pl.Utf8,
    'compreasonid': pl.Utf8,
    'computedResvStatus': pl.Utf8,
    'confirmationLegNumber': pl.Float64,
    'confirmationNo': pl.Utf8,
    'consumerYn': pl.Utf8,
    'contactName': pl.Utf8,
    'contactProfileID': pl.Float64,
    'contactProfileName': pl.Utf8,
    'createdBy': pl.Utf8,
    'createdByDefaultResort': pl.Utf8,
    'createdDate': pl.Utf8,
    'createdTime': pl.Utf8,
    'creditCardAuthDate': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditLimit': pl.Float64,
    'creditLimitAutoPayAllowYn': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'customReferenceNumber': pl.Utf8,
    'dSI': pl.Int64,
    'dateOfArrivalInCountry': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'departtransportid': pl.Utf8,
    'departureComments': pl.Utf8,
    'departureDate': pl.Utf8,
    'departureDateTime': pl.Utf8,
    'departureTime': pl.Utf8,
    'departureTransportCode': pl.Utf8,
    'departureTransportationYN': pl.Utf8,
    'depositMaturityType': pl.Utf8,
    'detatchedDate': pl.Utf8,
    'detatchedYN': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'directbillauthby': pl.Float64,
    'discountAmount': pl.Float64,
    'discountAmt': pl.Float64,
    'discountPercent': pl.Float64,
    'discountPrcnt': pl.Float64,
    'discountReason': pl.Utf8,
    'discountReasonDescription': pl.Utf8,
    'discountreasonid': pl.Utf8,
    'displayColor': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doNotMoveRoom': pl.Utf8,
    'doNotMoveYN': pl.Utf8,
    'dropOffCarrierCode': pl.Utf8,
    'dropOffDate': pl.Utf8,
    'dropOffStation': pl.Utf8,
    'dropOffTime': pl.Utf8,
    'dropOffType': pl.Utf8,
    'dropOffTypeDescription': pl.Utf8,
    'eTRComments': pl.Utf8,
    'effectiveRateAmount': pl.Float64,
    'eligibleForUpgradeYn': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'emailId': pl.Float64,
    'emailYn': pl.Utf8,
    'endCity': pl.Utf8,
    'endDatetime': pl.Utf8,
    'endDistrict': pl.Utf8,
    'endState': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'entryDate': pl.Utf8,
    'entryPoint': pl.Utf8,
    'esignedRegCardName': pl.Utf8,
    'estimatedDepartureTime': pl.Utf8,
    'eventId': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'excludeFromAutoAuthorizationYN': pl.Utf8,
    'expectedTimeOfReturnETR': pl.Utf8,
    'exportCheckinresId': pl.Float64,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'extensionId': pl.Float64,
    'externalEfolioYn': pl.Utf8,
    'externalReference': pl.Utf8,
    'externalReferencesList': pl.Utf8,
    'extraBeds': pl.Float64,
    'fBRevenue': pl.Float64,
    'fBRevenueRemaining': pl.Float64,
    'faxId': pl.Float64,
    'faxYn': pl.Utf8,
    'feature': pl.Utf8,
    'financiallyResponsibleYn': pl.Utf8,
    'fixedCharge': pl.Float64,
    'fixedRateYN': pl.Utf8,
    'folioAddrElementId': pl.Float64,
    'folioCloseDate': pl.Utf8,
    'folioNumber': pl.Utf8,
    'folioText1': pl.Utf8,
    'folioText2': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'freeChild': pl.Float64,
    'frequentFlyerMembershipYN': pl.Utf8,
    'grossRateFuture': pl.Float64,
    'grossRatePast': pl.Float64,
    'groupName': pl.Utf8,
    'groupProfileARNumber': pl.Float64,
    'groupProfileARNumberCentral': pl.Utf8,
    'groupProfileClientID': pl.Utf8,
    'groupProfileID': pl.Float64,
    'groupProfileName': pl.Utf8,
    'guaranteeCodePreCi': pl.Utf8,
    'guaranteecodeid': pl.Utf8,
    'guestFirstName': pl.Utf8,
    'guestFirstNameSdx': pl.Utf8,
    'guestLastNameSdx': pl.Utf8,
    'guestSignature': pl.Utf8,
    'guestStatus': pl.Utf8,
    'guestType': pl.Utf8,
    'guestprofileid': pl.Float64,
    'gueststatusid': pl.Utf8,
    'guesttypeid': pl.Utf8,
    'housekeepingServiceTime': pl.Utf8,
    'hurdle': pl.Float64,
    'hurdleOverride': pl.Utf8,
    'iDByMembershipClass': pl.Utf8,
    'iDByMembershipType': pl.Utf8,
    'individualCity': pl.Utf8,
    'individualCountry': pl.Utf8,
    'individualFirstName': pl.Utf8,
    'individualLastName': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertDateTime': pl.Utf8,
    'insertUser': pl.Int64,
    'intermediaryYn': pl.Utf8,
    'internalAwardMembershipId': pl.Float64,
    'internalBaseratecode': pl.Utf8,
    'internalBlockId': pl.Float64,
    'internalCompanyprofileid': pl.Float64,
    'internalGroupprofileid': pl.Float64,
    'internalSourceprofileid': pl.Float64,
    'itemsQuantities': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyValidUntil': pl.Utf8,
    'lastOnlinePrintSeq': pl.Float64,
    'lastPeriodicFolioDate': pl.Utf8,
    'lastRoomNumber': pl.Utf8,
    'lastSettleDate': pl.Utf8,
    'leadTimeDays': pl.Float64,
    'lengthOfStay': pl.Float64,
    'linkedArrivalDate': pl.Utf8,
    'linkedDepartureDate': pl.Utf8,
    'linkedRoomType': pl.Utf8,
    'listOfMembershipID': pl.Utf8,
    'localBaseRateAmount': pl.Float64,
    'locationID': pl.Utf8,
    'loyaltySchemeMembershipYN': pl.Utf8,
    'mailYn': pl.Utf8,
    'manualCheckoutStatus': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketid': pl.Utf8,
    'mcGenBeginDistrict': pl.Utf8,
    'mcGenBeginState': pl.Utf8,
    'mcGenEndDistrict': pl.Utf8,
    'mcGenEndState': pl.Utf8,
    'mcGenNextCountry': pl.Utf8,
    'mcGenPreviousCountry': pl.Utf8,
    'memberDescription': pl.Utf8,
    'memberLevel': pl.Utf8,
    'memberNumber': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipClassDescription': pl.Utf8,
    'membershipCode': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevelByMembershipClass': pl.Utf8,
    'membershipTypeByMembershipClass': pl.Utf8,
    'mobileActionAlertIssued': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'mobilePreferredCurrency': pl.Utf8,
    'mobileViewFolioAllowed': pl.Utf8,
    'name': pl.Utf8,
    'nameUsageType': pl.Utf8,
    'nextCountry': pl.Utf8,
    'nextDestination': pl.Utf8,
    'numberOfRooms': pl.Float64,
    'operaEsignedRegCardYn': pl.Utf8,
    'optInBatchFolYn': pl.Utf8,
    'optedForCommissionYN': pl.Utf8,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originOfBooking': pl.Utf8,
    'originalBaseRate': pl.Float64,
    'originalEndDate': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'ownerFfFlag': pl.Utf8,
    'ownerOrFriendsFamily': pl.Utf8,
    'packageCode': pl.Utf8,
    'packageCodeDescription': pl.Utf8,
    'packageForecastGroup': pl.Utf8,
    'packageForecastGroupDescription': pl.Utf8,
    'parentReservationNameId': pl.Float64,
    'parentreservationid': pl.Float64,
    'partAllotment': pl.Utf8,
    'partyCode': pl.Utf8,
    'paxNo': pl.Float64,
    'paymentAmount': pl.Float64,
    'paymentMethod': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'periodicFolioFreq': pl.Float64,
    'phoneDisplayNameYn': pl.Utf8,
    'phoneId': pl.Float64,
    'physicalQuantity': pl.Float64,
    'pickUpCarrierCode': pl.Utf8,
    'pickUpDate': pl.Utf8,
    'pickUpStation': pl.Utf8,
    'pickUpTransportNumber': pl.Utf8,
    'pickUpType': pl.Utf8,
    'pickUpTypeDescription': pl.Utf8,
    'pickUpTime': pl.Utf8,
    'pickupRequiredYN': pl.Utf8,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'postCoFlag': pl.Utf8,
    'postStayChargingYN': pl.Utf8,
    'postingAllowedYN': pl.Utf8,
    'preArrReviewedDt': pl.Utf8,
    'preArrReviewedUser': pl.Float64,
    'preChargingYn': pl.Utf8,
    'preRegisteredYn': pl.Utf8,
    'preference': pl.Utf8,
    'preferenceType': pl.Utf8,
    'preferredRoomType': pl.Utf8,
    'previousCountry': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryShare': pl.Utf8,
    'printRateYN': pl.Utf8,
    'projectedFBRevenue': pl.Float64,
    'projectedRoomRevenue': pl.Float64,
    'projectedTotalRevenue': pl.Float64,
    'promotionCode': pl.Utf8,
    'promotionDescription': pl.Utf8,
    'property': pl.Utf8,
    'pseudoMemTotalPoints': pl.Float64,
    'pseudoMemType': pl.Utf8,
    'purgeDate': pl.Utf8,
    'purposeOfStay': pl.Utf8,
    'quantity': pl.Float64,
    'queuePriority': pl.Float64,
    'queueWaitTime': pl.Float64,
    'quoteId': pl.Utf8,
    'rateAmount': pl.Float64,
    'rateCode': pl.Utf8,
    'rateCodeDescriptions': pl.Utf8,
    'rateTier': pl.Float64,
    'rateableValue': pl.Float64,
    'ratecodeid': pl.Utf8,
    'rdHousekeepingExpectedServiceTime': pl.Utf8,
    'rdResvStatus': pl.Utf8,
    'rdenBillingContactId': pl.Float64,
    'rdenReservationContactId': pl.Float64,
    'rdenReservationDate': pl.Utf8,
    'rdenResort': pl.Utf8,
    'referralYn': pl.Utf8,
    'registrationCardNo': pl.Utf8,
    'registrationNumber': pl.Float64,
    'reinstateDate': pl.Utf8,
    'repChannel': pl.Utf8,
    'repChannelDescription': pl.Utf8,
    'reportId': pl.Utf8,
    'resInsertSource': pl.Utf8,
    'resInsertSourceType': pl.Utf8,
    'reservationContactId': pl.Float64,
    'reservationDate': pl.Utf8,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reservationid': pl.Float64,
    'resort': pl.Utf8,
    'resortChargeNumber': pl.Utf8,
    'restrictionOverride': pl.Utf8,
    'resvGuid': pl.Utf8,
    'resvNameid': pl.Float64,
    'resvNumber': pl.Float64,
    'resvcontactprofileid': pl.Float64,
    'revenueTypeCode': pl.Utf8,
    'rhBillingContactId': pl.Float64,
    'rhReservationContactId': pl.Float64,
    'rhRoomFeatures': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomCost': pl.Float64,
    'roomInstructions': pl.Utf8,
    'roomResort': pl.Utf8,
    'roomRevenue': pl.Float64,
    'roomRevenueRemaining': pl.Float64,
    'roomServiceTime': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomTypeToChargeCode': pl.Utf8,
    'roomTypeToChargeDescription': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomid': pl.Utf8,
    'routingYN': pl.Utf8,
    'scheduleCheckoutYn': pl.Utf8,
    'sguestFirstname': pl.Utf8,
    'sguestName': pl.Utf8,
    'shareConfirmationNumbers': pl.Utf8,
    'shareId': pl.Float64,
    'shareName': pl.Utf8,
    'sharePrcnt': pl.Float64,
    'shareSeqNumber': pl.Float64,
    'shareOfRateAmount': pl.Float64,
    'sharedGuestName': pl.Utf8,
    'sharedProfileID': pl.Float64,
    'sharedReservationStatus': pl.Utf8,
    'sharingYN': pl.Utf8,
    'sourceCity': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCountry': pl.Utf8,
    'sourceName': pl.Utf8,
    'sourceProfileARNumber': pl.Float64,
    'sourceProfileARNumberCentral': pl.Utf8,
    'sourceProfileIATANumber': pl.Utf8,
    'sourceProfileID': pl.Float64,
    'sourceProfileName': pl.Utf8,
    'sourceid': pl.Utf8,
    'specialRequest': pl.Utf8,
    'specialRequestDescription': pl.Utf8,
    'spgDiscloseRoomTypeYn': pl.Utf8,
    'spgSuiteNightAwardStatus': pl.Utf8,
    'spgUpgradeConfirmedRoomtype': pl.Utf8,
    'spgUpgradeReasonCode': pl.Utf8,
    'splitFromReservationNameId': pl.Float64,
    'splitfromreservationid': pl.Float64,
    'statisticalRateTier': pl.Float64,
    'statisticalRoomType': pl.Float64,
    'stayRecordId': pl.Float64,
    'suiteNumber': pl.Utf8,
    'superSearchIndexText': pl.Utf8,
    'taRecordLocator': pl.Utf8,
    'taxExemptNumber': pl.Utf8,
    'taxNumberOfStays': pl.Float64,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tiad': pl.Utf8,
    'ticketNos': pl.Utf8,
    'totalCostOfStay': pl.Float64,
    'totalRevenue': pl.Float64,
    'totalRevenueRemaining': pl.Float64,
    'totalRoomRate': pl.Float64,
    'trackItGroups': pl.Utf8,
    'trackItTypes': pl.Utf8,
    'transactionid': pl.Float64,
    'travelAgentCity': pl.Utf8,
    'travelAgentCountry': pl.Utf8,
    'travelAgentID': pl.Float64,
    'travelAgentName': pl.Utf8,
    'travelAgentProfileARNumber': pl.Float64,
    'travelAgentProfileARNumberCentral': pl.Utf8,
    'travelAgentProfileIATANumber': pl.Utf8,
    'travelAgentProfileID': pl.Float64,
    'travelAgentProfileName': pl.Utf8,
    'truncActualCheckOutDate': pl.Utf8,
    'turndownStatus': pl.Utf8,
    'turndownYN': pl.Utf8,
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
    'uDFC11': pl.Utf8,
    'uDFC12': pl.Utf8,
    'uDFC13': pl.Utf8,
    'uDFC14': pl.Utf8,
    'uDFC15': pl.Utf8,
    'uDFC16': pl.Utf8,
    'uDFC17': pl.Utf8,
    'uDFC18': pl.Utf8,
    'uDFC19': pl.Utf8,
    'uDFC20': pl.Utf8,
    'uDFC21': pl.Utf8,
    'uDFC22': pl.Utf8,
    'uDFC23': pl.Utf8,
    'uDFC24': pl.Utf8,
    'uDFC25': pl.Utf8,
    'uDFC26': pl.Utf8,
    'uDFC27': pl.Utf8,
    'uDFC28': pl.Utf8,
    'uDFC29': pl.Utf8,
    'uDFC30': pl.Utf8,
    'uDFC31': pl.Utf8,
    'uDFC32': pl.Utf8,
    'uDFC33': pl.Utf8,
    'uDFC34': pl.Utf8,
    'uDFC35': pl.Utf8,
    'uDFC36': pl.Utf8,
    'uDFC37': pl.Utf8,
    'uDFC38': pl.Utf8,
    'uDFC39': pl.Utf8,
    'uDFC40': pl.Utf8,
    'uDFD01': pl.Utf8,
    'uDFD02': pl.Utf8,
    'uDFD03': pl.Utf8,
    'uDFD04': pl.Utf8,
    'uDFD05': pl.Utf8,
    'uDFD06': pl.Utf8,
    'uDFD07': pl.Utf8,
    'uDFD08': pl.Utf8,
    'uDFD09': pl.Utf8,
    'uDFD10': pl.Utf8,
    'uDFD11': pl.Utf8,
    'uDFD12': pl.Utf8,
    'uDFD13': pl.Utf8,
    'uDFD14': pl.Utf8,
    'uDFD15': pl.Utf8,
    'uDFD16': pl.Utf8,
    'uDFD17': pl.Utf8,
    'uDFD18': pl.Utf8,
    'uDFD19': pl.Utf8,
    'uDFD20': pl.Utf8,
    'uDFN01': pl.Float64,
    'uDFN02': pl.Float64,
    'uDFN03': pl.Float64,
    'uDFN04': pl.Float64,
    'uDFN05': pl.Float64,
    'uDFN06': pl.Float64,
    'uDFN07': pl.Float64,
    'uDFN08': pl.Float64,
    'uDFN09': pl.Float64,
    'uDFN10': pl.Float64,
    'uDFN11': pl.Float64,
    'uDFN12': pl.Float64,
    'uDFN13': pl.Float64,
    'uDFN14': pl.Float64,
    'uDFN15': pl.Float64,
    'uDFN16': pl.Float64,
    'uDFN17': pl.Float64,
    'uDFN18': pl.Float64,
    'uDFN19': pl.Float64,
    'uDFN20': pl.Float64,
    'uDFN21': pl.Float64,
    'uDFN22': pl.Float64,
    'uDFN23': pl.Float64,
    'uDFN24': pl.Float64,
    'uDFN25': pl.Float64,
    'uDFN26': pl.Float64,
    'uDFN27': pl.Float64,
    'uDFN28': pl.Float64,
    'uDFN29': pl.Float64,
    'uDFN30': pl.Float64,
    'uDFN31': pl.Float64,
    'uDFN32': pl.Float64,
    'uDFN33': pl.Float64,
    'uDFN34': pl.Float64,
    'uDFN35': pl.Float64,
    'uDFN36': pl.Float64,
    'uDFN37': pl.Float64,
    'uDFN38': pl.Float64,
    'uDFN39': pl.Float64,
    'uDFN40': pl.Float64,
    'uniCardId': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateDatetime': pl.Utf8,
    'updateUser': pl.Int64,
    'updatedBy': pl.Utf8,
    'updatedByDefaultResort': pl.Utf8,
    'updatedDate': pl.Utf8,
    'updatedTime': pl.Utf8,
    'upsellCharge': pl.Float64,
    'videoCheckoutYN': pl.Utf8,
    'visaExpiryDate': pl.Utf8,
    'visaIssueDate': pl.Utf8,
    'visaNumber': pl.Utf8,
    'waitlistComment': pl.Utf8,
    'waitlistPhoneNumber': pl.Utf8,
    'waitlistPriority': pl.Utf8,
    'waitlistPriorityDescription': pl.Utf8,
    'waitlistReason': pl.Utf8,
    'waitlistReasonDescription': pl.Utf8,
    'waitlistpriorityid': pl.Utf8,
    'waitlistreasonid': pl.Utf8,
    'walkInYN': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Utf8,
}
```