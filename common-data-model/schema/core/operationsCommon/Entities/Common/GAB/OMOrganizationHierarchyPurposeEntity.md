---
title: OMOrganizationHierarchyPurposeEntity in GAB - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Organization hierarchy purposes in GAB(OMOrganizationHierarchyPurposeEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Common/GAB/OMOrganizationHierarchyPurposeEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Organization hierarchy purposes</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[HierarchyPurpose](#HierarchyPurpose)||<a href="OMOrganizationHierarchyPurposeEntity.md" target="_blank">GAB/OMOrganizationHierarchyPurposeEntity</a>|
|[HierarchyTypeRecId](#HierarchyTypeRecId)||<a href="OMOrganizationHierarchyPurposeEntity.md" target="_blank">GAB/OMOrganizationHierarchyPurposeEntity</a>|
|[SetAsDefault](#SetAsDefault)||<a href="OMOrganizationHierarchyPurposeEntity.md" target="_blank">GAB/OMOrganizationHierarchyPurposeEntity</a>|
|[Immutable](#Immutable)||<a href="OMOrganizationHierarchyPurposeEntity.md" target="_blank">GAB/OMOrganizationHierarchyPurposeEntity</a>|
|[HierarchyType](#HierarchyType)||<a href="OMOrganizationHierarchyPurposeEntity.md" target="_blank">GAB/OMOrganizationHierarchyPurposeEntity</a>|
|[BackingTable_OMHierarchyPurposeRelationshipId](#BackingTable_OMHierarchyPurposeRelationshipId)||<a href="OMOrganizationHierarchyPurposeEntity.md" target="_blank">GAB/OMOrganizationHierarchyPurposeEntity</a>|

### <a href=#HierarchyPurpose name="HierarchyPurpose">HierarchyPurpose</a>

First included in: GAB/OMOrganizationHierarchyPurposeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyPurpose attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyTypeRecId name="HierarchyTypeRecId">HierarchyTypeRecId</a>

First included in: GAB/OMOrganizationHierarchyPurposeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SetAsDefault name="SetAsDefault">SetAsDefault</a>

First included in: GAB/OMOrganizationHierarchyPurposeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SetAsDefault attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Immutable name="Immutable">Immutable</a>

First included in: GAB/OMOrganizationHierarchyPurposeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Immutable attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#HierarchyType name="HierarchyType">HierarchyType</a>

First included in: GAB/OMOrganizationHierarchyPurposeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the HierarchyType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_OMHierarchyPurposeRelationshipId name="BackingTable_OMHierarchyPurposeRelationshipId">BackingTable_OMHierarchyPurposeRelationshipId</a>

First included in: GAB/OMOrganizationHierarchyPurposeEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_OMHierarchyPurposeRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Common/GAB/Main/OMHierarchyPurpose.md" target="_blank">/core/operationsCommon/Tables/Common/GAB/Main/OMHierarchyPurpose.cdm.json/OMHierarchyPurpose</a></td><td><a href="../../../Tables/Common/GAB/Main/OMHierarchyPurpose.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
