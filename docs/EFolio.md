# EFolio
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `eFolio`
> This subject area contains data for billing folio settlements to be used for exporting to an external system for efolios.
  
**Return:** [`[EFolioType]`](#efoliotype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`EFolioQueryArgumentsType!`](#efolioqueryargumentstype) |  |

## Object Types

### EFolioType

| Field | Type | Description |
| --- | --- | --- |
| folioTaxDetails | [`EFolioFolioTaxDetailsType`](#efoliofoliotaxdetailstype) | Folio Tax Details |
| folioTransactionsDetails | [`EFolioFolioTransactionsDetailsType`](#efoliofoliotransactionsdetailstype) | Folio Transactions Details |
| propertyExportValuesDetails | [`EFolioPropertyExportValuesDetailsType`](#efoliopropertyexportvaluesdetailstype) | Property Export Values |
| profileAllInformationDetails | [`EFolioProfileAllInformationDetailsType`](#efolioprofileallinformationdetailstype) | Profile All Details |
| profileAddressDetails | [`EFolioProfileAddressDetailsType`](#efolioprofileaddressdetailstype) | Profile Address Details |
| profileCommunicationDetails | [`EFolioProfileCommunicationDetailsType`](#efolioprofilecommunicationdetailstype) | Profile Communication Details |
| reservationDetails | [`EFolioReservationDetailsType`](#efolioreservationdetailstype) | Reservation Details |
| fiscalCalendarDetails | [`EFolioFiscalCalendarDetailsType`](#efoliofiscalcalendardetailstype) | Fiscal Calendar |
| gregerianCalendarDetails | [`EFolioGregerianCalendarDetailsType`](#efoliogregeriancalendardetailstype) | Gregerian Calendar |
| exportMapEfolioExportDetails | [`EFolioExportMapEfolioExportDetailsType`](#efolioexportmapefolioexportdetailstype) | Export Map Efolio Export |
| eFolioRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### EFolioFolioTaxDetailsType

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

### EFolioFolioTransactionsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| aSBFlag | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| accountCode | `Float` | Account Code |
| accountTypeFlag | `String` | Account Type Flag |
| accountid | `Float` | Accountid |
| address1 | `String` | Address1 |
| addresseeNameId | `Float` | Addressee Name ID |
| adjustmentflag | `String` | Adjustmentflag |
| advGenerateAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| advanceGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| advgentranscodeid | `String` | Advgentranscodeid |
| approvalCode | `String` | Approval Code |
| approvalDate | `Date` | Approval Date |
| approvalStatus | `String` | Approval Status |
| arLedgerCredit | `Float` | AR Led Credit |
| arLedgerDebit | `Float` | AR Led Debit |
| arNumber | `Float` | AR Number |
| arState | `String` | AR State |
| arTransferDate | `Date` | AR Transfer Date |
| archargetransferflag | `String` | Archargetransferflag |
| arrangementCode | `String` | Arrangement Code |
| arrangementDescription | `String` | Arrangement Description for the Transaction Code. |
| arrangementId | `Float` | Arrangement ID |
| articleId | `Float` | Article ID |
| associatedBillDate | `Date` | Date on which the Original Bill was generated. This is used in case of Credit Bill. |
| associatedBillNo | `String` | Associated Bill Number |
| associatedFiscalBillDate | `Date` | Associated Fiscal Bill number generation date. |
| associatedFiscalBillNo | `String` | Associated Fiscal Bill number. |
| associatedFiscalBillTime | `String` | Associated Fiscal Bill number generation time. |
| associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| associatedSeqNumber | `Float` | Self referencing sequence number to gather information for other operations. |
| associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| authemployeeid | `Float` | Authemployeeid |
| authorizerId | `Float` | Authorizer ID |
| autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| autoSettleYn | `String` | Auto Settle Y/N |
| billGenerationDate | `Date` | Bill Generation Date |
| billGenerationTime | `String` | Bill Generation Time |
| billNo | `Float` | Bill Number |
| billPaymentTrxNumber | `Float` | Bill Payment Transaction No |
| billPrefix | `String` | Bill Prefix |
| billSeqNumber | `Float` | Bill Sequence No |
| billStartDate | `Date` | Date of the first charge in the bill. |
| bonusCheckId | `Float` | Bonus Check ID |
| bucketCode | `String` | Bucket code related to this redemption. |
| bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| businessDate | `Date` | Business Date |
| businessId | `String` | Business ID |
| cARLedgerCredit | `Float` | Central Ar Led Credit |
| cARLedgerDebit | `Float` | Central Ar Led Debit |
| cCashierCredit | `Float` | Central Cashier Credit |
| cCashierDebit | `Float` | Central Cashier Debit |
| cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| cCashpay | `Float` | Central Cashpay |
| cCcTransactionFeeAmount | `Float` | Central Cc Trx Fee Amount |
| cCcpay | `Float` | Central Ccpay |
| cChangeDue | `Float` | Central Change Due |
| cClarpay | `Float` | Central Clarpay |
| cClpay | `Float` | Central Clpay |
| cCollectionTax1 | `Float` | Central Coll Tax1 |
| cCollectionTax2 | `Float` | Central Coll Tax2 |
| cCollectionTax3 | `Float` | Central Coll Tax3 |
| cCollectionTax4 | `Float` | Central Coll Tax4 |
| cCollectionTax5 | `Float` | Central Coll Tax5 |
| cContractGrossAmount | `Float` | Central Contract Gross Amount |
| cContractGuestCredit | `Float` | Central Contract Guest Credit |
| cContractGuestDebit | `Float` | Central Contract Guest Debit |
| cContractNetAmount | `Float` | Central Contract Net Amount |
| cDailyRunningTotal | `Float` | Central Daily Running Total |
| cDepLedgerCredit | `Float` | Central Dep Led Credit |
| cDepLedgerDebit | `Float` | Central Dep Led Debit |
| cDeposit | `Float` | Central Deposit |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFiscalInvoiceCurrencyRate | `Float` | Central Fiscal Invoice Currency Rate |
| cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| cGuestAccountCredit | `Float` | Central Guest Account Credit |
| cGuestAccountDebit | `Float` | Central Guest Account Debit |
| cInHouseCredit | `Float` | Central Inh Credit |
| cInHouseDebit | `Float` | Central Inh Debit |
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
| cNonRevenueAmount | `Float` | Central Non Revenue Amount |
| cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| cPackageAllowance | `Float` | Central Package Allowance |
| cPackageCredit | `Float` | Central Package Credit |
| cPackageDebit | `Float` | Central Package Debit |
| cPaidout | `Float` | Central Paidout |
| cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| cParallelNetAmount | `Float` | Central Parallel Net Amount |
| cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
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
| cPostedAmount | `Float` | Central Posted Amount |
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
| cRevenueAmount | `Float` | Central Revenue Amt |
| cTax1Amount | `Float` | Central Tax1 Amt |
| cTax1Rate | `Float` | Central Tax1 Rate |
| cTax2Amount | `Float` | Central Tax2 Amt |
| cTax2Rate | `Float` | Central Tax2 Rate |
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
| cTaxRate | `Float` | Central Tax Rate |
| cTax10Amount | `Float` | Central Tax10 Amt |
| cTax10Rate | `Float` | Central Tax10 Rate |
| cTax11Amount | `Float` | Central Tax11 Amt |
| cTax11Rate | `Float` | Central Tax11 Rate |
| cTax12Amount | `Float` | Central Tax12 Amt |
| cTax12Rate | `Float` | Central Tax12 Rate |
| cTax13Amount | `Float` | Central Tax13 Amt |
| cTax13Rate | `Float` | Central Tax13 Rate |
| cTax14Amount | `Float` | Central Tax14 Amt |
| cTax14Rate | `Float` | Central Tax14 Rate |
| cTax15Amount | `Float` | Central Tax15 Amt |
| cTax15Rate | `Float` | Central Tax15 Rate |
| cTax16Amount | `Float` | Central Tax16 Amt |
| cTax16Rate | `Float` | Central Tax16 Rate |
| cTax17Amount | `Float` | Central Tax17 Amt |
| cTax17Rate | `Float` | Central Tax17 Rate |
| cTax18Amount | `Float` | Central Tax18 Amt |
| cTax18Rate | `Float` | Central Tax18 Rate |
| cTax19Amount | `Float` | Central Tax19 Amt |
| cTax19Rate | `Float` | Central Tax19 Rate |
| cTax20Amount | `Float` | Central Tax20 Amt |
| cTax20Rate | `Float` | Central Tax20 Rate |
| cTax3Amount | `Float` | Central Tax3 Amt |
| cTax3Rate | `Float` | Central Tax3 Rate |
| cTax4Amount | `Float` | Central Tax4 Amt |
| cTax4Rate | `Float` | Central Tax4 Rate |
| cTax5Amount | `Float` | Central Tax5 Amt |
| cTax5Rate | `Float` | Central Tax5 Rate |
| cTax6Amount | `Float` | Central Tax6 Amt |
| cTax6Rate | `Float` | Central Tax6 Rate |
| cTax7Amount | `Float` | Central Tax7 Amt |
| cTax7Rate | `Float` | Central Tax7 Rate |
| cTax8Amount | `Float` | Central Tax8 Amt |
| cTax8Rate | `Float` | Central Tax8 Rate |
| cTax9Amount | `Float` | Central Tax9 Amt |
| cTax9Rate | `Float` | Central Tax9 Rate |
| cTotalGross | `Float` | Central Total Gross |
| cTotalNet | `Float` | Central Total Net |
| cTotalNonTaxable | `Float` | Central Total Nontaxable |
| cTotalNonrevNonTaxable | `Float` | Central Tot Nonrev Nontaxable |
| cTotalNonrevTaxable | `Float` | Central Tot Nonrev Taxable |
| cTotalRevenueNonTaxable | `Float` | Central Tot Rev Nontaxable |
| cTotalRevenueTaxable | `Float` | Central Tot Rev Taxable |
| cTotalTax | `Float` | Central Total Tax |
| cTransactionAmount | `Float` | Central Trx Amount |
| cTrialBalanceAmountGross | `Float` | Central Trial Balance Amount Gross |
| cTrialBalanceAmountNet | `Float` | Central Trial Balance Amount Net |
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
| calcmemberpointsflag | `String` | Calcmemberpointsflag |
| cashRegisterId | `String` | Cash Register ID |
| cashRegisterInvNumber | `Float` | Internal sequence number for the Cash Register ID. |
| cashierCredit | `Float` | Cashier Credit |
| cashierDebit | `Float` | Cashier Debit |
| cashierId | `Float` | Cashier ID |
| cashierOpeningBalance | `Float` | Cashier Opening Balance |
| cashpay | `Float` | Total paid in cash |
| ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| ccTrxFeeAmount | `Float` | Fee (surcharge) amount for a credit card transaction. |
| ccpay | `Float` | Total paid in the form of credit cards. |
| centralGrossAmount | `Float` | Central Gross Amount |
| centralNetAmount | `Float` | Central Net Amount |
| centralPaymentAmount | `Float` | Central Payment Amount |
| centralPrice | `Float` | Central Price |
| centralTaxAmount | `Float` | Central Tax Amount |
| centralTaxCode | `String` | Central Tax Code |
| centralTaxCodeDescription | `String` | Central Tax Code Description |
| centralTransactionAmount | `Float` | Central Transaction Amount |
| centralTransactionCode | `String` | Central Transaction Code |
| centralTransactionDescription | `String` | Central Transaction Description |
| centralTransactionGroupCode | `String` | Central Transaction Group Code |
| centralTransactionGroupDescription | `String` | Central Transaction Group Description |
| centralTransactionSubGroupCode | `String` | Central Transaction Sub-Group Code |
| centralTransactionSubGroupDescription | `String` | Central Transaction Sub-Group Description |
| changeDue | `Float` | Change Due |
| checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| checkNumber | `String` | Check Number |
| city | `String` | City |
| cityLedgerYn | `String` | City Ledger Y/N |
| clTrxNumber | `Float` | Internal number given to the direct bill payment in financial_transactions. |
| clarpay | `Float` | This is to store amount posted from AR for a bill. In this case CLPAY will not have value if the bill is generated in AR |
| closureNo | `Float` | Closure Number |
| clpay | `Float` | The amount that has been paid using direct bill. |
| collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| collectionTax1 | `Float` | Collection Tax 1 |
| collectionTax2 | `Float` | Collection Tax 2 |
| collectionTax3 | `Float` | Collection Tax3 |
| collectionTax4 | `Float` | Collection Tax4 |
| collectionTax5 | `Float` | Collection Tax5 |
| comments | `String` | Comments |
| compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| compTypeCode | `String` | Comp Type Code |
| companyFinancialValue | `String` | The financial value of the company. |
| companyName | `String` | Company Name |
| companyType | `String` | The type of legal entity / company e.g. Individual Micro enterprise etc. |
| complinktranscodeid | `String` | Complinktranscodeid |
| compressBillNo | `String` | To store the Compressed Bill No. and Converted Bill number information |
| compressedYn | `String` | Compressed Y/N |
| contractCurrency | `String` | Currency code for contract currency. |
| contractGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| contractGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| contractGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| contractNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| contractforeigncurrencyid | `String` | Contract Foreign Currency ID |
| correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| country | `String` | Country |
| countryCode | `String` | Country Code |
| couponNo | `String` | Coupon Number |
| covers | `String` | Covers |
| creditBillGeneratedYn | `String` | Indicates if a credit bill has been generated for this folio. |
| creditBillNo | `Float` | Credit Bill Number |
| creditCardId | `Float` | Credit Card ID |
| currency | `String` | Currency |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyRunningTotal | `Float` | Daily running total. |
| debitOrCredit | `String` | Debit or Credit |
| deferredYn | `String` | Deferred Y/N |
| deletedFlag | `String` | Deleted Flag |
| depLedgerCredit | `Float` | Dep Ledger Credit |
| depLedgerDebit | `Float` | Dep Ledger Debit |
| depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| deposit | `Float` | Total deposits. |
| depositReqReceiptNo | `Float` | Deposit Req Receipt Number |
| depositTransactionId | `String` | Deposit Transaction ID |
| depositlinkfintransid | `Float` | Depositlinkfintransid |
| displayflag | `String` | Displayflag |
| documentCode | `String` | Unique Document Code |
| documentType | `String` | Document Type |
| eArchiveEttnNumber | `String` | Unique ETTN number for an E Archive invoice. |
| eArchiveNumber | `String` | E Archive number. |
| eArchiveReportNo | `String` | E Archive report number provided by external system e.g. PROTEL. |
| eArchiveStatus | `String` | E Archive status. |
| eInvoiceNumber | `String` | E Invoice Number |
| eInvoiceStatus | `String` | E-Invoice number received from Portal+. This number be updated via Web Service call from Portal+. |
| effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| euroExchangeRate | `Float` | Euro Exchange Rate |
| exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| exchangeDate | `Date` | Exchange Date |
| exchangeRate | `Float` | Exchange Rate |
| exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| exchangedifferenceflag | `String` | Exchangedifferenceflag |
| expInvoiceType | `String` | Export Invoice Type |
| expOriginalInvoice | `String` | Export Original Invoice |
| extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| extTransactionId | `String` | Transaction ID from external system. |
| fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| filterChar1 | `String` | Filter Char1 |
| filterChar2 | `String` | Filter Char2 |
| filterChar3 | `String` | Filter Char3 |
| filterChar4 | `String` | Filter Char4 |
| filterChar5 | `String` | Filter Char5 |
| finBillNumber | `Float` | Financial Bill No |
| finBusinessDate | `Date` | Financial Business Date |
| finCountry | `String` | Financial Country |
| finDeletedFlag | `String` | Financial Deleted Flag |
| finFiscalBillNumber | `String` | Financial Fiscal Bill No |
| finFolioView | `Float` | Financial Folio View |
| finInsertDate | `Date` | Financial Insert Date |
| finInsertUser | `Float` | Financial Insert User |
| finInvoiceNumber | `Float` | Financial Invoice No |
| finNameTaxType | `String` | Financial Name Tax Type |
| finPkid | `Float` | Financial Pkid |
| finPostitNumber | `Float` | Financial Postit No |
| finPropertyBillPrefix | `String` | Financial Property Bill Prefix |
| finQueueName | `String` | Financial Queue Name |
| finRevisionNumber | `Float` | Financial Revision No |
| finRoom | `String` | Financial Room |
| finUpdateDate | `Date` | Financial Update Date |
| finUpdateUser | `Float` | Financial Update User |
| financialCExchangeDate | `Date` | Fin Central Xchange Date |
| financialCExchangeRate | `Float` | Fin Central Xchange Rate |
| financialCashierId | `Float` | Fin Cashier ID |
| financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| financialForexTaxYN | `String` | Fin Forex Tax Y/N |
| financialNameId | `Float` | Fin Name ID |
| financialPostitYN | `String` | Fin Postit Y/N |
| financialReservationNameId | `Float` | Fin Resv Name ID |
| fintransactionid | `Float` | Fintransactionid |
| fintransid | `Float` | Fintransid |
| first | `String` | First |
| fiscalBillCheckDigit | `Float` | Fiscal Bill Check Digit |
| fiscalBillGenerationDate | `Date` | Fiscal Bill Generation Date |
| fiscalBillGenerationTime | `String` | Fiscal Bill Generation Time |
| fiscalBillNo | `String` | Fiscal Bill Number |
| fiscalInvoiceCurrency | `String` | Currency Code used by and sent to the Fiscal Service. |
| fiscalInvoiceCurrencyRate | `Float` | Exchange Rate of the Fiscal Invoice currency for settlement on the bill generation date. |
| fiscalSessionNo | `String` | Session number generated by the fiscal printer. This numbers gets reset during EOD. |
| fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| fiscalUnitControlCode | `String` | Fiscal Unit Control Code |
| fixedchargesflag | `String` | Fixedchargesflag |
| folioAddress | `String` | Folio Full Address. |
| folioAddressCorrectedYn | `String` | Indicates if the folio header was corrected. |
| folioAttachmentLinkId | `Float` | Folio Attachment Link ID |
| folioAttachmentStatus | `Float` | Folio Attachment Status |
| folioNo | `Float` | Folio Number |
| folioStyle | `String` | Folio Style |
| folioTaxSeqNumber | `Float` | Folio Tax Sequence No |
| folioType | `String` | Folio Type |
| folioType1 | `String` | Folio Type 1 |
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
| fullFolioNo | `String` | Full Folio Number |
| genCashierId | `Float` | General Cashier Id. |
| gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| grossAmount | `Float` | Gross Amount |
| groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| guestAccountCredit | `Float` | Guest Account Credit |
| guestAccountDebit | `Float` | Debit amount on the guest account |
| hasWatermarkYn | `String` | If PERMANENT FOLIO STORAGE is active this flag indicates whether the PDF file has the "Copy" watermark. |
| hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| hotelName | `String` | Hotel name of the property at the time of bill generation. |
| incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| inclusiveTaxYN | `String` | Inclusive Tax YN |
| individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| inhCredit | `Float` | In House Credit |
| inhDebit | `Float` | In House Debit |
| insTimestamp | `DateTime` | Timestamp to capture the exact order of inserts. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| insertUserName | `String` | The name of the user who created the record. |
| installments | `Float` | Installments |
| internalArticleid | `Float` | Articleid |
| internalBusinessdate | `Date` | Businessdate |
| internalCashierid | `Float` | Cashierid |
| invoiceCloseDate | `Date` | Invoice Close Date |
| invoiceNo | `Float` | Invoice Number |
| invoiceType | `String` | Invoice Type |
| iscreditflag | `String` | Iscreditflag |
| isdebitflag | `String` | Isdebitflag |
| isinternalflag | `String` | Isinternalflag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| last | `String` | Last |
| lastSignatureHash | `String` | Last Signature Hash |
| linkTrxNumber | `Float` | Link Transaction No |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketid | `String` | Marketid |
| membershipid | `Float` | Membershipid |
| mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| nafApeHotelCode | `String` | NAF/APE code of the hotel at the time of bill generation. |
| nameId | `Float` | Name ID |
| nameTaxType | `String` | Name Tax Type |
| nameTypeDescription | `String` | Name Type Description |
| netAmount | `Float` | Net Amount |
| net1Amt | `Float` | Net1 Amount |
| net10Amt | `Float` | Net10 Amount |
| net11Amt | `Float` | Net11 Amount |
| net12Amt | `Float` | Net12 Amount |
| net13Amt | `Float` | Net13 Amount |
| net14Amt | `Float` | Net14 Amount |
| net15Amt | `Float` | Net15 Amount |
| net16Amt | `Float` | Net16 Amount |
| net17Amt | `Float` | Net17 Amount |
| net18Amt | `Float` | Net18 Amount |
| net19Amt | `Float` | Net19 Amount |
| net2Amt | `Float` | Net2 Amount |
| net20Amt | `Float` | Net20 Amount |
| net3Amt | `Float` | Net3 Amount |
| net4Amt | `Float` | Net4 Amount |
| net5Amt | `Float` | Net5 Amount |
| net6Amt | `Float` | Net6 Amount |
| net7Amt | `Float` | Net7 Amount |
| net8Amt | `Float` | Net8 Amount |
| net9Amt | `Float` | Net9 Amount |
| nonRevenueAmount | `Float` | Non Revenue Amount |
| nrBusinessId | `String` | Nr Business ID |
| numberDialed | `String` | Number Dialed. |
| numberOfPages | `Float` | Number of pages for a given bill. |
| oTransactionDesc | `String` | Transaction Description. |
| onholdflag | `String` | Onholdflag |
| operaFiscalFolioStatus | `String` | This coulumn is used to store the status of Fiscal Folio /Payload Generation. The values will be SUCCESS - Payload has been sent successfully OFFLINE - User confirmed to generate Offline Folio i.e. Folio will be generated but Fiscal Folio/Payload not generated FAILURE - User do not want to create OFFLINE FOLIO but as FISCAL service is not available so the status is FAILURE i.e. in this case VOID Folio generated with FAILURE Fiscal Folio Status BLANK/NULL - Fiscal Printing is turned off or Past data after the upgrade. |
| orgBillNumber | `Float` | Stores original bill number after void. |
| orgFolioType | `String` | Stores original folio type after void. |
| orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalReservationNameID | `Float` | Original Reservation Name ID |
| originalRoom | `String` | Original Room |
| originalresvid | `Float` | Originalresvid |
| packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| packageCredit | `Float` | Credit amount on the guest package account. |
| packageDebit | `Float` | Debit amount on the guest package account |
| packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| packagelinkfintransid | `Float` | Packagelinkfintransid |
| pageNumber | `Float` | Stores the page number within the bill generation. |
| paidout | `Float` | Total paid outs. |
| palmVideoFlag | `String` | Indicator to identify if the bill was generated from Video checkout or PALM.  (V->Video  P->PALM). |
| parallelCurrency | `String` | Cuurency code for parrallel currency. |
| parallelGrossAmount | `Float` | Parallel Gross Amount |
| parallelGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| parallelGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| parallelNetAmount | `Float` | Parallel Net Amount |
| parallelforeigncurrencyid | `String` | Parallel Foreign Currency ID |
| parentfintransid | `Float` | Parentfintransid |
| partnerFiscalFolioStatus | `String` | Partner Fiscal Folio Status |
| passerByName | `String` | Passerby Name. |
| payeeName | `String` | Payee Name used for signature generation. |
| payeeNameId | `Float` | Payee Name ID |
| payeeZipCode | `String` | Payee Zip Code used for signature generation. |
| paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| paymentDate | `Date` | Payment Date |
| paymentDescription | `String` | Payment Description |
| paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| paymentTrxDate | `Date` | Payment Transaction Date |
| paymentType | `String` | Payment Type |
| percentage | `Float` | Percentage |
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
| postedAmount | `Float` | Posted Amount |
| postingDate | `Date` | Posting Date |
| postingRhythm | `String` | Posting Rhythm |
| postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| postitNo | `Float` | Postit Number |
| postitYn | `String` | Postit Y/N |
| price | `Float` | Price |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| processed8300flag | `String` | Processed8300flag |
| product | `String` | Product |
| productid | `String` | Productid |
| profileid | `Float` | Profileid |
| profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| proformaYn | `String` | Proforma Y/N |
| promotionalText1 | `String` | Text returned by the credit card company |
| promotionalText2 | `String` | Text returned by the credit card company |
| property | `String` | Code to uniquely identify the Property |
| propertyBillPrefix | `String` | Property Bill Prefix |
| propertyTaxNo | `String` | Property Tax Number |
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
| quantity | `Float` | Quantity |
| queueName | `String` | Queue Name |
| rateCode | `String` | Rate Code |
| ratecodeid | `String` | Ratecodeid |
| realPerpetualAmount | `Float` | Real perpetual amount at the time of generating the bill. |
| reasonCode | `String` | Reason Code |
| receiptNo | `Float` | Recpt Number |
| receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| reference | `String` | Reference |
| reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| reservationNameId | `Float` | Resv Name ID |
| reservationid | `Float` | Reservationid |
| resortCity | `String` | City of the hotel at the time of bill generation. |
| resortCountry | `String` | Country of the hotel at the time of bill generation. |
| resortFullAddress | `String` | Property Full Address |
| resortZipcodeCode | `String` | Zipcode of the hotel at the time of bill generation. |
| resvenddate | `Date` | Resvenddate |
| revenueAmt | `Float` | Revenue Amount. |
| reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| revisionNo | `Float` | Revision Number |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
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
| seqNumber | `Float` | Sequence No |
| serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| serviceTypeCode | `String` | Service Type Code |
| settlementFlag | `String` | Settlement Flag |
| signatureHash | `String` | Signature Hash |
| signatureKeyVersion | `String` | Signature Key Version |
| softwareVersion | `String` | OPERA software version at the time of bill generation. |
| sourceCode | `String` | Source Code |
| sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| sourceid | `String` | Sourceid |
| splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| status | `String` | Status |
| supplement | `String` | Supplement |
| taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| tacommissionableflag | `String` | Tacommissionableflag |
| targetResort | `String` | Target Property |
| targetlocationid | `String` | Targetlocationid |
| tax1Amt | `Float` | Tax1 Amount |
| tax1No | `String` | Tax1 Number |
| tax1Rate | `Float` | Tax Rate 1 amount of the bill for which Tax Code 1 is attached as one of the taxes. |
| tax1RateType | `String` | Tax Rate Type 1 of the bill for which Tax Code 1 is attached as one of the taxes. |
| tax2Amt | `Float` | Tax2 Amount |
| tax2No | `String` | Tax2 Number |
| tax2Rate | `Float` | Tax Rate 2 amount of the bill for which Tax Code 2 is attached as one of the taxes. |
| tax2RateType | `String` | Tax Rate Type 2 of the bill for which Tax Code 2 is attached as one of the taxes. |
| taxAmount | `Float` | Tax Amount for Commission. |
| taxCode | `String` | Internal |
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
| taxCodeDescription | `String` | Tax Code Description |
| taxCodeNumber | `Float` | Tax Code Number |
| taxElements | `String` | Tax Elements |
| taxId | `String` | Tax ID |
| taxInvNumber | `String` | Tax Invoice No |
| taxRate | `Float` | Tax Rate |
| taxRateType | `String` | Tax Rate Type |
| tax10Amt | `Float` | Tax10 Amount |
| tax10Rate | `Float` | Tax Rate 10 amount of the bill for which Tax Code 10  is attached as one of the taxes. |
| tax10RateType | `String` | Tax Rate Type 10 of the bill for which Tax Code 10 is attached as one of the taxes. |
| tax11Amt | `Float` | Tax11 Amount |
| tax11Rate | `Float` | Tax Rate 11 amount of the bill for which Tax Code 11  is attached as one of the taxes. |
| tax11RateType | `String` | Tax Rate Type 11 of the bill for which Tax Code 11 is attached as one of the taxes. |
| tax12Amt | `Float` | Tax12 Amount |
| tax12Rate | `Float` | Tax Rate 12 amount of the bill for which Tax Code 12 is attached as one of the taxes. |
| tax12RateType | `String` | Tax Rate Type 12 of the bill for which Tax Code 12 is attached as one of the taxes. |
| tax13Amt | `Float` | Tax13 Amount |
| tax13Rate | `Float` | Tax Rate 13 amount of the bill for which Tax Code 13 is attached as one of the taxes. |
| tax13RateType | `String` | Tax Rate Type 13 of the bill for which Tax Code 13 is attached as one of the taxes. |
| tax14Amt | `Float` | Tax14 Amount |
| tax14Rate | `Float` | Tax Rate 14 amount of the bill for which Tax Code 14 is attached as one of the taxes. |
| tax14RateType | `String` | Tax Rate Type 14 of the bill for which Tax Code 14 is attached as one of the taxes. |
| tax15Amt | `Float` | Tax15 Amount |
| tax15Rate | `Float` | Tax Rate 15 amount of the bill for which Tax Code 15 is attached as one of the taxes. |
| tax15RateType | `String` | Tax Rate Type 15 of the bill for which Tax Code 15 is attached as one of the taxes. |
| tax16Amt | `Float` | Tax16 Amount |
| tax16Rate | `Float` | Tax Rate 16 amount of the bill for which Tax Code 16 is attached as one of the taxes. |
| tax16RateType | `String` | Tax Rate Type 16 of the bill for which Tax Code 16 is attached as one of the taxes. |
| tax17Amt | `Float` | Tax17 Amount |
| tax17Rate | `Float` | Tax Rate 17 amount of the bill for which Tax Code 17 is attached as one of the taxes. |
| tax17RateType | `String` | Tax Rate Type 17 of the bill for which Tax Code 17 is attached as one of the taxes. |
| tax18Amt | `Float` | Tax18 Amount |
| tax18Rate | `Float` | Tax Rate 18 amount of the bill for which Tax Code 18 is attached as one of the taxes. |
| tax18RateType | `String` | Tax Rate Type 18 of the bill for which Tax Code 18 is attached as one of the taxes. |
| tax19Amt | `Float` | Tax19 Amount |
| tax19Rate | `Float` | Tax Rate 19 amount of the bill for which Tax Code 19 is attached as one of the taxes. |
| tax19RateType | `String` | Tax Rate Type 19 of the bill for which Tax Code 19 is attached as one of the taxes. |
| tax20Amt | `Float` | Tax20 Amount |
| tax20Rate | `Float` | Tax Rate 20 amount of the bill for which Tax Code 20 is attached as one of the taxes. |
| tax20RateType | `String` | Tax Rate Type 20 of the bill for which Tax Code 20 is attached as one of the taxes. |
| tax3Amt | `Float` | Tax3 Amount |
| tax3Rate | `Float` | Tax Rate 3 amount of the bill for which Tax Code 3 is attached as one of the taxes. |
| tax3RateType | `String` | Tax Rate Type 3 of the bill for which Tax Code 3 is attached as one of the taxes. |
| tax4Amt | `Float` | Tax4 Amount |
| tax4Rate | `Float` | Tax Rate 4 amount of the bill for which Tax Code 4 is attached as one of the taxes. |
| tax4RateType | `String` | Tax Rate Type 4 of the bill for which Tax Code 4 is attached as one of the taxes. |
| tax5Amt | `Float` | Tax5 Amount |
| tax5Rate | `Float` | Tax Rate 5 amount of the bill for which Tax Code 5 is attached as one of the taxes. |
| tax5RateType | `String` | Tax Rate Type 5 of the bill for which Tax Code 5 is attached as one of the taxes. |
| tax6Amt | `Float` | Tax6 Amount |
| tax6Rate | `Float` | Tax Rate 6 amount of the bill for which Tax Code 6 is attached as one of the taxes. |
| tax6RateType | `String` | Tax Rate Type 6 of the bill for which Tax Code 6 is attached as one of the taxes. |
| tax7Amt | `Float` | Tax7 Amount |
| tax7Rate | `Float` | Tax Rate 7 amount of the bill for which Tax Code 7 is attached as one of the taxes. |
| tax7RateType | `String` | Tax Rate Type 7 of the bill for which Tax Code 7 is attached as one of the taxes. |
| tax8Amt | `Float` | Tax8 Amount |
| tax8Rate | `Float` | Tax Rate 8 amount of the bill for which Tax Code 8 is attached as one of the taxes. |
| tax8RateType | `String` | Tax Rate Type 8 of the bill for which Tax Code 8 is attached as one of the taxes. |
| tax9Amt | `Float` | Tax9 Amount |
| tax9Rate | `Float` | Tax Rate 9 amount of the bill for which Tax Code 9 is attached as one of the taxes. |
| tax9RateType | `String` | Tax Rate Type 9 of the bill for which Tax Code 9 is attached as one of the taxes. |
| taxdeferredflag | `String` | Taxdeferredflag |
| taxgeneratedflag | `String` | Taxgeneratedflag |
| tclCode1 | `String` | Class1 Code. |
| tclCode2 | `String` | Class1 Code. |
| terminal | `String` | Terminal |
| thresholdDiversionId | `Float` | Threshold Diversion ID |
| thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| thresholdEntityType | `String` | Threshold Entity Type |
| thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| toReservationNameId | `Float` | To Resv Name ID |
| totalGross | `Float` | Total Gross |
| totalNet | `Float` | Total Net |
| totalNonTaxable | `Float` | Total non taxable amount. |
| totalNonrevNonTaxable | `Float` | Total non revenue amount that is non taxable. |
| totalNonrevTaxable | `Float` | Total non revenue amount that is not taxable. |
| totalRevNonTaxable | `Float` | Total revenue amount that is non taxable. |
| totalRevTaxable | `Float` | Total revenue amount that is taxable. |
| totalTax | `Float` | Total Tax |
| tranActionId | `Float` | Tran Action ID |
| transactLastSignatureHash | `String` | Last Signature for Transaction Totals. |
| transactSignatureHash | `String` | Signature hash for Transaction Totals. |
| transactSignatureKeyVersion | `String` | Signature key version for Transaction Totals. |
| transactionAmount | `Float` | Transaction Amount |
| transactionCode | `String` | Transaction Code |
| transactionDate | `Date` | Transaction Date |
| transactionDescription | `String` | Transaction Description |
| transactionFromAcct | `Float` | Trns From Account |
| transactionGroupCode | `String` | Transaction Group Code |
| transactionGroupDescription | `String` | Transaction Group Description |
| transactionID | `Float` | Transaction ID |
| transactionSignature | `String` | Transaction Signature Value. |
| transactionSubGroupCode | `String` | Transaction Sub-Group Code |
| transactionSubGroupDescription | `String` | Transaction Sub-Group Description |
| transactionToAcct | `Float` | Trns To Account |
| transactionType | `String` | Transaction Type |
| transcodearrangementid | `Float` | Transcodearrangementid |
| transcodeid | `String` | Transcodeid |
| transferfromaccountid | `Float` | Transferfromaccountid |
| transferfromresvid | `Float` | Transferfromresvid |
| transfertoaccountid | `Float` | Transfertoaccountid |
| transfertoresvid | `Float` | Transfertoresvid |
| trialBalanceAmountGross | `Float` | Trial Balance Amount Gross |
| trialBalanceAmountNet | `Float` | Trial Balance Amount Net |
| trnsActivityDate | `Date` | Transaction Activity Date |
| trxAmount | `Float` | Transaction Amount |
| trxNumberAddedBy | `Float` | Transaction No Added By |
| trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| trxNumberHeader | `Float` | Transaction No Header |
| trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| trxServiceType | `String` | Transaction Service Type |
| trxTime | `String` | Transaction Time |
| trxType | `String` | Transaction type: possible values: [CACH]. |
| udfc01 | `String` | Udfc01 |
| udfc02 | `String` | Udfc02 |
| udfc03 | `String` | Udfc03 |
| udfc04 | `String` | Udfc04 |
| udfc05 | `String` | Udfc05 |
| udfc06 | `String` | Udfc06 |
| udfc07 | `String` | Udfc07 |
| udfc08 | `String` | Udfc08 |
| udfc09 | `String` | Udfc09 |
| udfc10 | `String` | Udfc10 |
| udfc11 | `String` | Udfc11 |
| udfc12 | `String` | Udfc12 |
| udfc13 | `String` | Udfc13 |
| udfc14 | `String` | Udfc14 |
| udfc15 | `String` | Udfc15 |
| udfc16 | `String` | Udfc16 |
| udfc17 | `String` | Udfc17 |
| udfc18 | `String` | Udfc18 |
| udfc19 | `String` | Udfc19 |
| udfc20 | `String` | Udfc20 |
| udfc21 | `String` | Udfc21 |
| udfc22 | `String` | Udfc22 |
| udfc23 | `String` | Udfc23 |
| udfc24 | `String` | Udfc24 |
| udfc25 | `String` | Udfc25 |
| udfc26 | `String` | Udfc26 |
| udfc27 | `String` | Udfc27 |
| udfc28 | `String` | Udfc28 |
| udfc29 | `String` | Udfc29 |
| udfc30 | `String` | Udfc30 |
| udfc31 | `String` | Udfc31 |
| udfc32 | `String` | Udfc32 |
| udfc33 | `String` | Udfc33 |
| udfc34 | `String` | Udfc34 |
| udfc35 | `String` | Udfc35 |
| udfc36 | `String` | Udfc36 |
| udfc37 | `String` | Udfc37 |
| udfc38 | `String` | Udfc38 |
| udfc39 | `String` | Udfc39 |
| udfc40 | `String` | Udfc40 |
| udfd01 | `Date` | Udfd01 |
| udfd02 | `Date` | Udfd02 |
| udfd03 | `Date` | Udfd03 |
| udfd04 | `Date` | Udfd04 |
| udfd05 | `Date` | Udfd05 |
| udfd06 | `Date` | Udfd06 |
| udfd07 | `Date` | Udfd07 |
| udfd08 | `Date` | Udfd08 |
| udfd09 | `Date` | Udfd09 |
| udfd10 | `Date` | Udfd10 |
| udfd11 | `Date` | Udfd11 |
| udfd12 | `Date` | Udfd12 |
| udfd13 | `Date` | Udfd13 |
| udfd14 | `Date` | Udfd14 |
| udfd15 | `Date` | Udfd15 |
| udfd16 | `Date` | Udfd16 |
| udfd17 | `Date` | Udfd17 |
| udfd18 | `Date` | Udfd18 |
| udfd19 | `Date` | Udfd19 |
| udfd20 | `Date` | Udfd20 |
| udfn01 | `Float` | Udfn01 |
| udfn02 | `Float` | Udfn02 |
| udfn03 | `Float` | Udfn03 |
| udfn04 | `Float` | Udfn04 |
| udfn05 | `Float` | Udfn05 |
| udfn06 | `Float` | Udfn06 |
| udfn07 | `Float` | Udfn07 |
| udfn08 | `Float` | Udfn08 |
| udfn09 | `Float` | Udfn09 |
| udfn10 | `Float` | Udfn10 |
| udfn11 | `Float` | Udfn11 |
| udfn12 | `Float` | Udfn12 |
| udfn13 | `Float` | Udfn13 |
| udfn14 | `Float` | Udfn14 |
| udfn15 | `Float` | Udfn15 |
| udfn16 | `Float` | Udfn16 |
| udfn17 | `Float` | Udfn17 |
| udfn18 | `Float` | Udfn18 |
| udfn19 | `Float` | Udfn19 |
| udfn20 | `Float` | Udfn20 |
| udfn21 | `Float` | Udfn21 |
| udfn22 | `Float` | Udfn22 |
| udfn23 | `Float` | Udfn23 |
| udfn24 | `Float` | Udfn24 |
| udfn25 | `Float` | Udfn25 |
| udfn26 | `Float` | Udfn26 |
| udfn27 | `Float` | Udfn27 |
| udfn28 | `Float` | Udfn28 |
| udfn29 | `Float` | Udfn29 |
| udfn30 | `Float` | Udfn30 |
| udfn31 | `Float` | Udfn31 |
| udfn32 | `Float` | Udfn32 |
| udfn33 | `Float` | Udfn33 |
| udfn34 | `Float` | Udfn34 |
| udfn35 | `Float` | Udfn35 |
| udfn36 | `Float` | Udfn36 |
| udfn37 | `Float` | Udfn37 |
| udfn38 | `Float` | Udfn38 |
| udfn39 | `Float` | Udfn39 |
| udfn40 | `Float` | Udfn40 |
| updTimestamp | `DateTime` | Timestamp to capture the exact order of updates. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| vatOffsetYn | `String` | Vat Offset Y/N |
| voidNo | `Float` | Void Number |
| voidReason | `String` | This column will store the reason for voiding the folio. |
| workingDocId | `Float` | Working Doc ID |
| wrapperTransactionID | `Float` | Wrapper Transaction ID |
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
| zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### EFolioPropertyExportValuesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRAccountNumberMandYN | `String` | Specifies if the AR acct No is mandatory(Y/N) |
| aRBalanceTrxCode | `String` | Internal |
| aRCreditTrxCode | `String` | Internal |
| additionalLogos | `String` | Additional Logos |
| address | `String` | Address |
| agingLevel1 | `Float` | Aging bucket 1 |
| agingLevel2 | `Float` | Aging bucket 2 |
| agingLevel3 | `Float` | Aging bucket 3 |
| agingLevel4 | `Float` | Aging bucket 4 |
| agingLevel5 | `Float` | Aging bucket 5 |
| airport | `String` | The Airport Code for the airport near the property |
| airportDistance | `String` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| airportTime | `String` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| allowLoginYn | `String` | Allow loggin in to this resort(Y/N) |
| allowancePeriodAdj | `String` | Period for the allowance |
| arAccountNumberFormat | `String` | Number format of AR account no. |
| arAgent | `String` | Default Account Type for an Agent for the Property |
| arCompany | `String` | Default Account Type for a Company for the Property |
| arGroups | `String` | Default Account Type for a Group for the Property |
| arIndividuals | `String` | Default Account Type for Individual for the Property |
| arSettleCode | `String` | Internal |
| arTypewriter | `String` | Internal |
| awardsTimeout | `Float` | Internal |
| bIC | `String` | BIC |
| bankAgencyCode | `String` | Bank Agency Code |
| bankAgencyName | `String` | Bank Agency Name |
| bankCode | `String` | Code for the bank account |
| bankName | `String` | Bank name |
| baseLanguage | `String` | The base language of the Hotel |
| beginDate | `Date` | Begin Date |
| block | `String` | Block |
| brArea | `String` | Ball Room Area |
| brSeats | `Float` | No of Ballroom Seats |
| brandCode | `String` | Brand Code |
| budgetMonth | `Float` | Financial Year of the Property |
| cROCode | `String` | CRO Code |
| cRSResort | `String` | Not used |
| cashShiftDrop | `String` | Internal |
| centralPropertyType | `String` | Central Property Type |
| chainCode | `String` | Chain Code |
| chainDescription | `String` | Chain Description |
| checkExgPaidout | `String` | Internal |
| checkInTime | `Date` | The Hotel official check intime |
| checkOutTime | `Date` | The Hotel official check out time |
| checkShiftDrop | `String` | Internal |
| checkTrxcode | `String` | Internal |
| city | `String` | City |
| cityDescription | `String` | City Description. |
| clientBookingReference | `String` | Client Booking Reference |
| comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| company | `String` | Company |
| companyAddressType | `String` | Internal |
| companyCapitalAmount | `String` | Company Capital Amount |
| companyCity | `String` | Company City |
| companyCountryName | `String` | Company Country Name |
| companyIMOBody | `String` | Company IMO Body |
| companyLegalText | `String` | Company Legal Text |
| companyNAF | `String` | Company NAF |
| companyPhoneType | `String` | Internal |
| companyRCS | `String` | Company RCS |
| companySiret | `String` | Company Siret |
| companyTypeBody | `String` | The type of legal entity / company e.g. Individual Micro enterprise etc. |
| configurationMode | `String` | Internal |
| confirmRegcardPrinter | `String` | Internal |
| copies | `Float` | Copies |
| country | `String` | Country |
| countryCode | `String` | Country Code |
| countryName | `String` | Country Name |
| creditLimit | `Float` | Credit Limit |
| currencyCode | `String` | Currency Code |
| currencyDecimals | `Float` | Number of decimals to designate currency |
| currencyDescription | `String` | Currency Description |
| currencyExgPaidout | `String` | Not used |
| currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateForAging | `String` | Date the aging should begin |
| dateSeparator | `String` | Type of separator to distinguish between DD MM and YYYY |
| dblNum | `String` | Not used |
| dblRate2 | `Float` | Not used |
| dblRate1 | `Float` | Not used |
| decimalPlaces | `Float` | Number of places for the default currency |
| decimalSeparator | `String` | Type of decimal separator |
| defaultCommissionPercentage | `String` | Not used |
| defaultFaxType | `String` | Not used |
| defaultFolioStyle | `Float` | Folio style to be used for all guests |
| defaultGroupsRateCode | `String` | Not used |
| defaultGuestAddress | `String` | Default guest address format. |
| defaultMembershipType | `String` | Future use |
| defaultPostingRoom | `String` | Future use |
| defaultPrepaidComm | `String` | Not used. |
| defaultPrinter | `String` | Not Used |
| defaultPropertyAddress | `String` | Default property address format. |
| defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| defaultRegistrationCard | `String` | Default registration card for the property. |
| defaultReservationType | `String` | The Default reservation type for this property |
| defaultTrxCommissionCode | `String` | Not used. |
| depositLedgerTrxCode | `String` | Future use |
| dfltPkgTranCode | `String` | Future use |
| dfltTranCodeRateCode | `String` | Future use |
| dirsales | `String` | Future use |
| dutyManagerPager | `String` | Pager number for the Manager on duty for the property. |
| email | `String` | Email |
| endDate | `Date` | End Date |
| exchangePostingType | `String` | Exchange Posting Type |
| expiryDate | `Date` | Expiry Date |
| extPropertyCode | `String` | Future use |
| fax | `String` | Fax |
| faxNoFormat | `String` | Fax number formats. |
| fileTransferFormat | `String` | Not used. |
| fiscalEndDate | `Date` | Future use |
| fiscalPeriodType | `String` | Future use |
| fiscalStartDate | `Date` | Future use |
| fiscalStartMonth | `Float` | Fiscal Start Month |
| fiscalStartYear | `Float` | Fiscal Start Year |
| flowCode | `String` | Future use |
| folioLanguage1 | `String` | Other languages |
| folioLanguage2 | `String` | Other languages |
| folioLanguage3 | `String` | Other languages |
| folioLanguage4 | `String` | Other languages |
| font | `Float` | Not used |
| footerLegalText1 | `String` | Footer Legal Text1 |
| footerLegalText2 | `String` | Footer Legal Text2 |
| footerLegalText3 | `String` | Footer Legal Text3 |
| genmgr | `String` | Future use |
| groupRoomWarning | `Float` | To define an upper limit to the number of rooms for Group |
| guarantorAddress | `String` | Guarantor Address |
| guestLookupTimeout | `Float` | Future use |
| hotelFc | `String` | Future use |
| hotelId | `String` | Hotel ID |
| hotelType | `String` | Hotel Type |
| iBAN | `String` | IBAN |
| imgDirectionId | `Float` | Future use |
| imgHotelId | `Float` | Future use |
| imgMapId | `Float` | Future use |
| inactiveDaysForGuestProfil | `Float` | Future use |
| individualAddressType | `String` | Future use |
| individualPhoneType | `String` | Future use |
| individualRoomWarning | `Float` | To define an upper limit to the number of rooms for group |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| insurerAddressBody | `String` | Insurer Address Body |
| internalLocationId | `String` | Location ID |
| internalOrganizationId | `Float` | Organization ID |
| inventoryYn | `String` | Indicates if the Resources under this Type need to maintain inventory. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keepAvailability | `Float` | To calculate the entire availability of the Hotel for future reservations |
| layoutTemplate | `String` | Layout Template |
| leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| legalOwner | `String` | The owner who owns this property |
| licenseCode | `String` | License Code |
| localCurrencyFormat | `String` | Format for the local currency. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| longDateFormat | `String` | Long date format for the property. |
| longStayControl | `Float` | The default length of stay |
| marketingText | `String` | Marketing Text |
| maxNoNights | `Float` | Not used |
| maxOccupancy | `Float` | Max Occupancy |
| meetRooms | `Float` | Future use |
| meetSeats | `Float` | Future use |
| meetSpace | `Float` | Future use |
| meetingFc | `String` | Future use |
| minDaysBet2ReminderLetter | `Float` | Minimum days for reminder letter. |
| nameIdLink | `Float` | Internal |
| nightAuditCashierId | `String` | Future use |
| notes | `String` | Notes |
| numberBeds | `Float` | Total number of beds in this property |
| numberFloors | `Float` | Total number of floors in this property |
| numberRooms | `Float` | Number Rooms |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| ownership | `String` | Future use |
| packageLoss | `String` | Package Loss code for a particular package |
| packageProfit | `String` | Package Profit code for a particular Package |
| passerbyMarket | `String` | Market code for passerby |
| passerbySource | `String` | Source code for passerby |
| perReservationRoomLimit | `Float` | Future use |
| postCode | `String` | Post Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| propertyName | `String` | Property Name |
| propertyType | `String` | Property Type |
| quotedCurrency | `String` | Future use |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repPasserbyMarket | `String` | Reporting Passerby Market |
| repPasserbySource | `String` | Reporting Passerby Source |
| repState | `String` | Reporting State |
| repStateDescription | `String` | Reporting State Desc |
| restaurant | `Float` | Future use |
| rhythmSheets | `Float` | Total number of Sheets |
| rhythmTowels | `Float` | Total number of Towels |
| saveProfiles | `Float` | To store number of days before deleting the gest profile |
| scriptId | `Float` | Script ID |
| season1 | `String` | Future use |
| season2 | `String` | Future use |
| season3 | `String` | Future use |
| season4 | `String` | Future use |
| season5 | `String` | Future use |
| sglNum | `String` | Future use |
| sglRate1 | `Float` | Future use |
| sglRate2 | `Float` | Future use |
| shortDateFormat | `String` | Short date format for the property. |
| sourceCommission | `String` | For default commission percentage |
| state | `String` | State |
| stateDesc | `String` | State Description of the Guest of Payee |
| street | `String` | The street of the property. |
| suiNum | `String` | Future use |
| suiRate1 | `Float` | Future use |
| suiRate2 | `Float` | Future use |
| summCurrencyCode | `String` | Internal |
| taCommission | `String` | For default commission percentage |
| taxID | `String` | Tax ID |
| telephone | `String` | The direct dial phone number of this property |
| telephoneNoFormat | `String` | Formats for telephone number |
| thousandSeparator | `String` | Separator for monetory values |
| timeFormat | `String` | Default time format for the property. |
| tollfree | `String` | Toll free telephone number. |
| totalRooms | `Float` | Future use |
| tplNum | `String` | Future use |
| tplRate1 | `Float` | Future use |
| tplRate2 | `Float` | Future use |
| turnawayCode | `String` | Turnaway Code |
| unitAddress | `String` | Unit Address |
| unitBrand | `String` | Unit Brand |
| unitCity | `String` | Unit City |
| unitCountry | `String` | Unit Country |
| unitCountryName | `String` | Unit Country Name |
| unitFax | `String` | Unit Fax |
| unitMail | `String` | Unit Mail |
| unitName | `String` | Unit Name |
| unitPhone | `String` | Unit Phone |
| unitType | `String` | Unit of measure. Values are Mile or KM or Block. |
| unitWeb | `String` | Unit Web |
| unitZIP | `String` | Unit Zipcode |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| vAT1 | `String` | VAT1 |
| vAT10 | `String` | VAT10 |
| vAT11 | `String` | VAT11 |
| vAT12 | `String` | VAT12 |
| vAT13 | `String` | VAT13 |
| vAT14 | `String` | VAT14 |
| vAT15 | `String` | VAT15 |
| vAT16 | `String` | VAT16 |
| vAT17 | `String` | VAT17 |
| vAT18 | `String` | VAT18 |
| vAT19 | `String` | VAT19 |
| vAT2 | `String` | VAT2 |
| vAT20 | `String` | VAT20 |
| vAT3 | `String` | VAT3 |
| vAT4 | `String` | VAT4 |
| vAT5 | `String` | VAT5 |
| vAT6 | `String` | VAT6 |
| vAT7 | `String` | VAT7 |
| vAT8 | `String` | VAT8 |
| vAT9 | `String` | VAT9 |
| videoCoStart | `Date` | Video check out start time. |
| videoCoStop | `Date` | Video check out end time. |
| videocheckoutPrinter | `String` | Future use |
| wakeUpDelay | `Float` | Future use |
| warningAmount | `Float` | Amount at which warning is raised. |
| webaddress | `String` | Webaddress of the property |
| weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| zeroInvPurDays | `Float` | Internal |

[⬆ Back to Query](#query)

---

### EFolioProfileAllInformationDetailsType

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

### EFolioProfileAddressDetailsType

| Field | Type | Description |
| --- | --- | --- |
| address1 | `String` | The first line of street address. |
| address2 | `String` | The second line of street address. |
| address3 | `String` | The third line of street address. |
| address4 | `String` | The fourth line of street address. |
| addressID | `Float` | The primary key for this table. |
| addressLanguage | `String` | Address Language |
| addressLanguageDescription | `String` | Description for each language code. |
| addressType | `String` | The type of address. |
| addressTypeDesc | `String` | The description of this value. |
| barcode | `String` | The postal barcode for the address. |
| beginDate | `Date` | Not used. |
| centralState | `String` | Central State |
| centralStateDescription | `String` | Central State Description |
| chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| city | `String` | The city for this address. |
| cleansedDatetime | `DateTime` | The Timestamp when this record was cleansed. |
| cleansedErrormsg | `String` | The error message why this record was not cleansed. |
| cleansedMatchstatus | `String` | Specifies how the address elements match with the postal reference data. |
| cleansedStatus | `String` | Status of Address Cleansing. Null = Record is not cleansed. C = Cleansed. F = Failure. |
| cleansedValidationstatus | `String` | Validation Status as returned by the Address Cleansing System. |
| clientID | `String` | The unique key of this name stores IATA# Company # etc. |
| countryCode | `String` | Country . |
| countryDescription | `String` | Country name. |
| createdByUser | `Float` | The user that created the record |
| createdOnDate | `DateTime` | The date the record was created |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedYN | `String` | Deleted Y/n |
| endDate | `Date` | Not used. |
| firstName | `String` | The first name of an individual name. |
| foreignCountry | `String` | Not used. |
| inCareOf | `String` | Not used. |
| inactiveDate | `DateTime` | The date the record was marked as inactive |
| inactiveYN | `String` | Inactive Y/n |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Code to synchronize with Laptop. (not used) |
| lastUpdatedResort | `String` | Last property that updated this record. |
| name | `String` | Name |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| postalCode | `String` | The postal code of this address. |
| postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Profile having Multiple Addresses Need to have one Primary Address for each Type. |
| profileAddressId | `Float` | The primary key for this table. |
| profileId | `Float` | The reference to the NAME record that owns this address. |
| profileIdx | `Float` | The reference to the NAME record that owns this address. |
| province | `String` | Province. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| state | `String` | State |
| stateCode | `String` | The state of this address. |
| updateDate | `DateTime` | The date the record was modified |
| updateUser | `Float` | The user that modified the record |

[⬆ Back to Query](#query)

---

### EFolioProfileCommunicationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| addressId | `Float` | Not used. |
| beginDate | `Date` | Not used. |
| chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| communicationID | `Float` | The primary key for this table. |
| communicationRole | `String` | Role in which this phone type belongs to. |
| communicationValue | `String` | The phone number for this record |
| countryCode | `String` | Country Code of the phone number. |
| countryDialingCode | `Float` | Numeric phone dialing prefix code for the country. |
| countryId | `String` | Country Code of the phone number. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultMethodYN | `String` | Phone_role to be used for default confirmation. |
| deletedFlag | `String` | Deleted Flag |
| displaySequence | `Float` | Order in which the phone numbers should be displayed. |
| emailFormat | `String` | Format type for email messages: HTML PLAIN text. |
| emailLanguage | `String` | Optional language for e-mail. |
| endDate | `Date` | The date this record becomes invalid for use in the system. User enterable. |
| extension | `String` | Telephone Extension. |
| firstName | `String` | The first name of an individual name. |
| inactiveDate | `DateTime` | The date the record was marked as inactive |
| inactiveFlag | `String` | Inactive Flag |
| indexPhone | `String` | Index Phone |
| insertDate | `DateTime` | The date the record was created |
| insertUser | `Float` | The user that created the record |
| internalOrganizationId | `Float` | Organization ID |
| internalProfileId | `Float` | The reference to the name that owns this phone. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Code to synchronize with Laptop |
| lastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| phoneId | `Float` | The primary key for this table. |
| phoneType | `String` | The type of this phone number. |
| phoneTypeDescription | `String` | Description of Phone Types. |
| phoneTypeId | `String` | The type of this phone number. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryYN | `String` | Indicates the primary telephone number in the case of multiple phone numbers on a profile. |
| profileID | `Float` | The reference to the name that owns this phone. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| shareEmailYn | `String` | Used for uploading the email to holidex if the value is Y. |
| updateDate | `DateTime` | The date the record was modified |
| updateUser | `Float` | The user that modified the record |
| validYn | `String` | Indicates that the phone number has been validated using the Starwood API and is determined to be valid a <NULL> value indicates that the phone number has not been validated. |

[⬆ Back to Query](#query)

---

### EFolioReservationDetailsType

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

### EFolioFiscalCalendarDetailsType

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

### EFolioGregerianCalendarDetailsType

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

### EFolioExportMapEfolioExportDetailsType

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
| configType | `String` | Config Type |
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
| mappedToDesc | `String` | Mapped To Description |
| mappingCode | `String` | Code for the mapping code. |
| mappingCodeDescription | `String` | Description for the mapping code. |
| mappingType | `String` | Mapping Type |
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
| typeDesc | `String` | Type Description |
| typeInsertDate | `DateTime` | Type Insert Date |
| typeInsertUser | `Float` | Type Insert User |
| typeInsertUserName | `String` | Type Insert User Name |
| typeUpdateDate | `DateTime` | Type Update Date |
| typeUpdateUser | `Float` | Type Update User |
| typeUpdateUserName | `String` | Type Update User Name |
| useLovYn | `String` | Show LOV button when linking this mapping code to the configuration item. |

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

### EFolioQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| foliotaxDetailsAccountCode | `FloatInput` | Account Code |
| foliotaxDetailsAddresseeNameId | `FloatInput` | Addressee Name ID |
| foliotaxDetailsAssociatedBillNo | `StringInput` | Associated Bill Number |
| foliotaxDetailsAssociatedSeqNo | `FloatInput` | Self referencing sequence number to gather information for other operations. |
| foliotaxDetailsBillGenerationDate | `DateInput!` | Bill Generation Date<br>`@mandatoryInput` |
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
| foliotaxDetailsResort | `StringInput!` | Code to uniquely identify the Property<br>`@mandatoryInput` |
| foliotaxDetailsResvNameId | `FloatInput` | Resv Name ID |
| foliotaxDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| foliotaxDetailsSeqNo | `FloatInput` | Sequence No |
| foliotransactionsDetailsAccountid | `FloatInput` | Accountid |
| foliotransactionsDetailsArLedCredit | `FloatInput` | AR Led Credit |
| foliotransactionsDetailsArLedDebit | `FloatInput` | AR Led Debit |
| foliotransactionsDetailsArNumber | `FloatInput` | AR Number |
| foliotransactionsDetailsArState | `StringInput` | AR State |
| foliotransactionsDetailsArticleId | `FloatInput` | Article ID |
| foliotransactionsDetailsAuthemployeeid | `FloatInput` | Authemployeeid |
| foliotransactionsDetailsAuthorizerId | `FloatInput` | Authorizer ID |
| foliotransactionsDetailsBillNo | `FloatInput` | Bill Number |
| foliotransactionsDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| foliotransactionsDetailsBusinessDate | `DateInput` | Business Date |
| foliotransactionsDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| foliotransactionsDetailsCashierId | `FloatInput` | Cashier ID |
| foliotransactionsDetailsChequeNumber | `StringInput` | Check Number |
| foliotransactionsDetailsClosureNo | `FloatInput` | Closure Number |
| foliotransactionsDetailsCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| foliotransactionsDetailsComplinktranscodeid | `StringInput` | Complinktranscodeid |
| foliotransactionsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| foliotransactionsDetailsExchDiffTrxNo | `FloatInput` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| foliotransactionsDetailsFinBillNo | `FloatInput` | Financial Bill No |
| foliotransactionsDetailsFinBusinessDate | `DateInput` | Financial Business Date |
| foliotransactionsDetailsFinFolioView | `FloatInput` | Financial Folio View |
| foliotransactionsDetailsFinInsertDate | `DateInput` | Financial Insert Date |
| foliotransactionsDetailsFinInvoiceNo | `FloatInput` | Financial Invoice No |
| foliotransactionsDetailsFinPostitNo | `FloatInput` | Financial Postit No |
| foliotransactionsDetailsFinRoom | `StringInput` | Financial Room |
| foliotransactionsDetailsFinCXchangeDate | `DateInput` | Fin Central Xchange Date |
| foliotransactionsDetailsFinCashierId | `FloatInput` | Fin Cashier ID |
| foliotransactionsDetailsFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| foliotransactionsDetailsFinNameId | `FloatInput` | Fin Name ID |
| foliotransactionsDetailsFinResvNameId | `FloatInput` | Fin Resv Name ID |
| foliotransactionsDetailsFintransactionid | `FloatInput` | Fintransactionid |
| foliotransactionsDetailsFintransid | `FloatInput` | Fintransid |
| foliotransactionsDetailsFolioNo | `FloatInput` | Folio Number |
| foliotransactionsDetailsFolioView | `FloatInput` | Folio View |
| foliotransactionsDetailsFolioid | `FloatInput` | Folioid |
| foliotransactionsDetailsFromResvId | `FloatInput` | From Resv ID |
| foliotransactionsDetailsGuestAccountCredit | `FloatInput` | Guest Account Credit |
| foliotransactionsDetailsGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| foliotransactionsDetailsHotelAcct | `StringInput` | Specifies the Hotel acct against which this transaction has beenposted. |
| foliotransactionsDetailsInsertDate | `DateTimeInput` | Insert Date |
| foliotransactionsDetailsArticleid | `FloatInput` | Articleid |
| foliotransactionsDetailsBusinessdate | `DateInput` | Businessdate |
| foliotransactionsDetailsCashierid | `FloatInput` | Cashierid |
| foliotransactionsDetailsInvoiceNo | `FloatInput` | Invoice Number |
| foliotransactionsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| foliotransactionsDetailsLinkTrxNo | `FloatInput` | Link Transaction No |
| foliotransactionsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| foliotransactionsDetailsNameId | `FloatInput` | Name ID |
| foliotransactionsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| foliotransactionsDetailsOriginalResvNameId | `FloatInput` | Original Reservation Name ID |
| foliotransactionsDetailsOriginalRoom | `StringInput` | Original Room |
| foliotransactionsDetailsOriginalresvid | `FloatInput` | Originalresvid |
| foliotransactionsDetailsPackagelinkfintransid | `FloatInput` | Packagelinkfintransid |
| foliotransactionsDetailsParentfintransid | `FloatInput` | Parentfintransid |
| foliotransactionsDetailsPostitNo | `FloatInput` | Postit Number |
| foliotransactionsDetailsProduct | `StringInput` | Product |
| foliotransactionsDetailsProductid | `StringInput` | Productid |
| foliotransactionsDetailsProfileid | `FloatInput` | Profileid |
| foliotransactionsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| foliotransactionsDetailsRateCode | `StringInput` | Rate Code |
| foliotransactionsDetailsRatecodeid | `StringInput` | Ratecodeid |
| foliotransactionsDetailsRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| foliotransactionsDetailsResvNameId | `FloatInput` | Resv Name ID |
| foliotransactionsDetailsReservationid | `FloatInput` | Reservationid |
| foliotransactionsDetailsRoom | `StringInput` | Room |
| foliotransactionsDetailsRoomid | `StringInput` | Roomid |
| foliotransactionsDetailsRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| foliotransactionsDetailsRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| foliotransactionsDetailsTaxElements | `StringInput` | Tax Elements |
| foliotransactionsDetailsTranActionId | `FloatInput` | Tran Action ID |
| foliotransactionsDetailsTrxCode | `StringInput` | Transaction Code |
| foliotransactionsDetailsTrxDate | `DateInput` | Transaction Date |
| foliotransactionsDetailsTcGroup | `StringInput` | Transaction Group Code |
| foliotransactionsDetailsTrxNo | `FloatInput` | Transaction ID |
| foliotransactionsDetailsTcSubgroup | `StringInput` | Transaction Sub-Group Code |
| foliotransactionsDetailsTranscodeid | `StringInput` | Transcodeid |
| foliotransactionsDetailsTrxNoAddedBy | `FloatInput` | Transaction No Added By |
| foliotransactionsDetailsTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| foliotransactionsDetailsTrxNoHeader | `FloatInput` | Transaction No Header |
| foliotransactionsDetailsTrxNoAgainstPackage | `FloatInput` | Wrapper Transaction ID |
| resortexportvaluesDetailsCrsResort | `StringInput` | Not used |
| resortexportvaluesDetailsCountryCode | `StringInput` | Country Code |
| resortexportvaluesDetailsCurrencyCode | `StringInput` | Currency Code |
| resortexportvaluesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortexportvaluesDetailsLocationId | `StringInput` | Location ID |
| resortexportvaluesDetailsOrganizationId | `FloatInput` | Organization ID |
| resortexportvaluesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortexportvaluesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| resortexportvaluesDetailsNameIdLink | `FloatInput` | Internal |
| resortexportvaluesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortexportvaluesDetailsResort | `StringInput` | Property |
| resortexportvaluesDetailsResortType | `StringInput` | Property Type |
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
| profileaddressDetailsAddress1 | `StringInput` | The first line of street address. |
| profileaddressDetailsAddress2 | `StringInput` | The second line of street address. |
| profileaddressDetailsAddress3 | `StringInput` | The third line of street address. |
| profileaddressDetailsAddress4 | `StringInput` | The fourth line of street address. |
| profileaddressDetailsAddressId | `FloatInput` | The primary key for this table. |
| profileaddressDetailsLanguageCode | `StringInput` | Address Language |
| profileaddressDetailsLanguageDesc | `StringInput` | Description for each language code. |
| profileaddressDetailsAddressType | `StringInput` | The type of address. |
| profileaddressDetailsAddressTypeDesc | `StringInput` | The description of this value. |
| profileaddressDetailsBarcode | `StringInput` | The postal barcode for the address. |
| profileaddressDetailsBeginDate | `DateInput` | Not used. |
| profileaddressDetailsRepStateCode | `StringInput` | Central State |
| profileaddressDetailsRepState | `StringInput` | Central State Description |
| profileaddressDetailsChainCode | `StringInput` | The Chain code of the chain for which this record belongs to. |
| profileaddressDetailsCity | `StringInput` | The city for this address. |
| profileaddressDetailsCleansedDatetime | `DateTimeInput` | The Timestamp when this record was cleansed. |
| profileaddressDetailsCleansedErrormsg | `StringInput` | The error message why this record was not cleansed. |
| profileaddressDetailsCleansedMatchstatus | `StringInput` | Specifies how the address elements match with the postal reference data. |
| profileaddressDetailsCleansedStatus | `StringInput` | Status of Address Cleansing. Null = Record is not cleansed. C = Cleansed. F = Failure. |
| profileaddressDetailsCleansedValidationstatus | `StringInput` | Validation Status as returned by the Address Cleansing System. |
| profileaddressDetailsNameCode | `StringInput` | The unique key of this name stores IATA# Company # etc. |
| profileaddressDetailsCountryCode | `StringInput` | Country . |
| profileaddressDetailsCountry | `StringInput` | Country name. |
| profileaddressDetailsInsertUser | `FloatInput` | The user that created the record |
| profileaddressDetailsInsertDate | `DateTimeInput` | The date the record was created |
| profileaddressDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaddressDetailsDeletedFlag | `StringInput` | Deleted Y/n |
| profileaddressDetailsEndDate | `DateInput` | Not used. |
| profileaddressDetailsFirst | `StringInput` | The first name of an individual name. |
| profileaddressDetailsForeignCountry | `StringInput` | Not used. |
| profileaddressDetailsInCareOf | `StringInput` | Not used. |
| profileaddressDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |
| profileaddressDetailsInactiveFlag | `StringInput` | Inactive Y/n |
| profileaddressDetailsOrganizationId | `FloatInput` | Organization ID |
| profileaddressDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileaddressDetailsLaptopChange | `FloatInput` | Code to synchronize with Laptop. (not used) |
| profileaddressDetailsLastUpdatedResort | `StringInput` | Last property that updated this record. |
| profileaddressDetailsName | `StringInput` | Name |
| profileaddressDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaddressDetailsZipCode | `StringInput` | The postal code of this address. |
| profileaddressDetailsCityExt | `StringInput` | City Extension mainly used for UK addresses. |
| profileaddressDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| profileaddressDetailsPrimaryYn | `StringInput` | Profile having Multiple Addresses Need to have one Primary Address for each Type. |
| profileaddressDetailsProfileAddressId | `FloatInput` | The primary key for this table. |
| profileaddressDetailsNameId | `FloatInput` | The reference to the NAME record that owns this address. |
| profileaddressDetailsProfileId | `FloatInput` | The reference to the NAME record that owns this address. |
| profileaddressDetailsProvince | `StringInput` | Province. |
| profileaddressDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| profileaddressDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| profileaddressDetailsState | `StringInput` | State |
| profileaddressDetailsStateCode | `StringInput` | The state of this address. |
| profileaddressDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| profileaddressDetailsUpdateUser | `FloatInput` | The user that modified the record |
| profilecommunicationDetailsAddressId | `FloatInput` | Not used. |
| profilecommunicationDetailsBeginDate | `DateInput` | Not used. |
| profilecommunicationDetailsChainCode | `StringInput` | The Chain code of the chain for which this record belongs to. |
| profilecommunicationDetailsPmsPhoneId | `FloatInput` | The primary key for this table. |
| profilecommunicationDetailsRole | `StringInput` | Role in which this phone type belongs to. |
| profilecommunicationDetailsPhoneNumber | `StringInput` | The phone number for this record |
| profilecommunicationDetailsCountryCode | `StringInput` | Country Code of the phone number. |
| profilecommunicationDetailsCountryDialingCode | `FloatInput` | Numeric phone dialing prefix code for the country. |
| profilecommunicationDetailsCountryId | `StringInput` | Country Code of the phone number. |
| profilecommunicationDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilecommunicationDetailsDefaultMethodFlag | `StringInput` | Phone_role to be used for default confirmation. |
| profilecommunicationDetailsDeletedFlag | `StringInput` | Deleted Flag |
| profilecommunicationDetailsOrderby | `FloatInput` | Order in which the phone numbers should be displayed. |
| profilecommunicationDetailsEmailFormat | `StringInput` | Format type for email messages: HTML PLAIN text. |
| profilecommunicationDetailsEmailLanguage | `StringInput` | Optional language for e-mail. |
| profilecommunicationDetailsEndDate | `DateInput` | The date this record becomes invalid for use in the system. User enterable. |
| profilecommunicationDetailsExtension | `StringInput` | Telephone Extension. |
| profilecommunicationDetailsFirst | `StringInput` | The first name of an individual name. |
| profilecommunicationDetailsInactiveDate | `DateTimeInput` | The date the record was marked as inactive |
| profilecommunicationDetailsInactiveFlag | `StringInput` | Inactive Flag |
| profilecommunicationDetailsIndexPhone | `StringInput` | Index Phone |
| profilecommunicationDetailsInsertDate | `DateTimeInput` | The date the record was created |
| profilecommunicationDetailsInsertUser | `FloatInput` | The user that created the record |
| profilecommunicationDetailsOrganizationId | `FloatInput` | Organization ID |
| profilecommunicationDetailsProfileId | `FloatInput` | The reference to the name that owns this phone. |
| profilecommunicationDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilecommunicationDetailsLaptopChange | `FloatInput` | Code to synchronize with Laptop |
| profilecommunicationDetailsLast | `StringInput` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| profilecommunicationDetailsMobileAudioKeyYn | `StringInput` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| profilecommunicationDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilecommunicationDetailsPhoneId | `FloatInput` | The primary key for this table. |
| profilecommunicationDetailsPhoneType | `StringInput` | The type of this phone number. |
| profilecommunicationDetailsPhoneTypeDescription | `StringInput` | Description of Phone Types. |
| profilecommunicationDetailsPhoneTypeId | `StringInput` | The type of this phone number. |
| profilecommunicationDetailsPkid | `FloatInput` | Internal Primary Key ID to uniquely identify the row |
| profilecommunicationDetailsPrimaryYn | `StringInput` | Indicates the primary telephone number in the case of multiple phone numbers on a profile. |
| profilecommunicationDetailsNameId | `FloatInput` | The reference to the name that owns this phone. |
| profilecommunicationDetailsRnaInsertdate | `DateTimeInput` | RnA Insertdate |
| profilecommunicationDetailsRnaUpdatedate | `DateTimeInput` | RnA Updatedate |
| profilecommunicationDetailsShareEmailYn | `StringInput` | Used for uploading the email to holidex if the value is Y. |
| profilecommunicationDetailsUpdateDate | `DateTimeInput` | The date the record was modified |
| profilecommunicationDetailsUpdateUser | `FloatInput` | The user that modified the record |
| profilecommunicationDetailsValidYn | `StringInput` | Indicates that the phone number has been validated using the Starwood API and is determined to be valid a <NULL> value indicates that the phone number has not been validated. |
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
| fiscalcalendarDetailsDaykey | `DateInput` | Business Date |
| fiscalcalendarDetailsCalendarcode | `StringInput` | Calendar |
| fiscalcalendarDetailsCalendarpkid | `FloatInput` | Calendarpkid |
| fiscalcalendarDetailsPeriodpkid | `FloatInput` | Periodpkid |
| fiscalcalendarDetailsQuartercode | `StringInput` | Quarter |
| fiscalcalendarDetailsQuarterpkid | `FloatInput` | Quarterpkid |
| fiscalcalendarDetailsYearcode | `FloatInput` | Year |
| fiscalcalendarDetailsYearpkid | `FloatInput` | Yearpkid |
| gregeriancalendarDetailsDaykey | `DateInput` | Business Date |
| gregeriancalendarDetailsCalendarcode | `StringInput` | Calendar |
| gregeriancalendarDetailsCalendarpkid | `FloatInput` | Calendarpkid |
| gregeriancalendarDetailsPeriodpkid | `FloatInput` | Periodpkid |
| gregeriancalendarDetailsQuartercode | `StringInput` | Quarter |
| gregeriancalendarDetailsQuarterpkid | `FloatInput` | Quarterpkid |
| gregeriancalendarDetailsYearcode | `FloatInput` | Year |
| gregeriancalendarDetailsYearpkid | `FloatInput` | Yearpkid |
| expmapefolioexportDetailsConfigType | `StringInput` | Config Type |
| expmapefolioexportDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| expmapefolioexportDetailsExpMappingId | `FloatInput` | Exp Mapping ID |
| expmapefolioexportDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| expmapefolioexportDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| expmapefolioexportDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| expmapefolioexportDetailsResort | `StringInput` | Code to uniquely identify the Property |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query eFolio($input: EFolioQueryArgumentsType!) {
  eFolio(input: $input) @stream {
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
    folioTransactionsDetails {
      aRChargeTransferYN
      aSBFlag
      aSBOnlyPostTaxesOnceYn
      aSBTaxFlag
      accountCode
      accountTypeFlag
      accountid
      address1
      addresseeNameId
      adjustmentflag
      advGenerateAdjustment
      advanceBillReversedYn
      advanceBillYn
      advanceGenerateTrxCode
      advancedGenerateYn
      advgentranscodeid
      approvalCode
      approvalDate
      approvalStatus
      arLedgerCredit
      arLedgerDebit
      arNumber
      arState
      arTransferDate
      archargetransferflag
      arrangementCode
      arrangementDescription
      arrangementId
      articleId
      associatedBillDate
      associatedBillNo
      associatedFiscalBillDate
      associatedFiscalBillNo
      associatedFiscalBillTime
      associatedReceiptNo
      associatedSeqNumber
      associatedTrxNumber
      authemployeeid
      authorizerId
      autoCreditbillYn
      autoSettleYn
      billGenerationDate
      billGenerationTime
      billNo
      billPaymentTrxNumber
      billPrefix
      billSeqNumber
      billStartDate
      bonusCheckId
      bucketCode
      bucketRedempYn
      businessDate
      businessId
      cARLedgerCredit
      cARLedgerDebit
      cCashierCredit
      cCashierDebit
      cCashierOpeningBalance
      cCashpay
      cCcTransactionFeeAmount
      cCcpay
      cChangeDue
      cClarpay
      cClpay
      cCollectionTax1
      cCollectionTax2
      cCollectionTax3
      cCollectionTax4
      cCollectionTax5
      cContractGrossAmount
      cContractGuestCredit
      cContractGuestDebit
      cContractNetAmount
      cDailyRunningTotal
      cDepLedgerCredit
      cDepLedgerDebit
      cDeposit
      cExchangeDate
      cExchangeRate
      cFiscalInvoiceCurrencyRate
      cForexCommissionAmount
      cGuestAccountCredit
      cGuestAccountDebit
      cInHouseCredit
      cInHouseDebit
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
      cNonRevenueAmount
      cOrganizationARLedgerDebit
      cOrganizationPostedAmount
      cPackageAllowance
      cPackageCredit
      cPackageDebit
      cPaidout
      cParallelGrossAmount
      cParallelGuestCredit
      cParallelGuestDebit
      cParallelNetAmount
      cPaymentSurchargeAmount
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
      cPostedAmount
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
      cRevenueAmount
      cTax1Amount
      cTax1Rate
      cTax2Amount
      cTax2Rate
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
      cTaxRate
      cTax10Amount
      cTax10Rate
      cTax11Amount
      cTax11Rate
      cTax12Amount
      cTax12Rate
      cTax13Amount
      cTax13Rate
      cTax14Amount
      cTax14Rate
      cTax15Amount
      cTax15Rate
      cTax16Amount
      cTax16Rate
      cTax17Amount
      cTax17Rate
      cTax18Amount
      cTax18Rate
      cTax19Amount
      cTax19Rate
      cTax20Amount
      cTax20Rate
      cTax3Amount
      cTax3Rate
      cTax4Amount
      cTax4Rate
      cTax5Amount
      cTax5Rate
      cTax6Amount
      cTax6Rate
      cTax7Amount
      cTax7Rate
      cTax8Amount
      cTax8Rate
      cTax9Amount
      cTax9Rate
      cTotalGross
      cTotalNet
      cTotalNonTaxable
      cTotalNonrevNonTaxable
      cTotalNonrevTaxable
      cTotalRevenueNonTaxable
      cTotalRevenueTaxable
      cTotalTax
      cTransactionAmount
      cTrialBalanceAmountGross
      cTrialBalanceAmountNet
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
      calcmemberpointsflag
      cashRegisterId
      cashRegisterInvNumber
      cashierCredit
      cashierDebit
      cashierId
      cashierOpeningBalance
      cashpay
      ccRefundPosting
      ccTrxFeeAmount
      ccpay
      centralGrossAmount
      centralNetAmount
      centralPaymentAmount
      centralPrice
      centralTaxAmount
      centralTaxCode
      centralTaxCodeDescription
      centralTransactionAmount
      centralTransactionCode
      centralTransactionDescription
      centralTransactionGroupCode
      centralTransactionGroupDescription
      centralTransactionSubGroupCode
      centralTransactionSubGroupDescription
      changeDue
      checkFileId
      checkNumber
      city
      cityLedgerYn
      clTrxNumber
      clarpay
      closureNo
      clpay
      collectionAgentPostingYn
      collectionTax1
      collectionTax2
      collectionTax3
      collectionTax4
      collectionTax5
      comments
      compLinkTrxCode
      compLinkTrxNumber
      compTypeCode
      companyFinancialValue
      companyName
      companyType
      complinktranscodeid
      compressBillNo
      compressedYn
      contractCurrency
      contractGrossAmount
      contractGuestCredit
      contractGuestDebit
      contractNetAmount
      contractforeigncurrencyid
      correctionYn
      country
      countryCode
      couponNo
      covers
      creditBillGeneratedYn
      creditBillNo
      creditCardId
      currency
      dSI
      dailyRunningTotal
      debitOrCredit
      deferredYn
      deletedFlag
      depLedgerCredit
      depLedgerDebit
      depPostingFlag
      depTaxTransferedYn
      deposit
      depositReqReceiptNo
      depositTransactionId
      depositlinkfintransid
      displayflag
      documentCode
      documentType
      eArchiveEttnNumber
      eArchiveNumber
      eArchiveReportNo
      eArchiveStatus
      eInvoiceNumber
      eInvoiceStatus
      effectiveDate
      electronicVoucherNo
      esignedReceiptName
      euroExchangeRate
      exchDifferenceTrxNumber
      exchangeDate
      exchangeRate
      exchangeType
      exchangedifferenceflag
      expInvoiceType
      expOriginalInvoice
      extSysResultMsg
      extTransactionId
      fbaCertificateNumber
      filterChar1
      filterChar2
      filterChar3
      filterChar4
      filterChar5
      finBillNumber
      finBusinessDate
      finCountry
      finDeletedFlag
      finFiscalBillNumber
      finFolioView
      finInsertDate
      finInsertUser
      finInvoiceNumber
      finNameTaxType
      finPkid
      finPostitNumber
      finPropertyBillPrefix
      finQueueName
      finRevisionNumber
      finRoom
      finUpdateDate
      finUpdateUser
      financialCExchangeDate
      financialCExchangeRate
      financialCashierId
      financialDmlSeqNumber
      financialForexTaxYN
      financialNameId
      financialPostitYN
      financialReservationNameId
      fintransactionid
      fintransid
      first
      fiscalBillCheckDigit
      fiscalBillGenerationDate
      fiscalBillGenerationTime
      fiscalBillNo
      fiscalInvoiceCurrency
      fiscalInvoiceCurrencyRate
      fiscalSessionNo
      fiscalTrxCodeType
      fiscalUnitControlCode
      fixedchargesflag
      folioAddress
      folioAddressCorrectedYn
      folioAttachmentLinkId
      folioAttachmentStatus
      folioNo
      folioStyle
      folioTaxSeqNumber
      folioType
      folioType1
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
      fullFolioNo
      genCashierId
      gpAwardCancelCode
      gpAwardCode
      grossAmount
      groupAwardCancelledYN
      guestAccountCredit
      guestAccountDebit
      hasWatermarkYn
      hotelAcct
      hotelName
      incTaxDeductedYn
      inclusiveTaxYN
      individualAdjustmentYN
      inhCredit
      inhDebit
      insTimestamp
      insertDate
      insertUser
      insertUserName
      installments
      internalArticleid
      internalBusinessdate
      internalCashierid
      invoiceCloseDate
      invoiceNo
      invoiceType
      iscreditflag
      isdebitflag
      isinternalflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      last
      lastSignatureHash
      linkTrxNumber
      locationID
      marketCode
      marketid
      membershipid
      mtrxNoAgainstPackage
      nafApeHotelCode
      nameId
      nameTaxType
      nameTypeDescription
      netAmount
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
      nrBusinessId
      numberDialed
      numberOfPages
      oTransactionDesc
      onholdflag
      operaFiscalFolioStatus
      orgBillNumber
      orgFolioType
      orgPostedAmount
      organizationArLedgerDebit
      organizationID
      originalReservationNameID
      originalRoom
      originalresvid
      packageAllowance
      packageArrangementCode
      packageCredit
      packageDebit
      packageTrxType
      packagelinkfintransid
      pageNumber
      paidout
      palmVideoFlag
      parallelCurrency
      parallelGrossAmount
      parallelGuestCredit
      parallelGuestDebit
      parallelNetAmount
      parallelforeigncurrencyid
      parentfintransid
      partnerFiscalFolioStatus
      passerByName
      payeeName
      payeeNameId
      payeeZipCode
      paymentAmount
      paymentDate
      paymentDescription
      paymentSurchargeAmt
      paymentSurchargeType
      paymentTrxDate
      paymentType
      percentage
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
      postedAmount
      postingDate
      postingRhythm
      postingSourceNameId
      postingType
      postitNo
      postitYn
      price
      primaryKeyID
      processed8300flag
      product
      productid
      profileid
      profitLossFlag
      proformaYn
      promotionalText1
      promotionalText2
      property
      propertyBillPrefix
      propertyTaxNo
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
      quantity
      queueName
      rateCode
      ratecodeid
      realPerpetualAmount
      reasonCode
      receiptNo
      receiptType
      reference
      reservationDepositId
      reservationNameId
      reservationid
      resortCity
      resortCountry
      resortFullAddress
      resortZipcodeCode
      resvenddate
      revenueAmt
      reversePaymentTrxNumber
      revisionNo
      rnaInsertDate
      rnaUpdateDate
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
      seqNumber
      serviceRecoveryAdjustmentYn
      serviceRecoveryDeptCode
      serviceTypeCode
      settlementFlag
      signatureHash
      signatureKeyVersion
      softwareVersion
      sourceCode
      sourceCommissionNetYn
      sourceid
      splitType
      status
      supplement
      taCommissionNetYn
      tacommissionableflag
      targetResort
      targetlocationid
      tax1Amt
      tax1No
      tax1Rate
      tax1RateType
      tax2Amt
      tax2No
      tax2Rate
      tax2RateType
      taxAmount
      taxCode
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
      taxCodeDescription
      taxCodeNumber
      taxElements
      taxId
      taxInvNumber
      taxRate
      taxRateType
      tax10Amt
      tax10Rate
      tax10RateType
      tax11Amt
      tax11Rate
      tax11RateType
      tax12Amt
      tax12Rate
      tax12RateType
      tax13Amt
      tax13Rate
      tax13RateType
      tax14Amt
      tax14Rate
      tax14RateType
      tax15Amt
      tax15Rate
      tax15RateType
      tax16Amt
      tax16Rate
      tax16RateType
      tax17Amt
      tax17Rate
      tax17RateType
      tax18Amt
      tax18Rate
      tax18RateType
      tax19Amt
      tax19Rate
      tax19RateType
      tax20Amt
      tax20Rate
      tax20RateType
      tax3Amt
      tax3Rate
      tax3RateType
      tax4Amt
      tax4Rate
      tax4RateType
      tax5Amt
      tax5Rate
      tax5RateType
      tax6Amt
      tax6Rate
      tax6RateType
      tax7Amt
      tax7Rate
      tax7RateType
      tax8Amt
      tax8Rate
      tax8RateType
      tax9Amt
      tax9Rate
      tax9RateType
      taxdeferredflag
      taxgeneratedflag
      tclCode1
      tclCode2
      terminal
      thresholdDiversionId
      thresholdEntityQty
      thresholdEntityType
      thresholdTreatmentFlag
      toReservationNameId
      totalGross
      totalNet
      totalNonTaxable
      totalNonrevNonTaxable
      totalNonrevTaxable
      totalRevNonTaxable
      totalRevTaxable
      totalTax
      tranActionId
      transactLastSignatureHash
      transactSignatureHash
      transactSignatureKeyVersion
      transactionAmount
      transactionCode
      transactionDate
      transactionDescription
      transactionFromAcct
      transactionGroupCode
      transactionGroupDescription
      transactionID
      transactionSignature
      transactionSubGroupCode
      transactionSubGroupDescription
      transactionToAcct
      transactionType
      transcodearrangementid
      transcodeid
      transferfromaccountid
      transferfromresvid
      transfertoaccountid
      transfertoresvid
      trialBalanceAmountGross
      trialBalanceAmountNet
      trnsActivityDate
      trxAmount
      trxNumberAddedBy
      trxNumberAdjust
      trxNumberHeader
      trxNumberSplit
      trxServiceType
      trxTime
      trxType
      udfc01
      udfc02
      udfc03
      udfc04
      udfc05
      udfc06
      udfc07
      udfc08
      udfc09
      udfc10
      udfc11
      udfc12
      udfc13
      udfc14
      udfc15
      udfc16
      udfc17
      udfc18
      udfc19
      udfc20
      udfc21
      udfc22
      udfc23
      udfc24
      udfc25
      udfc26
      udfc27
      udfc28
      udfc29
      udfc30
      udfc31
      udfc32
      udfc33
      udfc34
      udfc35
      udfc36
      udfc37
      udfc38
      udfc39
      udfc40
      udfd01
      udfd02
      udfd03
      udfd04
      udfd05
      udfd06
      udfd07
      udfd08
      udfd09
      udfd10
      udfd11
      udfd12
      udfd13
      udfd14
      udfd15
      udfd16
      udfd17
      udfd18
      udfd19
      udfd20
      udfn01
      udfn02
      udfn03
      udfn04
      udfn05
      udfn06
      udfn07
      udfn08
      udfn09
      udfn10
      udfn11
      udfn12
      udfn13
      udfn14
      udfn15
      udfn16
      udfn17
      udfn18
      udfn19
      udfn20
      udfn21
      udfn22
      udfn23
      udfn24
      udfn25
      udfn26
      udfn27
      udfn28
      udfn29
      udfn30
      udfn31
      udfn32
      udfn33
      udfn34
      udfn35
      udfn36
      udfn37
      udfn38
      udfn39
      udfn40
      updTimestamp
      updateDate
      updateUser
      upsellChargeYn
      vatOffsetYn
      voidNo
      voidReason
      workingDocId
      wrapperTransactionID
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
      zipCode
    }
    propertyExportValuesDetails {
      aRAccountNumberMandYN
      aRBalanceTrxCode
      aRCreditTrxCode
      additionalLogos
      address
      agingLevel1
      agingLevel2
      agingLevel3
      agingLevel4
      agingLevel5
      airport
      airportDistance
      airportTime
      allowLoginYn
      allowancePeriodAdj
      arAccountNumberFormat
      arAgent
      arCompany
      arGroups
      arIndividuals
      arSettleCode
      arTypewriter
      awardsTimeout
      bIC
      bankAgencyCode
      bankAgencyName
      bankCode
      bankName
      baseLanguage
      beginDate
      block
      brArea
      brSeats
      brandCode
      budgetMonth
      cROCode
      cRSResort
      cashShiftDrop
      centralPropertyType
      chainCode
      chainDescription
      checkExgPaidout
      checkInTime
      checkOutTime
      checkShiftDrop
      checkTrxcode
      city
      cityDescription
      clientBookingReference
      comAddress
      comMethod
      company
      companyAddressType
      companyCapitalAmount
      companyCity
      companyCountryName
      companyIMOBody
      companyLegalText
      companyNAF
      companyPhoneType
      companyRCS
      companySiret
      companyTypeBody
      configurationMode
      confirmRegcardPrinter
      copies
      country
      countryCode
      countryName
      creditLimit
      currencyCode
      currencyDecimals
      currencyDescription
      currencyExgPaidout
      currencySymbol
      dSI
      dateForAging
      dateSeparator
      dblNum
      dblRate2
      dblRate1
      decimalPlaces
      decimalSeparator
      defaultCommissionPercentage
      defaultFaxType
      defaultFolioStyle
      defaultGroupsRateCode
      defaultGuestAddress
      defaultMembershipType
      defaultPostingRoom
      defaultPrepaidComm
      defaultPrinter
      defaultPropertyAddress
      defaultRateCode
      defaultRegistrationCard
      defaultReservationType
      defaultTrxCommissionCode
      depositLedgerTrxCode
      dfltPkgTranCode
      dfltTranCodeRateCode
      dirsales
      dutyManagerPager
      email
      endDate
      exchangePostingType
      expiryDate
      extPropertyCode
      fax
      faxNoFormat
      fileTransferFormat
      fiscalEndDate
      fiscalPeriodType
      fiscalStartDate
      fiscalStartMonth
      fiscalStartYear
      flowCode
      folioLanguage1
      folioLanguage2
      folioLanguage3
      folioLanguage4
      font
      footerLegalText1
      footerLegalText2
      footerLegalText3
      genmgr
      groupRoomWarning
      guarantorAddress
      guestLookupTimeout
      hotelFc
      hotelId
      hotelType
      iBAN
      imgDirectionId
      imgHotelId
      imgMapId
      inactiveDaysForGuestProfil
      individualAddressType
      individualPhoneType
      individualRoomWarning
      insertDate
      insertUser
      insurerAddressBody
      internalLocationId
      internalOrganizationId
      inventoryYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      keepAvailability
      layoutTemplate
      leadsend
      legalOwner
      licenseCode
      localCurrencyFormat
      locationID
      longDateFormat
      longStayControl
      marketingText
      maxNoNights
      maxOccupancy
      meetRooms
      meetSeats
      meetSpace
      meetingFc
      minDaysBet2ReminderLetter
      nameIdLink
      nightAuditCashierId
      notes
      numberBeds
      numberFloors
      numberRooms
      organizationID
      ownership
      packageLoss
      packageProfit
      passerbyMarket
      passerbySource
      perReservationRoomLimit
      postCode
      primaryKeyID
      property
      propertyName
      propertyType
      quotedCurrency
      rNAInsertDate
      rNAUpdateDate
      repPasserbyMarket
      repPasserbySource
      repState
      repStateDescription
      restaurant
      rhythmSheets
      rhythmTowels
      saveProfiles
      scriptId
      season1
      season2
      season3
      season4
      season5
      sglNum
      sglRate1
      sglRate2
      shortDateFormat
      sourceCommission
      state
      stateDesc
      street
      suiNum
      suiRate1
      suiRate2
      summCurrencyCode
      taCommission
      taxID
      telephone
      telephoneNoFormat
      thousandSeparator
      timeFormat
      tollfree
      totalRooms
      tplNum
      tplRate1
      tplRate2
      turnawayCode
      unitAddress
      unitBrand
      unitCity
      unitCountry
      unitCountryName
      unitFax
      unitMail
      unitName
      unitPhone
      unitType
      unitWeb
      unitZIP
      updateDate
      updateUser
      vAT1
      vAT10
      vAT11
      vAT12
      vAT13
      vAT14
      vAT15
      vAT16
      vAT17
      vAT18
      vAT19
      vAT2
      vAT20
      vAT3
      vAT4
      vAT5
      vAT6
      vAT7
      vAT8
      vAT9
      videoCoStart
      videoCoStop
      videocheckoutPrinter
      wakeUpDelay
      warningAmount
      webaddress
      weekendDays
      zeroInvPurDays
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
    profileAddressDetails {
      address1
      address2
      address3
      address4
      addressID
      addressLanguage
      addressLanguageDescription
      addressType
      addressTypeDesc
      barcode
      beginDate
      centralState
      centralStateDescription
      chainCode
      city
      cleansedDatetime
      cleansedErrormsg
      cleansedMatchstatus
      cleansedStatus
      cleansedValidationstatus
      clientID
      countryCode
      countryDescription
      createdByUser
      createdOnDate
      dSI
      deletedYN
      endDate
      firstName
      foreignCountry
      inCareOf
      inactiveDate
      inactiveYN
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      lastUpdatedResort
      name
      organizationID
      postalCode
      postalCodeExtension
      primaryKeyID
      primaryYN
      profileAddressId
      profileId
      profileIdx
      province
      rnaInsertDate
      rnaUpdateDate
      state
      stateCode
      updateDate
      updateUser
    }
    profileCommunicationDetails {
      addressId
      beginDate
      chainCode
      communicationID
      communicationRole
      communicationValue
      countryCode
      countryDialingCode
      countryId
      dSI
      defaultMethodYN
      deletedFlag
      displaySequence
      emailFormat
      emailLanguage
      endDate
      extension
      firstName
      inactiveDate
      inactiveFlag
      indexPhone
      insertDate
      insertUser
      internalOrganizationId
      internalProfileId
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      lastName
      mobileAudioKeyYn
      organizationID
      phoneId
      phoneType
      phoneTypeDescription
      phoneTypeId
      primaryKeyID
      primaryYN
      profileID
      rnaInsertDate
      rnaUpdateDate
      shareEmailYn
      updateDate
      updateUser
      validYn
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
    exportMapEfolioExportDetails {
      chainCode
      codeCanDeleteYn
      codeInsertDate
      codeInsertUser
      codeInsertUserName
      codeUpdateDate
      codeUpdateUser
      codeUpdateUserName
      combinedMappingYn
      configType
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
      mappedToDesc
      mappingCode
      mappingCodeDescription
      mappingType
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
      typeDesc
      typeInsertDate
      typeInsertUser
      typeInsertUserName
      typeUpdateDate
      typeUpdateUser
      typeUpdateUserName
      useLovYn
    }
  }
}
```

## Polars Schema
> Polars data types based on the GraphQL specification to prevent schema inference errors when writing the output Parquet file.
  
```python
import polars as pl

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
    'dSI': pl.Float64,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
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

folio_transactions_details_schema = {
    'aRChargeTransferYN': pl.Utf8,
    'aSBFlag': pl.Utf8,
    'aSBOnlyPostTaxesOnceYn': pl.Utf8,
    'aSBTaxFlag': pl.Utf8,
    'accountCode': pl.Float64,
    'accountTypeFlag': pl.Utf8,
    'accountid': pl.Float64,
    'address1': pl.Utf8,
    'addresseeNameId': pl.Float64,
    'adjustmentflag': pl.Utf8,
    'advGenerateAdjustment': pl.Utf8,
    'advanceBillReversedYn': pl.Utf8,
    'advanceBillYn': pl.Utf8,
    'advanceGenerateTrxCode': pl.Utf8,
    'advancedGenerateYn': pl.Utf8,
    'advgentranscodeid': pl.Utf8,
    'approvalCode': pl.Utf8,
    'approvalDate': pl.Utf8,
    'approvalStatus': pl.Utf8,
    'arLedgerCredit': pl.Float64,
    'arLedgerDebit': pl.Float64,
    'arNumber': pl.Float64,
    'arState': pl.Utf8,
    'arTransferDate': pl.Utf8,
    'archargetransferflag': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'arrangementDescription': pl.Utf8,
    'arrangementId': pl.Float64,
    'articleId': pl.Float64,
    'associatedBillDate': pl.Utf8,
    'associatedBillNo': pl.Utf8,
    'associatedFiscalBillDate': pl.Utf8,
    'associatedFiscalBillNo': pl.Utf8,
    'associatedFiscalBillTime': pl.Utf8,
    'associatedReceiptNo': pl.Float64,
    'associatedSeqNumber': pl.Float64,
    'associatedTrxNumber': pl.Float64,
    'authemployeeid': pl.Float64,
    'authorizerId': pl.Float64,
    'autoCreditbillYn': pl.Utf8,
    'autoSettleYn': pl.Utf8,
    'billGenerationDate': pl.Utf8,
    'billGenerationTime': pl.Utf8,
    'billNo': pl.Float64,
    'billPaymentTrxNumber': pl.Float64,
    'billPrefix': pl.Utf8,
    'billSeqNumber': pl.Float64,
    'billStartDate': pl.Utf8,
    'bonusCheckId': pl.Float64,
    'bucketCode': pl.Utf8,
    'bucketRedempYn': pl.Utf8,
    'businessDate': pl.Utf8,
    'businessId': pl.Utf8,
    'cARLedgerCredit': pl.Float64,
    'cARLedgerDebit': pl.Float64,
    'cCashierCredit': pl.Float64,
    'cCashierDebit': pl.Float64,
    'cCashierOpeningBalance': pl.Float64,
    'cCashpay': pl.Float64,
    'cCcTransactionFeeAmount': pl.Float64,
    'cCcpay': pl.Float64,
    'cChangeDue': pl.Float64,
    'cClarpay': pl.Float64,
    'cClpay': pl.Float64,
    'cCollectionTax1': pl.Float64,
    'cCollectionTax2': pl.Float64,
    'cCollectionTax3': pl.Float64,
    'cCollectionTax4': pl.Float64,
    'cCollectionTax5': pl.Float64,
    'cContractGrossAmount': pl.Float64,
    'cContractGuestCredit': pl.Float64,
    'cContractGuestDebit': pl.Float64,
    'cContractNetAmount': pl.Float64,
    'cDailyRunningTotal': pl.Float64,
    'cDepLedgerCredit': pl.Float64,
    'cDepLedgerDebit': pl.Float64,
    'cDeposit': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFiscalInvoiceCurrencyRate': pl.Float64,
    'cForexCommissionAmount': pl.Float64,
    'cGuestAccountCredit': pl.Float64,
    'cGuestAccountDebit': pl.Float64,
    'cInHouseCredit': pl.Float64,
    'cInHouseDebit': pl.Float64,
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
    'cNonRevenueAmount': pl.Float64,
    'cOrganizationARLedgerDebit': pl.Float64,
    'cOrganizationPostedAmount': pl.Float64,
    'cPackageAllowance': pl.Float64,
    'cPackageCredit': pl.Float64,
    'cPackageDebit': pl.Float64,
    'cPaidout': pl.Float64,
    'cParallelGrossAmount': pl.Float64,
    'cParallelGuestCredit': pl.Float64,
    'cParallelGuestDebit': pl.Float64,
    'cParallelNetAmount': pl.Float64,
    'cPaymentSurchargeAmount': pl.Float64,
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
    'cPostedAmount': pl.Float64,
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
    'cRevenueAmount': pl.Float64,
    'cTax1Amount': pl.Float64,
    'cTax1Rate': pl.Float64,
    'cTax2Amount': pl.Float64,
    'cTax2Rate': pl.Float64,
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
    'cTaxRate': pl.Float64,
    'cTax10Amount': pl.Float64,
    'cTax10Rate': pl.Float64,
    'cTax11Amount': pl.Float64,
    'cTax11Rate': pl.Float64,
    'cTax12Amount': pl.Float64,
    'cTax12Rate': pl.Float64,
    'cTax13Amount': pl.Float64,
    'cTax13Rate': pl.Float64,
    'cTax14Amount': pl.Float64,
    'cTax14Rate': pl.Float64,
    'cTax15Amount': pl.Float64,
    'cTax15Rate': pl.Float64,
    'cTax16Amount': pl.Float64,
    'cTax16Rate': pl.Float64,
    'cTax17Amount': pl.Float64,
    'cTax17Rate': pl.Float64,
    'cTax18Amount': pl.Float64,
    'cTax18Rate': pl.Float64,
    'cTax19Amount': pl.Float64,
    'cTax19Rate': pl.Float64,
    'cTax20Amount': pl.Float64,
    'cTax20Rate': pl.Float64,
    'cTax3Amount': pl.Float64,
    'cTax3Rate': pl.Float64,
    'cTax4Amount': pl.Float64,
    'cTax4Rate': pl.Float64,
    'cTax5Amount': pl.Float64,
    'cTax5Rate': pl.Float64,
    'cTax6Amount': pl.Float64,
    'cTax6Rate': pl.Float64,
    'cTax7Amount': pl.Float64,
    'cTax7Rate': pl.Float64,
    'cTax8Amount': pl.Float64,
    'cTax8Rate': pl.Float64,
    'cTax9Amount': pl.Float64,
    'cTax9Rate': pl.Float64,
    'cTotalGross': pl.Float64,
    'cTotalNet': pl.Float64,
    'cTotalNonTaxable': pl.Float64,
    'cTotalNonrevNonTaxable': pl.Float64,
    'cTotalNonrevTaxable': pl.Float64,
    'cTotalRevenueNonTaxable': pl.Float64,
    'cTotalRevenueTaxable': pl.Float64,
    'cTotalTax': pl.Float64,
    'cTransactionAmount': pl.Float64,
    'cTrialBalanceAmountGross': pl.Float64,
    'cTrialBalanceAmountNet': pl.Float64,
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
    'calcmemberpointsflag': pl.Utf8,
    'cashRegisterId': pl.Utf8,
    'cashRegisterInvNumber': pl.Float64,
    'cashierCredit': pl.Float64,
    'cashierDebit': pl.Float64,
    'cashierId': pl.Float64,
    'cashierOpeningBalance': pl.Float64,
    'cashpay': pl.Float64,
    'ccRefundPosting': pl.Utf8,
    'ccTrxFeeAmount': pl.Float64,
    'ccpay': pl.Float64,
    'centralGrossAmount': pl.Float64,
    'centralNetAmount': pl.Float64,
    'centralPaymentAmount': pl.Float64,
    'centralPrice': pl.Float64,
    'centralTaxAmount': pl.Float64,
    'centralTaxCode': pl.Utf8,
    'centralTaxCodeDescription': pl.Utf8,
    'centralTransactionAmount': pl.Float64,
    'centralTransactionCode': pl.Utf8,
    'centralTransactionDescription': pl.Utf8,
    'centralTransactionGroupCode': pl.Utf8,
    'centralTransactionGroupDescription': pl.Utf8,
    'centralTransactionSubGroupCode': pl.Utf8,
    'centralTransactionSubGroupDescription': pl.Utf8,
    'changeDue': pl.Float64,
    'checkFileId': pl.Utf8,
    'checkNumber': pl.Utf8,
    'city': pl.Utf8,
    'cityLedgerYn': pl.Utf8,
    'clTrxNumber': pl.Float64,
    'clarpay': pl.Float64,
    'closureNo': pl.Float64,
    'clpay': pl.Float64,
    'collectionAgentPostingYn': pl.Utf8,
    'collectionTax1': pl.Float64,
    'collectionTax2': pl.Float64,
    'collectionTax3': pl.Float64,
    'collectionTax4': pl.Float64,
    'collectionTax5': pl.Float64,
    'comments': pl.Utf8,
    'compLinkTrxCode': pl.Utf8,
    'compLinkTrxNumber': pl.Float64,
    'compTypeCode': pl.Utf8,
    'companyFinancialValue': pl.Utf8,
    'companyName': pl.Utf8,
    'companyType': pl.Utf8,
    'complinktranscodeid': pl.Utf8,
    'compressBillNo': pl.Utf8,
    'compressedYn': pl.Utf8,
    'contractCurrency': pl.Utf8,
    'contractGrossAmount': pl.Float64,
    'contractGuestCredit': pl.Float64,
    'contractGuestDebit': pl.Float64,
    'contractNetAmount': pl.Float64,
    'contractforeigncurrencyid': pl.Utf8,
    'correctionYn': pl.Utf8,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'couponNo': pl.Utf8,
    'covers': pl.Utf8,
    'creditBillGeneratedYn': pl.Utf8,
    'creditBillNo': pl.Float64,
    'creditCardId': pl.Float64,
    'currency': pl.Utf8,
    'dSI': pl.Float64,
    'dailyRunningTotal': pl.Float64,
    'debitOrCredit': pl.Utf8,
    'deferredYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depLedgerCredit': pl.Float64,
    'depLedgerDebit': pl.Float64,
    'depPostingFlag': pl.Utf8,
    'depTaxTransferedYn': pl.Utf8,
    'deposit': pl.Float64,
    'depositReqReceiptNo': pl.Float64,
    'depositTransactionId': pl.Utf8,
    'depositlinkfintransid': pl.Float64,
    'displayflag': pl.Utf8,
    'documentCode': pl.Utf8,
    'documentType': pl.Utf8,
    'eArchiveEttnNumber': pl.Utf8,
    'eArchiveNumber': pl.Utf8,
    'eArchiveReportNo': pl.Utf8,
    'eArchiveStatus': pl.Utf8,
    'eInvoiceNumber': pl.Utf8,
    'eInvoiceStatus': pl.Utf8,
    'effectiveDate': pl.Utf8,
    'electronicVoucherNo': pl.Float64,
    'esignedReceiptName': pl.Utf8,
    'euroExchangeRate': pl.Float64,
    'exchDifferenceTrxNumber': pl.Float64,
    'exchangeDate': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exchangeType': pl.Utf8,
    'exchangedifferenceflag': pl.Utf8,
    'expInvoiceType': pl.Utf8,
    'expOriginalInvoice': pl.Utf8,
    'extSysResultMsg': pl.Utf8,
    'extTransactionId': pl.Utf8,
    'fbaCertificateNumber': pl.Utf8,
    'filterChar1': pl.Utf8,
    'filterChar2': pl.Utf8,
    'filterChar3': pl.Utf8,
    'filterChar4': pl.Utf8,
    'filterChar5': pl.Utf8,
    'finBillNumber': pl.Float64,
    'finBusinessDate': pl.Utf8,
    'finCountry': pl.Utf8,
    'finDeletedFlag': pl.Utf8,
    'finFiscalBillNumber': pl.Utf8,
    'finFolioView': pl.Float64,
    'finInsertDate': pl.Utf8,
    'finInsertUser': pl.Float64,
    'finInvoiceNumber': pl.Float64,
    'finNameTaxType': pl.Utf8,
    'finPkid': pl.Float64,
    'finPostitNumber': pl.Float64,
    'finPropertyBillPrefix': pl.Utf8,
    'finQueueName': pl.Utf8,
    'finRevisionNumber': pl.Float64,
    'finRoom': pl.Utf8,
    'finUpdateDate': pl.Utf8,
    'finUpdateUser': pl.Float64,
    'financialCExchangeDate': pl.Utf8,
    'financialCExchangeRate': pl.Float64,
    'financialCashierId': pl.Float64,
    'financialDmlSeqNumber': pl.Float64,
    'financialForexTaxYN': pl.Utf8,
    'financialNameId': pl.Float64,
    'financialPostitYN': pl.Utf8,
    'financialReservationNameId': pl.Float64,
    'fintransactionid': pl.Float64,
    'fintransid': pl.Float64,
    'first': pl.Utf8,
    'fiscalBillCheckDigit': pl.Float64,
    'fiscalBillGenerationDate': pl.Utf8,
    'fiscalBillGenerationTime': pl.Utf8,
    'fiscalBillNo': pl.Utf8,
    'fiscalInvoiceCurrency': pl.Utf8,
    'fiscalInvoiceCurrencyRate': pl.Float64,
    'fiscalSessionNo': pl.Utf8,
    'fiscalTrxCodeType': pl.Utf8,
    'fiscalUnitControlCode': pl.Utf8,
    'fixedchargesflag': pl.Utf8,
    'folioAddress': pl.Utf8,
    'folioAddressCorrectedYn': pl.Utf8,
    'folioAttachmentLinkId': pl.Float64,
    'folioAttachmentStatus': pl.Float64,
    'folioNo': pl.Float64,
    'folioStyle': pl.Utf8,
    'folioTaxSeqNumber': pl.Float64,
    'folioType': pl.Utf8,
    'folioType1': pl.Utf8,
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
    'fullFolioNo': pl.Utf8,
    'genCashierId': pl.Float64,
    'gpAwardCancelCode': pl.Utf8,
    'gpAwardCode': pl.Utf8,
    'grossAmount': pl.Float64,
    'groupAwardCancelledYN': pl.Utf8,
    'guestAccountCredit': pl.Float64,
    'guestAccountDebit': pl.Float64,
    'hasWatermarkYn': pl.Utf8,
    'hotelAcct': pl.Utf8,
    'hotelName': pl.Utf8,
    'incTaxDeductedYn': pl.Utf8,
    'inclusiveTaxYN': pl.Utf8,
    'individualAdjustmentYN': pl.Utf8,
    'inhCredit': pl.Float64,
    'inhDebit': pl.Float64,
    'insTimestamp': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'insertUserName': pl.Utf8,
    'installments': pl.Float64,
    'internalArticleid': pl.Float64,
    'internalBusinessdate': pl.Utf8,
    'internalCashierid': pl.Float64,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNo': pl.Float64,
    'invoiceType': pl.Utf8,
    'iscreditflag': pl.Utf8,
    'isdebitflag': pl.Utf8,
    'isinternalflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'last': pl.Utf8,
    'lastSignatureHash': pl.Utf8,
    'linkTrxNumber': pl.Float64,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketid': pl.Utf8,
    'membershipid': pl.Float64,
    'mtrxNoAgainstPackage': pl.Float64,
    'nafApeHotelCode': pl.Utf8,
    'nameId': pl.Float64,
    'nameTaxType': pl.Utf8,
    'nameTypeDescription': pl.Utf8,
    'netAmount': pl.Float64,
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
    'nrBusinessId': pl.Utf8,
    'numberDialed': pl.Utf8,
    'numberOfPages': pl.Float64,
    'oTransactionDesc': pl.Utf8,
    'onholdflag': pl.Utf8,
    'operaFiscalFolioStatus': pl.Utf8,
    'orgBillNumber': pl.Float64,
    'orgFolioType': pl.Utf8,
    'orgPostedAmount': pl.Float64,
    'organizationArLedgerDebit': pl.Float64,
    'organizationID': pl.Float64,
    'originalReservationNameID': pl.Float64,
    'originalRoom': pl.Utf8,
    'originalresvid': pl.Float64,
    'packageAllowance': pl.Float64,
    'packageArrangementCode': pl.Utf8,
    'packageCredit': pl.Float64,
    'packageDebit': pl.Float64,
    'packageTrxType': pl.Utf8,
    'packagelinkfintransid': pl.Float64,
    'pageNumber': pl.Float64,
    'paidout': pl.Float64,
    'palmVideoFlag': pl.Utf8,
    'parallelCurrency': pl.Utf8,
    'parallelGrossAmount': pl.Float64,
    'parallelGuestCredit': pl.Float64,
    'parallelGuestDebit': pl.Float64,
    'parallelNetAmount': pl.Float64,
    'parallelforeigncurrencyid': pl.Utf8,
    'parentfintransid': pl.Float64,
    'partnerFiscalFolioStatus': pl.Utf8,
    'passerByName': pl.Utf8,
    'payeeName': pl.Utf8,
    'payeeNameId': pl.Float64,
    'payeeZipCode': pl.Utf8,
    'paymentAmount': pl.Float64,
    'paymentDate': pl.Utf8,
    'paymentDescription': pl.Utf8,
    'paymentSurchargeAmt': pl.Float64,
    'paymentSurchargeType': pl.Utf8,
    'paymentTrxDate': pl.Utf8,
    'paymentType': pl.Utf8,
    'percentage': pl.Float64,
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
    'postedAmount': pl.Float64,
    'postingDate': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingSourceNameId': pl.Float64,
    'postingType': pl.Utf8,
    'postitNo': pl.Float64,
    'postitYn': pl.Utf8,
    'price': pl.Float64,
    'primaryKeyID': pl.Float64,
    'processed8300flag': pl.Utf8,
    'product': pl.Utf8,
    'productid': pl.Utf8,
    'profileid': pl.Float64,
    'profitLossFlag': pl.Utf8,
    'proformaYn': pl.Utf8,
    'promotionalText1': pl.Utf8,
    'promotionalText2': pl.Utf8,
    'property': pl.Utf8,
    'propertyBillPrefix': pl.Utf8,
    'propertyTaxNo': pl.Utf8,
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
    'quantity': pl.Float64,
    'queueName': pl.Utf8,
    'rateCode': pl.Utf8,
    'ratecodeid': pl.Utf8,
    'realPerpetualAmount': pl.Float64,
    'reasonCode': pl.Utf8,
    'receiptNo': pl.Float64,
    'receiptType': pl.Utf8,
    'reference': pl.Utf8,
    'reservationDepositId': pl.Float64,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'resortCity': pl.Utf8,
    'resortCountry': pl.Utf8,
    'resortFullAddress': pl.Utf8,
    'resortZipcodeCode': pl.Utf8,
    'resvenddate': pl.Utf8,
    'revenueAmt': pl.Float64,
    'reversePaymentTrxNumber': pl.Float64,
    'revisionNo': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
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
    'seqNumber': pl.Float64,
    'serviceRecoveryAdjustmentYn': pl.Utf8,
    'serviceRecoveryDeptCode': pl.Utf8,
    'serviceTypeCode': pl.Utf8,
    'settlementFlag': pl.Utf8,
    'signatureHash': pl.Utf8,
    'signatureKeyVersion': pl.Utf8,
    'softwareVersion': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceCommissionNetYn': pl.Utf8,
    'sourceid': pl.Utf8,
    'splitType': pl.Utf8,
    'status': pl.Utf8,
    'supplement': pl.Utf8,
    'taCommissionNetYn': pl.Utf8,
    'tacommissionableflag': pl.Utf8,
    'targetResort': pl.Utf8,
    'targetlocationid': pl.Utf8,
    'tax1Amt': pl.Float64,
    'tax1No': pl.Utf8,
    'tax1Rate': pl.Float64,
    'tax1RateType': pl.Utf8,
    'tax2Amt': pl.Float64,
    'tax2No': pl.Utf8,
    'tax2Rate': pl.Float64,
    'tax2RateType': pl.Utf8,
    'taxAmount': pl.Float64,
    'taxCode': pl.Utf8,
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
    'taxCodeDescription': pl.Utf8,
    'taxCodeNumber': pl.Float64,
    'taxElements': pl.Utf8,
    'taxId': pl.Utf8,
    'taxInvNumber': pl.Utf8,
    'taxRate': pl.Float64,
    'taxRateType': pl.Utf8,
    'tax10Amt': pl.Float64,
    'tax10Rate': pl.Float64,
    'tax10RateType': pl.Utf8,
    'tax11Amt': pl.Float64,
    'tax11Rate': pl.Float64,
    'tax11RateType': pl.Utf8,
    'tax12Amt': pl.Float64,
    'tax12Rate': pl.Float64,
    'tax12RateType': pl.Utf8,
    'tax13Amt': pl.Float64,
    'tax13Rate': pl.Float64,
    'tax13RateType': pl.Utf8,
    'tax14Amt': pl.Float64,
    'tax14Rate': pl.Float64,
    'tax14RateType': pl.Utf8,
    'tax15Amt': pl.Float64,
    'tax15Rate': pl.Float64,
    'tax15RateType': pl.Utf8,
    'tax16Amt': pl.Float64,
    'tax16Rate': pl.Float64,
    'tax16RateType': pl.Utf8,
    'tax17Amt': pl.Float64,
    'tax17Rate': pl.Float64,
    'tax17RateType': pl.Utf8,
    'tax18Amt': pl.Float64,
    'tax18Rate': pl.Float64,
    'tax18RateType': pl.Utf8,
    'tax19Amt': pl.Float64,
    'tax19Rate': pl.Float64,
    'tax19RateType': pl.Utf8,
    'tax20Amt': pl.Float64,
    'tax20Rate': pl.Float64,
    'tax20RateType': pl.Utf8,
    'tax3Amt': pl.Float64,
    'tax3Rate': pl.Float64,
    'tax3RateType': pl.Utf8,
    'tax4Amt': pl.Float64,
    'tax4Rate': pl.Float64,
    'tax4RateType': pl.Utf8,
    'tax5Amt': pl.Float64,
    'tax5Rate': pl.Float64,
    'tax5RateType': pl.Utf8,
    'tax6Amt': pl.Float64,
    'tax6Rate': pl.Float64,
    'tax6RateType': pl.Utf8,
    'tax7Amt': pl.Float64,
    'tax7Rate': pl.Float64,
    'tax7RateType': pl.Utf8,
    'tax8Amt': pl.Float64,
    'tax8Rate': pl.Float64,
    'tax8RateType': pl.Utf8,
    'tax9Amt': pl.Float64,
    'tax9Rate': pl.Float64,
    'tax9RateType': pl.Utf8,
    'taxdeferredflag': pl.Utf8,
    'taxgeneratedflag': pl.Utf8,
    'tclCode1': pl.Utf8,
    'tclCode2': pl.Utf8,
    'terminal': pl.Utf8,
    'thresholdDiversionId': pl.Float64,
    'thresholdEntityQty': pl.Float64,
    'thresholdEntityType': pl.Utf8,
    'thresholdTreatmentFlag': pl.Utf8,
    'toReservationNameId': pl.Float64,
    'totalGross': pl.Float64,
    'totalNet': pl.Float64,
    'totalNonTaxable': pl.Float64,
    'totalNonrevNonTaxable': pl.Float64,
    'totalNonrevTaxable': pl.Float64,
    'totalRevNonTaxable': pl.Float64,
    'totalRevTaxable': pl.Float64,
    'totalTax': pl.Float64,
    'tranActionId': pl.Float64,
    'transactLastSignatureHash': pl.Utf8,
    'transactSignatureHash': pl.Utf8,
    'transactSignatureKeyVersion': pl.Utf8,
    'transactionAmount': pl.Float64,
    'transactionCode': pl.Utf8,
    'transactionDate': pl.Utf8,
    'transactionDescription': pl.Utf8,
    'transactionFromAcct': pl.Float64,
    'transactionGroupCode': pl.Utf8,
    'transactionGroupDescription': pl.Utf8,
    'transactionID': pl.Float64,
    'transactionSignature': pl.Utf8,
    'transactionSubGroupCode': pl.Utf8,
    'transactionSubGroupDescription': pl.Utf8,
    'transactionToAcct': pl.Float64,
    'transactionType': pl.Utf8,
    'transcodearrangementid': pl.Float64,
    'transcodeid': pl.Utf8,
    'transferfromaccountid': pl.Float64,
    'transferfromresvid': pl.Float64,
    'transfertoaccountid': pl.Float64,
    'transfertoresvid': pl.Float64,
    'trialBalanceAmountGross': pl.Float64,
    'trialBalanceAmountNet': pl.Float64,
    'trnsActivityDate': pl.Utf8,
    'trxAmount': pl.Float64,
    'trxNumberAddedBy': pl.Float64,
    'trxNumberAdjust': pl.Float64,
    'trxNumberHeader': pl.Float64,
    'trxNumberSplit': pl.Float64,
    'trxServiceType': pl.Utf8,
    'trxTime': pl.Utf8,
    'trxType': pl.Utf8,
    'udfc01': pl.Utf8,
    'udfc02': pl.Utf8,
    'udfc03': pl.Utf8,
    'udfc04': pl.Utf8,
    'udfc05': pl.Utf8,
    'udfc06': pl.Utf8,
    'udfc07': pl.Utf8,
    'udfc08': pl.Utf8,
    'udfc09': pl.Utf8,
    'udfc10': pl.Utf8,
    'udfc11': pl.Utf8,
    'udfc12': pl.Utf8,
    'udfc13': pl.Utf8,
    'udfc14': pl.Utf8,
    'udfc15': pl.Utf8,
    'udfc16': pl.Utf8,
    'udfc17': pl.Utf8,
    'udfc18': pl.Utf8,
    'udfc19': pl.Utf8,
    'udfc20': pl.Utf8,
    'udfc21': pl.Utf8,
    'udfc22': pl.Utf8,
    'udfc23': pl.Utf8,
    'udfc24': pl.Utf8,
    'udfc25': pl.Utf8,
    'udfc26': pl.Utf8,
    'udfc27': pl.Utf8,
    'udfc28': pl.Utf8,
    'udfc29': pl.Utf8,
    'udfc30': pl.Utf8,
    'udfc31': pl.Utf8,
    'udfc32': pl.Utf8,
    'udfc33': pl.Utf8,
    'udfc34': pl.Utf8,
    'udfc35': pl.Utf8,
    'udfc36': pl.Utf8,
    'udfc37': pl.Utf8,
    'udfc38': pl.Utf8,
    'udfc39': pl.Utf8,
    'udfc40': pl.Utf8,
    'udfd01': pl.Utf8,
    'udfd02': pl.Utf8,
    'udfd03': pl.Utf8,
    'udfd04': pl.Utf8,
    'udfd05': pl.Utf8,
    'udfd06': pl.Utf8,
    'udfd07': pl.Utf8,
    'udfd08': pl.Utf8,
    'udfd09': pl.Utf8,
    'udfd10': pl.Utf8,
    'udfd11': pl.Utf8,
    'udfd12': pl.Utf8,
    'udfd13': pl.Utf8,
    'udfd14': pl.Utf8,
    'udfd15': pl.Utf8,
    'udfd16': pl.Utf8,
    'udfd17': pl.Utf8,
    'udfd18': pl.Utf8,
    'udfd19': pl.Utf8,
    'udfd20': pl.Utf8,
    'udfn01': pl.Float64,
    'udfn02': pl.Float64,
    'udfn03': pl.Float64,
    'udfn04': pl.Float64,
    'udfn05': pl.Float64,
    'udfn06': pl.Float64,
    'udfn07': pl.Float64,
    'udfn08': pl.Float64,
    'udfn09': pl.Float64,
    'udfn10': pl.Float64,
    'udfn11': pl.Float64,
    'udfn12': pl.Float64,
    'udfn13': pl.Float64,
    'udfn14': pl.Float64,
    'udfn15': pl.Float64,
    'udfn16': pl.Float64,
    'udfn17': pl.Float64,
    'udfn18': pl.Float64,
    'udfn19': pl.Float64,
    'udfn20': pl.Float64,
    'udfn21': pl.Float64,
    'udfn22': pl.Float64,
    'udfn23': pl.Float64,
    'udfn24': pl.Float64,
    'udfn25': pl.Float64,
    'udfn26': pl.Float64,
    'udfn27': pl.Float64,
    'udfn28': pl.Float64,
    'udfn29': pl.Float64,
    'udfn30': pl.Float64,
    'udfn31': pl.Float64,
    'udfn32': pl.Float64,
    'udfn33': pl.Float64,
    'udfn34': pl.Float64,
    'udfn35': pl.Float64,
    'udfn36': pl.Float64,
    'udfn37': pl.Float64,
    'udfn38': pl.Float64,
    'udfn39': pl.Float64,
    'udfn40': pl.Float64,
    'updTimestamp': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'upsellChargeYn': pl.Utf8,
    'vatOffsetYn': pl.Utf8,
    'voidNo': pl.Float64,
    'voidReason': pl.Utf8,
    'workingDocId': pl.Float64,
    'wrapperTransactionID': pl.Float64,
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
    'zipCode': pl.Utf8,
}

property_export_values_details_schema = {
    'aRAccountNumberMandYN': pl.Utf8,
    'aRBalanceTrxCode': pl.Utf8,
    'aRCreditTrxCode': pl.Utf8,
    'additionalLogos': pl.Utf8,
    'address': pl.Utf8,
    'agingLevel1': pl.Float64,
    'agingLevel2': pl.Float64,
    'agingLevel3': pl.Float64,
    'agingLevel4': pl.Float64,
    'agingLevel5': pl.Float64,
    'airport': pl.Utf8,
    'airportDistance': pl.Utf8,
    'airportTime': pl.Utf8,
    'allowLoginYn': pl.Utf8,
    'allowancePeriodAdj': pl.Utf8,
    'arAccountNumberFormat': pl.Utf8,
    'arAgent': pl.Utf8,
    'arCompany': pl.Utf8,
    'arGroups': pl.Utf8,
    'arIndividuals': pl.Utf8,
    'arSettleCode': pl.Utf8,
    'arTypewriter': pl.Utf8,
    'awardsTimeout': pl.Float64,
    'bIC': pl.Utf8,
    'bankAgencyCode': pl.Utf8,
    'bankAgencyName': pl.Utf8,
    'bankCode': pl.Utf8,
    'bankName': pl.Utf8,
    'baseLanguage': pl.Utf8,
    'beginDate': pl.Utf8,
    'block': pl.Utf8,
    'brArea': pl.Utf8,
    'brSeats': pl.Float64,
    'brandCode': pl.Utf8,
    'budgetMonth': pl.Float64,
    'cROCode': pl.Utf8,
    'cRSResort': pl.Utf8,
    'cashShiftDrop': pl.Utf8,
    'centralPropertyType': pl.Utf8,
    'chainCode': pl.Utf8,
    'chainDescription': pl.Utf8,
    'checkExgPaidout': pl.Utf8,
    'checkInTime': pl.Utf8,
    'checkOutTime': pl.Utf8,
    'checkShiftDrop': pl.Utf8,
    'checkTrxcode': pl.Utf8,
    'city': pl.Utf8,
    'cityDescription': pl.Utf8,
    'clientBookingReference': pl.Utf8,
    'comAddress': pl.Utf8,
    'comMethod': pl.Utf8,
    'company': pl.Utf8,
    'companyAddressType': pl.Utf8,
    'companyCapitalAmount': pl.Utf8,
    'companyCity': pl.Utf8,
    'companyCountryName': pl.Utf8,
    'companyIMOBody': pl.Utf8,
    'companyLegalText': pl.Utf8,
    'companyNAF': pl.Utf8,
    'companyPhoneType': pl.Utf8,
    'companyRCS': pl.Utf8,
    'companySiret': pl.Utf8,
    'companyTypeBody': pl.Utf8,
    'configurationMode': pl.Utf8,
    'confirmRegcardPrinter': pl.Utf8,
    'copies': pl.Float64,
    'country': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryName': pl.Utf8,
    'creditLimit': pl.Float64,
    'currencyCode': pl.Utf8,
    'currencyDecimals': pl.Float64,
    'currencyDescription': pl.Utf8,
    'currencyExgPaidout': pl.Utf8,
    'currencySymbol': pl.Utf8,
    'dSI': pl.Float64,
    'dateForAging': pl.Utf8,
    'dateSeparator': pl.Utf8,
    'dblNum': pl.Utf8,
    'dblRate2': pl.Float64,
    'dblRate1': pl.Float64,
    'decimalPlaces': pl.Float64,
    'decimalSeparator': pl.Utf8,
    'defaultCommissionPercentage': pl.Utf8,
    'defaultFaxType': pl.Utf8,
    'defaultFolioStyle': pl.Float64,
    'defaultGroupsRateCode': pl.Utf8,
    'defaultGuestAddress': pl.Utf8,
    'defaultMembershipType': pl.Utf8,
    'defaultPostingRoom': pl.Utf8,
    'defaultPrepaidComm': pl.Utf8,
    'defaultPrinter': pl.Utf8,
    'defaultPropertyAddress': pl.Utf8,
    'defaultRateCode': pl.Utf8,
    'defaultRegistrationCard': pl.Utf8,
    'defaultReservationType': pl.Utf8,
    'defaultTrxCommissionCode': pl.Utf8,
    'depositLedgerTrxCode': pl.Utf8,
    'dfltPkgTranCode': pl.Utf8,
    'dfltTranCodeRateCode': pl.Utf8,
    'dirsales': pl.Utf8,
    'dutyManagerPager': pl.Utf8,
    'email': pl.Utf8,
    'endDate': pl.Utf8,
    'exchangePostingType': pl.Utf8,
    'expiryDate': pl.Utf8,
    'extPropertyCode': pl.Utf8,
    'fax': pl.Utf8,
    'faxNoFormat': pl.Utf8,
    'fileTransferFormat': pl.Utf8,
    'fiscalEndDate': pl.Utf8,
    'fiscalPeriodType': pl.Utf8,
    'fiscalStartDate': pl.Utf8,
    'fiscalStartMonth': pl.Float64,
    'fiscalStartYear': pl.Float64,
    'flowCode': pl.Utf8,
    'folioLanguage1': pl.Utf8,
    'folioLanguage2': pl.Utf8,
    'folioLanguage3': pl.Utf8,
    'folioLanguage4': pl.Utf8,
    'font': pl.Float64,
    'footerLegalText1': pl.Utf8,
    'footerLegalText2': pl.Utf8,
    'footerLegalText3': pl.Utf8,
    'genmgr': pl.Utf8,
    'groupRoomWarning': pl.Float64,
    'guarantorAddress': pl.Utf8,
    'guestLookupTimeout': pl.Float64,
    'hotelFc': pl.Utf8,
    'hotelId': pl.Utf8,
    'hotelType': pl.Utf8,
    'iBAN': pl.Utf8,
    'imgDirectionId': pl.Float64,
    'imgHotelId': pl.Float64,
    'imgMapId': pl.Float64,
    'inactiveDaysForGuestProfil': pl.Float64,
    'individualAddressType': pl.Utf8,
    'individualPhoneType': pl.Utf8,
    'individualRoomWarning': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'insurerAddressBody': pl.Utf8,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'inventoryYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keepAvailability': pl.Float64,
    'layoutTemplate': pl.Utf8,
    'leadsend': pl.Utf8,
    'legalOwner': pl.Utf8,
    'licenseCode': pl.Utf8,
    'localCurrencyFormat': pl.Utf8,
    'locationID': pl.Utf8,
    'longDateFormat': pl.Utf8,
    'longStayControl': pl.Float64,
    'marketingText': pl.Utf8,
    'maxNoNights': pl.Float64,
    'maxOccupancy': pl.Float64,
    'meetRooms': pl.Float64,
    'meetSeats': pl.Float64,
    'meetSpace': pl.Float64,
    'meetingFc': pl.Utf8,
    'minDaysBet2ReminderLetter': pl.Float64,
    'nameIdLink': pl.Float64,
    'nightAuditCashierId': pl.Utf8,
    'notes': pl.Utf8,
    'numberBeds': pl.Float64,
    'numberFloors': pl.Float64,
    'numberRooms': pl.Float64,
    'organizationID': pl.Float64,
    'ownership': pl.Utf8,
    'packageLoss': pl.Utf8,
    'packageProfit': pl.Utf8,
    'passerbyMarket': pl.Utf8,
    'passerbySource': pl.Utf8,
    'perReservationRoomLimit': pl.Float64,
    'postCode': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'propertyName': pl.Utf8,
    'propertyType': pl.Utf8,
    'quotedCurrency': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repPasserbyMarket': pl.Utf8,
    'repPasserbySource': pl.Utf8,
    'repState': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'restaurant': pl.Float64,
    'rhythmSheets': pl.Float64,
    'rhythmTowels': pl.Float64,
    'saveProfiles': pl.Float64,
    'scriptId': pl.Float64,
    'season1': pl.Utf8,
    'season2': pl.Utf8,
    'season3': pl.Utf8,
    'season4': pl.Utf8,
    'season5': pl.Utf8,
    'sglNum': pl.Utf8,
    'sglRate1': pl.Float64,
    'sglRate2': pl.Float64,
    'shortDateFormat': pl.Utf8,
    'sourceCommission': pl.Utf8,
    'state': pl.Utf8,
    'stateDesc': pl.Utf8,
    'street': pl.Utf8,
    'suiNum': pl.Utf8,
    'suiRate1': pl.Float64,
    'suiRate2': pl.Float64,
    'summCurrencyCode': pl.Utf8,
    'taCommission': pl.Utf8,
    'taxID': pl.Utf8,
    'telephone': pl.Utf8,
    'telephoneNoFormat': pl.Utf8,
    'thousandSeparator': pl.Utf8,
    'timeFormat': pl.Utf8,
    'tollfree': pl.Utf8,
    'totalRooms': pl.Float64,
    'tplNum': pl.Utf8,
    'tplRate1': pl.Float64,
    'tplRate2': pl.Float64,
    'turnawayCode': pl.Utf8,
    'unitAddress': pl.Utf8,
    'unitBrand': pl.Utf8,
    'unitCity': pl.Utf8,
    'unitCountry': pl.Utf8,
    'unitCountryName': pl.Utf8,
    'unitFax': pl.Utf8,
    'unitMail': pl.Utf8,
    'unitName': pl.Utf8,
    'unitPhone': pl.Utf8,
    'unitType': pl.Utf8,
    'unitWeb': pl.Utf8,
    'unitZIP': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'vAT1': pl.Utf8,
    'vAT10': pl.Utf8,
    'vAT11': pl.Utf8,
    'vAT12': pl.Utf8,
    'vAT13': pl.Utf8,
    'vAT14': pl.Utf8,
    'vAT15': pl.Utf8,
    'vAT16': pl.Utf8,
    'vAT17': pl.Utf8,
    'vAT18': pl.Utf8,
    'vAT19': pl.Utf8,
    'vAT2': pl.Utf8,
    'vAT20': pl.Utf8,
    'vAT3': pl.Utf8,
    'vAT4': pl.Utf8,
    'vAT5': pl.Utf8,
    'vAT6': pl.Utf8,
    'vAT7': pl.Utf8,
    'vAT8': pl.Utf8,
    'vAT9': pl.Utf8,
    'videoCoStart': pl.Utf8,
    'videoCoStop': pl.Utf8,
    'videocheckoutPrinter': pl.Utf8,
    'wakeUpDelay': pl.Float64,
    'warningAmount': pl.Float64,
    'webaddress': pl.Utf8,
    'weekendDays': pl.Utf8,
    'zeroInvPurDays': pl.Float64,
}

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
    'dSI': pl.Float64,
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
    'organizationID': pl.Float64,
    'origNameId': pl.Float64,
    'paymentDueDays': pl.Float64,
    'phone': pl.Utf8,
    'phoneWeb': pl.Utf8,
    'phoneYN': pl.Utf8,
    'postalCode': pl.Utf8,
    'postalCodeExtension': pl.Utf8,
    'preferredRoomNo': pl.Utf8,
    'primaryAddressId': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Utf8,
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

profile_address_details_schema = {
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressID': pl.Float64,
    'addressLanguage': pl.Utf8,
    'addressLanguageDescription': pl.Utf8,
    'addressType': pl.Utf8,
    'addressTypeDesc': pl.Utf8,
    'barcode': pl.Utf8,
    'beginDate': pl.Utf8,
    'centralState': pl.Utf8,
    'centralStateDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cleansedDatetime': pl.Utf8,
    'cleansedErrormsg': pl.Utf8,
    'cleansedMatchstatus': pl.Utf8,
    'cleansedStatus': pl.Utf8,
    'cleansedValidationstatus': pl.Utf8,
    'clientID': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryDescription': pl.Utf8,
    'createdByUser': pl.Float64,
    'createdOnDate': pl.Utf8,
    'dSI': pl.Float64,
    'deletedYN': pl.Utf8,
    'endDate': pl.Utf8,
    'firstName': pl.Utf8,
    'foreignCountry': pl.Utf8,
    'inCareOf': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastUpdatedResort': pl.Utf8,
    'name': pl.Utf8,
    'organizationID': pl.Float64,
    'postalCode': pl.Utf8,
    'postalCodeExtension': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'primaryYN': pl.Utf8,
    'profileAddressId': pl.Float64,
    'profileId': pl.Float64,
    'profileIdx': pl.Float64,
    'province': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

profile_communication_details_schema = {
    'addressId': pl.Float64,
    'beginDate': pl.Utf8,
    'chainCode': pl.Utf8,
    'communicationID': pl.Float64,
    'communicationRole': pl.Utf8,
    'communicationValue': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryDialingCode': pl.Float64,
    'countryId': pl.Utf8,
    'dSI': pl.Float64,
    'defaultMethodYN': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'displaySequence': pl.Float64,
    'emailFormat': pl.Utf8,
    'emailLanguage': pl.Utf8,
    'endDate': pl.Utf8,
    'extension': pl.Utf8,
    'firstName': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'indexPhone': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalOrganizationId': pl.Float64,
    'internalProfileId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastName': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'organizationID': pl.Float64,
    'phoneId': pl.Float64,
    'phoneType': pl.Utf8,
    'phoneTypeDescription': pl.Utf8,
    'phoneTypeId': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'primaryYN': pl.Utf8,
    'profileID': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'shareEmailYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'validYn': pl.Utf8,
}

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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
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

export_map_efolio_export_details_schema = {
    'chainCode': pl.Utf8,
    'codeCanDeleteYn': pl.Utf8,
    'codeInsertDate': pl.Utf8,
    'codeInsertUser': pl.Float64,
    'codeInsertUserName': pl.Utf8,
    'codeUpdateDate': pl.Utf8,
    'codeUpdateUser': pl.Float64,
    'codeUpdateUserName': pl.Utf8,
    'combinedMappingYn': pl.Utf8,
    'configType': pl.Utf8,
    'dSI': pl.Float64,
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
    'mappedToDesc': pl.Utf8,
    'mappingCode': pl.Utf8,
    'mappingCodeDescription': pl.Utf8,
    'mappingType': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'requiredYn': pl.Utf8,
    'seqNumber': pl.Float64,
    'shortColumnTitle': pl.Utf8,
    'trxCode': pl.Utf8,
    'typeCanDeleteYn': pl.Utf8,
    'typeDesc': pl.Utf8,
    'typeInsertDate': pl.Utf8,
    'typeInsertUser': pl.Float64,
    'typeInsertUserName': pl.Utf8,
    'typeUpdateDate': pl.Utf8,
    'typeUpdateUser': pl.Float64,
    'typeUpdateUserName': pl.Utf8,
    'useLovYn': pl.Utf8,
}

```