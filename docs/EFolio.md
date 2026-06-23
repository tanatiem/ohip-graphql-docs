# EFolio
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
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

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | folioTaxDetails | [`EFolioFolioTaxDetailsType`](#efoliofoliotaxdetailstype) | Folio Tax Details |
| 2 | folioTransactionsDetails | [`EFolioFolioTransactionsDetailsType`](#efoliofoliotransactionsdetailstype) | Folio Transactions Details |
| 3 | propertyExportValuesDetails | [`EFolioPropertyExportValuesDetailsType`](#efoliopropertyexportvaluesdetailstype) | Property Export Values |
| 4 | profileAllInformationDetails | [`EFolioProfileAllInformationDetailsType`](#efolioprofileallinformationdetailstype) | Profile All Details |
| 5 | profileAddressDetails | [`EFolioProfileAddressDetailsType`](#efolioprofileaddressdetailstype) | Profile Address Details |
| 6 | profileCommunicationDetails | [`EFolioProfileCommunicationDetailsType`](#efolioprofilecommunicationdetailstype) | Profile Communication Details |
| 7 | reservationDetails | [`EFolioReservationDetailsType`](#efolioreservationdetailstype) | Reservation Details |
| 8 | fiscalCalendarDetails | [`EFolioFiscalCalendarDetailsType`](#efoliofiscalcalendardetailstype) | Fiscal Calendar |
| 9 | gregerianCalendarDetails | [`EFolioGregerianCalendarDetailsType`](#efoliogregeriancalendardetailstype) | Gregerian Calendar |
| 10 | exportMapEfolioExportDetails | [`EFolioExportMapEfolioExportDetailsType`](#efolioexportmapefolioexportdetailstype) | Export Map Efolio Export |
| 11 | eFolioRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### EFolioFolioTaxDetailsType

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

### EFolioFolioTransactionsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRChargeTransferYN | `String` | Indicates if an individual charge has been transferred to another invoice in AR. Used to disallow operations such as the transfer of same charge multiple times editing an already transferred charge etc. |
| 2 | aSBFlag | `String` | Indicates ASB transactions: Rental charge for an [A]partment Style Rental Cycle [O]ffsetting transaction for Rental charge for an Apartment Style Rental Cycle [N]ightly Rental Posting [W]aived Nights Rental Posting |
| 3 | aSBOnlyPostTaxesOnceYn | `String` | Set Y to transactions when the application parameter ONLY POST TAXES ONCE FOR APARTMENT STYLE BILLING CHARGES is set. Proper rows and net amount will be shown in reports when the parameter is turned on or off. |
| 4 | aSBTaxFlag | `String` | Populate the tax rows that are inserted for Trial balance with "ASB_TB_TAX". Other reports and screens will hide these transactions. |
| 5 | accountCode | `Float` | Account Code |
| 6 | accountTypeFlag | `String` | Account Type Flag |
| 7 | accountid | `Float` | Accountid |
| 8 | address1 | `String` | Address1 |
| 9 | addresseeNameId | `Float` | Addressee Name ID |
| 10 | adjustmentflag | `String` | Adjustmentflag |
| 11 | advGenerateAdjustment | `String` | Indicates the automatic adjustment posting for advanced generates. Possible values are ?NA? ?CO?. |
| 12 | advanceBillReversedYn | `String` | Identifies if this Advance Bill has been reversed. |
| 13 | advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| 14 | advanceGenerateTrxCode | `String` | Transaction code of the master posting of the automatic adjustment posting for advanced generates. |
| 15 | advancedGenerateYn | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| 16 | advgentranscodeid | `String` | Advgentranscodeid |
| 17 | approvalCode | `String` | Approval Code |
| 18 | approvalDate | `Date` | Approval Date |
| 19 | approvalStatus | `String` | Approval Status |
| 20 | arLedgerCredit | `Float` | AR Led Credit |
| 21 | arLedgerDebit | `Float` | AR Led Debit |
| 22 | arNumber | `Float` | AR Number |
| 23 | arState | `String` | AR State |
| 24 | arTransferDate | `Date` | AR Transfer Date |
| 25 | archargetransferflag | `String` | Archargetransferflag |
| 26 | arrangementCode | `String` | Arrangement Code |
| 27 | arrangementDescription | `String` | Arrangement Description for the Transaction Code. |
| 28 | arrangementId | `Float` | Arrangement ID |
| 29 | articleId | `Float` | Article ID |
| 30 | associatedBillDate | `Date` | Date on which the Original Bill was generated. This is used in case of Credit Bill. |
| 31 | associatedBillNo | `String` | Associated Bill Number |
| 32 | associatedFiscalBillDate | `Date` | Associated Fiscal Bill number generation date. |
| 33 | associatedFiscalBillNo | `String` | Associated Fiscal Bill number. |
| 34 | associatedFiscalBillTime | `String` | Associated Fiscal Bill number generation time. |
| 35 | associatedReceiptNo | `Float` | Indicates the associated receipt number printed for a particular receipt type. |
| 36 | associatedSeqNumber | `Float` | Self referencing sequence number to gather information for other operations. |
| 37 | associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| 38 | authemployeeid | `Float` | Authemployeeid |
| 39 | authorizerId | `Float` | Authorizer ID |
| 40 | autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| 41 | autoSettleYn | `String` | Auto Settle Y/N |
| 42 | billGenerationDate | `Date` | Bill Generation Date |
| 43 | billGenerationTime | `String` | Bill Generation Time |
| 44 | billNo | `Float` | Bill Number |
| 45 | billPaymentTrxNumber | `Float` | Bill Payment Transaction No |
| 46 | billPrefix | `String` | Bill Prefix |
| 47 | billSeqNumber | `Float` | Bill Sequence No |
| 48 | billStartDate | `Date` | Date of the first charge in the bill. |
| 49 | bonusCheckId | `Float` | Bonus Check ID |
| 50 | bucketCode | `String` | Bucket code related to this redemption. |
| 51 | bucketRedempYn | `String` | Indicates that this transaction was a gaming bucket redemption. |
| 52 | businessDate | `Date` | Business Date |
| 53 | businessId | `String` | Business ID |
| 54 | cARLedgerCredit | `Float` | Central Ar Led Credit |
| 55 | cARLedgerDebit | `Float` | Central Ar Led Debit |
| 56 | cCashierCredit | `Float` | Central Cashier Credit |
| 57 | cCashierDebit | `Float` | Central Cashier Debit |
| 58 | cCashierOpeningBalance | `Float` | Central Cashier Opening Balance |
| 59 | cCashpay | `Float` | Central Cashpay |
| 60 | cCcTransactionFeeAmount | `Float` | Central Cc Trx Fee Amount |
| 61 | cCcpay | `Float` | Central Ccpay |
| 62 | cChangeDue | `Float` | Central Change Due |
| 63 | cClarpay | `Float` | Central Clarpay |
| 64 | cClpay | `Float` | Central Clpay |
| 65 | cCollectionTax1 | `Float` | Central Coll Tax1 |
| 66 | cCollectionTax2 | `Float` | Central Coll Tax2 |
| 67 | cCollectionTax3 | `Float` | Central Coll Tax3 |
| 68 | cCollectionTax4 | `Float` | Central Coll Tax4 |
| 69 | cCollectionTax5 | `Float` | Central Coll Tax5 |
| 70 | cContractGrossAmount | `Float` | Central Contract Gross Amount |
| 71 | cContractGuestCredit | `Float` | Central Contract Guest Credit |
| 72 | cContractGuestDebit | `Float` | Central Contract Guest Debit |
| 73 | cContractNetAmount | `Float` | Central Contract Net Amount |
| 74 | cDailyRunningTotal | `Float` | Central Daily Running Total |
| 75 | cDepLedgerCredit | `Float` | Central Dep Led Credit |
| 76 | cDepLedgerDebit | `Float` | Central Dep Led Debit |
| 77 | cDeposit | `Float` | Central Deposit |
| 78 | cExchangeDate | `Date` | Central Xchange Date |
| 79 | cExchangeRate | `Float` | Central Xchange Rate |
| 80 | cFiscalInvoiceCurrencyRate | `Float` | Central Fiscal Invoice Currency Rate |
| 81 | cForexCommissionAmount | `Float` | Central Forex Comm Amount |
| 82 | cGuestAccountCredit | `Float` | Central Guest Account Credit |
| 83 | cGuestAccountDebit | `Float` | Central Guest Account Debit |
| 84 | cInHouseCredit | `Float` | Central Inh Credit |
| 85 | cInHouseDebit | `Float` | Central Inh Debit |
| 86 | cNet1Amount | `Float` | Central Net1 Amt |
| 87 | cNet10Amount | `Float` | Central Net10 Amt |
| 88 | cNet11Amount | `Float` | Central Net11 Amt |
| 89 | cNet12Amount | `Float` | Central Net12 Amt |
| 90 | cNet13Amount | `Float` | Central Net13 Amt |
| 91 | cNet14Amount | `Float` | Central Net14 Amt |
| 92 | cNet15Amount | `Float` | Central Net15 Amt |
| 93 | cNet16Amount | `Float` | Central Net16 Amt |
| 94 | cNet17Amount | `Float` | Central Net17 Amt |
| 95 | cNet18Amount | `Float` | Central Net18 Amt |
| 96 | cNet19Amount | `Float` | Central Net19 Amt |
| 97 | cNet2Amount | `Float` | Central Net2 Amt |
| 98 | cNet20Amount | `Float` | Central Net20 Amt |
| 99 | cNet3Amount | `Float` | Central Net3 Amt |
| 100 | cNet4Amount | `Float` | Central Net4 Amt |
| 101 | cNet5Amount | `Float` | Central Net5 Amt |
| 102 | cNet6Amount | `Float` | Central Net6 Amt |
| 103 | cNet7Amount | `Float` | Central Net7 Amt |
| 104 | cNet8Amount | `Float` | Central Net8 Amt |
| 105 | cNet9Amount | `Float` | Central Net9 Amt |
| 106 | cNonRevenueAmount | `Float` | Central Non Revenue Amount |
| 107 | cOrganizationARLedgerDebit | `Float` | Central Org Ar Led Debit |
| 108 | cOrganizationPostedAmount | `Float` | Central Org Posted Amount |
| 109 | cPackageAllowance | `Float` | Central Package Allowance |
| 110 | cPackageCredit | `Float` | Central Package Credit |
| 111 | cPackageDebit | `Float` | Central Package Debit |
| 112 | cPaidout | `Float` | Central Paidout |
| 113 | cParallelGrossAmount | `Float` | Central Parallel Gross Amount |
| 114 | cParallelGuestCredit | `Float` | Central Parallel Guest Credit |
| 115 | cParallelGuestDebit | `Float` | Central Parallel Guest Debit |
| 116 | cParallelNetAmount | `Float` | Central Parallel Net Amount |
| 117 | cPaymentSurchargeAmount | `Float` | Central Payment Surcharge Amt |
| 118 | cPerpetualAmount | `Float` | Central Perpetual Amount |
| 119 | cPnet1Amount | `Float` | Central Pnet1 Amt |
| 120 | cPnet10Amount | `Float` | Central Pnet10 Amt |
| 121 | cPnet11Amount | `Float` | Central Pnet11 Amt |
| 122 | cPnet12Amount | `Float` | Central Pnet12 Amt |
| 123 | cPnet13Amount | `Float` | Central Pnet13 Amt |
| 124 | cPnet14Amount | `Float` | Central Pnet14 Amt |
| 125 | cPnet15Amount | `Float` | Central Pnet15 Amt |
| 126 | cPnet16Amount | `Float` | Central Pnet16 Amt |
| 127 | cPnet17Amount | `Float` | Central Pnet17 Amt |
| 128 | cPnet18Amount | `Float` | Central Pnet18 Amt |
| 129 | cPnet19Amount | `Float` | Central Pnet19 Amt |
| 130 | cPnet2Amount | `Float` | Central Pnet2 Amt |
| 131 | cPnet20Amount | `Float` | Central Pnet20 Amt |
| 132 | cPnet3Amount | `Float` | Central Pnet3 Amt |
| 133 | cPnet4Amount | `Float` | Central Pnet4 Amt |
| 134 | cPnet5Amount | `Float` | Central Pnet5 Amt |
| 135 | cPnet6Amount | `Float` | Central Pnet6 Amt |
| 136 | cPnet7Amount | `Float` | Central Pnet7 Amt |
| 137 | cPnet8Amount | `Float` | Central Pnet8 Amt |
| 138 | cPnet9Amount | `Float` | Central Pnet9 Amt |
| 139 | cPostedAmount | `Float` | Central Posted Amount |
| 140 | cPtax1Amount | `Float` | Central Ptax1 Amt |
| 141 | cPtax10Amount | `Float` | Central Ptax10 Amt |
| 142 | cPtax11Amount | `Float` | Central Ptax11 Amt |
| 143 | cPtax12Amount | `Float` | Central Ptax12 Amt |
| 144 | cPtax13Amount | `Float` | Central Ptax13 Amt |
| 145 | cPtax14Amount | `Float` | Central Ptax14 Amt |
| 146 | cPtax15Amount | `Float` | Central Ptax15 Amt |
| 147 | cPtax16Amount | `Float` | Central Ptax16 Amt |
| 148 | cPtax17Amount | `Float` | Central Ptax17 Amt |
| 149 | cPtax18Amount | `Float` | Central Ptax18 Amt |
| 150 | cPtax19Amount | `Float` | Central Ptax19 Amt |
| 151 | cPtax2Amount | `Float` | Central Ptax2 Amt |
| 152 | cPtax20Amount | `Float` | Central Ptax20 Amt |
| 153 | cPtax3Amount | `Float` | Central Ptax3 Amt |
| 154 | cPtax4Amount | `Float` | Central Ptax4 Amt |
| 155 | cPtax5Amount | `Float` | Central Ptax5 Amt |
| 156 | cPtax6Amount | `Float` | Central Ptax6 Amt |
| 157 | cPtax7Amount | `Float` | Central Ptax7 Amt |
| 158 | cPtax8Amount | `Float` | Central Ptax8 Amt |
| 159 | cPtax9Amount | `Float` | Central Ptax9 Amt |
| 160 | cPtotNonrevNonTaxable | `Float` | Central Ptot Nonrev Nontaxable |
| 161 | cPtotNonrevTaxable | `Float` | Central Ptot Nonrev Taxable |
| 162 | cPtotRevenueNonTaxable | `Float` | Central Ptot Rev Nontaxable |
| 163 | cPtotRevenueTaxable | `Float` | Central Ptot Rev Taxable |
| 164 | cRealPerpetualAmount | `Float` | Central Real Perpetual Amount |
| 165 | cRevenueAmount | `Float` | Central Revenue Amt |
| 166 | cTax1Amount | `Float` | Central Tax1 Amt |
| 167 | cTax1Rate | `Float` | Central Tax1 Rate |
| 168 | cTax2Amount | `Float` | Central Tax2 Amt |
| 169 | cTax2Rate | `Float` | Central Tax2 Rate |
| 170 | cTaxCode1 | `String` | Central Tax Code 1 |
| 171 | cTaxCode10 | `String` | Central Tax Code 10 |
| 172 | cTaxCode11 | `String` | Central Tax Code 11 |
| 173 | cTaxCode12 | `String` | Central Tax Code 12 |
| 174 | cTaxCode13 | `String` | Central Tax Code 13 |
| 175 | cTaxCode14 | `String` | Central Tax Code 14 |
| 176 | cTaxCode15 | `String` | Central Tax Code 15 |
| 177 | cTaxCode16 | `String` | Central Tax Code 16 |
| 178 | cTaxCode17 | `String` | Central Tax Code 17 |
| 179 | cTaxCode18 | `String` | Central Tax Code 18 |
| 180 | cTaxCode19 | `String` | Central Tax Code 19 |
| 181 | cTaxCode2 | `String` | Central Tax Code 2 |
| 182 | cTaxCode20 | `String` | Central Tax Code 20 |
| 183 | cTaxCode3 | `String` | Central Tax Code 3 |
| 184 | cTaxCode4 | `String` | Central Tax Code 4 |
| 185 | cTaxCode5 | `String` | Central Tax Code 5 |
| 186 | cTaxCode6 | `String` | Central Tax Code 6 |
| 187 | cTaxCode7 | `String` | Central Tax Code 7 |
| 188 | cTaxCode8 | `String` | Central Tax Code 8 |
| 189 | cTaxCode9 | `String` | Central Tax Code 9 |
| 190 | cTaxCodeDescription1 | `String` | Central Tax Code Desc 1 |
| 191 | cTaxCodeDescription10 | `String` | Central Tax Code Desc 10 |
| 192 | cTaxCodeDescription11 | `String` | Central Tax Code Desc 11 |
| 193 | cTaxCodeDescription12 | `String` | Central Tax Code Desc 12 |
| 194 | cTaxCodeDescription13 | `String` | Central Tax Code Desc 13 |
| 195 | cTaxCodeDescription14 | `String` | Central Tax Code Desc 14 |
| 196 | cTaxCodeDescription15 | `String` | Central Tax Code Desc 15 |
| 197 | cTaxCodeDescription16 | `String` | Central Tax Code Desc 16 |
| 198 | cTaxCodeDescription17 | `String` | Central Tax Code Desc 17 |
| 199 | cTaxCodeDescription18 | `String` | Central Tax Code Desc 18 |
| 200 | cTaxCodeDescription19 | `String` | Central Tax Code Desc 19 |
| 201 | cTaxCodeDescription2 | `String` | Central Tax Code Desc 2 |
| 202 | cTaxCodeDescription20 | `String` | Central Tax Code Desc 20 |
| 203 | cTaxCodeDescription3 | `String` | Central Tax Code Desc 3 |
| 204 | cTaxCodeDescription4 | `String` | Central Tax Code Desc 4 |
| 205 | cTaxCodeDescription5 | `String` | Central Tax Code Desc 5 |
| 206 | cTaxCodeDescription6 | `String` | Central Tax Code Desc 6 |
| 207 | cTaxCodeDescription7 | `String` | Central Tax Code Desc 7 |
| 208 | cTaxCodeDescription8 | `String` | Central Tax Code Desc 8 |
| 209 | cTaxCodeDescription9 | `String` | Central Tax Code Desc 9 |
| 210 | cTaxRate | `Float` | Central Tax Rate |
| 211 | cTax10Amount | `Float` | Central Tax10 Amt |
| 212 | cTax10Rate | `Float` | Central Tax10 Rate |
| 213 | cTax11Amount | `Float` | Central Tax11 Amt |
| 214 | cTax11Rate | `Float` | Central Tax11 Rate |
| 215 | cTax12Amount | `Float` | Central Tax12 Amt |
| 216 | cTax12Rate | `Float` | Central Tax12 Rate |
| 217 | cTax13Amount | `Float` | Central Tax13 Amt |
| 218 | cTax13Rate | `Float` | Central Tax13 Rate |
| 219 | cTax14Amount | `Float` | Central Tax14 Amt |
| 220 | cTax14Rate | `Float` | Central Tax14 Rate |
| 221 | cTax15Amount | `Float` | Central Tax15 Amt |
| 222 | cTax15Rate | `Float` | Central Tax15 Rate |
| 223 | cTax16Amount | `Float` | Central Tax16 Amt |
| 224 | cTax16Rate | `Float` | Central Tax16 Rate |
| 225 | cTax17Amount | `Float` | Central Tax17 Amt |
| 226 | cTax17Rate | `Float` | Central Tax17 Rate |
| 227 | cTax18Amount | `Float` | Central Tax18 Amt |
| 228 | cTax18Rate | `Float` | Central Tax18 Rate |
| 229 | cTax19Amount | `Float` | Central Tax19 Amt |
| 230 | cTax19Rate | `Float` | Central Tax19 Rate |
| 231 | cTax20Amount | `Float` | Central Tax20 Amt |
| 232 | cTax20Rate | `Float` | Central Tax20 Rate |
| 233 | cTax3Amount | `Float` | Central Tax3 Amt |
| 234 | cTax3Rate | `Float` | Central Tax3 Rate |
| 235 | cTax4Amount | `Float` | Central Tax4 Amt |
| 236 | cTax4Rate | `Float` | Central Tax4 Rate |
| 237 | cTax5Amount | `Float` | Central Tax5 Amt |
| 238 | cTax5Rate | `Float` | Central Tax5 Rate |
| 239 | cTax6Amount | `Float` | Central Tax6 Amt |
| 240 | cTax6Rate | `Float` | Central Tax6 Rate |
| 241 | cTax7Amount | `Float` | Central Tax7 Amt |
| 242 | cTax7Rate | `Float` | Central Tax7 Rate |
| 243 | cTax8Amount | `Float` | Central Tax8 Amt |
| 244 | cTax8Rate | `Float` | Central Tax8 Rate |
| 245 | cTax9Amount | `Float` | Central Tax9 Amt |
| 246 | cTax9Rate | `Float` | Central Tax9 Rate |
| 247 | cTotalGross | `Float` | Central Total Gross |
| 248 | cTotalNet | `Float` | Central Total Net |
| 249 | cTotalNonTaxable | `Float` | Central Total Nontaxable |
| 250 | cTotalNonrevNonTaxable | `Float` | Central Tot Nonrev Nontaxable |
| 251 | cTotalNonrevTaxable | `Float` | Central Tot Nonrev Taxable |
| 252 | cTotalRevenueNonTaxable | `Float` | Central Tot Rev Nontaxable |
| 253 | cTotalRevenueTaxable | `Float` | Central Tot Rev Taxable |
| 254 | cTotalTax | `Float` | Central Total Tax |
| 255 | cTransactionAmount | `Float` | Central Trx Amount |
| 256 | cTrialBalanceAmountGross | `Float` | Central Trial Balance Amount Gross |
| 257 | cTrialBalanceAmountNet | `Float` | Central Trial Balance Amount Net |
| 258 | cXnet1Amount | `Float` | Central Xnet1 Amt |
| 259 | cXnet10Amount | `Float` | Central Xnet10 Amt |
| 260 | cXnet11Amount | `Float` | Central Xnet11 Amt |
| 261 | cXnet12Amount | `Float` | Central Xnet12 Amt |
| 262 | cXnet13Amount | `Float` | Central Xnet13 Amt |
| 263 | cXnet14Amount | `Float` | Central Xnet14 Amt |
| 264 | cXnet15Amount | `Float` | Central Xnet15 Amt |
| 265 | cXnet16Amount | `Float` | Central Xnet16 Amt |
| 266 | cXnet17Amount | `Float` | Central Xnet17 Amt |
| 267 | cXnet18Amount | `Float` | Central Xnet18 Amt |
| 268 | cXnet19Amount | `Float` | Central Xnet19 Amt |
| 269 | cXnet2Amount | `Float` | Central Xnet2 Amt |
| 270 | cXnet20Amount | `Float` | Central Xnet20 Amt |
| 271 | cXnet3Amount | `Float` | Central Xnet3 Amt |
| 272 | cXnet4Amount | `Float` | Central Xnet4 Amt |
| 273 | cXnet5Amount | `Float` | Central Xnet5 Amt |
| 274 | cXnet6Amount | `Float` | Central Xnet6 Amt |
| 275 | cXnet7Amount | `Float` | Central Xnet7 Amt |
| 276 | cXnet8Amount | `Float` | Central Xnet8 Amt |
| 277 | cXnet9Amount | `Float` | Central Xnet9 Amt |
| 278 | cXtax1Amount | `Float` | Central Xtax1 Amt |
| 279 | cXtax10Amount | `Float` | Central Xtax10 Amt |
| 280 | cXtax11Amount | `Float` | Central Xtax11 Amt |
| 281 | cXtax12Amount | `Float` | Central Xtax12 Amt |
| 282 | cXtax13Amount | `Float` | Central Xtax13 Amt |
| 283 | cXtax14Amount | `Float` | Central Xtax14 Amt |
| 284 | cXtax15Amount | `Float` | Central Xtax15 Amt |
| 285 | cXtax16Amount | `Float` | Central Xtax16 Amt |
| 286 | cXtax17Amount | `Float` | Central Xtax17 Amt |
| 287 | cXtax18Amount | `Float` | Central Xtax18 Amt |
| 288 | cXtax19Amount | `Float` | Central Xtax19 Amt |
| 289 | cXtax2Amount | `Float` | Central Xtax2 Amt |
| 290 | cXtax20Amount | `Float` | Central Xtax20 Amt |
| 291 | cXtax3Amount | `Float` | Central Xtax3 Amt |
| 292 | cXtax4Amount | `Float` | Central Xtax4 Amt |
| 293 | cXtax5Amount | `Float` | Central Xtax5 Amt |
| 294 | cXtax6Amount | `Float` | Central Xtax6 Amt |
| 295 | cXtax7Amount | `Float` | Central Xtax7 Amt |
| 296 | cXtax8Amount | `Float` | Central Xtax8 Amt |
| 297 | cXtax9Amount | `Float` | Central Xtax9 Amt |
| 298 | calcmemberpointsflag | `String` | Calcmemberpointsflag |
| 299 | cashRegisterId | `String` | Cash Register ID |
| 300 | cashRegisterInvNumber | `Float` | Internal sequence number for the Cash Register ID. |
| 301 | cashierCredit | `Float` | Cashier Credit |
| 302 | cashierDebit | `Float` | Cashier Debit |
| 303 | cashierId | `Float` | Cashier ID |
| 304 | cashierOpeningBalance | `Float` | Cashier Opening Balance |
| 305 | cashpay | `Float` | Total paid in cash |
| 306 | ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| 307 | ccTrxFeeAmount | `Float` | Fee (surcharge) amount for a credit card transaction. |
| 308 | ccpay | `Float` | Total paid in the form of credit cards. |
| 309 | centralGrossAmount | `Float` | Central Gross Amount |
| 310 | centralNetAmount | `Float` | Central Net Amount |
| 311 | centralPaymentAmount | `Float` | Central Payment Amount |
| 312 | centralPrice | `Float` | Central Price |
| 313 | centralTaxAmount | `Float` | Central Tax Amount |
| 314 | centralTaxCode | `String` | Central Tax Code |
| 315 | centralTaxCodeDescription | `String` | Central Tax Code Description |
| 316 | centralTransactionAmount | `Float` | Central Transaction Amount |
| 317 | centralTransactionCode | `String` | Central Transaction Code |
| 318 | centralTransactionDescription | `String` | Central Transaction Description |
| 319 | centralTransactionGroupCode | `String` | Central Transaction Group Code |
| 320 | centralTransactionGroupDescription | `String` | Central Transaction Group Description |
| 321 | centralTransactionSubGroupCode | `String` | Central Transaction Sub-Group Code |
| 322 | centralTransactionSubGroupDescription | `String` | Central Transaction Sub-Group Description |
| 323 | changeDue | `Float` | Change Due |
| 324 | checkFileId | `String` | This field will store the file number for the guest check PNG file which has to be appended to the application settings base URL. |
| 325 | checkNumber | `String` | Check Number |
| 326 | city | `String` | City |
| 327 | cityLedgerYn | `String` | City Ledger Y/N |
| 328 | clTrxNumber | `Float` | Internal number given to the direct bill payment in financial_transactions. |
| 329 | clarpay | `Float` | This is to store amount posted from AR for a bill. In this case CLPAY will not have value if the bill is generated in AR |
| 330 | closureNo | `Float` | Closure Number |
| 331 | clpay | `Float` | The amount that has been paid using direct bill. |
| 332 | collectionAgentPostingYn | `String` | Y => tax posting for a collecting agent |
| 333 | collectionTax1 | `Float` | Collection Tax 1 |
| 334 | collectionTax2 | `Float` | Collection Tax 2 |
| 335 | collectionTax3 | `Float` | Collection Tax3 |
| 336 | collectionTax4 | `Float` | Collection Tax4 |
| 337 | collectionTax5 | `Float` | Collection Tax5 |
| 338 | comments | `String` | Comments |
| 339 | compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| 340 | compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| 341 | compTypeCode | `String` | Comp Type Code |
| 342 | companyFinancialValue | `String` | The financial value of the company. |
| 343 | companyName | `String` | Company Name |
| 344 | companyType | `String` | The type of legal entity / company e.g. Individual Micro enterprise etc. |
| 345 | complinktranscodeid | `String` | Complinktranscodeid |
| 346 | compressBillNo | `String` | To store the Compressed Bill No. and Converted Bill number information |
| 347 | compressedYn | `String` | Compressed Y/N |
| 348 | contractCurrency | `String` | Currency code for contract currency. |
| 349 | contractGrossAmount | `Float` | Contract equivalent to the GROSS_AMOUNT field value for the transaction number this record applies to. |
| 350 | contractGuestCredit | `Float` | Stores the credit amount on the guest account in contract currency. |
| 351 | contractGuestDebit | `Float` | Stores the debit amount on the guest account in contract currency. |
| 352 | contractNetAmount | `Float` | Contract equivalent to the NET_AMOUNT field value for the transaction number this record applies to. |
| 353 | contractforeigncurrencyid | `String` | Contract Foreign Currency ID |
| 354 | correctionYn | `String` | Indicates if this transaction is used as part of a correction folio. |
| 355 | country | `String` | Country |
| 356 | countryCode | `String` | Country Code |
| 357 | couponNo | `String` | Coupon Number |
| 358 | covers | `String` | Covers |
| 359 | creditBillGeneratedYn | `String` | Indicates if a credit bill has been generated for this folio. |
| 360 | creditBillNo | `Float` | Credit Bill Number |
| 361 | creditCardId | `Float` | Credit Card ID |
| 362 | currency | `String` | Currency |
| 363 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 364 | dailyRunningTotal | `Float` | Daily running total. |
| 365 | debitOrCredit | `String` | Debit or Credit |
| 366 | deferredYn | `String` | Deferred Y/N |
| 367 | deletedFlag | `String` | Deleted Flag |
| 368 | depLedgerCredit | `Float` | Dep Ledger Credit |
| 369 | depLedgerDebit | `Float` | Dep Ledger Debit |
| 370 | depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| 371 | depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| 372 | deposit | `Float` | Total deposits. |
| 373 | depositReqReceiptNo | `Float` | Deposit Req Receipt Number |
| 374 | depositTransactionId | `String` | Deposit Transaction ID |
| 375 | depositlinkfintransid | `Float` | Depositlinkfintransid |
| 376 | displayflag | `String` | Displayflag |
| 377 | documentCode | `String` | Unique Document Code |
| 378 | documentType | `String` | Document Type |
| 379 | eArchiveEttnNumber | `String` | Unique ETTN number for an E Archive invoice. |
| 380 | eArchiveNumber | `String` | E Archive number. |
| 381 | eArchiveReportNo | `String` | E Archive report number provided by external system e.g. PROTEL. |
| 382 | eArchiveStatus | `String` | E Archive status. |
| 383 | eInvoiceNumber | `String` | E Invoice Number |
| 384 | eInvoiceStatus | `String` | E-Invoice number received from Portal+. This number be updated via Web Service call from Portal+. |
| 385 | effectiveDate | `Date` | Transactions statement date used for OVOS statement reports to allocate transactions into required statement period. |
| 386 | electronicVoucherNo | `Float` | Stores the voucher_no from VOUCHERS_DETAILS to keep track of voucher amount consumed. |
| 387 | esignedReceiptName | `String` | File Name of the Electronically Signed Payment Receipt. |
| 388 | euroExchangeRate | `Float` | Euro Exchange Rate |
| 389 | exchDifferenceTrxNumber | `Float` | Exchange difference posting transaction number of the posting that generated the exchange difference. |
| 390 | exchangeDate | `Date` | Exchange Date |
| 391 | exchangeRate | `Float` | Exchange Rate |
| 392 | exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| 393 | exchangedifferenceflag | `String` | Exchangedifferenceflag |
| 394 | expInvoiceType | `String` | Export Invoice Type |
| 395 | expOriginalInvoice | `String` | Export Original Invoice |
| 396 | extSysResultMsg | `String` | Oxi interface to External System Result message text. |
| 397 | extTransactionId | `String` | Transaction ID from external system. |
| 398 | fbaCertificateNumber | `String` | Flexible Benefit Award certificate number. |
| 399 | filterChar1 | `String` | Filter Char1 |
| 400 | filterChar2 | `String` | Filter Char2 |
| 401 | filterChar3 | `String` | Filter Char3 |
| 402 | filterChar4 | `String` | Filter Char4 |
| 403 | filterChar5 | `String` | Filter Char5 |
| 404 | finBillNumber | `Float` | Financial Bill No |
| 405 | finBusinessDate | `Date` | Financial Business Date |
| 406 | finCountry | `String` | Financial Country |
| 407 | finDeletedFlag | `String` | Financial Deleted Flag |
| 408 | finFiscalBillNumber | `String` | Financial Fiscal Bill No |
| 409 | finFolioView | `Float` | Financial Folio View |
| 410 | finInsertDate | `Date` | Financial Insert Date |
| 411 | finInsertUser | `Float` | Financial Insert User |
| 412 | finInvoiceNumber | `Float` | Financial Invoice No |
| 413 | finNameTaxType | `String` | Financial Name Tax Type |
| 414 | finPkid | `Float` | Financial Pkid |
| 415 | finPostitNumber | `Float` | Financial Postit No |
| 416 | finPropertyBillPrefix | `String` | Financial Property Bill Prefix |
| 417 | finQueueName | `String` | Financial Queue Name |
| 418 | finRevisionNumber | `Float` | Financial Revision No |
| 419 | finRoom | `String` | Financial Room |
| 420 | finUpdateDate | `Date` | Financial Update Date |
| 421 | finUpdateUser | `Float` | Financial Update User |
| 422 | financialCExchangeDate | `Date` | Fin Central Xchange Date |
| 423 | financialCExchangeRate | `Float` | Fin Central Xchange Rate |
| 424 | financialCashierId | `Float` | Fin Cashier ID |
| 425 | financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| 426 | financialForexTaxYN | `String` | Fin Forex Tax Y/N |
| 427 | financialNameId | `Float` | Fin Name ID |
| 428 | financialPostitYN | `String` | Fin Postit Y/N |
| 429 | financialReservationNameId | `Float` | Fin Resv Name ID |
| 430 | fintransactionid | `Float` | Fintransactionid |
| 431 | fintransid | `Float` | Fintransid |
| 432 | first | `String` | First |
| 433 | fiscalBillCheckDigit | `Float` | Fiscal Bill Check Digit |
| 434 | fiscalBillGenerationDate | `Date` | Fiscal Bill Generation Date |
| 435 | fiscalBillGenerationTime | `String` | Fiscal Bill Generation Time |
| 436 | fiscalBillNo | `String` | Fiscal Bill Number |
| 437 | fiscalInvoiceCurrency | `String` | Currency Code used by and sent to the Fiscal Service. |
| 438 | fiscalInvoiceCurrencyRate | `Float` | Exchange Rate of the Fiscal Invoice currency for settlement on the bill generation date. |
| 439 | fiscalSessionNo | `String` | Session number generated by the fiscal printer. This numbers gets reset during EOD. |
| 440 | fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| 441 | fiscalUnitControlCode | `String` | Fiscal Unit Control Code |
| 442 | fixedchargesflag | `String` | Fixedchargesflag |
| 443 | folioAddress | `String` | Folio Full Address. |
| 444 | folioAddressCorrectedYn | `String` | Indicates if the folio header was corrected. |
| 445 | folioAttachmentLinkId | `Float` | Folio Attachment Link ID |
| 446 | folioAttachmentStatus | `Float` | Folio Attachment Status |
| 447 | folioNo | `Float` | Folio Number |
| 448 | folioStyle | `String` | Folio Style |
| 449 | folioTaxSeqNumber | `Float` | Folio Tax Sequence No |
| 450 | folioType | `String` | Folio Type |
| 451 | folioType1 | `String` | Folio Type 1 |
| 452 | folioTypeJoin | `String` | Folio Type Join |
| 453 | folioView | `Float` | Folio View |
| 454 | folioid | `Float` | Folioid |
| 455 | foreignCurrencyID | `String` | Foreign Currency ID |
| 456 | forexCommAmount | `Float` | Foreign Exchange commission amount. |
| 457 | forexCommPerc | `Float` | Foreign Exchange commission percentage. |
| 458 | forexTaxYn | `String` | Populate as Y for transactions posted with application settings 1)Currency Exchange Tax and 2)Currency Exchange Offset. |
| 459 | forexType | `String` | Type of Foreign Currency Exchange. B=Buy  S=Sell. |
| 460 | fromReservationId | `Float` | From Resv ID |
| 461 | ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| 462 | ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| 463 | fullFolioNo | `String` | Full Folio Number |
| 464 | genCashierId | `Float` | General Cashier Id. |
| 465 | gpAwardCancelCode | `String` | HYATT mode: Gold Passport Award Cancel Code. Field will be populated for transactions that are created when awards redeemed in the past are cancelled e.g. when a Folio is Re-opened. |
| 466 | gpAwardCode | `String` | HYATT mode: Gold Passport Award Code associated with the redemption of points. Field will be populated for a payment transaction. |
| 467 | grossAmount | `Float` | Gross Amount |
| 468 | groupAwardCancelledYN | `String` | HYATT mode: Indicates if an Award Transaction was cancelled. |
| 469 | guestAccountCredit | `Float` | Guest Account Credit |
| 470 | guestAccountDebit | `Float` | Debit amount on the guest account |
| 471 | hasWatermarkYn | `String` | If PERMANENT FOLIO STORAGE is active this flag indicates whether the PDF file has the "Copy" watermark. |
| 472 | hotelAcct | `String` | Specifies the Hotel acct against which this transaction has beenposted. |
| 473 | hotelName | `String` | Hotel name of the property at the time of bill generation. |
| 474 | incTaxDeductedYn | `String` | Identifies if this transaction has had inclusive taxes removed during comping. |
| 475 | inclusiveTaxYN | `String` | Inclusive Tax YN |
| 476 | individualAdjustmentYN | `String` | Ind Adjustment Y/N |
| 477 | inhCredit | `Float` | In House Credit |
| 478 | inhDebit | `Float` | In House Debit |
| 479 | insTimestamp | `DateTime` | Timestamp to capture the exact order of inserts. |
| 480 | insertDate | `DateTime` | Insert Date |
| 481 | insertUser | `Float` | Insert User |
| 482 | insertUserName | `String` | The name of the user who created the record. |
| 483 | installments | `Float` | Installments |
| 484 | internalArticleid | `Float` | Articleid |
| 485 | internalBusinessdate | `Date` | Businessdate |
| 486 | internalCashierid | `Float` | Cashierid |
| 487 | invoiceCloseDate | `Date` | Invoice Close Date |
| 488 | invoiceNo | `Float` | Invoice Number |
| 489 | invoiceType | `String` | Invoice Type |
| 490 | iscreditflag | `String` | Iscreditflag |
| 491 | isdebitflag | `String` | Isdebitflag |
| 492 | isinternalflag | `String` | Isinternalflag |
| 493 | jRNUpdateDate | `Date` | JRN Update Date |
| 494 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 495 | last | `String` | Last |
| 496 | lastSignatureHash | `String` | Last Signature Hash |
| 497 | linkTrxNumber | `Float` | Link Transaction No |
| 498 | locationID | `String` | Internal ID to uniquely identify the Property |
| 499 | marketCode | `String` | Market Code |
| 500 | marketid | `String` | Marketid |
| 501 | membershipid | `Float` | Membershipid |
| 502 | mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| 503 | nafApeHotelCode | `String` | NAF/APE code of the hotel at the time of bill generation. |
| 504 | nameId | `Float` | Name ID |
| 505 | nameTaxType | `String` | Name Tax Type |
| 506 | nameTypeDescription | `String` | Name Type Description |
| 507 | netAmount | `Float` | Net Amount |
| 508 | net1Amt | `Float` | Net1 Amount |
| 509 | net10Amt | `Float` | Net10 Amount |
| 510 | net11Amt | `Float` | Net11 Amount |
| 511 | net12Amt | `Float` | Net12 Amount |
| 512 | net13Amt | `Float` | Net13 Amount |
| 513 | net14Amt | `Float` | Net14 Amount |
| 514 | net15Amt | `Float` | Net15 Amount |
| 515 | net16Amt | `Float` | Net16 Amount |
| 516 | net17Amt | `Float` | Net17 Amount |
| 517 | net18Amt | `Float` | Net18 Amount |
| 518 | net19Amt | `Float` | Net19 Amount |
| 519 | net2Amt | `Float` | Net2 Amount |
| 520 | net20Amt | `Float` | Net20 Amount |
| 521 | net3Amt | `Float` | Net3 Amount |
| 522 | net4Amt | `Float` | Net4 Amount |
| 523 | net5Amt | `Float` | Net5 Amount |
| 524 | net6Amt | `Float` | Net6 Amount |
| 525 | net7Amt | `Float` | Net7 Amount |
| 526 | net8Amt | `Float` | Net8 Amount |
| 527 | net9Amt | `Float` | Net9 Amount |
| 528 | nonRevenueAmount | `Float` | Non Revenue Amount |
| 529 | nrBusinessId | `String` | Nr Business ID |
| 530 | numberDialed | `String` | Number Dialed. |
| 531 | numberOfPages | `Float` | Number of pages for a given bill. |
| 532 | oTransactionDesc | `String` | Transaction Description. |
| 533 | onholdflag | `String` | Onholdflag |
| 534 | operaFiscalFolioStatus | `String` | This coulumn is used to store the status of Fiscal Folio /Payload Generation. The values will be SUCCESS - Payload has been sent successfully OFFLINE - User confirmed to generate Offline Folio i.e. Folio will be generated but Fiscal Folio/Payload not generated FAILURE - User do not want to create OFFLINE FOLIO but as FISCAL service is not available so the status is FAILURE i.e. in this case VOID Folio generated with FAILURE Fiscal Folio Status BLANK/NULL - Fiscal Printing is turned off or Past data after the upgrade. |
| 535 | orgBillNumber | `Float` | Stores original bill number after void. |
| 536 | orgFolioType | `String` | Stores original folio type after void. |
| 537 | orgPostedAmount | `Float` | The original transaction amount sent to the financial API. |
| 538 | organizationArLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| 539 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 540 | originalReservationNameID | `Float` | Original Reservation Name ID |
| 541 | originalRoom | `String` | Original Room |
| 542 | originalresvid | `Float` | Originalresvid |
| 543 | packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| 544 | packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| 545 | packageCredit | `Float` | Credit amount on the guest package account. |
| 546 | packageDebit | `Float` | Debit amount on the guest package account |
| 547 | packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| 548 | packagelinkfintransid | `Float` | Packagelinkfintransid |
| 549 | pageNumber | `Float` | Stores the page number within the bill generation. |
| 550 | paidout | `Float` | Total paid outs. |
| 551 | palmVideoFlag | `String` | Indicator to identify if the bill was generated from Video checkout or PALM.  (V->Video  P->PALM). |
| 552 | parallelCurrency | `String` | Cuurency code for parrallel currency. |
| 553 | parallelGrossAmount | `Float` | Parallel Gross Amount |
| 554 | parallelGuestCredit | `Float` | Credit amount on the guest account stored in parrallel currency. |
| 555 | parallelGuestDebit | `Float` | Debit amount on the guest account stored in parrallel currency. |
| 556 | parallelNetAmount | `Float` | Parallel Net Amount |
| 557 | parallelforeigncurrencyid | `String` | Parallel Foreign Currency ID |
| 558 | parentfintransid | `Float` | Parentfintransid |
| 559 | partnerFiscalFolioStatus | `String` | Partner Fiscal Folio Status |
| 560 | passerByName | `String` | Passerby Name. |
| 561 | payeeName | `String` | Payee Name used for signature generation. |
| 562 | payeeNameId | `Float` | Payee Name ID |
| 563 | payeeZipCode | `String` | Payee Zip Code used for signature generation. |
| 564 | paymentAmount | `Float` | Total amount of payment inclusive of VAT |
| 565 | paymentDate | `Date` | Payment Date |
| 566 | paymentDescription | `String` | Payment Description |
| 567 | paymentSurchargeAmt | `Float` | Payment Surcharge Amount. |
| 568 | paymentSurchargeType | `String` | Payment Surcharge Type. Currency for the CASH payment method. |
| 569 | paymentTrxDate | `Date` | Payment Transaction Date |
| 570 | paymentType | `String` | Payment Type |
| 571 | percentage | `Float` | Percentage |
| 572 | perpetualAmount | `Float` | Perpetual Amount. |
| 573 | pnet1Amt | `Float` | Parallel Net1 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 574 | pnet10Amt | `Float` | Parallel Net10 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 575 | pnet11Amt | `Float` | Parallel Net11 extension to the existing pnet amount. |
| 576 | pnet12Amt | `Float` | Parallel Net12 extension to the existing pnet amount. |
| 577 | pnet13Amt | `Float` | Parallel Net13 extension to the existing pnet amount. |
| 578 | pnet14Amt | `Float` | Parallel Net14 extension to the existing pnet amount. |
| 579 | pnet15Amt | `Float` | Parallel Net15 extension to the existing pnet amount. |
| 580 | pnet16Amt | `Float` | Parallel Net16 extension to the existing pnet amount. |
| 581 | pnet17Amt | `Float` | Parallel Net17 extension to the existing pnet amount. |
| 582 | pnet18Amt | `Float` | Parallel Net18 extension to the existing pnet amount. |
| 583 | pnet19Amt | `Float` | Parallel Net19 extension to the existing pnet amount. |
| 584 | pnet2Amt | `Float` | Parallel Net2 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 585 | pnet20Amt | `Float` | Parallel Net20 extension to the existing pnet amount. |
| 586 | pnet3Amt | `Float` | Parallel Net3 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 587 | pnet4Amt | `Float` | Parallel Net4 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 588 | pnet5Amt | `Float` | Parallel Net5 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 589 | pnet6Amt | `Float` | Parallel Net6 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 590 | pnet7Amt | `Float` | Parallel Net7 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 591 | pnet8Amt | `Float` | Parallel Net8 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 592 | pnet9Amt | `Float` | Parallel Net9 amount of the transaction for which the tax1 code is attached as one of the taxes. |
| 593 | postedAmount | `Float` | Posted Amount |
| 594 | postingDate | `Date` | Posting Date |
| 595 | postingRhythm | `String` | Posting Rhythm |
| 596 | postingSourceNameId | `Float` | Source Profile of the posting coming from IFC. Related to 9700 functionality. |
| 597 | postingType | `String` | Indicates if the posting is part of a rate code posting (RATE CODE) or if posted manually (MANUAL). |
| 598 | postitNo | `Float` | Postit Number |
| 599 | postitYn | `String` | Postit Y/N |
| 600 | price | `Float` | Price |
| 601 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 602 | processed8300flag | `String` | Processed8300flag |
| 603 | product | `String` | Product |
| 604 | productid | `String` | Productid |
| 605 | profileid | `Float` | Profileid |
| 606 | profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| 607 | proformaYn | `String` | Proforma Y/N |
| 608 | promotionalText1 | `String` | Text returned by the credit card company |
| 609 | promotionalText2 | `String` | Text returned by the credit card company |
| 610 | property | `String` | Code to uniquely identify the Property |
| 611 | propertyBillPrefix | `String` | Property Bill Prefix |
| 612 | propertyTaxNo | `String` | Property Tax Number |
| 613 | ptax1Amt | `Float` | Parallel Total tax1 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 614 | ptax10Amt | `Float` | Parallel Total tax10 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 615 | ptax11Amt | `Float` | Parallel Total tax11 amount extension to the existing ptax amounts. |
| 616 | ptax12Amt | `Float` | Parallel Total tax12 amount extension to the existing ptax amounts. |
| 617 | ptax13Amt | `Float` | Parallel Total tax13 amount extension to the existing ptax amounts. |
| 618 | ptax14Amt | `Float` | Parallel Total tax14 amount extension to the existing ptax amounts. |
| 619 | ptax15Amt | `Float` | Parallel Total tax15 amount extension to the existing ptax amounts. |
| 620 | ptax16Amt | `Float` | Parallel Total tax16 amount extension to the existing ptax amounts. |
| 621 | ptax17Amt | `Float` | Parallel Total tax17 amount extension to the existing ptax amounts. |
| 622 | ptax18Amt | `Float` | Parallel Total tax18 amount extension to the existing ptax amounts. |
| 623 | ptax19Amt | `Float` | Parallel Total tax19 amount extension to the existing ptax amounts. |
| 624 | ptax2Amt | `Float` | Parallel Total tax2 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 625 | ptax20Amt | `Float` | Parallel Total tax20 amount extension to the existing ptax amounts. |
| 626 | ptax3Amt | `Float` | Parallel Total tax3 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 627 | ptax4Amt | `Float` | Parallel Total tax4 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 628 | ptax5Amt | `Float` | Parallel Total tax5 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 629 | ptax6Amt | `Float` | Parallel Total tax6 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 630 | ptax7Amt | `Float` | Parallel Total tax7 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 631 | ptax8Amt | `Float` | Parallel Total tax8 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 632 | ptax9Amt | `Float` | Parallel Total tax9 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 633 | ptotNonrevNonTaxable | `Float` | Parallel total non revenue amount that is not taxable. |
| 634 | ptotNonrevTaxable | `Float` | Parallel total non revenue amount that is taxable. |
| 635 | ptotRevNonTaxable | `Float` | Parallel total revenue amount that is not taxable. |
| 636 | ptotRevTaxable | `Float` | Parallel total revenue amount that is taxable. |
| 637 | quantity | `Float` | Quantity |
| 638 | queueName | `String` | Queue Name |
| 639 | rateCode | `String` | Rate Code |
| 640 | ratecodeid | `String` | Ratecodeid |
| 641 | realPerpetualAmount | `Float` | Real perpetual amount at the time of generating the bill. |
| 642 | reasonCode | `String` | Reason Code |
| 643 | receiptNo | `Float` | Recpt Number |
| 644 | receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| 645 | reference | `String` | Reference |
| 646 | reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| 647 | reservationNameId | `Float` | Resv Name ID |
| 648 | reservationid | `Float` | Reservationid |
| 649 | resortCity | `String` | City of the hotel at the time of bill generation. |
| 650 | resortCountry | `String` | Country of the hotel at the time of bill generation. |
| 651 | resortFullAddress | `String` | Property Full Address |
| 652 | resortZipcodeCode | `String` | Zipcode of the hotel at the time of bill generation. |
| 653 | resvenddate | `Date` | Resvenddate |
| 654 | revenueAmt | `Float` | Revenue Amount. |
| 655 | reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| 656 | revisionNo | `Float` | Revision Number |
| 657 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 658 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 659 | room | `String` | Room |
| 660 | roomClass | `String` | Room Class |
| 661 | roomNts | `Float` | Room Nts |
| 662 | roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| 663 | roomid | `String` | Roomid |
| 664 | roundFactorYn | `String` | Round Factor Y/N |
| 665 | roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| 666 | routedYn | `String` | Indicates if the transaction has been routed. |
| 667 | routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| 668 | routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| 669 | seqNumber | `Float` | Sequence No |
| 670 | serviceRecoveryAdjustmentYn | `String` | Indicates if the transaction is a service recovery adjustment. |
| 671 | serviceRecoveryDeptCode | `String` | Stores the department code responsible for the adjustment. |
| 672 | serviceTypeCode | `String` | Service Type Code |
| 673 | settlementFlag | `String` | Settlement Flag |
| 674 | signatureHash | `String` | Signature Hash |
| 675 | signatureKeyVersion | `String` | Signature Key Version |
| 676 | softwareVersion | `String` | OPERA software version at the time of bill generation. |
| 677 | sourceCode | `String` | Source Code |
| 678 | sourceCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Source commission calculation. |
| 679 | sourceid | `String` | Sourceid |
| 680 | splitType | `String` | Stores the type of split performed: [A]mount [Q]uantity [P]ercent. |
| 681 | status | `String` | Status |
| 682 | supplement | `String` | Supplement |
| 683 | taCommissionNetYn | `String` | Current transaction uses Net or Gross revenue for Travel Agent commission calculation. |
| 684 | tacommissionableflag | `String` | Tacommissionableflag |
| 685 | targetResort | `String` | Target Property |
| 686 | targetlocationid | `String` | Targetlocationid |
| 687 | tax1Amt | `Float` | Tax1 Amount |
| 688 | tax1No | `String` | Tax1 Number |
| 689 | tax1Rate | `Float` | Tax Rate 1 amount of the bill for which Tax Code 1 is attached as one of the taxes. |
| 690 | tax1RateType | `String` | Tax Rate Type 1 of the bill for which Tax Code 1 is attached as one of the taxes. |
| 691 | tax2Amt | `Float` | Tax2 Amount |
| 692 | tax2No | `String` | Tax2 Number |
| 693 | tax2Rate | `Float` | Tax Rate 2 amount of the bill for which Tax Code 2 is attached as one of the taxes. |
| 694 | tax2RateType | `String` | Tax Rate Type 2 of the bill for which Tax Code 2 is attached as one of the taxes. |
| 695 | taxAmount | `Float` | Tax Amount for Commission. |
| 696 | taxCode | `String` | Internal |
| 697 | taxCode1 | `String` | Tax Code 1 |
| 698 | taxCode10 | `String` | Tax Code 10 |
| 699 | taxCode11 | `String` | Tax Code 11 |
| 700 | taxCode12 | `String` | Tax Code 12 |
| 701 | taxCode13 | `String` | Tax Code 13 |
| 702 | taxCode14 | `String` | Tax Code 14 |
| 703 | taxCode15 | `String` | Tax Code 15 |
| 704 | taxCode16 | `String` | Tax Code 16 |
| 705 | taxCode17 | `String` | Tax Code 17 |
| 706 | taxCode18 | `String` | Tax Code 18 |
| 707 | taxCode19 | `String` | Tax Code 19 |
| 708 | taxCode2 | `String` | Tax Code 2 |
| 709 | taxCode20 | `String` | Tax Code 20 |
| 710 | taxCode3 | `String` | Tax Code 3 |
| 711 | taxCode4 | `String` | Tax Code 4 |
| 712 | taxCode5 | `String` | Tax Code 5 |
| 713 | taxCode6 | `String` | Tax Code 6 |
| 714 | taxCode7 | `String` | Tax Code 7 |
| 715 | taxCode8 | `String` | Tax Code 8 |
| 716 | taxCode9 | `String` | Tax Code 9 |
| 717 | taxCodeDesc1 | `String` | Tax Code Description 1 |
| 718 | taxCodeDesc10 | `String` | Tax Code Description 10 |
| 719 | taxCodeDesc11 | `String` | Tax Code Description 11 |
| 720 | taxCodeDesc12 | `String` | Tax Code Description 12 |
| 721 | taxCodeDesc13 | `String` | Tax Code Description 13 |
| 722 | taxCodeDesc14 | `String` | Tax Code Description 14 |
| 723 | taxCodeDesc15 | `String` | Tax Code Description 15 |
| 724 | taxCodeDesc16 | `String` | Tax Code Description 16 |
| 725 | taxCodeDesc17 | `String` | Tax Code Description 17 |
| 726 | taxCodeDesc18 | `String` | Tax Code Description 18 |
| 727 | taxCodeDesc19 | `String` | Tax Code Description 19 |
| 728 | taxCodeDesc2 | `String` | Tax Code Description 2 |
| 729 | taxCodeDesc20 | `String` | Tax Code Description 20 |
| 730 | taxCodeDesc3 | `String` | Tax Code Description 3 |
| 731 | taxCodeDesc4 | `String` | Tax Code Description 4 |
| 732 | taxCodeDesc5 | `String` | Tax Code Description 5 |
| 733 | taxCodeDesc6 | `String` | Tax Code Description 6 |
| 734 | taxCodeDesc7 | `String` | Tax Code Description 7 |
| 735 | taxCodeDesc8 | `String` | Tax Code Description 8 |
| 736 | taxCodeDesc9 | `String` | Tax Code Description 9 |
| 737 | taxCodeDescription | `String` | Tax Code Description |
| 738 | taxCodeNumber | `Float` | Tax Code Number |
| 739 | taxElements | `String` | Tax Elements |
| 740 | taxId | `String` | Tax ID |
| 741 | taxInvNumber | `String` | Tax Invoice No |
| 742 | taxRate | `Float` | Tax Rate |
| 743 | taxRateType | `String` | Tax Rate Type |
| 744 | tax10Amt | `Float` | Tax10 Amount |
| 745 | tax10Rate | `Float` | Tax Rate 10 amount of the bill for which Tax Code 10  is attached as one of the taxes. |
| 746 | tax10RateType | `String` | Tax Rate Type 10 of the bill for which Tax Code 10 is attached as one of the taxes. |
| 747 | tax11Amt | `Float` | Tax11 Amount |
| 748 | tax11Rate | `Float` | Tax Rate 11 amount of the bill for which Tax Code 11  is attached as one of the taxes. |
| 749 | tax11RateType | `String` | Tax Rate Type 11 of the bill for which Tax Code 11 is attached as one of the taxes. |
| 750 | tax12Amt | `Float` | Tax12 Amount |
| 751 | tax12Rate | `Float` | Tax Rate 12 amount of the bill for which Tax Code 12 is attached as one of the taxes. |
| 752 | tax12RateType | `String` | Tax Rate Type 12 of the bill for which Tax Code 12 is attached as one of the taxes. |
| 753 | tax13Amt | `Float` | Tax13 Amount |
| 754 | tax13Rate | `Float` | Tax Rate 13 amount of the bill for which Tax Code 13 is attached as one of the taxes. |
| 755 | tax13RateType | `String` | Tax Rate Type 13 of the bill for which Tax Code 13 is attached as one of the taxes. |
| 756 | tax14Amt | `Float` | Tax14 Amount |
| 757 | tax14Rate | `Float` | Tax Rate 14 amount of the bill for which Tax Code 14 is attached as one of the taxes. |
| 758 | tax14RateType | `String` | Tax Rate Type 14 of the bill for which Tax Code 14 is attached as one of the taxes. |
| 759 | tax15Amt | `Float` | Tax15 Amount |
| 760 | tax15Rate | `Float` | Tax Rate 15 amount of the bill for which Tax Code 15 is attached as one of the taxes. |
| 761 | tax15RateType | `String` | Tax Rate Type 15 of the bill for which Tax Code 15 is attached as one of the taxes. |
| 762 | tax16Amt | `Float` | Tax16 Amount |
| 763 | tax16Rate | `Float` | Tax Rate 16 amount of the bill for which Tax Code 16 is attached as one of the taxes. |
| 764 | tax16RateType | `String` | Tax Rate Type 16 of the bill for which Tax Code 16 is attached as one of the taxes. |
| 765 | tax17Amt | `Float` | Tax17 Amount |
| 766 | tax17Rate | `Float` | Tax Rate 17 amount of the bill for which Tax Code 17 is attached as one of the taxes. |
| 767 | tax17RateType | `String` | Tax Rate Type 17 of the bill for which Tax Code 17 is attached as one of the taxes. |
| 768 | tax18Amt | `Float` | Tax18 Amount |
| 769 | tax18Rate | `Float` | Tax Rate 18 amount of the bill for which Tax Code 18 is attached as one of the taxes. |
| 770 | tax18RateType | `String` | Tax Rate Type 18 of the bill for which Tax Code 18 is attached as one of the taxes. |
| 771 | tax19Amt | `Float` | Tax19 Amount |
| 772 | tax19Rate | `Float` | Tax Rate 19 amount of the bill for which Tax Code 19 is attached as one of the taxes. |
| 773 | tax19RateType | `String` | Tax Rate Type 19 of the bill for which Tax Code 19 is attached as one of the taxes. |
| 774 | tax20Amt | `Float` | Tax20 Amount |
| 775 | tax20Rate | `Float` | Tax Rate 20 amount of the bill for which Tax Code 20 is attached as one of the taxes. |
| 776 | tax20RateType | `String` | Tax Rate Type 20 of the bill for which Tax Code 20 is attached as one of the taxes. |
| 777 | tax3Amt | `Float` | Tax3 Amount |
| 778 | tax3Rate | `Float` | Tax Rate 3 amount of the bill for which Tax Code 3 is attached as one of the taxes. |
| 779 | tax3RateType | `String` | Tax Rate Type 3 of the bill for which Tax Code 3 is attached as one of the taxes. |
| 780 | tax4Amt | `Float` | Tax4 Amount |
| 781 | tax4Rate | `Float` | Tax Rate 4 amount of the bill for which Tax Code 4 is attached as one of the taxes. |
| 782 | tax4RateType | `String` | Tax Rate Type 4 of the bill for which Tax Code 4 is attached as one of the taxes. |
| 783 | tax5Amt | `Float` | Tax5 Amount |
| 784 | tax5Rate | `Float` | Tax Rate 5 amount of the bill for which Tax Code 5 is attached as one of the taxes. |
| 785 | tax5RateType | `String` | Tax Rate Type 5 of the bill for which Tax Code 5 is attached as one of the taxes. |
| 786 | tax6Amt | `Float` | Tax6 Amount |
| 787 | tax6Rate | `Float` | Tax Rate 6 amount of the bill for which Tax Code 6 is attached as one of the taxes. |
| 788 | tax6RateType | `String` | Tax Rate Type 6 of the bill for which Tax Code 6 is attached as one of the taxes. |
| 789 | tax7Amt | `Float` | Tax7 Amount |
| 790 | tax7Rate | `Float` | Tax Rate 7 amount of the bill for which Tax Code 7 is attached as one of the taxes. |
| 791 | tax7RateType | `String` | Tax Rate Type 7 of the bill for which Tax Code 7 is attached as one of the taxes. |
| 792 | tax8Amt | `Float` | Tax8 Amount |
| 793 | tax8Rate | `Float` | Tax Rate 8 amount of the bill for which Tax Code 8 is attached as one of the taxes. |
| 794 | tax8RateType | `String` | Tax Rate Type 8 of the bill for which Tax Code 8 is attached as one of the taxes. |
| 795 | tax9Amt | `Float` | Tax9 Amount |
| 796 | tax9Rate | `Float` | Tax Rate 9 amount of the bill for which Tax Code 9 is attached as one of the taxes. |
| 797 | tax9RateType | `String` | Tax Rate Type 9 of the bill for which Tax Code 9 is attached as one of the taxes. |
| 798 | taxdeferredflag | `String` | Taxdeferredflag |
| 799 | taxgeneratedflag | `String` | Taxgeneratedflag |
| 800 | tclCode1 | `String` | Class1 Code. |
| 801 | tclCode2 | `String` | Class1 Code. |
| 802 | terminal | `String` | Terminal |
| 803 | thresholdDiversionId | `Float` | Threshold Diversion ID |
| 804 | thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| 805 | thresholdEntityType | `String` | Threshold Entity Type |
| 806 | thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| 807 | toReservationNameId | `Float` | To Resv Name ID |
| 808 | totalGross | `Float` | Total Gross |
| 809 | totalNet | `Float` | Total Net |
| 810 | totalNonTaxable | `Float` | Total non taxable amount. |
| 811 | totalNonrevNonTaxable | `Float` | Total non revenue amount that is non taxable. |
| 812 | totalNonrevTaxable | `Float` | Total non revenue amount that is not taxable. |
| 813 | totalRevNonTaxable | `Float` | Total revenue amount that is non taxable. |
| 814 | totalRevTaxable | `Float` | Total revenue amount that is taxable. |
| 815 | totalTax | `Float` | Total Tax |
| 816 | tranActionId | `Float` | Tran Action ID |
| 817 | transactLastSignatureHash | `String` | Last Signature for Transaction Totals. |
| 818 | transactSignatureHash | `String` | Signature hash for Transaction Totals. |
| 819 | transactSignatureKeyVersion | `String` | Signature key version for Transaction Totals. |
| 820 | transactionAmount | `Float` | Transaction Amount |
| 821 | transactionCode | `String` | Transaction Code |
| 822 | transactionDate | `Date` | Transaction Date |
| 823 | transactionDescription | `String` | Transaction Description |
| 824 | transactionFromAcct | `Float` | Trns From Account |
| 825 | transactionGroupCode | `String` | Transaction Group Code |
| 826 | transactionGroupDescription | `String` | Transaction Group Description |
| 827 | transactionID | `Float` | Transaction ID |
| 828 | transactionSignature | `String` | Transaction Signature Value. |
| 829 | transactionSubGroupCode | `String` | Transaction Sub-Group Code |
| 830 | transactionSubGroupDescription | `String` | Transaction Sub-Group Description |
| 831 | transactionToAcct | `Float` | Trns To Account |
| 832 | transactionType | `String` | Transaction Type |
| 833 | transcodearrangementid | `Float` | Transcodearrangementid |
| 834 | transcodeid | `String` | Transcodeid |
| 835 | transferfromaccountid | `Float` | Transferfromaccountid |
| 836 | transferfromresvid | `Float` | Transferfromresvid |
| 837 | transfertoaccountid | `Float` | Transfertoaccountid |
| 838 | transfertoresvid | `Float` | Transfertoresvid |
| 839 | trialBalanceAmountGross | `Float` | Trial Balance Amount Gross |
| 840 | trialBalanceAmountNet | `Float` | Trial Balance Amount Net |
| 841 | trnsActivityDate | `Date` | Transaction Activity Date |
| 842 | trxAmount | `Float` | Transaction Amount |
| 843 | trxNumberAddedBy | `Float` | Transaction No Added By |
| 844 | trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| 845 | trxNumberHeader | `Float` | Transaction No Header |
| 846 | trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| 847 | trxServiceType | `String` | Transaction Service Type |
| 848 | trxTime | `String` | Transaction Time |
| 849 | trxType | `String` | Transaction type: possible values: [CACH]. |
| 850 | udfc01 | `String` | Udfc01 |
| 851 | udfc02 | `String` | Udfc02 |
| 852 | udfc03 | `String` | Udfc03 |
| 853 | udfc04 | `String` | Udfc04 |
| 854 | udfc05 | `String` | Udfc05 |
| 855 | udfc06 | `String` | Udfc06 |
| 856 | udfc07 | `String` | Udfc07 |
| 857 | udfc08 | `String` | Udfc08 |
| 858 | udfc09 | `String` | Udfc09 |
| 859 | udfc10 | `String` | Udfc10 |
| 860 | udfc11 | `String` | Udfc11 |
| 861 | udfc12 | `String` | Udfc12 |
| 862 | udfc13 | `String` | Udfc13 |
| 863 | udfc14 | `String` | Udfc14 |
| 864 | udfc15 | `String` | Udfc15 |
| 865 | udfc16 | `String` | Udfc16 |
| 866 | udfc17 | `String` | Udfc17 |
| 867 | udfc18 | `String` | Udfc18 |
| 868 | udfc19 | `String` | Udfc19 |
| 869 | udfc20 | `String` | Udfc20 |
| 870 | udfc21 | `String` | Udfc21 |
| 871 | udfc22 | `String` | Udfc22 |
| 872 | udfc23 | `String` | Udfc23 |
| 873 | udfc24 | `String` | Udfc24 |
| 874 | udfc25 | `String` | Udfc25 |
| 875 | udfc26 | `String` | Udfc26 |
| 876 | udfc27 | `String` | Udfc27 |
| 877 | udfc28 | `String` | Udfc28 |
| 878 | udfc29 | `String` | Udfc29 |
| 879 | udfc30 | `String` | Udfc30 |
| 880 | udfc31 | `String` | Udfc31 |
| 881 | udfc32 | `String` | Udfc32 |
| 882 | udfc33 | `String` | Udfc33 |
| 883 | udfc34 | `String` | Udfc34 |
| 884 | udfc35 | `String` | Udfc35 |
| 885 | udfc36 | `String` | Udfc36 |
| 886 | udfc37 | `String` | Udfc37 |
| 887 | udfc38 | `String` | Udfc38 |
| 888 | udfc39 | `String` | Udfc39 |
| 889 | udfc40 | `String` | Udfc40 |
| 890 | udfd01 | `Date` | Udfd01 |
| 891 | udfd02 | `Date` | Udfd02 |
| 892 | udfd03 | `Date` | Udfd03 |
| 893 | udfd04 | `Date` | Udfd04 |
| 894 | udfd05 | `Date` | Udfd05 |
| 895 | udfd06 | `Date` | Udfd06 |
| 896 | udfd07 | `Date` | Udfd07 |
| 897 | udfd08 | `Date` | Udfd08 |
| 898 | udfd09 | `Date` | Udfd09 |
| 899 | udfd10 | `Date` | Udfd10 |
| 900 | udfd11 | `Date` | Udfd11 |
| 901 | udfd12 | `Date` | Udfd12 |
| 902 | udfd13 | `Date` | Udfd13 |
| 903 | udfd14 | `Date` | Udfd14 |
| 904 | udfd15 | `Date` | Udfd15 |
| 905 | udfd16 | `Date` | Udfd16 |
| 906 | udfd17 | `Date` | Udfd17 |
| 907 | udfd18 | `Date` | Udfd18 |
| 908 | udfd19 | `Date` | Udfd19 |
| 909 | udfd20 | `Date` | Udfd20 |
| 910 | udfn01 | `Float` | Udfn01 |
| 911 | udfn02 | `Float` | Udfn02 |
| 912 | udfn03 | `Float` | Udfn03 |
| 913 | udfn04 | `Float` | Udfn04 |
| 914 | udfn05 | `Float` | Udfn05 |
| 915 | udfn06 | `Float` | Udfn06 |
| 916 | udfn07 | `Float` | Udfn07 |
| 917 | udfn08 | `Float` | Udfn08 |
| 918 | udfn09 | `Float` | Udfn09 |
| 919 | udfn10 | `Float` | Udfn10 |
| 920 | udfn11 | `Float` | Udfn11 |
| 921 | udfn12 | `Float` | Udfn12 |
| 922 | udfn13 | `Float` | Udfn13 |
| 923 | udfn14 | `Float` | Udfn14 |
| 924 | udfn15 | `Float` | Udfn15 |
| 925 | udfn16 | `Float` | Udfn16 |
| 926 | udfn17 | `Float` | Udfn17 |
| 927 | udfn18 | `Float` | Udfn18 |
| 928 | udfn19 | `Float` | Udfn19 |
| 929 | udfn20 | `Float` | Udfn20 |
| 930 | udfn21 | `Float` | Udfn21 |
| 931 | udfn22 | `Float` | Udfn22 |
| 932 | udfn23 | `Float` | Udfn23 |
| 933 | udfn24 | `Float` | Udfn24 |
| 934 | udfn25 | `Float` | Udfn25 |
| 935 | udfn26 | `Float` | Udfn26 |
| 936 | udfn27 | `Float` | Udfn27 |
| 937 | udfn28 | `Float` | Udfn28 |
| 938 | udfn29 | `Float` | Udfn29 |
| 939 | udfn30 | `Float` | Udfn30 |
| 940 | udfn31 | `Float` | Udfn31 |
| 941 | udfn32 | `Float` | Udfn32 |
| 942 | udfn33 | `Float` | Udfn33 |
| 943 | udfn34 | `Float` | Udfn34 |
| 944 | udfn35 | `Float` | Udfn35 |
| 945 | udfn36 | `Float` | Udfn36 |
| 946 | udfn37 | `Float` | Udfn37 |
| 947 | udfn38 | `Float` | Udfn38 |
| 948 | udfn39 | `Float` | Udfn39 |
| 949 | udfn40 | `Float` | Udfn40 |
| 950 | updTimestamp | `DateTime` | Timestamp to capture the exact order of updates. |
| 951 | updateDate | `DateTime` | Update Date |
| 952 | updateUser | `Float` | Update User |
| 953 | upsellChargeYn | `String` | Flag to identify an Upsell posting. |
| 954 | vatOffsetYn | `String` | Vat Offset Y/N |
| 955 | voidNo | `Float` | Void Number |
| 956 | voidReason | `String` | This column will store the reason for voiding the folio. |
| 957 | workingDocId | `Float` | Working Doc ID |
| 958 | wrapperTransactionID | `Float` | Wrapper Transaction ID |
| 959 | xnet1Amt | `Float` | Xnet1 Amount |
| 960 | xnet10Amt | `Float` | Xnet10 Amount |
| 961 | xnet11Amt | `Float` | Xnet11 Amount |
| 962 | xnet12Amt | `Float` | Xnet12 Amount |
| 963 | xnet13Amt | `Float` | Xnet13 Amount |
| 964 | xnet14Amt | `Float` | Xnet14 Amount |
| 965 | xnet15Amt | `Float` | Xnet15 Amount |
| 966 | xnet16Amt | `Float` | Xnet16 Amount |
| 967 | xnet17Amt | `Float` | Xnet17 Amount |
| 968 | xnet18Amt | `Float` | Xnet18 Amount |
| 969 | xnet19Amt | `Float` | Xnet19 Amount |
| 970 | xnet2Amt | `Float` | Xnet2 Amount |
| 971 | xnet20Amt | `Float` | Xnet20 Amount |
| 972 | xnet3Amt | `Float` | Xnet3 Amount |
| 973 | xnet4Amt | `Float` | Xnet4 Amount |
| 974 | xnet5Amt | `Float` | Xnet5 Amount |
| 975 | xnet6Amt | `Float` | Xnet6 Amount |
| 976 | xnet7Amt | `Float` | Xnet7 Amount |
| 977 | xnet8Amt | `Float` | Xnet8 Amount |
| 978 | xnet9Amt | `Float` | Xnet9 Amount |
| 979 | xtax1Amt | `Float` | Total tax1 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 980 | xtax10Amt | `Float` | Total tax10 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 981 | xtax11Amt | `Float` | Total tax11 amount extension to the existing xtax amounts. |
| 982 | xtax12Amt | `Float` | Total tax12 amount extension to the existing xtax amounts. |
| 983 | xtax13Amt | `Float` | Total tax13 amount extension to the existing xtax amounts. |
| 984 | xtax14Amt | `Float` | Total tax14 amount extension to the existing xtax amounts. |
| 985 | xtax15Amt | `Float` | Total tax15 amount extension to the existing xtax amounts. |
| 986 | xtax16Amt | `Float` | Total tax16 amount extension to the existing xtax amounts. |
| 987 | xtax17Amt | `Float` | Total tax17 amount extension to the existing xtax amounts. |
| 988 | xtax18Amt | `Float` | Total tax18 amount extension to the existing xtax amounts. |
| 989 | xtax19Amt | `Float` | Total tax19 amount extension to the existing xtax amounts. |
| 990 | xtax2Amt | `Float` | Total tax2 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 991 | xtax20Amt | `Float` | Total tax20 amount extension to the existing xtax amounts. |
| 992 | xtax3Amt | `Float` | Total tax3 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 993 | xtax4Amt | `Float` | Total tax4 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 994 | xtax5Amt | `Float` | Total tax5 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 995 | xtax6Amt | `Float` | Total tax6 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 996 | xtax7Amt | `Float` | Total tax7 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 997 | xtax8Amt | `Float` | Total tax8 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 998 | xtax9Amt | `Float` | Total tax9 amount. Tax1 thru Tax10 are the codes that can be given to 10 different tax transaction codes in the setup. |
| 999 | zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### EFolioPropertyExportValuesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRAccountNumberMandYN | `String` | Specifies if the AR acct No is mandatory(Y/N) |
| 2 | aRBalanceTrxCode | `String` | Internal |
| 3 | aRCreditTrxCode | `String` | Internal |
| 4 | additionalLogos | `String` | Additional Logos |
| 5 | address | `String` | Address |
| 6 | agingLevel1 | `Float` | Aging bucket 1 |
| 7 | agingLevel2 | `Float` | Aging bucket 2 |
| 8 | agingLevel3 | `Float` | Aging bucket 3 |
| 9 | agingLevel4 | `Float` | Aging bucket 4 |
| 10 | agingLevel5 | `Float` | Aging bucket 5 |
| 11 | airport | `String` | The Airport Code for the airport near the property |
| 12 | airportDistance | `String` | Distance of the Airport specified in the AIRPORT_CODE column from the Property |
| 13 | airportTime | `String` | Time it takes to travel the distance between the Property and the Airport specified in AIRPORT_CODE column |
| 14 | allowLoginYn | `String` | Allow loggin in to this resort(Y/N) |
| 15 | allowancePeriodAdj | `String` | Period for the allowance |
| 16 | arAccountNumberFormat | `String` | Number format of AR account no. |
| 17 | arAgent | `String` | Default Account Type for an Agent for the Property |
| 18 | arCompany | `String` | Default Account Type for a Company for the Property |
| 19 | arGroups | `String` | Default Account Type for a Group for the Property |
| 20 | arIndividuals | `String` | Default Account Type for Individual for the Property |
| 21 | arSettleCode | `String` | Internal |
| 22 | arTypewriter | `String` | Internal |
| 23 | awardsTimeout | `Float` | Internal |
| 24 | bIC | `String` | BIC |
| 25 | bankAgencyCode | `String` | Bank Agency Code |
| 26 | bankAgencyName | `String` | Bank Agency Name |
| 27 | bankCode | `String` | Code for the bank account |
| 28 | bankName | `String` | Bank name |
| 29 | baseLanguage | `String` | The base language of the Hotel |
| 30 | beginDate | `Date` | Begin Date |
| 31 | block | `String` | Block |
| 32 | brArea | `String` | Ball Room Area |
| 33 | brSeats | `Float` | No of Ballroom Seats |
| 34 | brandCode | `String` | Brand Code |
| 35 | budgetMonth | `Float` | Financial Year of the Property |
| 36 | cROCode | `String` | CRO Code |
| 37 | cRSResort | `String` | Not used |
| 38 | cashShiftDrop | `String` | Internal |
| 39 | centralPropertyType | `String` | Central Property Type |
| 40 | chainCode | `String` | Chain Code |
| 41 | chainDescription | `String` | Chain Description |
| 42 | checkExgPaidout | `String` | Internal |
| 43 | checkInTime | `Date` | The Hotel official check intime |
| 44 | checkOutTime | `Date` | The Hotel official check out time |
| 45 | checkShiftDrop | `String` | Internal |
| 46 | checkTrxcode | `String` | Internal |
| 47 | city | `String` | City |
| 48 | cityDescription | `String` | City Description. |
| 49 | clientBookingReference | `String` | Client Booking Reference |
| 50 | comAddress | `String` | Communication Address for Contact 1 (E-mail / Fax #) |
| 51 | comMethod | `String` | How this lead is to be sent. [EMAIL|FAX|PRINT] |
| 52 | company | `String` | Company |
| 53 | companyAddressType | `String` | Internal |
| 54 | companyCapitalAmount | `String` | Company Capital Amount |
| 55 | companyCity | `String` | Company City |
| 56 | companyCountryName | `String` | Company Country Name |
| 57 | companyIMOBody | `String` | Company IMO Body |
| 58 | companyLegalText | `String` | Company Legal Text |
| 59 | companyNAF | `String` | Company NAF |
| 60 | companyPhoneType | `String` | Internal |
| 61 | companyRCS | `String` | Company RCS |
| 62 | companySiret | `String` | Company Siret |
| 63 | companyTypeBody | `String` | The type of legal entity / company e.g. Individual Micro enterprise etc. |
| 64 | configurationMode | `String` | Internal |
| 65 | confirmRegcardPrinter | `String` | Internal |
| 66 | copies | `Float` | Copies |
| 67 | country | `String` | Country |
| 68 | countryCode | `String` | Country Code |
| 69 | countryName | `String` | Country Name |
| 70 | creditLimit | `Float` | Credit Limit |
| 71 | currencyCode | `String` | Currency Code |
| 72 | currencyDecimals | `Float` | Number of decimals to designate currency |
| 73 | currencyDescription | `String` | Currency Description |
| 74 | currencyExgPaidout | `String` | Not used |
| 75 | currencySymbol | `String` | Currency Symbol like $ or EURO symbol |
| 76 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 77 | dateForAging | `String` | Date the aging should begin |
| 78 | dateSeparator | `String` | Type of separator to distinguish between DD MM and YYYY |
| 79 | dblNum | `String` | Not used |
| 80 | dblRate2 | `Float` | Not used |
| 81 | dblRate1 | `Float` | Not used |
| 82 | decimalPlaces | `Float` | Number of places for the default currency |
| 83 | decimalSeparator | `String` | Type of decimal separator |
| 84 | defaultCommissionPercentage | `String` | Not used |
| 85 | defaultFaxType | `String` | Not used |
| 86 | defaultFolioStyle | `Float` | Folio style to be used for all guests |
| 87 | defaultGroupsRateCode | `String` | Not used |
| 88 | defaultGuestAddress | `String` | Default guest address format. |
| 89 | defaultMembershipType | `String` | Future use |
| 90 | defaultPostingRoom | `String` | Future use |
| 91 | defaultPrepaidComm | `String` | Not used. |
| 92 | defaultPrinter | `String` | Not Used |
| 93 | defaultPropertyAddress | `String` | Default property address format. |
| 94 | defaultRateCode | `String` | Default rate code to be used to calculate the total revenue. |
| 95 | defaultRegistrationCard | `String` | Default registration card for the property. |
| 96 | defaultReservationType | `String` | The Default reservation type for this property |
| 97 | defaultTrxCommissionCode | `String` | Not used. |
| 98 | depositLedgerTrxCode | `String` | Future use |
| 99 | dfltPkgTranCode | `String` | Future use |
| 100 | dfltTranCodeRateCode | `String` | Future use |
| 101 | dirsales | `String` | Future use |
| 102 | dutyManagerPager | `String` | Pager number for the Manager on duty for the property. |
| 103 | email | `String` | Email |
| 104 | endDate | `Date` | End Date |
| 105 | exchangePostingType | `String` | Exchange Posting Type |
| 106 | expiryDate | `Date` | Expiry Date |
| 107 | extPropertyCode | `String` | Future use |
| 108 | fax | `String` | Fax |
| 109 | faxNoFormat | `String` | Fax number formats. |
| 110 | fileTransferFormat | `String` | Not used. |
| 111 | fiscalEndDate | `Date` | Future use |
| 112 | fiscalPeriodType | `String` | Future use |
| 113 | fiscalStartDate | `Date` | Future use |
| 114 | fiscalStartMonth | `Float` | Fiscal Start Month |
| 115 | fiscalStartYear | `Float` | Fiscal Start Year |
| 116 | flowCode | `String` | Future use |
| 117 | folioLanguage1 | `String` | Other languages |
| 118 | folioLanguage2 | `String` | Other languages |
| 119 | folioLanguage3 | `String` | Other languages |
| 120 | folioLanguage4 | `String` | Other languages |
| 121 | font | `Float` | Not used |
| 122 | footerLegalText1 | `String` | Footer Legal Text1 |
| 123 | footerLegalText2 | `String` | Footer Legal Text2 |
| 124 | footerLegalText3 | `String` | Footer Legal Text3 |
| 125 | genmgr | `String` | Future use |
| 126 | groupRoomWarning | `Float` | To define an upper limit to the number of rooms for Group |
| 127 | guarantorAddress | `String` | Guarantor Address |
| 128 | guestLookupTimeout | `Float` | Future use |
| 129 | hotelFc | `String` | Future use |
| 130 | hotelId | `String` | Hotel ID |
| 131 | hotelType | `String` | Hotel Type |
| 132 | iBAN | `String` | IBAN |
| 133 | imgDirectionId | `Float` | Future use |
| 134 | imgHotelId | `Float` | Future use |
| 135 | imgMapId | `Float` | Future use |
| 136 | inactiveDaysForGuestProfil | `Float` | Future use |
| 137 | individualAddressType | `String` | Future use |
| 138 | individualPhoneType | `String` | Future use |
| 139 | individualRoomWarning | `Float` | To define an upper limit to the number of rooms for group |
| 140 | insertDate | `DateTime` | Insert Date |
| 141 | insertUser | `Float` | Insert User |
| 142 | insurerAddressBody | `String` | Insurer Address Body |
| 143 | internalLocationId | `String` | Location ID |
| 144 | internalOrganizationId | `Float` | Organization ID |
| 145 | inventoryYn | `String` | Indicates if the Resources under this Type need to maintain inventory. |
| 146 | jRNUpdateDate | `Date` | JRN Update Date |
| 147 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 148 | keepAvailability | `Float` | To calculate the entire availability of the Hotel for future reservations |
| 149 | layoutTemplate | `String` | Layout Template |
| 150 | leadsend | `String` | Name of Contact 1 (Free text or from RESORT_CONTACTS) |
| 151 | legalOwner | `String` | The owner who owns this property |
| 152 | licenseCode | `String` | License Code |
| 153 | localCurrencyFormat | `String` | Format for the local currency. |
| 154 | locationID | `String` | Internal ID to uniquely identify the Property |
| 155 | longDateFormat | `String` | Long date format for the property. |
| 156 | longStayControl | `Float` | The default length of stay |
| 157 | marketingText | `String` | Marketing Text |
| 158 | maxNoNights | `Float` | Not used |
| 159 | maxOccupancy | `Float` | Max Occupancy |
| 160 | meetRooms | `Float` | Future use |
| 161 | meetSeats | `Float` | Future use |
| 162 | meetSpace | `Float` | Future use |
| 163 | meetingFc | `String` | Future use |
| 164 | minDaysBet2ReminderLetter | `Float` | Minimum days for reminder letter. |
| 165 | nameIdLink | `Float` | Internal |
| 166 | nightAuditCashierId | `String` | Future use |
| 167 | notes | `String` | Notes |
| 168 | numberBeds | `Float` | Total number of beds in this property |
| 169 | numberFloors | `Float` | Total number of floors in this property |
| 170 | numberRooms | `Float` | Number Rooms |
| 171 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 172 | ownership | `String` | Future use |
| 173 | packageLoss | `String` | Package Loss code for a particular package |
| 174 | packageProfit | `String` | Package Profit code for a particular Package |
| 175 | passerbyMarket | `String` | Market code for passerby |
| 176 | passerbySource | `String` | Source code for passerby |
| 177 | perReservationRoomLimit | `Float` | Future use |
| 178 | postCode | `String` | Post Code |
| 179 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 180 | property | `String` | Property |
| 181 | propertyName | `String` | Property Name |
| 182 | propertyType | `String` | Property Type |
| 183 | quotedCurrency | `String` | Future use |
| 184 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 185 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 186 | repPasserbyMarket | `String` | Reporting Passerby Market |
| 187 | repPasserbySource | `String` | Reporting Passerby Source |
| 188 | repState | `String` | Reporting State |
| 189 | repStateDescription | `String` | Reporting State Desc |
| 190 | restaurant | `Float` | Future use |
| 191 | rhythmSheets | `Float` | Total number of Sheets |
| 192 | rhythmTowels | `Float` | Total number of Towels |
| 193 | saveProfiles | `Float` | To store number of days before deleting the gest profile |
| 194 | scriptId | `Float` | Script ID |
| 195 | season1 | `String` | Future use |
| 196 | season2 | `String` | Future use |
| 197 | season3 | `String` | Future use |
| 198 | season4 | `String` | Future use |
| 199 | season5 | `String` | Future use |
| 200 | sglNum | `String` | Future use |
| 201 | sglRate1 | `Float` | Future use |
| 202 | sglRate2 | `Float` | Future use |
| 203 | shortDateFormat | `String` | Short date format for the property. |
| 204 | sourceCommission | `String` | For default commission percentage |
| 205 | state | `String` | State |
| 206 | stateDesc | `String` | State Description of the Guest of Payee |
| 207 | street | `String` | The street of the property. |
| 208 | suiNum | `String` | Future use |
| 209 | suiRate1 | `Float` | Future use |
| 210 | suiRate2 | `Float` | Future use |
| 211 | summCurrencyCode | `String` | Internal |
| 212 | taCommission | `String` | For default commission percentage |
| 213 | taxID | `String` | Tax ID |
| 214 | telephone | `String` | The direct dial phone number of this property |
| 215 | telephoneNoFormat | `String` | Formats for telephone number |
| 216 | thousandSeparator | `String` | Separator for monetory values |
| 217 | timeFormat | `String` | Default time format for the property. |
| 218 | tollfree | `String` | Toll free telephone number. |
| 219 | totalRooms | `Float` | Future use |
| 220 | tplNum | `String` | Future use |
| 221 | tplRate1 | `Float` | Future use |
| 222 | tplRate2 | `Float` | Future use |
| 223 | turnawayCode | `String` | Turnaway Code |
| 224 | unitAddress | `String` | Unit Address |
| 225 | unitBrand | `String` | Unit Brand |
| 226 | unitCity | `String` | Unit City |
| 227 | unitCountry | `String` | Unit Country |
| 228 | unitCountryName | `String` | Unit Country Name |
| 229 | unitFax | `String` | Unit Fax |
| 230 | unitMail | `String` | Unit Mail |
| 231 | unitName | `String` | Unit Name |
| 232 | unitPhone | `String` | Unit Phone |
| 233 | unitType | `String` | Unit of measure. Values are Mile or KM or Block. |
| 234 | unitWeb | `String` | Unit Web |
| 235 | unitZIP | `String` | Unit Zipcode |
| 236 | updateDate | `DateTime` | Update Date |
| 237 | updateUser | `Float` | Update User |
| 238 | vAT1 | `String` | VAT1 |
| 239 | vAT10 | `String` | VAT10 |
| 240 | vAT11 | `String` | VAT11 |
| 241 | vAT12 | `String` | VAT12 |
| 242 | vAT13 | `String` | VAT13 |
| 243 | vAT14 | `String` | VAT14 |
| 244 | vAT15 | `String` | VAT15 |
| 245 | vAT16 | `String` | VAT16 |
| 246 | vAT17 | `String` | VAT17 |
| 247 | vAT18 | `String` | VAT18 |
| 248 | vAT19 | `String` | VAT19 |
| 249 | vAT2 | `String` | VAT2 |
| 250 | vAT20 | `String` | VAT20 |
| 251 | vAT3 | `String` | VAT3 |
| 252 | vAT4 | `String` | VAT4 |
| 253 | vAT5 | `String` | VAT5 |
| 254 | vAT6 | `String` | VAT6 |
| 255 | vAT7 | `String` | VAT7 |
| 256 | vAT8 | `String` | VAT8 |
| 257 | vAT9 | `String` | VAT9 |
| 258 | videoCoStart | `Date` | Video check out start time. |
| 259 | videoCoStop | `Date` | Video check out end time. |
| 260 | videocheckoutPrinter | `String` | Future use |
| 261 | wakeUpDelay | `Float` | Future use |
| 262 | warningAmount | `Float` | Amount at which warning is raised. |
| 263 | webaddress | `String` | Webaddress of the property |
| 264 | weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| 265 | zeroInvPurDays | `Float` | Internal |

[⬆ Back to Query](#query)

---

### EFolioProfileAllInformationDetailsType

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

### EFolioProfileAddressDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | address1 | `String` | The first line of street address. |
| 2 | address2 | `String` | The second line of street address. |
| 3 | address3 | `String` | The third line of street address. |
| 4 | address4 | `String` | The fourth line of street address. |
| 5 | addressID | `Float` | The primary key for this table. |
| 6 | addressLanguage | `String` | Address Language |
| 7 | addressLanguageDescription | `String` | Description for each language code. |
| 8 | addressType | `String` | The type of address. |
| 9 | addressTypeDesc | `String` | The description of this value. |
| 10 | barcode | `String` | The postal barcode for the address. |
| 11 | beginDate | `Date` | Not used. |
| 12 | centralState | `String` | Central State |
| 13 | centralStateDescription | `String` | Central State Description |
| 14 | chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| 15 | city | `String` | The city for this address. |
| 16 | cleansedDatetime | `DateTime` | The Timestamp when this record was cleansed. |
| 17 | cleansedErrormsg | `String` | The error message why this record was not cleansed. |
| 18 | cleansedMatchstatus | `String` | Specifies how the address elements match with the postal reference data. |
| 19 | cleansedStatus | `String` | Status of Address Cleansing. Null = Record is not cleansed. C = Cleansed. F = Failure. |
| 20 | cleansedValidationstatus | `String` | Validation Status as returned by the Address Cleansing System. |
| 21 | clientID | `String` | The unique key of this name stores IATA# Company # etc. |
| 22 | countryCode | `String` | Country . |
| 23 | countryDescription | `String` | Country name. |
| 24 | createdByUser | `Float` | The user that created the record |
| 25 | createdOnDate | `DateTime` | The date the record was created |
| 26 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 27 | deletedYN | `String` | Deleted Y/n |
| 28 | endDate | `Date` | Not used. |
| 29 | firstName | `String` | The first name of an individual name. |
| 30 | foreignCountry | `String` | Not used. |
| 31 | inCareOf | `String` | Not used. |
| 32 | inactiveDate | `DateTime` | The date the record was marked as inactive |
| 33 | inactiveYN | `String` | Inactive Y/n |
| 34 | internalOrganizationId | `Float` | Organization ID |
| 35 | jRNUpdateDate | `Date` | JRN Update Date |
| 36 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 37 | laptopChange | `Float` | Code to synchronize with Laptop. (not used) |
| 38 | lastUpdatedResort | `String` | Last property that updated this record. |
| 39 | name | `String` | Name |
| 40 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 41 | postalCode | `String` | The postal code of this address. |
| 42 | postalCodeExtension | `String` | City Extension mainly used for UK addresses. |
| 43 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 44 | primaryYN | `String` | Profile having Multiple Addresses Need to have one Primary Address for each Type. |
| 45 | profileAddressId | `Float` | The primary key for this table. |
| 46 | profileId | `Float` | The reference to the NAME record that owns this address. |
| 47 | profileIdx | `Float` | The reference to the NAME record that owns this address. |
| 48 | province | `String` | Province. |
| 49 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 50 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 51 | state | `String` | State |
| 52 | stateCode | `String` | The state of this address. |
| 53 | updateDate | `DateTime` | The date the record was modified |
| 54 | updateUser | `Float` | The user that modified the record |

[⬆ Back to Query](#query)

---

### EFolioProfileCommunicationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | addressId | `Float` | Not used. |
| 2 | beginDate | `Date` | Not used. |
| 3 | chainCode | `String` | The Chain code of the chain for which this record belongs to. |
| 4 | communicationID | `Float` | The primary key for this table. |
| 5 | communicationRole | `String` | Role in which this phone type belongs to. |
| 6 | communicationValue | `String` | The phone number for this record |
| 7 | countryCode | `String` | Country Code of the phone number. |
| 8 | countryDialingCode | `Float` | Numeric phone dialing prefix code for the country. |
| 9 | countryId | `String` | Country Code of the phone number. |
| 10 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 11 | defaultMethodYN | `String` | Phone_role to be used for default confirmation. |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | displaySequence | `Float` | Order in which the phone numbers should be displayed. |
| 14 | emailFormat | `String` | Format type for email messages: HTML PLAIN text. |
| 15 | emailLanguage | `String` | Optional language for e-mail. |
| 16 | endDate | `Date` | The date this record becomes invalid for use in the system. User enterable. |
| 17 | extension | `String` | Telephone Extension. |
| 18 | firstName | `String` | The first name of an individual name. |
| 19 | inactiveDate | `DateTime` | The date the record was marked as inactive |
| 20 | inactiveFlag | `String` | Inactive Flag |
| 21 | indexPhone | `String` | Index Phone |
| 22 | insertDate | `DateTime` | The date the record was created |
| 23 | insertUser | `Float` | The user that created the record |
| 24 | internalOrganizationId | `Float` | Organization ID |
| 25 | internalProfileId | `Float` | The reference to the name that owns this phone. |
| 26 | jRNUpdateDate | `Date` | JRN Update Date |
| 27 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 28 | laptopChange | `Float` | Code to synchronize with Laptop |
| 29 | lastName | `String` | The last name of the individual Profile and Search name ofr the other Types of Profiles (Group Travel Agent & Source) are stored in this column. |
| 30 | mobileAudioKeyYn | `String` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| 31 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 32 | phoneId | `Float` | The primary key for this table. |
| 33 | phoneType | `String` | The type of this phone number. |
| 34 | phoneTypeDescription | `String` | Description of Phone Types. |
| 35 | phoneTypeId | `String` | The type of this phone number. |
| 36 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 37 | primaryYN | `String` | Indicates the primary telephone number in the case of multiple phone numbers on a profile. |
| 38 | profileID | `Float` | The reference to the name that owns this phone. |
| 39 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 40 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 41 | shareEmailYn | `String` | Used for uploading the email to holidex if the value is Y. |
| 42 | updateDate | `DateTime` | The date the record was modified |
| 43 | updateUser | `Float` | The user that modified the record |
| 44 | validYn | `String` | Indicates that the phone number has been validated using the Starwood API and is determined to be valid a <NULL> value indicates that the phone number has not been validated. |

[⬆ Back to Query](#query)

---

### EFolioReservationDetailsType

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

### EFolioFiscalCalendarDetailsType

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

### EFolioGregerianCalendarDetailsType

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

### EFolioExportMapEfolioExportDetailsType

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
| 10 | configType | `String` | Config Type |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | dataType | `String` | Data Type |
| 13 | deletedFlag | `String` | Deleted Flag |
| 14 | exportMappingId | `Float` | Exp Mapping ID |
| 15 | exportValue | `String` | Code to be sent in the export. |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | linkInsertDate | `DateTime` | Link Insert Date |
| 19 | linkInsertUser | `Float` | Link Insert User |
| 20 | linkInsertUserName | `String` | Link Insert User Name |
| 21 | linkUpdateDate | `DateTime` | Link Update Date |
| 22 | linkUpdateUser | `Float` | Link Update User |
| 23 | linkUpdateUserName | `String` | Link Update User Name |
| 24 | linkedCode | `String` | Code of the configuration item to which this mapping type is linked e.g. financial transaction code. |
| 25 | linkedDescription | `String` | Linked Description |
| 26 | locationID | `String` | Internal ID to uniquely identify the Property |
| 27 | lovName | `String` | Name of the LOV group to be used (from Screen Design) |
| 28 | mappedToDesc | `String` | Mapped To Description |
| 29 | mappingCode | `String` | Code for the mapping code. |
| 30 | mappingCodeDescription | `String` | Description for the mapping code. |
| 31 | mappingType | `String` | Mapping Type |
| 32 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 33 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 34 | property | `String` | Code to uniquely identify the Property |
| 35 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 36 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 37 | requiredYn | `String` | Required Y/N |
| 38 | seqNumber | `Float` | Sequence No |
| 39 | shortColumnTitle | `String` | Short text for column headers while configuring consolidated export mapping. |
| 40 | trxCode | `String` | Transaction Code |
| 41 | typeCanDeleteYn | `String` | Type Can Delete Y/N |
| 42 | typeDesc | `String` | Type Description |
| 43 | typeInsertDate | `DateTime` | Type Insert Date |
| 44 | typeInsertUser | `Float` | Type Insert User |
| 45 | typeInsertUserName | `String` | Type Insert User Name |
| 46 | typeUpdateDate | `DateTime` | Type Update Date |
| 47 | typeUpdateUser | `Float` | Type Update User |
| 48 | typeUpdateUserName | `String` | Type Update User Name |
| 49 | useLovYn | `String` | Show LOV button when linking this mapping code to the configuration item. |

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
#### Validation Rules

**`mandatoryInput`**
- foliotaxDetailsBillGenerationDate
- foliotaxDetailsResort


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

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
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
    'organizationID': pl.Int64,
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
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
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
```
```python
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
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
    'organizationID': pl.Int64,
    'ownership': pl.Utf8,
    'packageLoss': pl.Utf8,
    'packageProfit': pl.Utf8,
    'passerbyMarket': pl.Utf8,
    'passerbySource': pl.Utf8,
    'perReservationRoomLimit': pl.Float64,
    'postCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
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
    'dSI': pl.Int64,
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
    'organizationID': pl.Int64,
    'postalCode': pl.Utf8,
    'postalCodeExtension': pl.Utf8,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
}
```
```python
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
    'internalOrganizationId': pl.Float64,
    'internalProfileId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopChange': pl.Float64,
    'lastName': pl.Utf8,
    'mobileAudioKeyYn': pl.Utf8,
    'organizationID': pl.Int64,
    'phoneId': pl.Float64,
    'phoneType': pl.Utf8,
    'phoneTypeDescription': pl.Utf8,
    'phoneTypeId': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'primaryYN': pl.Utf8,
    'profileID': pl.Float64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'shareEmailYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'validYn': pl.Utf8,
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
    'mappedToDesc': pl.Utf8,
    'mappingCode': pl.Utf8,
    'mappingCodeDescription': pl.Utf8,
    'mappingType': pl.Utf8,
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