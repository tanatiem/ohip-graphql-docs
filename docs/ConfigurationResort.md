# ConfigurationResort
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `configurationResort`
> The Resort Configuration Subject Area contains configuration/setting attributes from components such as Enterprise Administration Financial Administration Booking Administration and Client Relations Administration in OPERA.
  
**Return:** [`[ConfigurationResortType]`](#configurationresorttype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`ConfigurationResortQueryArgumentsType!`](#configurationresortqueryargumentstype) |  |

## Object Types

### ConfigurationResortType

| Field | Type | Description |
| --- | --- | --- |
| propertyPropertyDetails | [`ConfigurationResortPropertyPropertyDetailsType`](#configurationresortpropertypropertydetailstype) | Resort Details |
| membershipClaimOriginDetails | [`ConfigurationResortMembershipClaimOriginDetailsType`](#configurationresortmembershipclaimorigindetailstype) | Membership Claim Origin |
| membershipPointsDetails | [`ConfigurationResortMembershipPointsDetailsType`](#configurationresortmembershippointsdetailstype) | Membership Points |
| membershipAwardRatesDetails | [`ConfigurationResortMembershipAwardRatesDetailsType`](#configurationresortmembershipawardratesdetailstype) | Membership Award Rates |
| membershipAwardProductsDetails | [`ConfigurationResortMembershipAwardProductsDetailsType`](#configurationresortmembershipawardproductsdetailstype) | Membership Award Products |
| membershipAwardUpgradesDetails | [`ConfigurationResortMembershipAwardUpgradesDetailsType`](#configurationresortmembershipawardupgradesdetailstype) | Membership Award Upgrades |
| membershipAwardFinancialTransactionDetails | [`ConfigurationResortMembershipAwardFinancialTransactionDetailsType`](#configurationresortmembershipawardfinancialtransactiondetailstype) | Membership Award Financial Transaction |
| membershipPropertyGroupCodeDetails | [`ConfigurationResortMembershipPropertyGroupCodeDetailsType`](#configurationresortmembershippropertygroupcodedetailstype) | Membership Property Group Code |
| airportDetails | [`ConfigurationResortAirportDetailsType`](#configurationresortairportdetailstype) | Airport Details |
| featureDetails | [`ConfigurationResortFeatureDetailsType`](#configurationresortfeaturedetailstype) | Feature Details |
| attractionCategoryDetails | [`ConfigurationResortAttractionCategoryDetailsType`](#configurationresortattractioncategorydetailstype) | Attraction Category Details |
| attractionDetails | [`ConfigurationResortAttractionDetailsType`](#configurationresortattractiondetailstype) | Attraction Details |
| chainDetails | [`ConfigurationResortChainDetailsType`](#configurationresortchaindetailstype) | Chain Details |
| closingScriptDetails | [`ConfigurationResortClosingScriptDetailsType`](#configurationresortclosingscriptdetailstype) | Closing Script Details |
| communicationMethodDetails | [`ConfigurationResortCommunicationMethodDetailsType`](#configurationresortcommunicationmethoddetailstype) | Communication Method Details |
| deliveryStatusDetails | [`ConfigurationResortDeliveryStatusDetailsType`](#configurationresortdeliverystatusdetailstype) | Delivery Status Details |
| departmentDetails | [`ConfigurationResortDepartmentDetailsType`](#configurationresortdepartmentdetailstype) | Department Details |
| elecRegCardScriptDetails | [`ConfigurationResortElecRegCardScriptDetailsType`](#configurationresortelecregcardscriptdetailstype) | Elec Reg Card Script Details |
| hubPropertyDetails | [`ConfigurationResortHubPropertyDetailsType`](#configurationresorthubpropertydetailstype) | Hub Property |
| jobTitleDetails | [`ConfigurationResortJobTitleDetailsType`](#configurationresortjobtitledetailstype) | Job Title Details |
| uDFCategoryDetails | [`ConfigurationResortUDFCategoryDetailsType`](#configurationresortudfcategorydetailstype) | UDF Category |
| uDFTypeDetails | [`ConfigurationResortUDFTypeDetailsType`](#configurationresortudftypedetailstype) | UDF Type |
| brandCodeDetails | [`ConfigurationResortBrandCodeDetailsType`](#configurationresortbrandcodedetailstype) | Brand Code Details |
| businessUnitDetails | [`ConfigurationResortBusinessUnitDetailsType`](#configurationresortbusinessunitdetailstype) | Business Unit Details |
| departmentCodeDetails | [`ConfigurationResortDepartmentCodeDetailsType`](#configurationresortdepartmentcodedetailstype) | Department Code Details |
| divisionDetails | [`ConfigurationResortDivisionDetailsType`](#configurationresortdivisiondetailstype) | Division Details |
| hotelCategoryDetails | [`ConfigurationResortHotelCategoryDetailsType`](#configurationresorthotelcategorydetailstype) | Hotel Category Details |
| operatingUnitDetails | [`ConfigurationResortOperatingUnitDetailsType`](#configurationresortoperatingunitdetailstype) | Operating Unit Details |
| applicationParameterValueDetails | [`ConfigurationResortApplicationParameterValueDetailsType`](#configurationresortapplicationparametervaluedetailstype) | Application Parameter Value Details |
| trackitActionDetails | [`ConfigurationResortTrackitActionDetailsType`](#configurationresorttrackitactiondetailstype) | Trackit Action Details |
| trackitLocationDetails | [`ConfigurationResortTrackitLocationDetailsType`](#configurationresorttrackitlocationdetailstype) | Trackit Location Details |
| trackitTypeDetails | [`ConfigurationResortTrackitTypeDetailsType`](#configurationresorttrackittypedetailstype) | Trackit Type Details |
| accountTypeDetails | [`ConfigurationResortAccountTypeDetailsType`](#configurationresortaccounttypedetailstype) | Account Type Details |
| aRReminderCycleDetails | [`ConfigurationResortARReminderCycleDetailsType`](#configurationresortarremindercycledetailstype) | AR Reminder Cycle |
| acctFlagReasonDetails | [`ConfigurationResortAcctFlagReasonDetailsType`](#configurationresortacctflagreasondetailstype) | Acct Flag Reason Details |
| transactionReasonCodeDetails | [`ConfigurationResortTransactionReasonCodeDetailsType`](#configurationresorttransactionreasoncodedetailstype) | Transaction Reason Code |
| creditCardAuthorizationRulesDetails | [`ConfigurationResortCreditCardAuthorizationRulesDetailsType`](#configurationresortcreditcardauthorizationrulesdetailstype) | Credit Card Authorization Rules |
| autoFolioSettlementTypeDetails | [`ConfigurationResortAutoFolioSettlementTypeDetailsType`](#configurationresortautofoliosettlementtypedetailstype) | Auto Folio Settlement Type Details |
| cashierDetails | [`ConfigurationResortCashierDetailsType`](#configurationresortcashierdetailstype) | Cashier Details |
| customNumberDetails | [`ConfigurationResortCustomNumberDetailsType`](#configurationresortcustomnumberdetailstype) | Custom Number Details |
| currencyExchangeTaxDetails | [`ConfigurationResortCurrencyExchangeTaxDetailsType`](#configurationresortcurrencyexchangetaxdetailstype) | Currency Exchange Tax Details |
| expenseArrangementCodeDetails | [`ConfigurationResortExpenseArrangementCodeDetailsType`](#configurationresortexpensearrangementcodedetailstype) | Expense Arrangement Code Details |
| transactionCodeDetails | [`ConfigurationResortTransactionCodeDetailsType`](#configurationresorttransactioncodedetailstype) | Transaction Code |
| folioArrangementCodeDetails | [`ConfigurationResortFolioArrangementCodeDetailsType`](#configurationresortfolioarrangementcodedetailstype) | Folio Arrangement Code Details |
| groupArrangementCodeDetails | [`ConfigurationResortGroupArrangementCodeDetailsType`](#configurationresortgrouparrangementcodedetailstype) | Group Arrangement Code Details |
| folioTypeDetails | [`ConfigurationResortFolioTypeDetailsType`](#configurationresortfoliotypedetailstype) | Folio Type Details |
| folioTypeDetailDetails | [`ConfigurationResortFolioTypeDetailDetailsType`](#configurationresortfoliotypedetaildetailstype) | Folio Type Detail Details |
| bankAccountDetails | [`ConfigurationResortBankAccountDetailsType`](#configurationresortbankaccountdetailstype) | Bank Account Details |
| commissionDetails | [`ConfigurationResortCommissionDetailsType`](#configurationresortcommissiondetailstype) | Commission Details |
| authorizerGroupDetails | [`ConfigurationResortAuthorizerGroupDetailsType`](#configurationresortauthorizergroupdetailstype) | Authorizer Group Details |
| authorizerGroupDetailDetails | [`ConfigurationResortAuthorizerGroupDetailDetailsType`](#configurationresortauthorizergroupdetaildetailstype) | Authorizer Group Detail Details |
| authorizerDetails | [`ConfigurationResortAuthorizerDetailsType`](#configurationresortauthorizerdetailstype) | Authorizer Details |
| bucketRedemptionCodeDetails | [`ConfigurationResortBucketRedemptionCodeDetailsType`](#configurationresortbucketredemptioncodedetailstype) | Bucket Redemption Code Details |
| compRoutingCodeDetails | [`ConfigurationResortCompRoutingCodeDetailsType`](#configurationresortcomproutingcodedetailstype) | Comp Routing Code Details |
| compTransactionCodeDetails | [`ConfigurationResortCompTransactionCodeDetailsType`](#configurationresortcomptransactioncodedetailstype) | Comp Transaction Code |
| transactionCodeCompExternalReferenceDetails | [`ConfigurationResortTransactionCodeCompExternalReferenceDetailsType`](#configurationresorttransactioncodecompexternalreferencedetailstype) | Transaction Code Comp External Reference |
| codeGeneratesDetails | [`ConfigurationResortCodeGeneratesDetailsType`](#configurationresortcodegeneratesdetailstype) | Code Generates Details |
| compTypeDetails | [`ConfigurationResortCompTypeDetailsType`](#configurationresortcomptypedetailstype) | Comp Type Details |
| barScheduleDetails | [`ConfigurationResortBarScheduleDetailsType`](#configurationresortbarscheduledetailstype) | Bar Schedule Details |
| cityTaxRangeDetails | [`ConfigurationResortCityTaxRangeDetailsType`](#configurationresortcitytaxrangedetailstype) | City Tax Range Details |
| propertyDayTypeDetails | [`ConfigurationResortPropertyDayTypeDetailsType`](#configurationresortpropertydaytypedetailstype) | Property Day Type |
| displaySetDetails | [`ConfigurationResortDisplaySetDetailsType`](#configurationresortdisplaysetdetailstype) | Display Set Details |
| propertyCalendarEventDetails | [`ConfigurationResortPropertyCalendarEventDetailsType`](#configurationresortpropertycalendareventdetailstype) | Property Calendar Event |
| rateHurdlesDetails | [`ConfigurationResortRateHurdlesDetailsType`](#configurationresortratehurdlesdetailstype) | Rate Hurdles Details |
| productDetails | [`ConfigurationResortProductDetailsType`](#configurationresortproductdetailstype) | Product Details |
| itemPackageDetails | [`ConfigurationResortItemPackageDetailsType`](#configurationresortitempackagedetailstype) | Item Package Details |
| rateProductPriceDetails | [`ConfigurationResortRateProductPriceDetailsType`](#configurationresortrateproductpricedetailstype) | Rate Product Price Details |
| packageForecastGroupDetails | [`ConfigurationResortPackageForecastGroupDetailsType`](#configurationresortpackageforecastgroupdetailstype) | Package Forecast Group |
| promotionDetails | [`ConfigurationResortPromotionDetailsType`](#configurationresortpromotiondetailstype) | Promotion Details |
| promotionRateDetails | [`ConfigurationResortPromotionRateDetailsType`](#configurationresortpromotionratedetailstype) | Promotion Rate |
| promotionCodeRoutingInstructionDetails | [`ConfigurationResortPromotionCodeRoutingInstructionDetailsType`](#configurationresortpromotioncoderoutinginstructiondetailstype) | Promotion Code Routing Instruction |
| rateCategoriesDetails | [`ConfigurationResortRateCategoriesDetailsType`](#configurationresortratecategoriesdetailstype) | Rate Categories Details |
| articleDetails | [`ConfigurationResortArticleDetailsType`](#configurationresortarticledetailstype) | Article Details |
| creditCardTypesDetails | [`ConfigurationResortCreditCardTypesDetailsType`](#configurationresortcreditcardtypesdetailstype) | Credit Card Types Details |
| paymentMethodDetails | [`ConfigurationResortPaymentMethodDetailsType`](#configurationresortpaymentmethoddetailstype) | Payment Method Details |
| exportBucketCodeDetails | [`ConfigurationResortExportBucketCodeDetailsType`](#configurationresortexportbucketcodedetailstype) | Export Bucket Code Details |
| transactionCodeArrangeDetailDetails | [`ConfigurationResortTransactionCodeArrangeDetailDetailsType`](#configurationresorttransactioncodearrangedetaildetailstype) | Transaction Code Arrange Detail |
| exportBucketTypeDetails | [`ConfigurationResortExportBucketTypeDetailsType`](#configurationresortexportbuckettypedetailstype) | Export Bucket Type Details |
| routingCodeDetails | [`ConfigurationResortRoutingCodeDetailsType`](#configurationresortroutingcodedetailstype) | Routing Code Details |
| transactionDiversionRuleDetails | [`ConfigurationResortTransactionDiversionRuleDetailsType`](#configurationresorttransactiondiversionruledetailstype) | Transaction Diversion Rule |
| transactionDiversionRuleDetailsDetails | [`ConfigurationResortTransactionDiversionRuleDetailsDetailsType`](#configurationresorttransactiondiversionruledetailsdetailstype) | Transaction Diversion Rule Details |
| transactionGroupDetails | [`ConfigurationResortTransactionGroupDetailsType`](#configurationresorttransactiongroupdetailstype) | Transaction Group |
| groupGeneratesDetails | [`ConfigurationResortGroupGeneratesDetailsType`](#configurationresortgroupgeneratesdetailstype) | Group Generates Details |
| transactionSubgroupDetails | [`ConfigurationResortTransactionSubgroupDetailsType`](#configurationresorttransactionsubgroupdetailstype) | Transaction Subgroup |
| subgroupGeneratesDetails | [`ConfigurationResortSubgroupGeneratesDetailsType`](#configurationresortsubgroupgeneratesdetailstype) | Subgroup Generates Details |
| propertyAlertDetails | [`ConfigurationResortPropertyAlertDetailsType`](#configurationresortpropertyalertdetailstype) | Property Alert |
| globalAlertsDetails | [`ConfigurationResortGlobalAlertsDetailsType`](#configurationresortglobalalertsdetailstype) | Global Alerts Details |
| blockCancellationCodeDetails | [`ConfigurationResortBlockCancellationCodeDetailsType`](#configurationresortblockcancellationcodedetailstype) | Block Cancellation Code Details |
| salesEventDestinationDetails | [`ConfigurationResortSalesEventDestinationDetailsType`](#configurationresortsaleseventdestinationdetailstype) | Sales Event Destination |
| lostBookingCodesDetails | [`ConfigurationResortLostBookingCodesDetailsType`](#configurationresortlostbookingcodesdetailstype) | Lost Booking Codes Details |
| refusedBookingCodesDetails | [`ConfigurationResortRefusedBookingCodesDetailsType`](#configurationresortrefusedbookingcodesdetailstype) | Refused Booking Codes Details |
| bookingMethodDetails | [`ConfigurationResortBookingMethodDetailsType`](#configurationresortbookingmethoddetailstype) | Booking Method Details |
| propertyCutoffScheduleDetails | [`ConfigurationResortPropertyCutoffScheduleDetailsType`](#configurationresortpropertycutoffscheduledetailstype) | Property Cutoff Schedule |
| bookingStatusDetails | [`ConfigurationResortBookingStatusDetailsType`](#configurationresortbookingstatusdetailstype) | Booking Status Details |
| cancelRuleDetails | [`ConfigurationResortCancelRuleDetailsType`](#configurationresortcancelruledetailstype) | Cancel Rule Details |
| cancelRuleScheduleDetails | [`ConfigurationResortCancelRuleScheduleDetailsType`](#configurationresortcancelrulescheduledetailstype) | Cancel Rule Schedule Details |
| depositRuleDetails | [`ConfigurationResortDepositRuleDetailsType`](#configurationresortdepositruledetailstype) | Deposit Rule Details |
| depositRuleScheduleDetails | [`ConfigurationResortDepositRuleScheduleDetailsType`](#configurationresortdepositrulescheduledetailstype) | Deposit Rule Schedule Details |
| guaranteeDetails | [`ConfigurationResortGuaranteeDetailsType`](#configurationresortguaranteedetailstype) | Guarantee Details |
| reservationTypeScheduleDetails | [`ConfigurationResortReservationTypeScheduleDetailsType`](#configurationresortreservationtypescheduledetailstype) | Reservation Type Schedule Details |
| marketDetails | [`ConfigurationResortMarketDetailsType`](#configurationresortmarketdetailstype) | Market Details |
| marketGroupDetails | [`ConfigurationResortMarketGroupDetailsType`](#configurationresortmarketgroupdetailstype) | Market Group Details |
| propertyMarketingCityDetails | [`ConfigurationResortPropertyMarketingCityDetailsType`](#configurationresortpropertymarketingcitydetailstype) | Property Marketing City |
| marketingRegionsDetails | [`ConfigurationResortMarketingRegionsDetailsType`](#configurationresortmarketingregionsdetailstype) | Marketing Regions Details |
| channelDetails | [`ConfigurationResortChannelDetailsType`](#configurationresortchanneldetailstype) | Channel Details |
| sellMessagesDetails | [`ConfigurationResortSellMessagesDetailsType`](#configurationresortsellmessagesdetailstype) | Sell Messages Details |
| sourceTableDetails | [`ConfigurationResortSourceTableDetailsType`](#configurationresortsourcetabledetailstype) | Source Table Details |
| sourceGroupDetails | [`ConfigurationResortSourceGroupDetailsType`](#configurationresortsourcegroupdetailstype) | Source Group Details |
| reservationAutoAttachRulesDetails | [`ConfigurationResortReservationAutoAttachRulesDetailsType`](#configurationresortreservationautoattachrulesdetailstype) | Reservation Auto Attach Rules |
| reservationAutoAttachDetailsDetails | [`ConfigurationResortReservationAutoAttachDetailsDetailsType`](#configurationresortreservationautoattachdetailsdetailstype) | Reservation Auto Attach Details |
| cancellationCodesDetails | [`ConfigurationResortCancellationCodesDetailsType`](#configurationresortcancellationcodesdetailstype) | Cancellation Codes Details |
| entryPointDetails | [`ConfigurationResortEntryPointDetailsType`](#configurationresortentrypointdetailstype) | Entry Point Details |
| discountReasonDetails | [`ConfigurationResortDiscountReasonDetailsType`](#configurationresortdiscountreasondetailstype) | Discount Reason Details |
| ecouponDetails | [`ConfigurationResortEcouponDetailsType`](#configurationresortecoupondetailstype) | Ecoupon Details |
| propertyLocatorDetails | [`ConfigurationResortPropertyLocatorDetailsType`](#configurationresortpropertylocatordetailstype) | Property Locator |
| propertyMessageDetails | [`ConfigurationResortPropertyMessageDetailsType`](#configurationresortpropertymessagedetailstype) | Property Message |
| guestStatusDetails | [`ConfigurationResortGuestStatusDetailsType`](#configurationresortgueststatusdetailstype) | Guest Status Details |
| guestTypeDetails | [`ConfigurationResortGuestTypeDetailsType`](#configurationresortguesttypedetailstype) | Guest Type Details |
| immigrationStatusDetails | [`ConfigurationResortImmigrationStatusDetailsType`](#configurationresortimmigrationstatusdetailstype) | Immigration Status Details |
| preRegRulesDetails | [`ConfigurationResortPreRegRulesDetailsType`](#configurationresortpreregrulesdetailstype) | Pre Reg Rules Details |
| itemClassDetails | [`ConfigurationResortItemClassDetailsType`](#configurationresortitemclassdetailstype) | Item Class Details |
| itemInventoryDetails | [`ConfigurationResortItemInventoryDetailsType`](#configurationresortiteminventorydetailstype) | Item Inventory Details |
| itemPoolDetails | [`ConfigurationResortItemPoolDetailsType`](#configurationresortitempooldetailstype) | Item Pool Details |
| birthCountryDetails | [`ConfigurationResortBirthCountryDetailsType`](#configurationresortbirthcountrydetailstype) | Birth Country Details |
| propertyCountryDetails | [`ConfigurationResortPropertyCountryDetailsType`](#configurationresortpropertycountrydetailstype) | Property Country |
| countryGroupDetails | [`ConfigurationResortCountryGroupDetailsType`](#configurationresortcountrygroupdetailstype) | Country Group Details |
| distanceTypeDetails | [`ConfigurationResortDistanceTypeDetailsType`](#configurationresortdistancetypedetailstype) | Distance Type Details |
| districtDetails | [`ConfigurationResortDistrictDetailsType`](#configurationresortdistrictdetailstype) | District Details |
| fiscalGuestTypeDetails | [`ConfigurationResortFiscalGuestTypeDetailsType`](#configurationresortfiscalguesttypedetailstype) | Fiscal Guest Type Details |
| fiscalRegionDetails | [`ConfigurationResortFiscalRegionDetailsType`](#configurationresortfiscalregiondetailstype) | Fiscal Region Details |
| profileIDCountryDetails | [`ConfigurationResortProfileIDCountryDetailsType`](#configurationresortprofileidcountrydetailstype) | Profile ID Country |
| nationalityDetails | [`ConfigurationResortNationalityDetailsType`](#configurationresortnationalitydetailstype) | Nationality Details |
| qualifyingRatesDetails | [`ConfigurationResortQualifyingRatesDetailsType`](#configurationresortqualifyingratesdetailstype) | Qualifying Rates Details |
| membershipStatusDetails | [`ConfigurationResortMembershipStatusDetailsType`](#configurationresortmembershipstatusdetailstype) | Membership Status Details |
| priorityDetails | [`ConfigurationResortPriorityDetailsType`](#configurationresortprioritydetailstype) | Priority Details |
| entityAccountTypeDetails | [`ConfigurationResortEntityAccountTypeDetailsType`](#configurationresortentityaccounttypedetailstype) | Entity Account Type Details |
| addressTypeDetails | [`ConfigurationResortAddressTypeDetailsType`](#configurationresortaddresstypedetailstype) | Address Type Details |
| alternateLanguageTitleDetails | [`ConfigurationResortAlternateLanguageTitleDetailsType`](#configurationresortalternatelanguagetitledetailstype) | Alternate Language Title |
| roomsPotentialDetails | [`ConfigurationResortRoomsPotentialDetailsType`](#configurationresortroomspotentialdetailstype) | Rooms Potential Details |
| businessSegmentDetails | [`ConfigurationResortBusinessSegmentDetailsType`](#configurationresortbusinesssegmentdetailstype) | Business Segment Details |
| companyTypeDetails | [`ConfigurationResortCompanyTypeDetailsType`](#configurationresortcompanytypedetailstype) | Company Type Details |
| competitionDetails | [`ConfigurationResortCompetitionDetailsType`](#configurationresortcompetitiondetailstype) | Competition Details |
| genderDetails | [`ConfigurationResortGenderDetailsType`](#configurationresortgenderdetailstype) | Gender Details |
| profileInactiveReasonDetails | [`ConfigurationResortProfileInactiveReasonDetailsType`](#configurationresortprofileinactivereasondetailstype) | Profile Inactive Reason Details |
| industryCodeDetails | [`ConfigurationResortIndustryCodeDetailsType`](#configurationresortindustrycodedetailstype) | Industry Code Details |
| influenceCodeDetails | [`ConfigurationResortInfluenceCodeDetailsType`](#configurationresortinfluencecodedetailstype) | Influence Code Details |
| keywordTypeDetails | [`ConfigurationResortKeywordTypeDetailsType`](#configurationresortkeywordtypedetailstype) | Keyword Type Details |
| mailingActionDetails | [`ConfigurationResortMailingActionDetailsType`](#configurationresortmailingactiondetailstype) | Mailing Action Details |
| preferenceDetails | [`ConfigurationResortPreferenceDetailsType`](#configurationresortpreferencedetailstype) | Preference Details |
| profileRestrictionReasonDetails | [`ConfigurationResortProfileRestrictionReasonDetailsType`](#configurationresortprofilerestrictionreasondetailstype) | Profile Restriction Reason Details |
| salesEventScopeDetails | [`ConfigurationResortSalesEventScopeDetailsType`](#configurationresortsaleseventscopedetailstype) | Sales Event Scope |
| salesEventScopeCityDetails | [`ConfigurationResortSalesEventScopeCityDetailsType`](#configurationresortsaleseventscopecitydetailstype) | Sales Event Scope City |
| membershipClaimAdjustmentLimitDetails | [`ConfigurationResortMembershipClaimAdjustmentLimitDetailsType`](#configurationresortmembershipclaimadjustmentlimitdetailstype) | Membership Claim Adjustment Limit |
| configurationResortRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyPropertyDetailsType

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

### ConfigurationResortMembershipClaimOriginDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| claimOriginCode | `String` | Claim Origin Code |
| claimOriginDescription | `String` | Claim Origin Description |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipPointsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allMembershipRatesYn | `String` | Indicates if this rule applies to all Rates checked for membership. |
| allMembershipTransactionYN | `String` | Indicates if this rule applies to all transactions checked for membership. |
| averageRateAmount | `Float` | Average Rate Amount |
| beginDate | `Date` | Begin Date |
| billingGroup | `String` | Billing Group |
| bookingEndDate | `Date` | Booking End Date |
| bookingStartDate | `Date` | Booking Start Date |
| calculationRule | `String` | Calculation Rule |
| chainCode | `String` | Chain Code |
| costPerPoint | `Float` | Cost Per Point |
| creditMultipleMembershipYn | `String` | Credit Multiple Membership Y/N |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| daysSinceEnrolled | `Float` | Number of days from enrollment. |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| earningRhythmFlg | `String` | Flag indicating type of earning rhythm applied. |
| earningRhythmNights | `Float` | Indicate that points will be earned every X nights. |
| endDate | `Date` | End Date |
| enrollmentCode | `String` | The enrollment code to which this rule applies. |
| enrollmentGroup | `String` | Enrollment group that includes the enrollment code(s) to which this rule applies. |
| excludeBbFlg | `String` | Flag to indicate this rule is excluded if back to back is detected. |
| excludeFromPointProjectionYN | `String` | Determines while calculating points projection should the rule be excluded or included. Default is included(N). |
| excludeMktGroup | `String` | Determines if the market group should be excluded or included ). Default is included(N). |
| excludeRevGroup | `String` | Determines if the revenue group should be excluded or included ). Default is included(N). |
| excludeRoomGroupYn | `String` | Indicates if the room group should be excluded if Y. |
| expirationDate | `Date` | Expiration date of the Card. |
| exportLabel | `String` | This field will be used to store export label and will be used only for exporting purposes. |
| fridayYN | `String` | Friday YN |
| inactiveDate | `DateTime` | Inactive Date |
| includeGraceRenewalFlg | `String` | This flag indicate if grace renewals need to be included or not. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| marketCode | `String` | Market Code |
| marketGroup | `String` | Market Group |
| marketGroupIncludeYN | `String` | Market Group Include YN |
| maxBucketSize | `Float` | Maximum quantity bucket can contain. |
| maximumNights | `Float` | This field indicates the maximum nights eligible  to receive points If membership type is based on NIGHTS. |
| maximumRevenue | `Float` | Maximum Revenue |
| memRevenueGroup | `String` | Membership rate group. |
| membershipLevel | `String` | Membership level to which this rule applies. |
| membershipPointsSeqno | `Float` | Membership Points Seqno |
| membershipRateGroupExcludeYN | `String` | Mem Rate Group Exclude Y/N |
| membershipType | `String` | Membership Type |
| minPropertiesReq | `Float` | Determines if transactions should belong to minimum different properties. If empty then they can belong to same property. |
| minimumNights | `Float` | This field indicates the minimum length of stay required to receive points If membership type is based on STAY. |
| minimumRateAmount | `Float` | This field indicates the minimum rate amount required for the guest to earn points. |
| minimumRevenue | `Float` | Minimum Revenue |
| minimumStays | `Float` | Minimum Stays |
| mondayYN | `String` | Monday YN |
| multipleTransactionsYn | `String` | Multiple Transactions Y/N |
| numberOfTimesEligible | `Float` | Number of Times Eligible |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| perRevenueUnits | `Float` | Specifies the minimum units needed |
| points | `Float` | Specifies the ratio of the points accumulated per Stay or Night or Revenue. This ratio multiplied by the actual Stays or Nights or Revenue will give the Total points accumulated. |
| pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| pointsRatioPercentYn | `String` | Points ratio is expressed in terms of %. |
| pointsRatioRoundingFlg | `String` | This flag tells if the total amount computed will be rounded rounded up or rounded down. |
| preferredCardExcludeYn | `String` | Exclude the rule if a preferred card exception exists on the transaction. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| programType | `String` | Program Type |
| programTypeDesc | `String` | Program Type Desc |
| promotionCode | `String` | Promotion Code |
| property | `String` | Property |
| propertyGroup | `String` | Property Group |
| pseudoRuleYn | `String` | Pseudo rule is used for OCIS memberships to show computed points in PMS for a reservation. |
| qualifyingRatesYN | `String` | Qualifying Rates YN |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rateGroup | `String` | Rate Group |
| rateGroupIncludeYN | `String` | Rate Group Include YN |
| reservationChannel | `String` | Reservation Channel |
| revenueGroup | `String` | Revenue Group |
| revenueGroupIncludeYN | `String` | Revenue Group Include YN |
| roomClass | `String` | Room Class |
| roomGroup | `String` | Room Group |
| roomType | `String` | Room Type |
| roomTypeToChargeYN | `String` | Y to calculate the membership upgrade based on the "room to charge" for the stay and not the actual room type in which the member stayed. |
| rounding | `String` | Rounding |
| ruleAppliesTo | `String` | Rule Applies To |
| ruleBasedOn | `String` | Indicates the field on which  calculation of points is valid for. Eg if value is 'RATE_GROUP' then this rule is valid for the value in RATE_GROUP field. Thus we can specify different points rule for BUSINESS rates and NON-BUSINESS rates. |
| ruleCode | `String` | Rule Code |
| saturdayYN | `String` | Saturday YN |
| sundayYN | `String` | Sunday YN |
| thursdayYN | `String` | Thursday YN |
| toMemberLevel | `String` | Used in membership tier upgrade rule to determine to which level the upgrade will eligible. |
| transactionType | `String` | Transaction Type |
| tuesdayYN | `String` | Tuesday YN |
| type | `String` | Type |
| typeOfPoints | `String` | Types of points earned (Loyalty FF). |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| userpostingOnlyYn | `String` | Userposting Only Y/N |
| wednesdayYN | `String` | Wednesday YN |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipAwardRatesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| awardType | `String` | Award Type |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| membershipType | `String` | Membership Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| property | `String` | Code to uniquely identify the Property |
| rateCode | `String` | Rate Code |
| rateDescription | `String` | Rate Description |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipAwardProductsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| awardType | `String` | Award Type |
| centralPackageCode | `String` | Central Package Code |
| centralPackageDescription | `String` | Central Package Description |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| membershipType | `String` | Membership Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| packageCode | `String` | Products Codes |
| packageDescription | `String` | Package Description |
| property | `String` | Code to uniquely identify the Property |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipAwardUpgradesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| awardType | `String` | Award Type |
| centralUpgradeFromRoom | `String` | Central Upgrade From Room |
| centralUpgradeToRoom | `String` | Central Upgrade To Room |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| fromDate | `Date` | From Date |
| fromRoom | `String` | Room Number of the reservation from which charges were routed when routing charges between reservations. |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| membershipAwardId | `Float` | Internal PK for the table. |
| membershipType | `String` | Membership Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pointsRequiredUpgrades | `Float` | Points Required Upgrades |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| toDate | `Date` | To Date |
| toRoom | `String` | Upgraded room. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upgradeFromRoom | `String` | Upgrade From Room |
| upgradeToRoom | `String` | Upgrade To Room |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipAwardFinancialTransactionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| awardType | `String` | Award Type |
| centralTransactionCode | `String` | Central Transaction Code |
| centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| membershipType | `String` | Membership Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| transactionCode | `String` | Transaction Code |
| transactionCodeDescription | `String` | Transaction Code Description |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipPropertyGroupCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| attachedPropertyCode | `String` | Attached Property Code |
| attachedPropertyDescription | `String` | Attached Property Description |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| membershipResortGroup | `String` | Mem Property Group |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| requiredYn | `String` | Required Y/N |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAirportDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `String` | Airport code. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| distance | `Float` | Distance from the airport to the property. |
| distanceType | `String` | Type of units for distance (mileskilometers). |
| drivingDirections | `String` | Directions from the airport to the property. |
| drivingTime | `String` | Driving Time |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| sequence | `Float` | Sequence |
| transportationCode1 | `String` | Internal. |
| transportationCode2 | `String` | Internal. |
| transportationCode3 | `String` | Internal. |
| transportationCode4 | `String` | Internal. |
| transportationCode5 | `String` | Internal. |
| transportationCode6 | `String` | Internal. |
| transportationCode7 | `String` | Internal. |
| transportationCode8 | `String` | Internal. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| website | `String` | Website |

[⬆ Back to Query](#query)

---

### ConfigurationResortFeatureDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| endDate | `Date` | End Date |
| featureType | `String` | Feature Type |
| featureid | `String` | Featureid |
| hours | `String` | Hours |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| notes | `String` | Notes |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| price | `String` | Price |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| startDate | `Date` | Start Date |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAttractionCategoryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAttractionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| address1 | `String` | Address1 |
| address2 | `String` | Address2 |
| address3 | `String` | Address3 |
| address4 | `String` | Address4 |
| attractionClass | `String` | Attraction Class |
| category | `String` | Type of attraction |
| city | `String` | City |
| code | `String` | The unique identifier for this attraction. The primary key to this table. |
| coordinateSupplier | `String` | Who supplied the geo-coded coordinates for this attraction. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| direction | `String` | Direction |
| directions | `String` | Internal |
| distance | `Float` | Distance |
| distanceType | `String` | Distance Type |
| drivingTime | `String` | Driving Time |
| generalDirections | `String` | The general directions to this attraction. |
| hoursOfOperation | `String` | The hours of operation for this attraction. |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| latitude | `Float` | The latitude of this attraction in geo-coded format. |
| longitude | `Float` | The longitude of this attraction in geo-coded format. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| priceRange | `String` | Price Range |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| region | `String` | Region |
| sequence | `Float` | Sequence |
| state | `String` | State |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| website | `String` | Website |
| zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### ConfigurationResortChainDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aspYn | `String` | Chain used for ASP Y/N. |
| beginDate | `Date` | Begin Date |
| bookingConditions | `String` | Booking conditions chainwide such as commission policies for TA Group policies Cancellation/Deposit/Guarantee and family and child rules. |
| centralChain | `String` | Central Chain |
| centralDescription | `String` | Central Description |
| chain | `String` | Chain |
| chainName | `String` | Chain Name |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| endDate | `Date` | End Date |
| frequentFlierCardsAcceptYn | `String` | Specifies if frequent flier cards are accepted by the chain (Y/N). |
| hoCity | `String` | The city of the Head Office of the chain. |
| hoCountry | `String` | The country of the Head Office of the chain. |
| hoEmail | `String` | The email ID of the Head Office of the chain. |
| hoFax | `String` | The fax number of the Head Office of the chain. |
| hoPostCode | `String` | The postal code of the Head Office of the chain. |
| hoState | `String` | The state of the Head Office of the chain. |
| hoStreet | `String` | The street of the Head Office of the chain. |
| hoTelephone | `String` | The phone number of the Head Office of the chain. |
| imgChainId | `Float` | Img Chain ID |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| logoFileName | `String` | File name of the chains' logo |
| loyaltyProgram | `String` | Loyalty program data. |
| marketingText | `String` | Marketing Text |
| nameId | `Float` | Name ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| scriptId | `Float` | Script ID |
| shareProfilesYN | `String` | Sharing Profiles across the Chain. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortClosingScriptDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| language | `String` | Language |
| membershipType | `String` | Membership Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| resortType | `String` | Property Type |
| scriptId | `Float` | Script ID |
| scriptType | `String` | Script Type. (e.g. [SMS] for SMS script and [RESV] for Closing Script) |

[⬆ Back to Query](#query)

---

### ConfigurationResortCommunicationMethodDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDeliveryStatusDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDepartmentDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allowOnTaskSheetYn | `String` | Indicates if Reservation Traces related to this Department will appear on Housekeeping Task Sheets. |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| departmentCode | `String` | Department Code |
| departmentid | `String` | Departmentid |
| deptManagerPager | `String` | Pager number of department manager |
| description | `String` | Description of the department |
| email | `String` | Department E-Mail Address. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| messageText | `String` | Message Text |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| repDeptName | `String` | Reporting Dept Name |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| reportingDeptId | `String` | Rep Dept ID |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortElecRegCardScriptDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| language | `String` | Language |
| membershipType | `String` | Membership Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| resortType | `String` | Property Type |
| scriptId | `Float` | Script ID |
| scriptType | `String` | Script Type. (e.g. [SMS] for SMS script and [RESV] for Closing Script) |

[⬆ Back to Query](#query)

---

### ConfigurationResortHubPropertyDetailsType

| Field | Type | Description |
| --- | --- | --- |
| associatedProperty | `String` | Associated Property |
| associatedPropertyName | `String` | Associated Property Name |
| croCode | `String` | Cro Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortJobTitleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| closingScriptYn | `String` | Display reservation closing script? |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Job title description |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### ConfigurationResortUDFCategoryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortUDFTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| attributeType | `String` | Determines the type of attribute. The value is bit specific. |
| attributeVerified | `String` | Attribute Verified |
| category | `String` | Category |
| chainCode | `String` | Chain Code |
| code | `String` | UDF type - CND. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| multipleYn | `String` | Not used. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| sequence | `Float` | Sequence |
| tableName | `String` | Table Name |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBrandCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBusinessUnitDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDepartmentCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDivisionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortHotelCategoryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortOperatingUnitDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortApplicationParameterValueDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aPNDeletedFlag | `String` | APN Deleted Flag |
| aPNDisplayYN | `String` | APN Display Parameter |
| aPNJRNUpdateDate | `Date` | JRN Update Date |
| aPNJRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| aPNPrimaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| aPNRNAInsertDate | `DateTime` | RNA Insert Date |
| aPNRNAUpdateDate | `DateTime` | RNA Update Date |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| copyYn | `String` | Determines if a parameter value shall not be copied due to dependent business logic in the target property. |
| coreYn | `String` | Indicates if parameter is used for Core functionality |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displayYn | `String` | Display Y/N |
| explanation | `String` | Not Used. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lovValues | `String` | Lov Values |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| parameterDescription | `String` | Parameter Description |
| parameterDisplayName | `String` | Parameter Display Name |
| parameterGroup | `String` | Parameter Group |
| parameterName | `String` | Parameter Name |
| parameterType | `String` | Parameter Type |
| parameterTypeDetail | `String` | Parameter Type Detail |
| parameterValue | `String` | Parameter Value |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| storedInResort | `String` | Internal Field that tells whether the value of the field is stored in the resort table or in the application Parameter table itself. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| usedInApp | `String` | Used In App |

[⬆ Back to Query](#query)

---

### ConfigurationResortTrackitActionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultYn | `String` | Default Y/N |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| messageText | `String` | Message Text |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sendMessageYn | `String` | Indicator to send a message to the guest when a new trackit item is created. |
| sequence | `Float` | Sequence |
| status | `String` | Internal status for this action. Used for ti_subgroup='ACTION'. |
| tiSubgroup | `String` | Track it SubGroup. Example: Location Type or Action. |
| trackItGroup | `String` | Trackit Group. |
| trackitTypesUrl | `String` | URL for trackit types. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTrackitLocationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actionStatus | `String` | Internal status for this action. Used for ti_subgroup='ACTION'. |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultYn | `String` | Default Y/N |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| messageText | `String` | Message Text |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sendMessageYn | `String` | Indicator to send a message to the guest when a new trackit item is created. |
| sequence | `Float` | Sequence |
| tiSubgroup | `String` | Track it SubGroup. Example: Location Type or Action. |
| trackItGroup | `String` | Trackit Group. |
| trackitTypesUrl | `String` | URL for trackit types. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTrackitTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actionStatus | `String` | Internal status for this action. Used for ti_subgroup='ACTION'. |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultYn | `String` | Default Y/N |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| messageText | `String` | Message Text |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sendMessageYN | `String` | Indicator to send a message to the guest when a new trackit item is created. |
| sequence | `Float` | Sequence |
| tiSubgroup | `String` | Track it SubGroup. Example: Location Type or Action. |
| trackItGroup | `String` | Trackit Group. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| website | `String` | URL for trackit types. |

[⬆ Back to Query](#query)

---

### ConfigurationResortAccountTypeDetailsType

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

### ConfigurationResortARReminderCycleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountTypeId | `Float` | Account Type ID |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| globalAccountYN | `String` | Indicates whether the account type is Global Account Type. Value 'Y' indicates that it is Global. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| letterName | `String` | Name of the reminder letter. |
| numberOfDays | `Float` | Number of days before the system geneates the Reminder letter. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reminderCode | `Float` | Internal number. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAcctFlagReasonDetailsType

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

### ConfigurationResortTransactionReasonCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adjustmentCode | `String` | Reason Code. |
| adjustmentCodeDescription | `String` | Description |
| adjustmentType | `String` | Adjustment Type |
| amountPercentFlag | `String` | Percentage / Amount flag. Allowed values: AMOUNT PERCENT. |
| amountPercentValue | `Float` | Amount or Percentage to consider during the adjustment. |
| birGuestType | `String` | Guest type in PH country mode. Further used for showing proper adjustment options. |
| codeType | `String` | Code Type |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| tranCodeType | `String` | Correction type. e.g. ADJ for adjustment COR for correction DEL for deletion. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCreditCardAuthorizationRulesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| amount | `Float` | Amount |
| authorizationRules | `Float` | Authorization Rules |
| cAmount | `Float` | Central Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| guaranteeCode | `String` | Guarantee Code |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| mainWindowYn | `String` | Indicates if this auth rule is for the main window (i.e. window 1). Default is Y i.e. Only if the flag is explicitly set to N does the rule apply to windows other than 1. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| percentage | `Float` | Percentage |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCategory | `String` | Rate Category |
| rateCode | `String` | Rate Code |
| roomClass | `String` | Room Class |
| roomType | `String` | Room Type |
| sourceCode | `String` | Source Code |

[⬆ Back to Query](#query)

---

### ConfigurationResortAutoFolioSettlementTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCashierDetailsType

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

### ConfigurationResortCustomNumberDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activeYN | `String` | Active YN |
| chainCode | `String` | Chain Code |
| code | `String` | Internal code to identify the custom number. |
| customNumberFormula | `String` | Custom Number Formula |
| customNumberType | `String` | Custom Number Type |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| endDate | `Date` | End Date |
| filterCondition | `String` | Filter Condition |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| sequence | `Float` | Sequence |
| startDate | `Date` | Start Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCurrencyExchangeTaxDetailsType

| Field | Type | Description |
| --- | --- | --- |
| amountFrom | `Float` | Minimum amount applicable to apply tax on the Currency Exchange. |
| amountTo | `Float` | Maximum amount applicable to apply tax on the Currency Exchange. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cMaxAmount | `Float` | Central Max Amount |
| cMaxServiceTax | `Float` | Central Max Service Tax |
| cMinimumAmount | `Float` | Central Min Amount |
| cMinimumServiceTax | `Float` | Central Min Service Tax |
| cNotionalAmount | `Float` | Central Notional Amount |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| maximum | `Float` | Flat amount service tax to be used when calculated service tax amount exceeds the flat amount. |
| minimum | `Float` | Flat amount service tax to be used when calculated service tax amount is less than this flat amount. |
| notionalAmount | `Float` | Notional amount applicable based on the service tax type range. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| percentage | `Float` | Tax Percentage applicable based on the service tax type. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| serviceTaxType | `String` | Stores the Service tax type. Possible values can be: R1 R2 R3 and so on. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortExpenseArrangementCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| arrangeId | `String` | Arrange ID |
| arrangementId | `Float` | Arrangement ID |
| bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRoutingAmount | `Float` | Central Routing Amount |
| compYn | `String` | Comp Y/N |
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
| expenseArrangementCode | `String` | Expense Arrangement Code |
| expenseArrangementDescription | `String` | Arrangement Description for the Transaction Code. |
| exportBucketType | `String` | User defined Export Bucket type. |
| inactiveDate | `DateTime` | Inactive Date |
| inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| routingPercent | `Float` | Routing Percent |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionCodeDetailsType

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

### ConfigurationResortFolioArrangementCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| arrangeId | `String` | Arrange ID |
| arrangementId | `Float` | Arrangement ID |
| bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRoutingAmount | `Float` | Central Routing Amount |
| compYn | `String` | Comp Y/N |
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
| folioArrangementCode | `String` | Folio Arrangement Code |
| folioArrangementDescription | `String` | Arrangement Description for the Transaction Code. |
| inactiveDate | `DateTime` | Inactive Date |
| inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| routingPercent | `Float` | Routing Percent |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGroupArrangementCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| arrangeId | `String` | Arrange ID |
| arrangementId | `Float` | Arrangement ID |
| bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRoutingAmount | `Float` | Central Routing Amount |
| compYn | `String` | Comp Y/N |
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
| groupArrangementCode | `String` | Group Arrangement Code |
| groupArrangementDescription | `String` | Arrangement Description for the Transaction Code. |
| inactiveDate | `DateTime` | Inactive Date |
| inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| routingPercent | `Float` | Routing Percent |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortFolioTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allowCompressYn | `String` | Folio to be use for compress bills |
| allowConvertYn | `String` | Folio type used for Converting the Folios |
| allowCreditbillYn | `String` | Allow Credit Bill |
| allowDifferenceProfile | `String` | This column is used to allow (or) disallow different profile when generating Credit/Debit bill. |
| arfolioName | `String` | name of the folio which is used for bills generated in A/R |
| associatedCreditFolioType | `String` | Stores the Linked / Associated Credit Folio Type. |
| clFlag | `String` | whether this folio type is used for City Ledger bills or not |
| columnSeparator | `String` | Column Separator to be used when creating XML file for Fiscal Printing. |
| compressYn | `String` | Whether to compress the file before delivery. |
| convertFolioType | `String` | Folio Type that will be converted to |
| correctionFolioYn | `String` | Identify the correction folio type. Added for Greece. |
| correctionHeaderYn | `String` | Identifies if this folio type is used for folio header correction. |
| creditYN | `String` | folio type used for Credit bills or not |
| currencyActionId | `Float` | Curr Action ID |
| customOnProfAttributesYn | `String` | If "Y" OPERA calls an API to consider the folio type based on attributes of the payee / company / TA / guest profiles of the guest. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| debitBillYN | `String` | Identifies if this folio type is used for a Supplemental Folio which is an additional folio to an existing folio. |
| debitFlag | `String` | Identifies if the folio_type is a debit folio. [Y/N] |
| deletedFlag | `String` | Deleted Flag |
| depositFolioYn | `String` | Identifies if this folio type is a deposit folio type. |
| directBillYn | `String` | Folio type related to Direct Bill / City Ledger settlements. |
| documentCode | `String` | Unique Document Code |
| fiscalPrintingYn | `String` | Identifies if the folio type will generate fiscal folio. |
| fiscalProgramName | `String` | Fiscal Executable Program Name (without filepath) |
| fiscalYn | `String` | Indicates if this export bucket is FISCAL related. |
| folioName | `String` | name of the folio report to be used for this folio type for Reservation Bills |
| folioTypeCode | `String` | Folio Type Code |
| guestType | `Float` | Guest Type |
| internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| localCurrFlag | `String` | whether this folio type is used for any bills generated with local currency or any other currency |
| manualFolioPrintTask | `String` | Indicates if the folio type has a manual folio print task associated. |
| nameTaxType | `String` | Name Tax Type |
| nationalityFlag | `String` | whether this record is used for Local national or foreigner |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalFolioStayDetailsYN | `String` | Indicates if this folio type will display stay details of the original folio.  Used for Credit Bills and Supplemental folios. |
| passerbyfolioName | `String` | name of the passerby folio used for bills generated from Passerby |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printFolioYn | `String` | Identifies if the settlements using this folio type will print a paper folio. |
| property | `String` | Property |
| queueName | `String` | Queue Name |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| simpleFolioYn | `String` | Identifies if this folio type is a simple folio type. |
| taxNoFlag | `String` | Folio type is used for profiles which have a tax number or not. |
| trxServiceType | `String` | Transaction Service Type |
| workingDocsYn | `String` | Used only for Information and Pro-forma folios. |

[⬆ Back to Query](#query)

---

### ConfigurationResortFolioTypeDetailDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `String` | name of the folio report to be used for this folio type for Reservation Bills |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| folioType | `String` | Folio Type |
| group | `String` | The Group for which this belongs to P- Passerby;G-Guest FolioA- Ar folio |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| language | `String` | Language |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### ConfigurationResortBankAccountDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountId | `Float` | Account ID |
| accountNumber | `String` | Account Number |
| bankAcctType | `String` | Flag to identify bank type  [O] OVOS user |
| bankCode | `String` | Code for the bank account |
| branchCode | `String` | Code for the bank accounts branch |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| centralMinProcessingAmount | `Float` | Central Min. Processing Amount |
| checkReport | `String` | Check Report |
| checkSubLines | `Float` | Number of lines to be printed on check stub |
| currency | `String` | Currency |
| currencyDescription | `String` | Currency Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultYN | `String` | Default YN |
| defaultForCurrencyYN | `String` | Only one 'Y' value is permitted per resort / currency combination used mainly by interface to figure out default bank for resort and currency combination |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Bank name |
| editCheckNumberYN | `String` | Check number allowed to be edited Y/N |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| language | `String` | Language |
| lastExportDate | `Date` | Last Export File Run Date |
| lastExportedFile | `Float` | Last Export Run File Number |
| maxCheckNo | `Float` | Internal |
| minProcessingAmount | `Float` | Minimum amount required to produce a check through commission processing for the selected account. |
| nextCheckNumber | `Float` | Last check number used by commisison handling module for bank account selected |
| onHold | `Float` | On Hold |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paidInAR | `Float` | Paid in AR |
| paymentMethod | `String` | Payment Method |
| positivePayExportYN | `String` | Indicate that the bank account uses Positive Pay Export. |
| potential | `Float` | Potential |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| routingNumber | `String` | Routing number for the bank account |
| sourceImportDir | `String` | Source directory for importing commission information. |
| targetImportDir | `String` | Target directory where import files will be stored. |
| tax1099ReportYN | `String` | Indicate that bank account use 1099 report |
| toBePaid | `Float` | To Be Paid |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| validateIATANumberYN | `String` | Force validation of TA/Source IATA number during commision payment process. |

[⬆ Back to Query](#query)

---

### ConfigurationResortCommissionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| amount | `Float` | Amount |
| basedOn | `String` | Based On |
| cAmount | `Float` | Central Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cVatAmount | `Float` | Central Vat Amount |
| centralCode | `String` | Central Code |
| centralCommissionDescription | `String` | Central Commission Description |
| code | `String` | Code |
| commissionCalcRule | `String` | Calculation rule for the commission |
| commissionFlatPercentage | `String` | Commission percentage or flat commission |
| commissionamount | `Float` | Commissionamount |
| commissionid | `String` | Commissionid |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultYN | `String` | Default YN |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| holdARYN | `String` | Commission marked as Hold if transaction code AR_SETTLE_CODE used for payment. |
| holdAlwaysYN | `String` | Commission marked as Hold automatically. |
| holdPrepaidYN | `String` | Commission marked as Hold if  transaction code DEFAULT_PREPAID_COMM used for payment. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masteralias | `Float` | Masteralias |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| perNight | `String` | Commission is per night Y/N |
| perNightAmount | `Float` | Per Night Amount |
| perStay | `String` | Commission is per stay Y/N |
| perStayAmount | `Float` | Per Stay Amount |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repSellSequence | `Float` | Reporting Sell Sequence |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sellSequence | `Float` | Sell Sequence |
| taxPercent | `Float` | Tax Amount for Commission. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAuthorizerGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `String` | Code |
| compAuthorizerGroupDescription | `String` | Comp Authorizer Group Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAuthorizerGroupDetailDetailsType

| Field | Type | Description |
| --- | --- | --- |
| arrangementId | `Float` | Arrangement ID |
| authGroupCode | `String` | Auth Group Code |
| cCreditLimit | `Float` | Central Credit Limit |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cOccurrenceLimit | `Float` | Central Occurrence Limit |
| centralTransactionCodes | `String` | Central Transaction Codes |
| compRoutingCodes | `String` | Comp Routing Codes |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyCreditLimit | `Float` | Daily Credit Limit |
| deletedFlag | `String` | Deleted Flag |
| groupHeaderId | `Float` | Group header ID used to assign transaction or arrangement codes to different limit groups |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| transactionCodes | `String` | Transaction Codes |
| transferLimit | `Float` | Per instance limit for this group_header_id. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAuthorizerDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRAccountNumber | `String` | AR Account Number |
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
| appPassword | `String` | The encrypted application password of this user |
| appUserDescription | `String` | Description about the User |
| appUserId | `Float` | App User ID |
| appUserType | `String` | Defines the type of user.Valid values: U and G U-->User :: G-->Group |
| appUserUniq | `String` | Unique internal ID...needed for ASP module as the same user name can't exists across chains. |
| authHeaderId | `Float` | Link from Authorizer_limits_header table. |
| authorizerGroup | `String` | Authorizer Group |
| authorizerId | `Float` | Authorizer ID |
| authorizerInactiveDate | `DateTime` | Date the authorizer became inactive |
| authorizerYn | `String` | Denotes if this user is an authorizer. Allowable values are 'Y' and 'N' |
| cCreditLimit | `Float` | Central Credit Limit |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cHourlyRate | `Float` | Central Hourly Rate |
| cOccurrenceLimit | `Float` | Central Occurrence Limit |
| cWeeklySalary | `Float` | Central Weekly Salary |
| centralTransactionCodes | `String` | Central  Transaction Codes |
| chainCode | `String` | Chain Code |
| comments | `String` | Comments |
| compRoutingCodes | `String` | Comp Routing Codes |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyCreditLimit | `Float` | Daily Credit Limit |
| dateHired | `Date` | Date employee was hired |
| defCashierId | `Float` | Cashier ID for the User |
| defaultForm | `String` | Not Used |
| defaultLanguage | `String` | Default language of the user. |
| defaultMfnResort | `String` | Not used. |
| defaultReportgroup | `String` | Defaults the Report Module to this Report Group |
| defaultResort | `String` | Stores resort name to which user will log in every time |
| defaultTerminal | `String` | Default terminal of the user. |
| deletedFlag | `String` | Deleted Flag |
| deptId | `String` | Dept ID |
| description | `String` | Description |
| disabledUntil | `Date` | When account is disabled this date is set to date when account should be enabled again |
| empExtension | `String` | Employee Extension Number |
| empPager | `String` | Pager Number |
| empStatus | `String` | Emp Status |
| employeeIncentiveNumber | `String` | Identifies a hotel employee for incentive programs. |
| employeeNumber | `String` | This column is used by Starwood Hotels for Storing their internal employee number |
| expiresOn | `DateTime` | Date on which user ID will be disabled. |
| firstName | `String` | First Name |
| forcePasswordChangeYn | `String` | Requires the user to change the password at login. |
| fridayMax | `Float` | Max hours for Friday |
| fridayMin | `Float` | Min hours for Friday |
| generalFilepath | `String` | Stores General File path for Mailmerge |
| graceLogin | `Float` | Number of Logins allowed after password has expired |
| hireType | `String` | Type of hire: F-Full Time P-Part Time |
| hourlyRate | `Float` | If RATE_TYPE=H: hourly employee rate |
| hoursPerWeek | `Float` | Hours Per Week |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveFrom | `DateTime` | Inactive Start Date |
| inactiveReasonCode | `String` | Reason Code for inactive status from REASON table |
| inactiveTo | `DateTime` | Inactive End Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalYn | `String` | Internal Y/N |
| isSuperuser | `String` | When this is set to Y a user gets all the rights defined in application. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopId | `Float` | Laptop ID |
| lastLoggedResort | `String` | Last property the user was logged in. |
| lastLoggedTimestamp | `Date` | Date and Time the User was logged in last time |
| lastName | `String` | Last Name |
| leadAddress | `String` | Lead Address Code determines primary receipient |
| leadAddressDet | `String` | Lead Address (email/fax no) |
| leadComm | `String` | Lead Communication Type |
| lockoutDate | `DateTime` | Timestamp with the useraccount was locked out. |
| loginAttempts | `Float` | Invalid password login attempts counter. |
| loginCro | `String` | Login Cro |
| loginDomain | `String` | Login Domain |
| maleFemale | `String` | Employee Gender |
| maxCheckoutDays | `Float` | Maximum number of days allowed for checkout in Laptop Module |
| maxDaysAfterCo | `Float` | Maximum number of days after checkout that a folio can be reopened. |
| maxUserSessions | `Float` | Maximum number of Opera Sessions allowed at single point of time. |
| mfnUserType | `String` | User type for OCM mode: [C]orporate User |
| mobileAlertsYn | `String` | Indiciates if alerts are send to mobile registered guests for required action and manual checkout.. |
| mondayMax | `Float` | Max hours for Monday |
| mondayMin | `Float` | Min hours for Monday |
| nCExchangeDate | `Date` | N Central Xchange Date |
| nCExchangeRate | `Float` | N Central Xchange Rate |
| nDeletedFlag | `String` | N Deleted Flag |
| nInsertDate | `DateTime` | N Insert Date |
| nInsertUser | `Float` | N Insert User |
| nUpdateDate | `Date` | N Update Date |
| nUpdateUser | `Float` | N Update User |
| occurrenceLimit | `Float` | Per instance limit for this group_header_id. |
| oraclePassword | `String` | not used |
| oracleUid | `Float` | Not used |
| oracleUser | `String` | not used |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| otMultiplier | `Float` | Overtime Multiplier |
| passwordChangeDays | `Float` | Period of Days the Password expires |
| passwordLastChange | `Date` | TimeStamp of last Password Change |
| personNameId | `Float` | Foreign key to NAME table that links this USER to an Employee |
| preventAccountLockout | `String` | Indicates if this user can be excluded from user account lock. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| propertyAccessYn | `String` | Indicates that a User Group has the purpose of defining property access only (no permissions allowed). |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Default rate code for this authorizer. |
| rateType | `String` | Rate Type |
| receiveBroadcastMsg | `String` | Receive Broadcast Msg |
| rehireYn | `String` | Indicates if a terminated employee shall be rehired |
| salaryInterval | `String` | Salary Interval: M-Monthly W-Weekly |
| saturdayMax | `Float` | Max hours for Saturday |
| saturdayMin | `Float` | Min hours for Saturday |
| serviceRequestAlertsYn | `String` | Indicates if this Application User can receive Alerts related to Service Requests. |
| sfaName | `String` | Sfa Name |
| srepCode | `String` | Srep Code |
| srepGroup | `String` | Assigned Sales Manager Group(s) |
| sundayMax | `Float` | Max hours for Sunday |
| sundayMin | `Float` | Min hours for Sunday |
| termReason | `String` | Termination Reason |
| terminatedDate | `Date` | Termination Date |
| thursdayMax | `Float` | Max hours for Thursday |
| thursdayMin | `Float` | Min hours for Thursday |
| timezoneRegion | `String` | Time zone region selected by the employee. |
| title | `String` | Title |
| transactionCodes | `String` | Transaction Codes |
| transferLimit | `Float` | Transfer Limit |
| tuesdayMax | `Float` | Max hours for Tuesday |
| tuesdayMin | `Float` | Min hours for Tuesday |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| userFilepath | `String` | Store User File path. for Mailmerge |
| userGroupAdmin | `String` | User group can be granted by the user group administrator if value is 'Y'. |
| userIDCode | `String` | User ID Code |
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

### ConfigurationResortBucketRedemptionCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| transactionCode | `String` | Transaction Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCompRoutingCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| applyPerDayYN | `String` | Apply Per Day YN |
| arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| arrangementId | `Float` | Arrangement ID |
| bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRoutingAmount | `Float` | Central Routing Amount |
| centralTransactionCodes | `String` | Central Transaction Codes |
| code | `String` | Code |
| compYn | `String` | Comp Y/N |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Arrangement Description for the Transaction Code. |
| eligibleYn | `String` | Specifies the Eligibility to calculate membership points. |
| exportBucketType | `String` | User defined Export Bucket type. |
| friday | `String` | Friday |
| inactiveDate | `DateTime` | Inactive Date |
| inheritRateCodeYN | `String` | Inherit the authorizer rate code onto the reservation. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| monday | `String` | Monday |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| routingPercentage | `Float` | Routing Percentage |
| saturday | `String` | Saturday |
| sunday | `String` | Sunday |
| thursday | `String` | Thursday |
| transactionCodes | `String` | Transaction Codes |
| tuesday | `String` | Tuesday |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| wednesday | `String` | Wednesday |

[⬆ Back to Query](#query)

---

### ConfigurationResortCompTransactionCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRNameId | `Float` | Ar Name ID |
| accountNumber | `String` | Account Number |
| accountingCode | `String` | Accounting Code |
| acctrecvprofileid | `Float` | Acctrecvprofileid |
| adjTrxCode | `String` | Adj Transaction Code |
| adjtranscodeid | `String` | Adjtranscodeid |
| arrangeCode | `String` | Arrange Code |
| cDefaultPrice | `Float` | Central Default Price |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cExportBucket | `Float` | Central Export Bucket |
| cMaxAmount | `Float` | Central Max Amt |
| cMinimumAmount | `Float` | Central Min Amt |
| cCCode | `String` | CC Code |
| cRSTaxDesc | `String` | Crs Tax Description |
| ccType | `String` | Cc Type |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralGroup | `String` | Central Group |
| centralSubgroup | `String` | Central Subgroup |
| checkNumberMandatoryYN | `String` | Check Number Mandatory YN |
| class1MandatoryYn | `String` | Class 1 Mandatory Y/N |
| class2MandatoryYn | `String` | Class 2 Mandatory Y/N |
| code | `String` | Code |
| commission | `Float` | Commission |
| compNightsYn | `String` | Comp Nights Y/N |
| compPaymentsYN | `String` | Comp Payments YN |
| compYn | `String` | Comp Y/N |
| corpPropFlag | `String` | Corp Prop Flag |
| corporateDescription | `String` | Corporate Description |
| currency | `String` | Currency |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyPlanFolio | `Float` | Daily Plan Folio |
| dedOwnerRevenueYN | `String` | Ded Owner Rev Y/N |
| defaultPrice | `Float` | Default Price |
| deferredYn | `String` | Deferred Y/N |
| deletedFlag | `String` | Deleted Flag |
| depositPostingOnlyYn | `String` | Deposit Posting Only Y/N |
| depositType | `String` | Stores the type of the deposit: possible values "RECEIPT" or "FOLIO". |
| description | `String` | Description |
| eInvoiceYn | `String` | E Invoice Y/N |
| expenseFolio | `Float` | Expense Folio |
| exportBucket | `Float` | Export Bucket |
| externalPaymentCode | `String` | External Payment Code |
| fiscalPaymentYn | `String` | Fiscal Payment Y/N |
| fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| foreignCurrencyID | `String` | Foreign Currency ID |
| frequentFlyerYn | `String` | Frequent Flyer Y/N |
| generatesInclusiveYN | `String` | Generates Inclusive YN |
| group | `String` | Group |
| groupFolio | `Float` | Group Folio |
| groupPointsRedemptionYN | `String` | Gp Points Redemption Y/N |
| inHouseDepositYN | `String` | To indicate that the transaction code can be used as a Deposit Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| inHousePayYN | `String` | To indicate that the transaction code can be used as a Payment Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| inHouseSalesYN | `String` | To indicate that the transaction code can be used as a Sales Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| includeIn8300Yn | `String` | Include In 8300 Y/N |
| includeInDepositCXLRuleYN | `String` | Include in Deposit/CXL Rule YN |
| indBilling | `String` | Individual Billing |
| indCash | `String` | Individual Cash |
| individualAr | `String` | Ind AR |
| individualDepositYN | `String` | Ind Deposit Y/N |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| internalYn | `String` | Internal Y/N |
| isManualPostAllowed | `String` | Is Manual Post Allowed |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| manualPostCoversYn | `String` | Manual Post Covers Y/N |
| maximumAmount | `Float` | Maximum Amount |
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
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| resultIncludedInSumArray | `String` | Result Included In Sum Array |
| revenueBucketId | `Float` | Rev Bucket ID |
| revenueGroupId | `Float` | Rev Gp ID |
| revenueGroupYN | `String` | Revenue Group YN |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| rotationRevenueYN | `String` | Rotation Rev Y/N |
| roundingFactorYN | `String` | Rounding Factor YN |
| serviceRecoveryTrxCode | `String` | Service Recovery Adjustment. |
| subgroup | `String` | Subgroup |
| taxCode | `Float` | Tax Code |
| tcBofInterface | `String` | Not Used. |
| tcBofInterface2 | `String` | Not Used. |
| tcBofRefCode | `String` | Not Used. |
| tcBofRefCode2 | `String` | Not Used. |
| tcResort2 | `String` | Not Used. |
| tcTransactionType | `String` | Transaction Code Transaction Type |
| tclCodeDfltCl1 | `String` | Tcl Code Dflt Cl1 |
| tclCodeDfltCl2 | `String` | Tcl Code Dflt Cl2 |
| transactionActionId | `Float` | Trx Action ID |
| transactionCodeResort | `String` | Not Used. |
| transactionType | `String` | Transaction Type |
| transcodearrangementid | `String` | Transcodearrangementid |
| transcodeid | `String` | Transcodeid |
| transgroupid | `String` | Transgroupid |
| transsubgroupid | `String` | Transsubgroupid |
| trxCodeDisplay | `String` | Transaction Code Display |
| trxCodeType | `String` | Transaction Code Type |
| trxServiceType | `String` | Transaction Service Type |
| trxTaxTypeCode | `String` | Transaction Tax Type Code |
| upcCode | `String` | Upc Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionCodeCompExternalReferenceDetailsType

| Field | Type | Description |
| --- | --- | --- |
| associatedTransactionCode | `String` | Associated Transaction Code |
| associatedTransactionDescription | `String` | Associated Transaction Description |
| centralAssociatedTransactionCode | `String` | Central Associated Transaction Code |
| centralAssociatedTransactionDescription | `String` | Central Associated Transaction Description |
| compTrxCode | `String` | Comp Transaction Code that the trx_code value will be posted against |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### ConfigurationResortCodeGeneratesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adjustmentType | `String` | Adjustment Type |
| amount | `Float` | Amount |
| amountFromScheduleYn | `String` | Whether to take the taxes from Price Schedules. |
| cAmount | `Float` | Central Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| calculationSequence | `Float` | Sequence in which the taxes should be applied. |
| centralDescription | `String` | Central Description |
| centralGeneratedCode | `String` | Central Generated Code |
| currency | `String` | Currency |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| generateRules | `String` | Generate Rules |
| generatedBy | `String` | Generated By |
| generatedCode | `String` | Generated Code |
| generatedPrintedOnFolioYn | `String` | Whether to print on folio. |
| id | `Float` | ID |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| nameTaxType | `String` | Name Tax Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| percentage | `Float` | Percentage |
| percentageBaseCode | `Float` | Indicates if the tax is based on a percentage. It would have a value of 0 if based on BASE amount 1 if on S1 2 if based on S2 3 if based on S3. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| resultIncludedInSumArray | `String` | Result Included In Sum Array |
| roundingMethod | `String` | Rounding method to be used when calculating a generate amount. Allowed values are UP DOWN NONE and NULL. |
| seqBy | `Float` | Sequence By |
| stopDays | `Float` | Days after which the generates will not be posted for long standing guests. |
| subTotal1YN | `String` | Sub-Total 1 YN |
| subTotal2YN | `String` | Sub-Total 2 YN |
| subTotal3YN | `String` | Sub-Total 3 YN |
| tcDsi | `Float` | Transaction Code Dsi |
| tcGroup | `String` | Transaction Code Group |
| tcGroupGenerator | `String` | Group generator. |
| tcOrganizationid | `Float` | Transaction Code Organizationid |
| tcSubgroup | `String` | Transaction Code Subgroup |
| tcSubgroupGenerator | `String` | Subgroup generator. |
| tclCodeGenerator | `String` | Identify if the taxes are generated on the Class. |
| tcrType | `String` | Flag to indicate the addon tax. |
| transactionCodeResort | `String` | Not Used. |
| transactionCodeTrxCode | `String` | Tc Transaction Code |
| trxCodeGenerator | `String` | Transaction Code Generator |
| udfFunction | `String` | Udf Function |
| udfInverse | `String` | Not used currently. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| useTaxBracketYn | `String` | Flag to indicate if tax brackets are used for this tax. |

[⬆ Back to Query](#query)

---

### ConfigurationResortCompTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
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
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBarScheduleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| date | `Date` | Date |
| dayOfWeek | `String` | Day of Week |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lengthOfStay | `Float` | Length of Stay |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCityTaxRangeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| amountFrom | `Float` | Defines the starting value for the amount range. |
| amountTo | `Float` | Defines the ending value for the amount range. |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| intervalAmount | `Float` | Defines the incremental value for the amounts that qualify for additional tax amounts. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| packageFormulaRangeId | `Float` | Oracle sequence to maintain uniqueness. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| recordType | `String` | Record Type |
| taxAmount | `Float` | Tax Amount |
| taxPercentage | `Float` | The Luxury Tax Percentage for the country for which this record belongs to. |
| taxRangeType | `String` | Stores the Japanese Tax Range Type. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyDayTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adder | `Float` | Amount to be added  before showing in rate query |
| centralDayTypesCode | `String` | Central Day Types Code |
| centralSequence | `Float` | Central Sequence |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dayTypesCode | `String` | Day Types Code |
| dayTypesDescription | `String` | Day Type description |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| dtRemarks | `String` | Remarks for the day type |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| multiplier | `Float` | Amount to be multiplied before showing in rate query |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repDtRemarks | `String` | Reporting Dt Remarks |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDisplaySetDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyCalendarEventDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activeYN | `String` | Active YN |
| blackoutYn | `String` | Indicates whether an event is a blackout event or not. |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description of the event |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| oRMSEventYN | `String` | Orms Event Y/N |
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
| showInOperaYn | `String` | Indicates if the event should be displayed in Opera. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortRateHurdlesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| actualRoomsSold | `Float` | Actual Rooms Sold |
| amountOfHurdleRate | `Float` | Amount of Hurdle Rate |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cHurdle | `Float` | Central Hurdle |
| cORMSPriceRoomDelta | `Float` | Central Orms Price Room Delta |
| centralRoomClass | `String` | Central Room Class |
| centralRoomClassDescription | `String` | Central Room Class Description |
| centralRoomType | `String` | Central Room Type |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| centralYieldCategory | `String` | Central Yield Category |
| centralYieldCategoryDescription | `String` | Central Yield Category Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| delta | `Float` | Delta |
| hurdleDate | `Date` | Hurdle Date |
| hurdlerateid | `Float` | Hurdlerateid |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lengthOfStay | `Float` | Length of Stay |
| locationID | `String` | Internal ID to uniquely identify the Property |
| maxRoomsSold | `Float` | Max Rooms Sold |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| overrideYN | `String` | Override YN |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomCategoryLabel | `String` | Room Category Label |
| roomClass | `String` | Room Class |
| roomClassDescription | `String` | Room Class Description |
| roomType | `String` | Room Type |
| roomTypeDescription | `String` | Room Type Description |
| roomcategoryid | `String` | Roomcategoryid |
| roomsToSellBeforeDeltaIsApplied | `Float` | Rooms to Sell before Delta is Applied |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| yieldCategory | `String` | Yield Category |
| yieldCategoryDescription | `String` | Yield Category Description |
| yieldcategoryid | `String` | Yieldcategoryid |
| yieldmarkettype | `String` | Yieldmarkettype |

[⬆ Back to Query](#query)

---

### ConfigurationResortProductDetailsType

| Field | Type | Description |
| --- | --- | --- |
| addtorateflag | `String` | Addtorateflag |
| alternateCodes | `String` | Alternate Codes |
| arrangementCode | `String` | Arrangement Code |
| beginSellDate | `Date` | Begin Sell Date |
| bookingDuration | `Float` | Not used |
| calculationRule | `String` | Calculation Rule |
| cateringYn | `String` | Catering Y/N |
| centralAlternateCodes | `String` | Central Alternate Codes |
| centralPackage | `String` | Central Package |
| centralPackageGroupCode | `String` | Central Package Group Code |
| centralPackageGroupDescription | `String` | Central Package Group Description |
| centralPackageLoss | `String` | Central Package Loss |
| centralPackageOverage | `String` | Central Package Overage |
| centralPackageProfit | `String` | Central Package Profit |
| centralTransactionCode | `String` | Central Transaction Code |
| currency | `String` | Currency |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| deliveryTimeReqrdYn | `String` | Indicates if a Delivery Time is required. |
| description | `String` | Description |
| endSellDate | `Date` | End Sell Date |
| externalLocked | `String` | External Locked |
| flexibleDurationYn | `String` | Not used |
| forecastGroup | `String` | Package forcast group code |
| forecastGroupCode | `String` | Not used |
| forecastNextDayYN | `String` | Forecast Next Day YN |
| foreignCurrencyID | `String` | Foreign Currency ID |
| formula | `String` | Formula |
| genPlAtEodOfCoDate | `String` | Gen Pl At Eod of Co Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| inventoriedflag | `String` | Inventoriedflag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| longInfo | `String` | Long Info |
| maxPersons | `String` | Maximum number of persons |
| minimumAdvBookDays | `Float` | Minimum Advance Booking Days required for the product. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| outletCode | `String` | Outlet Code |
| overrideFixedRateYn | `String` | Override Fixed Rate Y/N |
| package | `String` | Package |
| packageAllowanceYN | `String` | Package Allowance YN |
| packageDescription | `String` | Package Description |
| packageGroupCode | `String` | Package Group Code |
| packageGroupDescription | `String` | Package Group Description |
| packageLoss | `String` | Package Loss |
| packageOverage | `String` | Package Overage |
| packageOverageTaxInclusiveYN | `String` | Package Overage Tax Inclusive YN |
| packageProfit | `String` | Package Profit |
| pkgforecastgrpid | `String` | Pkgforecastgrpid |
| postNextDayYN | `String` | Post Next Day YN |
| postingRhythm | `String` | Posting Rhythm |
| postingType | `String` | Type of package (group element) |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printseparateflag | `String` | Printseparateflag |
| productid | `String` | Productid |
| property | `String` | Property |
| redemptionproductflag | `String` | Redemptionproductflag |
| repDescription | `String` | Rep Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repTrxCodeDesc | `String` | Rep Trx Code Desc |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sellSeparateYN | `String` | Sell Separate YN |
| sellowsflag | `String` | Sellowsflag |
| shortDescription | `String` | Short Description |
| standardDuration | `Float` | Not used |
| standardPersons | `String` | Not used |
| taxInclusiveYN | `String` | Tax included Y/N |
| ticketsYn | `String` | Indicates a Reservation Ticket Package. |
| transactionCode | `String` | Transaction Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| validEndTime | `Date` | Valid End Time |
| validStartTime | `Date` | Valid Start Time |

[⬆ Back to Query](#query)

---

### ConfigurationResortItemPackageDetailsType

| Field | Type | Description |
| --- | --- | --- |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| item | `String` | Item of configuration data. |
| itemId | `Float` | Item ID |
| itemProdId | `Float` | Unqiue ID from ITEM_PACKAGES_SEQNO |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| product | `String` | Product |
| property | `String` | Code to uniquely identify the Property |
| qunatity | `Float` | Qunatity |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortRateProductPriceDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allowanceAmount | `Float` | Allowance for the product. |
| bucket2AllowanceAmount | `Float` | Allowance for the product for children in age bucket2. |
| bucket2Price | `Float` | Product price for children in age bucket2. |
| bucket3AllowanceAmount | `Float` | Allowance for the product for children in age bucket3. |
| bucket3Price | `Float` | Product price for children in age bucket3. |
| cAllowanceAmount | `Float` | Central Allowance Amount |
| cBucket2AllowanceAmount | `Float` | Central Bucket2 Allowance Amount |
| cBucket2Price | `Float` | Central Bucket2 Price |
| cBucket3AllowanceAmount | `Float` | Central Bucket3 Allowance Amount |
| cBucket3Price | `Float` | Central Bucket3 Price |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cPrice | `Float` | Central Price |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| day1 | `String` | Day1 |
| day2 | `String` | Day2 |
| day3 | `String` | Day3 |
| day4 | `String` | Day4 |
| day5 | `String` | Day5 |
| day6 | `String` | Day6 |
| day7 | `String` | Day7 |
| deletedFlag | `String` | Deleted Flag |
| endDate | `Date` | End Date |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| maximumGuests | `Float` | Maximum number of persons |
| maximumNights | `Float` | Maximum Nights. |
| minimumGuests | `Float` | Minimum number of persons for the rate product price. |
| minimumNights | `Float` | Minimum number of stay nights for the rate product price. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pointsRequired | `Float` | Points Required |
| price | `Float` | Price |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| product | `String` | Product |
| property | `String` | Property |
| propertyRateProductDetailId | `Float` | Internal id |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| seasonCode | `String` | Season Code |
| startDate | `Date` | Start Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPackageForecastGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activeYN | `String` | Active YN |
| code | `String` | Package forcast group code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
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
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPromotionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| authorizerId | `Float` | Authorizer ID |
| bookingEndDate | `Date` | Last Date Bookings can be made using the promotion. |
| bookingStartDate | `Date` | First Date Bookings can be made using the promotion. |
| category | `String` | Category |
| centralDescription | `String` | Promotion Name. |
| chainCode | `String` | Chain Code |
| checkInTime | `Date` | CheckIn Time for Promotion. |
| checkOutTime | `Date` | Check Out Time for Promotion. |
| code | `String` | Code |
| couponExChars | `String` | Exclude Characters while generating custom coupons. |
| couponGenFormat | `String` | Format for Custom based Random Generation option. 9 :Numbers U  :  upper case alpha characters only X  :  any alpha-numeric characters (upper). |
| couponGenOption | `String` | Generation option. N :Numbers U  :  upper case alpha characters only X  :  any alpha-numeric characters (upper) C  :  Custom Format. |
| couponLength | `Float` | Length of coupon code. |
| couponPrefix | `String` | Any Prefix to be appended to custom coupons. |
| couponSuffix | `String` | Any Suffix to be appended to custom coupons. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| group | `String` | Group |
| idRequiredDescription | `String` | Description of id requirements. |
| idRequiredYN | `String` | Indicates if an id is required for the promotion. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| information | `String` | Information for the promotion. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| instructions | `String` | Promotion Instructions for the property. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| limitedTimePromotionYn | `String` | Indicate if promotion is limited time use. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| lockedByCode | `String` | Code of the system that is managing this record: local system application name or external system database id |
| lockedByType | `String` | Type of the system that is managing this record: L for local and E for external system. |
| longDescription | `String` | Description of Promotion. |
| mktgprogramid | `String` | Mktgprogramid |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| promoSequenceId | `Float` | Promo Seq ID |
| promotionid | `String` | Promotionid |
| property | `String` | Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repUpdateDate | `Date` | Reporting Updatedate |
| reportingPromoSequenceId | `String` | Rep Promo Seq ID |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| setOrAccountFlag | `String` | Indicates if set(S) or account (a) is required for booking. |
| stayEndDate | `Date` | End Date a guest can stay for the promotion. |
| stayStartDate | `Date` | First Date a guest can stay for the promotion. |
| updateDate | `DateTime` | Update Date |
| updateOutsideBookingDatesYN | `String` | Indicates if reservations with this promotion can be updated outside the promotion booking dates. |
| updateUser | `Float` | Update User |
| upgradeAllowedYN | `String` | Indicates if upgrades are allowed for the promotion. |
| voucherBenefitCode | `String` | Voucher Benefit Code |

[⬆ Back to Query](#query)

---

### ConfigurationResortPromotionRateDetailsType

| Field | Type | Description |
| --- | --- | --- |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | How  the Rate Plan applies to the promotion such as Booking awardmiles |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| promoCode | `String` | Promo Code |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### ConfigurationResortPromotionCodeRoutingInstructionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| authorizerId | `Float` | Authorizer ID |
| authorizerName | `String` | Authorizer Name |
| autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| beginDate | `Date` | Begin Date |
| centralTransactionCodes | `String` | Central  Transaction Codes |
| chainCode | `String` | Chain Code |
| comments | `String` | Comments |
| compPreApprovalRequiredYn | `String` | Comp Pre Approval Required Y/N |
| covers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| creditLimit | `Float` | Credit Limit |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyYn | `String` | Daily Y/N |
| deletedFlag | `String` | Deleted Flag |
| endDate | `Date` | End Date |
| folioView | `Float` | Folio View |
| friday | `String` | Friday |
| membershipId | `Float` | Membership ID |
| monday | `String` | Monday |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| percentage | `Float` | Percentage |
| promoCode | `String` | Promo Code |
| promptForAuthorizerYn | `String` | Indicates if the user should be prompted for an Authorizer. |
| property | `String` | Property |
| routingCodes | `String` | Reservation routing code. |
| saturday | `String` | Saturday |
| sunday | `String` | Sunday |
| thursday | `String` | Thursday |
| transactionCodes | `String` | Transaction Codes |
| tuesday | `String` | Tuesday |
| wednesday | `String` | Wednesday |

[⬆ Back to Query](#query)

---

### ConfigurationResortRateCategoriesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessDate | `Date` | Business Date |
| centralDescription | `String` | Central Description |
| centralRateCategory | `String` | Central Rate Category |
| centralRateClass | `String` | Central Rate Class |
| centralRateClassDescription | `String` | Central Rate Class Description |
| centralSequence | `Float` | Central Sequence |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| displayDefaultYn | `String` | Display the rate category Y/N |
| displaySet | `String` | Display Set |
| endDate | `Date` | End Date |
| exportBucketCode | `String` | Export Bucket Code |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rateCategory | `String` | Rate Category |
| rateCategoryDescription | `String` | Rate Category Description |
| rateClass | `String` | Rate Class |
| rateClassDescription | `String` | Rate Class Description |
| rateTier | `String` | Rate Tier |
| ratecategoryid | `String` | Ratecategoryid |
| ratetierid | `String` | Ratetierid |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortArticleDetailsType

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

### ConfigurationResortCreditCardTypesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| canDeleteYn | `String` | Can Delete Y/N |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPaymentMethodDetailsType

| Field | Type | Description |
| --- | --- | --- |
| addressVerificationYn | `String` | Determines if this payment type captures the credit card billing address information during payment. |
| authAtCheckinYn | `String` | Authorization has to be done during check in. |
| authDuringStayYn | `String` | Authorization is done during stay. |
| authReversalYn | `String` | Authorization reversal  has to be done. |
| authStlmtAtCheckOutYn | `String` | Indicates if this payment method supports credit card interface functionality of sending a combined message for Auth & Settlement. |
| autopayAtCheckinYn | `String` | Determines if this payment type can be used in Auto Advance Bill and Payment process after Check-In if this value equals 'Y'. |
| bonusCheckType | `String` | The type of bonus check. |
| calcPoints | `String` | Indicates if points have to be calculated. [A]lways [P]rompt to check. NULL = No points will be calculated. |
| cardNumberLength | `String` | Comma separated credit card number lengths. |
| cardPrefix | `String` | Card Prefix |
| cashSurchargeYn | `String` | Indicates that the payment method selected is subject to an additional surcharge. The surcharge amount / percentage is based on range of amount. The functionality is introduced for Algeria and is only applicable for Cash. |
| ccTrxFeePct | `Float` | Fee (surcharge) percentage amount for a credit card transaction. |
| ccTrxFeeThreshold | `Float` | Fee (surcharge) threshold that will indicate the minimum credit card transaction amount for which the fee applies. |
| centralPaymentMethod | `String` | Central Payment Method |
| centralPaymentMethodDescription | `String` | Central Payment Method Description |
| centralSequence | `Float` | Central Sequence |
| chipPinYn | `String` | Indicates if the payment type can be used with the chip and pin card functionality. |
| code | `String` | Code |
| creditCardType | `String` | Abbreviates the card_type and is used exclusively for the interface. |
| creditLimit | `Float` | Credit Limit |
| currencyCode | `String` | Currency Code |
| cvv2CheckYn | `String` | Determines if this payment type captures the Credit Card Security Code (CVV2) during payment. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| expirationRule | `String` | Expiration Rule |
| extraPerc | `Float` | Extra Percentage. |
| formatMask | `String` | Format Mask |
| formula | `String` | Formula |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| issueNumber | `Float` | Issue Number |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lastUsedDatetime | `Date` | Last Used Datetime |
| locationId | `String` | Location ID |
| merchantNumber | `String` | The merchant # to use when settling / transmitting credit card information. |
| numberDigits | `Float` | The number of digits to allow for this type of credit card. |
| numberPostYN | `String` | Indicates the code is used for post charging. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentMethod | `String` | Payment Method |
| paymentMethodDescription | `String` | Payment Method Description |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printAuthReceiptYn | `String` | Indicates if an Authorization Receipt needs to be printed. |
| promptAtCheckinYn | `String` | Prompt user to go to cashiering after Check-In if this value equals 'Y'. |
| property | `String` | Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `Date` | Reporting Updatedate |
| reservationYN | `String` | Indicates if the card type can be used as a payment method for a reservation. |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| startDate | `Float` | Start Date |
| tempFlag | `Float` | Temp Flag |
| transactionCode | `String` | Transaction Code |
| trxUsage1 | `String` | Transaction Code for Card Usage 1 for ex. Credit Card |
| trxUsage2 | `String` | Transaction Code for Card Usage 2 for ex. Debit Card |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| validationRule | `String` | Validation Rule |

[⬆ Back to Query](#query)

---

### ConfigurationResortExportBucketCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| arrangementId | `Float` | Arrangement ID |
| bucketType | `String` | User defined Export Bucket type. |
| bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRoutingAmount | `Float` | Central Routing Amount |
| code | `String` | Code |
| compYn | `String` | Comp Y/N |
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
| inactiveDate | `DateTime` | Inactive Date |
| inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| revenueBucketDescription | `String` | Arrangement Description for the Transaction Code. |
| revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| routingPercent | `Float` | Routing Percent |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionCodeArrangeDetailDetailsType

| Field | Type | Description |
| --- | --- | --- |
| addTransactionYN | `String` | Add Trx Y/N |
| arrangementId | `Float` | Arrangement ID |
| centralTransactionCode | `String` | Central Transaction Code |
| centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| childArrangementId | `Float` | Child arrangement id. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| transactionCode | `String` | Transaction Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortExportBucketTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `String` | User defined Export Bucket type. |
| compYn | `String` | Comp Y/N |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| fiscalYn | `String` | Indicates if this export bucket is FISCAL related. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| transactionCodeInMultiBucketsYN | `String` | Indicates that a user can configure the same Transaction Code into Revenue Buckets Codes of the same Revenue Bucket Type. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortRoutingCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| applyPerDayYN | `String` | Apply Per Day YN |
| arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| arrangementId | `Float` | Arrangement ID |
| bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRoutingAmount | `Float` | Central Routing Amount |
| code | `String` | Code |
| compYn | `String` | Comp Y/N |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Arrangement Description for the Transaction Code. |
| eligibleYn | `String` | Specifies the Eligibility to calculate membership points. |
| exportBucketType | `String` | User defined Export Bucket type. |
| friday | `String` | Friday |
| inactiveDate | `DateTime` | Inactive Date |
| inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| monday | `String` | Monday |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| routingPercentage | `Float` | Routing Percentage |
| saturday | `String` | Saturday |
| sunday | `String` | Sunday |
| thursday | `String` | Thursday |
| tuesday | `String` | Tuesday |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| wednesday | `String` | Wednesday |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionDiversionRuleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| basedOn | `String` | Based On |
| calculation | `String` | Indicates the scope or applicability of the threshold as PER STAY or PER DAY. |
| code | `String` | User configured diversion code. |
| complimentary | `Float` | The quantity to be diverted to a designated Posting Master. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| diversionId | `Float` | Unique ID generated for the Diversion Instruction. |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| level | `String` | Possible values: PROPERTY / RESERVATION. When configured as the PROPERTY type the rule is applicable to all the guests staying in the property. Thresholds of type RESERVATION need to be attached to a reservation to take effect. |
| membershipLevel | `String` | Membership Level |
| membershipType | `String` | Membership Type |
| minimumRequired | `Float` | The quantity required by the rule before the posting can be diverted to a designated Posting Master. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| room | `String` | Room number to receive all the diverted transactions configured for this instruction. |
| ruleType | `String` | Rule Type |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| vIP | `String` | VIP |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionDiversionRuleDetailsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| diversionId | `Float` | Unique ID generated for the Diversion Instruction. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| transactionCodes | `String` | Transaction Codes |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionGroupDetailsType

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

### ConfigurationResortGroupGeneratesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adjustmentType | `String` | Adjustment Type |
| amount | `Float` | Amount |
| amountFromScheduleYn | `String` | Whether to take the taxes from Price Schedules. |
| cAmount | `Float` | Central Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| calculationSequence | `Float` | Sequence in which the taxes should be applied. |
| centralDescription | `String` | Central Description |
| centralGeneratedCode | `String` | Central Generated Code |
| currency | `String` | Currency |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| generateRules | `String` | Generate Rules |
| generatedBy | `String` | Generated By |
| generatedCode | `String` | Generated Code |
| generatedPrintedOnFolioYn | `String` | Whether to print on folio. |
| id | `Float` | ID |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| nameTaxType | `String` | Name Tax Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| percentage | `Float` | Percentage |
| percentageBaseCode | `Float` | Indicates if the tax is based on a percentage. It would have a value of 0 if based on BASE amount 1 if on S1 2 if based on S2 3 if based on S3. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| resultIncludedInSumArray | `String` | Result Included In Sum Array |
| roundingMethod | `String` | Rounding method to be used when calculating a generate amount. Allowed values are UP DOWN NONE and NULL. |
| stopDays | `Float` | Days after which the generates will not be posted for long standing guests. |
| subTotal1YN | `String` | Sub-Total 1 YN |
| subTotal2YN | `String` | Sub-Total 2 YN |
| subTotal3YN | `String` | Sub-Total 3 YN |
| tcGroup | `String` | Transaction Code Group |
| tcGroupGenerator | `String` | Group generator. |
| tcSubgroup | `String` | Transaction Code Subgroup |
| tcSubgroupGenerator | `String` | Subgroup generator. |
| tclCodeGenerator | `String` | Identify if the taxes are generated on the Class. |
| tcrType | `String` | Flag to indicate the addon tax. |
| trxCodeGenerator | `String` | Transaction Code Generator |
| udfFunction | `String` | Udf Function |
| udfInverse | `String` | Not used currently. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| useTaxBracketYn | `String` | Flag to indicate if tax brackets are used for this tax. |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionSubgroupDetailsType

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

### ConfigurationResortSubgroupGeneratesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adjustmentType | `String` | Adjustment Type |
| amount | `Float` | Amount |
| amountFromScheduleYn | `String` | Whether to take the taxes from Price Schedules. |
| cAmount | `Float` | Central Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| calculationSequence | `Float` | Sequence in which the taxes should be applied. |
| centralDescription | `String` | Central Description |
| centralGeneratedCode | `String` | Central Generated Code |
| currency | `String` | Currency |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| generateRules | `String` | Generate Rules |
| generatedBy | `String` | Generated By |
| generatedCode | `String` | Generated Code |
| generatedPrintedOnFolioYn | `String` | Whether to print on folio. |
| id | `Float` | ID |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| nameTaxType | `String` | Name Tax Type |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| percentage | `Float` | Percentage |
| percentageBaseCode | `Float` | Indicates if the tax is based on a percentage. It would have a value of 0 if based on BASE amount 1 if on S1 2 if based on S2 3 if based on S3. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| resultIncludedInSumArray | `String` | Result Included In Sum Array |
| roundingMethod | `String` | Rounding method to be used when calculating a generate amount. Allowed values are UP DOWN NONE and NULL. |
| seqBy | `Float` | Sequence By |
| stopDays | `Float` | Days after which the generates will not be posted for long standing guests. |
| subTotal1YN | `String` | Sub-Total 1 YN |
| subTotal2YN | `String` | Sub-Total 2 YN |
| subTotal3YN | `String` | Sub-Total 3 YN |
| tcDsi | `Float` | Transaction Code Dsi |
| tcGroup | `String` | Transaction Code Group |
| tcGroupGenerator | `String` | Group generator. |
| tcOrganizationid | `Float` | Transaction Code Organizationid |
| tcSubgroup | `String` | Transaction Code Subgroup |
| tcSubgroupGenerator | `String` | Subgroup generator. |
| tcTcSubgroup | `String` | Transaction Code Transaction Code Subgroup |
| tclCodeGenerator | `String` | Identify if the taxes are generated on the Class. |
| tcrType | `String` | Flag to indicate the addon tax. |
| transactionCodeResort | `String` | Not Used. |
| trxCodeGenerator | `String` | Transaction Code Generator |
| udfFunction | `String` | Udf Function |
| udfInverse | `String` | Not used currently. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| useTaxBracketYn | `String` | Flag to indicate if tax brackets are used for this tax. |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyAlertDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| propery | `String` | Propery |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGlobalAlertsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| alertCode | `String` | Alert Code |
| alertText | `String` | Alert Text |
| area | `String` | Area |
| brandStayCnt | `Float` | Brand Stay Count |
| comments | `String` | Comments |
| conditions | `String` | Conditions |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| department | `String` | Department |
| description | `String` | Description |
| emailAddress | `String` | Email Address |
| emailYn | `String` | Email Y/N |
| externalAlertId | `String` | Unique ID in External System. |
| hasTagsYn | `String` | Indicates if the current alert can contain tags. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| language | `String` | Language |
| lastStayDate | `Date` | Last Stay Date |
| lastStayLocation | `String` | Last Stay Location |
| locationID | `String` | Internal ID to uniquely identify the Property |
| membershipAlertYn | `String` | Indicate if the current alert belongs to a membership module. |
| membershipCardNo | `String` | Membership Card Number |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pref1 | `String` | Preference 1 |
| pref2 | `String` | Preference 2 |
| pref3 | `String` | Preference 3 |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printerYN | `String` | Use this alert to print notification. |
| printerName | `String` | Name of the printer where alert will be printed. |
| property | `String` | Property |
| propertyStayCnt | `Float` | Property Stay Count |
| propertyStayDate | `Date` | Previous Stay Date at this property for repeat guests. |
| queryId | `Float` | Query ID |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reportName | `String` | Report Name |
| reservationAlertId | `Float` | Resv Alert ID |
| reservationNameId | `Float` | Resv Name ID |
| screenYN | `String` | Screen YN |
| skipGuestOverviewYn | `String` | Indicates if the guest overview screen should be suppressed. |
| smsNumber | `String` | The phone number to where the notification will be send. |
| smsYn | `String` | Use this alert to text a notification. |
| stopCheckInCheckOut | `String` | Indicates if this alert will be used to perform a validation. |
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
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| validationOverridePermission | `String` | The user permission required in order to override a validation alert. |
| valueRating | `String` | Value Rating |
| vipStatus | `String` | VIP Status |
| welcomeOfferCode | `String` | Offer code if this alert is linked to a guest welcome offer. |
| welcomeOfferYn | `String` | Welcome Offer Y/N |

[⬆ Back to Query](#query)

---

### ConfigurationResortBlockCancellationCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| lastUsedDatetime | `Date` | Last Used Datetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| tempFlag | `String` | Temp Flag |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSalesEventDestinationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| cancellationDestination | `String` | Cancellation Destination |
| centralCancellationDestination | `String` | Central Cancellation Destination |
| centralCancellationDestinationDescription | `String` | Central Cancellation Destination Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| lastUsedDatetime | `Date` | Last Used Datetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| scdestinationid | `String` | Scdestinationid |
| sequence | `Float` | Sequence |
| tempFlag | `String` | Temp Flag |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortLostBookingCodesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| lastUsedDatetime | `Date` | Last Used Datetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| tempFlag | `String` | Temp Flag |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortRefusedBookingCodesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| lastUsedDatetime | `Date` | Last Used Datetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| tempFlag | `String` | Temp Flag |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBookingMethodDetailsType

| Field | Type | Description |
| --- | --- | --- |
| bookingmethodid | `String` | Bookingmethodid |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralDescription | `String` | Central Description |
| centralReservationMethod | `String` | Central Reservation Method |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| reservationMethod | `String` | Reservation Method |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyCutoffScheduleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `String` | Unique code to identify a Wash schedule. |
| cutoffRooms2 | `Float` | Number of rooms that should be washed for Occupancy 2. |
| cutoffRooms3 | `Float` | Number of rooms that should be washed for Occupancy 3. |
| cutoffRooms4 | `Float` | Number of rooms that should be washed  for Occupancy 4. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| daysPriorToArrival | `Float` | Cut off days for the stay date. |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rooms | `Float` | Number of rooms that should be washed. |
| sell | `Float` | Wash value for sell limits when the SELL LIMITS parameter is ON. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| washByPercent | `Float` | Cutoff Percentage. |

[⬆ Back to Query](#query)

---

### ConfigurationResortBookingStatusDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allowPickupYN | `String` | Allow Pickup YN |
| bookingstatusid | `String` | Bookingstatusid |
| cateringStatusType | `String` | Catering Status Type |
| cateringdeductinvflag | `String` | Cateringdeductinvflag |
| centralDescription | `String` | Central Description |
| centralEventStatus | `String` | Central Event Status |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deductinventoryflag | `String` | Deductinventoryflag |
| defaultReservationType | `String` | Default reservation type |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| diaryYN | `String` | Show the booking status in the diary |
| displayColor | `String` | Display Color |
| fitStatusYn | `String` | Indicates an FIT statuscode. |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| leadStatusYn | `String` | Indicates if this Booking Status is an Initial Lead status. |
| logCateringYn | `String` | Will store the information whether the details_ok_yn flag of allotment_header will be set to Y. This operation is done at trigger level. |
| oRMSYN | `String` | Indicates that the blocks in this status will be considered by ORMS for forecasting. |
| oldBlockStatus | `String` | Old Block Status |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reasonType | `String` | Type of the reason for the booking status |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| returnInventoryYN | `String` | Return Inventory YN |
| roomStatusType | `String` | Room Status Type |
| sequence | `Float` | Sequence |
| startingYN | `String` | Booking starting status (intial pickup) |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCancelRuleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentHeaderId | `Float` | Allotment Header ID |
| amount | `Float` | Amount |
| applyRuleTo | `String` | For Web Bookings only the deposit amount will be calculated either from room or catering revenue or from both. This column stores either: [ALL] [ROOMS] or [CATERING]. |
| beforeTime | `DateTime` | Before Time |
| beginDate | `Date` | Begin Date |
| cCnclPenltyAmount | `Float` | Central Cncl Penlty Amount |
| cDepAmount | `Float` | Central Dep Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| code | `String` | Code |
| creditRating | `String` | Credit Rating |
| d1 | `String` | D1 |
| d2 | `String` | For future use |
| d3 | `String` | Internal date column. |
| d4 | `String` | Internal date column. |
| d5 | `String` | Internal date column. |
| d6 | `String` | Internal date column. |
| d7 | `String` | Internal date column. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| daysBeforeArrival | `Float` | Days Before Arrival |
| daysofweek | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| deletedflag | `String` | Deleted Flag |
| depositAmount | `Float` | Deposit Amount |
| depositAmountType | `String` | Deposit Amount Type |
| depositDaysAfterBooking | `Float` | Deposit Days After Booking |
| depositDaysPriorToArrival | `Float` | Deposit Days Prior To Arrival |
| depositcancelruleid | `Float` | Depositcancelruleid |
| depositcancelrulepmsref | `Float` | Deposit Cancel Rule PMS Reference |
| depositorCancellationRule | `String` | Depositor Cancellation Rule |
| description | `String` | Description |
| endDate | `Date` | End Date |
| guaranteeClass | `String` | Guarantee class for cancel policy. Specifically added for BWI. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| overrideYn | `String` | override allowed or not for booking. |
| parentRateDcSeq | `Float` | Refers to Master ID for this child record |
| paymentRequired | `String` | Payment Required within Rule Period. (FULL NONE PARTIAL) |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rateCodeDescription | `String` | Rate Code Description |
| rateSetId | `Float` | Rate Set ID |
| repSeasonCode | `String` | Reporting Season Code |
| reservationType | `String` | Reservation Type |
| seasonCode | `String` | Season Code |
| sequence | `Float` | Sequence |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCancelRuleScheduleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentHeaderId | `Float` | Allotment Header ID |
| applyRuleTo | `String` | For Web Bookings only the deposit amount will be calculated either from room or catering revenue or from both. This column stores either: [ALL] [ROOMS] or [CATERING]. |
| beginDate | `Date` | Begin Date |
| blockCode | `String` | Block Code |
| cCnclPenltyAmount | `Float` | Central Cncl Penlty Amount |
| cDepAmount | `Float` | Central Dep Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| canBeforeTime | `DateTime` | Can Before Time |
| canDaysPriorToArrival | `Float` | Can Days Prior To Arrival |
| canPenaltyAmount | `Float` | Can Penalty Amount |
| canPenaltyAmountType | `String` | Can Penalty Amount Type |
| creditRating | `String` | Credit Rating |
| d1 | `String` | D1 |
| d2 | `String` | For future use |
| d3 | `String` | Internal date column. |
| d4 | `String` | Internal date column. |
| d5 | `String` | Internal date column. |
| d6 | `String` | Internal date column. |
| d7 | `String` | Internal date column. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| daysofweek | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| deletedflag | `String` | Deleted Flag |
| depositAmount | `Float` | Deposit Amount |
| depositAmountType | `String` | Deposit Amount Type |
| depositDaysAfterBooking | `Float` | Deposit Days After Booking |
| depositDaysPriorToArrival | `Float` | Deposit Days Prior To Arrival |
| depositcancelruleid | `Float` | Depositcancelruleid |
| depositcancelrulepmsref | `Float` | Deposit Cancel Rule PMS Reference |
| depositorCancellationRule | `String` | Depositor Cancellation Rule |
| endDate | `Date` | End Date |
| guaranteeClass | `String` | Guarantee class for cancel policy. Specifically added for BWI. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| overrideYN | `String` | override allowed or not for booking. |
| parentRateDcSeq | `Float` | Refers to Master ID for this child record |
| paymentRequired | `String` | Payment Required within Rule Period. (FULL NONE PARTIAL) |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rateCodeDescription | `String` | Rate Code Description |
| rateSetId | `Float` | Rate Set ID |
| repSeasonCode | `String` | Reporting Season Code |
| reservationType | `String` | Reservation Type |
| rule | `String` | Rule |
| ruleDescription | `String` | Rule Description |
| seasonCode | `String` | Season Code |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDepositRuleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| afterBooking | `Float` | After Booking |
| allotmentHeaderId | `Float` | Allotment Header ID |
| amount | `Float` | Amount |
| applyRuleTo | `String` | For Web Bookings only the deposit amount will be calculated either from room or catering revenue or from both. This column stores either: [ALL] [ROOMS] or [CATERING]. |
| beforeArrival | `Float` | Before Arrival |
| beginDate | `Date` | Begin Date |
| cCnclPenltyAmount | `Float` | Central Cncl Penlty Amount |
| cDepAmount | `Float` | Central Dep Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| canBeforeTime | `Date` | Can Before Time |
| canDaysPriorToArrival | `Float` | Can Days Prior To Arrival |
| canPenaltyAmount | `Float` | Can Penalty Amount |
| canPenaltyAmountType | `String` | Can Penalty Amount Type |
| creditRating | `String` | Credit Rating |
| d1 | `String` | D1 |
| d2 | `String` | For future use |
| d3 | `String` | Internal date column. |
| d4 | `String` | Internal date column. |
| d5 | `String` | Internal date column. |
| d6 | `String` | Internal date column. |
| d7 | `String` | Internal date column. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| daysofweek | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| deletedflag | `String` | Deleted Flag |
| depositRule | `String` | Deposit Rule |
| depositcancelruleid | `Float` | Depositcancelruleid |
| depositcancelrulepmsref | `Float` | Deposit Cancel Rule PMS Reference |
| depositorCancellationRule | `String` | Depositor Cancellation Rule |
| description | `String` | Description |
| endDate | `Date` | End Date |
| guaranteeClass | `String` | Guarantee class for cancel policy. Specifically added for BWI. |
| inactiveDate | `Date` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| overrideYn | `String` | override allowed or not for booking. |
| parentRateDcSeq | `Float` | Refers to Master ID for this child record |
| paymentRequired | `String` | Payment Required within Rule Period. (FULL NONE PARTIAL) |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rateCodeDescription | `String` | Rate Code Description |
| rateSetId | `Float` | Rate Set ID |
| repSeasonCode | `String` | Reporting Season Code |
| reservationType | `String` | Reservation Type |
| seasonCode | `String` | Season Code |
| sequence | `Float` | Sequence |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDepositRuleScheduleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentHeaderId | `Float` | Allotment Header ID |
| applyRuleTo | `String` | For Web Bookings only the deposit amount will be calculated either from room or catering revenue or from both. This column stores either: [ALL] [ROOMS] or [CATERING]. |
| beginDate | `Date` | Begin Date |
| blockCode | `String` | Block Code |
| cCnclPenltyAmount | `Float` | Central Cncl Penlty Amount |
| cDepAmount | `Float` | Central Dep Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| canBeforeTime | `DateTime` | Can Before Time |
| canDaysPriorToArrival | `Float` | Can Days Prior To Arrival |
| canPenaltyAmount | `Float` | Can Penalty Amount |
| canPenaltyAmountType | `String` | Can Penalty Amount Type |
| creditRating | `String` | Credit Rating |
| d1 | `String` | D1 |
| d2 | `String` | For future use |
| d3 | `String` | Internal date column. |
| d4 | `String` | Internal date column. |
| d5 | `String` | Internal date column. |
| d6 | `String` | Internal date column. |
| d7 | `String` | Internal date column. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| daysofweek | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| deletedflag | `String` | Deleted Flag |
| depositAmount | `Float` | Deposit Amount |
| depositAmountType | `String` | Deposit Amount Type |
| depositDaysAfterBooking | `Float` | Deposit Days After Booking |
| depositDaysPriorToArrival | `Float` | Deposit Days Prior To Arrival |
| depositcancelruleid | `Float` | Depositcancelruleid |
| depositcancelrulepmsref | `Float` | Deposit Cancel Rule PMS Reference |
| depositorCancellationRule | `String` | Depositor Cancellation Rule |
| endDate | `Date` | End Date |
| guaranteeClass | `String` | Guarantee class for cancel policy. Specifically added for BWI. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| overrideYN | `String` | override allowed or not for booking. |
| parentRateDcSeq | `Float` | Refers to Master ID for this child record |
| paymentRequired | `String` | Payment Required within Rule Period. (FULL NONE PARTIAL) |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rateCodeDescription | `String` | Rate Code Description |
| rateSetId | `Float` | Rate Set ID |
| repSeasonCode | `String` | Reporting Season Code |
| reservationType | `String` | Reservation Type |
| rule | `String` | Rule |
| ruleDescription | `String` | Rule Description |
| seasonCode | `String` | Season Code |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGuaranteeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| addressYN | `String` | Is an address required when using this confirm code? Y/N |
| arrivalYN | `String` | Arrival Time needed |
| autoCancelReservationYN | `String` | Indicates whether a reservation of this type will be auto cancelled if no payment or CC is not received. |
| bookingStatus | `String` | Booking Status |
| bookingStatusOrder | `String` | Booking Status Order |
| canDeleteYn | `String` | Can Delete Y/N |
| cashBasisYn | `String` | Is a reservation with this confirm code on a cash basis? Y/N |
| ccPendingDays | `Float` | Cc Pending Days |
| ccVerifyCodeRequiredYn | `String` | Used for GDS channels and indicates the requirement of verification code. |
| centralReservationType | `String` | Central Reservation Type |
| centralReservationTypeDescription | `String` | Central Reservation Type Description |
| closingProbability | `Float` | A probability to have a revenue out of the reservation guaranted by this guaranted code |
| creditCardYN | `String` | Credit card needed |
| croAllowedYn | `String` | Is the CRO allowed to use this confirm code? Y/N |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| depositYN | `String` | Deposit YN |
| gDSShortDescription | `String` | External GDS Description |
| guaranteecodeid | `String` | Guaranteecodeid |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| internalYn | `String` | Internal Y/N |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| longDescription | `String` | Long Description |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| phoneYN | `String` | Is a phone # required when using this confirm code? Y/N |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| reservationType | `String` | Reservation Type |
| reservationTypeDescription | `String` | Reservation Type Description |
| reserveInventoryYn | `String` | Reserve Inventory Y/N |
| restrictedYn | `String` | Restricted Y/N |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| shortDescription | `String` | Short Description |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortReservationTypeScheduleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentHeaderId | `Float` | Allotment Header ID |
| applyRuleTo | `String` | For Web Bookings only the deposit amount will be calculated either from room or catering revenue or from both. This column stores either: [ALL] [ROOMS] or [CATERING]. |
| beginDate | `Date` | Begin Date |
| cCnclPenltyAmount | `Float` | Central Cncl Penlty Amount |
| cDepAmount | `Float` | Central Dep Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| canBeforeTime | `Date` | Can Before Time |
| canDaysPriorToArrival | `Float` | Can Days Prior To Arrival |
| canPenaltyAmount | `Float` | Can Penalty Amount |
| canPenaltyAmountType | `String` | Can Penalty Amount Type |
| creditRating | `String` | Credit Rating |
| d1 | `String` | D1 |
| d2 | `String` | For future use |
| d3 | `String` | Internal date column. |
| d4 | `String` | Internal date column. |
| d5 | `String` | Internal date column. |
| d6 | `String` | Internal date column. |
| d7 | `String` | Internal date column. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| daysofweek | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| deletedflag | `String` | Deleted Flag |
| depositAmount | `Float` | Deposit Amount |
| depositAmountType | `String` | Deposit Amount Type |
| depositDaysAfterBooking | `Float` | Deposit Days After Booking |
| depositDaysPriorToArrival | `Float` | Deposit Days Prior To Arrival |
| depositcancelruleid | `Float` | Depositcancelruleid |
| depositcancelrulepmsref | `Float` | Deposit Cancel Rule PMS Reference |
| depositorCancellationRule | `String` | Depositor Cancellation Rule |
| description | `String` | Description |
| endDate | `Date` | End Date |
| guaranteeClass | `String` | Guarantee class for cancel policy. Specifically added for BWI. |
| inactiveDate | `Date` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| overrideYN | `String` | override allowed or not for booking. |
| parentRateDcSeq | `Float` | Refers to Master ID for this child record |
| paymentRequired | `String` | Payment Required within Rule Period. (FULL NONE PARTIAL) |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| rateCodeDescription | `String` | Rate Code Description |
| rateSetId | `Float` | Rate Set ID |
| repSeasonCode | `String` | Reporting Season Code |
| reservationType | `String` | Reservation Type |
| ruleCode | `String` | Rule Code |
| ruledescription | `String` | Ruledescription |
| seasonCode | `String` | Season Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMarketDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displayColor | `String` | Display Color |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketDisplaySequence | `Float` | Market Display Sequence |
| marketGroupCode | `String` | Market group attached to the market code |
| marketGroupDescription | `String` | Market Group Description |
| marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| marketgroupid | `String` | Marketgroupid |
| marketid | `String` | Marketid |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printGroup | `String` | Print Group for Nationality Report |
| property | `String` | Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repMarketSellSequence | `Float` | Reporting Market Sell Sequence |
| repParentSellSequence | `Float` | Reporting Parent Sell Sequence |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| scOrderby | `Float` | Sc Orderby |
| trxCode | `String` | Transaction Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMarketGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| autoupgradeYn | `String` | Defines whether this Market Group is eligible for auto upgrade of room types in the Room Assignment Optimization. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketGroup | `String` | Market group code |
| marketgroupid | `String` | Marketgroupid |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repMarketGroup | `String` | Reporting Market Group |
| repSellSequence | `Float` | Reporting Sell Sequence |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| scOrderBy | `Float` | Sc Order By |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyMarketingCityDetailsType

| Field | Type | Description |
| --- | --- | --- |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | City Description. |
| direction | `String` | Direction |
| displaySeq | `Float` | Display Sequence |
| distance | `Float` | Distance |
| distanceType | `String` | Distance Type |
| drivingTime | `String` | Driving Time |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| marketingCity | `String` | Marketing City |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| regionCode | `String` | Region Code |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMarketingRegionsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| lastUsedDatetime | `Date` | Last Used Datetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| tempFlag | `String` | Temp Flag |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortChannelDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralOriginCode | `String` | Central Origin Code |
| centralOriginDescription | `String` | Central Origin Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| channelid | `String` | Channelid |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCode | `String` | Origin Code |
| originDescription | `String` | Origin Description |
| originDisplaySequence | `Float` | Origin Display Sequence |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSellMessagesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allotmentHeaderId | `Float` | Allotment Header ID |
| beginDate | `Date` | Begin Date |
| blockCode | `String` | Block Code |
| centralRoomType | `String` | Central Room Type |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| endDate | `Date` | End Date |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| language | `String` | Language |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| roomCategory | `String` | Room Category |
| roomType | `String` | Room Type |
| sellId | `Float` | The primary key for this table. |
| sellMessage | `String` | The actual message to be displayed. |
| sequence | `Float` | Sequence |
| stickyFlag | `String` | Stick the message on top of the screen without scrolling it. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSourceTableDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralSequence | `Float` | Central Sequence |
| centralSourceCode | `String` | Central Source Code |
| centralSourceDescription | `String` | Central Source Description |
| centralSourceGroupCode | `String` | Central Source Group Code |
| centralSourceGroupDescription | `String` | Central Source Group Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| deletedflag | `String` | Deleted Flag |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlagYN | `String` | Inactive YN |
| inactiveYn | `String` | Inactive Y/N |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internetSalesYn | `String` | Indicates if the source code is marked to track internet sales. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lastuseddatetime | `DateTime` | Lastuseddatetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| parentsourceid | `String` | Parentsourceid |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| sourceCode | `String` | Source Code |
| sourceDescription | `String` | Source Description |
| sourceDisplaySequence | `Float` | Source Display Sequence |
| sourceGroupCode | `String` | Source group of the source code |
| sourceGroupDescription | `String` | Source Group Description |
| sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| sourceid | `String` | Sourceid |
| tempYn | `String` | Temp Y/N |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSourceGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| centralSourceGroup | `String` | Central Source Group |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internetSalesYn | `String` | Indicates if the source code is marked to track internet sales. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| parentSourceCode | `String` | Source group of the source code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| scOrderby | `Float` | Sc Orderby |
| sequence | `Float` | Sequence |
| sourceGroup | `String` | Source Group |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortReservationAutoAttachRulesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| advancedYn | `String` | Indicates if this rule uses advanced filter conditions |
| basedOn | `String` | Defines what the rule is based on the type of condition which need to be satisfied in order to qualify for this rule. Valid values are MEMBERSHIP RATE_CODE REFERENCE VIP. |
| code | `String` | Code |
| convertedToAdvancedYn | `String` | Flag to indicate if the condition on this rule was automatically converted to an advanced expression. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keywordType | `String` | Keyword Type |
| level | `String` | Level |
| minAdults | `Float` | This column will be filled when Based_on value is MIN_ADULTS. Otherwise it will be empty. |
| minChildren | `Float` | This column will be filled when Based_on value is MIN_CHILDREN. Otherwise it will be empty. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| preference | `String` | Preference |
| preferenceType | `String` | Preference Type |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| queryId | `Float` | Query ID |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| roomCategory | `String` | Room Category |
| ruleType | `String` | Rule Type |
| type | `String` | Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| vipStatus | `String` | VIP Status |

[⬆ Back to Query](#query)

---

### ConfigurationResortReservationAutoAttachDetailsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| associatedCodes | `String` | Associated Codes. |
| attachId | `Float` | Attach ID |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| discountReasonCode | `String` | Discount Reason Code |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| itemId | `Float` | Item ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| preference | `String` | Preference |
| preferenceType | `String` | Preference Type |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| product | `String` | Product |
| promoCode | `String` | Promo Code |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ruleCode | `String` | Rule Code |
| traceDeptId | `String` | Internal Trace ID. |
| traceText | `String` | Trace Text |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCancellationCodesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| lastUsedDatetime | `DateTime` | Last Used Datetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| tempFlag | `String` | Temp Flag |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortEntryPointDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| lastUsedDatetime | `Date` | Last Used Datetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| tempFlag | `String` | Temp Flag |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDiscountReasonDetailsType

| Field | Type | Description |
| --- | --- | --- |
| advanceYN | `String` | Indicates if this rule uses advanced filter conditions |
| attributeCode | `String` | Attribute Code |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortEcouponDetailsType

| Field | Type | Description |
| --- | --- | --- |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| defaultQuantity | `Float` | Default quantity of the eCoupon. |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| postingRoom | `String` | Charges coming with this eCoupon will be routed to this Pseudo room. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateCode | `String` | Rate Code |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| welcomeOfferYn | `String` | Welcome Offer Y/N |
| eCouponCode | `String` | eCoupon Code |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyLocatorDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `Float` | Locator code. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveYN | `String` | Inactive YN |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyMessageDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `String` | Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| message | `String` | Message |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| sequence | `Float` | Sequence |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGuestStatusDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| guestStatus | `String` | Used for Police/Tourist Export |
| gueststatusid | `String` | Gueststatusid |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| internalEntityname | `String` | Entityname |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| statustype | `Float` | Statustype |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGuestTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralDescription | `String` | Central Description |
| centralGuestType | `String` | Central Guest Type |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| guestType | `String` | Guest Type |
| guesttypeid | `String` | Guesttypeid |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortImmigrationStatusDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPreRegRulesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| allowRestrict | `String` | Indicates whether this rule defines the values that will restrict or allow the internet check-in. Will be used in future versions. |
| beginDate | `Date` | Begin Date |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| endDate | `Date` | End Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ruleDetails | `String` | Rule Details |
| ruleId | `Float` | Rule ID |
| ruleType | `String` | Rule Type |
| ruleTypeDesc | `String` | Rule Type Desc |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortItemClassDetailsType

| Field | Type | Description |
| --- | --- | --- |
| bookableViaWebsiteYN | `String` | Bookable via Website YN |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| code | `String` | Item Class Code. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| discountableYn | `String` | Discountable Y/N |
| eventTypes | `String` | Event Types |
| iconName | `String` | Icon Name |
| inactiveDate | `DateTime` | Inactive Date |
| itemclassId | `Float` | Itemclass ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| reportingItemclassId | `String` | Rep Itemclass ID |
| reservationYN | `String` | Indicates if this menu item depends on the reservation. |
| responsibleDepartment | `String` | Responsible Department |
| sequence | `Float` | Sequence |
| usedInApp | `String` | Used In App |

[⬆ Back to Query](#query)

---

### ConfigurationResortItemInventoryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activityExtSystem | `String` | Exterbal system for which the activity will be created. |
| activityLinkYn | `String` | Indicates whether an activity will be created for the item or not. |
| activityLocationCode | `String` | Location code of the activity that will be created when linked with an activity. |
| activityStatusCode | `String` | Initial activity status code when linked to an activity. |
| activityType | `String` | Activity Type |
| allowedOutsideStayYn | `String` | Can this item be held outside of the reservation stay dates ? |
| availableFrom | `DateTime` | Item available from this time. |
| availableTo | `DateTime` | Item available until this time. |
| braceletRuleCode | `String` | Links to RESORT_BRACELET_RULES.RULE_CODE. |
| cCost | `Float` | Central Cost |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| cost | `Float` | Cost |
| criticalYn | `String` | Critical Item watch stock |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyInventoryYn | `String` | Indicates if daily inventory is setup for this item. |
| defaultDuration | `Float` | Defines the default duration when booking the item (in Days). |
| defaultQty | `Float` | Defines the default quantity when booking the item. |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| discountableYN | `String` | Discountable YN |
| displayColor | `String` | Display Color |
| externalYN | `String` | Item is external |
| inactiveDate | `DateTime` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| itemClass | `String` | Item Class |
| itemCode | `String` | Item Code |
| itemId | `Float` | Item ID |
| itemPoolId | `Float` | References the ITEM_POOL_ID from GEM$ITEM_POOL. |
| itemclassId | `Float` | Itemclass ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| mandatoryYn | `String` | Mandatory Y/N |
| objectType | `String` | Type of object  1.CONSTRAINT 2.TABLE. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| promptFixedChargesYn | `String` | Should the Fixed Charges screen be automatically displayed when this item gets attached to a reservation ? |
| property | `String` | Property |
| quantityInStock | `Float` | Item Quantity in stock |
| quickInsert | `String` | Quick Insert |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| reportingItemId | `String` | Rep Item ID |
| revType | `String` | Rev Type |
| revenueType | `String` | Revenue Type |
| sellSeparate | `String` | Indicates whether it could be sold separately |
| sequence | `Float` | Sequence |
| setdownTime | `Float` | Setdown Time |
| setupTime | `Float` | Setup Time |
| showbeoYn | `String` | Showbeo Y/N |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| webBookingYn | `String` | Web Booking Y/N |
| welcomeOfferYn | `String` | Welcome Offer Y/N |

[⬆ Back to Query](#query)

---

### ConfigurationResortItemPoolDetailsType

| Field | Type | Description |
| --- | --- | --- |
| code | `String` | User Definable Item Pool Code. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| insertTs | `DateTime` | Insert Ts |
| insertUser | `Float` | Insert User |
| itemClass | `String` | Item Class Code. |
| itemPoolId | `Float` | References the ITEM_POOL_ID from GEM$ITEM_POOL. |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| sequence | `Float` | Sequence |
| updateTs | `DateTime` | Update Ts |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBirthCountryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyCountryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| addressdoctorMode | `String` | Defines the mode used to invoke Addressdoctor service [INTERACTIVE or FASTCOMPLETION] |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| countryCode | `String` | Country Code |
| countryMainGroup | `String` | Country Main Group |
| countryName | `String` | Country Name |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displayCountryFlagYN | `String` | Indicates if the Country Flag should be displayed on the front end. |
| guestAddressFormat | `String` | Guest Address Format Codes. For Confirmation Letters. |
| iSOCode | `String` | ISO standard code for the country |
| iSOName | `String` | ISO standard name for the country |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| name | `String` | Name |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| propertyAddressFormat | `String` | Property Address Format Codes. For Confirmation Letters. |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| region | `String` | Region |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| reportSequence | `Float` | Report Sequence |
| sequence | `Float` | Display sequence for LOVs |
| statisticsCode | `String` | Internal |
| status | `String` | Status |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCountryGroupDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| comments | `String` | Comments |
| countryGroup | `String` | Country Group |
| countryGroupCode | `String` | Country Group Code |
| countrygroupid | `String` | Countrygroupid |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDistanceTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDistrictDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortFiscalGuestTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortFiscalRegionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortProfileIDCountryDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortNationalityDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralDescription | `String` | Central Description |
| centralNationalityCode | `String` | Central Nationality Code |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| nationalityid | `String` | Nationalityid |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortQualifyingRatesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aSBRateCycle | `String` | Not null value in this column indicates that this is ASB Rate. This column also specifies the cycle of ASB rate. MC=Fixed Calendar Month Cycle WC=Fixed Calendar Week Cycle MF= Floating Monthly Cycle WF=Floating Weekly Cycle. |
| addition | `String` | Amount to be added to the base rate when shown on rate query |
| advBaseRateCode | `String` | With Advanced Base Rate Parameter ON this field stores the rate code on which this rate schedule is dynamically based on. |
| advBaseRounding | `String` | Indicates how rounding of advanced dynamic rate calculation is performed.[U]p  [D]own [N]one [C] -Up - keep decimal [F] -Down - keep decimal. |
| advanceBaseCompareYN | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BAR rate code. |
| advanceBooking | `Float` | Min number of days to book rate in advance. |
| advanceDailyBaseYN | `String` | Indicates if this rate code is an Advanced Daily Base Rate. |
| advanceDailyRateYN | `String` | Indicates if this rate code is an Advanced Daily Rate. |
| alternateRateCode | `String` | Alternative rate code if current rate is not available |
| availabilityUpdateYn | `String` | Flag to indicate whether to send Rate code to AVH or not. |
| backToBackYn | `String` | Back To Back Y/N |
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
| beginBookingDate | `Date` | Begin Booking Date |
| breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| breakfastPrice | `Float` | Breakfast Price |
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
| changeState | `String` | Indicates the state of chaange of the rate code with values null=enabled D=disabled P=changes pending of approval |
| closedToArrival | `String` | Days the rate restriction is not available for arrival |
| commissionCode | `String` | Commission Code |
| commissionPct | `Float` | This field is used to populate rate code commission percentage for informational purposes for GDS and ORS reservation agents |
| commissionYn | `String` | Are commissions allowed for this rate code? Y/N |
| commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| commissionableYn | `String` | Commissionable Y/N |
| complimentaryYn | `String` | Complimentary Y/N |
| currCodeDecimalPos | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating the decimal position specific to the received the currency code. |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dailyRatesYn | `String` | Daily Rates Y/N |
| dayuseYn | `String` | Day use reservation Y/N. |
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
| description | `String` | Description |
| discountRateAmount | `Float` | Discount rate amount value. |
| discountRatePercentageYn | `String` | Indicates if discount rate amount is a percentage value. |
| discountYn | `String` | Discount Flag. |
| displayRegionalYn | `String` | Flag indicates rate needs to display in area availability or not. |
| displaySet | `String` | Display Set |
| distributeYn | `String` | Indicates if the profile should be distributed to the external database. |
| doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| endBookingDate | `Date` | End Booking Date |
| exchangePostingType | `String` | Exchange Posting Type |
| externalLocked | `String` | External Locked |
| extraPersonChargeBegins | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating at person level the extra charge begins. |
| fitDiscountLevel | `Float` | Fit Discount Level. |
| fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| flatOrPercentage | `String` | Flat Or Percentage |
| folioText | `String` | Text displayed on the Folio |
| gDSAllowedYn | `String` | Is this rate code available for GDS |
| groupCode | `String` | Group Code |
| highlightRateAmountYn | `String` | To highlight on the rate query |
| houseUseYn | `String` | House Use Y/N |
| inactiveDate | `Date` | Inactive Date |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| label | `String` | Label |
| longInfo | `String` | Long Info |
| losUnit | `Float` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| loyaltyProgramYn | `String` | Flag to indicate if this is a loyalty program |
| mandateResvProfiles | `String` | Indicates mandatory reservation profiles. This is used to force entry of profiles on the reservation header if this rate is picked. |
| marketCode | `String` | Market Code |
| marshaRateProgram | `String` | Contains the rate program information from the MARSHA interface. |
| maxAdvanceBooking | `Float` | Max number of days to book rate in advance. |
| maxLos | `Float` | Max Los |
| maxOccupancy | `Float` | Max Occupancy |
| mfnUploadYn | `String` | Flag used to determine if the rate code is to be sent to MyFidelio.net if the rate is being received from a V6 V7 V8 or OPMS on a lower version on which flag used to determine if the rate code is to be sent to MyFidelio.net does not exist on the rate header. |
| minOccupancy | `Float` | Minimum Occupancy |
| mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| multiplication | `String` | Amount to be multiplied to the base rate when shown on rate query |
| negotiated | `String` | Negotiated rate Y/N |
| occupancyBasedYn | `String` | Indicates if the rate code is occupancy based. |
| occupancyLevel | `Float` | Indicates the occupancy level for hurdle evaluation. |
| operatorType | `String` | The operator type to use during the calculation of base rates. (ADD_TO SUBTRACT) |
| orderBy | `Float` | Order By |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| orsSellSequence | `Float` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| overridePackageYn | `String` | Indicates if we need to override package for hurdle evaluation. |
| ownerRateYn | `String` | Indicates Owners Rate Code. This is used to perform rolling noshow. |
| packageTransactionTaxInclYN | `String` | Wrapper transaction code tax inclusive Y/N |
| packageTransactionWkTaxInclYN | `String` | Wrapper transaction code tax inclusive for weekend days Y/N |
| packageTrxCode | `String` | Wrapper transaction code |
| packageTrxCodeWk | `String` | Wrapper transaction code for weekend days |
| packageYn | `String` | Package Y/N |
| pendingApprovalYn | `String` | Indicates whether the rate code is pending for approval or not |
| postingRhythm | `String` | Posting Rhythm |
| postingRhythmNights | `Float` | Number of nights for posting rhythm. |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| printRateYn | `String` | Print Rate Y/N |
| privilegedRestrictionYn | `String` | Indicates if restriction for rate is privileged or not. |
| privilegedYn | `String` | Indicates if rate is privileged or not. |
| profitTrxCode | `String` | Transaction code for profit |
| property | `String` | Property |
| qualifying | `String` | Qualifying |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rankAdjustmentFactor | `Float` | Any number between -10 and +10. This adjustment factor will be applied to the daily ranking value of table RESORT_DAY_TYPE_DATES for the stay date to determine the Rate code rank value. |
| rankValue | `Float` | Rank Value |
| rateBucket | `String` | Yield rate bucket |
| rateCalendarYn | `String` | Indicates if rate Calendar factors such as adder/multiplier should be used for price calculation. |
| rateCategories | `String` | Rate Categories |
| rateClass | `String` | Rate Class |
| rateCodeLocked | `String` | Not used |
| rateCodes | `String` | Rate Codes |
| rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| rateFloorOverrideYn | `String` | This flag indicates if the Rate Floor Rate is overridden for a particular Rate Code. |
| rateIncludesTaxYn | `String` | Does this rate include tax? Y/N |
| rateLevel | `Float` | Rate Level this rate code belongs to. |
| rateinfoUrl | `String` | Rateinfo Url |
| ratesToGDSYn | `String` | Needs to send this rate to GDS or not. |
| redemptionRateYn | `String` | Redemption Rate Y/N |
| repeatPostingRhythmYn | `String` | Indicates if the posting rhythm on the rate code is repeated until the end of the stay otherwise the posting rhythm is applied only once. |
| rodBaseAmount | `Float` | Rod Base Amount |
| rodBaseFltPct | `String` | Rod Base Flt Pct |
| rodBaseRounding | `String` | Rod Base Rounding |
| rodBasedYn | `String` | Is the group code rate of day based |
| rodYn | `String` | Rod Y/N |
| roomAssignmentValue | `Float` | Room Assignment Value |
| sdowBeginBookingDate | `Date` | Holds a copy of the column begin_booking_date while the rate code is disabled or with changes pending of approval |
| sdowEndBookingDate | `Date` | Holds a copy of the column end_booking_date while the rate code is disabled or with changes pending of approval |
| sellSequence | `Float` | Sell Sequence |
| serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| servicePerc | `Float` | Service Percentage included. |
| shortInfo | `String` | Information to be used in the rate query |
| showRateAmountYn | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| sourceCode | `String` | Source Code |
| taxIncludedPerc | `Float` | Percentage of included Tax. |
| taxIncludedYn | `String` | Tax is included in this rate. |
| tieredYn | `String` | Indicates if the rate is a tiered rate. |
| transactionTaxInclYN | `String` | Transaction code is inclusive of tax Y/N |
| transactionWkTaxInclYN | `String` | Transaction code is inclusive of tax for weekend days Y/N |
| trxCode | `String` | Transaction Code |
| trxCodeWk | `String` | The transaction code associated with this rate for weekend days |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upsellYn | `String` | Indicates if the rate code can be upsold |
| voucherBenefitRateYn | `String` | Flag to indicate if this is a voucher benefit rate code. |
| weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| wkDeptCode | `String` | Wk Dept Code |
| yieldAs | `String` | Yield As |
| yieldableYn | `String` | Yieldable Y/N |
| ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipStatusDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPriorityDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| lastUsedDatetime | `Date` | Last Used Datetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| priorityId | `String` | Priority ID |
| priorityType | `String` | Priority Type.  Default Value is PMSGRID |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| tempFlag | `Float` | Temp Flag |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortEntityAccountTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAddressTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAlternateLanguageTitleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| envelopeGreeting | `String` | Envelope Greeting |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| language | `String` | Language |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| salutation | `String` | Salutation |
| sequence | `Float` | Sequence |
| titleNumber | `Float` | Title Number |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortRoomsPotentialDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| lastUsedDatetime | `Date` | Last Used Datetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomsPotentialType | `String` | Rooms Potential Type |
| sequence | `Float` | Sequence |
| tempFlag | `String` | Temp Flag |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBusinessSegmentDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCompanyTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCompetitionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| attributeCode | `String` | Attribute Code |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCompetition | `String` | Central Competition |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| competition | `String` | Competition |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| lastUsedDatetime | `Date` | Last Used Datetime |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| tempFlag | `Float` | Temp Flag |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGenderDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortProfileInactiveReasonDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortIndustryCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortInfluenceCodeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortKeywordTypeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMailingActionDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| lastUsedDatetime | `Date` | Last Used Datetime |
| locationID | `String` | Internal ID to uniquely identify the Property |
| mailingActionType | `String` | Mailing Action Type |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `Date` | Reporting Updatedate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| sequence | `Float` | Sequence |
| tempFlag | `String` | Temp Flag |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPreferenceDetailsType

| Field | Type | Description |
| --- | --- | --- |
| amenityYn | `String` | Indicates if a special request is an Amenity. Used in SPG Transformation functionality. |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cRoomAssignmentValue | `Float` | Central Room Assignment Value |
| cRSPreferenceYn | `String` | Whether this Preference is used in CRS Module or not. |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `Float` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| corporateYn | `String` | Indicates if the preference is configured as Global in ORS. |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| description1 | `String` | Description of the first column in the query result. |
| housekeepingYn | `String` | Indicated if this floor preference is used for task assignments broken out by floor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationId | `String` | Location ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| owsAllowedYN | `String` | Indicates if the preference is exposed in OWS Lookup queries. |
| preferenceAttribute | `String` | Preference Attribute. |
| preferenceCode | `String` | Preference Code |
| preferenceDescription | `String` | Preference Description |
| preferenceGroup | `String` | Preference Group |
| preferenceId | `Float` | Internal Id of the preference |
| preferenceSubType | `String` | Preference Sub Type. |
| preference1 | `String` | Preference1 |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| reportingPreferenceSequenceId | `String` | Rep Preference Seq ID |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomAssignmentValue | `Float` | Room Assignment Value |
| sendDeleteRequestYn | `String` | Indicates delete preference request should be to central system instead of deleting the preference from profile. |
| sequence | `Float` | Sequence |
| source | `String` | Source |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortProfileRestrictionReasonDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repAttributeCode | `String` | Reporting Attribute Code |
| repDescription | `String` | Reporting Description |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repOrderBy | `Float` | Reporting Order By |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSalesEventScopeDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSalesEventScopeCityDetailsType

| Field | Type | Description |
| --- | --- | --- |
| businessTitle | `String` | Business Title |
| canDeleteYn | `String` | Can Delete Y/N |
| centralCode | `String` | Central Code |
| centralDescription | `String` | Central Description |
| centralSequence | `Float` | Central Sequence |
| chainCode | `String` | Chain Code |
| code | `String` | Code |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| description | `String` | Description |
| displayColor | `String` | Display Color |
| entityName | `String` | Entity Name |
| externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| languageCode | `String` | Language Code |
| locationID | `String` | Internal ID to uniquely identify the Property |
| masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| ranking | `Float` | Ranking |
| repItem | `String` | Reporting Item |
| repItemName | `String` | Reporting Item Name |
| repItemOrderby | `Float` | Reporting Item Orderby |
| repUpdateDate | `DateTime` | Reporting Updatedate |
| sequence | `Float` | Sequence |
| titleSuffix | `Float` | Title Suffix |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipClaimAdjustmentLimitDetailsType

| Field | Type | Description |
| --- | --- | --- |
| adjustmentLimitCode | `String` | Adjustment Limit Code |
| awardLowerLimit | `Float` | Lower limit for award. |
| awardUpperLimit | `Float` | Higher limit for award. |
| billingGroup | `String` | Billing Group |
| chainCode | `String` | Chain Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Deprecated. Child table GDS_ACCESS_CODE_RESORTS will instead hold all properties to which to auto publish. |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| tierNightsLowerLimit | `Float` | Lower limit for tier points for nights. |
| tierNightsUpperLimit | `Float` | Higher limit for tier points for nights. |
| tierRevenueLowerLimit | `Float` | Lower limit for tier points for revenue. |
| tierRevenueUpperLimit | `Float` | Higher limit for tier points for revenue. |
| tierStaysLowerLimit | `Float` | Lower limit for tier points for stay. |
| tierStaysUpperLimit | `Float` | Higher limit for tier points for stay. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

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

### ConfigurationResortQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| resortDetailsResort | `StringInput` | The property that the record belongs to<br>`@conditionalInputPair(pair: 1)` |
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
| memclaimoriginDetailsAttributeCode | `StringInput` | Claim Origin Code |
| memclaimoriginDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memclaimoriginDetailsEntityName | `StringInput` | Entity Name |
| memclaimoriginDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memclaimoriginDetailsLanguageCode | `StringInput` | Language Code |
| memclaimoriginDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memclaimoriginDetailsTitleSuffix | `FloatInput` | Title Suffix |
| mempointsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| mempointsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| mempointsDetailsMembershipPointsSeqno | `FloatInput` | Membership Points Seqno |
| mempointsDetailsMembershipType | `StringInput` | Membership Type |
| mempointsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| mempointsDetailsResort | `StringInput` | Property |
| memawardratesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memawardratesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memawardratesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| memawardproductsDetailsAwardType | `StringInput` | Award Type |
| memawardproductsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memawardproductsDetailsMembershipType | `StringInput` | Membership Type |
| memawardproductsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memawardupgradesDetailsAwardType | `StringInput` | Award Type |
| memawardupgradesDetailsChainCode | `StringInput` | Chain Code |
| memawardupgradesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memawardupgradesDetailsBeginDate | `DateInput` | From Date |
| memawardupgradesDetailsFromRoom | `StringInput` | Room Number of the reservation from which charges were routed when routing charges between reservations. |
| memawardupgradesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memawardupgradesDetailsMembershipAwardId | `FloatInput` | Internal PK for the table. |
| memawardupgradesDetailsMembershipType | `StringInput` | Membership Type |
| memawardupgradesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memawardupgradesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| memawardupgradesDetailsEndDate | `DateInput` | To Date |
| memawardfintrxDetailsAwardType | `StringInput` | Award Type |
| memawardfintrxDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memawardfintrxDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memawardfintrxDetailsMembershipType | `StringInput` | Membership Type |
| memawardfintrxDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| memawardfintrxDetailsResort | `StringInput` | Code to uniquely identify the Property |
| memresortgroupcodeDetailsResort | `StringInput` | Attached Property Code |
| memresortgroupcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memresortgroupcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memresortgroupcodeDetailsMemResortGroup | `StringInput` | Mem Property Group |
| memresortgroupcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| airportDetailsAirportCode | `StringInput` | Airport code. |
| airportDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| airportDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| airportDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| airportDetailsResort | `StringInput` | Property |
| featureDetailsFeature | `StringInput` | Code |
| featureDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| featureDetailsFeatureid | `StringInput` | Featureid |
| featureDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| featureDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| featureDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| featureDetailsResort | `StringInput` | Property |
| featureDetailsBeginDate | `DateInput` | Start Date |
| attractioncategoryDetailsAttributeCode | `StringInput` | Code |
| attractioncategoryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| attractioncategoryDetailsEntityName | `StringInput` | Entity Name |
| attractioncategoryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| attractioncategoryDetailsLanguageCode | `StringInput` | Language Code |
| attractioncategoryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| attractioncategoryDetailsTitleSuffix | `FloatInput` | Title Suffix |
| attractionDetailsAttractionCode | `StringInput` | The unique identifier for this attraction. The primary key to this table. |
| attractionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| attractionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| attractionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| attractionDetailsResort | `StringInput` | Property |
| chainDetailsChainCode | `StringInput` | Chain |
| chainDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| chainDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| chainDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| closingscriptDetailsChainCode | `StringInput` | Chain Code |
| closingscriptDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| closingscriptDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| closingscriptDetailsLanguageCode | `StringInput` | Language |
| closingscriptDetailsMembershipType | `StringInput` | Membership Type |
| closingscriptDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| closingscriptDetailsResort | `StringInput` | Property |
| closingscriptDetailsResortType | `StringInput` | Property Type |
| closingscriptDetailsScriptId | `FloatInput` | Script ID |
| communicationmethodDetailsAttributeCode | `StringInput` | Code |
| communicationmethodDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| communicationmethodDetailsEntityName | `StringInput` | Entity Name |
| communicationmethodDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| communicationmethodDetailsLanguageCode | `StringInput` | Language Code |
| communicationmethodDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| communicationmethodDetailsTitleSuffix | `FloatInput` | Title Suffix |
| deliverystatusDetailsAttributeCode | `StringInput` | Code |
| deliverystatusDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deliverystatusDetailsEntityName | `StringInput` | Entity Name |
| deliverystatusDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| deliverystatusDetailsLanguageCode | `StringInput` | Language Code |
| deliverystatusDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| deliverystatusDetailsTitleSuffix | `FloatInput` | Title Suffix |
| departmentDetailsChainCode | `StringInput` | Chain Code |
| departmentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| departmentDetailsDeptId | `StringInput` | Department Code |
| departmentDetailsDeptName | `StringInput` | Description of the department |
| departmentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| departmentDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| departmentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| departmentDetailsResort | `StringInput` | Property |
| elecregcardscriptDetailsChainCode | `StringInput` | Chain Code |
| elecregcardscriptDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| elecregcardscriptDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| elecregcardscriptDetailsLanguageCode | `StringInput` | Language |
| elecregcardscriptDetailsMembershipType | `StringInput` | Membership Type |
| elecregcardscriptDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| elecregcardscriptDetailsResort | `StringInput` | Property |
| elecregcardscriptDetailsResortType | `StringInput` | Property Type |
| elecregcardscriptDetailsScriptId | `FloatInput` | Script ID |
| hubresortDetailsResort | `StringInput` | Associated Property |
| hubresortDetailsCroCode | `StringInput` | Cro Code |
| hubresortDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| hubresortDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| hubresortDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| jobtitleDetailsJobCode | `StringInput` | Code |
| jobtitleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| jobtitleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| jobtitleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| jobtitleDetailsResort | `StringInput` | Property |
| udfcategoryDetailsAttributeCode | `StringInput` | Code |
| udfcategoryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| udfcategoryDetailsEntityName | `StringInput` | Entity Name |
| udfcategoryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| udfcategoryDetailsLanguageCode | `StringInput` | Language Code |
| udfcategoryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| udfcategoryDetailsTitleSuffix | `FloatInput` | Title Suffix |
| udftypeDetailsUdfCategory | `StringInput` | Category |
| udftypeDetailsUdfType | `StringInput` | UDF type - CND. |
| udftypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| udftypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| udftypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| udftypeDetailsTableName | `StringInput` | Table Name |
| brandcodeDetailsAttributeCode | `StringInput` | Code |
| brandcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| brandcodeDetailsEntityName | `StringInput` | Entity Name |
| brandcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| brandcodeDetailsLanguageCode | `StringInput` | Language Code |
| brandcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| brandcodeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| businessunitDetailsAttributeCode | `StringInput` | Code |
| businessunitDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| businessunitDetailsEntityName | `StringInput` | Entity Name |
| businessunitDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| businessunitDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| businessunitDetailsTitleSuffix | `FloatInput` | Title Suffix |
| departmentcodeDetailsAttributeCode | `StringInput` | Code |
| departmentcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| departmentcodeDetailsEntityName | `StringInput` | Entity Name |
| departmentcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| departmentcodeDetailsLanguageCode | `StringInput` | Language Code |
| departmentcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| departmentcodeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| divisionDetailsAttributeCode | `StringInput` | Code |
| divisionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| divisionDetailsEntityName | `StringInput` | Entity Name |
| divisionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| divisionDetailsLanguageCode | `StringInput` | Language Code |
| divisionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| divisionDetailsTitleSuffix | `FloatInput` | Title Suffix |
| hotelcategoryDetailsAttributeCode | `StringInput` | Code |
| hotelcategoryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| hotelcategoryDetailsEntityName | `StringInput` | Entity Name |
| hotelcategoryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| hotelcategoryDetailsLanguageCode | `StringInput` | Language Code |
| hotelcategoryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| hotelcategoryDetailsTitleSuffix | `FloatInput` | Title Suffix |
| operatingunitDetailsAttributeCode | `StringInput` | Code |
| operatingunitDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| operatingunitDetailsEntityName | `StringInput` | Entity Name |
| operatingunitDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| operatingunitDetailsLanguageCode | `StringInput` | Language Code |
| operatingunitDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| operatingunitDetailsTitleSuffix | `FloatInput` | Title Suffix |
| applicationparametervalueDetailsApnJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| applicationparametervalueDetailsChainCode | `StringInput` | Chain Code |
| applicationparametervalueDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| applicationparametervalueDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| applicationparametervalueDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| applicationparametervalueDetailsParameterDisplay | `StringInput` | Parameter Display Name |
| applicationparametervalueDetailsParameterGroup | `StringInput` | Parameter Group |
| applicationparametervalueDetailsParameterName | `StringInput` | Parameter Name |
| applicationparametervalueDetailsResort | `StringInput` | Property |
| trackitactionDetailsCode | `StringInput` | Code |
| trackitactionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| trackitactionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| trackitactionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| trackitactionDetailsResort | `StringInput` | Property |
| trackitactionDetailsTiSubgroup | `StringInput` | Track it SubGroup. Example: Location Type or Action. |
| trackitactionDetailsTiGroup | `StringInput` | Trackit Group. |
| trackitlocationDetailsCode | `StringInput` | Code |
| trackitlocationDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| trackitlocationDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| trackitlocationDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| trackitlocationDetailsResort | `StringInput` | Property |
| trackitlocationDetailsTiSubgroup | `StringInput` | Track it SubGroup. Example: Location Type or Action. |
| trackitlocationDetailsTiGroup | `StringInput` | Trackit Group. |
| trackittypeDetailsCode | `StringInput` | Code |
| trackittypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| trackittypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| trackittypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| trackittypeDetailsResort | `StringInput` | Property |
| trackittypeDetailsTiSubgroup | `StringInput` | Track it SubGroup. Example: Location Type or Action. |
| trackittypeDetailsTiGroup | `StringInput` | Trackit Group. |
| accounttypeDetailsAccountType | `StringInput` | Account Type |
| accounttypeDetailsCXchangeDate | `DateInput` | Central Exchange Date |
| accounttypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| accounttypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| accounttypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| accounttypeDetailsResort | `StringInput` | Property |
| arremindercycleDetailsAccountTypeId | `FloatInput` | Account Type ID |
| arremindercycleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| arremindercycleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| arremindercycleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| arremindercycleDetailsResort | `StringInput` | Property |
| arremindercycleDetailsReminderCode | `FloatInput` | Internal number. |
| acctflagreasonDetailsAcctflagreasonid | `StringInput` | Acctflagreasonid |
| acctflagreasonDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| acctflagreasonDetailsReasonCode | `StringInput` | Flagged Reason Code |
| acctflagreasonDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| acctflagreasonDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| acctflagreasonDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| acctflagreasonDetailsResort | `StringInput` | Property |
| trxreasoncodeDetailsTranReasonCode | `StringInput` | Reason Code. |
| trxreasoncodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| trxreasoncodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| trxreasoncodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| trxreasoncodeDetailsResort | `StringInput` | Property |
| ccauthrulesDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| ccauthrulesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| ccauthrulesDetailsGuaranteeCode | `StringInput` | Guarantee Code |
| ccauthrulesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| ccauthrulesDetailsMainWindowYn | `StringInput` | Indicates if this auth rule is for the main window (i.e. window 1). Default is Y i.e. Only if the flag is explicitly set to N does the rule apply to windows other than 1. |
| ccauthrulesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| ccauthrulesDetailsResort | `StringInput` | Property |
| ccauthrulesDetailsRateCategory | `StringInput` | Rate Category |
| ccauthrulesDetailsRateCode | `StringInput` | Rate Code |
| ccauthrulesDetailsRoomClass | `StringInput` | Room Class |
| ccauthrulesDetailsRoomCategory | `StringInput` | Room Type |
| ccauthrulesDetailsSourceCode | `StringInput` | Source Code |
| autofoliosettlementtypeDetailsAttributeCode | `StringInput` | Code |
| autofoliosettlementtypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| autofoliosettlementtypeDetailsEntityName | `StringInput` | Entity Name |
| autofoliosettlementtypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| autofoliosettlementtypeDetailsLanguageCode | `StringInput` | Language Code |
| autofoliosettlementtypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| autofoliosettlementtypeDetailsTitleSuffix | `FloatInput` | Title Suffix |
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
| customnumberDetailsCustomCode | `StringInput` | Internal code to identify the custom number. |
| customnumberDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| customnumberDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| customnumberDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| customnumberDetailsResort | `StringInput` | Property |
| currencyexchangetaxDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| currencyexchangetaxDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| currencyexchangetaxDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| currencyexchangetaxDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| currencyexchangetaxDetailsResort | `StringInput` | Property |
| currencyexchangetaxDetailsServiceTaxType | `StringInput` | Stores the Service tax type. Possible values can be: R1 R2 R3 and so on. |
| expensearrangementcodeDetailsArrangementId | `FloatInput` | Arrangement ID |
| expensearrangementcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| expensearrangementcodeDetailsArrangementCode | `StringInput` | Expense Arrangement Code |
| expensearrangementcodeDetailsExportBucketType | `StringInput` | User defined Export Bucket type. |
| expensearrangementcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| expensearrangementcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| expensearrangementcodeDetailsResort | `StringInput` | Property |
| expensearrangementcodeDetailsType | `StringInput` | Type |
| transcodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| transcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| transcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| transcodeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| transcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| transcodeDetailsResort | `StringInput` | Property |
| transcodeDetailsTranscodeid | `StringInput` | Transcodeid |
| transcodeDetailsTrxCode | `StringInput` | Trx Code |
| folioarrangementcodeDetailsArrangementId | `FloatInput` | Arrangement ID |
| folioarrangementcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| folioarrangementcodeDetailsExportBucketType | `StringInput` | User defined Export Bucket type. |
| folioarrangementcodeDetailsArrangementCode | `StringInput` | Folio Arrangement Code |
| folioarrangementcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| folioarrangementcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| folioarrangementcodeDetailsResort | `StringInput` | Property |
| folioarrangementcodeDetailsType | `StringInput` | Type |
| grouparrangementcodeDetailsArrangementId | `FloatInput` | Arrangement ID |
| grouparrangementcodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| grouparrangementcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| grouparrangementcodeDetailsExportBucketType | `StringInput` | User defined Export Bucket type. |
| grouparrangementcodeDetailsArrangementCode | `StringInput` | Group Arrangement Code |
| grouparrangementcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| grouparrangementcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| grouparrangementcodeDetailsResort | `StringInput` | Property |
| grouparrangementcodeDetailsType | `StringInput` | Type |
| foliotypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| foliotypeDetailsFolioType | `StringInput` | Folio Type Code |
| foliotypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| foliotypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| foliotypeDetailsResort | `StringInput` | Property |
| foliotypedetailDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| foliotypedetailDetailsFolioType | `StringInput` | Folio Type |
| foliotypedetailDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| foliotypedetailDetailsLanguageCode | `StringInput` | Language |
| foliotypedetailDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| foliotypedetailDetailsResort | `StringInput` | Code to uniquely identify the Property |
| bankaccountDetailsAccountId | `FloatInput` | Account ID |
| bankaccountDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| bankaccountDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| bankaccountDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| bankaccountDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| bankaccountDetailsResort | `StringInput` | Property |
| commissionDetailsCommissionCode | `StringInput` | Code |
| commissionDetailsCommissionid | `StringInput` | Commissionid |
| commissionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| commissionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| commissionDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| commissionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| commissionDetailsResort | `StringInput` | Property |
| authorizergroupDetailsAuthGroupCode | `StringInput` | Code |
| authorizergroupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| authorizergroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| authorizergroupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| authorizergroupDetailsResort | `StringInput` | Property |
| authorizergroupdetailDetailsArrangementId | `FloatInput` | Arrangement ID |
| authorizergroupdetailDetailsAuthGroupCode | `StringInput` | Auth Group Code |
| authorizergroupdetailDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| authorizergroupdetailDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| authorizergroupdetailDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| authorizergroupdetailDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| authorizergroupdetailDetailsResort | `StringInput` | Code to uniquely identify the Property |
| authorizergroupdetailDetailsTrxCode | `StringInput` | Transaction Codes |
| authorizerDetailsAppUserId | `FloatInput` | App User ID |
| authorizerDetailsAppUserUniq | `StringInput` | Unique internal ID...needed for ASP module as the same user name can't exists across chains. |
| authorizerDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| authorizerDetailsChainCode | `StringInput` | Chain Code |
| authorizerDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| authorizerDetailsDefCashierId | `FloatInput` | Cashier ID for the User |
| authorizerDetailsDefaultResort | `StringInput` | Stores resort name to which user will log in every time |
| authorizerDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| authorizerDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| authorizerDetailsPersonNameId | `FloatInput` | Foreign key to NAME table that links this USER to an Employee |
| authorizerDetailsSrepCode | `StringInput` | Srep Code |
| authorizerDetailsAppUser | `StringInput` | User ID Code |
| bucketredemptioncodeDetailsCode | `StringInput` | Code |
| bucketredemptioncodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| bucketredemptioncodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| bucketredemptioncodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| bucketredemptioncodeDetailsResort | `StringInput` | Property |
| comproutingcodeDetailsArrangementId | `FloatInput` | Arrangement ID |
| comproutingcodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| comproutingcodeDetailsArrangementCode | `StringInput` | Code |
| comproutingcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| comproutingcodeDetailsExportBucketType | `StringInput` | User defined Export Bucket type. |
| comproutingcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| comproutingcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| comproutingcodeDetailsResort | `StringInput` | Property |
| comproutingcodeDetailsType | `StringInput` | Type |
| comptranscodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| comptranscodeDetailsTrxCode | `StringInput` | Code |
| comptranscodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| comptranscodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| comptranscodeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| comptranscodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| comptranscodeDetailsResort | `StringInput` | Property |
| trxcodecompxrefDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| codegeneratesDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| codegeneratesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| codegeneratesDetailsTrxCode | `StringInput` | Generated Code |
| codegeneratesDetailsId | `FloatInput` | ID |
| codegeneratesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| codegeneratesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| codegeneratesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| codegeneratesDetailsTcGroup | `StringInput` | Transaction Code Group |
| codegeneratesDetailsTcGroupGenerator | `StringInput` | Group generator. |
| codegeneratesDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| codegeneratesDetailsTcSubgroupGenerator | `StringInput` | Subgroup generator. |
| codegeneratesDetailsTclCodeGenerator | `StringInput` | Identify if the taxes are generated on the Class. |
| codegeneratesDetailsTrxCodeGenerator | `StringInput` | Transaction Code Generator |
| comptypeDetailsCompTypeCode | `StringInput` | Code |
| comptypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| comptypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| comptypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| comptypeDetailsResort | `StringInput` | Property |
| barscheduleDetailsRateDate | `DateInput` | Date |
| barscheduleDetailsDescription | `StringInput` | Description |
| barscheduleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| barscheduleDetailsLos | `FloatInput` | Length of Stay |
| barscheduleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| barscheduleDetailsResort | `StringInput` | Property |
| barscheduleDetailsRateCode | `StringInput` | Rate Code |
| citytaxrangeDetailsChainCode | `StringInput` | Chain Code |
| citytaxrangeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| citytaxrangeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| citytaxrangeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| citytaxrangeDetailsPkgFormulaRangeId | `FloatInput` | Oracle sequence to maintain uniqueness. |
| citytaxrangeDetailsResort | `StringInput` | Property |
| citytaxrangeDetailsRecordType | `StringInput` | Record Type |
| resortdaytypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortdaytypeDetailsDtCode | `StringInput` | Day Types Code |
| resortdaytypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortdaytypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortdaytypeDetailsResort | `StringInput` | Property |
| displaysetDetailsAttributeCode | `StringInput` | Code |
| displaysetDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| displaysetDetailsEntityName | `StringInput` | Entity Name |
| displaysetDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| displaysetDetailsLanguageCode | `StringInput` | Language Code |
| displaysetDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| displaysetDetailsTitleSuffix | `FloatInput` | Title Suffix |
| resortcalendareventDetailsEventCode | `StringInput` | Code |
| resortcalendareventDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortcalendareventDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortcalendareventDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortcalendareventDetailsResort | `StringInput` | Property |
| ratehurdlesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| ratehurdlesDetailsHurdleDate | `DateInput` | Hurdle Date |
| ratehurdlesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| ratehurdlesDetailsLengthOfStay | `FloatInput` | Length of Stay |
| ratehurdlesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| ratehurdlesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| ratehurdlesDetailsOverrideflag | `StringInput` | Override YN |
| ratehurdlesDetailsResort | `StringInput` | Property |
| ratehurdlesDetailsRoomCategoryLabel | `StringInput` | Room Category Label |
| ratehurdlesDetailsRoomcategoryid | `StringInput` | Roomcategoryid |
| ratehurdlesDetailsYieldCategory | `StringInput` | Yield Category |
| ratehurdlesDetailsYieldcategoryid | `StringInput` | Yieldcategoryid |
| ratehurdlesDetailsYieldmarkettype | `StringInput` | Yieldmarkettype |
| productDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| productDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| productDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| productDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| productDetailsProduct | `StringInput` | Package |
| productDetailsProductid | `StringInput` | Productid |
| productDetailsResort | `StringInput` | Property |
| itempackageDetailsDescription | `StringInput` | Description |
| itempackageDetailsItemId | `FloatInput` | Item ID |
| itempackageDetailsItemProdId | `FloatInput` | Unqiue ID from ITEM_PACKAGES_SEQNO |
| itempackageDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| itempackageDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| itempackageDetailsResort | `StringInput` | Code to uniquely identify the Property |
| rateproductpriceDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| rateproductpriceDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| rateproductpriceDetailsDay1 | `StringInput` | Day1 |
| rateproductpriceDetailsDay2 | `StringInput` | Day2 |
| rateproductpriceDetailsDay3 | `StringInput` | Day3 |
| rateproductpriceDetailsDay4 | `StringInput` | Day4 |
| rateproductpriceDetailsDay5 | `StringInput` | Day5 |
| rateproductpriceDetailsDay6 | `StringInput` | Day6 |
| rateproductpriceDetailsDay7 | `StringInput` | Day7 |
| rateproductpriceDetailsEndDate | `DateInput` | End Date |
| rateproductpriceDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| rateproductpriceDetailsMaxPersons | `FloatInput` | Maximum number of persons |
| rateproductpriceDetailsMaxNights | `FloatInput` | Maximum Nights. |
| rateproductpriceDetailsMinPersons | `FloatInput` | Minimum number of persons for the rate product price. |
| rateproductpriceDetailsMinNights | `FloatInput` | Minimum number of stay nights for the rate product price. |
| rateproductpriceDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| rateproductpriceDetailsProduct | `StringInput` | Product |
| rateproductpriceDetailsResort | `StringInput` | Property |
| rateproductpriceDetailsResortRateProductDtlId | `FloatInput` | Internal id |
| rateproductpriceDetailsRateCode | `StringInput` | Rate Code |
| rateproductpriceDetailsSeasonCode | `StringInput` | Season Code |
| rateproductpriceDetailsBeginDate | `DateInput` | Start Date |
| pkgforecastgroupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| pkgforecastgroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| pkgforecastgroupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| pkgforecastgroupDetailsResort | `StringInput` | Property |
| promotionDetailsPromoCode | `StringInput` | Code |
| promotionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| promotionDetailsMpcode | `StringInput` | Group |
| promotionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| promotionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| promotionDetailsPromoSeqId | `FloatInput` | Promo Seq ID |
| promotionDetailsResort | `StringInput` | Property |
| promorateDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| promorateDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| promorateDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| promorateDetailsPromoCode | `StringInput` | Promo Code |
| promorateDetailsResort | `StringInput` | Property |
| promocoderoutinstrDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| promocoderoutinstrDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| promocoderoutinstrDetailsPromoCode | `StringInput` | Promo Code |
| promocoderoutinstrDetailsResort | `StringInput` | Property |
| promocoderoutinstrDetailsTrxCodes | `StringInput` | Transaction Codes |
| ratecategoriesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| ratecategoriesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| ratecategoriesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| ratecategoriesDetailsResort | `StringInput` | Property |
| ratecategoriesDetailsRateCategory | `StringInput` | Rate Category |
| ratecategoriesDetailsRateClass | `StringInput` | Rate Class |
| articleDetailsArticleId | `FloatInput` | Article ID |
| articleDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| articleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| articleDetailsArticleid | `FloatInput` | Articleid |
| articleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| articleDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| articleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| articleDetailsResort | `StringInput` | Property |
| creditcardtypesDetailsAttributeCode | `StringInput` | Code |
| creditcardtypesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| creditcardtypesDetailsEntityName | `StringInput` | Entity Name |
| creditcardtypesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| creditcardtypesDetailsLanguageCode | `StringInput` | Language Code |
| creditcardtypesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| paymentmethodDetailsPaymentMethodId | `StringInput` | Code |
| paymentmethodDetailsCcTypeIfc | `StringInput` | Abbreviates the card_type and is used exclusively for the interface. |
| paymentmethodDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| paymentmethodDetailsOrganizationId | `FloatInput` | Organization ID |
| paymentmethodDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| paymentmethodDetailsLocationId | `StringInput` | Location ID |
| paymentmethodDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| paymentmethodDetailsCardType | `StringInput` | Payment Method |
| paymentmethodDetailsResort | `StringInput` | Property |
| exportbucketcodeDetailsArrangementId | `FloatInput` | Arrangement ID |
| exportbucketcodeDetailsExportBucketType | `StringInput` | User defined Export Bucket type. |
| exportbucketcodeDetailsArrangementCode | `StringInput` | Code |
| exportbucketcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| exportbucketcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| exportbucketcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| exportbucketcodeDetailsResort | `StringInput` | Property |
| exportbucketcodeDetailsType | `StringInput` | Type |
| transcodearrangedetDetailsAddTrxYn | `StringInput` | Add Trx Y/N |
| transcodearrangedetDetailsChildArrangementId | `FloatInput` | Child arrangement id. |
| transcodearrangedetDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| transcodearrangedetDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| transcodearrangedetDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| transcodearrangedetDetailsResort | `StringInput` | Code to uniquely identify the Property |
| transcodearrangedetDetailsTrxCode | `StringInput` | Transaction Code |
| exportbuckettypeDetailsExportBucketType | `StringInput` | User defined Export Bucket type. |
| exportbuckettypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| exportbuckettypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| exportbuckettypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| exportbuckettypeDetailsResort | `StringInput` | Property |
| routingcodeDetailsArrangementId | `FloatInput` | Arrangement ID |
| routingcodeDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| routingcodeDetailsArrangementCode | `StringInput` | Code |
| routingcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| routingcodeDetailsExportBucketType | `StringInput` | User defined Export Bucket type. |
| routingcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| routingcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| routingcodeDetailsResort | `StringInput` | Property |
| routingcodeDetailsType | `StringInput` | Type |
| trxdiversionruleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| trxdiversionruledetailsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| transgroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| groupgeneratesDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| groupgeneratesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| groupgeneratesDetailsTrxCode | `StringInput` | Generated Code |
| groupgeneratesDetailsId | `FloatInput` | ID |
| groupgeneratesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| groupgeneratesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| groupgeneratesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| groupgeneratesDetailsTcGroup | `StringInput` | Transaction Code Group |
| groupgeneratesDetailsTcGroupGenerator | `StringInput` | Group generator. |
| groupgeneratesDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| groupgeneratesDetailsTcSubgroupGenerator | `StringInput` | Subgroup generator. |
| groupgeneratesDetailsTclCodeGenerator | `StringInput` | Identify if the taxes are generated on the Class. |
| groupgeneratesDetailsTrxCodeGenerator | `StringInput` | Transaction Code Generator |
| transsubgroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| subgroupgeneratesDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| subgroupgeneratesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| subgroupgeneratesDetailsTrxCode | `StringInput` | Generated Code |
| subgroupgeneratesDetailsId | `FloatInput` | ID |
| subgroupgeneratesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| subgroupgeneratesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| subgroupgeneratesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| subgroupgeneratesDetailsTcGroup | `StringInput` | Transaction Code Group |
| subgroupgeneratesDetailsTcGroupGenerator | `StringInput` | Group generator. |
| subgroupgeneratesDetailsTcSubgroup | `StringInput` | Transaction Code Subgroup |
| subgroupgeneratesDetailsTcSubgroupGenerator | `StringInput` | Subgroup generator. |
| subgroupgeneratesDetailsTclCodeGenerator | `StringInput` | Identify if the taxes are generated on the Class. |
| subgroupgeneratesDetailsTrxCodeGenerator | `StringInput` | Transaction Code Generator |
| resortalertDetailsAlertCode | `StringInput` | Code |
| resortalertDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortalertDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortalertDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortalertDetailsResort | `StringInput` | Propery |
| globalalertsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| globalalertsDetailsExternalAlertId | `StringInput` | Unique ID in External System. |
| globalalertsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| globalalertsDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| globalalertsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| globalalertsDetailsResort | `StringInput` | Property |
| globalalertsDetailsQueryId | `FloatInput` | Query ID |
| globalalertsDetailsResvAlertId | `FloatInput` | Resv Alert ID |
| globalalertsDetailsResvNameId | `FloatInput` | Resv Name ID |
| blockcancellationcodeDetailsAttributeCode | `StringInput` | Code |
| blockcancellationcodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| blockcancellationcodeDetailsExternalAttributeCodes | `StringInput` | Contains a list of codes used by a vendor. |
| blockcancellationcodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| blockcancellationcodeDetailsLanguageCode | `StringInput` | Language Code |
| blockcancellationcodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| blockcancellationcodeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| scdestinationDetailsAttributeCode | `StringInput` | Cancellation Destination |
| scdestinationDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| scdestinationDetailsEntityName | `StringInput` | Entity Name |
| scdestinationDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| scdestinationDetailsLanguageCode | `StringInput` | Language Code |
| scdestinationDetailsScdestinationid | `StringInput` | Scdestinationid |
| scdestinationDetailsTitleSuffix | `FloatInput` | Title Suffix |
| lostbookingcodesDetailsAttributeCode | `StringInput` | Code |
| lostbookingcodesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| lostbookingcodesDetailsEntityName | `StringInput` | Entity Name |
| lostbookingcodesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| lostbookingcodesDetailsLanguageCode | `StringInput` | Language Code |
| lostbookingcodesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| lostbookingcodesDetailsTitleSuffix | `FloatInput` | Title Suffix |
| refusedbookingcodesDetailsAttributeCode | `StringInput` | Code |
| refusedbookingcodesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| refusedbookingcodesDetailsEntityName | `StringInput` | Entity Name |
| refusedbookingcodesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| refusedbookingcodesDetailsLanguageCode | `StringInput` | Language Code |
| refusedbookingcodesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| refusedbookingcodesDetailsTitleSuffix | `FloatInput` | Title Suffix |
| bookingmethodDetailsBookingmethodid | `StringInput` | Bookingmethodid |
| bookingmethodDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| bookingmethodDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| bookingmethodDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| bookingmethodDetailsAttributeCode | `StringInput` | Reservation Method |
| bookingmethodDetailsTitleSuffix | `FloatInput` | Title Suffix |
| resortcutoffscheduleDetailsWashcode | `StringInput` | Unique code to identify a Wash schedule. |
| resortcutoffscheduleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortcutoffscheduleDetailsCutoffDays | `FloatInput` | Cut off days for the stay date. |
| resortcutoffscheduleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortcutoffscheduleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortcutoffscheduleDetailsResort | `StringInput` | Property |
| bookingstatusDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| bookingstatusDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| bookingstatusDetailsStatus | `StringInput` | Old Block Status |
| bookingstatusDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| cancelruleDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| cancelruleDetailsRuleCode | `StringInput` | Code |
| cancelruleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| cancelruleDetailsDepositcancelruleid | `FloatInput` | Depositcancelruleid |
| cancelruleDetailsDepositcancelrulepmsref | `FloatInput` | Deposit Cancel Rule PMS Reference |
| cancelruleDetailsDepositorCancellationRule | `StringInput` | Depositor Cancellation Rule |
| cancelruleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| cancelruleDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| cancelruleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| cancelruleDetailsResort | `StringInput` | Property |
| cancelruleDetailsRateCode | `StringInput` | Rate Code |
| cancelruleDetailsRateSetId | `FloatInput` | Rate Set ID |
| cancelruleDetailsReservationType | `StringInput` | Reservation Type |
| cancelruleDetailsSeasonCode | `StringInput` | Season Code |
| cancelrulescheduleDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| cancelrulescheduleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| cancelrulescheduleDetailsDepositcancelruleid | `FloatInput` | Depositcancelruleid |
| cancelrulescheduleDetailsDepositcancelrulepmsref | `FloatInput` | Deposit Cancel Rule PMS Reference |
| cancelrulescheduleDetailsDepositorCancellationRule | `StringInput` | Depositor Cancellation Rule |
| cancelrulescheduleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| cancelrulescheduleDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| cancelrulescheduleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| cancelrulescheduleDetailsResort | `StringInput` | Property |
| cancelrulescheduleDetailsRateCode | `StringInput` | Rate Code |
| cancelrulescheduleDetailsRateSetId | `FloatInput` | Rate Set ID |
| cancelrulescheduleDetailsReservationType | `StringInput` | Reservation Type |
| cancelrulescheduleDetailsRuleCode | `StringInput` | Rule |
| cancelrulescheduleDetailsSeasonCode | `StringInput` | Season Code |
| depositruleDetailsBeginDate | `DateInput` | Begin Date |
| depositruleDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| depositruleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| depositruleDetailsRuleCode | `StringInput` | Deposit Rule |
| depositruleDetailsDepositcancelruleid | `FloatInput` | Depositcancelruleid |
| depositruleDetailsDepositcancelrulepmsref | `FloatInput` | Deposit Cancel Rule PMS Reference |
| depositruleDetailsDepositorCancellationRule | `StringInput` | Depositor Cancellation Rule |
| depositruleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| depositruleDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| depositruleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| depositruleDetailsResort | `StringInput` | Property |
| depositruleDetailsRateCode | `StringInput` | Rate Code |
| depositruleDetailsRateSetId | `FloatInput` | Rate Set ID |
| depositruleDetailsReservationType | `StringInput` | Reservation Type |
| depositruleDetailsSeasonCode | `StringInput` | Season Code |
| depositrulescheduleDetailsBeginDate | `DateInput` | Begin Date |
| depositrulescheduleDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| depositrulescheduleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| depositrulescheduleDetailsDepositcancelruleid | `FloatInput` | Depositcancelruleid |
| depositrulescheduleDetailsDepositcancelrulepmsref | `FloatInput` | Deposit Cancel Rule PMS Reference |
| depositrulescheduleDetailsDepositorCancellationRule | `StringInput` | Depositor Cancellation Rule |
| depositrulescheduleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| depositrulescheduleDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| depositrulescheduleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| depositrulescheduleDetailsResort | `StringInput` | Property |
| depositrulescheduleDetailsRateCode | `StringInput` | Rate Code |
| depositrulescheduleDetailsRateSetId | `FloatInput` | Rate Set ID |
| depositrulescheduleDetailsReservationType | `StringInput` | Reservation Type |
| depositrulescheduleDetailsRuleCode | `StringInput` | Rule |
| depositrulescheduleDetailsSeasonCode | `StringInput` | Season Code |
| guaranteeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| guaranteeDetailsGuaranteecodeid | `StringInput` | Guaranteecodeid |
| guaranteeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| guaranteeDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| guaranteeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| guaranteeDetailsResort | `StringInput` | Property |
| guaranteeDetailsGuaranteeCode | `StringInput` | Reservation Type |
| reservationtypescheduleDetailsBeginDate | `DateInput` | Begin Date |
| reservationtypescheduleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationtypescheduleDetailsDepositcancelruleid | `FloatInput` | Depositcancelruleid |
| reservationtypescheduleDetailsDepositcancelrulepmsref | `FloatInput` | Deposit Cancel Rule PMS Reference |
| reservationtypescheduleDetailsDepositorCancellationRule | `StringInput` | Depositor Cancellation Rule |
| reservationtypescheduleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| reservationtypescheduleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationtypescheduleDetailsResort | `StringInput` | Property |
| reservationtypescheduleDetailsRateCode | `StringInput` | Rate Code |
| reservationtypescheduleDetailsRateSetId | `FloatInput` | Rate Set ID |
| reservationtypescheduleDetailsReservationType | `StringInput` | Reservation Type |
| reservationtypescheduleDetailsRuleCode | `StringInput` | Rule Code |
| reservationtypescheduleDetailsSeasonCode | `StringInput` | Season Code |
| marketDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| marketDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| marketDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| marketDetailsMarketCode | `StringInput` | Market Code |
| marketDetailsParentMarketCode | `StringInput` | Market group attached to the market code |
| marketDetailsMarketgroupid | `StringInput` | Marketgroupid |
| marketDetailsMarketid | `StringInput` | Marketid |
| marketDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| marketDetailsResort | `StringInput` | Property |
| marketgroupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| marketgroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| marketgroupDetailsMarketGroup | `StringInput` | Market group code |
| marketgroupDetailsMarketgroupid | `StringInput` | Marketgroupid |
| marketgroupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| marketgroupDetailsResort | `StringInput` | Property |
| resortmarketingcityDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortmarketingcityDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortmarketingcityDetailsMarketingCity | `StringInput` | Marketing City |
| resortmarketingcityDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortmarketingcityDetailsResort | `StringInput` | Property |
| resortmarketingcityDetailsRegionCode | `StringInput` | Region Code |
| marketingregionsDetailsAttributeCode | `StringInput` | Code |
| marketingregionsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| marketingregionsDetailsEntityName | `StringInput` | Entity Name |
| marketingregionsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| marketingregionsDetailsLanguageCode | `StringInput` | Language Code |
| marketingregionsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| marketingregionsDetailsTitleSuffix | `FloatInput` | Title Suffix |
| channelDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| channelDetailsEntityName | `StringInput` | Entity Name |
| channelDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| channelDetailsLanguageCode | `StringInput` | Language Code |
| channelDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| channelDetailsAttributeCode | `StringInput` | Origin Code |
| channelDetailsTitleSuffix | `FloatInput` | Title Suffix |
| sellmessagesDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |
| sellmessagesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| sellmessagesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| sellmessagesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| sellmessagesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| sellmessagesDetailsResort | `StringInput` | Property |
| sellmessagesDetailsRateCode | `StringInput` | Rate Code |
| sellmessagesDetailsRoomCategory | `StringInput` | Room Category |
| sellmessagesDetailsSellId | `FloatInput` | The primary key for this table. |
| sourcetableDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| sourcetableDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| sourcetableDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| sourcetableDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| sourcetableDetailsResort | `StringInput` | Property |
| sourcetableDetailsSourceCode | `StringInput` | Source Code |
| sourcetableDetailsSourceid | `StringInput` | Sourceid |
| sourcegroupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| sourcegroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| sourcegroupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| sourcegroupDetailsResort | `StringInput` | Property |
| sourcegroupDetailsSourceCode | `StringInput` | Source Group |
| resvautoattachrulesDetailsRuleCode | `StringInput` | Code |
| resvautoattachrulesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvautoattachrulesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvautoattachrulesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvautoattachrulesDetailsResort | `StringInput` | Property |
| resvautoattachrulesDetailsRoomCategory | `StringInput` | Room Category |
| resvautoattachdetailsDetailsAttachId | `FloatInput` | Attach ID |
| resvautoattachdetailsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvautoattachdetailsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvautoattachdetailsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvautoattachdetailsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resvautoattachdetailsDetailsRuleCode | `StringInput` | Rule Code |
| cancellationcodesDetailsAttributeCode | `StringInput` | Code |
| cancellationcodesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| cancellationcodesDetailsEntityName | `StringInput` | Entity Name |
| cancellationcodesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| cancellationcodesDetailsLanguageCode | `StringInput` | Language Code |
| cancellationcodesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| cancellationcodesDetailsTitleSuffix | `FloatInput` | Title Suffix |
| entrypointDetailsAttributeCode | `StringInput` | Code |
| entrypointDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| entrypointDetailsEntityName | `StringInput` | Entity Name |
| entrypointDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| entrypointDetailsLanguageCode | `StringInput` | Language Code |
| entrypointDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| entrypointDetailsTitleSuffix | `FloatInput` | Title Suffix |
| discountreasonDetailsAttributeCode | `StringInput` | Attribute Code |
| discountreasonDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| discountreasonDetailsEntityName | `StringInput` | Entity Name |
| discountreasonDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| discountreasonDetailsLanguageCode | `StringInput` | Language Code |
| discountreasonDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| discountreasonDetailsTitleSuffix | `FloatInput` | Title Suffix |
| ecouponDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| ecouponDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| ecouponDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| ecouponDetailsResort | `StringInput` | Property |
| ecouponDetailsEcouponCode | `StringInput` | eCoupon Code |
| resortlocatorDetailsLocatorCode | `FloatInput` | Locator code. |
| resortlocatorDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortlocatorDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortlocatorDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortlocatorDetailsResort | `StringInput` | Property |
| resortmessageDetailsMessageCode | `StringInput` | Code |
| resortmessageDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortmessageDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortmessageDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resortmessageDetailsResort | `StringInput` | Property |
| gueststatusDetailsAttributeCode | `StringInput` | Code |
| gueststatusDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| gueststatusDetailsEntityName | `StringInput` | Entity Name |
| gueststatusDetailsEntityname | `StringInput` | Entityname |
| gueststatusDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| gueststatusDetailsLanguageCode | `StringInput` | Language Code |
| gueststatusDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| gueststatusDetailsTitleSuffix | `FloatInput` | Title Suffix |
| guesttypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| guesttypeDetailsEntityName | `StringInput` | Entity Name |
| guesttypeDetailsAttributeCode | `StringInput` | Guest Type |
| guesttypeDetailsGuesttypeid | `StringInput` | Guesttypeid |
| guesttypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| guesttypeDetailsLanguageCode | `StringInput` | Language Code |
| guesttypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| guesttypeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| immigrationstatusDetailsAttributeCode | `StringInput` | Code |
| immigrationstatusDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| immigrationstatusDetailsEntityName | `StringInput` | Entity Name |
| immigrationstatusDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| immigrationstatusDetailsLanguageCode | `StringInput` | Language Code |
| immigrationstatusDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| immigrationstatusDetailsTitleSuffix | `FloatInput` | Title Suffix |
| preregrulesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| preregrulesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| preregrulesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| preregrulesDetailsResort | `StringInput` | Property |
| preregrulesDetailsRuleId | `FloatInput` | Rule ID |
| itemclassDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| itemclassDetailsItemclassId | `FloatInput` | Itemclass ID |
| itemclassDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| itemclassDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| itemclassDetailsResort | `StringInput` | Property |
| iteminventoryDetailsBraceletRuleCode | `StringInput` | Links to RESORT_BRACELET_RULES.RULE_CODE. |
| iteminventoryDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| iteminventoryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| iteminventoryDetailsItemId | `FloatInput` | Item ID |
| iteminventoryDetailsItemPoolId | `FloatInput` | References the ITEM_POOL_ID from GEM$ITEM_POOL. |
| iteminventoryDetailsItemclassId | `FloatInput` | Itemclass ID |
| iteminventoryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| iteminventoryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| iteminventoryDetailsResort | `StringInput` | Property |
| iteminventoryDetailsArticleNumber | `StringInput` | Quick Insert |
| iteminventoryDetailsRevType | `StringInput` | Rev Type |
| itempoolDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| itempoolDetailsItemPoolId | `FloatInput` | References the ITEM_POOL_ID from GEM$ITEM_POOL. |
| itempoolDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| itempoolDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| itempoolDetailsResort | `StringInput` | Property |
| birthcountryDetailsAttributeCode | `StringInput` | Code |
| birthcountryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| birthcountryDetailsEntityName | `StringInput` | Entity Name |
| birthcountryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| birthcountryDetailsLanguageCode | `StringInput` | Language Code |
| birthcountryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| birthcountryDetailsTitleSuffix | `FloatInput` | Title Suffix |
| resortcountryDetailsChainCode | `StringInput` | Chain Code |
| resortcountryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resortcountryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resortcountryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| countrygroupDetailsAttributeCode | `StringInput` | Country Group Code |
| countrygroupDetailsCountrygroupid | `StringInput` | Countrygroupid |
| countrygroupDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| countrygroupDetailsEntityName | `StringInput` | Entity Name |
| countrygroupDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| countrygroupDetailsLanguageCode | `StringInput` | Language Code |
| countrygroupDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| countrygroupDetailsTitleSuffix | `FloatInput` | Title Suffix |
| distancetypeDetailsAttributeCode | `StringInput` | Code |
| distancetypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| distancetypeDetailsEntityName | `StringInput` | Entity Name |
| distancetypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| distancetypeDetailsLanguageCode | `StringInput` | Language Code |
| distancetypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| distancetypeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| districtDetailsAttributeCode | `StringInput` | Code |
| districtDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| districtDetailsEntityName | `StringInput` | Entity Name |
| districtDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| districtDetailsLanguageCode | `StringInput` | Language Code |
| districtDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| districtDetailsTitleSuffix | `FloatInput` | Title Suffix |
| fiscalguesttypeDetailsAttributeCode | `StringInput` | Code |
| fiscalguesttypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| fiscalguesttypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| fiscalguesttypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| fiscalguesttypeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| fiscalregionDetailsAttributeCode | `StringInput` | Code |
| fiscalregionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| fiscalregionDetailsEntityName | `StringInput` | Entity Name |
| fiscalregionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| fiscalregionDetailsLanguageCode | `StringInput` | Language Code |
| fiscalregionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| fiscalregionDetailsTitleSuffix | `FloatInput` | Title Suffix |
| profileidcountryDetailsAttributeCode | `StringInput` | Code |
| profileidcountryDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileidcountryDetailsEntityName | `StringInput` | Entity Name |
| profileidcountryDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileidcountryDetailsLanguageCode | `StringInput` | Language Code |
| profileidcountryDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileidcountryDetailsTitleSuffix | `FloatInput` | Title Suffix |
| nationalityDetailsAttributeCode | `StringInput` | Code |
| nationalityDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| nationalityDetailsEntityName | `StringInput` | Entity Name |
| nationalityDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| nationalityDetailsLanguageCode | `StringInput` | Language Code |
| nationalityDetailsNationalityid | `StringInput` | Nationalityid |
| nationalityDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| nationalityDetailsTitleSuffix | `FloatInput` | Title Suffix |
| qualifyingratesDetailsAdvanceBooking | `FloatInput` | Min number of days to book rate in advance. |
| qualifyingratesDetailsBaseRateCode | `StringInput` | Base Rate Code |
| qualifyingratesDetailsBeginBookingDate | `DateInput` | Begin Booking Date |
| qualifyingratesDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| qualifyingratesDetailsCommissionCode | `StringInput` | Commission Code |
| qualifyingratesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| qualifyingratesDetailsDailyRatesYn | `StringInput` | Daily Rates Y/N |
| qualifyingratesDetailsDbaseRateCode | `StringInput` | The rate code on which this rate shedule is dynamically based on. |
| qualifyingratesDetailsEndBookingDate | `DateInput` | End Booking Date |
| qualifyingratesDetailsGroupCode | `StringInput` | Group Code |
| qualifyingratesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| qualifyingratesDetailsLosUnit | `FloatInput` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| qualifyingratesDetailsMarketCode | `StringInput` | Market Code |
| qualifyingratesDetailsMaxAdvanceBooking | `FloatInput` | Max number of days to book rate in advance. |
| qualifyingratesDetailsMaxLos | `FloatInput` | Max Los |
| qualifyingratesDetailsMaxOccupancy | `FloatInput` | Max Occupancy |
| qualifyingratesDetailsMinOccupancy | `FloatInput` | Minimum Occupancy |
| qualifyingratesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| qualifyingratesDetailsOrsSellSequence | `FloatInput` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| qualifyingratesDetailsPendingApprovalYn | `StringInput` | Indicates whether the rate code is pending for approval or not |
| qualifyingratesDetailsResort | `StringInput` | Property |
| qualifyingratesDetailsRateBucket | `StringInput` | Yield rate bucket |
| qualifyingratesDetailsRateCode | `StringInput` | Rate Codes |
| qualifyingratesDetailsRateLevel | `FloatInput` | Rate Level this rate code belongs to. |
| qualifyingratesDetailsSellSequence | `FloatInput` | Sell Sequence |
| qualifyingratesDetailsSourceCode | `StringInput` | Source Code |
| qualifyingratesDetailsTrxCode | `StringInput` | Transaction Code |
| membershipstatusDetailsAttributeCode | `StringInput` | Code |
| membershipstatusDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| membershipstatusDetailsEntityName | `StringInput` | Entity Name |
| membershipstatusDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| membershipstatusDetailsLanguageCode | `StringInput` | Language Code |
| membershipstatusDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| membershipstatusDetailsTitleSuffix | `FloatInput` | Title Suffix |
| priorityDetailsAttributeCode | `StringInput` | Code |
| priorityDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| priorityDetailsEntityName | `StringInput` | Entity Name |
| priorityDetailsOrganizationId | `FloatInput` | Organization ID |
| priorityDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| priorityDetailsLanguageCode | `StringInput` | Language Code |
| priorityDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| priorityDetailsPriorityId | `StringInput` | Priority ID |
| priorityDetailsPriorityType | `StringInput` | Priority Type.  Default Value is PMSGRID |
| priorityDetailsTitleSuffix | `FloatInput` | Title Suffix |
| entityaccounttypeDetailsAttributeCode | `StringInput` | Code |
| entityaccounttypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| entityaccounttypeDetailsEntityName | `StringInput` | Entity Name |
| entityaccounttypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| entityaccounttypeDetailsLanguageCode | `StringInput` | Language Code |
| entityaccounttypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| entityaccounttypeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| addresstypeDetailsAttributeCode | `StringInput` | Code |
| addresstypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| addresstypeDetailsEntityName | `StringInput` | Entity Name |
| addresstypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| addresstypeDetailsLanguageCode | `StringInput` | Language Code |
| addresstypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| addresstypeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| altlanguagetitleDetailsAttributeCode | `StringInput` | Code |
| altlanguagetitleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| altlanguagetitleDetailsEntityName | `StringInput` | Entity Name |
| altlanguagetitleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| altlanguagetitleDetailsLanguageCode | `StringInput` | Language |
| altlanguagetitleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| altlanguagetitleDetailsTitleSuffix | `FloatInput` | Title Number |
| roomspotentialDetailsRoomsPotentialId | `StringInput` | Code |
| roomspotentialDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| roomspotentialDetailsEntityName | `StringInput` | Entity Name |
| roomspotentialDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| roomspotentialDetailsLanguageCode | `StringInput` | Language Code |
| roomspotentialDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomspotentialDetailsRoomsPotentialType | `StringInput` | Rooms Potential Type |
| roomspotentialDetailsTitleSuffix | `FloatInput` | Title Suffix |
| businesssegmentDetailsAttributeCode | `StringInput` | Code |
| businesssegmentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| businesssegmentDetailsEntityName | `StringInput` | Entity Name |
| businesssegmentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| businesssegmentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| businesssegmentDetailsTitleSuffix | `FloatInput` | Title Suffix |
| companytypeDetailsAttributeCode | `StringInput` | Code |
| companytypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| companytypeDetailsEntityName | `StringInput` | Entity Name |
| companytypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| companytypeDetailsLanguageCode | `StringInput` | Language Code |
| companytypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| companytypeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| competitionDetailsAttributeCode | `StringInput` | Attribute Code |
| competitionDetailsCompetitionId | `StringInput` | Code |
| competitionDetailsCompetitionType | `StringInput` | Competition |
| competitionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| competitionDetailsEntityName | `StringInput` | Entity Name |
| competitionDetailsOrganizationId | `FloatInput` | Organization ID |
| competitionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| competitionDetailsLanguageCode | `StringInput` | Language Code |
| competitionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| competitionDetailsTitleSuffix | `FloatInput` | Title Suffix |
| genderDetailsAttributeCode | `StringInput` | Code |
| genderDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| genderDetailsEntityName | `StringInput` | Entity Name |
| genderDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| genderDetailsLanguageCode | `StringInput` | Language Code |
| genderDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| genderDetailsTitleSuffix | `FloatInput` | Title Suffix |
| profileinactivereasonDetailsAttributeCode | `StringInput` | Code |
| profileinactivereasonDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileinactivereasonDetailsEntityName | `StringInput` | Entity Name |
| profileinactivereasonDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileinactivereasonDetailsLanguageCode | `StringInput` | Language Code |
| profileinactivereasonDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileinactivereasonDetailsTitleSuffix | `FloatInput` | Title Suffix |
| industrycodeDetailsAttributeCode | `StringInput` | Code |
| industrycodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| industrycodeDetailsEntityName | `StringInput` | Entity Name |
| industrycodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| industrycodeDetailsLanguageCode | `StringInput` | Language Code |
| industrycodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| industrycodeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| influencecodeDetailsAttributeCode | `StringInput` | Code |
| influencecodeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| influencecodeDetailsEntityName | `StringInput` | Entity Name |
| influencecodeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| influencecodeDetailsLanguageCode | `StringInput` | Language Code |
| influencecodeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| influencecodeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| keywordtypeDetailsAttributeCode | `StringInput` | Code |
| keywordtypeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| keywordtypeDetailsEntityName | `StringInput` | Entity Name |
| keywordtypeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| keywordtypeDetailsLanguageCode | `StringInput` | Language Code |
| keywordtypeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| keywordtypeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| mailingactionDetailsMailingActionId | `StringInput` | Code |
| mailingactionDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| mailingactionDetailsOrganizationId | `FloatInput` | Organization ID |
| mailingactionDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| mailingactionDetailsLanguageCode | `StringInput` | Language Code |
| mailingactionDetailsMailingActionType | `StringInput` | Mailing Action Type |
| mailingactionDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| mailingactionDetailsTitleSuffix | `FloatInput` | Title Suffix |
| preferenceDetailsPreferenceSeqId | `FloatInput` | Central Code |
| preferenceDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| preferenceDetailsOrganizationId | `FloatInput` | Organization ID |
| preferenceDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| preferenceDetailsLocationId | `StringInput` | Location ID |
| preferenceDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| preferenceDetailsPreferenceType | `StringInput` | Preference Group |
| preferenceDetailsPreferenceId | `FloatInput` | Internal Id of the preference |
| preferenceDetailsPreference1 | `StringInput` | Preference1 |
| preferenceDetailsResort | `StringInput` | Property |
| profilerestrictionreasonDetailsAttributeCode | `StringInput` | Code |
| profilerestrictionreasonDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profilerestrictionreasonDetailsEntityName | `StringInput` | Entity Name |
| profilerestrictionreasonDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profilerestrictionreasonDetailsLanguageCode | `StringInput` | Language Code |
| profilerestrictionreasonDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profilerestrictionreasonDetailsTitleSuffix | `FloatInput` | Title Suffix |
| scscopeDetailsAttributeCode | `StringInput` | Code |
| scscopeDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| scscopeDetailsEntityName | `StringInput` | Entity Name |
| scscopeDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| scscopeDetailsLanguageCode | `StringInput` | Language Code |
| scscopeDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| scscopeDetailsTitleSuffix | `FloatInput` | Title Suffix |
| scscopecityDetailsAttributeCode | `StringInput` | Code |
| scscopecityDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| scscopecityDetailsEntityName | `StringInput` | Entity Name |
| scscopecityDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| scscopecityDetailsLanguageCode | `StringInput` | Language Code |
| scscopecityDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| scscopecityDetailsTitleSuffix | `FloatInput` | Title Suffix |
| memclaimadjlimitDetailsClaimAdjLimitCode | `StringInput` | Adjustment Limit Code |
| memclaimadjlimitDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| memclaimadjlimitDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| memclaimadjlimitDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query configurationResort($input: ConfigurationResortQueryArgumentsType!) {
  configurationResort(input: $input) @stream {
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
    membershipClaimOriginDetails {
      businessTitle
      canDeleteYn
      chainCode
      claimOriginCode
      claimOriginDescription
      comments
      dSI
      deletedflag
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    membershipPointsDetails {
      allMembershipRatesYn
      allMembershipTransactionYN
      averageRateAmount
      beginDate
      billingGroup
      bookingEndDate
      bookingStartDate
      calculationRule
      chainCode
      costPerPoint
      creditMultipleMembershipYn
      dSI
      daysSinceEnrolled
      deletedFlag
      description
      earningRhythmFlg
      earningRhythmNights
      endDate
      enrollmentCode
      enrollmentGroup
      excludeBbFlg
      excludeFromPointProjectionYN
      excludeMktGroup
      excludeRevGroup
      excludeRoomGroupYn
      expirationDate
      exportLabel
      fridayYN
      inactiveDate
      includeGraceRenewalFlg
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      marketCode
      marketGroup
      marketGroupIncludeYN
      maxBucketSize
      maximumNights
      maximumRevenue
      memRevenueGroup
      membershipLevel
      membershipPointsSeqno
      membershipRateGroupExcludeYN
      membershipType
      minPropertiesReq
      minimumNights
      minimumRateAmount
      minimumRevenue
      minimumStays
      mondayYN
      multipleTransactionsYn
      numberOfTimesEligible
      organizationID
      perRevenueUnits
      points
      pointsEligibilityCode
      pointsRatioPercentYn
      pointsRatioRoundingFlg
      preferredCardExcludeYn
      primaryKeyID
      programType
      programTypeDesc
      promotionCode
      property
      propertyGroup
      pseudoRuleYn
      qualifyingRatesYN
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rateGroup
      rateGroupIncludeYN
      reservationChannel
      revenueGroup
      revenueGroupIncludeYN
      roomClass
      roomGroup
      roomType
      roomTypeToChargeYN
      rounding
      ruleAppliesTo
      ruleBasedOn
      ruleCode
      saturdayYN
      sundayYN
      thursdayYN
      toMemberLevel
      transactionType
      tuesdayYN
      type
      typeOfPoints
      updateDate
      updateUser
      userpostingOnlyYn
      wednesdayYN
    }
    membershipAwardRatesDetails {
      awardType
      chainCode
      dSI
      deletedFlag
      membershipType
      organizationID
      property
      rateCode
      rateDescription
    }
    membershipAwardProductsDetails {
      awardType
      centralPackageCode
      centralPackageDescription
      chainCode
      dSI
      deletedFlag
      membershipType
      organizationID
      packageCode
      packageDescription
      property
    }
    membershipAwardUpgradesDetails {
      awardType
      centralUpgradeFromRoom
      centralUpgradeToRoom
      chainCode
      dSI
      deletedFlag
      fromDate
      fromRoom
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      membershipAwardId
      membershipType
      organizationID
      pointsRequiredUpgrades
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      toDate
      toRoom
      updateDate
      updateUser
      upgradeFromRoom
      upgradeToRoom
    }
    membershipAwardFinancialTransactionDetails {
      awardType
      centralTransactionCode
      centralTransactionCodeDescription
      chainCode
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      membershipType
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      transactionCode
      transactionCodeDescription
      updateDate
      updateUser
    }
    membershipPropertyGroupCodeDetails {
      attachedPropertyCode
      attachedPropertyDescription
      chainCode
      dSI
      deletedFlag
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      membershipResortGroup
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      requiredYn
      updateDate
      updateUser
    }
    airportDetails {
      code
      dSI
      deletedFlag
      description
      distance
      distanceType
      drivingDirections
      drivingTime
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      sequence
      transportationCode1
      transportationCode2
      transportationCode3
      transportationCode4
      transportationCode5
      transportationCode6
      transportationCode7
      transportationCode8
      updateDate
      updateUser
      website
    }
    featureDetails {
      code
      dSI
      deletedFlag
      description
      endDate
      featureType
      featureid
      hours
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      notes
      organizationID
      price
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      sequence
      startDate
      type
      updateDate
      updateUser
    }
    attractionCategoryDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    attractionDetails {
      address1
      address2
      address3
      address4
      attractionClass
      category
      city
      code
      coordinateSupplier
      dSI
      deletedFlag
      description
      direction
      directions
      distance
      distanceType
      drivingTime
      generalDirections
      hoursOfOperation
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      latitude
      longitude
      organizationID
      priceRange
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      region
      sequence
      state
      updateDate
      updateUser
      website
      zipCode
    }
    chainDetails {
      aspYn
      beginDate
      bookingConditions
      centralChain
      centralDescription
      chain
      chainName
      dSI
      deletedFlag
      description
      endDate
      frequentFlierCardsAcceptYn
      hoCity
      hoCountry
      hoEmail
      hoFax
      hoPostCode
      hoState
      hoStreet
      hoTelephone
      imgChainId
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      logoFileName
      loyaltyProgram
      marketingText
      nameId
      organizationID
      primaryKeyID
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      scriptId
      shareProfilesYN
      updateDate
      updateUser
    }
    closingScriptDetails {
      chainCode
      dSI
      deletedFlag
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      membershipType
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      resortType
      scriptId
      scriptType
    }
    communicationMethodDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    deliveryStatusDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    departmentDetails {
      allowOnTaskSheetYn
      canDeleteYn
      chainCode
      dSI
      deletedFlag
      departmentCode
      departmentid
      deptManagerPager
      description
      email
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      messageText
      organizationID
      primaryKeyID
      property
      repDeptName
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      reportingDeptId
      rnaInsertDate
      rnaUpdateDate
      sequence
      updateDate
      updateUser
    }
    elecRegCardScriptDetails {
      chainCode
      dSI
      deletedFlag
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      membershipType
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      resortType
      scriptId
      scriptType
    }
    hubPropertyDetails {
      associatedProperty
      associatedPropertyName
      croCode
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
    jobTitleDetails {
      chainCode
      closingScriptYn
      code
      dSI
      deletedFlag
      description
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
    }
    uDFCategoryDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    uDFTypeDetails {
      attributeType
      attributeVerified
      category
      chainCode
      code
      dSI
      deletedFlag
      description
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      multipleYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      sequence
      tableName
      updateDate
      updateUser
    }
    brandCodeDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    businessUnitDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    departmentCodeDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    divisionDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    hotelCategoryDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    operatingUnitDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    applicationParameterValueDetails {
      aPNDeletedFlag
      aPNDisplayYN
      aPNJRNUpdateDate
      aPNJRNUpdateDateAndTime
      aPNPrimaryKeyID
      aPNRNAInsertDate
      aPNRNAUpdateDate
      canDeleteYn
      chainCode
      copyYn
      coreYn
      dSI
      deletedFlag
      displayYn
      explanation
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      lovValues
      orderBy
      organizationID
      parameterDescription
      parameterDisplayName
      parameterGroup
      parameterName
      parameterType
      parameterTypeDetail
      parameterValue
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      storedInResort
      updateDate
      updateUser
      usedInApp
    }
    trackitActionDetails {
      code
      dSI
      defaultYn
      deletedFlag
      description
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      messageText
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sendMessageYn
      sequence
      status
      tiSubgroup
      trackItGroup
      trackitTypesUrl
      updateDate
      updateUser
    }
    trackitLocationDetails {
      actionStatus
      code
      dSI
      defaultYn
      deletedFlag
      description
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      messageText
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sendMessageYn
      sequence
      tiSubgroup
      trackItGroup
      trackitTypesUrl
      updateDate
      updateUser
    }
    trackitTypeDetails {
      actionStatus
      code
      dSI
      defaultYn
      deletedFlag
      description
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      messageText
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sendMessageYN
      sequence
      tiSubgroup
      trackItGroup
      updateDate
      updateUser
      website
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
    aRReminderCycleDetails {
      accountTypeId
      dSI
      deletedFlag
      globalAccountYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      letterName
      numberOfDays
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reminderCode
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
    transactionReasonCodeDetails {
      adjustmentCode
      adjustmentCodeDescription
      adjustmentType
      amountPercentFlag
      amountPercentValue
      birGuestType
      codeType
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      tranCodeType
      updateDate
      updateUser
    }
    creditCardAuthorizationRulesDetails {
      amount
      authorizationRules
      cAmount
      cExchangeDate
      cExchangeRate
      dSI
      deletedFlag
      description
      guaranteeCode
      jRNUpdateDate
      jRNUpdateDateAndTime
      mainWindowYn
      organizationID
      percentage
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rateCategory
      rateCode
      roomClass
      roomType
      sourceCode
    }
    autoFolioSettlementTypeDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
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
    customNumberDetails {
      activeYN
      chainCode
      code
      customNumberFormula
      customNumberType
      dSI
      deletedFlag
      description
      endDate
      filterCondition
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      sequence
      startDate
      updateDate
      updateUser
    }
    currencyExchangeTaxDetails {
      amountFrom
      amountTo
      cExchangeDate
      cExchangeRate
      cMaxAmount
      cMaxServiceTax
      cMinimumAmount
      cMinimumServiceTax
      cNotionalAmount
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      maximum
      minimum
      notionalAmount
      organizationID
      percentage
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      serviceTaxType
      updateDate
      updateUser
    }
    expenseArrangementCodeDetails {
      arrTaxTypeCode
      arrangeId
      arrangementId
      bucketValue
      cExchangeDate
      cExchangeRate
      cRoutingAmount
      compYn
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
      expenseArrangementCode
      expenseArrangementDescription
      exportBucketType
      inactiveDate
      inheritAuthRatecodeYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      revenueYn
      routingAmount
      routingCovers
      routingPercent
      type
      updateDate
      updateUser
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
    folioArrangementCodeDetails {
      arrTaxTypeCode
      arrangeId
      arrangementId
      bucketValue
      cExchangeDate
      cExchangeRate
      cRoutingAmount
      compYn
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
      folioArrangementCode
      folioArrangementDescription
      inactiveDate
      inheritAuthRatecodeYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      revenueYn
      routingAmount
      routingCovers
      routingPercent
      type
      updateDate
      updateUser
    }
    groupArrangementCodeDetails {
      arrTaxTypeCode
      arrangeId
      arrangementId
      bucketValue
      cExchangeDate
      cExchangeRate
      cRoutingAmount
      compYn
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
      groupArrangementCode
      groupArrangementDescription
      inactiveDate
      inheritAuthRatecodeYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      revenueYn
      routingAmount
      routingCovers
      routingPercent
      type
      updateDate
      updateUser
    }
    folioTypeDetails {
      allowCompressYn
      allowConvertYn
      allowCreditbillYn
      allowDifferenceProfile
      arfolioName
      associatedCreditFolioType
      clFlag
      columnSeparator
      compressYn
      convertFolioType
      correctionFolioYn
      correctionHeaderYn
      creditYN
      currencyActionId
      customOnProfAttributesYn
      dSI
      debitBillYN
      debitFlag
      deletedFlag
      depositFolioYn
      directBillYn
      documentCode
      fiscalPrintingYn
      fiscalProgramName
      fiscalYn
      folioName
      folioTypeCode
      guestType
      internalBillYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      localCurrFlag
      manualFolioPrintTask
      nameTaxType
      nationalityFlag
      organizationID
      originalFolioStayDetailsYN
      passerbyfolioName
      primaryKeyID
      printFolioYn
      property
      queueName
      rNAInsertDate
      rNAUpdateDate
      simpleFolioYn
      taxNoFlag
      trxServiceType
      workingDocsYn
    }
    folioTypeDetailDetails {
      code
      dSI
      deletedFlag
      description
      folioType
      group
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
    }
    bankAccountDetails {
      accountId
      accountNumber
      bankAcctType
      bankCode
      branchCode
      cExchangeDate
      cExchangeRate
      centralMinProcessingAmount
      checkReport
      checkSubLines
      currency
      currencyDescription
      dSI
      defaultYN
      defaultForCurrencyYN
      deletedFlag
      description
      editCheckNumberYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      lastExportDate
      lastExportedFile
      maxCheckNo
      minProcessingAmount
      nextCheckNumber
      onHold
      organizationID
      paidInAR
      paymentMethod
      positivePayExportYN
      potential
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      routingNumber
      sourceImportDir
      targetImportDir
      tax1099ReportYN
      toBePaid
      updateDate
      updateUser
      validateIATANumberYN
    }
    commissionDetails {
      amount
      basedOn
      cAmount
      cExchangeDate
      cExchangeRate
      cVatAmount
      centralCode
      centralCommissionDescription
      code
      commissionCalcRule
      commissionFlatPercentage
      commissionamount
      commissionid
      dSI
      defaultYN
      deletedFlag
      description
      holdARYN
      holdAlwaysYN
      holdPrepaidYN
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      masteralias
      organizationID
      perNight
      perNightAmount
      perStay
      perStayAmount
      primaryKeyID
      property
      repItem
      repItemName
      repItemOrderby
      repSellSequence
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sellSequence
      taxPercent
      updateDate
      updateUser
    }
    authorizerGroupDetails {
      code
      compAuthorizerGroupDescription
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      updateDate
      updateUser
    }
    authorizerGroupDetailDetails {
      arrangementId
      authGroupCode
      cCreditLimit
      cExchangeDate
      cExchangeRate
      cOccurrenceLimit
      centralTransactionCodes
      compRoutingCodes
      dSI
      dailyCreditLimit
      deletedFlag
      groupHeaderId
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      transactionCodes
      transferLimit
      updateDate
      updateUser
    }
    authorizerDetails {
      aRAccountNumber
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
      appPassword
      appUserDescription
      appUserId
      appUserType
      appUserUniq
      authHeaderId
      authorizerGroup
      authorizerId
      authorizerInactiveDate
      authorizerYn
      cCreditLimit
      cExchangeDate
      cExchangeRate
      cHourlyRate
      cOccurrenceLimit
      cWeeklySalary
      centralTransactionCodes
      chainCode
      comments
      compRoutingCodes
      dSI
      dailyCreditLimit
      dateHired
      defCashierId
      defaultForm
      defaultLanguage
      defaultMfnResort
      defaultReportgroup
      defaultResort
      defaultTerminal
      deletedFlag
      deptId
      description
      disabledUntil
      empExtension
      empPager
      empStatus
      employeeIncentiveNumber
      employeeNumber
      expiresOn
      firstName
      forcePasswordChangeYn
      fridayMax
      fridayMin
      generalFilepath
      graceLogin
      hireType
      hourlyRate
      hoursPerWeek
      inactiveDate
      inactiveFrom
      inactiveReasonCode
      inactiveTo
      insertDate
      insertUser
      internalYn
      isSuperuser
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopId
      lastLoggedResort
      lastLoggedTimestamp
      lastName
      leadAddress
      leadAddressDet
      leadComm
      lockoutDate
      loginAttempts
      loginCro
      loginDomain
      maleFemale
      maxCheckoutDays
      maxDaysAfterCo
      maxUserSessions
      mfnUserType
      mobileAlertsYn
      mondayMax
      mondayMin
      nCExchangeDate
      nCExchangeRate
      nDeletedFlag
      nInsertDate
      nInsertUser
      nUpdateDate
      nUpdateUser
      occurrenceLimit
      oraclePassword
      oracleUid
      oracleUser
      organizationID
      otMultiplier
      passwordChangeDays
      passwordLastChange
      personNameId
      preventAccountLockout
      primaryKeyID
      property
      propertyAccessYn
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rateType
      receiveBroadcastMsg
      rehireYn
      salaryInterval
      saturdayMax
      saturdayMin
      serviceRequestAlertsYn
      sfaName
      srepCode
      srepGroup
      sundayMax
      sundayMin
      termReason
      terminatedDate
      thursdayMax
      thursdayMin
      timezoneRegion
      title
      transactionCodes
      transferLimit
      tuesdayMax
      tuesdayMin
      updateDate
      updateUser
      userFilepath
      userGroupAdmin
      userIDCode
      userPbxId
      wednesdayMax
      wednesdayMin
      weekMax
      weekMin
      weeklySalary
      workPermitExpdate
      workPermitNo
    }
    bucketRedemptionCodeDetails {
      code
      dSI
      deletedFlag
      description
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      transactionCode
      updateDate
      updateUser
    }
    compRoutingCodeDetails {
      applyPerDayYN
      arrTaxTypeCode
      arrangementId
      bucketValue
      cExchangeDate
      cExchangeRate
      cRoutingAmount
      centralTransactionCodes
      code
      compYn
      dSI
      deletedFlag
      description
      eligibleYn
      exportBucketType
      friday
      inactiveDate
      inheritRateCodeYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      monday
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      revenueYn
      routingAmount
      routingCovers
      routingPercentage
      saturday
      sunday
      thursday
      transactionCodes
      tuesday
      type
      updateDate
      updateUser
      wednesday
    }
    compTransactionCodeDetails {
      aRNameId
      accountNumber
      accountingCode
      acctrecvprofileid
      adjTrxCode
      adjtranscodeid
      arrangeCode
      cDefaultPrice
      cExchangeDate
      cExchangeRate
      cExportBucket
      cMaxAmount
      cMinimumAmount
      cCCode
      cRSTaxDesc
      ccType
      centralCode
      centralDescription
      centralGroup
      centralSubgroup
      checkNumberMandatoryYN
      class1MandatoryYn
      class2MandatoryYn
      code
      commission
      compNightsYn
      compPaymentsYN
      compYn
      corpPropFlag
      corporateDescription
      currency
      dSI
      dailyPlanFolio
      dedOwnerRevenueYN
      defaultPrice
      deferredYn
      deletedFlag
      depositPostingOnlyYn
      depositType
      description
      eInvoiceYn
      expenseFolio
      exportBucket
      externalPaymentCode
      fiscalPaymentYn
      fiscalTrxCodeType
      foreignCurrencyID
      frequentFlyerYn
      generatesInclusiveYN
      group
      groupFolio
      groupPointsRedemptionYN
      inHouseDepositYN
      inHousePayYN
      inHouseSalesYN
      inactiveDate
      inactiveflag
      includeIn8300Yn
      includeInDepositCXLRuleYN
      indBilling
      indCash
      individualAr
      individualDepositYN
      insertDate
      insertUser
      internalDeletedflag
      internalYn
      isManualPostAllowed
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      manualPostCoversYn
      maximumAmount
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
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      resultIncludedInSumArray
      revenueBucketId
      revenueGroupId
      revenueGroupYN
      rnaInsertDate
      rnaUpdateDate
      rotationRevenueYN
      roundingFactorYN
      serviceRecoveryTrxCode
      subgroup
      taxCode
      tcBofInterface
      tcBofInterface2
      tcBofRefCode
      tcBofRefCode2
      tcResort2
      tcTransactionType
      tclCodeDfltCl1
      tclCodeDfltCl2
      transactionActionId
      transactionCodeResort
      transactionType
      transcodearrangementid
      transcodeid
      transgroupid
      transsubgroupid
      trxCodeDisplay
      trxCodeType
      trxServiceType
      trxTaxTypeCode
      upcCode
      updateDate
      updateUser
    }
    transactionCodeCompExternalReferenceDetails {
      associatedTransactionCode
      associatedTransactionDescription
      centralAssociatedTransactionCode
      centralAssociatedTransactionDescription
      compTrxCode
      dSI
      deletedFlag
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
    }
    codeGeneratesDetails {
      adjustmentType
      amount
      amountFromScheduleYn
      cAmount
      cExchangeDate
      cExchangeRate
      calculationSequence
      centralDescription
      centralGeneratedCode
      currency
      dSI
      deletedFlag
      description
      generateRules
      generatedBy
      generatedCode
      generatedPrintedOnFolioYn
      id
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      nameTaxType
      organizationID
      percentage
      percentageBaseCode
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      resultIncludedInSumArray
      roundingMethod
      seqBy
      stopDays
      subTotal1YN
      subTotal2YN
      subTotal3YN
      tcDsi
      tcGroup
      tcGroupGenerator
      tcOrganizationid
      tcSubgroup
      tcSubgroupGenerator
      tclCodeGenerator
      tcrType
      transactionCodeResort
      transactionCodeTrxCode
      trxCodeGenerator
      udfFunction
      udfInverse
      updateDate
      updateUser
      useTaxBracketYn
    }
    compTypeDetails {
      centralCode
      centralDescription
      centralSequence
      code
      dSI
      deletedFlag
      description
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
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
      updateDate
      updateUser
    }
    barScheduleDetails {
      dSI
      date
      dayOfWeek
      deletedFlag
      description
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      lengthOfStay
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      updateDate
      updateUser
    }
    cityTaxRangeDetails {
      amountFrom
      amountTo
      chainCode
      dSI
      deletedFlag
      insertDate
      insertUser
      intervalAmount
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      packageFormulaRangeId
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      recordType
      taxAmount
      taxPercentage
      taxRangeType
      updateDate
      updateUser
    }
    propertyDayTypeDetails {
      adder
      centralDayTypesCode
      centralSequence
      dSI
      dayTypesCode
      dayTypesDescription
      deletedFlag
      description
      displayColor
      dtRemarks
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      multiplier
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      repDtRemarks
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      updateDate
      updateUser
    }
    displaySetDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    propertyCalendarEventDetails {
      activeYN
      blackoutYn
      centralCode
      centralDescription
      centralSequence
      code
      dSI
      deletedFlag
      description
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      oRMSEventYN
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
      showInOperaYn
      updateDate
      updateUser
    }
    rateHurdlesDetails {
      actualRoomsSold
      amountOfHurdleRate
      cExchangeDate
      cExchangeRate
      cHurdle
      cORMSPriceRoomDelta
      centralRoomClass
      centralRoomClassDescription
      centralRoomType
      centralRoomTypeDescription
      centralYieldCategory
      centralYieldCategoryDescription
      dSI
      deletedflag
      delta
      hurdleDate
      hurdlerateid
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      lengthOfStay
      locationID
      maxRoomsSold
      organizationID
      overrideYN
      primaryKeyID
      property
      rnaInsertDate
      rnaUpdateDate
      roomCategoryLabel
      roomClass
      roomClassDescription
      roomType
      roomTypeDescription
      roomcategoryid
      roomsToSellBeforeDeltaIsApplied
      updateDate
      updateUser
      yieldCategory
      yieldCategoryDescription
      yieldcategoryid
      yieldmarkettype
    }
    productDetails {
      addtorateflag
      alternateCodes
      arrangementCode
      beginSellDate
      bookingDuration
      calculationRule
      cateringYn
      centralAlternateCodes
      centralPackage
      centralPackageGroupCode
      centralPackageGroupDescription
      centralPackageLoss
      centralPackageOverage
      centralPackageProfit
      centralTransactionCode
      currency
      dSI
      deletedFlag
      deliveryTimeReqrdYn
      description
      endSellDate
      externalLocked
      flexibleDurationYn
      forecastGroup
      forecastGroupCode
      forecastNextDayYN
      foreignCurrencyID
      formula
      genPlAtEodOfCoDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      inventoriedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      longInfo
      maxPersons
      minimumAdvBookDays
      organizationID
      outletCode
      overrideFixedRateYn
      package
      packageAllowanceYN
      packageDescription
      packageGroupCode
      packageGroupDescription
      packageLoss
      packageOverage
      packageOverageTaxInclusiveYN
      packageProfit
      pkgforecastgrpid
      postNextDayYN
      postingRhythm
      postingType
      primaryKeyID
      printseparateflag
      productid
      property
      redemptionproductflag
      repDescription
      repItem
      repItemName
      repItemOrderby
      repTrxCodeDesc
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sellSeparateYN
      sellowsflag
      shortDescription
      standardDuration
      standardPersons
      taxInclusiveYN
      ticketsYn
      transactionCode
      updateDate
      updateUser
      validEndTime
      validStartTime
    }
    itemPackageDetails {
      dSI
      deletedFlag
      description
      insertDate
      insertUser
      item
      itemId
      itemProdId
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      product
      property
      qunatity
      rNAInsertDate
      rNAUpdateDate
      updateDate
      updateUser
    }
    rateProductPriceDetails {
      allowanceAmount
      bucket2AllowanceAmount
      bucket2Price
      bucket3AllowanceAmount
      bucket3Price
      cAllowanceAmount
      cBucket2AllowanceAmount
      cBucket2Price
      cBucket3AllowanceAmount
      cBucket3Price
      cExchangeDate
      cExchangeRate
      cPrice
      dSI
      day1
      day2
      day3
      day4
      day5
      day6
      day7
      deletedFlag
      endDate
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      maximumGuests
      maximumNights
      minimumGuests
      minimumNights
      organizationID
      pointsRequired
      price
      primaryKeyID
      product
      property
      propertyRateProductDetailId
      rNAInsertDate
      rNAUpdateDate
      rateCode
      seasonCode
      startDate
      updateDate
      updateUser
    }
    packageForecastGroupDetails {
      activeYN
      code
      dSI
      deletedFlag
      description
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
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
      updateDate
      updateUser
    }
    promotionDetails {
      authorizerId
      bookingEndDate
      bookingStartDate
      category
      centralDescription
      chainCode
      checkInTime
      checkOutTime
      code
      couponExChars
      couponGenFormat
      couponGenOption
      couponLength
      couponPrefix
      couponSuffix
      dSI
      deletedflag
      description
      group
      idRequiredDescription
      idRequiredYN
      inactiveDate
      inactiveflag
      information
      insertDate
      insertUser
      instructions
      jRNUpdateDate
      jRNUpdateDateAndTime
      limitedTimePromotionYn
      locationID
      lockedByCode
      lockedByType
      longDescription
      mktgprogramid
      organizationID
      primaryKeyID
      promoSequenceId
      promotionid
      property
      repItem
      repItemName
      repUpdateDate
      reportingPromoSequenceId
      rnaInsertDate
      rnaUpdateDate
      setOrAccountFlag
      stayEndDate
      stayStartDate
      updateDate
      updateOutsideBookingDatesYN
      updateUser
      upgradeAllowedYN
      voucherBenefitCode
    }
    promotionRateDetails {
      chainCode
      code
      dSI
      deletedFlag
      description
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      promoCode
      property
      rNAInsertDate
      rNAUpdateDate
    }
    promotionCodeRoutingInstructionDetails {
      authorizerId
      authorizerName
      autoPopulateRoutingYn
      beginDate
      centralTransactionCodes
      chainCode
      comments
      compPreApprovalRequiredYn
      covers
      creditLimit
      dSI
      dailyYn
      deletedFlag
      endDate
      folioView
      friday
      membershipId
      monday
      organizationID
      percentage
      promoCode
      promptForAuthorizerYn
      property
      routingCodes
      saturday
      sunday
      thursday
      transactionCodes
      tuesday
      wednesday
    }
    rateCategoriesDetails {
      businessDate
      centralDescription
      centralRateCategory
      centralRateClass
      centralRateClassDescription
      centralSequence
      dSI
      deletedflag
      displayDefaultYn
      displaySet
      endDate
      exportBucketCode
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      primaryKeyID
      property
      rateCategory
      rateCategoryDescription
      rateClass
      rateClassDescription
      rateTier
      ratecategoryid
      ratetierid
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      updateDate
      updateUser
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
    creditCardTypesDetails {
      canDeleteYn
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      sequence
      updateDate
      updateUser
    }
    paymentMethodDetails {
      addressVerificationYn
      authAtCheckinYn
      authDuringStayYn
      authReversalYn
      authStlmtAtCheckOutYn
      autopayAtCheckinYn
      bonusCheckType
      calcPoints
      cardNumberLength
      cardPrefix
      cashSurchargeYn
      ccTrxFeePct
      ccTrxFeeThreshold
      centralPaymentMethod
      centralPaymentMethodDescription
      centralSequence
      chipPinYn
      code
      creditCardType
      creditLimit
      currencyCode
      cvv2CheckYn
      dSI
      deletedFlag
      description
      expirationRule
      extraPerc
      formatMask
      formula
      inactiveDate
      inactiveFlag
      insertDate
      insertUser
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      issueNumber
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastUsedDatetime
      locationId
      merchantNumber
      numberDigits
      numberPostYN
      organizationID
      paymentMethod
      paymentMethodDescription
      primaryKeyID
      printAuthReceiptYn
      promptAtCheckinYn
      property
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      reservationYN
      rnaInsertDate
      rnaUpdateDate
      sequence
      startDate
      tempFlag
      transactionCode
      trxUsage1
      trxUsage2
      updateDate
      updateUser
      validationRule
    }
    exportBucketCodeDetails {
      arrTaxTypeCode
      arrangementId
      bucketType
      bucketValue
      cExchangeDate
      cExchangeRate
      cRoutingAmount
      code
      compYn
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
      inactiveDate
      inheritAuthRatecodeYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      revenueBucketDescription
      revenueYn
      routingAmount
      routingCovers
      routingPercent
      type
      updateDate
      updateUser
    }
    transactionCodeArrangeDetailDetails {
      addTransactionYN
      arrangementId
      centralTransactionCode
      centralTransactionCodeDescription
      childArrangementId
      dSI
      deletedFlag
      description
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      transactionCode
      updateDate
      updateUser
    }
    exportBucketTypeDetails {
      code
      compYn
      dSI
      deletedFlag
      description
      fiscalYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      transactionCodeInMultiBucketsYN
      updateDate
      updateUser
    }
    routingCodeDetails {
      applyPerDayYN
      arrTaxTypeCode
      arrangementId
      bucketValue
      cExchangeDate
      cExchangeRate
      cRoutingAmount
      code
      compYn
      dSI
      deletedFlag
      description
      eligibleYn
      exportBucketType
      friday
      inactiveDate
      inheritAuthRatecodeYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      monday
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      revenueYn
      routingAmount
      routingCovers
      routingPercentage
      saturday
      sunday
      thursday
      tuesday
      type
      updateDate
      updateUser
      wednesday
    }
    transactionDiversionRuleDetails {
      basedOn
      calculation
      code
      complimentary
      dSI
      deletedFlag
      description
      diversionId
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      level
      membershipLevel
      membershipType
      minimumRequired
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      room
      ruleType
      sequence
      updateDate
      updateUser
      vIP
    }
    transactionDiversionRuleDetailsDetails {
      dSI
      deletedFlag
      diversionId
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      transactionCodes
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
    groupGeneratesDetails {
      adjustmentType
      amount
      amountFromScheduleYn
      cAmount
      cExchangeDate
      cExchangeRate
      calculationSequence
      centralDescription
      centralGeneratedCode
      currency
      dSI
      deletedFlag
      description
      generateRules
      generatedBy
      generatedCode
      generatedPrintedOnFolioYn
      id
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      nameTaxType
      organizationID
      percentage
      percentageBaseCode
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      resultIncludedInSumArray
      roundingMethod
      stopDays
      subTotal1YN
      subTotal2YN
      subTotal3YN
      tcGroup
      tcGroupGenerator
      tcSubgroup
      tcSubgroupGenerator
      tclCodeGenerator
      tcrType
      trxCodeGenerator
      udfFunction
      udfInverse
      updateDate
      updateUser
      useTaxBracketYn
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
    subgroupGeneratesDetails {
      adjustmentType
      amount
      amountFromScheduleYn
      cAmount
      cExchangeDate
      cExchangeRate
      calculationSequence
      centralDescription
      centralGeneratedCode
      currency
      dSI
      deletedFlag
      description
      generateRules
      generatedBy
      generatedCode
      generatedPrintedOnFolioYn
      id
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      nameTaxType
      organizationID
      percentage
      percentageBaseCode
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      resultIncludedInSumArray
      roundingMethod
      seqBy
      stopDays
      subTotal1YN
      subTotal2YN
      subTotal3YN
      tcDsi
      tcGroup
      tcGroupGenerator
      tcOrganizationid
      tcSubgroup
      tcSubgroupGenerator
      tcTcSubgroup
      tclCodeGenerator
      tcrType
      transactionCodeResort
      trxCodeGenerator
      udfFunction
      udfInverse
      updateDate
      updateUser
      useTaxBracketYn
    }
    propertyAlertDetails {
      code
      dSI
      deletedFlag
      description
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      propery
      rNAInsertDate
      rNAUpdateDate
      sequence
      updateDate
      updateUser
    }
    globalAlertsDetails {
      alertCode
      alertText
      area
      brandStayCnt
      comments
      conditions
      dSI
      deletedFlag
      department
      description
      emailAddress
      emailYn
      externalAlertId
      hasTagsYn
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      lastStayDate
      lastStayLocation
      locationID
      membershipAlertYn
      membershipCardNo
      orderBy
      organizationID
      pref1
      pref2
      pref3
      primaryKeyID
      printerYN
      printerName
      property
      propertyStayCnt
      propertyStayDate
      queryId
      rNAInsertDate
      rNAUpdateDate
      reportName
      reservationAlertId
      reservationNameId
      screenYN
      skipGuestOverviewYn
      smsNumber
      smsYn
      stopCheckInCheckOut
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
      updateDate
      updateUser
      validationOverridePermission
      valueRating
      vipStatus
      welcomeOfferCode
      welcomeOfferYn
    }
    blockCancellationCodeDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      lastUsedDatetime
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      tempFlag
      titleSuffix
      updateDate
      updateUser
    }
    salesEventDestinationDetails {
      businessTitle
      canDeleteYn
      cancellationDestination
      centralCancellationDestination
      centralCancellationDestinationDescription
      centralSequence
      chainCode
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      lastUsedDatetime
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      scdestinationid
      sequence
      tempFlag
      titleSuffix
      updateDate
      updateUser
    }
    lostBookingCodesDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      lastUsedDatetime
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      tempFlag
      titleSuffix
      updateDate
      updateUser
    }
    refusedBookingCodesDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      lastUsedDatetime
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      tempFlag
      titleSuffix
      updateDate
      updateUser
    }
    bookingMethodDetails {
      bookingmethodid
      businessTitle
      canDeleteYn
      centralDescription
      centralReservationMethod
      centralSequence
      chainCode
      comments
      dSI
      deletedflag
      description
      displayColor
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      reservationMethod
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    propertyCutoffScheduleDetails {
      code
      cutoffRooms2
      cutoffRooms3
      cutoffRooms4
      dSI
      daysPriorToArrival
      deletedFlag
      description
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rooms
      sell
      updateDate
      updateUser
      washByPercent
    }
    bookingStatusDetails {
      allowPickupYN
      bookingstatusid
      cateringStatusType
      cateringdeductinvflag
      centralDescription
      centralEventStatus
      centralSequence
      chainCode
      dSI
      deductinventoryflag
      defaultReservationType
      deletedflag
      description
      diaryYN
      displayColor
      fitStatusYn
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      leadStatusYn
      logCateringYn
      oRMSYN
      oldBlockStatus
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reasonType
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      returnInventoryYN
      roomStatusType
      sequence
      startingYN
      updateDate
      updateUser
    }
    cancelRuleDetails {
      allotmentHeaderId
      amount
      applyRuleTo
      beforeTime
      beginDate
      cCnclPenltyAmount
      cDepAmount
      cExchangeDate
      cExchangeRate
      code
      creditRating
      d1
      d2
      d3
      d4
      d5
      d6
      d7
      dSI
      daysBeforeArrival
      daysofweek
      deletedflag
      depositAmount
      depositAmountType
      depositDaysAfterBooking
      depositDaysPriorToArrival
      depositcancelruleid
      depositcancelrulepmsref
      depositorCancellationRule
      description
      endDate
      guaranteeClass
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      overrideYn
      parentRateDcSeq
      paymentRequired
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rateCodeDescription
      rateSetId
      repSeasonCode
      reservationType
      seasonCode
      sequence
      type
      updateDate
      updateUser
    }
    cancelRuleScheduleDetails {
      allotmentHeaderId
      applyRuleTo
      beginDate
      blockCode
      cCnclPenltyAmount
      cDepAmount
      cExchangeDate
      cExchangeRate
      canBeforeTime
      canDaysPriorToArrival
      canPenaltyAmount
      canPenaltyAmountType
      creditRating
      d1
      d2
      d3
      d4
      d5
      d6
      d7
      dSI
      daysofweek
      deletedflag
      depositAmount
      depositAmountType
      depositDaysAfterBooking
      depositDaysPriorToArrival
      depositcancelruleid
      depositcancelrulepmsref
      depositorCancellationRule
      endDate
      guaranteeClass
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      overrideYN
      parentRateDcSeq
      paymentRequired
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rateCodeDescription
      rateSetId
      repSeasonCode
      reservationType
      rule
      ruleDescription
      seasonCode
      sequence
      updateDate
      updateUser
    }
    depositRuleDetails {
      afterBooking
      allotmentHeaderId
      amount
      applyRuleTo
      beforeArrival
      beginDate
      cCnclPenltyAmount
      cDepAmount
      cExchangeDate
      cExchangeRate
      canBeforeTime
      canDaysPriorToArrival
      canPenaltyAmount
      canPenaltyAmountType
      creditRating
      d1
      d2
      d3
      d4
      d5
      d6
      d7
      dSI
      daysofweek
      deletedflag
      depositRule
      depositcancelruleid
      depositcancelrulepmsref
      depositorCancellationRule
      description
      endDate
      guaranteeClass
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      overrideYn
      parentRateDcSeq
      paymentRequired
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rateCodeDescription
      rateSetId
      repSeasonCode
      reservationType
      seasonCode
      sequence
      type
      updateDate
      updateUser
    }
    depositRuleScheduleDetails {
      allotmentHeaderId
      applyRuleTo
      beginDate
      blockCode
      cCnclPenltyAmount
      cDepAmount
      cExchangeDate
      cExchangeRate
      canBeforeTime
      canDaysPriorToArrival
      canPenaltyAmount
      canPenaltyAmountType
      creditRating
      d1
      d2
      d3
      d4
      d5
      d6
      d7
      dSI
      daysofweek
      deletedflag
      depositAmount
      depositAmountType
      depositDaysAfterBooking
      depositDaysPriorToArrival
      depositcancelruleid
      depositcancelrulepmsref
      depositorCancellationRule
      endDate
      guaranteeClass
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      overrideYN
      parentRateDcSeq
      paymentRequired
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rateCodeDescription
      rateSetId
      repSeasonCode
      reservationType
      rule
      ruleDescription
      seasonCode
      sequence
      updateDate
      updateUser
    }
    guaranteeDetails {
      addressYN
      arrivalYN
      autoCancelReservationYN
      bookingStatus
      bookingStatusOrder
      canDeleteYn
      cashBasisYn
      ccPendingDays
      ccVerifyCodeRequiredYn
      centralReservationType
      centralReservationTypeDescription
      closingProbability
      creditCardYN
      croAllowedYn
      dSI
      deletedFlag
      depositYN
      gDSShortDescription
      guaranteecodeid
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      internalDeletedflag
      internalYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      longDescription
      organizationID
      phoneYN
      primaryKeyID
      property
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      reservationType
      reservationTypeDescription
      reserveInventoryYn
      restrictedYn
      rnaInsertDate
      rnaUpdateDate
      sequence
      shortDescription
      updateDate
      updateUser
    }
    reservationTypeScheduleDetails {
      allotmentHeaderId
      applyRuleTo
      beginDate
      cCnclPenltyAmount
      cDepAmount
      cExchangeDate
      cExchangeRate
      canBeforeTime
      canDaysPriorToArrival
      canPenaltyAmount
      canPenaltyAmountType
      creditRating
      d1
      d2
      d3
      d4
      d5
      d6
      d7
      dSI
      daysofweek
      deletedflag
      depositAmount
      depositAmountType
      depositDaysAfterBooking
      depositDaysPriorToArrival
      depositcancelruleid
      depositcancelrulepmsref
      depositorCancellationRule
      description
      endDate
      guaranteeClass
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      orderBy
      organizationID
      overrideYN
      parentRateDcSeq
      paymentRequired
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      rateCodeDescription
      rateSetId
      repSeasonCode
      reservationType
      ruleCode
      ruledescription
      seasonCode
      updateDate
      updateUser
    }
    marketDetails {
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      dSI
      deletedFlag
      displayColor
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      marketCode
      marketDescription
      marketDisplaySequence
      marketGroupCode
      marketGroupDescription
      marketGroupDisplaySequence
      marketgroupid
      marketid
      organizationID
      primaryKeyID
      printGroup
      property
      repItem
      repItemName
      repItemOrderby
      repMarketSellSequence
      repParentSellSequence
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      scOrderby
      trxCode
      updateDate
      updateUser
    }
    marketGroupDetails {
      autoupgradeYn
      dSI
      deletedFlag
      description
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      marketGroup
      marketgroupid
      organizationID
      primaryKeyID
      property
      ranking
      repDescription
      repItem
      repItemName
      repItemOrderby
      repMarketGroup
      repSellSequence
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      scOrderBy
      sequence
      updateDate
      updateUser
    }
    propertyMarketingCityDetails {
      dSI
      deletedFlag
      description
      direction
      displaySeq
      distance
      distanceType
      drivingTime
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      marketingCity
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      regionCode
      updateDate
      updateUser
    }
    marketingRegionsDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      lastUsedDatetime
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      tempFlag
      titleSuffix
      updateDate
      updateUser
    }
    channelDetails {
      businessTitle
      canDeleteYn
      centralOriginCode
      centralOriginDescription
      centralSequence
      chainCode
      channelid
      comments
      dSI
      deletedFlag
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      masterSubKeywordYn
      organizationID
      originCode
      originDescription
      originDisplaySequence
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      titleSuffix
      updateDate
      updateUser
    }
    sellMessagesDetails {
      allotmentHeaderId
      beginDate
      blockCode
      centralRoomType
      chainCode
      dSI
      endDate
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      locationID
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      roomCategory
      roomType
      sellId
      sellMessage
      sequence
      stickyFlag
      updateDate
      updateUser
    }
    sourceTableDetails {
      centralSequence
      centralSourceCode
      centralSourceDescription
      centralSourceGroupCode
      centralSourceGroupDescription
      dSI
      deletedYn
      deletedflag
      inactiveDate
      inactiveFlagYN
      inactiveYn
      insertDate
      insertUser
      internetSalesYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      lastuseddatetime
      locationID
      organizationID
      parentsourceid
      primaryKeyID
      property
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      sourceCode
      sourceDescription
      sourceDisplaySequence
      sourceGroupCode
      sourceGroupDescription
      sourceGroupDisplaySequence
      sourceid
      tempYn
      updateDate
      updateUser
    }
    sourceGroupDetails {
      centralDescription
      centralSequence
      centralSourceGroup
      dSI
      deletedFlag
      description
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      internetSalesYn
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      parentSourceCode
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      scOrderby
      sequence
      sourceGroup
      updateDate
      updateUser
    }
    reservationAutoAttachRulesDetails {
      advancedYn
      basedOn
      code
      convertedToAdvancedYn
      dSI
      deletedFlag
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      keywordType
      level
      minAdults
      minChildren
      organizationID
      preference
      preferenceType
      primaryKeyID
      property
      queryId
      rNAInsertDate
      rNAUpdateDate
      rateCode
      roomCategory
      ruleType
      type
      updateDate
      updateUser
      vipStatus
    }
    reservationAutoAttachDetailsDetails {
      associatedCodes
      attachId
      dSI
      deletedFlag
      discountReasonCode
      insertDate
      insertUser
      itemId
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      preference
      preferenceType
      primaryKeyID
      product
      promoCode
      property
      rNAInsertDate
      rNAUpdateDate
      ruleCode
      traceDeptId
      traceText
      updateDate
      updateUser
    }
    cancellationCodesDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      lastUsedDatetime
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      tempFlag
      titleSuffix
      updateDate
      updateUser
    }
    entryPointDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      lastUsedDatetime
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      tempFlag
      titleSuffix
      updateDate
      updateUser
    }
    discountReasonDetails {
      advanceYN
      attributeCode
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    ecouponDetails {
      dSI
      defaultQuantity
      deletedFlag
      description
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      postingRoom
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      rateCode
      sequence
      updateDate
      updateUser
      welcomeOfferYn
      eCouponCode
    }
    propertyLocatorDetails {
      code
      dSI
      deletedFlag
      description
      inactiveDate
      inactiveYN
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      sequence
      updateDate
      updateUser
    }
    propertyMessageDetails {
      code
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      message
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      sequence
      updateDate
      updateUser
    }
    guestStatusDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      guestStatus
      gueststatusid
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      internalEntityname
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      statustype
      titleSuffix
      updateDate
      updateUser
    }
    guestTypeDetails {
      businessTitle
      canDeleteYn
      centralDescription
      centralGuestType
      centralSequence
      chainCode
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      guestType
      guesttypeid
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    immigrationStatusDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    preRegRulesDetails {
      allowRestrict
      beginDate
      chainCode
      dSI
      deletedFlag
      endDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ruleDetails
      ruleId
      ruleType
      ruleTypeDesc
      updateDate
      updateUser
    }
    itemClassDetails {
      bookableViaWebsiteYN
      centralDescription
      centralSequence
      code
      dSI
      deletedFlag
      description
      discountableYn
      eventTypes
      iconName
      inactiveDate
      itemclassId
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repOrderBy
      repUpdateDate
      reportingItemclassId
      reservationYN
      responsibleDepartment
      sequence
      usedInApp
    }
    itemInventoryDetails {
      activityExtSystem
      activityLinkYn
      activityLocationCode
      activityStatusCode
      activityType
      allowedOutsideStayYn
      availableFrom
      availableTo
      braceletRuleCode
      cCost
      cExchangeDate
      cExchangeRate
      centralDescription
      centralSequence
      cost
      criticalYn
      dSI
      dailyInventoryYn
      defaultDuration
      defaultQty
      deletedFlag
      description
      discountableYN
      displayColor
      externalYN
      inactiveDate
      insertDate
      insertUser
      itemClass
      itemCode
      itemId
      itemPoolId
      itemclassId
      jRNUpdateDate
      jRNUpdateDateAndTime
      mandatoryYn
      objectType
      organizationID
      primaryKeyID
      promptFixedChargesYn
      property
      quantityInStock
      quickInsert
      rNAInsertDate
      rNAUpdateDate
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      reportingItemId
      revType
      revenueType
      sellSeparate
      sequence
      setdownTime
      setupTime
      showbeoYn
      updateDate
      updateUser
      webBookingYn
      welcomeOfferYn
    }
    itemPoolDetails {
      code
      dSI
      deletedFlag
      description
      insertTs
      insertUser
      itemClass
      itemPoolId
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      sequence
      updateTs
      updateUser
    }
    birthCountryDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    propertyCountryDetails {
      addressdoctorMode
      canDeleteYn
      chainCode
      countryCode
      countryMainGroup
      countryName
      dSI
      deletedFlag
      displayCountryFlagYN
      guestAddressFormat
      iSOCode
      iSOName
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      name
      organizationID
      primaryKeyID
      property
      propertyAddressFormat
      rNAInsertDate
      rNAUpdateDate
      region
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      reportSequence
      sequence
      statisticsCode
      status
      updateDate
      updateUser
    }
    countryGroupDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      comments
      countryGroup
      countryGroupCode
      countrygroupid
      dSI
      deletedFlag
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    distanceTypeDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    districtDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    fiscalGuestTypeDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    fiscalRegionDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    profileIDCountryDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    nationalityDetails {
      businessTitle
      canDeleteYn
      centralDescription
      centralNationalityCode
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalDeletedflag
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      nationalityid
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    qualifyingRatesDetails {
      aSBRateCycle
      addition
      advBaseRateCode
      advBaseRounding
      advanceBaseCompareYN
      advanceBooking
      advanceDailyBaseYN
      advanceDailyRateYN
      alternateRateCode
      availabilityUpdateYn
      backToBackYn
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
      beginBookingDate
      breakfastInclYn
      breakfastPrice
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
      changeState
      closedToArrival
      commissionCode
      commissionPct
      commissionYn
      commissionablePerc
      commissionableYn
      complimentaryYn
      currCodeDecimalPos
      currencyCode
      dSI
      dailyRatesYn
      dayuseYn
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
      description
      discountRateAmount
      discountRatePercentageYn
      discountYn
      displayRegionalYn
      displaySet
      distributeYn
      doubleRoomSupplementYN
      endBookingDate
      exchangePostingType
      externalLocked
      extraPersonChargeBegins
      fitDiscountLevel
      fitDiscountPerc
      flatOrPercentage
      folioText
      gDSAllowedYn
      groupCode
      highlightRateAmountYn
      houseUseYn
      inactiveDate
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      label
      longInfo
      losUnit
      loyaltyProgramYn
      mandateResvProfiles
      marketCode
      marshaRateProgram
      maxAdvanceBooking
      maxLos
      maxOccupancy
      mfnUploadYn
      minOccupancy
      mobileCheckinAllowedYn
      mobileChkoutAllowed
      multiplication
      negotiated
      occupancyBasedYn
      occupancyLevel
      operatorType
      orderBy
      organizationID
      orsSellSequence
      overridePackageYn
      ownerRateYn
      packageTransactionTaxInclYN
      packageTransactionWkTaxInclYN
      packageTrxCode
      packageTrxCodeWk
      packageYn
      pendingApprovalYn
      postingRhythm
      postingRhythmNights
      primaryKeyID
      printRateYn
      privilegedRestrictionYn
      privilegedYn
      profitTrxCode
      property
      qualifying
      rNAInsertDate
      rNAUpdateDate
      rankAdjustmentFactor
      rankValue
      rateBucket
      rateCalendarYn
      rateCategories
      rateClass
      rateCodeLocked
      rateCodes
      rateFloor
      rateFloorOverrideYn
      rateIncludesTaxYn
      rateLevel
      rateinfoUrl
      ratesToGDSYn
      redemptionRateYn
      repeatPostingRhythmYn
      rodBaseAmount
      rodBaseFltPct
      rodBaseRounding
      rodBasedYn
      rodYn
      roomAssignmentValue
      sdowBeginBookingDate
      sdowEndBookingDate
      sellSequence
      serviceInclYn
      servicePerc
      shortInfo
      showRateAmountYn
      sourceCode
      taxIncludedPerc
      taxIncludedYn
      tieredYn
      transactionTaxInclYN
      transactionWkTaxInclYN
      trxCode
      trxCodeWk
      updateDate
      updateUser
      upsellYn
      voucherBenefitRateYn
      weekendDays
      wkDeptCode
      yieldAs
      yieldableYn
      ymCode
    }
    membershipStatusDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    priorityDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveFlag
      insertDate
      insertUser
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      lastUsedDatetime
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      priorityId
      priorityType
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      tempFlag
      titleSuffix
      updateDate
      updateUser
    }
    entityAccountTypeDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    addressTypeDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    alternateLanguageTitleDetails {
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      displayColor
      entityName
      envelopeGreeting
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      language
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      salutation
      sequence
      titleNumber
      updateDate
      updateUser
    }
    roomsPotentialDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveFlag
      insertDate
      insertUser
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      lastUsedDatetime
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      roomsPotentialType
      sequence
      tempFlag
      titleSuffix
      updateDate
      updateUser
    }
    businessSegmentDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    companyTypeDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    competitionDetails {
      attributeCode
      businessTitle
      canDeleteYn
      centralCompetition
      centralDescription
      centralSequence
      chainCode
      code
      comments
      competition
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveFlag
      insertDate
      insertUser
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      lastUsedDatetime
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      tempFlag
      titleSuffix
      updateDate
      updateUser
    }
    genderDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    profileInactiveReasonDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    industryCodeDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    influenceCodeDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    keywordTypeDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    mailingActionDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedFlag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveFlag
      insertDate
      insertUser
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      lastUsedDatetime
      locationID
      mailingActionType
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      rnaInsertDate
      rnaUpdateDate
      sequence
      tempFlag
      titleSuffix
      updateDate
      updateUser
    }
    preferenceDetails {
      amenityYn
      cExchangeDate
      cExchangeRate
      cRoomAssignmentValue
      cRSPreferenceYn
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      corporateYn
      dSI
      deletedFlag
      description1
      housekeepingYn
      inactiveDate
      inactiveFlag
      insertDate
      insertUser
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationId
      organizationID
      owsAllowedYN
      preferenceAttribute
      preferenceCode
      preferenceDescription
      preferenceGroup
      preferenceId
      preferenceSubType
      preference1
      primaryKeyID
      property
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      reportingPreferenceSequenceId
      rnaInsertDate
      rnaUpdateDate
      roomAssignmentValue
      sendDeleteRequestYn
      sequence
      source
      updateDate
      updateUser
    }
    profileRestrictionReasonDetails {
      businessTitle
      canDeleteYn
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repAttributeCode
      repDescription
      repItem
      repItemName
      repItemOrderby
      repOrderBy
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    salesEventScopeDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    salesEventScopeCityDetails {
      businessTitle
      canDeleteYn
      centralCode
      centralDescription
      centralSequence
      chainCode
      code
      comments
      dSI
      deletedflag
      description
      displayColor
      entityName
      externalAttributeCodes
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      languageCode
      locationID
      masterSubKeywordYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      ranking
      repItem
      repItemName
      repItemOrderby
      repUpdateDate
      sequence
      titleSuffix
      updateDate
      updateUser
    }
    membershipClaimAdjustmentLimitDetails {
      adjustmentLimitCode
      awardLowerLimit
      awardUpperLimit
      billingGroup
      chainCode
      dSI
      deletedFlag
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      tierNightsLowerLimit
      tierNightsUpperLimit
      tierRevenueLowerLimit
      tierRevenueUpperLimit
      tierStaysLowerLimit
      tierStaysUpperLimit
      updateDate
      updateUser
    }
  }
}
```