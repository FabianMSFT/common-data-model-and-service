---
title: CFDIWithholdingComplInterest_MX in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Interests in WorksheetLine(CFDIWithholdingComplInterest_MX)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/EInvoice/WorksheetLine/CFDIWithholdingComplInterest_MX.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CFDIWithholdingComplInterest_MX/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Interests</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CFDIWithholdingComplInterest_MX.md" target="_blank">WorksheetLine/CFDIWithholdingComplInterest_MX</a>|
|[FinancialSystem](#FinancialSystem)||<a href="CFDIWithholdingComplInterest_MX.md" target="_blank">WorksheetLine/CFDIWithholdingComplInterest_MX</a>|
|[InterestBelongsDerivedFinOp](#InterestBelongsDerivedFinOp)||<a href="CFDIWithholdingComplInterest_MX.md" target="_blank">WorksheetLine/CFDIWithholdingComplInterest_MX</a>|
|[InterestCashedInTheCurrentPeriod](#InterestCashedInTheCurrentPeriod)||<a href="CFDIWithholdingComplInterest_MX.md" target="_blank">WorksheetLine/CFDIWithholdingComplInterest_MX</a>|
|[InterestLossAmount](#InterestLossAmount)||<a href="CFDIWithholdingComplInterest_MX.md" target="_blank">WorksheetLine/CFDIWithholdingComplInterest_MX</a>|
|[InterestNominalAmount](#InterestNominalAmount)||<a href="CFDIWithholdingComplInterest_MX.md" target="_blank">WorksheetLine/CFDIWithholdingComplInterest_MX</a>|
|[InterestRealAmount](#InterestRealAmount)||<a href="CFDIWithholdingComplInterest_MX.md" target="_blank">WorksheetLine/CFDIWithholdingComplInterest_MX</a>|
|[WithholdingJourRecId](#WithholdingJourRecId)||<a href="CFDIWithholdingComplInterest_MX.md" target="_blank">WorksheetLine/CFDIWithholdingComplInterest_MX</a>|
|[DataAreaId](#DataAreaId)||<a href="CFDIWithholdingComplInterest_MX.md" target="_blank">WorksheetLine/CFDIWithholdingComplInterest_MX</a>|
|[Relationship_CFDIWithholdingJour_MXRelationshipId](#Relationship_CFDIWithholdingJour_MXRelationshipId)||<a href="CFDIWithholdingComplInterest_MX.md" target="_blank">WorksheetLine/CFDIWithholdingComplInterest_MX</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CFDIWithholdingComplInterest_MX.md" target="_blank">WorksheetLine/CFDIWithholdingComplInterest_MX</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/CFDIWithholdingComplInterest_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CFDIWithholdingComplInterest_MX/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FinancialSystem name="FinancialSystem">FinancialSystem</a>

First included in: WorksheetLine/CFDIWithholdingComplInterest_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FinancialSystem attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InterestBelongsDerivedFinOp name="InterestBelongsDerivedFinOp">InterestBelongsDerivedFinOp</a>

First included in: WorksheetLine/CFDIWithholdingComplInterest_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestBelongsDerivedFinOp attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InterestCashedInTheCurrentPeriod name="InterestCashedInTheCurrentPeriod">InterestCashedInTheCurrentPeriod</a>

First included in: WorksheetLine/CFDIWithholdingComplInterest_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestCashedInTheCurrentPeriod attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#InterestLossAmount name="InterestLossAmount">InterestLossAmount</a>

First included in: WorksheetLine/CFDIWithholdingComplInterest_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestLossAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InterestNominalAmount name="InterestNominalAmount">InterestNominalAmount</a>

First included in: WorksheetLine/CFDIWithholdingComplInterest_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestNominalAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#InterestRealAmount name="InterestRealAmount">InterestRealAmount</a>

First included in: WorksheetLine/CFDIWithholdingComplInterest_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InterestRealAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#WithholdingJourRecId name="WithholdingJourRecId">WithholdingJourRecId</a>

First included in: WorksheetLine/CFDIWithholdingComplInterest_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WithholdingJourRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/CFDIWithholdingComplInterest_MX (this entity)  

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

### <a href=#Relationship_CFDIWithholdingJour_MXRelationshipId name="Relationship_CFDIWithholdingJour_MXRelationshipId">Relationship_CFDIWithholdingJour_MXRelationshipId</a>

First included in: WorksheetLine/CFDIWithholdingComplInterest_MX (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CFDIWithholdingJour_MXRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/CFDIWithholdingJour_MX.md" target="_blank">/core/operationsCommon/Tables/Finance/EInvoice/Transaction/CFDIWithholdingJour_MX.cdm.json/CFDIWithholdingJour_MX</a></td><td><a href="../Transaction/CFDIWithholdingJour_MX.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/CFDIWithholdingComplInterest_MX (this entity)  

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
