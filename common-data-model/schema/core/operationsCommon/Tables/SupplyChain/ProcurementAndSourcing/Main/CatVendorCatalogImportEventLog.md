---
title: CatVendorCatalogImportEventLog in Main - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Catalog import event log in Main(CatVendorCatalogImportEventLog)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorCatalogImportEventLog.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CatVendorCatalogImportEventLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Catalog import event log</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CatVendorCatalogImportEventLog.md" target="_blank">Main/CatVendorCatalogImportEventLog</a>|
|[CatVendorCatalogMaintenanceRequest](#CatVendorCatalogMaintenanceRequest)||<a href="CatVendorCatalogImportEventLog.md" target="_blank">Main/CatVendorCatalogImportEventLog</a>|
|[EventDateTime](#EventDateTime)||<a href="CatVendorCatalogImportEventLog.md" target="_blank">Main/CatVendorCatalogImportEventLog</a>|
|[Message](#Message)||<a href="CatVendorCatalogImportEventLog.md" target="_blank">Main/CatVendorCatalogImportEventLog</a>|
|[MessageType](#MessageType)||<a href="CatVendorCatalogImportEventLog.md" target="_blank">Main/CatVendorCatalogImportEventLog</a>|
|[ProcessingState](#ProcessingState)||<a href="CatVendorCatalogImportEventLog.md" target="_blank">Main/CatVendorCatalogImportEventLog</a>|
|[Relationship_CatVendorCatalogMaintenanceRequestRelationshipId](#Relationship_CatVendorCatalogMaintenanceRequestRelationshipId)||<a href="CatVendorCatalogImportEventLog.md" target="_blank">Main/CatVendorCatalogImportEventLog</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/CatVendorCatalogImportEventLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CatVendorCatalogImportEventLog/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CatVendorCatalogMaintenanceRequest name="CatVendorCatalogMaintenanceRequest">CatVendorCatalogMaintenanceRequest</a>

First included in: Main/CatVendorCatalogImportEventLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CatVendorCatalogMaintenanceRequest attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EventDateTime name="EventDateTime">EventDateTime</a>

First included in: Main/CatVendorCatalogImportEventLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EventDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#Message name="Message">Message</a>

First included in: Main/CatVendorCatalogImportEventLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Message attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#MessageType name="MessageType">MessageType</a>

First included in: Main/CatVendorCatalogImportEventLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the MessageType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProcessingState name="ProcessingState">ProcessingState</a>

First included in: Main/CatVendorCatalogImportEventLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProcessingState attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_CatVendorCatalogMaintenanceRequestRelationshipId name="Relationship_CatVendorCatalogMaintenanceRequestRelationshipId">Relationship_CatVendorCatalogMaintenanceRequestRelationshipId</a>

First included in: Main/CatVendorCatalogImportEventLog (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CatVendorCatalogMaintenanceRequestRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="CatVendorCatalogMaintenanceRequest.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProcurementAndSourcing/Main/CatVendorCatalogMaintenanceRequest.cdm.json/CatVendorCatalogMaintenanceRequest</a></td><td><a href="CatVendorCatalogMaintenanceRequest.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
