# ARAccountsReceivable
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `aRAccountsReceivable`
> Detailed Accounts Receivable data including  Adjustments Payments Invoices and Posting for AR Accounts with linked reservation data.
  
**Return:** [`[ARAccountsReceivableType]`](#araccountsreceivabletype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ARAccountsReceivableQueryArgumentsType!`](#araccountsreceivablequeryargumentstype) |  |

## Object Types

### ARAccountsReceivableType

| Field | Type | Description |
| --- | --- | --- |
| accountDetails | [`ARAccountsReceivableAccountDetailsType`](#araccountsreceivableaccountdetailstype) | Account Details |
| aRTransactionAdjustmentDetailsDetails | [`ARAccountsReceivableARTransactionAdjustmentDetailsDetailsType`](#araccountsreceivableartransactionadjustmentdetailsdetailstype) | AR Transaction Adjustment Details |
| aRLedgerDetails | [`ARAccountsReceivableARLedgerDetailsType`](#araccountsreceivablearledgerdetailstype) | AR Ledger |
| invoiceHeaderDetails | [`ARAccountsReceivableInvoiceHeaderDetailsType`](#araccountsreceivableinvoiceheaderdetailstype) | Invoice Header Details |
| aRPostDetailsDetails | [`ARAccountsReceivableARPostDetailsDetailsType`](#araccountsreceivablearpostdetailsdetailstype) | AR Post Details |
| accountTypeDetails | [`ARAccountsReceivableAccountTypeDetailsType`](#araccountsreceivableaccounttypedetailstype) | Account Type Details |
| acctFlagReasonDetails | [`ARAccountsReceivableAcctFlagReasonDetailsType`](#araccountsreceivableacctflagreasondetailstype) | Acct Flag Reason Details |
| employeeDetails | [`ARAccountsReceivableEmployeeDetailsType`](#araccountsreceivableemployeedetailstype) | Employee Details |
| accountNoteDetails | [`ARAccountsReceivableAccountNoteDetailsType`](#araccountsreceivableaccountnotedetailstype) | Account Note Details |
| profileAllInformationDetails | [`ARAccountsReceivableProfileAllInformationDetailsType`](#araccountsreceivableprofileallinformationdetailstype) | Profile All Details |
| propertyPropertyDetails | [`ARAccountsReceivablePropertyPropertyDetailsType`](#araccountsreceivablepropertypropertydetailstype) | Resort Details |
| aRAccountsReceivableRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableAccountDetailsType

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

### ARAccountsReceivableARTransactionAdjustmentDetailsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| aSBFlag | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| accountTypeFlag | `String` | Account Type Flag |
| accountid | `Float` | Accountid |
| advGenerateAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| advanceGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
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
| calcPointsYn | `String` | Indicates if points are to be calculated. |
| cashierCredit | `Float` | Cashier Credit |
| cashierDebit | `Float` | Cashier Debit |
| cashierId | `Float` | Cashier ID |
| cashierOpeningBalance | `Float` | Cashier Opening Balance |
| ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| ccTrxFeeAmount | `Float` | Fee (surcharge) amount for a credit card transaction. |
| centralTransactionAmount | `Float` | Central Transaction Amount |
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
| creditCardId | `Float` | Credit Card ID |
| currency | `String` | Currency |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deferredTaxesYn | `String` | Indicates whether the generated tax is because of a deferred tax generation scenario |
| deferredYn | `String` | Deferred Y/N |
| deletedFlag | `String` | Deleted Flag |
| depLedgerCredit | `Float` | Dep Ledger Credit |
| depLedgerDebit | `Float` | Dep Ledger Debit |
| depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| depositTransactionId | `String` | Deposit Transaction ID |
| depositlinkfintransid | `Float` | Depositlinkfintransid |
| displayYn | `String` | Display Y/N |
| effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| euroExchangeRate | `Float` | Euro Exchange Rate |
| exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| exchangeDate | `Date` | Exchange Date |
| exchangeDifferenceYn | `String` | The flag indicates if it is an exchange rate difference posting when dual currency is on. |
| exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| expInvoiceType | `String` | Export Invoice Type |
| expOriginalInvoice | `String` | Export Original Invoice |
| extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| extTransactionId | `String` | Transaction ID from external system. |
| fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| fintransactionid | `Float` | Fintransactionid |
| fintransid | `Float` | Fintransid |
| fiscalBillNo | `String` | Fiscal Bill Number |
| fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| fixedChargesYn | `String` | Distinguish ordinary postings from Fixed charge postings. |
| folioNo | `Float` | Folio Number |
| folioType | `String` | Folio Type |
| folioView | `Float` | Folio View |
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
| guestAccountCredit | `Float` | Guest Account Credit |
| guestAccountDebit | `Float` | Debit amount on the guest account |
| holdYn | `String` | Indicates transaction is on hold. |
| hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| inhCredit | `Float` | In House Credit |
| inhDebit | `Float` | In House Debit |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| installments | `Float` | Installments |
| invoiceCloseDate | `Date` | Invoice Close Date |
| invoiceNo | `Float` | Invoice Number |
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
| profileid | `Float` | Profileid |
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
| remark | `String` | Remark |
| reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| reservationNameId | `Float` | Resv Name ID |
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
| transactionAmount | `Float` | Transaction Amount |
| transactionDate | `Date` | Transaction Date |
| transactionFromAcct | `Float` | Trns From Account |
| transactionNumber | `Float` | Transaction Number |
| transactionNumberToDepositPosting | `Float` | Transaction Number to Deposit Posting |
| transactionToAcct | `Float` | Trns To Account |
| transactionType | `String` | Specifies the Transaction Type. Possible values: [I]nitial Invoice [N]ormal Invoice [Z]ero Invoice. |
| transcodearrangementid | `Float` | Transcodearrangementid |
| transcodeid | `String` | Transcodeid |
| trnsActivityDate | `Date` | Transaction Activity Date |
| trxCode | `String` | Transaction Code |
| trxNumberAddedBy | `Float` | Transaction No Added By |
| trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| trxNumberAgainstPackage | `Float` | Transaction No Against Package |
| trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| trxServiceType | `String` | Transaction Service Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| vatOffsetYn | `String` | Vat Offset Y/N |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableARLedgerDetailsType

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

### ARAccountsReceivableInvoiceHeaderDetailsType

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

### ARAccountsReceivableARPostDetailsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| aRLedgerCredit | `Float` | AR Ledger Credit |
| aRLedgerDebit | `Float` | AR Ledger Debit |
| aROpen | `Float` | AR Open |
| aRTransferDate | `Date` | AR Transfer Date |
| aSBFlag | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| accountTypeFlag | `String` | Account Type Flag |
| accountid | `Float` | Accountid |
| adjustmentYN | `String` | Adjustment YN |
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
| arNumber | `Float` | AR Number |
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
| cAropen | `Float` | Central Aropen |
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
| centralARLedgerCredit | `Float` | Central AR Ledger Credit |
| centralARLedgerDebit | `Float` | Central AR Ledger Debit |
| centralAmount | `Float` | Central Amount |
| centralPaid | `Float` | Central Paid |
| centralPostedAmount | `Float` | Central Posted Amount |
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
| creditCardId | `Float` | Credit Card ID |
| currency | `String` | Currency |
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
| fTCompany | `String` | FT Company |
| fTFirstName | `String` | FT First Name |
| fTLastName | `String` | FT Last Name |
| fTNameType | `String` | FT Name Type |
| fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
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
| ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| genCashierId | `Float` | General Cashier Id. |
| gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| grossAmount | `Float` | Gross Amount |
| groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| guestAccountCredit | `Float` | Guest Account Credit |
| guestAccountDebit | `Float` | Debit amount on the guest account |
| guestname | `String` | Last Name of the guest. |
| holdYn | `String` | Indicates transaction is on hold. |
| hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| inhCredit | `Float` | In House Credit |
| inhDebit | `Float` | In House Debit |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| installments | `Float` | Installments |
| invoiceAge | `Float` | Invoice Age |
| invoiceCloseDate | `Date` | Invoice Close Date |
| invoiceNumber | `Float` | Invoice Number |
| invoiceStatus | `String` | Invoice Status |
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
| organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| originalReservationNameId | `Float` | Original Resv Name ID |
| originalRoom | `String` | Original Room |
| packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| packageCredit | `Float` | Credit amount on the guest package account. |
| packageDebit | `Float` | Debit amount on the guest package account |
| packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| paid | `Float` | Amount paid. |
| parallelCurrency | `String` | Cuurency code for parrallel currency. |
| parallelGrossAmount | `Float` | Parallel Gross Amount |
| parallelGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| parallelGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| parallelNetAmount | `Float` | Parallel Net Amount |
| passerByName | `String` | Passerby Name. |
| paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| paymentType | `String` | Payment Type |
| postDate | `Date` | Post Date |
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
| profileID | `Float` | Profile ID |
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
| recordType | `String` | Record Type |
| reference | `String` | Reference |
| repGuestname | `String` | Reporting Guestname |
| reportingTransactionCodeDesc | `String` | ReportingTransaction Code Desc |
| reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| reservationFirstName | `String` | Reservation First Name |
| reservationNameId | `Float` | Resv Name ID |
| reservationid | `Float` | Reservationid |
| resevationLastName | `String` | Resevation Last Name |
| revenueAmt | `Float` | Revenue Amount. |
| reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| revisionNo | `Float` | Revision Number |
| room | `String` | Room |
| roomClass | `String` | Room Class |
| roomNts | `Float` | Room Nts |
| roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| roomid | `String` | Roomid |
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
| transactionCodeDesc | `String` | Transaction Code desc |
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

### ARAccountsReceivableAccountTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountType | `String` | Account Type |
| accountTypeDescription | `String` | Account Type Description |
| accountTypeId | `Float` | Account Type ID |
| agingDelayDays | `Float` | Stores the aging delay in days which is used by the ar_unpaid report. |
| centralAccountType | `String` | Central Account Type |
| centralAccountTypeDescription | `String` | Central Account Type Description |
| centralCreditLimit | `Float` | Central Credit Limit |
| centralFinanceChargeAmount | `Float` | Central Finance Charge Amount |
| centralXchangeDate | `Date` | Central Exchange Date |
| centralXchangeRate | `Float` | Central Exchange Rate |
| chargesOlderThanNDays | `Float` | Min Number of days to consider older invoices for the account to post finance charges. |
| creditLimit | `Float` | Credit Limit |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| financeChargeAmount | `Float` | Amount or Fee to charge to the Account for overdue invoices. |
| financeChargePercentage | `Float` | Percentage to apply to the sum of older invoices. |
| inactiveflag | `String` | Inactive Flag |
| includeUnallocatedPaymentsYN | `String` | Used to include unallocated payments in the calculation of the finance charges. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalAccounttypeid | `Float` | Accounttypeid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| letterNameEndOfMonth | `String` | Letter name that is send every end of month when the Reminder Cycle is set to [E]nd of Month. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ownerCashbookReport | `String` | Name of the owner cashbook report to be given to auditors. |
| ownerStatementName | `String` | Name of the owner statement report that needs to be send to the owner of the unit. |
| ownerSummary | `String` | Name of the owner summary report that needs to be send to the owner of the unit. |
| postOnDay | `Float` | Day of the month when Night Audit will check for older invoices to post finance charges onto a new invoice. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printInvoiceDetailsYn | `String` | Print Invoice Details on Statements Y/N. |
| printInvoicesWithDetailsYN | `String` | Print Invoices With Details YN |
| printInvoicesWithoutDetailsYN | `String` | Print Invoices Without Details YN |
| printSeperateFoliosYN | `String` | Print Seperate Folios YN |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reminderCycle | `String` | Indicates if the Reminder Cycle generation is based on calendar [D]ays or [E]nd of Month. |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| statementMode | `String` | Indicates if the Account Type will utilize the '(B)alance Brought Forward? single line or '(I)ndividual Open Items?  when generating statements. |
| statementName | `String` | Name of the statement that needs to be sent to the account. |
| statementNameDescription | `String` | Statement Name Description |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableAcctFlagReasonDetailsType

| Field | Type | Description |
| --- | --- | --- |
| acctflagreasonid | `String` | Acctflagreasonid |
| centralFlaggedReasonCode | `String` | Central Flagged Reason Code |
| centralRestrictedReasonDescription | `String` | Central Restricted Reason Description |
| centralSequence | `Float` | Central Sequence |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| flaggedReasonCode | `String` | Flagged Reason Code |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
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
| restrictedReasonDescription | `String` | Restricted Reason Description |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableEmployeeDetailsType

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

### ARAccountsReceivableAccountNoteDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountCode | `Float` | Account Code |
| accountid | `Float` | Accountid |
| accountnoteid | `Float` | Accountnoteid |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalflag | `String` | Internalflag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| noteCode | `String` | Note Code |
| noteDetails | `String` | Note Details |
| noteId | `Float` | Note ID |
| noteTitle | `String` | Note Title |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableProfileAllInformationDetailsType

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

### ARAccountsReceivablePropertyPropertyDetailsType

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

### ARAccountsReceivableQueryArgumentsType

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| accountDetailsAccountCode | `FloatInput` | Account Code |  |
| accountDetailsAccountNo | `StringInput` | Account Number |  |
| accountDetailsAccountSname | `StringInput` | Name on the account in upper case. |  |
| accountDetailsAccTypeFlag | `StringInput` | Account Type Flag |  |
| accountDetailsAccountTypeId | `FloatInput` | Account Type ID |  |
| accountDetailsAccountid | `FloatInput` | Accountid |  |
| accountDetailsAddressId | `FloatInput` | Address ID |  |
| accountDetailsBeginDate | `DateInput` | Begin Date |  |
| accountDetailsCXchangeDate | `DateInput` | Central Exchange Date |  |
| accountDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| accountDetailsEmailId | `FloatInput` | Email ID |  |
| accountDetailsEndDate | `DateInput` | End Date |  |
| accountDetailsFaxId | `FloatInput` | Fax ID |  |
| accountDetailsAccounttypeid | `FloatInput` | Accounttypeid |  |
| accountDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| accountDetailsLastActivityDate | `DateTimeInput` | Date of Last Activity on the AR Account in regards to: transfers between accounts payments applied (not unallocated) un-applied reversed and invoice compressions un-compressions on the account. |  |
| accountDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| accountDetailsNameId | `FloatInput` | Name ID |  |
| accountDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| accountDetailsPhoneId | `FloatInput` | Phone ID |  |
| accountDetailsProfileid | `FloatInput` | Profileid |  |
| accountDetailsResort | `StringInput!` | Code to uniquely identify the Property | `mandatoryInput` |
| accountDetailsUpperCaseName | `StringInput` | Upper Case Name |  |
| artranadjdetailsDetailsAccountid | `FloatInput` | Accountid |  |
| artranadjdetailsDetailsArLedCredit | `FloatInput` | AR Led Credit |  |
| artranadjdetailsDetailsArLedDebit | `FloatInput` | AR Led Debit |  |
| artranadjdetailsDetailsArState | `StringInput` | AR State |  |
| artranadjdetailsDetailsAuthorizerId | `FloatInput` | Authorizer ID |  |
| artranadjdetailsDetailsBillNo | `FloatInput` | Bill Number |  |
| artranadjdetailsDetailsBonusCheckId | `FloatInput` | Bonus Check ID |  |
| artranadjdetailsDetailsBusinessDate | `DateInput` | Business Date |  |
| artranadjdetailsDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| artranadjdetailsDetailsCashierId | `FloatInput` | Cashier ID |  |
| artranadjdetailsDetailsChequeNumber | `StringInput` | Cheque Number |  |
| artranadjdetailsDetailsClosureNo | `FloatInput` | Closure Number |  |
| artranadjdetailsDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |  |
| artranadjdetailsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| artranadjdetailsDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |  |
| artranadjdetailsDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |  |
| artranadjdetailsDetailsFintransactionid | `FloatInput` | Fintransactionid |  |
| artranadjdetailsDetailsFintransid | `FloatInput` | Fintransid |  |
| artranadjdetailsDetailsFolioNo | `FloatInput` | Folio Number |  |
| artranadjdetailsDetailsFolioView | `FloatInput` | Folio View |  |
| artranadjdetailsDetailsFromResvId | `FloatInput` | From Resv ID |  |
| artranadjdetailsDetailsGuestAccountCredit | `FloatInput` | Guest Account Credit |  |
| artranadjdetailsDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |  |
| artranadjdetailsDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |  |
| artranadjdetailsDetailsInsertDate | `DateTimeInput` | Insert Date |  |
| artranadjdetailsDetailsInvoiceNo | `FloatInput` | Invoice Number |  |
| artranadjdetailsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| artranadjdetailsDetailsLinkTrxNo | `FloatInput` | Link Transaction No |  |
| artranadjdetailsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| artranadjdetailsDetailsNameId | `FloatInput` | Name ID |  |
| artranadjdetailsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| artranadjdetailsDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |  |
| artranadjdetailsDetailsOriginalRoom | `StringInput` | Original Room |  |
| artranadjdetailsDetailsPostitNo | `FloatInput` | Postit Number |  |
| artranadjdetailsDetailsProduct | `StringInput` | Product |  |
| artranadjdetailsDetailsProfileid | `FloatInput` | Profileid |  |
| artranadjdetailsDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| artranadjdetailsDetailsRateCode | `StringInput` | Rate Code |  |
| artranadjdetailsDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |  |
| artranadjdetailsDetailsResvNameId | `FloatInput` | Resv Name ID |  |
| artranadjdetailsDetailsRoom | `StringInput` | Room |  |
| artranadjdetailsDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |  |
| artranadjdetailsDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |  |
| artranadjdetailsDetailsTaxElements | `StringInput` | Tax Elements |  |
| artranadjdetailsDetailsTcGroup | `StringInput` | Transaction Code Group |  |
| artranadjdetailsDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |  |
| artranadjdetailsDetailsTranActionId | `FloatInput` | Tran Action ID |  |
| artranadjdetailsDetailsTrxDate | `DateInput` | Transaction Date |  |
| artranadjdetailsDetailsTrxNo | `FloatInput` | Transaction Number |  |
| artranadjdetailsDetailsTrxNoHeader | `FloatInput` | Transaction Number to Deposit Posting |  |
| artranadjdetailsDetailsTranscodeid | `StringInput` | Transcodeid |  |
| artranadjdetailsDetailsTrxCode | `StringInput` | Transaction Code |  |
| artranadjdetailsDetailsTrxNoAddedBy | `FloatInput` | Transaction No Added By |  |
| artranadjdetailsDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |  |
| artranadjdetailsDetailsTrxNoAgainstPackage | `FloatInput` | Transaction No Against Package |  |
| arledgerDetailsArLedDebit | `FloatInput` | AR Led Debit |  |
| arledgerDetailsArNumber | `FloatInput` | AR Number |  |
| arledgerDetailsArState | `StringInput` | AR State |  |
| arledgerDetailsAuthorizerId | `FloatInput` | Authorizer ID |  |
| arledgerDetailsBillNo | `FloatInput` | Bill Number |  |
| arledgerDetailsBonusCheckId | `FloatInput` | Bonus Check ID |  |
| arledgerDetailsBusinessDate | `DateInput` | Business Date |  |
| arledgerDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| arledgerDetailsCashierId | `FloatInput` | Cashier ID |  |
| arledgerDetailsChequeNumber | `StringInput` | Cheque Number |  |
| arledgerDetailsClosureNo | `FloatInput` | Closure Number |  |
| arledgerDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |  |
| arledgerDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| arledgerDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |  |
| arledgerDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |  |
| arledgerDetailsFintransid | `FloatInput` | Fintransid |  |
| arledgerDetailsFolioNo | `FloatInput` | Folio Number |  |
| arledgerDetailsFolioView | `FloatInput` | Folio View |  |
| arledgerDetailsFromResvId | `FloatInput` | From Resv ID |  |
| arledgerDetailsGuestAccountCredit | `FloatInput` | Guest Account Credit |  |
| arledgerDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |  |
| arledgerDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |  |
| arledgerDetailsInsertDate | `DateTimeInput` | Insert Date |  |
| arledgerDetailsCashierid | `FloatInput` | Cashierid |  |
| arledgerDetailsInvoiceCloseDate | `DateInput` | Invoice Close Date |  |
| arledgerDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| arledgerDetailsLinkTrxNo | `FloatInput` | Link Transaction No |  |
| arledgerDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| arledgerDetailsNameId | `FloatInput` | Name ID |  |
| arledgerDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| arledgerDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |  |
| arledgerDetailsOriginalRoom | `StringInput` | Original Room |  |
| arledgerDetailsPostitNo | `FloatInput` | Postit Number |  |
| arledgerDetailsProduct | `StringInput` | Product |  |
| arledgerDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| arledgerDetailsRateCode | `StringInput` | Rate Code |  |
| arledgerDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |  |
| arledgerDetailsResvNameId | `FloatInput` | Resv Name ID |  |
| arledgerDetailsRoom | `StringInput` | Room |  |
| arledgerDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |  |
| arledgerDetailsTaxElements | `StringInput` | Tax Elements |  |
| arledgerDetailsTcGroup | `StringInput` | Transaction Code Group |  |
| arledgerDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |  |
| arledgerDetailsTranActionId | `FloatInput` | Tran Action ID |  |
| arledgerDetailsTrxDate | `DateInput` | Transaction Date |  |
| arledgerDetailsTrxNo | `FloatInput` | Transaction Number |  |
| arledgerDetailsTrxCode | `StringInput` | Transaction Code |  |
| arledgerDetailsTrxNoAddedBy | `FloatInput` | Transaction No Added By |  |
| arledgerDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |  |
| arledgerDetailsTrxNoAgainstPackage | `FloatInput` | Transaction No Against Package |  |
| arledgerDetailsTrxNoHeader | `FloatInput` | Transaction No Header |  |
| invoiceheaderDetailsArTransferDate | `DateInput` | AR Transfer Date |  |
| invoiceheaderDetailsAccountCode | `FloatInput` | Account Code |  |
| invoiceheaderDetailsAccountid | `FloatInput` | Accountid |  |
| invoiceheaderDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |  |
| invoiceheaderDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| invoiceheaderDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| invoiceheaderDetailsFintransid | `FloatInput` | Fintransid |  |
| invoiceheaderDetailsFolioNo | `FloatInput` | Folio Number |  |
| invoiceheaderDetailsFolioid | `FloatInput` | Folioid |  |
| invoiceheaderDetailsInvoiceNo | `FloatInput` | Invoice Number |  |
| invoiceheaderDetailsInvStatus | `StringInput` | Status of the invoice (H)old (O)pen or (C)losed. |  |
| invoiceheaderDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| invoiceheaderDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| invoiceheaderDetailsMasterInvoiceNo | `FloatInput` | Compressed Invoice No for which multiple invoices have been compressed to. |  |
| invoiceheaderDetailsNameId | `FloatInput` | Name ID |  |
| invoiceheaderDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| invoiceheaderDetailsBusinessDate | `DateInput` | Post Date |  |
| invoiceheaderDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| invoiceheaderDetailsPurgeYn | `StringInput` | Indicator whether to purge the Account. |  |
| invoiceheaderDetailsResvNameId | `FloatInput` | Resv Name ID |  |
| invoiceheaderDetailsTrxDate | `DateInput` | Transaction Date |  |
| invoiceheaderDetailsTranscodeid | `StringInput` | Transcodeid |  |
| invoiceheaderDetailsTrxCode | `StringInput` | Transaction Code |  |
| invoiceheaderDetailsTrxNo | `FloatInput` | Transaction No |  |
| arpostdetailsDetailsAccountid | `FloatInput` | Accountid |  |
| arpostdetailsDetailsArNumber | `FloatInput` | AR Number |  |
| arpostdetailsDetailsArticleId | `FloatInput` | Article ID |  |
| arpostdetailsDetailsAuthorizerId | `FloatInput` | Authorizer ID |  |
| arpostdetailsDetailsBillNo | `FloatInput` | Bill Number |  |
| arpostdetailsDetailsBonusCheckId | `FloatInput` | Bonus Check ID |  |
| arpostdetailsDetailsBusinessDate | `DateInput` | Business Date |  |
| arpostdetailsDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| arpostdetailsDetailsCashierId | `FloatInput` | Cashier ID |  |
| arpostdetailsDetailsChequeNumber | `StringInput` | Cheque Number |  |
| arpostdetailsDetailsClosureNo | `FloatInput` | Closure Number |  |
| arpostdetailsDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |  |
| arpostdetailsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| arpostdetailsDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |  |
| arpostdetailsDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |  |
| arpostdetailsDetailsFintransid | `FloatInput` | Fintransid |  |
| arpostdetailsDetailsFolioNo | `FloatInput` | Folio Number |  |
| arpostdetailsDetailsFolioView | `FloatInput` | Folio View |  |
| arpostdetailsDetailsFolioid | `FloatInput` | Folioid |  |
| arpostdetailsDetailsFromResvId | `FloatInput` | From Resv ID |  |
| arpostdetailsDetailsGuestAccountCredit | `FloatInput` | Guest Account Credit |  |
| arpostdetailsDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |  |
| arpostdetailsDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |  |
| arpostdetailsDetailsInsertDate | `DateTimeInput` | Insert Date |  |
| arpostdetailsDetailsInvoiceNo | `FloatInput` | Invoice Number |  |
| arpostdetailsDetailsArState | `StringInput` | Invoice Status |  |
| arpostdetailsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| arpostdetailsDetailsLinkTrxNo | `FloatInput` | Link Transaction No |  |
| arpostdetailsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| arpostdetailsDetailsNameId | `FloatInput` | Name ID |  |
| arpostdetailsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| arpostdetailsDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |  |
| arpostdetailsDetailsOriginalRoom | `StringInput` | Original Room |  |
| arpostdetailsDetailsTrxDate | `DateInput` | Post Date |  |
| arpostdetailsDetailsPostitNo | `FloatInput` | Postit Number |  |
| arpostdetailsDetailsProduct | `StringInput` | Product |  |
| arpostdetailsDetailsProfileid | `FloatInput` | Profile ID |  |
| arpostdetailsDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| arpostdetailsDetailsRateCode | `StringInput` | Rate Code |  |
| arpostdetailsDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |  |
| arpostdetailsDetailsResvNameId | `FloatInput` | Resv Name ID |  |
| arpostdetailsDetailsReservationid | `FloatInput` | Reservationid |  |
| arpostdetailsDetailsRoom | `StringInput` | Room |  |
| arpostdetailsDetailsRoomid | `StringInput` | Roomid |  |
| arpostdetailsDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |  |
| arpostdetailsDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |  |
| arpostdetailsDetailsTaxElements | `StringInput` | Tax Elements |  |
| arpostdetailsDetailsTcGroup | `StringInput` | Transaction Code Group |  |
| arpostdetailsDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |  |
| arpostdetailsDetailsTranActionId | `FloatInput` | Tran Action ID |  |
| arpostdetailsDetailsTrxNo | `FloatInput` | Transaction Number |  |
| arpostdetailsDetailsTranscodeid | `StringInput` | Transcodeid |  |
| arpostdetailsDetailsTrxCode | `StringInput` | Transaction Code |  |
| arpostdetailsDetailsTrxNoAddedBy | `FloatInput` | Transaction No Added By |  |
| arpostdetailsDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |  |
| arpostdetailsDetailsTrxNoAgainstPackage | `FloatInput` | Transaction No Against Package |  |
| arpostdetailsDetailsTrxNoHeader | `FloatInput` | Transaction No Header |  |
| accounttypeDetailsAccountType | `StringInput` | Account Type |  |
| accounttypeDetailsCXchangeDate | `DateInput` | Central Exchange Date |  |
| accounttypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| accounttypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| accounttypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| accounttypeDetailsResort | `StringInput` | Property |  |
| acctflagreasonDetailsAcctflagreasonid | `StringInput` | Acctflagreasonid |  |
| acctflagreasonDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| acctflagreasonDetailsReasonCode | `StringInput` | Flagged Reason Code |  |
| acctflagreasonDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| acctflagreasonDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| acctflagreasonDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| acctflagreasonDetailsResort | `StringInput` | Property |  |
| employeeDetailsAppUser | `StringInput` | Agent |  |
| employeeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| employeeDetailsDefCashierId | `FloatInput` | Cashier ID for the User |  |
| employeeDetailsDefaultResort | `StringInput` | Stores resort name to which user will log in every time |  |
| employeeDetailsEmployeeid | `FloatInput` | Employeeid |  |
| employeeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| employeeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |  |
| employeeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| employeeDetailsPersonNameId | `FloatInput` | Foreign key to NAME table that links this USER to an Employee |  |
| employeeDetailsSrepCode | `StringInput` | Primary Rooms Owner Code |  |
| employeeDetailsAppUserId | `FloatInput` | User ID |  |
| accountnoteDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| accountnoteDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| accountnoteDetailsNoteId | `FloatInput` | Note ID |  |
| accountnoteDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| accountnoteDetailsResort | `StringInput` | Code to uniquely identify the Property |  |
| profileallDetailsNameId | `FloatInput` | The primary key for this table. |  |
| profileallDetailsActiveYn | `StringInput` | Profile is active or not. |  |
| profileallDetailsCrsNameid | `FloatInput` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |  |
| profileallDetailsChainCode | `StringInput` | Chain Code |  |
| profileallDetailsNameCode | `StringInput` | The unique key of this name stores IATA# Company # etc. |  |
| profileallDetailsCompanyGroupId | `StringInput` | The company group or company group user ID in hierarchical format |  |
| profileallDetailsContactFlag | `StringInput` | Used in S&C Module. |  |
| profileallDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| profileallDetailsDirectBillBatchType | `StringInput` | Direct Bill Batch Type |  |
| profileallDetailsLast | `StringInput` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |  |
| profileallDetailsHistoryYn | `StringInput` | Keep guest in history Y/N |  |
| profileallDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |  |
| profileallDetailsIndexName | `StringInput` | Index Name |  |
| profileallDetailsOrganizationId | `FloatInput` | Organization ID |  |
| profileallDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| profileallDetailsNameType | `StringInput` | The type of Profile. |  |
| profileallDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| profileallDetailsProfileId | `FloatInput` | The primary key for this table. |  |
| profileallDetailsProfileType | `StringInput` | The type of Profile. |  |
| profileallDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |  |
| profileallDetailsCompany | `StringInput` | This column store the Name of the Company Profiles. |  |
| profileallDetailsSname | `StringInput` | The Uppercase value of Last or Company. |  |
| profileallDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |  |
| profileallDetailsSfirst | `StringInput` | Uppercase value of First Name. |  |
| profileallDetailsSrepCode | `StringInput` | Used in QMS Module |  |
| profileallDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |  |
| profileallDetailsUpdateDate | `DateTimeInput` | The date the record was modified |  |
| resortDetailsResort | `StringInput` | The property that the record belongs to |  |
| resortDetailsArAcctNoFormat | `StringInput` | Number format of AR account no. |  |
| resortDetailsArAcctNoMandYn | `StringInput` | Specifies if the AR acct No is mandatory(Y/N) |  |
| resortDetailsArAgent | `StringInput` | Default Account Type for an Agent for the Property |  |
| resortDetailsArBalTrxCode | `StringInput` | Internal |  |
| resortDetailsArCompany | `StringInput` | Default Account Type for a Company for the Property |  |
| resortDetailsArCreditTrxCode | `StringInput` | Internal |  |
| resortDetailsArGroups | `StringInput` | Default Account Type for a Group for the Property |  |
| resortDetailsArIndividuals | `StringInput` | Default Account Type for Individual for the Property |  |
| resortDetailsArSettleCode | `StringInput` | Internal |  |
| resortDetailsArTypewriter | `StringInput` | Internal |  |
| resortDetailsAccessCode | `StringInput` | Access Code |  |
| resortDetailsQtyHandicappedRooms | `FloatInput` | Number of handicapped rooms. |  |
| resortDetailsAgingLevel1 | `FloatInput` | Aging bucket 1 |  |
| resortDetailsAgingLevel2 | `FloatInput` | Aging bucket 2 |  |
| resortDetailsAgingLevel3 | `FloatInput` | Aging bucket 3 |  |
| resortDetailsAgingLevel4 | `FloatInput` | Aging bucket 4 |  |
| resortDetailsAgingLevel5 | `FloatInput` | Aging bucket 3 |  |
| resortDetailsAirport | `StringInput` | The Airport Code for the airport near the property |  |
| resortDetailsAirportDistance | `StringInput` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |  |
| resortDetailsAirportTime | `StringInput` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |  |
| resortDetailsAllowLoginYn | `StringInput` | Allow loggin in to this resort(Y/N) |  |
| resortDetailsAllowancePeriodAdj | `StringInput` | Period for the allowance |  |
| resortDetailsAwardsTimeout | `FloatInput` | Internal |  |
| resortDetailsBrArea | `StringInput` | Ball Room Area |  |
| resortDetailsBrSeats | `FloatInput` | No of Ballroom Seats |  |
| resortDetailsBaseLanguage | `StringInput` | The base language of the Hotel |  |
| resortDetailsBlock | `StringInput` | It contains the reservation type to be used when making group block |  |
| resortDetailsBrandCode | `StringInput` | Brand Code of the property. |  |
| resortDetailsBudgetMonth | `FloatInput` | Financial Year of the Property |  |
| resortDetailsBeginDate | `DateInput` | The date this resort becomes valid for use by the system |  |
| resortDetailsBusinessId | `StringInput` | Value for the parameter. |  |
| resortDetailsBusinessRegCode | `StringInput` | Value for the parameter. |  |
| resortDetailsCroCode | `StringInput` | Code for the CRO |  |
| resortDetailsCashShiftDrop | `StringInput` | Internal |  |
| resortDetailsCateringCurrencyCode | `StringInput` | Catering Currency Code used when Catering Currency differs from base currency. |  |
| resortDetailsCateringCurrencyFormat | `StringInput` | Catering currency format. |  |
| resortDetailsCXchangeDate | `DateInput` | Central  Exchange Date |  |
| resortDetailsCXchangeRate | `FloatInput` | Central  Exchange Rate |  |
| resortDetailsCCreditLimit | `FloatInput` | Central Credit Limit |  |
| resortDetailsCentralCurrencyCode | `StringInput` | Central Currency Code |  |
| resortDetailsCentralCurrencyDesc | `StringInput` | Central Currency Description |  |
| resortDetailsCDblRate2 | `FloatInput` | Central Double Rate2 |  |
| resortDetailsCDblRate1 | `FloatInput` | Central Double Rate1 |  |
| resortDetailsRepPasserbyMarket | `StringInput` | Central Passerby Market |  |
| resortDetailsRepPasserbySource | `StringInput` | Central Passerby Source |  |
| resortDetailsRepResortType | `StringInput` | Central Property Type |  |
| resortDetailsCSglRate1 | `FloatInput` | Central Sgl Rate1 |  |
| resortDetailsCSglRate2 | `FloatInput` | Central Sgl Rate 2 |  |
| resortDetailsRepState | `StringInput` | Central State |  |
| resortDetailsRepStateDesc | `StringInput` | Central State Description |  |
| resortDetailsCSuiRate1 | `FloatInput` | Central Sui Rate1 |  |
| resortDetailsCSuiRate2 | `FloatInput` | Central Sui Rate 2 |  |
| resortDetailsCTplRate1 | `FloatInput` | Central Tpl Rate1 |  |
| resortDetailsCTplRate2 | `FloatInput` | Central Tpl Rate 2 |  |
| resortDetailsCWarningAmount | `FloatInput` | Central Warning Amount |  |
| resortDetailsChainCode | `StringInput` | Chain Code for the chain to which the property belongs |  |
| resortDetailsChainDescription | `StringInput` | The description of this chain. |  |
| resortDetailsChainMode | `StringInput` | Chain Mode |  |
| resortDetailsCheckExgPaidout | `StringInput` | Internal |  |
| resortDetailsCheckOutTime | `DateTimeInput` | The Hotel official check out time |  |
| resortDetailsCheckShiftDrop | `StringInput` | Internal |  |
| resortDetailsCheckTrxcode | `StringInput` | Internal |  |
| resortDetailsCheckInTime | `DateTimeInput` | The Hotel official check intime |  |
| resortDetailsCity | `StringInput` | The physical city in which this property resides. |  |
| resortDetailsCityDescription | `StringInput` | City Description |  |
| resortDetailsComAddress | `StringInput` | Internal |  |
| resortDetailsComMethod | `StringInput` | Internal |  |
| resortDetailsComNameXrefId | `FloatInput` | Internal |  |
| resortDetailsCompanyAddressType | `StringInput` | Internal |  |
| resortDetailsCompanyPhoneType | `StringInput` | Internal |  |
| resortDetailsConfigurationMode | `StringInput` | Internal |  |
| resortDetailsConfirmRegcardPrinter | `StringInput` | Internal |  |
| resortDetailsQtyConnectingRooms | `FloatInput` | Number of connecting rooms. |  |
| resortDetailsAllContacts | `StringInput` | The unique name of application user |  |
| resortDetailsCopies | `FloatInput` | Number of copies to be printed |  |
| resortDetailsCountryName | `StringInput` | Country name. |  |
| resortDetailsCountryCode | `StringInput` | The name of the country in which this property resides. |  |
| resortDetailsCountryMode | `StringInput` | Value for the parameter. |  |
| resortDetailsCreditLimit | `FloatInput` | The default credit limit for guests. |  |
| resortDetailsCurrencyCode | `StringInput` | Currency Code. |  |
| resortDetailsCurrencySymbol | `StringInput` | Currency Symbol like $ or EURO symbol |  |
| resortDetailsCurrencyName | `StringInput` | A description of this currency. |  |
| resortDetailsLocalCurrencyFormat | `StringInput` | Format for the local currency. |  |
| resortDetailsCurtainColor | `StringInput` | Color that of the background |  |
| resortDetailsDsi | `FloatInput` | DSI |  |
| resortDetailsDateForAging | `StringInput` | Date the aging should begin |  |
| resortDetailsDateSeparator | `StringInput` | Type of separator to distinguish between DD MM and YYYY |  |
| resortDetailsDecimalPlaces | `FloatInput` | Number of places for the default currency |  |
| resortDetailsDecimalSeparator | `StringInput` | Type of decimal separator |  |
| resortDetailsCurrencyDecimals | `FloatInput` | Number of decimals to designate currency |  |
| resortDetailsDefaultFolioStyle | `FloatInput` | Folio style to be used for all guests |  |
| resortDetailsDefaultGuestAddress | `StringInput` | Default guest address format. |  |
| resortDetailsDefaultMembershipType | `StringInput` | Future use |  |
| resortDetailsDefaultPostingRoom | `StringInput` | Future use |  |
| resortDetailsDefaultPropertyAddress | `StringInput` | Default property address format. |  |
| resortDetailsDefaultRateCode | `StringInput` | Future use |  |
| resortDetailsDefaultRatecodePcr | `StringInput` | Rate code used to default a PCR rate code used in FIT Contracts. |  |
| resortDetailsDefaultRatecodeRack | `StringInput` | Rate code used to default a RACK rate code used for FIT Contracts. |  |
| resortDetailsDefaultRegistrationCard | `StringInput` | Default registration card for the property. |  |
| resortDetailsDefaultReservationType | `StringInput` | The Default reservation type for this property |  |
| resortDetailsDeletedFlag | `StringInput` | Deleted Flag |  |
| resortDetailsDepositLedTrxCode | `StringInput` | Future use |  |
| resortDetailsDestinationId | `StringInput` | Destination ID |  |
| resortDetailsDfltPkgTranCode | `StringInput` | Future use |  |
| resortDetailsDfltTranCodeRateCode | `StringInput` | Future use |  |
| resortDetailsDirections | `StringInput` | Internal |  |
| resortDetailsDirsales | `StringInput` | Future use |  |
| resortDetailsDisableLoginYn | `StringInput` | LOGIN into the application is disabled. |  |
| resortDetailsQtyDoubleRooms | `FloatInput` | Number of double rooms. |  |
| resortDetailsDownloadRestYn | `StringInput` | Download Rest YN |  |
| resortDetailsDutyManagerPager | `StringInput` | Pager number for the Manager on duty for the property. |  |
| resortDetailsEmail | `StringInput` | Email id for the property. |  |
| resortDetailsEndDate | `DateInput` | Future use. |  |
| resortDetailsExchangePostingType | `StringInput` | Default Exchange posting status for the property |  |
| resortDetailsFloorNumExecutiveFloor | `StringInput` | Floor number of executive floor. |  |
| resortDetailsExpHotelCode | `StringInput` | Hotel code used for third party exports |  |
| resortDetailsExtExpFileLocation | `StringInput` | Future use |  |
| resortDetailsExtPropertyCode | `StringInput` | Future use |  |
| resortDetailsExternalScYn | `StringInput` | Indicates that the property uses an external SC system. |  |
| resortDetailsQtyFamilyRooms | `FloatInput` | Number of family rooms. |  |
| resortDetailsFaxNoFormat | `StringInput` | Fax number formats. |  |
| resortDetailsFax | `StringInput` | The fax phone number |  |
| resortDetailsFiscalEndDate | `DateInput` | Future use |  |
| resortDetailsFiscalPeriodType | `StringInput` | Future use |  |
| resortDetailsFiscalStartDate | `DateInput` | Future use |  |
| resortDetailsFiscalStartMonth | `FloatInput` | Fiscal Year Begin Month |  |
| resortDetailsFiscalStartYear | `FloatInput` | Fiscal Year Begin Year |  |
| resortDetailsFlags | `StringInput` | Screen Painter flags to indicate whether an item is changable/ movable etc. |  |
| resortDetailsFlowCode | `StringInput` | Future use |  |
| resortDetailsFnsTier | `StringInput` | Property Free Nights Stay Tier. |  |
| resortDetailsFolioLanguage1 | `StringInput` | Other languages |  |
| resortDetailsFolioLanguage2 | `StringInput` | Other languages |  |
| resortDetailsFolioLanguage3 | `StringInput` | Other languages |  |
| resortDetailsFolioLanguage4 | `StringInput` | Other languages |  |
| resortDetailsGenmgr | `StringInput` | Future use |  |
| resortDetailsGroupRoomWarning | `FloatInput` | To define an upper limit to the number of rooms for Group |  |
| resortDetailsGuestLookupTimeout | `FloatInput` | Future use |  |
| resortDetailsQtyGuestElevators | `FloatInput` | Number of guest elevators. |  |
| resortDetailsQtyGuestRoomFloors | `FloatInput` | Total of guest rooms floors. |  |
| resortDetailsHotelCode | `StringInput` | Future use |  |
| resortDetailsHotelFc | `StringInput` | Future use |  |
| resortDetailsHotelId | `StringInput` | Hotel id |  |
| resortDetailsHotelType | `StringInput` | Future use |  |
| resortDetailsImgDirectionId | `FloatInput` | Future use |  |
| resortDetailsImgHotelId | `FloatInput` | Future use |  |
| resortDetailsImgMapId | `FloatInput` | Future use |  |
| resortDetailsInactiveDaysForGuestProfil | `FloatInput` | Future use |  |
| resortDetailsInactiveFlag | `StringInput` | Inactive Flag |  |
| resortDetailsIndividualAddressType | `StringInput` | Future use |  |
| resortDetailsIndividualPhoneType | `StringInput` | Future use |  |
| resortDetailsIndividualRoomWarning | `FloatInput` | To define an upper limit to the number of rooms for group |  |
| resortDetailsInsertDate | `DateTimeInput` | The date the record was created |  |
| resortDetailsInsertUser | `FloatInput` | The user that created the record |  |
| resortDetailsIntTaxIncludedYn | `StringInput` | Int Tax Included YN |  |
| resortDetailsInventoryYn | `StringInput` | Future use |  |
| resortDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| resortDetailsKeepAvailability | `FloatInput` | To calculate the entire availability of the Hotel for future reservations |  |
| resortDetailsLatitude | `FloatInput` | Latitude of the property in decimal |  |
| resortDetailsLeadsend | `StringInput` | Future use |  |
| resortDetailsLegalOwner | `StringInput` | The owner who owns this property |  |
| resortDetailsLocationId | `StringInput` | The property that the record belongs to |  |
| resortDetailsLongDateFormat | `StringInput` | Long date format for the property. |  |
| resortDetailsLongStayControl | `FloatInput` | The default length of stay |  |
| resortDetailsLongitude | `FloatInput` | Longitude of the property in decimal |  |
| resortDetailsMaxAdultsFamilyRoom | `FloatInput` | Maximum adults in family rooms. |  |
| resortDetailsMaxChildrenFamilyRoom | `FloatInput` | Maximum children in family rooms. |  |
| resortDetailsMaxOccupancy | `FloatInput` | Future use |  |
| resortDetailsMaxcreditdays | `FloatInput` | Maximum number of days that are allowed to credit a bill. (Country requirements.) Used in CASHIERING MODULE. |  |
| resortDetailsMbsSupportedYn | `StringInput` | Indicates whether the property supports MBS. Used in some file exports. |  |
| resortDetailsMeetRooms | `FloatInput` | Future use |  |
| resortDetailsMeetSeats | `FloatInput` | Future use |  |
| resortDetailsMeetSpace | `FloatInput` | Future use |  |
| resortDetailsMeetingFc | `StringInput` | Future use |  |
| resortDetailsMinDaysBet2ReminderLetter | `FloatInput` | Minimum days for reminder letter. |  |
| resortDetailsNameIdLink | `FloatInput` | Internal |  |
| resortDetailsNightAuditCashierId | `StringInput` | Future use |  |
| resortDetailsQtyNonSmokingRooms | `FloatInput` | Number of non smoking rooms. |  |
| resortDetailsNotes | `StringInput` | Notes for the property |  |
| resortDetailsNumberBeds | `FloatInput` | Total number of beds in this property |  |
| resortDetailsNumberFloors | `FloatInput` | Total number of floors in this property |  |
| resortDetailsNumberRooms | `FloatInput` | Number of Rooms |  |
| resortDetailsOpusCurrencyCode | `StringInput` | Future use |  |
| resortDetailsOrganizationId | `FloatInput` | Organization ID |  |
| resortDetailsOrganizationid | `FloatInput` | Organization Internal ID |  |
| resortDetailsOwnership | `StringInput` | Future use |  |
| resortDetailsPackageLoss | `StringInput` | Package Loss code for a particular package |  |
| resortDetailsPackageProfit | `StringInput` | Package Profit code for a particular Package |  |
| resortDetailsParentOrgCode | `StringInput` | Parent Org Code |  |
| resortDetailsPasserbyMarket | `StringInput` | Market code |  |
| resortDetailsPasserbySource | `StringInput` | Source code |  |
| resortDetailsPath | `StringInput` | Path |  |
| resortDetailsPaymentDate | `DateTimeInput` | Minimim Payment Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |  |
| resortDetailsPerReservationRoomLimit | `FloatInput` | Future use |  |
| resortDetailsTelephone | `StringInput` | The direct dial phone number of this property |  |
| resortDetailsPostCode | `StringInput` | The postal code of this property. |  |
| resortDetailsPkid | `FloatInput` | Primary Key ID |  |
| resortDetailsProinfoUrl | `StringInput` | URL where property information is located. |  |
| resortDetailsPropMapUrl | `StringInput` | Property MAP URL. |  |
| resortDetailsPropPicUrl | `StringInput` | Property picture URL. |  |
| resortDetailsLocationid | `StringInput` | The property that the record belongs to |  |
| resortDetailsName | `StringInput` | The name of this property. |  |
| resortDetailsResortType | `StringInput` | Type of resort. |  |
| resortDetailsQuotedCurrency | `StringInput` | Future use |  |
| resortDetailsRnaInsertdate | `DateTimeInput` | RNA Insert Date |  |
| resortDetailsRnaUpdatedate | `DateTimeInput` | RNA Update Date |  |
| resortDetailsReconcileDate | `DateTimeInput` | Minimim last Reconciliation Date for the Property used in Cross Property Postings. This will get updated while running the user defined procedure during the night audit process. |  |
| resortDetailsRegionCode | `StringInput` | Future use |  |
| resortDetailsRegionDescription | `StringInput` | Description of the Region. |  |
| resortDetailsRestaurant | `FloatInput` | Future use |  |
| resortDetailsRhythmSheets | `FloatInput` | Total number of Sheets |  |
| resortDetailsRhythmTowels | `FloatInput` | Total number of Towels |  |
| resortDetailsRoomAmenity | `StringInput` | Room amenity. |  |
| resortDetailsSglNum | `StringInput` | Future use |  |
| resortDetailsSglRate1 | `FloatInput` | Future use |  |
| resortDetailsSglRate2 | `FloatInput` | Future use |  |
| resortDetailsSuiNum | `StringInput` | Future use |  |
| resortDetailsSuiRate1 | `FloatInput` | Future use |  |
| resortDetailsSuiRate2 | `FloatInput` | Future use |  |
| resortDetailsSaveProfiles | `FloatInput` | To store number of days before deleting the gest profile |  |
| resortDetailsScriptId | `FloatInput` | Future use |  |
| resortDetailsSeason1 | `StringInput` | Future use |  |
| resortDetailsSeason2 | `StringInput` | Future use |  |
| resortDetailsSeason3 | `StringInput` | Future use |  |
| resortDetailsSeason4 | `StringInput` | Future use |  |
| resortDetailsSeason5 | `StringInput` | Future use |  |
| resortDetailsSendLeadAsBooking | `StringInput` | Indicates that the property accepts leads as bookings. |  |
| resortDetailsShopDescription | `StringInput` | Shop description. |  |
| resortDetailsShortDateFormat | `StringInput` | Short date format for the property. |  |
| resortDetailsQtySingleRooms | `FloatInput` | Number of single rooms. |  |
| resortDetailsSourceCommission | `StringInput` | For default commission percentage |  |
| resortDetailsState | `StringInput` | The state in which this property is located. |  |
| resortDetailsStateDesc | `StringInput` | Description of the state. |  |
| resortDetailsStreet | `StringInput` | The street of the property. |  |
| resortDetailsQtySuites | `FloatInput` | Number of suites. |  |
| resortDetailsSummCurrencyCode | `StringInput` | Internal |  |
| resortDetailsTaCommission | `StringInput` | For default commission percentage |  |
| resortDetailsTplNum | `StringInput` | Future use |  |
| resortDetailsTplRate1 | `FloatInput` | Future use |  |
| resortDetailsTplRate2 | `FloatInput` | Future use |  |
| resortDetailsTelephoneNoFormat | `StringInput` | Formats for telephone number |  |
| resortDetailsThousandSeparator | `StringInput` | Separator for monetory values |  |
| resortDetailsTimeFormat | `StringInput` | Default time format for the property. |  |
| resortDetailsTimezoneRegion | `StringInput` | Time zone region selected by the employee. |  |
| resortDetailsTollfree | `StringInput` | Toll free telephone number. |  |
| resortDetailsTotRooms | `FloatInput` | Future use |  |
| resortDetailsTouristNumber | `StringInput` | Tourist Number |  |
| resortDetailsTranslateMulticharYn | `StringInput` | Indicates whether the property handles multi byte characters and whether they are translateable or not |  |
| resortDetailsTurnawayCode | `StringInput` | Turnaway code for the property. |  |
| resortDetailsQtyTwinRooms | `FloatInput` | Number of twin rooms. |  |
| resortDetailsUpdateDate | `DateTimeInput` | The date the record was modified |  |
| resortDetailsUpdateUser | `FloatInput` | The user that modified the record |  |
| resortDetailsVatId | `StringInput` | VAT ID of this property. |  |
| resortDetailsVideocheckoutPrinter | `StringInput` | Future use |  |
| resortDetailsVideoCoStart | `DateTimeInput` | Video check out start time. |  |
| resortDetailsVideoCoStop | `DateTimeInput` | Video check out end time. |  |
| resortDetailsWakeUpDelay | `FloatInput` | Future use |  |
| resortDetailsWarningAmount | `FloatInput` | Amount at which warning is raised. |  |
| resortDetailsWebaddress | `StringInput` | Webaddress of the property |  |
| resortDetailsWeekendDays | `StringInput` | Weekend days for the property. |  |
| resortDetailsZeroInvPurDays | `FloatInput` | Internal |  |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query aRAccountsReceivable($input: ARAccountsReceivableQueryArgumentsType!) {
  aRAccountsReceivable(input: $input) @stream {
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
    aRTransactionAdjustmentDetailsDetails {
      aRChargeTransferYN
      aSBFlag
      aSBOnlyPostTaxesOnceYn
      aSBTaxFlag
      accountTypeFlag
      accountid
      advGenerateAdjustment
      advanceBillReversedYn
      advanceBillYn
      advanceGenerateTrxCode
      advancedGenerateYn
      allowanceType
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
      calcPointsYn
      cashierCredit
      cashierDebit
      cashierId
      cashierOpeningBalance
      ccRefundPosting
      ccTrxFeeAmount
      centralTransactionAmount
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
      creditCardId
      currency
      dSI
      deferredTaxesYn
      deferredYn
      deletedFlag
      depLedgerCredit
      depLedgerDebit
      depPostingFlag
      depTaxTransferedYn
      depositTransactionId
      depositlinkfintransid
      displayYn
      effectiveDate
      electronicVoucherNo
      esignedReceiptName
      euroExchangeRate
      exchDifferenceTrxNumber
      exchangeDate
      exchangeDifferenceYn
      exchangeType
      expInvoiceType
      expOriginalInvoice
      extSysResultMsg
      extTransactionId
      fbaCertificateNumber
      financialDmlSeqNumber
      fintransactionid
      fintransid
      fiscalBillNo
      fiscalTrxCodeType
      fixedChargesYn
      folioNo
      folioType
      folioView
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
      guestAccountCredit
      guestAccountDebit
      holdYn
      hotelAcct
      incTaxDeductedYn
      inhCredit
      inhDebit
      insertDate
      insertUser
      installments
      invoiceCloseDate
      invoiceNo
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
      profileid
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
      remark
      reservationDepositId
      reservationNameId
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
      transactionAmount
      transactionDate
      transactionFromAcct
      transactionNumber
      transactionNumberToDepositPosting
      transactionToAcct
      transactionType
      transcodearrangementid
      transcodeid
      trnsActivityDate
      trxCode
      trxNumberAddedBy
      trxNumberAdjust
      trxNumberAgainstPackage
      trxNumberSplit
      trxServiceType
      updateDate
      updateUser
      upsellChargeYn
      vatOffsetYn
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
    aRPostDetailsDetails {
      aRChargeTransferYN
      aRLedgerCredit
      aRLedgerDebit
      aROpen
      aRTransferDate
      aSBFlag
      aSBOnlyPostTaxesOnceYn
      aSBTaxFlag
      accountTypeFlag
      accountid
      adjustmentYN
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
      arNumber
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
      cAropen
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
      centralARLedgerCredit
      centralARLedgerDebit
      centralAmount
      centralPaid
      centralPostedAmount
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
      creditCardId
      currency
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
      fTCompany
      fTFirstName
      fTLastName
      fTNameType
      fbaCertificateNumber
      financialDmlSeqNumber
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
      ftSubtype
      genCashierId
      gpAwardCancelCode
      gpAwardCode
      grossAmount
      groupAwardCancelledYN
      guestAccountCredit
      guestAccountDebit
      guestname
      holdYn
      hotelAcct
      incTaxDeductedYn
      inhCredit
      inhDebit
      insertDate
      insertUser
      installments
      invoiceAge
      invoiceCloseDate
      invoiceNumber
      invoiceStatus
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
      organizationArLedgerDebit
      organizationID
      originalPostedAmount
      originalReservationNameId
      originalRoom
      packageAllowance
      packageArrangementCode
      packageCredit
      packageDebit
      packageTrxType
      paid
      parallelCurrency
      parallelGrossAmount
      parallelGuestCredit
      parallelGuestDebit
      parallelNetAmount
      passerByName
      paymentSurchargeAmt
      paymentSurchargeType
      paymentType
      postDate
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
      profileID
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
      recordType
      reference
      repGuestname
      reportingTransactionCodeDesc
      reservationDepositId
      reservationFirstName
      reservationNameId
      reservationid
      resevationLastName
      revenueAmt
      reversePaymentTrxNumber
      revisionNo
      room
      roomClass
      roomNts
      roomNtsEffective
      roomid
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
      transactionCodeDesc
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
    accountTypeDetails {
      accountType
      accountTypeDescription
      accountTypeId
      agingDelayDays
      centralAccountType
      centralAccountTypeDescription
      centralCreditLimit
      centralFinanceChargeAmount
      centralXchangeDate
      centralXchangeRate
      chargesOlderThanNDays
      creditLimit
      dSI
      deletedflag
      financeChargeAmount
      financeChargePercentage
      inactiveflag
      includeUnallocatedPaymentsYN
      insertDate
      insertUser
      internalAccounttypeid
      jRNUpdateDate
      jRNUpdateDateAndTime
      letterNameEndOfMonth
      locationID
      organizationID
      ownerCashbookReport
      ownerStatementName
      ownerSummary
      postOnDay
      primaryKeyID
      printInvoiceDetailsYn
      printInvoicesWithDetailsYN
      printInvoicesWithoutDetailsYN
      printSeperateFoliosYN
      property
      rNAInsertDate
      rNAUpdateDate
      reminderCycle
      repItem
      repItemName
      repUpdateDate
      statementMode
      statementName
      statementNameDescription
      updateDate
      updateUser
    }
    acctFlagReasonDetails {
      acctflagreasonid
      centralFlaggedReasonCode
      centralRestrictedReasonDescription
      centralSequence
      dSI
      deletedflag
      flaggedReasonCode
      inactiveflag
      insertDate
      insertUser
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
      restrictedReasonDescription
      sequence
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
    accountNoteDetails {
      accountCode
      accountid
      accountnoteid
      dSI
      deletedflag
      inactiveflag
      insertDate
      insertUser
      internalflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      noteCode
      noteDetails
      noteId
      noteTitle
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
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