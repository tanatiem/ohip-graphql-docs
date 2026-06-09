# ARAccountsReceivable
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
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

### ARAccountsReceivableQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
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
| accountDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| accountDetailsUpperCaseName | `StringInput` | Upper Case Name |
| artranadjdetailsDetailsAccountid | `FloatInput` | Accountid |
| artranadjdetailsDetailsArLedCredit | `FloatInput` | AR Led Credit |
| artranadjdetailsDetailsArLedDebit | `FloatInput` | AR Led Debit |
| artranadjdetailsDetailsArState | `StringInput` | AR State |
| artranadjdetailsDetailsAuthorizerId | `FloatInput` | Authorizer ID |
| artranadjdetailsDetailsBillNo | `FloatInput` | Bill Number |
| artranadjdetailsDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| artranadjdetailsDetailsBusinessDate | `DateInput` | Business Date |
| artranadjdetailsDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| artranadjdetailsDetailsCashierId | `FloatInput` | Cashier ID |
| artranadjdetailsDetailsChequeNumber | `StringInput` | Cheque Number |
| artranadjdetailsDetailsClosureNo | `FloatInput` | Closure Number |
| artranadjdetailsDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| artranadjdetailsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| artranadjdetailsDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| artranadjdetailsDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| artranadjdetailsDetailsFintransactionid | `FloatInput` | Fintransactionid |
| artranadjdetailsDetailsFintransid | `FloatInput` | Fintransid |
| artranadjdetailsDetailsFolioNo | `FloatInput` | Folio Number |
| artranadjdetailsDetailsFolioView | `FloatInput` | Folio View |
| artranadjdetailsDetailsFromResvId | `FloatInput` | From Resv ID |
| artranadjdetailsDetailsGuestAccountCredit | `FloatInput` | Guest Account Credit |
| artranadjdetailsDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| artranadjdetailsDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |
| artranadjdetailsDetailsInsertDate | `DateTimeInput` | Insert Date |
| artranadjdetailsDetailsInvoiceNo | `FloatInput` | Invoice Number |
| artranadjdetailsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| artranadjdetailsDetailsLinkTrxNo | `FloatInput` | Link Transaction No |
| artranadjdetailsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| artranadjdetailsDetailsNameId | `FloatInput` | Name ID |
| artranadjdetailsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| artranadjdetailsDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |
| artranadjdetailsDetailsOriginalRoom | `StringInput` | Original Room |
| artranadjdetailsDetailsPostitNo | `FloatInput` | Postit Number |
| artranadjdetailsDetailsProduct | `StringInput` | Product |
| artranadjdetailsDetailsProfileid | `FloatInput` | Profileid |
| artranadjdetailsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| artranadjdetailsDetailsRateCode | `StringInput` | Rate Code |
| artranadjdetailsDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| artranadjdetailsDetailsResvNameId | `FloatInput` | Resv Name ID |
| artranadjdetailsDetailsRoom | `StringInput` | Room |
| artranadjdetailsDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| artranadjdetailsDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| artranadjdetailsDetailsTaxElements | `StringInput` | Tax Elements |
| artranadjdetailsDetailsTcGroup | `StringInput` | Transaction Code Group |
| artranadjdetailsDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| artranadjdetailsDetailsTranActionId | `FloatInput` | Tran Action ID |
| artranadjdetailsDetailsTrxDate | `DateInput` | Transaction Date |
| artranadjdetailsDetailsTrxNo | `FloatInput` | Transaction Number |
| artranadjdetailsDetailsTrxNoHeader | `FloatInput` | Transaction Number to Deposit Posting |
| artranadjdetailsDetailsTranscodeid | `StringInput` | Transcodeid |
| artranadjdetailsDetailsTrxCode | `StringInput` | Transaction Code |
| artranadjdetailsDetailsTrxNoAddedBy | `FloatInput` | Transaction No Added By |
| artranadjdetailsDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| artranadjdetailsDetailsTrxNoAgainstPackage | `FloatInput` | Transaction No Against Package |
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
| arpostdetailsDetailsAccountid | `FloatInput` | Accountid |
| arpostdetailsDetailsArNumber | `FloatInput` | AR Number |
| arpostdetailsDetailsArticleId | `FloatInput` | Article ID |
| arpostdetailsDetailsAuthorizerId | `FloatInput` | Authorizer ID |
| arpostdetailsDetailsBillNo | `FloatInput` | Bill Number |
| arpostdetailsDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| arpostdetailsDetailsBusinessDate | `DateInput` | Business Date |
| arpostdetailsDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| arpostdetailsDetailsCashierId | `FloatInput` | Cashier ID |
| arpostdetailsDetailsChequeNumber | `StringInput` | Cheque Number |
| arpostdetailsDetailsClosureNo | `FloatInput` | Closure Number |
| arpostdetailsDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| arpostdetailsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| arpostdetailsDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| arpostdetailsDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| arpostdetailsDetailsFintransid | `FloatInput` | Fintransid |
| arpostdetailsDetailsFolioNo | `FloatInput` | Folio Number |
| arpostdetailsDetailsFolioView | `FloatInput` | Folio View |
| arpostdetailsDetailsFolioid | `FloatInput` | Folioid |
| arpostdetailsDetailsFromResvId | `FloatInput` | From Resv ID |
| arpostdetailsDetailsGuestAccountCredit | `FloatInput` | Guest Account Credit |
| arpostdetailsDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| arpostdetailsDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |
| arpostdetailsDetailsInsertDate | `DateTimeInput` | Insert Date |
| arpostdetailsDetailsInvoiceNo | `FloatInput` | Invoice Number |
| arpostdetailsDetailsArState | `StringInput` | Invoice Status |
| arpostdetailsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| arpostdetailsDetailsLinkTrxNo | `FloatInput` | Link Transaction No |
| arpostdetailsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| arpostdetailsDetailsNameId | `FloatInput` | Name ID |
| arpostdetailsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| arpostdetailsDetailsOriginalResvNameId | `FloatInput` | Original Resv Name ID |
| arpostdetailsDetailsOriginalRoom | `StringInput` | Original Room |
| arpostdetailsDetailsTrxDate | `DateInput` | Post Date |
| arpostdetailsDetailsPostitNo | `FloatInput` | Postit Number |
| arpostdetailsDetailsProduct | `StringInput` | Product |
| arpostdetailsDetailsProfileid | `FloatInput` | Profile ID |
| arpostdetailsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| arpostdetailsDetailsRateCode | `StringInput` | Rate Code |
| arpostdetailsDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| arpostdetailsDetailsResvNameId | `FloatInput` | Resv Name ID |
| arpostdetailsDetailsReservationid | `FloatInput` | Reservationid |
| arpostdetailsDetailsRoom | `StringInput` | Room |
| arpostdetailsDetailsRoomid | `StringInput` | Roomid |
| arpostdetailsDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| arpostdetailsDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| arpostdetailsDetailsTaxElements | `StringInput` | Tax Elements |
| arpostdetailsDetailsTcGroup | `StringInput` | Transaction Code Group |
| arpostdetailsDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| arpostdetailsDetailsTranActionId | `FloatInput` | Tran Action ID |
| arpostdetailsDetailsTrxNo | `FloatInput` | Transaction Number |
| arpostdetailsDetailsTranscodeid | `StringInput` | Transcodeid |
| arpostdetailsDetailsTrxCode | `StringInput` | Transaction Code |
| arpostdetailsDetailsTrxNoAddedBy | `FloatInput` | Transaction No Added By |
| arpostdetailsDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| arpostdetailsDetailsTrxNoAgainstPackage | `FloatInput` | Transaction No Against Package |
| arpostdetailsDetailsTrxNoHeader | `FloatInput` | Transaction No Header |
| accounttypeDetailsAccountType | `StringInput` | Account Type |
| accounttypeDetailsCXchangeDate | `DateInput` | Central Exchange Date |
| accounttypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| accounttypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| accounttypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| accounttypeDetailsResort | `StringInput` | Property |
| acctflagreasonDetailsAcctflagreasonid | `StringInput` | Acctflagreasonid |
| acctflagreasonDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| acctflagreasonDetailsReasonCode | `StringInput` | Flagged Reason Code |
| acctflagreasonDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| acctflagreasonDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| acctflagreasonDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| acctflagreasonDetailsResort | `StringInput` | Property |
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
| accountnoteDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| accountnoteDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| accountnoteDetailsNoteId | `FloatInput` | Note ID |
| accountnoteDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| accountnoteDetailsResort | `StringInput` | Code to uniquely identify the Property |
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

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
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
a_r_transaction_adjustment_details_details_schema = {
    'aRChargeTransferYN': pl.Utf8,
    'aSBFlag': pl.Utf8,
    'aSBOnlyPostTaxesOnceYn': pl.Utf8,
    'aSBTaxFlag': pl.Utf8,
    'accountTypeFlag': pl.Utf8,
    'accountid': pl.Float64,
    'advGenerateAdjustment': pl.Utf8,
    'advanceBillReversedYn': pl.Utf8,
    'advanceBillYn': pl.Utf8,
    'advanceGenerateTrxCode': pl.Utf8,
    'advancedGenerateYn': pl.Utf8,
    'allowanceType': pl.Utf8,
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
    'calcPointsYn': pl.Utf8,
    'cashierCredit': pl.Float64,
    'cashierDebit': pl.Float64,
    'cashierId': pl.Float64,
    'cashierOpeningBalance': pl.Float64,
    'ccRefundPosting': pl.Utf8,
    'ccTrxFeeAmount': pl.Float64,
    'centralTransactionAmount': pl.Float64,
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
    'creditCardId': pl.Float64,
    'currency': pl.Utf8,
    'dSI': pl.Int64,
    'deferredTaxesYn': pl.Utf8,
    'deferredYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depLedgerCredit': pl.Float64,
    'depLedgerDebit': pl.Float64,
    'depPostingFlag': pl.Utf8,
    'depTaxTransferedYn': pl.Utf8,
    'depositTransactionId': pl.Utf8,
    'depositlinkfintransid': pl.Float64,
    'displayYn': pl.Utf8,
    'effectiveDate': pl.Utf8,
    'electronicVoucherNo': pl.Float64,
    'esignedReceiptName': pl.Utf8,
    'euroExchangeRate': pl.Float64,
    'exchDifferenceTrxNumber': pl.Float64,
    'exchangeDate': pl.Utf8,
    'exchangeDifferenceYn': pl.Utf8,
    'exchangeType': pl.Utf8,
    'expInvoiceType': pl.Utf8,
    'expOriginalInvoice': pl.Utf8,
    'extSysResultMsg': pl.Utf8,
    'extTransactionId': pl.Utf8,
    'fbaCertificateNumber': pl.Utf8,
    'financialDmlSeqNumber': pl.Float64,
    'fintransactionid': pl.Float64,
    'fintransid': pl.Float64,
    'fiscalBillNo': pl.Utf8,
    'fiscalTrxCodeType': pl.Utf8,
    'fixedChargesYn': pl.Utf8,
    'folioNo': pl.Float64,
    'folioType': pl.Utf8,
    'folioView': pl.Float64,
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
    'guestAccountCredit': pl.Float64,
    'guestAccountDebit': pl.Float64,
    'holdYn': pl.Utf8,
    'hotelAcct': pl.Utf8,
    'incTaxDeductedYn': pl.Utf8,
    'inhCredit': pl.Float64,
    'inhDebit': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'installments': pl.Float64,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNo': pl.Float64,
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
    'profileid': pl.Float64,
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
    'remark': pl.Utf8,
    'reservationDepositId': pl.Float64,
    'reservationNameId': pl.Float64,
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
    'transactionAmount': pl.Float64,
    'transactionDate': pl.Utf8,
    'transactionFromAcct': pl.Float64,
    'transactionNumber': pl.Float64,
    'transactionNumberToDepositPosting': pl.Float64,
    'transactionToAcct': pl.Float64,
    'transactionType': pl.Utf8,
    'transcodearrangementid': pl.Float64,
    'transcodeid': pl.Utf8,
    'trnsActivityDate': pl.Utf8,
    'trxCode': pl.Utf8,
    'trxNumberAddedBy': pl.Float64,
    'trxNumberAdjust': pl.Float64,
    'trxNumberAgainstPackage': pl.Float64,
    'trxNumberSplit': pl.Float64,
    'trxServiceType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellChargeYn': pl.Utf8,
    'vatOffsetYn': pl.Utf8,
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
a_r_post_details_details_schema = {
    'aRChargeTransferYN': pl.Utf8,
    'aRLedgerCredit': pl.Float64,
    'aRLedgerDebit': pl.Float64,
    'aROpen': pl.Float64,
    'aRTransferDate': pl.Utf8,
    'aSBFlag': pl.Utf8,
    'aSBOnlyPostTaxesOnceYn': pl.Utf8,
    'aSBTaxFlag': pl.Utf8,
    'accountTypeFlag': pl.Utf8,
    'accountid': pl.Float64,
    'adjustmentYN': pl.Utf8,
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
    'arNumber': pl.Float64,
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
    'cAropen': pl.Float64,
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
    'centralARLedgerCredit': pl.Float64,
    'centralARLedgerDebit': pl.Float64,
    'centralAmount': pl.Float64,
    'centralPaid': pl.Float64,
    'centralPostedAmount': pl.Float64,
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
    'creditCardId': pl.Float64,
    'currency': pl.Utf8,
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
    'fTCompany': pl.Utf8,
    'fTFirstName': pl.Utf8,
    'fTLastName': pl.Utf8,
    'fTNameType': pl.Utf8,
    'fbaCertificateNumber': pl.Utf8,
    'financialDmlSeqNumber': pl.Float64,
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
    'ftSubtype': pl.Utf8,
    'genCashierId': pl.Float64,
    'gpAwardCancelCode': pl.Utf8,
    'gpAwardCode': pl.Utf8,
    'grossAmount': pl.Float64,
    'groupAwardCancelledYN': pl.Utf8,
    'guestAccountCredit': pl.Float64,
    'guestAccountDebit': pl.Float64,
    'guestname': pl.Utf8,
    'holdYn': pl.Utf8,
    'hotelAcct': pl.Utf8,
    'incTaxDeductedYn': pl.Utf8,
    'inhCredit': pl.Float64,
    'inhDebit': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'installments': pl.Float64,
    'invoiceAge': pl.Float64,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNumber': pl.Float64,
    'invoiceStatus': pl.Utf8,
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
    'organizationArLedgerDebit': pl.Float64,
    'organizationID': pl.Int64,
    'originalPostedAmount': pl.Float64,
    'originalReservationNameId': pl.Float64,
    'originalRoom': pl.Utf8,
    'packageAllowance': pl.Float64,
    'packageArrangementCode': pl.Utf8,
    'packageCredit': pl.Float64,
    'packageDebit': pl.Float64,
    'packageTrxType': pl.Utf8,
    'paid': pl.Float64,
    'parallelCurrency': pl.Utf8,
    'parallelGrossAmount': pl.Float64,
    'parallelGuestCredit': pl.Float64,
    'parallelGuestDebit': pl.Float64,
    'parallelNetAmount': pl.Float64,
    'passerByName': pl.Utf8,
    'paymentSurchargeAmt': pl.Float64,
    'paymentSurchargeType': pl.Utf8,
    'paymentType': pl.Utf8,
    'postDate': pl.Utf8,
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
    'profileID': pl.Float64,
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
    'recordType': pl.Utf8,
    'reference': pl.Utf8,
    'repGuestname': pl.Utf8,
    'reportingTransactionCodeDesc': pl.Utf8,
    'reservationDepositId': pl.Float64,
    'reservationFirstName': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'resevationLastName': pl.Utf8,
    'revenueAmt': pl.Float64,
    'reversePaymentTrxNumber': pl.Float64,
    'revisionNo': pl.Float64,
    'room': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomNts': pl.Float64,
    'roomNtsEffective': pl.Float64,
    'roomid': pl.Utf8,
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
    'transactionCodeDesc': pl.Utf8,
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
account_type_details_schema = {
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'accountTypeId': pl.Float64,
    'agingDelayDays': pl.Float64,
    'centralAccountType': pl.Utf8,
    'centralAccountTypeDescription': pl.Utf8,
    'centralCreditLimit': pl.Float64,
    'centralFinanceChargeAmount': pl.Float64,
    'centralXchangeDate': pl.Utf8,
    'centralXchangeRate': pl.Float64,
    'chargesOlderThanNDays': pl.Float64,
    'creditLimit': pl.Float64,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'financeChargeAmount': pl.Float64,
    'financeChargePercentage': pl.Float64,
    'inactiveflag': pl.Utf8,
    'includeUnallocatedPaymentsYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalAccounttypeid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'letterNameEndOfMonth': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'ownerCashbookReport': pl.Utf8,
    'ownerStatementName': pl.Utf8,
    'ownerSummary': pl.Utf8,
    'postOnDay': pl.Float64,
    'primaryKeyID': pl.Int64,
    'printInvoiceDetailsYn': pl.Utf8,
    'printInvoicesWithDetailsYN': pl.Utf8,
    'printInvoicesWithoutDetailsYN': pl.Utf8,
    'printSeperateFoliosYN': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reminderCycle': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repUpdateDate': pl.Utf8,
    'statementMode': pl.Utf8,
    'statementName': pl.Utf8,
    'statementNameDescription': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
acct_flag_reason_details_schema = {
    'acctflagreasonid': pl.Utf8,
    'centralFlaggedReasonCode': pl.Utf8,
    'centralRestrictedReasonDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'flaggedReasonCode': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
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
    'restrictedReasonDescription': pl.Utf8,
    'sequence': pl.Float64,
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
account_note_details_schema = {
    'accountCode': pl.Float64,
    'accountid': pl.Float64,
    'accountnoteid': pl.Float64,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'noteCode': pl.Utf8,
    'noteDetails': pl.Utf8,
    'noteId': pl.Float64,
    'noteTitle': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
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