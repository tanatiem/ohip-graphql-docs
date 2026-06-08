# FinancialTransactionCodes
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template) | [Parquet Schema](#parquet-schema)
## Query
### `financialTransactionCodes`
> Transaction code header details including flags group and sub-group details.
  
**Return:** [`[FinancialTransactionCodesType]`](#financialtransactioncodestype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`FinancialTransactionCodesQueryArgumentsType!`](#financialtransactioncodesqueryargumentstype) |  |

## Object Types

### FinancialTransactionCodesType

| Field | Type | Description |
| --- | --- | --- |
| transactionCodeDetails | [`FinancialTransactionCodesTransactionCodeDetailsType`](#financialtransactioncodestransactioncodedetailstype) | Transaction Code |
| transactionGroupDetails | [`FinancialTransactionCodesTransactionGroupDetailsType`](#financialtransactioncodestransactiongroupdetailstype) | Transaction Group |
| transactionSubgroupDetails | [`FinancialTransactionCodesTransactionSubgroupDetailsType`](#financialtransactioncodestransactionsubgroupdetailstype) | Transaction Subgroup |
| transactionCodeArrangmentDetails | [`FinancialTransactionCodesTransactionCodeArrangmentDetailsType`](#financialtransactioncodestransactioncodearrangmentdetailstype) | Transaction Code Arrangment |
| propertyPropertyDetails | [`FinancialTransactionCodesPropertyPropertyDetailsType`](#financialtransactioncodespropertypropertydetailstype) | Resort Details |
| financialTransactionCodesRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### FinancialTransactionCodesTransactionCodeDetailsType

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

### FinancialTransactionCodesTransactionGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralDescription | `String` | Central Description |
| centralDisplaySequence | `Float` | Central Display Sequence |
| centralTransactionCodeGroup | `String` | Central Transaction Code Group |
| class1MandatoryYn | `String` | Class 1 Mandatory Y/N |
| class2MandatoryYn | `String` | Class 2 Mandatory Y/N |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displaySequence | `Float` | Display Sequence |
| inactiveflag | `String` | Inactive Flag |
| indRevenueGroup | `String` | Individual Revenue Gp |
| indicatorRevenueGroup | `String` | Indicator Revenue Group |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| internalYn | `String` | Internal Y/N |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| resultIncludedInSumArray | `String` | Result Included In Sum Array |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| tctClassType1 | `String` | Not Used. |
| tctClassType2 | `String` | Not Used. |
| transactionCodeActivityType | `String` | Transaction Code Activity Type |
| transactionCodeGroup | `String` | Transaction Code Group |
| transgroupid | `String` | Transgroupid |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionCodesTransactionSubgroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralDescription | `String` | Central Description |
| centralDisplaySequence | `Float` | Central Display Sequence |
| centralGroup | `String` | Central Group |
| centralTransactionCodeSubGroup | `String` | Central Transaction Code Sub-Group |
| class1MandatoryYn | `String` | Class 1 Mandatory Y/N |
| class2MandatoryYn | `String` | Class 2 Mandatory Y/N |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displaySequence | `Float` | Display Sequence |
| frequentFlyerYn | `String` | Frequent Flyer Y/N |
| group | `String` | Group |
| groupPointsRedemptionYN | `String` | Gp Points Redemption Y/N |
| inactiveflag | `String` | Inactive Flag |
| indRevenueGroup | `String` | Individual Revenue Gp |
| indicatorRevenueGroup | `String` | Indicator Revenue Group |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| internalYn | `String` | Internal Y/N |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| resultIncludedInSumArray | `String` | Result Included In Sum Array |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| subGroupType | `String` | Sub-Group level code to group all attached transaction codes into one of the different pre-defined categories. |
| taxFlagYN | `String` | Tax YN |
| taxYN | `String` | Not Used. |
| tcGroupAndSubgroup | `String` | Transaction Code Group And Subgroup |
| tcTransactionType | `String` | Transaction Code Transaction Type |
| transactionCodeSubGroup | `String` | Transaction Code Sub-Group |
| transgroupid | `String` | Transgroupid |
| transsubgroupid | `String` | Transsubgroupid |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### FinancialTransactionCodesTransactionCodeArrangmentDetailsType

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

### FinancialTransactionCodesPropertyPropertyDetailsType

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

### FinancialTransactionCodesQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| transcodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| transcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| transcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| transcodeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| transcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| transcodeDetailsResort | `StringInput!` | Property<br>`@mandatoryInput` |
| transcodeDetailsTranscodeid | `StringInput` | Transcodeid |
| transcodeDetailsTrxCode | `StringInput` | Trx Code |
| transgroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| transsubgroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
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
query financialTransactionCodes($input: FinancialTransactionCodesQueryArgumentsType!) {
  financialTransactionCodes(input: $input) @stream {
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
    transactionGroupDetails {
      centralDescription
      centralDisplaySequence
      centralTransactionCodeGroup
      class1MandatoryYn
      class2MandatoryYn
      dSI
      deletedFlag
      description
      displaySequence
      inactiveflag
      indRevenueGroup
      indicatorRevenueGroup
      insertDate
      insertUser
      internalDeletedflag
      internalYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      resultIncludedInSumArray
      rnaInsertDate
      rnaUpdateDate
      tctClassType1
      tctClassType2
      transactionCodeActivityType
      transactionCodeGroup
      transgroupid
      type
      updateDate
      updateUser
    }
    transactionSubgroupDetails {
      centralDescription
      centralDisplaySequence
      centralGroup
      centralTransactionCodeSubGroup
      class1MandatoryYn
      class2MandatoryYn
      dSI
      deletedFlag
      description
      displaySequence
      frequentFlyerYn
      group
      groupPointsRedemptionYN
      inactiveflag
      indRevenueGroup
      indicatorRevenueGroup
      insertDate
      insertUser
      internalDeletedflag
      internalYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      resultIncludedInSumArray
      rnaInsertDate
      rnaUpdateDate
      subGroupType
      taxFlagYN
      taxYN
      tcGroupAndSubgroup
      tcTransactionType
      transactionCodeSubGroup
      transgroupid
      transsubgroupid
      type
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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
    'ownerRevenueYN': pl.Utf8,
    'paymentTaxInvoiceYn': pl.Utf8,
    'paymentType': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
}
```
```python
transaction_group_details_schema = {
    'centralDescription': pl.Utf8,
    'centralDisplaySequence': pl.Float64,
    'centralTransactionCodeGroup': pl.Utf8,
    'class1MandatoryYn': pl.Utf8,
    'class2MandatoryYn': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displaySequence': pl.Float64,
    'inactiveflag': pl.Utf8,
    'indRevenueGroup': pl.Utf8,
    'indicatorRevenueGroup': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalDeletedflag': pl.Utf8,
    'internalYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'resultIncludedInSumArray': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'tctClassType1': pl.Utf8,
    'tctClassType2': pl.Utf8,
    'transactionCodeActivityType': pl.Utf8,
    'transactionCodeGroup': pl.Utf8,
    'transgroupid': pl.Utf8,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}
```
```python
transaction_subgroup_details_schema = {
    'centralDescription': pl.Utf8,
    'centralDisplaySequence': pl.Float64,
    'centralGroup': pl.Utf8,
    'centralTransactionCodeSubGroup': pl.Utf8,
    'class1MandatoryYn': pl.Utf8,
    'class2MandatoryYn': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displaySequence': pl.Float64,
    'frequentFlyerYn': pl.Utf8,
    'group': pl.Utf8,
    'groupPointsRedemptionYN': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'indRevenueGroup': pl.Utf8,
    'indicatorRevenueGroup': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalDeletedflag': pl.Utf8,
    'internalYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'resultIncludedInSumArray': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'subGroupType': pl.Utf8,
    'taxFlagYN': pl.Utf8,
    'taxYN': pl.Utf8,
    'tcGroupAndSubgroup': pl.Utf8,
    'tcTransactionType': pl.Utf8,
    'transactionCodeSubGroup': pl.Utf8,
    'transgroupid': pl.Utf8,
    'transsubgroupid': pl.Utf8,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
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