---
title: TaxGSTReportConfigurationLine_MY in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# GST report configuration lines in Miscellaneous(TaxGSTReportConfigurationLine_MY)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxGSTReportConfigurationLine_MY.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxGSTReportConfigurationLine_MY/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>GST report configuration lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="TaxGSTReportConfigurationLine_MY.md" target="_blank">Miscellaneous/TaxGSTReportConfigurationLine_MY</a>|
|[TaxGSTReportConfiguration](#TaxGSTReportConfiguration)||<a href="TaxGSTReportConfigurationLine_MY.md" target="_blank">Miscellaneous/TaxGSTReportConfigurationLine_MY</a>|
|[TaxReportCollectionRecIdsTaxAmount](#TaxReportCollectionRecIdsTaxAmount)||<a href="TaxGSTReportConfigurationLine_MY.md" target="_blank">Miscellaneous/TaxGSTReportConfigurationLine_MY</a>|
|[TaxReportCollectionRecIdsTaxBaseAmount](#TaxReportCollectionRecIdsTaxBaseAmount)||<a href="TaxGSTReportConfigurationLine_MY.md" target="_blank">Miscellaneous/TaxGSTReportConfigurationLine_MY</a>|
|[TaxReportCollectionsTaxAmount](#TaxReportCollectionsTaxAmount)||<a href="TaxGSTReportConfigurationLine_MY.md" target="_blank">Miscellaneous/TaxGSTReportConfigurationLine_MY</a>|
|[TaxReportCollectionsTaxBaseAmount](#TaxReportCollectionsTaxBaseAmount)||<a href="TaxGSTReportConfigurationLine_MY.md" target="_blank">Miscellaneous/TaxGSTReportConfigurationLine_MY</a>|
|[TypeOfTransaction](#TypeOfTransaction)||<a href="TaxGSTReportConfigurationLine_MY.md" target="_blank">Miscellaneous/TaxGSTReportConfigurationLine_MY</a>|
|[DataAreaId](#DataAreaId)||<a href="TaxGSTReportConfigurationLine_MY.md" target="_blank">Miscellaneous/TaxGSTReportConfigurationLine_MY</a>|
|[Relationship_TaxGSTReportConfiguration_MYRelationshipId](#Relationship_TaxGSTReportConfiguration_MYRelationshipId)||<a href="TaxGSTReportConfigurationLine_MY.md" target="_blank">Miscellaneous/TaxGSTReportConfigurationLine_MY</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="TaxGSTReportConfigurationLine_MY.md" target="_blank">Miscellaneous/TaxGSTReportConfigurationLine_MY</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/TaxGSTReportConfigurationLine_MY (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[TaxGSTReportConfigurationLine_MY/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxGSTReportConfiguration name="TaxGSTReportConfiguration">TaxGSTReportConfiguration</a>

First included in: Miscellaneous/TaxGSTReportConfigurationLine_MY (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxGSTReportConfiguration attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TaxReportCollectionRecIdsTaxAmount name="TaxReportCollectionRecIdsTaxAmount">TaxReportCollectionRecIdsTaxAmount</a>

First included in: Miscellaneous/TaxGSTReportConfigurationLine_MY (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportCollectionRecIdsTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReportCollectionRecIdsTaxBaseAmount name="TaxReportCollectionRecIdsTaxBaseAmount">TaxReportCollectionRecIdsTaxBaseAmount</a>

First included in: Miscellaneous/TaxGSTReportConfigurationLine_MY (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportCollectionRecIdsTaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReportCollectionsTaxAmount name="TaxReportCollectionsTaxAmount">TaxReportCollectionsTaxAmount</a>

First included in: Miscellaneous/TaxGSTReportConfigurationLine_MY (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>GST amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportCollectionsTaxAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>GST amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TaxReportCollectionsTaxBaseAmount name="TaxReportCollectionsTaxBaseAmount">TaxReportCollectionsTaxBaseAmount</a>

First included in: Miscellaneous/TaxGSTReportConfigurationLine_MY (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction amount</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TaxReportCollectionsTaxBaseAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TypeOfTransaction name="TypeOfTransaction">TypeOfTransaction</a>

First included in: Miscellaneous/TaxGSTReportConfigurationLine_MY (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Type of transactions</td></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TypeOfTransaction attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type of transactions</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/TaxGSTReportConfigurationLine_MY (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_TaxGSTReportConfiguration_MYRelationshipId name="Relationship_TaxGSTReportConfiguration_MYRelationshipId">Relationship_TaxGSTReportConfiguration_MYRelationshipId</a>

First included in: Miscellaneous/TaxGSTReportConfigurationLine_MY (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_TaxGSTReportConfiguration_MYRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="TaxGSTReportConfiguration_MY.md" target="_blank">/core/operationsCommon/Tables/Finance/Tax/Miscellaneous/TaxGSTReportConfiguration_MY.cdm.json/TaxGSTReportConfiguration_MY</a></td><td><a href="TaxGSTReportConfiguration_MY.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/TaxGSTReportConfigurationLine_MY (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CompanyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
