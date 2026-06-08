# BookingReservationExtended
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `bookingReservationExtended`
> Provide booking reservation information with extended or additional details such as blocks routing etc.
  
**Return:** [`[BookingReservationExtendedType]`](#bookingreservationextendedtype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`BookingReservationExtendedQueryArgumentsType!`](#bookingreservationextendedqueryargumentstype) |  |

## Object Types

### BookingReservationExtendedType

| Field | Type | Description |
| --- | --- | --- |
| reservationUnifiedDetails | [`BookingReservationExtendedReservationUnifiedDetailsType`](#bookingreservationextendedreservationunifieddetailstype) | Reservation Unified |
| profileAllInformationDetails | [`BookingReservationExtendedProfileAllInformationDetailsType`](#bookingreservationextendedprofileallinformationdetailstype) | Profile All Details |
| profileAccountsSourceDetails | [`BookingReservationExtendedProfileAccountsSourceDetailsType`](#bookingreservationextendedprofileaccountssourcedetailstype) | Profile Accounts Source Details |
| profileAccountsTravelAgentDetails | [`BookingReservationExtendedProfileAccountsTravelAgentDetailsType`](#bookingreservationextendedprofileaccountstravelagentdetailstype) | Profile Accounts Travel Agent Details |
| externalReferencesDetails | [`BookingReservationExtendedExternalReferencesDetailsType`](#bookingreservationextendedexternalreferencesdetailstype) | External References Details |
| reservationMembershipDetails | [`BookingReservationExtendedReservationMembershipDetailsType`](#bookingreservationextendedreservationmembershipdetailstype) | Reservation Membership |
| reservationPaymentMethodsDetails | [`BookingReservationExtendedReservationPaymentMethodsDetailsType`](#bookingreservationextendedreservationpaymentmethodsdetailstype) | Reservation Payment Methods |
| profileAccountsDetails | [`BookingReservationExtendedProfileAccountsDetailsType`](#bookingreservationextendedprofileaccountsdetailstype) | Profile Accounts Details |
| reservationDepositScheduleDetails | [`BookingReservationExtendedReservationDepositScheduleDetailsType`](#bookingreservationextendedreservationdepositscheduledetailstype) | Reservation Deposit Schedule |
| rateCodeDetailsDetails | [`BookingReservationExtendedRateCodeDetailsDetailsType`](#bookingreservationextendedratecodedetailsdetailstype) | Rate Code Details Details |
| routingInstructionDetails | [`BookingReservationExtendedRoutingInstructionDetailsType`](#bookingreservationextendedroutinginstructiondetailstype) | Routing Instruction Details |
| folioTaxDetails | [`BookingReservationExtendedFolioTaxDetailsType`](#bookingreservationextendedfoliotaxdetailstype) | Folio Tax Details |
| financialUnifiedDetails | [`BookingReservationExtendedFinancialUnifiedDetailsType`](#bookingreservationextendedfinancialunifieddetailstype) | Financial Unified |
| propertyPropertyDetails | [`BookingReservationExtendedPropertyPropertyDetailsType`](#bookingreservationextendedpropertypropertydetailstype) | Resort Details |
| roomDetails | [`BookingReservationExtendedRoomDetailsType`](#bookingreservationextendedroomdetailstype) | Room Details |
| fixedChargesDetails | [`BookingReservationExtendedFixedChargesDetailsType`](#bookingreservationextendedfixedchargesdetailstype) | Fixed Charges Details |
| bookingReservationExtendedRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedReservationUnifiedDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aSBProratedYn | `String` | Indicates whether a prorated amount should be used for an Apartment Style Billing rate. |
| actionId | `Float` | Action ID |
| actualCheckInDateTime | `String` | Actual Check In Date Time |
| actualCheckOutDateTime | `String` | Actual Check Out Date Time |
| actualCheckInDate | `Date` | Actual Check-In Date |
| actualCheckOutDate | `Date` | Actual Check-Out Date |
| addressId | `Float` | Address ID |
| addresseeNameId | `Float` | Addressee Name ID |
| adults | `Float` | Adults |
| adultsTaxFree | `Float` | Adults Tax Free |
| advanceCheckedInYn | `String` | Indicates if the reservation has performed an Advance Check In. |
| agencyprofileid | `Float` | Agencyprofileid |
| agentNameId | `Float` | Agent Name ID |
| allAliases | `String` | All Aliases |
| allBlockOwners | `String` | All Block Owners |
| allCateringOwners | `String` | All Catering Owners |
| allCompanyContacts | `String` | All Company Contacts |
| allRateCodes | `String` | All Rate Codes |
| allRoomOwners | `String` | All Room Owners |
| allRoomTypes | `String` | All Room Types |
| allSourceContacts | `String` | All Source Contacts |
| allTravelAgentContacts | `String` | All Travel Agent Contacts |
| allotmentOrigin | `String` | Allotment Origin |
| allotmentRecordType | `Float` | Indicates whether the room type inventory was taken from the allotment or House availabilty. |
| allotmentType | `String` | Type of Block alloted for the group. |
| allotmentid | `Float` | Block ID |
| amenityEligibleYn | `String` | SPG - Indicates if this stay is eligible for an Amenity. |
| amenityLevelCode | `String` | Amenity Level Code |
| amountPercent | `Float` | Amount Percent |
| approvalAmount | `Float` | Approval Amount |
| approvalAmountCalcMethod | `Float` | Approval Amount Calc Method |
| approvalCode | `String` | Approval Code |
| arrivalComments | `String` | Arrival Comments |
| arrivalDate | `DateTime` | Arrival Date |
| arrivalDateTime | `Date` | Arrival Date Time |
| arrivalEstimateTime | `Date` | Arrival Estimate Time |
| authorizedBy | `Float` | This stores the pmsp.logged_uid who authorizes the direct bill |
| authorizerId | `Float` | Authorizer ID |
| autoCheckinYn | `String` | Auto Checkin Y/N |
| autoSettleDays | `String` | Auto Settle Days |
| autoSettleYN | `Float` | Auto Settle YN |
| averageRate | `Float` | Average Rate |
| awardCode | `String` | Award Code |
| awardCode1 | `String` | Award code 1 |
| awardCode2 | `String` | Award code 2 |
| awardCode3 | `String` | Award code 3 |
| awardCode4 | `String` | Award Code 4 |
| awardCode5 | `String` | Award code 5 |
| awardVoucher1 | `String` | Award Voucher number 1 |
| awardVoucher2 | `String` | Award Voucher number 2 |
| awardVoucher3 | `String` | Award Voucher number 3 |
| awardVoucher4 | `String` | Award Voucher number 4 |
| awardVoucher5 | `String` | Award Voucher number 5 |
| awdUpgrFrom | `String` | Room Type  before the Upgrade Award |
| awdUpgrTo | `String` | Room Type after the Upgrade Award |
| baseRateAmount | `Float` | Base Rate Amount |
| baseRateCode | `String` | Base Rate Code |
| baseRateCurrencyCode | `String` | Base Rate Currency Code |
| baseratecurrencyid | `String` | Baseratecurrencyid |
| beginDatetime | `String` | Begin Datetime |
| beginSystemDateTime | `String` | Stores the actual guest check in date and time. |
| billingContactId | `Float` | Billing Contact ID |
| billingcontactprofileid | `Float` | Billing Contact Profile ID |
| blockAlias | `String` | Block Alias |
| blockCode | `String` | Block Code |
| blockDescription | `String` | Block Description |
| blockDmlSeqNumber | `Float` | Block Dml Seq Number |
| blockEndbusinessdate | `Date` | Block Endbusinessdate |
| blockExchangePostingType | `String` | Block Exchange Posting Type |
| blockExchangeRate | `Float` | Block Exchange Rate |
| blockExternalReference | `String` | Block External Reference |
| blockID | `String` | Block ID |
| blockOwnerCode | `String` | Block Owner Code |
| blockResort | `String` | Property this block belongs to. |
| blockStatus | `String` | Block Status |
| blockStatusDescription | `String` | Block Status Description |
| blocksExternalReference | `String` | Blocks External Reference |
| bonusCheckId | `Float` | Bonus Check ID |
| bookedRoomCategory | `String` | Booked Room Category |
| bookedroomcategoryid | `String` | Bookedroomcategoryid |
| businessDateCreated | `Date` | Business Date Created |
| cancelDate | `Date` | Cancel Date |
| cancelReason | `String` | Cancel Reason |
| cancelTime | `String` | Cancel Time |
| cancellationDate | `DateTime` | Cancellation Date |
| cancellationNumber | `String` | Cancellation Number |
| cancellationReasonDescription | `String` | Cancellation Reason Description |
| cancellationreasonid | `String` | Cancellationreasonid |
| centralApprovalAmount | `Float` | Central Approval Amount |
| changesLogCheckIn | `String` | Changes Log Check In |
| changesLogCheckOut | `String` | Changes Log Check Out |
| changesLogCloseFolio | `String` | Changes Log Close Folio |
| changesLogReopenFolio | `String` | Changes Log Reopen Folio |
| changesLogUpdateReservation | `String` | Changes Log Update Reservation |
| checkinDuration | `Float` | Duration in seconds to complete Check-In |
| childBucket1 | `Float` | Child Bucket 1 |
| childBucket4 | `Float` | Child Bucket 4 |
| childBucket5 | `Float` | Child Bucket 5 |
| children | `Float` | Children |
| childrenAgeGroup2 | `Float` | Children Age Group 2) |
| childrenAgeGroup3 | `Float` | Children Age Group 3) |
| commissionCode | `String` | Commission Code |
| commissionHoldCode | `String` | Commission Hold Code |
| commissionPaid | `Float` | Commission Paid |
| commissionPayoutTo | `Float` | Indicates to whom the commission will be paid: NULL T (Travel Agent)  S (Source) and B (Both). |
| commissionableYN | `String` | Commissionable YN |
| commissionid | `String` | Commissionid |
| compTypeCode | `String` | Comp Type Code |
| companyAll | `String` | Company All |
| companyID | `Float` | Company ID |
| companyNameId | `Float` | Company Name ID |
| compreasonid | `String` | Compreasonid |
| confirmationLegNumber | `Float` | Confirmation Leg Number. |
| confirmationNo | `String` | Shared Confirmation Number |
| consumerYn | `String` | Consumer Y/N |
| contactNameId | `Float` | Contact Name ID |
| contactProfileID | `Float` | Contact Profile ID |
| createdBy | `String` | The name of the user who created the record. |
| createdDate | `Date` | Created Date |
| creditCardId | `Float` | Credit Card ID |
| creditLimitAutoPayAllowYn | `String` | Indicates if the reservation has opted-in for auto payment when credit limit overage is detected. |
| cribs | `Float` | Cribs |
| currencyCode | `String` | Currency Code |
| customReferenceNumber | `String` | Custom Reference Number |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateOfArrivalInCountry | `String` | Country Specific Requirement for Nigeria. |
| dateOpenedForPickup | `Date` | Date Opened for Pickup |
| departureComments | `String` | Departure Comments |
| departureDate | `Date` | Departure Date |
| departureDateTime | `Date` | Departure Date Time |
| departureTime | `String` | Departure Time |
| departureTransportCode | `String` | Departure Transport Code |
| departureTransportationYN | `String` | Departure Transportation YN |
| directBillVerifyResponse | `String` | Direct Bill Verify Response |
| discountAmount | `Float` | Discount Amount |
| discountAmt | `Float` | Discount Amount |
| discountPercent | `Float` | Discount Percentage. |
| discountPrcnt | `Float` | Discount Prcnt |
| discountReason | `String` | Discount Reason |
| discountreasonid | `String` | Discountreasonid |
| displayColor | `String` | Display Color |
| dmlSeqNumber | `Float` | Dml Sequence No |
| doNotMoveRoom | `String` | Do Not Move Room |
| doNotMoveYN | `String` | Do not move room flag. |
| downloadDate | `Date` | Download Date |
| downloadResort | `String` | Download Property |
| downloadSrep | `Float` | Download Srep |
| dropOffCarrierCode | `String` | Drop Off Carrier Code |
| dropOffDate | `Date` | Drop Off Date |
| dropOffStation | `String` | Drop Off Station |
| dropOffTime | `String` | Drop Off Time |
| eTRComments | `Date` | Comments related to Estimated Time of Return. |
| effectiveRateAmount | `Float` | Not used. |
| eligibleForUpgradeYn | `String` | Indicates if the reservation is eligible to receive room upgrades. Controlled by Central System. |
| emailAddress | `String` | Email Address |
| emailFolioYn | `String` | Email Folio Y/N |
| emailId | `Float` | Email ID |
| emailYn | `String` | Email Y/N |
| endDate | `Date` | End Date |
| endbusinessdate | `Date` | Endbusinessdate |
| entryDate | `String` | Entry Date into the country. (Croatian Requirements) |
| entryPoint | `Float` | (Customized) Entry point into the country. (Croatian Requirements) |
| esignedRegCardName | `String` | Name of file that contains the electronically signed registration card. |
| estimatedDepartureTime | `Date` | Estimated Departure Time |
| eventId | `Float` | Event ID |
| exchangePostingType | `String` | Exchange Posting Type |
| exchangeRate | `Float` | Exchange Rate |
| expectedTimeOfReturnETR | `String` | The time when an Advance Checked-In Guest is expected to return to perform the actual Check-In. |
| exportCheckinresId | `Float` | Used for Croatian Requirement Exports to store a unique checkin number. |
| extBookingID | `String` | Ext Allotment ID |
| extSegNo | `Float` | Not used |
| extSeqNumber | `Float` | Not used |
| extensionId | `Float` | Internal extension number for the main reservation |
| externalEfolioYn | `Date` | Indicates if the guest has opted to receive Efolio through an external system. |
| externalReference | `String` | External Reference |
| externallyLocked | `String` | Externally Locked |
| extraBeds | `Float` | Extra Beds |
| faxId | `Float` | Fax ID |
| faxYn | `String` | Should a confirmation be faxed for this reservation name? Y/N |
| financiallyResponsibleYn | `String` | Financially Responsible Y/N |
| fixedRateYN | `String` | Fixed Rate YN |
| folioAddrElementId | `Float` | Oracle sequence to identify different attribute values of an address. |
| folioCloseDate | `Date` | Date the folio was changed to closed. |
| folioText1 | `Date` | Folio Text1 |
| folioText2 | `String` | Folio Text2 |
| foreignCurrencyID | `String` | Foreign Currency ID |
| freeChild | `Float` | Free Child |
| gUID | `String` | GUID |
| guaranteeCodePreCi | `String` | Guarantee code before check in. Populated when the guarantee code is changed to CHECKED IN. |
| guaranteecodeid | `String` | Guaranteecodeid |
| guestFirstName | `String` | Guest First Name |
| guestFirstNameSdx | `String` | This is soundex of GUEST FIRST NAME - Phonotic sound. |
| guestLastNameSdx | `String` | Guest Last Name Sdx |
| guestSignature | `Float` | Signature of the guest |
| guestStatus | `String` | Used for Police/Tourist Export |
| guestType | `String` | Guest Type |
| guestprofileid | `Float` | Guestprofileid |
| gueststatusid | `String` | Gueststatusid |
| guesttypeid | `String` | Guesttypeid |
| housekeepingServiceTime | `String` | Housekeeping Service Time |
| hurdle | `Float` | Hurdle |
| hurdleOverride | `String` | Hurdle Override |
| inactiveDate | `Date` | Inactive Date |
| insertActionInstanceId | `Float` | Insert Action Instance ID |
| insertUser | `Float` | Insert User |
| interfaceID | `String` | This is the Interface_id of the System which sent/Received Allotment |
| intermediaryYn | `String` | Intermediary Y/N |
| internalAwardMembershipId | `Float` | Award Membership ID |
| internalBaseratecode | `String` | Baseratecode |
| internalBlockId | `String` | Block ID. |
| internalCompanyprofileid | `Float` | Companyprofileid |
| internalGroupprofileid | `Float` | Groupprofileid |
| internalSourceprofileid | `Float` | Sourceprofileid |
| keyValidUntil | `Float` | Key Valid Until |
| laptopChange | `Float` | Laptop Change |
| lastOnlinePrintSeq | `Float` | Last Online-Printing Sequence Number used by this reservation. |
| lastPeriodicFolioDate | `Date` | Latest date when a folio was printed using the "Periodic Batch Folios" option |
| lastSettleDate | `Date` | Latest date when a direct bill settlement was automatically done using the "Direct Bill Batch Folios" option |
| lengthOfStay | `Float` | Length of Stay |
| linkedArrivalDate | `Date` | Linked Arrival Date |
| linkedDepartureDate | `Date` | Linked Departure Date |
| localBaseRateAmount | `Float` | Local Base Rate Amount |
| mailYn | `String` | Mail Y/N |
| mainmarket | `String` | Mainmarket |
| manualCheckoutStatus | `String` | Indicates if this Reservation has requested or processed a Manual Checkout for consumer mobility. Possible Values: NULL [R]equested [P]rocessed. |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketid | `String` | Marketid |
| masterBlockID | `Float` | Parent Block ID |
| masterBlockProperty | `String` | Parent Resort |
| masterNameId | `Float` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| membershipId | `Float` | Membership ID |
| mobileActionAlertIssued | `String` | Stores when this Reservation has received a mobile action needed Alert for consumer mobility. |
| mobileAudioKeyYn | `Float` | Marked as Y when the Phone Number/EMail Address is Opt In. |
| mobileCheckinAllowedYn | `Date` | Mobile Checkin Allowed Y/N |
| mobileChkoutAllowed | `String` | Mobile Chkout Allowed |
| mobilePreferredCurrency | `String` | Currency preferred by a Mobile Registered Guest. |
| mobileViewFolioAllowed | `String` | Indicates if the reservation is eligible to view the folio by sending a mobile message. |
| name | `String` | Name |
| nameUsageType | `String` | Name Usage Type |
| nextDestination | `String` | Country Specific Requirement for Nigeria. |
| numberOfRooms | `Float` | No of Rooms |
| operaEsignedRegCardYn | `String` | Indicates if reservation?s registration card was esigned via Opera. |
| optInBatchFolYn | `String` | Indicates if the guest has opted in to receive email through the batch folio option. |
| optedForCommissionYN | `String` | Indicates if the reservation has opted-in for communications. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originCodeDescription | `String` | Origin Code Description |
| originOfBooking | `String` | Origin Of Booking |
| originalBaseRate | `Float` | Not used. |
| originalEndDate | `Date` | Original End Date |
| originalStartDate | `Date` | Original Start Date |
| owner | `Float` | Owner |
| ownerFfFlag | `String` | Owner Ff Flag |
| ownerResort | `String` | Owner Property |
| parentReservationNameId | `Float` | Parent Resv Name ID |
| parentreservationid | `Float` | Parentreservationid |
| partAllotment | `String` | Part Allotment |
| partyCode | `String` | Party Code |
| payment | `String` | Payment |
| paymentDescription | `String` | Payment Description |
| paymentMethod | `String` | Payment Method |
| paymentmethodid | `String` | Paymentmethodid |
| periodicFolioFreq | `Date` | Frequency in number of days when folios should be printed for this reservation |
| phoneDisplayNameYn | `String` | Indicates if the Phone Display Name is send to the Interface. |
| phoneId | `Float` | Phone ID |
| physicalQuantity | `Float` | Physical Quantity |
| pickUpCarrierCode | `String` | Pick Up Carrier Code |
| pickUpDate | `Date` | Pick Up Date |
| pickUpStation | `String` | Pick Up Station |
| pickUpTransportNumber | `String` | Pick Up Transport Number |
| pickUpTime | `String` | Pick-Up Time |
| pickupRequiredYN | `String` | Pickup Required YN |
| points | `Float` | Points |
| pointsEligibilityCode | `String` | Membership Points Eligibility Code. |
| postCoFlag | `String` | Identifies the charging status of the reservation after check out. O=Open Checkout P=Charging Privileges C=Closed Checkout. |
| postStayChargingYN | `String` | Indicates if the reservation has charging privileges after checkout. |
| postingAllowedYN | `String` | Posting Allowed YN |
| preArrReviewedDt | `Date` | This date flags if and when the record was reviewed from pre-arrival screen. |
| preArrReviewedUser | `Date` | User id who reviewed the record. |
| preChargingYn | `String` | Indicates if the reservation has charging privileges before arrival. |
| preRegisteredYn | `Date` | Indicates whether the reservation is pre-registered for internet check-in or not. |
| primaryShare | `String` | Primary Share |
| printRateYN | `String` | Print Rate YN |
| profileId | `String` | Profile ID |
| property | `String` | Indicates if the value set for the specific property. |
| pseudoMemTotalPoints | `String` | Total pseudo membership points accrued for the default membership type. |
| pseudoMemType | `String` | Default membership type used with the Pseudo Membership Points calculation functionality. |
| purgeDate | `Date` | Purge Date |
| purposeOfStay | `String` | Purpose of stay. |
| quantity | `Float` | Number of Rooms |
| quoteId | `String` | Quote ID provided by external system. |
| rateAmount | `String` | Rate Amount |
| rateCode | `String` | Rate Code |
| rateableValue | `Float` | Stay rateable value. |
| ratecodeid | `String` | Ratecodeid |
| rdenBillingContactId | `Float` | Rden Billing Contact ID |
| rdenReservationContactId | `Float` | Rden Resv Contact ID |
| rdenReservationDate | `Date` | Rden Reservation Date |
| referralYn | `String` | Rotation Rule to be configured for referral flag ? |
| registrationCardNo | `String` | Registration Card Number |
| registrationNumber | `String` | Registration Number |
| reinstateDate | `String` | Reinstate Date |
| reportId | `String` | Report ID |
| resInsertSource | `String` | Reservation Insert Source |
| resInsertSourceType | `String` | Reservation Insert Source Type |
| reservationContactId | `Float` | Resv Contact ID |
| reservationNameID | `Float` | Reservation Name ID |
| reservationStatus | `String` | Reservation Status |
| reservationType | `String` | Reservation Type |
| reservationTypeDescription | `String` | The Description of the Guarantee code. |
| reserveInventoryYN | `String` | Reserve Inventory YN |
| resort | `String` | Property |
| resortBooked | `String` | Final resort where Booking is confirmed -via Lead process. |
| resortChargeNumber | `String` | Auto generated charge number for Point Of Sale systems to identify guests. |
| restrictionOverride | `String` | Restriction Override |
| resvNumber | `Float` | Not used in PMS currently. |
| resvcontactprofileid | `Float` | Resvcontactprofileid |
| revenueTypeCode | `String` | Revenue type (catering/rooms) |
| rhBillingContactId | `Float` | Rh Billing Contact ID |
| rhReservationContactId | `Float` | Rh Resv Contact ID |
| rivMarketSegment | `String` | Not used |
| room | `String` | Room |
| roomCategory | `String` | Room Category |
| roomClass | `String` | Room Class |
| roomInstructions | `String` | Room Instructions |
| roomServiceTime | `String` | This is the Turndown room service time. |
| roomcategoryid | `String` | Roomcategoryid |
| roomid | `String` | Roomid |
| roomsPerDay | `Float` | Rooms Per Day |
| salesId | `String` | Not used |
| sbegindate | `Date` | Sbegindate |
| scheduleCheckoutYn | `String` | Is the guest scheduled for automatic check out? |
| senddate | `Date` | Senddate |
| serviceCharge | `Float` | Service Charge |
| sguestFirstName | `String` | Sguest First Name |
| sguestName | `String` | Sguest Name |
| shareId | `Float` | Share ID. |
| shareSeqNumber | `String` | Type of revenue |
| shareOfRateAmount | `Float` | Share of Rate Amount |
| sharedProfileID | `Float` | Shared Profile ID |
| sharedReservationStatus | `String` | Shared Reservation Status |
| shoulderEnd | `Date` | Shoulder End |
| shoulderStart | `Date` | Shoulder Start |
| sourceCodeDescription | `String` | Source Code Description |
| sourceContactAll | `String` | Source Contact All |
| sourceNameId | `Float` | Source Name ID |
| sourceid | `String` | Sourceid |
| spgDiscloseRoomTypeYn | `String` | SPG Room Type Disclosure Flag. Indicates if the guest stationery will disclose the actual room type. |
| spgSuiteNightAwardStatus | `String` | SPG Suite Night Award Status. |
| spgUpgradeConfirmedRoomtype | `String` | SPG Upgrade Confirmed Room Type Label. |
| spgUpgradeReasonCode | `String` | SPG Upgrade Reason Code. |
| splitFromReservationNameId | `Float` | Stores resv_name_id of the original multi room reservation from which this reservation is split off. |
| splitfromreservationid | `Float` | Splitfromreservationid |
| startDate | `Date` | Start Date |
| statisticalRateTier | `Float` | Rate Tier used for exports(DRS). |
| statisticalRoomType | `String` | Room Type used to calculate statistics for export(DRS). |
| stayRecordId | `Float` | Stay Record ID |
| superSearchIndexText | `String` | Super Search Index Text |
| taxAmount | `Float` | Tax Amount |
| taxExemptNumber | `String` | Tax exempt number on the profile |
| taxNumberOfStays | `Date` | Tax No of Stays |
| taxType | `String` | Tax Type |
| taxtypeid | `String` | Taxtypeid |
| tiad | `String` | Tiad |
| traceCode | `String` | Trace Code |
| transactionid | `Float` | Transactionid |
| travelAgentAll | `String` | Travel Agent All |
| travelAgentID | `Float` | Travel Agent ID |
| truncActualCheckOutDate | `Date` | This is the actual check out date with no time component. |
| turndownStatus | `Float` | Turndown status of the room per reservation per day. C-Completed NR-Not required R-Requested. |
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
| uniCardId | `String` | Universal Card ID used by interfaces for key encoding purposes. |
| updateUser | `Float` | Update User |
| updatedBy | `String` | Updated By |
| updatedDate | `Date` | Updated Date |
| uploadDate | `Date` | Upload Date |
| upsellCharge | `Float` | Incremental Upsell charges for the reservation date. |
| videoCheckoutYN | `String` | Flag if the guest can do video checkout |
| visaExpiryDate | `Date` | Visa Expiry Date |
| visaIssueDate | `String` | Visa Issue Date |
| visaNumber | `Float` | Visa Number |
| waitlistComment | `String` | Waitlist Comment |
| waitlistPhoneNumber | `String` | This is the waitlist telephone number. |
| walkInYN | `String` | Walk-In YN |
| yieldableYn | `String` | Yieldable Y/N |
| ymCode | `Float` | Ym Code |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedProfileAllInformationDetailsType

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

### BookingReservationExtendedProfileAccountsSourceDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRNumber | `String` | AR Number |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountEmailPrimary | `String` | Account Email Primary |
| accountID | `Float` | Account ID |
| accountName | `String` | Account Name |
| accountName2 | `String` | Account Name 2 |
| accountName3 | `String` | Account Name 3 |
| accountOwnerTitle | `String` | Account Owner Title |
| accountOwnersAll | `String` | Account Owners(All) |
| accountPhonePrimary | `String` | Phone no. |
| accountPhoneWeb | `String` | Account Phone Web |
| accountSource | `String` | Account Source |
| accountSourceDescription | `String` | Account Source Description |
| accountType | `String` | Account Type |
| accountTypeDescription | `String` | Account Type Description |
| acctContact | `String` | Billing contact person in company. |
| actionCode | `String` | Action Code |
| activeFlag | `String` | Active Flag |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| addressLangCodeDesc | `String` | Address Lang Code Description |
| addressLanguage | `String` | Address Language |
| addressLanguageCode | `String` | Address Language Code |
| addressType | `String` | Address Type |
| allProperties | `String` | All Properties |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Alternate Language Description |
| alternateName | `String` | Alternate Name |
| alternateSalutation | `String` | Alternate Salutation |
| alternateTitle | `String` | Alternate Title |
| arNumberCentral | `String` | AR No Central |
| autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| billingInstruction | `String` | Billing Instruction |
| billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| birthDate | `Date` | Birth Date |
| birthDateStr | `String` | Birth Date Str |
| birthPlace | `String` | Place of birth. |
| blMsg | `String` | Bl Msg |
| businessPotential | `String` | Business Potential |
| businessPotentialDescription | `String` | Business Potential Description |
| businessSegement | `String` | Business Segement |
| businessSegementDescription | `String` | Business Segement Description |
| businessTitle | `String` | Business Title |
| centralAccountOwnerTitle | `String` | Central Account Owner Title |
| centralAccountSource | `String` | Central Account Source |
| centralAccountSourceDescription | `String` | Central Account Source Description |
| centralAccountType | `String` | Central Account Type |
| centralAccountTypeDescription | `String` | Central Account Type Description |
| centralBusinessPotential | `String` | Central Business Potential |
| centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| centralBusinessSegementDescription | `String` | Central Business Segement Description |
| centralBusinessSegment | `String` | Central Business Segment |
| centralCompetitionCode | `String` | Central Competition Code |
| centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| centralCorporateType | `String` | Central Corporate Type |
| centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralIndustryCode | `String` | Central Industry Code |
| centralIndustryCodeDescription | `String` | Central Industry Code Description |
| centralKeyword | `String` | Central Keyword |
| centralPriority | `String` | Central Priority |
| centralPriorityDescription | `String` | Central Priority Description |
| centralProfileTypeCode | `String` | Central Profile Type Code |
| centralProfileTypeDescription | `String` | Central Profile Type Description |
| centralScope | `String` | Central Scope |
| centralScopeCity | `String` | Central Scope City |
| centralScopeCityDescription | `String` | Central Scope City Description |
| centralScopeDescription | `String` | Central Scope Description |
| centralState | `String` | Central State |
| centralTerritory | `String` | Central Territory |
| centralTerritoryDescription | `String` | Central Territory Description |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| cityExt | `String` | City Ext |
| combinedName | `String` | Combined Name |
| commissionCode | `String` | Commission Code |
| commissionCodeAll | `String` | Commission Code All |
| communicationRole1 | `String` | Communication Role1 |
| communicationRole2 | `String` | Communication Role2 |
| communicationRole3 | `String` | Communication Role3 |
| communicationType1 | `String` | Communication Type1 |
| communicationType2 | `String` | Communication Type2 |
| communicationType3 | `String` | Communication Type3 |
| communicationValue1 | `String` | Communication Value1 |
| communicationValue2 | `String` | Communication Value2 |
| communicationValue3 | `String` | Communication Value3 |
| company | `String` | Company |
| competitionCode | `String` | Competition Code |
| competitionCodeDescription | `String` | Competition Code Description |
| corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| corporateTypeDescription | `String` | Corporate Type Description |
| country | `String` | Country |
| countryDescription | `String` | Country Description |
| createdByUser | `String` | Created By User |
| createdOnDate | `DateTime` | Created On Date |
| creditCardName | `String` | Credit Card Name |
| creditCardType | `String` | Credit Card Type |
| creditRating | `String` | Credit Rating |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| emailYn | `String` | Email Y/N |
| envelopeGreeting | `String` | Envelope Greeting |
| externalId | `String` | External ID |
| fSubscriptionDb | `String` | F Subscription Db |
| fSubscriptionYn | `String` | F Subscription Y/N |
| faxNo | `String` | Fax Number |
| first | `String` | First |
| gender | `String` | Gender |
| guestPrivYn | `String` | Guest Priv Y/N |
| historyYn | `String` | History Y/N |
| holdCode | `String` | Hold Code |
| iATANumber | `String` | IATA Number |
| iataConsortia | `String` | IATA Consortia |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReason | `String` | Reason Code for inactive status from REASON table |
| inactiveReasonDescription | `String` | Reason why record was inactivated. |
| industryCode | `String` | Industry Code |
| industryCodeDescription | `String` | Industry Code Description |
| interest | `String` | Interest Code. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyword | `String` | Keyword |
| last | `String` | Last |
| lastGroup | `String` | Last Group |
| lastRate | `Float` | Last Rate |
| lastRoom | `String` | Not used. |
| lastSource | `String` | Last Source |
| lastStay | `Date` | Last Stay |
| legalCompany | `String` | Legal Company |
| letterGreeting | `String` | Letter Greeting |
| mailAction | `String` | Mail Action |
| mailActionDescription | `String` | Mail Action Description |
| mailList | `String` | Mail List |
| mailType | `String` | The type of mail this user should be sent. |
| mailYn | `String` | Mail Y/N |
| marketResearchYn | `String` | Market Research Y/N |
| middle | `String` | Middle |
| nameId | `Float` | Name ID |
| nationalityCode | `String` | Nationality Code |
| nationalityDescription | `String` | Nationality Description |
| negotiatedRate | `String` | Negotiated Rate |
| nextStay | `Date` | Next Stay |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryOwner | `String` | Primary Owner |
| primaryOwnerCode | `String` | Primary Owner Code |
| priority | `String` | Priority |
| priorityDescription | `String` | Priority Description |
| productInterest | `String` | Product Interest |
| profession | `String` | Profession of the guest |
| profileLanguageDescription | `String` | Profile Language Description |
| profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| profileType | `String` | Profile Type |
| profileTypeCode | `String` | Profile Type Code |
| profileTypeDescription | `String` | Profile Type Description |
| protected | `String` | Protected |
| referenceCurrency | `String` | Reference Currency |
| repInfluence | `String` | Reporting Influence |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repMailActionCodes | `String` | Rep Mail Action Codes |
| repMailActionDesc | `String` | Rep Mail Action Desc |
| repNationalityCode | `String` | Reporting Nationality Code |
| repNationalityDescription | `String` | Reporting Nationality Description |
| repStateDescription | `String` | Reporting State Desc |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTitleName | `String` | Reporting Title Name |
| repVIPName | `String` | Reporting Vip Name |
| repVIPStatus | `String` | Reporting Vip Status |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| resortRegistered | `String` | Resort for which Job is registered. |
| restricted | `String` | Restricted |
| restrictedRule | `String` | Restricted Rule |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope |
| scopeCity | `String` | Scope City |
| scopeCityDecription | `String` | Scope City Decription |
| scopeDescription | `String` | Scope Description |
| searchAccountName | `String` | The Uppercase value of Last or Company. |
| sfirst | `String` | Uppercase value of First Name. |
| state | `String` | State |
| stateCode | `String` | State Code |
| stateDesc | `String` | State Description of the Guest of Payee |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| tax1No | `String` | Tax1 Number |
| tax2No | `String` | Tax2 Number |
| taxCategory | `String` | Tax Category |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| territory | `String` | Territory |
| territoryDescription | `String` | Territory Description |
| thirdPartyYn | `String` | Third Party Y/N |
| traceCode | `String` | Trace Code |
| traceCodeDescription | `String` | Trace Code Description |
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
| updateDate | `DateTime` | Update Date |
| updateFaxDate | `Date` | The last date this record's fax # was updated. |
| updateUser | `String` | Update User |
| vipName | `String` | VIP Name |
| vipStatus | `String` | VIP Status |
| xcompanyName | `String` | Extended Byte Company Name |
| xenvelopeGreeting | `String` | Xenvelope Greeting |
| xfirstName | `String` | Xfirst Name |
| xlastName | `String` | Xlast Name |
| xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedProfileAccountsTravelAgentDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRNumber | `String` | AR Number |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountEmailPrimary | `String` | Account Email Primary |
| accountID | `Float` | Account ID |
| accountName | `String` | Account Name |
| accountName2 | `String` | Account Name 2 |
| accountName3 | `String` | Account Name 3 |
| accountOwnerTitle | `String` | Account Owner Title |
| accountOwnersAll | `String` | Account Owners(All) |
| accountPhonePrimary | `String` | Phone no. |
| accountPhoneWeb | `String` | Account Phone Web |
| accountSource | `String` | Account Source |
| accountSourceDescription | `String` | Account Source Description |
| accountType | `String` | Account Type |
| accountTypeDescription | `String` | Account Type Description |
| acctContact | `String` | Billing contact person in company. |
| actionCode | `String` | Action Code |
| activeFlag | `String` | Active Flag |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| addressLangCodeDesc | `String` | Address Lang Code Description |
| addressLanguage | `String` | Address Language |
| addressLanguageCode | `String` | Address Language Code |
| addressType | `String` | Address Type |
| allProperties | `String` | All Properties |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Alternate Language Description |
| alternateName | `String` | Alternate Name |
| alternateSalutation | `String` | Alternate Salutation |
| alternateTitle | `String` | Alternate Title |
| arNumberCentral | `String` | AR No Central |
| autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| billingInstruction | `String` | Billing Instruction |
| billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| birthDate | `Date` | Birth Date |
| birthDateStr | `String` | Birth Date Str |
| birthPlace | `String` | Place of birth. |
| blMsg | `String` | Bl Msg |
| businessPotential | `String` | Business Potential |
| businessPotentialDescription | `String` | Business Potential Description |
| businessSegement | `String` | Business Segement |
| businessSegementDescription | `String` | Business Segement Description |
| businessTitle | `String` | Business Title |
| centralAccountOwnerTitle | `String` | Central Account Owner Title |
| centralAccountSource | `String` | Central Account Source |
| centralAccountSourceDescription | `String` | Central Account Source Description |
| centralAccountType | `String` | Central Account Type |
| centralAccountTypeDescription | `String` | Central Account Type Description |
| centralBusinessPotential | `String` | Central Business Potential |
| centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| centralBusinessSegementDescription | `String` | Central Business Segement Description |
| centralBusinessSegment | `String` | Central Business Segment |
| centralCompetitionCode | `String` | Central Competition Code |
| centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| centralCorporateType | `String` | Central Corporate Type |
| centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralIndustryCode | `String` | Central Industry Code |
| centralIndustryCodeDescription | `String` | Central Industry Code Description |
| centralKeyword | `String` | Central Keyword |
| centralPriority | `String` | Central Priority |
| centralPriorityDescription | `String` | Central Priority Description |
| centralProfileTypeCode | `String` | Central Profile Type Code |
| centralProfileTypeDescription | `String` | Central Profile Type Description |
| centralScope | `String` | Central Scope |
| centralScopeCity | `String` | Central Scope City |
| centralScopeCityDescription | `String` | Central Scope City Description |
| centralScopeDescription | `String` | Central Scope Description |
| centralState | `String` | Central State |
| centralTerritory | `String` | Central Territory |
| centralTerritoryDescription | `String` | Central Territory Description |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| cityExt | `String` | City Ext |
| combinedName | `String` | Combined Name |
| commissionCode | `String` | Commission Code |
| commissionCodeAll | `String` | Commission Code All |
| communicationRole1 | `String` | Communication Role1 |
| communicationRole2 | `String` | Communication Role2 |
| communicationRole3 | `String` | Communication Role3 |
| communicationType1 | `String` | Communication Type1 |
| communicationType2 | `String` | Communication Type2 |
| communicationType3 | `String` | Communication Type3 |
| communicationValue1 | `String` | Communication Value1 |
| communicationValue2 | `String` | Communication Value2 |
| communicationValue3 | `String` | Communication Value3 |
| company | `String` | Company |
| competitionCode | `String` | Competition Code |
| competitionCodeDescription | `String` | Competition Code Description |
| corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| corporateTypeDescription | `String` | Corporate Type Description |
| country | `String` | Country |
| countryDescription | `String` | Country Description |
| createdByUser | `String` | Created By User |
| createdOnDate | `DateTime` | Created On Date |
| creditCardName | `String` | Credit Card Name |
| creditCardType | `String` | Credit Card Type |
| creditRating | `String` | Credit Rating |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| emailYn | `String` | Email Y/N |
| envelopeGreeting | `String` | Envelope Greeting |
| externalId | `String` | External ID |
| fSubscriptionDb | `String` | F Subscription Db |
| fSubscriptionYn | `String` | F Subscription Y/N |
| faxNo | `String` | Fax Number |
| first | `String` | First |
| gender | `String` | Gender |
| guestPrivYn | `String` | Guest Priv Y/N |
| historyYn | `String` | History Y/N |
| holdCode | `String` | Hold Code |
| iATANumber | `String` | IATA Number |
| iataConsortia | `String` | IATA Consortia |
| inactiveDate | `Date` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReason | `String` | Reason Code for inactive status from REASON table |
| inactiveReasonDescription | `String` | Reason why record was inactivated. |
| industryCode | `String` | Industry Code |
| industryCodeDescription | `String` | Industry Code Description |
| interest | `String` | Interest Code. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyword | `String` | Keyword |
| last | `String` | Last |
| lastGroup | `String` | Last Group |
| lastRate | `Float` | Last Rate |
| lastRoom | `String` | Not used. |
| lastSource | `String` | Last Source |
| lastStay | `Date` | Last Stay |
| legalCompany | `String` | Legal Company |
| letterGreeting | `String` | Letter Greeting |
| mailAction | `String` | Mail Action |
| mailActionDescription | `String` | Mail Action Description |
| mailList | `String` | Mail List |
| mailType | `String` | The type of mail this user should be sent. |
| mailYn | `String` | Mail Y/N |
| marketResearchYn | `String` | Market Research Y/N |
| middle | `String` | Middle |
| nameId | `Float` | Name ID |
| nationalityCode | `String` | Nationality Code |
| nationalityDescription | `String` | Nationality Description |
| negotiatedRate | `String` | Negotiated Rate |
| nextStay | `Date` | Next Stay |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryOwner | `String` | Primary Owner |
| primaryOwnerCode | `String` | Primary Owner Code |
| priority | `String` | Priority |
| priorityDescription | `String` | Priority Description |
| productInterest | `String` | Product Interest |
| profession | `String` | Profession of the guest |
| profileLanguageDescription | `String` | Profile Language Description |
| profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| profileType | `String` | Profile Type |
| profileTypeCode | `String` | Profile Type Code |
| profileTypeDescription | `String` | Profile Type Description |
| protected | `String` | Protected |
| referenceCurrency | `String` | Reference Currency |
| repInfluence | `String` | Reporting Influence |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repMailActionCodes | `String` | Rep Mail Action Codes |
| repMailActionDesc | `String` | Rep Mail Action Desc |
| repNationalityCode | `String` | Reporting Nationality Code |
| repNationalityDescription | `String` | Reporting Nationality Description |
| repStateDescription | `String` | Reporting State Desc |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTitleName | `String` | Reporting Title Name |
| repVIPName | `String` | Reporting Vip Name |
| repVIPStatus | `String` | Reporting Vip Status |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| resortRegistered | `String` | Resort for which Job is registered. |
| restricted | `String` | Restricted |
| restrictedRule | `String` | Restricted Rule |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope |
| scopeCity | `String` | Scope City |
| scopeCityDecription | `String` | Scope City Decription |
| scopeDescription | `String` | Scope Description |
| searchAccountName | `String` | The Uppercase value of Last or Company. |
| sfirst | `String` | Uppercase value of First Name. |
| state | `String` | State |
| stateCode | `String` | State Code |
| stateDesc | `String` | State Description of the Guest of Payee |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| tax1No | `String` | Tax1 Number |
| tax2No | `String` | Tax2 Number |
| taxCategory | `String` | Tax Category |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| territory | `String` | Territory |
| territoryDescription | `String` | Territory Description |
| thirdPartyYn | `String` | Third Party Y/N |
| traceCode | `String` | Trace Code |
| traceCodeDescription | `String` | Trace Code Description |
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
| updateDate | `DateTime` | Update Date |
| updateFaxDate | `Date` | The last date this record's fax # was updated. |
| updateUser | `String` | Update User |
| vipName | `String` | VIP Name |
| vipStatus | `String` | VIP Status |
| xcompanyName | `String` | Extended Byte Company Name |
| xenvelopeGreeting | `String` | Xenvelope Greeting |
| xfirstName | `String` | Xfirst Name |
| xlastName | `String` | Xlast Name |
| xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedExternalReferencesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| extCancellationNo | `String` | Cancellation number received from the external system. |
| externalReferenceLegNumber | `Float` | Reservation leg number for itinerary reservations. |
| externalReferenceNumber | `String` | External Reference Number |
| externalReferenceType | `String` | Type of external reference depending from what external system the number was passed. |
| externalStatus | `String` | Status of the reservation in the external system 'C' -> Cancelled value NULL or 'A' -> 'Active'. |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| manualYn | `String` | Manual Y/N |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reservationNameId | `Float` | Resv Name ID |
| revisionToken | `String` | Indicates the revision of information provided by an external system that this record corresponds to. This will be used to keep information consistent between OPERA and the external system. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| upperExternalReference | `String` | External reference stored in upper case. |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedReservationMembershipDetailsType

| Field | Type | Description |
| --- | --- | --- |
| cardNumberByMembershipClass | `String` | Card Number by Membership Class |
| cardNumberByMembershipType | `String` | Card Number by Membership Type |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| earningPreference | `String` | Earning Preference |
| frequentFlyerMembershipYN | `String` | Frequent Flyer Membership YN |
| hostBusinessDate | `Date` | Business date when the host-multiplier relationship was set. |
| hostCardinality | `Float` | Number of multipliers attached if a host-multiplier relationship exists. |
| hostFlag | `String` | Indicator whether the current membership for the rervation is a (H)ost membership detail |
| iDByMembershipClass | `String` | ID by Membership Class |
| iDByMembershipType | `String` | ID by Membership Type |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalMembershipid | `Float` | Membershipid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| levelByMembershipType | `String` | Level by Membership Type |
| listOfMembershipIDs | `Float` | Membership ID |
| locationID | `String` | Internal ID to uniquely identify the Property |
| loyaltySchemeMembershipYN | `String` | Loyalty Scheme Membership YN |
| mbrprefChangedDate | `Date` | Last Date Earning Preference was changed. |
| membershipCardNo | `String` | Membership Card Number |
| membershipCardNumber | `String` | Membership Card Number |
| membershipClass | `String` | Membership Class |
| membershipClassDescription | `String` | Membership Class Description |
| membershipCode | `String` | Membership Code |
| membershipDescription | `String` | Membership Description |
| membershipId | `Float` | Membership ID |
| membershipLevel | `String` | Membership Level |
| membershipLevelByMembershipClass | `String` | Membership Level by Membership Class |
| membershipType | `String` | Membership Type |
| membershipTypeByMembershipClass | `String` | Membership Type by Membership Class |
| multiplierInstance | `Float` | Multiplier instance number if a host-multiplier relationship exists. |
| nameId | `Float` | Name ID |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| pointsMultiplier | `Float` | Indicates any multiplier for the points accumulated. |
| populationMethod | `String` | Population Method |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| processedDate | `Date` | Processed Date |
| processedYn | `String` | Processed Y/N |
| profileid | `Float` | Profileid |
| property | `String` | Code to uniquely identify the Property |
| rankValue | `Float` | Rank Value |
| reservationNameId | `Float` | Resv Name ID |
| reservationid | `Float` | Reservationid |
| reservationmembershipid | `Float` | Reservationmembershipid |
| resvenddate | `Date` | Resvenddate |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedReservationPaymentMethodsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| authorizationAmount | `Float` | Authorization Amount |
| authorizationDescription | `String` | Authorization Description |
| authorizationRule | `Float` | Authorization Rule |
| bonusCheckId | `Float` | Bonus Check ID |
| centralPaymentMethodType | `String` | Central Payment Method Type |
| centralPaymentMethodTypeDescription | `String` | Central Payment Method Type Description |
| creditCardAuthorizationDate | `DateTime` | Credit Card Authorization Date |
| creditCardId | `Float` | Credit Card ID |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| directBillVerifyResponse | `String` | Direct Bill Verify Response |
| emailAddress | `String` | Email Address |
| emailFolioYn | `String` | Email Folio Y/N |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentMethodType | `String` | Payment Method Type |
| paymentMethodTypeDescription | `String` | Payment Method Type Description |
| paymentWindow | `Float` | Payment Window |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reservationNameId | `Float` | Resv Name ID |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedProfileAccountsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRNumber | `String` | AR Number |
| aRCUpdateDate | `Date` | The date this record was last updated by the ARC update program. |
| accountEmailPrimary | `String` | Account Email Primary |
| accountID | `Float` | Account ID |
| accountName | `String` | Account Name |
| accountName2 | `String` | Account Name 2 |
| accountName3 | `String` | Account Name 3 |
| accountOwnerTitle | `String` | Account Owner Title |
| accountOwnersAll | `String` | Account Owners(All) |
| accountPhonePrimary | `String` | Phone no. |
| accountPhoneWeb | `String` | Account Phone Web |
| accountSource | `String` | Account Source |
| accountSourceDescription | `String` | Account Source Description |
| accountType | `String` | Account Type |
| accountTypeDescription | `String` | Account Type Description |
| acctContact | `String` | Billing contact person in company. |
| actionCode | `String` | Action Code |
| activeFlag | `String` | Active Flag |
| address1 | `String` | Address 1 |
| address2 | `String` | Address 2 |
| address3 | `String` | Address 3 |
| address4 | `String` | Address 4 |
| addressLangCodeDesc | `String` | Address Lang Code Description |
| addressLanguage | `String` | Address Language |
| addressLanguageCode | `String` | Address Language Code |
| addressType | `String` | Address Type |
| allProperties | `String` | All Properties |
| alternateLanguage | `String` | The Extended Byte Language of the Profile. |
| alternateLanguageDescription | `String` | Alternate Language Description |
| alternateName | `String` | Alternate Name |
| alternateSalutation | `String` | Alternate Salutation |
| alternateTitle | `String` | Alternate Title |
| arNumberCentral | `String` | AR No Central |
| autoenrollMemberYn | `String` | Autoenroll Member Y/N |
| billingInstruction | `String` | Billing Instruction |
| billingProfileCode | `String` | For tour operators the type of billing profile for this name. |
| birthDate | `Date` | Birth Date |
| birthDateStr | `String` | Birth Date Str |
| birthPlace | `String` | Place of birth. |
| blMsg | `String` | Bl Msg |
| businessPotential | `String` | Business Potential |
| businessPotentialDescription | `String` | Business Potential Description |
| businessSegement | `String` | Business Segement |
| businessSegementDescription | `String` | Business Segement Description |
| businessTitle | `String` | Business Title |
| centralAccountOwnerTitle | `String` | Central Account Owner Title |
| centralAccountSource | `String` | Central Account Source |
| centralAccountSourceDescription | `String` | Central Account Source Description |
| centralAccountType | `String` | Central Account Type |
| centralAccountTypeDescription | `String` | Central Account Type Description |
| centralBusinessPotential | `String` | Central Business Potential |
| centralBusinessPotentialDescription | `String` | Central Business Potential Description |
| centralBusinessSegementDescription | `String` | Central Business Segement Description |
| centralBusinessSegment | `String` | Central Business Segment |
| centralCompetitionCode | `String` | Central Competition Code |
| centralCompetitionCodeDescription | `String` | Central Competition Code Description |
| centralCorporateType | `String` | Central Corporate Type |
| centralCorporateTypeDescription | `String` | Central Corporate Type Description |
| centralInactiveReason | `String` | Central Inactive Reason |
| centralInactiveReasonDescription | `String` | Central Inactive Reason Description |
| centralIndustryCode | `String` | Central Industry Code |
| centralIndustryCodeDescription | `String` | Central Industry Code Description |
| centralKeyword | `String` | Central Keyword |
| centralPriority | `String` | Central Priority |
| centralPriorityDescription | `String` | Central Priority Description |
| centralProfileTypeCode | `String` | Central Profile Type Code |
| centralProfileTypeDescription | `String` | Central Profile Type Description |
| centralScope | `String` | Central Scope |
| centralScopeCity | `String` | Central Scope City |
| centralScopeCityDescription | `String` | Central Scope City Description |
| centralScopeDescription | `String` | Central Scope Description |
| centralState | `String` | Central State |
| centralTerritory | `String` | Central Territory |
| centralTerritoryDescription | `String` | Central Territory Description |
| chainCode | `String` | Chain Code |
| city | `String` | City |
| cityExt | `String` | City Ext |
| combinedName | `String` | Combined Name |
| commissionCode | `String` | Commission Code |
| commissionCodeAll | `String` | Commission Code All |
| communicationRole1 | `String` | Communication Role1 |
| communicationRole2 | `String` | Communication Role2 |
| communicationRole3 | `String` | Communication Role3 |
| communicationType1 | `String` | Communication Type1 |
| communicationType2 | `String` | Communication Type2 |
| communicationType3 | `String` | Communication Type3 |
| communicationValue1 | `String` | Communication Value1 |
| communicationValue2 | `String` | Communication Value2 |
| communicationValue3 | `String` | Communication Value3 |
| company | `String` | Company |
| competitionCode | `String` | Competition Code |
| competitionCodeDescription | `String` | Competition Code Description |
| corporateType | `String` | Specified whether Name_Code column has Company # or IATA #. For Company # the value will beCOMP and for IATA # the Value of this column will be IATA. |
| corporateTypeDescription | `String` | Corporate Type Description |
| country | `String` | Country |
| countryDescription | `String` | Country Description |
| createdByUser | `String` | Created By User |
| createdOnDate | `DateTime` | Created On Date |
| creditCardName | `String` | Credit Card Name |
| creditCardType | `String` | Credit Card Type |
| creditRating | `String` | Credit Rating |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| emailYn | `String` | Email Y/N |
| envelopeGreeting | `String` | Envelope Greeting |
| externalId | `String` | External ID |
| fSubscriptionDb | `String` | F Subscription Db |
| fSubscriptionYn | `String` | F Subscription Y/N |
| faxNo | `String` | Fax Number |
| first | `String` | First |
| gender | `String` | Gender |
| guestPrivYn | `String` | Guest Priv Y/N |
| historyYn | `String` | History Y/N |
| holdCode | `String` | Hold Code |
| iATANumber | `String` | IATA Number |
| iataConsortia | `String` | IATA Consortia |
| inactiveDate | `DateTime` | Inactive Date |
| inactiveFlag | `String` | Inactive Flag |
| inactiveReason | `String` | Reason Code for inactive status from REASON table |
| inactiveReasonDescription | `String` | Reason why record was inactivated. |
| industryCode | `String` | Industry Code |
| industryCodeDescription | `String` | Industry Code Description |
| interest | `String` | Interest Code. |
| internalDeletedflag | `String` | Deleted Flag |
| internalInactiveflag | `String` | Inactive Flag |
| internalOrganizationId | `Float` | Organization ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| keyword | `String` | Keyword |
| last | `String` | Last |
| lastGroup | `String` | Last Group |
| lastRate | `Float` | Last Rate |
| lastRoom | `String` | Not used. |
| lastSource | `String` | Last Source |
| lastStay | `Date` | Last Stay |
| legalCompany | `String` | Legal Company |
| letterGreeting | `String` | Letter Greeting |
| mailAction | `String` | Mail Action |
| mailActionDescription | `String` | Mail Action Description |
| mailList | `String` | Mail List |
| mailType | `String` | The type of mail this user should be sent. |
| mailYn | `String` | Mail Y/N |
| marketResearchYn | `String` | Market Research Y/N |
| middle | `String` | Middle |
| nameId | `Float` | Name ID |
| nationalityCode | `String` | Nationality Code |
| nationalityDescription | `String` | Nationality Description |
| negotiatedRate | `String` | Negotiated Rate |
| nextStay | `Date` | Next Stay |
| nickname | `String` | The nickname of this individual. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentDueDays | `Float` | Number of days a payment is due for the account. |
| postalCode | `String` | Postal Code |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| primaryOwner | `String` | Primary Owner |
| primaryOwnerCode | `String` | Primary Owner Code |
| priority | `String` | Priority |
| priorityDescription | `String` | Priority Description |
| productInterest | `String` | Product Interest |
| profession | `String` | Profession of the guest |
| profileLanguageDescription | `String` | Profile Language Description |
| profilePrivacyFlg | `String` | Profile privacy flag determine if the profile is marked as private for a property. |
| profileType | `String` | Profile Type |
| profileTypeCode | `String` | Profile Type Code |
| profileTypeDescription | `String` | Profile Type Description |
| protected | `String` | Protected |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| referenceCurrency | `String` | Reference Currency |
| repInfluence | `String` | Reporting Influence |
| repInfluenceDescription | `String` | Reporting Influence Desc |
| repMailActionCodes | `String` | Rep Mail Action Codes |
| repMailActionDesc | `String` | Rep Mail Action Desc |
| repNationalityCode | `String` | Reporting Nationality Code |
| repNationalityDescription | `String` | Reporting Nationality Description |
| repStateDescription | `String` | Reporting State Desc |
| repTaxTypeDescription | `String` | Reporting Tax Type Desc |
| repTitleName | `String` | Reporting Title Name |
| repVIPName | `String` | Reporting Vip Name |
| repVIPStatus | `String` | Reporting Vip Status |
| replaceAddress | `String` | User option to replace address in ORS with one from PMS. |
| resortRegistered | `String` | Resort for which Job is registered. |
| restricted | `String` | Restricted |
| restrictedRule | `String` | Restricted Rule |
| salutation | `String` | Salutation Greeting |
| scope | `String` | Scope |
| scopeCity | `String` | Scope City |
| scopeCityDecription | `String` | Scope City Decription |
| scopeDescription | `String` | Scope Description |
| searchAccountName | `String` | The Uppercase value of Last or Company. |
| sfirst | `String` | Uppercase value of First Name. |
| state | `String` | State |
| stateCode | `String` | State Code |
| stateDesc | `String` | State Description of the Guest of Payee |
| sxfirstName | `String` | Internal Indexed field for Searching by Extended Byte First Name. |
| sxname | `String` | Internal Indexed field for Searching by Extended Byte Name. |
| tax1No | `String` | Tax1 Number |
| tax2No | `String` | Tax2 Number |
| taxCategory | `String` | Tax Category |
| taxType | `String` | Tax Type |
| taxTypeDescription | `String` | Tax Type Description |
| territory | `String` | Territory |
| territoryDescription | `String` | Territory Description |
| thirdPartyYn | `String` | Third Party Y/N |
| traceCode | `String` | Trace Code |
| traceCodeDescription | `String` | Trace Code Description |
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
| updateDate | `DateTime` | Update Date |
| updateFaxDate | `Date` | The last date this record's fax # was updated. |
| updateUser | `String` | Update User |
| vipName | `String` | VIP Name |
| vipStatus | `String` | VIP Status |
| xcompanyName | `String` | Extended Byte Company Name |
| xenvelopeGreeting | `String` | Xenvelope Greeting |
| xfirstName | `String` | Xfirst Name |
| xlastName | `String` | Xlast Name |
| xmiddleName | `String` | Extended Byte middle name. |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedReservationDepositScheduleDetailsType

| Field | Type | Description |
| --- | --- | --- |
| activityDeposit | `Float` | Deposit Amount for the Activity. Populated by Concept system currently. |
| cActivityDeposit | `Float` | Central Activity Deposit |
| cCancelPnltyAmount | `Float` | Central Cancel Pnlty Amount |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cForeignDepositAmount | `Float` | Central Foreign Deposit Amount |
| cancelDeadline | `Date` | Date the reservation can be cancelled |
| cancelPnltyAmount | `Float` | Amount to be charged for a cancellation |
| centralDepositAmountOutstanding | `Float` | Central Deposit Amount Outstanding |
| centralDepositAmountRequested | `Float` | Central Deposit Amount Requested |
| centralTotalDepositPayments | `Float` | Central Total Deposit Payments |
| comments | `String` | Comments |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedFlag | `String` | Deleted Flag |
| depositAmountOutstanding | `Float` | Deposit Amount Outstanding |
| depositAmountRequested | `Float` | Deposit Amount Requested |
| depositDueDate | `Date` | Deposit Due Date |
| depositPercentage | `Float` | Deposit Percentage |
| depositReqLinkId | `Float` | ID will be populated for reversal records to link the main deposit request. |
| depositReqReceiptNo | `Float` | Deposit Req Receipt Number |
| depositReqReversalYn | `String` | Identifies if this record is a deposit request reversal. |
| depositRule | `String` | Deposit Rule |
| depositRuleDescription | `String` | Deposit Rule Description |
| depositRuleType | `String` | Deposit Rule Type |
| depositScheduleReservationNameId | `Float` | Deposit Schedule Resv Name ID |
| depositType | `String` | Stores the type of the deposit: possible values "RECEIPT" or "FOLIO". |
| dmlSeqNumber | `Float` | Dml Sequence No |
| exchangeRateInfo | `String` | Exchange Rate info used for cancelation penalty if Rate code is in a difference currency. |
| externalId | `String` | External ID |
| foreignDepositAmount | `Float` | Deposit Amount in Foreign currency if Rate code is in a different currency. |
| insertActionInstanceId | `Float` | Insert Action Instance ID |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| manualYn | `String` | Manual Y/N |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| paymentFlag | `String` | Not used |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| processedYn | `String` | Processed Y/N |
| productId | `String` | Product ID |
| property | `String` | Code to uniquely identify the Property |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| rateDcSeq | `Float` | Rate Dc Sequence |
| reservationDepositScheduleId | `Float` | Resv Deposit Schedule ID |
| roomDeposit | `Float` | Deposit Amount due to pure room charges. |
| totalDepositPayments | `Float` | Amount of the transaction that resulted in the form being required |
| trxDate | `Date` | Transaction Date |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedRateCodeDetailsDetailsType

| Field | Type | Description |
| --- | --- | --- |
| addAfterRounding | `Float` | Amount to be added after rounding |
| adultCharge | `Float` | Adult Charge |
| adultsThreshold | `Float` | Threshold for number of adults on a reservation. Additional charge will be added when reservation exceeds this threshold. |
| adultsThresholdCharge | `Float` | Amount used to calculate price for adults when the number of adults on the reservation exceed the adult threshold. |
| advBaseAmount | `Float` | Indicates either Flat amount or Percentage increase or decrease from the advanced dynamic base rate. |
| advBaseFltPct | `String` | Calculate as Flat [FLT] or Percentage [PCT] amount of the advanced dynamic base rate code. |
| advDailyBaseRateCode | `String` | Identifies the Advanced Daily Base Rate Code from which this rate detail was copied. |
| advanceBaseCompareYN | `String` | Identifies if during the availability check the calculated based amount should be compared to rate detail of BAR rate code. |
| ageRangeForBucket1 | `String` | Age Range for Bucket 1 |
| ageRangeForBucket2 | `String` | Age Range for Bucket 2 |
| ageRangeForBucket3 | `String` | Age Range for Bucket 3 |
| amount1Type | `String` | Indicate the amount type for the 1 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| amount2Type | `String` | Indicate the amount type for the 2 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| amount3Type | `String` | Indicate the amount type for the 3 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| amount4Type | `String` | Indicate the amount type for the 4 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| amount5Type | `String` | Indicate the amount type for the 5 Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| amountFor1Person | `Float` | Amount for 1 Person |
| amountFor2Persons | `Float` | Amount for 2 Persons |
| amountFor3Persons | `Float` | Amount for 3 Persons |
| amountFor4Persons | `Float` | Amount for 4 Persons |
| amountFor5Persons | `Float` | Amount for 5 adults |
| barAmount | `Float` | Stores the Percentage or Amount difference between BAR Rate code and this Rate Code. |
| barFltPct | `String` | Identifies if the amount column represents a Flat [FLT] or Percentage [PCT] value. |
| barRounding | `String` | Identifies the rounding formula for the BBAR Rate calculation. |
| barYn | `String` | Is this schedule applied to bar by los rate pushing also. |
| cAdultCharge | `Float` | Central Adult Charge |
| cAdultsThresholdCharge | `Float` | Central Adults Threshold Charge |
| cAdvanceBaseAmount | `Float` | Central Adv Base Amount |
| cAmount1 | `Float` | Central Amount 1 |
| cAmount2 | `Float` | Central Amount 2 |
| cAmount3 | `Float` | Central Amount 3 |
| cAmount4 | `Float` | Central Amount 4 |
| cAmount5 | `Float` | Central Amount 5 |
| cBarAmount | `Float` | Central Bar Amount |
| cChildCharge1 | `Float` | Central Child Charge 1 |
| cChildCharge2 | `Float` | Central Child Charge 2 |
| cChildCharge3 | `Float` | Central Child Charge 3 |
| cChildOwnCharge1 | `Float` | Central Child Own Charge 1 |
| cChildOwnCharge2 | `Float` | Central Child Own Charge 2 |
| cChildOwnCharge3 | `Float` | Central Child Own Charge 3 |
| cChildOwnCharge4 | `Float` | Central Child Own Charge 4 |
| cChildrenCharge | `Float` | Central Children Charge |
| cChildrenThresholdCharge | `Float` | Central Children Threshold Charge |
| cDifferenceAmount1 | `Float` | Central Diff Amount 1 |
| cDifferenceAmount2 | `Float` | Central Diff Amount 2 |
| cDifferenceAmount3 | `Float` | Central Diff Amount 3 |
| cDifferenceAmount4 | `Float` | Central Diff Amount 4 |
| cDifferenceAmount5 | `Float` | Central Diff Amount 5 |
| cDifferenceAmountExtraAdult | `Float` | Central Diff Amount Extra Adult |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cFlatIncrease | `Float` | Central Flat Increase |
| cLos1Amount | `Float` | Central Los1 Amt |
| cLos10Amount | `Float` | Central Los10 Amt |
| cLos11Amount | `Float` | Central Los11 Amt |
| cLos12Amount | `Float` | Central Los12 Amt |
| cLos13Amount | `Float` | Central Los13 Amt |
| cLos14Amount | `Float` | Central Los14 Amt |
| cLos2Amount | `Float` | Central Los2 Amt |
| cLos3Amount | `Float` | Central Los3 Amt |
| cLos4Amount | `Float` | Central Los4 Amt |
| cLos5Amount | `Float` | Central Los5 Amt |
| cLos6Amount | `Float` | Central Los6 Amt |
| cLos7Amount | `Float` | Central Los7 Amt |
| cLos8Amount | `Float` | Central Los8 Amt |
| cLos9Amount | `Float` | Central Los9 Amt |
| cMaximumAmount1 | `Float` | Central Maximum Amount 1 |
| cMaximumAmount2 | `Float` | Central Maximum Amount 2 |
| cMinimumAmount1 | `Float` | Central Minimum Amount 1 |
| cMinimumAmount2 | `Float` | Central Minimum Amount 2 |
| cOccupantsThresholdCharge | `Float` | Central Occupants Threshold Charge |
| cPackageRateStayOver | `Float` | Central Package Rate Stay Over |
| cRoomCost | `Float` | Central Room Cost |
| calculationFlag | `String` | Indicates Global rate update was (P)ercent or (F)lat |
| catPackagePriceCode | `String` | Stores the catering package price code for the package linked to the rate code in rate header. |
| centralMarketCode | `String` | Central Market Code |
| centralMarketDescription | `String` | Central Market Description |
| centralMarketGroupCode | `String` | Central Market Group Code |
| centralMarketGroupDescription | `String` | Central Market Group Description |
| centralPackageCode | `String` | Central Package Code |
| centralRoomType | `String` | Central Room Type |
| centralRoomTypeDescription | `String` | Central Room Type Description |
| centralSeasonCode | `String` | Central Season Code |
| centralSourceCode | `String` | Central Source Code |
| centralSourceDescription | `String` | Central Source Description |
| centralSourceGroupCode | `String` | Central Source Group Code |
| centralSourceGroupDescription | `String` | Central Source Group Description |
| childExcThreshold1 | `String` | Indicates whether the child 1 count will be excluded while calculating the total occupants threshold excess amount. |
| childExcThreshold2 | `String` | Indicates whether the child 2 count will be excluded while calculating the total occupants threshold excess amount. |
| childExcThreshold3 | `String` | Indicates whether the child 3 count will be excluded while calculating the total occupants threshold excess amount. |
| childOwnCharge1 | `Float` | Child Own Charge 1 |
| childOwnCharge2 | `Float` | Child Own Charge 2 |
| childOwnCharge3 | `Float` | Child Own Charge 3 |
| childOwnCharge4 | `Float` | Child Own Charge 4 |
| childrenFreeStay | `Float` | Number of children that will stay free. |
| childrenCharge | `Float` | Children Charge |
| childrenThreshold | `Float` | Threshold for number of children on a reservation. Additional charge will be added when reservation exceeds this threshold. |
| childrenThresholdCharge | `Float` | Amount used to calculate price for children when the number of children on the reservation exceed the children threshold. |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| deletedflag | `String` | Deleted Flag |
| depositRequieredYn | `String` | Deposit required Y/N |
| differenceAmount1 | `Float` | Contains a flat/percentage value for 1 Adult differential. |
| differenceAmount2 | `Float` | Contains a flat/percentage value for 2 Adult differential. |
| differenceAmount3 | `Float` | Contains a flat/percentage value for 3 Adult differential. |
| differenceAmount4 | `Float` | Contains a flat/percentage value for 4 Adult differential. |
| differenceAmount5 | `Float` | Contains a flat/percentage value for 5 Adult differential. |
| differenceAmountExtraAdult | `Float` | Contains a flat/percentage value for Extra Adult differential. |
| differencePercentage1Yn | `String` | Indicate if percentage value for 1 Adult differential should be used. |
| differencePercentage2Yn | `String` | Indicate if percentage value for 2 Adult differential should be used. |
| differencePercentage3Yn | `String` | Indicate if percentage value for 3 Adult differential should be used. |
| differencePercentage4Yn | `String` | Indicate if percentage value for 4 Adult differential should be used. |
| differencePercentage5Yn | `String` | Indicate if percentage value for 5 Adult differential should be used. |
| differencePercentageExtraAdultYn | `String` | Indicate if percentage value for Extra Adult differential should be used. |
| endDate | `Date` | End Date |
| externalRateSetId | `Float` | This field is required by OXI to store the external system rate_set_id to be used for locating the record in rate_set table during an update. |
| extraAdultType | `String` | Indicate the amount type for the Extra Adult. A [FLAT] or [DIFFERENTIAL] amount. |
| flatIncrease | `Float` | Flat Increase Amount |
| globalRateUpdateYn | `String` | Indicates if Rate set created by Global Rate Update |
| inactiveDate | `Date` | Inactive Date |
| inactiveflag | `String` | Inactive Flag |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| internalLocationId | `String` | Location ID |
| internalOrganizationId | `Float` | Organization ID |
| internalRatesetid | `Float` | Ratesetid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| lengthOfStay1Amount | `Float` | LOS1 amount for prevailing rate code. |
| lengthOfStay10Amount | `Float` | LOS10 amount for prevailing rate code. |
| lengthOfStay11Amount | `Float` | LOS11 amount for prevailing rate code. |
| lengthOfStay12Amount | `Float` | LOS12 amount for prevailing rate code. |
| lengthOfStay13Amount | `Float` | LOS13 amount for prevailing rate code. |
| lengthOfStay14Amount | `Float` | LOS14 amount for prevailing rate code. |
| lengthOfStay2Amount | `Float` | LOS2 amount for prevailing rate code. |
| lengthOfStay3Amount | `Float` | LOS3 amount for prevailing rate code. |
| lengthOfStay4Amount | `Float` | LOS4 amount for prevailing rate code. |
| lengthOfStay5Amount | `Float` | LOS5 amount for prevailing rate code. |
| lengthOfStay6Amount | `Float` | LOS6 amount for prevailing rate code. |
| lengthOfStay7Amount | `Float` | LOS7 amount for prevailing rate code. |
| lengthOfStay8Amount | `Float` | LOS8 amount for prevailing rate code. |
| lengthOfStay9Amount | `Float` | LOS9 amount for prevailing rate code. |
| linkRateSetId | `Float` | Rate set id of the base rates rate set. |
| locationID | `String` | Internal ID to uniquely identify the Property |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| marketGroupCode | `String` | Market Group Code |
| marketGroupDescription | `String` | Market Group Description |
| maximumAmount1 | `Float` | Maximum rate amount value for 1 adult. |
| maximumAmount2 | `Float` | Maximum rate amount value for 2 adults. |
| minChildrenForFreeStay | `Float` | Represents every x number of children to get free "num_children_stay_free" |
| minimumAmount1 | `Float` | Minimum rate amount value for 1 adult. |
| minimumAmount2 | `Float` | Minimum rate amount value for 2 adults. |
| minimumClosingProbability | `Float` | Not used |
| occupantsThreshold | `Float` | Threshold for number of occupants on a reservation. Additional charge will be added when reservation exceeds this threshold. |
| occupantsThresholdCharge | `Float` | Amount used to calculate price for occupants when the number of occupants on the reservation exceed the occupant threshold. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| packageAdultStayOver | `Float` | The amount to charge per extra adult on every additional day of stay for a package that extends beyo |
| packageChildrenStayOver | `Float` | The amount to charge per extra child on every additional day of stay for a package that extends beyo |
| packageCode | `String` | Package Code |
| packageRateStayOver | `Float` | The amount to charge extra on every additional day of stay for a package that extends beyond the inc |
| percentIncrease | `Float` | Not used |
| pointsRequired | `Float` | Points Required |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| rateAvailableOnFridaysYN | `String` | Rate Available on Fridays YN |
| rateAvailableOnMondaysYN | `String` | Rate Available on Mondays YN |
| rateAvailableOnSaturdaysYN | `String` | Rate Available on Saturdays YN |
| rateAvailableOnSundaysYN | `String` | Rate Available on Sundays YN |
| rateAvailableOnThursdaysYN | `String` | Rate Available on Thursdays YN |
| rateAvailableOnTuesdaysYN | `String` | Rate Available on Tuesdays YN |
| rateAvailableOnWednesdaysYN | `String` | Rate Available on Wednesdays YN |
| rateCode | `String` | Rate Code |
| rateCodeDesc | `String` | Event Reservation Rate Code Description |
| rateCodeId | `String` | Rate Code ID |
| rateRule | `String` | Rate Rule |
| rateSetId | `Float` | Rate Set ID |
| rateForChildInAgeBucket1 | `Float` | Child charge for defined rate bucket 1. |
| rateForChildInAgeBucket2 | `Float` | Child charge for defined rate bucket 2. |
| rateForChildInAgeBucket3 | `Float` | Child charge for defined rate bucket 3. |
| ratesActiveYn | `String` | Indicates if the rate amounts are activated. |
| ratetierid | `Float` | Ratetierid |
| repSeasonDescription | `String` | Reporting Season Desc |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomCost | `Float` | Room Cost |
| roomType | `String` | Room Type |
| roomTypeDescription | `String` | Room Type Description |
| roundToNearest | `Float` | Type of rounding after rate_update |
| season | `String` | Season |
| seasonCode | `String` | Season Code |
| seasonDesc | `String` | User defined description for season. |
| sourceCode | `String` | Source Code |
| sourceDescription | `String` | Source Description |
| sourceGroupCode | `String` | Source Group Code |
| sourceGroupDescription | `String` | Source Group Description |
| startDate | `Date` | Start Date |
| tierId | `Float` | Tier ID for the Rate Detail. |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedRoutingInstructionDetailsType

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

### BookingReservationExtendedFolioTaxDetailsType

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

### BookingReservationExtendedFinancialUnifiedDetailsType

| Field | Type | Description |
| --- | --- | --- |
| aRChargeTransferFlagYN | `String` | AR Charge Transfer YN |
| aRLedgerCredit | `Float` | AR Ledger Credit |
| aRLedgerDebit | `Float` | AR Ledger Debit |
| aRState | `String` | AR State |
| aRTransferDate | `Date` | AR Transfer Date |
| accountCode | `Float` | Account Code |
| accountNumber | `String` | Account Number |
| addressId | `Float` | Address ID |
| advanceBillReversedYN | `String` | Identifies if this Advance Bill has been reversed. |
| advanceBillYn | `String` | Identifies if this transaction was generated by Advance Bill. |
| advancedGenerateYN | `String` | The charge / generate is eligible as part of advanced generates functionality. |
| advgenTtransCodeID | `String` | Advgen Ttrans Code ID |
| arrangementCode | `String` | Arrangement Code |
| arrangementDesc | `String` | Arrangement Description for the Transaction Code. |
| articleId | `Float` | Article ID |
| associatedTrxNumber | `Float` | Indicates the associated transaction number for a particular receipt type. |
| attachedToUser | `String` | Application User Name |
| authEmployeeID | `Float` | Auth Employee ID |
| authorizer | `String` | Authorizer |
| autoCreditbillYn | `String` | Indicates if this column was automatically created for Automatic Credit Bills. |
| autoSettleYn | `String` | Auto Settle Y/N |
| businessDate | `Date` | Business Date |
| cCApproval | `String` | CC Approval Code |
| cashierCode | `Float` | Cashier Code |
| cashierCredit | `Float` | Cashier Credit |
| cashierDebit | `Float` | Cashier Debit |
| cashierID | `Float` | Cashier ID |
| cashierName | `String` | Cashier Name |
| cashierOpeningBalance | `Float` | Cashier Opening Balance |
| ccRefundPosting | `String` | Identifies if this record was the result of a credit card refund possible values: REFUND or OVERRIDE.OVERRIDE means a user authorized a refund amount larger than the original cc charge. |
| changesLogCheckIn | `String` | Changes Log Check In |
| changesLogCheckOut | `String` | Changes Log Check Out |
| changesLogCloseFolio | `String` | Changes Log Close Folio |
| changesLogReopenFolio | `String` | Changes Log Reopen Folio |
| changesLogUpdateReservation | `String` | Changes Log Update Reservation |
| checkNumber | `String` | Check Number |
| closureNumber | `Float` | Closure Number |
| comments | `String` | Comments |
| compLinkTrxCode | `String` | Trx code of original transaction that was turned into a comp |
| compLinkTrxNumber | `Float` | Trx no of original transaction that was turned into a comp |
| compTypeCode | `String` | Comp Type Code |
| compressedYn | `String` | Compressed Y/N |
| covers | `String` | Covers |
| creditCardId | `Float` | Credit Card ID |
| creditCardSurcharge | `Float` | Fee (surcharge) amount for a credit card transaction. |
| creditYN | `String` | Credit YN |
| currencyCode | `String` | Currency Code |
| currencyDescription | `String` | Currency Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| debitYN | `String` | Debit YN |
| decimals | `Float` | Decimals |
| deferredYn | `String` | Deferred Y/N |
| depPostingFlag | `String` | Indicates if the posting is a deposit posting as part of the Guest Ledger Deposits functionality. Also indicates if the charge has been offset after checkin. Possible values [PRX] |
| depTaxTransferedYn | `String` | Indicates if this row is a deposit tax which has been transfered. |
| depositLedgerCredit | `Float` | Deposit Ledger Credit |
| depositLedgerDebit | `Float` | Deposit Ledger Debit |
| depositTransactionId | `String` | Deposit Transaction ID |
| displayYN | `String` | Display YN |
| euroExchangeRate | `Float` | Euro Exchange Rate |
| exchangeDate | `Date` | Exchange Date |
| exchangeDifferenceYN | `String` | Exchange Difference YN |
| exchangeRate | `Float` | Exchange Rate |
| exchangeType | `String` | Type of currency exchange conducted.  Possible values: [E]xchange [S]ettlement [C]ommission [M]embership [EC] Exchange Check [P]osting. |
| financialDmlSeqNumber | `Float` | Number to identify the DML sequence. |
| fiscalBillNo | `String` | Fiscal Bill Number |
| fixedChargesYN | `String` | Fixed Charges YN |
| folio | `Float` | Folio |
| folioNo | `Float` | Folio Number |
| folioType | `String` | Folio Type |
| folioView | `Float` | Folio View |
| foreignCurrencyCode | `String` | Foreign Currency Code |
| fromReservationId | `Float` | From Resv ID |
| ftGeneratedType | `String` | Column has become unused after the chage of business rules down the line. |
| ftSubtype | `String` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| genCashierId | `Float` | General Cashier Id. |
| generalCashierYN | `String` | Determines whether the cashier is a General cashier. |
| grossAmount | `Float` | Gross Amount |
| guestAccountLedgerCredit | `Float` | Guest Account Ledger Credit |
| guestAccountLedgerDebit | `Float` | Debit amount on the guest account |
| inHouseCredit | `Float` | In-House Credit |
| inHouseDebit | `Float` | In-House Debit |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| insertUserName | `String` | The name of the user who created the record. |
| interfaceCashierYN | `String` | Decides whether the cashier number is used in interfaces or not. The interface cashiers cannot have numbers more than 999. |
| internalArticleid | `Float` | Articleid |
| internalWindowId | `Float` | Internal Window ID |
| internalYN | `String` | Internal YN |
| invoiceCloseDate | `Date` | Invoice Close Date |
| invoiceNumber | `Float` | Invoice Number |
| invoiceType | `String` | Invoice Type |
| linkTrxNumber | `Float` | Link Transaction No |
| marketCode | `String` | Market Code |
| marketDescription | `String` | Market Description |
| membershipID | `Float` | Membership ID |
| mtrxNoAgainstPackage | `Float` | Sequence number generated automatically when packages are posted during manual room and tax. |
| nameTaxType | `String` | Name Tax Type |
| netAmount | `Float` | Net Amount |
| nonRevenueAmount | `Float` | Non Revenue Amount |
| numberDialed | `String` | Number Dialed. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalARLedgerDebit | `Float` | Stores the original AR ledger debit amount for Direct Bill transactions. |
| originalBillNumber | `Float` | Stores original bill number after void. |
| originalFolioNumber | `String` | Stores original folio type after void. |
| originalReservationNameId | `Float` | Original Resv Name ID |
| originalRoom | `String` | Original Room |
| package | `String` | Package |
| packageAllowance | `Float` | Package Allowance amount of a package that has an allowance. |
| packageArrangementCode | `String` | Arrangement code from the package associated to this transaction. |
| packageLedgerCredit | `Float` | Credit amount on the guest package account. |
| packageLedgerDebit | `Float` | Debit amount on the guest package account |
| packageTrxType | `String` | Identifies the type of a package posting. Possible values are: PKG_WRAPPER INCLTAX_PKG_ROOM EXCLTAX_PKG_ROOM INCLTAX_PKG_WITH_ALLOWANCE EXCLTAX_PKG_WITH_ALLOWANCE INCLTAX_PKG_WITHOUT_ALLOWANCE EXCLTAX_PKG_WITHOUT_ALLOWANCE |
| passerByName | `String` | Passerby Name. |
| payeeNameID | `Float` | Name Id to which it should be routed. |
| payeeResvNameID | `Float` | Payee Resv Name ID |
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
| profileID | `Float` | Profile ID |
| profitLossFlag | `String` | Populated with [P] for package profit and [L] for package loss transactions. |
| proformaYN | `String` | Proforma Y/N |
| property | `String` | Property |
| quantity | `Float` | Quantity |
| queueName | `String` | Queue Name |
| rateCode | `String` | Rate Code |
| receiptNumber | `Float` | Receipt Number |
| receiptType | `String` | Indicates the receipt type. Different receipts are identified by different types |
| repTransactionCode | `String` | Reporting Trx Code |
| repTransactionCodeGroup | `String` | Reporting Tc Group |
| repTransactionCodeGroupDescription | `String` | Reporting Tc Group Desc |
| repTransactionCodeSubgroup | `String` | Reporting Tc Subgroup |
| repTransactionCodeSubgroupDescription | `String` | Reporting Tc Subgroup Desc |
| reservationDepositId | `Float` | Stores Reservation_deposit_schedule_id from RESERVATION_DEPOSIT_SCHEDULE table  to link the deposit payment to the deposit request. |
| reservationNameID | `Float` | Reservation Name ID |
| revenueAmount | `Float` | Revenue Amount. |
| reversePaymentTrxNumber | `Float` | Stores the trx_no of the reversed payment. |
| roomClass | `String` | Room Class |
| roomNts | `Float` | Room Nts |
| roomNtsEffective | `Float` | Stores the effective room nights with decimals making it significant for postings splits edits and adjustments. Required by B&B Hotels. |
| roomNumber | `String` | Room Number |
| roundFactorYn | `String` | Round Factor Y/N |
| roundLinkTrxno | `Float` | TRX_NO of the transaction associated with this rounding factor posting. |
| routedYn | `String` | Indicates if the transaction has been routed. |
| routingCode | `String` | Routing Code |
| routingCodeDescription | `String` | Routing Code Description |
| routingDate | `Date` | Routing date for comp routings - populated only if routed transaction has trx date less than business date. |
| routingIinstructionID | `Float` | Routing Iinstruction ID |
| routingInstrnId | `Float` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| routingType | `String` | To specify whether it is a package routing or not |
| settlementFlag | `String` | Settlement Flag |
| sourceCode | `String` | Source Code |
| sourceDescription | `String` | Source Description |
| supplement | `String` | Supplement |
| tRXCode | `String` | Transaction Code |
| targetResort | `String` | Target Property |
| taxDeferredUntilCheckOutYN | `String` | Tax Deferred Until Check-Out YN |
| taxElements | `String` | Tax Elements |
| taxGeneratedYN | `String` | Tax Generated YN |
| taxInclusiveYN | `String` | Tax Inclusive YN |
| tcGroup | `String` | Transaction Code Group |
| tcSubgroup | `String` | Transaction Code Subgroup |
| thresholdDiversionId | `Float` | Threshold Diversion ID |
| thresholdEntityQty | `Float` | Stores the corresponding quantity of the threshold for QUANTITY and MINUTES types. |
| thresholdEntityType | `String` | Threshold Entity Type |
| thresholdTreatmentFlag | `String` | Flag to identify how the posting was treated.[THRESHOLD_ALLOWED] --> OPERA treated this of ?Allowed? type at the time of posting.[THRESHOLD_REQUIRED] --> OPERA treated this of ?Required? type at the time of posting.[null / blank] --> not a diversion related transaction. |
| toReservationNameId | `Float` | To Resv Name ID |
| tranActionId | `Float` | Tran Action ID |
| transCodeArrangementID | `Float` | Trans Code Arrangement ID |
| transactionActivityDate | `Date` | Transaction Activity Date |
| transactionCodeDescription | `String` | Transaction Code Description |
| transactionCodeGroupDesc | `String` | Tc Group Description |
| transactionCodeSubgroupDesc | `String` | Tc Subgroup Description |
| transactionDate | `Date` | Transaction Date |
| transactionNumberAddedBy | `Float` | Transaction Number Added By |
| transactionPostingDate | `Date` | Transaction Posting Date |
| transactionPostingTime | `String` | Time transaction was posted. |
| transactionPostingTimeWithSeconds | `String` | Time transaction was posted with seconds. |
| transactionType | `String` | Transaction Type |
| transactionFromAccount | `Float` | Transaction from Account |
| transactionToAccount | `Float` | Transaction to Account |
| transferFromAccountID | `Float` | Transfer from Account ID |
| transferToAccountID | `Float` | Transfer to Account ID |
| trxNo | `Float` | Trx Number |
| trxNoAgainstPackage | `Float` | Trx Number Against Package |
| trxNumberAdjust | `Float` | The trx_no against which this transaction gets adjusted. |
| trxNumberHeader | `Float` | Transaction No Header |
| trxNumberSplit | `Float` | Stores the Trx_No of the main transaction being split. |
| trxServiceType | `String` | Transaction Service Type |
| updateDate | `DateTime` | Update Date |
| updateUser | `Float` | Update User |
| vatAmount | `Float` | Tax Amount for Commission. |

[⬆ Back to Query](#query)

---

### BookingReservationExtendedPropertyPropertyDetailsType

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

### BookingReservationExtendedRoomDetailsType

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

### BookingReservationExtendedFixedChargesDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountCode | `Float` | Account Code |
| accountid | `Float` | Accountid |
| amountOrPercentage | `Float` | Amount or Percentage |
| amountOrPercentageFlag | `String` | Percentage / Amount flag. Allowed values: AMOUNT PERCENT. |
| articleId | `Float` | Article ID |
| beginDateNullable | `Date` | The date from which the charge is effective (null allowed). |
| businessDate | `Date` | Business Date |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cPrice | `Float` | Central Price |
| centralTransactionCode | `String` | Central Transaction Code |
| centralTransactionCodeDescription | `String` | Central Transaction Code Description |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| daytoexecute | `String` | Daytoexecute |
| deletedFlag | `String` | Deleted Flag |
| endDate | `Date` | End Date |
| endDateNullable | `Date` | The date from which the charge is not effective (null allowed). |
| fixedChargesId | `Float` | Unique number to identify the entry. |
| fixedchargespmsref | `Float` | Fixedchargespmsref |
| frequency | `String` | Frequency |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| insertUserName | `String` | The name of the user who created the record. |
| internalArticleid | `Float` | Articleid |
| internalFixedchargesid | `Float` | Fixedchargesid |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| locationID | `String` | Internal ID to uniquely identify the Property |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| percentage | `Float` | Percentage |
| price | `Float` | Price |
| primaryKeyID | `Float` | Internal Primary Key ID to uniquely identify the row |
| property | `String` | Code to uniquely identify the Property |
| quantity | `Float` | Quantity |
| rNAInsertDate | `DateTime` | RNA Insert Date |
| rNAUpdateDate | `DateTime` | RNA Update Date |
| reservationNameId | `Float` | Resv Name ID |
| reservationid | `Float` | Reservationid |
| resvenddate | `Date` | Resvenddate |
| roomnights | `Float` | Roomnights |
| supplement | `String` | Supplement |
| transactionCode | `String` | Rate transaction code |
| transactionCodeDescription | `String` | Transaction Code Description |
| transactionCodeGroup | `Float` | Transaction Code Group |
| transactionCodeSubGroup | `Float` | Transaction Code Sub-Group |
| transactionCodeType | `String` | Transaction Code Type |
| transcodeid | `String` | Transcodeid |
| updateUser | `Float` | Update User |
| updatedate | `Date` | Update Date |
| yearlyfixedchargedate | `Date` | Yearlyfixedchargedate |

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

### BookingReservationExtendedQueryArgumentsType

| Field | Type | Description |
| --- | --- | --- |
| reservationunifiedDetailsResvActualCheckInTime | `StringInput` | Actual Check In Date Time<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvActualCheckOutTime | `StringInput` | Actual Check Out Date Time<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvActualCheckOutDate | `DateInput` | Actual Check-Out Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvAddresseeNameId | `FloatInput` | Addressee Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsAgentNameId | `FloatInput` | Agent Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvAllotmentid | `FloatInput` | Block ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvTruncBeginDate | `DateTimeInput` | Arrival Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvBillingContactId | `FloatInput` | Billing Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvBillingcontactprofileid | `FloatInput` | Billing Contact Profile ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsAllotmentCode | `StringInput` | Block Code |
| reservationunifiedDetailsResvAllotmentHeaderId | `StringInput` | Block ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsOwnerCode | `StringInput` | Block Owner Code |
| reservationunifiedDetailsResvBonusCheckId | `FloatInput` | Bonus Check ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvBusinessDateCreated | `DateInput` | Business Date Created<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvCancellationDate | `DateTimeInput` | Cancellation Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvCancellationNo | `StringInput` | Cancellation Number<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsCompanyNameId | `FloatInput` | Company Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvConfirmationNo | `StringInput` | Shared Confirmation Number<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsContactNameId | `FloatInput` | Contact Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsInsertDate | `DateInput` | Created Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvCustomReference | `StringInput` | Custom Reference Number |
| reservationunifiedDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| reservationunifiedDetailsResvTruncEndDate | `DateInput` | Departure Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsEndDate | `DateInput` | End Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvEndbusinessdate | `DateInput` | Endbusinessdate<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvEventId | `FloatInput` | Event ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsBlocksExtAllotmentId | `StringInput` | Ext Allotment ID |
| reservationunifiedDetailsResvFolioCloseDate | `DateInput` | Date the folio was changed to closed.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvGuaranteecodeid | `StringInput` | Guaranteecodeid |
| reservationunifiedDetailsResvGuestprofileid | `FloatInput` | Guestprofileid<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvInsertActionInstanceId | `FloatInput` | Insert Action Instance ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsInsertUser | `FloatInput` | Insert User<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsBlocksInterfaceId | `StringInput` | This is the Interface_id of the System which sent/Received Allotment |
| reservationunifiedDetailsResvAwardMembershipId | `FloatInput` | Award Membership ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvEndDate | `DateInput` | Linked Departure Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsSuperBlockId | `FloatInput` | Parent Block ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsSuperBlockResort | `StringInput` | Parent Resort |
| reservationunifiedDetailsMasterNameId | `FloatInput` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvNameUsageType | `StringInput` | Name Usage Type |
| reservationunifiedDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| reservationunifiedDetailsResvOriginalEndDate | `DateInput` | Original End Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsOwner | `FloatInput` | Owner<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvParentResvNameId | `FloatInput` | Parent Resv Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvParentreservationid | `FloatInput` | Parentreservationid<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvQuoteId | `StringInput` | Quote ID provided by external system.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvResvContactId | `FloatInput` | Resv Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvNameId | `FloatInput` | Reservation Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvResvStatus | `StringInput` | Reservation Status |
| reservationunifiedDetailsResvGuaranteeCode | `StringInput` | Reservation Type |
| reservationunifiedDetailsResort | `StringInput` | Property<br>`@conditionalInputPair(pair: 1)` |
| reservationunifiedDetailsResvResortChargeNumber | `StringInput` | Auto generated charge number for Point Of Sale systems to identify guests. |
| reservationunifiedDetailsResvResvcontactprofileid | `FloatInput` | Resvcontactprofileid<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvRhBillingContactId | `FloatInput` | Rh Billing Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvRhResvContactId | `FloatInput` | Rh Resv Contact ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvRoomcategoryid | `StringInput` | Roomcategoryid |
| reservationunifiedDetailsResvSchedulecheckoutYn | `StringInput` | Is the guest scheduled for automatic check out? |
| reservationunifiedDetailsResvSguestFirstname | `StringInput` | Sguest First Name |
| reservationunifiedDetailsResvSguestName | `StringInput` | Sguest Name |
| reservationunifiedDetailsResvNameNameId | `FloatInput` | Shared Profile ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvReservationStatus | `StringInput` | Shared Reservation Status |
| reservationunifiedDetailsShoulderEndDate | `DateInput` | Shoulder End<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsShoulderBeginDate | `DateInput` | Shoulder Start<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsSourceNameId | `FloatInput` | Source Name ID<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvSplitFromResvNameId | `FloatInput` | Stores resv_name_id of the original multi room reservation from which this reservation is split off.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvSplitfromreservationid | `FloatInput` | Splitfromreservationid<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsBeginDate | `DateInput` | Start Date<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvTruncActualCheckOutDate | `DateInput` | This is the actual check out date with no time component.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsResvUniCardId | `StringInput` | Universal Card ID used by interfaces for key encoding purposes.<br>`@conditionalInputPair(pair: 2)` |
| reservationunifiedDetailsUpdateDate | `DateInput` | Updated Date<br>`@conditionalInputPair(pair: 2)` |
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
| profileaccountssourceDetailsProfileId | `FloatInput` | Account ID |
| profileaccountssourceDetailsActiveYn | `StringInput` | Active Flag |
| profileaccountssourceDetailsChainCode | `StringInput` | Chain Code |
| profileaccountssourceDetailsCompany | `StringInput` | Company |
| profileaccountssourceDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaccountssourceDetailsHistoryYn | `StringInput` | History Y/N |
| profileaccountssourceDetailsNameCode | `StringInput` | IATA Number |
| profileaccountssourceDetailsInactiveDate | `DateInput` | Inactive Date |
| profileaccountssourceDetailsOrganizationId | `FloatInput` | Organization ID |
| profileaccountssourceDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileaccountssourceDetailsLast | `StringInput` | Last |
| profileaccountssourceDetailsNameId | `FloatInput` | Name ID |
| profileaccountssourceDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaccountssourceDetailsProfileType | `StringInput` | Profile Type |
| profileaccountssourceDetailsNameType | `StringInput` | Profile Type Code |
| profileaccountssourceDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileaccountssourceDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileaccountssourceDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileaccountssourceDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileaccountssourceDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileaccountssourceDetailsUpdateDate | `DateTimeInput` | Update Date |
| profileaccountstravelagentDetailsProfileId | `FloatInput` | Account ID |
| profileaccountstravelagentDetailsActiveYn | `StringInput` | Active Flag |
| profileaccountstravelagentDetailsChainCode | `StringInput` | Chain Code |
| profileaccountstravelagentDetailsCompany | `StringInput` | Company |
| profileaccountstravelagentDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaccountstravelagentDetailsHistoryYn | `StringInput` | History Y/N |
| profileaccountstravelagentDetailsNameCode | `StringInput` | IATA Number |
| profileaccountstravelagentDetailsInactiveDate | `DateInput` | Inactive Date |
| profileaccountstravelagentDetailsOrganizationId | `FloatInput` | Organization ID |
| profileaccountstravelagentDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileaccountstravelagentDetailsLast | `StringInput` | Last |
| profileaccountstravelagentDetailsNameId | `FloatInput` | Name ID |
| profileaccountstravelagentDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaccountstravelagentDetailsProfileType | `StringInput` | Profile Type |
| profileaccountstravelagentDetailsNameType | `StringInput` | Profile Type Code |
| profileaccountstravelagentDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileaccountstravelagentDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileaccountstravelagentDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileaccountstravelagentDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileaccountstravelagentDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileaccountstravelagentDetailsUpdateDate | `DateTimeInput` | Update Date |
| externalreferencesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| externalreferencesDetailsExternalReference | `StringInput` | External Reference Number |
| externalreferencesDetailsExternalReferenceType | `StringInput` | Type of external reference depending from what external system the number was passed. |
| externalreferencesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| externalreferencesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| externalreferencesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| externalreferencesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| externalreferencesDetailsResvNameId | `FloatInput` | Resv Name ID |
| externalreferencesDetailsUpperExternalReference | `StringInput` | External reference stored in upper case. |
| resvmembershipDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvpaymentmethodsDetailsBonusCheckId | `FloatInput` | Bonus Check ID |
| resvpaymentmethodsDetailsCreditCardId | `FloatInput` | Credit Card ID |
| resvpaymentmethodsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvpaymentmethodsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvpaymentmethodsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvpaymentmethodsDetailsFolioView | `FloatInput` | Payment Window |
| resvpaymentmethodsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resvpaymentmethodsDetailsResvNameId | `FloatInput` | Resv Name ID |
| profileaccountsDetailsProfileId | `FloatInput` | Account ID |
| profileaccountsDetailsActiveYn | `StringInput` | Active Flag |
| profileaccountsDetailsChainCode | `StringInput` | Chain Code |
| profileaccountsDetailsCompany | `StringInput` | Company |
| profileaccountsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| profileaccountsDetailsHistoryYn | `StringInput` | History Y/N |
| profileaccountsDetailsNameCode | `StringInput` | IATA Number |
| profileaccountsDetailsInactiveDate | `DateTimeInput` | Inactive Date |
| profileaccountsDetailsOrganizationId | `FloatInput` | Organization ID |
| profileaccountsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| profileaccountsDetailsLast | `StringInput` | Last |
| profileaccountsDetailsNameId | `FloatInput` | Name ID |
| profileaccountsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| profileaccountsDetailsProfileType | `StringInput` | Profile Type |
| profileaccountsDetailsNameType | `StringInput` | Profile Type Code |
| profileaccountsDetailsResortRegistered | `StringInput` | Resort for which Job is registered. |
| profileaccountsDetailsSname | `StringInput` | The Uppercase value of Last or Company. |
| profileaccountsDetailsSfirst | `StringInput` | Uppercase value of First Name. |
| profileaccountsDetailsSxfirstName | `StringInput` | Internal Indexed field for Searching by Extended Byte First Name. |
| profileaccountsDetailsSxname | `StringInput` | Internal Indexed field for Searching by Extended Byte Name. |
| profileaccountsDetailsUpdateDate | `DateTimeInput` | Update Date |
| resvdepositscheduleDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| resvdepositscheduleDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| resvdepositscheduleDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| resvdepositscheduleDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| resvdepositscheduleDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| resvdepositscheduleDetailsResort | `StringInput` | Code to uniquely identify the Property |
| resvdepositscheduleDetailsResvDepositScheduleId | `FloatInput` | Resv Deposit Schedule ID |
| ratecodedetailsDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| ratecodedetailsDetailsEndDate | `DateInput` | End Date |
| ratecodedetailsDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| ratecodedetailsDetailsLinkRateSetId | `FloatInput` | Rate set id of the base rates rate set. |
| ratecodedetailsDetailsMarketCode | `StringInput` | Market Code |
| ratecodedetailsDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| ratecodedetailsDetailsResort | `StringInput` | Code to uniquely identify the Property |
| ratecodedetailsDetailsRateCode | `StringInput` | Rate Code |
| ratecodedetailsDetailsRateSetId | `FloatInput` | Rate Set ID |
| ratecodedetailsDetailsSeasonCode | `StringInput` | Season Code |
| ratecodedetailsDetailsSourceCode | `StringInput` | Source Code |
| ratecodedetailsDetailsBeginDate | `DateInput` | Start Date |
| ratecodedetailsDetailsTierId | `FloatInput` | Tier ID for the Rate Detail. |
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
| financialunifiedDetailsFtArLedCredit | `FloatInput` | AR Ledger Credit |
| financialunifiedDetailsFtArLedDebit | `FloatInput` | AR Ledger Debit |
| financialunifiedDetailsFtArState | `StringInput` | AR State |
| financialunifiedDetailsFtArNumber | `FloatInput` | Account Code |
| financialunifiedDetailsFtArticleId | `FloatInput` | Article ID |
| financialunifiedDetailsFtBusinessDate | `DateInput` | Business Date |
| financialunifiedDetailsFtCashierId | `FloatInput` | Cashier ID |
| financialunifiedDetailsFtChequeNumber | `StringInput` | Check Number |
| financialunifiedDetailsFtClosureNo | `FloatInput` | Closure Number |
| financialunifiedDetailsFtCompLinkTrxCode | `StringInput` | Trx code of original transaction that was turned into a comp |
| financialunifiedDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| financialunifiedDetailsFtFinDmlSeqNo | `FloatInput` | Number to identify the DML sequence. |
| financialunifiedDetailsFtBillNo | `FloatInput` | Folio Number |
| financialunifiedDetailsFtFolioView | `FloatInput` | Folio View |
| financialunifiedDetailsFromResvId | `FloatInput` | From Resv ID |
| financialunifiedDetailsFtFtSubtype | `StringInput` | This is the transaction type which says whether it is a Consumption(C) Payment (FC) or Package (PK)  and it is inherited from transaction code. |
| financialunifiedDetailsFtGuestAccountCredit | `FloatInput` | Guest Account Ledger Credit |
| financialunifiedDetailsFtGuestAccountDebit | `FloatInput` | Debit amount on the guest account |
| financialunifiedDetailsFtInsertDate | `DateTimeInput` | Insert Date |
| financialunifiedDetailsFtFolioNo | `FloatInput` | Internal Window ID |
| financialunifiedDetailsFtInvoiceNo | `FloatInput` | Invoice Number |
| financialunifiedDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| financialunifiedDetailsFtOriginalResvNameId | `FloatInput` | Original Resv Name ID |
| financialunifiedDetailsFtOriginalRoom | `StringInput` | Original Room |
| financialunifiedDetailsFtProduct | `StringInput` | Package |
| financialunifiedDetailsFtPackageCredit | `FloatInput` | Credit amount on the guest package account. |
| financialunifiedDetailsFtPackageDebit | `FloatInput` | Debit amount on the guest package account |
| financialunifiedDetailsFtPostitNo | `FloatInput` | Postit Number |
| financialunifiedDetailsFtProfileid | `FloatInput` | Profile ID |
| financialunifiedDetailsResort | `StringInput` | Property |
| financialunifiedDetailsFtRateCode | `StringInput` | Rate Code |
| financialunifiedDetailsFtRecptType | `StringInput` | Indicates the receipt type. Different receipts are identified by different types |
| financialunifiedDetailsResvNameId | `FloatInput` | Reservation Name ID |
| financialunifiedDetailsFtRoom | `StringInput` | Room Number |
| financialunifiedDetailsFtRoundLinkTrxno | `FloatInput` | TRX_NO of the transaction associated with this rounding factor posting. |
| financialunifiedDetailsFtRoutingInstrnId | `FloatInput` | Link the posting to the routing instruction that is specified during the setup of routing instructions for guests. |
| financialunifiedDetailsFtTaxElements | `StringInput` | Tax Elements |
| financialunifiedDetailsFtTcGroup | `StringInput` | Transaction Code Group |
| financialunifiedDetailsFtTcSubgroup | `StringInput` | Transaction Code Subgroup |
| financialunifiedDetailsFtTranActionId | `FloatInput` | Tran Action ID |
| financialunifiedDetailsFtTrxDate | `DateInput` | Transaction Date |
| financialunifiedDetailsFtTrxNoAddedBy | `FloatInput` | Transaction Number Added By |
| financialunifiedDetailsFtTrxNo | `FloatInput` | Trx Number |
| financialunifiedDetailsFtTrxNoAgainstPackage | `FloatInput` | Trx Number Against Package |
| financialunifiedDetailsFtTrxNoAdjust | `FloatInput` | The trx_no against which this transaction gets adjusted. |
| financialunifiedDetailsFtTrxNoHeader | `FloatInput` | Transaction No Header |
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
| roomDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| roomDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| roomDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| roomDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| roomDetailsResort | `StringInput` | Code to uniquely identify the Property |
| roomDetailsRoompmsref | `StringInput` | Room |
| roomDetailsRoom | `StringInput` | Room Number |
| roomDetailsRoomid | `StringInput` | Roomid |
| fixedchargesDetailsAccountCode | `FloatInput` | Account Code |
| fixedchargesDetailsAccountid | `FloatInput` | Accountid |
| fixedchargesDetailsFixedchargestartdate | `DateInput` | Business Date |
| fixedchargesDetailsCXchangeDate | `DateInput` | Central Xchange Date |
| fixedchargesDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |
| fixedchargesDetailsFixedchargeenddate | `DateInput` | End Date |
| fixedchargesDetailsFixedChargesId | `FloatInput` | Unique number to identify the entry. |
| fixedchargesDetailsFixedchargespmsref | `FloatInput` | Fixedchargespmsref |
| fixedchargesDetailsFixedchargesid | `FloatInput` | Fixedchargesid |
| fixedchargesDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |
| fixedchargesDetailsLocationid | `StringInput` | Internal ID to uniquely identify the Property |
| fixedchargesDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |
| fixedchargesDetailsResort | `StringInput` | Code to uniquely identify the Property |
| fixedchargesDetailsResvNameId | `FloatInput` | Resv Name ID |
| fixedchargesDetailsReservationid | `FloatInput` | Reservationid |
| fixedchargesDetailsTransactionCode | `StringInput` | Rate transaction code |
| fixedchargesDetailsTranscodeid | `StringInput` | Transcodeid |

[⬆ Back to Query](#query)

---

## Query Template
```graphql
query bookingReservationExtended($input: BookingReservationExtendedQueryArgumentsType!) {
  bookingReservationExtended(input: $input) @stream {
    reservationUnifiedDetails {
      aSBProratedYn
      actionId
      actualCheckInDateTime
      actualCheckOutDateTime
      actualCheckInDate
      actualCheckOutDate
      addressId
      addresseeNameId
      adults
      adultsTaxFree
      advanceCheckedInYn
      agencyprofileid
      agentNameId
      allAliases
      allBlockOwners
      allCateringOwners
      allCompanyContacts
      allRateCodes
      allRoomOwners
      allRoomTypes
      allSourceContacts
      allTravelAgentContacts
      allotmentOrigin
      allotmentRecordType
      allotmentType
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
      authorizedBy
      authorizerId
      autoCheckinYn
      autoSettleDays
      autoSettleYN
      averageRate
      awardCode
      awardCode1
      awardCode2
      awardCode3
      awardCode4
      awardCode5
      awardVoucher1
      awardVoucher2
      awardVoucher3
      awardVoucher4
      awardVoucher5
      awdUpgrFrom
      awdUpgrTo
      baseRateAmount
      baseRateCode
      baseRateCurrencyCode
      baseratecurrencyid
      beginDatetime
      beginSystemDateTime
      billingContactId
      billingcontactprofileid
      blockAlias
      blockCode
      blockDescription
      blockDmlSeqNumber
      blockEndbusinessdate
      blockExchangePostingType
      blockExchangeRate
      blockExternalReference
      blockID
      blockOwnerCode
      blockResort
      blockStatus
      blockStatusDescription
      blocksExternalReference
      bonusCheckId
      bookedRoomCategory
      bookedroomcategoryid
      businessDateCreated
      cancelDate
      cancelReason
      cancelTime
      cancellationDate
      cancellationNumber
      cancellationReasonDescription
      cancellationreasonid
      centralApprovalAmount
      changesLogCheckIn
      changesLogCheckOut
      changesLogCloseFolio
      changesLogReopenFolio
      changesLogUpdateReservation
      checkinDuration
      childBucket1
      childBucket4
      childBucket5
      children
      childrenAgeGroup2
      childrenAgeGroup3
      commissionCode
      commissionHoldCode
      commissionPaid
      commissionPayoutTo
      commissionableYN
      commissionid
      compTypeCode
      companyAll
      companyID
      companyNameId
      compreasonid
      confirmationLegNumber
      confirmationNo
      consumerYn
      contactNameId
      contactProfileID
      createdBy
      createdDate
      creditCardId
      creditLimitAutoPayAllowYn
      cribs
      currencyCode
      customReferenceNumber
      dSI
      dateOfArrivalInCountry
      dateOpenedForPickup
      departureComments
      departureDate
      departureDateTime
      departureTime
      departureTransportCode
      departureTransportationYN
      directBillVerifyResponse
      discountAmount
      discountAmt
      discountPercent
      discountPrcnt
      discountReason
      discountreasonid
      displayColor
      dmlSeqNumber
      doNotMoveRoom
      doNotMoveYN
      downloadDate
      downloadResort
      downloadSrep
      dropOffCarrierCode
      dropOffDate
      dropOffStation
      dropOffTime
      eTRComments
      effectiveRateAmount
      eligibleForUpgradeYn
      emailAddress
      emailFolioYn
      emailId
      emailYn
      endDate
      endbusinessdate
      entryDate
      entryPoint
      esignedRegCardName
      estimatedDepartureTime
      eventId
      exchangePostingType
      exchangeRate
      expectedTimeOfReturnETR
      exportCheckinresId
      extBookingID
      extSegNo
      extSeqNumber
      extensionId
      externalEfolioYn
      externalReference
      externallyLocked
      extraBeds
      faxId
      faxYn
      financiallyResponsibleYn
      fixedRateYN
      folioAddrElementId
      folioCloseDate
      folioText1
      folioText2
      foreignCurrencyID
      freeChild
      gUID
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
      inactiveDate
      insertActionInstanceId
      insertUser
      interfaceID
      intermediaryYn
      internalAwardMembershipId
      internalBaseratecode
      internalBlockId
      internalCompanyprofileid
      internalGroupprofileid
      internalSourceprofileid
      keyValidUntil
      laptopChange
      lastOnlinePrintSeq
      lastPeriodicFolioDate
      lastSettleDate
      lengthOfStay
      linkedArrivalDate
      linkedDepartureDate
      localBaseRateAmount
      mailYn
      mainmarket
      manualCheckoutStatus
      marketCode
      marketDescription
      marketid
      masterBlockID
      masterBlockProperty
      masterNameId
      membershipId
      mobileActionAlertIssued
      mobileAudioKeyYn
      mobileCheckinAllowedYn
      mobileChkoutAllowed
      mobilePreferredCurrency
      mobileViewFolioAllowed
      name
      nameUsageType
      nextDestination
      numberOfRooms
      operaEsignedRegCardYn
      optInBatchFolYn
      optedForCommissionYN
      organizationID
      originCodeDescription
      originOfBooking
      originalBaseRate
      originalEndDate
      originalStartDate
      owner
      ownerFfFlag
      ownerResort
      parentReservationNameId
      parentreservationid
      partAllotment
      partyCode
      payment
      paymentDescription
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
      primaryShare
      printRateYN
      profileId
      property
      pseudoMemTotalPoints
      pseudoMemType
      purgeDate
      purposeOfStay
      quantity
      quoteId
      rateAmount
      rateCode
      rateableValue
      ratecodeid
      rdenBillingContactId
      rdenReservationContactId
      rdenReservationDate
      referralYn
      registrationCardNo
      registrationNumber
      reinstateDate
      reportId
      resInsertSource
      resInsertSourceType
      reservationContactId
      reservationNameID
      reservationStatus
      reservationType
      reservationTypeDescription
      reserveInventoryYN
      resort
      resortBooked
      resortChargeNumber
      restrictionOverride
      resvNumber
      resvcontactprofileid
      revenueTypeCode
      rhBillingContactId
      rhReservationContactId
      rivMarketSegment
      room
      roomCategory
      roomClass
      roomInstructions
      roomServiceTime
      roomcategoryid
      roomid
      roomsPerDay
      salesId
      sbegindate
      scheduleCheckoutYn
      senddate
      serviceCharge
      sguestFirstName
      sguestName
      shareId
      shareSeqNumber
      shareOfRateAmount
      sharedProfileID
      sharedReservationStatus
      shoulderEnd
      shoulderStart
      sourceCodeDescription
      sourceContactAll
      sourceNameId
      sourceid
      spgDiscloseRoomTypeYn
      spgSuiteNightAwardStatus
      spgUpgradeConfirmedRoomtype
      spgUpgradeReasonCode
      splitFromReservationNameId
      splitfromreservationid
      startDate
      statisticalRateTier
      statisticalRoomType
      stayRecordId
      superSearchIndexText
      taxAmount
      taxExemptNumber
      taxNumberOfStays
      taxType
      taxtypeid
      tiad
      traceCode
      transactionid
      travelAgentAll
      travelAgentID
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
      uniCardId
      updateUser
      updatedBy
      updatedDate
      uploadDate
      upsellCharge
      videoCheckoutYN
      visaExpiryDate
      visaIssueDate
      visaNumber
      waitlistComment
      waitlistPhoneNumber
      walkInYN
      yieldableYn
      ymCode
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
    profileAccountsSourceDetails {
      aRNumber
      aRCUpdateDate
      accountEmailPrimary
      accountID
      accountName
      accountName2
      accountName3
      accountOwnerTitle
      accountOwnersAll
      accountPhonePrimary
      accountPhoneWeb
      accountSource
      accountSourceDescription
      accountType
      accountTypeDescription
      acctContact
      actionCode
      activeFlag
      address1
      address2
      address3
      address4
      addressLangCodeDesc
      addressLanguage
      addressLanguageCode
      addressType
      allProperties
      alternateLanguage
      alternateLanguageDescription
      alternateName
      alternateSalutation
      alternateTitle
      arNumberCentral
      autoenrollMemberYn
      billingInstruction
      billingProfileCode
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessPotential
      businessPotentialDescription
      businessSegement
      businessSegementDescription
      businessTitle
      centralAccountOwnerTitle
      centralAccountSource
      centralAccountSourceDescription
      centralAccountType
      centralAccountTypeDescription
      centralBusinessPotential
      centralBusinessPotentialDescription
      centralBusinessSegementDescription
      centralBusinessSegment
      centralCompetitionCode
      centralCompetitionCodeDescription
      centralCorporateType
      centralCorporateTypeDescription
      centralInactiveReason
      centralInactiveReasonDescription
      centralIndustryCode
      centralIndustryCodeDescription
      centralKeyword
      centralPriority
      centralPriorityDescription
      centralProfileTypeCode
      centralProfileTypeDescription
      centralScope
      centralScopeCity
      centralScopeCityDescription
      centralScopeDescription
      centralState
      centralTerritory
      centralTerritoryDescription
      chainCode
      city
      cityExt
      combinedName
      commissionCode
      commissionCodeAll
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      company
      competitionCode
      competitionCodeDescription
      corporateType
      corporateTypeDescription
      country
      countryDescription
      createdByUser
      createdOnDate
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dSI
      deletedFlag
      emailYn
      envelopeGreeting
      externalId
      fSubscriptionDb
      fSubscriptionYn
      faxNo
      first
      gender
      guestPrivYn
      historyYn
      holdCode
      iATANumber
      iataConsortia
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      industryCode
      industryCodeDescription
      interest
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      legalCompany
      letterGreeting
      mailAction
      mailActionDescription
      mailList
      mailType
      mailYn
      marketResearchYn
      middle
      nameId
      nationalityCode
      nationalityDescription
      negotiatedRate
      nextStay
      nickname
      organizationID
      paymentDueDays
      postalCode
      primaryKeyID
      primaryOwner
      primaryOwnerCode
      priority
      priorityDescription
      productInterest
      profession
      profileLanguageDescription
      profilePrivacyFlg
      profileType
      profileTypeCode
      profileTypeDescription
      protected
      referenceCurrency
      repInfluence
      repInfluenceDescription
      repMailActionCodes
      repMailActionDesc
      repNationalityCode
      repNationalityDescription
      repStateDescription
      repTaxTypeDescription
      repTitleName
      repVIPName
      repVIPStatus
      replaceAddress
      resortRegistered
      restricted
      restrictedRule
      salutation
      scope
      scopeCity
      scopeCityDecription
      scopeDescription
      searchAccountName
      sfirst
      state
      stateCode
      stateDesc
      sxfirstName
      sxname
      tax1No
      tax2No
      taxCategory
      taxType
      taxTypeDescription
      territory
      territoryDescription
      thirdPartyYn
      traceCode
      traceCodeDescription
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
      vipName
      vipStatus
      xcompanyName
      xenvelopeGreeting
      xfirstName
      xlastName
      xmiddleName
    }
    profileAccountsTravelAgentDetails {
      aRNumber
      aRCUpdateDate
      accountEmailPrimary
      accountID
      accountName
      accountName2
      accountName3
      accountOwnerTitle
      accountOwnersAll
      accountPhonePrimary
      accountPhoneWeb
      accountSource
      accountSourceDescription
      accountType
      accountTypeDescription
      acctContact
      actionCode
      activeFlag
      address1
      address2
      address3
      address4
      addressLangCodeDesc
      addressLanguage
      addressLanguageCode
      addressType
      allProperties
      alternateLanguage
      alternateLanguageDescription
      alternateName
      alternateSalutation
      alternateTitle
      arNumberCentral
      autoenrollMemberYn
      billingInstruction
      billingProfileCode
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessPotential
      businessPotentialDescription
      businessSegement
      businessSegementDescription
      businessTitle
      centralAccountOwnerTitle
      centralAccountSource
      centralAccountSourceDescription
      centralAccountType
      centralAccountTypeDescription
      centralBusinessPotential
      centralBusinessPotentialDescription
      centralBusinessSegementDescription
      centralBusinessSegment
      centralCompetitionCode
      centralCompetitionCodeDescription
      centralCorporateType
      centralCorporateTypeDescription
      centralInactiveReason
      centralInactiveReasonDescription
      centralIndustryCode
      centralIndustryCodeDescription
      centralKeyword
      centralPriority
      centralPriorityDescription
      centralProfileTypeCode
      centralProfileTypeDescription
      centralScope
      centralScopeCity
      centralScopeCityDescription
      centralScopeDescription
      centralState
      centralTerritory
      centralTerritoryDescription
      chainCode
      city
      cityExt
      combinedName
      commissionCode
      commissionCodeAll
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      company
      competitionCode
      competitionCodeDescription
      corporateType
      corporateTypeDescription
      country
      countryDescription
      createdByUser
      createdOnDate
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dSI
      deletedFlag
      emailYn
      envelopeGreeting
      externalId
      fSubscriptionDb
      fSubscriptionYn
      faxNo
      first
      gender
      guestPrivYn
      historyYn
      holdCode
      iATANumber
      iataConsortia
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      industryCode
      industryCodeDescription
      interest
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      legalCompany
      letterGreeting
      mailAction
      mailActionDescription
      mailList
      mailType
      mailYn
      marketResearchYn
      middle
      nameId
      nationalityCode
      nationalityDescription
      negotiatedRate
      nextStay
      nickname
      organizationID
      paymentDueDays
      postalCode
      primaryKeyID
      primaryOwner
      primaryOwnerCode
      priority
      priorityDescription
      productInterest
      profession
      profileLanguageDescription
      profilePrivacyFlg
      profileType
      profileTypeCode
      profileTypeDescription
      protected
      referenceCurrency
      repInfluence
      repInfluenceDescription
      repMailActionCodes
      repMailActionDesc
      repNationalityCode
      repNationalityDescription
      repStateDescription
      repTaxTypeDescription
      repTitleName
      repVIPName
      repVIPStatus
      replaceAddress
      resortRegistered
      restricted
      restrictedRule
      salutation
      scope
      scopeCity
      scopeCityDecription
      scopeDescription
      searchAccountName
      sfirst
      state
      stateCode
      stateDesc
      sxfirstName
      sxname
      tax1No
      tax2No
      taxCategory
      taxType
      taxTypeDescription
      territory
      territoryDescription
      thirdPartyYn
      traceCode
      traceCodeDescription
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
      vipName
      vipStatus
      xcompanyName
      xenvelopeGreeting
      xfirstName
      xlastName
      xmiddleName
    }
    externalReferencesDetails {
      dSI
      deletedFlag
      extCancellationNo
      externalReferenceLegNumber
      externalReferenceNumber
      externalReferenceType
      externalStatus
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      manualYn
      organizationID
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      revisionToken
      updateDate
      updateUser
      upperExternalReference
    }
    reservationMembershipDetails {
      cardNumberByMembershipClass
      cardNumberByMembershipType
      dSI
      deletedFlag
      earningPreference
      frequentFlyerMembershipYN
      hostBusinessDate
      hostCardinality
      hostFlag
      iDByMembershipClass
      iDByMembershipType
      insertDate
      insertUser
      internalMembershipid
      jRNUpdateDate
      jRNUpdateDateAndTime
      levelByMembershipType
      listOfMembershipIDs
      locationID
      loyaltySchemeMembershipYN
      mbrprefChangedDate
      membershipCardNo
      membershipCardNumber
      membershipClass
      membershipClassDescription
      membershipCode
      membershipDescription
      membershipId
      membershipLevel
      membershipLevelByMembershipClass
      membershipType
      membershipTypeByMembershipClass
      multiplierInstance
      nameId
      organizationID
      pointsMultiplier
      populationMethod
      primaryKeyID
      processedDate
      processedYn
      profileid
      property
      rankValue
      reservationNameId
      reservationid
      reservationmembershipid
      resvenddate
      rnaInsertDate
      rnaUpdateDate
      updateDate
      updateUser
    }
    reservationPaymentMethodsDetails {
      authorizationAmount
      authorizationDescription
      authorizationRule
      bonusCheckId
      centralPaymentMethodType
      centralPaymentMethodTypeDescription
      creditCardAuthorizationDate
      creditCardId
      dSI
      deletedFlag
      directBillVerifyResponse
      emailAddress
      emailFolioYn
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      organizationID
      paymentMethodType
      paymentMethodTypeDescription
      paymentWindow
      primaryKeyID
      property
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      updateDate
      updateUser
    }
    profileAccountsDetails {
      aRNumber
      aRCUpdateDate
      accountEmailPrimary
      accountID
      accountName
      accountName2
      accountName3
      accountOwnerTitle
      accountOwnersAll
      accountPhonePrimary
      accountPhoneWeb
      accountSource
      accountSourceDescription
      accountType
      accountTypeDescription
      acctContact
      actionCode
      activeFlag
      address1
      address2
      address3
      address4
      addressLangCodeDesc
      addressLanguage
      addressLanguageCode
      addressType
      allProperties
      alternateLanguage
      alternateLanguageDescription
      alternateName
      alternateSalutation
      alternateTitle
      arNumberCentral
      autoenrollMemberYn
      billingInstruction
      billingProfileCode
      birthDate
      birthDateStr
      birthPlace
      blMsg
      businessPotential
      businessPotentialDescription
      businessSegement
      businessSegementDescription
      businessTitle
      centralAccountOwnerTitle
      centralAccountSource
      centralAccountSourceDescription
      centralAccountType
      centralAccountTypeDescription
      centralBusinessPotential
      centralBusinessPotentialDescription
      centralBusinessSegementDescription
      centralBusinessSegment
      centralCompetitionCode
      centralCompetitionCodeDescription
      centralCorporateType
      centralCorporateTypeDescription
      centralInactiveReason
      centralInactiveReasonDescription
      centralIndustryCode
      centralIndustryCodeDescription
      centralKeyword
      centralPriority
      centralPriorityDescription
      centralProfileTypeCode
      centralProfileTypeDescription
      centralScope
      centralScopeCity
      centralScopeCityDescription
      centralScopeDescription
      centralState
      centralTerritory
      centralTerritoryDescription
      chainCode
      city
      cityExt
      combinedName
      commissionCode
      commissionCodeAll
      communicationRole1
      communicationRole2
      communicationRole3
      communicationType1
      communicationType2
      communicationType3
      communicationValue1
      communicationValue2
      communicationValue3
      company
      competitionCode
      competitionCodeDescription
      corporateType
      corporateTypeDescription
      country
      countryDescription
      createdByUser
      createdOnDate
      creditCardName
      creditCardType
      creditRating
      currencyCode
      currencyDescription
      dSI
      deletedFlag
      emailYn
      envelopeGreeting
      externalId
      fSubscriptionDb
      fSubscriptionYn
      faxNo
      first
      gender
      guestPrivYn
      historyYn
      holdCode
      iATANumber
      iataConsortia
      inactiveDate
      inactiveFlag
      inactiveReason
      inactiveReasonDescription
      industryCode
      industryCodeDescription
      interest
      internalDeletedflag
      internalInactiveflag
      internalOrganizationId
      jRNUpdateDate
      jRNUpdateDateAndTime
      keyword
      last
      lastGroup
      lastRate
      lastRoom
      lastSource
      lastStay
      legalCompany
      letterGreeting
      mailAction
      mailActionDescription
      mailList
      mailType
      mailYn
      marketResearchYn
      middle
      nameId
      nationalityCode
      nationalityDescription
      negotiatedRate
      nextStay
      nickname
      organizationID
      paymentDueDays
      postalCode
      primaryKeyID
      primaryOwner
      primaryOwnerCode
      priority
      priorityDescription
      productInterest
      profession
      profileLanguageDescription
      profilePrivacyFlg
      profileType
      profileTypeCode
      profileTypeDescription
      protected
      rNAInsertDate
      rNAUpdateDate
      referenceCurrency
      repInfluence
      repInfluenceDescription
      repMailActionCodes
      repMailActionDesc
      repNationalityCode
      repNationalityDescription
      repStateDescription
      repTaxTypeDescription
      repTitleName
      repVIPName
      repVIPStatus
      replaceAddress
      resortRegistered
      restricted
      restrictedRule
      salutation
      scope
      scopeCity
      scopeCityDecription
      scopeDescription
      searchAccountName
      sfirst
      state
      stateCode
      stateDesc
      sxfirstName
      sxname
      tax1No
      tax2No
      taxCategory
      taxType
      taxTypeDescription
      territory
      territoryDescription
      thirdPartyYn
      traceCode
      traceCodeDescription
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
      vipName
      vipStatus
      xcompanyName
      xenvelopeGreeting
      xfirstName
      xlastName
      xmiddleName
    }
    reservationDepositScheduleDetails {
      activityDeposit
      cActivityDeposit
      cCancelPnltyAmount
      cExchangeDate
      cExchangeRate
      cForeignDepositAmount
      cancelDeadline
      cancelPnltyAmount
      centralDepositAmountOutstanding
      centralDepositAmountRequested
      centralTotalDepositPayments
      comments
      dSI
      deletedFlag
      depositAmountOutstanding
      depositAmountRequested
      depositDueDate
      depositPercentage
      depositReqLinkId
      depositReqReceiptNo
      depositReqReversalYn
      depositRule
      depositRuleDescription
      depositRuleType
      depositScheduleReservationNameId
      depositType
      dmlSeqNumber
      exchangeRateInfo
      externalId
      foreignDepositAmount
      insertActionInstanceId
      insertDate
      insertUser
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      manualYn
      organizationID
      paymentFlag
      primaryKeyID
      processedYn
      productId
      property
      rNAInsertDate
      rNAUpdateDate
      rateDcSeq
      reservationDepositScheduleId
      roomDeposit
      totalDepositPayments
      trxDate
      updateDate
      updateUser
    }
    rateCodeDetailsDetails {
      addAfterRounding
      adultCharge
      adultsThreshold
      adultsThresholdCharge
      advBaseAmount
      advBaseFltPct
      advDailyBaseRateCode
      advanceBaseCompareYN
      ageRangeForBucket1
      ageRangeForBucket2
      ageRangeForBucket3
      amount1Type
      amount2Type
      amount3Type
      amount4Type
      amount5Type
      amountFor1Person
      amountFor2Persons
      amountFor3Persons
      amountFor4Persons
      amountFor5Persons
      barAmount
      barFltPct
      barRounding
      barYn
      cAdultCharge
      cAdultsThresholdCharge
      cAdvanceBaseAmount
      cAmount1
      cAmount2
      cAmount3
      cAmount4
      cAmount5
      cBarAmount
      cChildCharge1
      cChildCharge2
      cChildCharge3
      cChildOwnCharge1
      cChildOwnCharge2
      cChildOwnCharge3
      cChildOwnCharge4
      cChildrenCharge
      cChildrenThresholdCharge
      cDifferenceAmount1
      cDifferenceAmount2
      cDifferenceAmount3
      cDifferenceAmount4
      cDifferenceAmount5
      cDifferenceAmountExtraAdult
      cExchangeDate
      cExchangeRate
      cFlatIncrease
      cLos1Amount
      cLos10Amount
      cLos11Amount
      cLos12Amount
      cLos13Amount
      cLos14Amount
      cLos2Amount
      cLos3Amount
      cLos4Amount
      cLos5Amount
      cLos6Amount
      cLos7Amount
      cLos8Amount
      cLos9Amount
      cMaximumAmount1
      cMaximumAmount2
      cMinimumAmount1
      cMinimumAmount2
      cOccupantsThresholdCharge
      cPackageRateStayOver
      cRoomCost
      calculationFlag
      catPackagePriceCode
      centralMarketCode
      centralMarketDescription
      centralMarketGroupCode
      centralMarketGroupDescription
      centralPackageCode
      centralRoomType
      centralRoomTypeDescription
      centralSeasonCode
      centralSourceCode
      centralSourceDescription
      centralSourceGroupCode
      centralSourceGroupDescription
      childExcThreshold1
      childExcThreshold2
      childExcThreshold3
      childOwnCharge1
      childOwnCharge2
      childOwnCharge3
      childOwnCharge4
      childrenFreeStay
      childrenCharge
      childrenThreshold
      childrenThresholdCharge
      currencyCode
      currencyDescription
      dSI
      deletedflag
      depositRequieredYn
      differenceAmount1
      differenceAmount2
      differenceAmount3
      differenceAmount4
      differenceAmount5
      differenceAmountExtraAdult
      differencePercentage1Yn
      differencePercentage2Yn
      differencePercentage3Yn
      differencePercentage4Yn
      differencePercentage5Yn
      differencePercentageExtraAdultYn
      endDate
      externalRateSetId
      extraAdultType
      flatIncrease
      globalRateUpdateYn
      inactiveDate
      inactiveflag
      insertDate
      insertUser
      internalLocationId
      internalOrganizationId
      internalRatesetid
      jRNUpdateDate
      jRNUpdateDateAndTime
      lengthOfStay1Amount
      lengthOfStay10Amount
      lengthOfStay11Amount
      lengthOfStay12Amount
      lengthOfStay13Amount
      lengthOfStay14Amount
      lengthOfStay2Amount
      lengthOfStay3Amount
      lengthOfStay4Amount
      lengthOfStay5Amount
      lengthOfStay6Amount
      lengthOfStay7Amount
      lengthOfStay8Amount
      lengthOfStay9Amount
      linkRateSetId
      locationID
      marketCode
      marketDescription
      marketGroupCode
      marketGroupDescription
      maximumAmount1
      maximumAmount2
      minChildrenForFreeStay
      minimumAmount1
      minimumAmount2
      minimumClosingProbability
      occupantsThreshold
      occupantsThresholdCharge
      organizationID
      packageAdultStayOver
      packageChildrenStayOver
      packageCode
      packageRateStayOver
      percentIncrease
      pointsRequired
      primaryKeyID
      property
      rateAvailableOnFridaysYN
      rateAvailableOnMondaysYN
      rateAvailableOnSaturdaysYN
      rateAvailableOnSundaysYN
      rateAvailableOnThursdaysYN
      rateAvailableOnTuesdaysYN
      rateAvailableOnWednesdaysYN
      rateCode
      rateCodeDesc
      rateCodeId
      rateRule
      rateSetId
      rateForChildInAgeBucket1
      rateForChildInAgeBucket2
      rateForChildInAgeBucket3
      ratesActiveYn
      ratetierid
      repSeasonDescription
      rnaInsertDate
      rnaUpdateDate
      roomCost
      roomType
      roomTypeDescription
      roundToNearest
      season
      seasonCode
      seasonDesc
      sourceCode
      sourceDescription
      sourceGroupCode
      sourceGroupDescription
      startDate
      tierId
      updateDate
      updateUser
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
    financialUnifiedDetails {
      aRChargeTransferFlagYN
      aRLedgerCredit
      aRLedgerDebit
      aRState
      aRTransferDate
      accountCode
      accountNumber
      addressId
      advanceBillReversedYN
      advanceBillYn
      advancedGenerateYN
      advgenTtransCodeID
      arrangementCode
      arrangementDesc
      articleId
      associatedTrxNumber
      attachedToUser
      authEmployeeID
      authorizer
      autoCreditbillYn
      autoSettleYn
      businessDate
      cCApproval
      cashierCode
      cashierCredit
      cashierDebit
      cashierID
      cashierName
      cashierOpeningBalance
      ccRefundPosting
      changesLogCheckIn
      changesLogCheckOut
      changesLogCloseFolio
      changesLogReopenFolio
      changesLogUpdateReservation
      checkNumber
      closureNumber
      comments
      compLinkTrxCode
      compLinkTrxNumber
      compTypeCode
      compressedYn
      covers
      creditCardId
      creditCardSurcharge
      creditYN
      currencyCode
      currencyDescription
      dSI
      debitYN
      decimals
      deferredYn
      depPostingFlag
      depTaxTransferedYn
      depositLedgerCredit
      depositLedgerDebit
      depositTransactionId
      displayYN
      euroExchangeRate
      exchangeDate
      exchangeDifferenceYN
      exchangeRate
      exchangeType
      financialDmlSeqNumber
      fiscalBillNo
      fixedChargesYN
      folio
      folioNo
      folioType
      folioView
      foreignCurrencyCode
      fromReservationId
      ftGeneratedType
      ftSubtype
      genCashierId
      generalCashierYN
      grossAmount
      guestAccountLedgerCredit
      guestAccountLedgerDebit
      inHouseCredit
      inHouseDebit
      insertDate
      insertUser
      insertUserName
      interfaceCashierYN
      internalArticleid
      internalWindowId
      internalYN
      invoiceCloseDate
      invoiceNumber
      invoiceType
      linkTrxNumber
      marketCode
      marketDescription
      membershipID
      mtrxNoAgainstPackage
      nameTaxType
      netAmount
      nonRevenueAmount
      numberDialed
      organizationID
      originalARLedgerDebit
      originalBillNumber
      originalFolioNumber
      originalReservationNameId
      originalRoom
      package
      packageAllowance
      packageArrangementCode
      packageLedgerCredit
      packageLedgerDebit
      packageTrxType
      passerByName
      payeeNameID
      payeeResvNameID
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
      profileID
      profitLossFlag
      proformaYN
      property
      quantity
      queueName
      rateCode
      receiptNumber
      receiptType
      repTransactionCode
      repTransactionCodeGroup
      repTransactionCodeGroupDescription
      repTransactionCodeSubgroup
      repTransactionCodeSubgroupDescription
      reservationDepositId
      reservationNameID
      revenueAmount
      reversePaymentTrxNumber
      roomClass
      roomNts
      roomNtsEffective
      roomNumber
      roundFactorYn
      roundLinkTrxno
      routedYn
      routingCode
      routingCodeDescription
      routingDate
      routingIinstructionID
      routingInstrnId
      routingType
      settlementFlag
      sourceCode
      sourceDescription
      supplement
      tRXCode
      targetResort
      taxDeferredUntilCheckOutYN
      taxElements
      taxGeneratedYN
      taxInclusiveYN
      tcGroup
      tcSubgroup
      thresholdDiversionId
      thresholdEntityQty
      thresholdEntityType
      thresholdTreatmentFlag
      toReservationNameId
      tranActionId
      transCodeArrangementID
      transactionActivityDate
      transactionCodeDescription
      transactionCodeGroupDesc
      transactionCodeSubgroupDesc
      transactionDate
      transactionNumberAddedBy
      transactionPostingDate
      transactionPostingTime
      transactionPostingTimeWithSeconds
      transactionType
      transactionFromAccount
      transactionToAccount
      transferFromAccountID
      transferToAccountID
      trxNo
      trxNoAgainstPackage
      trxNumberAdjust
      trxNumberHeader
      trxNumberSplit
      trxServiceType
      updateDate
      updateUser
      vatAmount
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
    fixedChargesDetails {
      accountCode
      accountid
      amountOrPercentage
      amountOrPercentageFlag
      articleId
      beginDateNullable
      businessDate
      cExchangeDate
      cExchangeRate
      cPrice
      centralTransactionCode
      centralTransactionCodeDescription
      dSI
      daytoexecute
      deletedFlag
      endDate
      endDateNullable
      fixedChargesId
      fixedchargespmsref
      frequency
      insertDate
      insertUser
      insertUserName
      internalArticleid
      internalFixedchargesid
      jRNUpdateDate
      jRNUpdateDateAndTime
      locationID
      organizationID
      percentage
      price
      primaryKeyID
      property
      quantity
      rNAInsertDate
      rNAUpdateDate
      reservationNameId
      reservationid
      resvenddate
      roomnights
      supplement
      transactionCode
      transactionCodeDescription
      transactionCodeGroup
      transactionCodeSubGroup
      transactionCodeType
      transcodeid
      updateUser
      updatedate
      yearlyfixedchargedate
    }
  }
}
```

## Polars Schema
> Polars data types based on the GraphQL specification to prevent schema inference errors when writing the output Parquet file.
  
```python
import polars as pl

reservation_unified_details_schema = {
    'aSBProratedYn': pl.Utf8,
    'actionId': pl.Float64,
    'actualCheckInDateTime': pl.Utf8,
    'actualCheckOutDateTime': pl.Utf8,
    'actualCheckInDate': pl.Utf8,
    'actualCheckOutDate': pl.Utf8,
    'addressId': pl.Float64,
    'addresseeNameId': pl.Float64,
    'adults': pl.Float64,
    'adultsTaxFree': pl.Float64,
    'advanceCheckedInYn': pl.Utf8,
    'agencyprofileid': pl.Float64,
    'agentNameId': pl.Float64,
    'allAliases': pl.Utf8,
    'allBlockOwners': pl.Utf8,
    'allCateringOwners': pl.Utf8,
    'allCompanyContacts': pl.Utf8,
    'allRateCodes': pl.Utf8,
    'allRoomOwners': pl.Utf8,
    'allRoomTypes': pl.Utf8,
    'allSourceContacts': pl.Utf8,
    'allTravelAgentContacts': pl.Utf8,
    'allotmentOrigin': pl.Utf8,
    'allotmentRecordType': pl.Float64,
    'allotmentType': pl.Utf8,
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
    'authorizedBy': pl.Float64,
    'authorizerId': pl.Float64,
    'autoCheckinYn': pl.Utf8,
    'autoSettleDays': pl.Utf8,
    'autoSettleYN': pl.Float64,
    'averageRate': pl.Float64,
    'awardCode': pl.Utf8,
    'awardCode1': pl.Utf8,
    'awardCode2': pl.Utf8,
    'awardCode3': pl.Utf8,
    'awardCode4': pl.Utf8,
    'awardCode5': pl.Utf8,
    'awardVoucher1': pl.Utf8,
    'awardVoucher2': pl.Utf8,
    'awardVoucher3': pl.Utf8,
    'awardVoucher4': pl.Utf8,
    'awardVoucher5': pl.Utf8,
    'awdUpgrFrom': pl.Utf8,
    'awdUpgrTo': pl.Utf8,
    'baseRateAmount': pl.Float64,
    'baseRateCode': pl.Utf8,
    'baseRateCurrencyCode': pl.Utf8,
    'baseratecurrencyid': pl.Utf8,
    'beginDatetime': pl.Utf8,
    'beginSystemDateTime': pl.Utf8,
    'billingContactId': pl.Float64,
    'billingcontactprofileid': pl.Float64,
    'blockAlias': pl.Utf8,
    'blockCode': pl.Utf8,
    'blockDescription': pl.Utf8,
    'blockDmlSeqNumber': pl.Float64,
    'blockEndbusinessdate': pl.Utf8,
    'blockExchangePostingType': pl.Utf8,
    'blockExchangeRate': pl.Float64,
    'blockExternalReference': pl.Utf8,
    'blockID': pl.Utf8,
    'blockOwnerCode': pl.Utf8,
    'blockResort': pl.Utf8,
    'blockStatus': pl.Utf8,
    'blockStatusDescription': pl.Utf8,
    'blocksExternalReference': pl.Utf8,
    'bonusCheckId': pl.Float64,
    'bookedRoomCategory': pl.Utf8,
    'bookedroomcategoryid': pl.Utf8,
    'businessDateCreated': pl.Utf8,
    'cancelDate': pl.Utf8,
    'cancelReason': pl.Utf8,
    'cancelTime': pl.Utf8,
    'cancellationDate': pl.Utf8,
    'cancellationNumber': pl.Utf8,
    'cancellationReasonDescription': pl.Utf8,
    'cancellationreasonid': pl.Utf8,
    'centralApprovalAmount': pl.Float64,
    'changesLogCheckIn': pl.Utf8,
    'changesLogCheckOut': pl.Utf8,
    'changesLogCloseFolio': pl.Utf8,
    'changesLogReopenFolio': pl.Utf8,
    'changesLogUpdateReservation': pl.Utf8,
    'checkinDuration': pl.Float64,
    'childBucket1': pl.Float64,
    'childBucket4': pl.Float64,
    'childBucket5': pl.Float64,
    'children': pl.Float64,
    'childrenAgeGroup2': pl.Float64,
    'childrenAgeGroup3': pl.Float64,
    'commissionCode': pl.Utf8,
    'commissionHoldCode': pl.Utf8,
    'commissionPaid': pl.Float64,
    'commissionPayoutTo': pl.Float64,
    'commissionableYN': pl.Utf8,
    'commissionid': pl.Utf8,
    'compTypeCode': pl.Utf8,
    'companyAll': pl.Utf8,
    'companyID': pl.Float64,
    'companyNameId': pl.Float64,
    'compreasonid': pl.Utf8,
    'confirmationLegNumber': pl.Float64,
    'confirmationNo': pl.Utf8,
    'consumerYn': pl.Utf8,
    'contactNameId': pl.Float64,
    'contactProfileID': pl.Float64,
    'createdBy': pl.Utf8,
    'createdDate': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditLimitAutoPayAllowYn': pl.Utf8,
    'cribs': pl.Float64,
    'currencyCode': pl.Utf8,
    'customReferenceNumber': pl.Utf8,
    'dSI': pl.Float64,
    'dateOfArrivalInCountry': pl.Utf8,
    'dateOpenedForPickup': pl.Utf8,
    'departureComments': pl.Utf8,
    'departureDate': pl.Utf8,
    'departureDateTime': pl.Utf8,
    'departureTime': pl.Utf8,
    'departureTransportCode': pl.Utf8,
    'departureTransportationYN': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'discountAmount': pl.Float64,
    'discountAmt': pl.Float64,
    'discountPercent': pl.Float64,
    'discountPrcnt': pl.Float64,
    'discountReason': pl.Utf8,
    'discountreasonid': pl.Utf8,
    'displayColor': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'doNotMoveRoom': pl.Utf8,
    'doNotMoveYN': pl.Utf8,
    'downloadDate': pl.Utf8,
    'downloadResort': pl.Utf8,
    'downloadSrep': pl.Float64,
    'dropOffCarrierCode': pl.Utf8,
    'dropOffDate': pl.Utf8,
    'dropOffStation': pl.Utf8,
    'dropOffTime': pl.Utf8,
    'eTRComments': pl.Utf8,
    'effectiveRateAmount': pl.Float64,
    'eligibleForUpgradeYn': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'emailId': pl.Float64,
    'emailYn': pl.Utf8,
    'endDate': pl.Utf8,
    'endbusinessdate': pl.Utf8,
    'entryDate': pl.Utf8,
    'entryPoint': pl.Float64,
    'esignedRegCardName': pl.Utf8,
    'estimatedDepartureTime': pl.Utf8,
    'eventId': pl.Float64,
    'exchangePostingType': pl.Utf8,
    'exchangeRate': pl.Float64,
    'expectedTimeOfReturnETR': pl.Utf8,
    'exportCheckinresId': pl.Float64,
    'extBookingID': pl.Utf8,
    'extSegNo': pl.Float64,
    'extSeqNumber': pl.Float64,
    'extensionId': pl.Float64,
    'externalEfolioYn': pl.Utf8,
    'externalReference': pl.Utf8,
    'externallyLocked': pl.Utf8,
    'extraBeds': pl.Float64,
    'faxId': pl.Float64,
    'faxYn': pl.Utf8,
    'financiallyResponsibleYn': pl.Utf8,
    'fixedRateYN': pl.Utf8,
    'folioAddrElementId': pl.Float64,
    'folioCloseDate': pl.Utf8,
    'folioText1': pl.Utf8,
    'folioText2': pl.Utf8,
    'foreignCurrencyID': pl.Utf8,
    'freeChild': pl.Float64,
    'gUID': pl.Utf8,
    'guaranteeCodePreCi': pl.Utf8,
    'guaranteecodeid': pl.Utf8,
    'guestFirstName': pl.Utf8,
    'guestFirstNameSdx': pl.Utf8,
    'guestLastNameSdx': pl.Utf8,
    'guestSignature': pl.Float64,
    'guestStatus': pl.Utf8,
    'guestType': pl.Utf8,
    'guestprofileid': pl.Float64,
    'gueststatusid': pl.Utf8,
    'guesttypeid': pl.Utf8,
    'housekeepingServiceTime': pl.Utf8,
    'hurdle': pl.Float64,
    'hurdleOverride': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'insertActionInstanceId': pl.Float64,
    'insertUser': pl.Float64,
    'interfaceID': pl.Utf8,
    'intermediaryYn': pl.Utf8,
    'internalAwardMembershipId': pl.Float64,
    'internalBaseratecode': pl.Utf8,
    'internalBlockId': pl.Utf8,
    'internalCompanyprofileid': pl.Float64,
    'internalGroupprofileid': pl.Float64,
    'internalSourceprofileid': pl.Float64,
    'keyValidUntil': pl.Float64,
    'laptopChange': pl.Float64,
    'lastOnlinePrintSeq': pl.Float64,
    'lastPeriodicFolioDate': pl.Utf8,
    'lastSettleDate': pl.Utf8,
    'lengthOfStay': pl.Float64,
    'linkedArrivalDate': pl.Utf8,
    'linkedDepartureDate': pl.Utf8,
    'localBaseRateAmount': pl.Float64,
    'mailYn': pl.Utf8,
    'mainmarket': pl.Utf8,
    'manualCheckoutStatus': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketid': pl.Utf8,
    'masterBlockID': pl.Float64,
    'masterBlockProperty': pl.Utf8,
    'masterNameId': pl.Float64,
    'membershipId': pl.Float64,
    'mobileActionAlertIssued': pl.Utf8,
    'mobileAudioKeyYn': pl.Float64,
    'mobileCheckinAllowedYn': pl.Utf8,
    'mobileChkoutAllowed': pl.Utf8,
    'mobilePreferredCurrency': pl.Utf8,
    'mobileViewFolioAllowed': pl.Utf8,
    'name': pl.Utf8,
    'nameUsageType': pl.Utf8,
    'nextDestination': pl.Utf8,
    'numberOfRooms': pl.Float64,
    'operaEsignedRegCardYn': pl.Utf8,
    'optInBatchFolYn': pl.Utf8,
    'optedForCommissionYN': pl.Utf8,
    'organizationID': pl.Float64,
    'originCodeDescription': pl.Utf8,
    'originOfBooking': pl.Utf8,
    'originalBaseRate': pl.Float64,
    'originalEndDate': pl.Utf8,
    'originalStartDate': pl.Utf8,
    'owner': pl.Float64,
    'ownerFfFlag': pl.Utf8,
    'ownerResort': pl.Utf8,
    'parentReservationNameId': pl.Float64,
    'parentreservationid': pl.Float64,
    'partAllotment': pl.Utf8,
    'partyCode': pl.Utf8,
    'payment': pl.Utf8,
    'paymentDescription': pl.Utf8,
    'paymentMethod': pl.Utf8,
    'paymentmethodid': pl.Utf8,
    'periodicFolioFreq': pl.Utf8,
    'phoneDisplayNameYn': pl.Utf8,
    'phoneId': pl.Float64,
    'physicalQuantity': pl.Float64,
    'pickUpCarrierCode': pl.Utf8,
    'pickUpDate': pl.Utf8,
    'pickUpStation': pl.Utf8,
    'pickUpTransportNumber': pl.Utf8,
    'pickUpTime': pl.Utf8,
    'pickupRequiredYN': pl.Utf8,
    'points': pl.Float64,
    'pointsEligibilityCode': pl.Utf8,
    'postCoFlag': pl.Utf8,
    'postStayChargingYN': pl.Utf8,
    'postingAllowedYN': pl.Utf8,
    'preArrReviewedDt': pl.Utf8,
    'preArrReviewedUser': pl.Utf8,
    'preChargingYn': pl.Utf8,
    'preRegisteredYn': pl.Utf8,
    'primaryShare': pl.Utf8,
    'printRateYN': pl.Utf8,
    'profileId': pl.Utf8,
    'property': pl.Utf8,
    'pseudoMemTotalPoints': pl.Utf8,
    'pseudoMemType': pl.Utf8,
    'purgeDate': pl.Utf8,
    'purposeOfStay': pl.Utf8,
    'quantity': pl.Float64,
    'quoteId': pl.Utf8,
    'rateAmount': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateableValue': pl.Float64,
    'ratecodeid': pl.Utf8,
    'rdenBillingContactId': pl.Float64,
    'rdenReservationContactId': pl.Float64,
    'rdenReservationDate': pl.Utf8,
    'referralYn': pl.Utf8,
    'registrationCardNo': pl.Utf8,
    'registrationNumber': pl.Utf8,
    'reinstateDate': pl.Utf8,
    'reportId': pl.Utf8,
    'resInsertSource': pl.Utf8,
    'resInsertSourceType': pl.Utf8,
    'reservationContactId': pl.Float64,
    'reservationNameID': pl.Float64,
    'reservationStatus': pl.Utf8,
    'reservationType': pl.Utf8,
    'reservationTypeDescription': pl.Utf8,
    'reserveInventoryYN': pl.Utf8,
    'resort': pl.Utf8,
    'resortBooked': pl.Utf8,
    'resortChargeNumber': pl.Utf8,
    'restrictionOverride': pl.Utf8,
    'resvNumber': pl.Float64,
    'resvcontactprofileid': pl.Float64,
    'revenueTypeCode': pl.Utf8,
    'rhBillingContactId': pl.Float64,
    'rhReservationContactId': pl.Float64,
    'rivMarketSegment': pl.Utf8,
    'room': pl.Utf8,
    'roomCategory': pl.Utf8,
    'roomClass': pl.Utf8,
    'roomInstructions': pl.Utf8,
    'roomServiceTime': pl.Utf8,
    'roomcategoryid': pl.Utf8,
    'roomid': pl.Utf8,
    'roomsPerDay': pl.Float64,
    'salesId': pl.Utf8,
    'sbegindate': pl.Utf8,
    'scheduleCheckoutYn': pl.Utf8,
    'senddate': pl.Utf8,
    'serviceCharge': pl.Float64,
    'sguestFirstName': pl.Utf8,
    'sguestName': pl.Utf8,
    'shareId': pl.Float64,
    'shareSeqNumber': pl.Utf8,
    'shareOfRateAmount': pl.Float64,
    'sharedProfileID': pl.Float64,
    'sharedReservationStatus': pl.Utf8,
    'shoulderEnd': pl.Utf8,
    'shoulderStart': pl.Utf8,
    'sourceCodeDescription': pl.Utf8,
    'sourceContactAll': pl.Utf8,
    'sourceNameId': pl.Float64,
    'sourceid': pl.Utf8,
    'spgDiscloseRoomTypeYn': pl.Utf8,
    'spgSuiteNightAwardStatus': pl.Utf8,
    'spgUpgradeConfirmedRoomtype': pl.Utf8,
    'spgUpgradeReasonCode': pl.Utf8,
    'splitFromReservationNameId': pl.Float64,
    'splitfromreservationid': pl.Float64,
    'startDate': pl.Utf8,
    'statisticalRateTier': pl.Float64,
    'statisticalRoomType': pl.Utf8,
    'stayRecordId': pl.Float64,
    'superSearchIndexText': pl.Utf8,
    'taxAmount': pl.Float64,
    'taxExemptNumber': pl.Utf8,
    'taxNumberOfStays': pl.Utf8,
    'taxType': pl.Utf8,
    'taxtypeid': pl.Utf8,
    'tiad': pl.Utf8,
    'traceCode': pl.Utf8,
    'transactionid': pl.Float64,
    'travelAgentAll': pl.Utf8,
    'travelAgentID': pl.Float64,
    'truncActualCheckOutDate': pl.Utf8,
    'turndownStatus': pl.Float64,
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
    'uniCardId': pl.Utf8,
    'updateUser': pl.Float64,
    'updatedBy': pl.Utf8,
    'updatedDate': pl.Utf8,
    'uploadDate': pl.Utf8,
    'upsellCharge': pl.Float64,
    'videoCheckoutYN': pl.Utf8,
    'visaExpiryDate': pl.Utf8,
    'visaIssueDate': pl.Utf8,
    'visaNumber': pl.Float64,
    'waitlistComment': pl.Utf8,
    'waitlistPhoneNumber': pl.Utf8,
    'walkInYN': pl.Utf8,
    'yieldableYn': pl.Utf8,
    'ymCode': pl.Float64,
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

profile_accounts_source_details_schema = {
    'aRNumber': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountEmailPrimary': pl.Utf8,
    'accountID': pl.Float64,
    'accountName': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountOwnersAll': pl.Utf8,
    'accountPhonePrimary': pl.Utf8,
    'accountPhoneWeb': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountSourceDescription': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'acctContact': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeFlag': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguage': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'allProperties': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'arNumberCentral': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessPotential': pl.Utf8,
    'businessPotentialDescription': pl.Utf8,
    'businessSegement': pl.Utf8,
    'businessSegementDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'centralAccountOwnerTitle': pl.Utf8,
    'centralAccountSource': pl.Utf8,
    'centralAccountSourceDescription': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralAccountTypeDescription': pl.Utf8,
    'centralBusinessPotential': pl.Utf8,
    'centralBusinessPotentialDescription': pl.Utf8,
    'centralBusinessSegementDescription': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralCompetitionCode': pl.Utf8,
    'centralCompetitionCodeDescription': pl.Utf8,
    'centralCorporateType': pl.Utf8,
    'centralCorporateTypeDescription': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralKeyword': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralPriorityDescription': pl.Utf8,
    'centralProfileTypeCode': pl.Utf8,
    'centralProfileTypeDescription': pl.Utf8,
    'centralScope': pl.Utf8,
    'centralScopeCity': pl.Utf8,
    'centralScopeCityDescription': pl.Utf8,
    'centralScopeDescription': pl.Utf8,
    'centralState': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralTerritoryDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeAll': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'company': pl.Utf8,
    'competitionCode': pl.Utf8,
    'competitionCodeDescription': pl.Utf8,
    'corporateType': pl.Utf8,
    'corporateTypeDescription': pl.Utf8,
    'country': pl.Utf8,
    'countryDescription': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNo': pl.Utf8,
    'first': pl.Utf8,
    'gender': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYn': pl.Utf8,
    'holdCode': pl.Utf8,
    'iATANumber': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'interest': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailAction': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'middle': pl.Utf8,
    'nameId': pl.Float64,
    'nationalityCode': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'negotiatedRate': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Float64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'priority': pl.Utf8,
    'priorityDescription': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileLanguageDescription': pl.Utf8,
    'profilePrivacyFlg': pl.Utf8,
    'profileType': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'profileTypeDescription': pl.Utf8,
    'protected': pl.Utf8,
    'referenceCurrency': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repMailActionDesc': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDecription': pl.Utf8,
    'scopeDescription': pl.Utf8,
    'searchAccountName': pl.Utf8,
    'sfirst': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDesc': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDescription': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceCodeDescription': pl.Utf8,
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
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}

profile_accounts_travel_agent_details_schema = {
    'aRNumber': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountEmailPrimary': pl.Utf8,
    'accountID': pl.Float64,
    'accountName': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountOwnersAll': pl.Utf8,
    'accountPhonePrimary': pl.Utf8,
    'accountPhoneWeb': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountSourceDescription': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'acctContact': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeFlag': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguage': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'allProperties': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'arNumberCentral': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessPotential': pl.Utf8,
    'businessPotentialDescription': pl.Utf8,
    'businessSegement': pl.Utf8,
    'businessSegementDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'centralAccountOwnerTitle': pl.Utf8,
    'centralAccountSource': pl.Utf8,
    'centralAccountSourceDescription': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralAccountTypeDescription': pl.Utf8,
    'centralBusinessPotential': pl.Utf8,
    'centralBusinessPotentialDescription': pl.Utf8,
    'centralBusinessSegementDescription': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralCompetitionCode': pl.Utf8,
    'centralCompetitionCodeDescription': pl.Utf8,
    'centralCorporateType': pl.Utf8,
    'centralCorporateTypeDescription': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralKeyword': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralPriorityDescription': pl.Utf8,
    'centralProfileTypeCode': pl.Utf8,
    'centralProfileTypeDescription': pl.Utf8,
    'centralScope': pl.Utf8,
    'centralScopeCity': pl.Utf8,
    'centralScopeCityDescription': pl.Utf8,
    'centralScopeDescription': pl.Utf8,
    'centralState': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralTerritoryDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeAll': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'company': pl.Utf8,
    'competitionCode': pl.Utf8,
    'competitionCodeDescription': pl.Utf8,
    'corporateType': pl.Utf8,
    'corporateTypeDescription': pl.Utf8,
    'country': pl.Utf8,
    'countryDescription': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNo': pl.Utf8,
    'first': pl.Utf8,
    'gender': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYn': pl.Utf8,
    'holdCode': pl.Utf8,
    'iATANumber': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'interest': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailAction': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'middle': pl.Utf8,
    'nameId': pl.Float64,
    'nationalityCode': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'negotiatedRate': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Float64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'priority': pl.Utf8,
    'priorityDescription': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileLanguageDescription': pl.Utf8,
    'profilePrivacyFlg': pl.Utf8,
    'profileType': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'profileTypeDescription': pl.Utf8,
    'protected': pl.Utf8,
    'referenceCurrency': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repMailActionDesc': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDecription': pl.Utf8,
    'scopeDescription': pl.Utf8,
    'searchAccountName': pl.Utf8,
    'sfirst': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDesc': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDescription': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceCodeDescription': pl.Utf8,
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
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}

external_references_details_schema = {
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'extCancellationNo': pl.Utf8,
    'externalReferenceLegNumber': pl.Float64,
    'externalReferenceNumber': pl.Utf8,
    'externalReferenceType': pl.Utf8,
    'externalStatus': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'manualYn': pl.Utf8,
    'organizationID': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'revisionToken': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'upperExternalReference': pl.Utf8,
}

reservation_membership_details_schema = {
    'cardNumberByMembershipClass': pl.Utf8,
    'cardNumberByMembershipType': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'earningPreference': pl.Utf8,
    'frequentFlyerMembershipYN': pl.Utf8,
    'hostBusinessDate': pl.Utf8,
    'hostCardinality': pl.Float64,
    'hostFlag': pl.Utf8,
    'iDByMembershipClass': pl.Utf8,
    'iDByMembershipType': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalMembershipid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'levelByMembershipType': pl.Utf8,
    'listOfMembershipIDs': pl.Float64,
    'locationID': pl.Utf8,
    'loyaltySchemeMembershipYN': pl.Utf8,
    'mbrprefChangedDate': pl.Utf8,
    'membershipCardNo': pl.Utf8,
    'membershipCardNumber': pl.Utf8,
    'membershipClass': pl.Utf8,
    'membershipClassDescription': pl.Utf8,
    'membershipCode': pl.Utf8,
    'membershipDescription': pl.Utf8,
    'membershipId': pl.Float64,
    'membershipLevel': pl.Utf8,
    'membershipLevelByMembershipClass': pl.Utf8,
    'membershipType': pl.Utf8,
    'membershipTypeByMembershipClass': pl.Utf8,
    'multiplierInstance': pl.Float64,
    'nameId': pl.Float64,
    'organizationID': pl.Float64,
    'pointsMultiplier': pl.Float64,
    'populationMethod': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'processedDate': pl.Utf8,
    'processedYn': pl.Utf8,
    'profileid': pl.Float64,
    'property': pl.Utf8,
    'rankValue': pl.Float64,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'reservationmembershipid': pl.Float64,
    'resvenddate': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

reservation_payment_methods_details_schema = {
    'authorizationAmount': pl.Float64,
    'authorizationDescription': pl.Utf8,
    'authorizationRule': pl.Float64,
    'bonusCheckId': pl.Float64,
    'centralPaymentMethodType': pl.Utf8,
    'centralPaymentMethodTypeDescription': pl.Utf8,
    'creditCardAuthorizationDate': pl.Utf8,
    'creditCardId': pl.Float64,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'directBillVerifyResponse': pl.Utf8,
    'emailAddress': pl.Utf8,
    'emailFolioYn': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'organizationID': pl.Float64,
    'paymentMethodType': pl.Utf8,
    'paymentMethodTypeDescription': pl.Utf8,
    'paymentWindow': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

profile_accounts_details_schema = {
    'aRNumber': pl.Utf8,
    'aRCUpdateDate': pl.Utf8,
    'accountEmailPrimary': pl.Utf8,
    'accountID': pl.Float64,
    'accountName': pl.Utf8,
    'accountName2': pl.Utf8,
    'accountName3': pl.Utf8,
    'accountOwnerTitle': pl.Utf8,
    'accountOwnersAll': pl.Utf8,
    'accountPhonePrimary': pl.Utf8,
    'accountPhoneWeb': pl.Utf8,
    'accountSource': pl.Utf8,
    'accountSourceDescription': pl.Utf8,
    'accountType': pl.Utf8,
    'accountTypeDescription': pl.Utf8,
    'acctContact': pl.Utf8,
    'actionCode': pl.Utf8,
    'activeFlag': pl.Utf8,
    'address1': pl.Utf8,
    'address2': pl.Utf8,
    'address3': pl.Utf8,
    'address4': pl.Utf8,
    'addressLangCodeDesc': pl.Utf8,
    'addressLanguage': pl.Utf8,
    'addressLanguageCode': pl.Utf8,
    'addressType': pl.Utf8,
    'allProperties': pl.Utf8,
    'alternateLanguage': pl.Utf8,
    'alternateLanguageDescription': pl.Utf8,
    'alternateName': pl.Utf8,
    'alternateSalutation': pl.Utf8,
    'alternateTitle': pl.Utf8,
    'arNumberCentral': pl.Utf8,
    'autoenrollMemberYn': pl.Utf8,
    'billingInstruction': pl.Utf8,
    'billingProfileCode': pl.Utf8,
    'birthDate': pl.Utf8,
    'birthDateStr': pl.Utf8,
    'birthPlace': pl.Utf8,
    'blMsg': pl.Utf8,
    'businessPotential': pl.Utf8,
    'businessPotentialDescription': pl.Utf8,
    'businessSegement': pl.Utf8,
    'businessSegementDescription': pl.Utf8,
    'businessTitle': pl.Utf8,
    'centralAccountOwnerTitle': pl.Utf8,
    'centralAccountSource': pl.Utf8,
    'centralAccountSourceDescription': pl.Utf8,
    'centralAccountType': pl.Utf8,
    'centralAccountTypeDescription': pl.Utf8,
    'centralBusinessPotential': pl.Utf8,
    'centralBusinessPotentialDescription': pl.Utf8,
    'centralBusinessSegementDescription': pl.Utf8,
    'centralBusinessSegment': pl.Utf8,
    'centralCompetitionCode': pl.Utf8,
    'centralCompetitionCodeDescription': pl.Utf8,
    'centralCorporateType': pl.Utf8,
    'centralCorporateTypeDescription': pl.Utf8,
    'centralInactiveReason': pl.Utf8,
    'centralInactiveReasonDescription': pl.Utf8,
    'centralIndustryCode': pl.Utf8,
    'centralIndustryCodeDescription': pl.Utf8,
    'centralKeyword': pl.Utf8,
    'centralPriority': pl.Utf8,
    'centralPriorityDescription': pl.Utf8,
    'centralProfileTypeCode': pl.Utf8,
    'centralProfileTypeDescription': pl.Utf8,
    'centralScope': pl.Utf8,
    'centralScopeCity': pl.Utf8,
    'centralScopeCityDescription': pl.Utf8,
    'centralScopeDescription': pl.Utf8,
    'centralState': pl.Utf8,
    'centralTerritory': pl.Utf8,
    'centralTerritoryDescription': pl.Utf8,
    'chainCode': pl.Utf8,
    'city': pl.Utf8,
    'cityExt': pl.Utf8,
    'combinedName': pl.Utf8,
    'commissionCode': pl.Utf8,
    'commissionCodeAll': pl.Utf8,
    'communicationRole1': pl.Utf8,
    'communicationRole2': pl.Utf8,
    'communicationRole3': pl.Utf8,
    'communicationType1': pl.Utf8,
    'communicationType2': pl.Utf8,
    'communicationType3': pl.Utf8,
    'communicationValue1': pl.Utf8,
    'communicationValue2': pl.Utf8,
    'communicationValue3': pl.Utf8,
    'company': pl.Utf8,
    'competitionCode': pl.Utf8,
    'competitionCodeDescription': pl.Utf8,
    'corporateType': pl.Utf8,
    'corporateTypeDescription': pl.Utf8,
    'country': pl.Utf8,
    'countryDescription': pl.Utf8,
    'createdByUser': pl.Utf8,
    'createdOnDate': pl.Utf8,
    'creditCardName': pl.Utf8,
    'creditCardType': pl.Utf8,
    'creditRating': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'emailYn': pl.Utf8,
    'envelopeGreeting': pl.Utf8,
    'externalId': pl.Utf8,
    'fSubscriptionDb': pl.Utf8,
    'fSubscriptionYn': pl.Utf8,
    'faxNo': pl.Utf8,
    'first': pl.Utf8,
    'gender': pl.Utf8,
    'guestPrivYn': pl.Utf8,
    'historyYn': pl.Utf8,
    'holdCode': pl.Utf8,
    'iATANumber': pl.Utf8,
    'iataConsortia': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveFlag': pl.Utf8,
    'inactiveReason': pl.Utf8,
    'inactiveReasonDescription': pl.Utf8,
    'industryCode': pl.Utf8,
    'industryCodeDescription': pl.Utf8,
    'interest': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalInactiveflag': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'keyword': pl.Utf8,
    'last': pl.Utf8,
    'lastGroup': pl.Utf8,
    'lastRate': pl.Float64,
    'lastRoom': pl.Utf8,
    'lastSource': pl.Utf8,
    'lastStay': pl.Utf8,
    'legalCompany': pl.Utf8,
    'letterGreeting': pl.Utf8,
    'mailAction': pl.Utf8,
    'mailActionDescription': pl.Utf8,
    'mailList': pl.Utf8,
    'mailType': pl.Utf8,
    'mailYn': pl.Utf8,
    'marketResearchYn': pl.Utf8,
    'middle': pl.Utf8,
    'nameId': pl.Float64,
    'nationalityCode': pl.Utf8,
    'nationalityDescription': pl.Utf8,
    'negotiatedRate': pl.Utf8,
    'nextStay': pl.Utf8,
    'nickname': pl.Utf8,
    'organizationID': pl.Float64,
    'paymentDueDays': pl.Float64,
    'postalCode': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'primaryOwner': pl.Utf8,
    'primaryOwnerCode': pl.Utf8,
    'priority': pl.Utf8,
    'priorityDescription': pl.Utf8,
    'productInterest': pl.Utf8,
    'profession': pl.Utf8,
    'profileLanguageDescription': pl.Utf8,
    'profilePrivacyFlg': pl.Utf8,
    'profileType': pl.Utf8,
    'profileTypeCode': pl.Utf8,
    'profileTypeDescription': pl.Utf8,
    'protected': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'referenceCurrency': pl.Utf8,
    'repInfluence': pl.Utf8,
    'repInfluenceDescription': pl.Utf8,
    'repMailActionCodes': pl.Utf8,
    'repMailActionDesc': pl.Utf8,
    'repNationalityCode': pl.Utf8,
    'repNationalityDescription': pl.Utf8,
    'repStateDescription': pl.Utf8,
    'repTaxTypeDescription': pl.Utf8,
    'repTitleName': pl.Utf8,
    'repVIPName': pl.Utf8,
    'repVIPStatus': pl.Utf8,
    'replaceAddress': pl.Utf8,
    'resortRegistered': pl.Utf8,
    'restricted': pl.Utf8,
    'restrictedRule': pl.Utf8,
    'salutation': pl.Utf8,
    'scope': pl.Utf8,
    'scopeCity': pl.Utf8,
    'scopeCityDecription': pl.Utf8,
    'scopeDescription': pl.Utf8,
    'searchAccountName': pl.Utf8,
    'sfirst': pl.Utf8,
    'state': pl.Utf8,
    'stateCode': pl.Utf8,
    'stateDesc': pl.Utf8,
    'sxfirstName': pl.Utf8,
    'sxname': pl.Utf8,
    'tax1No': pl.Utf8,
    'tax2No': pl.Utf8,
    'taxCategory': pl.Utf8,
    'taxType': pl.Utf8,
    'taxTypeDescription': pl.Utf8,
    'territory': pl.Utf8,
    'territoryDescription': pl.Utf8,
    'thirdPartyYn': pl.Utf8,
    'traceCode': pl.Utf8,
    'traceCodeDescription': pl.Utf8,
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
    'vipName': pl.Utf8,
    'vipStatus': pl.Utf8,
    'xcompanyName': pl.Utf8,
    'xenvelopeGreeting': pl.Utf8,
    'xfirstName': pl.Utf8,
    'xlastName': pl.Utf8,
    'xmiddleName': pl.Utf8,
}

reservation_deposit_schedule_details_schema = {
    'activityDeposit': pl.Float64,
    'cActivityDeposit': pl.Float64,
    'cCancelPnltyAmount': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cForeignDepositAmount': pl.Float64,
    'cancelDeadline': pl.Utf8,
    'cancelPnltyAmount': pl.Float64,
    'centralDepositAmountOutstanding': pl.Float64,
    'centralDepositAmountRequested': pl.Float64,
    'centralTotalDepositPayments': pl.Float64,
    'comments': pl.Utf8,
    'dSI': pl.Float64,
    'deletedFlag': pl.Utf8,
    'depositAmountOutstanding': pl.Float64,
    'depositAmountRequested': pl.Float64,
    'depositDueDate': pl.Utf8,
    'depositPercentage': pl.Float64,
    'depositReqLinkId': pl.Float64,
    'depositReqReceiptNo': pl.Float64,
    'depositReqReversalYn': pl.Utf8,
    'depositRule': pl.Utf8,
    'depositRuleDescription': pl.Utf8,
    'depositRuleType': pl.Utf8,
    'depositScheduleReservationNameId': pl.Float64,
    'depositType': pl.Utf8,
    'dmlSeqNumber': pl.Float64,
    'exchangeRateInfo': pl.Utf8,
    'externalId': pl.Utf8,
    'foreignDepositAmount': pl.Float64,
    'insertActionInstanceId': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'manualYn': pl.Utf8,
    'organizationID': pl.Float64,
    'paymentFlag': pl.Utf8,
    'primaryKeyID': pl.Float64,
    'processedYn': pl.Utf8,
    'productId': pl.Utf8,
    'property': pl.Utf8,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'rateDcSeq': pl.Float64,
    'reservationDepositScheduleId': pl.Float64,
    'roomDeposit': pl.Float64,
    'totalDepositPayments': pl.Float64,
    'trxDate': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

rate_code_details_details_schema = {
    'addAfterRounding': pl.Float64,
    'adultCharge': pl.Float64,
    'adultsThreshold': pl.Float64,
    'adultsThresholdCharge': pl.Float64,
    'advBaseAmount': pl.Float64,
    'advBaseFltPct': pl.Utf8,
    'advDailyBaseRateCode': pl.Utf8,
    'advanceBaseCompareYN': pl.Utf8,
    'ageRangeForBucket1': pl.Utf8,
    'ageRangeForBucket2': pl.Utf8,
    'ageRangeForBucket3': pl.Utf8,
    'amount1Type': pl.Utf8,
    'amount2Type': pl.Utf8,
    'amount3Type': pl.Utf8,
    'amount4Type': pl.Utf8,
    'amount5Type': pl.Utf8,
    'amountFor1Person': pl.Float64,
    'amountFor2Persons': pl.Float64,
    'amountFor3Persons': pl.Float64,
    'amountFor4Persons': pl.Float64,
    'amountFor5Persons': pl.Float64,
    'barAmount': pl.Float64,
    'barFltPct': pl.Utf8,
    'barRounding': pl.Utf8,
    'barYn': pl.Utf8,
    'cAdultCharge': pl.Float64,
    'cAdultsThresholdCharge': pl.Float64,
    'cAdvanceBaseAmount': pl.Float64,
    'cAmount1': pl.Float64,
    'cAmount2': pl.Float64,
    'cAmount3': pl.Float64,
    'cAmount4': pl.Float64,
    'cAmount5': pl.Float64,
    'cBarAmount': pl.Float64,
    'cChildCharge1': pl.Float64,
    'cChildCharge2': pl.Float64,
    'cChildCharge3': pl.Float64,
    'cChildOwnCharge1': pl.Float64,
    'cChildOwnCharge2': pl.Float64,
    'cChildOwnCharge3': pl.Float64,
    'cChildOwnCharge4': pl.Float64,
    'cChildrenCharge': pl.Float64,
    'cChildrenThresholdCharge': pl.Float64,
    'cDifferenceAmount1': pl.Float64,
    'cDifferenceAmount2': pl.Float64,
    'cDifferenceAmount3': pl.Float64,
    'cDifferenceAmount4': pl.Float64,
    'cDifferenceAmount5': pl.Float64,
    'cDifferenceAmountExtraAdult': pl.Float64,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cFlatIncrease': pl.Float64,
    'cLos1Amount': pl.Float64,
    'cLos10Amount': pl.Float64,
    'cLos11Amount': pl.Float64,
    'cLos12Amount': pl.Float64,
    'cLos13Amount': pl.Float64,
    'cLos14Amount': pl.Float64,
    'cLos2Amount': pl.Float64,
    'cLos3Amount': pl.Float64,
    'cLos4Amount': pl.Float64,
    'cLos5Amount': pl.Float64,
    'cLos6Amount': pl.Float64,
    'cLos7Amount': pl.Float64,
    'cLos8Amount': pl.Float64,
    'cLos9Amount': pl.Float64,
    'cMaximumAmount1': pl.Float64,
    'cMaximumAmount2': pl.Float64,
    'cMinimumAmount1': pl.Float64,
    'cMinimumAmount2': pl.Float64,
    'cOccupantsThresholdCharge': pl.Float64,
    'cPackageRateStayOver': pl.Float64,
    'cRoomCost': pl.Float64,
    'calculationFlag': pl.Utf8,
    'catPackagePriceCode': pl.Utf8,
    'centralMarketCode': pl.Utf8,
    'centralMarketDescription': pl.Utf8,
    'centralMarketGroupCode': pl.Utf8,
    'centralMarketGroupDescription': pl.Utf8,
    'centralPackageCode': pl.Utf8,
    'centralRoomType': pl.Utf8,
    'centralRoomTypeDescription': pl.Utf8,
    'centralSeasonCode': pl.Utf8,
    'centralSourceCode': pl.Utf8,
    'centralSourceDescription': pl.Utf8,
    'centralSourceGroupCode': pl.Utf8,
    'centralSourceGroupDescription': pl.Utf8,
    'childExcThreshold1': pl.Utf8,
    'childExcThreshold2': pl.Utf8,
    'childExcThreshold3': pl.Utf8,
    'childOwnCharge1': pl.Float64,
    'childOwnCharge2': pl.Float64,
    'childOwnCharge3': pl.Float64,
    'childOwnCharge4': pl.Float64,
    'childrenFreeStay': pl.Float64,
    'childrenCharge': pl.Float64,
    'childrenThreshold': pl.Float64,
    'childrenThresholdCharge': pl.Float64,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Float64,
    'deletedflag': pl.Utf8,
    'depositRequieredYn': pl.Utf8,
    'differenceAmount1': pl.Float64,
    'differenceAmount2': pl.Float64,
    'differenceAmount3': pl.Float64,
    'differenceAmount4': pl.Float64,
    'differenceAmount5': pl.Float64,
    'differenceAmountExtraAdult': pl.Float64,
    'differencePercentage1Yn': pl.Utf8,
    'differencePercentage2Yn': pl.Utf8,
    'differencePercentage3Yn': pl.Utf8,
    'differencePercentage4Yn': pl.Utf8,
    'differencePercentage5Yn': pl.Utf8,
    'differencePercentageExtraAdultYn': pl.Utf8,
    'endDate': pl.Utf8,
    'externalRateSetId': pl.Float64,
    'extraAdultType': pl.Utf8,
    'flatIncrease': pl.Float64,
    'globalRateUpdateYn': pl.Utf8,
    'inactiveDate': pl.Utf8,
    'inactiveflag': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'internalLocationId': pl.Utf8,
    'internalOrganizationId': pl.Float64,
    'internalRatesetid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'lengthOfStay1Amount': pl.Float64,
    'lengthOfStay10Amount': pl.Float64,
    'lengthOfStay11Amount': pl.Float64,
    'lengthOfStay12Amount': pl.Float64,
    'lengthOfStay13Amount': pl.Float64,
    'lengthOfStay14Amount': pl.Float64,
    'lengthOfStay2Amount': pl.Float64,
    'lengthOfStay3Amount': pl.Float64,
    'lengthOfStay4Amount': pl.Float64,
    'lengthOfStay5Amount': pl.Float64,
    'lengthOfStay6Amount': pl.Float64,
    'lengthOfStay7Amount': pl.Float64,
    'lengthOfStay8Amount': pl.Float64,
    'lengthOfStay9Amount': pl.Float64,
    'linkRateSetId': pl.Float64,
    'locationID': pl.Utf8,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'marketGroupCode': pl.Utf8,
    'marketGroupDescription': pl.Utf8,
    'maximumAmount1': pl.Float64,
    'maximumAmount2': pl.Float64,
    'minChildrenForFreeStay': pl.Float64,
    'minimumAmount1': pl.Float64,
    'minimumAmount2': pl.Float64,
    'minimumClosingProbability': pl.Float64,
    'occupantsThreshold': pl.Float64,
    'occupantsThresholdCharge': pl.Float64,
    'organizationID': pl.Float64,
    'packageAdultStayOver': pl.Float64,
    'packageChildrenStayOver': pl.Float64,
    'packageCode': pl.Utf8,
    'packageRateStayOver': pl.Float64,
    'percentIncrease': pl.Float64,
    'pointsRequired': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'rateAvailableOnFridaysYN': pl.Utf8,
    'rateAvailableOnMondaysYN': pl.Utf8,
    'rateAvailableOnSaturdaysYN': pl.Utf8,
    'rateAvailableOnSundaysYN': pl.Utf8,
    'rateAvailableOnThursdaysYN': pl.Utf8,
    'rateAvailableOnTuesdaysYN': pl.Utf8,
    'rateAvailableOnWednesdaysYN': pl.Utf8,
    'rateCode': pl.Utf8,
    'rateCodeDesc': pl.Utf8,
    'rateCodeId': pl.Utf8,
    'rateRule': pl.Utf8,
    'rateSetId': pl.Float64,
    'rateForChildInAgeBucket1': pl.Float64,
    'rateForChildInAgeBucket2': pl.Float64,
    'rateForChildInAgeBucket3': pl.Float64,
    'ratesActiveYn': pl.Utf8,
    'ratetierid': pl.Float64,
    'repSeasonDescription': pl.Utf8,
    'rnaInsertDate': pl.Utf8,
    'rnaUpdateDate': pl.Utf8,
    'roomCost': pl.Float64,
    'roomType': pl.Utf8,
    'roomTypeDescription': pl.Utf8,
    'roundToNearest': pl.Float64,
    'season': pl.Utf8,
    'seasonCode': pl.Utf8,
    'seasonDesc': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'sourceGroupCode': pl.Utf8,
    'sourceGroupDescription': pl.Utf8,
    'startDate': pl.Utf8,
    'tierId': pl.Float64,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
}

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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
    'instructionSummary': pl.Utf8,
    'internalDeletedflag': pl.Utf8,
    'internalMembershipid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'membershipId': pl.Float64,
    'mondayYN': pl.Utf8,
    'organizationID': pl.Float64,
    'payeeFirstName': pl.Utf8,
    'payeeLastName': pl.Utf8,
    'payeeNameID': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
    'wednesdayYN': pl.Utf8,
}

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

financial_unified_details_schema = {
    'aRChargeTransferFlagYN': pl.Utf8,
    'aRLedgerCredit': pl.Float64,
    'aRLedgerDebit': pl.Float64,
    'aRState': pl.Utf8,
    'aRTransferDate': pl.Utf8,
    'accountCode': pl.Float64,
    'accountNumber': pl.Utf8,
    'addressId': pl.Float64,
    'advanceBillReversedYN': pl.Utf8,
    'advanceBillYn': pl.Utf8,
    'advancedGenerateYN': pl.Utf8,
    'advgenTtransCodeID': pl.Utf8,
    'arrangementCode': pl.Utf8,
    'arrangementDesc': pl.Utf8,
    'articleId': pl.Float64,
    'associatedTrxNumber': pl.Float64,
    'attachedToUser': pl.Utf8,
    'authEmployeeID': pl.Float64,
    'authorizer': pl.Utf8,
    'autoCreditbillYn': pl.Utf8,
    'autoSettleYn': pl.Utf8,
    'businessDate': pl.Utf8,
    'cCApproval': pl.Utf8,
    'cashierCode': pl.Float64,
    'cashierCredit': pl.Float64,
    'cashierDebit': pl.Float64,
    'cashierID': pl.Float64,
    'cashierName': pl.Utf8,
    'cashierOpeningBalance': pl.Float64,
    'ccRefundPosting': pl.Utf8,
    'changesLogCheckIn': pl.Utf8,
    'changesLogCheckOut': pl.Utf8,
    'changesLogCloseFolio': pl.Utf8,
    'changesLogReopenFolio': pl.Utf8,
    'changesLogUpdateReservation': pl.Utf8,
    'checkNumber': pl.Utf8,
    'closureNumber': pl.Float64,
    'comments': pl.Utf8,
    'compLinkTrxCode': pl.Utf8,
    'compLinkTrxNumber': pl.Float64,
    'compTypeCode': pl.Utf8,
    'compressedYn': pl.Utf8,
    'covers': pl.Utf8,
    'creditCardId': pl.Float64,
    'creditCardSurcharge': pl.Float64,
    'creditYN': pl.Utf8,
    'currencyCode': pl.Utf8,
    'currencyDescription': pl.Utf8,
    'dSI': pl.Float64,
    'debitYN': pl.Utf8,
    'decimals': pl.Float64,
    'deferredYn': pl.Utf8,
    'depPostingFlag': pl.Utf8,
    'depTaxTransferedYn': pl.Utf8,
    'depositLedgerCredit': pl.Float64,
    'depositLedgerDebit': pl.Float64,
    'depositTransactionId': pl.Utf8,
    'displayYN': pl.Utf8,
    'euroExchangeRate': pl.Float64,
    'exchangeDate': pl.Utf8,
    'exchangeDifferenceYN': pl.Utf8,
    'exchangeRate': pl.Float64,
    'exchangeType': pl.Utf8,
    'financialDmlSeqNumber': pl.Float64,
    'fiscalBillNo': pl.Utf8,
    'fixedChargesYN': pl.Utf8,
    'folio': pl.Float64,
    'folioNo': pl.Float64,
    'folioType': pl.Utf8,
    'folioView': pl.Float64,
    'foreignCurrencyCode': pl.Utf8,
    'fromReservationId': pl.Float64,
    'ftGeneratedType': pl.Utf8,
    'ftSubtype': pl.Utf8,
    'genCashierId': pl.Float64,
    'generalCashierYN': pl.Utf8,
    'grossAmount': pl.Float64,
    'guestAccountLedgerCredit': pl.Float64,
    'guestAccountLedgerDebit': pl.Float64,
    'inHouseCredit': pl.Float64,
    'inHouseDebit': pl.Float64,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'insertUserName': pl.Utf8,
    'interfaceCashierYN': pl.Utf8,
    'internalArticleid': pl.Float64,
    'internalWindowId': pl.Float64,
    'internalYN': pl.Utf8,
    'invoiceCloseDate': pl.Utf8,
    'invoiceNumber': pl.Float64,
    'invoiceType': pl.Utf8,
    'linkTrxNumber': pl.Float64,
    'marketCode': pl.Utf8,
    'marketDescription': pl.Utf8,
    'membershipID': pl.Float64,
    'mtrxNoAgainstPackage': pl.Float64,
    'nameTaxType': pl.Utf8,
    'netAmount': pl.Float64,
    'nonRevenueAmount': pl.Float64,
    'numberDialed': pl.Utf8,
    'organizationID': pl.Float64,
    'originalARLedgerDebit': pl.Float64,
    'originalBillNumber': pl.Float64,
    'originalFolioNumber': pl.Utf8,
    'originalReservationNameId': pl.Float64,
    'originalRoom': pl.Utf8,
    'package': pl.Utf8,
    'packageAllowance': pl.Float64,
    'packageArrangementCode': pl.Utf8,
    'packageLedgerCredit': pl.Float64,
    'packageLedgerDebit': pl.Float64,
    'packageTrxType': pl.Utf8,
    'passerByName': pl.Utf8,
    'payeeNameID': pl.Float64,
    'payeeResvNameID': pl.Float64,
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
    'primaryKeyID': pl.Float64,
    'profileID': pl.Float64,
    'profitLossFlag': pl.Utf8,
    'proformaYN': pl.Utf8,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'queueName': pl.Utf8,
    'rateCode': pl.Utf8,
    'receiptNumber': pl.Float64,
    'receiptType': pl.Utf8,
    'repTransactionCode': pl.Utf8,
    'repTransactionCodeGroup': pl.Utf8,
    'repTransactionCodeGroupDescription': pl.Utf8,
    'repTransactionCodeSubgroup': pl.Utf8,
    'repTransactionCodeSubgroupDescription': pl.Utf8,
    'reservationDepositId': pl.Float64,
    'reservationNameID': pl.Float64,
    'revenueAmount': pl.Float64,
    'reversePaymentTrxNumber': pl.Float64,
    'roomClass': pl.Utf8,
    'roomNts': pl.Float64,
    'roomNtsEffective': pl.Float64,
    'roomNumber': pl.Utf8,
    'roundFactorYn': pl.Utf8,
    'roundLinkTrxno': pl.Float64,
    'routedYn': pl.Utf8,
    'routingCode': pl.Utf8,
    'routingCodeDescription': pl.Utf8,
    'routingDate': pl.Utf8,
    'routingIinstructionID': pl.Float64,
    'routingInstrnId': pl.Float64,
    'routingType': pl.Utf8,
    'settlementFlag': pl.Utf8,
    'sourceCode': pl.Utf8,
    'sourceDescription': pl.Utf8,
    'supplement': pl.Utf8,
    'tRXCode': pl.Utf8,
    'targetResort': pl.Utf8,
    'taxDeferredUntilCheckOutYN': pl.Utf8,
    'taxElements': pl.Utf8,
    'taxGeneratedYN': pl.Utf8,
    'taxInclusiveYN': pl.Utf8,
    'tcGroup': pl.Utf8,
    'tcSubgroup': pl.Utf8,
    'thresholdDiversionId': pl.Float64,
    'thresholdEntityQty': pl.Float64,
    'thresholdEntityType': pl.Utf8,
    'thresholdTreatmentFlag': pl.Utf8,
    'toReservationNameId': pl.Float64,
    'tranActionId': pl.Float64,
    'transCodeArrangementID': pl.Float64,
    'transactionActivityDate': pl.Utf8,
    'transactionCodeDescription': pl.Utf8,
    'transactionCodeGroupDesc': pl.Utf8,
    'transactionCodeSubgroupDesc': pl.Utf8,
    'transactionDate': pl.Utf8,
    'transactionNumberAddedBy': pl.Float64,
    'transactionPostingDate': pl.Utf8,
    'transactionPostingTime': pl.Utf8,
    'transactionPostingTimeWithSeconds': pl.Utf8,
    'transactionType': pl.Utf8,
    'transactionFromAccount': pl.Float64,
    'transactionToAccount': pl.Float64,
    'transferFromAccountID': pl.Float64,
    'transferToAccountID': pl.Float64,
    'trxNo': pl.Float64,
    'trxNoAgainstPackage': pl.Float64,
    'trxNumberAdjust': pl.Float64,
    'trxNumberHeader': pl.Float64,
    'trxNumberSplit': pl.Float64,
    'trxServiceType': pl.Utf8,
    'updateDate': pl.Utf8,
    'updateUser': pl.Float64,
    'vatAmount': pl.Float64,
}

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
    'dSI': pl.Float64,
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
    'insertUser': pl.Float64,
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
    'organizationID': pl.Float64,
    'ovosGradeCode': pl.Utf8,
    'ovosUnitYn': pl.Utf8,
    'pcode': pl.Utf8,
    'personDiscrepancy': pl.Float64,
    'phoneNumber': pl.Utf8,
    'physicalNumberOfRooms': pl.Float64,
    'pickupCredits': pl.Float64,
    'primaryKeyID': pl.Float64,
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
    'updateUser': pl.Float64,
    'visibleOnWebYn': pl.Utf8,
    'webBookingYn': pl.Utf8,
    'weightF': pl.Float64,
    'weightM': pl.Float64,
    'widthF': pl.Float64,
    'widthM': pl.Float64,
}

fixed_charges_details_schema = {
    'accountCode': pl.Float64,
    'accountid': pl.Float64,
    'amountOrPercentage': pl.Float64,
    'amountOrPercentageFlag': pl.Utf8,
    'articleId': pl.Float64,
    'beginDateNullable': pl.Utf8,
    'businessDate': pl.Utf8,
    'cExchangeDate': pl.Utf8,
    'cExchangeRate': pl.Float64,
    'cPrice': pl.Float64,
    'centralTransactionCode': pl.Utf8,
    'centralTransactionCodeDescription': pl.Utf8,
    'dSI': pl.Float64,
    'daytoexecute': pl.Utf8,
    'deletedFlag': pl.Utf8,
    'endDate': pl.Utf8,
    'endDateNullable': pl.Utf8,
    'fixedChargesId': pl.Float64,
    'fixedchargespmsref': pl.Float64,
    'frequency': pl.Utf8,
    'insertDate': pl.Utf8,
    'insertUser': pl.Float64,
    'insertUserName': pl.Utf8,
    'internalArticleid': pl.Float64,
    'internalFixedchargesid': pl.Float64,
    'jRNUpdateDate': pl.Utf8,
    'jRNUpdateDateAndTime': pl.Utf8,
    'locationID': pl.Utf8,
    'organizationID': pl.Float64,
    'percentage': pl.Float64,
    'price': pl.Float64,
    'primaryKeyID': pl.Float64,
    'property': pl.Utf8,
    'quantity': pl.Float64,
    'rNAInsertDate': pl.Utf8,
    'rNAUpdateDate': pl.Utf8,
    'reservationNameId': pl.Float64,
    'reservationid': pl.Float64,
    'resvenddate': pl.Utf8,
    'roomnights': pl.Float64,
    'supplement': pl.Utf8,
    'transactionCode': pl.Utf8,
    'transactionCodeDescription': pl.Utf8,
    'transactionCodeGroup': pl.Float64,
    'transactionCodeSubGroup': pl.Float64,
    'transactionCodeType': pl.Utf8,
    'transcodeid': pl.Utf8,
    'updateUser': pl.Float64,
    'updatedate': pl.Utf8,
    'yearlyfixedchargedate': pl.Utf8,
}

```