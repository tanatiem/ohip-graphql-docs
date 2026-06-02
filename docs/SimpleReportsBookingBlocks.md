# SimpleReportsBookingBlocks
[Object Types](#object-types) | [Input Types](#input-types) | [Query Template](#query-template)
## Query
### `simpleReportsBookingBlocks`
> The Simple Reports Booking Blocks Subject Area simplifies creating and building adhoc reports including the ability to create new reports.
  
**Return:** [`[SimpleReportsBookingBlocksType]`](#simplereportsbookingblockstype)  
**Arguments:**  
| Name | Type | Description |
| --- | --- | --- |
| limit | `Int` |  |
| offset | `Int` |  |
| input | [`SimpleReportsBookingBlocksQueryArgumentsType!`](#simplereportsbookingblocksqueryargumentstype) |  |

## Object Types

### SimpleReportsBookingBlocksType

| Field | Type | Description |
| --- | --- | --- |
| salesEventBusinessBlockInformationDetails | [`SimpleReportsBookingBlocksSalesEventBusinessBlockInformationDetailsType`](#simplereportsbookingblockssaleseventbusinessblockinformationdetailstype) | Sales Event Business Block Information |
| propertyPropertyDetails | [`SimpleReportsBookingBlocksPropertyPropertyDetailsType`](#simplereportsbookingblockspropertypropertydetailstype) | Resort Details |
| simpleReportsBookingBlocksRecordCount | `Int` |  |

[⬆ Back to Query](#query)

---

### SimpleReportsBookingBlocksSalesEventBusinessBlockInformationDetailsType

| Field | Type | Description |
| --- | --- | --- |
| accountActionCode | `String` | Account Action Code |
| accountActiveYN | `String` | Acc Active Y/N |
| accountAddressType | `String` | Account Address Type |
| accountAddress1 | `String` | Account Address1 |
| accountAddress2 | `String` | Account Address2 |
| accountAlternateLanguage | `String` | Account Alternate Language |
| accountAlternateLanguageDesc | `String` | Acc Xlanguage Description |
| accountAlternateSalutation | `String` | Account Alternate Salutation |
| accountAlternateTitle | `String` | Account Alternate Title |
| accountArNumber | `String` | Acc AR No |
| accountAvailoverYN | `String` | Acc Availover Y/N |
| accountBlMsg | `String` | Account Bl Msg |
| accountBookingId | `Float` | Acc Booking ID |
| accountCblIndividual | `String` | Account Cbl Ind |
| accountCity | `String` | Account City. |
| accountCityExt | `String` | Account City Ext |
| accountCommissionCode | `String` | Account Commission Code |
| accountCompetitionCode | `String` | Account Competition Code |
| accountCountry | `String` | Account Country. |
| accountCountryDesc | `String` | Acc Country Description |
| accountDsi | `Float` | Account Dsi |
| accountEmail | `String` | Account Email |
| accountFax | `String` | Account Fax |
| accountHistoryYN | `String` | Acc History Y/N |
| accountHoldCode | `String` | Account Hold Code |
| accountIATACompType | `String` | Account Iata Comp Type |
| accountId | `Float` | Acc ID |
| accountIndustryCode | `String` | Account Industry Code |
| accountKeyword | `String` | Account Keyword |
| accountLanguage | `String` | Account Language |
| accountLanguageDesc | `String` | Acc Language Description |
| accountLinkId | `Float` | Acc Link ID |
| accountLinkType | `String` | Account Link Type |
| accountMailList | `String` | Account Mail List |
| accountMailType | `String` | Account Mail Type |
| accountMarkets | `String` | Account Markets |
| accountName | `String` | Account Name |
| accountNameKeywords | `String` | Account Name Keywords |
| accountNameType | `String` | Account Name Type |
| accountName2 | `String` | Account Name2 |
| accountName3 | `String` | Account Name3 |
| accountOrganizationid | `Float` | Account Organizationid |
| accountPhone | `String` | Account Phone |
| accountPhoneId | `Float` | Acc Phone ID |
| accountPhoneNumber | `String` | Account Phone No. |
| accountPrimaryYN | `String` | Acc Primary Y/N |
| accountPriority | `String` | Account Priority |
| accountProductInterest | `String` | Account Product Interest |
| accountProperty | `String` | Account Resort |
| accountRelationship | `String` | Account Relationship |
| accountRelationshipDesc | `String` | Acc Relationship Description |
| accountRepActionCode | `String` | Acc Reporting Actioncode |
| accountRepCompetionCode | `String` | Acc Reporting Competion Code |
| accountRepIATACompType | `String` | Acc Reporting Iata Comp Type |
| accountRepIndustryCode | `String` | Acc Reporting Industry Code |
| accountRepMarkets | `String` | Acc Reporting Markets |
| accountRepNameType | `String` | Acc Reporting Name Type |
| accountRepScope | `String` | Acc Reporting Scope |
| accountRepScopeCity | `String` | Acc Reporting Scope City |
| accountRepSource | `String` | Acc Reporting Source |
| accountRepStateCode | `String` | Acc Reporting State Code |
| accountRepStateDescription | `String` | Acc Reporting State Desc |
| accountRepTerritory | `String` | Acc Reporting Territory |
| accountRepType | `String` | Acc Reporting Type |
| accountRoomsPotential | `String` | Account Rooms Potential |
| accountScope | `String` | Account Scope |
| accountScopeCity | `String` | Account Scope City |
| accountSname | `String` | Account Sname |
| accountSource | `String` | Account Source |
| accountSrepCode | `String` | Account Srep Code |
| accountState | `String` | Account State. |
| accountStateDesc | `String` | Acc State Description |
| accountSxname | `String` | Account Sxname |
| accountTerritory | `String` | Account Territory |
| accountType | `String` | Account Type |
| accountXdisplayName | `String` | Account Xdisplay Name |
| accountXenvelopeGreeting | `String` | Account Xenvelope Greeting |
| accountXfirstName | `String` | Account Xfirst Name |
| accountZipcode | `String` | Account Zipcode |
| actionId | `Float` | Action ID |
| agentActiveYn | `String` | Agent Active Y/N |
| agentAddressType | `String` | Agent Address Type |
| agentAddress1 | `String` | Agent Address1 |
| agentAddress2 | `String` | Agent Address2 |
| agentAlternateLanguage | `String` | Agent Alternate Language |
| agentAlternateLanguageDesc | `String` | Agent Xlanguage Description |
| agentAlternateSalutation | `String` | Agent Alternate Salutation |
| agentAlternateTitle | `String` | Agent Alternate Title |
| agentArNumber | `String` | Agent AR No |
| agentAuSrepCode | `String` | Agent Au Srep Code |
| agentAvailabilityOverride | `String` | Agent Availability Override |
| agentBookingId | `Float` | Agent Booking ID |
| agentCblInd | `String` | Agent Cbl Individual |
| agentCity | `String` | Agent City |
| agentCityExt | `String` | Agent City Ext |
| agentConActionCode | `String` | Agent Con Action Code |
| agentConActiveYn | `String` | Agent Con Active Y/N |
| agentConAddressType | `String` | Agent Con Address Type |
| agentConAddress1 | `String` | Agent Con Address1 |
| agentConAddress2 | `String` | Agent Con Address2 |
| agentConAddress3 | `String` | Agent Con Address3 |
| agentConAddress4 | `String` | Agent Con Address4 |
| agentConAlternateLanguage | `String` | Agent Con Alternate Language |
| agentConAlternateLanguageDesc | `String` | Agent Con Xlanguage Description |
| agentConAlternateSalutation | `String` | Agent Con Alternate Salutation |
| agentConAlternateTitle | `String` | Agent Con Alternate Title |
| agentConArNumber | `String` | Agent Con AR No |
| agentConAuSrepCode | `String` | Agent Con Au Srep Code |
| agentConAvailabilityOverride | `String` | Agent Con Availability Override |
| agentConBirthDate | `Date` | Agent Con Birth Date |
| agentConBirthDateStr | `String` | Agent Con Birth Date Str |
| agentConBookingId | `Float` | Agent Con Booking ID |
| agentConBusinessGreeting | `String` | Agent Con Business Greeting |
| agentConCashBlInd | `String` | Agent Con Cash Bl Individual |
| agentConCity | `String` | Agent Con City |
| agentConCityExt | `String` | Agent Con City Ext |
| agentConContactYn | `String` | Agent Con Contact Y/N |
| agentConCountry | `String` | Agent Con Country |
| agentConCountryDesc | `String` | Agent Con Country Description |
| agentConDepartment | `String` | Agent Con Department |
| agentConDsi | `Float` | Agent Con Dsi |
| agentConEmail | `String` | Agent Con Email |
| agentConFax | `String` | Agent Con Fax |
| agentConFirst | `String` | Agent Con First |
| agentConHistoryYn | `String` | Agent Con History Y/N |
| agentConIataCompType | `String` | Agent Con IATA Comp Type |
| agentConId | `Float` | Agent Con ID |
| agentConIndustryCode | `String` | Agent Con Industry Code |
| agentConInfluence | `String` | Agent Con Influence |
| agentConLanguage | `String` | Agent Con Language |
| agentConLanguageDesc | `String` | Agent Con Language Description |
| agentConLast | `String` | Agent Con Last |
| agentConLetterGreeting | `String` | Agent Con Letter Greeting |
| agentConLinkId | `Float` | Agent Con Link ID |
| agentConLinkType | `String` | Agent Con Link Type |
| agentConMailType | `String` | Agent Con Mail Type |
| agentConMarkets | `String` | Agent Con Markets |
| agentConMiddle | `String` | Agent Con Middle |
| agentConName | `String` | Agent Con Name |
| agentConNameType | `String` | Agent Con Name Type |
| agentConName2 | `String` | Agent Con Name2 |
| agentConName3 | `String` | Agent Con Name3 |
| agentConOrganizationid | `Float` | Agent Con Organizationid |
| agentConPhone | `String` | Agent Con Phone |
| agentConPosition | `String` | Agent Con Position |
| agentConPrimaryYn | `String` | Agent Con Primary Y/N |
| agentConProductInterest | `String` | Agent Con Product Interest |
| agentConRelationship | `String` | Agent Con Relationship |
| agentConRelationshipDesc | `String` | Agent Con Relationship Description |
| agentConRepAccountType | `String` | Agent Con Reporting Account Type |
| agentConRepAccountsource | `String` | Agent Con Reporting Accountsource |
| agentConRepActionCode | `String` | Agent Con Reporting Actioncode |
| agentConRepIATACompType | `String` | Agent Con Reporting Iata Comp Type |
| agentConRepIndustryCode | `String` | Agent Con Reporting Industry Code |
| agentConRepInfluence | `String` | Agent Con Reporting Influence |
| agentConRepMarkets | `String` | Agent Con Reporting Markets |
| agentConRepNameType | `String` | Agent Con Reporting Name Type |
| agentConRepScope | `String` | Agent Con Reporting Scope |
| agentConRepScopeCity | `String` | Agent Con Reporting Scope City |
| agentConRepStateCode | `String` | Agent Con Reporting State Code |
| agentConRepStateDescription | `String` | Agent Con Reporting State Desc |
| agentConRepTerritory | `String` | Agent Con Reporting Territory |
| agentConRepTitle | `String` | Agent Con Reporting Title |
| agentConResort | `String` | Agent Con Property |
| agentConScope | `String` | Agent Con Scope |
| agentConScopeCity | `String` | Agent Con Scope City |
| agentConSfirst | `String` | Agent Con Sfirst |
| agentConSname | `String` | Agent Con Sname |
| agentConSrepId | `Float` | Agent Con Srep ID |
| agentConSrepName | `String` | Agent Con Srep Name |
| agentConState | `String` | Agent Con State |
| agentConStateDesc | `String` | Agent Con State Description |
| agentConSxfirstName | `String` | Agent Con Sxfirst Name |
| agentConSxname | `String` | Agent Con Sxname |
| agentConTerritory | `String` | Agent Con Territory |
| agentConTitle | `String` | Agent Con Title |
| agentConXfirst | `String` | Agent Con Xfirst |
| agentConXlast | `String` | Agent Con Xlast |
| agentConXletterGreeting | `String` | Agent Con Xletter Greeting |
| agentConXname | `String` | Agent Con Xname |
| agentConZipcode | `String` | Agent Con Zipcode |
| agentCountry | `String` | Agent Country |
| agentCountryDesc | `String` | Agent Country Description |
| agentDsi | `Float` | Agent Dsi |
| agentEmail | `String` | Agent Email |
| agentFax | `String` | Agent Fax |
| agentHistoryYn | `String` | Agent History Y/N |
| agentIataCompType | `String` | Agent IATA Comp Type |
| agentId | `Float` | Agent ID |
| agentIndustryCode | `String` | Agent Industry Code |
| agentLanguage | `String` | Agent Language |
| agentLanguageDesc | `String` | Agent Language Description |
| agentLinkId | `Float` | Agent Link ID |
| agentLinkType | `String` | Agent Link Type |
| agentMailType | `String` | Agent Mail Type |
| agentMarkets | `String` | Agent Markets |
| agentName | `String` | Agent Name |
| agentNameId | `Float` | Agent Name ID |
| agentNameType | `String` | Agent Name Type |
| agentName2 | `String` | Agent Name2 |
| agentName3 | `String` | Agent Name3 |
| agentOrganizationid | `Float` | Agent Organizationid |
| agentPhone | `String` | Agent Phone |
| agentPrimaryYn | `String` | Agent Primary Y/N |
| agentProductInterest | `String` | Agent Product Interest |
| agentRelationship | `String` | Agent Relationship |
| agentRelationshipDesc | `String` | Agent Relationship Description |
| agentRepStateCode | `String` | Agent Reporting State Code |
| agentResort | `String` | Agent Property |
| agentScope | `String` | Agent Scope |
| agentScopeCity | `String` | Agent Scope City |
| agentSname | `String` | Agent Sname |
| agentState | `String` | Agent State |
| agentStateDesc | `String` | Agent State Description |
| agentSxname | `String` | Agent Sxname |
| agentTerritory | `String` | Agent Territory |
| agentXdisplayName | `String` | Agent Xdisplay Name |
| agentXenvelopeGreeting | `String` | Agent Xenvelope Greeting |
| agentXfirstName | `String` | Agent Xfirst Name |
| agentZipcode | `String` | Agent Zipcode |
| alias | `String` | Alias |
| allOwners | `String` | All Owners |
| allotmentCode | `String` | Allotment Code |
| allotmentHeaderId | `Float` | Allotment Header ID |
| allotmentOrigion | `String` | Allotment Origion |
| allotmentType | `String` | Type of Block alloted for the group. |
| arrivalTime | `DateTime` | Arrival Time |
| attendees | `Float` | Attendees |
| avgPeoplePerRoom | `Float` | Avg People Per Room |
| avgRateNet | `Float` | Avg Rate Net |
| beginDate | `Date` | Begin Date |
| bookingStatus | `String` | Booking Status |
| bookingStatusOrderby | `Float` | Booking Status Orderby |
| bookingStatusType | `String` | Booking Status Type |
| bookingStatusorder | `Float` | Booking Statusorder |
| bookingmethod | `String` | Bookingmethod |
| bookingmethoddesc | `String` | Bookingmethoddesc |
| bookingtype | `String` | Bookingtype |
| breakfastDesc | `String` | Bfst Description |
| breakfastPrice | `Float` | Breakfast Price |
| breakfastYn | `String` | Bfst Y/N |
| busblockId | `Float` | Busblock ID |
| busblockProperty | `String` | Busblock Property |
| cBreakfastPrice | `Float` | Central Bfst Price |
| cCompRoomValue | `Float` | Central Comp Room Value |
| cExchangeDate | `Date` | Central Xchange Date |
| cExchangeRate | `Float` | Central Xchange Rate |
| cMtgBudget | `Float` | Central Mtg Budget |
| cPorteragePrice | `Float` | Central Porterage Price |
| cPotRoomRevenue | `Float` | Central Pot Room Revenue |
| cServiceCharge | `Float` | Central Service Charge |
| cTaxAmount | `Float` | Central Tax Amount |
| cancelRule | `String` | Not Used |
| cancellationCode | `String` | Cancellation Code |
| cancellationDate | `Date` | Cancellation Date |
| cancellationDescription | `String` | Cancellation Description |
| cancellationNo | `Float` | Cancellation Number |
| catCanxCode | `String` | Catering Canx Code |
| catCanxDate | `Date` | Catering Canx Date |
| catCanxNumber | `Float` | Catering Canx No |
| catCurrency | `String` | Catering Currency |
| catCutoff | `Date` | Catering Cutoff |
| catDecision | `Date` | Catering Decision |
| catExchange | `Float` | Catering Exchange |
| catFollowup | `Date` | Catering Followup |
| catOwner | `Float` | Catering Owner |
| catOwnerCode | `String` | Catering Owner Code |
| catOwnerEmail | `String` | Catering Owner Email |
| catOwnerFax | `String` | Catering Owner Fax |
| catOwnerPhone | `String` | Catering Owner Phone |
| catOwnerProperty | `String` | Property of Catering Owner |
| catOwnerSrepname | `String` | Catering Owner Srepname |
| catOwnerTitle | `String` | Catering Owner Title |
| catOwners | `String` | Catering Owners |
| catQuoteCurrency | `String` | Catering Quote Curr |
| catStatus | `String` | Catering Status |
| catStatusOrderby | `Float` | Catering Status Orderby |
| catStatusType | `String` | Catering Status Type describes Inventory behaviour |
| catStatusorder | `Float` | Catering Statusorder |
| cateringCanxDesc | `String` | Cat Canx Description |
| cateringPkgsYn | `String` | Catering Pkgs Y/N |
| cateringonlyYn | `String` | Cateringonly Y/N |
| centralOwner | `String` | Stores the name and phone number of the primary central owner. |
| channel | `String` | Channel |
| commission | `String` | Commission |
| compPerStayYn | `String` | Complimentary Rooms based per Stay (Y) or per Night (N) |
| compRoomValue | `Float` | Complimentary Rooms: Value given to Customer |
| compRooms | `Float` | Number of complimentary Rooms |
| compRoomsFixedYn | `String` | Complimentary Rooms: Fixed amount (Y) or calculated (N) |
| companyNameId | `Float` | Company Name ID |
| competition | `String` | Competition |
| conActionCode | `String` | Con Action Code |
| conActiveYn | `String` | Con Active Y/N |
| conAddressType | `String` | Con Address Type |
| conAddress1 | `String` | Con Address1 |
| conAddress2 | `String` | Con Address2 |
| conAddress3 | `String` | Con Address3 |
| conAddress4 | `String` | Con Address4 |
| conAlternateLanguage | `String` | Con Alternate Language |
| conAlternateLanguageDesc | `String` | Con Xlanguage Description |
| conAlternateSalutation | `String` | Con Alternate Salutation |
| conAlternateTitle | `String` | Con Alternate Title |
| conArNumber | `String` | Con AR No |
| conAvailabilityOverride | `String` | Con Availability Override |
| conBirthDate | `Date` | Con Birth Date |
| conBirthDateStr | `String` | Con Birth Date Str |
| conBookingId | `Float` | Con Booking ID |
| conBusinessGreeting | `String` | Con Business Greeting |
| conCashBlInd | `String` | Con Cash Bl Individual |
| conCity | `String` | Con City |
| conCityExt | `String` | Con City Ext |
| conContactYn | `String` | Con Contact Y/N |
| conCountry | `String` | Con Country |
| conCountryDesc | `String` | Con Country Description |
| conDepartment | `String` | Con Department |
| conDsi | `Float` | Con Dsi |
| conFirst | `String` | Con First |
| conHistoryYn | `String` | Con History Y/N |
| conIataCompType | `String` | Con IATA Comp Type |
| conId | `Float` | Con ID |
| conIndustryCode | `String` | Con Industry Code |
| conInfluence | `String` | Con Influence |
| conLanguage | `String` | Con Language |
| conLanguageDesc | `String` | Con Language Description |
| conLast | `String` | Con Last |
| conLetterGreeting | `String` | Con Letter Greeting |
| conLinkId | `Float` | Con Link ID |
| conLinkType | `String` | Con Link Type |
| conMailType | `String` | Con Mail Type |
| conMarkets | `String` | Con Markets |
| conMiddle | `String` | Con Middle |
| conName | `String` | Con Name |
| conNameType | `String` | Con Name Type |
| conName2 | `String` | Con Name2 |
| conName3 | `String` | Con Name3 |
| conOrganizationid | `Float` | Con Organizationid |
| conPosition | `String` | Con Position |
| conPrimaryYn | `String` | Con Primary Y/N |
| conProductInterest | `String` | Con Product Interest |
| conRelationship | `String` | Con Relationship |
| conRelationshipDesc | `String` | Con Relationship Description |
| conRepActionCode | `String` | Con Reporting Actioncode |
| conRepInfluence | `String` | Con Reporting Influence |
| conRepMarkets | `String` | Con Reporting Markets |
| conRepNameType | `String` | Con Reporting Name Type |
| conRepScope | `String` | Con Reporting Scope |
| conRepScopeCity | `String` | Con Reporting Scope City |
| conRepStateCode | `String` | Con Reporting State Code |
| conRepStateDescription | `String` | Con Reporting State Desc |
| conRepTerritory | `String` | Con Reporting Territory |
| conRepTitle | `String` | Con Reporting Title |
| conResort | `String` | Con Property |
| conScope | `String` | Con Scope |
| conScopeCity | `String` | Con Scope City |
| conSfirst | `String` | Con Sfirst |
| conSname | `String` | Con Sname |
| conSrepCode | `String` | Con Srep Code |
| conSrepId | `Float` | Con Srep ID |
| conSrepName | `String` | Con Srep Name |
| conState | `String` | Con State |
| conStateDesc | `String` | Con State Description |
| conSxfirstName | `String` | Con Sxfirst Name |
| conSxname | `String` | Con Sxname |
| conTerritory | `String` | Con Territory |
| conTitle | `String` | Con Title |
| conXfirst | `String` | Con Xfirst |
| conXlast | `String` | Con Xlast |
| conXletterGreeting | `String` | Con Xletter Greeting |
| conXname | `String` | Con Xname |
| contactEmail | `String` | Reservation Contact id salutation information. |
| contactFax | `String` | Contact Fax |
| contactNameId | `Float` | Contact Name ID |
| contactPhone | `String` | Contact Phone |
| contactZipcode | `String` | Contact Zipcode |
| contractNr | `String` | Contract Nr |
| conversionCode | `String` | Conversion Code |
| currencyCode | `String` | Currency Code |
| dSI | `Float` | DSI Internal Data Source ID to identify Opera Chain and instance |
| dateOpenedForPickup | `Date` | Business Date when the business block was opened for pickup. |
| datePro | `DateTime` | Date Pro |
| dateTen | `DateTime` | Date Ten |
| defaultPmReservationNameId | `Float` | Defualt Posting Master ID |
| deletedflag | `String` | Deleted Flag |
| departureTime | `DateTime` | Departure Time |
| description | `String` | Description |
| destination | `String` | Destination |
| detailsOkYn | `String` | Details Ok Y/N |
| distributedYn | `String` | Distributed Y/N |
| dmlSeqNumber | `Float` | Dml Sequence No |
| downloadDate | `Date` | Download Date |
| downloadResort | `String` | Download Property |
| downloadSrep | `Float` | Download Srep |
| dueDate | `Date` | Due Date |
| elastic | `String` | Elastic |
| endDate | `Date` | End Date |
| eventsGuaranteedYn | `String` | Events Guaranteed Y/N |
| exchangePostingType | `String` | Exchange Posting Type |
| exchangeRate | `Float` | Exchange Rate |
| externalLocked | `String` | External Locked |
| functiontype | `String` | Functiontype |
| giid | `String` | Group IATA Number. |
| guaranteeCode | `String` | Guarantee Code |
| iataCorpNumber | `String` | IATA Corp No |
| inactiveDate | `Date` | Inactive Date |
| info | `String` | Not Used |
| infoboard | `String` | Infoboard |
| insertDate | `DateTime` | Insert Date |
| insertUser | `Float` | Insert User |
| insertUserName | `String` | The name of the user who created the record. |
| invCutoffDate | `Date` | Invoice Cutoff Date |
| invCutoffDays | `Float` | Invoice Cutoff Days |
| isacOpptyId | `String` | STAR MODE: ISAC opportunity ID. |
| isacQuoteId | `String` | Isac Quote ID |
| jRNUpdateDate | `Date` | JRN Update Date |
| jRNUpdateDateAndTime | `DateTime` | JRN Update Date and Time |
| laptopChange | `Float` | Laptop Change |
| leadOrigin | `String` | Lead Origin |
| leadSource | `String` | Lead Source |
| linkDate | `DateTime` | STAR MODE: Date when the OPERA block was linked to an ISAC opportunity. |
| lostToProperty | `String` | Competitor to whom the booking was lost. |
| mainmarket | `String` | Mainmarket |
| marEventType | `String` | MARRIOTT mode: Marsha Event Type. |
| marHouseProtectYn | `String` | MARRIOTT mode: Marsha column for Housing Protected. |
| marRollEndDateYn | `String` | MARRIOTT mode: Specifies if the Marsha block has a rolling end date. |
| marketCode | `String` | Market Code |
| masterNameId | `Float` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |
| methodDue | `Date` | Method Due |
| mtgBudget | `Float` | Meeting Budget |
| nonCompete | `String` | Indicate that no other block of the same industry can be booked for the selected dates.Non-Compete indicator : [A]ll [S]ome [N]one. |
| nonCompeteCode | `String` | Indicates the Non-Compete code of a block. |
| organizationID | `Float` | Internal ID to uniquely identify the Organization |
| originalRateCode | `String` | Not used |
| owner | `Float` | Owner |
| ownerCode | `String` | Owner Code |
| ownerCodeSrepname | `String` | Owner Code Srepname |
| ownerEmail | `String` | Owner Email |
| ownerFax | `String` | Owner Fax |
| ownerPhone | `String` | Owner Phone |
| ownerResort | `String` | Owner Property |
| ownerTitle | `String` | Owner Title |
| paymentMethod | `String` | Payment Method |
| peakRooms | `Float` | Peak Rooms |
| porteragePrice | `Float` | Porterage Price |
| porterageYn | `String` | Porterage Y/N |
| printAccountActiveYN | `String` | Print Acc Active Y/N |
| printAccountAddress1 | `String` | Print Account Address1 |
| printAccountAddress2 | `String` | Print Account Address2 |
| printAccountAddress3 | `String` | Print Account Address3 |
| printAccountAddress4 | `String` | Print Account Address4 |
| printAccountBookingId | `Float` | Print Acc Booking ID |
| printAccountCity | `String` | Print Account City |
| printAccountCityExt | `String` | Print Account City Ext |
| printAccountCountry | `String` | Print Account Country |
| printAccountCountryDesc | `String` | Print Acc Country Description |
| printAccountDsi | `Float` | Print Account Dsi |
| printAccountId | `Float` | Print Acc ID |
| printAccountLinkId | `Float` | Print Acc Link ID |
| printAccountLinkType | `String` | Print Account Link Type |
| printAccountName | `String` | Print Account Name |
| printAccountName2 | `String` | Print Account Name2 |
| printAccountName3 | `String` | Print Account Name3 |
| printAccountOrganizationid | `Float` | Print Account Organizationid |
| printAccountPhone | `String` | Print Account Phone |
| printAccountPosition | `String` | Print Account Position |
| printAccountPrimaryYN | `String` | Print Acc Primary Y/N |
| printAccountProperty | `String` | Print Account Resort |
| printAccountRepStateCode | `String` | Print Acc Reporting State Code |
| printAccountRepStateDescription | `String` | Print Acc Reporting State Desc |
| printAccountRepTerritory | `String` | Print Acc Reporting Territory |
| printAccountScope | `String` | Print Account Scope |
| printAccountScopeCity | `String` | Print Account Scope City |
| printAccountSname | `String` | Print Account Sname |
| printAccountState | `String` | Print Account State |
| printAccountStateDesc | `String` | Print Acc State Description |
| printAccountSxname | `String` | Print Account Sxname |
| printAccountTerritory | `String` | Print Account Territory |
| printAccountXdisplayName | `String` | Print Account Xdisplay Name |
| printAccountXenvelopeGreeting | `String` | Print Account Xenvelope Greeting |
| printAccountXfirstName | `String` | Print Account Xfirst Name |
| printAccountXname | `String` | Print Account Xname |
| printAccountZipcode | `String` | Print Account Zipcode |
| printConAddress1 | `String` | Print Con Address1 |
| printConAddress2 | `String` | Print Con Address2 |
| printConAddress3 | `String` | Print Con Address3 |
| printConAddress4 | `String` | Print Con Address4 |
| printConAlternateSalutation | `String` | Print Con Alternate Salutation |
| printConBusinessGreeting | `String` | Print Con Business Greeting |
| printConCity | `String` | Print Con City |
| printConCityExt | `String` | Print Con City Ext |
| printConCountry | `String` | Print Con Country |
| printConCountryDesc | `String` | Print Con Country Description |
| printConDepartment | `String` | Print Con Department |
| printConDsi | `Float` | Print Con Dsi |
| printConEmail | `String` | Print Con Email |
| printConFirst | `String` | Print Con First |
| printConId | `Float` | Print Con ID |
| printConLast | `String` | Print Con Last |
| printConLetterGreeting | `String` | Print Con Letter Greeting |
| printConLinkId | `Float` | Print Con Link ID |
| printConLinkType | `String` | Print Con Link Type |
| printConMiddle | `String` | Print Con Middle |
| printConName | `String` | Print Con Name |
| printConName2 | `String` | Print Con Name2 |
| printConName3 | `String` | Print Con Name3 |
| printConOrganizationid | `Float` | Print Con Organizationid |
| printConPhone | `String` | Print Con Phone |
| printConPosition | `String` | Print Con Position |
| printConPrimaryYn | `String` | Print Con Primary Y/N |
| printConProductInterest | `String` | Print Con Product Interest |
| printConRelationship | `String` | Print Con Relationship |
| printConRelationshipDesc | `String` | Print Con Relationship Description |
| printConRepStateCode | `String` | Print Con Reporting State Code |
| printConRepTitle | `String` | Print Con Reporting Title |
| printConResort | `String` | Print Con Property |
| printConScope | `String` | Print Con Scope |
| printConScopeCity | `String` | Print Con Scope City |
| printConSname | `String` | Print Con Sname |
| printConState | `String` | Print Con State |
| printConStateDesc | `String` | Print Con State Description |
| printConSxname | `String` | Print Con Sxname |
| printConTerritory | `String` | Print Con Territory |
| printConTitle | `String` | Print Con Title |
| printConXdisplayName | `String` | Print Con Xdisplay Name |
| printConXfirst | `String` | Print Con Xfirst |
| printConXlast | `String` | Print Con Xlast |
| printConXletterGreeting | `String` | Print Con Xletter Greeting |
| printConZipcode | `String` | Print Con Zipcode |
| profileDesc | `String` | Profile Description |
| profileId | `Float` | Profile ID |
| program | `String` | Program |
| property | `String` | Code to uniquely identify the Property |
| rankingCode | `String` | Indicates the ranking of a block. |
| rateCode | `String` | Rate Code |
| rateGuaranteedYn | `String` | Rate Guaranteed Y/N. |
| rateOverride | `String` | Indicates if the rate code can be overridden. |
| rateOverrideReason | `String` | Reason why the rate code was overridden used for FIT Contracts. |
| rateProtection | `String` | Indicates that a Rate Protection exists for this booking: [A]ll [S]ome [N]one. No other group can be booked using rates lower than the one that is flagged as rate protect. |
| relatedResorts | `String` | Related Resorts |
| repBlockStatusDescription | `String` | Reporting Block Status Description |
| repBookingmethod | `String` | Reporting Bookingmethod |
| repBookingmethodDescription | `String` | Reporting Bookingmethod Desc |
| repBookingtype | `String` | Reporting Bookingtype |
| repBsOrderBy | `Float` | Reporting Bs Order By |
| repCateringOrderBy | `Float` | Reporting Cat Order By |
| repCateringStatus | `String` | Reporting Cat Status |
| repCateringStatusDescription | `String` | Reporting Cat Status Description |
| repChannel | `String` | Reporting Channel |
| repConversionCode | `String` | Reporting Conversion Code |
| repDestination | `String` | Reporting Destination |
| repGuaranteeCode | `String` | Reporting Guarantee Code |
| repMarketCode | `String` | Reporting Market Code |
| repNonCompeteCode | `String` | Reporting Non Compete Code |
| repPaymentMethod | `String` | Reporting Payment Method |
| repRankingCode | `String` | Reporting Ranking Code |
| repSourceCode | `String` | Reporting Source Code |
| representative | `String` | Representative |
| reserveInventoryYn | `String` | Reserve Inventory Y/N |
| resortBooked | `String` | Final resort where Booking is confirmed -via Lead process. |
| revBlocked | `Float` | Revenue Blocked |
| revBlockedNet | `Float` | Revenue Blocked Net |
| revContracted | `Float` | Revenue Contracted |
| rivMarketSegment | `String` | Not used |
| rnaInsertDate | `DateTime` | RnA Insertdate |
| rnaUpdateDate | `DateTime` | RnA Updatedate |
| roomsBlocked | `Float` | Rooms Blocked |
| roomsContracted | `Float` | Rooms Contracted |
| roomsCurrency | `String` | Rooms Currency |
| roomsDecision | `Date` | Rooms Decision |
| roomsExchange | `Float` | Rooms Exchange |
| roomsFollowup | `Date` | Rooms Followup |
| roomsOwner | `Float` | Rooms Owner |
| roomsOwnerCode | `String` | Rooms Owner Code |
| roomsOwnerEmail | `String` | Rooms Owner Email |
| roomsOwnerFax | `String` | Rooms Owner Fax |
| roomsOwnerPhone | `String` | Rooms Owner Phone |
| roomsOwnerResort | `String` | Property of Rooms Salesmanager |
| roomsOwnerSrepname | `String` | Rooms Owner Srepname |
| roomsOwnerTitle | `String` | Rooms Owner Title |
| roomsOwners | `String` | Rooms Owners |
| roomsPerDay | `Float` | Rooms Per Day |
| roomsQuoteCurr | `String` | Rms Quote Currency |
| salesId | `String` | Not used |
| sbegindate | `Date` | Sbegindate |
| secConActionCode | `String` | Sec Con Action Code |
| secConActiveYn | `String` | Sec Con Active Y/N |
| secConAddress1 | `String` | Sec Con Address1 |
| secConAddress2 | `String` | Sec Con Address2 |
| secConAddress3 | `String` | Sec Con Address3 |
| secConAddress4 | `String` | Sec Con Address4 |
| secConAlternateLanguage | `String` | Sec Con Alternate Language |
| secConAlternateLanguageDesc | `String` | Sec Con Xlanguage Description |
| secConAlternateSalutation | `String` | Sec Con Alternate Salutation |
| secConAlternateTitle | `String` | Sec Con Alternate Title |
| secConBirthDate | `Date` | Sec Con Birth Date |
| secConBirthDateStr | `String` | Sec Con Birth Date Str |
| secConBookingId | `Float` | Sec Con Booking ID |
| secConBusinessGreeting | `String` | Sec Con Business Greeting |
| secConCashBlInd | `String` | Sec Con Cash Bl Individual |
| secConCity | `String` | Sec Con City |
| secConCityExt | `String` | Sec Con City Ext |
| secConContactYn | `String` | Sec Con Contact Y/N |
| secConCountry | `String` | Sec Con Country |
| secConCountryDesc | `String` | Sec Con Country Description |
| secConDepartment | `String` | Sec Con Department |
| secConDsi | `Float` | Sec Con Dsi |
| secConEmail | `String` | Sec Con Email |
| secConFax | `String` | Sec Con Fax |
| secConFirstName | `String` | Sec Con First Name |
| secConFullName | `String` | Sec Con Full Name |
| secConId | `Float` | Sec Con ID |
| secConInfluence | `String` | Sec Con Influence |
| secConLanguage | `String` | Sec Con Language |
| secConLanguageDesc | `String` | Sec Con Language Description |
| secConLastName | `String` | Sec Con Last Name |
| secConLetterGreeting | `String` | Sec Con Letter Greeting |
| secConLinkId | `Float` | Sec Con Link ID |
| secConLinkType | `String` | Sec Con Link Type |
| secConMarkets | `String` | Sec Con Markets |
| secConMiddleName | `String` | Sec Con Middle Name |
| secConNameType | `String` | Sec Con Name Type |
| secConName2 | `String` | Sec Con Name2 |
| secConName3 | `String` | Sec Con Name3 |
| secConOrganizationid | `Float` | Sec Con Organizationid |
| secConPhone | `String` | Sec Con Phone |
| secConPosition | `String` | Sec Con Position |
| secConPrimaryYn | `String` | Sec Con Primary Y/N |
| secConProductInterest | `String` | Sec Con Product Interest |
| secConRelationship | `String` | Sec Con Relationship |
| secConRelationshipDesc | `String` | Sec Con Relationship Description |
| secConRepActionCode | `String` | Sec Con Reporting Actioncode |
| secConRepInfluence | `String` | Sec Con Reporting Influence |
| secConRepMarkets | `String` | Sec Con Reporting Markets |
| secConRepNameType | `String` | Sec Con Reporting Name Type |
| secConRepScope | `String` | Sec Con Reporting Scope |
| secConRepScopeCity | `String` | Sec Con Reporting Scope City |
| secConRepStateCode | `String` | Sec Con Reporting State Code |
| secConRepStateDescription | `String` | Sec Con Reporting State Desc |
| secConRepTerritory | `String` | Sec Con Reporting Territory |
| secConRepTitle | `String` | Sec Con Reporting Title |
| secConResort | `String` | Sec Con Property |
| secConScope | `String` | Sec Con Scope |
| secConScopeCity | `String` | Sec Con Scope City |
| secConSfirst | `String` | Sec Con Sfirst |
| secConSname | `String` | Sec Con Sname |
| secConSrepCode | `String` | Sec Con Srep Code |
| secConSrepId | `Float` | Sec Con Srep ID |
| secConSrepName | `String` | Sec Con Srep Name |
| secConState | `String` | Sec Con State |
| secConStateDesc | `String` | Sec Con State Description |
| secConSxfirstName | `String` | Sec Con Sxfirst Name |
| secConSxname | `String` | Sec Con Sxname |
| secConTerritory | `String` | Sec Con Territory |
| secConTitle | `String` | Sec Con Title |
| secConXenvelopeGreeting | `String` | Sec Con Xenvelope Greeting |
| secConXfirstName | `String` | Sec Con Xfirst Name |
| secConXfullName | `String` | Sec Con Xfull Name |
| secConXlastName | `String` | Sec Con Xlast Name |
| secConZipCode | `String` | Sec Con Zipcode Code |
| senddate | `Date` | Senddate |
| sentDate | `DateTime` | Sent Date |
| serviceCharge | `Float` | Service Charge |
| shoulderBeginDate | `Date` | Shoulder Begin Date |
| shoulderEndDate | `Date` | Shoulder End Date |
| source | `String` | Source |
| sourceActiveYn | `String` | Source Active Y/N |
| sourceAddressType | `String` | Source Address Type |
| sourceAddress1 | `String` | Source Address1 |
| sourceAddress2 | `String` | Source Address2 |
| sourceAlternateLanguage | `String` | Source Alternate Language |
| sourceAlternateLanguageDesc | `String` | Source Xlanguage Description |
| sourceAlternateSalutation | `String` | Source Alternate Salutation |
| sourceAlternateTitle | `String` | Source Alternate Title |
| sourceBookingId | `Float` | Source Booking ID |
| sourceBusinessGreeting | `String` | Source Business Greeting |
| sourceCity | `String` | Source City |
| sourceCityExt | `String` | Source City Ext |
| sourceConActionCode | `String` | Source Con Action Code |
| sourceConActiveYn | `String` | Source Con Active Y/N |
| sourceConAddressType | `String` | Source Con Address Type |
| sourceConAddress1 | `String` | Source Con Address1 |
| sourceConAddress2 | `String` | Source Con Address2 |
| sourceConAddress3 | `String` | Source Con Address3 |
| sourceConAddress4 | `String` | Source Con Address4 |
| sourceConAlternateLanguage | `String` | Source Con Alternate Language |
| sourceConAlternateLanguageDesc | `String` | Source Con Xlanguage Description |
| sourceConAlternateSalutation | `String` | Source Con Alternate Salutation |
| sourceConAlternateTitle | `String` | Source Con Alternate Title |
| sourceConArNumber | `String` | Source Con AR No |
| sourceConAuSrepCode | `String` | Source Con Au Srep Code |
| sourceConAvailabilityOverride | `String` | Source Con Availability Override |
| sourceConBirthDate | `Date` | Source Con Birth Date |
| sourceConBirthDateStr | `String` | Source Con Birth Date Str |
| sourceConBookingId | `Float` | Source Con Booking ID |
| sourceConBusinessGreeting | `String` | Source Con Business Greeting |
| sourceConCashBlInd | `String` | Source Con Cash Bl Individual |
| sourceConCity | `String` | Source Con City |
| sourceConCityExt | `String` | Source Con City Ext |
| sourceConContactYn | `String` | Source Con Contact Y/N |
| sourceConCountry | `String` | Source Con Country |
| sourceConCountryDesc | `String` | Source Con Country Description |
| sourceConDepartment | `String` | Source Con Department |
| sourceConDsi | `Float` | Source Con Dsi |
| sourceConEmail | `String` | Source Con Email |
| sourceConFax | `String` | Source Con Fax |
| sourceConFirst | `String` | Source Con First |
| sourceConHistoryYn | `String` | Source Con History Y/N |
| sourceConIataCompType | `String` | Source Con IATA Comp Type |
| sourceConId | `Float` | Source Con ID |
| sourceConIndustryCode | `String` | Source Con Industry Code |
| sourceConInfluence | `String` | Source Con Influence |
| sourceConLanguage | `String` | Source Con Language |
| sourceConLanguageDesc | `String` | Source Con Language Description |
| sourceConLast | `String` | Source Con Last |
| sourceConLetterGreeting | `String` | Source Con Letter Greeting |
| sourceConLinkId | `Float` | Source Con Link ID |
| sourceConLinkType | `String` | Source Con Link Type |
| sourceConMailType | `String` | Source Con Mail Type |
| sourceConMarkets | `String` | Source Con Markets |
| sourceConMiddle | `String` | Source Con Middle |
| sourceConName | `String` | Source Con Name |
| sourceConNameType | `String` | Source Con Name Type |
| sourceConName2 | `String` | Source Con Name2 |
| sourceConName3 | `String` | Source Con Name3 |
| sourceConOrganizationid | `Float` | Source Con Organizationid |
| sourceConPhone | `String` | Source Con Phone |
| sourceConPosition | `String` | Source Con Position |
| sourceConPrimaryYn | `String` | Source Con Primary Y/N |
| sourceConProductInterest | `String` | Source Con Product Interest |
| sourceConRelationship | `String` | Source Con Relationship |
| sourceConRelationshipDesc | `String` | Source Con Relationship Description |
| sourceConRepActionCode | `String` | Source Con Reporting Actioncode |
| sourceConRepInfluence | `String` | Source Con Reporting Influence |
| sourceConRepMarkets | `String` | Source Con Reporting Markets |
| sourceConRepNameType | `String` | Source Con Reporting Name Type |
| sourceConRepScope | `String` | Source Con Reporting Scope |
| sourceConRepScopeCity | `String` | Source Con Reporting Scope City |
| sourceConRepStateCode | `String` | Source Con Reporting State Code |
| sourceConRepStateDescription | `String` | Source Con Reporting State Desc |
| sourceConRepTerritory | `String` | Source Con Reporting Territory |
| sourceConRepTitle | `String` | Source Con Reporting Title |
| sourceConResort | `String` | Source Con Property |
| sourceConScope | `String` | Source Con Scope |
| sourceConScopeCity | `String` | Source Con Scope City |
| sourceConSfirst | `String` | Source Con Sfirst |
| sourceConSname | `String` | Source Con Sname |
| sourceConSrepId | `Float` | Source Con Srep ID |
| sourceConSrepName | `String` | Source Con Srep Name |
| sourceConState | `String` | Source Con State |
| sourceConStateDesc | `String` | Source Con State Description |
| sourceConSxfirstName | `String` | Source Con Sxfirst Name |
| sourceConSxname | `String` | Source Con Sxname |
| sourceConTerritory | `String` | Source Con Territory |
| sourceConTitle | `String` | Source Con Title |
| sourceConXfirst | `String` | Source Con Xfirst |
| sourceConXlast | `String` | Source Con Xlast |
| sourceConXletterGreeting | `String` | Source Con Xletter Greeting |
| sourceConXname | `String` | Source Con Xname |
| sourceConZipcode | `String` | Source Con Zipcode |
| sourceCountry | `String` | Source Country |
| sourceCountryDesc | `String` | Source Country Description |
| sourceDsi | `Float` | Source Dsi |
| sourceEmail | `String` | Source Email |
| sourceFax | `String` | Source Fax |
| sourceId | `Float` | Source ID |
| sourceLinkId | `Float` | Source Link ID |
| sourceLinkType | `String` | Source Link Type |
| sourceName | `String` | Source Name |
| sourceNameId | `Float` | Source Name ID |
| sourceNameType | `String` | Source Name Type |
| sourceName2 | `String` | Source Name2 |
| sourceName3 | `String` | Source Name3 |
| sourceOrganizationid | `Float` | Source Organizationid |
| sourcePhone | `String` | Source Phone |
| sourcePrimaryYn | `String` | Source Primary Y/N |
| sourceRelationship | `String` | Source Relationship |
| sourceRelationshipDesc | `String` | Source Relationship Description |
| sourceRepStateCode | `String` | Source Reporting State Code |
| sourceResort | `String` | Comma separated list of properties to migrate. |
| sourceScope | `String` | Source Scope |
| sourceScopeCity | `String` | Source Scope City |
| sourceSname | `String` | Source Sname |
| sourceState | `String` | Source State |
| sourceStateDesc | `String` | Source State Description |
| sourceSxname | `String` | Source Sxname |
| sourceTerritory | `String` | Source Territory |
| sourceXdisplayName | `String` | Source Xdisplay Name |
| sourceXenvelopeGreeting | `String` | Source Xenvelope Greeting |
| sourceXfirstName | `String` | Source Xfirst Name |
| sourceZipcode | `String` | Source Zipcode |
| status | `String` | Status |
| superBlockId | `Float` | Parent Block ID |
| superBlockResort | `String` | Parent Resort |
| taxAmount | `Float` | Tax Amount |
| tbdRates | `String` | To be Determined Rates |
| tentativeLevel | `Float` | Not used |
| tracecode | `String` | Tracecode |
| udescription | `String` | This is upper-case description of regular description column for fast search |
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
| updateUserName | `String` | Update User Name |
| uploadDate | `Date` | Upload Date |
| xaccName | `String` | Xacc Name |
| xagentName | `String` | Xagent Name |
| xsourceName | `String` | Extended Byte Source Name |

[⬆ Back to Query](#query)

---

### SimpleReportsBookingBlocksPropertyPropertyDetailsType

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

### SimpleReportsBookingBlocksQueryArgumentsType

| Field | Type | Description | Directives |
| --- | --- | --- | --- |
| scbusblockinfoDetailsAgentNameId | `FloatInput` | Agent Name ID |  |
| scbusblockinfoDetailsAllotmentCode | `StringInput` | Allotment Code |  |
| scbusblockinfoDetailsAllotmentHeaderId | `FloatInput` | Allotment Header ID |  |
| scbusblockinfoDetailsBeginDate | `DateInput!` | Begin Date | `mandatoryInput` |
| scbusblockinfoDetailsBookingStatus | `StringInput` | Booking Status |  |
| scbusblockinfoDetailsCXchangeDate | `DateInput` | Central Xchange Date |  |
| scbusblockinfoDetailsCompanyNameId | `FloatInput` | Company Name ID |  |
| scbusblockinfoDetailsContactNameId | `FloatInput` | Contact Name ID |  |
| scbusblockinfoDetailsDsi | `FloatInput` | DSI Internal Data Source ID to identify Opera Chain and instance |  |
| scbusblockinfoDetailsEndDate | `DateInput!` | End Date | `mandatoryInput` |
| scbusblockinfoDetailsGuaranteeCode | `StringInput` | Guarantee Code |  |
| scbusblockinfoDetailsInsertDate | `DateTimeInput` | Insert Date |  |
| scbusblockinfoDetailsInsertUser | `FloatInput` | Insert User |  |
| scbusblockinfoDetailsIsacOpptyId | `StringInput` | STAR MODE: ISAC opportunity ID. |  |
| scbusblockinfoDetailsJrnupdatedttm | `DateTimeInput` | JRN Update Date and Time |  |
| scbusblockinfoDetailsMarketCode | `StringInput` | Market Code |  |
| scbusblockinfoDetailsMasterNameId | `FloatInput` | Profile Id. ( Name_Id ) of the Group Profile attached to this business block. |  |
| scbusblockinfoDetailsOrganizationid | `FloatInput` | Internal ID to uniquely identify the Organization |  |
| scbusblockinfoDetailsOwner | `FloatInput` | Owner |  |
| scbusblockinfoDetailsOwnerCode | `StringInput` | Owner Code |  |
| scbusblockinfoDetailsResort | `StringInput!` | Code to uniquely identify the Property | `mandatoryInput` |
| scbusblockinfoDetailsRateCode | `StringInput` | Rate Code |  |
| scbusblockinfoDetailsShoulderBeginDate | `DateInput` | Shoulder Begin Date |  |
| scbusblockinfoDetailsShoulderEndDate | `DateInput` | Shoulder End Date |  |
| scbusblockinfoDetailsSourceNameId | `FloatInput` | Source Name ID |  |
| scbusblockinfoDetailsSuperBlockId | `FloatInput` | Parent Block ID |  |
| scbusblockinfoDetailsSuperBlockResort | `StringInput` | Parent Resort |  |
| scbusblockinfoDetailsUdescription | `StringInput` | This is upper-case description of regular description column for fast search |  |
| scbusblockinfoDetailsUpdateDate | `DateTimeInput` | Update Date |  |
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
query simpleReportsBookingBlocks($input: SimpleReportsBookingBlocksQueryArgumentsType!) {
  simpleReportsBookingBlocks(input: $input) @stream {
    salesEventBusinessBlockInformationDetails {
      accountActionCode
      accountActiveYN
      accountAddressType
      accountAddress1
      accountAddress2
      accountAlternateLanguage
      accountAlternateLanguageDesc
      accountAlternateSalutation
      accountAlternateTitle
      accountArNumber
      accountAvailoverYN
      accountBlMsg
      accountBookingId
      accountCblIndividual
      accountCity
      accountCityExt
      accountCommissionCode
      accountCompetitionCode
      accountCountry
      accountCountryDesc
      accountDsi
      accountEmail
      accountFax
      accountHistoryYN
      accountHoldCode
      accountIATACompType
      accountId
      accountIndustryCode
      accountKeyword
      accountLanguage
      accountLanguageDesc
      accountLinkId
      accountLinkType
      accountMailList
      accountMailType
      accountMarkets
      accountName
      accountNameKeywords
      accountNameType
      accountName2
      accountName3
      accountOrganizationid
      accountPhone
      accountPhoneId
      accountPhoneNumber
      accountPrimaryYN
      accountPriority
      accountProductInterest
      accountProperty
      accountRelationship
      accountRelationshipDesc
      accountRepActionCode
      accountRepCompetionCode
      accountRepIATACompType
      accountRepIndustryCode
      accountRepMarkets
      accountRepNameType
      accountRepScope
      accountRepScopeCity
      accountRepSource
      accountRepStateCode
      accountRepStateDescription
      accountRepTerritory
      accountRepType
      accountRoomsPotential
      accountScope
      accountScopeCity
      accountSname
      accountSource
      accountSrepCode
      accountState
      accountStateDesc
      accountSxname
      accountTerritory
      accountType
      accountXdisplayName
      accountXenvelopeGreeting
      accountXfirstName
      accountZipcode
      actionId
      agentActiveYn
      agentAddressType
      agentAddress1
      agentAddress2
      agentAlternateLanguage
      agentAlternateLanguageDesc
      agentAlternateSalutation
      agentAlternateTitle
      agentArNumber
      agentAuSrepCode
      agentAvailabilityOverride
      agentBookingId
      agentCblInd
      agentCity
      agentCityExt
      agentConActionCode
      agentConActiveYn
      agentConAddressType
      agentConAddress1
      agentConAddress2
      agentConAddress3
      agentConAddress4
      agentConAlternateLanguage
      agentConAlternateLanguageDesc
      agentConAlternateSalutation
      agentConAlternateTitle
      agentConArNumber
      agentConAuSrepCode
      agentConAvailabilityOverride
      agentConBirthDate
      agentConBirthDateStr
      agentConBookingId
      agentConBusinessGreeting
      agentConCashBlInd
      agentConCity
      agentConCityExt
      agentConContactYn
      agentConCountry
      agentConCountryDesc
      agentConDepartment
      agentConDsi
      agentConEmail
      agentConFax
      agentConFirst
      agentConHistoryYn
      agentConIataCompType
      agentConId
      agentConIndustryCode
      agentConInfluence
      agentConLanguage
      agentConLanguageDesc
      agentConLast
      agentConLetterGreeting
      agentConLinkId
      agentConLinkType
      agentConMailType
      agentConMarkets
      agentConMiddle
      agentConName
      agentConNameType
      agentConName2
      agentConName3
      agentConOrganizationid
      agentConPhone
      agentConPosition
      agentConPrimaryYn
      agentConProductInterest
      agentConRelationship
      agentConRelationshipDesc
      agentConRepAccountType
      agentConRepAccountsource
      agentConRepActionCode
      agentConRepIATACompType
      agentConRepIndustryCode
      agentConRepInfluence
      agentConRepMarkets
      agentConRepNameType
      agentConRepScope
      agentConRepScopeCity
      agentConRepStateCode
      agentConRepStateDescription
      agentConRepTerritory
      agentConRepTitle
      agentConResort
      agentConScope
      agentConScopeCity
      agentConSfirst
      agentConSname
      agentConSrepId
      agentConSrepName
      agentConState
      agentConStateDesc
      agentConSxfirstName
      agentConSxname
      agentConTerritory
      agentConTitle
      agentConXfirst
      agentConXlast
      agentConXletterGreeting
      agentConXname
      agentConZipcode
      agentCountry
      agentCountryDesc
      agentDsi
      agentEmail
      agentFax
      agentHistoryYn
      agentIataCompType
      agentId
      agentIndustryCode
      agentLanguage
      agentLanguageDesc
      agentLinkId
      agentLinkType
      agentMailType
      agentMarkets
      agentName
      agentNameId
      agentNameType
      agentName2
      agentName3
      agentOrganizationid
      agentPhone
      agentPrimaryYn
      agentProductInterest
      agentRelationship
      agentRelationshipDesc
      agentRepStateCode
      agentResort
      agentScope
      agentScopeCity
      agentSname
      agentState
      agentStateDesc
      agentSxname
      agentTerritory
      agentXdisplayName
      agentXenvelopeGreeting
      agentXfirstName
      agentZipcode
      alias
      allOwners
      allotmentCode
      allotmentHeaderId
      allotmentOrigion
      allotmentType
      arrivalTime
      attendees
      avgPeoplePerRoom
      avgRateNet
      beginDate
      bookingStatus
      bookingStatusOrderby
      bookingStatusType
      bookingStatusorder
      bookingmethod
      bookingmethoddesc
      bookingtype
      breakfastDesc
      breakfastPrice
      breakfastYn
      busblockId
      busblockProperty
      cBreakfastPrice
      cCompRoomValue
      cExchangeDate
      cExchangeRate
      cMtgBudget
      cPorteragePrice
      cPotRoomRevenue
      cServiceCharge
      cTaxAmount
      cancelRule
      cancellationCode
      cancellationDate
      cancellationDescription
      cancellationNo
      catCanxCode
      catCanxDate
      catCanxNumber
      catCurrency
      catCutoff
      catDecision
      catExchange
      catFollowup
      catOwner
      catOwnerCode
      catOwnerEmail
      catOwnerFax
      catOwnerPhone
      catOwnerProperty
      catOwnerSrepname
      catOwnerTitle
      catOwners
      catQuoteCurrency
      catStatus
      catStatusOrderby
      catStatusType
      catStatusorder
      cateringCanxDesc
      cateringPkgsYn
      cateringonlyYn
      centralOwner
      channel
      commission
      compPerStayYn
      compRoomValue
      compRooms
      compRoomsFixedYn
      companyNameId
      competition
      conActionCode
      conActiveYn
      conAddressType
      conAddress1
      conAddress2
      conAddress3
      conAddress4
      conAlternateLanguage
      conAlternateLanguageDesc
      conAlternateSalutation
      conAlternateTitle
      conArNumber
      conAvailabilityOverride
      conBirthDate
      conBirthDateStr
      conBookingId
      conBusinessGreeting
      conCashBlInd
      conCity
      conCityExt
      conContactYn
      conCountry
      conCountryDesc
      conDepartment
      conDsi
      conFirst
      conHistoryYn
      conIataCompType
      conId
      conIndustryCode
      conInfluence
      conLanguage
      conLanguageDesc
      conLast
      conLetterGreeting
      conLinkId
      conLinkType
      conMailType
      conMarkets
      conMiddle
      conName
      conNameType
      conName2
      conName3
      conOrganizationid
      conPosition
      conPrimaryYn
      conProductInterest
      conRelationship
      conRelationshipDesc
      conRepActionCode
      conRepInfluence
      conRepMarkets
      conRepNameType
      conRepScope
      conRepScopeCity
      conRepStateCode
      conRepStateDescription
      conRepTerritory
      conRepTitle
      conResort
      conScope
      conScopeCity
      conSfirst
      conSname
      conSrepCode
      conSrepId
      conSrepName
      conState
      conStateDesc
      conSxfirstName
      conSxname
      conTerritory
      conTitle
      conXfirst
      conXlast
      conXletterGreeting
      conXname
      contactEmail
      contactFax
      contactNameId
      contactPhone
      contactZipcode
      contractNr
      conversionCode
      currencyCode
      dSI
      dateOpenedForPickup
      datePro
      dateTen
      defaultPmReservationNameId
      deletedflag
      departureTime
      description
      destination
      detailsOkYn
      distributedYn
      dmlSeqNumber
      downloadDate
      downloadResort
      downloadSrep
      dueDate
      elastic
      endDate
      eventsGuaranteedYn
      exchangePostingType
      exchangeRate
      externalLocked
      functiontype
      giid
      guaranteeCode
      iataCorpNumber
      inactiveDate
      info
      infoboard
      insertDate
      insertUser
      insertUserName
      invCutoffDate
      invCutoffDays
      isacOpptyId
      isacQuoteId
      jRNUpdateDate
      jRNUpdateDateAndTime
      laptopChange
      leadOrigin
      leadSource
      linkDate
      lostToProperty
      mainmarket
      marEventType
      marHouseProtectYn
      marRollEndDateYn
      marketCode
      masterNameId
      methodDue
      mtgBudget
      nonCompete
      nonCompeteCode
      organizationID
      originalRateCode
      owner
      ownerCode
      ownerCodeSrepname
      ownerEmail
      ownerFax
      ownerPhone
      ownerResort
      ownerTitle
      paymentMethod
      peakRooms
      porteragePrice
      porterageYn
      printAccountActiveYN
      printAccountAddress1
      printAccountAddress2
      printAccountAddress3
      printAccountAddress4
      printAccountBookingId
      printAccountCity
      printAccountCityExt
      printAccountCountry
      printAccountCountryDesc
      printAccountDsi
      printAccountId
      printAccountLinkId
      printAccountLinkType
      printAccountName
      printAccountName2
      printAccountName3
      printAccountOrganizationid
      printAccountPhone
      printAccountPosition
      printAccountPrimaryYN
      printAccountProperty
      printAccountRepStateCode
      printAccountRepStateDescription
      printAccountRepTerritory
      printAccountScope
      printAccountScopeCity
      printAccountSname
      printAccountState
      printAccountStateDesc
      printAccountSxname
      printAccountTerritory
      printAccountXdisplayName
      printAccountXenvelopeGreeting
      printAccountXfirstName
      printAccountXname
      printAccountZipcode
      printConAddress1
      printConAddress2
      printConAddress3
      printConAddress4
      printConAlternateSalutation
      printConBusinessGreeting
      printConCity
      printConCityExt
      printConCountry
      printConCountryDesc
      printConDepartment
      printConDsi
      printConEmail
      printConFirst
      printConId
      printConLast
      printConLetterGreeting
      printConLinkId
      printConLinkType
      printConMiddle
      printConName
      printConName2
      printConName3
      printConOrganizationid
      printConPhone
      printConPosition
      printConPrimaryYn
      printConProductInterest
      printConRelationship
      printConRelationshipDesc
      printConRepStateCode
      printConRepTitle
      printConResort
      printConScope
      printConScopeCity
      printConSname
      printConState
      printConStateDesc
      printConSxname
      printConTerritory
      printConTitle
      printConXdisplayName
      printConXfirst
      printConXlast
      printConXletterGreeting
      printConZipcode
      profileDesc
      profileId
      program
      property
      rankingCode
      rateCode
      rateGuaranteedYn
      rateOverride
      rateOverrideReason
      rateProtection
      relatedResorts
      repBlockStatusDescription
      repBookingmethod
      repBookingmethodDescription
      repBookingtype
      repBsOrderBy
      repCateringOrderBy
      repCateringStatus
      repCateringStatusDescription
      repChannel
      repConversionCode
      repDestination
      repGuaranteeCode
      repMarketCode
      repNonCompeteCode
      repPaymentMethod
      repRankingCode
      repSourceCode
      representative
      reserveInventoryYn
      resortBooked
      revBlocked
      revBlockedNet
      revContracted
      rivMarketSegment
      rnaInsertDate
      rnaUpdateDate
      roomsBlocked
      roomsContracted
      roomsCurrency
      roomsDecision
      roomsExchange
      roomsFollowup
      roomsOwner
      roomsOwnerCode
      roomsOwnerEmail
      roomsOwnerFax
      roomsOwnerPhone
      roomsOwnerResort
      roomsOwnerSrepname
      roomsOwnerTitle
      roomsOwners
      roomsPerDay
      roomsQuoteCurr
      salesId
      sbegindate
      secConActionCode
      secConActiveYn
      secConAddress1
      secConAddress2
      secConAddress3
      secConAddress4
      secConAlternateLanguage
      secConAlternateLanguageDesc
      secConAlternateSalutation
      secConAlternateTitle
      secConBirthDate
      secConBirthDateStr
      secConBookingId
      secConBusinessGreeting
      secConCashBlInd
      secConCity
      secConCityExt
      secConContactYn
      secConCountry
      secConCountryDesc
      secConDepartment
      secConDsi
      secConEmail
      secConFax
      secConFirstName
      secConFullName
      secConId
      secConInfluence
      secConLanguage
      secConLanguageDesc
      secConLastName
      secConLetterGreeting
      secConLinkId
      secConLinkType
      secConMarkets
      secConMiddleName
      secConNameType
      secConName2
      secConName3
      secConOrganizationid
      secConPhone
      secConPosition
      secConPrimaryYn
      secConProductInterest
      secConRelationship
      secConRelationshipDesc
      secConRepActionCode
      secConRepInfluence
      secConRepMarkets
      secConRepNameType
      secConRepScope
      secConRepScopeCity
      secConRepStateCode
      secConRepStateDescription
      secConRepTerritory
      secConRepTitle
      secConResort
      secConScope
      secConScopeCity
      secConSfirst
      secConSname
      secConSrepCode
      secConSrepId
      secConSrepName
      secConState
      secConStateDesc
      secConSxfirstName
      secConSxname
      secConTerritory
      secConTitle
      secConXenvelopeGreeting
      secConXfirstName
      secConXfullName
      secConXlastName
      secConZipCode
      senddate
      sentDate
      serviceCharge
      shoulderBeginDate
      shoulderEndDate
      source
      sourceActiveYn
      sourceAddressType
      sourceAddress1
      sourceAddress2
      sourceAlternateLanguage
      sourceAlternateLanguageDesc
      sourceAlternateSalutation
      sourceAlternateTitle
      sourceBookingId
      sourceBusinessGreeting
      sourceCity
      sourceCityExt
      sourceConActionCode
      sourceConActiveYn
      sourceConAddressType
      sourceConAddress1
      sourceConAddress2
      sourceConAddress3
      sourceConAddress4
      sourceConAlternateLanguage
      sourceConAlternateLanguageDesc
      sourceConAlternateSalutation
      sourceConAlternateTitle
      sourceConArNumber
      sourceConAuSrepCode
      sourceConAvailabilityOverride
      sourceConBirthDate
      sourceConBirthDateStr
      sourceConBookingId
      sourceConBusinessGreeting
      sourceConCashBlInd
      sourceConCity
      sourceConCityExt
      sourceConContactYn
      sourceConCountry
      sourceConCountryDesc
      sourceConDepartment
      sourceConDsi
      sourceConEmail
      sourceConFax
      sourceConFirst
      sourceConHistoryYn
      sourceConIataCompType
      sourceConId
      sourceConIndustryCode
      sourceConInfluence
      sourceConLanguage
      sourceConLanguageDesc
      sourceConLast
      sourceConLetterGreeting
      sourceConLinkId
      sourceConLinkType
      sourceConMailType
      sourceConMarkets
      sourceConMiddle
      sourceConName
      sourceConNameType
      sourceConName2
      sourceConName3
      sourceConOrganizationid
      sourceConPhone
      sourceConPosition
      sourceConPrimaryYn
      sourceConProductInterest
      sourceConRelationship
      sourceConRelationshipDesc
      sourceConRepActionCode
      sourceConRepInfluence
      sourceConRepMarkets
      sourceConRepNameType
      sourceConRepScope
      sourceConRepScopeCity
      sourceConRepStateCode
      sourceConRepStateDescription
      sourceConRepTerritory
      sourceConRepTitle
      sourceConResort
      sourceConScope
      sourceConScopeCity
      sourceConSfirst
      sourceConSname
      sourceConSrepId
      sourceConSrepName
      sourceConState
      sourceConStateDesc
      sourceConSxfirstName
      sourceConSxname
      sourceConTerritory
      sourceConTitle
      sourceConXfirst
      sourceConXlast
      sourceConXletterGreeting
      sourceConXname
      sourceConZipcode
      sourceCountry
      sourceCountryDesc
      sourceDsi
      sourceEmail
      sourceFax
      sourceId
      sourceLinkId
      sourceLinkType
      sourceName
      sourceNameId
      sourceNameType
      sourceName2
      sourceName3
      sourceOrganizationid
      sourcePhone
      sourcePrimaryYn
      sourceRelationship
      sourceRelationshipDesc
      sourceRepStateCode
      sourceResort
      sourceScope
      sourceScopeCity
      sourceSname
      sourceState
      sourceStateDesc
      sourceSxname
      sourceTerritory
      sourceXdisplayName
      sourceXenvelopeGreeting
      sourceXfirstName
      sourceZipcode
      status
      superBlockId
      superBlockResort
      taxAmount
      tbdRates
      tentativeLevel
      tracecode
      udescription
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
      updateUserName
      uploadDate
      xaccName
      xagentName
      xsourceName
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