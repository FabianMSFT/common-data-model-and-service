---
title: AifPortValueMap in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Port value map in Miscellaneous(AifPortValueMap)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Miscellaneous/AifPortValueMap.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AifPortValueMap/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Document setup</td></tr><tr><td>en</td><td>Port value map</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[CurrencyExtCodeId](#CurrencyExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[ActionId](#ActionId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[AgreementClassificationExtCodeId](#AgreementClassificationExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[BarCodeSetupId](#BarCodeSetupId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[BarCodeTypeCodeValue](#BarCodeTypeCodeValue)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[CountryRegionExtCodeId](#CountryRegionExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[CountyExtCodeId](#CountyExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[CustAccountExtCodeId](#CustAccountExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Defaulting](#Defaulting)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[DlvModeExtCodeId](#DlvModeExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[DlvTermExtCodeId](#DlvTermExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[EndpointId](#EndpointId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[InventLocationExtCodeId](#InventLocationExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[ItemExtCodeId](#ItemExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[LimitationType](#LimitationType)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[LimitDocuments](#LimitDocuments)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[MarkupExtCodeId](#MarkupExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[MaxNoOfDocuments](#MaxNoOfDocuments)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[ReturnDispCodeExtCodeId](#ReturnDispCodeExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[ReturnReasonCodeExtCodeId](#ReturnReasonCodeExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[StateExtCodeId](#StateExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[TaxExtCodeId](#TaxExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[UnitExtCodeId](#UnitExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[ValidateInput](#ValidateInput)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[VendAccountExtCodeId](#VendAccountExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLDocPurpose](#XMLDocPurpose)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapAgreementClassification](#XMLMapAgreementClassification)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapCountryRegion](#XMLMapCountryRegion)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapCounty](#XMLMapCounty)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapCurrencyCode](#XMLMapCurrencyCode)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapCustAccount](#XMLMapCustAccount)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapDlvMode](#XMLMapDlvMode)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapDlvTerm](#XMLMapDlvTerm)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapInventLocation](#XMLMapInventLocation)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapItemId](#XMLMapItemId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapMarkup](#XMLMapMarkup)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapReturnDispCodeId](#XMLMapReturnDispCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapReturnReasonCodeId](#XMLMapReturnReasonCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapState](#XMLMapState)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapTaxCode](#XMLMapTaxCode)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapUnitOfMeasureSymbol](#XMLMapUnitOfMeasureSymbol)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapVendAccount](#XMLMapVendAccount)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[XMLMapZipCode](#XMLMapZipCode)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[ZipCodeExtCodeId](#ZipCodeExtCodeId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_AgreementClassificationExtCodeRelationshipId](#Relationship_AgreementClassificationExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_BarCodeSetupRelationshipId](#Relationship_BarCodeSetupRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_CountryRegionExtCodeRelationshipId](#Relationship_CountryRegionExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_CountyExtCodeRelationshipId](#Relationship_CountyExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_CustAccountExtCodeRelationshipId](#Relationship_CustAccountExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_DlvModeExtCodeRelationshipId](#Relationship_DlvModeExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_DlvTermExtCodeRelationshipId](#Relationship_DlvTermExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_InventLocationExtCodeRelationshipId](#Relationship_InventLocationExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_ItemExtCodeRelationshipId](#Relationship_ItemExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_MarkupExtCodeRelationshipId](#Relationship_MarkupExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_ReturnDispCodeExtCodeRelationshipId](#Relationship_ReturnDispCodeExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_ReturnReasonCodeExtCodeRelationshipId](#Relationship_ReturnReasonCodeExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_StateExtCodeRelationshipId](#Relationship_StateExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_TaxExtCodeRelationshipId](#Relationship_TaxExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_UnitExtCodeRelationshipId](#Relationship_UnitExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_VendAccountExtCodeRelationshipId](#Relationship_VendAccountExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[Relationship_ZipCodeExtCodeRelationshipId](#Relationship_ZipCodeExtCodeRelationshipId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|
|[PortId](#PortId)||<a href="AifPortValueMap.md" target="_blank">Miscellaneous/AifPortValueMap</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[AifPortValueMap/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CurrencyExtCodeId name="CurrencyExtCodeId">CurrencyExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#ActionId name="ActionId">ActionId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ActionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AgreementClassificationExtCodeId name="AgreementClassificationExtCodeId">AgreementClassificationExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AgreementClassificationExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#BarCodeSetupId name="BarCodeSetupId">BarCodeSetupId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCodeSetupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BarCodeTypeCodeValue name="BarCodeTypeCodeValue">BarCodeTypeCodeValue</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BarCodeTypeCodeValue attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#CountryRegionExtCodeId name="CountryRegionExtCodeId">CountryRegionExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountryRegionExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#CountyExtCodeId name="CountyExtCodeId">CountyExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CountyExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#CustAccountExtCodeId name="CustAccountExtCodeId">CustAccountExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccountExtCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Defaulting name="Defaulting">Defaulting</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use defaulting</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Defaulting attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Use defaulting</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#DlvModeExtCodeId name="DlvModeExtCodeId">DlvModeExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvModeExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#DlvTermExtCodeId name="DlvTermExtCodeId">DlvTermExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DlvTermExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#EndpointId name="EndpointId">EndpointId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EndpointId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InventLocationExtCodeId name="InventLocationExtCodeId">InventLocationExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InventLocationExtCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ItemExtCodeId name="ItemExtCodeId">ItemExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ItemExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#LimitationType name="LimitationType">LimitationType</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitationType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#LimitDocuments name="LimitDocuments">LimitDocuments</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Limit number of documents</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitDocuments attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Limit number of documents</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#MarkupExtCodeId name="MarkupExtCodeId">MarkupExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MarkupExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#MaxNoOfDocuments name="MaxNoOfDocuments">MaxNoOfDocuments</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MaxNoOfDocuments attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ReturnDispCodeExtCodeId name="ReturnDispCodeExtCodeId">ReturnDispCodeExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnDispCodeExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#ReturnReasonCodeExtCodeId name="ReturnReasonCodeExtCodeId">ReturnReasonCodeExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReturnReasonCodeExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#StateExtCodeId name="StateExtCodeId">StateExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the StateExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#TaxExtCodeId name="TaxExtCodeId">TaxExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#UnitExtCodeId name="UnitExtCodeId">UnitExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UnitExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#ValidateInput name="ValidateInput">ValidateInput</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Validate input</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidateInput attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Validate input</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#VendAccountExtCodeId name="VendAccountExtCodeId">VendAccountExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VendAccountExtCodeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#XMLDocPurpose name="XMLDocPurpose">XMLDocPurpose</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLDocPurpose attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapAgreementClassification name="XMLMapAgreementClassification">XMLMapAgreementClassification</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapAgreementClassification attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapCountryRegion name="XMLMapCountryRegion">XMLMapCountryRegion</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapCountryRegion attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapCounty name="XMLMapCounty">XMLMapCounty</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapCounty attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapCurrencyCode name="XMLMapCurrencyCode">XMLMapCurrencyCode</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapCurrencyCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapCustAccount name="XMLMapCustAccount">XMLMapCustAccount</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapCustAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapDlvMode name="XMLMapDlvMode">XMLMapDlvMode</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapDlvMode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapDlvTerm name="XMLMapDlvTerm">XMLMapDlvTerm</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapDlvTerm attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapInventLocation name="XMLMapInventLocation">XMLMapInventLocation</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapInventLocation attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapItemId name="XMLMapItemId">XMLMapItemId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapItemId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapMarkup name="XMLMapMarkup">XMLMapMarkup</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapMarkup attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapReturnDispCodeId name="XMLMapReturnDispCodeId">XMLMapReturnDispCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapReturnDispCodeId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapReturnReasonCodeId name="XMLMapReturnReasonCodeId">XMLMapReturnReasonCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapReturnReasonCodeId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapState name="XMLMapState">XMLMapState</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapTaxCode name="XMLMapTaxCode">XMLMapTaxCode</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapTaxCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapUnitOfMeasureSymbol name="XMLMapUnitOfMeasureSymbol">XMLMapUnitOfMeasureSymbol</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapUnitOfMeasureSymbol attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapVendAccount name="XMLMapVendAccount">XMLMapVendAccount</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapVendAccount attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#XMLMapZipCode name="XMLMapZipCode">XMLMapZipCode</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the XMLMapZipCode attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ZipCodeExtCodeId name="ZipCodeExtCodeId">ZipCodeExtCodeId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ZipCodeExtCodeId attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#Relationship_AgreementClassificationExtCodeRelationshipId name="Relationship_AgreementClassificationExtCodeRelationshipId">Relationship_AgreementClassificationExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_AgreementClassificationExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_BarCodeSetupRelationshipId name="Relationship_BarCodeSetupRelationshipId">Relationship_BarCodeSetupRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_BarCodeSetupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Inventory/Group/BarcodeSetup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/Inventory/Group/BarcodeSetup.cdm.json/BarcodeSetup</a></td><td><a href="../../Inventory/Group/BarcodeSetup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CountryRegionExtCodeRelationshipId name="Relationship_CountryRegionExtCodeRelationshipId">Relationship_CountryRegionExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CountryRegionExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CountyExtCodeRelationshipId name="Relationship_CountyExtCodeRelationshipId">Relationship_CountyExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CountyExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustAccountExtCodeRelationshipId name="Relationship_CustAccountExtCodeRelationshipId">Relationship_CustAccountExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustAccountExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DlvModeExtCodeRelationshipId name="Relationship_DlvModeExtCodeRelationshipId">Relationship_DlvModeExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DlvModeExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DlvTermExtCodeRelationshipId name="Relationship_DlvTermExtCodeRelationshipId">Relationship_DlvTermExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DlvTermExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_InventLocationExtCodeRelationshipId name="Relationship_InventLocationExtCodeRelationshipId">Relationship_InventLocationExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_InventLocationExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ItemExtCodeRelationshipId name="Relationship_ItemExtCodeRelationshipId">Relationship_ItemExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ItemExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_MarkupExtCodeRelationshipId name="Relationship_MarkupExtCodeRelationshipId">Relationship_MarkupExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_MarkupExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReturnDispCodeExtCodeRelationshipId name="Relationship_ReturnDispCodeExtCodeRelationshipId">Relationship_ReturnDispCodeExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReturnDispCodeExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ReturnReasonCodeExtCodeRelationshipId name="Relationship_ReturnReasonCodeExtCodeRelationshipId">Relationship_ReturnReasonCodeExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ReturnReasonCodeExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_StateExtCodeRelationshipId name="Relationship_StateExtCodeRelationshipId">Relationship_StateExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_StateExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxExtCodeRelationshipId name="Relationship_TaxExtCodeRelationshipId">Relationship_TaxExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_UnitExtCodeRelationshipId name="Relationship_UnitExtCodeRelationshipId">Relationship_UnitExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_UnitExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendAccountExtCodeRelationshipId name="Relationship_VendAccountExtCodeRelationshipId">Relationship_VendAccountExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendAccountExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_ZipCodeExtCodeRelationshipId name="Relationship_ZipCodeExtCodeRelationshipId">Relationship_ZipCodeExtCodeRelationshipId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_ZipCodeExtCodeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/ExtCodeTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Group/ExtCodeTable.cdm.json/ExtCodeTable</a></td><td><a href="../Group/ExtCodeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PortId name="PortId">PortId</a>

First included in: Miscellaneous/AifPortValueMap (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PortId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>
