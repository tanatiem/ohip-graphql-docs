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

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | financialTransactionDetails | [`FinancialTransactionDetailsFinancialTransactionDetailsType`](#financialtransactiondetailsfinancialtransactiondetailstype) | Financial Transaction |
| 2 | eventPostingDetails | [`FinancialTransactionDetailsEventPostingDetailsType`](#financialtransactiondetailseventpostingdetailstype) | Event Posting Details |
| 3 | propertyBudgetForecastDetails | [`FinancialTransactionDetailsPropertyBudgetForecastDetailsType`](#financialtransactiondetailspropertybudgetforecastdetailstype) | Property Budget Forecast |
| 4 | exportMapFintrxcodesDetails | [`FinancialTransactionDetailsExportMapFintrxcodesDetailsType`](#financialtransactiondetailsexportmapfintrxcodesdetailstype) | Export Map Fintrxcodes |
| 5 | exportMapPayMethDetails | [`FinancialTransactionDetailsExportMapPayMethDetailsType`](#financialtransactiondetailsexportmappaymethdetailstype) | Export Map Pay Meth |
| 6 | propertyPropertyDetails | [`FinancialTransactionDetailsPropertyPropertyDetailsType`](#financialtransactiondetailspropertypropertydetailstype) | Resort Details |
| 7 | accountDetails | [`FinancialTransactionDetailsAccountDetailsType`](#financialtransactiondetailsaccountdetailstype) | Account Details |
| 8 | articleDetails | [`FinancialTransactionDetailsArticleDetailsType`](#financialtransactiondetailsarticledetailstype) | Article Details |
| 9 | calendarPeriodDetails | [`FinancialTransactionDetailsCalendarPeriodDetailsType`](#financialtransactiondetailscalendarperioddetailstype) | Calendar Period Details |
| 10 | cashierDetails | [`FinancialTransactionDetailsCashierDetailsType`](#financialtransactiondetailscashierdetailstype) | Cashier Details |
| 11 | employeeDetails | [`FinancialTransactionDetailsEmployeeDetailsType`](#financialtransactiondetailsemployeedetailstype) | Employee Details |
| 12 | exportMapPackagecodesDetails | [`FinancialTransactionDetailsExportMapPackagecodesDetailsType`](#financialtransactiondetailsexportmappackagecodesdetailstype) | Export Map Packagecodes |
| 13 | financialPeriodDetails | [`FinancialTransactionDetailsFinancialPeriodDetailsType`](#financialtransactiondetailsfinancialperioddetailstype) | Financial Period Details |
| 14 | folioTaxDetails | [`FinancialTransactionDetailsFolioTaxDetailsType`](#financialtransactiondetailsfoliotaxdetailstype) | Folio Tax Details |
| 15 | foreignCurrencyDetails | [`FinancialTransactionDetailsForeignCurrencyDetailsType`](#financialtransactiondetailsforeigncurrencydetailstype) | Foreign Currency Details |
| 16 | invoicePaymentDetails | [`FinancialTransactionDetailsInvoicePaymentDetailsType`](#financialtransactiondetailsinvoicepaymentdetailstype) | Invoice Payment Details |
| 17 | profileAllInformationDetails | [`FinancialTransactionDetailsProfileAllInformationDetailsType`](#financialtransactiondetailsprofileallinformationdetailstype) | Profile All Details |
| 18 | rateCodeDetails | [`FinancialTransactionDetailsRateCodeDetailsType`](#financialtransactiondetailsratecodedetailstype) | Rate Code Details |
| 19 | rateSeasonDetails | [`FinancialTransactionDetailsRateSeasonDetailsType`](#financialtransactiondetailsrateseasondetailstype) | Rate Season Details |
| 20 | reportCalendarDetails | [`FinancialTransactionDetailsReportCalendarDetailsType`](#financialtransactiondetailsreportcalendardetailstype) | Report Calendar |
| 21 | reservationDetails | [`FinancialTransactionDetailsReservationDetailsType`](#financialtransactiondetailsreservationdetailstype) | Reservation Details |
| 22 | revenuePackagesDetails | [`FinancialTransactionDetailsRevenuePackagesDetailsType`](#financialtransactiondetailsrevenuepackagesdetailstype) | Revenue Packages Details |
| 23 | roomDetails | [`FinancialTransactionDetailsRoomDetailsType`](#financialtransactiondetailsroomdetailstype) | Room Details |
| 24 | routingInstructionDetails | [`FinancialTransactionDetailsRoutingInstructionDetailsType`](#financialtransactiondetailsroutinginstructiondetailstype) | Routing Instruction Details |
| 25 | transactionCodeDetails | [`FinancialTransactionDetailsTransactionCodeDetailsType`](#financialtransactiondetailstransactioncodedetailstype) | Transaction Code |
| 26 | transactionCodeArrangmentDetails | [`FinancialTransactionDetailsTransactionCodeArrangmentDetailsType`](#financialtransactiondetailstransactioncodearrangmentdetailstype) | Transaction Code Arrangment |
| 27 | fromReservationDetails | [`FinancialTransactionDetailsFromReservationDetailsType`](#financialtransactiondetailsfromreservationdetailstype) | From Reservation Details |
| 28 | toReservationDetails | [`FinancialTransactionDetailsToReservationDetailsType`](#financialtransactiondetailstoreservationdetailstype) | To Reservation Details |
| 29 | financialTransactionDetailsRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsFinancialTransactionDetailsType

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
| 299 | sourceid | `String` | Sourceid |
| 300 | splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| 301 | stampDutyYN | `String` | Identifies if the transaction is stamp duty. |
| 302 | supplement | `String` | Supplement |
| 303 | taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| 304 | targetResort | `String` | Target Property |
| 305 | targetlocationid | `String` | Targetlocationid |
| 306 | taxDeferredUntilCheckOutYN | `String` | Tax Deferred Until Check-Out YN |
| 307 | taxElements | `String` | Tax Elements |
| 308 | taxGeneratedYN | `String` | Tax Generated YN |
| 309 | taxInclusiveYN | `String` | Tax Inclusive YN |
| 310 | taxInvNumber | `String` | Tax Invoice No |
| 311 | taxRate | `Float` | Tax Rate |
| 312 | taxRateType | `String` | Tax Rate Type |
| 313 | tcGroup | `String` | Transaction Code Group |
| 314 | tcSubgroup | `String` | Transaction Code Subgroup |
| 315 | tclCode1 | `String` | Class1 Code. |
| 316 | tclCode2 | `String` | Class1 Code. |
| 317 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 318 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 319 | thresholdEntityType | `String` | Threshold Entity Type |
| 320 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 321 | toReservationNameId | `Float` | To Resv Name ID |
| 322 | tranActionId | `Float` | Tran Action ID |
| 323 | transactionActivityDate | `Date` | Transaction Activity Date |
| 324 | transactionCode | `String` | Transaction Code |
| 325 | transactionCodeDescription | `String` | Transaction Code Description |
| 326 | transactionCodeGroupDesc | `String` | Tc Group Description |
| 327 | transactionCodeSubgroupDesc | `String` | Tc Subgroup Description |
| 328 | transactionDate | `Date` | Transaction Date |
| 329 | transactionNumberAddedBy | `Float` | Transaction Number Added By |
| 330 | transactionPostingDate | `Date` | Transaction Posting Date |
| 331 | transactionPostingTime | `String` | Time transaction was posted. |
| 332 | transactionPostingTimeWithSeconds | `String` | Time transaction was posted with seconds. |
| 333 | transactionReservationNameID | `Float` | Transaction Reservation Name ID |
| 334 | transactionStatus | `String` | Transaction Status |
| 335 | transactionType | `String` | Transaction Type |
| 336 | transactionFromAccount | `Float` | Transaction from Account |
| 337 | transactionToAccount | `Float` | Transaction to Account |
| 338 | transactionsReasonCode | `String` | Transactions-Reason Code |
| 339 | transcodearrangementid | `Float` | Transcodearrangementid |
| 340 | transferfromaccountid | `Float` | Transferfromaccountid |
| 341 | transferfromresvid | `Float` | Transferfromresvid |
| 342 | transfertoaccountid | `Float` | Transfertoaccountid |
| 343 | transfertoresvid | `Float` | Transfertoresvid |
| 344 | travelAgentCommissionableYN | `String` | Travel Agent Commissionable YN |
| 345 | trialBalanceAmountGross | `Float` | Trial Balance Amount Gross |
| 346 | trialBalanceAmountNet | `Float` | Trial Balance Amount Net |
| 347 | trxCode | `String` | Transaction Code |
| 348 | trxNo | `Float` | Trx Number |
| 349 | trxNoAgainstPackage | `Float` | Trx Number Against Package |
| 350 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 351 | trxNumberHeader | `Float` | Transaction No Header |
| 352 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 353 | trxServiceType | `String` | Transaction Service Type |
| 354 | trxType | `String` | Transaction type: possible values: [CACH]. |
| 355 | updateDate | `DateTime` | Update Date |
| 356 | updateUser | `Float` | Update User |
| 357 | upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| 358 | userID | `Float` | User ID |
| 359 | vatAmount | `Float` | Tax Amount for Commission. |
| 360 | vatOffsetYn | `String` | Vat Offset Y/N |
| 361 | vendorTranID | `String` | Vendor Tran ID |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsEventPostingDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allotmentid | `Float` | Block ID |
| 2 | blockBeginDate | `Date` | Block Begin Date |
| 3 | blockEndDate | `Date` | Block End Date |
| 4 | bookId | `Float` | Book ID |
| 5 | businessDate | `DateTime` | Business Date |
| 6 | cExchangeDate | `Date` | Central Xchange Date |
| 7 | cExchangeRate | `Float` | Central Xchange Rate |
| 8 | cPostedToExtra | `Float` | Central Posted To Extra |
| 9 | cPostedToIncl | `Float` | Central Posted To Incl |
| 10 | cSvcTaxExtra | `Float` | Central Svc Tax Extra |
| 11 | cSvcTaxInclude | `Float` | Central Svc Tax Include |
| 12 | cTaxExtra | `Float` | Central Tax Extra |
| 13 | cTaxIncl | `Float` | Central Tax Incl |
| 14 | cTransactionExtra | `Float` | Central Trx Extra |
| 15 | cTransactionIncl | `Float` | Central Trx Incl |
| 16 | calculationRuleExtra | `String` | Service Charge is calculated [NET] or [GROSS] for Extra Revenue ? |
| 17 | calculationRuleIncluded | `String` | Service Charge is calculated [NET] or [GROSS] for Included Revenue ? |
| 18 | centralPostingRevenueExtra | `Float` | Central Posting - Revenue Extra |
| 19 | centralRevenueIncluded | `Float` | Central Revenue Included |
| 20 | centralServiceChargeIncluded | `Float` | Central Service Charge - Included |
| 21 | centralServiceChargeExtra | `Float` | Central Service Charge- Extra |
| 22 | centralTaxType | `String` | Central Tax Type |
| 23 | centralTaxTypeDescription | `String` | Central Tax Type Description |
| 24 | centralUnitPrice | `Float` | Central Unit Price |
| 25 | checkNumber | `String` | Check Number |
| 26 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 27 | deletedFlag | `String` | Deleted Flag |
| 28 | evPostId | `Float` | Event Post ID Primary Key |
| 29 | eventId | `Float` | Event ID |
| 30 | eventpostingid | `Float` | Eventpostingid |
| 31 | extraallotmentid | `Float` | Extraallotmentid |
| 32 | extraforresvid | `Float` | Extraforresvid |
| 33 | extratranscodeid | `String` | Extratranscodeid |
| 34 | includedallotmentid | `Float` | Includedallotmentid |
| 35 | includedforresvid | `Float` | Includedforresvid |
| 36 | includedtranscodeid | `String` | Includedtranscodeid |
| 37 | insertUser | `Float` | Insert User |
| 38 | internalEventid | `Float` | Eventid |
| 39 | jRNUpdateDate | `Date` | JRN Update Date |
| 40 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 41 | locationID | `String` | Internal ID to uniquely identify the Property |
| 42 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 43 | postedById | `Float` | Posted By ID |
| 44 | postedByUserName | `String` | The User ID who posted the message. |
| 45 | postedDateExtra | `Date` | Posted Date Extra |
| 46 | postedDateIncluded | `Date` | Posted Date Included |
| 47 | postedToExtra | `Float` | Posted To Extra |
| 48 | postedToIncl | `Float` | Posted To Incl |
| 49 | postedYN | `String` | Posted YN |
| 50 | postedByProperty | `String` | Posted by Property |
| 51 | postedToRoomExtra | `String` | Posted to Room - Extra |
| 52 | postedToRoomIncluded | `String` | Posted to Room - Included |
| 53 | postingRevenueExtra | `Float` | Extra Revenue Amount |
| 54 | postinglocationid | `String` | Postinglocationid |
| 55 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 56 | property | `String` | Code to uniquely identify the Property |
| 57 | resourceName | `String` | Resource Name |
| 58 | resourceType | `String` | Resource Type |
| 59 | revenueIncluded | `Float` | Included Revenue Amount |
| 60 | revenueType | `String` | Revenue Type |
| 61 | revenuetypeid | `String` | Revenuetypeid |
| 62 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 63 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 64 | serviceChargeIncluded | `Float` | Service Charge - Included |
| 65 | serviceChargePercentExtra | `Float` | Service Charge Percentage for Extra Revenue. |
| 66 | serviceChargePercentIncluded | `Float` | Service Charge Percentage for Included Revenue. |
| 67 | serviceChargeTransactionCode | `String` | Service Charge Transaction Code for Included Revenue. |
| 68 | serviceChargeExtra | `Float` | Service Charge- Extra |
| 69 | svcTaxExtra | `Float` | Svc Tax Extra |
| 70 | svcTaxInclude | `Float` | Svc Tax Include |
| 71 | svcTrxCodeExtra | `String` | Service Charge Transaction Code for Extra Revenue. |
| 72 | svcTrxNumberExtra | `Float` | Transaction ID for Service Charge included Revenue. |
| 73 | svcTrxNumberIncl | `Float` | Transaction ID for Service Charge extra Revenue. |
| 74 | taxExtra | `Float` | Tax Extra |
| 75 | taxIncl | `Float` | Tax Incl |
| 76 | taxType | `String` | Tax Type |
| 77 | taxTypeDescription | `String` | Tax Type Description |
| 78 | transactionCodeExtraRevenue | `String` | Transactioncode for Extra Revenue |
| 79 | transactionCodeIncludedRevenue | `String` | Transactioncode for Included Revenue |
| 80 | trxExtra | `Float` | Transaction Extra |
| 81 | trxIncl | `Float` | Transaction Incl |
| 82 | trxNumberExtra | `Float` | Transaction No Extra |
| 83 | trxNumberIncl | `Float` | Transaction No Incl |
| 84 | unitPrice | `Float` | Unit Price |
| 85 | units | `Float` | Number of units which will be used to calculate the total revenue to be posted. |
| 86 | updateDate | `DateTime` | Update Date |
| 87 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsPropertyBudgetForecastDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountingType | `String` | Accounting Period used by the Property. Valid Values are : CALENDAR or FISCAL. |
| 2 | accountingYear | `Float` | Accounting Year. |
| 3 | budgetCode | `String` | Budget Code |
| 4 | budgetCodeDescription | `String` | Budget Code Description |
| 5 | budgetType | `String` | Budget Type |
| 6 | budgetValue | `String` | Budget Code. Can be either Market Code Transaction Code or Custom Code. Depends on field Budget Code Type. |
| 7 | budgetValueDescription | `String` | Budget Value Description |
| 8 | cExchangeDate | `Date` | Central Xchange Date |
| 9 | cExchangeRate | `Float` | Central Xchange Rate |
| 10 | centralRevenue | `Float` | Central Revenue |
| 11 | covers | `Float` | Covers |
| 12 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 13 | deletedFlag | `String` | Deleted Flag |
| 14 | endDate | `Date` | End Date |
| 15 | insertDate | `DateTime` | Insert Date |
| 16 | insertUser | `Float` | Insert User |
| 17 | jRNUpdateDate | `Date` | JRN Update Date |
| 18 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | lockedYN | `String` | Locked YN |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | periodType | `String` | Period Type |
| 23 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 24 | property | `String` | Code to uniquely identify the Property |
| 25 | revenue | `Float` | Revenue |
| 26 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 27 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 28 | roomNights | `Float` | Room Nights |
| 29 | startDate | `Date` | Start Date |
| 30 | updateDate | `DateTime` | Update Date |
| 31 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsExportMapFintrxcodesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | codeCanDeleteYn | `String` | Code Can Delete Y/N |
| 3 | codeInsertDate | `DateTime` | Code Insert Date |
| 4 | codeInsertUser | `Float` | Code Insert User |
| 5 | codeInsertUserName | `String` | Code Insert User Name |
| 6 | codeUpdateDate | `DateTime` | Code Update Date |
| 7 | codeUpdateUser | `Float` | Code Update User |
| 8 | codeUpdateUserName | `String` | Code Update User Name |
| 9 | combinedMappingYn | `String` | Types configured with Y can be mapped via the Combined Export Mapping screen in OPERA.  User will be presented with a consolidated view of all codes. |
| 10 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 11 | dataType | `String` | Data Type |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | exportMappingId | `Float` | Exp Mapping ID |
| 14 | exportValue | `String` | Code to be sent in the export. |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | linkInsertDate | `DateTime` | Link Insert Date |
| 18 | linkInsertUser | `Float` | Link Insert User |
| 19 | linkInsertUserName | `String` | Link Insert User Name |
| 20 | linkUpdateDate | `DateTime` | Link Update Date |
| 21 | linkUpdateUser | `Float` | Link Update User |
| 22 | linkUpdateUserName | `String` | Link Update User Name |
| 23 | linkedCode | `String` | Code of the configuration item to which this mapping type is linked e.g. financial transaction code. |
| 24 | linkedDescription | `String` | Linked Description |
| 25 | locationID | `String` | Internal ID to uniquely identify the Property |
| 26 | lovName | `String` | Name of the LOV group to be used (from Screen Design) |
| 27 | mappedToCode | `String` | Mapped To Code |
| 28 | mappedToDescription | `String` | Mapped To Description |
| 29 | mappingCode | `String` | Code for the mapping code. |
| 30 | mappingCodeDescription | `String` | Description for the mapping code. |
| 31 | mappingTypeCode | `String` | Mapping Type Code |
| 32 | mappingTypeDescription | `String` | Mapping Type Description |
| 33 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 34 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 35 | property | `String` | Code to uniquely identify the Property |
| 36 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 37 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 38 | requiredYn | `String` | Required Y/N |
| 39 | seqNumber | `Float` | Sequence No |
| 40 | shortColumnTitle | `String` | Short text for column headers while configuring consolidated export mapping. |
| 41 | trxCode | `String` | Transaction Code |
| 42 | typeCanDeleteYn | `String` | Type Can Delete Y/N |
| 43 | typeInsertDate | `DateTime` | Type Insert Date |
| 44 | typeInsertUser | `Float` | Type Insert User |
| 45 | typeInsertUserName | `String` | Type Insert User Name |
| 46 | typeUpdateDate | `DateTime` | Type Update Date |
| 47 | typeUpdateUser | `Float` | Type Update User |
| 48 | typeUpdateUserName | `String` | Type Update User Name |
| 49 | useLovYn | `String` | Show LOV button when linking this mapping code to the configuration item. |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsExportMapPayMethDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | codeCanDeleteYn | `String` | Code Can Delete Y/N |
| 3 | codeInsertDate | `DateTime` | Code Insert Date |
| 4 | codeInsertUser | `Float` | Code Insert User |
| 5 | codeInsertUserName | `String` | Code Insert User Name |
| 6 | codeUpdateDate | `DateTime` | Code Update Date |
| 7 | codeUpdateUser | `Float` | Code Update User |
| 8 | codeUpdateUserName | `String` | Code Update User Name |
| 9 | combinedMappingYn | `String` | Types configured with Y can be mapped via the Combined Export Mapping screen in OPERA.  User will be presented with a consolidated view of all codes. |
| 10 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 11 | dataType | `String` | Data Type |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | exportMappingId | `Float` | Exp Mapping ID |
| 14 | exportValue | `String` | Code to be sent in the export. |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | linkInsertDate | `DateTime` | Link Insert Date |
| 18 | linkInsertUser | `Float` | Link Insert User |
| 19 | linkInsertUserName | `String` | Link Insert User Name |
| 20 | linkUpdateDate | `DateTime` | Link Update Date |
| 21 | linkUpdateUser | `Float` | Link Update User |
| 22 | linkUpdateUserName | `String` | Link Update User Name |
| 23 | linkedCode | `String` | Code of the configuration item to which this mapping type is linked e.g. financial transaction code. |
| 24 | linkedDescription | `String` | Linked Description |
| 25 | locationID | `String` | Internal ID to uniquely identify the Property |
| 26 | lovName | `String` | Name of the LOV group to be used (from Screen Design) |
| 27 | mappedToCode | `String` | Mapped To Code |
| 28 | mappedToDescription | `String` | Mapped To Description |
| 29 | mappingCode | `String` | Code for the mapping code. |
| 30 | mappingCodeDescription | `String` | Description for the mapping code. |
| 31 | mappingTypeCode | `String` | Mapping Type Code |
| 32 | mappingTypeDescription | `String` | Mapping Type Description |
| 33 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 34 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 35 | property | `String` | Code to uniquely identify the Property |
| 36 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 37 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 38 | requiredYn | `String` | Required Y/N |
| 39 | seqNumber | `Float` | Sequence No |
| 40 | shortColumnTitle | `String` | Short text for column headers while configuring consolidated export mapping. |
| 41 | trxCode | `String` | Transaction Code |
| 42 | typeCanDeleteYn | `String` | Type Can Delete Y/N |
| 43 | typeInsertDate | `DateTime` | Type Insert Date |
| 44 | typeInsertUser | `Float` | Type Insert User |
| 45 | typeInsertUserName | `String` | Type Insert User Name |
| 46 | typeUpdateDate | `DateTime` | Type Update Date |
| 47 | typeUpdateUser | `Float` | Type Update User |
| 48 | typeUpdateUserName | `String` | Type Update User Name |
| 49 | useLovYn | `String` | Show LOV button when linking this mapping code to the configuration item. |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsPropertyPropertyDetailsType

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

### FinancialTransactionDetailsAccountDetailsType

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

### FinancialTransactionDetailsArticleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activeYN | `String` | Active YN |
| 2 | articleCode | `String` | Article Code |
| 3 | articleDescription | `String` | Article Description |
| 4 | articleId | `Float` | Article ID |
| 5 | availableInPostItYN | `String` | Available in Post It YN |
| 6 | cDefaultPrice | `Float` | Central Default Price |
| 7 | cExchangeDate | `Date` | Central Xchange Date |
| 8 | cExchangeRate | `Float` | Central Xchange Rate |
| 9 | centralArticleCode | `String` | Central Article Code |
| 10 | centralArticleDescription | `String` | Central Article Description |
| 11 | centralSequence | `Float` | Central Sequence |
| 12 | centralTransactionCode | `String` | Central Transaction Code |
| 13 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 14 | defaultPrice | `Float` | Default Price |
| 15 | deletedflag | `String` | Deleted Flag |
| 16 | description | `String` | Description |
| 17 | displayColor | `String` | The button colour used in the Postit screen for this article. |
| 18 | inactiveDate | `DateTime` | Inactive Date |
| 19 | insertDate | `DateTime` | Insert Date |
| 20 | insertUser | `Float` | Insert User |
| 21 | internalArticleid | `Float` | Articleid |
| 22 | jRNUpdateDate | `Date` | JRN Update Date |
| 23 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 24 | locationID | `String` | Internal ID to uniquely identify the Property |
| 25 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 26 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 27 | property | `String` | Property |
| 28 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 29 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | transactionCode | `String` | Transaction Code |
| 36 | transcodeid | `String` | Transcodeid |
| 37 | uPC | `String` | UPC |
| 38 | updateDate | `DateTime` | Update Date |
| 39 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsCalendarPeriodDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | endDate | `Date` | End Date |
| 5 | jRNUpdateDate | `Date` | JRN Update Date |
| 6 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 7 | locationID | `String` | Internal ID to uniquely identify the Property |
| 8 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 9 | parentPeriod | `String` | Indicates the Parent Period of the current period scope. Used primarily in OBI. Eg. YEAR - QUARTER - MONTH -WEEK |
| 10 | parentperiodid | `String` | Parentperiodid |
| 11 | periodCode | `String` | Period Code |
| 12 | periodDescription | `String` | Period Description |
| 13 | periodScope | `String` | Indicates Scope of the period. Eg. QUARTER - MONTH -WEEK. Used primarily in OBI. |
| 14 | periodType | `String` | Period Type |
| 15 | periodTypeDesc | `String` | Period Type Description |
| 16 | periodsetupid | `Float` | Periodsetupid |
| 17 | periodsetuppmsref | `String` | Periodsetuppmsref |
| 18 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 19 | property | `String` | Code to uniquely identify the Property |
| 20 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 21 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 22 | startDate | `Date` | Start Date |
| 23 | updateDate | `DateTime` | Update Date |
| 24 | updateUser | `Float` | Update User |
| 25 | year | `Float` | Year |
| 26 | yearDescription | `String` | Year Description |
| 27 | yearEndDate | `Date` | Year End Date. |
| 28 | yearId | `Float` | Year ID |
| 29 | yearStartDate | `Date` | Year Start Date. |
| 30 | yearType | `String` | Year Type. |
| 31 | yearsetupid | `Float` | Yearsetupid |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsCashierDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activeYN | `String` | Active YN |
| 2 | amtDifferenceInitial | `Float` | The difference in cash the cashier must pay or receive when the cashier is set up. |
| 3 | attachedToUser | `String` | Application User Name |
| 4 | cAmountDifferenceInitial | `Float` | Central Amt Diff Initial |
| 5 | cAmountFloat | `Float` | Central Amt Float |
| 6 | cCashierBalance | `Float` | Central Cashier Bal |
| 7 | cExchangeDate | `Date` | Central Xchange Date |
| 8 | cExchangeRate | `Float` | Central Xchange Rate |
| 9 | cashierBal | `Float` | At the time he closes his account on that day after drop off the difference in cash he has to pay or has to be paid. |
| 10 | cashierid | `Float` | Cashierid |
| 11 | chainCode | `String` | Chain Code |
| 12 | closureInProgressYn | `String` | Indicates if the cashier is in progress to be closed. |
| 13 | closureNo | `Float` | Closure Number |
| 14 | csrTrxNumber | `Float` | CSR Trx No. |
| 15 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 16 | dateoflastuse | `Date` | Date of last use. |
| 17 | deletedflag | `String` | Deleted Flag |
| 18 | floatOverShort | `String` | Parameter to set up whether the cashier has to drop the whole cash including the float or just the amt excess of float. |
| 19 | generalCashierYN | `String` | Determines whether the cashier is a General cashier. |
| 20 | insertDate | `DateTime` | Insert Date |
| 21 | insertUser | `Float` | Insert User |
| 22 | interfaceCashierYN | `String` | Decides whether the cashier number is used in interfaces or not. The interface cashiers cannot have numbers more than 999. |
| 23 | internalUpdateYn | `String` | Internally used. |
| 24 | jRNUpdateDate | `Date` | JRN Update Date |
| 25 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 26 | kioskCashierYN | `String` | Identifies if the cashier is used by KIOSK interfaces. Only one KIOSK cashier is allowed. |
| 27 | lastOpened | `Date` | Date Last Opened. |
| 28 | locationID | `String` | Internal ID to uniquely identify the Property |
| 29 | maximumDailyUses | `Float` | The no. of times cashier is allowed to open per day. |
| 30 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 31 | paymentsCashierCode | `Float` | Payments-Cashier Code |
| 32 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 33 | property | `String` | Property |
| 34 | reservedResort | `String` | Property that this cashier is reserved for. Used for floating cashier functionality. |
| 35 | reservedYn | `String` | Identifies if this cashier is currently being used as a floating cashier. |
| 36 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 37 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 38 | startingAmount | `Float` | The initial amount the cashier should have every day. |
| 39 | state | `String` | State |
| 40 | timeoffirstopen | `Date` | Time first time he opened on that day. |
| 41 | timeoflastclose | `Date` | Time cashier last closed on that day. |
| 42 | timesOpened | `Float` | The no. of times the cashier opened his account today. |
| 43 | tranActionId | `Float` | Tran Action ID |
| 44 | transactionsCashierName | `String` | Transactions-Cashier Name |
| 45 | updateDate | `DateTime` | Update Date |
| 46 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsEmployeeDetailsType

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

### FinancialTransactionDetailsExportMapPackagecodesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | codeCanDeleteYn | `String` | Code Can Delete Y/N |
| 3 | codeInsertDate | `DateTime` | Code Insert Date |
| 4 | codeInsertUser | `Float` | Code Insert User |
| 5 | codeInsertUserName | `String` | Code Insert User Name |
| 6 | codeUpdateDate | `DateTime` | Code Update Date |
| 7 | codeUpdateUser | `Float` | Code Update User |
| 8 | codeUpdateUserName | `String` | Code Update User Name |
| 9 | combinedMappingYn | `String` | Types configured with Y can be mapped via the Combined Export Mapping screen in OPERA.  User will be presented with a consolidated view of all codes. |
| 10 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 11 | dataType | `String` | Data Type |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | exportMappingId | `Float` | Exp Mapping ID |
| 14 | exportValue | `String` | Code to be sent in the export. |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | linkInsertDate | `DateTime` | Link Insert Date |
| 18 | linkInsertUser | `Float` | Link Insert User |
| 19 | linkInsertUserName | `String` | Link Insert User Name |
| 20 | linkUpdateDate | `DateTime` | Link Update Date |
| 21 | linkUpdateUser | `Float` | Link Update User |
| 22 | linkUpdateUserName | `String` | Link Update User Name |
| 23 | linkedCode | `String` | Code of the configuration item to which this mapping type is linked e.g. financial transaction code. |
| 24 | linkedDescription | `String` | Linked Description |
| 25 | locationID | `String` | Internal ID to uniquely identify the Property |
| 26 | lovName | `String` | Name of the LOV group to be used (from Screen Design) |
| 27 | mappedToCode | `String` | Mapped To Code |
| 28 | mappedToDescription | `String` | Mapped To Description |
| 29 | mappingCode | `String` | Code for the mapping code. |
| 30 | mappingCodeDescription | `String` | Description for the mapping code. |
| 31 | mappingTypeCode | `String` | Mapping Type Code |
| 32 | mappingTypeDescription | `String` | Mapping Type Description |
| 33 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 34 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 35 | product | `String` | Product |
| 36 | property | `String` | Code to uniquely identify the Property |
| 37 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 38 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 39 | requiredYn | `String` | Required Y/N |
| 40 | seqNumber | `Float` | Sequence No |
| 41 | shortColumnTitle | `String` | Short text for column headers while configuring consolidated export mapping. |
| 42 | typeCanDeleteYn | `String` | Type Can Delete Y/N |
| 43 | typeInsertDate | `DateTime` | Type Insert Date |
| 44 | typeInsertUser | `Float` | Type Insert User |
| 45 | typeInsertUserName | `String` | Type Insert User Name |
| 46 | typeUpdateDate | `DateTime` | Type Update Date |
| 47 | typeUpdateUser | `Float` | Type Update User |
| 48 | typeUpdateUserName | `String` | Type Update User Name |
| 49 | useLovYn | `String` | Show LOV button when linking this mapping code to the configuration item. |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsFinancialPeriodDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | endDate | `Date` | End Date |
| 5 | jRNUpdateDate | `Date` | JRN Update Date |
| 6 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 7 | locationID | `String` | Internal ID to uniquely identify the Property |
| 8 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 9 | parentPeriod | `String` | Indicates the Parent Period of the current period scope. Used primarily in OBI. Eg. YEAR - QUARTER - MONTH -WEEK |
| 10 | parentperiodid | `String` | Parentperiodid |
| 11 | periodCode | `String` | Period Code |
| 12 | periodDescription | `String` | Period Description |
| 13 | periodScope | `String` | Indicates Scope of the period. Eg. QUARTER - MONTH -WEEK. Used primarily in OBI. |
| 14 | periodType | `String` | Period Type |
| 15 | periodTypeDesc | `String` | Period Type Description |
| 16 | periodsetupid | `Float` | Periodsetupid |
| 17 | periodsetuppmsref | `String` | Periodsetuppmsref |
| 18 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 19 | property | `String` | Code to uniquely identify the Property |
| 20 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 21 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 22 | startDate | `Date` | Start Date |
| 23 | updateDate | `DateTime` | Update Date |
| 24 | updateUser | `Float` | Update User |
| 25 | year | `Float` | Year |
| 26 | yearDescription | `String` | Year Description |
| 27 | yearEndDate | `Date` | Year End Date. |
| 28 | yearId | `Float` | Year ID |
| 29 | yearStartDate | `Date` | Year Start Date. |
| 30 | yearType | `String` | Year Type. |
| 31 | yearsetupid | `Float` | Yearsetupid |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsFolioTaxDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountCode | `Float` | Account Code |
| 2 | addresseeNameId | `Float` | Addressee Name ID |
| 3 | amountPostedFromAR | `Float` | This is to store amount posted from AR for a bill. In this case CLPAY will not have value if the bill is generated in AR |
| 4 | amountFromDirectBill | `Float` | The amount that has been paid using direct bill. |
| 5 | associatedBillDate | `Date` | Date on which the Original Bill was generated. This is used in case of Credit Bill. |
| 6 | associatedBillNumber | `String` | Associated Bill Number |
| 7 | associatedFiscalBillDate | `Date` | Associated Fiscal Bill number generation date. |
| 8 | associatedFiscalBillNumber | `String` | Associated Fiscal Bill number. |
| 9 | associatedFiscalBillNumberGenerationTime | `String` | Associated Fiscal Bill number generation time. |
| 10 | associatedSeqNumber | `Float` | Self referencing sequence number to gather information for other operations. |
| 11 | billGenerationDate | `Date` | Bill Generation Date |
| 12 | billNumber | `Float` | Bill Number |
| 13 | billPaymentTrxNumber | `Float` | Bill Payment Transaction No |
| 14 | billPrefix | `String` | Bill Prefix |
| 15 | billSequenceNumber | `Float` | Bill Sequence Number |
| 16 | billStartDate | `Date` | Date of the first charge in the bill. |
| 17 | billStatus | `String` | Bill Status |
| 18 | businessDate | `Date` | Business Date |
| 19 | businessId | `String` | Business ID |
| 20 | cCashpay | `Float` | Central Cashpay |
| 21 | cCcpay | `Float` | Central Ccpay |
| 22 | cClarpay | `Float` | Central Clarpay |
| 23 | cClpay | `Float` | Central Clpay |
| 24 | cCollectionTax1 | `Float` | Central Coll Tax1 |
| 25 | cCollectionTax2 | `Float` | Central Coll Tax2 |
| 26 | cCollectionTax3 | `Float` | Central Coll Tax3 |
| 27 | cCollectionTax4 | `Float` | Central Coll Tax4 |
| 28 | cCollectionTax5 | `Float` | Central Coll Tax5 |
| 29 | cDailyRunningTotal | `Float` | Central Daily Running Total |
| 30 | cDeposit | `Float` | Central Deposit |
| 31 | cExchangeDate | `Date` | Central Xchange Date |
| 32 | cExchangeRate | `Float` | Central Xchange Rate |
| 33 | cFiscalInvoiceCurrencyRate | `Float` | Central Fiscal Invoice Currency Rate |
| 34 | cNet1Amount | `Float` | Central Net1 Amt |
| 35 | cNet10Amount | `Float` | Central Net10 Amt |
| 36 | cNet11Amount | `Float` | Central Net11 Amt |
| 37 | cNet12Amount | `Float` | Central Net12 Amt |
| 38 | cNet13Amount | `Float` | Central Net13 Amt |
| 39 | cNet14Amount | `Float` | Central Net14 Amt |
| 40 | cNet15Amount | `Float` | Central Net15 Amt |
| 41 | cNet16Amount | `Float` | Central Net16 Amt |
| 42 | cNet17Amount | `Float` | Central Net17 Amt |
| 43 | cNet18Amount | `Float` | Central Net18 Amt |
| 44 | cNet19Amount | `Float` | Central Net19 Amt |
| 45 | cNet2Amount | `Float` | Central Net2 Amt |
| 46 | cNet20Amount | `Float` | Central Net20 Amt |
| 47 | cNet3Amount | `Float` | Central Net3 Amt |
| 48 | cNet4Amount | `Float` | Central Net4 Amt |
| 49 | cNet5Amount | `Float` | Central Net5 Amt |
| 50 | cNet6Amount | `Float` | Central Net6 Amt |
| 51 | cNet7Amount | `Float` | Central Net7 Amt |
| 52 | cNet8Amount | `Float` | Central Net8 Amt |
| 53 | cNet9Amount | `Float` | Central Net9 Amt |
| 54 | cPaidout | `Float` | Central Paidout |
| 55 | cPerpetualAmount | `Float` | Central Perpetual Amount |
| 56 | cPnet1Amount | `Float` | Central Pnet1 Amt |
| 57 | cPnet10Amount | `Float` | Central Pnet10 Amt |
| 58 | cPnet11Amount | `Float` | Central Pnet11 Amt |
| 59 | cPnet12Amount | `Float` | Central Pnet12 Amt |
| 60 | cPnet13Amount | `Float` | Central Pnet13 Amt |
| 61 | cPnet14Amount | `Float` | Central Pnet14 Amt |
| 62 | cPnet15Amount | `Float` | Central Pnet15 Amt |
| 63 | cPnet16Amount | `Float` | Central Pnet16 Amt |
| 64 | cPnet17Amount | `Float` | Central Pnet17 Amt |
| 65 | cPnet18Amount | `Float` | Central Pnet18 Amt |
| 66 | cPnet19Amount | `Float` | Central Pnet19 Amt |
| 67 | cPnet2Amount | `Float` | Central Pnet2 Amt |
| 68 | cPnet20Amount | `Float` | Central Pnet20 Amt |
| 69 | cPnet3Amount | `Float` | Central Pnet3 Amt |
| 70 | cPnet4Amount | `Float` | Central Pnet4 Amt |
| 71 | cPnet5Amount | `Float` | Central Pnet5 Amt |
| 72 | cPnet6Amount | `Float` | Central Pnet6 Amt |
| 73 | cPnet7Amount | `Float` | Central Pnet7 Amt |
| 74 | cPnet8Amount | `Float` | Central Pnet8 Amt |
| 75 | cPnet9Amount | `Float` | Central Pnet9 Amt |
| 76 | cPtax1Amount | `Float` | Central Ptax1 Amt |
| 77 | cPtax10Amount | `Float` | Central Ptax10 Amt |
| 78 | cPtax11Amount | `Float` | Central Ptax11 Amt |
| 79 | cPtax12Amount | `Float` | Central Ptax12 Amt |
| 80 | cPtax13Amount | `Float` | Central Ptax13 Amt |
| 81 | cPtax14Amount | `Float` | Central Ptax14 Amt |
| 82 | cPtax15Amount | `Float` | Central Ptax15 Amt |
| 83 | cPtax16Amount | `Float` | Central Ptax16 Amt |
| 84 | cPtax17Amount | `Float` | Central Ptax17 Amt |
| 85 | cPtax18Amount | `Float` | Central Ptax18 Amt |
| 86 | cPtax19Amount | `Float` | Central Ptax19 Amt |
| 87 | cPtax2Amount | `Float` | Central Ptax2 Amt |
| 88 | cPtax20Amount | `Float` | Central Ptax20 Amt |
| 89 | cPtax3Amount | `Float` | Central Ptax3 Amt |
| 90 | cPtax4Amount | `Float` | Central Ptax4 Amt |
| 91 | cPtax5Amount | `Float` | Central Ptax5 Amt |
| 92 | cPtax6Amount | `Float` | Central Ptax6 Amt |
| 93 | cPtax7Amount | `Float` | Central Ptax7 Amt |
| 94 | cPtax8Amount | `Float` | Central Ptax8 Amt |
| 95 | cPtax9Amount | `Float` | Central Ptax9 Amt |
| 96 | cPtotNonrevNonTaxable | `Float` | Central Ptot Nonrev Nontaxable |
| 97 | cPtotNonrevTaxable | `Float` | Central Ptot Nonrev Taxable |
| 98 | cPtotRevenueNonTaxable | `Float` | Central Ptot Rev Nontaxable |
| 99 | cPtotRevenueTaxable | `Float` | Central Ptot Rev Taxable |
| 100 | cRealPerpetualAmount | `Float` | Central Real Perpetual Amount |
| 101 | cTax1Amount | `Float` | Central Tax1 Amt |
| 102 | cTax2Amount | `Float` | Central Tax2 Amt |
| 103 | cTaxCode1 | `String` | Central Tax Code 1 |
| 104 | cTaxCode10 | `String` | Central Tax Code 10 |
| 105 | cTaxCode11 | `String` | Central Tax Code 11 |
| 106 | cTaxCode12 | `String` | Central Tax Code 12 |
| 107 | cTaxCode13 | `String` | Central Tax Code 13 |
| 108 | cTaxCode14 | `String` | Central Tax Code 14 |
| 109 | cTaxCode15 | `String` | Central Tax Code 15 |
| 110 | cTaxCode16 | `String` | Central Tax Code 16 |
| 111 | cTaxCode17 | `String` | Central Tax Code 17 |
| 112 | cTaxCode18 | `String` | Central Tax Code 18 |
| 113 | cTaxCode19 | `String` | Central Tax Code 19 |
| 114 | cTaxCode2 | `String` | Central Tax Code 2 |
| 115 | cTaxCode20 | `String` | Central Tax Code 20 |
| 116 | cTaxCode3 | `String` | Central Tax Code 3 |
| 117 | cTaxCode4 | `String` | Central Tax Code 4 |
| 118 | cTaxCode5 | `String` | Central Tax Code 5 |
| 119 | cTaxCode6 | `String` | Central Tax Code 6 |
| 120 | cTaxCode7 | `String` | Central Tax Code 7 |
| 121 | cTaxCode8 | `String` | Central Tax Code 8 |
| 122 | cTaxCode9 | `String` | Central Tax Code 9 |
| 123 | cTaxCodeDescription1 | `String` | Central Tax Code Desc 1 |
| 124 | cTaxCodeDescription10 | `String` | Central Tax Code Desc 10 |
| 125 | cTaxCodeDescription11 | `String` | Central Tax Code Desc 11 |
| 126 | cTaxCodeDescription12 | `String` | Central Tax Code Desc 12 |
| 127 | cTaxCodeDescription13 | `String` | Central Tax Code Desc 13 |
| 128 | cTaxCodeDescription14 | `String` | Central Tax Code Desc 14 |
| 129 | cTaxCodeDescription15 | `String` | Central Tax Code Desc 15 |
| 130 | cTaxCodeDescription16 | `String` | Central Tax Code Desc 16 |
| 131 | cTaxCodeDescription17 | `String` | Central Tax Code Desc 17 |
| 132 | cTaxCodeDescription18 | `String` | Central Tax Code Desc 18 |
| 133 | cTaxCodeDescription19 | `String` | Central Tax Code Desc 19 |
| 134 | cTaxCodeDescription2 | `String` | Central Tax Code Desc 2 |
| 135 | cTaxCodeDescription20 | `String` | Central Tax Code Desc 20 |
| 136 | cTaxCodeDescription3 | `String` | Central Tax Code Desc 3 |
| 137 | cTaxCodeDescription4 | `String` | Central Tax Code Desc 4 |
| 138 | cTaxCodeDescription5 | `String` | Central Tax Code Desc 5 |
| 139 | cTaxCodeDescription6 | `String` | Central Tax Code Desc 6 |
| 140 | cTaxCodeDescription7 | `String` | Central Tax Code Desc 7 |
| 141 | cTaxCodeDescription8 | `String` | Central Tax Code Desc 8 |
| 142 | cTaxCodeDescription9 | `String` | Central Tax Code Desc 9 |
| 143 | cTax10Amount | `Float` | Central Tax10 Amt |
| 144 | cTax11Amount | `Float` | Central Tax11 Amt |
| 145 | cTax12Amount | `Float` | Central Tax12 Amt |
| 146 | cTax13Amount | `Float` | Central Tax13 Amt |
| 147 | cTax14Amount | `Float` | Central Tax14 Amt |
| 148 | cTax15Amount | `Float` | Central Tax15 Amt |
| 149 | cTax16Amount | `Float` | Central Tax16 Amt |
| 150 | cTax17Amount | `Float` | Central Tax17 Amt |
| 151 | cTax18Amount | `Float` | Central Tax18 Amt |
| 152 | cTax19Amount | `Float` | Central Tax19 Amt |
| 153 | cTax20Amount | `Float` | Central Tax20 Amt |
| 154 | cTax3Amount | `Float` | Central Tax3 Amt |
| 155 | cTax4Amount | `Float` | Central Tax4 Amt |
| 156 | cTax5Amount | `Float` | Central Tax5 Amt |
| 157 | cTax6Amount | `Float` | Central Tax6 Amt |
| 158 | cTax7Amount | `Float` | Central Tax7 Amt |
| 159 | cTax8Amount | `Float` | Central Tax8 Amt |
| 160 | cTax9Amount | `Float` | Central Tax9 Amt |
| 161 | cTotalGross | `Float` | Central Total Gross |
| 162 | cTotalNet | `Float` | Central Total Net |
| 163 | cTotalNonTaxable | `Float` | Central Total Nontaxable |
| 164 | cTotalNonrevNonTaxable | `Float` | Central Tot Nonrev Nontaxable |
| 165 | cTotalNonrevTaxable | `Float` | Central Tot Nonrev Taxable |
| 166 | cTotalRevenueNonTaxable | `Float` | Central Tot Rev Nontaxable |
| 167 | cTotalRevenueTaxable | `Float` | Central Tot Rev Taxable |
| 168 | cTotalTax | `Float` | Central Total Tax |
| 169 | cXnet1Amount | `Float` | Central Xnet1 Amt |
| 170 | cXnet10Amount | `Float` | Central Xnet10 Amt |
| 171 | cXnet11Amount | `Float` | Central Xnet11 Amt |
| 172 | cXnet12Amount | `Float` | Central Xnet12 Amt |
| 173 | cXnet13Amount | `Float` | Central Xnet13 Amt |
| 174 | cXnet14Amount | `Float` | Central Xnet14 Amt |
| 175 | cXnet15Amount | `Float` | Central Xnet15 Amt |
| 176 | cXnet16Amount | `Float` | Central Xnet16 Amt |
| 177 | cXnet17Amount | `Float` | Central Xnet17 Amt |
| 178 | cXnet18Amount | `Float` | Central Xnet18 Amt |
| 179 | cXnet19Amount | `Float` | Central Xnet19 Amt |
| 180 | cXnet2Amount | `Float` | Central Xnet2 Amt |
| 181 | cXnet20Amount | `Float` | Central Xnet20 Amt |
| 182 | cXnet3Amount | `Float` | Central Xnet3 Amt |
| 183 | cXnet4Amount | `Float` | Central Xnet4 Amt |
| 184 | cXnet5Amount | `Float` | Central Xnet5 Amt |
| 185 | cXnet6Amount | `Float` | Central Xnet6 Amt |
| 186 | cXnet7Amount | `Float` | Central Xnet7 Amt |
| 187 | cXnet8Amount | `Float` | Central Xnet8 Amt |
| 188 | cXnet9Amount | `Float` | Central Xnet9 Amt |
| 189 | cXtax1Amount | `Float` | Central Xtax1 Amt |
| 190 | cXtax10Amount | `Float` | Central Xtax10 Amt |
| 191 | cXtax11Amount | `Float` | Central Xtax11 Amt |
| 192 | cXtax12Amount | `Float` | Central Xtax12 Amt |
| 193 | cXtax13Amount | `Float` | Central Xtax13 Amt |
| 194 | cXtax14Amount | `Float` | Central Xtax14 Amt |
| 195 | cXtax15Amount | `Float` | Central Xtax15 Amt |
| 196 | cXtax16Amount | `Float` | Central Xtax16 Amt |
| 197 | cXtax17Amount | `Float` | Central Xtax17 Amt |
| 198 | cXtax18Amount | `Float` | Central Xtax18 Amt |
| 199 | cXtax19Amount | `Float` | Central Xtax19 Amt |
| 200 | cXtax2Amount | `Float` | Central Xtax2 Amt |
| 201 | cXtax20Amount | `Float` | Central Xtax20 Amt |
| 202 | cXtax3Amount | `Float` | Central Xtax3 Amt |
| 203 | cXtax4Amount | `Float` | Central Xtax4 Amt |
| 204 | cXtax5Amount | `Float` | Central Xtax5 Amt |
| 205 | cXtax6Amount | `Float` | Central Xtax6 Amt |
| 206 | cXtax7Amount | `Float` | Central Xtax7 Amt |
| 207 | cXtax8Amount | `Float` | Central Xtax8 Amt |
| 208 | cXtax9Amount | `Float` | Central Xtax9 Amt |
| 209 | cashRegisterId | `String` | Cash Register ID |
| 210 | cashRegisterInvNumber | `Float` | Internal sequence number for the Cash Register ID. |
| 211 | cashTotal | `Float` | Total paid in cash |
| 212 | cashierID | `Float` | Cashier ID |
| 213 | centralTaxRate1 | `Float` | Central Tax Rate 1 |
| 214 | centralTaxRate10 | `Float` | Central Tax Rate 10 |
| 215 | centralTaxRate11 | `Float` | Central Tax Rate 11 |
| 216 | centralTaxRate12 | `Float` | Central Tax Rate 12 |
| 217 | centralTaxRate13 | `Float` | Central Tax Rate 13 |
| 218 | centralTaxRate14 | `Float` | Central Tax Rate 14 |
| 219 | centralTaxRate15 | `Float` | Central Tax Rate 15 |
| 220 | centralTaxRate16 | `Float` | Central Tax Rate 16 |
| 221 | centralTaxRate17 | `Float` | Central Tax Rate 17 |
| 222 | centralTaxRate18 | `Float` | Central Tax Rate 18 |
| 223 | centralTaxRate19 | `Float` | Central Tax Rate 19 |
| 224 | centralTaxRate2 | `Float` | Central Tax Rate 2 |
| 225 | centralTaxRate20 | `Float` | Central Tax Rate 20 |
| 226 | centralTaxRate3 | `Float` | Central Tax Rate 3 |
| 227 | centralTaxRate4 | `Float` | Central Tax Rate 4 |
| 228 | centralTaxRate5 | `Float` | Central Tax Rate 5 |
| 229 | centralTaxRate6 | `Float` | Central Tax Rate 6 |
| 230 | centralTaxRate7 | `Float` | Central Tax Rate 7 |
| 231 | centralTaxRate8 | `Float` | Central Tax Rate 8 |
| 232 | centralTaxRate9 | `Float` | Central Tax Rate 9 |
| 233 | city | `String` | City |
| 234 | cityLedgerYN | `String` | City Ledger YN |
| 235 | clTrxNumber | `Float` | Internal number given to the direct bill payment in financial_transactions. |
| 236 | collectionAgentTotalTax1 | `Float` | Collection Agent Total Tax 1 |
| 237 | collectionAgentTotalTax2 | `Float` | Collection Agent Total Tax 2 |
| 238 | collectionAgentTotalTax3 | `Float` | Collection Agent Total Tax 3 |
| 239 | collectionAgentTotalTax4 | `Float` | Collection Agent Total Tax 4 |
| 240 | collectionAgentTotalTax5 | `Float` | Collection Agent Total Tax 5 |
| 241 | companyFinancialValue | `String` | The financial value of the company. |
| 242 | companyName | `String` | Company Name |
| 243 | companyType | `String` | The type of legal entity / company e.g. Individual Micro enterprise etc. |
| 244 | compressBillNo | `String` | To store the Compressed Bill No. and Converted Bill number information |
| 245 | creditBillGeneratedYN | `String` | Indicates if a credit bill has been generated for this folio. |
| 246 | creditBillNumber | `Float` | Credit Bill Number |
| 247 | creditCardTotal | `Float` | Total paid in the form of credit cards. |
| 248 | customNumber1 | `String` | Custom Number 1 |
| 249 | customNumber2 | `String` | Custom Number 2 |
| 250 | customNumber3 | `String` | Custom Number 3 |
| 251 | customNumber4 | `String` | Custom Number 4 |
| 252 | customNumber5 | `String` | Custom Number 5 |
| 253 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 254 | dailyRunningTotal | `Float` | Daily running total. |
| 255 | deletedFlag | `String` | Deleted Flag |
| 256 | deposit | `Float` | Total deposits. |
| 257 | depositReqReceiptNumber | `Float` | Deposit Req Receipt Number |
| 258 | documentCode | `String` | Unique Document Code |
| 259 | documentType | `String` | Document Type |
| 260 | eArchiveEttnNumber | `String` | Unique ETTN number for an E Archive invoice. |
| 261 | eArchiveNumber | `String` | E Archive number. |
| 262 | eArchiveReportNo | `String` | E Archive report number provided by external system e.g. PROTEL. |
| 263 | eArchiveStatus | `String` | E Archive status. |
| 264 | eInvoiceNumber | `String` | E-Invoice Number |
| 265 | eInvoiceStatus | `String` | E-Invoice number received from Portal+. This number be updated via Web Service call from Portal+. |
| 266 | fiscalBillCheckDigit | `Float` | Fiscal Bill Check Digit |
| 267 | fiscalBillGenerationDate | `Date` | Fiscal Bill Generation Date |
| 268 | fiscalBillGenerationTime | `String` | Fiscal Bill Generation Time |
| 269 | fiscalBillNumber | `String` | Fiscal Bill Number |
| 270 | fiscalInvoiceCurrency | `String` | Currency Code used by and sent to the Fiscal Service. |
| 271 | fiscalInvoiceCurrencyRate | `Float` | Exchange Rate of the Fiscal Invoice currency for settlement on the bill generation date. |
| 272 | fiscalSessionNo | `String` | Session number generated by the fiscal printer. This numbers gets reset during EOD. |
| 273 | fiscalUnitControlCode | `String` | Fiscal Unit Control Code |
| 274 | folioAddress | `String` | Folio Full Address. |
| 275 | folioAddressCorrectedYn | `String` | Indicates if the folio header was corrected. |
| 276 | folioAttachmentLinkId | `Float` | Folio Attachment Link ID |
| 277 | folioAttachmentStatus | `Float` | Folio Attachment Status |
| 278 | folioNo | `Float` | Folio Number |
| 279 | folioStyle | `String` | Folio Style |
| 280 | folioTaxSeqNumber | `Float` | Folio Tax Sequence No |
| 281 | folioTime | `String` | Folio Time |
| 282 | folioType | `String` | Folio Type |
| 283 | folioType1 | `String` | Folio Type 1 |
| 284 | folioTypeJoin | `String` | Folio Type Join |
| 285 | folioView | `Float` | Folio View |
| 286 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 287 | fullFolioNo | `String` | Full Folio Number |
| 288 | hasWatermarkYn | `String` | If PERMANENT FOLIO STORAGE is active this flag indicates whether the PDF file has the "Copy" watermark. |
| 289 | hotelName | `String` | Hotel name of the property at the time of bill generation. |
| 290 | insTimestamp | `DateTime` | Timestamp to capture the exact order of inserts. |
| 291 | insertDate | `DateTime` | Insert Date |
| 292 | invoiceNumber | `Float` | Invoice Number |
| 293 | jRNUpdateDate | `Date` | JRN Update Date |
| 294 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 295 | lastSignature | `String` | Last Signature |
| 296 | locationID | `String` | Internal ID to uniquely identify the Property |
| 297 | nRBusinessID | `String` | Business ID |
| 298 | nafApeHotelCode | `String` | NAF/APE code of the hotel at the time of bill generation. |
| 299 | nameId | `Float` | Name ID |
| 300 | nameTaxType | `String` | Name Tax Type |
| 301 | netAmount1 | `Float` | Net Amount 1 |
| 302 | netAmount10 | `Float` | Net Amount 10 |
| 303 | netAmount11 | `Float` | Net Amount 11 |
| 304 | netAmount12 | `Float` | Net Amount 12 |
| 305 | netAmount13 | `Float` | Net Amount 13 |
| 306 | netAmount14 | `Float` | Net Amount 14 |
| 307 | netAmount15 | `Float` | Net Amount 15 |
| 308 | netAmount16 | `Float` | Net Amount 16 |
| 309 | netAmount17 | `Float` | Net Amount 17 |
| 310 | netAmount18 | `Float` | Net Amount 18 |
| 311 | netAmount19 | `Float` | Net Amount 19 |
| 312 | netAmount2 | `Float` | Net Amount 2 |
| 313 | netAmount20 | `Float` | Net Amount 20 |
| 314 | netAmount3 | `Float` | Net Amount 3 |
| 315 | netAmount4 | `Float` | Net Amount 4 |
| 316 | netAmount5 | `Float` | Net Amount 5 |
| 317 | netAmount6 | `Float` | Net Amount 6 |
| 318 | netAmount7 | `Float` | Net Amount 7 |
| 319 | netAmount8 | `Float` | Net Amount 8 |
| 320 | netAmount9 | `Float` | Net Amount 9 |
| 321 | numberOfPages | `Float` | Number of pages for a given bill. |
| 322 | operaFiscalFolioStatus | `String` | This coulumn is used to store the status of Fiscal Folio /Payload Generation. The values will be SUCCESS - Payload has been sent successfully OFFLINE - User confirmed to generate Offline Folio i.e. Folio will be generated but Fiscal Folio/Payload not generated FAILURE - User do not want to create OFFLINE FOLIO but as FISCAL service is not available so the status is FAILURE i.e. in this case VOID Folio generated with FAILURE Fiscal Folio Status BLANK/NULL - Fiscal Printing is turned off or Past data after the upgrade. |
| 323 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 324 | pageNumber | `Float` | Stores the page number within the bill generation. |
| 325 | palmVideoFlag | `String` | Indicator to identify if the bill was generated from Video checkout or PALM.  (V->Video  P->PALM). |
| 326 | partnerFiscalFolioStatus | `String` | Partner Fiscal Folio Status |
| 327 | payeeAddress | `String` | Payee Address |
| 328 | payeeCountry | `String` | Payee Country |
| 329 | payeeFirstName | `String` | Payee First Name |
| 330 | payeeLastName | `String` | Payee Last Name |
| 331 | payeeName | `String` | Payee Name used for signature generation. |
| 332 | payeeNameID | `Float` | Payee Name ID |
| 333 | payeePostalCode | `String` | Payee Postal Code |
| 334 | payeeTaxID1 | `String` | Payee Tax ID 1 |
| 335 | payeeTaxID2 | `String` | Payee Tax ID 2 |
| 336 | payeeZipCode | `String` | Payee Zip Code used for signature generation. |
| 337 | paymentDate | `Date` | Payment Date |
| 338 | perpetualAmount | `Float` | Perpetual Amount. |
| 339 | pnet1Amt | `Float` | Parallel Net1 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 340 | pnet10Amt | `Float` | Parallel Net10 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 341 | pnet11Amt | `Float` | Parallel Net11 extension to the existing pnet amount. |
| 342 | pnet12Amt | `Float` | Parallel Net12 extension to the existing pnet amount. |
| 343 | pnet13Amt | `Float` | Parallel Net13 extension to the existing pnet amount. |
| 344 | pnet14Amt | `Float` | Parallel Net14 extension to the existing pnet amount. |
| 345 | pnet15Amt | `Float` | Parallel Net15 extension to the existing pnet amount. |
| 346 | pnet16Amt | `Float` | Parallel Net16 extension to the existing pnet amount. |
| 347 | pnet17Amt | `Float` | Parallel Net17 extension to the existing pnet amount. |
| 348 | pnet18Amt | `Float` | Parallel Net18 extension to the existing pnet amount. |
| 349 | pnet19Amt | `Float` | Parallel Net19 extension to the existing pnet amount. |
| 350 | pnet2Amt | `Float` | Parallel Net2 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 351 | pnet20Amt | `Float` | Parallel Net20 extension to the existing pnet amount. |
| 352 | pnet3Amt | `Float` | Parallel Net3 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 353 | pnet4Amt | `Float` | Parallel Net4 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 354 | pnet5Amt | `Float` | Parallel Net5 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 355 | pnet6Amt | `Float` | Parallel Net6 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 356 | pnet7Amt | `Float` | Parallel Net7 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 357 | pnet8Amt | `Float` | Parallel Net8 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 358 | pnet9Amt | `Float` | Parallel Net9 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 359 | postitSequenceNumber | `Float` | Postit Sequence Number |
| 360 | postitYN | `String` | Postit YN |
| 361 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 362 | printerQueueName | `String` | Printer Queue Name |
| 363 | profileTypeCode | `String` | Profile Type Code |
| 364 | promotionalText1 | `String` | Text returned by the credit card company |
| 365 | promotionalText2 | `String` | Text returned by the credit card company |
| 366 | property | `String` | Code to uniquely identify the Property |
| 367 | propertyBillPrefix | `String` | Property Bill Prefix |
| 368 | propertyTaxNumber | `String` | Property Tax Number |
| 369 | ptax1Amt | `Float` | Parallel Total tax1 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 370 | ptax10Amt | `Float` | Parallel Total tax10 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 371 | ptax11Amt | `Float` | Parallel Total tax11 amount extension to the existing ptax amounts. |
| 372 | ptax12Amt | `Float` | Parallel Total tax12 amount extension to the existing ptax amounts. |
| 373 | ptax13Amt | `Float` | Parallel Total tax13 amount extension to the existing ptax amounts. |
| 374 | ptax14Amt | `Float` | Parallel Total tax14 amount extension to the existing ptax amounts. |
| 375 | ptax15Amt | `Float` | Parallel Total tax15 amount extension to the existing ptax amounts. |
| 376 | ptax16Amt | `Float` | Parallel Total tax16 amount extension to the existing ptax amounts. |
| 377 | ptax17Amt | `Float` | Parallel Total tax17 amount extension to the existing ptax amounts. |
| 378 | ptax18Amt | `Float` | Parallel Total tax18 amount extension to the existing ptax amounts. |
| 379 | ptax19Amt | `Float` | Parallel Total tax19 amount extension to the existing ptax amounts. |
| 380 | ptax2Amt | `Float` | Parallel Total tax2 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 381 | ptax20Amt | `Float` | Parallel Total tax20 amount extension to the existing ptax amounts. |
| 382 | ptax3Amt | `Float` | Parallel Total tax3 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 383 | ptax4Amt | `Float` | Parallel Total tax4 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 384 | ptax5Amt | `Float` | Parallel Total tax5 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 385 | ptax6Amt | `Float` | Parallel Total tax6 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 386 | ptax7Amt | `Float` | Parallel Total tax7 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 387 | ptax8Amt | `Float` | Parallel Total tax8 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 388 | ptax9Amt | `Float` | Parallel Total tax9 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 389 | ptotNonrevNonTaxable | `Float` | Parallel total non revenue amount that is not taxable. |
| 390 | ptotNonrevTaxable | `Float` | Parallel total non revenue amount that is taxable. |
| 391 | ptotRevNonTaxable | `Float` | Parallel total revenue amount that is not taxable. |
| 392 | ptotRevTaxable | `Float` | Parallel total revenue amount that is taxable. |
| 393 | realPerpetualAmount | `Float` | Real perpetual amount at the time of generating the bill. |
| 394 | reservationNameId | `Float` | Resv Name ID |
| 395 | resortCity | `String` | City of the hotel at the time of bill generation. |
| 396 | resortCountry | `String` | Country of the hotel at the time of bill generation. |
| 397 | resortFullAddress | `String` | Property Full Address |
| 398 | resortZipcodeCode | `String` | Zipcode of the hotel at the time of bill generation. |
| 399 | revisionNo | `Float` | Revision Number |
| 400 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 401 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 402 | roomNumber | `String` | Room Number |
| 403 | seqNumber | `Float` | Sequence No |
| 404 | signature | `String` | Signature |
| 405 | signatureKeyVersion | `String` | Signature Key Version |
| 406 | softwareVersion | `String` | OPERA software version at the time of bill generation. |
| 407 | tax1RateType | `String` | Tax Rate Type 1 of the bill for which Tax Code 1 is attached as one of the taxes. |
| 408 | tax2RateType | `String` | Tax Rate Type 2 of the bill for which Tax Code 2 is attached as one of the taxes. |
| 409 | taxAmount1 | `Float` | Tax Amount 1 |
| 410 | taxAmount10 | `Float` | Tax Amount 10 |
| 411 | taxAmount11 | `Float` | Tax Amount 11 |
| 412 | taxAmount12 | `Float` | Tax Amount 12 |
| 413 | taxAmount13 | `Float` | Tax Amount 13 |
| 414 | taxAmount14 | `Float` | Tax Amount 14 |
| 415 | taxAmount15 | `Float` | Tax Amount 15 |
| 416 | taxAmount16 | `Float` | Tax Amount 16 |
| 417 | taxAmount17 | `Float` | Tax Amount 17 |
| 418 | taxAmount18 | `Float` | Tax Amount 18 |
| 419 | taxAmount19 | `Float` | Tax Amount 19 |
| 420 | taxAmount2 | `Float` | Tax Amount 2 |
| 421 | taxAmount20 | `Float` | Tax Amount 20 |
| 422 | taxAmount3 | `Float` | Tax Amount 3 |
| 423 | taxAmount4 | `Float` | Tax Amount 4 |
| 424 | taxAmount5 | `Float` | Tax Amount 5 |
| 425 | taxAmount6 | `Float` | Tax Amount 6 |
| 426 | taxAmount7 | `Float` | Tax Amount 7 |
| 427 | taxAmount8 | `Float` | Tax Amount 8 |
| 428 | taxAmount9 | `Float` | Tax Amount 9 |
| 429 | taxCode1 | `String` | Tax Code 1 |
| 430 | taxCode10 | `String` | Tax Code 10 |
| 431 | taxCode11 | `String` | Tax Code 11 |
| 432 | taxCode12 | `String` | Tax Code 12 |
| 433 | taxCode13 | `String` | Tax Code 13 |
| 434 | taxCode14 | `String` | Tax Code 14 |
| 435 | taxCode15 | `String` | Tax Code 15 |
| 436 | taxCode16 | `String` | Tax Code 16 |
| 437 | taxCode17 | `String` | Tax Code 17 |
| 438 | taxCode18 | `String` | Tax Code 18 |
| 439 | taxCode19 | `String` | Tax Code 19 |
| 440 | taxCode2 | `String` | Tax Code 2 |
| 441 | taxCode20 | `String` | Tax Code 20 |
| 442 | taxCode3 | `String` | Tax Code 3 |
| 443 | taxCode4 | `String` | Tax Code 4 |
| 444 | taxCode5 | `String` | Tax Code 5 |
| 445 | taxCode6 | `String` | Tax Code 6 |
| 446 | taxCode7 | `String` | Tax Code 7 |
| 447 | taxCode8 | `String` | Tax Code 8 |
| 448 | taxCode9 | `String` | Tax Code 9 |
| 449 | taxCodeDesc1 | `String` | Tax Code Description 1 |
| 450 | taxCodeDesc10 | `String` | Tax Code Description 10 |
| 451 | taxCodeDesc11 | `String` | Tax Code Description 11 |
| 452 | taxCodeDesc12 | `String` | Tax Code Description 12 |
| 453 | taxCodeDesc13 | `String` | Tax Code Description 13 |
| 454 | taxCodeDesc14 | `String` | Tax Code Description 14 |
| 455 | taxCodeDesc15 | `String` | Tax Code Description 15 |
| 456 | taxCodeDesc16 | `String` | Tax Code Description 16 |
| 457 | taxCodeDesc17 | `String` | Tax Code Description 17 |
| 458 | taxCodeDesc18 | `String` | Tax Code Description 18 |
| 459 | taxCodeDesc19 | `String` | Tax Code Description 19 |
| 460 | taxCodeDesc2 | `String` | Tax Code Description 2 |
| 461 | taxCodeDesc20 | `String` | Tax Code Description 20 |
| 462 | taxCodeDesc3 | `String` | Tax Code Description 3 |
| 463 | taxCodeDesc4 | `String` | Tax Code Description 4 |
| 464 | taxCodeDesc5 | `String` | Tax Code Description 5 |
| 465 | taxCodeDesc6 | `String` | Tax Code Description 6 |
| 466 | taxCodeDesc7 | `String` | Tax Code Description 7 |
| 467 | taxCodeDesc8 | `String` | Tax Code Description 8 |
| 468 | taxCodeDesc9 | `String` | Tax Code Description 9 |
| 469 | taxId | `String` | Tax ID |
| 470 | taxRate1 | `Float` | Tax Rate 1 amount of the bill for which Tax Code 1 is attached as one of the taxes. |
| 471 | taxRate10 | `Float` | Tax Rate 10 amount of the bill for which Tax Code 10  is attached as one of the taxes. |
| 472 | taxRate11 | `Float` | Tax Rate 11 amount of the bill for which Tax Code 11  is attached as one of the taxes. |
| 473 | taxRate12 | `Float` | Tax Rate 12 amount of the bill for which Tax Code 12 is attached as one of the taxes. |
| 474 | taxRate13 | `Float` | Tax Rate 13 amount of the bill for which Tax Code 13 is attached as one of the taxes. |
| 475 | taxRate14 | `Float` | Tax Rate 14 amount of the bill for which Tax Code 14 is attached as one of the taxes. |
| 476 | taxRate15 | `Float` | Tax Rate 15 amount of the bill for which Tax Code 15 is attached as one of the taxes. |
| 477 | taxRate16 | `Float` | Tax Rate 16 amount of the bill for which Tax Code 16 is attached as one of the taxes. |
| 478 | taxRate17 | `Float` | Tax Rate 17 amount of the bill for which Tax Code 17 is attached as one of the taxes. |
| 479 | taxRate18 | `Float` | Tax Rate 18 amount of the bill for which Tax Code 18 is attached as one of the taxes. |
| 480 | taxRate19 | `Float` | Tax Rate 19 amount of the bill for which Tax Code 19 is attached as one of the taxes. |
| 481 | taxRate2 | `Float` | Tax Rate 2 amount of the bill for which Tax Code 2 is attached as one of the taxes. |
| 482 | taxRate20 | `Float` | Tax Rate 20 amount of the bill for which Tax Code 20 is attached as one of the taxes. |
| 483 | taxRate3 | `Float` | Tax Rate 3 amount of the bill for which Tax Code 3 is attached as one of the taxes. |
| 484 | taxRate4 | `Float` | Tax Rate 4 amount of the bill for which Tax Code 4 is attached as one of the taxes. |
| 485 | taxRate5 | `Float` | Tax Rate 5 amount of the bill for which Tax Code 5 is attached as one of the taxes. |
| 486 | taxRate6 | `Float` | Tax Rate 6 amount of the bill for which Tax Code 6 is attached as one of the taxes. |
| 487 | taxRate7 | `Float` | Tax Rate 7 amount of the bill for which Tax Code 7 is attached as one of the taxes. |
| 488 | taxRate8 | `Float` | Tax Rate 8 amount of the bill for which Tax Code 8 is attached as one of the taxes. |
| 489 | taxRate9 | `Float` | Tax Rate 9 amount of the bill for which Tax Code 9 is attached as one of the taxes. |
| 490 | tax10RateType | `String` | Tax Rate Type 10 of the bill for which Tax Code 10 is attached as one of the taxes. |
| 491 | tax11RateType | `String` | Tax Rate Type 11 of the bill for which Tax Code 11 is attached as one of the taxes. |
| 492 | tax12RateType | `String` | Tax Rate Type 12 of the bill for which Tax Code 12 is attached as one of the taxes. |
| 493 | tax13RateType | `String` | Tax Rate Type 13 of the bill for which Tax Code 13 is attached as one of the taxes. |
| 494 | tax14RateType | `String` | Tax Rate Type 14 of the bill for which Tax Code 14 is attached as one of the taxes. |
| 495 | tax15RateType | `String` | Tax Rate Type 15 of the bill for which Tax Code 15 is attached as one of the taxes. |
| 496 | tax16RateType | `String` | Tax Rate Type 16 of the bill for which Tax Code 16 is attached as one of the taxes. |
| 497 | tax17RateType | `String` | Tax Rate Type 17 of the bill for which Tax Code 17 is attached as one of the taxes. |
| 498 | tax18RateType | `String` | Tax Rate Type 18 of the bill for which Tax Code 18 is attached as one of the taxes. |
| 499 | tax19RateType | `String` | Tax Rate Type 19 of the bill for which Tax Code 19 is attached as one of the taxes. |
| 500 | tax20RateType | `String` | Tax Rate Type 20 of the bill for which Tax Code 20 is attached as one of the taxes. |
| 501 | tax3RateType | `String` | Tax Rate Type 3 of the bill for which Tax Code 3 is attached as one of the taxes. |
| 502 | tax4RateType | `String` | Tax Rate Type 4 of the bill for which Tax Code 4 is attached as one of the taxes. |
| 503 | tax5RateType | `String` | Tax Rate Type 5 of the bill for which Tax Code 5 is attached as one of the taxes. |
| 504 | tax6RateType | `String` | Tax Rate Type 6 of the bill for which Tax Code 6 is attached as one of the taxes. |
| 505 | tax7RateType | `String` | Tax Rate Type 7 of the bill for which Tax Code 7 is attached as one of the taxes. |
| 506 | tax8RateType | `String` | Tax Rate Type 8 of the bill for which Tax Code 8 is attached as one of the taxes. |
| 507 | tax9RateType | `String` | Tax Rate Type 9 of the bill for which Tax Code 9 is attached as one of the taxes. |
| 508 | terminal | `String` | Terminal |
| 509 | totalGrossAmount | `Float` | Total Gross Amount |
| 510 | totalNetAmount | `Float` | Total Net Amount |
| 511 | totalNonRevenueNonTaxableAmount | `Float` | Total non revenue amount that is non taxable. |
| 512 | totalNonRevenueTaxableAmount | `Float` | Total non revenue amount that is not taxable. |
| 513 | totalNonTaxableAmount | `Float` | Total non taxable amount. |
| 514 | totalNonTaxableRevenue | `Float` | Total revenue amount that is non taxable. |
| 515 | totalPaidOuts | `Float` | Total paid outs. |
| 516 | totalTax | `Float` | Total Tax |
| 517 | totalTaxableRevenue | `Float` | Total revenue amount that is taxable. |
| 518 | transactLastSignatureHash | `String` | Last Signature for Transaction Totals. |
| 519 | transactSignatureHash | `String` | Signature hash for Transaction Totals. |
| 520 | transactSignatureKeyVersion | `String` | Signature key version for Transaction Totals. |
| 521 | transactionSignature | `String` | Transaction Signature Value. |
| 522 | trxServiceType | `String` | Transaction Service Type |
| 523 | uDFC01 | `String` | UDFC01 |
| 524 | uDFC02 | `String` | UDFC02 |
| 525 | uDFC03 | `String` | UDFC03 |
| 526 | uDFC04 | `String` | UDFC04 |
| 527 | uDFC05 | `String` | UDFC05 |
| 528 | uDFC06 | `String` | UDFC06 |
| 529 | uDFC07 | `String` | UDFC07 |
| 530 | uDFC08 | `String` | UDFC08 |
| 531 | uDFC09 | `String` | UDFC09 |
| 532 | uDFC10 | `String` | UDFC10 |
| 533 | uDFC11 | `String` | UDFC11 |
| 534 | uDFC12 | `String` | UDFC12 |
| 535 | uDFC13 | `String` | UDFC13 |
| 536 | uDFC14 | `String` | UDFC14 |
| 537 | uDFC15 | `String` | UDFC15 |
| 538 | uDFC16 | `String` | UDFC16 |
| 539 | uDFC17 | `String` | UDFC17 |
| 540 | uDFC18 | `String` | UDFC18 |
| 541 | uDFC19 | `String` | UDFC19 |
| 542 | uDFC20 | `String` | UDFC20 |
| 543 | uDFC21 | `String` | UDFC21 |
| 544 | uDFC22 | `String` | UDFC22 |
| 545 | uDFC23 | `String` | UDFC23 |
| 546 | uDFC24 | `String` | UDFC24 |
| 547 | uDFC25 | `String` | UDFC25 |
| 548 | uDFC26 | `String` | UDFC26 |
| 549 | uDFC27 | `String` | UDFC27 |
| 550 | uDFC28 | `String` | UDFC28 |
| 551 | uDFC29 | `String` | UDFC29 |
| 552 | uDFC30 | `String` | UDFC30 |
| 553 | uDFC31 | `String` | UDFC31 |
| 554 | uDFC32 | `String` | UDFC32 |
| 555 | uDFC33 | `String` | UDFC33 |
| 556 | uDFC34 | `String` | UDFC34 |
| 557 | uDFC35 | `String` | UDFC35 |
| 558 | uDFC36 | `String` | UDFC36 |
| 559 | uDFC37 | `String` | UDFC37 |
| 560 | uDFC38 | `String` | UDFC38 |
| 561 | uDFC39 | `String` | UDFC39 |
| 562 | uDFC40 | `String` | UDFC40 |
| 563 | uDFD01 | `Date` | UDFD01 |
| 564 | uDFD02 | `Date` | UDFD02 |
| 565 | uDFD03 | `Date` | UDFD03 |
| 566 | uDFD04 | `Date` | UDFD04 |
| 567 | uDFD05 | `Date` | UDFD05 |
| 568 | uDFD06 | `Date` | UDFD06 |
| 569 | uDFD07 | `Date` | UDFD07 |
| 570 | uDFD08 | `Date` | UDFD08 |
| 571 | uDFD09 | `Date` | UDFD09 |
| 572 | uDFD10 | `Date` | UDFD10 |
| 573 | uDFD11 | `Date` | UDFD11 |
| 574 | uDFD12 | `Date` | UDFD12 |
| 575 | uDFD13 | `Date` | UDFD13 |
| 576 | uDFD14 | `Date` | UDFD14 |
| 577 | uDFD15 | `Date` | UDFD15 |
| 578 | uDFD16 | `Date` | UDFD16 |
| 579 | uDFD17 | `Date` | UDFD17 |
| 580 | uDFD18 | `Date` | UDFD18 |
| 581 | uDFD19 | `Date` | UDFD19 |
| 582 | uDFD20 | `Date` | UDFD20 |
| 583 | uDFN01 | `Float` | UDFN01 |
| 584 | uDFN02 | `Float` | UDFN02 |
| 585 | uDFN03 | `Float` | UDFN03 |
| 586 | uDFN04 | `Float` | UDFN04 |
| 587 | uDFN05 | `Float` | UDFN05 |
| 588 | uDFN06 | `Float` | UDFN06 |
| 589 | uDFN07 | `Float` | UDFN07 |
| 590 | uDFN08 | `Float` | UDFN08 |
| 591 | uDFN09 | `Float` | UDFN09 |
| 592 | uDFN10 | `Float` | UDFN10 |
| 593 | uDFN11 | `Float` | UDFN11 |
| 594 | uDFN12 | `Float` | UDFN12 |
| 595 | uDFN13 | `Float` | UDFN13 |
| 596 | uDFN14 | `Float` | UDFN14 |
| 597 | uDFN15 | `Float` | UDFN15 |
| 598 | uDFN16 | `Float` | UDFN16 |
| 599 | uDFN17 | `Float` | UDFN17 |
| 600 | uDFN18 | `Float` | UDFN18 |
| 601 | uDFN19 | `Float` | UDFN19 |
| 602 | uDFN20 | `Float` | UDFN20 |
| 603 | uDFN21 | `Float` | UDFN21 |
| 604 | uDFN22 | `Float` | UDFN22 |
| 605 | uDFN23 | `Float` | UDFN23 |
| 606 | uDFN24 | `Float` | UDFN24 |
| 607 | uDFN25 | `Float` | UDFN25 |
| 608 | uDFN26 | `Float` | UDFN26 |
| 609 | uDFN27 | `Float` | UDFN27 |
| 610 | uDFN28 | `Float` | UDFN28 |
| 611 | uDFN29 | `Float` | UDFN29 |
| 612 | uDFN30 | `Float` | UDFN30 |
| 613 | uDFN31 | `Float` | UDFN31 |
| 614 | uDFN32 | `Float` | UDFN32 |
| 615 | uDFN33 | `Float` | UDFN33 |
| 616 | uDFN34 | `Float` | UDFN34 |
| 617 | uDFN35 | `Float` | UDFN35 |
| 618 | uDFN36 | `Float` | UDFN36 |
| 619 | uDFN37 | `Float` | UDFN37 |
| 620 | uDFN38 | `Float` | UDFN38 |
| 621 | uDFN39 | `Float` | UDFN39 |
| 622 | uDFN40 | `Float` | UDFN40 |
| 623 | updTimestamp | `DateTime` | Timestamp to capture the exact order of updates. |
| 624 | updateDate | `DateTime` | Update Date |
| 625 | updateUser | `Float` | Update User |
| 626 | userID | `Float` | User ID |
| 627 | userName | `String` | The name of the user who created the record. |
| 628 | voidNumber | `Float` | Void Number |
| 629 | voidReason | `String` | This column will store the reason for voiding the folio. |
| 630 | workingDocId | `Float` | Working Doc ID |
| 631 | xnet1Amt | `Float` | Xnet1 Amount |
| 632 | xnet10Amt | `Float` | Xnet10 Amount |
| 633 | xnet11Amt | `Float` | Xnet11 Amount |
| 634 | xnet12Amt | `Float` | Xnet12 Amount |
| 635 | xnet13Amt | `Float` | Xnet13 Amount |
| 636 | xnet14Amt | `Float` | Xnet14 Amount |
| 637 | xnet15Amt | `Float` | Xnet15 Amount |
| 638 | xnet16Amt | `Float` | Xnet16 Amount |
| 639 | xnet17Amt | `Float` | Xnet17 Amount |
| 640 | xnet18Amt | `Float` | Xnet18 Amount |
| 641 | xnet19Amt | `Float` | Xnet19 Amount |
| 642 | xnet2Amt | `Float` | Xnet2 Amount |
| 643 | xnet20Amt | `Float` | Xnet20 Amount |
| 644 | xnet3Amt | `Float` | Xnet3 Amount |
| 645 | xnet4Amt | `Float` | Xnet4 Amount |
| 646 | xnet5Amt | `Float` | Xnet5 Amount |
| 647 | xnet6Amt | `Float` | Xnet6 Amount |
| 648 | xnet7Amt | `Float` | Xnet7 Amount |
| 649 | xnet8Amt | `Float` | Xnet8 Amount |
| 650 | xnet9Amt | `Float` | Xnet9 Amount |
| 651 | xtax1Amt | `Float` | Total tax1 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 652 | xtax10Amt | `Float` | Total tax10 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 653 | xtax11Amt | `Float` | Total tax11 amount extension to the existing xtax amounts. |
| 654 | xtax12Amt | `Float` | Total tax12 amount extension to the existing xtax amounts. |
| 655 | xtax13Amt | `Float` | Total tax13 amount extension to the existing xtax amounts. |
| 656 | xtax14Amt | `Float` | Total tax14 amount extension to the existing xtax amounts. |
| 657 | xtax15Amt | `Float` | Total tax15 amount extension to the existing xtax amounts. |
| 658 | xtax16Amt | `Float` | Total tax16 amount extension to the existing xtax amounts. |
| 659 | xtax17Amt | `Float` | Total tax17 amount extension to the existing xtax amounts. |
| 660 | xtax18Amt | `Float` | Total tax18 amount extension to the existing xtax amounts. |
| 661 | xtax19Amt | `Float` | Total tax19 amount extension to the existing xtax amounts. |
| 662 | xtax2Amt | `Float` | Total tax2 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 663 | xtax20Amt | `Float` | Total tax20 amount extension to the existing xtax amounts. |
| 664 | xtax3Amt | `Float` | Total tax3 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 665 | xtax4Amt | `Float` | Total tax4 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 666 | xtax5Amt | `Float` | Total tax5 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 667 | xtax6Amt | `Float` | Total tax6 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 668 | xtax7Amt | `Float` | Total tax7 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 669 | xtax8Amt | `Float` | Total tax8 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 670 | xtax9Amt | `Float` | Total tax9 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsForeignCurrencyDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | abbreviation | `String` | Abbreviation |
| 2 | activeYN | `String` | Active YN |
| 3 | canDeleteYn | `String` | Can Delete Y/N |
| 4 | chainCode | `String` | Chain Code |
| 5 | currencyActionId | `Float` | Curr Action ID |
| 6 | currencyCode | `String` | Currency Code |
| 7 | currencyDescription | `String` | Currency Description |
| 8 | currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | decimals | `Float` | Decimals |
| 11 | deletedFlag | `String` | Deleted Flag |
| 12 | foreignCurrencyID | `String` | Foreign Currency ID |
| 13 | formatMask | `String` | Format Mask |
| 14 | inactiveDate | `DateTime` | Inactive Date |
| 15 | inactiveflag | `String` | Inactive Flag |
| 16 | insertDate | `DateTime` | Insert Date |
| 17 | insertUser | `Float` | Insert User |
| 18 | internalDeletedflag | `String` | Deleted Flag |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | mobileYn | `String` | Indicates if this Currency Exchange Rate is available for consumer mobility. |
| 22 | multiply | `Float` | Multiply |
| 23 | orderBy | `Float` | Order By |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | previousLocalCurrencyYn | `String` | This will be significant after EURO conversion. The currency before the Euro conversion gets a value Y. |
| 26 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 27 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 28 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 29 | sellCurrency | `String` | Indicates whether this currency code can be sold though currency exchange. |
| 30 | trianMethodYn | `String` | Indicates whether the currency is Euro participant. |
| 31 | updateDate | `DateTime` | Update Date |
| 32 | updateUser | `Float` | Update User |
| 33 | usedForCcPaymentsYn | `String` | Indicates if this currency can be used for Credit Card payments. |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsInvoicePaymentDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | appliedAmount | `Float` | Amount Applied. you can apply one payment partially to one transactions and partially to another transaction. |
| 2 | businessDate | `Date` | Date on which the payment was applied. |
| 3 | cExchangeDate | `Date` | Central Xchange Date |
| 4 | cExchangeRate | `Float` | Central Xchange Rate |
| 5 | cashierId | `Float` | Cashier ID |
| 6 | centralAppliedAmount | `Float` | Central Applied Amount |
| 7 | chainCode | `String` | Chain Code |
| 8 | consumptionTransactionNumber | `Float` | Consumption Transaction Number |
| 9 | consumptionTrx | `Float` | Transaction no for which you are applying to other transactions. |
| 10 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 11 | deletedFlag | `String` | Deleted Flag |
| 12 | insertDate | `DateTime` | Insert Date |
| 13 | insertUser | `Float` | Insert User |
| 14 | invoicepaymentid | `Float` | Invoicepaymentid |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | locationID | `String` | Internal ID to uniquely identify the Property |
| 18 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 19 | paymentApplicationId | `Float` | Unique Sequence id for each payment applications. |
| 20 | paymentTransactionNumber | `Float` | Payment Transaction Number |
| 21 | paymentTrx | `Float` | Transaction no for which you want to pay for the other transactions. |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Code to uniquely identify the Property |
| 24 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 25 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 26 | updateDate | `DateTime` | Update Date |
| 27 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsProfileAllInformationDetailsType

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

### FinancialTransactionDetailsRateCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBRateCycle | `String` | Not null value in this column indicates that this is ASB Rate. This column also specifies the cycle of ASB rate. MC=Fixed Calendar Month Cycle WC=Fixed Calendar Week Cycle MF= Floating Monthly Cycle WF=Floating Weekly Cycle. |
| 2 | addition | `String` | Amount to be added to the base rate when shown on rate query |
| 3 | advBaseRateCode | `String` | With Advanced Base Rate Parameter ON this field stores the rate code on which this rate schedule is dynamically based on. |
| 4 | advBaseRounding | `String` | Indicates how rounding of advanced dynamic rate calculation is performed.[U]p  [D]own [N]one [C] -Up - keep decimal [F] -Down - keep decimal. |
| 5 | advanceBaseCompareYN | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BAR rate code. |
| 6 | advanceDailyBaseYN | `String` | Indicates if this rate code is an Advanced Daily Base Rate. |
| 7 | advanceDailyRateYN | `String` | Indicates if this rate code is an Advanced Daily Rate. |
| 8 | alternateRateCode | `String` | Alternative rate code if current rate is not available |
| 9 | availabilityUpdateYn | `String` | Flag to indicate whether to send Rate code to AVH or not. |
| 10 | backToBackYN | `String` | Back To Back YN |
| 11 | baseAmount | `Float` | Base Amount |
| 12 | baseFltPct | `String` | Flat or Percentage of the Base Rate |
| 13 | baseRateCode | `String` | Base Rate Code |
| 14 | baseRounding | `String` | Indicates if rounding of rate is required |
| 15 | baseType | `String` | Indicating a rate type such as flat rate or percentage rate. Possible values are: FLAT DIFFERENTIAL and NULL. |
| 16 | bbarBaseAmount | `Float` | This column use to store Percentage or Amount difference between BAR Rate code and this Rate Code. |
| 17 | bbarBaseFltPct | `String` | This flag column identify that amount column represent Flat or Percentage value. |
| 18 | bbarBaseRounding | `String` | This column identify the rounding formula for the BBAR Rate calculation. |
| 19 | bbarBasedYn | `String` | This column will identify that Rate Code is Best BAR based rate code or not. Possible values are Y/N. |
| 20 | bbarCompareYn | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BBAR rate code. |
| 21 | bbarYn | `String` | Bbar Y/N |
| 22 | blockName | `String` | Block Name |
| 23 | breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| 24 | breakfastPrice | `Float` | Breakfast Price |
| 25 | businessDate | `Date` | Business Date |
| 26 | bypassHurdleYn | `String` | In case of ORMS when this flag is Y system ignore this rate code from Hurdle Check. |
| 27 | bypassRankCheckYn | `String` | Indicates that this rate code will not go through rank validations if value is 'Y'. |
| 28 | cBaseAmount | `Float` | Central Base Amount |
| 29 | cBbarBaseAmount | `Float` | Central Bbar Base Amount |
| 30 | cBreakfastPrice | `Float` | Central Bfst Price |
| 31 | cDbaseAmount | `Float` | Central Dbase Amount |
| 32 | cDiscountRateAmount | `Float` | Central Discount Rate Amount |
| 33 | cDoubleRoomSupplementPrice | `Float` | Central Dbl Rm Supplement Price |
| 34 | cExchangeDate | `Date` | Central Xchange Date |
| 35 | cExchangeRate | `Float` | Central Xchange Rate |
| 36 | cRateFloor | `Float` | Central Rate Floor |
| 37 | cRateLevel | `Float` | Central Rate Level |
| 38 | cRodBaseAmount | `Float` | Central Rod Base Amount |
| 39 | cRoomAssignmentValue | `Float` | Central Room Assignment Value |
| 40 | catPackageCode | `String` | Stores the catering package code linked to this rate code. |
| 41 | cateringPackageYN | `String` | Specifies if a catering package is linked to this rate code. |
| 42 | centralMarketCode | `String` | Central Market Code |
| 43 | centralMarketDescription | `String` | Central Market Description |
| 44 | centralMarketGroupCode | `String` | Central Market Group Code |
| 45 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 46 | centralRateBucket | `String` | Central Rate Bucket |
| 47 | centralRateBucketDescription | `String` | Central Rate Bucket Description |
| 48 | centralRateCategory | `String` | Central Rate Category |
| 49 | centralRateCategoryDescription | `String` | Central Rate Category Description |
| 50 | centralRateClass | `String` | Central Rate Class |
| 51 | centralRateClassDescription | `String` | Central Rate Class Description |
| 52 | centralRoomType | `String` | Central Room Type |
| 53 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 54 | centralSourceCode | `String` | Central Source Code |
| 55 | centralSourceDescription | `String` | Central Source Description |
| 56 | centralSourceGroupCode | `String` | Central Source Group Code |
| 57 | centralSourceGroupDescription | `String` | Central Source Group Description |
| 58 | changeState | `String` | Indicates the state of chaange of the rate code with values null=enabled D=disabled P=changes pending of approval |
| 59 | commissionPercent | `Float` | This field is used to populate rate code commission percentage for informational purposes for GDS and ORS reservation agents |
| 60 | commissionCode | `String` | Commission Code |
| 61 | commissionYn | `String` | Are commissions allowed for this rate code? Y/N |
| 62 | commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| 63 | commissionableYn | `String` | Commissionable Y/N |
| 64 | complimentaryYN | `String` | Complimentary YN |
| 65 | currCodeDecimalPos | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating the decimal position specific to the received the currency code. |
| 66 | currencyCode | `String` | Currency Code |
| 67 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 68 | dailyRatesYn | `String` | Daily Rates Y/N |
| 69 | dayUseYN | `String` | Day use reservation Y/N. |
| 70 | daysWhenClosedToArrival | `String` | Days the rate restriction is not available for arrival |
| 71 | dbaseAmount | `Float` | Indicates either Flat amount or Percentage increase or decrease from the dynamic base rate. |
| 72 | dbaseCompareYn | `String` | This flag identify that while checking availability calculated based amount should be compared to rate detail of rate code or not. |
| 73 | dbaseFltPct | `String` | Flat or Percentage of the dynamic base rate code. |
| 74 | dbaseRateCode | `String` | The rate code on which this rate shedule is dynamically based on. |
| 75 | dbaseRounding | `String` | Indicates if rounding of dynamic rate calculation is required. |
| 76 | dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| 77 | defaultToHighestBarYn | `String` | For BAR dependent Rate Code this flag indicates that when all BAR Rates are closed the Rate Amount should be calculated based on the highest BAR Rate Amount instead of based on its own Rate Detail. |
| 78 | deletedFlag | `String` | Deleted Flag |
| 79 | depositMaturityPreference | `String` | Stores the Deposit maturity preference. |
| 80 | deptCode | `String` | Department code for the transaction. |
| 81 | discountRateAmount | `Float` | Discount rate amount value. |
| 82 | discountRatePercentageYn | `String` | Indicates if discount rate amount is a percentage value. |
| 83 | discountYN | `String` | Discount Flag. |
| 84 | displaySequence | `Float` | Display Sequence |
| 85 | displaySet | `String` | Display Set |
| 86 | distributeYn | `String` | Indicates if the profile should be distributed to the external database. |
| 87 | doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| 88 | endDate | `Date` | End Date |
| 89 | eventProperty | `String` | Indicates if the value set for the specific property. |
| 90 | exchangeType | `String` | Exchange Type |
| 91 | externallyControlledYN | `String` | Externally Controlled YN |
| 92 | extraPersonChargeBegins | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating at person level the extra charge begins. |
| 93 | fitDiscountLevel | `Float` | Fit Discount Level. |
| 94 | fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| 95 | flatYN | `String` | Flat YN |
| 96 | folioText | `String` | Text displayed on the Folio |
| 97 | frequentFlyerYN | `String` | Frequent Flyer YN |
| 98 | gDSAllowedYN | `String` | Is this rate code available for GDS |
| 99 | groupCode | `String` | Group Code |
| 100 | highlightRateAmountYn | `String` | To highlight on the rate query |
| 101 | houseUseYN | `String` | House-Use YN |
| 102 | inactiveDate | `Date` | Inactive Date |
| 103 | insertDate | `DateTime` | Insert Date |
| 104 | insertUser | `Float` | Insert User |
| 105 | internalLocationId | `String` | Location ID |
| 106 | internalOrganizationId | `Float` | Organization ID |
| 107 | jRNUpdateDate | `Date` | JRN Update Date |
| 108 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 109 | locationID | `String` | Internal ID to uniquely identify the Property |
| 110 | longInfo | `String` | Long Info |
| 111 | loyaltyProgramYN | `String` | Flag to indicate if this is a loyalty program |
| 112 | mandateResvProfiles | `String` | Indicates mandatory reservation profiles. This is used to force entry of profiles on the reservation header if this rate is picked. |
| 113 | marketCode | `String` | Market Code |
| 114 | marketDescription | `String` | Market Description |
| 115 | marketGroupCode | `String` | Market Group Code |
| 116 | marketGroupDescription | `String` | Market Group Description |
| 117 | marshaRateProgram | `String` | Contains the rate program information from the MARSHA interface. |
| 118 | maximumDaysAdvanceBooking | `Float` | Maximum Days Advance Booking |
| 119 | maximumLengthOfStay | `Float` | Maximum Length of Stay |
| 120 | maximumOccupancy | `Float` | Maximum Occupancy |
| 121 | mfnUploadYn | `String` | Flag used to determine if the rate code is to be sent to MyFidelio.net if the rate is being received from a V6 V7 V8 or OPMS on a lower version on which flag used to determine if the rate code is to be sent to MyFidelio.net does not exist on the rate header. |
| 122 | minimumDaysAdvanceBooking | `Float` | Minimum Days Advance Booking |
| 123 | minimumOccupancy | `Float` | Minimum Occupancy |
| 124 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 125 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 126 | multiplication | `String` | Amount to be multiplied to the base rate when shown on rate query |
| 127 | myFidelioUploadYN | `String` | MyFidelio Upload YN |
| 128 | negotiatedYN | `String` | Property is negotiated of search criteria or not. |
| 129 | occupancyBasedYn | `String` | Indicates if the rate code is occupancy based. |
| 130 | occupancyLevel | `Float` | Indicates the occupancy level for hurdle evaluation. |
| 131 | operatorType | `String` | The operator type to use during the calculation of base rates. (ADD_TO SUBTRACT) |
| 132 | orderBy | `Float` | Order By |
| 133 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 134 | originalRateCode | `String` | Original Rate Code |
| 135 | orsSellSequence | `Float` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| 136 | overridePackageYn | `String` | Indicates if we need to override package for hurdle evaluation. |
| 137 | ownerRateYN | `String` | Indicates Owners Rate Code. This is used to perform rolling noshow. |
| 138 | packageTransactionCode | `String` | Package Transaction Code |
| 139 | packageTransactionCodeWeekend | `String` | Package Transaction Code Weekend |
| 140 | packageTransactionTaxInclYN | `String` | Wrapper transaction code tax inclusive Y/N |
| 141 | packageTransactionTaxIncludedYN | `String` | Transaction code is inclusive of tax Y/N |
| 142 | packageTransactionWkTaxInclYN | `String` | Wrapper transaction code tax inclusive for weekend days Y/N |
| 143 | packageYN | `String` | Package YN |
| 144 | packages | `String` | Packages |
| 145 | pendingApprovalYn | `String` | Indicates whether the rate code is pending for approval or not |
| 146 | postingRhythm | `String` | Posting Rhythm |
| 147 | postingRhythmNights | `Float` | Number of nights for posting rhythm. |
| 148 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 149 | printRateYn | `String` | Print Rate Y/N |
| 150 | privilegedRestrictionYn | `String` | Indicates if restriction for rate is privileged or not. |
| 151 | privilegedYn | `String` | Indicates if rate is privileged or not. |
| 152 | profitTransactionCode | `String` | Profit Transaction Code |
| 153 | property | `String` | Code to uniquely identify the Property |
| 154 | propertyName | `String` | Property Name |
| 155 | rankAdjustmentFactor | `Float` | Any number between -10 and +10. This adjustment factor will be applied to the daily ranking value of table RESORT_DAY_TYPE_DATES for the stay date to determine the Rate code rank value. |
| 156 | rankValue | `Float` | Rank Value |
| 157 | rateBucket | `String` | Yield rate bucket |
| 158 | rateBucketDescription | `String` | Rate Bucket Description |
| 159 | rateCalendarYn | `String` | Indicates if rate Calendar factors such as adder/multiplier should be used for price calculation. |
| 160 | rateCategory | `String` | Rate Category |
| 161 | rateCategoryDescription | `String` | Rate Category Description |
| 162 | rateClass | `String` | Rate Class |
| 163 | rateClassDescription | `String` | Rate Class Description |
| 164 | rateCodeId | `String` | Rate Code ID |
| 165 | rateCodeLockedYn | `String` | Rate Code Locked Y/N |
| 166 | rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| 167 | rateFloorOverrideYn | `String` | This flag indicates if the Rate Floor Rate is overridden for a particular Rate Code. |
| 168 | rateIncludesTaxYn | `String` | Does this rate include tax? Y/N |
| 169 | rateLabel | `String` | Rate Label |
| 170 | rateLevel | `Float` | Rate Level this rate code belongs to. |
| 171 | rateUpdateYN | `String` | Needs to send this rate to GDS or not. |
| 172 | rateinfoUrl | `String` | Rateinfo Url |
| 173 | redemptionRateYN | `String` | Redemption Rate YN |
| 174 | regionalAvailabilityYN | `String` | Regional Availability YN |
| 175 | repeatPostingRhythmYn | `String` | Indicates if the posting rhythm on the rate code is repeated until the end of the stay otherwise the posting rhythm is applied only once. |
| 176 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 177 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 178 | rodBaseAmount | `Float` | Rod Base Amount |
| 179 | rodBaseFltPct | `String` | Rod Base Flt Pct |
| 180 | rodBaseRounding | `String` | Rod Base Rounding |
| 181 | rodBasedYn | `String` | Is the group code rate of day based |
| 182 | rodYn | `String` | Rod Y/N |
| 183 | roomAssignmentValue | `Float` | Room Assignment Value |
| 184 | roomType | `String` | Room Type |
| 185 | roomTypeDescription | `String` | Room Type Description |
| 186 | sdowBeginBookingDate | `Date` | Holds a copy of the column begin_booking_date while the rate code is disabled or with changes pending of approval |
| 187 | sdowEndBookingDate | `Date` | Holds a copy of the column end_booking_date while the rate code is disabled or with changes pending of approval |
| 188 | serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| 189 | servicePerc | `Float` | Service Percentage included. |
| 190 | shortInfo | `String` | Information to be used in the rate query |
| 191 | showRateAmountYn | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| 192 | sourceCode | `String` | Source Code |
| 193 | sourceDescription | `String` | Source Description |
| 194 | sourceGroupCode | `String` | Source Group Code |
| 195 | sourceGroupDescription | `String` | Source Group Description |
| 196 | taxIncludedPerc | `Float` | Percentage of included Tax. |
| 197 | taxIncludedYn | `String` | Tax is included in this rate. |
| 198 | tieredYN | `String` | Indicates if the rate is a tiered rate. |
| 199 | transactionCode | `String` | Rate transaction code |
| 200 | transactionCodeWeekend | `String` | Transaction Code Weekend |
| 201 | transactionTaxWeekendIncludedYN | `String` | Transaction code is inclusive of tax for weekend days Y/N |
| 202 | unitOfLengthOfStay | `Float` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| 203 | updateDate | `DateTime` | Update Date |
| 204 | updateUser | `Float` | Update User |
| 205 | upsellYn | `String` | Indicates if the rate code can be upsold |
| 206 | voucherBenefitRateYn | `String` | Flag to indicate if this is a voucher benefit rate code. |
| 207 | weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| 208 | wkDeptCode | `String` | Wk Dept Code |
| 209 | yieldAs | `String` | Yield As |
| 210 | yieldableYN | `String` | Yieldable YN |
| 211 | ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsRateSeasonDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralSeasonCode | `String` | Central Season Code |
| 2 | centralSeasonDescription | `String` | Central Season Description |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| 5 | displayColor | `String` | Display Color |
| 6 | endDate | `Date` | End Date |
| 7 | inactiveDate | `Date` | Inactive Date |
| 8 | inactiveYn | `String` | Inactive Y/N |
| 9 | insertDate | `DateTime` | Insert Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | locationID | `String` | Internal ID to uniquely identify the Property |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | property | `String` | Code to uniquely identify the Property |
| 17 | rateCode | `String` | Rate Code |
| 18 | ratecodeid | `String` | Ratecodeid |
| 19 | rateseasonid | `String` | Rateseasonid |
| 20 | repItem | `String` | Reporting Item |
| 21 | repItemName | `String` | Reporting Item Name |
| 22 | repItemOrderby | `Float` | Reporting Item Orderby |
| 23 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 24 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 25 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 26 | seasonCode | `String` | Season Code |
| 27 | seasonDescription | `String` | Season Description |
| 28 | startDate | `Date` | Start Date |
| 29 | updateDate | `DateTime` | Update Date |
| 30 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsReportCalendarDetailsType

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

### FinancialTransactionDetailsReservationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| 2 | accompaniedYN | `String` | Accompanied YN |
| 3 | accompanyingName | `String` | Accompanying guest names. |
| 4 | actualCheckInDateTime | `DateTime` | Actual Check In Date Time |
| 5 | actualCheckOutDateTime | `DateTime` | Actual Check Out Date Time |
| 6 | actualCheckInDate | `Date` | Actual Check-In Date |
| 7 | actualCheckInTime | `String` | Actual Check-In Time |
| 8 | actualCheckOutDate | `Date` | Actual Check-Out Date |
| 9 | actualCheckOutTime | `String` | Actual Check-Out Time |
| 10 | addressId | `Float` | Address ID |
| 11 | addresseeNameId | `Float` | Addressee Name ID |
| 12 | adults | `Float` | Adults |
| 13 | adultsTaxFree | `Float` | Adults Tax Free |
| 14 | advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| 15 | agencyprofileid | `Float` | Agencyprofileid |
| 16 | allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| 17 | allotmentid | `Float` | Block ID |
| 18 | amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| 19 | amenityLevelCode | `String` | Amenity Level Code |
| 20 | amountPercent | `Float` | Amount Percent |
| 21 | approvalAmount | `Float` | Approval Amount |
| 22 | approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| 23 | approvalCode | `String` | Approval Code |
| 24 | arrivalComments | `String` | Arrival Comments |
| 25 | arrivalDate | `Date` | Arrival Date |
| 26 | arrivalDateTime | `DateTime` | Arrival Date Time |
| 27 | arrivalEstimateTime | `Date` | Arrival Estimate Time |
| 28 | arrivalTime | `String` | Activity begin time |
| 29 | arrivaltransportid | `String` | Arrivaltransportid |
| 30 | attachedDate | `Date` | Attached Date |
| 31 | authorizedBillingYN | `String` | Not used. |
| 32 | authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| 33 | authorizerId | `Float` | Authorizer ID |
| 34 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 35 | autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| 36 | autoSettleDays | `Float` | Auto Settle Days |
| 37 | autoSettleType | `String` | Auto Settle Type |
| 38 | autoSettleYN | `String` | Auto Settle YN |
| 39 | awardCode | `String` | Award Code |
| 40 | awardCode1 | `String` | Award code 1 |
| 41 | awardCode2 | `String` | Award code 2 |
| 42 | awardCode3 | `String` | Award code 3 |
| 43 | awardCode4 | `String` | Award Code 4 |
| 44 | awardCode5 | `String` | Award code 5 |
| 45 | awardMembershipID | `Float` | Award Membership ID |
| 46 | awardVoucher1 | `String` | Award Voucher number 1 |
| 47 | awardVoucher2 | `String` | Award Voucher number 2 |
| 48 | awardVoucher3 | `String` | Award Voucher number 3 |
| 49 | awardVoucher4 | `String` | Award Voucher number 4 |
| 50 | awardVoucher5 | `String` | Award Voucher number 5 |
| 51 | awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| 52 | awdUpgrTo | `String` | Room Type after the Upgrade Award |
| 53 | backToBackYN | `String` | Back To Back YN |
| 54 | balance | `Float` | Balance on the account. |
| 55 | baseRateAmount | `Float` | Base Rate Amount |
| 56 | baseRateCode | `String` | Base Rate Code |
| 57 | baseRateCurrencyCode | `String` | Base Rate Currency Code |
| 58 | basedOnRule | `String` | Based On Rule |
| 59 | baseratecurrencyid | `String` | Baseratecurrencyid |
| 60 | beginCity | `String` | Begin City |
| 61 | beginDatetime | `DateTime` | Begin Datetime |
| 62 | beginDistrict | `String` | Begin District |
| 63 | beginState | `String` | Begin State |
| 64 | beginSystemDateTime | `DateTime` | Stores the actual guest check in date and time. |
| 65 | billNumber | `String` | Bill Number |
| 66 | billingContact | `String` | Billing Contact |
| 67 | billingContactDisplayName | `String` | Billing Contact Display Name |
| 68 | billingContactId | `Float` | Billing Contact ID |
| 69 | billingContactName | `String` | Billing Contact Name |
| 70 | billingcontactprofileid | `Float` | Billing Contact Profile ID |
| 71 | blockCode | `String` | Block Code |
| 72 | blockCreateDate | `DateTime` | Block Create Date |
| 73 | blockID | `Float` | Block ID |
| 74 | blockName | `String` | Block Name |
| 75 | blockResort | `String` | Property this block belongs to. |
| 76 | blockStatus | `String` | Block Status |
| 77 | bonusCheckId | `Float` | Bonus Check ID |
| 78 | bookedRoomCategory | `String` | Booked Room Category |
| 79 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 80 | businessDateCreated | `Date` | Business Date Created |
| 81 | businessDatetimeCreated | `DateTime` | Business Datetime Created |
| 82 | bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| 83 | cAutoPostAmount | `Float` | Central Auto Post Amount |
| 84 | cBaseRateAmount | `Float` | Central Base Rate Amount |
| 85 | cDiscountAmount | `Float` | C Discount Amount |
| 86 | cDiscountAmt | `Float` | C Discount Amt |
| 87 | cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| 88 | cExchangeDate | `Date` | Central Xchange Date |
| 89 | cExchangeRate | `Float` | Central Xchange Rate |
| 90 | cFixedCharge | `Float` | Central Fixed Charge |
| 91 | cGrossRateAmount | `Float` | Central Gross Rate Amt |
| 92 | cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| 93 | cNetRoomAmount | `Float` | Central Net Room Amt |
| 94 | cOriginalBaseRate | `Float` | Central Original Base Rate |
| 95 | cPackageAmount | `Float` | Central Pkg Amt |
| 96 | cPackageTax | `Float` | Central Pkg Tax |
| 97 | cRateAmount | `Float` | C Rate Amount |
| 98 | cRoomCost | `Float` | Central Room Cost |
| 99 | cRoomTax | `Float` | Central Room Tax |
| 100 | cShareAmountOriginal | `Float` | Central Share Amount Original |
| 101 | cUpsellCharge | `Float` | Central Upsell Charge |
| 102 | cancelDate | `Date` | Cancel Date |
| 103 | cancelReason | `String` | Cancel Reason |
| 104 | cancelTime | `String` | Cancel Time |
| 105 | cancellationDate | `DateTime` | Cancellation Date |
| 106 | cancellationDatetime | `DateTime` | Cancellation Datetime |
| 107 | cancellationNumber | `String` | Cancellation Number |
| 108 | cancellationReasonDescription | `String` | Cancellation Reason Description |
| 109 | cancellationreasonid | `String` | Cancellationreasonid |
| 110 | cancelledBy | `String` | The user who canceled this Reservation. |
| 111 | cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| 112 | cardNumberByMembershipType | `String` | Card Number by Membership Type |
| 113 | centralApprovalAmount | `Float` | Central Approval Amount |
| 114 | centralCancelReason | `String` | Central Cancel Reason |
| 115 | centralCommissionCode | `String` | Central Commission Code |
| 116 | centralCommissionDescription | `String` | Central Commission Description |
| 117 | centralCreditLimit | `Float` | Central Credit Limit |
| 118 | centralDiscountReason | `String` | Central Discount Reason |
| 119 | centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| 120 | centralFBRevenue | `Float` | Central FB Revenue |
| 121 | centralGuestType | `String` | Central Guest Type |
| 122 | centralHurdle | `Float` | Central Hurdle |
| 123 | centralPackageCode | `String` | Central Package Code |
| 124 | centralPackageCodeDescription | `String` | Central Package Code Description |
| 125 | centralPackageForecastGroup | `String` | Central Package Forecast Group |
| 126 | centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| 127 | centralPaymentAmount | `Float` | Central Payment Amount |
| 128 | centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| 129 | centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| 130 | centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| 131 | centralPromotionDescription | `String` | Central Promotion Description |
| 132 | centralRateableValue | `Float` | Central Rateable Value |
| 133 | centralReservationType | `String` | Central Reservation Type |
| 134 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 135 | centralRoomRevenue | `Float` | Central Room Revenue |
| 136 | centralRoomTypeCode | `String` | Central Room Type Code |
| 137 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 138 | centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| 139 | centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| 140 | centralSharedRoomRate | `Float` | Central Shared Room Rate |
| 141 | centralSpecialRequestDescription | `String` | Central Special Request Description |
| 142 | centralTaxType | `String` | Central Tax Type |
| 143 | centralTaxTypeDescription | `String` | Central Tax Type Description |
| 144 | centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| 145 | centralTotalRevenue | `Float` | Central Total Revenue |
| 146 | centralTotalRoomRate | `Float` | Central Total Room Rate |
| 147 | centralWaitlistPriority | `String` | Central Waitlist Priority |
| 148 | centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| 149 | centralWaitlistReason | `String` | Central Waitlist Reason |
| 150 | centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| 151 | chainCode | `String` | Chain Code |
| 152 | channelDescription | `String` | Channel Description |
| 153 | channelOrderBy | `Float` | Channel Order By |
| 154 | channelid | `String` | Channelid |
| 155 | checkInInitiatedBy | `String` | Check In Initiated By |
| 156 | checkinDuration | `Float` | Duration in seconds to complete Check-In |
| 157 | childBucket1 | `Float` | Child Bucket 1 |
| 158 | childBucket4 | `Float` | Child Bucket 4 |
| 159 | childBucket5 | `Float` | Child Bucket 5 |
| 160 | children | `Float` | Children |
| 161 | childrenAgeGroup2 | `Float` | Children Age Group 2) |
| 162 | childrenAgeGroup3 | `Float` | Children Age Group 3) |
| 163 | childrenAges | `String` | Children Ages |
| 164 | commissionCode | `String` | Commission Code |
| 165 | commissionDescription | `String` | Commission Description |
| 166 | commissionHoldCode | `String` | Commission Hold Code |
| 167 | commissionPaid | `Float` | Commission Paid |
| 168 | commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| 169 | commissionableYN | `String` | Commissionable YN |
| 170 | commissionid | `String` | Commissionid |
| 171 | compHouse | `String` | Comp House |
| 172 | compTypeCode | `String` | Comp Type Code |
| 173 | companyCity | `String` | Company City |
| 174 | companyCountry | `String` | Company Country |
| 175 | companyID | `Float` | Company ID |
| 176 | companyName | `String` | Company Name |
| 177 | companyProfileCorporateID | `String` | Company Profile Corporate ID |
| 178 | companyProfileID | `Float` | Company Profile ID |
| 179 | complimentaryYN | `String` | Complimentary YN |
| 180 | compreasonid | `String` | Compreasonid |
| 181 | computedResvStatus | `String` | Calculated reservation status. |
| 182 | confirmationLegNumber | `Float` | Confirmation Leg Number. |
| 183 | confirmationNo | `String` | Shared Confirmation Number |
| 184 | consumerYn | `String` | Consumer Y/N |
| 185 | contactName | `String` | Contact Name; UDFC02 on reservation. |
| 186 | contactProfileID | `Float` | Contact Profile ID |
| 187 | contactProfileName | `String` | Contact Profile Name |
| 188 | createdBy | `String` | The name of the user who created the record. |
| 189 | createdByDefaultResort | `String` | Created By Default Property |
| 190 | createdDate | `Date` | Created Date |
| 191 | createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| 192 | creditCardAuthDate | `Date` | Credit Card Auth Date |
| 193 | creditCardId | `Float` | Credit Card ID |
| 194 | creditLimit | `Float` | Credit Limit |
| 195 | creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| 196 | cribs | `Float` | Cribs |
| 197 | currencyCode | `String` | Currency Code |
| 198 | customReferenceNumber | `String` | Custom Reference Number |
| 199 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 200 | dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| 201 | deletedFlag | `String` | Deleted Flag |
| 202 | departtransportid | `String` | Departtransportid |
| 203 | departureComments | `String` | Departure Comments |
| 204 | departureDate | `Date` | Departure Date |
| 205 | departureDateTime | `Date` | Departure Date Time |
| 206 | departureTime | `String` | Departure Time |
| 207 | departureTransportCode | `String` | Departure Transport Code |
| 208 | departureTransportationYN | `String` | Departure Transportation YN |
| 209 | depositMaturityType | `String` | Stores the Deposit maturity preference. |
| 210 | detatchedDate | `Date` | Detatched Date |
| 211 | detatchedYN | `String` | Detatched YN |
| 212 | directBillVerifyResponse | `String` | Direct Bill Verify Response |
| 213 | directbillauthby | `Float` | Directbillauthby |
| 214 | discountAmount | `Float` | Discount Amount |
| 215 | discountAmt | `Float` | Discount Amount |
| 216 | discountPercent | `Float` | Discount Percentage. |
| 217 | discountPrcnt | `Float` | Discount Prcnt |
| 218 | discountReason | `String` | Discount Reason |
| 219 | discountReasonDescription | `String` | Discount Reason Description |
| 220 | discountreasonid | `String` | Discountreasonid |
| 221 | displayColor | `String` | Display Color |
| 222 | dmlSeqNumber | `Float` | Dml Sequence No |
| 223 | doNotMoveRoom | `String` | Do Not Move Room |
| 224 | doNotMoveYN | `String` | Do not move room flag. |
| 225 | dropOffCarrierCode | `String` | Drop Off Carrier Code |
| 226 | dropOffDate | `Date` | Drop Off Date |
| 227 | dropOffStation | `String` | Drop Off Station |
| 228 | dropOffTime | `String` | Drop Off Time |
| 229 | dropOffType | `String` | Drop Off Type |
| 230 | dropOffTypeDescription | `String` | Drop Off Type Description |
| 231 | eTRComments | `String` | Comments related to Estimated Time of Return. |
| 232 | effectiveRateAmount | `Float` | Not used. |
| 233 | eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| 234 | emailAddress | `String` | Email Address |
| 235 | emailFolioYn | `String` | Email Folio Y/N |
| 236 | emailId | `Float` | Email ID |
| 237 | emailYn | `String` | Email Y/N |
| 238 | endCity | `String` | End City |
| 239 | endDatetime | `DateTime` | End Datetime |
| 240 | endDistrict | `String` | End District |
| 241 | endState | `String` | End State |
| 242 | endbusinessdate | `Date` | Endbusinessdate |
| 243 | entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| 244 | entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| 245 | esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| 246 | estimatedDepartureTime | `Date` | Estimated Departure Time |
| 247 | eventId | `Float` | Event ID |
| 248 | exchangePostingType | `String` | Exchange Posting Type |
| 249 | exchangeRate | `Float` | Exchange Rate |
| 250 | excludeFromAutoAuthorizationYN | `String` | Exclude From Auto Authorization YN |
| 251 | expectedTimeOfReturnETR | `DateTime` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| 252 | exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| 253 | extSegNo | `Float` | Not used |
| 254 | extSeqNumber | `Float` | Not used |
| 255 | extensionId | `Float` | Internal extension number for the main reservation |
| 256 | externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| 257 | externalReference | `String` | External Reference |
| 258 | externalReferencesList | `String` | External References List |
| 259 | extraBeds | `Float` | Extra Beds |
| 260 | fBRevenue | `Float` | FB Revenue |
| 261 | fBRevenueRemaining | `Float` | F&B Revenue Remaining |
| 262 | faxId | `Float` | Fax ID |
| 263 | faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| 264 | feature | `String` | This stores the codes for the rooms features. Currently not used |
| 265 | financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| 266 | fixedCharge | `Float` | Not used. |
| 267 | fixedRateYN | `String` | Fixed Rate YN |
| 268 | folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| 269 | folioCloseDate | `Date` | Date the folio was changed to closed. |
| 270 | folioNumber | `String` | Folio Number |
| 271 | folioText1 | `String` | Folio Text1 |
| 272 | folioText2 | `String` | Folio Text2 |
| 273 | foreignCurrencyID | `String` | Foreign Currency ID |
| 274 | freeChild | `Float` | Free Child |
| 275 | frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| 276 | grossRateFuture | `Float` | Gross Rate Future |
| 277 | grossRatePast | `Float` | Gross Rate Past |
| 278 | groupName | `String` | Group Name |
| 279 | groupProfileARNumber | `Float` | Group Profile AR Number |
| 280 | groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| 281 | groupProfileClientID | `String` | Group Profile Client ID |
| 282 | groupProfileID | `Float` | Group Profile ID |
| 283 | groupProfileName | `String` | Group Profile Name |
| 284 | guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| 285 | guaranteecodeid | `String` | Guaranteecodeid |
| 286 | guestFirstName | `String` | Guest First Name |
| 287 | guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| 288 | guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| 289 | guestSignature | `String` | Signature of the guest |
| 290 | guestStatus | `String` | Used for Police/Tourist Export |
| 291 | guestType | `String` | Guest Type |
| 292 | guestprofileid | `Float` | Guestprofileid |
| 293 | gueststatusid | `String` | Gueststatusid |
| 294 | guesttypeid | `String` | Guesttypeid |
| 295 | housekeepingServiceTime | `String` | Housekeeping Service Time |
| 296 | hurdle | `Float` | Hurdle |
| 297 | hurdleOverride | `String` | Hurdle Override |
| 298 | iDByMembershipClass | `String` | ID by Membership Class |
| 299 | iDByMembershipType | `String` | ID by Membership Type |
| 300 | individualCity | `String` | Guest Address. |
| 301 | individualCountry | `String` | Country of the guest |
| 302 | individualFirstName | `String` | Individual First Name |
| 303 | individualLastName | `String` | Individual Last Name |
| 304 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 305 | insertDate | `DateTime` | Insert Date |
| 306 | insertDateTime | `DateTime` | Insert DateTime |
| 307 | insertUser | `Float` | Insert User |
| 308 | intermediaryYn | `String` | Intermediary Y/N |
| 309 | internalAwardMembershipId | `Float` | Award Membership ID |
| 310 | internalBaseratecode | `String` | Baseratecode |
| 311 | internalBlockId | `Float` | Block ID. |
| 312 | internalCompanyprofileid | `Float` | Companyprofileid |
| 313 | internalGroupprofileid | `Float` | Groupprofileid |
| 314 | internalSourceprofileid | `Float` | Sourceprofileid |
| 315 | itemsQuantities | `String` | Items and Quantities |
| 316 | jRNUpdateDate | `Date` | JRN Update Date |
| 317 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 318 | keyValidUntil | `Date` | Key Valid Until |
| 319 | lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| 320 | lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| 321 | lastRoomNumber | `String` | Not used. |
| 322 | lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| 323 | leadTimeDays | `Float` | Lead Time for ordering |
| 324 | lengthOfStay | `Float` | Length of Stay |
| 325 | linkedArrivalDate | `DateTime` | Linked Arrival Date |
| 326 | linkedDepartureDate | `DateTime` | Linked Departure Date |
| 327 | linkedRoomType | `String` | Linked Room Type |
| 328 | listOfMembershipID | `String` | Membership ID |
| 329 | localBaseRateAmount | `Float` | Local Base Rate Amount |
| 330 | locationID | `String` | Internal ID to uniquely identify the Property |
| 331 | loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| 332 | mailYn | `String` | Mail Y/N |
| 333 | manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| 334 | marketCode | `String` | Market Code |
| 335 | marketid | `String` | Marketid |
| 336 | mcGenBeginDistrict | `String` | Mc Gen Begin District |
| 337 | mcGenBeginState | `String` | Mc Gen Begin State |
| 338 | mcGenEndDistrict | `String` | Mc Gen End District |
| 339 | mcGenEndState | `String` | Mc Gen End State |
| 340 | mcGenNextCountry | `String` | Mc Gen Next Country |
| 341 | mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| 342 | memberDescription | `String` | Member Description |
| 343 | memberLevel | `String` | Member Level |
| 344 | memberNumber | `String` | Member Number |
| 345 | membershipClass | `String` | Membership Class |
| 346 | membershipClassDescription | `String` | Membership Class Description |
| 347 | membershipCode | `String` | Membership Code |
| 348 | membershipId | `Float` | Membership ID |
| 349 | membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| 350 | membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| 351 | mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| 352 | mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| 353 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 354 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 355 | mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| 356 | mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| 357 | name | `String` | Name |
| 358 | nameUsageType | `String` | Name Usage Type |
| 359 | nextCountry | `String` | Next Country |
| 360 | nextDestination | `String` | Country Specific Requirement for Nigeria. |
| 361 | numberOfRooms | `Float` | No of Rooms |
| 362 | operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| 363 | optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| 364 | optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| 365 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 366 | originCode | `String` | Origin Code |
| 367 | originOfBooking | `String` | Origin Of Booking |
| 368 | originalBaseRate | `Float` | Not used. |
| 369 | originalEndDate | `Date` | Original End Date |
| 370 | originalStartDate | `Date` | Original Start Date |
| 371 | ownerFfFlag | `String` | Owner Ff Flag |
| 372 | ownerOrFriendsFamily | `String` | Owner or Friends/Family |
| 373 | packageCode | `String` | Package Code |
| 374 | packageCodeDescription | `String` | Package Code Description |
| 375 | packageForecastGroup | `String` | Package Forecast Group |
| 376 | packageForecastGroupDescription | `String` | Package Forecast Group Description |
| 377 | parentReservationNameId | `Float` | Parent Resv Name ID |
| 378 | parentreservationid | `Float` | Parentreservationid |
| 379 | partAllotment | `String` | Part Allotment |
| 380 | partyCode | `String` | Party Code |
| 381 | paxNo | `Float` | Pax Number |
| 382 | paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| 383 | paymentMethod | `String` | Payment Method |
| 384 | paymentmethodid | `String` | Paymentmethodid |
| 385 | periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| 386 | phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| 387 | phoneId | `Float` | Phone ID |
| 388 | physicalQuantity | `Float` | Physical Quantity |
| 389 | pickUpCarrierCode | `String` | Pick Up Carrier Code |
| 390 | pickUpDate | `Date` | Pick Up Date |
| 391 | pickUpStation | `String` | Pick Up Station |
| 392 | pickUpTransportNumber | `String` | Pick Up Transport Number |
| 393 | pickUpType | `String` | Pick Up Type |
| 394 | pickUpTypeDescription | `String` | Pick Up Type Description |
| 395 | pickUpTime | `String` | Pick-Up Time |
| 396 | pickupRequiredYN | `String` | Pickup Required YN |
| 397 | points | `Float` | Points |
| 398 | pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| 399 | postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| 400 | postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| 401 | postingAllowedYN | `String` | Posting Allowed YN |
| 402 | preArrReviewedDt | `DateTime` | This date flags if and when the record was reviewed from pre-arrival screen. |
| 403 | preArrReviewedUser | `Float` | User id who reviewed the record. |
| 404 | preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| 405 | preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| 406 | preference | `String` | Preference |
| 407 | preferenceType | `String` | Preference Type |
| 408 | preferredRoomType | `String` | Preferred Room Type |
| 409 | previousCountry | `String` | Previous Country |
| 410 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 411 | primaryShare | `String` | Primary Share |
| 412 | printRateYN | `String` | Print Rate YN |
| 413 | projectedFBRevenue | `Float` | Projected FB Revenue |
| 414 | projectedRoomRevenue | `Float` | Projected Room Revenue |
| 415 | projectedTotalRevenue | `Float` | Projected Total Revenue |
| 416 | promotionCode | `String` | Promotion Code |
| 417 | promotionDescription | `String` | Promotion Description |
| 418 | property | `String` | Indicates if the value set for the specific property. |
| 419 | pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| 420 | pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| 421 | purgeDate | `DateTime` | Purge Date |
| 422 | purposeOfStay | `String` | Purpose of stay. |
| 423 | quantity | `Float` | Number of Rooms |
| 424 | queuePriority | `Float` | Queue priority of the reservation. |
| 425 | queueWaitTime | `Float` | Queue Wait Time |
| 426 | quoteId | `String` | Quote ID provided by external system. |
| 427 | rateAmount | `Float` | Rate Amount |
| 428 | rateCode | `String` | Rate Code |
| 429 | rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| 430 | rateTier | `Float` | Tier ID for the Rate Detail. |
| 431 | rateableValue | `Float` | Stay rateable value. |
| 432 | ratecodeid | `String` | Ratecodeid |
| 433 | rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| 434 | rdResvStatus | `String` | Rd Reservation Status |
| 435 | rdenBillingContactId | `Float` | Rden Billing Contact ID |
| 436 | rdenReservationContactId | `Float` | Rden Resv Contact ID |
| 437 | rdenReservationDate | `Date` | Rden Reservation Date |
| 438 | rdenResort | `String` | Rden Property |
| 439 | referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| 440 | registrationCardNo | `String` | Registration Card Number |
| 441 | registrationNumber | `Float` | Registration Number |
| 442 | reinstateDate | `DateTime` | Reinstate Date |
| 443 | repChannel | `String` | Reporting Channel |
| 444 | repChannelDescription | `String` | Reporting Channel Description |
| 445 | reportId | `String` | Report ID |
| 446 | resInsertSource | `String` | Reservation Insert Source |
| 447 | resInsertSourceType | `String` | Reservation Insert Source Type |
| 448 | reservationContactId | `Float` | Resv Contact ID |
| 449 | reservationDate | `DateTime` | Reservation Date |
| 450 | reservationNameID | `Float` | Reservation Name ID |
| 451 | reservationStatus | `String` | Reservation Status |
| 452 | reservationType | `String` | Reservation Type |
| 453 | reservationTypeDescription | `String` | Reservation Type Description |
| 454 | reservationid | `Float` | Reservationid |
| 455 | resort | `String` | Property |
| 456 | resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| 457 | restrictionOverride | `String` | Restriction Override |
| 458 | resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| 459 | resvNameid | `Float` | Reservation Nameid |
| 460 | resvNumber | `Float` | Not used in PMS currently. |
| 461 | resvcontactprofileid | `Float` | Resvcontactprofileid |
| 462 | revenueTypeCode | `String` | Revenue type (catering/rooms) |
| 463 | rhBillingContactId | `Float` | Rh Billing Contact ID |
| 464 | rhReservationContactId | `Float` | Rh Resv Contact ID |
| 465 | rhRoomFeatures | `String` | Rh Room Features |
| 466 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 467 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 468 | room | `String` | Room |
| 469 | roomCategory | `String` | Room Category |
| 470 | roomClass | `String` | Room Class |
| 471 | roomCost | `Float` | Room Cost |
| 472 | roomInstructions | `String` | Room Instructions |
| 473 | roomResort | `String` | Meeting Room Property |
| 474 | roomRevenue | `Float` | Room Revenue |
| 475 | roomRevenueRemaining | `Float` | Room Revenue Remaining |
| 476 | roomServiceTime | `String` | This is the Turndown room service time. |
| 477 | roomTypeDescription | `String` | Room Type Description |
| 478 | roomTypeToChargeCode | `String` | Room Type To Charge Code |
| 479 | roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| 480 | roomcategoryid | `String` | Roomcategoryid |
| 481 | roomid | `String` | Roomid |
| 482 | routingYN | `String` | Routing YN |
| 483 | scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| 484 | sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| 485 | sguestName | `String` | Sguest Name |
| 486 | shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| 487 | shareId | `Float` | Share ID. |
| 488 | shareName | `String` | Share Name |
| 489 | sharePrcnt | `Float` | Not used. |
| 490 | shareSeqNumber | `Float` | Type of revenue |
| 491 | shareOfRateAmount | `Float` | Share of Rate Amount |
| 492 | sharedGuestName | `String` | Shared Guest Name |
| 493 | sharedProfileID | `Float` | Shared Profile ID |
| 494 | sharedReservationStatus | `String` | Shared Reservation Status |
| 495 | sharingYN | `String` | Sharing YN |
| 496 | sourceCity | `String` | Source City |
| 497 | sourceCode | `String` | Source Code |
| 498 | sourceCountry | `String` | Source Country |
| 499 | sourceName | `String` | Source Name |
| 500 | sourceProfileARNumber | `Float` | Source Profile AR Number |
| 501 | sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| 502 | sourceProfileIATANumber | `String` | Source Profile IATA Number |
| 503 | sourceProfileID | `Float` | Source Profile ID |
| 504 | sourceProfileName | `String` | Source Profile Name |
| 505 | sourceid | `String` | Sourceid |
| 506 | specialRequest | `String` | Special Request |
| 507 | specialRequestDescription | `String` | Special Request Description |
| 508 | spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| 509 | spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| 510 | spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| 511 | spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| 512 | splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| 513 | splitfromreservationid | `Float` | Splitfromreservationid |
| 514 | statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| 515 | statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| 516 | stayRecordId | `Float` | Stay Record ID |
| 517 | suiteNumber | `String` | Suite Number |
| 518 | superSearchIndexText | `String` | Super Search Index Text |
| 519 | taRecordLocator | `String` | Ta Record Locator |
| 520 | taxExemptNumber | `String` | Tax exempt number on the profile |
| 521 | taxNumberOfStays | `Float` | Tax No of Stays |
| 522 | taxType | `String` | Tax Type |
| 523 | taxTypeDescription | `String` | Tax Type Description |
| 524 | taxtypeid | `String` | Taxtypeid |
| 525 | tiad | `String` | Tiad |
| 526 | ticketNos | `String` | Ticket Nos |
| 527 | totalCostOfStay | `Float` | Total Cost of Stay |
| 528 | totalRevenue | `Float` | Total Revenue |
| 529 | totalRevenueRemaining | `Float` | Total Revenue Remaining |
| 530 | totalRoomRate | `Float` | Total Room Rate |
| 531 | trackItGroups | `String` | Track It Groups |
| 532 | trackItTypes | `String` | Track It Types |
| 533 | transactionid | `Float` | Transactionid |
| 534 | travelAgentCity | `String` | Travel Agent Address. |
| 535 | travelAgentCountry | `String` | Travel Agent Country |
| 536 | travelAgentID | `Float` | Travel Agent ID |
| 537 | travelAgentName | `String` | Travel Agent Name |
| 538 | travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| 539 | travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| 540 | travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| 541 | travelAgentProfileID | `Float` | Travel Agent Profile ID |
| 542 | travelAgentProfileName | `String` | Travel Agent Profile Name |
| 543 | truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| 544 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 545 | turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| 546 | uDFC01 | `String` | UDFC01 |
| 547 | uDFC02 | `String` | UDFC02 |
| 548 | uDFC03 | `String` | UDFC03 |
| 549 | uDFC04 | `String` | UDFC04 |
| 550 | uDFC05 | `String` | UDFC05 |
| 551 | uDFC06 | `String` | UDFC06 |
| 552 | uDFC07 | `String` | UDFC07 |
| 553 | uDFC08 | `String` | UDFC08 |
| 554 | uDFC09 | `String` | UDFC09 |
| 555 | uDFC10 | `String` | UDFC10 |
| 556 | uDFC11 | `String` | UDFC11 |
| 557 | uDFC12 | `String` | UDFC12 |
| 558 | uDFC13 | `String` | UDFC13 |
| 559 | uDFC14 | `String` | UDFC14 |
| 560 | uDFC15 | `String` | UDFC15 |
| 561 | uDFC16 | `String` | UDFC16 |
| 562 | uDFC17 | `String` | UDFC17 |
| 563 | uDFC18 | `String` | UDFC18 |
| 564 | uDFC19 | `String` | UDFC19 |
| 565 | uDFC20 | `String` | UDFC20 |
| 566 | uDFC21 | `String` | UDFC21 |
| 567 | uDFC22 | `String` | UDFC22 |
| 568 | uDFC23 | `String` | UDFC23 |
| 569 | uDFC24 | `String` | UDFC24 |
| 570 | uDFC25 | `String` | UDFC25 |
| 571 | uDFC26 | `String` | UDFC26 |
| 572 | uDFC27 | `String` | UDFC27 |
| 573 | uDFC28 | `String` | UDFC28 |
| 574 | uDFC29 | `String` | UDFC29 |
| 575 | uDFC30 | `String` | UDFC30 |
| 576 | uDFC31 | `String` | UDFC31 |
| 577 | uDFC32 | `String` | UDFC32 |
| 578 | uDFC33 | `String` | UDFC33 |
| 579 | uDFC34 | `String` | UDFC34 |
| 580 | uDFC35 | `String` | UDFC35 |
| 581 | uDFC36 | `String` | UDFC36 |
| 582 | uDFC37 | `String` | UDFC37 |
| 583 | uDFC38 | `String` | UDFC38 |
| 584 | uDFC39 | `String` | UDFC39 |
| 585 | uDFC40 | `String` | UDFC40 |
| 586 | uDFD01 | `Date` | UDFD01 |
| 587 | uDFD02 | `Date` | UDFD02 |
| 588 | uDFD03 | `Date` | UDFD03 |
| 589 | uDFD04 | `Date` | UDFD04 |
| 590 | uDFD05 | `Date` | UDFD05 |
| 591 | uDFD06 | `Date` | UDFD06 |
| 592 | uDFD07 | `Date` | UDFD07 |
| 593 | uDFD08 | `Date` | UDFD08 |
| 594 | uDFD09 | `Date` | UDFD09 |
| 595 | uDFD10 | `Date` | UDFD10 |
| 596 | uDFD11 | `Date` | UDFD11 |
| 597 | uDFD12 | `Date` | UDFD12 |
| 598 | uDFD13 | `Date` | UDFD13 |
| 599 | uDFD14 | `Date` | UDFD14 |
| 600 | uDFD15 | `Date` | UDFD15 |
| 601 | uDFD16 | `Date` | UDFD16 |
| 602 | uDFD17 | `Date` | UDFD17 |
| 603 | uDFD18 | `Date` | UDFD18 |
| 604 | uDFD19 | `Date` | UDFD19 |
| 605 | uDFD20 | `Date` | UDFD20 |
| 606 | uDFN01 | `Float` | UDFN01 |
| 607 | uDFN02 | `Float` | UDFN02 |
| 608 | uDFN03 | `Float` | UDFN03 |
| 609 | uDFN04 | `Float` | UDFN04 |
| 610 | uDFN05 | `Float` | UDFN05 |
| 611 | uDFN06 | `Float` | UDFN06 |
| 612 | uDFN07 | `Float` | UDFN07 |
| 613 | uDFN08 | `Float` | UDFN08 |
| 614 | uDFN09 | `Float` | UDFN09 |
| 615 | uDFN10 | `Float` | UDFN10 |
| 616 | uDFN11 | `Float` | UDFN11 |
| 617 | uDFN12 | `Float` | UDFN12 |
| 618 | uDFN13 | `Float` | UDFN13 |
| 619 | uDFN14 | `Float` | UDFN14 |
| 620 | uDFN15 | `Float` | UDFN15 |
| 621 | uDFN16 | `Float` | UDFN16 |
| 622 | uDFN17 | `Float` | UDFN17 |
| 623 | uDFN18 | `Float` | UDFN18 |
| 624 | uDFN19 | `Float` | UDFN19 |
| 625 | uDFN20 | `Float` | UDFN20 |
| 626 | uDFN21 | `Float` | UDFN21 |
| 627 | uDFN22 | `Float` | UDFN22 |
| 628 | uDFN23 | `Float` | UDFN23 |
| 629 | uDFN24 | `Float` | UDFN24 |
| 630 | uDFN25 | `Float` | UDFN25 |
| 631 | uDFN26 | `Float` | UDFN26 |
| 632 | uDFN27 | `Float` | UDFN27 |
| 633 | uDFN28 | `Float` | UDFN28 |
| 634 | uDFN29 | `Float` | UDFN29 |
| 635 | uDFN30 | `Float` | UDFN30 |
| 636 | uDFN31 | `Float` | UDFN31 |
| 637 | uDFN32 | `Float` | UDFN32 |
| 638 | uDFN33 | `Float` | UDFN33 |
| 639 | uDFN34 | `Float` | UDFN34 |
| 640 | uDFN35 | `Float` | UDFN35 |
| 641 | uDFN36 | `Float` | UDFN36 |
| 642 | uDFN37 | `Float` | UDFN37 |
| 643 | uDFN38 | `Float` | UDFN38 |
| 644 | uDFN39 | `Float` | UDFN39 |
| 645 | uDFN40 | `Float` | UDFN40 |
| 646 | uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| 647 | updateDate | `DateTime` | Update Date |
| 648 | updateDatetime | `DateTime` | Update Datetime |
| 649 | updateUser | `Float` | Update User |
| 650 | updatedBy | `String` | Updated By |
| 651 | updatedByDefaultResort | `String` | Updated By Default Property |
| 652 | updatedDate | `Date` | Updated Date |
| 653 | updatedTime | `String` | Updated Time |
| 654 | upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| 655 | videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| 656 | visaExpiryDate | `Date` | Visa Expiry Date |
| 657 | visaIssueDate | `Date` | Visa Issue Date |
| 658 | visaNumber | `String` | Visa Number |
| 659 | waitlistComment | `String` | Waitlist Comment |
| 660 | waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| 661 | waitlistPriority | `String` | Waitlist Priority |
| 662 | waitlistPriorityDescription | `String` | Waitlist Priority Description |
| 663 | waitlistReason | `String` | Waitlist Reason |
| 664 | waitlistReasonDescription | `String` | Waitlist Reason Description |
| 665 | waitlistpriorityid | `String` | Waitlistpriorityid |
| 666 | waitlistreasonid | `String` | Waitlistreasonid |
| 667 | walkInYN | `String` | Walk-In YN |
| 668 | yieldableYn | `String` | Yieldable Y/N |
| 669 | ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsRevenuePackagesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | addToRateYN | `String` | Add To Rate YN |
| 2 | arrangementCode | `String` | Arrangement Code |
| 3 | beginBookingDate | `Date` | Begin Booking Date |
| 4 | bookingDuration | `Float` | Not used |
| 5 | calculationRule | `String` | Calculation Rule |
| 6 | cateringYn | `String` | Catering Y/N |
| 7 | centralPackageCode | `String` | Central Package Code |
| 8 | centralPackageCodeDescription | `String` | Central Package Code Description |
| 9 | centralPackageForecastGroup | `String` | Central Package Forecast Group |
| 10 | centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| 11 | currencyCode | `String` | Currency Code |
| 12 | currencyDesc | `String` | Currency Desc |
| 13 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 14 | deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| 15 | deliveryTimeReqrdYn | `String` | Indicates if a Delivery Time is required. |
| 16 | endBookingDate | `Date` | End Booking Date |
| 17 | externalLocked | `String` | External Locked |
| 18 | flexibleDurationYN | `String` | Flexible Duration YN |
| 19 | forecastGroupCode | `String` | Not used |
| 20 | forecastNextDayYN | `String` | Forecast Next Day YN |
| 21 | formula | `String` | Formula |
| 22 | genPlAtEodOfCoDate | `String` | Gen Pl At Eod of Co Date |
| 23 | insertDate | `DateTime` | Insert Date |
| 24 | insertUser | `Float` | Insert User |
| 25 | internalPostingrhythm | `String` | Postingrhythm |
| 26 | inventoriedYN | `String` | Inventoried YN |
| 27 | jRNUpdateDate | `Date` | JRN Update Date |
| 28 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 29 | locationID | `String` | Internal ID to uniquely identify the Property |
| 30 | longInfo | `String` | Long Info |
| 31 | maxPersons | `String` | Maximum number of persons |
| 32 | maximumPersons | `String` | Maximum Persons |
| 33 | minimumAdvBookDays | `Float` | Minimum Advance Booking Days required for the product. |
| 34 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 35 | outletCode | `String` | Outlet Code |
| 36 | overrideFixedRateYn | `String` | Override Fixed Rate Y/N |
| 37 | pOSAccountYN | `String` | POS Account YN |
| 38 | pOSNextDayYN | `String` | POS Next Day YN |
| 39 | packageCode | `String` | Package Code |
| 40 | packageCodeDescription | `String` | Package Code Description |
| 41 | packageCodeShortDescription | `String` | Package Code Short Description |
| 42 | packageForecastGroup | `String` | Package Forecast Group |
| 43 | packageForecastGroupDescription | `String` | Package Forecast Group Description |
| 44 | pkgForcastGroup | `String` | Package forcast group code |
| 45 | pkgforecastgrpid | `String` | Pkgforecastgrpid |
| 46 | postingRhythm | `String` | Posting Rhythm |
| 47 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 48 | printSeparateYN | `String` | Print Separate YN |
| 49 | product | `String` | Product |
| 50 | productType | `String` | Product Type |
| 51 | productid | `String` | Productid |
| 52 | property | `String` | Code to uniquely identify the Property |
| 53 | redemptionProductYN | `String` | Redemption Product YN |
| 54 | repItem | `String` | Reporting Item |
| 55 | repItemName | `String` | Reporting Item Name |
| 56 | repItemOrderby | `Float` | Reporting Item Orderby |
| 57 | repUpdateDate | `Date` | Reporting Updatedate |
| 58 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 59 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 60 | separatelySoldYN | `String` | Separately Sold YN |
| 61 | standardDuration | `Float` | Not used |
| 62 | standardPersons | `String` | Not used |
| 63 | ticketsYn | `String` | Indicates a Reservation Ticket Package. |
| 64 | updateDate | `DateTime` | Update Date |
| 65 | updateUser | `Float` | Update User |
| 66 | validFromTime | `Date` | Valid From Time |
| 67 | validToTime | `Date` | Valid To Time |
| 68 | webBookableYN | `String` | Web Bookable YN |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsRoomDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accessible | `String` | Accessible |
| 2 | areaF | `Float` | Area in sqft |
| 3 | areaM | `Float` | Area in sqm |
| 4 | assignAssignStatus | `String` | Assign Assign Status |
| 5 | assignDate | `DateTime` | Room assignment date |
| 6 | assignReasonDesc | `String` | Assign Reason Desc |
| 7 | assignType | `String` | Assign Type |
| 8 | assignemployeeid | `Float` | Assignemployeeid |
| 9 | assignreasonid | `String` | Assignreasonid |
| 10 | bedType | `String` | Bed Type |
| 11 | building | `String` | Building |
| 12 | buildingGroup | `String` | Building Group |
| 13 | businessDate | `Date` | Business Date |
| 14 | cExchangeDate | `Date` | Central Xchange Date |
| 15 | cExchangeRate | `Float` | Central Xchange Rate |
| 16 | cMinimumRevenue | `Float` | Central Minimum Revenue |
| 17 | cRackRate | `Float` | Central Rack Rate |
| 18 | centralMeetingRoomType | `String` | Central Meeting Room Type |
| 19 | centralRoomClass | `String` | Central Room Class |
| 20 | centralRoomType | `String` | Central Room Type |
| 21 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 22 | combinationRoomYN | `String` | Combination Room YN |
| 23 | comments | `String` | Comments |
| 24 | componentRoom | `String` | Suite component room numbers |
| 25 | connectingRoomNumber | `String` | Connecting Room Number |
| 26 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 27 | daySection | `String` | Indicates the section to which employee belongs. |
| 28 | deductYN | `String` | Deduct YN |
| 29 | defatulratecodeid | `String` | Defatulratecodeid |
| 30 | defaultRateDesc | `String` | Default Rate Description |
| 31 | deletedflag | `String` | Deleted Flag |
| 32 | departureCredits | `Float` | Credits associated with the task after departure. |
| 33 | description | `String` | Description |
| 34 | diaryName | `String` | Diary name to show room in |
| 35 | diarydisplayflag | `String` | Diarydisplayflag |
| 36 | discrepancy | `String` | Discrepancy |
| 37 | doors | `String` | Number of doors |
| 38 | eveningSection | `String` | Section the room belongs to for evening housekeeping |
| 39 | evisitorFacilityId | `String` | Facility ID for eVisitor. |
| 40 | excludedEventTypes | `String` | Stores event types which do not require alternate spaces. |
| 41 | facing | `String` | Direction room faces |
| 42 | floor | `String` | Floor |
| 43 | foPers | `Float` | The persons staying in room according to Front office. |
| 44 | forceAlternateYn | `String` | Defines if the function space needs an alternate space when booked. |
| 45 | frontDeskLocation | `String` | The front desk location this room should check in to. |
| 46 | frontOfficeStatus | `String` | Front Office Status of the room i.e.: Vacant or Occupied. |
| 47 | fullUtilizationTime | `Float` | Minutes occupied that define the room as 100% utilized. Maximum is 1440 minutes. |
| 48 | genericYN | `String` | Generic YN |
| 49 | handicapflag | `String` | Handicapflag |
| 50 | heightmaxF | `Float` | Max Height in ft |
| 51 | heightmaxM | `Float` | Max Height in m |
| 52 | heightminF | `Float` | Minumum heigth of room (feet) |
| 53 | heightminM | `Float` | Minumum heigth of room (meters) |
| 54 | holdDateTime | `DateTime` | Date and time when room will be released from hold. |
| 55 | holdType | `String` | Hold type from resort_assignment_reasons table. |
| 56 | holdUser | `Float` | User that is holding the room. |
| 57 | housekeepingAssignmentOrderBy | `Float` | Sequence for automatically generated task assignment. |
| 58 | housekeepingInspDate | `Date` | Housekeeping Inspected date |
| 59 | housekeepingInspEmpId | `String` | Houskeeping inspected employee id |
| 60 | housekeepingPers | `Float` | The number of persons staying in the room according to housekeeping |
| 61 | housekeepingStatus | `String` | The status of this room according to housekeeping |
| 62 | imageId | `Float` | Image ID |
| 63 | inactiveflag | `String` | Inactive Flag |
| 64 | includeInStatisticsYN | `String` | Include in Statistics YN |
| 65 | insertDate | `DateTime` | Insert Date |
| 66 | insertUser | `Float` | Insert User |
| 67 | internalTempflag | `String` | Tempflag |
| 68 | jRNUpdateDate | `Date` | JRN Update Date |
| 69 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 70 | keyCode | `String` | The current key code for this room.  Used to create keys for a room. |
| 71 | keyOptions | `String` | Privileges available for this key |
| 72 | lastCheckOutDate | `Date` | The last check out date for this room. |
| 73 | lastMeterReading | `Float` | The last meter reading for condos that track electrical usage of rented rooms. |
| 74 | lengthF | `Float` | Length (feet) |
| 75 | lengthM | `Float` | Length (meters) |
| 76 | light | `String` | Number of lights in the room |
| 77 | locationID | `String` | Internal ID to uniquely identify the Property |
| 78 | loudspeakersflag | `String` | Loudspeakersflag |
| 79 | maxAdvance | `Float` | Maximum number of days before the catering event date  that the space can be booked on the web. |
| 80 | maxCapacity | `Float` | Function Space Maximum Capacity. |
| 81 | maxSharedGroups | `Float` | Maximum number of groups for a Shared function space allowed. |
| 82 | maximumOccupancy | `Float` | Maximum Occupancy |
| 83 | measurement | `String` | The unit of measurement for this square units (IE: Feet Meters etc) |
| 84 | meetingRoomType | `String` | Type of meeting room |
| 85 | meetingRoomYN | `String` | Meeting Room YN |
| 86 | meetingroomTypeDesc | `String` | Meetingroom Type Description |
| 87 | meetingroomTypeSeq | `Float` | Meetingroom Type Sequence |
| 88 | microphoneSocketTypes | `String` | Type of microphone sockets |
| 89 | microphoneSockets | `Float` | Number of microphone sockets |
| 90 | minAdvance | `Float` | Minimum number of days before the catering event date that the space can be booked on the web. |
| 91 | minCapacity | `Float` | Minimum Capacity |
| 92 | minimumRevenue | `Float` | Minimum Revenue |
| 93 | numberOfBeds | `Float` | Specifies the number of beds in this room. |
| 94 | occupancyCondition | `String` | Current room condition updated daily.(ie StayOverDueOutExpected etc) |
| 95 | occupantDiscrepancy | `Float` | Discrepancy between front desk and housekeeping |
| 96 | onlinePrintingYn | `String` | Used for pseudo rooms. If Y then this pseudo room will be included in Online Printing for reservation changes. |
| 97 | orderBy2 | `Float` | Display sequence 2 |
| 98 | orderBy3 | `Float` | Display sequence 3 |
| 99 | orderBy4 | `Float` | Display sequence 4 |
| 100 | orderBy5 | `Float` | Display sequence 5 |
| 101 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 102 | ovosGradeCode | `String` | Stores a Grade associated with a unit to determine the room display order in Room Assignment and Room Plan screens. |
| 103 | ovosUnitYn | `String` | Room can be OVOS unit. |
| 104 | pcode | `String` | Not used |
| 105 | personDiscrepancy | `Float` | Person discrepancy between front desk and houskeeping |
| 106 | phoneNumber | `String` | Phone Number |
| 107 | physicalNumberOfRooms | `Float` | Physical Number of Rooms |
| 108 | pickupCredits | `Float` | Houskeeping credits for cleaning room in pickup status |
| 109 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 110 | property | `String` | Code to uniquely identify the Property |
| 111 | pseudoRoomYN | `String` | Pseudo Room YN |
| 112 | publishedRateAmount | `Float` | Default rate for the room |
| 113 | publishedRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| 114 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 115 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 116 | rateCode | `String` | Rate Code |
| 117 | rating | `String` | Rating |
| 118 | repAssignReasonDescription | `String` | Reporting Assign Reason Desc |
| 119 | repBedTypeDescription | `String` | Reporting Bed Type Desc |
| 120 | repMeetingroomTypeDescription | `String` | Reporting Meetingroom Type Desc |
| 121 | repMeetingroomTypeSequence | `Float` | Reporting Meetingroom Type Seq |
| 122 | repRoomClassSellSequence | `Float` | Reporting Room Class Sell Seq |
| 123 | repRoomFeaturesDescs | `String` | Reporting Room Features Descs |
| 124 | repRoomStatusReason | `String` | Reporting Room Status Reason |
| 125 | repRoomStatusReasonDescription | `String` | Reporting Room Status Reason Desc |
| 126 | returnStatus | `String` | Room return status |
| 127 | room | `String` | Room |
| 128 | roomAssignmentRating | `Float` | Room Assignment Rating. |
| 129 | roomCategoryBedtype | `String` | Room Category Bedtype |
| 130 | roomCategoryDesc | `String` | Room Category Desc |
| 131 | roomClass | `String` | Room Class |
| 132 | roomClassCentralDescription | `String` | Room Class Central Description |
| 133 | roomClassDescription | `String` | Room Class Description |
| 134 | roomClassSequence | `Float` | Room Class Sequence |
| 135 | roomCondition | `String` | Room Condition |
| 136 | roomFeatureDescription | `String` | Room Feature Description |
| 137 | roomFeatures | `String` | This stores the codes for the rooms features. Currently not used |
| 138 | roomNumber | `String` | Room Number |
| 139 | roomParity | `String` | Room Parity |
| 140 | roomStatus | `String` | Room Status |
| 141 | roomStatusDescription | `String` | Room Status Description |
| 142 | roomStatusFromDate | `Date` | The date as of which the room_status is valid. |
| 143 | roomStatusReason | `String` | Room Status Reason |
| 144 | roomStatusReasonDesc | `String` | Room Status Reason Description |
| 145 | roomStatusRemarks | `String` | Room status remarks |
| 146 | roomStatusToDate | `Date` | The date till which the room_status is valid.(Used during OO and OS status of rooms ) |
| 147 | roomType | `String` | Room Type |
| 148 | roomUseCount | `Float` | Total Count of the number of days the room was used. |
| 149 | roomcategoryid | `String` | Roomcategoryid |
| 150 | roomclassid | `String` | Roomclassid |
| 151 | roomid | `String` | Roomid |
| 152 | roomstatusreasonid | `String` | Roomstatusreasonid |
| 153 | sequence | `Float` | Sequence |
| 154 | serviceStatus | `String` | Current guest service status code for this room. Example: Service status can be DND (Do Not Disturb) or MUP (Make Up Room) |
| 155 | setupNotes | `String` | Notes for the setup of the room |
| 156 | shareableflag | `String` | Shareableflag |
| 157 | smoking | `String` | Smoking |
| 158 | smokingPreferences | `String` | Smoking Preferences |
| 159 | squareUnits | `Float` | The square units for this room (IE: if a condo in the US likely the square feet of this room) |
| 160 | stayoverCredits | `Float` | Stayover Credits |
| 161 | suiteType | `String` | Standard or Suite |
| 162 | suiteYN | `String` | Suite YN |
| 163 | supplement | `String` | Supplement |
| 164 | tempFlag | `String` | Temp Flag |
| 165 | translationboothNum | `Float` | Number for the booth |
| 166 | turnDown | `String` | Turn Down |
| 167 | turndownCredits | `Float` | Houskeeping credits for Turndown. |
| 168 | tvRadioSockets | `Float` | Number of TV or radio sockets |
| 169 | unit | `String` | Unit |
| 170 | updateDate | `DateTime` | Update Date |
| 171 | updateUser | `Float` | Update User |
| 172 | visibleOnWebYn | `String` | Flag makes a Function Space visible on the web. |
| 173 | webBookingYn | `String` | Web Booking Y/N |
| 174 | weightF | `Float` | Room weigth (feet) |
| 175 | weightM | `Float` | Room weigth (meters) |
| 176 | widthF | `Float` | Width (feet) |
| 177 | widthM | `Float` | Width (meters) |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsRoutingInstructionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountCode | `String` | Account Code |
| 2 | addTransactionYN | `String` | Add Trx Y/N |
| 3 | addressId | `Float` | Address ID |
| 4 | authemployeeid | `Float` | Authemployeeid |
| 5 | authorizerId | `Float` | Authorizer ID |
| 6 | basedOnRate | `String` | Rate Code that is the source for this routing instruction. |
| 7 | billingInstrnCode | `Float` | Billing Instruction Code. |
| 8 | billtoprofileid | `Float` | Billtoprofileid |
| 9 | cCompPreApprovalAmount | `Float` | Central Comp Pre Approval Amt |
| 10 | cExchangeDate | `Date` | Central Xchange Date |
| 11 | cExchangeRate | `Float` | Central Xchange Rate |
| 12 | centralExtendedInstructionSummary | `String` | Central Extended Instruction Summary |
| 13 | centralInstructionSummary | `String` | Central Instruction Summary |
| 14 | centralRoutingAmountLimit | `Float` | Central Routing Amount Limit |
| 15 | centralRoutingLimitUsed | `Float` | Central Routing Limit Used |
| 16 | centralRoutingTransactionCode | `String` | Central Routing Transaction Code |
| 17 | centralRoutingTransactionCodeDescription | `String` | Central Routing Transaction Code Description |
| 18 | comments | `String` | Comments |
| 19 | compAuthorizer | `String` | Comp Authorizer |
| 20 | compPreApprovalAmt | `Float` | Amount for which the comp pre approval is sought. |
| 21 | compPreApprovalCode | `String` | Approval Code from PTS system. |
| 22 | compPreApprovalDate | `Date` | Approval Date from PTS system. |
| 23 | compPreApprovalRequiredYn | `String` | Comp Pre Approval Required Y/N |
| 24 | compTypeCode | `String` | Comp Type Code |
| 25 | compVoucherNo | `String` | Comp Voucher Number |
| 26 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 27 | dailyYn | `String` | Daily Y/N |
| 28 | dayString | `String` | Concatenated string of all the days. This is also used part of the unique key. |
| 29 | declinedBy | `Float` | User ID of user that declined comp routing request |
| 30 | declinedYn | `String` | Used to decline comp routing requests |
| 31 | deletedFlag | `String` | Deleted Flag |
| 32 | endDate | `DateTime` | End Date |
| 33 | extendedInstructionSummary | `String` | Extended Instruction Summary |
| 34 | folio | `Float` | Folio |
| 35 | fridayYN | `String` | Friday YN |
| 36 | insertDate | `DateTime` | Insert Date |
| 37 | insertUser | `Float` | Insert User |
| 38 | instructionSummary | `String` | Instruction Summary |
| 39 | internalDeletedflag | `String` | Deleted Flag |
| 40 | internalMembershipid | `Float` | Membershipid |
| 41 | jRNUpdateDate | `Date` | JRN Update Date |
| 42 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 43 | locationID | `String` | Internal ID to uniquely identify the Property |
| 44 | membershipId | `Float` | Membership ID |
| 45 | mondayYN | `String` | Monday YN |
| 46 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 47 | payeeFirstName | `String` | First name of the guest paying the bill |
| 48 | payeeLastName | `String` | Nirst name of the guest paying the bill |
| 49 | payeeNameID | `Float` | Name Id to which it should be routed. |
| 50 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 51 | printReceiptYn | `String` | Flag to indicate if a receipt has to be printed on posting the transaction used in Opera 9. |
| 52 | property | `String` | Code to uniquely identify the Property |
| 53 | requestedBy | `String` | Application user who requested the report. |
| 54 | reservationNameId | `Float` | Resv Name ID |
| 55 | reservationid | `Float` | Reservationid |
| 56 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 57 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 58 | routedToRoomNo | `String` | Routed To Room Number |
| 59 | routingAmountLimit | `Float` | Routing Amount Limit |
| 60 | routingBeginDate | `DateTime` | Routing Begin Date |
| 61 | routingCode | `String` | Routing Code |
| 62 | routingCodeDescription | `String` | Routing Code Description |
| 63 | routingCoversLimit | `Float` | No. of covers for this routing instruction. |
| 64 | routingDateRange | `String` | Routing Date Range |
| 65 | routingDaysOfWeek | `String` | Routing Days of Week |
| 66 | routingInstructionsId | `Float` | Number to identify the entry. |
| 67 | routingLimitType | `String` | Identifies whether this routing instruction has a limit amount or limit percent. |
| 68 | routingLimitUsed | `Float` | Amount of credit used for this routing instruction |
| 69 | routingLinkId | `Float` | Value used to group routing instructions. Taken from Sequence ROUTING_LINK_ID_SEQ. |
| 70 | routingPercentageLimit | `Float` | Routing Percentage Limit |
| 71 | routingTransactionCode | `String` | Routing Transaction Code |
| 72 | routingTransactionCodeDescription | `String` | Routing Transaction Code Description |
| 73 | routingType | `String` | To specify whether it is a package routing or not |
| 74 | routingTypeDesc | `String` | Routing Type Desc |
| 75 | routinginstructid | `Float` | Routinginstructid |
| 76 | saturdayYN | `String` | Saturday YN |
| 77 | sundayYN | `String` | Sunday YN |
| 78 | tcGroup | `String` | Transaction Code Group |
| 79 | tcSubgroup | `String` | Transaction Code Subgroup |
| 80 | thursdayYN | `String` | Thursday YN |
| 81 | toReservationNameId | `Float` | To Resv Name ID |
| 82 | toreservationid | `Float` | Toreservationid |
| 83 | transcodearrangementid | `Float` | Transcodearrangementid |
| 84 | transcodeid | `String` | Transcodeid |
| 85 | transgroupid | `String` | Transgroupid |
| 86 | transsubgroupid | `String` | Transsubgroupid |
| 87 | trxServiceType | `String` | Transaction Service Type |
| 88 | tuesdayYN | `String` | Tuesday YN |
| 89 | updateDate | `DateTime` | Update Date |
| 90 | updateUser | `Float` | Update User |
| 91 | wednesdayYN | `String` | Wednesday YN |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsTransactionCodeDetailsType

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

### FinancialTransactionDetailsTransactionCodeArrangmentDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| 2 | arrangementCode | `String` | Arrangement Code |
| 3 | arrangementDescription | `String` | Arrangement Description for the Transaction Code. |
| 4 | arrangementId | `Float` | Arrangement ID |
| 5 | arrangementType | `String` | Arrangement Type |
| 6 | bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| 7 | cExchangeDate | `Date` | Central Xchange Date |
| 8 | cExchangeRate | `Float` | Central Xchange Rate |
| 9 | cRoutingAmount | `Float` | Central Routing Amount |
| 10 | centralTransactionCode | `String` | Central Transaction Code |
| 11 | centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| 12 | compYn | `String` | Comp Y/N |
| 13 | complimentaryYN | `String` | Complimentary YN |
| 14 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 15 | dailyYn | `String` | Daily Y/N |
| 16 | day1 | `String` | Day1 |
| 17 | day2 | `String` | Day2 |
| 18 | day3 | `String` | Day3 |
| 19 | day4 | `String` | Day4 |
| 20 | day5 | `String` | Day5 |
| 21 | day6 | `String` | Day6 |
| 22 | day7 | `String` | Day7 |
| 23 | deletedFlag | `String` | Deleted Flag |
| 24 | eligibleYn | `String` | Specifies the Eligibility to calculate membership points. |
| 25 | exportBucketType | `String` | User defined Export Bucket type. |
| 26 | inactiveDate | `DateTime` | Inactive Date |
| 27 | inactiveflag | `Date` | Inactive Flag |
| 28 | inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| 29 | insertDate | `DateTime` | Insert Date |
| 30 | insertUser | `Float` | Insert User |
| 31 | internalDeletedflag | `String` | Deleted Flag |
| 32 | jRNUpdateDate | `Date` | JRN Update Date |
| 33 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 34 | locationID | `String` | Internal ID to uniquely identify the Property |
| 35 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 36 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 37 | property | `String` | Code to uniquely identify the Property |
| 38 | revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| 39 | revenueflag | `String` | Revenueflag |
| 40 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 41 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 42 | routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| 43 | routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| 44 | routingPercent | `Float` | Routing Percent |
| 45 | transactionCode | `String` | Transaction Code |
| 46 | transactionCodeDescription | `String` | Transaction Code Description |
| 47 | transcodearrangementid | `Float` | Transcodearrangementid |
| 48 | updateDate | `DateTime` | Update Date |
| 49 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsFromReservationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| 2 | accompaniedYN | `String` | Accompanied YN |
| 3 | accompanyingName | `String` | Accompanying guest names. |
| 4 | actualCheckInDateTime | `DateTime` | Actual Check In Date Time |
| 5 | actualCheckOutDateTime | `DateTime` | Actual Check Out Date Time |
| 6 | actualCheckInDate | `Date` | Actual Check-In Date |
| 7 | actualCheckInTime | `String` | Actual Check-In Time |
| 8 | actualCheckOutDate | `Date` | Actual Check-Out Date |
| 9 | actualCheckOutTime | `String` | Actual Check-Out Time |
| 10 | addressId | `Float` | Address ID |
| 11 | addresseeNameId | `Float` | Addressee Name ID |
| 12 | adults | `Float` | Adults |
| 13 | adultsTaxFree | `Float` | Adults Tax Free |
| 14 | advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| 15 | agencyprofileid | `Float` | Agencyprofileid |
| 16 | allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| 17 | allotmentid | `Float` | Block ID |
| 18 | amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| 19 | amenityLevelCode | `String` | Amenity Level Code |
| 20 | amountPercent | `Float` | Amount Percent |
| 21 | approvalAmount | `Float` | Approval Amount |
| 22 | approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| 23 | approvalCode | `String` | Approval Code |
| 24 | arrivalComments | `String` | Arrival Comments |
| 25 | arrivalDate | `Date` | Arrival Date |
| 26 | arrivalDateTime | `DateTime` | Arrival Date Time |
| 27 | arrivalEstimateTime | `Date` | Arrival Estimate Time |
| 28 | arrivalTime | `String` | Activity begin time |
| 29 | arrivaltransportid | `String` | Arrivaltransportid |
| 30 | attachedDate | `Date` | Attached Date |
| 31 | authorizedBillingYN | `String` | Not used. |
| 32 | authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| 33 | authorizerId | `Float` | Authorizer ID |
| 34 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 35 | autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| 36 | autoSettleDays | `Float` | Auto Settle Days |
| 37 | autoSettleType | `String` | Auto Settle Type |
| 38 | autoSettleYN | `String` | Auto Settle YN |
| 39 | awardCode | `String` | Award Code |
| 40 | awardCode1 | `String` | Award code 1 |
| 41 | awardCode2 | `String` | Award code 2 |
| 42 | awardCode3 | `String` | Award code 3 |
| 43 | awardCode4 | `String` | Award Code 4 |
| 44 | awardCode5 | `String` | Award code 5 |
| 45 | awardMembershipID | `Float` | Award Membership ID |
| 46 | awardVoucher1 | `String` | Award Voucher number 1 |
| 47 | awardVoucher2 | `String` | Award Voucher number 2 |
| 48 | awardVoucher3 | `String` | Award Voucher number 3 |
| 49 | awardVoucher4 | `String` | Award Voucher number 4 |
| 50 | awardVoucher5 | `String` | Award Voucher number 5 |
| 51 | awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| 52 | awdUpgrTo | `String` | Room Type after the Upgrade Award |
| 53 | backToBackYN | `String` | Back To Back YN |
| 54 | balance | `Float` | Balance on the account. |
| 55 | baseRateAmount | `Float` | Base Rate Amount |
| 56 | baseRateCode | `String` | Base Rate Code |
| 57 | baseRateCurrencyCode | `String` | Base Rate Currency Code |
| 58 | basedOnRule | `String` | Based On Rule |
| 59 | baseratecurrencyid | `String` | Baseratecurrencyid |
| 60 | beginCity | `String` | Begin City |
| 61 | beginDatetime | `DateTime` | Begin Datetime |
| 62 | beginDistrict | `String` | Begin District |
| 63 | beginState | `String` | Begin State |
| 64 | beginSystemDateTime | `DateTime` | Stores the actual guest check in date and time. |
| 65 | billNumber | `String` | Bill Number |
| 66 | billingContact | `String` | Billing Contact |
| 67 | billingContactDisplayName | `String` | Billing Contact Display Name |
| 68 | billingContactId | `Float` | Billing Contact ID |
| 69 | billingContactName | `String` | Billing Contact Name |
| 70 | billingcontactprofileid | `Float` | Billing Contact Profile ID |
| 71 | blockCode | `String` | Block Code |
| 72 | blockCreateDate | `DateTime` | Block Create Date |
| 73 | blockID | `Float` | Block ID |
| 74 | blockName | `String` | Block Name |
| 75 | blockResort | `String` | Property this block belongs to. |
| 76 | blockStatus | `String` | Block Status |
| 77 | bonusCheckId | `Float` | Bonus Check ID |
| 78 | bookedRoomCategory | `String` | Booked Room Category |
| 79 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 80 | businessDateCreated | `Date` | Business Date Created |
| 81 | businessDatetimeCreated | `DateTime` | Business Datetime Created |
| 82 | bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| 83 | cAutoPostAmount | `Float` | Central Auto Post Amount |
| 84 | cBaseRateAmount | `Float` | Central Base Rate Amount |
| 85 | cDiscountAmount | `Float` | C Discount Amount |
| 86 | cDiscountAmt | `Float` | C Discount Amt |
| 87 | cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| 88 | cExchangeDate | `Date` | Central Xchange Date |
| 89 | cExchangeRate | `Float` | Central Xchange Rate |
| 90 | cFixedCharge | `Float` | Central Fixed Charge |
| 91 | cGrossRateAmount | `Float` | Central Gross Rate Amt |
| 92 | cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| 93 | cNetRoomAmount | `Float` | Central Net Room Amt |
| 94 | cOriginalBaseRate | `Float` | Central Original Base Rate |
| 95 | cPackageAmount | `Float` | Central Pkg Amt |
| 96 | cPackageTax | `Float` | Central Pkg Tax |
| 97 | cRateAmount | `Float` | C Rate Amount |
| 98 | cRoomCost | `Float` | Central Room Cost |
| 99 | cRoomTax | `Float` | Central Room Tax |
| 100 | cShareAmountOriginal | `Float` | Central Share Amount Original |
| 101 | cUpsellCharge | `Float` | Central Upsell Charge |
| 102 | cancelDate | `Date` | Cancel Date |
| 103 | cancelReason | `String` | Cancel Reason |
| 104 | cancelTime | `String` | Cancel Time |
| 105 | cancellationDate | `DateTime` | Cancellation Date |
| 106 | cancellationDatetime | `DateTime` | Cancellation Datetime |
| 107 | cancellationNumber | `String` | Cancellation Number |
| 108 | cancellationReasonDescription | `String` | Cancellation Reason Description |
| 109 | cancellationreasonid | `String` | Cancellationreasonid |
| 110 | cancelledBy | `String` | The user who canceled this Reservation. |
| 111 | cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| 112 | cardNumberByMembershipType | `String` | Card Number by Membership Type |
| 113 | centralApprovalAmount | `Float` | Central Approval Amount |
| 114 | centralCancelReason | `String` | Central Cancel Reason |
| 115 | centralCommissionCode | `String` | Central Commission Code |
| 116 | centralCommissionDescription | `String` | Central Commission Description |
| 117 | centralCreditLimit | `Float` | Central Credit Limit |
| 118 | centralDiscountReason | `String` | Central Discount Reason |
| 119 | centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| 120 | centralFBRevenue | `Float` | Central FB Revenue |
| 121 | centralGuestType | `String` | Central Guest Type |
| 122 | centralHurdle | `Float` | Central Hurdle |
| 123 | centralPackageCode | `String` | Central Package Code |
| 124 | centralPackageCodeDescription | `String` | Central Package Code Description |
| 125 | centralPackageForecastGroup | `String` | Central Package Forecast Group |
| 126 | centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| 127 | centralPaymentAmount | `Float` | Central Payment Amount |
| 128 | centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| 129 | centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| 130 | centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| 131 | centralPromotionDescription | `String` | Central Promotion Description |
| 132 | centralRateableValue | `Float` | Central Rateable Value |
| 133 | centralReservationType | `String` | Central Reservation Type |
| 134 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 135 | centralRoomRevenue | `Float` | Central Room Revenue |
| 136 | centralRoomTypeCode | `String` | Central Room Type Code |
| 137 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 138 | centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| 139 | centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| 140 | centralSharedRoomRate | `Float` | Central Shared Room Rate |
| 141 | centralSpecialRequestDescription | `String` | Central Special Request Description |
| 142 | centralTaxType | `String` | Central Tax Type |
| 143 | centralTaxTypeDescription | `String` | Central Tax Type Description |
| 144 | centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| 145 | centralTotalRevenue | `Float` | Central Total Revenue |
| 146 | centralTotalRoomRate | `Float` | Central Total Room Rate |
| 147 | centralWaitlistPriority | `String` | Central Waitlist Priority |
| 148 | centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| 149 | centralWaitlistReason | `String` | Central Waitlist Reason |
| 150 | centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| 151 | channelDescription | `String` | Channel Description |
| 152 | channelOrderBy | `Float` | Channel Order By |
| 153 | channelid | `String` | Channelid |
| 154 | checkInInitiatedBy | `String` | Check In Initiated By |
| 155 | checkinDuration | `Float` | Duration in seconds to complete Check-In |
| 156 | childBucket1 | `Float` | Child Bucket 1 |
| 157 | childBucket4 | `Float` | Child Bucket 4 |
| 158 | childBucket5 | `Float` | Child Bucket 5 |
| 159 | children | `Float` | Children |
| 160 | childrenAgeGroup2 | `Float` | Children Age Group 2) |
| 161 | childrenAgeGroup3 | `Float` | Children Age Group 3) |
| 162 | childrenAges | `String` | Children Ages |
| 163 | commissionCode | `String` | Commission Code |
| 164 | commissionDescription | `String` | Commission Description |
| 165 | commissionHoldCode | `String` | Commission Hold Code |
| 166 | commissionPaid | `Float` | Commission Paid |
| 167 | commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| 168 | commissionableYN | `String` | Commissionable YN |
| 169 | commissionid | `String` | Commissionid |
| 170 | compHouse | `String` | Comp House |
| 171 | compTypeCode | `String` | Comp Type Code |
| 172 | companyCity | `String` | Company City |
| 173 | companyCountry | `String` | Company Country |
| 174 | companyID | `Float` | Company ID |
| 175 | companyName | `String` | Company Name |
| 176 | companyProfileCorporateID | `String` | Company Profile Corporate ID |
| 177 | companyProfileID | `Float` | Company Profile ID |
| 178 | complimentaryYN | `String` | Complimentary YN |
| 179 | compreasonid | `String` | Compreasonid |
| 180 | computedResvStatus | `String` | Calculated reservation status. |
| 181 | confirmationLegNumber | `Float` | Confirmation Leg Number. |
| 182 | confirmationNo | `String` | Shared Confirmation Number |
| 183 | consumerYn | `String` | Consumer Y/N |
| 184 | contactName | `String` | Contact Name; UDFC02 on reservation. |
| 185 | contactProfileID | `Float` | Contact Profile ID |
| 186 | contactProfileName | `String` | Contact Profile Name |
| 187 | createdBy | `String` | The name of the user who created the record. |
| 188 | createdByDefaultResort | `String` | Created By Default Property |
| 189 | createdDate | `Date` | Created Date |
| 190 | createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| 191 | creditCardAuthDate | `Date` | Credit Card Auth Date |
| 192 | creditCardId | `Float` | Credit Card ID |
| 193 | creditLimit | `Float` | Credit Limit |
| 194 | creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| 195 | cribs | `Float` | Cribs |
| 196 | currencyCode | `String` | Currency Code |
| 197 | customReferenceNumber | `String` | Custom Reference Number |
| 198 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 199 | dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| 200 | deletedFlag | `String` | Deleted Flag |
| 201 | departtransportid | `String` | Departtransportid |
| 202 | departureComments | `String` | Departure Comments |
| 203 | departureDate | `Date` | Departure Date |
| 204 | departureDateTime | `Date` | Departure Date Time |
| 205 | departureTime | `String` | Departure Time |
| 206 | departureTransportCode | `String` | Departure Transport Code |
| 207 | departureTransportationYN | `String` | Departure Transportation YN |
| 208 | depositMaturityType | `String` | Stores the Deposit maturity preference. |
| 209 | detatchedDate | `Date` | Detatched Date |
| 210 | detatchedYN | `String` | Detatched YN |
| 211 | directBillVerifyResponse | `String` | Direct Bill Verify Response |
| 212 | directbillauthby | `Float` | Directbillauthby |
| 213 | discountAmount | `Float` | Discount Amount |
| 214 | discountAmt | `Float` | Discount Amount |
| 215 | discountPercent | `Float` | Discount Percentage. |
| 216 | discountPrcnt | `Float` | Discount Prcnt |
| 217 | discountReason | `String` | Discount Reason |
| 218 | discountReasonDescription | `String` | Discount Reason Description |
| 219 | discountreasonid | `String` | Discountreasonid |
| 220 | displayColor | `String` | Display Color |
| 221 | dmlSeqNumber | `Float` | Dml Sequence No |
| 222 | doNotMoveRoom | `String` | Do Not Move Room |
| 223 | doNotMoveYN | `String` | Do not move room flag. |
| 224 | dropOffCarrierCode | `String` | Drop Off Carrier Code |
| 225 | dropOffDate | `Date` | Drop Off Date |
| 226 | dropOffStation | `String` | Drop Off Station |
| 227 | dropOffTime | `String` | Drop Off Time |
| 228 | dropOffType | `String` | Drop Off Type |
| 229 | dropOffTypeDescription | `String` | Drop Off Type Description |
| 230 | eTRComments | `String` | Comments related to Estimated Time of Return. |
| 231 | effectiveRateAmount | `Float` | Not used. |
| 232 | eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| 233 | emailAddress | `String` | Email Address |
| 234 | emailFolioYn | `String` | Email Folio Y/N |
| 235 | emailId | `Float` | Email ID |
| 236 | emailYn | `String` | Email Y/N |
| 237 | endCity | `String` | End City |
| 238 | endDatetime | `DateTime` | End Datetime |
| 239 | endDistrict | `String` | End District |
| 240 | endState | `String` | End State |
| 241 | endbusinessdate | `Date` | Endbusinessdate |
| 242 | entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| 243 | entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| 244 | esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| 245 | estimatedDepartureTime | `Date` | Estimated Departure Time |
| 246 | eventId | `Float` | Event ID |
| 247 | exchangePostingType | `String` | Exchange Posting Type |
| 248 | exchangeRate | `Float` | Exchange Rate |
| 249 | excludeFromAutoAuthorizationYN | `String` | Exclude From Auto Authorization YN |
| 250 | expectedTimeOfReturnETR | `DateTime` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| 251 | exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| 252 | extSegNo | `Float` | Not used |
| 253 | extSeqNumber | `Float` | Not used |
| 254 | extensionId | `Float` | Internal extension number for the main reservation |
| 255 | externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| 256 | externalReference | `String` | External Reference |
| 257 | externalReferencesList | `String` | External References List |
| 258 | extraBeds | `Float` | Extra Beds |
| 259 | fBRevenue | `Float` | FB Revenue |
| 260 | fBRevenueRemaining | `Float` | F&B Revenue Remaining |
| 261 | faxId | `Float` | Fax ID |
| 262 | faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| 263 | feature | `String` | This stores the codes for the rooms features. Currently not used |
| 264 | financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| 265 | fixedCharge | `Float` | Not used. |
| 266 | fixedRateYN | `String` | Fixed Rate YN |
| 267 | folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| 268 | folioCloseDate | `Date` | Date the folio was changed to closed. |
| 269 | folioNumber | `String` | Folio Number |
| 270 | folioText1 | `String` | Folio Text1 |
| 271 | folioText2 | `String` | Folio Text2 |
| 272 | foreignCurrencyID | `String` | Foreign Currency ID |
| 273 | freeChild | `Float` | Free Child |
| 274 | frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| 275 | grossRateFuture | `Float` | Gross Rate Future |
| 276 | grossRatePast | `Float` | Gross Rate Past |
| 277 | groupName | `String` | Group Name |
| 278 | groupProfileARNumber | `Float` | Group Profile AR Number |
| 279 | groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| 280 | groupProfileClientID | `String` | Group Profile Client ID |
| 281 | groupProfileID | `Float` | Group Profile ID |
| 282 | groupProfileName | `String` | Group Profile Name |
| 283 | guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| 284 | guaranteecodeid | `String` | Guaranteecodeid |
| 285 | guestFirstName | `String` | Guest First Name |
| 286 | guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| 287 | guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| 288 | guestSignature | `String` | Signature of the guest |
| 289 | guestStatus | `String` | Used for Police/Tourist Export |
| 290 | guestType | `String` | Guest Type |
| 291 | guestprofileid | `Float` | Guestprofileid |
| 292 | gueststatusid | `String` | Gueststatusid |
| 293 | guesttypeid | `String` | Guesttypeid |
| 294 | housekeepingServiceTime | `String` | Housekeeping Service Time |
| 295 | hurdle | `Float` | Hurdle |
| 296 | hurdleOverride | `String` | Hurdle Override |
| 297 | iDByMembershipClass | `String` | ID by Membership Class |
| 298 | iDByMembershipType | `String` | ID by Membership Type |
| 299 | individualCity | `String` | Guest Address. |
| 300 | individualCountry | `String` | Country of the guest |
| 301 | individualFirstName | `String` | Individual First Name |
| 302 | individualLastName | `String` | Individual Last Name |
| 303 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 304 | insertDate | `DateTime` | Insert Date |
| 305 | insertDateTime | `DateTime` | Insert DateTime |
| 306 | insertUser | `Float` | Insert User |
| 307 | intermediaryYn | `String` | Intermediary Y/N |
| 308 | internalAwardMembershipId | `Float` | Award Membership ID |
| 309 | internalBaseratecode | `String` | Baseratecode |
| 310 | internalBlockId | `Float` | Block ID. |
| 311 | internalCompanyprofileid | `Float` | Companyprofileid |
| 312 | internalGroupprofileid | `Float` | Groupprofileid |
| 313 | internalSourceprofileid | `Float` | Sourceprofileid |
| 314 | itemsQuantities | `String` | Items and Quantities |
| 315 | jRNUpdateDate | `Date` | JRN Update Date |
| 316 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 317 | keyValidUntil | `Date` | Key Valid Until |
| 318 | lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| 319 | lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| 320 | lastRoomNumber | `String` | Not used. |
| 321 | lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| 322 | leadTimeDays | `Float` | Lead Time for ordering |
| 323 | lengthOfStay | `Float` | Length of Stay |
| 324 | linkedArrivalDate | `DateTime` | Linked Arrival Date |
| 325 | linkedDepartureDate | `DateTime` | Linked Departure Date |
| 326 | linkedRoomType | `String` | Linked Room Type |
| 327 | listOfMembershipID | `String` | Membership ID |
| 328 | localBaseRateAmount | `Float` | Local Base Rate Amount |
| 329 | locationID | `String` | Internal ID to uniquely identify the Property |
| 330 | loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| 331 | mailYn | `String` | Mail Y/N |
| 332 | manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| 333 | marketCode | `String` | Market Code |
| 334 | marketid | `String` | Marketid |
| 335 | mcGenBeginDistrict | `String` | Mc Gen Begin District |
| 336 | mcGenBeginState | `String` | Mc Gen Begin State |
| 337 | mcGenEndDistrict | `String` | Mc Gen End District |
| 338 | mcGenEndState | `String` | Mc Gen End State |
| 339 | mcGenNextCountry | `String` | Mc Gen Next Country |
| 340 | mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| 341 | memberDescription | `String` | Member Description |
| 342 | memberLevel | `String` | Member Level |
| 343 | memberNumber | `String` | Member Number |
| 344 | membershipClass | `String` | Membership Class |
| 345 | membershipClassDescription | `String` | Membership Class Description |
| 346 | membershipCode | `String` | Membership Code |
| 347 | membershipId | `Float` | Membership ID |
| 348 | membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| 349 | membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| 350 | mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| 351 | mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| 352 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 353 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 354 | mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| 355 | mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| 356 | name | `String` | Name |
| 357 | nameUsageType | `String` | Name Usage Type |
| 358 | nextCountry | `String` | Next Country |
| 359 | nextDestination | `String` | Country Specific Requirement for Nigeria. |
| 360 | numberOfRooms | `Float` | No of Rooms |
| 361 | operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| 362 | optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| 363 | optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| 364 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 365 | originCode | `String` | Origin Code |
| 366 | originOfBooking | `String` | Origin Of Booking |
| 367 | originalBaseRate | `Float` | Not used. |
| 368 | originalEndDate | `Date` | Original End Date |
| 369 | originalStartDate | `Date` | Original Start Date |
| 370 | ownerFfFlag | `String` | Owner Ff Flag |
| 371 | ownerOrFriendsFamily | `String` | Owner or Friends/Family |
| 372 | packageCode | `String` | Package Code |
| 373 | packageCodeDescription | `String` | Package Code Description |
| 374 | packageForecastGroup | `String` | Package Forecast Group |
| 375 | packageForecastGroupDescription | `String` | Package Forecast Group Description |
| 376 | parentReservationNameId | `Float` | Parent Resv Name ID |
| 377 | parentreservationid | `Float` | Parentreservationid |
| 378 | partAllotment | `String` | Part Allotment |
| 379 | partyCode | `String` | Party Code |
| 380 | paxNo | `Float` | Pax Number |
| 381 | paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| 382 | paymentMethod | `String` | Payment Method |
| 383 | paymentmethodid | `String` | Paymentmethodid |
| 384 | periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| 385 | phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| 386 | phoneId | `Float` | Phone ID |
| 387 | physicalQuantity | `Float` | Physical Quantity |
| 388 | pickUpCarrierCode | `String` | Pick Up Carrier Code |
| 389 | pickUpDate | `Date` | Pick Up Date |
| 390 | pickUpStation | `String` | Pick Up Station |
| 391 | pickUpTransportNumber | `String` | Pick Up Transport Number |
| 392 | pickUpType | `String` | Pick Up Type |
| 393 | pickUpTypeDescription | `String` | Pick Up Type Description |
| 394 | pickUpTime | `String` | Pick-Up Time |
| 395 | pickupRequiredYN | `String` | Pickup Required YN |
| 396 | points | `Float` | Points |
| 397 | pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| 398 | postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| 399 | postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| 400 | postingAllowedYN | `String` | Posting Allowed YN |
| 401 | preArrReviewedDt | `DateTime` | This date flags if and when the record was reviewed from pre-arrival screen. |
| 402 | preArrReviewedUser | `Float` | User id who reviewed the record. |
| 403 | preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| 404 | preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| 405 | preference | `String` | Preference |
| 406 | preferenceType | `String` | Preference Type |
| 407 | preferredRoomType | `String` | Preferred Room Type |
| 408 | previousCountry | `String` | Previous Country |
| 409 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 410 | primaryShare | `String` | Primary Share |
| 411 | printRateYN | `String` | Print Rate YN |
| 412 | projectedFBRevenue | `Float` | Projected FB Revenue |
| 413 | projectedRoomRevenue | `Float` | Projected Room Revenue |
| 414 | projectedTotalRevenue | `Float` | Projected Total Revenue |
| 415 | promotionCode | `String` | Promotion Code |
| 416 | promotionDescription | `String` | Promotion Description |
| 417 | property | `String` | Indicates if the value set for the specific property. |
| 418 | pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| 419 | pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| 420 | purgeDate | `DateTime` | Purge Date |
| 421 | purposeOfStay | `String` | Purpose of stay. |
| 422 | quantity | `Float` | Number of Rooms |
| 423 | queuePriority | `Float` | Queue priority of the reservation. |
| 424 | queueWaitTime | `Float` | Queue Wait Time |
| 425 | quoteId | `String` | Quote ID provided by external system. |
| 426 | rateAmount | `Float` | Rate Amount |
| 427 | rateCode | `String` | Rate Code |
| 428 | rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| 429 | rateTier | `Float` | Tier ID for the Rate Detail. |
| 430 | rateableValue | `Float` | Stay rateable value. |
| 431 | ratecodeid | `String` | Ratecodeid |
| 432 | rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| 433 | rdResvStatus | `String` | Rd Reservation Status |
| 434 | rdenBillingContactId | `Float` | Rden Billing Contact ID |
| 435 | rdenReservationContactId | `Float` | Rden Resv Contact ID |
| 436 | rdenReservationDate | `Date` | Rden Reservation Date |
| 437 | rdenResort | `String` | Rden Property |
| 438 | referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| 439 | registrationCardNo | `String` | Registration Card Number |
| 440 | registrationNumber | `Float` | Registration Number |
| 441 | reinstateDate | `DateTime` | Reinstate Date |
| 442 | repChannel | `String` | Reporting Channel |
| 443 | repChannelDescription | `String` | Reporting Channel Description |
| 444 | reportId | `String` | Report ID |
| 445 | resInsertSource | `String` | Reservation Insert Source |
| 446 | resInsertSourceType | `String` | Reservation Insert Source Type |
| 447 | reservationContactId | `Float` | Resv Contact ID |
| 448 | reservationDate | `DateTime` | Reservation Date |
| 449 | reservationNameID | `Float` | Reservation Name ID |
| 450 | reservationStatus | `String` | Reservation Status |
| 451 | reservationType | `String` | Reservation Type |
| 452 | reservationTypeDescription | `String` | Reservation Type Description |
| 453 | reservationid | `Float` | Reservationid |
| 454 | resort | `String` | Property |
| 455 | resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| 456 | restrictionOverride | `String` | Restriction Override |
| 457 | resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| 458 | resvNameid | `Float` | Reservation Nameid |
| 459 | resvNumber | `Float` | Not used in PMS currently. |
| 460 | resvcontactprofileid | `Float` | Resvcontactprofileid |
| 461 | revenueTypeCode | `String` | Revenue type (catering/rooms) |
| 462 | rhBillingContactId | `Float` | Rh Billing Contact ID |
| 463 | rhReservationContactId | `Float` | Rh Resv Contact ID |
| 464 | rhRoomFeatures | `String` | Rh Room Features |
| 465 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 466 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 467 | room | `String` | Room |
| 468 | roomCategory | `String` | Room Category |
| 469 | roomClass | `String` | Room Class |
| 470 | roomCost | `Float` | Room Cost |
| 471 | roomInstructions | `String` | Room Instructions |
| 472 | roomResort | `String` | Meeting Room Property |
| 473 | roomRevenue | `Float` | Room Revenue |
| 474 | roomRevenueRemaining | `Float` | Room Revenue Remaining |
| 475 | roomServiceTime | `String` | This is the Turndown room service time. |
| 476 | roomTypeDescription | `String` | Room Type Description |
| 477 | roomTypeToChargeCode | `String` | Room Type To Charge Code |
| 478 | roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| 479 | roomcategoryid | `String` | Roomcategoryid |
| 480 | roomid | `String` | Roomid |
| 481 | routingYN | `String` | Routing YN |
| 482 | scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| 483 | sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| 484 | sguestName | `String` | Sguest Name |
| 485 | shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| 486 | shareId | `Float` | Share ID. |
| 487 | shareName | `String` | Share Name |
| 488 | sharePrcnt | `Float` | Not used. |
| 489 | shareSeqNumber | `Float` | Type of revenue |
| 490 | shareOfRateAmount | `Float` | Share of Rate Amount |
| 491 | sharedGuestName | `String` | Shared Guest Name |
| 492 | sharedProfileID | `Float` | Shared Profile ID |
| 493 | sharedReservationStatus | `String` | Shared Reservation Status |
| 494 | sharingYN | `String` | Sharing YN |
| 495 | sourceCity | `String` | Source City |
| 496 | sourceCode | `String` | Source Code |
| 497 | sourceCountry | `String` | Source Country |
| 498 | sourceName | `String` | Source Name |
| 499 | sourceProfileARNumber | `Float` | Source Profile AR Number |
| 500 | sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| 501 | sourceProfileIATANumber | `String` | Source Profile IATA Number |
| 502 | sourceProfileID | `Float` | Source Profile ID |
| 503 | sourceProfileName | `String` | Source Profile Name |
| 504 | sourceid | `String` | Sourceid |
| 505 | specialRequest | `String` | Special Request |
| 506 | specialRequestDescription | `String` | Special Request Description |
| 507 | spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| 508 | spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| 509 | spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| 510 | spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| 511 | splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| 512 | splitfromreservationid | `Float` | Splitfromreservationid |
| 513 | statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| 514 | statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| 515 | stayRecordId | `Float` | Stay Record ID |
| 516 | suiteNumber | `String` | Suite Number |
| 517 | superSearchIndexText | `String` | Super Search Index Text |
| 518 | taRecordLocator | `String` | Ta Record Locator |
| 519 | taxExemptNumber | `String` | Tax exempt number on the profile |
| 520 | taxNumberOfStays | `Float` | Tax No of Stays |
| 521 | taxType | `String` | Tax Type |
| 522 | taxTypeDescription | `String` | Tax Type Description |
| 523 | taxtypeid | `String` | Taxtypeid |
| 524 | tiad | `String` | Tiad |
| 525 | ticketNos | `String` | Ticket Nos |
| 526 | totalCostOfStay | `Float` | Total Cost of Stay |
| 527 | totalRevenue | `Float` | Total Revenue |
| 528 | totalRevenueRemaining | `Float` | Total Revenue Remaining |
| 529 | totalRoomRate | `Float` | Total Room Rate |
| 530 | trackItGroups | `String` | Track It Groups |
| 531 | trackItTypes | `String` | Track It Types |
| 532 | transactionid | `Float` | Transactionid |
| 533 | travelAgentCity | `String` | Travel Agent Address. |
| 534 | travelAgentCountry | `String` | Travel Agent Country |
| 535 | travelAgentID | `Float` | Travel Agent ID |
| 536 | travelAgentName | `String` | Travel Agent Name |
| 537 | travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| 538 | travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| 539 | travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| 540 | travelAgentProfileID | `Float` | Travel Agent Profile ID |
| 541 | travelAgentProfileName | `String` | Travel Agent Profile Name |
| 542 | truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| 543 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 544 | turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| 545 | uDFC01 | `String` | UDFC01 |
| 546 | uDFC02 | `String` | UDFC02 |
| 547 | uDFC03 | `String` | UDFC03 |
| 548 | uDFC04 | `String` | UDFC04 |
| 549 | uDFC05 | `String` | UDFC05 |
| 550 | uDFC06 | `String` | UDFC06 |
| 551 | uDFC07 | `String` | UDFC07 |
| 552 | uDFC08 | `String` | UDFC08 |
| 553 | uDFC09 | `String` | UDFC09 |
| 554 | uDFC10 | `String` | UDFC10 |
| 555 | uDFC11 | `String` | UDFC11 |
| 556 | uDFC12 | `String` | UDFC12 |
| 557 | uDFC13 | `String` | UDFC13 |
| 558 | uDFC14 | `String` | UDFC14 |
| 559 | uDFC15 | `String` | UDFC15 |
| 560 | uDFC16 | `String` | UDFC16 |
| 561 | uDFC17 | `String` | UDFC17 |
| 562 | uDFC18 | `String` | UDFC18 |
| 563 | uDFC19 | `String` | UDFC19 |
| 564 | uDFC20 | `String` | UDFC20 |
| 565 | uDFC21 | `String` | UDFC21 |
| 566 | uDFC22 | `String` | UDFC22 |
| 567 | uDFC23 | `String` | UDFC23 |
| 568 | uDFC24 | `String` | UDFC24 |
| 569 | uDFC25 | `String` | UDFC25 |
| 570 | uDFC26 | `String` | UDFC26 |
| 571 | uDFC27 | `String` | UDFC27 |
| 572 | uDFC28 | `String` | UDFC28 |
| 573 | uDFC29 | `String` | UDFC29 |
| 574 | uDFC30 | `String` | UDFC30 |
| 575 | uDFC31 | `String` | UDFC31 |
| 576 | uDFC32 | `String` | UDFC32 |
| 577 | uDFC33 | `String` | UDFC33 |
| 578 | uDFC34 | `String` | UDFC34 |
| 579 | uDFC35 | `String` | UDFC35 |
| 580 | uDFC36 | `String` | UDFC36 |
| 581 | uDFC37 | `String` | UDFC37 |
| 582 | uDFC38 | `String` | UDFC38 |
| 583 | uDFC39 | `String` | UDFC39 |
| 584 | uDFC40 | `String` | UDFC40 |
| 585 | uDFD01 | `Date` | UDFD01 |
| 586 | uDFD02 | `Date` | UDFD02 |
| 587 | uDFD03 | `Date` | UDFD03 |
| 588 | uDFD04 | `Date` | UDFD04 |
| 589 | uDFD05 | `Date` | UDFD05 |
| 590 | uDFD06 | `Date` | UDFD06 |
| 591 | uDFD07 | `Date` | UDFD07 |
| 592 | uDFD08 | `Date` | UDFD08 |
| 593 | uDFD09 | `Date` | UDFD09 |
| 594 | uDFD10 | `Date` | UDFD10 |
| 595 | uDFD11 | `Date` | UDFD11 |
| 596 | uDFD12 | `Date` | UDFD12 |
| 597 | uDFD13 | `Date` | UDFD13 |
| 598 | uDFD14 | `Date` | UDFD14 |
| 599 | uDFD15 | `Date` | UDFD15 |
| 600 | uDFD16 | `Date` | UDFD16 |
| 601 | uDFD17 | `Date` | UDFD17 |
| 602 | uDFD18 | `Date` | UDFD18 |
| 603 | uDFD19 | `Date` | UDFD19 |
| 604 | uDFD20 | `Date` | UDFD20 |
| 605 | uDFN01 | `Float` | UDFN01 |
| 606 | uDFN02 | `Float` | UDFN02 |
| 607 | uDFN03 | `Float` | UDFN03 |
| 608 | uDFN04 | `Float` | UDFN04 |
| 609 | uDFN05 | `Float` | UDFN05 |
| 610 | uDFN06 | `Float` | UDFN06 |
| 611 | uDFN07 | `Float` | UDFN07 |
| 612 | uDFN08 | `Float` | UDFN08 |
| 613 | uDFN09 | `Float` | UDFN09 |
| 614 | uDFN10 | `Float` | UDFN10 |
| 615 | uDFN11 | `Float` | UDFN11 |
| 616 | uDFN12 | `Float` | UDFN12 |
| 617 | uDFN13 | `Float` | UDFN13 |
| 618 | uDFN14 | `Float` | UDFN14 |
| 619 | uDFN15 | `Float` | UDFN15 |
| 620 | uDFN16 | `Float` | UDFN16 |
| 621 | uDFN17 | `Float` | UDFN17 |
| 622 | uDFN18 | `Float` | UDFN18 |
| 623 | uDFN19 | `Float` | UDFN19 |
| 624 | uDFN20 | `Float` | UDFN20 |
| 625 | uDFN21 | `Float` | UDFN21 |
| 626 | uDFN22 | `Float` | UDFN22 |
| 627 | uDFN23 | `Float` | UDFN23 |
| 628 | uDFN24 | `Float` | UDFN24 |
| 629 | uDFN25 | `Float` | UDFN25 |
| 630 | uDFN26 | `Float` | UDFN26 |
| 631 | uDFN27 | `Float` | UDFN27 |
| 632 | uDFN28 | `Float` | UDFN28 |
| 633 | uDFN29 | `Float` | UDFN29 |
| 634 | uDFN30 | `Float` | UDFN30 |
| 635 | uDFN31 | `Float` | UDFN31 |
| 636 | uDFN32 | `Float` | UDFN32 |
| 637 | uDFN33 | `Float` | UDFN33 |
| 638 | uDFN34 | `Float` | UDFN34 |
| 639 | uDFN35 | `Float` | UDFN35 |
| 640 | uDFN36 | `Float` | UDFN36 |
| 641 | uDFN37 | `Float` | UDFN37 |
| 642 | uDFN38 | `Float` | UDFN38 |
| 643 | uDFN39 | `Float` | UDFN39 |
| 644 | uDFN40 | `Float` | UDFN40 |
| 645 | uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| 646 | updateDate | `DateTime` | Update Date |
| 647 | updateDatetime | `DateTime` | Update Datetime |
| 648 | updateUser | `Float` | Update User |
| 649 | updatedBy | `String` | Updated By |
| 650 | updatedByDefaultResort | `String` | Updated By Default Property |
| 651 | updatedDate | `Date` | Updated Date |
| 652 | updatedTime | `String` | Updated Time |
| 653 | upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| 654 | videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| 655 | visaExpiryDate | `Date` | Visa Expiry Date |
| 656 | visaIssueDate | `Date` | Visa Issue Date |
| 657 | visaNumber | `String` | Visa Number |
| 658 | waitlistComment | `String` | Waitlist Comment |
| 659 | waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| 660 | waitlistPriority | `String` | Waitlist Priority |
| 661 | waitlistPriorityDescription | `String` | Waitlist Priority Description |
| 662 | waitlistReason | `String` | Waitlist Reason |
| 663 | waitlistReasonDescription | `String` | Waitlist Reason Description |
| 664 | waitlistpriorityid | `String` | Waitlistpriorityid |
| 665 | waitlistreasonid | `String` | Waitlistreasonid |
| 666 | walkInYN | `String` | Walk-In YN |
| 667 | yieldableYn | `String` | Yieldable Y/N |
| 668 | ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### FinancialTransactionDetailsToReservationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| 2 | accompaniedYN | `String` | Accompanied YN |
| 3 | accompanyingName | `String` | Accompanying guest names. |
| 4 | actualCheckInDateTime | `DateTime` | Actual Check In Date Time |
| 5 | actualCheckOutDateTime | `DateTime` | Actual Check Out Date Time |
| 6 | actualCheckInDate | `Date` | Actual Check-In Date |
| 7 | actualCheckInTime | `String` | Actual Check-In Time |
| 8 | actualCheckOutDate | `Date` | Actual Check-Out Date |
| 9 | actualCheckOutTime | `String` | Actual Check-Out Time |
| 10 | addressId | `Float` | Address ID |
| 11 | addresseeNameId | `Float` | Addressee Name ID |
| 12 | adults | `Float` | Adults |
| 13 | adultsTaxFree | `Float` | Adults Tax Free |
| 14 | advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| 15 | agencyprofileid | `Float` | Agencyprofileid |
| 16 | allotmentRecordType | `String` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| 17 | allotmentid | `Float` | Block ID |
| 18 | amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| 19 | amenityLevelCode | `String` | Amenity Level Code |
| 20 | amountPercent | `Float` | Amount Percent |
| 21 | approvalAmount | `Float` | Approval Amount |
| 22 | approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| 23 | approvalCode | `String` | Approval Code |
| 24 | arrivalComments | `String` | Arrival Comments |
| 25 | arrivalDate | `Date` | Arrival Date |
| 26 | arrivalDateTime | `DateTime` | Arrival Date Time |
| 27 | arrivalEstimateTime | `Date` | Arrival Estimate Time |
| 28 | arrivalTime | `String` | Activity begin time |
| 29 | arrivaltransportid | `String` | Arrivaltransportid |
| 30 | attachedDate | `Date` | Attached Date |
| 31 | authorizedBillingYN | `String` | Not used. |
| 32 | authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| 33 | authorizerId | `Float` | Authorizer ID |
| 34 | autoCheckinYn | `String` | Auto Checkin Y/N |
| 35 | autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| 36 | autoSettleDays | `Float` | Auto Settle Days |
| 37 | autoSettleType | `String` | Auto Settle Type |
| 38 | autoSettleYN | `String` | Auto Settle YN |
| 39 | awardCode | `String` | Award Code |
| 40 | awardCode1 | `String` | Award code 1 |
| 41 | awardCode2 | `String` | Award code 2 |
| 42 | awardCode3 | `String` | Award code 3 |
| 43 | awardCode4 | `String` | Award Code 4 |
| 44 | awardCode5 | `String` | Award code 5 |
| 45 | awardMembershipID | `Float` | Award Membership ID |
| 46 | awardVoucher1 | `String` | Award Voucher number 1 |
| 47 | awardVoucher2 | `String` | Award Voucher number 2 |
| 48 | awardVoucher3 | `String` | Award Voucher number 3 |
| 49 | awardVoucher4 | `String` | Award Voucher number 4 |
| 50 | awardVoucher5 | `String` | Award Voucher number 5 |
| 51 | awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| 52 | awdUpgrTo | `String` | Room Type after the Upgrade Award |
| 53 | backToBackYN | `String` | Back To Back YN |
| 54 | balance | `Float` | Balance on the account. |
| 55 | baseRateAmount | `Float` | Base Rate Amount |
| 56 | baseRateCode | `String` | Base Rate Code |
| 57 | baseRateCurrencyCode | `String` | Base Rate Currency Code |
| 58 | basedOnRule | `String` | Based On Rule |
| 59 | baseratecurrencyid | `String` | Baseratecurrencyid |
| 60 | beginCity | `String` | Begin City |
| 61 | beginDatetime | `DateTime` | Begin Datetime |
| 62 | beginDistrict | `String` | Begin District |
| 63 | beginState | `String` | Begin State |
| 64 | beginSystemDateTime | `DateTime` | Stores the actual guest check in date and time. |
| 65 | billNumber | `String` | Bill Number |
| 66 | billingContact | `String` | Billing Contact |
| 67 | billingContactDisplayName | `String` | Billing Contact Display Name |
| 68 | billingContactId | `Float` | Billing Contact ID |
| 69 | billingContactName | `String` | Billing Contact Name |
| 70 | billingcontactprofileid | `Float` | Billing Contact Profile ID |
| 71 | blockCode | `String` | Block Code |
| 72 | blockCreateDate | `DateTime` | Block Create Date |
| 73 | blockID | `Float` | Block ID |
| 74 | blockName | `String` | Block Name |
| 75 | blockResort | `String` | Property this block belongs to. |
| 76 | blockStatus | `String` | Block Status |
| 77 | bonusCheckId | `Float` | Bonus Check ID |
| 78 | bookedRoomCategory | `String` | Booked Room Category |
| 79 | bookedroomcategoryid | `String` | Bookedroomcategoryid |
| 80 | businessDateCreated | `Date` | Business Date Created |
| 81 | businessDatetimeCreated | `DateTime` | Business Datetime Created |
| 82 | bxgyDiscountYn | `String` | Bxgy Discount Y/N |
| 83 | cAutoPostAmount | `Float` | Central Auto Post Amount |
| 84 | cBaseRateAmount | `Float` | Central Base Rate Amount |
| 85 | cDiscountAmount | `Float` | C Discount Amount |
| 86 | cDiscountAmt | `Float` | C Discount Amt |
| 87 | cEffectiveRateAmount | `Float` | C Effective Rate Amount |
| 88 | cExchangeDate | `Date` | Central Xchange Date |
| 89 | cExchangeRate | `Float` | Central Xchange Rate |
| 90 | cFixedCharge | `Float` | Central Fixed Charge |
| 91 | cGrossRateAmount | `Float` | Central Gross Rate Amt |
| 92 | cLocalBaseRateAmount | `Float` | Central Local Base Rate Amount |
| 93 | cNetRoomAmount | `Float` | Central Net Room Amt |
| 94 | cOriginalBaseRate | `Float` | Central Original Base Rate |
| 95 | cPackageAmount | `Float` | Central Pkg Amt |
| 96 | cPackageTax | `Float` | Central Pkg Tax |
| 97 | cRateAmount | `Float` | C Rate Amount |
| 98 | cRoomCost | `Float` | Central Room Cost |
| 99 | cRoomTax | `Float` | Central Room Tax |
| 100 | cShareAmountOriginal | `Float` | Central Share Amount Original |
| 101 | cUpsellCharge | `Float` | Central Upsell Charge |
| 102 | cancelDate | `Date` | Cancel Date |
| 103 | cancelReason | `String` | Cancel Reason |
| 104 | cancelTime | `String` | Cancel Time |
| 105 | cancellationDate | `DateTime` | Cancellation Date |
| 106 | cancellationDatetime | `DateTime` | Cancellation Datetime |
| 107 | cancellationNumber | `String` | Cancellation Number |
| 108 | cancellationReasonDescription | `String` | Cancellation Reason Description |
| 109 | cancellationreasonid | `String` | Cancellationreasonid |
| 110 | cancelledBy | `String` | The user who canceled this Reservation. |
| 111 | cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| 112 | cardNumberByMembershipType | `String` | Card Number by Membership Type |
| 113 | centralApprovalAmount | `Float` | Central Approval Amount |
| 114 | centralCancelReason | `String` | Central Cancel Reason |
| 115 | centralCommissionCode | `String` | Central Commission Code |
| 116 | centralCommissionDescription | `String` | Central Commission Description |
| 117 | centralCreditLimit | `Float` | Central Credit Limit |
| 118 | centralDiscountReason | `String` | Central Discount Reason |
| 119 | centralDiscountReasonDescription | `String` | Central Discount Reason Description |
| 120 | centralFBRevenue | `Float` | Central FB Revenue |
| 121 | centralGuestType | `String` | Central Guest Type |
| 122 | centralHurdle | `Float` | Central Hurdle |
| 123 | centralPackageCode | `String` | Central Package Code |
| 124 | centralPackageCodeDescription | `String` | Central Package Code Description |
| 125 | centralPackageForecastGroup | `String` | Central Package Forecast Group |
| 126 | centralPackageForecastGroupDescription | `String` | Central Package Forecast Group Description |
| 127 | centralPaymentAmount | `Float` | Central Payment Amount |
| 128 | centralProjectedFBRevenue | `Float` | Central Projected FB Revenue |
| 129 | centralProjectedRoomRevenue | `Float` | Central Projected Room Revenue |
| 130 | centralProjectedTotalRevenue | `Float` | Central Projected Total Revenue |
| 131 | centralPromotionDescription | `String` | Central Promotion Description |
| 132 | centralRateableValue | `Float` | Central Rateable Value |
| 133 | centralReservationType | `String` | Central Reservation Type |
| 134 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 135 | centralRoomRevenue | `Float` | Central Room Revenue |
| 136 | centralRoomTypeCode | `String` | Central Room Type Code |
| 137 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 138 | centralRoomTypeToChargeCode | `String` | Central Room Type To Charge Code |
| 139 | centralRoomTypeToChargeDescription | `String` | Central Room Type to Charge Description |
| 140 | centralSharedRoomRate | `Float` | Central Shared Room Rate |
| 141 | centralSpecialRequestDescription | `String` | Central Special Request Description |
| 142 | centralTaxType | `String` | Central Tax Type |
| 143 | centralTaxTypeDescription | `String` | Central Tax Type Description |
| 144 | centralTotalCostOfStay | `Float` | Central Total Cost of Stay |
| 145 | centralTotalRevenue | `Float` | Central Total Revenue |
| 146 | centralTotalRoomRate | `Float` | Central Total Room Rate |
| 147 | centralWaitlistPriority | `String` | Central Waitlist Priority |
| 148 | centralWaitlistPriorityDescription | `String` | Central Waitlist Priority Description |
| 149 | centralWaitlistReason | `String` | Central Waitlist Reason |
| 150 | centralWaitlistReasonDescription | `String` | Central Waitlist Reason Description |
| 151 | channelDescription | `String` | Channel Description |
| 152 | channelOrderBy | `Float` | Channel Order By |
| 153 | channelid | `String` | Channelid |
| 154 | checkInInitiatedBy | `String` | Check In Initiated By |
| 155 | checkinDuration | `Float` | Duration in seconds to complete Check-In |
| 156 | childBucket1 | `Float` | Child Bucket 1 |
| 157 | childBucket4 | `Float` | Child Bucket 4 |
| 158 | childBucket5 | `Float` | Child Bucket 5 |
| 159 | children | `Float` | Children |
| 160 | childrenAgeGroup2 | `Float` | Children Age Group 2) |
| 161 | childrenAgeGroup3 | `Float` | Children Age Group 3) |
| 162 | childrenAges | `String` | Children Ages |
| 163 | commissionCode | `String` | Commission Code |
| 164 | commissionDescription | `String` | Commission Description |
| 165 | commissionHoldCode | `String` | Commission Hold Code |
| 166 | commissionPaid | `Float` | Commission Paid |
| 167 | commissionPayoutTo | `String` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| 168 | commissionableYN | `String` | Commissionable YN |
| 169 | commissionid | `String` | Commissionid |
| 170 | compHouse | `String` | Comp House |
| 171 | compTypeCode | `String` | Comp Type Code |
| 172 | companyCity | `String` | Company City |
| 173 | companyCountry | `String` | Company Country |
| 174 | companyID | `Float` | Company ID |
| 175 | companyName | `String` | Company Name |
| 176 | companyProfileCorporateID | `String` | Company Profile Corporate ID |
| 177 | companyProfileID | `Float` | Company Profile ID |
| 178 | complimentaryYN | `String` | Complimentary YN |
| 179 | compreasonid | `String` | Compreasonid |
| 180 | computedResvStatus | `String` | Calculated reservation status. |
| 181 | confirmationLegNumber | `Float` | Confirmation Leg Number. |
| 182 | confirmationNo | `String` | Shared Confirmation Number |
| 183 | consumerYn | `String` | Consumer Y/N |
| 184 | contactName | `String` | Contact Name; UDFC02 on reservation. |
| 185 | contactProfileID | `Float` | Contact Profile ID |
| 186 | contactProfileName | `String` | Contact Profile Name |
| 187 | createdBy | `String` | The name of the user who created the record. |
| 188 | createdByDefaultResort | `String` | Created By Default Property |
| 189 | createdDate | `Date` | Created Date |
| 190 | createdTime | `String` | Refer to the same column name in the table IFC_WAKE |
| 191 | creditCardAuthDate | `Date` | Credit Card Auth Date |
| 192 | creditCardId | `Float` | Credit Card ID |
| 193 | creditLimit | `Float` | Credit Limit |
| 194 | creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| 195 | cribs | `Float` | Cribs |
| 196 | currencyCode | `String` | Currency Code |
| 197 | customReferenceNumber | `String` | Custom Reference Number |
| 198 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 199 | dateOfArrivalInCountry | `Date` | Country Specific Requirement for Nigeria. |
| 200 | deletedFlag | `String` | Deleted Flag |
| 201 | departtransportid | `String` | Departtransportid |
| 202 | departureComments | `String` | Departure Comments |
| 203 | departureDate | `Date` | Departure Date |
| 204 | departureDateTime | `Date` | Departure Date Time |
| 205 | departureTime | `String` | Departure Time |
| 206 | departureTransportCode | `String` | Departure Transport Code |
| 207 | departureTransportationYN | `String` | Departure Transportation YN |
| 208 | depositMaturityType | `String` | Stores the Deposit maturity preference. |
| 209 | detatchedDate | `Date` | Detatched Date |
| 210 | detatchedYN | `String` | Detatched YN |
| 211 | directBillVerifyResponse | `String` | Direct Bill Verify Response |
| 212 | directbillauthby | `Float` | Directbillauthby |
| 213 | discountAmount | `Float` | Discount Amount |
| 214 | discountAmt | `Float` | Discount Amount |
| 215 | discountPercent | `Float` | Discount Percentage. |
| 216 | discountPrcnt | `Float` | Discount Prcnt |
| 217 | discountReason | `String` | Discount Reason |
| 218 | discountReasonDescription | `String` | Discount Reason Description |
| 219 | discountreasonid | `String` | Discountreasonid |
| 220 | displayColor | `String` | Display Color |
| 221 | dmlSeqNumber | `Float` | Dml Sequence No |
| 222 | doNotMoveRoom | `String` | Do Not Move Room |
| 223 | doNotMoveYN | `String` | Do not move room flag. |
| 224 | dropOffCarrierCode | `String` | Drop Off Carrier Code |
| 225 | dropOffDate | `Date` | Drop Off Date |
| 226 | dropOffStation | `String` | Drop Off Station |
| 227 | dropOffTime | `String` | Drop Off Time |
| 228 | dropOffType | `String` | Drop Off Type |
| 229 | dropOffTypeDescription | `String` | Drop Off Type Description |
| 230 | eTRComments | `String` | Comments related to Estimated Time of Return. |
| 231 | effectiveRateAmount | `Float` | Not used. |
| 232 | eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| 233 | emailAddress | `String` | Email Address |
| 234 | emailFolioYn | `String` | Email Folio Y/N |
| 235 | emailId | `Float` | Email ID |
| 236 | emailYn | `String` | Email Y/N |
| 237 | endCity | `String` | End City |
| 238 | endDatetime | `DateTime` | End Datetime |
| 239 | endDistrict | `String` | End District |
| 240 | endState | `String` | End State |
| 241 | endbusinessdate | `Date` | Endbusinessdate |
| 242 | entryDate | `Date` | Entry Date into the country. (Croatian Requirements) |
| 243 | entryPoint | `String` | (Customized) Entry point into the country. (Croatian Requirements) |
| 244 | esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| 245 | estimatedDepartureTime | `Date` | Estimated Departure Time |
| 246 | eventId | `Float` | Event ID |
| 247 | exchangePostingType | `String` | Exchange Posting Type |
| 248 | exchangeRate | `Float` | Exchange Rate |
| 249 | excludeFromAutoAuthorizationYN | `String` | Exclude From Auto Authorization YN |
| 250 | expectedTimeOfReturnETR | `DateTime` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| 251 | exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| 252 | extSegNo | `Float` | Not used |
| 253 | extSeqNumber | `Float` | Not used |
| 254 | extensionId | `Float` | Internal extension number for the main reservation |
| 255 | externalEfolioYn | `String` | Indicates if the guest has opted to receive Efolio through an external system. |
| 256 | externalReference | `String` | External Reference |
| 257 | externalReferencesList | `String` | External References List |
| 258 | extraBeds | `Float` | Extra Beds |
| 259 | fBRevenue | `Float` | FB Revenue |
| 260 | fBRevenueRemaining | `Float` | F&B Revenue Remaining |
| 261 | faxId | `Float` | Fax ID |
| 262 | faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| 263 | feature | `String` | This stores the codes for the rooms features. Currently not used |
| 264 | financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| 265 | fixedCharge | `Float` | Not used. |
| 266 | fixedRateYN | `String` | Fixed Rate YN |
| 267 | folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| 268 | folioCloseDate | `Date` | Date the folio was changed to closed. |
| 269 | folioNumber | `String` | Folio Number |
| 270 | folioText1 | `String` | Folio Text1 |
| 271 | folioText2 | `String` | Folio Text2 |
| 272 | foreignCurrencyID | `String` | Foreign Currency ID |
| 273 | freeChild | `Float` | Free Child |
| 274 | frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| 275 | grossRateFuture | `Float` | Gross Rate Future |
| 276 | grossRatePast | `Float` | Gross Rate Past |
| 277 | groupName | `String` | Group Name |
| 278 | groupProfileARNumber | `Float` | Group Profile AR Number |
| 279 | groupProfileARNumberCentral | `String` | Group Profile AR Number (Central) |
| 280 | groupProfileClientID | `String` | Group Profile Client ID |
| 281 | groupProfileID | `Float` | Group Profile ID |
| 282 | groupProfileName | `String` | Group Profile Name |
| 283 | guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| 284 | guaranteecodeid | `String` | Guaranteecodeid |
| 285 | guestFirstName | `String` | Guest First Name |
| 286 | guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| 287 | guestLastNameSdx | `String` | This is soundex of GUEST LAST NAME - Phonotic sound. |
| 288 | guestSignature | `String` | Signature of the guest |
| 289 | guestStatus | `String` | Used for Police/Tourist Export |
| 290 | guestType | `String` | Guest Type |
| 291 | guestprofileid | `Float` | Guestprofileid |
| 292 | gueststatusid | `String` | Gueststatusid |
| 293 | guesttypeid | `String` | Guesttypeid |
| 294 | housekeepingServiceTime | `String` | Housekeeping Service Time |
| 295 | hurdle | `Float` | Hurdle |
| 296 | hurdleOverride | `String` | Hurdle Override |
| 297 | iDByMembershipClass | `String` | ID by Membership Class |
| 298 | iDByMembershipType | `String` | ID by Membership Type |
| 299 | individualCity | `String` | Guest Address. |
| 300 | individualCountry | `String` | Country of the guest |
| 301 | individualFirstName | `String` | Individual First Name |
| 302 | individualLastName | `String` | Individual Last Name |
| 303 | insertActionInstanceId | `Float` | Insert Action Instance ID |
| 304 | insertDate | `DateTime` | Insert Date |
| 305 | insertDateTime | `DateTime` | Insert DateTime |
| 306 | insertUser | `Float` | Insert User |
| 307 | intermediaryYn | `String` | Intermediary Y/N |
| 308 | internalAwardMembershipId | `Float` | Award Membership ID |
| 309 | internalBaseratecode | `String` | Baseratecode |
| 310 | internalBlockId | `Float` | Block ID. |
| 311 | internalCompanyprofileid | `Float` | Companyprofileid |
| 312 | internalGroupprofileid | `Float` | Groupprofileid |
| 313 | internalSourceprofileid | `Float` | Sourceprofileid |
| 314 | itemsQuantities | `String` | Items and Quantities |
| 315 | jRNUpdateDate | `Date` | JRN Update Date |
| 316 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 317 | keyValidUntil | `Date` | Key Valid Until |
| 318 | lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| 319 | lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| 320 | lastRoomNumber | `String` | Not used. |
| 321 | lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| 322 | leadTimeDays | `Float` | Lead Time for ordering |
| 323 | lengthOfStay | `Float` | Length of Stay |
| 324 | linkedArrivalDate | `DateTime` | Linked Arrival Date |
| 325 | linkedDepartureDate | `DateTime` | Linked Departure Date |
| 326 | linkedRoomType | `String` | Linked Room Type |
| 327 | listOfMembershipID | `String` | Membership ID |
| 328 | localBaseRateAmount | `Float` | Local Base Rate Amount |
| 329 | locationID | `String` | Internal ID to uniquely identify the Property |
| 330 | loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| 331 | mailYn | `String` | Mail Y/N |
| 332 | manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| 333 | marketCode | `String` | Market Code |
| 334 | marketid | `String` | Marketid |
| 335 | mcGenBeginDistrict | `String` | Mc Gen Begin District |
| 336 | mcGenBeginState | `String` | Mc Gen Begin State |
| 337 | mcGenEndDistrict | `String` | Mc Gen End District |
| 338 | mcGenEndState | `String` | Mc Gen End State |
| 339 | mcGenNextCountry | `String` | Mc Gen Next Country |
| 340 | mcGenPreviousCountry | `String` | Mc Gen Previous Country |
| 341 | memberDescription | `String` | Member Description |
| 342 | memberLevel | `String` | Member Level |
| 343 | memberNumber | `String` | Member Number |
| 344 | membershipClass | `String` | Membership Class |
| 345 | membershipClassDescription | `String` | Membership Class Description |
| 346 | membershipCode | `String` | Membership Code |
| 347 | membershipId | `Float` | Membership ID |
| 348 | membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| 349 | membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| 350 | mobileActionAlertIssued | `Date` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| 351 | mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| 352 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 353 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 354 | mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| 355 | mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| 356 | name | `String` | Name |
| 357 | nameUsageType | `String` | Name Usage Type |
| 358 | nextCountry | `String` | Next Country |
| 359 | nextDestination | `String` | Country Specific Requirement for Nigeria. |
| 360 | numberOfRooms | `Float` | No of Rooms |
| 361 | operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| 362 | optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| 363 | optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| 364 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 365 | originCode | `String` | Origin Code |
| 366 | originOfBooking | `String` | Origin Of Booking |
| 367 | originalBaseRate | `Float` | Not used. |
| 368 | originalEndDate | `Date` | Original End Date |
| 369 | originalStartDate | `Date` | Original Start Date |
| 370 | ownerFfFlag | `String` | Owner Ff Flag |
| 371 | ownerOrFriendsFamily | `String` | Owner or Friends/Family |
| 372 | packageCode | `String` | Package Code |
| 373 | packageCodeDescription | `String` | Package Code Description |
| 374 | packageForecastGroup | `String` | Package Forecast Group |
| 375 | packageForecastGroupDescription | `String` | Package Forecast Group Description |
| 376 | parentReservationNameId | `Float` | Parent Resv Name ID |
| 377 | parentreservationid | `Float` | Parentreservationid |
| 378 | partAllotment | `String` | Part Allotment |
| 379 | partyCode | `String` | Party Code |
| 380 | paxNo | `Float` | Pax Number |
| 381 | paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| 382 | paymentMethod | `String` | Payment Method |
| 383 | paymentmethodid | `String` | Paymentmethodid |
| 384 | periodicFolioFreq | `Float` | Frequency in number of days when folios should be printed for this reservation |
| 385 | phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| 386 | phoneId | `Float` | Phone ID |
| 387 | physicalQuantity | `Float` | Physical Quantity |
| 388 | pickUpCarrierCode | `String` | Pick Up Carrier Code |
| 389 | pickUpDate | `Date` | Pick Up Date |
| 390 | pickUpStation | `String` | Pick Up Station |
| 391 | pickUpTransportNumber | `String` | Pick Up Transport Number |
| 392 | pickUpType | `String` | Pick Up Type |
| 393 | pickUpTypeDescription | `String` | Pick Up Type Description |
| 394 | pickUpTime | `String` | Pick-Up Time |
| 395 | pickupRequiredYN | `String` | Pickup Required YN |
| 396 | points | `Float` | Points |
| 397 | pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| 398 | postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| 399 | postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| 400 | postingAllowedYN | `String` | Posting Allowed YN |
| 401 | preArrReviewedDt | `DateTime` | This date flags if and when the record was reviewed from pre-arrival screen. |
| 402 | preArrReviewedUser | `Float` | User id who reviewed the record. |
| 403 | preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| 404 | preRegisteredYn | `String` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| 405 | preference | `String` | Preference |
| 406 | preferenceType | `String` | Preference Type |
| 407 | preferredRoomType | `String` | Preferred Room Type |
| 408 | previousCountry | `String` | Previous Country |
| 409 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 410 | primaryShare | `String` | Primary Share |
| 411 | printRateYN | `String` | Print Rate YN |
| 412 | projectedFBRevenue | `Float` | Projected FB Revenue |
| 413 | projectedRoomRevenue | `Float` | Projected Room Revenue |
| 414 | projectedTotalRevenue | `Float` | Projected Total Revenue |
| 415 | promotionCode | `String` | Promotion Code |
| 416 | promotionDescription | `String` | Promotion Description |
| 417 | property | `String` | Indicates if the value set for the specific property. |
| 418 | pseudoMemTotalPoints | `Float` | Total pseudo membership points accrued for the default membership type. |
| 419 | pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| 420 | purgeDate | `DateTime` | Purge Date |
| 421 | purposeOfStay | `String` | Purpose of stay. |
| 422 | quantity | `Float` | Number of Rooms |
| 423 | queuePriority | `Float` | Queue priority of the reservation. |
| 424 | queueWaitTime | `Float` | Queue Wait Time |
| 425 | quoteId | `String` | Quote ID provided by external system. |
| 426 | rateAmount | `Float` | Rate Amount |
| 427 | rateCode | `String` | Rate Code |
| 428 | rateCodeDescriptions | `String` | Event Reservation Rate Code Description |
| 429 | rateTier | `Float` | Tier ID for the Rate Detail. |
| 430 | rateableValue | `Float` | Stay rateable value. |
| 431 | ratecodeid | `String` | Ratecodeid |
| 432 | rdHousekeepingExpectedServiceTime | `String` | Rd Housekeeping Expected Service Time |
| 433 | rdResvStatus | `String` | Rd Reservation Status |
| 434 | rdenBillingContactId | `Float` | Rden Billing Contact ID |
| 435 | rdenReservationContactId | `Float` | Rden Resv Contact ID |
| 436 | rdenReservationDate | `Date` | Rden Reservation Date |
| 437 | rdenResort | `String` | Rden Property |
| 438 | referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| 439 | registrationCardNo | `String` | Registration Card Number |
| 440 | registrationNumber | `Float` | Registration Number |
| 441 | reinstateDate | `DateTime` | Reinstate Date |
| 442 | repChannel | `String` | Reporting Channel |
| 443 | repChannelDescription | `String` | Reporting Channel Description |
| 444 | reportId | `String` | Report ID |
| 445 | resInsertSource | `String` | Reservation Insert Source |
| 446 | resInsertSourceType | `String` | Reservation Insert Source Type |
| 447 | reservationContactId | `Float` | Resv Contact ID |
| 448 | reservationDate | `DateTime` | Reservation Date |
| 449 | reservationNameID | `Float` | Reservation Name ID |
| 450 | reservationStatus | `String` | Reservation Status |
| 451 | reservationType | `String` | Reservation Type |
| 452 | reservationTypeDescription | `String` | Reservation Type Description |
| 453 | reservationid | `Float` | Reservationid |
| 454 | resort | `String` | Property |
| 455 | resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| 456 | restrictionOverride | `String` | Restriction Override |
| 457 | resvGuid | `String` | Globally unique ID using SYS_GUID() as the source. |
| 458 | resvNameid | `Float` | Reservation Nameid |
| 459 | resvNumber | `Float` | Not used in PMS currently. |
| 460 | resvcontactprofileid | `Float` | Resvcontactprofileid |
| 461 | revenueTypeCode | `String` | Revenue type (catering/rooms) |
| 462 | rhBillingContactId | `Float` | Rh Billing Contact ID |
| 463 | rhReservationContactId | `Float` | Rh Resv Contact ID |
| 464 | rhRoomFeatures | `String` | Rh Room Features |
| 465 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 466 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 467 | room | `String` | Room |
| 468 | roomCategory | `String` | Room Category |
| 469 | roomClass | `String` | Room Class |
| 470 | roomCost | `Float` | Room Cost |
| 471 | roomInstructions | `String` | Room Instructions |
| 472 | roomResort | `String` | Meeting Room Property |
| 473 | roomRevenue | `Float` | Room Revenue |
| 474 | roomRevenueRemaining | `Float` | Room Revenue Remaining |
| 475 | roomServiceTime | `String` | This is the Turndown room service time. |
| 476 | roomTypeDescription | `String` | Room Type Description |
| 477 | roomTypeToChargeCode | `String` | Room Type To Charge Code |
| 478 | roomTypeToChargeDescription | `String` | Room Type to Charge Description |
| 479 | roomcategoryid | `String` | Roomcategoryid |
| 480 | roomid | `String` | Roomid |
| 481 | routingYN | `String` | Routing YN |
| 482 | scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| 483 | sguestFirstname | `String` | This is CAPITOL version of guest_first_name |
| 484 | sguestName | `String` | Sguest Name |
| 485 | shareConfirmationNumbers | `String` | Share Confirmation Numbers |
| 486 | shareId | `Float` | Share ID. |
| 487 | shareName | `String` | Share Name |
| 488 | sharePrcnt | `Float` | Not used. |
| 489 | shareSeqNumber | `Float` | Type of revenue |
| 490 | shareOfRateAmount | `Float` | Share of Rate Amount |
| 491 | sharedGuestName | `String` | Shared Guest Name |
| 492 | sharedProfileID | `Float` | Shared Profile ID |
| 493 | sharedReservationStatus | `String` | Shared Reservation Status |
| 494 | sharingYN | `String` | Sharing YN |
| 495 | sourceCity | `String` | Source City |
| 496 | sourceCode | `String` | Source Code |
| 497 | sourceCountry | `String` | Source Country |
| 498 | sourceName | `String` | Source Name |
| 499 | sourceProfileARNumber | `Float` | Source Profile AR Number |
| 500 | sourceProfileARNumberCentral | `String` | Source Profile AR Number (Central) |
| 501 | sourceProfileIATANumber | `String` | Source Profile IATA Number |
| 502 | sourceProfileID | `Float` | Source Profile ID |
| 503 | sourceProfileName | `String` | Source Profile Name |
| 504 | sourceid | `String` | Sourceid |
| 505 | specialRequest | `String` | Special Request |
| 506 | specialRequestDescription | `String` | Special Request Description |
| 507 | spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| 508 | spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| 509 | spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| 510 | spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| 511 | splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| 512 | splitfromreservationid | `Float` | Splitfromreservationid |
| 513 | statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| 514 | statisticalRoomType | `Float` | Room Type used to calculate statistics for export(DRS). |
| 515 | stayRecordId | `Float` | Stay Record ID |
| 516 | suiteNumber | `String` | Suite Number |
| 517 | superSearchIndexText | `String` | Super Search Index Text |
| 518 | taRecordLocator | `String` | Ta Record Locator |
| 519 | taxExemptNumber | `String` | Tax exempt number on the profile |
| 520 | taxNumberOfStays | `Float` | Tax No of Stays |
| 521 | taxType | `String` | Tax Type |
| 522 | taxTypeDescription | `String` | Tax Type Description |
| 523 | taxtypeid | `String` | Taxtypeid |
| 524 | tiad | `String` | Tiad |
| 525 | ticketNos | `String` | Ticket Nos |
| 526 | totalCostOfStay | `Float` | Total Cost of Stay |
| 527 | totalRevenue | `Float` | Total Revenue |
| 528 | totalRevenueRemaining | `Float` | Total Revenue Remaining |
| 529 | totalRoomRate | `Float` | Total Room Rate |
| 530 | trackItGroups | `String` | Track It Groups |
| 531 | trackItTypes | `String` | Track It Types |
| 532 | transactionid | `Float` | Transactionid |
| 533 | travelAgentCity | `String` | Travel Agent Address. |
| 534 | travelAgentCountry | `String` | Travel Agent Country |
| 535 | travelAgentID | `Float` | Travel Agent ID |
| 536 | travelAgentName | `String` | Travel Agent Name |
| 537 | travelAgentProfileARNumber | `Float` | Travel Agent Profile AR Number |
| 538 | travelAgentProfileARNumberCentral | `String` | Travel Agent Profile AR Number (Central) |
| 539 | travelAgentProfileIATANumber | `String` | Travel Agent Profile IATA Number |
| 540 | travelAgentProfileID | `Float` | Travel Agent Profile ID |
| 541 | travelAgentProfileName | `String` | Travel Agent Profile Name |
| 542 | truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| 543 | turndownStatus | `String` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
| 544 | turndownYN | `String` | Is the guest wants turndown facility or not ? Y/N |
| 545 | uDFC01 | `String` | UDFC01 |
| 546 | uDFC02 | `String` | UDFC02 |
| 547 | uDFC03 | `String` | UDFC03 |
| 548 | uDFC04 | `String` | UDFC04 |
| 549 | uDFC05 | `String` | UDFC05 |
| 550 | uDFC06 | `String` | UDFC06 |
| 551 | uDFC07 | `String` | UDFC07 |
| 552 | uDFC08 | `String` | UDFC08 |
| 553 | uDFC09 | `String` | UDFC09 |
| 554 | uDFC10 | `String` | UDFC10 |
| 555 | uDFC11 | `String` | UDFC11 |
| 556 | uDFC12 | `String` | UDFC12 |
| 557 | uDFC13 | `String` | UDFC13 |
| 558 | uDFC14 | `String` | UDFC14 |
| 559 | uDFC15 | `String` | UDFC15 |
| 560 | uDFC16 | `String` | UDFC16 |
| 561 | uDFC17 | `String` | UDFC17 |
| 562 | uDFC18 | `String` | UDFC18 |
| 563 | uDFC19 | `String` | UDFC19 |
| 564 | uDFC20 | `String` | UDFC20 |
| 565 | uDFC21 | `String` | UDFC21 |
| 566 | uDFC22 | `String` | UDFC22 |
| 567 | uDFC23 | `String` | UDFC23 |
| 568 | uDFC24 | `String` | UDFC24 |
| 569 | uDFC25 | `String` | UDFC25 |
| 570 | uDFC26 | `String` | UDFC26 |
| 571 | uDFC27 | `String` | UDFC27 |
| 572 | uDFC28 | `String` | UDFC28 |
| 573 | uDFC29 | `String` | UDFC29 |
| 574 | uDFC30 | `String` | UDFC30 |
| 575 | uDFC31 | `String` | UDFC31 |
| 576 | uDFC32 | `String` | UDFC32 |
| 577 | uDFC33 | `String` | UDFC33 |
| 578 | uDFC34 | `String` | UDFC34 |
| 579 | uDFC35 | `String` | UDFC35 |
| 580 | uDFC36 | `String` | UDFC36 |
| 581 | uDFC37 | `String` | UDFC37 |
| 582 | uDFC38 | `String` | UDFC38 |
| 583 | uDFC39 | `String` | UDFC39 |
| 584 | uDFC40 | `String` | UDFC40 |
| 585 | uDFD01 | `Date` | UDFD01 |
| 586 | uDFD02 | `Date` | UDFD02 |
| 587 | uDFD03 | `Date` | UDFD03 |
| 588 | uDFD04 | `Date` | UDFD04 |
| 589 | uDFD05 | `Date` | UDFD05 |
| 590 | uDFD06 | `Date` | UDFD06 |
| 591 | uDFD07 | `Date` | UDFD07 |
| 592 | uDFD08 | `Date` | UDFD08 |
| 593 | uDFD09 | `Date` | UDFD09 |
| 594 | uDFD10 | `Date` | UDFD10 |
| 595 | uDFD11 | `Date` | UDFD11 |
| 596 | uDFD12 | `Date` | UDFD12 |
| 597 | uDFD13 | `Date` | UDFD13 |
| 598 | uDFD14 | `Date` | UDFD14 |
| 599 | uDFD15 | `Date` | UDFD15 |
| 600 | uDFD16 | `Date` | UDFD16 |
| 601 | uDFD17 | `Date` | UDFD17 |
| 602 | uDFD18 | `Date` | UDFD18 |
| 603 | uDFD19 | `Date` | UDFD19 |
| 604 | uDFD20 | `Date` | UDFD20 |
| 605 | uDFN01 | `Float` | UDFN01 |
| 606 | uDFN02 | `Float` | UDFN02 |
| 607 | uDFN03 | `Float` | UDFN03 |
| 608 | uDFN04 | `Float` | UDFN04 |
| 609 | uDFN05 | `Float` | UDFN05 |
| 610 | uDFN06 | `Float` | UDFN06 |
| 611 | uDFN07 | `Float` | UDFN07 |
| 612 | uDFN08 | `Float` | UDFN08 |
| 613 | uDFN09 | `Float` | UDFN09 |
| 614 | uDFN10 | `Float` | UDFN10 |
| 615 | uDFN11 | `Float` | UDFN11 |
| 616 | uDFN12 | `Float` | UDFN12 |
| 617 | uDFN13 | `Float` | UDFN13 |
| 618 | uDFN14 | `Float` | UDFN14 |
| 619 | uDFN15 | `Float` | UDFN15 |
| 620 | uDFN16 | `Float` | UDFN16 |
| 621 | uDFN17 | `Float` | UDFN17 |
| 622 | uDFN18 | `Float` | UDFN18 |
| 623 | uDFN19 | `Float` | UDFN19 |
| 624 | uDFN20 | `Float` | UDFN20 |
| 625 | uDFN21 | `Float` | UDFN21 |
| 626 | uDFN22 | `Float` | UDFN22 |
| 627 | uDFN23 | `Float` | UDFN23 |
| 628 | uDFN24 | `Float` | UDFN24 |
| 629 | uDFN25 | `Float` | UDFN25 |
| 630 | uDFN26 | `Float` | UDFN26 |
| 631 | uDFN27 | `Float` | UDFN27 |
| 632 | uDFN28 | `Float` | UDFN28 |
| 633 | uDFN29 | `Float` | UDFN29 |
| 634 | uDFN30 | `Float` | UDFN30 |
| 635 | uDFN31 | `Float` | UDFN31 |
| 636 | uDFN32 | `Float` | UDFN32 |
| 637 | uDFN33 | `Float` | UDFN33 |
| 638 | uDFN34 | `Float` | UDFN34 |
| 639 | uDFN35 | `Float` | UDFN35 |
| 640 | uDFN36 | `Float` | UDFN36 |
| 641 | uDFN37 | `Float` | UDFN37 |
| 642 | uDFN38 | `Float` | UDFN38 |
| 643 | uDFN39 | `Float` | UDFN39 |
| 644 | uDFN40 | `Float` | UDFN40 |
| 645 | uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| 646 | updateDate | `DateTime` | Update Date |
| 647 | updateDatetime | `DateTime` | Update Datetime |
| 648 | updateUser | `Float` | Update User |
| 649 | updatedBy | `String` | Updated By |
| 650 | updatedByDefaultResort | `String` | Updated By Default Property |
| 651 | updatedDate | `Date` | Updated Date |
| 652 | updatedTime | `String` | Updated Time |
| 653 | upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| 654 | videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| 655 | visaExpiryDate | `Date` | Visa Expiry Date |
| 656 | visaIssueDate | `Date` | Visa Issue Date |
| 657 | visaNumber | `String` | Visa Number |
| 658 | waitlistComment | `String` | Waitlist Comment |
| 659 | waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| 660 | waitlistPriority | `String` | Waitlist Priority |
| 661 | waitlistPriorityDescription | `String` | Waitlist Priority Description |
| 662 | waitlistReason | `String` | Waitlist Reason |
| 663 | waitlistReasonDescription | `String` | Waitlist Reason Description |
| 664 | waitlistpriorityid | `String` | Waitlistpriorityid |
| 665 | waitlistreasonid | `String` | Waitlistreasonid |
| 666 | walkInYN | `String` | Walk-In YN |
| 667 | yieldableYn | `String` | Yieldable Y/N |
| 668 | ymCode | `String` | Ym Code |

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
#### Validation Rules

**`conditionalInputPair(pair: 1)`**
- financialtransDetailsChainCode
- financialtransDetailsResort

**`conditionalInputPair(pair: 2)`**
- financialtransDetailsArLedCredit
- financialtransDetailsArLedDebit
- financialtransDetailsArNumber
- financialtransDetailsAccountid
- financialtransDetailsArticleId
- financialtransDetailsAuthemployeeid
- financialtransDetailsBonusCheckId
- financialtransDetailsBusinessDate
- financialtransDetailsCXchangeDate
- financialtransDetailsCXchangeRate
- financialtransDetailsCashierId
- financialtransDetailsChequeNumber
- financialtransDetailsClosureNo
- financialtransDetailsCompLinkTrxCode
- financialtransDetailsComplinktranscodeid
- financialtransDetailsExchDiffTrxNo
- financialtransDetailsFinDmlSeqNo
- financialtransDetailsFintransactionid
- financialtransDetailsFintransid
- financialtransDetailsBillNo
- financialtransDetailsFolioView
- financialtransDetailsFolioid
- financialtransDetailsFromResvId
- financialtransDetailsGuestAccountCredit
- financialtransDetailsGuestAccountDebit
- financialtransDetailsHotelAcct
- financialtransDetailsInsertDate
- financialtransDetailsArticleid
- financialtransDetailsBusinessdate
- financialtransDetailsCashierid
- financialtransDetailsFolioNo
- financialtransDetailsInvoiceNo
- financialtransDetailsJrnupdatedttm
- financialtransDetailsLinkTrxNo
- financialtransDetailsLocationid
- financialtransDetailsNameId
- financialtransDetailsOriginalResvNameId
- financialtransDetailsOriginalRoom
- financialtransDetailsOriginalresvid
- financialtransDetailsProduct
- financialtransDetailsPackagelinkfintransid
- financialtransDetailsParentfintransid
- financialtransDetailsPostitNo
- financialtransDetailsProductid
- financialtransDetailsProfileid
- financialtransDetailsRateCode
- financialtransDetailsRatecodeid
- financialtransDetailsReservationid
- financialtransDetailsRoom
- financialtransDetailsRoomid
- financialtransDetailsRoundLinkTrxno
- financialtransDetailsRoutingInstrnId
- financialtransDetailsTranActionId
- financialtransDetailsTranscodeid
- financialtransDetailsTrxDate
- financialtransDetailsTrxNoAddedBy
- financialtransDetailsResvNameId
- financialtransDetailsTrxNo
- financialtransDetailsTrxNoAgainstPackage
- financialtransDetailsTrxNoAdjust
- financialtransDetailsTrxNoHeader
- financialtransDetailsAuthorizerId


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