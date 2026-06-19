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

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountDetails | [`ARAccountsReceivableAccountDetailsType`](#araccountsreceivableaccountdetailstype) | Account Details |
| 2 | aRTransactionAdjustmentDetailsDetails | [`ARAccountsReceivableARTransactionAdjustmentDetailsDetailsType`](#araccountsreceivableartransactionadjustmentdetailsdetailstype) | AR Transaction Adjustment Details |
| 3 | aRLedgerDetails | [`ARAccountsReceivableARLedgerDetailsType`](#araccountsreceivablearledgerdetailstype) | AR Ledger |
| 4 | invoiceHeaderDetails | [`ARAccountsReceivableInvoiceHeaderDetailsType`](#araccountsreceivableinvoiceheaderdetailstype) | Invoice Header Details |
| 5 | aRPostDetailsDetails | [`ARAccountsReceivableARPostDetailsDetailsType`](#araccountsreceivablearpostdetailsdetailstype) | AR Post Details |
| 6 | accountTypeDetails | [`ARAccountsReceivableAccountTypeDetailsType`](#araccountsreceivableaccounttypedetailstype) | Account Type Details |
| 7 | acctFlagReasonDetails | [`ARAccountsReceivableAcctFlagReasonDetailsType`](#araccountsreceivableacctflagreasondetailstype) | Acct Flag Reason Details |
| 8 | employeeDetails | [`ARAccountsReceivableEmployeeDetailsType`](#araccountsreceivableemployeedetailstype) | Employee Details |
| 9 | accountNoteDetails | [`ARAccountsReceivableAccountNoteDetailsType`](#araccountsreceivableaccountnotedetailstype) | Account Note Details |
| 10 | profileAllInformationDetails | [`ARAccountsReceivableProfileAllInformationDetailsType`](#araccountsreceivableprofileallinformationdetailstype) | Profile All Details |
| 11 | propertyPropertyDetails | [`ARAccountsReceivablePropertyPropertyDetailsType`](#araccountsreceivablepropertypropertydetailstype) | Resort Details |
| 12 | aRAccountsReceivableRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableAccountDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountCode | `Float` | Account Code |
| 2 | accountCreditLimitYn | `String` | Indicates if a Credit Limit amount will be required "Y" will take precedence over the credit limit amount on Profile level. |
| 3 | accountName | `String` | Account Name |
| 4 | accountNumber | `String` | Account Number |
| 5 | accountSname | `String` | Name on the account in upper case. |
| 6 | accountStatus | `String` | Status of an account. (Normal Restricted) |
| 7 | accountStatusMsg | `String` | Message prompt when the AR Account is defined as restricted. |
| 8 | accountType | `String` | Account Type |
| 9 | accountTypeFlag | `String` | Account Type Flag |
| 10 | accountTypeId | `Float` | Account Type ID |
| 11 | accountid | `Float` | Accountid |
| 12 | acctflagreasonid | `String` | Acctflagreasonid |
| 13 | activeYN | `String` | Active YN |
| 14 | addressId | `Float` | Address ID |
| 15 | address1 | `String` | Address1 |
| 16 | address2 | `String` | Address2 |
| 17 | address3 | `String` | Address3 |
| 18 | age | `Float` | Age. |
| 19 | agent | `String` | Agent |
| 20 | agentUserId | `Float` | Application User ID of the Account Controller/Agent |
| 21 | agentemployeeid | `Float` | Agentemployeeid |
| 22 | balance | `Float` | Balance on the account. |
| 23 | batchStmtYn | `String` | Include the account in batch statement |
| 24 | beginDate | `Date` | Begin Date |
| 25 | centralAccountType | `String` | Central Account Type |
| 26 | centralBalance | `Float` | Central Balance |
| 27 | centralCreditLimit | `Float` | Central Credit Limit |
| 28 | centralFlaggedReasonCode | `String` | Central Flagged Reason Code |
| 29 | centralState | `String` | Central State |
| 30 | centralXchangeDate | `Date` | Central Exchange Date |
| 31 | centralXchangeRate | `Float` | Central Exchange Rate |
| 32 | city | `String` | City |
| 33 | company | `String` | Company |
| 34 | contact | `String` | Contact information. |
| 35 | country | `String` | Country |
| 36 | countryCode | `String` | Country Code |
| 37 | countryName | `String` | Country Name |
| 38 | creditLimit | `Float` | Credit Limit |
| 39 | creditLimitUpdatedOn | `DateTime` | Date when the Credit Limit was updated. |
| 40 | currencyCode | `String` | Summary Currency Code |
| 41 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 42 | debtorName | `String` | Debtor Name |
| 43 | deletedflag | `String` | Deleted Flag |
| 44 | email | `String` | Email |
| 45 | emailAddr | `String` | Email Addr |
| 46 | emailId | `Float` | Email ID |
| 47 | emailOptInYn | `String` | Indicates if the email address can be used to send Statements and Reminders by default. |
| 48 | endDate | `Date` | End Date |
| 49 | fax | `String` | Fax |
| 50 | faxId | `Float` | Fax ID |
| 51 | faxNumber | `String` | Fax Number |
| 52 | flaggedReasonCode | `String` | The flagged reason code from table AR$_FLAGGED_REASONS. |
| 53 | inactiveDate | `DateTime` | Inactive Date |
| 54 | insertDate | `DateTime` | Insert Date |
| 55 | insertUser | `Float` | Insert User |
| 56 | internalAccounttypeid | `Float` | Accounttypeid |
| 57 | jRNUpdateDate | `Date` | JRN Update Date |
| 58 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 59 | lastActivityDate | `DateTime` | Date of Last Activity on the AR Account in regards to: transfers between accounts payments applied (not unallocated) un-applied reversed and invoice compressions un-compressions on the account. |
| 60 | lastRemFaxNo | `String` | Fax number to which the last reminder letter was sent. |
| 61 | lastStmtFaxNo | `String` | Fax number to which the last statement was sent. |
| 62 | locationID | `String` | Internal ID to uniquely identify the Property |
| 63 | lstRemPrtDate | `Date` | Date on which the last reminder letter was printed. |
| 64 | lstRemSent | `Date` | Date on which the last reminder letter was sent. |
| 65 | lstRemText | `String` | Name of the reminder letter |
| 66 | lstStmtNoSent | `Float` | Stores the statement number of the last statement sent for a particular AR account. |
| 67 | lstStmtSent | `DateTime` | Date of Last reminderletter sent |
| 68 | monthEndCalcYn | `String` | If Y the Payment due date calculation begins from the last day of the month of invoice generation date if N  then calculation starts from the day of the invoice generation. |
| 69 | nAAddress1 | `String` | NA Address 1 |
| 70 | nAAddress2 | `String` | NA Address 2 |
| 71 | nAAddress3 | `String` | NA Address 3 |
| 72 | naCity | `String` | Na City |
| 73 | naCountryName | `String` | Na Country Name |
| 74 | naState | `String` | Na State |
| 75 | naStateDescription | `String` | Na State Description |
| 76 | nameId | `Float` | Name ID |
| 77 | numberOfPersons | `Float` | No of persons currently using the account |
| 78 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 79 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 80 | permAccountYN | `String` | Status indicator to show the account as a permanent account. User will not be able to delete the account if it is Y |
| 81 | phone | `String` | Phone |
| 82 | phoneId | `Float` | Phone ID |
| 83 | phoneNumber | `String` | Phone Number |
| 84 | postalCode | `String` | Postal Code |
| 85 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 86 | primaryYn | `String` | Primary Y/N |
| 87 | profileid | `Float` | Profileid |
| 88 | property | `String` | Code to uniquely identify the Property |
| 89 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 90 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 91 | repStateDescription | `String` | Reporting State Description |
| 92 | revenuePool | `String` | Revenue Pool |
| 93 | state | `String` | State |
| 94 | stateDescription | `String` | State Description |
| 95 | status | `String` | Status |
| 96 | summaryforeigncurrid | `String` | Summaryforeigncurrid |
| 97 | superSearchIndexText | `String` | Super Search Index Text |
| 98 | supplement | `String` | Supplement |
| 99 | updateDate | `DateTime` | Update Date |
| 100 | updateUser | `Float` | Update User |
| 101 | upperCaseName | `String` | Upper Case Name |
| 102 | zip | `String` | Zip code. |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableARTransactionAdjustmentDetailsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| 2 | aSBFlag | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| 3 | aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| 4 | aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| 5 | accountTypeFlag | `String` | Account Type Flag |
| 6 | accountid | `Float` | Accountid |
| 7 | advGenerateAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| 8 | advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| 9 | advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| 10 | advanceGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| 11 | advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| 12 | allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| 13 | approvalCode | `String` | Approval Code |
| 14 | approvalDate | `Date` | Approval Date |
| 15 | approvalStatus | `String` | Approval Status |
| 16 | arLedgerCredit | `Float` | AR Led Credit |
| 17 | arLedgerDebit | `Float` | AR Led Debit |
| 18 | arNumber | `Float` | AR Number |
| 19 | arState | `String` | AR State |
| 20 | arTransferDate | `Date` | AR Transfer Date |
| 21 | arrangementId | `Float` | Arrangement ID |
| 22 | articleId | `Float` | Article ID |
| 23 | associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| 24 | associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| 25 | authorizerId | `Float` | Authorizer ID |
| 26 | autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| 27 | autoSettleYn | `String` | Auto Settle Y/N |
| 28 | billNo | `Float` | Bill Number |
| 29 | bonusCheckId | `Float` | Bonus Check ID |
| 30 | bucketCode | `String` | Bucket code related to this redemption. |
| 31 | bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| 32 | businessDate | `Date` | Business Date |
| 33 | cARLedgerCredit | `Float` | Central Ar Led Credit |
| 34 | cARLedgerDebit | `Float` | Central Ar Led Debit |
| 35 | cCashierCredit | `Float` | Central Cashier Credit |
| 36 | cCashierDebit | `Float` | Central Cashier Debit |
| 37 | cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| 38 | cCcTransactionFeeAmount | `Float` | Central Cc Trx Fee Amount |
| 39 | cChangeDue | `Float` | Central Change Due |
| 40 | cContractGrossAmount | `Float` | Central Contract Gross Amount |
| 41 | cContractGuestCredit | `Float` | Central Contract Guest Credit |
| 42 | cContractGuestDebit | `Float` | Central Contract Guest Debit |
| 43 | cContractNetAmount | `Float` | Central Contract Net Amount |
| 44 | cDepLedgerCredit | `Float` | Central Dep Led Credit |
| 45 | cDepLedgerDebit | `Float` | Central Dep Led Debit |
| 46 | cExchangeDate | `Date` | Central Xchange Date |
| 47 | cExchangeRate | `Float` | Central Xchange Rate |
| 48 | cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| 49 | cGrossAmount | `Float` | Central Gross Amount |
| 50 | cGuestAccountCredit | `Float` | Central Guest Account Credit |
| 51 | cGuestAccountDebit | `Float` | Central Guest Account Debit |
| 52 | cInHouseCredit | `Float` | Central Inh Credit |
| 53 | cInHouseDebit | `Float` | Central Inh Debit |
| 54 | cNetAmount | `Float` | Central Net Amount |
| 55 | cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| 56 | cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| 57 | cPackageAllowance | `Float` | Central Package Allowance |
| 58 | cPackageCredit | `Float` | Central Package Credit |
| 59 | cPackageDebit | `Float` | Central Package Debit |
| 60 | cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| 61 | cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| 62 | cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| 63 | cParallelNetAmount | `Float` | Central Parallel Net Amount |
| 64 | cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| 65 | cPostedAmount | `Float` | Central Posted Amount |
| 66 | cPricePerUnit | `Float` | Central Price Per Unit |
| 67 | cRevenueAmount | `Float` | Central Revenue Amt |
| 68 | cTaxRate | `Float` | Central Tax Rate |
| 69 | calcPointsYn | `String` | Indicates if points are to be calculated. |
| 70 | cashierCredit | `Float` | Cashier Credit |
| 71 | cashierDebit | `Float` | Cashier Debit |
| 72 | cashierId | `Float` | Cashier ID |
| 73 | cashierOpeningBalance | `Float` | Cashier Opening Balance |
| 74 | ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| 75 | ccTrxFeeAmount | `Float` | Fee (surcharge) amount for a credit card transaction. |
| 76 | centralTransactionAmount | `Float` | Central Transaction Amount |
| 77 | changeDue | `Float` | Change Due |
| 78 | checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| 79 | chequeNumber | `String` | Cheque Number |
| 80 | closureNo | `Float` | Closure Number |
| 81 | collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| 82 | comments | `String` | Comments |
| 83 | compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| 84 | compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| 85 | compTypeCode | `String` | Comp Type Code |
| 86 | compressedYn | `String` | Compressed Y/N |
| 87 | contractCurrency | `String` | Currency code for contract currency. |
| 88 | contractGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| 89 | contractGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| 90 | contractGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| 91 | contractNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| 92 | correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| 93 | couponNo | `String` | Coupon Number |
| 94 | covers | `String` | Covers |
| 95 | creditCardId | `Float` | Credit Card ID |
| 96 | currency | `String` | Currency |
| 97 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 98 | deferredTaxesYn | `String` | Indicates whether the generated tax is because of a deferred tax generation scenario |
| 99 | deferredYn | `String` | Deferred Y/N |
| 100 | deletedFlag | `String` | Deleted Flag |
| 101 | depLedgerCredit | `Float` | Dep Ledger Credit |
| 102 | depLedgerDebit | `Float` | Dep Ledger Debit |
| 103 | depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| 104 | depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| 105 | depositTransactionId | `String` | Deposit Transaction ID |
| 106 | depositlinkfintransid | `Float` | Depositlinkfintransid |
| 107 | displayYn | `String` | Display Y/N |
| 108 | effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| 109 | electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| 110 | esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| 111 | euroExchangeRate | `Float` | Euro Exchange Rate |
| 112 | exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| 113 | exchangeDate | `Date` | Exchange Date |
| 114 | exchangeDifferenceYn | `String` | The flag indicates if it is an exchange rate difference posting when dual currency is on. |
| 115 | exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| 116 | expInvoiceType | `String` | Export Invoice Type |
| 117 | expOriginalInvoice | `String` | Export Original Invoice |
| 118 | extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| 119 | extTransactionId | `String` | Transaction ID from external system. |
| 120 | fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| 121 | financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| 122 | fintransactionid | `Float` | Fintransactionid |
| 123 | fintransid | `Float` | Fintransid |
| 124 | fiscalBillNo | `String` | Fiscal Bill Number |
| 125 | fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| 126 | fixedChargesYn | `String` | Distinguish ordinary postings from Fixed charge postings. |
| 127 | folioNo | `Float` | Folio Number |
| 128 | folioType | `String` | Folio Type |
| 129 | folioView | `Float` | Folio View |
| 130 | foreignCurrencyID | `String` | Foreign Currency ID |
| 131 | forexCommAmount | `Float` | Foreign Exchange commission amount. |
| 132 | forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| 133 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 134 | forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| 135 | fromReservationId | `Float` | From Resv ID |
| 136 | ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| 137 | ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| 138 | genCashierId | `Float` | General Cashier Id. |
| 139 | gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| 140 | gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| 141 | grossAmount | `Float` | Gross Amount |
| 142 | groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| 143 | guestAccountCredit | `Float` | Guest Account Credit |
| 144 | guestAccountDebit | `Float` | Debit amount on the guest account |
| 145 | holdYn | `String` | Indicates transaction is on hold. |
| 146 | hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| 147 | incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| 148 | inhCredit | `Float` | In House Credit |
| 149 | inhDebit | `Float` | In House Debit |
| 150 | insertDate | `DateTime` | Insert Date |
| 151 | insertUser | `Float` | Insert User |
| 152 | installments | `Float` | Installments |
| 153 | invoiceCloseDate | `Date` | Invoice Close Date |
| 154 | invoiceNo | `Float` | Invoice Number |
| 155 | jRNUpdateDate | `Date` | JRN Update Date |
| 156 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 157 | linkTrxNumber | `Float` | Link Transaction No |
| 158 | locationID | `String` | Internal ID to uniquely identify the Property |
| 159 | marketCode | `String` | Market Code |
| 160 | membershipId | `Float` | Membership ID |
| 161 | mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| 162 | nameId | `Float` | Name ID |
| 163 | nameTaxType | `String` | Name Tax Type |
| 164 | netAmount | `Float` | Net Amount |
| 165 | numberDialed | `String` | Number Dialed. |
| 166 | oTransactionDesc | `String` | Transaction Description. |
| 167 | orgBillNumber | `Float` | Stores original bill number after void. |
| 168 | orgFolioType | `String` | Stores original folio type after void. |
| 169 | orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| 170 | organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| 171 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 172 | originalReservationNameId | `Float` | Original Resv Name ID |
| 173 | originalRoom | `String` | Original Room |
| 174 | packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| 175 | packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| 176 | packageCredit | `Float` | Credit amount on the guest package account. |
| 177 | packageDebit | `Float` | Debit amount on the guest package account |
| 178 | packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| 179 | parallelCurrency | `String` | Cuurency code for parrallel currency. |
| 180 | parallelGrossAmount | `Float` | Parallel Gross Amount |
| 181 | parallelGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| 182 | parallelGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| 183 | parallelNetAmount | `Float` | Parallel Net Amount |
| 184 | passerByName | `String` | Passerby Name. |
| 185 | paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| 186 | paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| 187 | paymentType | `String` | Payment Type |
| 188 | postingDate | `Date` | Posting Date |
| 189 | postingRhythm | `String` | Posting Rhythm |
| 190 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 191 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 192 | postitNo | `Float` | Postit Number |
| 193 | postitYn | `String` | Postit Y/N |
| 194 | pricePerUnit | `Float` | Price Per Unit |
| 195 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 196 | processed8300Yn | `String` | Indicates whether this particular transaction has been included in an 8300 tax form yet. |
| 197 | product | `String` | Product |
| 198 | profileid | `Float` | Profileid |
| 199 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 200 | proformaYn | `String` | Proforma Y/N |
| 201 | property | `String` | Code to uniquely identify the Property |
| 202 | propertyBillPrefix | `String` | Property Bill Prefix |
| 203 | quantity | `Float` | Quantity |
| 204 | queueName | `String` | Queue Name |
| 205 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 206 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 207 | rateCode | `String` | Rate Code |
| 208 | reasonCode | `String` | Reason Code |
| 209 | receiptNo | `Float` | Recpt Number |
| 210 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 211 | reference | `String` | Reference |
| 212 | remark | `String` | Remark |
| 213 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 214 | reservationNameId | `Float` | Resv Name ID |
| 215 | revenueAmt | `Float` | Revenue Amount. |
| 216 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 217 | revisionNo | `Float` | Revision Number |
| 218 | room | `String` | Room |
| 219 | roomClass | `String` | Room Class |
| 220 | roomNts | `Float` | Room Nts |
| 221 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 222 | roundFactorYn | `String` | Round Factor Y/N |
| 223 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 224 | routedYn | `String` | Indicates if the transaction has been routed. |
| 225 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 226 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| 227 | serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| 228 | serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| 229 | settlementFlag | `String` | Settlement Flag |
| 230 | sourceCode | `String` | Source Code |
| 231 | sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| 232 | splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| 233 | taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| 234 | taCommissionableYn | `String` | The value 'Y' indicates that the commission has been paid for the transaction. |
| 235 | targetResort | `String` | Target Property |
| 236 | taxElements | `String` | Tax Elements |
| 237 | taxGeneratedYn | `String` | Indicates whether tax has been generated for a particuar posting. |
| 238 | taxInclusiveYn | `String` | Tax Inclusive Y/N |
| 239 | taxInvNumber | `String` | Tax Invoice No |
| 240 | taxRate | `Float` | Tax Rate |
| 241 | taxRateType | `String` | Tax Rate Type |
| 242 | tcGroup | `String` | Transaction Code Group |
| 243 | tcSubgroup | `String` | Transaction Code Subgroup |
| 244 | tclCode1 | `String` | Class1 Code. |
| 245 | tclCode2 | `String` | Class1 Code. |
| 246 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 247 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 248 | thresholdEntityType | `String` | Threshold Entity Type |
| 249 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 250 | toReservationNameId | `Float` | To Resv Name ID |
| 251 | tranActionId | `Float` | Tran Action ID |
| 252 | transactionAmount | `Float` | Transaction Amount |
| 253 | transactionDate | `Date` | Transaction Date |
| 254 | transactionFromAcct | `Float` | Trns From Account |
| 255 | transactionNumber | `Float` | Transaction Number |
| 256 | transactionNumberToDepositPosting | `Float` | Transaction Number to Deposit Posting |
| 257 | transactionToAcct | `Float` | Trns To Account |
| 258 | transactionType | `String` | Specifies the Transaction Type. Possible values: [I]nitial Invoice [N]ormal Invoice [Z]ero Invoice. |
| 259 | transcodearrangementid | `Float` | Transcodearrangementid |
| 260 | transcodeid | `String` | Transcodeid |
| 261 | trnsActivityDate | `Date` | Transaction Activity Date |
| 262 | trxCode | `String` | Transaction Code |
| 263 | trxNumberAddedBy | `Float` | Transaction No Added By |
| 264 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 265 | trxNumberAgainstPackage | `Float` | Transaction No Against Package |
| 266 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 267 | trxServiceType | `String` | Transaction Service Type |
| 268 | updateDate | `DateTime` | Update Date |
| 269 | updateUser | `Float` | Update User |
| 270 | upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| 271 | vatOffsetYn | `String` | Vat Offset Y/N |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableARLedgerDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| 2 | aSBFlag | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| 3 | aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| 4 | aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| 5 | accountCode | `Float` | Account Code |
| 6 | accountName | `String` | Account Name |
| 7 | accountNumber | `String` | Account Number |
| 8 | accountTypeFlag | `String` | Account Type Flag |
| 9 | accountid | `Float` | Accountid |
| 10 | advGenerateAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| 11 | advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| 12 | advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| 13 | advanceGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| 14 | advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| 15 | allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| 16 | amount | `Float` | Amount |
| 17 | approvalCode | `String` | Approval Code |
| 18 | approvalDate | `Date` | Approval Date |
| 19 | approvalStatus | `String` | Approval Status |
| 20 | arLedgerCredit | `Float` | AR Led Credit |
| 21 | arLedgerDebit | `Float` | AR Led Debit |
| 22 | arNumber | `Float` | AR Number |
| 23 | arState | `String` | AR State |
| 24 | arTransferDate | `Date` | AR Transfer Date |
| 25 | arrangementId | `Float` | Arrangement ID |
| 26 | articleId | `Float` | Article ID |
| 27 | associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| 28 | associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| 29 | authorizerId | `Float` | Authorizer ID |
| 30 | autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| 31 | autoSettleYn | `String` | Auto Settle Y/N |
| 32 | billNo | `Float` | Bill Number |
| 33 | bonusCheckId | `Float` | Bonus Check ID |
| 34 | bucketCode | `String` | Bucket code related to this redemption. |
| 35 | bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| 36 | businessDate | `Date` | Business Date |
| 37 | cARLedgerCredit | `Float` | Central Ar Led Credit |
| 38 | cARLedgerDebit | `Float` | Central Ar Led Debit |
| 39 | cCashierCredit | `Float` | Central Cashier Credit |
| 40 | cCashierDebit | `Float` | Central Cashier Debit |
| 41 | cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| 42 | cCcTransactionFeeAmount | `Float` | Central Cc Trx Fee Amount |
| 43 | cChangeDue | `Float` | Central Change Due |
| 44 | cContractGrossAmount | `Float` | Central Contract Gross Amount |
| 45 | cContractGuestCredit | `Float` | Central Contract Guest Credit |
| 46 | cContractGuestDebit | `Float` | Central Contract Guest Debit |
| 47 | cContractNetAmount | `Float` | Central Contract Net Amount |
| 48 | cDepLedgerCredit | `Float` | Central Dep Led Credit |
| 49 | cDepLedgerDebit | `Float` | Central Dep Led Debit |
| 50 | cExchangeDate | `Date` | Central Xchange Date |
| 51 | cExchangeRate | `Float` | Central Xchange Rate |
| 52 | cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| 53 | cGrossAmount | `Float` | Central Gross Amount |
| 54 | cGuestAccountCredit | `Float` | Central Guest Account Credit |
| 55 | cGuestAccountDebit | `Float` | Central Guest Account Debit |
| 56 | cInHouseCredit | `Float` | Central Inh Credit |
| 57 | cInHouseDebit | `Float` | Central Inh Debit |
| 58 | cNetAmount | `Float` | Central Net Amount |
| 59 | cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| 60 | cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| 61 | cPackageAllowance | `Float` | Central Package Allowance |
| 62 | cPackageCredit | `Float` | Central Package Credit |
| 63 | cPackageDebit | `Float` | Central Package Debit |
| 64 | cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| 65 | cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| 66 | cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| 67 | cParallelNetAmount | `Float` | Central Parallel Net Amount |
| 68 | cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| 69 | cPostedAmount | `Float` | Central Posted Amount |
| 70 | cPricePerUnit | `Float` | Central Price Per Unit |
| 71 | cRevenueAmount | `Float` | Central Revenue Amt |
| 72 | cTaxRate | `Float` | Central Tax Rate |
| 73 | cTransactionAmount | `Float` | Central Trx Amount |
| 74 | calcPointsYn | `String` | Indicates if points are to be calculated. |
| 75 | cashierCredit | `Float` | Cashier Credit |
| 76 | cashierDebit | `Float` | Cashier Debit |
| 77 | cashierId | `Float` | Cashier ID |
| 78 | cashierOpeningBalance | `Float` | Cashier Opening Balance |
| 79 | ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| 80 | ccTrxFeeAmount | `Float` | Fee (surcharge) amount for a credit card transaction. |
| 81 | centralARLedgerAmount | `Float` | Central AR Ledger Amount |
| 82 | changeDue | `Float` | Change Due |
| 83 | checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| 84 | chequeNumber | `String` | Cheque Number |
| 85 | closureNo | `Float` | Closure Number |
| 86 | collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| 87 | comments | `String` | Comments |
| 88 | compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| 89 | compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| 90 | compTypeCode | `String` | Comp Type Code |
| 91 | compressedYn | `String` | Compressed Y/N |
| 92 | contractCurrency | `String` | Currency code for contract currency. |
| 93 | contractGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| 94 | contractGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| 95 | contractGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| 96 | contractNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| 97 | correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| 98 | couponNo | `String` | Coupon Number |
| 99 | covers | `String` | Covers |
| 100 | currencyCode | `String` | Currency Code |
| 101 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 102 | deferredTaxesYn | `String` | Indicates whether the generated tax is because of a deferred tax generation scenario |
| 103 | deferredYn | `String` | Deferred Y/N |
| 104 | deletedFlag | `String` | Deleted Flag |
| 105 | depLedgerCredit | `Float` | Dep Ledger Credit |
| 106 | depLedgerDebit | `Float` | Dep Ledger Debit |
| 107 | depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| 108 | depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| 109 | depositTransactionId | `String` | Deposit Transaction ID |
| 110 | displayYn | `String` | Display Y/N |
| 111 | effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| 112 | electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| 113 | esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| 114 | euroExchangeRate | `Float` | Euro Exchange Rate |
| 115 | exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| 116 | exchangeDate | `Date` | Exchange Date |
| 117 | exchangeDifferenceYn | `String` | The flag indicates if it is an exchange rate difference posting when dual currency is on. |
| 118 | exchangeRate | `Float` | Exchange Rate |
| 119 | exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| 120 | expInvoiceType | `String` | Export Invoice Type |
| 121 | expOriginalInvoice | `String` | Export Original Invoice |
| 122 | extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| 123 | extTransactionId | `String` | Transaction ID from external system. |
| 124 | fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| 125 | financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| 126 | financialTransactionSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| 127 | fintransid | `Float` | Fintransid |
| 128 | fiscalBillNo | `String` | Fiscal Bill Number |
| 129 | fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| 130 | fixedChargesYn | `String` | Distinguish ordinary postings from Fixed charge postings. |
| 131 | folioNo | `Float` | Folio Number |
| 132 | folioType | `String` | Folio Type |
| 133 | folioView | `Float` | Folio View |
| 134 | folioid | `Float` | Folioid |
| 135 | foreignCurrencyID | `String` | Foreign Currency ID |
| 136 | forexCommAmount | `Float` | Foreign Exchange commission amount. |
| 137 | forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| 138 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 139 | forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| 140 | fromReservationId | `Float` | From Resv ID |
| 141 | ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| 142 | genCashierId | `Float` | General Cashier Id. |
| 143 | gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| 144 | gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| 145 | grossAmount | `Float` | Gross Amount |
| 146 | groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| 147 | guestAccountCredit | `Float` | Guest Account Credit |
| 148 | guestAccountDebit | `Float` | Debit amount on the guest account |
| 149 | holdYn | `String` | Indicates transaction is on hold. |
| 150 | hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| 151 | incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| 152 | individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| 153 | inhCredit | `Float` | In House Credit |
| 154 | inhDebit | `Float` | In House Debit |
| 155 | insertDate | `DateTime` | Insert Date |
| 156 | insertUser | `Float` | Insert User |
| 157 | installments | `Float` | Installments |
| 158 | internalCashierid | `Float` | Cashierid |
| 159 | invoiceCloseDate | `Date` | Invoice Close Date |
| 160 | invoiceNo | `Float` | Invoice Number |
| 161 | invoiceType | `String` | Invoice Type |
| 162 | jRNUpdateDate | `Date` | JRN Update Date |
| 163 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 164 | linkTrxNumber | `Float` | Link Transaction No |
| 165 | locationID | `String` | Internal ID to uniquely identify the Property |
| 166 | marketCode | `String` | Market Code |
| 167 | membershipId | `Float` | Membership ID |
| 168 | mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| 169 | nameId | `Float` | Name ID |
| 170 | nameTaxType | `String` | Name Tax Type |
| 171 | netAmount | `Float` | Net Amount |
| 172 | numberDialed | `String` | Number Dialed. |
| 173 | oTransactionDesc | `String` | Transaction Description. |
| 174 | orgBillNumber | `Float` | Stores original bill number after void. |
| 175 | orgFolioType | `String` | Stores original folio type after void. |
| 176 | orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| 177 | organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| 178 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 179 | originalReservationNameId | `Float` | Original Resv Name ID |
| 180 | originalRoom | `String` | Original Room |
| 181 | packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| 182 | packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| 183 | packageCredit | `Float` | Credit amount on the guest package account. |
| 184 | packageDebit | `Float` | Debit amount on the guest package account |
| 185 | packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| 186 | parallelCurrency | `String` | Cuurency code for parrallel currency. |
| 187 | parallelGrossAmount | `Float` | Parallel Gross Amount |
| 188 | parallelGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| 189 | parallelGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| 190 | parallelNetAmount | `Float` | Parallel Net Amount |
| 191 | passerByName | `String` | Passerby Name. |
| 192 | paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| 193 | paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| 194 | paymentType | `String` | Payment Type |
| 195 | postedAmount | `Float` | Posted Amount |
| 196 | postingDate | `Date` | Posting Date |
| 197 | postingRhythm | `String` | Posting Rhythm |
| 198 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 199 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 200 | postitNo | `Float` | Postit Number |
| 201 | postitYn | `String` | Postit Y/N |
| 202 | pricePerUnit | `Float` | Price Per Unit |
| 203 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 204 | processed8300Yn | `String` | Indicates whether this particular transaction has been included in an 8300 tax form yet. |
| 205 | product | `String` | Product |
| 206 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 207 | proformaYn | `String` | Proforma Y/N |
| 208 | property | `String` | Code to uniquely identify the Property |
| 209 | propertyBillPrefix | `String` | Property Bill Prefix |
| 210 | quantity | `Float` | Quantity |
| 211 | queueName | `String` | Queue Name |
| 212 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 213 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 214 | rateCode | `String` | Rate Code |
| 215 | reasonCode | `String` | Reason Code |
| 216 | receiptNo | `Float` | Recpt Number |
| 217 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 218 | reference | `String` | Reference |
| 219 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 220 | reservationNameId | `Float` | Resv Name ID |
| 221 | reservationid | `Float` | Reservationid |
| 222 | revenueAmt | `Float` | Revenue Amount. |
| 223 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 224 | revisionNo | `Float` | Revision Number |
| 225 | room | `String` | Room |
| 226 | roomClass | `String` | Room Class |
| 227 | roomNts | `Float` | Room Nts |
| 228 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 229 | roundFactorYn | `String` | Round Factor Y/N |
| 230 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 231 | routedYn | `String` | Indicates if the transaction has been routed. |
| 232 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 233 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| 234 | serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| 235 | serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| 236 | settlementFlag | `String` | Settlement Flag |
| 237 | sourceCode | `String` | Source Code |
| 238 | sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| 239 | splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| 240 | supplement | `String` | Supplement |
| 241 | taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| 242 | taCommissionableYn | `String` | The value 'Y' indicates that the commission has been paid for the transaction. |
| 243 | targetResort | `String` | Target Property |
| 244 | taxElements | `String` | Tax Elements |
| 245 | taxGeneratedYn | `String` | Indicates whether tax has been generated for a particuar posting. |
| 246 | taxInclusiveYn | `String` | Tax Inclusive Y/N |
| 247 | taxInvNumber | `String` | Tax Invoice No |
| 248 | taxRate | `Float` | Tax Rate |
| 249 | taxRateType | `String` | Tax Rate Type |
| 250 | tcGroup | `String` | Transaction Code Group |
| 251 | tcSubgroup | `String` | Transaction Code Subgroup |
| 252 | tclCode1 | `String` | Class1 Code. |
| 253 | tclCode2 | `String` | Class1 Code. |
| 254 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 255 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 256 | thresholdEntityType | `String` | Threshold Entity Type |
| 257 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 258 | toReservationNameId | `Float` | To Resv Name ID |
| 259 | tranActionId | `Float` | Tran Action ID |
| 260 | transactionDate | `Date` | Transaction Date |
| 261 | transactionFromAcct | `Float` | Trns From Account |
| 262 | transactionNumber | `Float` | Transaction Number |
| 263 | transactionToAcct | `Float` | Trns To Account |
| 264 | transcodearrangementid | `Float` | Transcodearrangementid |
| 265 | transcodeid | `String` | Transcodeid |
| 266 | trnsActivityDate | `Date` | Transaction Activity Date |
| 267 | trxAmount | `Float` | Transaction Amount |
| 268 | trxCode | `String` | Transaction Code |
| 269 | trxNumberAddedBy | `Float` | Transaction No Added By |
| 270 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 271 | trxNumberAgainstPackage | `Float` | Transaction No Against Package |
| 272 | trxNumberHeader | `Float` | Transaction No Header |
| 273 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 274 | trxServiceType | `String` | Transaction Service Type |
| 275 | updateDate | `DateTime` | Update Date |
| 276 | updateUser | `Float` | Update User |
| 277 | upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| 278 | vatOffsetYn | `String` | Vat Offset Y/N |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableInvoiceHeaderDetailsType

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

### ARAccountsReceivableARPostDetailsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| 2 | aRLedgerCredit | `Float` | AR Ledger Credit |
| 3 | aRLedgerDebit | `Float` | AR Ledger Debit |
| 4 | aROpen | `Float` | AR Open |
| 5 | aRTransferDate | `Date` | AR Transfer Date |
| 6 | aSBFlag | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| 7 | aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| 8 | aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| 9 | accountTypeFlag | `String` | Account Type Flag |
| 10 | accountid | `Float` | Accountid |
| 11 | adjustmentYN | `String` | Adjustment YN |
| 12 | advGenerateAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| 13 | advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| 14 | advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| 15 | advanceGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| 16 | advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| 17 | allowanceType | `String` | Distinguish "Same day" package from a next day package by storing N/S. |
| 18 | amount | `Float` | Amount |
| 19 | approvalCode | `String` | Approval Code |
| 20 | approvalDate | `Date` | Approval Date |
| 21 | approvalStatus | `String` | Approval Status |
| 22 | arNumber | `Float` | AR Number |
| 23 | arrangementId | `Float` | Arrangement ID |
| 24 | articleId | `Float` | Article ID |
| 25 | associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| 26 | associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| 27 | authorizerId | `Float` | Authorizer ID |
| 28 | autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| 29 | autoSettleYn | `String` | Auto Settle Y/N |
| 30 | billNo | `Float` | Bill Number |
| 31 | bonusCheckId | `Float` | Bonus Check ID |
| 32 | bucketCode | `String` | Bucket code related to this redemption. |
| 33 | bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| 34 | businessDate | `Date` | Business Date |
| 35 | cAropen | `Float` | Central Aropen |
| 36 | cCashierCredit | `Float` | Central Cashier Credit |
| 37 | cCashierDebit | `Float` | Central Cashier Debit |
| 38 | cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| 39 | cCcTransactionFeeAmount | `Float` | Central Cc Trx Fee Amount |
| 40 | cChangeDue | `Float` | Central Change Due |
| 41 | cContractGrossAmount | `Float` | Central Contract Gross Amount |
| 42 | cContractGuestCredit | `Float` | Central Contract Guest Credit |
| 43 | cContractGuestDebit | `Float` | Central Contract Guest Debit |
| 44 | cContractNetAmount | `Float` | Central Contract Net Amount |
| 45 | cDepLedgerCredit | `Float` | Central Dep Led Credit |
| 46 | cDepLedgerDebit | `Float` | Central Dep Led Debit |
| 47 | cExchangeDate | `Date` | Central Xchange Date |
| 48 | cExchangeRate | `Float` | Central Xchange Rate |
| 49 | cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| 50 | cGrossAmount | `Float` | Central Gross Amount |
| 51 | cGuestAccountCredit | `Float` | Central Guest Account Credit |
| 52 | cGuestAccountDebit | `Float` | Central Guest Account Debit |
| 53 | cInHouseCredit | `Float` | Central Inh Credit |
| 54 | cInHouseDebit | `Float` | Central Inh Debit |
| 55 | cNetAmount | `Float` | Central Net Amount |
| 56 | cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| 57 | cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| 58 | cPackageAllowance | `Float` | Central Package Allowance |
| 59 | cPackageCredit | `Float` | Central Package Credit |
| 60 | cPackageDebit | `Float` | Central Package Debit |
| 61 | cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| 62 | cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| 63 | cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| 64 | cParallelNetAmount | `Float` | Central Parallel Net Amount |
| 65 | cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| 66 | cPricePerUnit | `Float` | Central Price Per Unit |
| 67 | cRevenueAmount | `Float` | Central Revenue Amt |
| 68 | cTaxRate | `Float` | Central Tax Rate |
| 69 | cTransactionAmount | `Float` | Central Trx Amount |
| 70 | calcPointsYn | `String` | Indicates if points are to be calculated. |
| 71 | cashierCredit | `Float` | Cashier Credit |
| 72 | cashierDebit | `Float` | Cashier Debit |
| 73 | cashierId | `Float` | Cashier ID |
| 74 | cashierOpeningBalance | `Float` | Cashier Opening Balance |
| 75 | ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| 76 | ccTrxFeeAmount | `Float` | Fee (surcharge) amount for a credit card transaction. |
| 77 | centralARLedgerCredit | `Float` | Central AR Ledger Credit |
| 78 | centralARLedgerDebit | `Float` | Central AR Ledger Debit |
| 79 | centralAmount | `Float` | Central Amount |
| 80 | centralPaid | `Float` | Central Paid |
| 81 | centralPostedAmount | `Float` | Central Posted Amount |
| 82 | changeDue | `Float` | Change Due |
| 83 | checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| 84 | chequeNumber | `String` | Cheque Number |
| 85 | closureNo | `Float` | Closure Number |
| 86 | collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| 87 | comments | `String` | Comments |
| 88 | compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| 89 | compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| 90 | compTypeCode | `String` | Comp Type Code |
| 91 | compressedYn | `String` | Compressed Y/N |
| 92 | contractCurrency | `String` | Currency code for contract currency. |
| 93 | contractGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| 94 | contractGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| 95 | contractGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| 96 | contractNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| 97 | correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| 98 | couponNo | `String` | Coupon Number |
| 99 | covers | `String` | Covers |
| 100 | creditCardId | `Float` | Credit Card ID |
| 101 | currency | `String` | Currency |
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
| 125 | fTCompany | `String` | FT Company |
| 126 | fTFirstName | `String` | FT First Name |
| 127 | fTLastName | `String` | FT Last Name |
| 128 | fTNameType | `String` | FT Name Type |
| 129 | fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| 130 | financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| 131 | fintransid | `Float` | Fintransid |
| 132 | fiscalBillNo | `String` | Fiscal Bill Number |
| 133 | fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| 134 | fixedChargesYn | `String` | Distinguish ordinary postings from Fixed charge postings. |
| 135 | folioNo | `Float` | Folio Number |
| 136 | folioType | `String` | Folio Type |
| 137 | folioView | `Float` | Folio View |
| 138 | folioid | `Float` | Folioid |
| 139 | foreignCurrencyID | `String` | Foreign Currency ID |
| 140 | forexCommAmount | `Float` | Foreign Exchange commission amount. |
| 141 | forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| 142 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 143 | forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| 144 | fromReservationId | `Float` | From Resv ID |
| 145 | ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| 146 | ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| 147 | genCashierId | `Float` | General Cashier Id. |
| 148 | gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| 149 | gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| 150 | grossAmount | `Float` | Gross Amount |
| 151 | groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| 152 | guestAccountCredit | `Float` | Guest Account Credit |
| 153 | guestAccountDebit | `Float` | Debit amount on the guest account |
| 154 | guestname | `String` | Last Name of the guest. |
| 155 | holdYn | `String` | Indicates transaction is on hold. |
| 156 | hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| 157 | incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| 158 | inhCredit | `Float` | In House Credit |
| 159 | inhDebit | `Float` | In House Debit |
| 160 | insertDate | `DateTime` | Insert Date |
| 161 | insertUser | `Float` | Insert User |
| 162 | installments | `Float` | Installments |
| 163 | invoiceAge | `Float` | Invoice Age |
| 164 | invoiceCloseDate | `Date` | Invoice Close Date |
| 165 | invoiceNumber | `Float` | Invoice Number |
| 166 | invoiceStatus | `String` | Invoice Status |
| 167 | invoiceType | `String` | Invoice Type |
| 168 | jRNUpdateDate | `Date` | JRN Update Date |
| 169 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 170 | linkTrxNumber | `Float` | Link Transaction No |
| 171 | locationID | `String` | Internal ID to uniquely identify the Property |
| 172 | marketCode | `String` | Market Code |
| 173 | membershipId | `Float` | Membership ID |
| 174 | mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| 175 | nameId | `Float` | Name ID |
| 176 | nameTaxType | `String` | Name Tax Type |
| 177 | netAmount | `Float` | Net Amount |
| 178 | numberDialed | `String` | Number Dialed. |
| 179 | oTransactionDesc | `String` | Transaction Description. |
| 180 | orgBillNumber | `Float` | Stores original bill number after void. |
| 181 | orgFolioType | `String` | Stores original folio type after void. |
| 182 | organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| 183 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 184 | originalPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| 185 | originalReservationNameId | `Float` | Original Resv Name ID |
| 186 | originalRoom | `String` | Original Room |
| 187 | packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| 188 | packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| 189 | packageCredit | `Float` | Credit amount on the guest package account. |
| 190 | packageDebit | `Float` | Debit amount on the guest package account |
| 191 | packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| 192 | paid | `Float` | Amount paid. |
| 193 | parallelCurrency | `String` | Cuurency code for parrallel currency. |
| 194 | parallelGrossAmount | `Float` | Parallel Gross Amount |
| 195 | parallelGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| 196 | parallelGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| 197 | parallelNetAmount | `Float` | Parallel Net Amount |
| 198 | passerByName | `String` | Passerby Name. |
| 199 | paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| 200 | paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| 201 | paymentType | `String` | Payment Type |
| 202 | postDate | `Date` | Post Date |
| 203 | postedAmount | `Float` | Posted Amount |
| 204 | postingDate | `Date` | Posting Date |
| 205 | postingRhythm | `String` | Posting Rhythm |
| 206 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 207 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 208 | postitNo | `Float` | Postit Number |
| 209 | postitYn | `String` | Postit Y/N |
| 210 | pricePerUnit | `Float` | Price Per Unit |
| 211 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 212 | processed8300Yn | `String` | Indicates whether this particular transaction has been included in an 8300 tax form yet. |
| 213 | product | `String` | Product |
| 214 | profileID | `Float` | Profile ID |
| 215 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 216 | proformaYn | `String` | Proforma Y/N |
| 217 | property | `String` | Code to uniquely identify the Property |
| 218 | propertyBillPrefix | `String` | Property Bill Prefix |
| 219 | quantity | `Float` | Quantity |
| 220 | queueName | `String` | Queue Name |
| 221 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 222 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 223 | rateCode | `String` | Rate Code |
| 224 | reasonCode | `String` | Reason Code |
| 225 | receiptNo | `Float` | Recpt Number |
| 226 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 227 | recordType | `String` | Record Type |
| 228 | reference | `String` | Reference |
| 229 | repGuestname | `String` | Reporting Guestname |
| 230 | reportingTransactionCodeDesc | `String` | ReportingTransaction Code Desc |
| 231 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 232 | reservationFirstName | `String` | Reservation First Name |
| 233 | reservationNameId | `Float` | Resv Name ID |
| 234 | reservationid | `Float` | Reservationid |
| 235 | resevationLastName | `String` | Resevation Last Name |
| 236 | revenueAmt | `Float` | Revenue Amount. |
| 237 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 238 | revisionNo | `Float` | Revision Number |
| 239 | room | `String` | Room |
| 240 | roomClass | `String` | Room Class |
| 241 | roomNts | `Float` | Room Nts |
| 242 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 243 | roomid | `String` | Roomid |
| 244 | roundFactorYn | `String` | Round Factor Y/N |
| 245 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 246 | routedYn | `String` | Indicates if the transaction has been routed. |
| 247 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 248 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| 249 | serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| 250 | serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| 251 | settlementFlag | `String` | Settlement Flag |
| 252 | sourceCode | `String` | Source Code |
| 253 | sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| 254 | splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| 255 | supplement | `String` | Supplement |
| 256 | taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| 257 | taCommissionableYn | `String` | The value 'Y' indicates that the commission has been paid for the transaction. |
| 258 | targetResort | `String` | Target Property |
| 259 | taxElements | `String` | Tax Elements |
| 260 | taxGeneratedYn | `String` | Indicates whether tax has been generated for a particuar posting. |
| 261 | taxInclusiveYn | `String` | Tax Inclusive Y/N |
| 262 | taxInvNumber | `String` | Tax Invoice No |
| 263 | taxRate | `Float` | Tax Rate |
| 264 | taxRateType | `String` | Tax Rate Type |
| 265 | tcGroup | `String` | Transaction Code Group |
| 266 | tcSubgroup | `String` | Transaction Code Subgroup |
| 267 | tclCode1 | `String` | Class1 Code. |
| 268 | tclCode2 | `String` | Class1 Code. |
| 269 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 270 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 271 | thresholdEntityType | `String` | Threshold Entity Type |
| 272 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 273 | toReservationNameId | `Float` | To Resv Name ID |
| 274 | tranActionId | `Float` | Tran Action ID |
| 275 | transactionCodeDesc | `String` | Transaction Code desc |
| 276 | transactionFromAcct | `Float` | Trns From Account |
| 277 | transactionNumber | `Float` | Transaction Number |
| 278 | transactionToAcct | `Float` | Trns To Account |
| 279 | transcodearrangementid | `Float` | Transcodearrangementid |
| 280 | transcodeid | `String` | Transcodeid |
| 281 | trnsActivityDate | `Date` | Transaction Activity Date |
| 282 | trxAmount | `Float` | Transaction Amount |
| 283 | trxCode | `String` | Transaction Code |
| 284 | trxNumberAddedBy | `Float` | Transaction No Added By |
| 285 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 286 | trxNumberAgainstPackage | `Float` | Transaction No Against Package |
| 287 | trxNumberHeader | `Float` | Transaction No Header |
| 288 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 289 | trxServiceType | `String` | Transaction Service Type |
| 290 | updateDate | `DateTime` | Update Date |
| 291 | updateUser | `Float` | Update User |
| 292 | upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| 293 | vatOffsetYn | `String` | Vat Offset Y/N |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableAccountTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountType | `String` | Account Type |
| 2 | accountTypeDescription | `String` | Account Type Description |
| 3 | accountTypeId | `Float` | Account Type ID |
| 4 | agingDelayDays | `Float` | Stores the aging delay in days which is used by the ar_unpaid report. |
| 5 | centralAccountType | `String` | Central Account Type |
| 6 | centralAccountTypeDescription | `String` | Central Account Type Description |
| 7 | centralCreditLimit | `Float` | Central Credit Limit |
| 8 | centralFinanceChargeAmount | `Float` | Central Finance Charge Amount |
| 9 | centralXchangeDate | `Date` | Central Exchange Date |
| 10 | centralXchangeRate | `Float` | Central Exchange Rate |
| 11 | chargesOlderThanNDays | `Float` | Min Number of days to consider older invoices for the account to post finance charges. |
| 12 | creditLimit | `Float` | Credit Limit |
| 13 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 14 | deletedflag | `String` | Deleted Flag |
| 15 | financeChargeAmount | `Float` | Amount or Fee to charge to the Account for overdue invoices. |
| 16 | financeChargePercentage | `Float` | Percentage to apply to the sum of older invoices. |
| 17 | inactiveflag | `String` | Inactive Flag |
| 18 | includeUnallocatedPaymentsYN | `String` | Used to include unallocated payments in the calculation of the finance charges. |
| 19 | insertDate | `DateTime` | Insert Date |
| 20 | insertUser | `Float` | Insert User |
| 21 | internalAccounttypeid | `Float` | Accounttypeid |
| 22 | jRNUpdateDate | `Date` | JRN Update Date |
| 23 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 24 | letterNameEndOfMonth | `String` | Letter name that is send every end of month when the Reminder Cycle is set to [E]nd of Month. |
| 25 | locationID | `String` | Internal ID to uniquely identify the Property |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | ownerCashbookReport | `String` | Name of the owner cashbook report to be given to auditors. |
| 28 | ownerStatementName | `String` | Name of the owner statement report that needs to be send to the owner of the unit. |
| 29 | ownerSummary | `String` | Name of the owner summary report that needs to be send to the owner of the unit. |
| 30 | postOnDay | `Float` | Day of the month when Night Audit will check for older invoices to post finance charges onto a new invoice. |
| 31 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 32 | printInvoiceDetailsYn | `String` | Print Invoice Details on Statements Y/N. |
| 33 | printInvoicesWithDetailsYN | `String` | Print Invoices With Details YN |
| 34 | printInvoicesWithoutDetailsYN | `String` | Print Invoices Without Details YN |
| 35 | printSeperateFoliosYN | `String` | Print Seperate Folios YN |
| 36 | property | `String` | Property |
| 37 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 38 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 39 | reminderCycle | `String` | Indicates if the Reminder Cycle generation is based on calendar [D]ays or [E]nd of Month. |
| 40 | repItem | `String` | Reporting Item |
| 41 | repItemName | `String` | Reporting Item Name |
| 42 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 43 | statementMode | `String` | Indicates if the Account Type will utilize the '(B)alance Brought Forward? single line or '(I)ndividual Open Items?  when generating statements. |
| 44 | statementName | `String` | Name of the statement that needs to be sent to the account. |
| 45 | statementNameDescription | `String` | Statement Name Description |
| 46 | updateDate | `DateTime` | Update Date |
| 47 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableAcctFlagReasonDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | acctflagreasonid | `String` | Acctflagreasonid |
| 2 | centralFlaggedReasonCode | `String` | Central Flagged Reason Code |
| 3 | centralRestrictedReasonDescription | `String` | Central Restricted Reason Description |
| 4 | centralSequence | `Float` | Central Sequence |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedflag | `String` | Deleted Flag |
| 7 | flaggedReasonCode | `String` | Flagged Reason Code |
| 8 | inactiveflag | `String` | Inactive Flag |
| 9 | insertDate | `DateTime` | Insert Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | locationID | `String` | Internal ID to uniquely identify the Property |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | property | `String` | Property |
| 17 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 18 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 19 | repItem | `String` | Reporting Item |
| 20 | repItemName | `String` | Reporting Item Name |
| 21 | repItemOrderby | `Float` | Reporting Item Orderby |
| 22 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 23 | restrictedReasonDescription | `String` | Restricted Reason Description |
| 24 | sequence | `Float` | Sequence |
| 25 | updateDate | `DateTime` | Update Date |
| 26 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableEmployeeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accessConfig | `String` | Allow user access to Configuration. |
| 2 | accessEod | `String` | Allow user access to End of Day. |
| 3 | accessObi | `String` | Allow user access to Opera BI. |
| 4 | accessOcis | `String` | Allow user access to OCIS. |
| 5 | accessOcm | `String` | Allow user access to Channel Mangement. |
| 6 | accessOcrm | `String` | Allow user access to OCRM. |
| 7 | accessOrms | `String` | Allow user access to Opera Revenue Management System. |
| 8 | accessOrs | `String` | Allow user access to ORS. |
| 9 | accessOxi | `String` | Allow user access to OXI. |
| 10 | accessOxihub | `String` | Allow user access to OXIHUB. |
| 11 | accessPms | `String` | Allow user access to PMS. |
| 12 | accessSc | `String` | Allow user access to SC. |
| 13 | accessScbi | `String` | Allow user access to OPERA S&C Analytics. |
| 14 | accessSfa | `String` | Allow user access to SFA. |
| 15 | accessUtil | `String` | Allow user access to Utilities. |
| 16 | accountLockedOutYn | `String` | Indicates if user is allowed to login in the application. |
| 17 | agent | `String` | Agent |
| 18 | appUserType | `String` | Defines the type of user.Valid values: U and G U-->User :: G-->Group |
| 19 | authorizerInactiveDate | `DateTime` | Date the authorizer became inactive |
| 20 | authorizerRateCode | `String` | Default rate code for this authorizer. |
| 21 | authorizerYn | `String` | Denotes if this user is an authorizer. Allowable values are 'Y' and 'N' |
| 22 | birthDate | `Date` | Birth Date |
| 23 | businessTitle | `String` | Business Title |
| 24 | businessTitleDescription | `String` | Business Title Description |
| 25 | cExchangeDate | `Date` | Central Xchange Date |
| 26 | cExchangeRate | `Float` | Central Xchange Rate |
| 27 | cHourlyRate | `Float` | Central Hourly Rate |
| 28 | cWeeklySalary | `Float` | Central Weekly Salary |
| 29 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 30 | dateHired | `Date` | Date employee was hired |
| 31 | defCashierId | `Float` | Cashier ID for the User |
| 32 | defaultForm | `String` | Not Used |
| 33 | defaultMfnResort | `String` | Not used. |
| 34 | defaultReportgroup | `String` | Defaults the Report Module to this Report Group |
| 35 | defaultResort | `String` | Stores resort name to which user will log in every time |
| 36 | deletedflag | `String` | Deleted Flag |
| 37 | departmentid | `String` | Departmentid |
| 38 | deptEmail | `String` | Department E-Mail Address. |
| 39 | deptId | `String` | Dept ID |
| 40 | deptManagerPager | `String` | Pager number of department manager |
| 41 | deptName | `String` | Description of the department |
| 42 | deptOrderBy | `Float` | Dept Order By |
| 43 | disabledUntil | `Date` | When account is disabled this date is set to date when account should be enabled again |
| 44 | eMail | `String` | E Mail |
| 45 | empExtension | `String` | Employee Extension Number |
| 46 | empStatus | `String` | Emp Status |
| 47 | employeeIncentiveNumber | `String` | Identifies a hotel employee for incentive programs. |
| 48 | employeeNumber | `String` | This column is used by Starwood Hotels for Storing their internal employee number |
| 49 | employeeid | `Float` | Employeeid |
| 50 | expiresOn | `Date` | Date on which user ID will be disabled. |
| 51 | first | `String` | First |
| 52 | forcePasswordChangeYn | `String` | Requires the user to change the password at login. |
| 53 | fridayMax | `Float` | Max hours for Friday |
| 54 | fridayMin | `Float` | Min hours for Friday |
| 55 | generalFilepath | `String` | Stores General File path for Mailmerge |
| 56 | graceLogin | `Float` | Number of Logins allowed after password has expired |
| 57 | hireType | `String` | Type of hire: F-Full Time P-Part Time |
| 58 | hourlyRate | `Float` | If RATE_TYPE=H: hourly employee rate |
| 59 | hoursPerWeek | `Float` | Hours Per Week |
| 60 | inactiveDesc | `String` | Inactive Description |
| 61 | inactiveFrom | `Date` | Inactive Start Date |
| 62 | inactiveReasonCode | `String` | Reason Code for inactive status from REASON table |
| 63 | inactiveTo | `Date` | Inactive End Date |
| 64 | inactiveflag | `String` | Inactive Flag |
| 65 | insertDate | `DateTime` | Insert Date |
| 66 | insertUser | `Float` | Insert User |
| 67 | jRNUpdateDate | `Date` | JRN Update Date |
| 68 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 69 | laptopId | `Float` | Laptop ID |
| 70 | last | `String` | Last |
| 71 | leadAddress | `String` | Lead Address Code determines primary receipient |
| 72 | leadAddressDet | `String` | Lead Address (email/fax no) |
| 73 | leadComm | `String` | Lead Communication Type |
| 74 | locationID | `String` | Internal ID to uniquely identify the Property |
| 75 | lockoutDate | `DateTime` | Timestamp with the useraccount was locked out. |
| 76 | loginCro | `String` | Login Cro |
| 77 | loginDomain | `String` | Login Domain |
| 78 | maleFemale | `String` | Employee Gender |
| 79 | maxCheckoutDays | `Float` | Maximum number of days allowed for checkout in Laptop Module |
| 80 | maxUserSessions | `Float` | Maximum number of Opera Sessions allowed at single point of time. |
| 81 | mfnUserType | `String` | User type for OCM mode: [C]orporate User |
| 82 | middle | `String` | Middle |
| 83 | mobileAlertsYn | `String` | Indiciates if alerts are send to mobile registered guests for required action and manual checkout.. |
| 84 | mondayMax | `Float` | Max hours for Monday |
| 85 | mondayMin | `Float` | Min hours for Monday |
| 86 | nameNotes | `String` | Name Notes |
| 87 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 88 | otMultiplier | `Float` | Overtime Multiplier |
| 89 | passwordChangeDays | `Float` | Period of Days the Password expires |
| 90 | passwordLastChange | `Date` | TimeStamp of last Password Change |
| 91 | personNameId | `Float` | Foreign key to NAME table that links this USER to an Employee |
| 92 | phoneNo | `String` | Phone no. |
| 93 | phoneNumber | `String` | Phone Number |
| 94 | preventAccountLockout | `String` | Indicates if this user can be excluded from user account lock. |
| 95 | primaryBlockOwnerName | `String` | Primary Block Owner Name |
| 96 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 97 | primaryRoomsOwnerCode | `String` | Primary Rooms Owner Code |
| 98 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 99 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 100 | rateType | `String` | Rate Type |
| 101 | receiveBroadcastMsg | `String` | Receive Broadcast Msg |
| 102 | rehireYn | `String` | Indicates if a terminated employee shall be rehired |
| 103 | salaryInterval | `String` | Salary Interval: M-Monthly W-Weekly |
| 104 | saturdayMax | `Float` | Max hours for Saturday |
| 105 | saturdayMin | `Float` | Min hours for Saturday |
| 106 | serviceRequestAlertsYn | `String` | Indicates if this Application User can receive Alerts related to Service Requests. |
| 107 | sfaName | `String` | Sfa Name |
| 108 | srepGroup | `String` | Assigned Sales Manager Group(s) |
| 109 | sundayMax | `Float` | Max hours for Sunday |
| 110 | sundayMin | `Float` | Min hours for Sunday |
| 111 | termReason | `String` | Termination Reason |
| 112 | terminatedDate | `Date` | Termination Date |
| 113 | territory | `String` | Territory |
| 114 | thursdayMax | `Float` | Max hours for Thursday |
| 115 | thursdayMin | `Float` | Min hours for Thursday |
| 116 | timezoneRegion | `String` | Time zone region selected by the employee. |
| 117 | tuesdayMax | `Float` | Max hours for Tuesday |
| 118 | tuesdayMin | `Float` | Min hours for Tuesday |
| 119 | updateDate | `DateTime` | Update Date |
| 120 | updateUser | `Float` | Update User |
| 121 | userFilepath | `String` | Store User File path. for Mailmerge |
| 122 | userID | `Float` | User ID |
| 123 | userPbxId | `Float` | PBX ID - referred as password to access PBX system |
| 124 | wednesdayMax | `Float` | Max hours for Wednesday |
| 125 | wednesdayMin | `Float` | Min hours for Wednesday |
| 126 | weekMax | `Float` | Maximum total hours this employee can work per week |
| 127 | weekMin | `Float` | Minimum total hours this employee can work per week |
| 128 | weeklySalary | `Float` | Weekly Salary |
| 129 | workPermitExpdate | `Date` | Workpermit Expiration date |
| 130 | workPermitNo | `String` | Working Permit Number |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableAccountNoteDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountCode | `Float` | Account Code |
| 2 | accountid | `Float` | Accountid |
| 3 | accountnoteid | `Float` | Accountnoteid |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedflag | `String` | Deleted Flag |
| 6 | inactiveflag | `String` | Inactive Flag |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | internalflag | `String` | Internalflag |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | locationID | `String` | Internal ID to uniquely identify the Property |
| 13 | noteCode | `String` | Note Code |
| 14 | noteDetails | `String` | Note Details |
| 15 | noteId | `Float` | Note ID |
| 16 | noteTitle | `String` | Note Title |
| 17 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 18 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 19 | property | `String` | Code to uniquely identify the Property |
| 20 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 21 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 22 | updateDate | `DateTime` | Update Date |
| 23 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ARAccountsReceivableProfileAllInformationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | guestProfileID | `Float` | The primary key for this table. |
| 2 | aRNumber | `String` | Account number. |
| 3 | aRNumberCentral | `String` | Account Receivable No. of this profile. |
| 4 | aRCreditLimitYN | `String` | Indicates if a Credit Limit amount on Profile level will be required. |
| 5 | aRCMailFlag | `String` | The ARC mailing flag (received from ARC Update program) |
| 6 | aRCOfficeType | `String` | The ARC office type (received from ARC Update program) |
| 7 | aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| 8 | accountBillingContact | `String` | Billing contact person in company. |
| 9 | accountSource | `String` | Used in S&C Module. |
| 10 | accountType | `String` | Account Type of this Profile |
| 11 | accountTypeDescription | `String` | The description of this value. |
| 12 | accountsourceDesc | `String` | The description of this value. |
| 13 | actionCode | `String` | Mailing action codes. |
| 14 | activeYN | `String` | Profile is active or not. |
| 15 | address1 | `String` | The first line of street address. |
| 16 | address2 | `String` | The second line of street address. |
| 17 | address3 | `String` | The third line of street address. |
| 18 | address4 | `String` | The fourth line of street address. |
| 19 | addressId | `Float` | The primary key for this table. |
| 20 | addressLangCodeDesc | `String` | Description for each language code. |
| 21 | addressLanguageCode | `String` | Address Language Code |
| 22 | addressType | `String` | The type of address. |
| 23 | alienRegistrationNo | `String` | Country Specific Requirement for Nigeria. |
| 24 | allResorts | `String` | All Resorts |
| 25 | alternateEnvelopeGreeting | `String` | Field which stores the multibyte envelop greeting used in S&C |
| 26 | alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| 27 | alternateLanguageDescription | `String` | Description for each language code. |
| 28 | alternateSalutation | `String` | Alternate Salutation |
| 29 | autoEnrollMemberYN | `String` | Auto-Enroll Member YN |
| 30 | availabilityOverride | `String` | Does profile have Availability Override Y/N |
| 31 | billingCode | `String` | The billing code for this name record. |
| 32 | billingInstruction | `String` | Billing Instruction |
| 33 | billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| 34 | birthCountry | `String` | Country of Birth |
| 35 | birthDate | `Date` | Date of Birth of the Individual Profiles. |
| 36 | birthDateStr | `String` | Stores the encrypted birth date. |
| 37 | birthPlace | `String` | Place of Birth |
| 38 | blMsg | `String` | Any Message for the Restricted profile. |
| 39 | businessSegment | `String` | Used in S&C Module. |
| 40 | businessSegmentDescription | `String` | The description of this value. |
| 41 | businessTitle | `String` | The business title for this individual. |
| 42 | cExchangeDate | `Date` | Central Xchange Date |
| 43 | cExchangeRate | `Float` | Central Xchange Rate |
| 44 | cProfileCreditLimit | `Float` | Central Profile Credit Limit |
| 45 | cRSNameid | `Float` | This is a  name_id (Profile number) of profiles that exist in a Central database in a typical CRS environment. |
| 46 | ccProfileYn | `String` | This field tells whether this profile is a credit card profile or not. |
| 47 | centralAccountType | `String` | Central Account Type |
| 48 | centralBusinessSegment | `String` | Central Business Segment |
| 49 | centralBusinessSegmentDescription | `String` | Central Business Segment Description |
| 50 | centralCorporateIDType | `String` | Central Corporate ID Type |
| 51 | centralDefaultKeyword | `String` | The keyword to search on. |
| 52 | centralGuestTitleCode | `String` | Central Guest Title Code |
| 53 | centralInactiveReason | `String` | Central Inactive Reason |
| 54 | centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| 55 | centralMailActionDescription | `String` | Central Mail Action Description |
| 56 | centralMailingActionCode | `String` | Central Mailing Action Code |
| 57 | centralPriority | `String` | Central Priority |
| 58 | centralStateCode | `String` | Central State Code |
| 59 | centralTerritory | `String` | Central Territory |
| 60 | centralVIPCode | `String` | Central VIP Code |
| 61 | centralVIPDescription | `String` | Central VIP Description |
| 62 | chainCode | `String` | Chain Code |
| 63 | city | `String` | The city for this address. |
| 64 | clientID | `String` | The unique key of this name stores IATA# Company # etc. |
| 65 | collectionUserId | `Float` | The user that has been assigned to this account for collections. |
| 66 | combinedName | `String` | Combined Name |
| 67 | commPayCentral | `String` | This flag will be used in case Profiles are being controlled Centrally (CRS). |
| 68 | comments | `String` | Not Used. |
| 69 | commissionCode | `String` | Commission Code for the Commission Percentage. |
| 70 | commissionCodes | `String` | Code for the commission for Travel Agent |
| 71 | commissionCurrencyId | `String` | Comm Curr ID |
| 72 | commissionid | `String` | Commission Code for the Commission Percentage. |
| 73 | communicationRole1 | `String` | Role in which this phone type belongs to. |
| 74 | communicationRole2 | `String` | Role in which this phone type belongs to. |
| 75 | communicationRole3 | `String` | Role in which this phone type belongs to. |
| 76 | communicationType1 | `String` | The type of this phone number. |
| 77 | communicationType2 | `String` | The type of this phone number. |
| 78 | communicationType3 | `String` | The type of this phone number. |
| 79 | communicationValue1 | `String` | The phone number for this record |
| 80 | communicationValue2 | `String` | The phone number for this record |
| 81 | communicationValue3 | `String` | The phone number for this record |
| 82 | companyAlternate | `String` | Extended Byte Company Name |
| 83 | companyGroupId | `String` | The company group or company group user ID in hierarchical format |
| 84 | companyNameId | `Float` | Not used. |
| 85 | competition | `String` | Competaion code . |
| 86 | competitionDesc | `String` | The description of this value. |
| 87 | contactYN | `String` | Used in S&C Module. |
| 88 | contractNo | `String` | Group Contract number. |
| 89 | contractRecvDate | `Date` | The date the group contract was received. |
| 90 | corpTypeDesc | `String` | Corp Type Description |
| 91 | corporateIDType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| 92 | country | `String` | Country name. |
| 93 | countryCode | `String` | Country . |
| 94 | createdByUser | `String` | The user that created the record |
| 95 | createdOnDate | `DateTime` | The date the record was created |
| 96 | creditRating | `String` | Credit rating. |
| 97 | currencyCode | `String` | Currency Code |
| 98 | currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| 99 | dOptInAutoenrollMemberFlg | `String` | Double Opt In for  AUTOENROLL_MEMBER_YN |
| 100 | dOptInEmailFlg | `String` | Double Opt In for  EMAIL_YN |
| 101 | dOptInGuestPrivFlg | `String` | Double Opt In for  GUEST_PRIV_YN |
| 102 | dOptInMailListFlg | `String` | Double Opt In for  MAIL_LIST |
| 103 | dOptInMarketResearchFlg | `String` | Double Opt In for  MARKET_RESEARCH_YN |
| 104 | dOptInPhoneFlg | `String` | Double Opt In for  PHONE_YN |
| 105 | dOptInSmsFlg | `String` | Double Opt In for  SMS_YN |
| 106 | dOptInThirdPartyFlg | `String` | Double Opt In for  THIRD_PARTY_YN |
| 107 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 108 | debtorName | `String` | Debtor Name |
| 109 | decimalPositions | `Float` | The number of digits after the decimal to allow for this currency. |
| 110 | defaultKeyword | `String` | The keyword to search on. |
| 111 | deletedFlag | `String` | Deleted Flag |
| 112 | department | `String` | Used in S&C Module. |
| 113 | deptId | `String` | Used in S&C Module. |
| 114 | description | `String` | Used in QMS Module |
| 115 | directBillBatchType | `String` | Direct Bill Batch Type |
| 116 | displayName | `String` | Display Name |
| 117 | downloadDate | `Date` | Date on which the record is downloaded to laptop. |
| 118 | downloadResort | `String` | REsort name which has downloaded on the laptop. |
| 119 | downloadSrep | `Float` | Owner of the record who downloaded on to laptop. |
| 120 | eInvLiableLastUpdated | `DateTime` | The date when the E-Invoice liable flag was updated for this profile. |
| 121 | eInvoiceLiableYn | `String` | Turkey Country requirement: Indicated if this profile e-Invoice liable. Folios generated for this profile will be directly sent to an external system. |
| 122 | email | `String` | The phone number for this record |
| 123 | emailYN | `String` | Email YN |
| 124 | envelopeGreeting | `String` | Field which stores the envelop greeting used in S&C |
| 125 | externalDisplayName | `String` | External Display Name |
| 126 | externalFirstName | `String` | The first name of an individual. |
| 127 | externalId | `String` | External ID used for V6 Interface stores the PMS guest number |
| 128 | externalName | `String` | The last name of the individual profile. |
| 129 | externalReferenceRequ | `String` | Not Used. |
| 130 | externalReferenceRequired | `String` | During the booking process is the user required to enter the tour operator or TA record locator. |
| 131 | fMembershipCardNumbers | `String` | Membership Card Number. |
| 132 | fMembershipClassDesc | `String` | Descripion of membership class |
| 133 | fMembershipClasses | `String` | F Membership Classes |
| 134 | fMembershipCodes | `String` | F Membership Codes |
| 135 | fMembershipDescriptions | `String` | F Membership Descriptions |
| 136 | fMembershipIds | `String` | Primary Key for this table. |
| 137 | fMembershipType | `String` | Type of the Membership. |
| 138 | fSubscriptionDb | `String` | The ID of the external Database. |
| 139 | fSubscriptionYn | `String` | The ID of the external Database. |
| 140 | faxNumber | `String` | The phone number for this record |
| 141 | firstName | `String` | The first name of an individual name. |
| 142 | firstNameAlternate | `String` | First Name Alternate |
| 143 | firstNameIncognito | `String` | The keyword to search on. |
| 144 | followOn | `String` | The follow on for this individual (I.E: III etc). |
| 145 | gDSName | `String` | The name as communicated from the GDS. system.  Filled on names that are created during the booking. |
| 146 | gDSTransactionNo | `String` | Not used. |
| 147 | gender | `String` | Indicates gender of Individual profile. Either (M)ale or F(emale) |
| 148 | geographicRegion | `String` | Not used. |
| 149 | guestClassification | `String` | Not used. |
| 150 | guestCountry | `String` | Country name. |
| 151 | guestCurrencyCode | `String` | Currency code for the Commission payment. |
| 152 | guestLanguageCode | `String` | Description for each language code. |
| 153 | guestLastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| 154 | guestMiddleName | `String` | The middle name of this individual. |
| 155 | guestNameSuffix | `String` | Guest Name Suffix |
| 156 | guestPrivilegeYN | `String` | Guest Privilege YN |
| 157 | guestTitleCode | `String` | The title of the individual. |
| 158 | hasRequestedMailYN | `String` | Has Requested Mail YN |
| 159 | historyYN | `String` | Keep guest in history Y/N |
| 160 | holdCode | `String` | Hold code for the Commission handling purposes. |
| 161 | iataConsortia | `String` | Consortia for the IATA number. |
| 162 | idCountry | `String` | The country where ID was issued |
| 163 | idDate | `Date` | Issued date of Identification |
| 164 | idDocumentAttachId | `Float` | This will store the value of LINKED_ATTACHMENTS.ATTACH_ID (Which maps to the physical table WORK_ORDERS.WO_NUMBER) |
| 165 | idPlace | `String` | The place where ID was issued |
| 166 | idType | `String` | Identification Type. Eg Passport Driving License etc |
| 167 | immigrationStatus | `String` | Country Specific Requirement for Nigeria. |
| 168 | inactiveDate | `DateTime` | The date the record was marked as inactive |
| 169 | inactiveFlag | `String` | Inactive Flag |
| 170 | inactiveReason | `String` | Reason why record was inactivated. |
| 171 | inactiveReasonDescription | `String` | The description of this value. |
| 172 | includeInTax1099Yn | `String` | Include travel agents/sources profile in 1099 reporting ?Y/N |
| 173 | indexName | `String` | Index Name |
| 174 | industryCode | `String` | The Industry this profile belongs to. Used only for the Non-Individual Profiles. |
| 175 | industryDesc | `String` | The description of this value. |
| 176 | influence | `String` | Used in S&C Module. |
| 177 | influenceDesc | `String` | The description of this value. |
| 178 | interest | `String` | Interest Code. |
| 179 | internalBillYn | `String` | Indicates that this profile should be generating an internal bill instead of a regular bill during settlement. |
| 180 | internalDeletedflag | `String` | Deleted Flag |
| 181 | internalInactiveflag | `String` | Inactive Flag |
| 182 | internalOrganizationId | `Float` | Organization ID |
| 183 | jRNUpdateDate | `Date` | JRN Update Date |
| 184 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 185 | languageCode | `String` | Primary language used for the profile. |
| 186 | laptopChange | `Float` | Code to synchronize to Laptop values are 012. |
| 187 | lastGroup | `String` | Last Group |
| 188 | lastNameAlternate | `String` | Last Name Alternate |
| 189 | lastNameIncognito | `String` | The keyword to search on. |
| 190 | lastRate | `Float` | Last Rate |
| 191 | lastRateCode | `String` | Last Rate Code |
| 192 | lastRoom | `String` | The room that is booked for this reservation leg. |
| 193 | lastRoomProperty | `String` | Last Room Property |
| 194 | lastSource | `String` | Last Source |
| 195 | lastStay | `Date` | This contains the truncated component of end_date (i.e without timecomponent) |
| 196 | lastUpdatedResort | `String` | Last property that updated this record. |
| 197 | legalCompany | `String` | The legal company name for this company. |
| 198 | letterGreeting | `String` | Used in S&C Module. |
| 199 | mailActionDescription | `String` | The description of this value. |
| 200 | mailList | `String` | This indicates whether the mailing list must be sent to the guest. |
| 201 | mailType | `String` | The type of mail this user should be sent. |
| 202 | mailingActionCode | `String` | Mailing action codes. |
| 203 | marketResearchYN | `String` | Market Research YN |
| 204 | masterAccountYn | `String` | Is this account a master account (Y/N)? |
| 205 | nameTaxType | `String` | Not used. |
| 206 | nameType | `String` | The type of Profile. |
| 207 | nameTypeDescription | `String` | The description of this value. |
| 208 | name2 | `String` | Not Used. |
| 209 | name3 | `String` | Not used. |
| 210 | nationality | `String` | Nationality |
| 211 | nationalityCode | `String` | Nationality of the individual. |
| 212 | negotiatedRateCodes | `String` | The rate code for which this record applies. |
| 213 | nextStay | `Date` | This is a begin_date  with no  time component. |
| 214 | nickname | `String` | The nickname of this individual. |
| 215 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 216 | origNameId | `Float` | Stores the original NAME_ID prior to a migration. |
| 217 | paymentDueDays | `Float` | Number of days a payment is due for the account. |
| 218 | phone | `String` | The phone number for this record |
| 219 | phoneWeb | `String` | The phone number for this record |
| 220 | phoneYN | `String` | Phone YN |
| 221 | postalCode | `String` | The postal code of this address. |
| 222 | postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| 223 | preferredRoomNo | `String` | Preferred Room Number |
| 224 | primaryAddressId | `Float` | Not used. |
| 225 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 226 | primaryNameId | `Float` | Not Used. |
| 227 | primaryOwner | `String` | Primary Owner |
| 228 | primaryOwnerCode | `String` | Primary Owner Code |
| 229 | primaryPhoneId | `Float` | Not used. |
| 230 | priority | `String` | Priority of the account |
| 231 | priorityDesc | `String` | The description of this value. |
| 232 | privacyFlagYN | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| 233 | productInterest | `String` | Preference Code. Part of the Primary Key. |
| 234 | profession | `String` | The profession of the Individual |
| 235 | profileCreditLimit | `Float` | Credit Limit amount for all AR accounts created in different properties for this profile. |
| 236 | profileId | `Float` | The primary key for this table. |
| 237 | profileType | `String` | The type of Profile. |
| 238 | propertyRegistered | `String` | Resort for which Job is registered. |
| 239 | protected | `String` | Protected |
| 240 | psuedoProfileYn | `String` | Psuedo Profile Y/N |
| 241 | rateStructure | `String` | The default rate structure for this name. |
| 242 | region | `String` | The region for this name. |
| 243 | regionid | `String` | The region for this name. |
| 244 | repAccountTypeDescription | `String` | Reporting Account Type Description |
| 245 | repAccountsource | `String` | Reporting Accountsource |
| 246 | repAccountsourceDescription | `String` | Reporting Accountsource Desc |
| 247 | repCompetitionCode | `String` | Reporting Competition Code |
| 248 | repCompetitionDescription | `String` | Reporting Competition Desc |
| 249 | repCorpTypeDescription | `String` | Reporting Corp Type Desc |
| 250 | repIndustryCode | `String` | Reporting Industry Code |
| 251 | repIndustryDescription | `String` | Reporting Industry Desc |
| 252 | repInfluence | `String` | Reporting Influence |
| 253 | repInfluenceDescription | `String` | Reporting Influence Desc |
| 254 | repNameType | `String` | Reporting Name Type |
| 255 | repNameTypeDescription | `String` | Reporting Name Type Description |
| 256 | repNationalityCode | `String` | Rep Nationality Code |
| 257 | repNationalityDescription | `String` | Rep Nationality Description |
| 258 | repPriorityDescription | `String` | Reporting Priority Desc |
| 259 | repRoomsPotential | `String` | Reporting Rooms Potential |
| 260 | repRoomsPotentialDescription | `String` | Reporting Rooms Potential Desc |
| 261 | repScope | `String` | Reporting Scope |
| 262 | repScopeCity | `String` | Reporting Scope City |
| 263 | repScopeCityDescription | `String` | Reporting Scope City Desc |
| 264 | repScopeDescription | `String` | Reporting Scope Desc |
| 265 | repStateDescription | `String` | Reporting State Desc |
| 266 | repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| 267 | repTerritoryDescription | `String` | Reporting Territory Desc |
| 268 | repTitleName | `String` | Reporting Title Name |
| 269 | repeatGuestId | `String` | The primary membership # for this guest. |
| 270 | replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| 271 | requestType | `String` | This column store the Name of the Company Profiles. |
| 272 | restricted | `String` | Normal Restricted and Cash Only informations are stored in this column. |
| 273 | restrictedRule | `String` | The description of this value. |
| 274 | resvContact | `String` | Reservation Contact person. |
| 275 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 276 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 277 | roomsPotential | `String` | Potential no of rooms per year for a account |
| 278 | roomsPotentialDesc | `String` | The description of this value. |
| 279 | sMSYN | `String` | Use this alert to text a notification. |
| 280 | salutation | `String` | Salutation Greeting |
| 281 | scope | `String` | Scope of the account |
| 282 | scopeCity | `String` | Scope City |
| 283 | scopeCityDesc | `String` | The description of this value. |
| 284 | scopeDesc | `String` | The description of this value. |
| 285 | searchName | `String` | The Uppercase value of Last or Company. |
| 286 | searchNameAlternate | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| 287 | sfirst | `String` | Uppercase value of First Name. |
| 288 | soundExCompany | `String` | The soundex value for this company record.  Used for performance reasons when finding a name based on the Sounds. |
| 289 | soundExLast | `String` | The soundex value for this individual record. Used for performance reasons when finding a name based on the sounds. |
| 290 | srepCode | `String` | Used in QMS Module |
| 291 | state | `String` | The state of this address. |
| 292 | stateCode | `String` | State Code |
| 293 | stateDescription | `String` | Description of the state. |
| 294 | summRefCc | `String` | Summary Reference Currency for the Folio Generation. |
| 295 | summRefCurrencyId | `String` | Summary Reference Currency for the Folio Generation. |
| 296 | superSearchIndexText | `String` | Used in Oracle Text Index. |
| 297 | sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| 298 | taxCategory | `String` | Tax Category |
| 299 | taxExemptStatus | `String` | Not used. |
| 300 | taxID1 | `String` | The tax id of this name.  Usually issued by a government agency.  Used by 1099 printing. |
| 301 | taxID2 | `String` | Tax No |
| 302 | taxOffice | `String` | Tax Office Name |
| 303 | taxType | `String` | Tax Type |
| 304 | territory | `String` | TERRITORY of  a account |
| 305 | territoryDesc | `String` | The description of this value. |
| 306 | thirdPartyYN | `String` | Third Party YN |
| 307 | titleAlternate | `String` | Title Alternate |
| 308 | titleName | `String` | The description of this value. |
| 309 | titleSuffix | `Float` | Stores the suffix value of the selected title code.  This will be used for Processing to External System. |
| 310 | totalStay | `Float` | Sum of total number of stays on stay records for the time period. |
| 311 | tourOperatorType | `String` | The type of tour operator. Only valid for tour operators/wholesalers. |
| 312 | traceCode | `String` | Code to Trace a record for all Triggered actions. |
| 313 | tracecodeDesc | `String` | Description |
| 314 | typeOfTax1099 | `String` | What type of 1099 is issued to this name. |
| 315 | uDFC01 | `String` | User defined character field. |
| 316 | uDFC02 | `String` | User defined character field. |
| 317 | uDFC03 | `String` | User defined character field. |
| 318 | uDFC04 | `String` | User defined character field. |
| 319 | uDFC05 | `String` | User defined character field. |
| 320 | uDFC06 | `String` | User defined character field. |
| 321 | uDFC07 | `String` | User defined character field. |
| 322 | uDFC08 | `String` | User defined character field. |
| 323 | uDFC09 | `String` | User defined character field. |
| 324 | uDFC10 | `String` | User defined character field. |
| 325 | uDFC11 | `String` | User defined character field. |
| 326 | uDFC12 | `String` | User defined character field. |
| 327 | uDFC13 | `String` | User defined character field. |
| 328 | uDFC14 | `String` | User defined character field. |
| 329 | uDFC15 | `String` | User defined character field. |
| 330 | uDFC16 | `String` | User defined character field. |
| 331 | uDFC17 | `String` | User defined character field. |
| 332 | uDFC18 | `String` | User defined character field. |
| 333 | uDFC19 | `String` | User defined character field. |
| 334 | uDFC20 | `String` | User defined character field. |
| 335 | uDFC21 | `String` | User defined character field. |
| 336 | uDFC22 | `String` | User defined character field. |
| 337 | uDFC23 | `String` | User defined character field. |
| 338 | uDFC24 | `String` | User defined character field. |
| 339 | uDFC25 | `String` | User defined character field. |
| 340 | uDFC26 | `String` | User defined character field. |
| 341 | uDFC27 | `String` | User defined character field. |
| 342 | uDFC28 | `String` | User defined character field. |
| 343 | uDFC29 | `String` | User defined character field. |
| 344 | uDFC30 | `String` | User defined character field. |
| 345 | uDFC31 | `String` | User defined character field. |
| 346 | uDFC32 | `String` | User defined character field. |
| 347 | uDFC33 | `String` | User defined character field. |
| 348 | uDFC34 | `String` | User defined character field. |
| 349 | uDFC35 | `String` | User defined character field. |
| 350 | uDFC36 | `String` | User defined character field. |
| 351 | uDFC37 | `String` | User defined character field. |
| 352 | uDFC38 | `String` | User defined character field. |
| 353 | uDFC39 | `String` | User defined character field. |
| 354 | uDFC40 | `String` | User defined character field. |
| 355 | uDFD01 | `Date` | User defined date field. |
| 356 | uDFD02 | `Date` | User defined date field. |
| 357 | uDFD03 | `Date` | User defined date field. |
| 358 | uDFD04 | `Date` | User defined date field. |
| 359 | uDFD05 | `Date` | User defined date field. |
| 360 | uDFD06 | `Date` | User defined date field. |
| 361 | uDFD07 | `Date` | User defined date field. |
| 362 | uDFD08 | `Date` | User defined date field. |
| 363 | uDFD09 | `Date` | User defined date field. |
| 364 | uDFD10 | `Date` | User defined date field. |
| 365 | uDFD11 | `Date` | User defined date field. |
| 366 | uDFD12 | `Date` | User defined date field. |
| 367 | uDFD13 | `Date` | User defined date field. |
| 368 | uDFD14 | `Date` | User defined date field. |
| 369 | uDFD15 | `Date` | User defined date field. |
| 370 | uDFD16 | `Date` | User defined date field. |
| 371 | uDFD17 | `Date` | User defined date field. |
| 372 | uDFD18 | `Date` | User defined date field. |
| 373 | uDFD19 | `Date` | User defined date field. |
| 374 | uDFD20 | `Date` | User defined date field. |
| 375 | uDFN01 | `Float` | User defined number field. |
| 376 | uDFN02 | `Float` | User defined number field. |
| 377 | uDFN03 | `Float` | User defined number field. |
| 378 | uDFN04 | `Float` | User defined number field. |
| 379 | uDFN05 | `Float` | User defined number field. |
| 380 | uDFN06 | `Float` | User defined number field. |
| 381 | uDFN07 | `Float` | User defined number field. |
| 382 | uDFN08 | `Float` | User defined number field. |
| 383 | uDFN09 | `Float` | User defined number field. |
| 384 | uDFN10 | `Float` | User defined number field. |
| 385 | uDFN11 | `Float` | User defined number field. |
| 386 | uDFN12 | `Float` | User defined number field. |
| 387 | uDFN13 | `Float` | User defined number field. |
| 388 | uDFN14 | `Float` | User defined number field. |
| 389 | uDFN15 | `Float` | User defined number field. |
| 390 | uDFN16 | `Float` | User defined number field. |
| 391 | uDFN17 | `Float` | User defined number field. |
| 392 | uDFN18 | `Float` | User defined number field. |
| 393 | uDFN19 | `Float` | User defined number field. |
| 394 | uDFN20 | `Float` | User defined number field. |
| 395 | uDFN21 | `Float` | User defined number field. |
| 396 | uDFN22 | `Float` | User defined number field. |
| 397 | uDFN23 | `Float` | User defined number field. |
| 398 | uDFN24 | `Float` | User defined number field. |
| 399 | uDFN25 | `Float` | User defined number field. |
| 400 | uDFN26 | `Float` | User defined number field. |
| 401 | uDFN27 | `Float` | User defined number field. |
| 402 | uDFN28 | `Float` | User defined number field. |
| 403 | uDFN29 | `Float` | User defined number field. |
| 404 | uDFN30 | `Float` | User defined number field. |
| 405 | uDFN31 | `Float` | User defined number field. |
| 406 | uDFN32 | `Float` | User defined number field. |
| 407 | uDFN33 | `Float` | User defined number field. |
| 408 | uDFN34 | `Float` | User defined number field. |
| 409 | uDFN35 | `Float` | User defined number field. |
| 410 | uDFN36 | `Float` | User defined number field. |
| 411 | uDFN37 | `Float` | User defined number field. |
| 412 | uDFN38 | `Float` | User defined number field. |
| 413 | uDFN39 | `Float` | User defined number field. |
| 414 | uDFN40 | `Float` | User defined number field. |
| 415 | updateDate | `DateTime` | The date the record was modified |
| 416 | updateFaxDate | `Date` | The last date this record's fax # was updated. |
| 417 | updateUser | `String` | The user that modified the record |
| 418 | uploadDate | `Date` | Date on which the record is uploaded to laptop. |
| 419 | vIPCode | `String` | VIP Status of the Individual. |
| 420 | vIPDescription | `String` | The description of this value. |
| 421 | vendorId | `Float` | The Oracle Financials vendor id for this record.  Used with the Oracle Financials A/P interface. |
| 422 | vendorSiteId | `Float` | The Oracle Financial vendor site id for this record.  Used with the Oracle Financials A/P interface. |
| 423 | vipAuthorization | `String` | Not Used. |
| 424 | visaValidityType | `String` | Country Specific Requirement for Nigeria. |
| 425 | xdisplayName | `String` | Xdisplay Name |
| 426 | xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### ARAccountsReceivablePropertyPropertyDetailsType

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
#### Validation Rules

**`mandatoryInput`**
- accountDetailsResort


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