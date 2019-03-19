---
title: Competitor - Common Data Model | Microsoft Docs
description: Business competing for the sale represented by a lead or opportunity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 3/11/2019
ms.author: nebanfic
---

# Competitor

Business competing for the sale represented by a lead or opportunity.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/sales/Competitor.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/sales/Competitor  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[competitorId](#competitorId)|Unique identifier of the competitor.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[createdBy](#createdBy)|Shows who created the record.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[versionNumber](#versionNumber)|Version Number|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[name](#name)|Type the company or business name used to identify the competitor in data views and related records.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[processId](#processId)|Contains the id of the process associated with the entity.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1AddressId](#address1AddressId)|Unique identifier for address 1.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1AddressTypeCode](#address1AddressTypeCode)|Select the primary address type.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1AddressTypeCode_display](#address1AddressTypeCode_display)||<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1City](#address1City)|Type the city for the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Country](#address1Country)|Type the country or region for the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Composite](#address1Composite)|Shows the complete primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1County](#address1County)|Type the county for the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Fax](#address1Fax)|Type the fax number associated with the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Latitude](#address1Latitude)|Type the latitude value for the primary address for use in mapping and other applications.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Line1](#address1Line1)|Type the first line of the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Line2](#address1Line2)|Type the second line of the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Line3](#address1Line3)|Type the third line of the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Longitude](#address1Longitude)|Type the longitude value for the primary address for use in mapping and other applications.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Name](#address1Name)|Type a descriptive name for the primary address, such as Corporate Headquarters.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1PostalCode](#address1PostalCode)|Type the ZIP Code or postal code for the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1PostOfficeBox](#address1PostOfficeBox)|Type the post office box number of the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1ShippingMethodCode](#address1ShippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1ShippingMethodCode_display](#address1ShippingMethodCode_display)||<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1StateOrProvince](#address1StateOrProvince)|Type the state or province of the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Telephone1](#address1Telephone1)|Type the main phone number associated with the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Telephone2](#address1Telephone2)|Type a second phone number associated with the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1Telephone3](#address1Telephone3)|Type a third phone number associated with the primary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1UPSZone](#address1UPSZone)|Type the UPS zone of the primary address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address1UTCOffset](#address1UTCOffset)|Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2AddressId](#address2AddressId)|Unique identifier for address 2.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2AddressTypeCode](#address2AddressTypeCode)|Select the secondary address type.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2AddressTypeCode_display](#address2AddressTypeCode_display)||<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2City](#address2City)|Type the city for the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Composite](#address2Composite)|Shows the complete secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Country](#address2Country)|Type the country or region for the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2County](#address2County)|Type the county for the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Fax](#address2Fax)|Type the fax number associated with the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Latitude](#address2Latitude)|Type the latitude value for the secondary address for use in mapping and other applications.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Line1](#address2Line1)|Type the first line of the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Line2](#address2Line2)|Type the second line of the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Line3](#address2Line3)|Type the third line of the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Longitude](#address2Longitude)|Type the longitude value for the secondary address for use in mapping and other applications.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Name](#address2Name)|Type a descriptive name for the secondary address, such as Corporate Headquarters.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2PostalCode](#address2PostalCode)|Type the ZIP Code or postal code for the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2PostOfficeBox](#address2PostOfficeBox)|Type the post office box number of the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2ShippingMethodCode](#address2ShippingMethodCode)|Select a shipping method for deliveries sent to this address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2ShippingMethodCode_display](#address2ShippingMethodCode_display)||<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2StateOrProvince](#address2StateOrProvince)|Type the state or province of the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Telephone1](#address2Telephone1)|Type the main phone number associated with the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Telephone2](#address2Telephone2)|Type a second phone number associated with the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2Telephone3](#address2Telephone3)|Type a third phone number associated with the secondary address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2UPSZone](#address2UPSZone)|Type the UPS zone of the secondary address to make sure shipping charges are calculated correctly and deliveries are made promptly , if shipped by UPS.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[address2UTCOffset](#address2UTCOffset)|Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[keyProduct](#keyProduct)|Type the competitor's primary product, service, or specialty.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[opportunities](#opportunities)|Type notes or other information about the competitive opportunities or selling points you can make.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[overview](#overview)|Type notes or other information about the competitor's business, such as location, revenue, or distribution channel.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[referenceInfoUrl](#referenceInfoUrl)|Type the URL for the website used to obtain reference information about the competitor.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[reportedRevenue](#reportedRevenue)|Type the amount of revenue reported in the competitor's annual report or other source.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[reportedRevenueBase](#reportedRevenueBase)|Value of the Reported Revenue in base currency.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[reportingQuarter](#reportingQuarter)|Type the quarter number during which the competitor's reported revenue was recorded or announced for use in reporting and analysis.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[reportingYear](#reportingYear)|Type the fiscal year during which the competitor's reported revenue was announced for use in reporting and analysis.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[stockExchange](#stockExchange)|Type the stock exchange at which the competitor is listed to track their stock and financial performance of the company.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[strengths](#strengths)|Type notes or other information about the competitor's strengths, such as top-selling products and targeted industries or markets.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[threats](#threats)|Type notes or other information about the competitor's threats to your organization when you sell to the same prospect or customer.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[tickerSymbol](#tickerSymbol)|Type the stock exchange symbol for the competitor to track financial performance of the company. You can click the code entered in this field to access the latest trading information from MSN Money.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[weaknesses](#weaknesses)|Type notes or other information about the competitor's weaknesses or areas in which your organization outperforms the competitor.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[webSiteUrl](#webSiteUrl)|Type the website URL for the competitor.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[winPercentage](#winPercentage)|Type the percentage of your organization's lost opportunities that are won by the competitor to identify your strongest competitors.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[entityImageId](#entityImageId)||<a href="Competitor.md" target="_blank">sales/Competitor</a>|
|[yomiName](#yomiName)|Type the phonetic spelling of the competitor's name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.|<a href="Competitor.md" target="_blank">sales/Competitor</a>|

### <a href=#competitorId name="competitorId">competitorId</a>

Unique identifier of the competitor.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Competitor </td></tr><tr><td>description</td><td>Unique identifier of the competitor.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>competitorid</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Shows who created the record.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Shows who last updated the record.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version Number  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#name name="name">name</a>

Type the company or business name used to identify the competitor in data views and related records.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type the company or business name used to identify the competitor in data views and related records.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#processId name="processId">processId</a>

Contains the id of the process associated with the entity.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Process Id</td></tr><tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>processid</td></tr></table>

### <a href=#stageId name="stageId">stageId</a>

Contains the id of the stage where the entity is located.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stage Id</td></tr><tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stageid</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#address1AddressId name="address1AddressId">address1AddressId</a>

Unique identifier for address 1.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: ID</td></tr><tr><td>description</td><td>Unique identifier for address 1.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_addressid</td></tr></table>

### <a href=#address1AddressTypeCode name="address1AddressTypeCode">address1AddressTypeCode</a>

Select the primary address type.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Address Type</td></tr><tr><td>description</td><td>Select the primary address type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address1AddressTypeCode_display name="address1AddressTypeCode_display">address1AddressTypeCode_display</a>

First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1City name="address1City">address1City</a>

Type the city for the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>City</td></tr><tr><td>description</td><td>Type the city for the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_city</td></tr></table>

### <a href=#address1Country name="address1Country">address1Country</a>

Type the country or region for the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_country</td></tr></table>

### <a href=#address1Composite name="address1Composite">address1Composite</a>

Shows the complete primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1</td></tr><tr><td>description</td><td>Shows the complete primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_composite</td></tr></table>

### <a href=#address1County name="address1County">address1County</a>

Type the county for the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: County</td></tr><tr><td>description</td><td>Type the county for the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_county</td></tr></table>

### <a href=#address1Fax name="address1Fax">address1Fax</a>

Type the fax number associated with the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Fax</td></tr><tr><td>description</td><td>Type the fax number associated with the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_fax</td></tr></table>

### <a href=#address1Latitude name="address1Latitude">address1Latitude</a>

Type the latitude value for the primary address for use in mapping and other applications.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Latitude</td></tr><tr><td>description</td><td>Type the latitude value for the primary address for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_latitude</td></tr></table>

### <a href=#address1Line1 name="address1Line1">address1Line1</a>

Type the first line of the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 1</td></tr><tr><td>description</td><td>Type the first line of the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line1</td></tr></table>

### <a href=#address1Line2 name="address1Line2">address1Line2</a>

Type the second line of the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 2</td></tr><tr><td>description</td><td>Type the second line of the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line2</td></tr></table>

### <a href=#address1Line3 name="address1Line3">address1Line3</a>

Type the third line of the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Street 3</td></tr><tr><td>description</td><td>Type the third line of the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_line3</td></tr></table>

### <a href=#address1Longitude name="address1Longitude">address1Longitude</a>

Type the longitude value for the primary address for use in mapping and other applications.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Longitude</td></tr><tr><td>description</td><td>Type the longitude value for the primary address for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_longitude</td></tr></table>

### <a href=#address1Name name="address1Name">address1Name</a>

Type a descriptive name for the primary address, such as Corporate Headquarters.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Name</td></tr><tr><td>description</td><td>Type a descriptive name for the primary address, such as Corporate Headquarters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_name</td></tr></table>

### <a href=#address1PostalCode name="address1PostalCode">address1PostalCode</a>

Type the ZIP Code or postal code for the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_postalcode</td></tr></table>

### <a href=#address1PostOfficeBox name="address1PostOfficeBox">address1PostOfficeBox</a>

Type the post office box number of the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Post Office Box</td></tr><tr><td>description</td><td>Type the post office box number of the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_postofficebox</td></tr></table>

### <a href=#address1ShippingMethodCode name="address1ShippingMethodCode">address1ShippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address1ShippingMethodCode_display name="address1ShippingMethodCode_display">address1ShippingMethodCode_display</a>

First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address1StateOrProvince name="address1StateOrProvince">address1StateOrProvince</a>

Type the state or province of the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>State/Province</td></tr><tr><td>description</td><td>Type the state or province of the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_stateorprovince</td></tr></table>

### <a href=#address1Telephone1 name="address1Telephone1">address1Telephone1</a>

Type the main phone number associated with the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Telephone 1</td></tr><tr><td>description</td><td>Type the main phone number associated with the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone1</td></tr></table>

### <a href=#address1Telephone2 name="address1Telephone2">address1Telephone2</a>

Type a second phone number associated with the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Telephone 2</td></tr><tr><td>description</td><td>Type a second phone number associated with the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone2</td></tr></table>

### <a href=#address1Telephone3 name="address1Telephone3">address1Telephone3</a>

Type a third phone number associated with the primary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number associated with the primary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_telephone3</td></tr></table>

### <a href=#address1UPSZone name="address1UPSZone">address1UPSZone</a>

Type the UPS zone of the primary address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: UPS Zone</td></tr><tr><td>description</td><td>Type the UPS zone of the primary address to make sure shipping charges are calculated correctly and deliveries are made promptly, if shipped by UPS.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_upszone</td></tr></table>

### <a href=#address1UTCOffset name="address1UTCOffset">address1UTCOffset</a>

Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 1: UTC Offset</td></tr><tr><td>description</td><td>Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address1_utcoffset</td></tr></table>

### <a href=#address2AddressId name="address2AddressId">address2AddressId</a>

Unique identifier for address 2.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: ID</td></tr><tr><td>description</td><td>Unique identifier for address 2.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_addressid</td></tr></table>

### <a href=#address2AddressTypeCode name="address2AddressTypeCode">address2AddressTypeCode</a>

Select the secondary address type.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Address Type</td></tr><tr><td>description</td><td>Select the secondary address type.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_addresstypecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address2AddressTypeCode_display name="address2AddressTypeCode_display">address2AddressTypeCode_display</a>

First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2City name="address2City">address2City</a>

Type the city for the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: City</td></tr><tr><td>description</td><td>Type the city for the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_city</td></tr></table>

### <a href=#address2Composite name="address2Composite">address2Composite</a>

Shows the complete secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2</td></tr><tr><td>description</td><td>Shows the complete secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_composite</td></tr></table>

### <a href=#address2Country name="address2Country">address2Country</a>

Type the country or region for the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Country/Region</td></tr><tr><td>description</td><td>Type the country or region for the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>80</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_country</td></tr></table>

### <a href=#address2County name="address2County">address2County</a>

Type the county for the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: County</td></tr><tr><td>description</td><td>Type the county for the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_county</td></tr></table>

### <a href=#address2Fax name="address2Fax">address2Fax</a>

Type the fax number associated with the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Fax</td></tr><tr><td>description</td><td>Type the fax number associated with the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_fax</td></tr></table>

### <a href=#address2Latitude name="address2Latitude">address2Latitude</a>

Type the latitude value for the secondary address for use in mapping and other applications.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Latitude</td></tr><tr><td>description</td><td>Type the latitude value for the secondary address for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>90</td></tr><tr><td>minimumValue</td><td>-90</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_latitude</td></tr></table>

### <a href=#address2Line1 name="address2Line1">address2Line1</a>

Type the first line of the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Street 1</td></tr><tr><td>description</td><td>Type the first line of the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line1</td></tr></table>

### <a href=#address2Line2 name="address2Line2">address2Line2</a>

Type the second line of the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Street 2</td></tr><tr><td>description</td><td>Type the second line of the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line2</td></tr></table>

### <a href=#address2Line3 name="address2Line3">address2Line3</a>

Type the third line of the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Street 3</td></tr><tr><td>description</td><td>Type the third line of the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>250</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_line3</td></tr></table>

### <a href=#address2Longitude name="address2Longitude">address2Longitude</a>

Type the longitude value for the secondary address for use in mapping and other applications.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Longitude</td></tr><tr><td>description</td><td>Type the longitude value for the secondary address for use in mapping and other applications.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>180</td></tr><tr><td>minimumValue</td><td>-180</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_longitude</td></tr></table>

### <a href=#address2Name name="address2Name">address2Name</a>

Type a descriptive name for the secondary address, such as Corporate Headquarters.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Name</td></tr><tr><td>description</td><td>Type a descriptive name for the secondary address, such as Corporate Headquarters.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_name</td></tr></table>

### <a href=#address2PostalCode name="address2PostalCode">address2PostalCode</a>

Type the ZIP Code or postal code for the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: ZIP/Postal Code</td></tr><tr><td>description</td><td>Type the ZIP Code or postal code for the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_postalcode</td></tr></table>

### <a href=#address2PostOfficeBox name="address2PostOfficeBox">address2PostOfficeBox</a>

Type the post office box number of the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Post Office Box</td></tr><tr><td>description</td><td>Type the post office box number of the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_postofficebox</td></tr></table>

### <a href=#address2ShippingMethodCode name="address2ShippingMethodCode">address2ShippingMethodCode</a>

Select a shipping method for deliveries sent to this address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Shipping Method</td></tr><tr><td>description</td><td>Select a shipping method for deliveries sent to this address.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_shippingmethodcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Default Value</td><td>1</td></tr></table></td></tr></table>

### <a href=#address2ShippingMethodCode_display name="address2ShippingMethodCode_display">address2ShippingMethodCode_display</a>

First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#address2StateOrProvince name="address2StateOrProvince">address2StateOrProvince</a>

Type the state or province of the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: State/Province</td></tr><tr><td>description</td><td>Type the state or province of the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_stateorprovince</td></tr></table>

### <a href=#address2Telephone1 name="address2Telephone1">address2Telephone1</a>

Type the main phone number associated with the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 1</td></tr><tr><td>description</td><td>Type the main phone number associated with the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone1</td></tr></table>

### <a href=#address2Telephone2 name="address2Telephone2">address2Telephone2</a>

Type a second phone number associated with the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 2</td></tr><tr><td>description</td><td>Type a second phone number associated with the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone2</td></tr></table>

### <a href=#address2Telephone3 name="address2Telephone3">address2Telephone3</a>

Type a third phone number associated with the secondary address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: Telephone 3</td></tr><tr><td>description</td><td>Type a third phone number associated with the secondary address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_telephone3</td></tr></table>

### <a href=#address2UPSZone name="address2UPSZone">address2UPSZone</a>

Type the UPS zone of the secondary address to make sure shipping charges are calculated correctly and deliveries are made promptly , if shipped by UPS.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: UPS Zone</td></tr><tr><td>description</td><td>Type the UPS zone of the secondary address to make sure shipping charges are calculated correctly and deliveries are made promptly , if shipped by UPS.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_upszone</td></tr></table>

### <a href=#address2UTCOffset name="address2UTCOffset">address2UTCOffset</a>

Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Address 2: UTC Offset</td></tr><tr><td>description</td><td>Select the time zone, or UTC offset, for this address so that other people can reference it when they contact someone at this address.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>1500</td></tr><tr><td>minimumValue</td><td>-1500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>address2_utcoffset</td></tr></table>

### <a href=#keyProduct name="keyProduct">keyProduct</a>

Type the competitor's primary product, service, or specialty.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Key Product</td></tr><tr><td>description</td><td>Type the competitor's primary product, service, or specialty.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>keyproduct</td></tr></table>

### <a href=#opportunities name="opportunities">opportunities</a>

Type notes or other information about the competitive opportunities or selling points you can make.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Opportunity</td></tr><tr><td>description</td><td>Type notes or other information about the competitive opportunities or selling points you can make.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>opportunities</td></tr></table>

### <a href=#overview name="overview">overview</a>

Type notes or other information about the competitor's business, such as location, revenue, or distribution channel.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overview</td></tr><tr><td>description</td><td>Type notes or other information about the competitor's business, such as location, revenue, or distribution channel.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overview</td></tr></table>

### <a href=#referenceInfoUrl name="referenceInfoUrl">referenceInfoUrl</a>

Type the URL for the website used to obtain reference information about the competitor.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reference Info URL</td></tr><tr><td>description</td><td>Type the URL for the website used to obtain reference information about the competitor.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>referenceinfourl</td></tr></table>

### <a href=#reportedRevenue name="reportedRevenue">reportedRevenue</a>

Type the amount of revenue reported in the competitor's annual report or other source.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reported Revenue</td></tr><tr><td>description</td><td>Type the amount of revenue reported in the competitor's annual report or other source.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>reportedrevenue</td></tr></table>

### <a href=#transactionCurrencyId name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr></table>

### <a href=#exchangeRate name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr></table>

### <a href=#reportedRevenueBase name="reportedRevenueBase">reportedRevenueBase</a>

Value of the Reported Revenue in base currency.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reported Revenue (Base)</td></tr><tr><td>description</td><td>Value of the Reported Revenue in base currency.</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>reportedrevenue_base</td></tr></table>

### <a href=#reportingQuarter name="reportingQuarter">reportingQuarter</a>

Type the quarter number during which the competitor's reported revenue was recorded or announced for use in reporting and analysis.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reporting Quarter</td></tr><tr><td>description</td><td>Type the quarter number during which the competitor's reported revenue was recorded or announced for use in reporting and analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>reportingquarter</td></tr></table>

### <a href=#reportingYear name="reportingYear">reportingYear</a>

Type the fiscal year during which the competitor's reported revenue was announced for use in reporting and analysis.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reporting Year</td></tr><tr><td>description</td><td>Type the fiscal year during which the competitor's reported revenue was announced for use in reporting and analysis.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>reportingyear</td></tr></table>

### <a href=#stockExchange name="stockExchange">stockExchange</a>

Type the stock exchange at which the competitor is listed to track their stock and financial performance of the company.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stock Exchange</td></tr><tr><td>description</td><td>Type the stock exchange at which the competitor is listed to track their stock and financial performance of the company.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stockexchange</td></tr></table>

### <a href=#strengths name="strengths">strengths</a>

Type notes or other information about the competitor's strengths, such as top-selling products and targeted industries or markets.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Strength</td></tr><tr><td>description</td><td>Type notes or other information about the competitor's strengths, such as top-selling products and targeted industries or markets.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>strengths</td></tr></table>

### <a href=#threats name="threats">threats</a>

Type notes or other information about the competitor's threats to your organization when you sell to the same prospect or customer.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Threat</td></tr><tr><td>description</td><td>Type notes or other information about the competitor's threats to your organization when you sell to the same prospect or customer.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>threats</td></tr></table>

### <a href=#tickerSymbol name="tickerSymbol">tickerSymbol</a>

Type the stock exchange symbol for the competitor to track financial performance of the company. You can click the code entered in this field to access the latest trading information from MSN Money.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ticker Symbol</td></tr><tr><td>description</td><td>Type the stock exchange symbol for the competitor to track financial performance of the company. You can click the code entered in this field to access the latest trading information from MSN Money.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>10</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>tickersymbol</td></tr></table>

### <a href=#weaknesses name="weaknesses">weaknesses</a>

Type notes or other information about the competitor's weaknesses or areas in which your organization outperforms the competitor.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Weakness</td></tr><tr><td>description</td><td>Type notes or other information about the competitor's weaknesses or areas in which your organization outperforms the competitor.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>weaknesses</td></tr></table>

### <a href=#webSiteUrl name="webSiteUrl">webSiteUrl</a>

Type the website URL for the competitor.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Website</td></tr><tr><td>description</td><td>Type the website URL for the competitor.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>websiteurl</td></tr></table>

### <a href=#winPercentage name="winPercentage">winPercentage</a>

Type the percentage of your organization's lost opportunities that are won by the competitor to identify your strongest competitors.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Win Percentage</td></tr><tr><td>description</td><td>Type the percentage of your organization's lost opportunities that are won by the competitor to identify your strongest competitors.</td></tr><tr><td>dataFormat</td><td>Double</td></tr><tr><td>maximumValue</td><td>1000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>winpercentage</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#yomiName name="yomiName">yomiName</a>

Type the phonetic spelling of the competitor's name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.  
First included in: sales/Competitor (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yomi Name</td></tr><tr><td>description</td><td>Type the phonetic spelling of the competitor's name, if specified in Japanese, to make sure the name is pronounced correctly in phone calls and other communications.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yominame</td></tr></table>
