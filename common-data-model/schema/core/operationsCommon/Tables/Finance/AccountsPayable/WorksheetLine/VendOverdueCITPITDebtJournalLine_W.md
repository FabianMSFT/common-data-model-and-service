---
title: VendOverdueCITPITDebtJournalLine_W in WorksheetLine - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Overdue vendor debt CIT and PIT lines in WorksheetLine(VendOverdueCITPITDebtJournalLine_W)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsPayable/WorksheetLine/VendOverdueCITPITDebtJournalLine_W.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendOverdueCITPITDebtJournalLine_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Overdue vendor debt CIT and PIT lines</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|
|[DueDate](#DueDate)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|
|[JournalId](#JournalId)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|
|[OverdueAmountCur](#OverdueAmountCur)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|
|[OverdueAmountMST](#OverdueAmountMST)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|
|[SettingRecId](#SettingRecId)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|
|[TransRefRecId](#TransRefRecId)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|
|[DataAreaId](#DataAreaId)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|
|[Relationship_OverdueJournalSettings_WRelationshipId](#Relationship_OverdueJournalSettings_WRelationshipId)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|
|[Relationship_VendOverdueCITPITJournalTable_WRelationshipId](#Relationship_VendOverdueCITPITJournalTable_WRelationshipId)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|
|[Relationship_VendTransRelationshipId](#Relationship_VendTransRelationshipId)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="VendOverdueCITPITDebtJournalLine_W.md" target="_blank">WorksheetLine/VendOverdueCITPITDebtJournalLine_W</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[VendOverdueCITPITDebtJournalLine_W/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DueDate name="DueDate">DueDate</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DueDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#OverdueAmountCur name="OverdueAmountCur">OverdueAmountCur</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overdue amount in transaction currency</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverdueAmountCur attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Overdue amount in transaction currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#OverdueAmountMST name="OverdueAmountMST">OverdueAmountMST</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overdue amount</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the OverdueAmountMST attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Overdue amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#SettingRecId name="SettingRecId">SettingRecId</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SettingRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#TransRefRecId name="TransRefRecId">TransRefRecId</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransRefRecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

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

### <a href=#Relationship_OverdueJournalSettings_WRelationshipId name="Relationship_OverdueJournalSettings_WRelationshipId">Relationship_OverdueJournalSettings_WRelationshipId</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_OverdueJournalSettings_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Parameter/OverdueJournalSettings_W.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Parameter/OverdueJournalSettings_W.cdm.json/OverdueJournalSettings_W</a></td><td><a href="../../APARShared/Parameter/OverdueJournalSettings_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendOverdueCITPITJournalTable_WRelationshipId name="Relationship_VendOverdueCITPITJournalTable_WRelationshipId">Relationship_VendOverdueCITPITJournalTable_WRelationshipId</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendOverdueCITPITJournalTable_WRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/VendOverdueCITPITJournalTable_W.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/WorksheetHeader/VendOverdueCITPITJournalTable_W.cdm.json/VendOverdueCITPITJournalTable_W</a></td><td><a href="../WorksheetHeader/VendOverdueCITPITJournalTable_W.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_VendTransRelationshipId name="Relationship_VendTransRelationshipId">Relationship_VendTransRelationshipId</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_VendTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/VendTrans.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsPayable/Transaction/VendTrans.cdm.json/VendTrans</a></td><td><a href="../Transaction/VendTrans.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: WorksheetLine/VendOverdueCITPITDebtJournalLine_W (this entity)  

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
