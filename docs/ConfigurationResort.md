# ConfigurationResort
[📦 Object Types](#object-types) | [📥 Input Types](#input-types) | [📝 Query Template](#query-template) | [🗄️ Parquet Schema](#parquet-schema)
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

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | propertyPropertyDetails | [`ConfigurationResortPropertyPropertyDetailsType`](#configurationresortpropertypropertydetailstype) | Resort Details |
| 2 | membershipClaimOriginDetails | [`ConfigurationResortMembershipClaimOriginDetailsType`](#configurationresortmembershipclaimorigindetailstype) | Membership Claim Origin |
| 3 | membershipPointsDetails | [`ConfigurationResortMembershipPointsDetailsType`](#configurationresortmembershippointsdetailstype) | Membership Points |
| 4 | membershipAwardRatesDetails | [`ConfigurationResortMembershipAwardRatesDetailsType`](#configurationresortmembershipawardratesdetailstype) | Membership Award Rates |
| 5 | membershipAwardProductsDetails | [`ConfigurationResortMembershipAwardProductsDetailsType`](#configurationresortmembershipawardproductsdetailstype) | Membership Award Products |
| 6 | membershipAwardUpgradesDetails | [`ConfigurationResortMembershipAwardUpgradesDetailsType`](#configurationresortmembershipawardupgradesdetailstype) | Membership Award Upgrades |
| 7 | membershipAwardFinancialTransactionDetails | [`ConfigurationResortMembershipAwardFinancialTransactionDetailsType`](#configurationresortmembershipawardfinancialtransactiondetailstype) | Membership Award Financial Transaction |
| 8 | membershipPropertyGroupCodeDetails | [`ConfigurationResortMembershipPropertyGroupCodeDetailsType`](#configurationresortmembershippropertygroupcodedetailstype) | Membership Property Group Code |
| 9 | airportDetails | [`ConfigurationResortAirportDetailsType`](#configurationresortairportdetailstype) | Airport Details |
| 10 | featureDetails | [`ConfigurationResortFeatureDetailsType`](#configurationresortfeaturedetailstype) | Feature Details |
| 11 | attractionCategoryDetails | [`ConfigurationResortAttractionCategoryDetailsType`](#configurationresortattractioncategorydetailstype) | Attraction Category Details |
| 12 | attractionDetails | [`ConfigurationResortAttractionDetailsType`](#configurationresortattractiondetailstype) | Attraction Details |
| 13 | chainDetails | [`ConfigurationResortChainDetailsType`](#configurationresortchaindetailstype) | Chain Details |
| 14 | closingScriptDetails | [`ConfigurationResortClosingScriptDetailsType`](#configurationresortclosingscriptdetailstype) | Closing Script Details |
| 15 | communicationMethodDetails | [`ConfigurationResortCommunicationMethodDetailsType`](#configurationresortcommunicationmethoddetailstype) | Communication Method Details |
| 16 | deliveryStatusDetails | [`ConfigurationResortDeliveryStatusDetailsType`](#configurationresortdeliverystatusdetailstype) | Delivery Status Details |
| 17 | departmentDetails | [`ConfigurationResortDepartmentDetailsType`](#configurationresortdepartmentdetailstype) | Department Details |
| 18 | elecRegCardScriptDetails | [`ConfigurationResortElecRegCardScriptDetailsType`](#configurationresortelecregcardscriptdetailstype) | Elec Reg Card Script Details |
| 19 | hubPropertyDetails | [`ConfigurationResortHubPropertyDetailsType`](#configurationresorthubpropertydetailstype) | Hub Property |
| 20 | jobTitleDetails | [`ConfigurationResortJobTitleDetailsType`](#configurationresortjobtitledetailstype) | Job Title Details |
| 21 | uDFCategoryDetails | [`ConfigurationResortUDFCategoryDetailsType`](#configurationresortudfcategorydetailstype) | UDF Category |
| 22 | uDFTypeDetails | [`ConfigurationResortUDFTypeDetailsType`](#configurationresortudftypedetailstype) | UDF Type |
| 23 | brandCodeDetails | [`ConfigurationResortBrandCodeDetailsType`](#configurationresortbrandcodedetailstype) | Brand Code Details |
| 24 | businessUnitDetails | [`ConfigurationResortBusinessUnitDetailsType`](#configurationresortbusinessunitdetailstype) | Business Unit Details |
| 25 | departmentCodeDetails | [`ConfigurationResortDepartmentCodeDetailsType`](#configurationresortdepartmentcodedetailstype) | Department Code Details |
| 26 | divisionDetails | [`ConfigurationResortDivisionDetailsType`](#configurationresortdivisiondetailstype) | Division Details |
| 27 | hotelCategoryDetails | [`ConfigurationResortHotelCategoryDetailsType`](#configurationresorthotelcategorydetailstype) | Hotel Category Details |
| 28 | operatingUnitDetails | [`ConfigurationResortOperatingUnitDetailsType`](#configurationresortoperatingunitdetailstype) | Operating Unit Details |
| 29 | applicationParameterValueDetails | [`ConfigurationResortApplicationParameterValueDetailsType`](#configurationresortapplicationparametervaluedetailstype) | Application Parameter Value Details |
| 30 | trackitActionDetails | [`ConfigurationResortTrackitActionDetailsType`](#configurationresorttrackitactiondetailstype) | Trackit Action Details |
| 31 | trackitLocationDetails | [`ConfigurationResortTrackitLocationDetailsType`](#configurationresorttrackitlocationdetailstype) | Trackit Location Details |
| 32 | trackitTypeDetails | [`ConfigurationResortTrackitTypeDetailsType`](#configurationresorttrackittypedetailstype) | Trackit Type Details |
| 33 | accountTypeDetails | [`ConfigurationResortAccountTypeDetailsType`](#configurationresortaccounttypedetailstype) | Account Type Details |
| 34 | aRReminderCycleDetails | [`ConfigurationResortARReminderCycleDetailsType`](#configurationresortarremindercycledetailstype) | AR Reminder Cycle |
| 35 | acctFlagReasonDetails | [`ConfigurationResortAcctFlagReasonDetailsType`](#configurationresortacctflagreasondetailstype) | Acct Flag Reason Details |
| 36 | transactionReasonCodeDetails | [`ConfigurationResortTransactionReasonCodeDetailsType`](#configurationresorttransactionreasoncodedetailstype) | Transaction Reason Code |
| 37 | creditCardAuthorizationRulesDetails | [`ConfigurationResortCreditCardAuthorizationRulesDetailsType`](#configurationresortcreditcardauthorizationrulesdetailstype) | Credit Card Authorization Rules |
| 38 | autoFolioSettlementTypeDetails | [`ConfigurationResortAutoFolioSettlementTypeDetailsType`](#configurationresortautofoliosettlementtypedetailstype) | Auto Folio Settlement Type Details |
| 39 | cashierDetails | [`ConfigurationResortCashierDetailsType`](#configurationresortcashierdetailstype) | Cashier Details |
| 40 | customNumberDetails | [`ConfigurationResortCustomNumberDetailsType`](#configurationresortcustomnumberdetailstype) | Custom Number Details |
| 41 | currencyExchangeTaxDetails | [`ConfigurationResortCurrencyExchangeTaxDetailsType`](#configurationresortcurrencyexchangetaxdetailstype) | Currency Exchange Tax Details |
| 42 | expenseArrangementCodeDetails | [`ConfigurationResortExpenseArrangementCodeDetailsType`](#configurationresortexpensearrangementcodedetailstype) | Expense Arrangement Code Details |
| 43 | transactionCodeDetails | [`ConfigurationResortTransactionCodeDetailsType`](#configurationresorttransactioncodedetailstype) | Transaction Code |
| 44 | folioArrangementCodeDetails | [`ConfigurationResortFolioArrangementCodeDetailsType`](#configurationresortfolioarrangementcodedetailstype) | Folio Arrangement Code Details |
| 45 | groupArrangementCodeDetails | [`ConfigurationResortGroupArrangementCodeDetailsType`](#configurationresortgrouparrangementcodedetailstype) | Group Arrangement Code Details |
| 46 | folioTypeDetails | [`ConfigurationResortFolioTypeDetailsType`](#configurationresortfoliotypedetailstype) | Folio Type Details |
| 47 | folioTypeDetailDetails | [`ConfigurationResortFolioTypeDetailDetailsType`](#configurationresortfoliotypedetaildetailstype) | Folio Type Detail Details |
| 48 | bankAccountDetails | [`ConfigurationResortBankAccountDetailsType`](#configurationresortbankaccountdetailstype) | Bank Account Details |
| 49 | commissionDetails | [`ConfigurationResortCommissionDetailsType`](#configurationresortcommissiondetailstype) | Commission Details |
| 50 | authorizerGroupDetails | [`ConfigurationResortAuthorizerGroupDetailsType`](#configurationresortauthorizergroupdetailstype) | Authorizer Group Details |
| 51 | authorizerGroupDetailDetails | [`ConfigurationResortAuthorizerGroupDetailDetailsType`](#configurationresortauthorizergroupdetaildetailstype) | Authorizer Group Detail Details |
| 52 | authorizerDetails | [`ConfigurationResortAuthorizerDetailsType`](#configurationresortauthorizerdetailstype) | Authorizer Details |
| 53 | bucketRedemptionCodeDetails | [`ConfigurationResortBucketRedemptionCodeDetailsType`](#configurationresortbucketredemptioncodedetailstype) | Bucket Redemption Code Details |
| 54 | compRoutingCodeDetails | [`ConfigurationResortCompRoutingCodeDetailsType`](#configurationresortcomproutingcodedetailstype) | Comp Routing Code Details |
| 55 | compTransactionCodeDetails | [`ConfigurationResortCompTransactionCodeDetailsType`](#configurationresortcomptransactioncodedetailstype) | Comp Transaction Code |
| 56 | transactionCodeCompExternalReferenceDetails | [`ConfigurationResortTransactionCodeCompExternalReferenceDetailsType`](#configurationresorttransactioncodecompexternalreferencedetailstype) | Transaction Code Comp External Reference |
| 57 | codeGeneratesDetails | [`ConfigurationResortCodeGeneratesDetailsType`](#configurationresortcodegeneratesdetailstype) | Code Generates Details |
| 58 | compTypeDetails | [`ConfigurationResortCompTypeDetailsType`](#configurationresortcomptypedetailstype) | Comp Type Details |
| 59 | barScheduleDetails | [`ConfigurationResortBarScheduleDetailsType`](#configurationresortbarscheduledetailstype) | Bar Schedule Details |
| 60 | cityTaxRangeDetails | [`ConfigurationResortCityTaxRangeDetailsType`](#configurationresortcitytaxrangedetailstype) | City Tax Range Details |
| 61 | propertyDayTypeDetails | [`ConfigurationResortPropertyDayTypeDetailsType`](#configurationresortpropertydaytypedetailstype) | Property Day Type |
| 62 | displaySetDetails | [`ConfigurationResortDisplaySetDetailsType`](#configurationresortdisplaysetdetailstype) | Display Set Details |
| 63 | propertyCalendarEventDetails | [`ConfigurationResortPropertyCalendarEventDetailsType`](#configurationresortpropertycalendareventdetailstype) | Property Calendar Event |
| 64 | rateHurdlesDetails | [`ConfigurationResortRateHurdlesDetailsType`](#configurationresortratehurdlesdetailstype) | Rate Hurdles Details |
| 65 | productDetails | [`ConfigurationResortProductDetailsType`](#configurationresortproductdetailstype) | Product Details |
| 66 | itemPackageDetails | [`ConfigurationResortItemPackageDetailsType`](#configurationresortitempackagedetailstype) | Item Package Details |
| 67 | rateProductPriceDetails | [`ConfigurationResortRateProductPriceDetailsType`](#configurationresortrateproductpricedetailstype) | Rate Product Price Details |
| 68 | packageForecastGroupDetails | [`ConfigurationResortPackageForecastGroupDetailsType`](#configurationresortpackageforecastgroupdetailstype) | Package Forecast Group |
| 69 | promotionDetails | [`ConfigurationResortPromotionDetailsType`](#configurationresortpromotiondetailstype) | Promotion Details |
| 70 | promotionRateDetails | [`ConfigurationResortPromotionRateDetailsType`](#configurationresortpromotionratedetailstype) | Promotion Rate |
| 71 | promotionCodeRoutingInstructionDetails | [`ConfigurationResortPromotionCodeRoutingInstructionDetailsType`](#configurationresortpromotioncoderoutinginstructiondetailstype) | Promotion Code Routing Instruction |
| 72 | rateCategoriesDetails | [`ConfigurationResortRateCategoriesDetailsType`](#configurationresortratecategoriesdetailstype) | Rate Categories Details |
| 73 | articleDetails | [`ConfigurationResortArticleDetailsType`](#configurationresortarticledetailstype) | Article Details |
| 74 | creditCardTypesDetails | [`ConfigurationResortCreditCardTypesDetailsType`](#configurationresortcreditcardtypesdetailstype) | Credit Card Types Details |
| 75 | paymentMethodDetails | [`ConfigurationResortPaymentMethodDetailsType`](#configurationresortpaymentmethoddetailstype) | Payment Method Details |
| 76 | exportBucketCodeDetails | [`ConfigurationResortExportBucketCodeDetailsType`](#configurationresortexportbucketcodedetailstype) | Export Bucket Code Details |
| 77 | transactionCodeArrangeDetailDetails | [`ConfigurationResortTransactionCodeArrangeDetailDetailsType`](#configurationresorttransactioncodearrangedetaildetailstype) | Transaction Code Arrange Detail |
| 78 | exportBucketTypeDetails | [`ConfigurationResortExportBucketTypeDetailsType`](#configurationresortexportbuckettypedetailstype) | Export Bucket Type Details |
| 79 | routingCodeDetails | [`ConfigurationResortRoutingCodeDetailsType`](#configurationresortroutingcodedetailstype) | Routing Code Details |
| 80 | transactionDiversionRuleDetails | [`ConfigurationResortTransactionDiversionRuleDetailsType`](#configurationresorttransactiondiversionruledetailstype) | Transaction Diversion Rule |
| 81 | transactionDiversionRuleDetailsDetails | [`ConfigurationResortTransactionDiversionRuleDetailsDetailsType`](#configurationresorttransactiondiversionruledetailsdetailstype) | Transaction Diversion Rule Details |
| 82 | transactionGroupDetails | [`ConfigurationResortTransactionGroupDetailsType`](#configurationresorttransactiongroupdetailstype) | Transaction Group |
| 83 | groupGeneratesDetails | [`ConfigurationResortGroupGeneratesDetailsType`](#configurationresortgroupgeneratesdetailstype) | Group Generates Details |
| 84 | transactionSubgroupDetails | [`ConfigurationResortTransactionSubgroupDetailsType`](#configurationresorttransactionsubgroupdetailstype) | Transaction Subgroup |
| 85 | subgroupGeneratesDetails | [`ConfigurationResortSubgroupGeneratesDetailsType`](#configurationresortsubgroupgeneratesdetailstype) | Subgroup Generates Details |
| 86 | propertyAlertDetails | [`ConfigurationResortPropertyAlertDetailsType`](#configurationresortpropertyalertdetailstype) | Property Alert |
| 87 | globalAlertsDetails | [`ConfigurationResortGlobalAlertsDetailsType`](#configurationresortglobalalertsdetailstype) | Global Alerts Details |
| 88 | blockCancellationCodeDetails | [`ConfigurationResortBlockCancellationCodeDetailsType`](#configurationresortblockcancellationcodedetailstype) | Block Cancellation Code Details |
| 89 | salesEventDestinationDetails | [`ConfigurationResortSalesEventDestinationDetailsType`](#configurationresortsaleseventdestinationdetailstype) | Sales Event Destination |
| 90 | lostBookingCodesDetails | [`ConfigurationResortLostBookingCodesDetailsType`](#configurationresortlostbookingcodesdetailstype) | Lost Booking Codes Details |
| 91 | refusedBookingCodesDetails | [`ConfigurationResortRefusedBookingCodesDetailsType`](#configurationresortrefusedbookingcodesdetailstype) | Refused Booking Codes Details |
| 92 | bookingMethodDetails | [`ConfigurationResortBookingMethodDetailsType`](#configurationresortbookingmethoddetailstype) | Booking Method Details |
| 93 | propertyCutoffScheduleDetails | [`ConfigurationResortPropertyCutoffScheduleDetailsType`](#configurationresortpropertycutoffscheduledetailstype) | Property Cutoff Schedule |
| 94 | bookingStatusDetails | [`ConfigurationResortBookingStatusDetailsType`](#configurationresortbookingstatusdetailstype) | Booking Status Details |
| 95 | cancelRuleDetails | [`ConfigurationResortCancelRuleDetailsType`](#configurationresortcancelruledetailstype) | Cancel Rule Details |
| 96 | cancelRuleScheduleDetails | [`ConfigurationResortCancelRuleScheduleDetailsType`](#configurationresortcancelrulescheduledetailstype) | Cancel Rule Schedule Details |
| 97 | depositRuleDetails | [`ConfigurationResortDepositRuleDetailsType`](#configurationresortdepositruledetailstype) | Deposit Rule Details |
| 98 | depositRuleScheduleDetails | [`ConfigurationResortDepositRuleScheduleDetailsType`](#configurationresortdepositrulescheduledetailstype) | Deposit Rule Schedule Details |
| 99 | guaranteeDetails | [`ConfigurationResortGuaranteeDetailsType`](#configurationresortguaranteedetailstype) | Guarantee Details |
| 100 | reservationTypeScheduleDetails | [`ConfigurationResortReservationTypeScheduleDetailsType`](#configurationresortreservationtypescheduledetailstype) | Reservation Type Schedule Details |
| 101 | marketDetails | [`ConfigurationResortMarketDetailsType`](#configurationresortmarketdetailstype) | Market Details |
| 102 | marketGroupDetails | [`ConfigurationResortMarketGroupDetailsType`](#configurationresortmarketgroupdetailstype) | Market Group Details |
| 103 | propertyMarketingCityDetails | [`ConfigurationResortPropertyMarketingCityDetailsType`](#configurationresortpropertymarketingcitydetailstype) | Property Marketing City |
| 104 | marketingRegionsDetails | [`ConfigurationResortMarketingRegionsDetailsType`](#configurationresortmarketingregionsdetailstype) | Marketing Regions Details |
| 105 | channelDetails | [`ConfigurationResortChannelDetailsType`](#configurationresortchanneldetailstype) | Channel Details |
| 106 | sellMessagesDetails | [`ConfigurationResortSellMessagesDetailsType`](#configurationresortsellmessagesdetailstype) | Sell Messages Details |
| 107 | sourceTableDetails | [`ConfigurationResortSourceTableDetailsType`](#configurationresortsourcetabledetailstype) | Source Table Details |
| 108 | sourceGroupDetails | [`ConfigurationResortSourceGroupDetailsType`](#configurationresortsourcegroupdetailstype) | Source Group Details |
| 109 | reservationAutoAttachRulesDetails | [`ConfigurationResortReservationAutoAttachRulesDetailsType`](#configurationresortreservationautoattachrulesdetailstype) | Reservation Auto Attach Rules |
| 110 | reservationAutoAttachDetailsDetails | [`ConfigurationResortReservationAutoAttachDetailsDetailsType`](#configurationresortreservationautoattachdetailsdetailstype) | Reservation Auto Attach Details |
| 111 | cancellationCodesDetails | [`ConfigurationResortCancellationCodesDetailsType`](#configurationresortcancellationcodesdetailstype) | Cancellation Codes Details |
| 112 | entryPointDetails | [`ConfigurationResortEntryPointDetailsType`](#configurationresortentrypointdetailstype) | Entry Point Details |
| 113 | discountReasonDetails | [`ConfigurationResortDiscountReasonDetailsType`](#configurationresortdiscountreasondetailstype) | Discount Reason Details |
| 114 | ecouponDetails | [`ConfigurationResortEcouponDetailsType`](#configurationresortecoupondetailstype) | Ecoupon Details |
| 115 | propertyLocatorDetails | [`ConfigurationResortPropertyLocatorDetailsType`](#configurationresortpropertylocatordetailstype) | Property Locator |
| 116 | propertyMessageDetails | [`ConfigurationResortPropertyMessageDetailsType`](#configurationresortpropertymessagedetailstype) | Property Message |
| 117 | guestStatusDetails | [`ConfigurationResortGuestStatusDetailsType`](#configurationresortgueststatusdetailstype) | Guest Status Details |
| 118 | guestTypeDetails | [`ConfigurationResortGuestTypeDetailsType`](#configurationresortguesttypedetailstype) | Guest Type Details |
| 119 | immigrationStatusDetails | [`ConfigurationResortImmigrationStatusDetailsType`](#configurationresortimmigrationstatusdetailstype) | Immigration Status Details |
| 120 | preRegRulesDetails | [`ConfigurationResortPreRegRulesDetailsType`](#configurationresortpreregrulesdetailstype) | Pre Reg Rules Details |
| 121 | itemClassDetails | [`ConfigurationResortItemClassDetailsType`](#configurationresortitemclassdetailstype) | Item Class Details |
| 122 | itemInventoryDetails | [`ConfigurationResortItemInventoryDetailsType`](#configurationresortiteminventorydetailstype) | Item Inventory Details |
| 123 | itemPoolDetails | [`ConfigurationResortItemPoolDetailsType`](#configurationresortitempooldetailstype) | Item Pool Details |
| 124 | birthCountryDetails | [`ConfigurationResortBirthCountryDetailsType`](#configurationresortbirthcountrydetailstype) | Birth Country Details |
| 125 | propertyCountryDetails | [`ConfigurationResortPropertyCountryDetailsType`](#configurationresortpropertycountrydetailstype) | Property Country |
| 126 | countryGroupDetails | [`ConfigurationResortCountryGroupDetailsType`](#configurationresortcountrygroupdetailstype) | Country Group Details |
| 127 | distanceTypeDetails | [`ConfigurationResortDistanceTypeDetailsType`](#configurationresortdistancetypedetailstype) | Distance Type Details |
| 128 | districtDetails | [`ConfigurationResortDistrictDetailsType`](#configurationresortdistrictdetailstype) | District Details |
| 129 | fiscalGuestTypeDetails | [`ConfigurationResortFiscalGuestTypeDetailsType`](#configurationresortfiscalguesttypedetailstype) | Fiscal Guest Type Details |
| 130 | fiscalRegionDetails | [`ConfigurationResortFiscalRegionDetailsType`](#configurationresortfiscalregiondetailstype) | Fiscal Region Details |
| 131 | profileIDCountryDetails | [`ConfigurationResortProfileIDCountryDetailsType`](#configurationresortprofileidcountrydetailstype) | Profile ID Country |
| 132 | nationalityDetails | [`ConfigurationResortNationalityDetailsType`](#configurationresortnationalitydetailstype) | Nationality Details |
| 133 | qualifyingRatesDetails | [`ConfigurationResortQualifyingRatesDetailsType`](#configurationresortqualifyingratesdetailstype) | Qualifying Rates Details |
| 134 | membershipStatusDetails | [`ConfigurationResortMembershipStatusDetailsType`](#configurationresortmembershipstatusdetailstype) | Membership Status Details |
| 135 | priorityDetails | [`ConfigurationResortPriorityDetailsType`](#configurationresortprioritydetailstype) | Priority Details |
| 136 | entityAccountTypeDetails | [`ConfigurationResortEntityAccountTypeDetailsType`](#configurationresortentityaccounttypedetailstype) | Entity Account Type Details |
| 137 | addressTypeDetails | [`ConfigurationResortAddressTypeDetailsType`](#configurationresortaddresstypedetailstype) | Address Type Details |
| 138 | alternateLanguageTitleDetails | [`ConfigurationResortAlternateLanguageTitleDetailsType`](#configurationresortalternatelanguagetitledetailstype) | Alternate Language Title |
| 139 | roomsPotentialDetails | [`ConfigurationResortRoomsPotentialDetailsType`](#configurationresortroomspotentialdetailstype) | Rooms Potential Details |
| 140 | businessSegmentDetails | [`ConfigurationResortBusinessSegmentDetailsType`](#configurationresortbusinesssegmentdetailstype) | Business Segment Details |
| 141 | companyTypeDetails | [`ConfigurationResortCompanyTypeDetailsType`](#configurationresortcompanytypedetailstype) | Company Type Details |
| 142 | competitionDetails | [`ConfigurationResortCompetitionDetailsType`](#configurationresortcompetitiondetailstype) | Competition Details |
| 143 | genderDetails | [`ConfigurationResortGenderDetailsType`](#configurationresortgenderdetailstype) | Gender Details |
| 144 | profileInactiveReasonDetails | [`ConfigurationResortProfileInactiveReasonDetailsType`](#configurationresortprofileinactivereasondetailstype) | Profile Inactive Reason Details |
| 145 | industryCodeDetails | [`ConfigurationResortIndustryCodeDetailsType`](#configurationresortindustrycodedetailstype) | Industry Code Details |
| 146 | influenceCodeDetails | [`ConfigurationResortInfluenceCodeDetailsType`](#configurationresortinfluencecodedetailstype) | Influence Code Details |
| 147 | keywordTypeDetails | [`ConfigurationResortKeywordTypeDetailsType`](#configurationresortkeywordtypedetailstype) | Keyword Type Details |
| 148 | mailingActionDetails | [`ConfigurationResortMailingActionDetailsType`](#configurationresortmailingactiondetailstype) | Mailing Action Details |
| 149 | preferenceDetails | [`ConfigurationResortPreferenceDetailsType`](#configurationresortpreferencedetailstype) | Preference Details |
| 150 | profileRestrictionReasonDetails | [`ConfigurationResortProfileRestrictionReasonDetailsType`](#configurationresortprofilerestrictionreasondetailstype) | Profile Restriction Reason Details |
| 151 | salesEventScopeDetails | [`ConfigurationResortSalesEventScopeDetailsType`](#configurationresortsaleseventscopedetailstype) | Sales Event Scope |
| 152 | salesEventScopeCityDetails | [`ConfigurationResortSalesEventScopeCityDetailsType`](#configurationresortsaleseventscopecitydetailstype) | Sales Event Scope City |
| 153 | membershipClaimAdjustmentLimitDetails | [`ConfigurationResortMembershipClaimAdjustmentLimitDetailsType`](#configurationresortmembershipclaimadjustmentlimitdetailstype) | Membership Claim Adjustment Limit |
| 154 | configurationResortRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyPropertyDetailsType

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

### ConfigurationResortMembershipClaimOriginDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | claimOriginCode | `String` | Claim Origin Code |
| 5 | claimOriginDescription | `String` | Claim Origin Description |
| 6 | comments | `String` | Comments |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedflag | `String` | Deleted Flag |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Code to uniquely identify the Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipPointsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allMembershipRatesYn | `String` | Indicates if this rule applies to all Rates checked for membership. |
| 2 | allMembershipTransactionYN | `String` | Indicates if this rule applies to all transactions checked for membership. |
| 3 | averageRateAmount | `Float` | Average Rate Amount |
| 4 | beginDate | `Date` | Begin Date |
| 5 | billingGroup | `String` | Billing Group |
| 6 | bookingEndDate | `Date` | Booking End Date |
| 7 | bookingStartDate | `Date` | Booking Start Date |
| 8 | calculationRule | `String` | Calculation Rule |
| 9 | chainCode | `String` | Chain Code |
| 10 | costPerPoint | `Float` | Cost Per Point |
| 11 | creditMultipleMembershipYn | `String` | Credit Multiple Membership Y/N |
| 12 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 13 | daysSinceEnrolled | `Float` | Number of days from enrollment. |
| 14 | deletedFlag | `String` | Deleted Flag |
| 15 | description | `String` | Description |
| 16 | earningRhythmFlg | `String` | Flag indicating type of earning rhythm applied. |
| 17 | earningRhythmNights | `Float` | Indicate that points will be earned every X nights. |
| 18 | endDate | `Date` | End Date |
| 19 | enrollmentCode | `String` | The enrollment code to which this rule applies. |
| 20 | enrollmentGroup | `String` | Enrollment group that includes the enrollment code(s) to which this rule applies. |
| 21 | excludeBbFlg | `String` | Flag to indicate this rule is excluded if back to back is detected. |
| 22 | excludeFromPointProjectionYN | `String` | Determines while calculating points projection should the rule be excluded or included. Default is included(N). |
| 23 | excludeMktGroup | `String` | Determines if the market group should be excluded or included ). Default is included(N). |
| 24 | excludeRevGroup | `String` | Determines if the revenue group should be excluded or included ). Default is included(N). |
| 25 | excludeRoomGroupYn | `String` | Indicates if the room group should be excluded if Y. |
| 26 | expirationDate | `Date` | Expiration date of the Card. |
| 27 | exportLabel | `String` | This field will be used to store export label and will be used only for exporting purposes. |
| 28 | fridayYN | `String` | Friday YN |
| 29 | inactiveDate | `DateTime` | Inactive Date |
| 30 | includeGraceRenewalFlg | `String` | This flag indicate if grace renewals need to be included or not. |
| 31 | insertDate | `DateTime` | Insert Date |
| 32 | insertUser | `Float` | Insert User |
| 33 | jRNUpdateDate | `Date` | JRN Update Date |
| 34 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 35 | marketCode | `String` | Market Code |
| 36 | marketGroup | `String` | Market Group |
| 37 | marketGroupIncludeYN | `String` | Market Group Include YN |
| 38 | maxBucketSize | `Float` | Maximum quantity bucket can contain. |
| 39 | maximumNights | `Float` | This field indicates the maximum nights eligible  to receive points If membership type is based on NIGHTS. |
| 40 | maximumRevenue | `Float` | Maximum Revenue |
| 41 | memRevenueGroup | `String` | Membership rate group. |
| 42 | membershipLevel | `String` | Membership level to which this rule applies. |
| 43 | membershipPointsSeqno | `Float` | Membership Points Seqno |
| 44 | membershipRateGroupExcludeYN | `String` | Mem Rate Group Exclude Y/N |
| 45 | membershipType | `String` | Membership Type |
| 46 | minPropertiesReq | `Float` | Determines if transactions should belong to minimum different properties. If empty then they can belong to same property. |
| 47 | minimumNights | `Float` | This field indicates the minimum length of stay required to receive points If membership type is based on STAY. |
| 48 | minimumRateAmount | `Float` | This field indicates the minimum rate amount required for the guest to earn points. |
| 49 | minimumRevenue | `Float` | Minimum Revenue |
| 50 | minimumStays | `Float` | Minimum Stays |
| 51 | mondayYN | `String` | Monday YN |
| 52 | multipleTransactionsYn | `String` | Multiple Transactions Y/N |
| 53 | numberOfTimesEligible | `Float` | Number of Times Eligible |
| 54 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 55 | perRevenueUnits | `Float` | Specifies the minimum units needed |
| 56 | points | `Float` | Specifies the ratio of the points accumulated per Stay or Night or Revenue. This ratio multiplied by the actual Stays or Nights or Revenue will give the Total points accumulated. |
| 57 | pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| 58 | pointsRatioPercentYn | `String` | Points ratio is expressed in terms of %. |
| 59 | pointsRatioRoundingFlg | `String` | This flag tells if the total amount computed will be rounded rounded up or rounded down. |
| 60 | preferredCardExcludeYn | `String` | Exclude the rule if a preferred card exception exists on the transaction. |
| 61 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 62 | programType | `String` | Program Type |
| 63 | programTypeDesc | `String` | Program Type Desc |
| 64 | promotionCode | `String` | Promotion Code |
| 65 | property | `String` | Property |
| 66 | propertyGroup | `String` | Property Group |
| 67 | pseudoRuleYn | `String` | Pseudo rule is used for OCIS memberships to show computed points in PMS for a reservation. |
| 68 | qualifyingRatesYN | `String` | Qualifying Rates YN |
| 69 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 70 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 71 | rateCode | `String` | Rate Code |
| 72 | rateGroup | `String` | Rate Group |
| 73 | rateGroupIncludeYN | `String` | Rate Group Include YN |
| 74 | reservationChannel | `String` | Reservation Channel |
| 75 | revenueGroup | `String` | Revenue Group |
| 76 | revenueGroupIncludeYN | `String` | Revenue Group Include YN |
| 77 | roomClass | `String` | Room Class |
| 78 | roomGroup | `String` | Room Group |
| 79 | roomType | `String` | Room Type |
| 80 | roomTypeToChargeYN | `String` | Y to calculate the membership upgrade based on the "room to charge" for the stay and not the actual room type in which the member stayed. |
| 81 | rounding | `String` | Rounding |
| 82 | ruleAppliesTo | `String` | Rule Applies To |
| 83 | ruleBasedOn | `String` | Indicates the field on which  calculation of points is valid for. Eg if value is 'RATE_GROUP' then this rule is valid for the value in RATE_GROUP field. Thus we can specify different points rule for BUSINESS rates and NON-BUSINESS rates. |
| 84 | ruleCode | `String` | Rule Code |
| 85 | saturdayYN | `String` | Saturday YN |
| 86 | sundayYN | `String` | Sunday YN |
| 87 | thursdayYN | `String` | Thursday YN |
| 88 | toMemberLevel | `String` | Used in membership tier upgrade rule to determine to which level the upgrade will eligible. |
| 89 | transactionType | `String` | Transaction Type |
| 90 | tuesdayYN | `String` | Tuesday YN |
| 91 | type | `String` | Type |
| 92 | typeOfPoints | `String` | Types of points earned (Loyalty FF). |
| 93 | updateDate | `DateTime` | Update Date |
| 94 | updateUser | `Float` | Update User |
| 95 | userpostingOnlyYn | `String` | Userposting Only Y/N |
| 96 | wednesdayYN | `String` | Wednesday YN |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipAwardRatesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | awardType | `String` | Award Type |
| 2 | chainCode | `String` | Chain Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | membershipType | `String` | Membership Type |
| 6 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 7 | property | `String` | Code to uniquely identify the Property |
| 8 | rateCode | `String` | Rate Code |
| 9 | rateDescription | `String` | Rate Description |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipAwardProductsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | awardType | `String` | Award Type |
| 2 | centralPackageCode | `String` | Central Package Code |
| 3 | centralPackageDescription | `String` | Central Package Description |
| 4 | chainCode | `String` | Chain Code |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | membershipType | `String` | Membership Type |
| 8 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 9 | packageCode | `String` | Products Codes |
| 10 | packageDescription | `String` | Package Description |
| 11 | property | `String` | Code to uniquely identify the Property |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipAwardUpgradesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | awardType | `String` | Award Type |
| 2 | centralUpgradeFromRoom | `String` | Central Upgrade From Room |
| 3 | centralUpgradeToRoom | `String` | Central Upgrade To Room |
| 4 | chainCode | `String` | Chain Code |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | fromDate | `Date` | From Date |
| 8 | fromRoom | `String` | Room Number of the reservation from which charges were routed when routing charges between reservations. |
| 9 | inactiveDate | `DateTime` | Inactive Date |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | membershipAwardId | `Float` | Internal PK for the table. |
| 15 | membershipType | `String` | Membership Type |
| 16 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 17 | pointsRequiredUpgrades | `Float` | Points Required Upgrades |
| 18 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 19 | property | `String` | Code to uniquely identify the Property |
| 20 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 21 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 22 | toDate | `Date` | To Date |
| 23 | toRoom | `String` | Upgraded room. |
| 24 | updateDate | `DateTime` | Update Date |
| 25 | updateUser | `Float` | Update User |
| 26 | upgradeFromRoom | `String` | Upgrade From Room |
| 27 | upgradeToRoom | `String` | Upgrade To Room |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipAwardFinancialTransactionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | awardType | `String` | Award Type |
| 2 | centralTransactionCode | `String` | Central Transaction Code |
| 3 | centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| 4 | chainCode | `String` | Chain Code |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | membershipType | `String` | Membership Type |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | property | `String` | Code to uniquely identify the Property |
| 15 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 16 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 17 | transactionCode | `String` | Transaction Code |
| 18 | transactionCodeDescription | `String` | Transaction Code Description |
| 19 | updateDate | `DateTime` | Update Date |
| 20 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipPropertyGroupCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | attachedPropertyCode | `String` | Attached Property Code |
| 2 | attachedPropertyDescription | `String` | Attached Property Description |
| 3 | chainCode | `String` | Chain Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | inactiveDate | `DateTime` | Inactive Date |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | membershipResortGroup | `String` | Mem Property Group |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | requiredYn | `String` | Required Y/N |
| 17 | updateDate | `DateTime` | Update Date |
| 18 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAirportDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `String` | Airport code. |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | distance | `Float` | Distance from the airport to the property. |
| 6 | distanceType | `String` | Type of units for distance (mileskilometers). |
| 7 | drivingDirections | `String` | Directions from the airport to the property. |
| 8 | drivingTime | `String` | Driving Time |
| 9 | insertDate | `DateTime` | Insert Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | property | `String` | Property |
| 16 | sequence | `Float` | Sequence |
| 17 | transportationCode1 | `String` | Internal. |
| 18 | transportationCode2 | `String` | Internal. |
| 19 | transportationCode3 | `String` | Internal. |
| 20 | transportationCode4 | `String` | Internal. |
| 21 | transportationCode5 | `String` | Internal. |
| 22 | transportationCode6 | `String` | Internal. |
| 23 | transportationCode7 | `String` | Internal. |
| 24 | transportationCode8 | `String` | Internal. |
| 25 | updateDate | `DateTime` | Update Date |
| 26 | updateUser | `Float` | Update User |
| 27 | website | `String` | Website |

[⬆ Back to Query](#query)

---

### ConfigurationResortFeatureDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `String` | Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | endDate | `Date` | End Date |
| 6 | featureType | `String` | Feature Type |
| 7 | featureid | `String` | Featureid |
| 8 | hours | `String` | Hours |
| 9 | inactiveDate | `Date` | Inactive Date |
| 10 | inactiveflag | `String` | Inactive Flag |
| 11 | insertDate | `DateTime` | Insert Date |
| 12 | insertUser | `Float` | Insert User |
| 13 | internalDeletedflag | `String` | Deleted Flag |
| 14 | jRNUpdateDate | `Date` | JRN Update Date |
| 15 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 16 | locationID | `String` | Internal ID to uniquely identify the Property |
| 17 | notes | `String` | Notes |
| 18 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 19 | price | `String` | Price |
| 20 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 21 | property | `String` | Property |
| 22 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 23 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 24 | sequence | `Float` | Sequence |
| 25 | startDate | `Date` | Start Date |
| 26 | type | `String` | Type |
| 27 | updateDate | `DateTime` | Update Date |
| 28 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAttractionCategoryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAttractionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | address1 | `String` | Address1 |
| 2 | address2 | `String` | Address2 |
| 3 | address3 | `String` | Address3 |
| 4 | address4 | `String` | Address4 |
| 5 | attractionClass | `String` | Attraction Class |
| 6 | category | `String` | Type of attraction |
| 7 | city | `String` | City |
| 8 | code | `String` | The unique identifier for this attraction. The primary key to this table. |
| 9 | coordinateSupplier | `String` | Who supplied the geo-coded coordinates for this attraction. |
| 10 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 11 | deletedFlag | `String` | Deleted Flag |
| 12 | description | `String` | Description |
| 13 | direction | `String` | Direction |
| 14 | directions | `String` | Internal |
| 15 | distance | `Float` | Distance |
| 16 | distanceType | `String` | Distance Type |
| 17 | drivingTime | `String` | Driving Time |
| 18 | generalDirections | `String` | The general directions to this attraction. |
| 19 | hoursOfOperation | `String` | The hours of operation for this attraction. |
| 20 | inactiveDate | `Date` | Inactive Date |
| 21 | insertDate | `DateTime` | Insert Date |
| 22 | insertUser | `Float` | Insert User |
| 23 | jRNUpdateDate | `Date` | JRN Update Date |
| 24 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 25 | latitude | `Float` | The latitude of this attraction in geo-coded format. |
| 26 | longitude | `Float` | The longitude of this attraction in geo-coded format. |
| 27 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 28 | priceRange | `String` | Price Range |
| 29 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 30 | property | `String` | Property |
| 31 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 32 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 33 | region | `String` | Region |
| 34 | sequence | `Float` | Sequence |
| 35 | state | `String` | State |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |
| 38 | website | `String` | Website |
| 39 | zipCode | `String` | Zipcode Code |

[⬆ Back to Query](#query)

---

### ConfigurationResortChainDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aspYn | `String` | Chain used for ASP Y/N. |
| 2 | beginDate | `Date` | Begin Date |
| 3 | bookingConditions | `String` | Booking conditions chainwide such as commission policies for TA Group policies Cancellation/Deposit/Guarantee and family and child rules. |
| 4 | centralChain | `String` | Central Chain |
| 5 | centralDescription | `String` | Central Description |
| 6 | chain | `String` | Chain |
| 7 | chainName | `String` | Chain Name |
| 8 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 9 | deletedFlag | `String` | Deleted Flag |
| 10 | description | `String` | Description |
| 11 | endDate | `Date` | End Date |
| 12 | frequentFlierCardsAcceptYn | `String` | Specifies if frequent flier cards are accepted by the chain (Y/N). |
| 13 | hoCity | `String` | The city of the Head Office of the chain. |
| 14 | hoCountry | `String` | The country of the Head Office of the chain. |
| 15 | hoEmail | `String` | The email ID of the Head Office of the chain. |
| 16 | hoFax | `String` | The fax number of the Head Office of the chain. |
| 17 | hoPostCode | `String` | The postal code of the Head Office of the chain. |
| 18 | hoState | `String` | The state of the Head Office of the chain. |
| 19 | hoStreet | `String` | The street of the Head Office of the chain. |
| 20 | hoTelephone | `String` | The phone number of the Head Office of the chain. |
| 21 | imgChainId | `Float` | Img Chain ID |
| 22 | inactiveDate | `Date` | Inactive Date |
| 23 | insertDate | `DateTime` | Insert Date |
| 24 | insertUser | `Float` | Insert User |
| 25 | jRNUpdateDate | `Date` | JRN Update Date |
| 26 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 27 | logoFileName | `String` | File name of the chains' logo |
| 28 | loyaltyProgram | `String` | Loyalty program data. |
| 29 | marketingText | `String` | Marketing Text |
| 30 | nameId | `Float` | Name ID |
| 31 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 32 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 33 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 34 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 35 | repItem | `String` | Reporting Item |
| 36 | repItemName | `String` | Reporting Item Name |
| 37 | repItemOrderby | `Float` | Reporting Item Orderby |
| 38 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 39 | scriptId | `Float` | Script ID |
| 40 | shareProfilesYN | `String` | Sharing Profiles across the Chain. |
| 41 | updateDate | `DateTime` | Update Date |
| 42 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortClosingScriptDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | jRNUpdateDate | `Date` | JRN Update Date |
| 5 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 6 | language | `String` | Language |
| 7 | membershipType | `String` | Membership Type |
| 8 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 9 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 10 | property | `String` | Property |
| 11 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 12 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 13 | resortType | `String` | Property Type |
| 14 | scriptId | `Float` | Script ID |
| 15 | scriptType | `String` | Script Type. (e.g. [SMS] for SMS script and [RESV] for Closing Script) |

[⬆ Back to Query](#query)

---

### ConfigurationResortCommunicationMethodDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDeliveryStatusDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDepartmentDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allowOnTaskSheetYn | `String` | Indicates if Reservation Traces related to this Department will appear on Housekeeping Task Sheets. |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | departmentCode | `String` | Department Code |
| 7 | departmentid | `String` | Departmentid |
| 8 | deptManagerPager | `String` | Pager number of department manager |
| 9 | description | `String` | Description of the department |
| 10 | email | `String` | Department E-Mail Address. |
| 11 | inactiveDate | `DateTime` | Inactive Date |
| 12 | inactiveflag | `String` | Inactive Flag |
| 13 | insertDate | `DateTime` | Insert Date |
| 14 | insertUser | `Float` | Insert User |
| 15 | internalDeletedflag | `String` | Deleted Flag |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | locationID | `String` | Internal ID to uniquely identify the Property |
| 19 | messageText | `String` | Message Text |
| 20 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 21 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 22 | property | `String` | Property |
| 23 | repDeptName | `String` | Reporting Dept Name |
| 24 | repItem | `String` | Reporting Item |
| 25 | repItemName | `String` | Reporting Item Name |
| 26 | repItemOrderby | `Float` | Reporting Item Orderby |
| 27 | repOrderBy | `Float` | Reporting Order By |
| 28 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 29 | reportingDeptId | `String` | Rep Dept ID |
| 30 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 31 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 32 | sequence | `Float` | Sequence |
| 33 | updateDate | `DateTime` | Update Date |
| 34 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortElecRegCardScriptDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | jRNUpdateDate | `Date` | JRN Update Date |
| 5 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 6 | language | `String` | Language |
| 7 | membershipType | `String` | Membership Type |
| 8 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 9 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 10 | property | `String` | Property |
| 11 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 12 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 13 | resortType | `String` | Property Type |
| 14 | scriptId | `Float` | Script ID |
| 15 | scriptType | `String` | Script Type. (e.g. [SMS] for SMS script and [RESV] for Closing Script) |

[⬆ Back to Query](#query)

---

### ConfigurationResortHubPropertyDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | associatedProperty | `String` | Associated Property |
| 2 | associatedPropertyName | `String` | Associated Property Name |
| 3 | croCode | `String` | Cro Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | insertDate | `DateTime` | Insert Date |
| 7 | insertUser | `Float` | Insert User |
| 8 | jRNUpdateDate | `Date` | JRN Update Date |
| 9 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 10 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 11 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 12 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 13 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 14 | updateDate | `DateTime` | Update Date |
| 15 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortJobTitleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | closingScriptYn | `String` | Display reservation closing script? |
| 3 | code | `String` | Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | description | `String` | Job title description |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 10 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 11 | property | `String` | Property |
| 12 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 13 | rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### ConfigurationResortUDFCategoryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortUDFTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | attributeType | `String` | Determines the type of attribute. The value is bit specific. |
| 2 | attributeVerified | `String` | Attribute Verified |
| 3 | category | `String` | Category |
| 4 | chainCode | `String` | Chain Code |
| 5 | code | `String` | UDF type - CND. |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | inactiveDate | `DateTime` | Inactive Date |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | multipleYn | `String` | Not used. |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | property | `String` | Property |
| 18 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 19 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 20 | sequence | `Float` | Sequence |
| 21 | tableName | `String` | Table Name |
| 22 | updateDate | `DateTime` | Update Date |
| 23 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBrandCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBusinessUnitDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDepartmentCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDivisionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortHotelCategoryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortOperatingUnitDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortApplicationParameterValueDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aPNDeletedFlag | `String` | APN Deleted Flag |
| 2 | aPNDisplayYN | `String` | APN Display Parameter |
| 3 | aPNJRNUpdateDate | `Date` | JRN Update Date |
| 4 | aPNJRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 5 | aPNPrimaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 6 | aPNRNAInsertDate | `DateTime` | RNA Insert Date |
| 7 | aPNRNAUpdateDate | `DateTime` | RNA Update Date |
| 8 | canDeleteYn | `String` | Can Delete Y/N |
| 9 | chainCode | `String` | Chain Code |
| 10 | copyYn | `String` | Determines if a parameter value shall not be copied due to dependent business logic in the target property. |
| 11 | coreYn | `String` | Indicates if parameter is used for Core functionality |
| 12 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 13 | deletedFlag | `String` | Deleted Flag |
| 14 | displayYn | `String` | Display Y/N |
| 15 | explanation | `String` | Not Used. |
| 16 | insertDate | `DateTime` | Insert Date |
| 17 | insertUser | `Float` | Insert User |
| 18 | jRNUpdateDate | `Date` | JRN Update Date |
| 19 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 20 | lovValues | `String` | Lov Values |
| 21 | orderBy | `Float` | Order By |
| 22 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 23 | parameterDescription | `String` | Parameter Description |
| 24 | parameterDisplayName | `String` | Parameter Display Name |
| 25 | parameterGroup | `String` | Parameter Group |
| 26 | parameterName | `String` | Parameter Name |
| 27 | parameterType | `String` | Parameter Type |
| 28 | parameterTypeDetail | `String` | Parameter Type Detail |
| 29 | parameterValue | `String` | Parameter Value |
| 30 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 31 | property | `String` | Property |
| 32 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 33 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 34 | storedInResort | `String` | Internal Field that tells whether the value of the field is stored in the resort table or in the application Parameter table itself. |
| 35 | updateDate | `DateTime` | Update Date |
| 36 | updateUser | `Float` | Update User |
| 37 | usedInApp | `String` | Used In App |

[⬆ Back to Query](#query)

---

### ConfigurationResortTrackitActionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `String` | Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | defaultYn | `String` | Default Y/N |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | description | `String` | Description |
| 6 | inactiveDate | `DateTime` | Inactive Date |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | messageText | `String` | Message Text |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | property | `String` | Property |
| 15 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 16 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 17 | repItem | `String` | Reporting Item |
| 18 | repItemName | `String` | Reporting Item Name |
| 19 | repItemOrderby | `Float` | Reporting Item Orderby |
| 20 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 21 | sendMessageYn | `String` | Indicator to send a message to the guest when a new trackit item is created. |
| 22 | sequence | `Float` | Sequence |
| 23 | status | `String` | Internal status for this action. Used for ti_subgroup='ACTION'. |
| 24 | tiSubgroup | `String` | Track it SubGroup. Example: Location Type or Action. |
| 25 | trackItGroup | `String` | Trackit Group. |
| 26 | trackitTypesUrl | `String` | URL for trackit types. |
| 27 | updateDate | `DateTime` | Update Date |
| 28 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTrackitLocationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionStatus | `String` | Internal status for this action. Used for ti_subgroup='ACTION'. |
| 2 | code | `String` | Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | defaultYn | `String` | Default Y/N |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | description | `String` | Description |
| 7 | inactiveDate | `DateTime` | Inactive Date |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | messageText | `String` | Message Text |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | property | `String` | Property |
| 16 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 17 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 18 | repItem | `String` | Reporting Item |
| 19 | repItemName | `String` | Reporting Item Name |
| 20 | repItemOrderby | `Float` | Reporting Item Orderby |
| 21 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 22 | sendMessageYn | `String` | Indicator to send a message to the guest when a new trackit item is created. |
| 23 | sequence | `Float` | Sequence |
| 24 | tiSubgroup | `String` | Track it SubGroup. Example: Location Type or Action. |
| 25 | trackItGroup | `String` | Trackit Group. |
| 26 | trackitTypesUrl | `String` | URL for trackit types. |
| 27 | updateDate | `DateTime` | Update Date |
| 28 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTrackitTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actionStatus | `String` | Internal status for this action. Used for ti_subgroup='ACTION'. |
| 2 | code | `String` | Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | defaultYn | `String` | Default Y/N |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | description | `String` | Description |
| 7 | inactiveDate | `DateTime` | Inactive Date |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | messageText | `String` | Message Text |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | property | `String` | Property |
| 16 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 17 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 18 | repItem | `String` | Reporting Item |
| 19 | repItemName | `String` | Reporting Item Name |
| 20 | repItemOrderby | `Float` | Reporting Item Orderby |
| 21 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 22 | sendMessageYN | `String` | Indicator to send a message to the guest when a new trackit item is created. |
| 23 | sequence | `Float` | Sequence |
| 24 | tiSubgroup | `String` | Track it SubGroup. Example: Location Type or Action. |
| 25 | trackItGroup | `String` | Trackit Group. |
| 26 | updateDate | `DateTime` | Update Date |
| 27 | updateUser | `Float` | Update User |
| 28 | website | `String` | URL for trackit types. |

[⬆ Back to Query](#query)

---

### ConfigurationResortAccountTypeDetailsType

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

### ConfigurationResortARReminderCycleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountTypeId | `Float` | Account Type ID |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | globalAccountYN | `String` | Indicates whether the account type is Global Account Type. Value 'Y' indicates that it is Global. |
| 5 | insertDate | `DateTime` | Insert Date |
| 6 | insertUser | `Float` | Insert User |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | letterName | `String` | Name of the reminder letter. |
| 10 | numberOfDays | `Float` | Number of days before the system geneates the Reminder letter. |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 13 | property | `String` | Property |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | reminderCode | `Float` | Internal number. |
| 17 | updateDate | `DateTime` | Update Date |
| 18 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAcctFlagReasonDetailsType

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

### ConfigurationResortTransactionReasonCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adjustmentCode | `String` | Reason Code. |
| 2 | adjustmentCodeDescription | `String` | Description |
| 3 | adjustmentType | `String` | Adjustment Type |
| 4 | amountPercentFlag | `String` | Percentage / Amount flag. Allowed values: AMOUNT PERCENT. |
| 5 | amountPercentValue | `Float` | Amount or Percentage to consider during the adjustment. |
| 6 | birGuestType | `String` | Guest type in PH country mode. Further used for showing proper adjustment options. |
| 7 | codeType | `String` | Code Type |
| 8 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 9 | deletedFlag | `String` | Deleted Flag |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | property | `String` | Property |
| 17 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 18 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 19 | tranCodeType | `String` | Correction type. e.g. ADJ for adjustment COR for correction DEL for deletion. |
| 20 | updateDate | `DateTime` | Update Date |
| 21 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCreditCardAuthorizationRulesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | amount | `Float` | Amount |
| 2 | authorizationRules | `Float` | Authorization Rules |
| 3 | cAmount | `Float` | Central Amount |
| 4 | cExchangeDate | `Date` | Central Xchange Date |
| 5 | cExchangeRate | `Float` | Central Xchange Rate |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | guaranteeCode | `String` | Guarantee Code |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | mainWindowYn | `String` | Indicates if this auth rule is for the main window (i.e. window 1). Default is Y i.e. Only if the flag is explicitly set to N does the rule apply to windows other than 1. |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | percentage | `Float` | Percentage |
| 15 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 16 | property | `String` | Property |
| 17 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 18 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 19 | rateCategory | `String` | Rate Category |
| 20 | rateCode | `String` | Rate Code |
| 21 | roomClass | `String` | Room Class |
| 22 | roomType | `String` | Room Type |
| 23 | sourceCode | `String` | Source Code |

[⬆ Back to Query](#query)

---

### ConfigurationResortAutoFolioSettlementTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCashierDetailsType

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

### ConfigurationResortCustomNumberDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activeYN | `String` | Active YN |
| 2 | chainCode | `String` | Chain Code |
| 3 | code | `String` | Internal code to identify the custom number. |
| 4 | customNumberFormula | `String` | Custom Number Formula |
| 5 | customNumberType | `String` | Custom Number Type |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | endDate | `Date` | End Date |
| 10 | filterCondition | `String` | Filter Condition |
| 11 | inactiveDate | `DateTime` | Inactive Date |
| 12 | insertDate | `DateTime` | Insert Date |
| 13 | insertUser | `Float` | Insert User |
| 14 | jRNUpdateDate | `Date` | JRN Update Date |
| 15 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 16 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 17 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 18 | property | `String` | Property |
| 19 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 20 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 21 | sequence | `Float` | Sequence |
| 22 | startDate | `Date` | Start Date |
| 23 | updateDate | `DateTime` | Update Date |
| 24 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCurrencyExchangeTaxDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | amountFrom | `Float` | Minimum amount applicable to apply tax on the Currency Exchange. |
| 2 | amountTo | `Float` | Maximum amount applicable to apply tax on the Currency Exchange. |
| 3 | cExchangeDate | `Date` | Central Xchange Date |
| 4 | cExchangeRate | `Float` | Central Xchange Rate |
| 5 | cMaxAmount | `Float` | Central Max Amount |
| 6 | cMaxServiceTax | `Float` | Central Max Service Tax |
| 7 | cMinimumAmount | `Float` | Central Min Amount |
| 8 | cMinimumServiceTax | `Float` | Central Min Service Tax |
| 9 | cNotionalAmount | `Float` | Central Notional Amount |
| 10 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 11 | deletedFlag | `String` | Deleted Flag |
| 12 | insertDate | `DateTime` | Insert Date |
| 13 | insertUser | `Float` | Insert User |
| 14 | jRNUpdateDate | `Date` | JRN Update Date |
| 15 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 16 | maximum | `Float` | Flat amount service tax to be used when calculated service tax amount exceeds the flat amount. |
| 17 | minimum | `Float` | Flat amount service tax to be used when calculated service tax amount is less than this flat amount. |
| 18 | notionalAmount | `Float` | Notional amount applicable based on the service tax type range. |
| 19 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 20 | percentage | `Float` | Tax Percentage applicable based on the service tax type. |
| 21 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 22 | property | `String` | Property |
| 23 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 24 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 25 | serviceTaxType | `String` | Stores the Service tax type. Possible values can be: R1 R2 R3 and so on. |
| 26 | updateDate | `DateTime` | Update Date |
| 27 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortExpenseArrangementCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| 2 | arrangeId | `String` | Arrange ID |
| 3 | arrangementId | `Float` | Arrangement ID |
| 4 | bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| 5 | cExchangeDate | `Date` | Central Xchange Date |
| 6 | cExchangeRate | `Float` | Central Xchange Rate |
| 7 | cRoutingAmount | `Float` | Central Routing Amount |
| 8 | compYn | `String` | Comp Y/N |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | dailyYn | `String` | Daily Y/N |
| 11 | day1 | `String` | Day1 |
| 12 | day2 | `String` | Day2 |
| 13 | day3 | `String` | Day3 |
| 14 | day4 | `String` | Day4 |
| 15 | day5 | `String` | Day5 |
| 16 | day6 | `String` | Day6 |
| 17 | day7 | `String` | Day7 |
| 18 | deletedFlag | `String` | Deleted Flag |
| 19 | eligibleYn | `String` | Specifies the Eligibility to calculate membership points. |
| 20 | expenseArrangementCode | `String` | Expense Arrangement Code |
| 21 | expenseArrangementDescription | `String` | Arrangement Description for the Transaction Code. |
| 22 | exportBucketType | `String` | User defined Export Bucket type. |
| 23 | inactiveDate | `DateTime` | Inactive Date |
| 24 | inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| 25 | insertDate | `DateTime` | Insert Date |
| 26 | insertUser | `Float` | Insert User |
| 27 | jRNUpdateDate | `Date` | JRN Update Date |
| 28 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 29 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 30 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 31 | property | `String` | Property |
| 32 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 33 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 34 | revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| 35 | routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| 36 | routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| 37 | routingPercent | `Float` | Routing Percent |
| 38 | type | `String` | Type |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionCodeDetailsType

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

### ConfigurationResortFolioArrangementCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| 2 | arrangeId | `String` | Arrange ID |
| 3 | arrangementId | `Float` | Arrangement ID |
| 4 | bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| 5 | cExchangeDate | `Date` | Central Xchange Date |
| 6 | cExchangeRate | `Float` | Central Xchange Rate |
| 7 | cRoutingAmount | `Float` | Central Routing Amount |
| 8 | compYn | `String` | Comp Y/N |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | dailyYn | `String` | Daily Y/N |
| 11 | day1 | `String` | Day1 |
| 12 | day2 | `String` | Day2 |
| 13 | day3 | `String` | Day3 |
| 14 | day4 | `String` | Day4 |
| 15 | day5 | `String` | Day5 |
| 16 | day6 | `String` | Day6 |
| 17 | day7 | `String` | Day7 |
| 18 | deletedFlag | `String` | Deleted Flag |
| 19 | eligibleYn | `String` | Specifies the Eligibility to calculate membership points. |
| 20 | exportBucketType | `String` | User defined Export Bucket type. |
| 21 | folioArrangementCode | `String` | Folio Arrangement Code |
| 22 | folioArrangementDescription | `String` | Arrangement Description for the Transaction Code. |
| 23 | inactiveDate | `DateTime` | Inactive Date |
| 24 | inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| 25 | insertDate | `DateTime` | Insert Date |
| 26 | insertUser | `Float` | Insert User |
| 27 | jRNUpdateDate | `Date` | JRN Update Date |
| 28 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 29 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 30 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 31 | property | `String` | Property |
| 32 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 33 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 34 | revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| 35 | routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| 36 | routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| 37 | routingPercent | `Float` | Routing Percent |
| 38 | type | `String` | Type |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGroupArrangementCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| 2 | arrangeId | `String` | Arrange ID |
| 3 | arrangementId | `Float` | Arrangement ID |
| 4 | bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| 5 | cExchangeDate | `Date` | Central Xchange Date |
| 6 | cExchangeRate | `Float` | Central Xchange Rate |
| 7 | cRoutingAmount | `Float` | Central Routing Amount |
| 8 | compYn | `String` | Comp Y/N |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | dailyYn | `String` | Daily Y/N |
| 11 | day1 | `String` | Day1 |
| 12 | day2 | `String` | Day2 |
| 13 | day3 | `String` | Day3 |
| 14 | day4 | `String` | Day4 |
| 15 | day5 | `String` | Day5 |
| 16 | day6 | `String` | Day6 |
| 17 | day7 | `String` | Day7 |
| 18 | deletedFlag | `String` | Deleted Flag |
| 19 | eligibleYn | `String` | Specifies the Eligibility to calculate membership points. |
| 20 | exportBucketType | `String` | User defined Export Bucket type. |
| 21 | groupArrangementCode | `String` | Group Arrangement Code |
| 22 | groupArrangementDescription | `String` | Arrangement Description for the Transaction Code. |
| 23 | inactiveDate | `DateTime` | Inactive Date |
| 24 | inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| 25 | insertDate | `DateTime` | Insert Date |
| 26 | insertUser | `Float` | Insert User |
| 27 | jRNUpdateDate | `Date` | JRN Update Date |
| 28 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 29 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 30 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 31 | property | `String` | Property |
| 32 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 33 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 34 | revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| 35 | routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| 36 | routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| 37 | routingPercent | `Float` | Routing Percent |
| 38 | type | `String` | Type |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortFolioTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allowCompressYn | `String` | Folio to be use for compress bills |
| 2 | allowConvertYn | `String` | Folio type used for Converting the Folios |
| 3 | allowCreditbillYn | `String` | Allow Credit Bill |
| 4 | allowDifferenceProfile | `String` | This column is used to allow (or) disallow different profile when generating Credit/Debit bill. |
| 5 | arfolioName | `String` | name of the folio which is used for bills generated in A/R |
| 6 | associatedCreditFolioType | `String` | Stores the Linked / Associated Credit Folio Type. |
| 7 | clFlag | `String` | whether this folio type is used for City Ledger bills or not |
| 8 | columnSeparator | `String` | Column Separator to be used when creating XML file for Fiscal Printing. |
| 9 | compressYn | `String` | Whether to compress the file before delivery. |
| 10 | convertFolioType | `String` | Folio Type that will be converted to |
| 11 | correctionFolioYn | `String` | Identify the correction folio type. Added for Greece. |
| 12 | correctionHeaderYn | `String` | Identifies if this folio type is used for folio header correction. |
| 13 | creditYN | `String` | folio type used for Credit bills or not |
| 14 | currencyActionId | `Float` | Curr Action ID |
| 15 | customOnProfAttributesYn | `String` | If "Y" OPERA calls an API to consider the folio type based on attributes of the payee / company / TA / guest profiles of the guest. |
| 16 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 17 | debitBillYN | `String` | Identifies if this folio type is used for a Supplemental Folio which is an additional folio to an existing folio. |
| 18 | debitFlag | `String` | Identifies if the folio_type is a debit folio. [Y/N] |
| 19 | deletedFlag | `String` | Deleted Flag |
| 20 | depositFolioYn | `String` | Identifies if this folio type is a deposit folio type. |
| 21 | directBillYn | `String` | Folio type related to Direct Bill / City Ledger settlements. |
| 22 | documentCode | `String` | Unique Document Code |
| 23 | fiscalPrintingYn | `String` | Identifies if the folio type will generate fiscal folio. |
| 24 | fiscalProgramName | `String` | Fiscal Executable Program Name (without filepath) |
| 25 | fiscalYn | `String` | Indicates if this export bucket is FISCAL related. |
| 26 | folioName | `String` | name of the folio report to be used for this folio type for Reservation Bills |
| 27 | folioTypeCode | `String` | Folio Type Code |
| 28 | guestType | `Float` | Guest Type |
| 29 | internalBillYn | `String` | Internal bill that will be solely used for accounting purposes on barter agreements and interim billing amongst hotels which belong to the same owner. |
| 30 | jRNUpdateDate | `Date` | JRN Update Date |
| 31 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 32 | localCurrFlag | `String` | whether this folio type is used for any bills generated with local currency or any other currency |
| 33 | manualFolioPrintTask | `String` | Indicates if the folio type has a manual folio print task associated. |
| 34 | nameTaxType | `String` | Name Tax Type |
| 35 | nationalityFlag | `String` | whether this record is used for Local national or foreigner |
| 36 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 37 | originalFolioStayDetailsYN | `String` | Indicates if this folio type will display stay details of the original folio.  Used for Credit Bills and Supplemental folios. |
| 38 | passerbyfolioName | `String` | name of the passerby folio used for bills generated from Passerby |
| 39 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 40 | printFolioYn | `String` | Identifies if the settlements using this folio type will print a paper folio. |
| 41 | property | `String` | Property |
| 42 | queueName | `String` | Queue Name |
| 43 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 44 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 45 | simpleFolioYn | `String` | Identifies if this folio type is a simple folio type. |
| 46 | taxNoFlag | `String` | Folio type is used for profiles which have a tax number or not. |
| 47 | trxServiceType | `String` | Transaction Service Type |
| 48 | workingDocsYn | `String` | Used only for Information and Pro-forma folios. |

[⬆ Back to Query](#query)

---

### ConfigurationResortFolioTypeDetailDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `String` | name of the folio report to be used for this folio type for Reservation Bills |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | folioType | `String` | Folio Type |
| 6 | group | `String` | The Group for which this belongs to P- Passerby;G-Guest FolioA- Ar folio |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | language | `String` | Language |
| 10 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 11 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 12 | property | `String` | Code to uniquely identify the Property |
| 13 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 14 | rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### ConfigurationResortBankAccountDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | accountId | `Float` | Account ID |
| 2 | accountNumber | `String` | Account Number |
| 3 | bankAcctType | `String` | Flag to identify bank type  [O] OVOS user |
| 4 | bankCode | `String` | Code for the bank account |
| 5 | branchCode | `String` | Code for the bank accounts branch |
| 6 | cExchangeDate | `Date` | Central Xchange Date |
| 7 | cExchangeRate | `Float` | Central Xchange Rate |
| 8 | centralMinProcessingAmount | `Float` | Central Min. Processing Amount |
| 9 | checkReport | `String` | Check Report |
| 10 | checkSubLines | `Float` | Number of lines to be printed on check stub |
| 11 | currency | `String` | Currency |
| 12 | currencyDescription | `String` | Currency Description |
| 13 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 14 | defaultYN | `String` | Default YN |
| 15 | defaultForCurrencyYN | `String` | Only one 'Y' value is permitted per resort / currency combination used mainly by interface to figure out default bank for resort and currency combination |
| 16 | deletedFlag | `String` | Deleted Flag |
| 17 | description | `String` | Bank name |
| 18 | editCheckNumberYN | `String` | Check number allowed to be edited Y/N |
| 19 | insertDate | `DateTime` | Insert Date |
| 20 | insertUser | `Float` | Insert User |
| 21 | jRNUpdateDate | `Date` | JRN Update Date |
| 22 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 23 | language | `String` | Language |
| 24 | lastExportDate | `Date` | Last Export File Run Date |
| 25 | lastExportedFile | `Float` | Last Export Run File Number |
| 26 | maxCheckNo | `Float` | Internal |
| 27 | minProcessingAmount | `Float` | Minimum amount required to produce a check through commission processing for the selected account. |
| 28 | nextCheckNumber | `Float` | Last check number used by commisison handling module for bank account selected |
| 29 | onHold | `Float` | On Hold |
| 30 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 31 | paidInAR | `Float` | Paid in AR |
| 32 | paymentMethod | `String` | Payment Method |
| 33 | positivePayExportYN | `String` | Indicate that the bank account uses Positive Pay Export. |
| 34 | potential | `Float` | Potential |
| 35 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 36 | property | `String` | Property |
| 37 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 38 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 39 | routingNumber | `String` | Routing number for the bank account |
| 40 | sourceImportDir | `String` | Source directory for importing commission information. |
| 41 | targetImportDir | `String` | Target directory where import files will be stored. |
| 42 | tax1099ReportYN | `String` | Indicate that bank account use 1099 report |
| 43 | toBePaid | `Float` | To Be Paid |
| 44 | updateDate | `DateTime` | Update Date |
| 45 | updateUser | `Float` | Update User |
| 46 | validateIATANumberYN | `String` | Force validation of TA/Source IATA number during commision payment process. |

[⬆ Back to Query](#query)

---

### ConfigurationResortCommissionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | amount | `Float` | Amount |
| 2 | basedOn | `String` | Based On |
| 3 | cAmount | `Float` | Central Amount |
| 4 | cExchangeDate | `Date` | Central Xchange Date |
| 5 | cExchangeRate | `Float` | Central Xchange Rate |
| 6 | cVatAmount | `Float` | Central Vat Amount |
| 7 | centralCode | `String` | Central Code |
| 8 | centralCommissionDescription | `String` | Central Commission Description |
| 9 | code | `String` | Code |
| 10 | commissionCalcRule | `String` | Calculation rule for the commission |
| 11 | commissionFlatPercentage | `String` | Commission percentage or flat commission |
| 12 | commissionamount | `Float` | Commissionamount |
| 13 | commissionid | `String` | Commissionid |
| 14 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 15 | defaultYN | `String` | Default YN |
| 16 | deletedFlag | `String` | Deleted Flag |
| 17 | description | `String` | Description |
| 18 | holdARYN | `String` | Commission marked as Hold if transaction code AR_SETTLE_CODE used for payment. |
| 19 | holdAlwaysYN | `String` | Commission marked as Hold automatically. |
| 20 | holdPrepaidYN | `String` | Commission marked as Hold if  transaction code DEFAULT_PREPAID_COMM used for payment. |
| 21 | inactiveDate | `DateTime` | Inactive Date |
| 22 | inactiveflag | `String` | Inactive Flag |
| 23 | insertDate | `DateTime` | Insert Date |
| 24 | insertUser | `Float` | Insert User |
| 25 | internalDeletedflag | `String` | Deleted Flag |
| 26 | jRNUpdateDate | `Date` | JRN Update Date |
| 27 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 28 | locationID | `String` | Internal ID to uniquely identify the Property |
| 29 | masteralias | `Float` | Masteralias |
| 30 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 31 | perNight | `String` | Commission is per night Y/N |
| 32 | perNightAmount | `Float` | Per Night Amount |
| 33 | perStay | `String` | Commission is per stay Y/N |
| 34 | perStayAmount | `Float` | Per Stay Amount |
| 35 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 36 | property | `String` | Property |
| 37 | repItem | `String` | Reporting Item |
| 38 | repItemName | `String` | Reporting Item Name |
| 39 | repItemOrderby | `Float` | Reporting Item Orderby |
| 40 | repSellSequence | `Float` | Reporting Sell Sequence |
| 41 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 42 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 43 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 44 | sellSequence | `Float` | Sell Sequence |
| 45 | taxPercent | `Float` | Tax Amount for Commission. |
| 46 | updateDate | `DateTime` | Update Date |
| 47 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAuthorizerGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `String` | Code |
| 2 | compAuthorizerGroupDescription | `String` | Comp Authorizer Group Description |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | insertDate | `DateTime` | Insert Date |
| 6 | insertUser | `Float` | Insert User |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 10 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 11 | property | `String` | Property |
| 12 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 13 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 14 | rateCode | `String` | Rate Code |
| 15 | updateDate | `DateTime` | Update Date |
| 16 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAuthorizerGroupDetailDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | arrangementId | `Float` | Arrangement ID |
| 2 | authGroupCode | `String` | Auth Group Code |
| 3 | cCreditLimit | `Float` | Central Credit Limit |
| 4 | cExchangeDate | `Date` | Central Xchange Date |
| 5 | cExchangeRate | `Float` | Central Xchange Rate |
| 6 | cOccurrenceLimit | `Float` | Central Occurrence Limit |
| 7 | centralTransactionCodes | `String` | Central Transaction Codes |
| 8 | compRoutingCodes | `String` | Comp Routing Codes |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | dailyCreditLimit | `Float` | Daily Credit Limit |
| 11 | deletedFlag | `String` | Deleted Flag |
| 12 | groupHeaderId | `Float` | Group header ID used to assign transaction or arrangement codes to different limit groups |
| 13 | insertDate | `DateTime` | Insert Date |
| 14 | insertUser | `Float` | Insert User |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 18 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 19 | property | `String` | Code to uniquely identify the Property |
| 20 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 21 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 22 | transactionCodes | `String` | Transaction Codes |
| 23 | transferLimit | `Float` | Per instance limit for this group_header_id. |
| 24 | updateDate | `DateTime` | Update Date |
| 25 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAuthorizerDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRAccountNumber | `String` | AR Account Number |
| 2 | accessConfig | `String` | Allow user access to Configuration. |
| 3 | accessEod | `String` | Allow user access to End of Day. |
| 4 | accessObi | `String` | Allow user access to Opera BI. |
| 5 | accessOcis | `String` | Allow user access to OCIS. |
| 6 | accessOcm | `String` | Allow user access to Channel Mangement. |
| 7 | accessOcrm | `String` | Allow user access to OCRM. |
| 8 | accessOrms | `String` | Allow user access to Opera Revenue Management System. |
| 9 | accessOrs | `String` | Allow user access to ORS. |
| 10 | accessOxi | `String` | Allow user access to OXI. |
| 11 | accessOxihub | `String` | Allow user access to OXIHUB. |
| 12 | accessPms | `String` | Allow user access to PMS. |
| 13 | accessSc | `String` | Allow user access to SC. |
| 14 | accessScbi | `String` | Allow user access to OPERA S&C Analytics. |
| 15 | accessSfa | `String` | Allow user access to SFA. |
| 16 | accessUtil | `String` | Allow user access to Utilities. |
| 17 | accountLockedOutYn | `String` | Indicates if user is allowed to login in the application. |
| 18 | appPassword | `String` | The encrypted application password of this user |
| 19 | appUserDescription | `String` | Description about the User |
| 20 | appUserId | `Float` | App User ID |
| 21 | appUserType | `String` | Defines the type of user.Valid values: U and G U-->User :: G-->Group |
| 22 | appUserUniq | `String` | Unique internal ID...needed for ASP module as the same user name can't exists across chains. |
| 23 | authHeaderId | `Float` | Link from Authorizer_limits_header table. |
| 24 | authorizerGroup | `String` | Authorizer Group |
| 25 | authorizerId | `Float` | Authorizer ID |
| 26 | authorizerInactiveDate | `DateTime` | Date the authorizer became inactive |
| 27 | authorizerYn | `String` | Denotes if this user is an authorizer. Allowable values are 'Y' and 'N' |
| 28 | cCreditLimit | `Float` | Central Credit Limit |
| 29 | cExchangeDate | `Date` | Central Xchange Date |
| 30 | cExchangeRate | `Float` | Central Xchange Rate |
| 31 | cHourlyRate | `Float` | Central Hourly Rate |
| 32 | cOccurrenceLimit | `Float` | Central Occurrence Limit |
| 33 | cWeeklySalary | `Float` | Central Weekly Salary |
| 34 | centralTransactionCodes | `String` | Central  Transaction Codes |
| 35 | chainCode | `String` | Chain Code |
| 36 | comments | `String` | Comments |
| 37 | compRoutingCodes | `String` | Comp Routing Codes |
| 38 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 39 | dailyCreditLimit | `Float` | Daily Credit Limit |
| 40 | dateHired | `Date` | Date employee was hired |
| 41 | defCashierId | `Float` | Cashier ID for the User |
| 42 | defaultForm | `String` | Not Used |
| 43 | defaultLanguage | `String` | Default language of the user. |
| 44 | defaultMfnResort | `String` | Not used. |
| 45 | defaultReportgroup | `String` | Defaults the Report Module to this Report Group |
| 46 | defaultResort | `String` | Stores resort name to which user will log in every time |
| 47 | defaultTerminal | `String` | Default terminal of the user. |
| 48 | deletedFlag | `String` | Deleted Flag |
| 49 | deptId | `String` | Dept ID |
| 50 | description | `String` | Description |
| 51 | disabledUntil | `Date` | When account is disabled this date is set to date when account should be enabled again |
| 52 | empExtension | `String` | Employee Extension Number |
| 53 | empPager | `String` | Pager Number |
| 54 | empStatus | `String` | Emp Status |
| 55 | employeeIncentiveNumber | `String` | Identifies a hotel employee for incentive programs. |
| 56 | employeeNumber | `String` | This column is used by Starwood Hotels for Storing their internal employee number |
| 57 | expiresOn | `DateTime` | Date on which user ID will be disabled. |
| 58 | firstName | `String` | First Name |
| 59 | forcePasswordChangeYn | `String` | Requires the user to change the password at login. |
| 60 | fridayMax | `Float` | Max hours for Friday |
| 61 | fridayMin | `Float` | Min hours for Friday |
| 62 | generalFilepath | `String` | Stores General File path for Mailmerge |
| 63 | graceLogin | `Float` | Number of Logins allowed after password has expired |
| 64 | hireType | `String` | Type of hire: F-Full Time P-Part Time |
| 65 | hourlyRate | `Float` | If RATE_TYPE=H: hourly employee rate |
| 66 | hoursPerWeek | `Float` | Hours Per Week |
| 67 | inactiveDate | `DateTime` | Inactive Date |
| 68 | inactiveFrom | `DateTime` | Inactive Start Date |
| 69 | inactiveReasonCode | `String` | Reason Code for inactive status from REASON table |
| 70 | inactiveTo | `DateTime` | Inactive End Date |
| 71 | insertDate | `DateTime` | Insert Date |
| 72 | insertUser | `Float` | Insert User |
| 73 | internalYn | `String` | Internal Y/N |
| 74 | isSuperuser | `String` | When this is set to Y a user gets all the rights defined in application. |
| 75 | jRNUpdateDate | `Date` | JRN Update Date |
| 76 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 77 | laptopId | `Float` | Laptop ID |
| 78 | lastLoggedResort | `String` | Last property the user was logged in. |
| 79 | lastLoggedTimestamp | `Date` | Date and Time the User was logged in last time |
| 80 | lastName | `String` | Last Name |
| 81 | leadAddress | `String` | Lead Address Code determines primary receipient |
| 82 | leadAddressDet | `String` | Lead Address (email/fax no) |
| 83 | leadComm | `String` | Lead Communication Type |
| 84 | lockoutDate | `DateTime` | Timestamp with the useraccount was locked out. |
| 85 | loginAttempts | `Float` | Invalid password login attempts counter. |
| 86 | loginCro | `String` | Login Cro |
| 87 | loginDomain | `String` | Login Domain |
| 88 | maleFemale | `String` | Employee Gender |
| 89 | maxCheckoutDays | `Float` | Maximum number of days allowed for checkout in Laptop Module |
| 90 | maxDaysAfterCo | `Float` | Maximum number of days after checkout that a folio can be reopened. |
| 91 | maxUserSessions | `Float` | Maximum number of Opera Sessions allowed at single point of time. |
| 92 | mfnUserType | `String` | User type for OCM mode: [C]orporate User |
| 93 | mobileAlertsYn | `String` | Indiciates if alerts are send to mobile registered guests for required action and manual checkout.. |
| 94 | mondayMax | `Float` | Max hours for Monday |
| 95 | mondayMin | `Float` | Min hours for Monday |
| 96 | nCExchangeDate | `Date` | N Central Xchange Date |
| 97 | nCExchangeRate | `Float` | N Central Xchange Rate |
| 98 | nDeletedFlag | `String` | N Deleted Flag |
| 99 | nInsertDate | `DateTime` | N Insert Date |
| 100 | nInsertUser | `Float` | N Insert User |
| 101 | nUpdateDate | `Date` | N Update Date |
| 102 | nUpdateUser | `Float` | N Update User |
| 103 | occurrenceLimit | `Float` | Per instance limit for this group_header_id. |
| 104 | oraclePassword | `String` | not used |
| 105 | oracleUid | `Float` | Not used |
| 106 | oracleUser | `String` | not used |
| 107 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 108 | otMultiplier | `Float` | Overtime Multiplier |
| 109 | passwordChangeDays | `Float` | Period of Days the Password expires |
| 110 | passwordLastChange | `Date` | TimeStamp of last Password Change |
| 111 | personNameId | `Float` | Foreign key to NAME table that links this USER to an Employee |
| 112 | preventAccountLockout | `String` | Indicates if this user can be excluded from user account lock. |
| 113 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 114 | property | `String` | Property |
| 115 | propertyAccessYn | `String` | Indicates that a User Group has the purpose of defining property access only (no permissions allowed). |
| 116 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 117 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 118 | rateCode | `String` | Default rate code for this authorizer. |
| 119 | rateType | `String` | Rate Type |
| 120 | receiveBroadcastMsg | `String` | Receive Broadcast Msg |
| 121 | rehireYn | `String` | Indicates if a terminated employee shall be rehired |
| 122 | salaryInterval | `String` | Salary Interval: M-Monthly W-Weekly |
| 123 | saturdayMax | `Float` | Max hours for Saturday |
| 124 | saturdayMin | `Float` | Min hours for Saturday |
| 125 | serviceRequestAlertsYn | `String` | Indicates if this Application User can receive Alerts related to Service Requests. |
| 126 | sfaName | `String` | Sfa Name |
| 127 | srepCode | `String` | Srep Code |
| 128 | srepGroup | `String` | Assigned Sales Manager Group(s) |
| 129 | sundayMax | `Float` | Max hours for Sunday |
| 130 | sundayMin | `Float` | Min hours for Sunday |
| 131 | termReason | `String` | Termination Reason |
| 132 | terminatedDate | `Date` | Termination Date |
| 133 | thursdayMax | `Float` | Max hours for Thursday |
| 134 | thursdayMin | `Float` | Min hours for Thursday |
| 135 | timezoneRegion | `String` | Time zone region selected by the employee. |
| 136 | title | `String` | Title |
| 137 | transactionCodes | `String` | Transaction Codes |
| 138 | transferLimit | `Float` | Transfer Limit |
| 139 | tuesdayMax | `Float` | Max hours for Tuesday |
| 140 | tuesdayMin | `Float` | Min hours for Tuesday |
| 141 | updateDate | `DateTime` | Update Date |
| 142 | updateUser | `Float` | Update User |
| 143 | userFilepath | `String` | Store User File path. for Mailmerge |
| 144 | userGroupAdmin | `String` | User group can be granted by the user group administrator if value is 'Y'. |
| 145 | userIDCode | `String` | User ID Code |
| 146 | userPbxId | `Float` | PBX ID - referred as password to access PBX system |
| 147 | wednesdayMax | `Float` | Max hours for Wednesday |
| 148 | wednesdayMin | `Float` | Min hours for Wednesday |
| 149 | weekMax | `Float` | Maximum total hours this employee can work per week |
| 150 | weekMin | `Float` | Minimum total hours this employee can work per week |
| 151 | weeklySalary | `Float` | Weekly Salary |
| 152 | workPermitExpdate | `Date` | Workpermit Expiration date |
| 153 | workPermitNo | `String` | Working Permit Number |

[⬆ Back to Query](#query)

---

### ConfigurationResortBucketRedemptionCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `String` | Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | insertDate | `DateTime` | Insert Date |
| 6 | insertUser | `Float` | Insert User |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 10 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 11 | property | `String` | Property |
| 12 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 13 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 14 | transactionCode | `String` | Transaction Code |
| 15 | updateDate | `DateTime` | Update Date |
| 16 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCompRoutingCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | applyPerDayYN | `String` | Apply Per Day YN |
| 2 | arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| 3 | arrangementId | `Float` | Arrangement ID |
| 4 | bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| 5 | cExchangeDate | `Date` | Central Xchange Date |
| 6 | cExchangeRate | `Float` | Central Xchange Rate |
| 7 | cRoutingAmount | `Float` | Central Routing Amount |
| 8 | centralTransactionCodes | `String` | Central Transaction Codes |
| 9 | code | `String` | Code |
| 10 | compYn | `String` | Comp Y/N |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | description | `String` | Arrangement Description for the Transaction Code. |
| 14 | eligibleYn | `String` | Specifies the Eligibility to calculate membership points. |
| 15 | exportBucketType | `String` | User defined Export Bucket type. |
| 16 | friday | `String` | Friday |
| 17 | inactiveDate | `DateTime` | Inactive Date |
| 18 | inheritRateCodeYN | `String` | Inherit the authorizer rate code onto the reservation. |
| 19 | insertDate | `DateTime` | Insert Date |
| 20 | insertUser | `Float` | Insert User |
| 21 | jRNUpdateDate | `Date` | JRN Update Date |
| 22 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 23 | monday | `String` | Monday |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| 30 | routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| 31 | routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| 32 | routingPercentage | `Float` | Routing Percentage |
| 33 | saturday | `String` | Saturday |
| 34 | sunday | `String` | Sunday |
| 35 | thursday | `String` | Thursday |
| 36 | transactionCodes | `String` | Transaction Codes |
| 37 | tuesday | `String` | Tuesday |
| 38 | type | `String` | Type |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |
| 41 | wednesday | `String` | Wednesday |

[⬆ Back to Query](#query)

---

### ConfigurationResortCompTransactionCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aRNameId | `Float` | Ar Name ID |
| 2 | accountNumber | `String` | Account Number |
| 3 | accountingCode | `String` | Accounting Code |
| 4 | acctrecvprofileid | `Float` | Acctrecvprofileid |
| 5 | adjTrxCode | `String` | Adj Transaction Code |
| 6 | adjtranscodeid | `String` | Adjtranscodeid |
| 7 | arrangeCode | `String` | Arrange Code |
| 8 | cDefaultPrice | `Float` | Central Default Price |
| 9 | cExchangeDate | `Date` | Central Xchange Date |
| 10 | cExchangeRate | `Float` | Central Xchange Rate |
| 11 | cExportBucket | `Float` | Central Export Bucket |
| 12 | cMaxAmount | `Float` | Central Max Amt |
| 13 | cMinimumAmount | `Float` | Central Min Amt |
| 14 | cCCode | `String` | CC Code |
| 15 | cRSTaxDesc | `String` | Crs Tax Description |
| 16 | ccType | `String` | Cc Type |
| 17 | centralCode | `String` | Central Code |
| 18 | centralDescription | `String` | Central Description |
| 19 | centralGroup | `String` | Central Group |
| 20 | centralSubgroup | `String` | Central Subgroup |
| 21 | checkNumberMandatoryYN | `String` | Check Number Mandatory YN |
| 22 | class1MandatoryYn | `String` | Class 1 Mandatory Y/N |
| 23 | class2MandatoryYn | `String` | Class 2 Mandatory Y/N |
| 24 | code | `String` | Code |
| 25 | commission | `Float` | Commission |
| 26 | compNightsYn | `String` | Comp Nights Y/N |
| 27 | compPaymentsYN | `String` | Comp Payments YN |
| 28 | compYn | `String` | Comp Y/N |
| 29 | corpPropFlag | `String` | Corp Prop Flag |
| 30 | corporateDescription | `String` | Corporate Description |
| 31 | currency | `String` | Currency |
| 32 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 33 | dailyPlanFolio | `Float` | Daily Plan Folio |
| 34 | dedOwnerRevenueYN | `String` | Ded Owner Rev Y/N |
| 35 | defaultPrice | `Float` | Default Price |
| 36 | deferredYn | `String` | Deferred Y/N |
| 37 | deletedFlag | `String` | Deleted Flag |
| 38 | depositPostingOnlyYn | `String` | Deposit Posting Only Y/N |
| 39 | depositType | `String` | Stores the type of the deposit: possible values "RECEIPT" or "FOLIO". |
| 40 | description | `String` | Description |
| 41 | eInvoiceYn | `String` | E Invoice Y/N |
| 42 | expenseFolio | `Float` | Expense Folio |
| 43 | exportBucket | `Float` | Export Bucket |
| 44 | externalPaymentCode | `String` | External Payment Code |
| 45 | fiscalPaymentYn | `String` | Fiscal Payment Y/N |
| 46 | fiscalTrxCodeType | `String` | Fiscal Transaction Code Type |
| 47 | foreignCurrencyID | `String` | Foreign Currency ID |
| 48 | frequentFlyerYn | `String` | Frequent Flyer Y/N |
| 49 | generatesInclusiveYN | `String` | Generates Inclusive YN |
| 50 | group | `String` | Group |
| 51 | groupFolio | `Float` | Group Folio |
| 52 | groupPointsRedemptionYN | `String` | Gp Points Redemption Y/N |
| 53 | inHouseDepositYN | `String` | To indicate that the transaction code can be used as a Deposit Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| 54 | inHousePayYN | `String` | To indicate that the transaction code can be used as a Payment Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| 55 | inHouseSalesYN | `String` | To indicate that the transaction code can be used as a Sales Transaction Code in Cross Postings. There can be only one transaction code per one resort. |
| 56 | inactiveDate | `Date` | Inactive Date |
| 57 | inactiveflag | `String` | Inactive Flag |
| 58 | includeIn8300Yn | `String` | Include In 8300 Y/N |
| 59 | includeInDepositCXLRuleYN | `String` | Include in Deposit/CXL Rule YN |
| 60 | indBilling | `String` | Individual Billing |
| 61 | indCash | `String` | Individual Cash |
| 62 | individualAr | `String` | Ind AR |
| 63 | individualDepositYN | `String` | Ind Deposit Y/N |
| 64 | insertDate | `DateTime` | Insert Date |
| 65 | insertUser | `Float` | Insert User |
| 66 | internalDeletedflag | `String` | Deleted Flag |
| 67 | internalYn | `String` | Internal Y/N |
| 68 | isManualPostAllowed | `String` | Is Manual Post Allowed |
| 69 | jRNUpdateDate | `Date` | JRN Update Date |
| 70 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 71 | locationID | `String` | Internal ID to uniquely identify the Property |
| 72 | manualPostCoversYn | `String` | Manual Post Covers Y/N |
| 73 | maximumAmount | `Float` | Maximum Amount |
| 74 | minimumAmount | `Float` | Minimum Amount |
| 75 | nonTaxableYn | `String` | Non Taxable Y/N |
| 76 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 77 | ownerRevenueYN | `String` | Owner Rev Y/N |
| 78 | paymentTaxInvoiceYn | `String` | Payment Tax Invoice Y/N |
| 79 | paymentType | `String` | Payment Type |
| 80 | paymentmethodid | `String` | Paymentmethodid |
| 81 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 82 | printReceiptYN | `String` | Flag to indicate if a receipt has to be printed on posting the transaction used in Opera 9. |
| 83 | processingType | `String` | Type of process that generated this payment.  IE PaymentCheck out AR or Passerby. |
| 84 | property | `String` | Property |
| 85 | quantityCode | `String` | Quantity Code |
| 86 | repItem | `String` | Reporting Item |
| 87 | repItemName | `String` | Reporting Item Name |
| 88 | repItemOrderby | `Float` | Reporting Item Orderby |
| 89 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 90 | resultIncludedInSumArray | `String` | Result Included In Sum Array |
| 91 | revenueBucketId | `Float` | Rev Bucket ID |
| 92 | revenueGroupId | `Float` | Rev Gp ID |
| 93 | revenueGroupYN | `String` | Revenue Group YN |
| 94 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 95 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 96 | rotationRevenueYN | `String` | Rotation Rev Y/N |
| 97 | roundingFactorYN | `String` | Rounding Factor YN |
| 98 | serviceRecoveryTrxCode | `String` | Service Recovery Adjustment. |
| 99 | subgroup | `String` | Subgroup |
| 100 | taxCode | `Float` | Tax Code |
| 101 | tcBofInterface | `String` | Not Used. |
| 102 | tcBofInterface2 | `String` | Not Used. |
| 103 | tcBofRefCode | `String` | Not Used. |
| 104 | tcBofRefCode2 | `String` | Not Used. |
| 105 | tcResort2 | `String` | Not Used. |
| 106 | tcTransactionType | `String` | Transaction Code Transaction Type |
| 107 | tclCodeDfltCl1 | `String` | Tcl Code Dflt Cl1 |
| 108 | tclCodeDfltCl2 | `String` | Tcl Code Dflt Cl2 |
| 109 | transactionActionId | `Float` | Trx Action ID |
| 110 | transactionCodeResort | `String` | Not Used. |
| 111 | transactionType | `String` | Transaction Type |
| 112 | transcodearrangementid | `String` | Transcodearrangementid |
| 113 | transcodeid | `String` | Transcodeid |
| 114 | transgroupid | `String` | Transgroupid |
| 115 | transsubgroupid | `String` | Transsubgroupid |
| 116 | trxCodeDisplay | `String` | Transaction Code Display |
| 117 | trxCodeType | `String` | Transaction Code Type |
| 118 | trxServiceType | `String` | Transaction Service Type |
| 119 | trxTaxTypeCode | `String` | Transaction Tax Type Code |
| 120 | upcCode | `String` | Upc Code |
| 121 | updateDate | `DateTime` | Update Date |
| 122 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionCodeCompExternalReferenceDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | associatedTransactionCode | `String` | Associated Transaction Code |
| 2 | associatedTransactionDescription | `String` | Associated Transaction Description |
| 3 | centralAssociatedTransactionCode | `String` | Central Associated Transaction Code |
| 4 | centralAssociatedTransactionDescription | `String` | Central Associated Transaction Description |
| 5 | compTrxCode | `String` | Comp Transaction Code that the trx_code value will be posted against |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | jRNUpdateDate | `Date` | JRN Update Date |
| 9 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 10 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 11 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 12 | property | `String` | Code to uniquely identify the Property |
| 13 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 14 | rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### ConfigurationResortCodeGeneratesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adjustmentType | `String` | Adjustment Type |
| 2 | amount | `Float` | Amount |
| 3 | amountFromScheduleYn | `String` | Whether to take the taxes from Price Schedules. |
| 4 | cAmount | `Float` | Central Amount |
| 5 | cExchangeDate | `Date` | Central Xchange Date |
| 6 | cExchangeRate | `Float` | Central Xchange Rate |
| 7 | calculationSequence | `Float` | Sequence in which the taxes should be applied. |
| 8 | centralDescription | `String` | Central Description |
| 9 | centralGeneratedCode | `String` | Central Generated Code |
| 10 | currency | `String` | Currency |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | description | `String` | Description |
| 14 | generateRules | `String` | Generate Rules |
| 15 | generatedBy | `String` | Generated By |
| 16 | generatedCode | `String` | Generated Code |
| 17 | generatedPrintedOnFolioYn | `String` | Whether to print on folio. |
| 18 | id | `Float` | ID |
| 19 | insertDate | `DateTime` | Insert Date |
| 20 | insertUser | `Float` | Insert User |
| 21 | jRNUpdateDate | `Date` | JRN Update Date |
| 22 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 23 | nameTaxType | `String` | Name Tax Type |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | percentage | `Float` | Percentage |
| 26 | percentageBaseCode | `Float` | Indicates if the tax is based on a percentage. It would have a value of 0 if based on BASE amount 1 if on S1 2 if based on S2 3 if based on S3. |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Code to uniquely identify the Property |
| 29 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 30 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 31 | resultIncludedInSumArray | `String` | Result Included In Sum Array |
| 32 | roundingMethod | `String` | Rounding method to be used when calculating a generate amount. Allowed values are UP DOWN NONE and NULL. |
| 33 | seqBy | `Float` | Sequence By |
| 34 | stopDays | `Float` | Days after which the generates will not be posted for long standing guests. |
| 35 | subTotal1YN | `String` | Sub-Total 1 YN |
| 36 | subTotal2YN | `String` | Sub-Total 2 YN |
| 37 | subTotal3YN | `String` | Sub-Total 3 YN |
| 38 | tcDsi | `Float` | Transaction Code Dsi |
| 39 | tcGroup | `String` | Transaction Code Group |
| 40 | tcGroupGenerator | `String` | Group generator. |
| 41 | tcOrganizationid | `Float` | Transaction Code Organizationid |
| 42 | tcSubgroup | `String` | Transaction Code Subgroup |
| 43 | tcSubgroupGenerator | `String` | Subgroup generator. |
| 44 | tclCodeGenerator | `String` | Identify if the taxes are generated on the Class. |
| 45 | tcrType | `String` | Flag to indicate the addon tax. |
| 46 | transactionCodeResort | `String` | Not Used. |
| 47 | transactionCodeTrxCode | `String` | Tc Transaction Code |
| 48 | trxCodeGenerator | `String` | Transaction Code Generator |
| 49 | udfFunction | `String` | Udf Function |
| 50 | udfInverse | `String` | Not used currently. |
| 51 | updateDate | `DateTime` | Update Date |
| 52 | updateUser | `Float` | Update User |
| 53 | useTaxBracketYn | `String` | Flag to indicate if tax brackets are used for this tax. |

[⬆ Back to Query](#query)

---

### ConfigurationResortCompTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralCode | `String` | Central Code |
| 2 | centralDescription | `String` | Central Description |
| 3 | centralSequence | `Float` | Central Sequence |
| 4 | code | `String` | Code |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | description | `String` | Description |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | property | `String` | Property |
| 15 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 16 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 17 | repItem | `String` | Reporting Item |
| 18 | repItemName | `String` | Reporting Item Name |
| 19 | repItemOrderby | `Float` | Reporting Item Orderby |
| 20 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 21 | sequence | `Float` | Sequence |
| 22 | updateDate | `DateTime` | Update Date |
| 23 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBarScheduleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 2 | date | `Date` | Date |
| 3 | dayOfWeek | `String` | Day of Week |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | description | `String` | Description |
| 6 | inactiveDate | `Date` | Inactive Date |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | lengthOfStay | `Float` | Length of Stay |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | property | `String` | Property |
| 15 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 16 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 17 | rateCode | `String` | Rate Code |
| 18 | updateDate | `DateTime` | Update Date |
| 19 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCityTaxRangeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | amountFrom | `Float` | Defines the starting value for the amount range. |
| 2 | amountTo | `Float` | Defines the ending value for the amount range. |
| 3 | chainCode | `String` | Chain Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | insertDate | `DateTime` | Insert Date |
| 7 | insertUser | `Float` | Insert User |
| 8 | intervalAmount | `Float` | Defines the incremental value for the amounts that qualify for additional tax amounts. |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | packageFormulaRangeId | `Float` | Oracle sequence to maintain uniqueness. |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | property | `String` | Property |
| 15 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 16 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 17 | recordType | `String` | Record Type |
| 18 | taxAmount | `Float` | Tax Amount |
| 19 | taxPercentage | `Float` | The Luxury Tax Percentage for the country for which this record belongs to. |
| 20 | taxRangeType | `String` | Stores the Japanese Tax Range Type. |
| 21 | updateDate | `DateTime` | Update Date |
| 22 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyDayTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adder | `Float` | Amount to be added  before showing in rate query |
| 2 | centralDayTypesCode | `String` | Central Day Types Code |
| 3 | centralSequence | `Float` | Central Sequence |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | dayTypesCode | `String` | Day Types Code |
| 6 | dayTypesDescription | `String` | Day Type description |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | dtRemarks | `String` | Remarks for the day type |
| 11 | inactiveDate | `Date` | Inactive Date |
| 12 | insertDate | `DateTime` | Insert Date |
| 13 | insertUser | `Float` | Insert User |
| 14 | jRNUpdateDate | `Date` | JRN Update Date |
| 15 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 16 | multiplier | `Float` | Amount to be multiplied before showing in rate query |
| 17 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 18 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 19 | property | `String` | Property |
| 20 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 21 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 22 | repDtRemarks | `String` | Reporting Dt Remarks |
| 23 | repItem | `String` | Reporting Item |
| 24 | repItemName | `String` | Reporting Item Name |
| 25 | repItemOrderby | `Float` | Reporting Item Orderby |
| 26 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 27 | sequence | `Float` | Sequence |
| 28 | updateDate | `DateTime` | Update Date |
| 29 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDisplaySetDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyCalendarEventDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activeYN | `String` | Active YN |
| 2 | blackoutYn | `String` | Indicates whether an event is a blackout event or not. |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | code | `String` | Code |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedFlag | `String` | Deleted Flag |
| 9 | description | `String` | Description of the event |
| 10 | inactiveDate | `DateTime` | Inactive Date |
| 11 | insertDate | `DateTime` | Insert Date |
| 12 | insertUser | `Float` | Insert User |
| 13 | jRNUpdateDate | `Date` | JRN Update Date |
| 14 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 15 | oRMSEventYN | `String` | Orms Event Y/N |
| 16 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 17 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 18 | property | `String` | Property |
| 19 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 20 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 21 | repItem | `String` | Reporting Item |
| 22 | repItemName | `String` | Reporting Item Name |
| 23 | repItemOrderby | `Float` | Reporting Item Orderby |
| 24 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 25 | sequence | `Float` | Sequence |
| 26 | showInOperaYn | `String` | Indicates if the event should be displayed in Opera. |
| 27 | updateDate | `DateTime` | Update Date |
| 28 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortRateHurdlesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | actualRoomsSold | `Float` | Actual Rooms Sold |
| 2 | amountOfHurdleRate | `Float` | Amount of Hurdle Rate |
| 3 | cExchangeDate | `Date` | Central Xchange Date |
| 4 | cExchangeRate | `Float` | Central Xchange Rate |
| 5 | cHurdle | `Float` | Central Hurdle |
| 6 | cORMSPriceRoomDelta | `Float` | Central Orms Price Room Delta |
| 7 | centralRoomClass | `String` | Central Room Class |
| 8 | centralRoomClassDescription | `String` | Central Room Class Description |
| 9 | centralRoomType | `String` | Central Room Type |
| 10 | centralRoomTypeDescription | `String` | Central Room Type Description |
| 11 | centralYieldCategory | `String` | Central Yield Category |
| 12 | centralYieldCategoryDescription | `String` | Central Yield Category Description |
| 13 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 14 | deletedflag | `String` | Deleted Flag |
| 15 | delta | `Float` | Delta |
| 16 | hurdleDate | `Date` | Hurdle Date |
| 17 | hurdlerateid | `Float` | Hurdlerateid |
| 18 | insertDate | `DateTime` | Insert Date |
| 19 | insertUser | `Float` | Insert User |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | lengthOfStay | `Float` | Length of Stay |
| 23 | locationID | `String` | Internal ID to uniquely identify the Property |
| 24 | maxRoomsSold | `Float` | Max Rooms Sold |
| 25 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 26 | overrideYN | `String` | Override YN |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 30 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 31 | roomCategoryLabel | `String` | Room Category Label |
| 32 | roomClass | `String` | Room Class |
| 33 | roomClassDescription | `String` | Room Class Description |
| 34 | roomType | `String` | Room Type |
| 35 | roomTypeDescription | `String` | Room Type Description |
| 36 | roomcategoryid | `String` | Roomcategoryid |
| 37 | roomsToSellBeforeDeltaIsApplied | `Float` | Rooms to Sell before Delta is Applied |
| 38 | updateDate | `DateTime` | Update Date |
| 39 | updateUser | `Float` | Update User |
| 40 | yieldCategory | `String` | Yield Category |
| 41 | yieldCategoryDescription | `String` | Yield Category Description |
| 42 | yieldcategoryid | `String` | Yieldcategoryid |
| 43 | yieldmarkettype | `String` | Yieldmarkettype |

[⬆ Back to Query](#query)

---

### ConfigurationResortProductDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | addtorateflag | `String` | Addtorateflag |
| 2 | alternateCodes | `String` | Alternate Codes |
| 3 | arrangementCode | `String` | Arrangement Code |
| 4 | beginSellDate | `Date` | Begin Sell Date |
| 5 | bookingDuration | `Float` | Not used |
| 6 | calculationRule | `String` | Calculation Rule |
| 7 | cateringYn | `String` | Catering Y/N |
| 8 | centralAlternateCodes | `String` | Central Alternate Codes |
| 9 | centralPackage | `String` | Central Package |
| 10 | centralPackageGroupCode | `String` | Central Package Group Code |
| 11 | centralPackageGroupDescription | `String` | Central Package Group Description |
| 12 | centralPackageLoss | `String` | Central Package Loss |
| 13 | centralPackageOverage | `String` | Central Package Overage |
| 14 | centralPackageProfit | `String` | Central Package Profit |
| 15 | centralTransactionCode | `String` | Central Transaction Code |
| 16 | currency | `String` | Currency |
| 17 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 18 | deletedFlag | `String` | Deleted Flag |
| 19 | deliveryTimeReqrdYn | `String` | Indicates if a Delivery Time is required. |
| 20 | description | `String` | Description |
| 21 | endSellDate | `Date` | End Sell Date |
| 22 | externalLocked | `String` | External Locked |
| 23 | flexibleDurationYn | `String` | Not used |
| 24 | forecastGroup | `String` | Package forcast group code |
| 25 | forecastGroupCode | `String` | Not used |
| 26 | forecastNextDayYN | `String` | Forecast Next Day YN |
| 27 | foreignCurrencyID | `String` | Foreign Currency ID |
| 28 | formula | `String` | Formula |
| 29 | genPlAtEodOfCoDate | `String` | Gen Pl At Eod of Co Date |
| 30 | inactiveflag | `String` | Inactive Flag |
| 31 | insertDate | `DateTime` | Insert Date |
| 32 | insertUser | `Float` | Insert User |
| 33 | internalDeletedflag | `String` | Deleted Flag |
| 34 | inventoriedflag | `String` | Inventoriedflag |
| 35 | jRNUpdateDate | `Date` | JRN Update Date |
| 36 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 37 | locationID | `String` | Internal ID to uniquely identify the Property |
| 38 | longInfo | `String` | Long Info |
| 39 | maxPersons | `String` | Maximum number of persons |
| 40 | minimumAdvBookDays | `Float` | Minimum Advance Booking Days required for the product. |
| 41 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 42 | outletCode | `String` | Outlet Code |
| 43 | overrideFixedRateYn | `String` | Override Fixed Rate Y/N |
| 44 | package | `String` | Package |
| 45 | packageAllowanceYN | `String` | Package Allowance YN |
| 46 | packageDescription | `String` | Package Description |
| 47 | packageGroupCode | `String` | Package Group Code |
| 48 | packageGroupDescription | `String` | Package Group Description |
| 49 | packageLoss | `String` | Package Loss |
| 50 | packageOverage | `String` | Package Overage |
| 51 | packageOverageTaxInclusiveYN | `String` | Package Overage Tax Inclusive YN |
| 52 | packageProfit | `String` | Package Profit |
| 53 | pkgforecastgrpid | `String` | Pkgforecastgrpid |
| 54 | postNextDayYN | `String` | Post Next Day YN |
| 55 | postingRhythm | `String` | Posting Rhythm |
| 56 | postingType | `String` | Type of package (group element) |
| 57 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 58 | printseparateflag | `String` | Printseparateflag |
| 59 | productid | `String` | Productid |
| 60 | property | `String` | Property |
| 61 | redemptionproductflag | `String` | Redemptionproductflag |
| 62 | repDescription | `String` | Rep Description |
| 63 | repItem | `String` | Reporting Item |
| 64 | repItemName | `String` | Reporting Item Name |
| 65 | repItemOrderby | `Float` | Reporting Item Orderby |
| 66 | repTrxCodeDesc | `String` | Rep Trx Code Desc |
| 67 | repUpdateDate | `Date` | Reporting Updatedate |
| 68 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 69 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 70 | sellSeparateYN | `String` | Sell Separate YN |
| 71 | sellowsflag | `String` | Sellowsflag |
| 72 | shortDescription | `String` | Short Description |
| 73 | standardDuration | `Float` | Not used |
| 74 | standardPersons | `String` | Not used |
| 75 | taxInclusiveYN | `String` | Tax included Y/N |
| 76 | ticketsYn | `String` | Indicates a Reservation Ticket Package. |
| 77 | transactionCode | `String` | Transaction Code |
| 78 | updateDate | `DateTime` | Update Date |
| 79 | updateUser | `Float` | Update User |
| 80 | validEndTime | `Date` | Valid End Time |
| 81 | validStartTime | `Date` | Valid Start Time |

[⬆ Back to Query](#query)

---

### ConfigurationResortItemPackageDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 2 | deletedFlag | `String` | Deleted Flag |
| 3 | description | `String` | Description |
| 4 | insertDate | `DateTime` | Insert Date |
| 5 | insertUser | `Float` | Insert User |
| 6 | item | `String` | Item of configuration data. |
| 7 | itemId | `Float` | Item ID |
| 8 | itemProdId | `Float` | Unqiue ID from ITEM_PACKAGES_SEQNO |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 13 | product | `String` | Product |
| 14 | property | `String` | Code to uniquely identify the Property |
| 15 | qunatity | `Float` | Qunatity |
| 16 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 17 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 18 | updateDate | `DateTime` | Update Date |
| 19 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortRateProductPriceDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allowanceAmount | `Float` | Allowance for the product. |
| 2 | bucket2AllowanceAmount | `Float` | Allowance for the product for children in age bucket2. |
| 3 | bucket2Price | `Float` | Product price for children in age bucket2. |
| 4 | bucket3AllowanceAmount | `Float` | Allowance for the product for children in age bucket3. |
| 5 | bucket3Price | `Float` | Product price for children in age bucket3. |
| 6 | cAllowanceAmount | `Float` | Central Allowance Amount |
| 7 | cBucket2AllowanceAmount | `Float` | Central Bucket2 Allowance Amount |
| 8 | cBucket2Price | `Float` | Central Bucket2 Price |
| 9 | cBucket3AllowanceAmount | `Float` | Central Bucket3 Allowance Amount |
| 10 | cBucket3Price | `Float` | Central Bucket3 Price |
| 11 | cExchangeDate | `Date` | Central Xchange Date |
| 12 | cExchangeRate | `Float` | Central Xchange Rate |
| 13 | cPrice | `Float` | Central Price |
| 14 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 15 | day1 | `String` | Day1 |
| 16 | day2 | `String` | Day2 |
| 17 | day3 | `String` | Day3 |
| 18 | day4 | `String` | Day4 |
| 19 | day5 | `String` | Day5 |
| 20 | day6 | `String` | Day6 |
| 21 | day7 | `String` | Day7 |
| 22 | deletedFlag | `String` | Deleted Flag |
| 23 | endDate | `Date` | End Date |
| 24 | inactiveDate | `Date` | Inactive Date |
| 25 | insertDate | `DateTime` | Insert Date |
| 26 | insertUser | `Float` | Insert User |
| 27 | jRNUpdateDate | `Date` | JRN Update Date |
| 28 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 29 | maximumGuests | `Float` | Maximum number of persons |
| 30 | maximumNights | `Float` | Maximum Nights. |
| 31 | minimumGuests | `Float` | Minimum number of persons for the rate product price. |
| 32 | minimumNights | `Float` | Minimum number of stay nights for the rate product price. |
| 33 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 34 | pointsRequired | `Float` | Points Required |
| 35 | price | `Float` | Price |
| 36 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 37 | product | `String` | Product |
| 38 | property | `String` | Property |
| 39 | propertyRateProductDetailId | `Float` | Internal id |
| 40 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 41 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 42 | rateCode | `String` | Rate Code |
| 43 | seasonCode | `String` | Season Code |
| 44 | startDate | `Date` | Start Date |
| 45 | updateDate | `DateTime` | Update Date |
| 46 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPackageForecastGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activeYN | `String` | Active YN |
| 2 | code | `String` | Package forcast group code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | description | `String` | Description |
| 6 | inactiveDate | `DateTime` | Inactive Date |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 13 | property | `String` | Property |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | repItem | `String` | Reporting Item |
| 17 | repItemName | `String` | Reporting Item Name |
| 18 | repItemOrderby | `Float` | Reporting Item Orderby |
| 19 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 20 | sequence | `Float` | Sequence |
| 21 | updateDate | `DateTime` | Update Date |
| 22 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPromotionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | authorizerId | `Float` | Authorizer ID |
| 2 | bookingEndDate | `Date` | Last Date Bookings can be made using the promotion. |
| 3 | bookingStartDate | `Date` | First Date Bookings can be made using the promotion. |
| 4 | category | `String` | Category |
| 5 | centralDescription | `String` | Promotion Name. |
| 6 | chainCode | `String` | Chain Code |
| 7 | checkInTime | `Date` | CheckIn Time for Promotion. |
| 8 | checkOutTime | `Date` | Check Out Time for Promotion. |
| 9 | code | `String` | Code |
| 10 | couponExChars | `String` | Exclude Characters while generating custom coupons. |
| 11 | couponGenFormat | `String` | Format for Custom based Random Generation option. 9 :Numbers U  :  upper case alpha characters only X  :  any alpha-numeric characters (upper). |
| 12 | couponGenOption | `String` | Generation option. N :Numbers U  :  upper case alpha characters only X  :  any alpha-numeric characters (upper) C  :  Custom Format. |
| 13 | couponLength | `Float` | Length of coupon code. |
| 14 | couponPrefix | `String` | Any Prefix to be appended to custom coupons. |
| 15 | couponSuffix | `String` | Any Suffix to be appended to custom coupons. |
| 16 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 17 | deletedflag | `String` | Deleted Flag |
| 18 | description | `String` | Description |
| 19 | group | `String` | Group |
| 20 | idRequiredDescription | `String` | Description of id requirements. |
| 21 | idRequiredYN | `String` | Indicates if an id is required for the promotion. |
| 22 | inactiveDate | `Date` | Inactive Date |
| 23 | inactiveflag | `String` | Inactive Flag |
| 24 | information | `String` | Information for the promotion. |
| 25 | insertDate | `DateTime` | Insert Date |
| 26 | insertUser | `Float` | Insert User |
| 27 | instructions | `String` | Promotion Instructions for the property. |
| 28 | jRNUpdateDate | `Date` | JRN Update Date |
| 29 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 30 | limitedTimePromotionYn | `String` | Indicate if promotion is limited time use. |
| 31 | locationID | `String` | Internal ID to uniquely identify the Property |
| 32 | lockedByCode | `String` | Code of the system that is managing this record: local system application name or external system database id |
| 33 | lockedByType | `String` | Type of the system that is managing this record: L for local and E for external system. |
| 34 | longDescription | `String` | Description of Promotion. |
| 35 | mktgprogramid | `String` | Mktgprogramid |
| 36 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 37 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 38 | promoSequenceId | `Float` | Promo Seq ID |
| 39 | promotionid | `String` | Promotionid |
| 40 | property | `String` | Property |
| 41 | repItem | `String` | Reporting Item |
| 42 | repItemName | `String` | Reporting Item Name |
| 43 | repUpdateDate | `Date` | Reporting Updatedate |
| 44 | reportingPromoSequenceId | `String` | Rep Promo Seq ID |
| 45 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 46 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 47 | setOrAccountFlag | `String` | Indicates if set(S) or account (a) is required for booking. |
| 48 | stayEndDate | `Date` | End Date a guest can stay for the promotion. |
| 49 | stayStartDate | `Date` | First Date a guest can stay for the promotion. |
| 50 | updateDate | `DateTime` | Update Date |
| 51 | updateOutsideBookingDatesYN | `String` | Indicates if reservations with this promotion can be updated outside the promotion booking dates. |
| 52 | updateUser | `Float` | Update User |
| 53 | upgradeAllowedYN | `String` | Indicates if upgrades are allowed for the promotion. |
| 54 | voucherBenefitCode | `String` | Voucher Benefit Code |

[⬆ Back to Query](#query)

---

### ConfigurationResortPromotionRateDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | chainCode | `String` | Chain Code |
| 2 | code | `String` | Code |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | description | `String` | How  the Rate Plan applies to the promotion such as Booking awardmiles |
| 6 | jRNUpdateDate | `Date` | JRN Update Date |
| 7 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 8 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 9 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 10 | promoCode | `String` | Promo Code |
| 11 | property | `String` | Property |
| 12 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 13 | rNAUpdateDate | `DateTime` | RNA Update Date |

[⬆ Back to Query](#query)

---

### ConfigurationResortPromotionCodeRoutingInstructionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | authorizerId | `Float` | Authorizer ID |
| 2 | authorizerName | `String` | Authorizer Name |
| 3 | autoPopulateRoutingYn | `String` | Activates auto population of routing instructions. |
| 4 | beginDate | `Date` | Begin Date |
| 5 | centralTransactionCodes | `String` | Central  Transaction Codes |
| 6 | chainCode | `String` | Chain Code |
| 7 | comments | `String` | Comments |
| 8 | compPreApprovalRequiredYn | `String` | Comp Pre Approval Required Y/N |
| 9 | covers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| 10 | creditLimit | `Float` | Credit Limit |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | dailyYn | `String` | Daily Y/N |
| 13 | deletedFlag | `String` | Deleted Flag |
| 14 | endDate | `Date` | End Date |
| 15 | folioView | `Float` | Folio View |
| 16 | friday | `String` | Friday |
| 17 | membershipId | `Float` | Membership ID |
| 18 | monday | `String` | Monday |
| 19 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 20 | percentage | `Float` | Percentage |
| 21 | promoCode | `String` | Promo Code |
| 22 | promptForAuthorizerYn | `String` | Indicates if the user should be prompted for an Authorizer. |
| 23 | property | `String` | Property |
| 24 | routingCodes | `String` | Reservation routing code. |
| 25 | saturday | `String` | Saturday |
| 26 | sunday | `String` | Sunday |
| 27 | thursday | `String` | Thursday |
| 28 | transactionCodes | `String` | Transaction Codes |
| 29 | tuesday | `String` | Tuesday |
| 30 | wednesday | `String` | Wednesday |

[⬆ Back to Query](#query)

---

### ConfigurationResortRateCategoriesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessDate | `Date` | Business Date |
| 2 | centralDescription | `String` | Central Description |
| 3 | centralRateCategory | `String` | Central Rate Category |
| 4 | centralRateClass | `String` | Central Rate Class |
| 5 | centralRateClassDescription | `String` | Central Rate Class Description |
| 6 | centralSequence | `Float` | Central Sequence |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedflag | `String` | Deleted Flag |
| 9 | displayDefaultYn | `String` | Display the rate category Y/N |
| 10 | displaySet | `String` | Display Set |
| 11 | endDate | `Date` | End Date |
| 12 | exportBucketCode | `String` | Export Bucket Code |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | locationID | `String` | Internal ID to uniquely identify the Property |
| 19 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 20 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 21 | property | `String` | Property |
| 22 | rateCategory | `String` | Rate Category |
| 23 | rateCategoryDescription | `String` | Rate Category Description |
| 24 | rateClass | `String` | Rate Class |
| 25 | rateClassDescription | `String` | Rate Class Description |
| 26 | rateTier | `String` | Rate Tier |
| 27 | ratecategoryid | `String` | Ratecategoryid |
| 28 | ratetierid | `String` | Ratetierid |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 33 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 34 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 35 | sequence | `Float` | Sequence |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortArticleDetailsType

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

### ConfigurationResortCreditCardTypesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | canDeleteYn | `String` | Can Delete Y/N |
| 2 | code | `String` | Code |
| 3 | comments | `String` | Comments |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | description | `String` | Description |
| 7 | displayColor | `String` | Display Color |
| 8 | entityName | `String` | Entity Name |
| 9 | inactiveDate | `DateTime` | Inactive Date |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | languageCode | `String` | Language Code |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | property | `String` | Property |
| 18 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 19 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 20 | sequence | `Float` | Sequence |
| 21 | updateDate | `DateTime` | Update Date |
| 22 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPaymentMethodDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | addressVerificationYn | `String` | Determines if this payment type captures the credit card billing address information during payment. |
| 2 | authAtCheckinYn | `String` | Authorization has to be done during check in. |
| 3 | authDuringStayYn | `String` | Authorization is done during stay. |
| 4 | authReversalYn | `String` | Authorization reversal  has to be done. |
| 5 | authStlmtAtCheckOutYn | `String` | Indicates if this payment method supports credit card interface functionality of sending a combined message for Auth & Settlement. |
| 6 | autopayAtCheckinYn | `String` | Determines if this payment type can be used in Auto Advance Bill and Payment process after Check-In if this value equals 'Y'. |
| 7 | bonusCheckType | `String` | The type of bonus check. |
| 8 | calcPoints | `String` | Indicates if points have to be calculated. [A]lways [P]rompt to check. NULL = No points will be calculated. |
| 9 | cardNumberLength | `String` | Comma separated credit card number lengths. |
| 10 | cardPrefix | `String` | Card Prefix |
| 11 | cashSurchargeYn | `String` | Indicates that the payment method selected is subject to an additional surcharge. The surcharge amount / percentage is based on range of amount. The functionality is introduced for Algeria and is only applicable for Cash. |
| 12 | ccTrxFeePct | `Float` | Fee (surcharge) percentage amount for a credit card transaction. |
| 13 | ccTrxFeeThreshold | `Float` | Fee (surcharge) threshold that will indicate the minimum credit card transaction amount for which the fee applies. |
| 14 | centralPaymentMethod | `String` | Central Payment Method |
| 15 | centralPaymentMethodDescription | `String` | Central Payment Method Description |
| 16 | centralSequence | `Float` | Central Sequence |
| 17 | chipPinYn | `String` | Indicates if the payment type can be used with the chip and pin card functionality. |
| 18 | code | `String` | Code |
| 19 | creditCardType | `String` | Abbreviates the card_type and is used exclusively for the interface. |
| 20 | creditLimit | `Float` | Credit Limit |
| 21 | currencyCode | `String` | Currency Code |
| 22 | cvv2CheckYn | `String` | Determines if this payment type captures the Credit Card Security Code (CVV2) during payment. |
| 23 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 24 | deletedFlag | `String` | Deleted Flag |
| 25 | description | `String` | Description |
| 26 | expirationRule | `String` | Expiration Rule |
| 27 | extraPerc | `Float` | Extra Percentage. |
| 28 | formatMask | `String` | Format Mask |
| 29 | formula | `String` | Formula |
| 30 | inactiveDate | `Date` | Inactive Date |
| 31 | inactiveFlag | `String` | Inactive Flag |
| 32 | insertDate | `DateTime` | Insert Date |
| 33 | insertUser | `Float` | Insert User |
| 34 | internalDeletedflag | `String` | Deleted Flag |
| 35 | internalInactiveflag | `String` | Inactive Flag |
| 36 | internalOrganizationId | `Float` | Organization ID |
| 37 | issueNumber | `Float` | Issue Number |
| 38 | jRNUpdateDate | `Date` | JRN Update Date |
| 39 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 40 | lastUsedDatetime | `Date` | Last Used Datetime |
| 41 | locationId | `String` | Location ID |
| 42 | merchantNumber | `String` | The merchant # to use when settling / transmitting credit card information. |
| 43 | numberDigits | `Float` | The number of digits to allow for this type of credit card. |
| 44 | numberPostYN | `String` | Indicates the code is used for post charging. |
| 45 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 46 | paymentMethod | `String` | Payment Method |
| 47 | paymentMethodDescription | `String` | Payment Method Description |
| 48 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 49 | printAuthReceiptYn | `String` | Indicates if an Authorization Receipt needs to be printed. |
| 50 | promptAtCheckinYn | `String` | Prompt user to go to cashiering after Check-In if this value equals 'Y'. |
| 51 | property | `String` | Property |
| 52 | repItem | `String` | Reporting Item |
| 53 | repItemName | `String` | Reporting Item Name |
| 54 | repItemOrderby | `Float` | Reporting Item Orderby |
| 55 | repUpdateDate | `Date` | Reporting Updatedate |
| 56 | reservationYN | `String` | Indicates if the card type can be used as a payment method for a reservation. |
| 57 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 58 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 59 | sequence | `Float` | Sequence |
| 60 | startDate | `Float` | Start Date |
| 61 | tempFlag | `Float` | Temp Flag |
| 62 | transactionCode | `String` | Transaction Code |
| 63 | trxUsage1 | `String` | Transaction Code for Card Usage 1 for ex. Credit Card |
| 64 | trxUsage2 | `String` | Transaction Code for Card Usage 2 for ex. Debit Card |
| 65 | updateDate | `DateTime` | Update Date |
| 66 | updateUser | `Float` | Update User |
| 67 | validationRule | `String` | Validation Rule |

[⬆ Back to Query](#query)

---

### ConfigurationResortExportBucketCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| 2 | arrangementId | `Float` | Arrangement ID |
| 3 | bucketType | `String` | User defined Export Bucket type. |
| 4 | bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| 5 | cExchangeDate | `Date` | Central Xchange Date |
| 6 | cExchangeRate | `Float` | Central Xchange Rate |
| 7 | cRoutingAmount | `Float` | Central Routing Amount |
| 8 | code | `String` | Code |
| 9 | compYn | `String` | Comp Y/N |
| 10 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 11 | dailyYn | `String` | Daily Y/N |
| 12 | day1 | `String` | Day1 |
| 13 | day2 | `String` | Day2 |
| 14 | day3 | `String` | Day3 |
| 15 | day4 | `String` | Day4 |
| 16 | day5 | `String` | Day5 |
| 17 | day6 | `String` | Day6 |
| 18 | day7 | `String` | Day7 |
| 19 | deletedFlag | `String` | Deleted Flag |
| 20 | eligibleYn | `String` | Specifies the Eligibility to calculate membership points. |
| 21 | inactiveDate | `DateTime` | Inactive Date |
| 22 | inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| 23 | insertDate | `DateTime` | Insert Date |
| 24 | insertUser | `Float` | Insert User |
| 25 | jRNUpdateDate | `Date` | JRN Update Date |
| 26 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 27 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 28 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 29 | property | `String` | Property |
| 30 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 31 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 32 | revenueBucketDescription | `String` | Arrangement Description for the Transaction Code. |
| 33 | revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| 34 | routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| 35 | routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| 36 | routingPercent | `Float` | Routing Percent |
| 37 | type | `String` | Type |
| 38 | updateDate | `DateTime` | Update Date |
| 39 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionCodeArrangeDetailDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | addTransactionYN | `String` | Add Trx Y/N |
| 2 | arrangementId | `Float` | Arrangement ID |
| 3 | centralTransactionCode | `String` | Central Transaction Code |
| 4 | centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| 5 | childArrangementId | `Float` | Child arrangement id. |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | insertDate | `DateTime` | Insert Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | property | `String` | Code to uniquely identify the Property |
| 16 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 17 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 18 | transactionCode | `String` | Transaction Code |
| 19 | updateDate | `DateTime` | Update Date |
| 20 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortExportBucketTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `String` | User defined Export Bucket type. |
| 2 | compYn | `String` | Comp Y/N |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | description | `String` | Description |
| 6 | fiscalYn | `String` | Indicates if this export bucket is FISCAL related. |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 13 | property | `String` | Property |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | transactionCodeInMultiBucketsYN | `String` | Indicates that a user can configure the same Transaction Code into Revenue Buckets Codes of the same Revenue Bucket Type. |
| 17 | updateDate | `DateTime` | Update Date |
| 18 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortRoutingCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | applyPerDayYN | `String` | Apply Per Day YN |
| 2 | arrTaxTypeCode | `String` | Tax Type code used for certain country requirements. |
| 3 | arrangementId | `Float` | Arrangement ID |
| 4 | bucketValue | `String` | Stores the default value for the arrangement code for revenue buckets in order to group transaction codes. |
| 5 | cExchangeDate | `Date` | Central Xchange Date |
| 6 | cExchangeRate | `Float` | Central Xchange Rate |
| 7 | cRoutingAmount | `Float` | Central Routing Amount |
| 8 | code | `String` | Code |
| 9 | compYn | `String` | Comp Y/N |
| 10 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 11 | deletedFlag | `String` | Deleted Flag |
| 12 | description | `String` | Arrangement Description for the Transaction Code. |
| 13 | eligibleYn | `String` | Specifies the Eligibility to calculate membership points. |
| 14 | exportBucketType | `String` | User defined Export Bucket type. |
| 15 | friday | `String` | Friday |
| 16 | inactiveDate | `DateTime` | Inactive Date |
| 17 | inheritAuthRatecodeYn | `String` | Inherit the authorizer rate code onto the reservation. |
| 18 | insertDate | `DateTime` | Insert Date |
| 19 | insertUser | `Float` | Insert User |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | monday | `String` | Monday |
| 23 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 24 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 25 | property | `String` | Property |
| 26 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 27 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 28 | revenueYn | `String` | Indicates if arrangement code is of a revenue type. Used for country requirements. |
| 29 | routingAmount | `Float` | Contains amount to route for a routing code. This value will be auto populated to the routing instruction. |
| 30 | routingCovers | `Float` | Contains covers to route for a routing code. This value will be auto populated to the routing instruction. |
| 31 | routingPercentage | `Float` | Routing Percentage |
| 32 | saturday | `String` | Saturday |
| 33 | sunday | `String` | Sunday |
| 34 | thursday | `String` | Thursday |
| 35 | tuesday | `String` | Tuesday |
| 36 | type | `String` | Type |
| 37 | updateDate | `DateTime` | Update Date |
| 38 | updateUser | `Float` | Update User |
| 39 | wednesday | `String` | Wednesday |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionDiversionRuleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | basedOn | `String` | Based On |
| 2 | calculation | `String` | Indicates the scope or applicability of the threshold as PER STAY or PER DAY. |
| 3 | code | `String` | User configured diversion code. |
| 4 | complimentary | `Float` | The quantity to be diverted to a designated Posting Master. |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | description | `String` | Description |
| 8 | diversionId | `Float` | Unique ID generated for the Diversion Instruction. |
| 9 | inactiveDate | `DateTime` | Inactive Date |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | level | `String` | Possible values: PROPERTY / RESERVATION. When configured as the PROPERTY type the rule is applicable to all the guests staying in the property. Thresholds of type RESERVATION need to be attached to a reservation to take effect. |
| 15 | membershipLevel | `String` | Membership Level |
| 16 | membershipType | `String` | Membership Type |
| 17 | minimumRequired | `Float` | The quantity required by the rule before the posting can be diverted to a designated Posting Master. |
| 18 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 19 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 20 | property | `String` | Property |
| 21 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 22 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 23 | room | `String` | Room number to receive all the diverted transactions configured for this instruction. |
| 24 | ruleType | `String` | Rule Type |
| 25 | sequence | `Float` | Sequence |
| 26 | updateDate | `DateTime` | Update Date |
| 27 | updateUser | `Float` | Update User |
| 28 | vIP | `String` | VIP |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionDiversionRuleDetailsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 2 | deletedFlag | `String` | Deleted Flag |
| 3 | diversionId | `Float` | Unique ID generated for the Diversion Instruction. |
| 4 | insertDate | `DateTime` | Insert Date |
| 5 | insertUser | `Float` | Insert User |
| 6 | jRNUpdateDate | `Date` | JRN Update Date |
| 7 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 8 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 9 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 10 | property | `String` | Code to uniquely identify the Property |
| 11 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 12 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 13 | transactionCodes | `String` | Transaction Codes |
| 14 | updateDate | `DateTime` | Update Date |
| 15 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralDescription | `String` | Central Description |
| 2 | centralDisplaySequence | `Float` | Central Display Sequence |
| 3 | centralTransactionCodeGroup | `String` | Central Transaction Code Group |
| 4 | class1MandatoryYn | `String` | Class 1 Mandatory Y/N |
| 5 | class2MandatoryYn | `String` | Class 2 Mandatory Y/N |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displaySequence | `Float` | Display Sequence |
| 10 | inactiveflag | `String` | Inactive Flag |
| 11 | indRevenueGroup | `String` | Individual Revenue Gp |
| 12 | indicatorRevenueGroup | `String` | Indicator Revenue Group |
| 13 | insertDate | `DateTime` | Insert Date |
| 14 | insertUser | `Float` | Insert User |
| 15 | internalDeletedflag | `String` | Deleted Flag |
| 16 | internalYn | `String` | Internal Y/N |
| 17 | jRNUpdateDate | `Date` | JRN Update Date |
| 18 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 21 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 22 | property | `String` | Property |
| 23 | repItem | `String` | Reporting Item |
| 24 | repItemName | `String` | Reporting Item Name |
| 25 | repItemOrderby | `Float` | Reporting Item Orderby |
| 26 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 27 | resultIncludedInSumArray | `String` | Result Included In Sum Array |
| 28 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 29 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 30 | tctClassType1 | `String` | Not Used. |
| 31 | tctClassType2 | `String` | Not Used. |
| 32 | transactionCodeActivityType | `String` | Transaction Code Activity Type |
| 33 | transactionCodeGroup | `String` | Transaction Code Group |
| 34 | transgroupid | `String` | Transgroupid |
| 35 | type | `String` | Type |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGroupGeneratesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adjustmentType | `String` | Adjustment Type |
| 2 | amount | `Float` | Amount |
| 3 | amountFromScheduleYn | `String` | Whether to take the taxes from Price Schedules. |
| 4 | cAmount | `Float` | Central Amount |
| 5 | cExchangeDate | `Date` | Central Xchange Date |
| 6 | cExchangeRate | `Float` | Central Xchange Rate |
| 7 | calculationSequence | `Float` | Sequence in which the taxes should be applied. |
| 8 | centralDescription | `String` | Central Description |
| 9 | centralGeneratedCode | `String` | Central Generated Code |
| 10 | currency | `String` | Currency |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | description | `String` | Description |
| 14 | generateRules | `String` | Generate Rules |
| 15 | generatedBy | `String` | Generated By |
| 16 | generatedCode | `String` | Generated Code |
| 17 | generatedPrintedOnFolioYn | `String` | Whether to print on folio. |
| 18 | id | `Float` | ID |
| 19 | insertDate | `DateTime` | Insert Date |
| 20 | insertUser | `Float` | Insert User |
| 21 | jRNUpdateDate | `Date` | JRN Update Date |
| 22 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 23 | nameTaxType | `String` | Name Tax Type |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | percentage | `Float` | Percentage |
| 26 | percentageBaseCode | `Float` | Indicates if the tax is based on a percentage. It would have a value of 0 if based on BASE amount 1 if on S1 2 if based on S2 3 if based on S3. |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Code to uniquely identify the Property |
| 29 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 30 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 31 | resultIncludedInSumArray | `String` | Result Included In Sum Array |
| 32 | roundingMethod | `String` | Rounding method to be used when calculating a generate amount. Allowed values are UP DOWN NONE and NULL. |
| 33 | stopDays | `Float` | Days after which the generates will not be posted for long standing guests. |
| 34 | subTotal1YN | `String` | Sub-Total 1 YN |
| 35 | subTotal2YN | `String` | Sub-Total 2 YN |
| 36 | subTotal3YN | `String` | Sub-Total 3 YN |
| 37 | tcGroup | `String` | Transaction Code Group |
| 38 | tcGroupGenerator | `String` | Group generator. |
| 39 | tcSubgroup | `String` | Transaction Code Subgroup |
| 40 | tcSubgroupGenerator | `String` | Subgroup generator. |
| 41 | tclCodeGenerator | `String` | Identify if the taxes are generated on the Class. |
| 42 | tcrType | `String` | Flag to indicate the addon tax. |
| 43 | trxCodeGenerator | `String` | Transaction Code Generator |
| 44 | udfFunction | `String` | Udf Function |
| 45 | udfInverse | `String` | Not used currently. |
| 46 | updateDate | `DateTime` | Update Date |
| 47 | updateUser | `Float` | Update User |
| 48 | useTaxBracketYn | `String` | Flag to indicate if tax brackets are used for this tax. |

[⬆ Back to Query](#query)

---

### ConfigurationResortTransactionSubgroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralDescription | `String` | Central Description |
| 2 | centralDisplaySequence | `Float` | Central Display Sequence |
| 3 | centralGroup | `String` | Central Group |
| 4 | centralTransactionCodeSubGroup | `String` | Central Transaction Code Sub-Group |
| 5 | class1MandatoryYn | `String` | Class 1 Mandatory Y/N |
| 6 | class2MandatoryYn | `String` | Class 2 Mandatory Y/N |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedFlag | `String` | Deleted Flag |
| 9 | description | `String` | Description |
| 10 | displaySequence | `Float` | Display Sequence |
| 11 | frequentFlyerYn | `String` | Frequent Flyer Y/N |
| 12 | group | `String` | Group |
| 13 | groupPointsRedemptionYN | `String` | Gp Points Redemption Y/N |
| 14 | inactiveflag | `String` | Inactive Flag |
| 15 | indRevenueGroup | `String` | Individual Revenue Gp |
| 16 | indicatorRevenueGroup | `String` | Indicator Revenue Group |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | internalDeletedflag | `String` | Deleted Flag |
| 20 | internalYn | `String` | Internal Y/N |
| 21 | jRNUpdateDate | `Date` | JRN Update Date |
| 22 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 23 | locationID | `String` | Internal ID to uniquely identify the Property |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | resultIncludedInSumArray | `String` | Result Included In Sum Array |
| 28 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 29 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 30 | subGroupType | `String` | Sub-Group level code to group all attached transaction codes into one of the different pre-defined categories. |
| 31 | taxFlagYN | `String` | Tax YN |
| 32 | taxYN | `String` | Not Used. |
| 33 | tcGroupAndSubgroup | `String` | Transaction Code Group And Subgroup |
| 34 | tcTransactionType | `String` | Transaction Code Transaction Type |
| 35 | transactionCodeSubGroup | `String` | Transaction Code Sub-Group |
| 36 | transgroupid | `String` | Transgroupid |
| 37 | transsubgroupid | `String` | Transsubgroupid |
| 38 | type | `String` | Type |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSubgroupGeneratesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adjustmentType | `String` | Adjustment Type |
| 2 | amount | `Float` | Amount |
| 3 | amountFromScheduleYn | `String` | Whether to take the taxes from Price Schedules. |
| 4 | cAmount | `Float` | Central Amount |
| 5 | cExchangeDate | `Date` | Central Xchange Date |
| 6 | cExchangeRate | `Float` | Central Xchange Rate |
| 7 | calculationSequence | `Float` | Sequence in which the taxes should be applied. |
| 8 | centralDescription | `String` | Central Description |
| 9 | centralGeneratedCode | `String` | Central Generated Code |
| 10 | currency | `String` | Currency |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | description | `String` | Description |
| 14 | generateRules | `String` | Generate Rules |
| 15 | generatedBy | `String` | Generated By |
| 16 | generatedCode | `String` | Generated Code |
| 17 | generatedPrintedOnFolioYn | `String` | Whether to print on folio. |
| 18 | id | `Float` | ID |
| 19 | insertDate | `DateTime` | Insert Date |
| 20 | insertUser | `Float` | Insert User |
| 21 | jRNUpdateDate | `Date` | JRN Update Date |
| 22 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 23 | nameTaxType | `String` | Name Tax Type |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | percentage | `Float` | Percentage |
| 26 | percentageBaseCode | `Float` | Indicates if the tax is based on a percentage. It would have a value of 0 if based on BASE amount 1 if on S1 2 if based on S2 3 if based on S3. |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Code to uniquely identify the Property |
| 29 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 30 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 31 | resultIncludedInSumArray | `String` | Result Included In Sum Array |
| 32 | roundingMethod | `String` | Rounding method to be used when calculating a generate amount. Allowed values are UP DOWN NONE and NULL. |
| 33 | seqBy | `Float` | Sequence By |
| 34 | stopDays | `Float` | Days after which the generates will not be posted for long standing guests. |
| 35 | subTotal1YN | `String` | Sub-Total 1 YN |
| 36 | subTotal2YN | `String` | Sub-Total 2 YN |
| 37 | subTotal3YN | `String` | Sub-Total 3 YN |
| 38 | tcDsi | `Float` | Transaction Code Dsi |
| 39 | tcGroup | `String` | Transaction Code Group |
| 40 | tcGroupGenerator | `String` | Group generator. |
| 41 | tcOrganizationid | `Float` | Transaction Code Organizationid |
| 42 | tcSubgroup | `String` | Transaction Code Subgroup |
| 43 | tcSubgroupGenerator | `String` | Subgroup generator. |
| 44 | tcTcSubgroup | `String` | Transaction Code Transaction Code Subgroup |
| 45 | tclCodeGenerator | `String` | Identify if the taxes are generated on the Class. |
| 46 | tcrType | `String` | Flag to indicate the addon tax. |
| 47 | transactionCodeResort | `String` | Not Used. |
| 48 | trxCodeGenerator | `String` | Transaction Code Generator |
| 49 | udfFunction | `String` | Udf Function |
| 50 | udfInverse | `String` | Not used currently. |
| 51 | updateDate | `DateTime` | Update Date |
| 52 | updateUser | `Float` | Update User |
| 53 | useTaxBracketYn | `String` | Flag to indicate if tax brackets are used for this tax. |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyAlertDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `String` | Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | insertDate | `DateTime` | Insert Date |
| 6 | insertUser | `Float` | Insert User |
| 7 | jRNUpdateDate | `Date` | JRN Update Date |
| 8 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 9 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 10 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 11 | propery | `String` | Propery |
| 12 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 13 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 14 | sequence | `Float` | Sequence |
| 15 | updateDate | `DateTime` | Update Date |
| 16 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGlobalAlertsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | alertCode | `String` | Alert Code |
| 2 | alertText | `String` | Alert Text |
| 3 | area | `String` | Area |
| 4 | brandStayCnt | `Float` | Brand Stay Count |
| 5 | comments | `String` | Comments |
| 6 | conditions | `String` | Conditions |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedFlag | `String` | Deleted Flag |
| 9 | department | `String` | Department |
| 10 | description | `String` | Description |
| 11 | emailAddress | `String` | Email Address |
| 12 | emailYn | `String` | Email Y/N |
| 13 | externalAlertId | `String` | Unique ID in External System. |
| 14 | hasTagsYn | `String` | Indicates if the current alert can contain tags. |
| 15 | insertDate | `DateTime` | Insert Date |
| 16 | insertUser | `Float` | Insert User |
| 17 | jRNUpdateDate | `Date` | JRN Update Date |
| 18 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 19 | language | `String` | Language |
| 20 | lastStayDate | `Date` | Last Stay Date |
| 21 | lastStayLocation | `String` | Last Stay Location |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | membershipAlertYn | `String` | Indicate if the current alert belongs to a membership module. |
| 24 | membershipCardNo | `String` | Membership Card Number |
| 25 | orderBy | `Float` | Order By |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | pref1 | `String` | Preference 1 |
| 28 | pref2 | `String` | Preference 2 |
| 29 | pref3 | `String` | Preference 3 |
| 30 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 31 | printerYN | `String` | Use this alert to print notification. |
| 32 | printerName | `String` | Name of the printer where alert will be printed. |
| 33 | property | `String` | Property |
| 34 | propertyStayCnt | `Float` | Property Stay Count |
| 35 | propertyStayDate | `Date` | Previous Stay Date at this property for repeat guests. |
| 36 | queryId | `Float` | Query ID |
| 37 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 38 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 39 | reportName | `String` | Report Name |
| 40 | reservationAlertId | `Float` | Resv Alert ID |
| 41 | reservationNameId | `Float` | Resv Name ID |
| 42 | screenYN | `String` | Screen YN |
| 43 | skipGuestOverviewYn | `String` | Indicates if the guest overview screen should be suppressed. |
| 44 | smsNumber | `String` | The phone number to where the notification will be send. |
| 45 | smsYn | `String` | Use this alert to text a notification. |
| 46 | stopCheckInCheckOut | `String` | Indicates if this alert will be used to perform a validation. |
| 47 | udfc01 | `String` | Udfc01 |
| 48 | udfc02 | `String` | Udfc02 |
| 49 | udfc03 | `String` | Udfc03 |
| 50 | udfc04 | `String` | Udfc04 |
| 51 | udfc05 | `String` | Udfc05 |
| 52 | udfc06 | `String` | Udfc06 |
| 53 | udfc07 | `String` | Udfc07 |
| 54 | udfc08 | `String` | Udfc08 |
| 55 | udfc09 | `String` | Udfc09 |
| 56 | udfc10 | `String` | Udfc10 |
| 57 | udfc11 | `String` | Udfc11 |
| 58 | udfc12 | `String` | Udfc12 |
| 59 | udfc13 | `String` | Udfc13 |
| 60 | udfc14 | `String` | Udfc14 |
| 61 | udfc15 | `String` | Udfc15 |
| 62 | udfc16 | `String` | Udfc16 |
| 63 | udfc17 | `String` | Udfc17 |
| 64 | udfc18 | `String` | Udfc18 |
| 65 | udfc19 | `String` | Udfc19 |
| 66 | udfc20 | `String` | Udfc20 |
| 67 | udfc21 | `String` | Udfc21 |
| 68 | udfc22 | `String` | Udfc22 |
| 69 | udfc23 | `String` | Udfc23 |
| 70 | udfc24 | `String` | Udfc24 |
| 71 | udfc25 | `String` | Udfc25 |
| 72 | udfc26 | `String` | Udfc26 |
| 73 | udfc27 | `String` | Udfc27 |
| 74 | udfc28 | `String` | Udfc28 |
| 75 | udfc29 | `String` | Udfc29 |
| 76 | udfc30 | `String` | Udfc30 |
| 77 | udfc31 | `String` | Udfc31 |
| 78 | udfc32 | `String` | Udfc32 |
| 79 | udfc33 | `String` | Udfc33 |
| 80 | udfc34 | `String` | Udfc34 |
| 81 | udfc35 | `String` | Udfc35 |
| 82 | udfc36 | `String` | Udfc36 |
| 83 | udfc37 | `String` | Udfc37 |
| 84 | udfc38 | `String` | Udfc38 |
| 85 | udfc39 | `String` | Udfc39 |
| 86 | udfc40 | `String` | Udfc40 |
| 87 | udfd01 | `Date` | Udfd01 |
| 88 | udfd02 | `Date` | Udfd02 |
| 89 | udfd03 | `Date` | Udfd03 |
| 90 | udfd04 | `Date` | Udfd04 |
| 91 | udfd05 | `Date` | Udfd05 |
| 92 | udfd06 | `Date` | Udfd06 |
| 93 | udfd07 | `Date` | Udfd07 |
| 94 | udfd08 | `Date` | Udfd08 |
| 95 | udfd09 | `Date` | Udfd09 |
| 96 | udfd10 | `Date` | Udfd10 |
| 97 | udfd11 | `Date` | Udfd11 |
| 98 | udfd12 | `Date` | Udfd12 |
| 99 | udfd13 | `Date` | Udfd13 |
| 100 | udfd14 | `Date` | Udfd14 |
| 101 | udfd15 | `Date` | Udfd15 |
| 102 | udfd16 | `Date` | Udfd16 |
| 103 | udfd17 | `Date` | Udfd17 |
| 104 | udfd18 | `Date` | Udfd18 |
| 105 | udfd19 | `Date` | Udfd19 |
| 106 | udfd20 | `Date` | Udfd20 |
| 107 | udfn01 | `Float` | Udfn01 |
| 108 | udfn02 | `Float` | Udfn02 |
| 109 | udfn03 | `Float` | Udfn03 |
| 110 | udfn04 | `Float` | Udfn04 |
| 111 | udfn05 | `Float` | Udfn05 |
| 112 | udfn06 | `Float` | Udfn06 |
| 113 | udfn07 | `Float` | Udfn07 |
| 114 | udfn08 | `Float` | Udfn08 |
| 115 | udfn09 | `Float` | Udfn09 |
| 116 | udfn10 | `Float` | Udfn10 |
| 117 | udfn11 | `Float` | Udfn11 |
| 118 | udfn12 | `Float` | Udfn12 |
| 119 | udfn13 | `Float` | Udfn13 |
| 120 | udfn14 | `Float` | Udfn14 |
| 121 | udfn15 | `Float` | Udfn15 |
| 122 | udfn16 | `Float` | Udfn16 |
| 123 | udfn17 | `Float` | Udfn17 |
| 124 | udfn18 | `Float` | Udfn18 |
| 125 | udfn19 | `Float` | Udfn19 |
| 126 | udfn20 | `Float` | Udfn20 |
| 127 | udfn21 | `Float` | Udfn21 |
| 128 | udfn22 | `Float` | Udfn22 |
| 129 | udfn23 | `Float` | Udfn23 |
| 130 | udfn24 | `Float` | Udfn24 |
| 131 | udfn25 | `Float` | Udfn25 |
| 132 | udfn26 | `Float` | Udfn26 |
| 133 | udfn27 | `Float` | Udfn27 |
| 134 | udfn28 | `Float` | Udfn28 |
| 135 | udfn29 | `Float` | Udfn29 |
| 136 | udfn30 | `Float` | Udfn30 |
| 137 | udfn31 | `Float` | Udfn31 |
| 138 | udfn32 | `Float` | Udfn32 |
| 139 | udfn33 | `Float` | Udfn33 |
| 140 | udfn34 | `Float` | Udfn34 |
| 141 | udfn35 | `Float` | Udfn35 |
| 142 | udfn36 | `Float` | Udfn36 |
| 143 | udfn37 | `Float` | Udfn37 |
| 144 | udfn38 | `Float` | Udfn38 |
| 145 | udfn39 | `Float` | Udfn39 |
| 146 | udfn40 | `Float` | Udfn40 |
| 147 | updateDate | `DateTime` | Update Date |
| 148 | updateUser | `Float` | Update User |
| 149 | validationOverridePermission | `String` | The user permission required in order to override a validation alert. |
| 150 | valueRating | `String` | Value Rating |
| 151 | vipStatus | `String` | VIP Status |
| 152 | welcomeOfferCode | `String` | Offer code if this alert is linked to a guest welcome offer. |
| 153 | welcomeOfferYn | `String` | Welcome Offer Y/N |

[⬆ Back to Query](#query)

---

### ConfigurationResortBlockCancellationCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `Date` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | internalDeletedflag | `String` | Deleted Flag |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | languageCode | `String` | Language Code |
| 23 | lastUsedDatetime | `Date` | Last Used Datetime |
| 24 | locationID | `String` | Internal ID to uniquely identify the Property |
| 25 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `Date` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | sequence | `Float` | Sequence |
| 37 | tempFlag | `String` | Temp Flag |
| 38 | titleSuffix | `Float` | Title Suffix |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSalesEventDestinationDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | cancellationDestination | `String` | Cancellation Destination |
| 4 | centralCancellationDestination | `String` | Central Cancellation Destination |
| 5 | centralCancellationDestinationDescription | `String` | Central Cancellation Destination Description |
| 6 | centralSequence | `Float` | Central Sequence |
| 7 | chainCode | `String` | Chain Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `Date` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | internalDeletedflag | `String` | Deleted Flag |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | languageCode | `String` | Language Code |
| 23 | lastUsedDatetime | `Date` | Last Used Datetime |
| 24 | locationID | `String` | Internal ID to uniquely identify the Property |
| 25 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `Date` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | scdestinationid | `String` | Scdestinationid |
| 37 | sequence | `Float` | Sequence |
| 38 | tempFlag | `String` | Temp Flag |
| 39 | titleSuffix | `Float` | Title Suffix |
| 40 | updateDate | `DateTime` | Update Date |
| 41 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortLostBookingCodesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `Date` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | internalDeletedflag | `String` | Deleted Flag |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | languageCode | `String` | Language Code |
| 23 | lastUsedDatetime | `Date` | Last Used Datetime |
| 24 | locationID | `String` | Internal ID to uniquely identify the Property |
| 25 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `Date` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | sequence | `Float` | Sequence |
| 37 | tempFlag | `String` | Temp Flag |
| 38 | titleSuffix | `Float` | Title Suffix |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortRefusedBookingCodesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `Date` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | internalDeletedflag | `String` | Deleted Flag |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | languageCode | `String` | Language Code |
| 23 | lastUsedDatetime | `Date` | Last Used Datetime |
| 24 | locationID | `String` | Internal ID to uniquely identify the Property |
| 25 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `Date` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | sequence | `Float` | Sequence |
| 37 | tempFlag | `String` | Temp Flag |
| 38 | titleSuffix | `Float` | Title Suffix |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBookingMethodDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | bookingmethodid | `String` | Bookingmethodid |
| 2 | businessTitle | `String` | Business Title |
| 3 | canDeleteYn | `String` | Can Delete Y/N |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralReservationMethod | `String` | Central Reservation Method |
| 6 | centralSequence | `Float` | Central Sequence |
| 7 | chainCode | `String` | Chain Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 14 | inactiveDate | `DateTime` | Inactive Date |
| 15 | inactiveflag | `String` | Inactive Flag |
| 16 | insertDate | `DateTime` | Insert Date |
| 17 | insertUser | `Float` | Insert User |
| 18 | jRNUpdateDate | `Date` | JRN Update Date |
| 19 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repItem | `String` | Reporting Item |
| 28 | repItemName | `String` | Reporting Item Name |
| 29 | repItemOrderby | `Float` | Reporting Item Orderby |
| 30 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 31 | reservationMethod | `String` | Reservation Method |
| 32 | sequence | `Float` | Sequence |
| 33 | titleSuffix | `Float` | Title Suffix |
| 34 | updateDate | `DateTime` | Update Date |
| 35 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyCutoffScheduleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `String` | Unique code to identify a Wash schedule. |
| 2 | cutoffRooms2 | `Float` | Number of rooms that should be washed for Occupancy 2. |
| 3 | cutoffRooms3 | `Float` | Number of rooms that should be washed for Occupancy 3. |
| 4 | cutoffRooms4 | `Float` | Number of rooms that should be washed  for Occupancy 4. |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | daysPriorToArrival | `Float` | Cut off days for the stay date. |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | insertDate | `DateTime` | Insert Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | property | `String` | Property |
| 16 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 17 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 18 | rooms | `Float` | Number of rooms that should be washed. |
| 19 | sell | `Float` | Wash value for sell limits when the SELL LIMITS parameter is ON. |
| 20 | updateDate | `DateTime` | Update Date |
| 21 | updateUser | `Float` | Update User |
| 22 | washByPercent | `Float` | Cutoff Percentage. |

[⬆ Back to Query](#query)

---

### ConfigurationResortBookingStatusDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allowPickupYN | `String` | Allow Pickup YN |
| 2 | bookingstatusid | `String` | Bookingstatusid |
| 3 | cateringStatusType | `String` | Catering Status Type |
| 4 | cateringdeductinvflag | `String` | Cateringdeductinvflag |
| 5 | centralDescription | `String` | Central Description |
| 6 | centralEventStatus | `String` | Central Event Status |
| 7 | centralSequence | `Float` | Central Sequence |
| 8 | chainCode | `String` | Chain Code |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deductinventoryflag | `String` | Deductinventoryflag |
| 11 | defaultReservationType | `String` | Default reservation type |
| 12 | deletedflag | `String` | Deleted Flag |
| 13 | description | `String` | Description |
| 14 | diaryYN | `String` | Show the booking status in the diary |
| 15 | displayColor | `String` | Display Color |
| 16 | fitStatusYn | `String` | Indicates an FIT statuscode. |
| 17 | inactiveflag | `String` | Inactive Flag |
| 18 | insertDate | `DateTime` | Insert Date |
| 19 | insertUser | `Float` | Insert User |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | leadStatusYn | `String` | Indicates if this Booking Status is an Initial Lead status. |
| 23 | logCateringYn | `String` | Will store the information whether the details_ok_yn flag of allotment_header will be set to Y. This operation is done at trigger level. |
| 24 | oRMSYN | `String` | Indicates that the blocks in this status will be considered by ORMS for forecasting. |
| 25 | oldBlockStatus | `String` | Old Block Status |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 30 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 31 | reasonType | `String` | Type of the reason for the booking status |
| 32 | repItem | `String` | Reporting Item |
| 33 | repItemName | `String` | Reporting Item Name |
| 34 | repItemOrderby | `Float` | Reporting Item Orderby |
| 35 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 36 | returnInventoryYN | `String` | Return Inventory YN |
| 37 | roomStatusType | `String` | Room Status Type |
| 38 | sequence | `Float` | Sequence |
| 39 | startingYN | `String` | Booking starting status (intial pickup) |
| 40 | updateDate | `DateTime` | Update Date |
| 41 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCancelRuleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allotmentHeaderId | `Float` | Allotment Header ID |
| 2 | amount | `Float` | Amount |
| 3 | applyRuleTo | `String` | For Web Bookings only the deposit amount will be calculated either from room or catering revenue or from both. This column stores either: [ALL] [ROOMS] or [CATERING]. |
| 4 | beforeTime | `DateTime` | Before Time |
| 5 | beginDate | `Date` | Begin Date |
| 6 | cCnclPenltyAmount | `Float` | Central Cncl Penlty Amount |
| 7 | cDepAmount | `Float` | Central Dep Amount |
| 8 | cExchangeDate | `Date` | Central Xchange Date |
| 9 | cExchangeRate | `Float` | Central Xchange Rate |
| 10 | code | `String` | Code |
| 11 | creditRating | `String` | Credit Rating |
| 12 | d1 | `String` | D1 |
| 13 | d2 | `String` | For future use |
| 14 | d3 | `String` | Internal date column. |
| 15 | d4 | `String` | Internal date column. |
| 16 | d5 | `String` | Internal date column. |
| 17 | d6 | `String` | Internal date column. |
| 18 | d7 | `String` | Internal date column. |
| 19 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 20 | daysBeforeArrival | `Float` | Days Before Arrival |
| 21 | daysofweek | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| 22 | deletedflag | `String` | Deleted Flag |
| 23 | depositAmount | `Float` | Deposit Amount |
| 24 | depositAmountType | `String` | Deposit Amount Type |
| 25 | depositDaysAfterBooking | `Float` | Deposit Days After Booking |
| 26 | depositDaysPriorToArrival | `Float` | Deposit Days Prior To Arrival |
| 27 | depositcancelruleid | `Float` | Depositcancelruleid |
| 28 | depositcancelrulepmsref | `Float` | Deposit Cancel Rule PMS Reference |
| 29 | depositorCancellationRule | `String` | Depositor Cancellation Rule |
| 30 | description | `String` | Description |
| 31 | endDate | `Date` | End Date |
| 32 | guaranteeClass | `String` | Guarantee class for cancel policy. Specifically added for BWI. |
| 33 | inactiveDate | `DateTime` | Inactive Date |
| 34 | inactiveflag | `String` | Inactive Flag |
| 35 | insertDate | `DateTime` | Insert Date |
| 36 | insertUser | `Float` | Insert User |
| 37 | jRNUpdateDate | `Date` | JRN Update Date |
| 38 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 39 | locationID | `String` | Internal ID to uniquely identify the Property |
| 40 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 41 | overrideYn | `String` | override allowed or not for booking. |
| 42 | parentRateDcSeq | `Float` | Refers to Master ID for this child record |
| 43 | paymentRequired | `String` | Payment Required within Rule Period. (FULL NONE PARTIAL) |
| 44 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 45 | property | `String` | Property |
| 46 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 47 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 48 | rateCode | `String` | Rate Code |
| 49 | rateCodeDescription | `String` | Rate Code Description |
| 50 | rateSetId | `Float` | Rate Set ID |
| 51 | repSeasonCode | `String` | Reporting Season Code |
| 52 | reservationType | `String` | Reservation Type |
| 53 | seasonCode | `String` | Season Code |
| 54 | sequence | `Float` | Sequence |
| 55 | type | `String` | Type |
| 56 | updateDate | `DateTime` | Update Date |
| 57 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCancelRuleScheduleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allotmentHeaderId | `Float` | Allotment Header ID |
| 2 | applyRuleTo | `String` | For Web Bookings only the deposit amount will be calculated either from room or catering revenue or from both. This column stores either: [ALL] [ROOMS] or [CATERING]. |
| 3 | beginDate | `Date` | Begin Date |
| 4 | blockCode | `String` | Block Code |
| 5 | cCnclPenltyAmount | `Float` | Central Cncl Penlty Amount |
| 6 | cDepAmount | `Float` | Central Dep Amount |
| 7 | cExchangeDate | `Date` | Central Xchange Date |
| 8 | cExchangeRate | `Float` | Central Xchange Rate |
| 9 | canBeforeTime | `DateTime` | Can Before Time |
| 10 | canDaysPriorToArrival | `Float` | Can Days Prior To Arrival |
| 11 | canPenaltyAmount | `Float` | Can Penalty Amount |
| 12 | canPenaltyAmountType | `String` | Can Penalty Amount Type |
| 13 | creditRating | `String` | Credit Rating |
| 14 | d1 | `String` | D1 |
| 15 | d2 | `String` | For future use |
| 16 | d3 | `String` | Internal date column. |
| 17 | d4 | `String` | Internal date column. |
| 18 | d5 | `String` | Internal date column. |
| 19 | d6 | `String` | Internal date column. |
| 20 | d7 | `String` | Internal date column. |
| 21 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 22 | daysofweek | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| 23 | deletedflag | `String` | Deleted Flag |
| 24 | depositAmount | `Float` | Deposit Amount |
| 25 | depositAmountType | `String` | Deposit Amount Type |
| 26 | depositDaysAfterBooking | `Float` | Deposit Days After Booking |
| 27 | depositDaysPriorToArrival | `Float` | Deposit Days Prior To Arrival |
| 28 | depositcancelruleid | `Float` | Depositcancelruleid |
| 29 | depositcancelrulepmsref | `Float` | Deposit Cancel Rule PMS Reference |
| 30 | depositorCancellationRule | `String` | Depositor Cancellation Rule |
| 31 | endDate | `Date` | End Date |
| 32 | guaranteeClass | `String` | Guarantee class for cancel policy. Specifically added for BWI. |
| 33 | inactiveDate | `DateTime` | Inactive Date |
| 34 | inactiveYN | `String` | Inactive YN |
| 35 | insertDate | `DateTime` | Insert Date |
| 36 | insertUser | `Float` | Insert User |
| 37 | jRNUpdateDate | `Date` | JRN Update Date |
| 38 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 39 | locationID | `String` | Internal ID to uniquely identify the Property |
| 40 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 41 | overrideYN | `String` | override allowed or not for booking. |
| 42 | parentRateDcSeq | `Float` | Refers to Master ID for this child record |
| 43 | paymentRequired | `String` | Payment Required within Rule Period. (FULL NONE PARTIAL) |
| 44 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 45 | property | `String` | Property |
| 46 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 47 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 48 | rateCode | `String` | Rate Code |
| 49 | rateCodeDescription | `String` | Rate Code Description |
| 50 | rateSetId | `Float` | Rate Set ID |
| 51 | repSeasonCode | `String` | Reporting Season Code |
| 52 | reservationType | `String` | Reservation Type |
| 53 | rule | `String` | Rule |
| 54 | ruleDescription | `String` | Rule Description |
| 55 | seasonCode | `String` | Season Code |
| 56 | sequence | `Float` | Sequence |
| 57 | updateDate | `DateTime` | Update Date |
| 58 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDepositRuleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | afterBooking | `Float` | After Booking |
| 2 | allotmentHeaderId | `Float` | Allotment Header ID |
| 3 | amount | `Float` | Amount |
| 4 | applyRuleTo | `String` | For Web Bookings only the deposit amount will be calculated either from room or catering revenue or from both. This column stores either: [ALL] [ROOMS] or [CATERING]. |
| 5 | beforeArrival | `Float` | Before Arrival |
| 6 | beginDate | `Date` | Begin Date |
| 7 | cCnclPenltyAmount | `Float` | Central Cncl Penlty Amount |
| 8 | cDepAmount | `Float` | Central Dep Amount |
| 9 | cExchangeDate | `Date` | Central Xchange Date |
| 10 | cExchangeRate | `Float` | Central Xchange Rate |
| 11 | canBeforeTime | `Date` | Can Before Time |
| 12 | canDaysPriorToArrival | `Float` | Can Days Prior To Arrival |
| 13 | canPenaltyAmount | `Float` | Can Penalty Amount |
| 14 | canPenaltyAmountType | `String` | Can Penalty Amount Type |
| 15 | creditRating | `String` | Credit Rating |
| 16 | d1 | `String` | D1 |
| 17 | d2 | `String` | For future use |
| 18 | d3 | `String` | Internal date column. |
| 19 | d4 | `String` | Internal date column. |
| 20 | d5 | `String` | Internal date column. |
| 21 | d6 | `String` | Internal date column. |
| 22 | d7 | `String` | Internal date column. |
| 23 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 24 | daysofweek | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| 25 | deletedflag | `String` | Deleted Flag |
| 26 | depositRule | `String` | Deposit Rule |
| 27 | depositcancelruleid | `Float` | Depositcancelruleid |
| 28 | depositcancelrulepmsref | `Float` | Deposit Cancel Rule PMS Reference |
| 29 | depositorCancellationRule | `String` | Depositor Cancellation Rule |
| 30 | description | `String` | Description |
| 31 | endDate | `Date` | End Date |
| 32 | guaranteeClass | `String` | Guarantee class for cancel policy. Specifically added for BWI. |
| 33 | inactiveDate | `Date` | Inactive Date |
| 34 | inactiveYN | `String` | Inactive YN |
| 35 | insertDate | `DateTime` | Insert Date |
| 36 | insertUser | `Float` | Insert User |
| 37 | jRNUpdateDate | `Date` | JRN Update Date |
| 38 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 39 | locationID | `String` | Internal ID to uniquely identify the Property |
| 40 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 41 | overrideYn | `String` | override allowed or not for booking. |
| 42 | parentRateDcSeq | `Float` | Refers to Master ID for this child record |
| 43 | paymentRequired | `String` | Payment Required within Rule Period. (FULL NONE PARTIAL) |
| 44 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 45 | property | `String` | Property |
| 46 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 47 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 48 | rateCode | `String` | Rate Code |
| 49 | rateCodeDescription | `String` | Rate Code Description |
| 50 | rateSetId | `Float` | Rate Set ID |
| 51 | repSeasonCode | `String` | Reporting Season Code |
| 52 | reservationType | `String` | Reservation Type |
| 53 | seasonCode | `String` | Season Code |
| 54 | sequence | `Float` | Sequence |
| 55 | type | `String` | Type |
| 56 | updateDate | `DateTime` | Update Date |
| 57 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDepositRuleScheduleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allotmentHeaderId | `Float` | Allotment Header ID |
| 2 | applyRuleTo | `String` | For Web Bookings only the deposit amount will be calculated either from room or catering revenue or from both. This column stores either: [ALL] [ROOMS] or [CATERING]. |
| 3 | beginDate | `Date` | Begin Date |
| 4 | blockCode | `String` | Block Code |
| 5 | cCnclPenltyAmount | `Float` | Central Cncl Penlty Amount |
| 6 | cDepAmount | `Float` | Central Dep Amount |
| 7 | cExchangeDate | `Date` | Central Xchange Date |
| 8 | cExchangeRate | `Float` | Central Xchange Rate |
| 9 | canBeforeTime | `DateTime` | Can Before Time |
| 10 | canDaysPriorToArrival | `Float` | Can Days Prior To Arrival |
| 11 | canPenaltyAmount | `Float` | Can Penalty Amount |
| 12 | canPenaltyAmountType | `String` | Can Penalty Amount Type |
| 13 | creditRating | `String` | Credit Rating |
| 14 | d1 | `String` | D1 |
| 15 | d2 | `String` | For future use |
| 16 | d3 | `String` | Internal date column. |
| 17 | d4 | `String` | Internal date column. |
| 18 | d5 | `String` | Internal date column. |
| 19 | d6 | `String` | Internal date column. |
| 20 | d7 | `String` | Internal date column. |
| 21 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 22 | daysofweek | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| 23 | deletedflag | `String` | Deleted Flag |
| 24 | depositAmount | `Float` | Deposit Amount |
| 25 | depositAmountType | `String` | Deposit Amount Type |
| 26 | depositDaysAfterBooking | `Float` | Deposit Days After Booking |
| 27 | depositDaysPriorToArrival | `Float` | Deposit Days Prior To Arrival |
| 28 | depositcancelruleid | `Float` | Depositcancelruleid |
| 29 | depositcancelrulepmsref | `Float` | Deposit Cancel Rule PMS Reference |
| 30 | depositorCancellationRule | `String` | Depositor Cancellation Rule |
| 31 | endDate | `Date` | End Date |
| 32 | guaranteeClass | `String` | Guarantee class for cancel policy. Specifically added for BWI. |
| 33 | inactiveDate | `DateTime` | Inactive Date |
| 34 | inactiveYN | `String` | Inactive YN |
| 35 | insertDate | `DateTime` | Insert Date |
| 36 | insertUser | `Float` | Insert User |
| 37 | jRNUpdateDate | `Date` | JRN Update Date |
| 38 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 39 | locationID | `String` | Internal ID to uniquely identify the Property |
| 40 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 41 | overrideYN | `String` | override allowed or not for booking. |
| 42 | parentRateDcSeq | `Float` | Refers to Master ID for this child record |
| 43 | paymentRequired | `String` | Payment Required within Rule Period. (FULL NONE PARTIAL) |
| 44 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 45 | property | `String` | Property |
| 46 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 47 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 48 | rateCode | `String` | Rate Code |
| 49 | rateCodeDescription | `String` | Rate Code Description |
| 50 | rateSetId | `Float` | Rate Set ID |
| 51 | repSeasonCode | `String` | Reporting Season Code |
| 52 | reservationType | `String` | Reservation Type |
| 53 | rule | `String` | Rule |
| 54 | ruleDescription | `String` | Rule Description |
| 55 | seasonCode | `String` | Season Code |
| 56 | sequence | `Float` | Sequence |
| 57 | updateDate | `DateTime` | Update Date |
| 58 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGuaranteeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | addressYN | `String` | Is an address required when using this confirm code? Y/N |
| 2 | arrivalYN | `String` | Arrival Time needed |
| 3 | autoCancelReservationYN | `String` | Indicates whether a reservation of this type will be auto cancelled if no payment or CC is not received. |
| 4 | bookingStatus | `String` | Booking Status |
| 5 | bookingStatusOrder | `String` | Booking Status Order |
| 6 | canDeleteYn | `String` | Can Delete Y/N |
| 7 | cashBasisYn | `String` | Is a reservation with this confirm code on a cash basis? Y/N |
| 8 | ccPendingDays | `Float` | Cc Pending Days |
| 9 | ccVerifyCodeRequiredYn | `String` | Used for GDS channels and indicates the requirement of verification code. |
| 10 | centralReservationType | `String` | Central Reservation Type |
| 11 | centralReservationTypeDescription | `String` | Central Reservation Type Description |
| 12 | closingProbability | `Float` | A probability to have a revenue out of the reservation guaranted by this guaranted code |
| 13 | creditCardYN | `String` | Credit card needed |
| 14 | croAllowedYn | `String` | Is the CRO allowed to use this confirm code? Y/N |
| 15 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 16 | deletedFlag | `String` | Deleted Flag |
| 17 | depositYN | `String` | Deposit YN |
| 18 | gDSShortDescription | `String` | External GDS Description |
| 19 | guaranteecodeid | `String` | Guaranteecodeid |
| 20 | inactiveDate | `DateTime` | Inactive Date |
| 21 | inactiveYN | `String` | Inactive YN |
| 22 | insertDate | `DateTime` | Insert Date |
| 23 | insertUser | `Float` | Insert User |
| 24 | internalDeletedflag | `String` | Deleted Flag |
| 25 | internalYn | `String` | Internal Y/N |
| 26 | jRNUpdateDate | `Date` | JRN Update Date |
| 27 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 28 | locationID | `String` | Internal ID to uniquely identify the Property |
| 29 | longDescription | `String` | Long Description |
| 30 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 31 | phoneYN | `String` | Is a phone # required when using this confirm code? Y/N |
| 32 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 33 | property | `String` | Property |
| 34 | repItem | `String` | Reporting Item |
| 35 | repItemName | `String` | Reporting Item Name |
| 36 | repItemOrderby | `Float` | Reporting Item Orderby |
| 37 | repOrderBy | `Float` | Reporting Order By |
| 38 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 39 | reservationType | `String` | Reservation Type |
| 40 | reservationTypeDescription | `String` | Reservation Type Description |
| 41 | reserveInventoryYn | `String` | Reserve Inventory Y/N |
| 42 | restrictedYn | `String` | Restricted Y/N |
| 43 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 44 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 45 | sequence | `Float` | Sequence |
| 46 | shortDescription | `String` | Short Description |
| 47 | updateDate | `DateTime` | Update Date |
| 48 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortReservationTypeScheduleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allotmentHeaderId | `Float` | Allotment Header ID |
| 2 | applyRuleTo | `String` | For Web Bookings only the deposit amount will be calculated either from room or catering revenue or from both. This column stores either: [ALL] [ROOMS] or [CATERING]. |
| 3 | beginDate | `Date` | Begin Date |
| 4 | cCnclPenltyAmount | `Float` | Central Cncl Penlty Amount |
| 5 | cDepAmount | `Float` | Central Dep Amount |
| 6 | cExchangeDate | `Date` | Central Xchange Date |
| 7 | cExchangeRate | `Float` | Central Xchange Rate |
| 8 | canBeforeTime | `Date` | Can Before Time |
| 9 | canDaysPriorToArrival | `Float` | Can Days Prior To Arrival |
| 10 | canPenaltyAmount | `Float` | Can Penalty Amount |
| 11 | canPenaltyAmountType | `String` | Can Penalty Amount Type |
| 12 | creditRating | `String` | Credit Rating |
| 13 | d1 | `String` | D1 |
| 14 | d2 | `String` | For future use |
| 15 | d3 | `String` | Internal date column. |
| 16 | d4 | `String` | Internal date column. |
| 17 | d5 | `String` | Internal date column. |
| 18 | d6 | `String` | Internal date column. |
| 19 | d7 | `String` | Internal date column. |
| 20 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 21 | daysofweek | `String` | Day of week values as Y or N applicable for the cancel policies starting Sun to Sat. |
| 22 | deletedflag | `String` | Deleted Flag |
| 23 | depositAmount | `Float` | Deposit Amount |
| 24 | depositAmountType | `String` | Deposit Amount Type |
| 25 | depositDaysAfterBooking | `Float` | Deposit Days After Booking |
| 26 | depositDaysPriorToArrival | `Float` | Deposit Days Prior To Arrival |
| 27 | depositcancelruleid | `Float` | Depositcancelruleid |
| 28 | depositcancelrulepmsref | `Float` | Deposit Cancel Rule PMS Reference |
| 29 | depositorCancellationRule | `String` | Depositor Cancellation Rule |
| 30 | description | `String` | Description |
| 31 | endDate | `Date` | End Date |
| 32 | guaranteeClass | `String` | Guarantee class for cancel policy. Specifically added for BWI. |
| 33 | inactiveDate | `Date` | Inactive Date |
| 34 | inactiveYN | `String` | Inactive YN |
| 35 | insertDate | `DateTime` | Insert Date |
| 36 | insertUser | `Float` | Insert User |
| 37 | jRNUpdateDate | `Date` | JRN Update Date |
| 38 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 39 | locationID | `String` | Internal ID to uniquely identify the Property |
| 40 | orderBy | `Float` | Order By |
| 41 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 42 | overrideYN | `String` | override allowed or not for booking. |
| 43 | parentRateDcSeq | `Float` | Refers to Master ID for this child record |
| 44 | paymentRequired | `String` | Payment Required within Rule Period. (FULL NONE PARTIAL) |
| 45 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 46 | property | `String` | Property |
| 47 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 48 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 49 | rateCode | `String` | Rate Code |
| 50 | rateCodeDescription | `String` | Rate Code Description |
| 51 | rateSetId | `Float` | Rate Set ID |
| 52 | repSeasonCode | `String` | Reporting Season Code |
| 53 | reservationType | `String` | Reservation Type |
| 54 | ruleCode | `String` | Rule Code |
| 55 | ruledescription | `String` | Ruledescription |
| 56 | seasonCode | `String` | Season Code |
| 57 | updateDate | `DateTime` | Update Date |
| 58 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMarketDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralMarketCode | `String` | Central Market Code |
| 2 | centralMarketDescription | `String` | Central Market Description |
| 3 | centralMarketGroupCode | `String` | Central Market Group Code |
| 4 | centralMarketGroupDescription | `String` | Central Market Group Description |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | displayColor | `String` | Display Color |
| 8 | inactiveDate | `DateTime` | Inactive Date |
| 9 | inactiveYN | `String` | Inactive YN |
| 10 | insertDate | `DateTime` | Insert Date |
| 11 | insertUser | `Float` | Insert User |
| 12 | internalDeletedflag | `String` | Deleted Flag |
| 13 | jRNUpdateDate | `Date` | JRN Update Date |
| 14 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 15 | locationID | `String` | Internal ID to uniquely identify the Property |
| 16 | marketCode | `String` | Market Code |
| 17 | marketDescription | `String` | Market Description |
| 18 | marketDisplaySequence | `Float` | Market Display Sequence |
| 19 | marketGroupCode | `String` | Market group attached to the market code |
| 20 | marketGroupDescription | `String` | Market Group Description |
| 21 | marketGroupDisplaySequence | `Float` | Market Group Display Sequence |
| 22 | marketgroupid | `String` | Marketgroupid |
| 23 | marketid | `String` | Marketid |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | printGroup | `String` | Print Group for Nationality Report |
| 27 | property | `String` | Property |
| 28 | repItem | `String` | Reporting Item |
| 29 | repItemName | `String` | Reporting Item Name |
| 30 | repItemOrderby | `Float` | Reporting Item Orderby |
| 31 | repMarketSellSequence | `Float` | Reporting Market Sell Sequence |
| 32 | repParentSellSequence | `Float` | Reporting Parent Sell Sequence |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | scOrderby | `Float` | Sc Orderby |
| 37 | trxCode | `String` | Transaction Code |
| 38 | updateDate | `DateTime` | Update Date |
| 39 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMarketGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | autoupgradeYn | `String` | Defines whether this Market Group is eligible for auto upgrade of room types in the Room Assignment Optimization. |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | inactiveDate | `DateTime` | Inactive Date |
| 6 | inactiveYN | `String` | Inactive YN |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | internalDeletedflag | `String` | Deleted Flag |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | locationID | `String` | Internal ID to uniquely identify the Property |
| 13 | marketGroup | `String` | Market group code |
| 14 | marketgroupid | `String` | Marketgroupid |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | property | `String` | Property |
| 18 | ranking | `Float` | Ranking |
| 19 | repDescription | `String` | Reporting Description |
| 20 | repItem | `String` | Reporting Item |
| 21 | repItemName | `String` | Reporting Item Name |
| 22 | repItemOrderby | `Float` | Reporting Item Orderby |
| 23 | repMarketGroup | `String` | Reporting Market Group |
| 24 | repSellSequence | `Float` | Reporting Sell Sequence |
| 25 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 26 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 27 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 28 | scOrderBy | `Float` | Sc Order By |
| 29 | sequence | `Float` | Sequence |
| 30 | updateDate | `DateTime` | Update Date |
| 31 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyMarketingCityDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 2 | deletedFlag | `String` | Deleted Flag |
| 3 | description | `String` | City Description. |
| 4 | direction | `String` | Direction |
| 5 | displaySeq | `Float` | Display Sequence |
| 6 | distance | `Float` | Distance |
| 7 | distanceType | `String` | Distance Type |
| 8 | drivingTime | `String` | Driving Time |
| 9 | inactiveDate | `DateTime` | Inactive Date |
| 10 | inactiveYN | `String` | Inactive YN |
| 11 | insertDate | `DateTime` | Insert Date |
| 12 | insertUser | `Float` | Insert User |
| 13 | jRNUpdateDate | `Date` | JRN Update Date |
| 14 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 15 | marketingCity | `String` | Marketing City |
| 16 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 17 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 18 | property | `String` | Property |
| 19 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 20 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 21 | regionCode | `String` | Region Code |
| 22 | updateDate | `DateTime` | Update Date |
| 23 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMarketingRegionsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `Date` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | internalDeletedflag | `String` | Deleted Flag |
| 17 | jRNUpdateDate | `Date` | JRN Update Date |
| 18 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 19 | languageCode | `String` | Language Code |
| 20 | lastUsedDatetime | `Date` | Last Used Datetime |
| 21 | locationID | `String` | Internal ID to uniquely identify the Property |
| 22 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 23 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 24 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 25 | property | `String` | Property |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `Date` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | sequence | `Float` | Sequence |
| 37 | tempFlag | `String` | Temp Flag |
| 38 | titleSuffix | `Float` | Title Suffix |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortChannelDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralOriginCode | `String` | Central Origin Code |
| 4 | centralOriginDescription | `String` | Central Origin Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | channelid | `String` | Channelid |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | displayColor | `String` | Display Color |
| 12 | entityName | `String` | Entity Name |
| 13 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 14 | inactiveDate | `DateTime` | Inactive Date |
| 15 | inactiveflag | `String` | Inactive Flag |
| 16 | insertDate | `DateTime` | Insert Date |
| 17 | insertUser | `Float` | Insert User |
| 18 | internalDeletedflag | `String` | Deleted Flag |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 23 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 24 | originCode | `String` | Origin Code |
| 25 | originDescription | `String` | Origin Description |
| 26 | originDisplaySequence | `Float` | Origin Display Sequence |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | titleSuffix | `Float` | Title Suffix |
| 37 | updateDate | `DateTime` | Update Date |
| 38 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSellMessagesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allotmentHeaderId | `Float` | Allotment Header ID |
| 2 | beginDate | `Date` | Begin Date |
| 3 | blockCode | `String` | Block Code |
| 4 | centralRoomType | `String` | Central Room Type |
| 5 | chainCode | `String` | Chain Code |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | endDate | `Date` | End Date |
| 8 | inactiveDate | `DateTime` | Inactive Date |
| 9 | insertDate | `DateTime` | Insert Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | language | `String` | Language |
| 14 | locationID | `String` | Internal ID to uniquely identify the Property |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | property | `String` | Property |
| 18 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 19 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 20 | rateCode | `String` | Rate Code |
| 21 | roomCategory | `String` | Room Category |
| 22 | roomType | `String` | Room Type |
| 23 | sellId | `Float` | The primary key for this table. |
| 24 | sellMessage | `String` | The actual message to be displayed. |
| 25 | sequence | `Float` | Sequence |
| 26 | stickyFlag | `String` | Stick the message on top of the screen without scrolling it. |
| 27 | updateDate | `DateTime` | Update Date |
| 28 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSourceTableDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralSequence | `Float` | Central Sequence |
| 2 | centralSourceCode | `String` | Central Source Code |
| 3 | centralSourceDescription | `String` | Central Source Description |
| 4 | centralSourceGroupCode | `String` | Central Source Group Code |
| 5 | centralSourceGroupDescription | `String` | Central Source Group Description |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedYn | `String` | Row deleted YN (if set to 'Y' then the row joined by SEQ from postal_codes will not be displayed). |
| 8 | deletedflag | `String` | Deleted Flag |
| 9 | inactiveDate | `Date` | Inactive Date |
| 10 | inactiveFlagYN | `String` | Inactive YN |
| 11 | inactiveYn | `String` | Inactive Y/N |
| 12 | insertDate | `DateTime` | Insert Date |
| 13 | insertUser | `Float` | Insert User |
| 14 | internetSalesYn | `String` | Indicates if the source code is marked to track internet sales. |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | lastuseddatetime | `DateTime` | Lastuseddatetime |
| 18 | locationID | `String` | Internal ID to uniquely identify the Property |
| 19 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 20 | parentsourceid | `String` | Parentsourceid |
| 21 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 22 | property | `String` | Property |
| 23 | repItem | `String` | Reporting Item |
| 24 | repItemName | `String` | Reporting Item Name |
| 25 | repItemOrderby | `Float` | Reporting Item Orderby |
| 26 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 27 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 28 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 29 | sequence | `Float` | Sequence |
| 30 | sourceCode | `String` | Source Code |
| 31 | sourceDescription | `String` | Source Description |
| 32 | sourceDisplaySequence | `Float` | Source Display Sequence |
| 33 | sourceGroupCode | `String` | Source group of the source code |
| 34 | sourceGroupDescription | `String` | Source Group Description |
| 35 | sourceGroupDisplaySequence | `Float` | Source Group Display Sequence |
| 36 | sourceid | `String` | Sourceid |
| 37 | tempYn | `String` | Temp Y/N |
| 38 | updateDate | `DateTime` | Update Date |
| 39 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSourceGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | centralDescription | `String` | Central Description |
| 2 | centralSequence | `Float` | Central Sequence |
| 3 | centralSourceGroup | `String` | Central Source Group |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | description | `String` | Description |
| 7 | inactiveDate | `DateTime` | Inactive Date |
| 8 | inactiveYN | `String` | Inactive YN |
| 9 | insertDate | `DateTime` | Insert Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | internetSalesYn | `String` | Indicates if the source code is marked to track internet sales. |
| 12 | jRNUpdateDate | `Date` | JRN Update Date |
| 13 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 14 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 15 | parentSourceCode | `String` | Source group of the source code |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | property | `String` | Property |
| 18 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 19 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 20 | repItem | `String` | Reporting Item |
| 21 | repItemName | `String` | Reporting Item Name |
| 22 | repItemOrderby | `Float` | Reporting Item Orderby |
| 23 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 24 | scOrderby | `Float` | Sc Orderby |
| 25 | sequence | `Float` | Sequence |
| 26 | sourceGroup | `String` | Source Group |
| 27 | updateDate | `DateTime` | Update Date |
| 28 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortReservationAutoAttachRulesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | advancedYn | `String` | Indicates if this rule uses advanced filter conditions |
| 2 | basedOn | `String` | Defines what the rule is based on the type of condition which need to be satisfied in order to qualify for this rule. Valid values are MEMBERSHIP RATE_CODE REFERENCE VIP. |
| 3 | code | `String` | Code |
| 4 | convertedToAdvancedYn | `String` | Flag to indicate if the condition on this rule was automatically converted to an advanced expression. |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | inactiveDate | `DateTime` | Inactive Date |
| 8 | inactiveYN | `String` | Inactive YN |
| 9 | insertDate | `DateTime` | Insert Date |
| 10 | insertUser | `Float` | Insert User |
| 11 | jRNUpdateDate | `Date` | JRN Update Date |
| 12 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 13 | keywordType | `String` | Keyword Type |
| 14 | level | `String` | Level |
| 15 | minAdults | `Float` | This column will be filled when Based_on value is MIN_ADULTS. Otherwise it will be empty. |
| 16 | minChildren | `Float` | This column will be filled when Based_on value is MIN_CHILDREN. Otherwise it will be empty. |
| 17 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 18 | preference | `String` | Preference |
| 19 | preferenceType | `String` | Preference Type |
| 20 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 21 | property | `String` | Property |
| 22 | queryId | `Float` | Query ID |
| 23 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 24 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 25 | rateCode | `String` | Rate Code |
| 26 | roomCategory | `String` | Room Category |
| 27 | ruleType | `String` | Rule Type |
| 28 | type | `String` | Type |
| 29 | updateDate | `DateTime` | Update Date |
| 30 | updateUser | `Float` | Update User |
| 31 | vipStatus | `String` | VIP Status |

[⬆ Back to Query](#query)

---

### ConfigurationResortReservationAutoAttachDetailsDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | associatedCodes | `String` | Associated Codes. |
| 2 | attachId | `Float` | Attach ID |
| 3 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 4 | deletedFlag | `String` | Deleted Flag |
| 5 | discountReasonCode | `String` | Discount Reason Code |
| 6 | insertDate | `DateTime` | Insert Date |
| 7 | insertUser | `Float` | Insert User |
| 8 | itemId | `Float` | Item ID |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | preference | `String` | Preference |
| 13 | preferenceType | `String` | Preference Type |
| 14 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 15 | product | `String` | Product |
| 16 | promoCode | `String` | Promo Code |
| 17 | property | `String` | Code to uniquely identify the Property |
| 18 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 19 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 20 | ruleCode | `String` | Rule Code |
| 21 | traceDeptId | `String` | Internal Trace ID. |
| 22 | traceText | `String` | Trace Text |
| 23 | updateDate | `DateTime` | Update Date |
| 24 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCancellationCodesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `Date` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | internalDeletedflag | `String` | Deleted Flag |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | languageCode | `String` | Language Code |
| 23 | lastUsedDatetime | `DateTime` | Last Used Datetime |
| 24 | locationID | `String` | Internal ID to uniquely identify the Property |
| 25 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | sequence | `Float` | Sequence |
| 37 | tempFlag | `String` | Temp Flag |
| 38 | titleSuffix | `Float` | Title Suffix |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortEntryPointDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `Date` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | internalDeletedflag | `String` | Deleted Flag |
| 17 | jRNUpdateDate | `Date` | JRN Update Date |
| 18 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 19 | languageCode | `String` | Language Code |
| 20 | lastUsedDatetime | `Date` | Last Used Datetime |
| 21 | locationID | `String` | Internal ID to uniquely identify the Property |
| 22 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 23 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 24 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 25 | property | `String` | Property |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `Date` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | sequence | `Float` | Sequence |
| 37 | tempFlag | `String` | Temp Flag |
| 38 | titleSuffix | `Float` | Title Suffix |
| 39 | updateDate | `DateTime` | Update Date |
| 40 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDiscountReasonDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | advanceYN | `String` | Indicates if this rule uses advanced filter conditions |
| 2 | attributeCode | `String` | Attribute Code |
| 3 | businessTitle | `String` | Business Title |
| 4 | canDeleteYn | `String` | Can Delete Y/N |
| 5 | chainCode | `String` | Chain Code |
| 6 | code | `String` | Code |
| 7 | comments | `String` | Comments |
| 8 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 9 | deletedflag | `String` | Deleted Flag |
| 10 | description | `String` | Description |
| 11 | displayColor | `String` | Display Color |
| 12 | entityName | `String` | Entity Name |
| 13 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 14 | inactiveDate | `DateTime` | Inactive Date |
| 15 | inactiveflag | `String` | Inactive Flag |
| 16 | insertDate | `DateTime` | Insert Date |
| 17 | insertUser | `Float` | Insert User |
| 18 | jRNUpdateDate | `Date` | JRN Update Date |
| 19 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 20 | languageCode | `String` | Language Code |
| 21 | locationID | `String` | Internal ID to uniquely identify the Property |
| 22 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 23 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 24 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 25 | property | `String` | Property |
| 26 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 27 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 28 | ranking | `Float` | Ranking |
| 29 | repAttributeCode | `String` | Reporting Attribute Code |
| 30 | repDescription | `String` | Reporting Description |
| 31 | repItem | `String` | Reporting Item |
| 32 | repItemName | `String` | Reporting Item Name |
| 33 | repItemOrderby | `Float` | Reporting Item Orderby |
| 34 | repOrderBy | `Float` | Reporting Order By |
| 35 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 36 | sequence | `Float` | Sequence |
| 37 | titleSuffix | `Float` | Title Suffix |
| 38 | updateDate | `DateTime` | Update Date |
| 39 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortEcouponDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 2 | defaultQuantity | `Float` | Default quantity of the eCoupon. |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | inactiveDate | `DateTime` | Inactive Date |
| 6 | inactiveYN | `String` | Inactive YN |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | postingRoom | `String` | Charges coming with this eCoupon will be routed to this Pseudo room. |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | property | `String` | Property |
| 15 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 16 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 17 | rateCode | `String` | Rate Code |
| 18 | sequence | `Float` | Sequence |
| 19 | updateDate | `DateTime` | Update Date |
| 20 | updateUser | `Float` | Update User |
| 21 | welcomeOfferYn | `String` | Welcome Offer Y/N |
| 22 | eCouponCode | `String` | eCoupon Code |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyLocatorDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `Float` | Locator code. |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | inactiveDate | `DateTime` | Inactive Date |
| 6 | inactiveYN | `String` | Inactive YN |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 13 | property | `String` | Property |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | sequence | `Float` | Sequence |
| 17 | updateDate | `DateTime` | Update Date |
| 18 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyMessageDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `String` | Code |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | insertDate | `DateTime` | Insert Date |
| 5 | insertUser | `Float` | Insert User |
| 6 | jRNUpdateDate | `Date` | JRN Update Date |
| 7 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 8 | message | `String` | Message |
| 9 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 10 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 11 | property | `String` | Property |
| 12 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 13 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 14 | sequence | `Float` | Sequence |
| 15 | updateDate | `DateTime` | Update Date |
| 16 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGuestStatusDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | guestStatus | `String` | Used for Police/Tourist Export |
| 16 | gueststatusid | `String` | Gueststatusid |
| 17 | inactiveDate | `DateTime` | Inactive Date |
| 18 | inactiveflag | `String` | Inactive Flag |
| 19 | insertDate | `DateTime` | Insert Date |
| 20 | insertUser | `Float` | Insert User |
| 21 | internalDeletedflag | `String` | Deleted Flag |
| 22 | internalEntityname | `String` | Entityname |
| 23 | jRNUpdateDate | `Date` | JRN Update Date |
| 24 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 25 | languageCode | `String` | Language Code |
| 26 | locationID | `String` | Internal ID to uniquely identify the Property |
| 27 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 28 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 29 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 30 | property | `String` | Property |
| 31 | ranking | `Float` | Ranking |
| 32 | repItem | `String` | Reporting Item |
| 33 | repItemName | `String` | Reporting Item Name |
| 34 | repItemOrderby | `Float` | Reporting Item Orderby |
| 35 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 36 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 37 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 38 | sequence | `Float` | Sequence |
| 39 | statustype | `Float` | Statustype |
| 40 | titleSuffix | `Float` | Title Suffix |
| 41 | updateDate | `DateTime` | Update Date |
| 42 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGuestTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralDescription | `String` | Central Description |
| 4 | centralGuestType | `String` | Central Guest Type |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | comments | `String` | Comments |
| 8 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 9 | deletedFlag | `String` | Deleted Flag |
| 10 | description | `String` | Description |
| 11 | displayColor | `String` | Display Color |
| 12 | entityName | `String` | Entity Name |
| 13 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 14 | guestType | `String` | Guest Type |
| 15 | guesttypeid | `String` | Guesttypeid |
| 16 | inactiveDate | `DateTime` | Inactive Date |
| 17 | inactiveflag | `String` | Inactive Flag |
| 18 | insertDate | `DateTime` | Insert Date |
| 19 | insertUser | `Float` | Insert User |
| 20 | internalDeletedflag | `String` | Deleted Flag |
| 21 | jRNUpdateDate | `Date` | JRN Update Date |
| 22 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 23 | languageCode | `String` | Language Code |
| 24 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 25 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 26 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 27 | property | `String` | Property |
| 28 | ranking | `Float` | Ranking |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 33 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 34 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 35 | sequence | `Float` | Sequence |
| 36 | titleSuffix | `Float` | Title Suffix |
| 37 | updateDate | `DateTime` | Update Date |
| 38 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortImmigrationStatusDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `Date` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPreRegRulesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | allowRestrict | `String` | Indicates whether this rule defines the values that will restrict or allow the internet check-in. Will be used in future versions. |
| 2 | beginDate | `Date` | Begin Date |
| 3 | chainCode | `String` | Chain Code |
| 4 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 5 | deletedFlag | `String` | Deleted Flag |
| 6 | endDate | `Date` | End Date |
| 7 | insertDate | `DateTime` | Insert Date |
| 8 | insertUser | `Float` | Insert User |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 13 | property | `String` | Property |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | ruleDetails | `String` | Rule Details |
| 17 | ruleId | `Float` | Rule ID |
| 18 | ruleType | `String` | Rule Type |
| 19 | ruleTypeDesc | `String` | Rule Type Desc |
| 20 | updateDate | `DateTime` | Update Date |
| 21 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortItemClassDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | bookableViaWebsiteYN | `String` | Bookable via Website YN |
| 2 | centralDescription | `String` | Central Description |
| 3 | centralSequence | `Float` | Central Sequence |
| 4 | code | `String` | Item Class Code. |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedFlag | `String` | Deleted Flag |
| 7 | description | `String` | Description |
| 8 | discountableYn | `String` | Discountable Y/N |
| 9 | eventTypes | `String` | Event Types |
| 10 | iconName | `String` | Icon Name |
| 11 | inactiveDate | `DateTime` | Inactive Date |
| 12 | itemclassId | `Float` | Itemclass ID |
| 13 | jRNUpdateDate | `Date` | JRN Update Date |
| 14 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 15 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 16 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 17 | property | `String` | Property |
| 18 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 19 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 20 | repItem | `String` | Reporting Item |
| 21 | repItemName | `String` | Reporting Item Name |
| 22 | repOrderBy | `Float` | Reporting Order By |
| 23 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 24 | reportingItemclassId | `String` | Rep Itemclass ID |
| 25 | reservationYN | `String` | Indicates if this menu item depends on the reservation. |
| 26 | responsibleDepartment | `String` | Responsible Department |
| 27 | sequence | `Float` | Sequence |
| 28 | usedInApp | `String` | Used In App |

[⬆ Back to Query](#query)

---

### ConfigurationResortItemInventoryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | activityExtSystem | `String` | Exterbal system for which the activity will be created. |
| 2 | activityLinkYn | `String` | Indicates whether an activity will be created for the item or not. |
| 3 | activityLocationCode | `String` | Location code of the activity that will be created when linked with an activity. |
| 4 | activityStatusCode | `String` | Initial activity status code when linked to an activity. |
| 5 | activityType | `String` | Activity Type |
| 6 | allowedOutsideStayYn | `String` | Can this item be held outside of the reservation stay dates ? |
| 7 | availableFrom | `DateTime` | Item available from this time. |
| 8 | availableTo | `DateTime` | Item available until this time. |
| 9 | braceletRuleCode | `String` | Links to RESORT_BRACELET_RULES.RULE_CODE. |
| 10 | cCost | `Float` | Central Cost |
| 11 | cExchangeDate | `Date` | Central Xchange Date |
| 12 | cExchangeRate | `Float` | Central Xchange Rate |
| 13 | centralDescription | `String` | Central Description |
| 14 | centralSequence | `Float` | Central Sequence |
| 15 | cost | `Float` | Cost |
| 16 | criticalYn | `String` | Critical Item watch stock |
| 17 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 18 | dailyInventoryYn | `String` | Indicates if daily inventory is setup for this item. |
| 19 | defaultDuration | `Float` | Defines the default duration when booking the item (in Days). |
| 20 | defaultQty | `Float` | Defines the default quantity when booking the item. |
| 21 | deletedFlag | `String` | Deleted Flag |
| 22 | description | `String` | Description |
| 23 | discountableYN | `String` | Discountable YN |
| 24 | displayColor | `String` | Display Color |
| 25 | externalYN | `String` | Item is external |
| 26 | inactiveDate | `DateTime` | Inactive Date |
| 27 | insertDate | `DateTime` | Insert Date |
| 28 | insertUser | `Float` | Insert User |
| 29 | itemClass | `String` | Item Class |
| 30 | itemCode | `String` | Item Code |
| 31 | itemId | `Float` | Item ID |
| 32 | itemPoolId | `Float` | References the ITEM_POOL_ID from GEM$ITEM_POOL. |
| 33 | itemclassId | `Float` | Itemclass ID |
| 34 | jRNUpdateDate | `Date` | JRN Update Date |
| 35 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 36 | mandatoryYn | `String` | Mandatory Y/N |
| 37 | objectType | `String` | Type of object  1.CONSTRAINT 2.TABLE. |
| 38 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 39 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 40 | promptFixedChargesYn | `String` | Should the Fixed Charges screen be automatically displayed when this item gets attached to a reservation ? |
| 41 | property | `String` | Property |
| 42 | quantityInStock | `Float` | Item Quantity in stock |
| 43 | quickInsert | `String` | Quick Insert |
| 44 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 45 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 46 | repItem | `String` | Reporting Item |
| 47 | repItemName | `String` | Reporting Item Name |
| 48 | repItemOrderby | `Float` | Reporting Item Orderby |
| 49 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 50 | reportingItemId | `String` | Rep Item ID |
| 51 | revType | `String` | Rev Type |
| 52 | revenueType | `String` | Revenue Type |
| 53 | sellSeparate | `String` | Indicates whether it could be sold separately |
| 54 | sequence | `Float` | Sequence |
| 55 | setdownTime | `Float` | Setdown Time |
| 56 | setupTime | `Float` | Setup Time |
| 57 | showbeoYn | `String` | Showbeo Y/N |
| 58 | updateDate | `DateTime` | Update Date |
| 59 | updateUser | `Float` | Update User |
| 60 | webBookingYn | `String` | Web Booking Y/N |
| 61 | welcomeOfferYn | `String` | Welcome Offer Y/N |

[⬆ Back to Query](#query)

---

### ConfigurationResortItemPoolDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | code | `String` | User Definable Item Pool Code. |
| 2 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 3 | deletedFlag | `String` | Deleted Flag |
| 4 | description | `String` | Description |
| 5 | insertTs | `DateTime` | Insert Ts |
| 6 | insertUser | `Float` | Insert User |
| 7 | itemClass | `String` | Item Class Code. |
| 8 | itemPoolId | `Float` | References the ITEM_POOL_ID from GEM$ITEM_POOL. |
| 9 | jRNUpdateDate | `Date` | JRN Update Date |
| 10 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 11 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 12 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 13 | property | `String` | Property |
| 14 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 15 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 16 | sequence | `Float` | Sequence |
| 17 | updateTs | `DateTime` | Update Ts |
| 18 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBirthCountryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPropertyCountryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | addressdoctorMode | `String` | Defines the mode used to invoke Addressdoctor service [INTERACTIVE or FASTCOMPLETION] |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | countryCode | `String` | Country Code |
| 5 | countryMainGroup | `String` | Country Main Group |
| 6 | countryName | `String` | Country Name |
| 7 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 8 | deletedFlag | `String` | Deleted Flag |
| 9 | displayCountryFlagYN | `String` | Indicates if the Country Flag should be displayed on the front end. |
| 10 | guestAddressFormat | `String` | Guest Address Format Codes. For Confirmation Letters. |
| 11 | iSOCode | `String` | ISO standard code for the country |
| 12 | iSOName | `String` | ISO standard name for the country |
| 13 | inactiveDate | `Date` | Inactive Date |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | name | `String` | Name |
| 19 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 20 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 21 | property | `String` | Property |
| 22 | propertyAddressFormat | `String` | Property Address Format Codes. For Confirmation Letters. |
| 23 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 24 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 25 | region | `String` | Region |
| 26 | repItem | `String` | Reporting Item |
| 27 | repItemName | `String` | Reporting Item Name |
| 28 | repItemOrderby | `Float` | Reporting Item Orderby |
| 29 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 30 | reportSequence | `Float` | Report Sequence |
| 31 | sequence | `Float` | Display sequence for LOVs |
| 32 | statisticsCode | `String` | Internal |
| 33 | status | `String` | Status |
| 34 | updateDate | `DateTime` | Update Date |
| 35 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCountryGroupDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | comments | `String` | Comments |
| 8 | countryGroup | `String` | Country Group |
| 9 | countryGroupCode | `String` | Country Group Code |
| 10 | countrygroupid | `String` | Countrygroupid |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | displayColor | `String` | Display Color |
| 14 | entityName | `String` | Entity Name |
| 15 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 16 | inactiveDate | `DateTime` | Inactive Date |
| 17 | inactiveflag | `String` | Inactive Flag |
| 18 | insertDate | `DateTime` | Insert Date |
| 19 | insertUser | `Float` | Insert User |
| 20 | internalDeletedflag | `String` | Deleted Flag |
| 21 | jRNUpdateDate | `Date` | JRN Update Date |
| 22 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 23 | languageCode | `String` | Language Code |
| 24 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 25 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 26 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 27 | property | `String` | Property |
| 28 | ranking | `Float` | Ranking |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 33 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 34 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 35 | sequence | `Float` | Sequence |
| 36 | titleSuffix | `Float` | Title Suffix |
| 37 | updateDate | `DateTime` | Update Date |
| 38 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDistanceTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortDistrictDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortFiscalGuestTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortFiscalRegionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortProfileIDCountryDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortNationalityDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralDescription | `String` | Central Description |
| 4 | centralNationalityCode | `String` | Central Nationality Code |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `Date` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | internalDeletedflag | `String` | Deleted Flag |
| 20 | jRNUpdateDate | `Date` | JRN Update Date |
| 21 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 22 | languageCode | `String` | Language Code |
| 23 | locationID | `String` | Internal ID to uniquely identify the Property |
| 24 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 25 | nationalityid | `String` | Nationalityid |
| 26 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 27 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 28 | property | `String` | Property |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 35 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 36 | sequence | `Float` | Sequence |
| 37 | titleSuffix | `Float` | Title Suffix |
| 38 | updateDate | `DateTime` | Update Date |
| 39 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortQualifyingRatesDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | aSBRateCycle | `String` | Not null value in this column indicates that this is ASB Rate. This column also specifies the cycle of ASB rate. MC=Fixed Calendar Month Cycle WC=Fixed Calendar Week Cycle MF= Floating Monthly Cycle WF=Floating Weekly Cycle. |
| 2 | addition | `String` | Amount to be added to the base rate when shown on rate query |
| 3 | advBaseRateCode | `String` | With Advanced Base Rate Parameter ON this field stores the rate code on which this rate schedule is dynamically based on. |
| 4 | advBaseRounding | `String` | Indicates how rounding of advanced dynamic rate calculation is performed.[U]p  [D]own [N]one [C] -Up - keep decimal [F] -Down - keep decimal. |
| 5 | advanceBaseCompareYN | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BAR rate code. |
| 6 | advanceBooking | `Float` | Min number of days to book rate in advance. |
| 7 | advanceDailyBaseYN | `String` | Indicates if this rate code is an Advanced Daily Base Rate. |
| 8 | advanceDailyRateYN | `String` | Indicates if this rate code is an Advanced Daily Rate. |
| 9 | alternateRateCode | `String` | Alternative rate code if current rate is not available |
| 10 | availabilityUpdateYn | `String` | Flag to indicate whether to send Rate code to AVH or not. |
| 11 | backToBackYn | `String` | Back To Back Y/N |
| 12 | baseAmount | `Float` | Base Amount |
| 13 | baseFltPct | `String` | Flat or Percentage of the Base Rate |
| 14 | baseRateCode | `String` | Base Rate Code |
| 15 | baseRounding | `String` | Indicates if rounding of rate is required |
| 16 | baseType | `String` | Indicating a rate type such as flat rate or percentage rate. Possible values are: FLAT DIFFERENTIAL and NULL. |
| 17 | bbarBaseAmount | `Float` | This column use to store Percentage or Amount difference between BAR Rate code and this Rate Code. |
| 18 | bbarBaseFltPct | `String` | This flag column identify that amount column represent Flat or Percentage value. |
| 19 | bbarBaseRounding | `String` | This column identify the rounding formula for the BBAR Rate calculation. |
| 20 | bbarBasedYn | `String` | This column will identify that Rate Code is Best BAR based rate code or not. Possible values are Y/N. |
| 21 | bbarCompareYn | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BBAR rate code. |
| 22 | bbarYn | `String` | Bbar Y/N |
| 23 | beginBookingDate | `Date` | Begin Booking Date |
| 24 | breakfastInclYn | `String` | PCR: Is breakfast is included in this rate code? |
| 25 | breakfastPrice | `Float` | Breakfast Price |
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
| 42 | changeState | `String` | Indicates the state of chaange of the rate code with values null=enabled D=disabled P=changes pending of approval |
| 43 | closedToArrival | `String` | Days the rate restriction is not available for arrival |
| 44 | commissionCode | `String` | Commission Code |
| 45 | commissionPct | `Float` | This field is used to populate rate code commission percentage for informational purposes for GDS and ORS reservation agents |
| 46 | commissionYn | `String` | Are commissions allowed for this rate code? Y/N |
| 47 | commissionablePerc | `Float` | PCR: Commissionable Percentage. |
| 48 | commissionableYn | `String` | Commissionable Y/N |
| 49 | complimentaryYn | `String` | Complimentary Y/N |
| 50 | currCodeDecimalPos | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating the decimal position specific to the received the currency code. |
| 51 | currencyCode | `String` | Currency Code |
| 52 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 53 | dailyRatesYn | `String` | Daily Rates Y/N |
| 54 | dayuseYn | `String` | Day use reservation Y/N. |
| 55 | dbaseAmount | `Float` | Indicates either Flat amount or Percentage increase or decrease from the dynamic base rate. |
| 56 | dbaseCompareYn | `String` | This flag identify that while checking availability calculated based amount should be compared to rate detail of rate code or not. |
| 57 | dbaseFltPct | `String` | Flat or Percentage of the dynamic base rate code. |
| 58 | dbaseRateCode | `String` | The rate code on which this rate shedule is dynamically based on. |
| 59 | dbaseRounding | `String` | Indicates if rounding of dynamic rate calculation is required. |
| 60 | dblRoomSupplementPrice | `Float` | Stores the double room supplement price. |
| 61 | defaultToHighestBarYn | `String` | For BAR dependent Rate Code this flag indicates that when all BAR Rates are closed the Rate Amount should be calculated based on the highest BAR Rate Amount instead of based on its own Rate Detail. |
| 62 | deletedFlag | `String` | Deleted Flag |
| 63 | depositMaturityPreference | `String` | Stores the Deposit maturity preference. |
| 64 | deptCode | `String` | Department code for the transaction. |
| 65 | description | `String` | Description |
| 66 | discountRateAmount | `Float` | Discount rate amount value. |
| 67 | discountRatePercentageYn | `String` | Indicates if discount rate amount is a percentage value. |
| 68 | discountYn | `String` | Discount Flag. |
| 69 | displayRegionalYn | `String` | Flag indicates rate needs to display in area availability or not. |
| 70 | displaySet | `String` | Display Set |
| 71 | distributeYn | `String` | Indicates if the profile should be distributed to the external database. |
| 72 | doubleRoomSupplementYN | `String` | Stores the double room supplement. |
| 73 | endBookingDate | `Date` | End Booking Date |
| 74 | exchangePostingType | `String` | Exchange Posting Type |
| 75 | externalLocked | `String` | External Locked |
| 76 | extraPersonChargeBegins | `Float` | Introduced for Holidex inbound delta rate processing this column stores the value indicating at person level the extra charge begins. |
| 77 | fitDiscountLevel | `Float` | Fit Discount Level. |
| 78 | fitDiscountPerc | `Float` | Published Corporate Rate: Discount Percentage. |
| 79 | flatOrPercentage | `String` | Flat Or Percentage |
| 80 | folioText | `String` | Text displayed on the Folio |
| 81 | gDSAllowedYn | `String` | Is this rate code available for GDS |
| 82 | groupCode | `String` | Group Code |
| 83 | highlightRateAmountYn | `String` | To highlight on the rate query |
| 84 | houseUseYn | `String` | House Use Y/N |
| 85 | inactiveDate | `Date` | Inactive Date |
| 86 | insertDate | `DateTime` | Insert Date |
| 87 | insertUser | `Float` | Insert User |
| 88 | jRNUpdateDate | `Date` | JRN Update Date |
| 89 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 90 | label | `String` | Label |
| 91 | longInfo | `String` | Long Info |
| 92 | losUnit | `Float` | Indicates the lengh of Stay Unit in days. If value is > 1 then it is a pkg rate code. |
| 93 | loyaltyProgramYn | `String` | Flag to indicate if this is a loyalty program |
| 94 | mandateResvProfiles | `String` | Indicates mandatory reservation profiles. This is used to force entry of profiles on the reservation header if this rate is picked. |
| 95 | marketCode | `String` | Market Code |
| 96 | marshaRateProgram | `String` | Contains the rate program information from the MARSHA interface. |
| 97 | maxAdvanceBooking | `Float` | Max number of days to book rate in advance. |
| 98 | maxLos | `Float` | Max Los |
| 99 | maxOccupancy | `Float` | Max Occupancy |
| 100 | mfnUploadYn | `String` | Flag used to determine if the rate code is to be sent to MyFidelio.net if the rate is being received from a V6 V7 V8 or OPMS on a lower version on which flag used to determine if the rate code is to be sent to MyFidelio.net does not exist on the rate header. |
| 101 | minOccupancy | `Float` | Minimum Occupancy |
| 102 | mobileCheckinAllowedYn | `String` | Mobile Checkin Allowed Y/N |
| 103 | mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| 104 | multiplication | `String` | Amount to be multiplied to the base rate when shown on rate query |
| 105 | negotiated | `String` | Negotiated rate Y/N |
| 106 | occupancyBasedYn | `String` | Indicates if the rate code is occupancy based. |
| 107 | occupancyLevel | `Float` | Indicates the occupancy level for hurdle evaluation. |
| 108 | operatorType | `String` | The operator type to use during the calculation of base rates. (ADD_TO SUBTRACT) |
| 109 | orderBy | `Float` | Order By |
| 110 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 111 | orsSellSequence | `Float` | Indicates the order in which this rate should be displayed during the booking process when the ors_rate_sell_sequence functionality is active. |
| 112 | overridePackageYn | `String` | Indicates if we need to override package for hurdle evaluation. |
| 113 | ownerRateYn | `String` | Indicates Owners Rate Code. This is used to perform rolling noshow. |
| 114 | packageTransactionTaxInclYN | `String` | Wrapper transaction code tax inclusive Y/N |
| 115 | packageTransactionWkTaxInclYN | `String` | Wrapper transaction code tax inclusive for weekend days Y/N |
| 116 | packageTrxCode | `String` | Wrapper transaction code |
| 117 | packageTrxCodeWk | `String` | Wrapper transaction code for weekend days |
| 118 | packageYn | `String` | Package Y/N |
| 119 | pendingApprovalYn | `String` | Indicates whether the rate code is pending for approval or not |
| 120 | postingRhythm | `String` | Posting Rhythm |
| 121 | postingRhythmNights | `Float` | Number of nights for posting rhythm. |
| 122 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 123 | printRateYn | `String` | Print Rate Y/N |
| 124 | privilegedRestrictionYn | `String` | Indicates if restriction for rate is privileged or not. |
| 125 | privilegedYn | `String` | Indicates if rate is privileged or not. |
| 126 | profitTrxCode | `String` | Transaction code for profit |
| 127 | property | `String` | Property |
| 128 | qualifying | `String` | Qualifying |
| 129 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 130 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 131 | rankAdjustmentFactor | `Float` | Any number between -10 and +10. This adjustment factor will be applied to the daily ranking value of table RESORT_DAY_TYPE_DATES for the stay date to determine the Rate code rank value. |
| 132 | rankValue | `Float` | Rank Value |
| 133 | rateBucket | `String` | Yield rate bucket |
| 134 | rateCalendarYn | `String` | Indicates if rate Calendar factors such as adder/multiplier should be used for price calculation. |
| 135 | rateCategories | `String` | Rate Categories |
| 136 | rateClass | `String` | Rate Class |
| 137 | rateCodeLocked | `String` | Not used |
| 138 | rateCodes | `String` | Rate Codes |
| 139 | rateFloor | `Float` | Contains the minimum value of the rate amount which can be defined in the rate details. |
| 140 | rateFloorOverrideYn | `String` | This flag indicates if the Rate Floor Rate is overridden for a particular Rate Code. |
| 141 | rateIncludesTaxYn | `String` | Does this rate include tax? Y/N |
| 142 | rateLevel | `Float` | Rate Level this rate code belongs to. |
| 143 | rateinfoUrl | `String` | Rateinfo Url |
| 144 | ratesToGDSYn | `String` | Needs to send this rate to GDS or not. |
| 145 | redemptionRateYn | `String` | Redemption Rate Y/N |
| 146 | repeatPostingRhythmYn | `String` | Indicates if the posting rhythm on the rate code is repeated until the end of the stay otherwise the posting rhythm is applied only once. |
| 147 | rodBaseAmount | `Float` | Rod Base Amount |
| 148 | rodBaseFltPct | `String` | Rod Base Flt Pct |
| 149 | rodBaseRounding | `String` | Rod Base Rounding |
| 150 | rodBasedYn | `String` | Is the group code rate of day based |
| 151 | rodYn | `String` | Rod Y/N |
| 152 | roomAssignmentValue | `Float` | Room Assignment Value |
| 153 | sdowBeginBookingDate | `Date` | Holds a copy of the column begin_booking_date while the rate code is disabled or with changes pending of approval |
| 154 | sdowEndBookingDate | `Date` | Holds a copy of the column end_booking_date while the rate code is disabled or with changes pending of approval |
| 155 | sellSequence | `Float` | Sell Sequence |
| 156 | serviceInclYn | `String` | PCR: Are Service Charges included in this rate code? |
| 157 | servicePerc | `Float` | Service Percentage included. |
| 158 | shortInfo | `String` | Information to be used in the rate query |
| 159 | showRateAmountYn | `String` | Flag used to show or hide rate column in Block Grid and used as default by block reservations. |
| 160 | sourceCode | `String` | Source Code |
| 161 | taxIncludedPerc | `Float` | Percentage of included Tax. |
| 162 | taxIncludedYn | `String` | Tax is included in this rate. |
| 163 | tieredYn | `String` | Indicates if the rate is a tiered rate. |
| 164 | transactionTaxInclYN | `String` | Transaction code is inclusive of tax Y/N |
| 165 | transactionWkTaxInclYN | `String` | Transaction code is inclusive of tax for weekend days Y/N |
| 166 | trxCode | `String` | Transaction Code |
| 167 | trxCodeWk | `String` | The transaction code associated with this rate for weekend days |
| 168 | updateDate | `DateTime` | Update Date |
| 169 | updateUser | `Float` | Update User |
| 170 | upsellYn | `String` | Indicates if the rate code can be upsold |
| 171 | voucherBenefitRateYn | `String` | Flag to indicate if this is a voucher benefit rate code. |
| 172 | weekendDays | `String` | Indicates weekend days seperated by '' Eg 17 ie Sun and Sat |
| 173 | wkDeptCode | `String` | Wk Dept Code |
| 174 | yieldAs | `String` | Yield As |
| 175 | yieldableYn | `String` | Yieldable Y/N |
| 176 | ymCode | `String` | Ym Code |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipStatusDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPriorityDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `Date` | Inactive Date |
| 16 | inactiveFlag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | internalDeletedflag | `String` | Deleted Flag |
| 20 | internalInactiveflag | `String` | Inactive Flag |
| 21 | internalOrganizationId | `Float` | Organization ID |
| 22 | jRNUpdateDate | `Date` | JRN Update Date |
| 23 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 24 | languageCode | `String` | Language Code |
| 25 | lastUsedDatetime | `Date` | Last Used Datetime |
| 26 | locationID | `String` | Internal ID to uniquely identify the Property |
| 27 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 28 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 29 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 30 | priorityId | `String` | Priority ID |
| 31 | priorityType | `String` | Priority Type.  Default Value is PMSGRID |
| 32 | property | `String` | Property |
| 33 | ranking | `Float` | Ranking |
| 34 | repItem | `String` | Reporting Item |
| 35 | repItemName | `String` | Reporting Item Name |
| 36 | repItemOrderby | `Float` | Reporting Item Orderby |
| 37 | repUpdateDate | `Date` | Reporting Updatedate |
| 38 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 39 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 40 | sequence | `Float` | Sequence |
| 41 | tempFlag | `Float` | Temp Flag |
| 42 | titleSuffix | `Float` | Title Suffix |
| 43 | updateDate | `DateTime` | Update Date |
| 44 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortEntityAccountTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAddressTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortAlternateLanguageTitleDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | canDeleteYn | `String` | Can Delete Y/N |
| 2 | chainCode | `String` | Chain Code |
| 3 | code | `String` | Code |
| 4 | comments | `String` | Comments |
| 5 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 6 | deletedflag | `String` | Deleted Flag |
| 7 | displayColor | `String` | Display Color |
| 8 | entityName | `String` | Entity Name |
| 9 | envelopeGreeting | `String` | Envelope Greeting |
| 10 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 11 | inactiveDate | `DateTime` | Inactive Date |
| 12 | inactiveflag | `String` | Inactive Flag |
| 13 | insertDate | `DateTime` | Insert Date |
| 14 | insertUser | `Float` | Insert User |
| 15 | jRNUpdateDate | `Date` | JRN Update Date |
| 16 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 17 | language | `String` | Language |
| 18 | locationID | `String` | Internal ID to uniquely identify the Property |
| 19 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 20 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 21 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 22 | property | `String` | Property |
| 23 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 24 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 25 | ranking | `Float` | Ranking |
| 26 | repAttributeCode | `String` | Reporting Attribute Code |
| 27 | repDescription | `String` | Reporting Description |
| 28 | repItem | `String` | Reporting Item |
| 29 | repItemName | `String` | Reporting Item Name |
| 30 | repItemOrderby | `Float` | Reporting Item Orderby |
| 31 | repOrderBy | `Float` | Reporting Order By |
| 32 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 33 | salutation | `String` | Salutation |
| 34 | sequence | `Float` | Sequence |
| 35 | titleNumber | `Float` | Title Number |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortRoomsPotentialDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `Date` | Inactive Date |
| 16 | inactiveFlag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | internalDeletedflag | `String` | Deleted Flag |
| 20 | internalInactiveflag | `String` | Inactive Flag |
| 21 | internalOrganizationId | `Float` | Organization ID |
| 22 | jRNUpdateDate | `Date` | JRN Update Date |
| 23 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 24 | languageCode | `String` | Language Code |
| 25 | lastUsedDatetime | `Date` | Last Used Datetime |
| 26 | locationID | `String` | Internal ID to uniquely identify the Property |
| 27 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 28 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 29 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 30 | property | `String` | Property |
| 31 | ranking | `Float` | Ranking |
| 32 | repItem | `String` | Reporting Item |
| 33 | repItemName | `String` | Reporting Item Name |
| 34 | repItemOrderby | `Float` | Reporting Item Orderby |
| 35 | repUpdateDate | `Date` | Reporting Updatedate |
| 36 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 37 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 38 | roomsPotentialType | `String` | Rooms Potential Type |
| 39 | sequence | `Float` | Sequence |
| 40 | tempFlag | `String` | Temp Flag |
| 41 | titleSuffix | `Float` | Title Suffix |
| 42 | updateDate | `DateTime` | Update Date |
| 43 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortBusinessSegmentDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCompanyTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortCompetitionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | attributeCode | `String` | Attribute Code |
| 2 | businessTitle | `String` | Business Title |
| 3 | canDeleteYn | `String` | Can Delete Y/N |
| 4 | centralCompetition | `String` | Central Competition |
| 5 | centralDescription | `String` | Central Description |
| 6 | centralSequence | `Float` | Central Sequence |
| 7 | chainCode | `String` | Chain Code |
| 8 | code | `String` | Code |
| 9 | comments | `String` | Comments |
| 10 | competition | `String` | Competition |
| 11 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 12 | deletedFlag | `String` | Deleted Flag |
| 13 | description | `String` | Description |
| 14 | displayColor | `String` | Display Color |
| 15 | entityName | `String` | Entity Name |
| 16 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 17 | inactiveDate | `Date` | Inactive Date |
| 18 | inactiveFlag | `String` | Inactive Flag |
| 19 | insertDate | `DateTime` | Insert Date |
| 20 | insertUser | `Float` | Insert User |
| 21 | internalOrganizationId | `Float` | Organization ID |
| 22 | jRNUpdateDate | `Date` | JRN Update Date |
| 23 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 24 | languageCode | `String` | Language Code |
| 25 | lastUsedDatetime | `Date` | Last Used Datetime |
| 26 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 27 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 28 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 29 | property | `String` | Property |
| 30 | ranking | `Float` | Ranking |
| 31 | repItem | `String` | Reporting Item |
| 32 | repItemName | `String` | Reporting Item Name |
| 33 | repItemOrderby | `Float` | Reporting Item Orderby |
| 34 | repUpdateDate | `Date` | Reporting Updatedate |
| 35 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 36 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 37 | sequence | `Float` | Sequence |
| 38 | tempFlag | `Float` | Temp Flag |
| 39 | titleSuffix | `Float` | Title Suffix |
| 40 | updateDate | `DateTime` | Update Date |
| 41 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortGenderDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortProfileInactiveReasonDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortIndustryCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortInfluenceCodeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortKeywordTypeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMailingActionDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedFlag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `Date` | Inactive Date |
| 16 | inactiveFlag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | internalDeletedflag | `String` | Deleted Flag |
| 20 | internalInactiveflag | `String` | Inactive Flag |
| 21 | internalOrganizationId | `Float` | Organization ID |
| 22 | jRNUpdateDate | `Date` | JRN Update Date |
| 23 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 24 | languageCode | `String` | Language Code |
| 25 | lastUsedDatetime | `Date` | Last Used Datetime |
| 26 | locationID | `String` | Internal ID to uniquely identify the Property |
| 27 | mailingActionType | `String` | Mailing Action Type |
| 28 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 29 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 30 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 31 | property | `String` | Property |
| 32 | ranking | `Float` | Ranking |
| 33 | repItem | `String` | Reporting Item |
| 34 | repItemName | `String` | Reporting Item Name |
| 35 | repItemOrderby | `Float` | Reporting Item Orderby |
| 36 | repUpdateDate | `Date` | Reporting Updatedate |
| 37 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 38 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 39 | sequence | `Float` | Sequence |
| 40 | tempFlag | `String` | Temp Flag |
| 41 | titleSuffix | `Float` | Title Suffix |
| 42 | updateDate | `DateTime` | Update Date |
| 43 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortPreferenceDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | amenityYn | `String` | Indicates if a special request is an Amenity. Used in SPG Transformation functionality. |
| 2 | cExchangeDate | `Date` | Central Xchange Date |
| 3 | cExchangeRate | `Float` | Central Xchange Rate |
| 4 | cRoomAssignmentValue | `Float` | Central Room Assignment Value |
| 5 | cRSPreferenceYn | `String` | Whether this Preference is used in CRS Module or not. |
| 6 | canDeleteYn | `String` | Can Delete Y/N |
| 7 | centralCode | `Float` | Central Code |
| 8 | centralDescription | `String` | Central Description |
| 9 | centralSequence | `Float` | Central Sequence |
| 10 | chainCode | `String` | Chain Code |
| 11 | corporateYn | `String` | Indicates if the preference is configured as Global in ORS. |
| 12 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 13 | deletedFlag | `String` | Deleted Flag |
| 14 | description1 | `String` | Description of the first column in the query result. |
| 15 | housekeepingYn | `String` | Indicated if this floor preference is used for task assignments broken out by floor. |
| 16 | inactiveDate | `DateTime` | Inactive Date |
| 17 | inactiveFlag | `String` | Inactive Flag |
| 18 | insertDate | `DateTime` | Insert Date |
| 19 | insertUser | `Float` | Insert User |
| 20 | internalOrganizationId | `Float` | Organization ID |
| 21 | jRNUpdateDate | `Date` | JRN Update Date |
| 22 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 23 | locationId | `String` | Location ID |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | owsAllowedYN | `String` | Indicates if the preference is exposed in OWS Lookup queries. |
| 26 | preferenceAttribute | `String` | Preference Attribute. |
| 27 | preferenceCode | `String` | Preference Code |
| 28 | preferenceDescription | `String` | Preference Description |
| 29 | preferenceGroup | `String` | Preference Group |
| 30 | preferenceId | `Float` | Internal Id of the preference |
| 31 | preferenceSubType | `String` | Preference Sub Type. |
| 32 | preference1 | `String` | Preference1 |
| 33 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 34 | property | `String` | Property |
| 35 | repItem | `String` | Reporting Item |
| 36 | repItemName | `String` | Reporting Item Name |
| 37 | repItemOrderby | `Float` | Reporting Item Orderby |
| 38 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 39 | reportingPreferenceSequenceId | `String` | Rep Preference Seq ID |
| 40 | rnaInsertDate | `DateTime` | RnA Insertdate |
| 41 | rnaUpdateDate | `DateTime` | RnA Updatedate |
| 42 | roomAssignmentValue | `Float` | Room Assignment Value |
| 43 | sendDeleteRequestYn | `String` | Indicates delete preference request should be to central system instead of deleting the preference from profile. |
| 44 | sequence | `Float` | Sequence |
| 45 | source | `String` | Source |
| 46 | updateDate | `DateTime` | Update Date |
| 47 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortProfileRestrictionReasonDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | chainCode | `String` | Chain Code |
| 4 | code | `String` | Code |
| 5 | comments | `String` | Comments |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedflag | `String` | Deleted Flag |
| 8 | description | `String` | Description |
| 9 | displayColor | `String` | Display Color |
| 10 | entityName | `String` | Entity Name |
| 11 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 12 | inactiveDate | `DateTime` | Inactive Date |
| 13 | inactiveflag | `String` | Inactive Flag |
| 14 | insertDate | `DateTime` | Insert Date |
| 15 | insertUser | `Float` | Insert User |
| 16 | jRNUpdateDate | `Date` | JRN Update Date |
| 17 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 18 | languageCode | `String` | Language Code |
| 19 | locationID | `String` | Internal ID to uniquely identify the Property |
| 20 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 21 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 22 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 23 | property | `String` | Property |
| 24 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 25 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 26 | ranking | `Float` | Ranking |
| 27 | repAttributeCode | `String` | Reporting Attribute Code |
| 28 | repDescription | `String` | Reporting Description |
| 29 | repItem | `String` | Reporting Item |
| 30 | repItemName | `String` | Reporting Item Name |
| 31 | repItemOrderby | `Float` | Reporting Item Orderby |
| 32 | repOrderBy | `Float` | Reporting Order By |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSalesEventScopeDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortSalesEventScopeCityDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | businessTitle | `String` | Business Title |
| 2 | canDeleteYn | `String` | Can Delete Y/N |
| 3 | centralCode | `String` | Central Code |
| 4 | centralDescription | `String` | Central Description |
| 5 | centralSequence | `Float` | Central Sequence |
| 6 | chainCode | `String` | Chain Code |
| 7 | code | `String` | Code |
| 8 | comments | `String` | Comments |
| 9 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 10 | deletedflag | `String` | Deleted Flag |
| 11 | description | `String` | Description |
| 12 | displayColor | `String` | Display Color |
| 13 | entityName | `String` | Entity Name |
| 14 | externalAttributeCodes | `String` | Contains a list of codes used by a vendor. |
| 15 | inactiveDate | `DateTime` | Inactive Date |
| 16 | inactiveflag | `String` | Inactive Flag |
| 17 | insertDate | `DateTime` | Insert Date |
| 18 | insertUser | `Float` | Insert User |
| 19 | jRNUpdateDate | `Date` | JRN Update Date |
| 20 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 21 | languageCode | `String` | Language Code |
| 22 | locationID | `String` | Internal ID to uniquely identify the Property |
| 23 | masterSubKeywordYn | `String` | Indicates if the KEYWORD TYPE is to be copied from a Company Master to a Company Subsidiary. |
| 24 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 25 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 26 | property | `String` | Property |
| 27 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 28 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 29 | ranking | `Float` | Ranking |
| 30 | repItem | `String` | Reporting Item |
| 31 | repItemName | `String` | Reporting Item Name |
| 32 | repItemOrderby | `Float` | Reporting Item Orderby |
| 33 | repUpdateDate | `DateTime` | Reporting Updatedate |
| 34 | sequence | `Float` | Sequence |
| 35 | titleSuffix | `Float` | Title Suffix |
| 36 | updateDate | `DateTime` | Update Date |
| 37 | updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### ConfigurationResortMembershipClaimAdjustmentLimitDetailsType

| No. | Field | Type | Description |
| --- | --- | --- | --- |
| 1 | adjustmentLimitCode | `String` | Adjustment Limit Code |
| 2 | awardLowerLimit | `Float` | Lower limit for award. |
| 3 | awardUpperLimit | `Float` | Higher limit for award. |
| 4 | billingGroup | `String` | Billing Group |
| 5 | chainCode | `String` | Chain Code |
| 6 | dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| 7 | deletedFlag | `String` | Deleted Flag |
| 8 | insertDate | `DateTime` | Insert Date |
| 9 | insertUser | `Float` | Insert User |
| 10 | jRNUpdateDate | `Date` | JRN Update Date |
| 11 | jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| 12 | organizationID | `Float` | Internal ID to uniquely identify the Organization |
| 13 | primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| 14 | property | `String` | Deprecated. Child table GDS_ACCESS_CODE_RESORTS will instead hold all properties to which to auto publish. |
| 15 | rNAInsertDate | `DateTime` | RNA Insert Date |
| 16 | rNAUpdateDate | `DateTime` | RNA Update Date |
| 17 | tierNightsLowerLimit | `Float` | Lower limit for tier points for nights. |
| 18 | tierNightsUpperLimit | `Float` | Higher limit for tier points for nights. |
| 19 | tierRevenueLowerLimit | `Float` | Lower limit for tier points for revenue. |
| 20 | tierRevenueUpperLimit | `Float` | Higher limit for tier points for revenue. |
| 21 | tierStaysLowerLimit | `Float` | Lower limit for tier points for stay. |
| 22 | tierStaysUpperLimit | `Float` | Higher limit for tier points for stay. |
| 23 | updateDate | `DateTime` | Update Date |
| 24 | updateUser | `Float` | Update User |

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
#### Validation Rules

**`conditionalInputPair(pair: 1)`**
- resortDetailsResort


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

## Parquet Schema
> Explicit data types generated from the GraphQL specification to ensure safe Parquet conversion and prevent schema inference errors. (using Python `Polars`)
  
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
membership_claim_origin_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'claimOriginCode': pl.Utf8,
    'claimOriginDescription': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_points_details_schema = {
    'allMembershipRatesYn': pl.Utf8,
    'allMembershipTransactionYN': pl.Utf8,
    'averageRateAmount': pl.Float64,
    'beginDate': pl.Utf8,
    'billingGroup': pl.Utf8,
    'bookingEndDate': pl.Utf8,
    'bookingStartDate': pl.Utf8,
    'calculationRule': pl.Utf8,
    'chainCode': pl.Utf8,
    'costPerPoint': pl.Float64,
    'creditMultipleMembershipYn': pl.Utf8,
    'dSI': pl.Int64,
    'daysSinceEnrolled': pl.Float64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'earningRhythmFlg': pl.Utf8,
    'earningRhythmNights': pl.Float64,
    'endDate': pl.Utf8,
    'enrollmentCode': pl.Utf8,
    'enrollmentGroup': pl.Utf8,
    'excludeBbFlg': pl.Utf8,
    'excludeFromPointProjectionYN': pl.Utf8,
    'excludeMktGroup': pl.Utf8,
    'excludeRevGroup': pl.Utf8,
    'excludeRoomGroupYn': pl.Utf8,
    'expirationDate': pl.Utf8,
    'exportLabel': pl.Utf8,
    'fridayYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'includeGraceRenewalFlg': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketGroup': pl.Utf8,
    'marketGroupIncludeYN': pl.Utf8,
    'maxBucketSize': pl.Float64,
    'maximumNights': pl.Float64,
    'maximumRevenue': pl.Float64,
    'memRevenueGroup': pl.Utf8,
    'membershipLevel': pl.Utf8,
    'membershipPointsSeqno': pl.Float64,
    'membershipRateGroupExcludeYN': pl.Utf8,
    'membershipType': pl.Utf8,
    'minPropertiesReq': pl.Float64,
    'minimumNights': pl.Float64,
    'minimumRateAmount': pl.Float64,
    'minimumRevenue': pl.Float64,
    'minimumStays': pl.Float64,
    'mondayYN': pl.Utf8,
    'multipleTransactionsYn': pl.Utf8,
    'numberOfTimesEligible': pl.Float64,
    'organizationID': pl.Int64,
    'perRevenueUnits': pl.Float64,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'pointsRatioPercentYn': pl.Utf8,
    'pointsRatioRoundingFlg': pl.Utf8,
    'preferredCardExcludeYn': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'programType': pl.Utf8,
    'programTypeDesc': pl.Utf8,
    'promotionCode': pl.Utf8,
    'property': pl.Utf8,
    'propertyGroup': pl.Utf8,
    'pseudoRuleYn': pl.Utf8,
    'qualifyingRatesYN': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateGroup': pl.Utf8,
    'rateGroupIncludeYN': pl.Utf8,
    'reservationChannel': pl.Utf8,
    'revenueGroup': pl.Utf8,
    'revenueGroupIncludeYN': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomGroup': pl.Utf8,
    'roomType': pl.Utf8,
    'roomTypeToChargeYN': pl.Utf8,
    'rounding': pl.Utf8,
    'ruleAppliesTo': pl.Utf8,
    'ruleBasedOn': pl.Utf8,
    'ruleCode': pl.Utf8,
    'saturdayYN': pl.Utf8,
    'sundayYN': pl.Utf8,
    'thursdayYN': pl.Utf8,
    'toMemberLevel': pl.Utf8,
    'transactionType': pl.Utf8,
    'tuesdayYN': pl.Utf8,
    'type': pl.Utf8,
    'typeOfPoints': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'userpostingOnlyYn': pl.Utf8,
    'wednesdayYN': pl.Utf8,
}
```
```python
membership_award_rates_details_schema = {
    'awardType': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'membershipType': pl.Utf8,
    'organizationID': pl.Int64,
    'property': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateDescription': pl.Utf8,
}
```
```python
membership_award_products_details_schema = {
    'awardType': pl.Utf8,
    'centralPackageCode': pl.Utf8,
    'centralPackageDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'membershipType': pl.Utf8,
    'organizationID': pl.Int64,
    'packageCode': pl.Utf8,
    'packageDescription': pl.Utf8,
    'property': pl.Utf8,
}
```
```python
membership_award_upgrades_details_schema = {
    'awardType': pl.Utf8,
    'centralUpgradeFromRoom': pl.Utf8,
    'centralUpgradeToRoom': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'fromDate': pl.Utf8,
    'fromRoom': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipAwardId': pl.Float64,
    'membershipType': pl.Utf8,
    'organizationID': pl.Int64,
    'pointsRequiredUpgrades': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'toDate': pl.Utf8,
    'toRoom': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upgradeFromRoom': pl.Utf8,
    'upgradeToRoom': pl.Utf8,
}
```
```python
membership_award_financial_transaction_details_schema = {
    'awardType': pl.Utf8,
    'centralTransactionCode': pl.Utf8,
    'centralTransactionCodeDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipType': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'transactionCode': pl.Utf8,
    'transactionCodeDescription': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_property_group_code_details_schema = {
    'attachedPropertyCode': pl.Utf8,
    'attachedPropertyDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'membershipResortGroup': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'requiredYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
airport_details_schema = {
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'distance': pl.Float64,
    'distanceType': pl.Utf8,
    'drivingDirections': pl.Utf8,
    'drivingTime': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'sequence': pl.Float64,
    'transportationCode1': pl.Utf8,
    'transportationCode2': pl.Utf8,
    'transportationCode3': pl.Utf8,
    'transportationCode4': pl.Utf8,
    'transportationCode5': pl.Utf8,
    'transportationCode6': pl.Utf8,
    'transportationCode7': pl.Utf8,
    'transportationCode8': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'website': pl.Utf8,
}
```
```python
feature_details_schema = {
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'endDate': pl.Utf8,
    'featureType': pl.Utf8,
    'featureid': pl.Utf8,
    'hours': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'notes': pl.Utf8,
    'organizationID': pl.Int64,
    'price': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'startDate': pl.Utf8,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
attraction_category_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
attraction_details_schema = {
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'attractionClass': pl.Utf8,
    'category': pl.Utf8,
    'city': pl.Utf8,
    'code': pl.Utf8,
    'coordinateSupplier': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'direction': pl.Utf8,
    'directions': pl.Utf8,
    'distance': pl.Float64,
    'distanceType': pl.Utf8,
    'drivingTime': pl.Utf8,
    'generalDirections': pl.Utf8,
    'hoursOfOperation': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'latitude': pl.Float64,
    'longitude': pl.Float64,
    'organizationID': pl.Int64,
    'priceRange': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'region': pl.Utf8,
    'sequence': pl.Float64,
    'state': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'website': pl.Utf8,
    'zipCode': pl.Utf8,
}
```
```python
chain_details_schema = {
    'aspYn': pl.Utf8,
    'beginDate': pl.Utf8,
    'bookingConditions': pl.Utf8,
    'centralChain': pl.Utf8,
    'centralDescription': pl.Utf8,
    'chain': pl.Utf8,
    'chainName': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'endDate': pl.Utf8,
    'frequentFlierCardsAcceptYn': pl.Utf8,
    'hoCity': pl.Utf8,
    'hoCountry': pl.Utf8,
    'hoEmail': pl.Utf8,
    'hoFax': pl.Utf8,
    'hoPostCode': pl.Utf8,
    'hoState': pl.Utf8,
    'hoStreet': pl.Utf8,
    'hoTelephone': pl.Utf8,
    'imgChainId': pl.Float64,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'logoFileName': pl.Utf8,
    'loyaltyProgram': pl.Utf8,
    'marketingText': pl.Utf8,
    'nameId': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'scriptId': pl.Float64,
    'shareProfilesYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
closing_script_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'membershipType': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'resortType': pl.Utf8,
    'scriptId': pl.Float64,
    'scriptType': pl.Utf8,
}
```
```python
communication_method_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
delivery_status_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
department_details_schema = {
    'allowOnTaskSheetYn': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'departmentCode': pl.Utf8,
    'departmentid': pl.Utf8,
    'deptManagerPager': pl.Utf8,
    'description': pl.Utf8,
    'email': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'messageText': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'repDeptName': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'reportingDeptId': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
elec_reg_card_script_details_schema = {
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'membershipType': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'resortType': pl.Utf8,
    'scriptId': pl.Float64,
    'scriptType': pl.Utf8,
}
```
```python
hub_property_details_schema = {
    'associatedProperty': pl.Utf8,
    'associatedPropertyName': pl.Utf8,
    'croCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
job_title_details_schema = {
    'chainCode': pl.Utf8,
    'closingScriptYn': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
}
```
```python
u_df_category_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
u_df_type_details_schema = {
    'attributeType': pl.Utf8,
    'attributeVerified': pl.Utf8,
    'category': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'multipleYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'tableName': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
brand_code_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
business_unit_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
department_code_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
division_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
hotel_category_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
operating_unit_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
application_parameter_value_details_schema = {
    'aPNDeletedFlag': pl.Utf8,
    'aPNDisplayYN': pl.Utf8,
    'aPNJRNUpdateDate': pl.Utf8,
    'aPNJRNUpdateDateAndTime': pl.Utf8,
    'aPNPrimaryKeyID': pl.Float64,
    'aPNRNAInsertDate': pl.Utf8,
    'aPNRNAUpdateDate': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'copyYn': pl.Utf8,
    'coreYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayYn': pl.Utf8,
    'explanation': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lovValues': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'parameterDescription': pl.Utf8,
    'parameterDisplayName': pl.Utf8,
    'parameterGroup': pl.Utf8,
    'parameterName': pl.Utf8,
    'parameterType': pl.Utf8,
    'parameterTypeDetail': pl.Utf8,
    'parameterValue': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'storedInResort': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'usedInApp': pl.Utf8,
}
```
```python
trackit_action_details_schema = {
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'defaultYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'messageText': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sendMessageYn': pl.Utf8,
    'sequence': pl.Float64,
    'status': pl.Utf8,
    'tiSubgroup': pl.Utf8,
    'trackItGroup': pl.Utf8,
    'trackitTypesUrl': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
trackit_location_details_schema = {
    'actionStatus': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'defaultYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'messageText': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sendMessageYn': pl.Utf8,
    'sequence': pl.Float64,
    'tiSubgroup': pl.Utf8,
    'trackItGroup': pl.Utf8,
    'trackitTypesUrl': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
trackit_type_details_schema = {
    'actionStatus': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'defaultYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'messageText': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sendMessageYN': pl.Utf8,
    'sequence': pl.Float64,
    'tiSubgroup': pl.Utf8,
    'trackItGroup': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'website': pl.Utf8,
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
a_r_reminder_cycle_details_schema = {
    'accountTypeId': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'globalAccountYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'letterName': pl.Utf8,
    'numberOfDays': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reminderCode': pl.Float64,
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
transaction_reason_code_details_schema = {
    'adjustmentCode': pl.Utf8,
    'adjustmentCodeDescription': pl.Utf8,
    'adjustmentType': pl.Utf8,
    'amountPercentFlag': pl.Utf8,
    'amountPercentValue': pl.Float64,
    'birGuestType': pl.Utf8,
    'codeType': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'tranCodeType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
credit_card_authorization_rules_details_schema = {
    'amount': pl.Float64,
    'authorizationRules': pl.Float64,
    'cAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'guaranteeCode': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'mainWindowYn': pl.Utf8,
    'organizationID': pl.Int64,
    'percentage': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCategory': pl.Utf8,
    'rateCode': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomType': pl.Utf8,
    'sourceCode': pl.Utf8,
}
```
```python
auto_folio_settlement_type_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
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
custom_number_details_schema = {
    'activeYN': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'customNumberFormula': pl.Utf8,
    'customNumberType': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'endDate': pl.Utf8,
    'filterCondition': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'startDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
currency_exchange_tax_details_schema = {
    'amountFrom': pl.Float64,
    'amountTo': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cMaxAmount': pl.Float64,
    'cMaxServiceTax': pl.Float64,
    'cMinimumAmount': pl.Float64,
    'cMinimumServiceTax': pl.Float64,
    'cNotionalAmount': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'maximum': pl.Float64,
    'minimum': pl.Float64,
    'notionalAmount': pl.Float64,
    'organizationID': pl.Int64,
    'percentage': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'serviceTaxType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
expense_arrangement_code_details_schema = {
    'arrTaxTypeCode': pl.Utf8,
    'arrangeId': pl.Utf8,
    'arrangementId': pl.Float64,
    'bucketValue': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRoutingAmount': pl.Float64,
    'compYn': pl.Utf8,
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
    'expenseArrangementCode': pl.Utf8,
    'expenseArrangementDescription': pl.Utf8,
    'exportBucketType': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inheritAuthRatecodeYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'revenueYn': pl.Utf8,
    'routingAmount': pl.Float64,
    'routingCovers': pl.Float64,
    'routingPercent': pl.Float64,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
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
folio_arrangement_code_details_schema = {
    'arrTaxTypeCode': pl.Utf8,
    'arrangeId': pl.Utf8,
    'arrangementId': pl.Float64,
    'bucketValue': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRoutingAmount': pl.Float64,
    'compYn': pl.Utf8,
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
    'folioArrangementCode': pl.Utf8,
    'folioArrangementDescription': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inheritAuthRatecodeYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'revenueYn': pl.Utf8,
    'routingAmount': pl.Float64,
    'routingCovers': pl.Float64,
    'routingPercent': pl.Float64,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
group_arrangement_code_details_schema = {
    'arrTaxTypeCode': pl.Utf8,
    'arrangeId': pl.Utf8,
    'arrangementId': pl.Float64,
    'bucketValue': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRoutingAmount': pl.Float64,
    'compYn': pl.Utf8,
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
    'groupArrangementCode': pl.Utf8,
    'groupArrangementDescription': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inheritAuthRatecodeYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'revenueYn': pl.Utf8,
    'routingAmount': pl.Float64,
    'routingCovers': pl.Float64,
    'routingPercent': pl.Float64,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
folio_type_details_schema = {
    'allowCompressYn': pl.Utf8,
    'allowConvertYn': pl.Utf8,
    'allowCreditbillYn': pl.Utf8,
    'allowDifferenceProfile': pl.Utf8,
    'arfolioName': pl.Utf8,
    'associatedCreditFolioType': pl.Utf8,
    'clFlag': pl.Utf8,
    'columnSeparator': pl.Utf8,
    'compressYn': pl.Utf8,
    'convertFolioType': pl.Utf8,
    'correctionFolioYn': pl.Utf8,
    'correctionHeaderYn': pl.Utf8,
    'creditYN': pl.Utf8,
    'currencyActionId': pl.Float64,
    'customOnProfAttributesYn': pl.Utf8,
    'dSI': pl.Int64,
    'debitBillYN': pl.Utf8,
    'debitFlag': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depositFolioYn': pl.Utf8,
    'directBillYn': pl.Utf8,
    'documentCode': pl.Utf8,
    'fiscalPrintingYn': pl.Utf8,
    'fiscalProgramName': pl.Utf8,
    'fiscalYn': pl.Utf8,
    'folioName': pl.Utf8,
    'folioTypeCode': pl.Utf8,
    'guestType': pl.Float64,
    'internalBillYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'localCurrFlag': pl.Utf8,
    'manualFolioPrintTask': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'nationalityFlag': pl.Utf8,
    'organizationID': pl.Int64,
    'originalFolioStayDetailsYN': pl.Utf8,
    'passerbyfolioName': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'printFolioYn': pl.Utf8,
    'property': pl.Utf8,
    'queueName': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'simpleFolioYn': pl.Utf8,
    'taxNoFlag': pl.Utf8,
    'trxServiceType': pl.Utf8,
    'workingDocsYn': pl.Utf8,
}
```
```python
folio_type_detail_details_schema = {
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'folioType': pl.Utf8,
    'group': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
}
```
```python
bank_account_details_schema = {
    'accountId': pl.Float64,
    'accountNumber': pl.Utf8,
    'bankAcctType': pl.Utf8,
    'bankCode': pl.Utf8,
    'branchCode': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralMinProcessingAmount': pl.Float64,
    'checkReport': pl.Utf8,
    'checkSubLines': pl.Float64,
    'currency': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Int64,
    'defaultYN': pl.Utf8,
    'defaultForCurrencyYN': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'editCheckNumberYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'lastExportDate': pl.Utf8,
    'lastExportedFile': pl.Float64,
    'maxCheckNo': pl.Float64,
    'minProcessingAmount': pl.Float64,
    'nextCheckNumber': pl.Float64,
    'onHold': pl.Float64,
    'organizationID': pl.Int64,
    'paidInAR': pl.Float64,
    'paymentMethod': pl.Utf8,
    'positivePayExportYN': pl.Utf8,
    'potential': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'routingNumber': pl.Utf8,
    'sourceImportDir': pl.Utf8,
    'targetImportDir': pl.Utf8,
    'tax1099ReportYN': pl.Utf8,
    'toBePaid': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'validateIATANumberYN': pl.Utf8,
}
```
```python
commission_details_schema = {
    'amount': pl.Float64,
    'basedOn': pl.Utf8,
    'cAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cVatAmount': pl.Float64,
    'centralCode': pl.Utf8,
    'centralCommissionDescription': pl.Utf8,
    'code': pl.Utf8,
    'commissionCalcRule': pl.Utf8,
    'commissionFlatPercentage': pl.Utf8,
    'commissionamount': pl.Float64,
    'commissionid': pl.Utf8,
    'dSI': pl.Int64,
    'defaultYN': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'holdARYN': pl.Utf8,
    'holdAlwaysYN': pl.Utf8,
    'holdPrepaidYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'masteralias': pl.Float64,
    'organizationID': pl.Int64,
    'perNight': pl.Utf8,
    'perNightAmount': pl.Float64,
    'perStay': pl.Utf8,
    'perStayAmount': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repSellSequence': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sellSequence': pl.Float64,
    'taxPercent': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
authorizer_group_details_schema = {
    'code': pl.Utf8,
    'compAuthorizerGroupDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
authorizer_group_detail_details_schema = {
    'arrangementId': pl.Float64,
    'authGroupCode': pl.Utf8,
    'cCreditLimit': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cOccurrenceLimit': pl.Float64,
    'centralTransactionCodes': pl.Utf8,
    'compRoutingCodes': pl.Utf8,
    'dSI': pl.Int64,
    'dailyCreditLimit': pl.Float64,
    'deletedFlag': pl.Utf8,
    'groupHeaderId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'transactionCodes': pl.Utf8,
    'transferLimit': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
authorizer_details_schema = {
    'aRAccountNumber': pl.Utf8,
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
    'appPassword': pl.Utf8,
    'appUserDescription': pl.Utf8,
    'appUserId': pl.Float64,
    'appUserType': pl.Utf8,
    'appUserUniq': pl.Utf8,
    'authHeaderId': pl.Float64,
    'authorizerGroup': pl.Utf8,
    'authorizerId': pl.Float64,
    'authorizerInactiveDate': pl.Utf8,
    'authorizerYn': pl.Utf8,
    'cCreditLimit': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cHourlyRate': pl.Float64,
    'cOccurrenceLimit': pl.Float64,
    'cWeeklySalary': pl.Float64,
    'centralTransactionCodes': pl.Utf8,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'compRoutingCodes': pl.Utf8,
    'dSI': pl.Int64,
    'dailyCreditLimit': pl.Float64,
    'dateHired': pl.Utf8,
    'defCashierId': pl.Float64,
    'defaultForm': pl.Utf8,
    'defaultLanguage': pl.Utf8,
    'defaultMfnResort': pl.Utf8,
    'defaultReportgroup': pl.Utf8,
    'defaultResort': pl.Utf8,
    'defaultTerminal': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'deptId': pl.Utf8,
    'description': pl.Utf8,
    'disabledUntil': pl.Utf8,
    'empExtension': pl.Utf8,
    'empPager': pl.Utf8,
    'empStatus': pl.Utf8,
    'employeeIncentiveNumber': pl.Utf8,
    'employeeNumber': pl.Utf8,
    'expiresOn': pl.Utf8,
    'firstName': pl.Utf8,
    'forcePasswordChangeYn': pl.Utf8,
    'fridayMax': pl.Float64,
    'fridayMin': pl.Float64,
    'generalFilepath': pl.Utf8,
    'graceLogin': pl.Float64,
    'hireType': pl.Utf8,
    'hourlyRate': pl.Float64,
    'hoursPerWeek': pl.Float64,
    'inactiveDate': pl.Utf8,
    'inactiveFrom': pl.Utf8,
    'inactiveReasonCode': pl.Utf8,
    'inactiveTo': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalYn': pl.Utf8,
    'isSuperuser': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'laptopId': pl.Float64,
    'lastLoggedResort': pl.Utf8,
    'lastLoggedTimestamp': pl.Utf8,
    'lastName': pl.Utf8,
    'leadAddress': pl.Utf8,
    'leadAddressDet': pl.Utf8,
    'leadComm': pl.Utf8,
    'lockoutDate': pl.Utf8,
    'loginAttempts': pl.Float64,
    'loginCro': pl.Utf8,
    'loginDomain': pl.Utf8,
    'maleFemale': pl.Utf8,
    'maxCheckoutDays': pl.Float64,
    'maxDaysAfterCo': pl.Float64,
    'maxUserSessions': pl.Float64,
    'mfnUserType': pl.Utf8,
    'mobileAlertsYn': pl.Utf8,
    'mondayMax': pl.Float64,
    'mondayMin': pl.Float64,
    'nCExchangeDate': pl.Utf8,
    'nCExchangeRate': pl.Float64,
    'nDeletedFlag': pl.Utf8,
    'nInsertDate': pl.Utf8,
    'nInsertUser': pl.Float64,
    'nUpdateDate': pl.Utf8,
    'nUpdateUser': pl.Float64,
    'occurrenceLimit': pl.Float64,
    'oraclePassword': pl.Utf8,
    'oracleUid': pl.Float64,
    'oracleUser': pl.Utf8,
    'organizationID': pl.Int64,
    'otMultiplier': pl.Float64,
    'passwordChangeDays': pl.Float64,
    'passwordLastChange': pl.Utf8,
    'personNameId': pl.Float64,
    'preventAccountLockout': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'propertyAccessYn': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateType': pl.Utf8,
    'receiveBroadcastMsg': pl.Utf8,
    'rehireYn': pl.Utf8,
    'salaryInterval': pl.Utf8,
    'saturdayMax': pl.Float64,
    'saturdayMin': pl.Float64,
    'serviceRequestAlertsYn': pl.Utf8,
    'sfaName': pl.Utf8,
    'srepCode': pl.Utf8,
    'srepGroup': pl.Utf8,
    'sundayMax': pl.Float64,
    'sundayMin': pl.Float64,
    'termReason': pl.Utf8,
    'terminatedDate': pl.Utf8,
    'thursdayMax': pl.Float64,
    'thursdayMin': pl.Float64,
    'timezoneRegion': pl.Utf8,
    'title': pl.Utf8,
    'transactionCodes': pl.Utf8,
    'transferLimit': pl.Float64,
    'tuesdayMax': pl.Float64,
    'tuesdayMin': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'userFilepath': pl.Utf8,
    'userGroupAdmin': pl.Utf8,
    'userIDCode': pl.Utf8,
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
bucket_redemption_code_details_schema = {
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'transactionCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
comp_routing_code_details_schema = {
    'applyPerDayYN': pl.Utf8,
    'arrTaxTypeCode': pl.Utf8,
    'arrangementId': pl.Float64,
    'bucketValue': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRoutingAmount': pl.Float64,
    'centralTransactionCodes': pl.Utf8,
    'code': pl.Utf8,
    'compYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'eligibleYn': pl.Utf8,
    'exportBucketType': pl.Utf8,
    'friday': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inheritRateCodeYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'monday': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'revenueYn': pl.Utf8,
    'routingAmount': pl.Float64,
    'routingCovers': pl.Float64,
    'routingPercentage': pl.Float64,
    'saturday': pl.Utf8,
    'sunday': pl.Utf8,
    'thursday': pl.Utf8,
    'transactionCodes': pl.Utf8,
    'tuesday': pl.Utf8,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'wednesday': pl.Utf8,
}
```
```python
comp_transaction_code_details_schema = {
    'aRNameId': pl.Float64,
    'accountNumber': pl.Utf8,
    'accountingCode': pl.Utf8,
    'acctrecvprofileid': pl.Float64,
    'adjTrxCode': pl.Utf8,
    'adjtranscodeid': pl.Utf8,
    'arrangeCode': pl.Utf8,
    'cDefaultPrice': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cExportBucket': pl.Float64,
    'cMaxAmount': pl.Float64,
    'cMinimumAmount': pl.Float64,
    'cCCode': pl.Utf8,
    'cRSTaxDesc': pl.Utf8,
    'ccType': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralGroup': pl.Utf8,
    'centralSubgroup': pl.Utf8,
    'checkNumberMandatoryYN': pl.Utf8,
    'class1MandatoryYn': pl.Utf8,
    'class2MandatoryYn': pl.Utf8,
    'code': pl.Utf8,
    'commission': pl.Float64,
    'compNightsYn': pl.Utf8,
    'compPaymentsYN': pl.Utf8,
    'compYn': pl.Utf8,
    'corpPropFlag': pl.Utf8,
    'corporateDescription': pl.Utf8,
    'currency': pl.Utf8,
    'dSI': pl.Int64,
    'dailyPlanFolio': pl.Float64,
    'dedOwnerRevenueYN': pl.Utf8,
    'defaultPrice': pl.Float64,
    'deferredYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'depositPostingOnlyYn': pl.Utf8,
    'depositType': pl.Utf8,
    'description': pl.Utf8,
    'eInvoiceYn': pl.Utf8,
    'expenseFolio': pl.Float64,
    'exportBucket': pl.Float64,
    'externalPaymentCode': pl.Utf8,
    'fiscalPaymentYn': pl.Utf8,
    'fiscalTrxCodeType': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'frequentFlyerYn': pl.Utf8,
    'generatesInclusiveYN': pl.Utf8,
    'group': pl.Utf8,
    'groupFolio': pl.Float64,
    'groupPointsRedemptionYN': pl.Utf8,
    'inHouseDepositYN': pl.Utf8,
    'inHousePayYN': pl.Utf8,
    'inHouseSalesYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'includeIn8300Yn': pl.Utf8,
    'includeInDepositCXLRuleYN': pl.Utf8,
    'indBilling': pl.Utf8,
    'indCash': pl.Utf8,
    'individualAr': pl.Utf8,
    'individualDepositYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalYn': pl.Utf8,
    'isManualPostAllowed': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'manualPostCoversYn': pl.Utf8,
    'maximumAmount': pl.Float64,
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
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'resultIncludedInSumArray': pl.Utf8,
    'revenueBucketId': pl.Float64,
    'revenueGroupId': pl.Float64,
    'revenueGroupYN': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'rotationRevenueYN': pl.Utf8,
    'roundingFactorYN': pl.Utf8,
    'serviceRecoveryTrxCode': pl.Utf8,
    'subgroup': pl.Utf8,
    'taxCode': pl.Float64,
    'tcBofInterface': pl.Utf8,
    'tcBofInterface2': pl.Utf8,
    'tcBofRefCode': pl.Utf8,
    'tcBofRefCode2': pl.Utf8,
    'tcResort2': pl.Utf8,
    'tcTransactionType': pl.Utf8,
    'tclCodeDfltCl1': pl.Utf8,
    'tclCodeDfltCl2': pl.Utf8,
    'transactionActionId': pl.Float64,
    'transactionCodeResort': pl.Utf8,
    'transactionType': pl.Utf8,
    'transcodearrangementid': pl.Utf8,
    'transcodeid': pl.Utf8,
    'transgroupid': pl.Utf8,
    'transsubgroupid': pl.Utf8,
    'trxCodeDisplay': pl.Utf8,
    'trxCodeType': pl.Utf8,
    'trxServiceType': pl.Utf8,
    'trxTaxTypeCode': pl.Utf8,
    'upcCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
transaction_code_comp_external_reference_details_schema = {
    'associatedTransactionCode': pl.Utf8,
    'associatedTransactionDescription': pl.Utf8,
    'centralAssociatedTransactionCode': pl.Utf8,
    'centralAssociatedTransactionDescription': pl.Utf8,
    'compTrxCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
}
```
```python
code_generates_details_schema = {
    'adjustmentType': pl.Utf8,
    'amount': pl.Float64,
    'amountFromScheduleYn': pl.Utf8,
    'cAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'calculationSequence': pl.Float64,
    'centralDescription': pl.Utf8,
    'centralGeneratedCode': pl.Utf8,
    'currency': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'generateRules': pl.Utf8,
    'generatedBy': pl.Utf8,
    'generatedCode': pl.Utf8,
    'generatedPrintedOnFolioYn': pl.Utf8,
    'id': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'organizationID': pl.Int64,
    'percentage': pl.Float64,
    'percentageBaseCode': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'resultIncludedInSumArray': pl.Utf8,
    'roundingMethod': pl.Utf8,
    'seqBy': pl.Float64,
    'stopDays': pl.Float64,
    'subTotal1YN': pl.Utf8,
    'subTotal2YN': pl.Utf8,
    'subTotal3YN': pl.Utf8,
    'tcDsi': pl.Float64,
    'tcGroup': pl.Utf8,
    'tcGroupGenerator': pl.Utf8,
    'tcOrganizationid': pl.Float64,
    'tcSubgroup': pl.Utf8,
    'tcSubgroupGenerator': pl.Utf8,
    'tclCodeGenerator': pl.Utf8,
    'tcrType': pl.Utf8,
    'transactionCodeResort': pl.Utf8,
    'transactionCodeTrxCode': pl.Utf8,
    'trxCodeGenerator': pl.Utf8,
    'udfFunction': pl.Utf8,
    'udfInverse': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'useTaxBracketYn': pl.Utf8,
}
```
```python
comp_type_details_schema = {
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
bar_schedule_details_schema = {
    'dSI': pl.Int64,
    'date': pl.Utf8,
    'dayOfWeek': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lengthOfStay': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
city_tax_range_details_schema = {
    'amountFrom': pl.Float64,
    'amountTo': pl.Float64,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'intervalAmount': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'packageFormulaRangeId': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'recordType': pl.Utf8,
    'taxAmount': pl.Float64,
    'taxPercentage': pl.Float64,
    'taxRangeType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
property_day_type_details_schema = {
    'adder': pl.Float64,
    'centralDayTypesCode': pl.Utf8,
    'centralSequence': pl.Float64,
    'dSI': pl.Int64,
    'dayTypesCode': pl.Utf8,
    'dayTypesDescription': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'dtRemarks': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'multiplier': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repDtRemarks': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
display_set_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
property_calendar_event_details_schema = {
    'activeYN': pl.Utf8,
    'blackoutYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'oRMSEventYN': pl.Utf8,
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
    'showInOperaYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
rate_hurdles_details_schema = {
    'actualRoomsSold': pl.Float64,
    'amountOfHurdleRate': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cHurdle': pl.Float64,
    'cORMSPriceRoomDelta': pl.Float64,
    'centralRoomClass': pl.Utf8,
    'centralRoomClassDescription': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralYieldCategory': pl.Utf8,
    'centralYieldCategoryDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'delta': pl.Float64,
    'hurdleDate': pl.Utf8,
    'hurdlerateid': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lengthOfStay': pl.Float64,
    'locationID': pl.Utf8,
    'maxRoomsSold': pl.Float64,
    'organizationID': pl.Int64,
    'overrideYN': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomCategoryLabel': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomClassDescription': pl.Utf8,
    'roomType': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomsToSellBeforeDeltaIsApplied': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'yieldCategory': pl.Utf8,
    'yieldCategoryDescription': pl.Utf8,
    'yieldcategoryid': pl.Utf8,
    'yieldmarkettype': pl.Utf8,
}
```
```python
product_details_schema = {
    'addtorateflag': pl.Utf8,
    'alternateCodes': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'beginSellDate': pl.Utf8,
    'bookingDuration': pl.Float64,
    'calculationRule': pl.Utf8,
    'cateringYn': pl.Utf8,
    'centralAlternateCodes': pl.Utf8,
    'centralPackage': pl.Utf8,
    'centralPackageGroupCode': pl.Utf8,
    'centralPackageGroupDescription': pl.Utf8,
    'centralPackageLoss': pl.Utf8,
    'centralPackageOverage': pl.Utf8,
    'centralPackageProfit': pl.Utf8,
    'centralTransactionCode': pl.Utf8,
    'currency': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'deliveryTimeReqrdYn': pl.Utf8,
    'description': pl.Utf8,
    'endSellDate': pl.Utf8,
    'externalLocked': pl.Utf8,
    'flexibleDurationYn': pl.Utf8,
    'forecastGroup': pl.Utf8,
    'forecastGroupCode': pl.Utf8,
    'forecastNextDayYN': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'formula': pl.Utf8,
    'genPlAtEodOfCoDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'inventoriedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'longInfo': pl.Utf8,
    'maxPersons': pl.Utf8,
    'minimumAdvBookDays': pl.Float64,
    'organizationID': pl.Int64,
    'outletCode': pl.Utf8,
    'overrideFixedRateYn': pl.Utf8,
    'package': pl.Utf8,
    'packageAllowanceYN': pl.Utf8,
    'packageDescription': pl.Utf8,
    'packageGroupCode': pl.Utf8,
    'packageGroupDescription': pl.Utf8,
    'packageLoss': pl.Utf8,
    'packageOverage': pl.Utf8,
    'packageOverageTaxInclusiveYN': pl.Utf8,
    'packageProfit': pl.Utf8,
    'pkgforecastgrpid': pl.Utf8,
    'postNextDayYN': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingType': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'printseparateflag': pl.Utf8,
    'productid': pl.Utf8,
    'property': pl.Utf8,
    'redemptionproductflag': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repTrxCodeDesc': pl.Utf8,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sellSeparateYN': pl.Utf8,
    'sellowsflag': pl.Utf8,
    'shortDescription': pl.Utf8,
    'standardDuration': pl.Float64,
    'standardPersons': pl.Utf8,
    'taxInclusiveYN': pl.Utf8,
    'ticketsYn': pl.Utf8,
    'transactionCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'validEndTime': pl.Utf8,
    'validStartTime': pl.Utf8,
}
```
```python
item_package_details_schema = {
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'item': pl.Utf8,
    'itemId': pl.Float64,
    'itemProdId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'product': pl.Utf8,
    'property': pl.Utf8,
    'qunatity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
rate_product_price_details_schema = {
    'allowanceAmount': pl.Float64,
    'bucket2AllowanceAmount': pl.Float64,
    'bucket2Price': pl.Float64,
    'bucket3AllowanceAmount': pl.Float64,
    'bucket3Price': pl.Float64,
    'cAllowanceAmount': pl.Float64,
    'cBucket2AllowanceAmount': pl.Float64,
    'cBucket2Price': pl.Float64,
    'cBucket3AllowanceAmount': pl.Float64,
    'cBucket3Price': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cPrice': pl.Float64,
    'dSI': pl.Int64,
    'day1': pl.Utf8,
    'day2': pl.Utf8,
    'day3': pl.Utf8,
    'day4': pl.Utf8,
    'day5': pl.Utf8,
    'day6': pl.Utf8,
    'day7': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'maximumGuests': pl.Float64,
    'maximumNights': pl.Float64,
    'minimumGuests': pl.Float64,
    'minimumNights': pl.Float64,
    'organizationID': pl.Int64,
    'pointsRequired': pl.Float64,
    'price': pl.Float64,
    'primaryKeyID': pl.Int64,
    'product': pl.Utf8,
    'property': pl.Utf8,
    'propertyRateProductDetailId': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'seasonCode': pl.Utf8,
    'startDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
package_forecast_group_details_schema = {
    'activeYN': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
promotion_details_schema = {
    'authorizerId': pl.Float64,
    'bookingEndDate': pl.Utf8,
    'bookingStartDate': pl.Utf8,
    'category': pl.Utf8,
    'centralDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'checkInTime': pl.Utf8,
    'checkOutTime': pl.Utf8,
    'code': pl.Utf8,
    'couponExChars': pl.Utf8,
    'couponGenFormat': pl.Utf8,
    'couponGenOption': pl.Utf8,
    'couponLength': pl.Float64,
    'couponPrefix': pl.Utf8,
    'couponSuffix': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'group': pl.Utf8,
    'idRequiredDescription': pl.Utf8,
    'idRequiredYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'information': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'instructions': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'limitedTimePromotionYn': pl.Utf8,
    'locationID': pl.Utf8,
    'lockedByCode': pl.Utf8,
    'lockedByType': pl.Utf8,
    'longDescription': pl.Utf8,
    'mktgprogramid': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'promoSequenceId': pl.Float64,
    'promotionid': pl.Utf8,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repUpdateDate': pl.Utf8,
    'reportingPromoSequenceId': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'setOrAccountFlag': pl.Utf8,
    'stayEndDate': pl.Utf8,
    'stayStartDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateOutsideBookingDatesYN': pl.Utf8,
    'updateUser': pl.Int64,
    'upgradeAllowedYN': pl.Utf8,
    'voucherBenefitCode': pl.Utf8,
}
```
```python
promotion_rate_details_schema = {
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'promoCode': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
}
```
```python
promotion_code_routing_instruction_details_schema = {
    'authorizerId': pl.Float64,
    'authorizerName': pl.Utf8,
    'autoPopulateRoutingYn': pl.Utf8,
    'beginDate': pl.Utf8,
    'centralTransactionCodes': pl.Utf8,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'compPreApprovalRequiredYn': pl.Utf8,
    'covers': pl.Float64,
    'creditLimit': pl.Float64,
    'dSI': pl.Int64,
    'dailyYn': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'folioView': pl.Float64,
    'friday': pl.Utf8,
    'membershipId': pl.Float64,
    'monday': pl.Utf8,
    'organizationID': pl.Int64,
    'percentage': pl.Float64,
    'promoCode': pl.Utf8,
    'promptForAuthorizerYn': pl.Utf8,
    'property': pl.Utf8,
    'routingCodes': pl.Utf8,
    'saturday': pl.Utf8,
    'sunday': pl.Utf8,
    'thursday': pl.Utf8,
    'transactionCodes': pl.Utf8,
    'tuesday': pl.Utf8,
    'wednesday': pl.Utf8,
}
```
```python
rate_categories_details_schema = {
    'businessDate': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralRateCategory': pl.Utf8,
    'centralRateClass': pl.Utf8,
    'centralRateClassDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'displayDefaultYn': pl.Utf8,
    'displaySet': pl.Utf8,
    'endDate': pl.Utf8,
    'exportBucketCode': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rateCategory': pl.Utf8,
    'rateCategoryDescription': pl.Utf8,
    'rateClass': pl.Utf8,
    'rateClassDescription': pl.Utf8,
    'rateTier': pl.Utf8,
    'ratecategoryid': pl.Utf8,
    'ratetierid': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
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
credit_card_types_details_schema = {
    'canDeleteYn': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
payment_method_details_schema = {
    'addressVerificationYn': pl.Utf8,
    'authAtCheckinYn': pl.Utf8,
    'authDuringStayYn': pl.Utf8,
    'authReversalYn': pl.Utf8,
    'authStlmtAtCheckOutYn': pl.Utf8,
    'autopayAtCheckinYn': pl.Utf8,
    'bonusCheckType': pl.Utf8,
    'calcPoints': pl.Utf8,
    'cardNumberLength': pl.Utf8,
    'cardPrefix': pl.Utf8,
    'cashSurchargeYn': pl.Utf8,
    'ccTrxFeePct': pl.Float64,
    'ccTrxFeeThreshold': pl.Float64,
    'centralPaymentMethod': pl.Utf8,
    'centralPaymentMethodDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chipPinYn': pl.Utf8,
    'code': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditLimit': pl.Float64,
    'currencyCode': pl.Utf8,
    'cvv2CheckYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'expirationRule': pl.Utf8,
    'extraPerc': pl.Float64,
    'formatMask': pl.Utf8,
    'formula': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'issueNumber': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'locationId': pl.Utf8,
    'merchantNumber': pl.Utf8,
    'numberDigits': pl.Float64,
    'numberPostYN': pl.Utf8,
    'organizationID': pl.Int64,
    'paymentMethod': pl.Utf8,
    'paymentMethodDescription': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'printAuthReceiptYn': pl.Utf8,
    'promptAtCheckinYn': pl.Utf8,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'reservationYN': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'startDate': pl.Float64,
    'tempFlag': pl.Float64,
    'transactionCode': pl.Utf8,
    'trxUsage1': pl.Utf8,
    'trxUsage2': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'validationRule': pl.Utf8,
}
```
```python
export_bucket_code_details_schema = {
    'arrTaxTypeCode': pl.Utf8,
    'arrangementId': pl.Float64,
    'bucketType': pl.Utf8,
    'bucketValue': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRoutingAmount': pl.Float64,
    'code': pl.Utf8,
    'compYn': pl.Utf8,
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
    'inactiveDate': pl.Utf8,
    'inheritAuthRatecodeYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'revenueBucketDescription': pl.Utf8,
    'revenueYn': pl.Utf8,
    'routingAmount': pl.Float64,
    'routingCovers': pl.Float64,
    'routingPercent': pl.Float64,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
transaction_code_arrange_detail_details_schema = {
    'addTransactionYN': pl.Utf8,
    'arrangementId': pl.Float64,
    'centralTransactionCode': pl.Utf8,
    'centralTransactionCodeDescription': pl.Utf8,
    'childArrangementId': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'transactionCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
export_bucket_type_details_schema = {
    'code': pl.Utf8,
    'compYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'fiscalYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'transactionCodeInMultiBucketsYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
routing_code_details_schema = {
    'applyPerDayYN': pl.Utf8,
    'arrTaxTypeCode': pl.Utf8,
    'arrangementId': pl.Float64,
    'bucketValue': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRoutingAmount': pl.Float64,
    'code': pl.Utf8,
    'compYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'eligibleYn': pl.Utf8,
    'exportBucketType': pl.Utf8,
    'friday': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inheritAuthRatecodeYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'monday': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'revenueYn': pl.Utf8,
    'routingAmount': pl.Float64,
    'routingCovers': pl.Float64,
    'routingPercentage': pl.Float64,
    'saturday': pl.Utf8,
    'sunday': pl.Utf8,
    'thursday': pl.Utf8,
    'tuesday': pl.Utf8,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'wednesday': pl.Utf8,
}
```
```python
transaction_diversion_rule_details_schema = {
    'basedOn': pl.Utf8,
    'calculation': pl.Utf8,
    'code': pl.Utf8,
    'complimentary': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'diversionId': pl.Float64,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'level': pl.Utf8,
    'membershipLevel': pl.Utf8,
    'membershipType': pl.Utf8,
    'minimumRequired': pl.Float64,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'room': pl.Utf8,
    'ruleType': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vIP': pl.Utf8,
}
```
```python
transaction_diversion_rule_details_details_schema = {
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'diversionId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'transactionCodes': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
transaction_group_details_schema = {
    'centralDescription': pl.Utf8,
    'centralDisplaySequence': pl.Float64,
    'centralTransactionCodeGroup': pl.Utf8,
    'class1MandatoryYn': pl.Utf8,
    'class2MandatoryYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displaySequence': pl.Float64,
    'inactiveflag': pl.Utf8,
    'indRevenueGroup': pl.Utf8,
    'indicatorRevenueGroup': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
}
```
```python
group_generates_details_schema = {
    'adjustmentType': pl.Utf8,
    'amount': pl.Float64,
    'amountFromScheduleYn': pl.Utf8,
    'cAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'calculationSequence': pl.Float64,
    'centralDescription': pl.Utf8,
    'centralGeneratedCode': pl.Utf8,
    'currency': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'generateRules': pl.Utf8,
    'generatedBy': pl.Utf8,
    'generatedCode': pl.Utf8,
    'generatedPrintedOnFolioYn': pl.Utf8,
    'id': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'organizationID': pl.Int64,
    'percentage': pl.Float64,
    'percentageBaseCode': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'resultIncludedInSumArray': pl.Utf8,
    'roundingMethod': pl.Utf8,
    'stopDays': pl.Float64,
    'subTotal1YN': pl.Utf8,
    'subTotal2YN': pl.Utf8,
    'subTotal3YN': pl.Utf8,
    'tcGroup': pl.Utf8,
    'tcGroupGenerator': pl.Utf8,
    'tcSubgroup': pl.Utf8,
    'tcSubgroupGenerator': pl.Utf8,
    'tclCodeGenerator': pl.Utf8,
    'tcrType': pl.Utf8,
    'trxCodeGenerator': pl.Utf8,
    'udfFunction': pl.Utf8,
    'udfInverse': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'useTaxBracketYn': pl.Utf8,
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
    'dSI': pl.Int64,
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
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
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
    'updateUser': pl.Int64,
}
```
```python
subgroup_generates_details_schema = {
    'adjustmentType': pl.Utf8,
    'amount': pl.Float64,
    'amountFromScheduleYn': pl.Utf8,
    'cAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'calculationSequence': pl.Float64,
    'centralDescription': pl.Utf8,
    'centralGeneratedCode': pl.Utf8,
    'currency': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'generateRules': pl.Utf8,
    'generatedBy': pl.Utf8,
    'generatedCode': pl.Utf8,
    'generatedPrintedOnFolioYn': pl.Utf8,
    'id': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'nameTaxType': pl.Utf8,
    'organizationID': pl.Int64,
    'percentage': pl.Float64,
    'percentageBaseCode': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'resultIncludedInSumArray': pl.Utf8,
    'roundingMethod': pl.Utf8,
    'seqBy': pl.Float64,
    'stopDays': pl.Float64,
    'subTotal1YN': pl.Utf8,
    'subTotal2YN': pl.Utf8,
    'subTotal3YN': pl.Utf8,
    'tcDsi': pl.Float64,
    'tcGroup': pl.Utf8,
    'tcGroupGenerator': pl.Utf8,
    'tcOrganizationid': pl.Float64,
    'tcSubgroup': pl.Utf8,
    'tcSubgroupGenerator': pl.Utf8,
    'tcTcSubgroup': pl.Utf8,
    'tclCodeGenerator': pl.Utf8,
    'tcrType': pl.Utf8,
    'transactionCodeResort': pl.Utf8,
    'trxCodeGenerator': pl.Utf8,
    'udfFunction': pl.Utf8,
    'udfInverse': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'useTaxBracketYn': pl.Utf8,
}
```
```python
property_alert_details_schema = {
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'propery': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
global_alerts_details_schema = {
    'alertCode': pl.Utf8,
    'alertText': pl.Utf8,
    'area': pl.Utf8,
    'brandStayCnt': pl.Float64,
    'comments': pl.Utf8,
    'conditions': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'department': pl.Utf8,
    'description': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailYn': pl.Utf8,
    'externalAlertId': pl.Utf8,
    'hasTagsYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'lastStayDate': pl.Utf8,
    'lastStayLocation': pl.Utf8,
    'locationID': pl.Utf8,
    'membershipAlertYn': pl.Utf8,
    'membershipCardNo': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'pref1': pl.Utf8,
    'pref2': pl.Utf8,
    'pref3': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'printerYN': pl.Utf8,
    'printerName': pl.Utf8,
    'property': pl.Utf8,
    'propertyStayCnt': pl.Float64,
    'propertyStayDate': pl.Utf8,
    'queryId': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reportName': pl.Utf8,
    'reservationAlertId': pl.Float64,
    'reservationNameId': pl.Float64,
    'screenYN': pl.Utf8,
    'skipGuestOverviewYn': pl.Utf8,
    'smsNumber': pl.Utf8,
    'smsYn': pl.Utf8,
    'stopCheckInCheckOut': pl.Utf8,
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
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'validationOverridePermission': pl.Utf8,
    'valueRating': pl.Utf8,
    'vipStatus': pl.Utf8,
    'welcomeOfferCode': pl.Utf8,
    'welcomeOfferYn': pl.Utf8,
}
```
```python
block_cancellation_code_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'tempFlag': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
sales_event_destination_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'cancellationDestination': pl.Utf8,
    'centralCancellationDestination': pl.Utf8,
    'centralCancellationDestinationDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'scdestinationid': pl.Utf8,
    'sequence': pl.Float64,
    'tempFlag': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
lost_booking_codes_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'tempFlag': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
refused_booking_codes_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'tempFlag': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
booking_method_details_schema = {
    'bookingmethodid': pl.Utf8,
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralReservationMethod': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'reservationMethod': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
property_cutoff_schedule_details_schema = {
    'code': pl.Utf8,
    'cutoffRooms2': pl.Float64,
    'cutoffRooms3': pl.Float64,
    'cutoffRooms4': pl.Float64,
    'dSI': pl.Int64,
    'daysPriorToArrival': pl.Float64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rooms': pl.Float64,
    'sell': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'washByPercent': pl.Float64,
}
```
```python
booking_status_details_schema = {
    'allowPickupYN': pl.Utf8,
    'bookingstatusid': pl.Utf8,
    'cateringStatusType': pl.Utf8,
    'cateringdeductinvflag': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralEventStatus': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deductinventoryflag': pl.Utf8,
    'defaultReservationType': pl.Utf8,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'diaryYN': pl.Utf8,
    'displayColor': pl.Utf8,
    'fitStatusYn': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'leadStatusYn': pl.Utf8,
    'logCateringYn': pl.Utf8,
    'oRMSYN': pl.Utf8,
    'oldBlockStatus': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reasonType': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'returnInventoryYN': pl.Utf8,
    'roomStatusType': pl.Utf8,
    'sequence': pl.Float64,
    'startingYN': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
cancel_rule_details_schema = {
    'allotmentHeaderId': pl.Float64,
    'amount': pl.Float64,
    'applyRuleTo': pl.Utf8,
    'beforeTime': pl.Utf8,
    'beginDate': pl.Utf8,
    'cCnclPenltyAmount': pl.Float64,
    'cDepAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'code': pl.Utf8,
    'creditRating': pl.Utf8,
    'd1': pl.Utf8,
    'd2': pl.Utf8,
    'd3': pl.Utf8,
    'd4': pl.Utf8,
    'd5': pl.Utf8,
    'd6': pl.Utf8,
    'd7': pl.Utf8,
    'dSI': pl.Int64,
    'daysBeforeArrival': pl.Float64,
    'daysofweek': pl.Utf8,
    'deletedflag': pl.Utf8,
    'depositAmount': pl.Float64,
    'depositAmountType': pl.Utf8,
    'depositDaysAfterBooking': pl.Float64,
    'depositDaysPriorToArrival': pl.Float64,
    'depositcancelruleid': pl.Float64,
    'depositcancelrulepmsref': pl.Float64,
    'depositorCancellationRule': pl.Utf8,
    'description': pl.Utf8,
    'endDate': pl.Utf8,
    'guaranteeClass': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'overrideYn': pl.Utf8,
    'parentRateDcSeq': pl.Float64,
    'paymentRequired': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateCodeDescription': pl.Utf8,
    'rateSetId': pl.Float64,
    'repSeasonCode': pl.Utf8,
    'reservationType': pl.Utf8,
    'seasonCode': pl.Utf8,
    'sequence': pl.Float64,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
cancel_rule_schedule_details_schema = {
    'allotmentHeaderId': pl.Float64,
    'applyRuleTo': pl.Utf8,
    'beginDate': pl.Utf8,
    'blockCode': pl.Utf8,
    'cCnclPenltyAmount': pl.Float64,
    'cDepAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'canBeforeTime': pl.Utf8,
    'canDaysPriorToArrival': pl.Float64,
    'canPenaltyAmount': pl.Float64,
    'canPenaltyAmountType': pl.Utf8,
    'creditRating': pl.Utf8,
    'd1': pl.Utf8,
    'd2': pl.Utf8,
    'd3': pl.Utf8,
    'd4': pl.Utf8,
    'd5': pl.Utf8,
    'd6': pl.Utf8,
    'd7': pl.Utf8,
    'dSI': pl.Int64,
    'daysofweek': pl.Utf8,
    'deletedflag': pl.Utf8,
    'depositAmount': pl.Float64,
    'depositAmountType': pl.Utf8,
    'depositDaysAfterBooking': pl.Float64,
    'depositDaysPriorToArrival': pl.Float64,
    'depositcancelruleid': pl.Float64,
    'depositcancelrulepmsref': pl.Float64,
    'depositorCancellationRule': pl.Utf8,
    'endDate': pl.Utf8,
    'guaranteeClass': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'overrideYN': pl.Utf8,
    'parentRateDcSeq': pl.Float64,
    'paymentRequired': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateCodeDescription': pl.Utf8,
    'rateSetId': pl.Float64,
    'repSeasonCode': pl.Utf8,
    'reservationType': pl.Utf8,
    'rule': pl.Utf8,
    'ruleDescription': pl.Utf8,
    'seasonCode': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
deposit_rule_details_schema = {
    'afterBooking': pl.Float64,
    'allotmentHeaderId': pl.Float64,
    'amount': pl.Float64,
    'applyRuleTo': pl.Utf8,
    'beforeArrival': pl.Float64,
    'beginDate': pl.Utf8,
    'cCnclPenltyAmount': pl.Float64,
    'cDepAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'canBeforeTime': pl.Utf8,
    'canDaysPriorToArrival': pl.Float64,
    'canPenaltyAmount': pl.Float64,
    'canPenaltyAmountType': pl.Utf8,
    'creditRating': pl.Utf8,
    'd1': pl.Utf8,
    'd2': pl.Utf8,
    'd3': pl.Utf8,
    'd4': pl.Utf8,
    'd5': pl.Utf8,
    'd6': pl.Utf8,
    'd7': pl.Utf8,
    'dSI': pl.Int64,
    'daysofweek': pl.Utf8,
    'deletedflag': pl.Utf8,
    'depositRule': pl.Utf8,
    'depositcancelruleid': pl.Float64,
    'depositcancelrulepmsref': pl.Float64,
    'depositorCancellationRule': pl.Utf8,
    'description': pl.Utf8,
    'endDate': pl.Utf8,
    'guaranteeClass': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'overrideYn': pl.Utf8,
    'parentRateDcSeq': pl.Float64,
    'paymentRequired': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateCodeDescription': pl.Utf8,
    'rateSetId': pl.Float64,
    'repSeasonCode': pl.Utf8,
    'reservationType': pl.Utf8,
    'seasonCode': pl.Utf8,
    'sequence': pl.Float64,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
deposit_rule_schedule_details_schema = {
    'allotmentHeaderId': pl.Float64,
    'applyRuleTo': pl.Utf8,
    'beginDate': pl.Utf8,
    'blockCode': pl.Utf8,
    'cCnclPenltyAmount': pl.Float64,
    'cDepAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'canBeforeTime': pl.Utf8,
    'canDaysPriorToArrival': pl.Float64,
    'canPenaltyAmount': pl.Float64,
    'canPenaltyAmountType': pl.Utf8,
    'creditRating': pl.Utf8,
    'd1': pl.Utf8,
    'd2': pl.Utf8,
    'd3': pl.Utf8,
    'd4': pl.Utf8,
    'd5': pl.Utf8,
    'd6': pl.Utf8,
    'd7': pl.Utf8,
    'dSI': pl.Int64,
    'daysofweek': pl.Utf8,
    'deletedflag': pl.Utf8,
    'depositAmount': pl.Float64,
    'depositAmountType': pl.Utf8,
    'depositDaysAfterBooking': pl.Float64,
    'depositDaysPriorToArrival': pl.Float64,
    'depositcancelruleid': pl.Float64,
    'depositcancelrulepmsref': pl.Float64,
    'depositorCancellationRule': pl.Utf8,
    'endDate': pl.Utf8,
    'guaranteeClass': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'overrideYN': pl.Utf8,
    'parentRateDcSeq': pl.Float64,
    'paymentRequired': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateCodeDescription': pl.Utf8,
    'rateSetId': pl.Float64,
    'repSeasonCode': pl.Utf8,
    'reservationType': pl.Utf8,
    'rule': pl.Utf8,
    'ruleDescription': pl.Utf8,
    'seasonCode': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
guarantee_details_schema = {
    'addressYN': pl.Utf8,
    'arrivalYN': pl.Utf8,
    'autoCancelReservationYN': pl.Utf8,
    'bookingStatus': pl.Utf8,
    'bookingStatusOrder': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'cashBasisYn': pl.Utf8,
    'ccPendingDays': pl.Float64,
    'ccVerifyCodeRequiredYn': pl.Utf8,
    'centralReservationType': pl.Utf8,
    'centralReservationTypeDescription': pl.Utf8,
    'closingProbability': pl.Float64,
    'creditCardYN': pl.Utf8,
    'croAllowedYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'depositYN': pl.Utf8,
    'gDSShortDescription': pl.Utf8,
    'guaranteecodeid': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'longDescription': pl.Utf8,
    'organizationID': pl.Int64,
    'phoneYN': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reserveInventoryYn': pl.Utf8,
    'restrictedYn': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'shortDescription': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
reservation_type_schedule_details_schema = {
    'allotmentHeaderId': pl.Float64,
    'applyRuleTo': pl.Utf8,
    'beginDate': pl.Utf8,
    'cCnclPenltyAmount': pl.Float64,
    'cDepAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'canBeforeTime': pl.Utf8,
    'canDaysPriorToArrival': pl.Float64,
    'canPenaltyAmount': pl.Float64,
    'canPenaltyAmountType': pl.Utf8,
    'creditRating': pl.Utf8,
    'd1': pl.Utf8,
    'd2': pl.Utf8,
    'd3': pl.Utf8,
    'd4': pl.Utf8,
    'd5': pl.Utf8,
    'd6': pl.Utf8,
    'd7': pl.Utf8,
    'dSI': pl.Int64,
    'daysofweek': pl.Utf8,
    'deletedflag': pl.Utf8,
    'depositAmount': pl.Float64,
    'depositAmountType': pl.Utf8,
    'depositDaysAfterBooking': pl.Float64,
    'depositDaysPriorToArrival': pl.Float64,
    'depositcancelruleid': pl.Float64,
    'depositcancelrulepmsref': pl.Float64,
    'depositorCancellationRule': pl.Utf8,
    'description': pl.Utf8,
    'endDate': pl.Utf8,
    'guaranteeClass': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'overrideYN': pl.Utf8,
    'parentRateDcSeq': pl.Float64,
    'paymentRequired': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateCodeDescription': pl.Utf8,
    'rateSetId': pl.Float64,
    'repSeasonCode': pl.Utf8,
    'reservationType': pl.Utf8,
    'ruleCode': pl.Utf8,
    'ruledescription': pl.Utf8,
    'seasonCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
market_details_schema = {
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayColor': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketDisplaySequence': pl.Float64,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'marketGroupDisplaySequence': pl.Float64,
    'marketgroupid': pl.Utf8,
    'marketid': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'printGroup': pl.Utf8,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repMarketSellSequence': pl.Float64,
    'repParentSellSequence': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'scOrderby': pl.Float64,
    'trxCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
market_group_details_schema = {
    'autoupgradeYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'marketGroup': pl.Utf8,
    'marketgroupid': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repMarketGroup': pl.Utf8,
    'repSellSequence': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'scOrderBy': pl.Float64,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
property_marketing_city_details_schema = {
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'direction': pl.Utf8,
    'displaySeq': pl.Float64,
    'distance': pl.Float64,
    'distanceType': pl.Utf8,
    'drivingTime': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'marketingCity': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'regionCode': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
marketing_regions_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'tempFlag': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
channel_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralOriginCode': pl.Utf8,
    'centralOriginDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'channelid': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'originCode': pl.Utf8,
    'originDescription': pl.Utf8,
    'originDisplaySequence': pl.Float64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
sell_messages_details_schema = {
    'allotmentHeaderId': pl.Float64,
    'beginDate': pl.Utf8,
    'blockCode': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'endDate': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomType': pl.Utf8,
    'sellId': pl.Float64,
    'sellMessage': pl.Utf8,
    'sequence': pl.Float64,
    'stickyFlag': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
source_table_details_schema = {
    'centralSequence': pl.Float64,
    'centralSourceCode': pl.Utf8,
    'centralSourceDescription': pl.Utf8,
    'centralSourceGroupCode': pl.Utf8,
    'centralSourceGroupDescription': pl.Utf8,
    'dSI': pl.Int64,
    'deletedYn': pl.Utf8,
    'deletedflag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlagYN': pl.Utf8,
    'inactiveYn': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internetSalesYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lastuseddatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Int64,
    'parentsourceid': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'sourceCode': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceDisplaySequence': pl.Float64,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'sourceGroupDisplaySequence': pl.Float64,
    'sourceid': pl.Utf8,
    'tempYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
source_group_details_schema = {
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'centralSourceGroup': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internetSalesYn': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'parentSourceCode': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'scOrderby': pl.Float64,
    'sequence': pl.Float64,
    'sourceGroup': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
reservation_auto_attach_rules_details_schema = {
    'advancedYn': pl.Utf8,
    'basedOn': pl.Utf8,
    'code': pl.Utf8,
    'convertedToAdvancedYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keywordType': pl.Utf8,
    'level': pl.Utf8,
    'minAdults': pl.Float64,
    'minChildren': pl.Float64,
    'organizationID': pl.Int64,
    'preference': pl.Utf8,
    'preferenceType': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'queryId': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'roomCategory': pl.Utf8,
    'ruleType': pl.Utf8,
    'type': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'vipStatus': pl.Utf8,
}
```
```python
reservation_auto_attach_details_details_schema = {
    'associatedCodes': pl.Utf8,
    'attachId': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'discountReasonCode': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'itemId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'preference': pl.Utf8,
    'preferenceType': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'product': pl.Utf8,
    'promoCode': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ruleCode': pl.Utf8,
    'traceDeptId': pl.Utf8,
    'traceText': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
cancellation_codes_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'tempFlag': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
entry_point_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'tempFlag': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
discount_reason_details_schema = {
    'advanceYN': pl.Utf8,
    'attributeCode': pl.Utf8,
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
ecoupon_details_schema = {
    'dSI': pl.Int64,
    'defaultQuantity': pl.Float64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'postingRoom': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateCode': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'welcomeOfferYn': pl.Utf8,
    'eCouponCode': pl.Utf8,
}
```
```python
property_locator_details_schema = {
    'code': pl.Float64,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveYN': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
property_message_details_schema = {
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'message': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
guest_status_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'guestStatus': pl.Utf8,
    'gueststatusid': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalEntityname': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'statustype': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
guest_type_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralGuestType': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'guestType': pl.Utf8,
    'guesttypeid': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
immigration_status_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
pre_reg_rules_details_schema = {
    'allowRestrict': pl.Utf8,
    'beginDate': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ruleDetails': pl.Utf8,
    'ruleId': pl.Float64,
    'ruleType': pl.Utf8,
    'ruleTypeDesc': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
item_class_details_schema = {
    'bookableViaWebsiteYN': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'discountableYn': pl.Utf8,
    'eventTypes': pl.Utf8,
    'iconName': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'itemclassId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'reportingItemclassId': pl.Utf8,
    'reservationYN': pl.Utf8,
    'responsibleDepartment': pl.Utf8,
    'sequence': pl.Float64,
    'usedInApp': pl.Utf8,
}
```
```python
item_inventory_details_schema = {
    'activityExtSystem': pl.Utf8,
    'activityLinkYn': pl.Utf8,
    'activityLocationCode': pl.Utf8,
    'activityStatusCode': pl.Utf8,
    'activityType': pl.Utf8,
    'allowedOutsideStayYn': pl.Utf8,
    'availableFrom': pl.Utf8,
    'availableTo': pl.Utf8,
    'braceletRuleCode': pl.Utf8,
    'cCost': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'cost': pl.Float64,
    'criticalYn': pl.Utf8,
    'dSI': pl.Int64,
    'dailyInventoryYn': pl.Utf8,
    'defaultDuration': pl.Float64,
    'defaultQty': pl.Float64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'discountableYN': pl.Utf8,
    'displayColor': pl.Utf8,
    'externalYN': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'itemClass': pl.Utf8,
    'itemCode': pl.Utf8,
    'itemId': pl.Float64,
    'itemPoolId': pl.Float64,
    'itemclassId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'mandatoryYn': pl.Utf8,
    'objectType': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'promptFixedChargesYn': pl.Utf8,
    'property': pl.Utf8,
    'quantityInStock': pl.Float64,
    'quickInsert': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'reportingItemId': pl.Utf8,
    'revType': pl.Utf8,
    'revenueType': pl.Utf8,
    'sellSeparate': pl.Utf8,
    'sequence': pl.Float64,
    'setdownTime': pl.Float64,
    'setupTime': pl.Float64,
    'showbeoYn': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'webBookingYn': pl.Utf8,
    'welcomeOfferYn': pl.Utf8,
}
```
```python
item_pool_details_schema = {
    'code': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'insertTs': pl.Utf8,
    'insertUser': pl.Int64,
    'itemClass': pl.Utf8,
    'itemPoolId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'updateTs': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
birth_country_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
property_country_details_schema = {
    'addressdoctorMode': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'countryCode': pl.Utf8,
    'countryMainGroup': pl.Utf8,
    'countryName': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayCountryFlagYN': pl.Utf8,
    'guestAddressFormat': pl.Utf8,
    'iSOCode': pl.Utf8,
    'iSOName': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'name': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'propertyAddressFormat': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'region': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'reportSequence': pl.Float64,
    'sequence': pl.Float64,
    'statisticsCode': pl.Utf8,
    'status': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
country_group_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'comments': pl.Utf8,
    'countryGroup': pl.Utf8,
    'countryGroupCode': pl.Utf8,
    'countrygroupid': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
distance_type_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
district_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
fiscal_guest_type_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
fiscal_region_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_id_country_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
nationality_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralNationalityCode': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'nationalityid': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
qualifying_rates_details_schema = {
    'aSBRateCycle': pl.Utf8,
    'addition': pl.Utf8,
    'advBaseRateCode': pl.Utf8,
    'advBaseRounding': pl.Utf8,
    'advanceBaseCompareYN': pl.Utf8,
    'advanceBooking': pl.Float64,
    'advanceDailyBaseYN': pl.Utf8,
    'advanceDailyRateYN': pl.Utf8,
    'alternateRateCode': pl.Utf8,
    'availabilityUpdateYn': pl.Utf8,
    'backToBackYn': pl.Utf8,
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
    'beginBookingDate': pl.Utf8,
    'breakfastInclYn': pl.Utf8,
    'breakfastPrice': pl.Float64,
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
    'changeState': pl.Utf8,
    'closedToArrival': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionPct': pl.Float64,
    'commissionYn': pl.Utf8,
    'commissionablePerc': pl.Float64,
    'commissionableYn': pl.Utf8,
    'complimentaryYn': pl.Utf8,
    'currCodeDecimalPos': pl.Float64,
    'currencyCode': pl.Utf8,
    'dSI': pl.Int64,
    'dailyRatesYn': pl.Utf8,
    'dayuseYn': pl.Utf8,
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
    'description': pl.Utf8,
    'discountRateAmount': pl.Float64,
    'discountRatePercentageYn': pl.Utf8,
    'discountYn': pl.Utf8,
    'displayRegionalYn': pl.Utf8,
    'displaySet': pl.Utf8,
    'distributeYn': pl.Utf8,
    'doubleRoomSupplementYN': pl.Utf8,
    'endBookingDate': pl.Utf8,
    'exchangePostingType': pl.Utf8,
    'externalLocked': pl.Utf8,
    'extraPersonChargeBegins': pl.Float64,
    'fitDiscountLevel': pl.Float64,
    'fitDiscountPerc': pl.Float64,
    'flatOrPercentage': pl.Utf8,
    'folioText': pl.Utf8,
    'gDSAllowedYn': pl.Utf8,
    'groupCode': pl.Utf8,
    'highlightRateAmountYn': pl.Utf8,
    'houseUseYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'label': pl.Utf8,
    'longInfo': pl.Utf8,
    'losUnit': pl.Float64,
    'loyaltyProgramYn': pl.Utf8,
    'mandateResvProfiles': pl.Utf8,
    'marketCode': pl.Utf8,
    'marshaRateProgram': pl.Utf8,
    'maxAdvanceBooking': pl.Float64,
    'maxLos': pl.Float64,
    'maxOccupancy': pl.Float64,
    'mfnUploadYn': pl.Utf8,
    'minOccupancy': pl.Float64,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'multiplication': pl.Utf8,
    'negotiated': pl.Utf8,
    'occupancyBasedYn': pl.Utf8,
    'occupancyLevel': pl.Float64,
    'operatorType': pl.Utf8,
    'orderBy': pl.Float64,
    'organizationID': pl.Int64,
    'orsSellSequence': pl.Float64,
    'overridePackageYn': pl.Utf8,
    'ownerRateYn': pl.Utf8,
    'packageTransactionTaxInclYN': pl.Utf8,
    'packageTransactionWkTaxInclYN': pl.Utf8,
    'packageTrxCode': pl.Utf8,
    'packageTrxCodeWk': pl.Utf8,
    'packageYn': pl.Utf8,
    'pendingApprovalYn': pl.Utf8,
    'postingRhythm': pl.Utf8,
    'postingRhythmNights': pl.Float64,
    'primaryKeyID': pl.Int64,
    'printRateYn': pl.Utf8,
    'privilegedRestrictionYn': pl.Utf8,
    'privilegedYn': pl.Utf8,
    'profitTrxCode': pl.Utf8,
    'property': pl.Utf8,
    'qualifying': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rankAdjustmentFactor': pl.Float64,
    'rankValue': pl.Float64,
    'rateBucket': pl.Utf8,
    'rateCalendarYn': pl.Utf8,
    'rateCategories': pl.Utf8,
    'rateClass': pl.Utf8,
    'rateCodeLocked': pl.Utf8,
    'rateCodes': pl.Utf8,
    'rateFloor': pl.Float64,
    'rateFloorOverrideYn': pl.Utf8,
    'rateIncludesTaxYn': pl.Utf8,
    'rateLevel': pl.Float64,
    'rateinfoUrl': pl.Utf8,
    'ratesToGDSYn': pl.Utf8,
    'redemptionRateYn': pl.Utf8,
    'repeatPostingRhythmYn': pl.Utf8,
    'rodBaseAmount': pl.Float64,
    'rodBaseFltPct': pl.Utf8,
    'rodBaseRounding': pl.Utf8,
    'rodBasedYn': pl.Utf8,
    'rodYn': pl.Utf8,
    'roomAssignmentValue': pl.Float64,
    'sdowBeginBookingDate': pl.Utf8,
    'sdowEndBookingDate': pl.Utf8,
    'sellSequence': pl.Float64,
    'serviceInclYn': pl.Utf8,
    'servicePerc': pl.Float64,
    'shortInfo': pl.Utf8,
    'showRateAmountYn': pl.Utf8,
    'sourceCode': pl.Utf8,
    'taxIncludedPerc': pl.Float64,
    'taxIncludedYn': pl.Utf8,
    'tieredYn': pl.Utf8,
    'transactionTaxInclYN': pl.Utf8,
    'transactionWkTaxInclYN': pl.Utf8,
    'trxCode': pl.Utf8,
    'trxCodeWk': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
    'upsellYn': pl.Utf8,
    'voucherBenefitRateYn': pl.Utf8,
    'weekendDays': pl.Utf8,
    'wkDeptCode': pl.Utf8,
    'yieldAs': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Utf8,
}
```
```python
membership_status_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
priority_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'priorityId': pl.Utf8,
    'priorityType': pl.Utf8,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'tempFlag': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
entity_account_type_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
address_type_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
alternate_language_title_details_schema = {
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'language': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'salutation': pl.Utf8,
    'sequence': pl.Float64,
    'titleNumber': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
rooms_potential_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomsPotentialType': pl.Utf8,
    'sequence': pl.Float64,
    'tempFlag': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
business_segment_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
company_type_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
competition_details_schema = {
    'attributeCode': pl.Utf8,
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCompetition': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'competition': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'tempFlag': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
gender_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_inactive_reason_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
industry_code_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
influence_code_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
keyword_type_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
mailing_action_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'lastUsedDatetime': pl.Utf8,
    'locationID': pl.Utf8,
    'mailingActionType': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'tempFlag': pl.Utf8,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
preference_details_schema = {
    'amenityYn': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cRoomAssignmentValue': pl.Float64,
    'cRSPreferenceYn': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Float64,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'corporateYn': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'description1': pl.Utf8,
    'housekeepingYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationId': pl.Utf8,
    'organizationID': pl.Int64,
    'owsAllowedYN': pl.Utf8,
    'preferenceAttribute': pl.Utf8,
    'preferenceCode': pl.Utf8,
    'preferenceDescription': pl.Utf8,
    'preferenceGroup': pl.Utf8,
    'preferenceId': pl.Float64,
    'preferenceSubType': pl.Utf8,
    'preference1': pl.Utf8,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'reportingPreferenceSequenceId': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomAssignmentValue': pl.Float64,
    'sendDeleteRequestYn': pl.Utf8,
    'sequence': pl.Float64,
    'source': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
profile_restriction_reason_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repAttributeCode': pl.Utf8,
    'repDescription': pl.Utf8,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repOrderBy': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
sales_event_scope_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
sales_event_scope_city_details_schema = {
    'businessTitle': pl.Utf8,
    'canDeleteYn': pl.Utf8,
    'centralCode': pl.Utf8,
    'centralDescription': pl.Utf8,
    'centralSequence': pl.Float64,
    'chainCode': pl.Utf8,
    'code': pl.Utf8,
    'comments': pl.Utf8,
    'dSI': pl.Int64,
    'deletedflag': pl.Utf8,
    'description': pl.Utf8,
    'displayColor': pl.Utf8,
    'entityName': pl.Utf8,
    'externalAttributeCodes': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'languageCode': pl.Utf8,
    'locationID': pl.Utf8,
    'masterSubKeywordYn': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'ranking': pl.Float64,
    'repItem': pl.Utf8,
    'repItemName': pl.Utf8,
    'repItemOrderby': pl.Float64,
    'repUpdateDate': pl.Utf8,
    'sequence': pl.Float64,
    'titleSuffix': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```
```python
membership_claim_adjustment_limit_details_schema = {
    'adjustmentLimitCode': pl.Utf8,
    'awardLowerLimit': pl.Float64,
    'awardUpperLimit': pl.Float64,
    'billingGroup': pl.Utf8,
    'chainCode': pl.Utf8,
    'dSI': pl.Int64,
    'deletedFlag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Int64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Int64,
    'primaryKeyID': pl.Int64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'tierNightsLowerLimit': pl.Float64,
    'tierNightsUpperLimit': pl.Float64,
    'tierRevenueLowerLimit': pl.Float64,
    'tierRevenueUpperLimit': pl.Float64,
    'tierStaysLowerLimit': pl.Float64,
    'tierStaysUpperLimit': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Int64,
}
```