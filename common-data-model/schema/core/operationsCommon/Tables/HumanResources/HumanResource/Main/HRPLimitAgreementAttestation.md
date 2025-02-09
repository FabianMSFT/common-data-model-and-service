---
title: HRPLimitAgreementAttestation in Main - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Signing limit agreement confirmation in Main(HRPLimitAgreementAttestation)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/HumanResources/HumanResource/Main/HRPLimitAgreementAttestation.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[HRPLimitAgreementAttestation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Signing limit agreement confirmation</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="HRPLimitAgreementAttestation.md" target="_blank">Main/HRPLimitAgreementAttestation</a>|
|[AttestationDateTime](#AttestationDateTime)||<a href="HRPLimitAgreementAttestation.md" target="_blank">Main/HRPLimitAgreementAttestation</a>|
|[LimitAgreementDetail](#LimitAgreementDetail)||<a href="HRPLimitAgreementAttestation.md" target="_blank">Main/HRPLimitAgreementAttestation</a>|
|[SigningLimitRequest](#SigningLimitRequest)||<a href="HRPLimitAgreementAttestation.md" target="_blank">Main/HRPLimitAgreementAttestation</a>|
|[ValidFrom](#ValidFrom)||<a href="HRPLimitAgreementAttestation.md" target="_blank">Main/HRPLimitAgreementAttestation</a>|
|[ValidTo](#ValidTo)||<a href="HRPLimitAgreementAttestation.md" target="_blank">Main/HRPLimitAgreementAttestation</a>|
|[Relationship_HRPLimitAgreementDetailRelationshipId](#Relationship_HRPLimitAgreementDetailRelationshipId)||<a href="HRPLimitAgreementAttestation.md" target="_blank">Main/HRPLimitAgreementAttestation</a>|
|[Relationship_HRPLimitRequestRelationshipId](#Relationship_HRPLimitRequestRelationshipId)||<a href="HRPLimitAgreementAttestation.md" target="_blank">Main/HRPLimitAgreementAttestation</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/HRPLimitAgreementAttestation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[HRPLimitAgreementAttestation/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#AttestationDateTime name="AttestationDateTime">AttestationDateTime</a>

First included in: Main/HRPLimitAgreementAttestation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AttestationDateTime attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.dataFormat.date**  
</details>

### <a href=#LimitAgreementDetail name="LimitAgreementDetail">LimitAgreementDetail</a>

First included in: Main/HRPLimitAgreementAttestation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LimitAgreementDetail attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SigningLimitRequest name="SigningLimitRequest">SigningLimitRequest</a>

First included in: Main/HRPLimitAgreementAttestation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SigningLimitRequest attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: Main/HRPLimitAgreementAttestation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: Main/HRPLimitAgreementAttestation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#Relationship_HRPLimitAgreementDetailRelationshipId name="Relationship_HRPLimitAgreementDetailRelationshipId">Relationship_HRPLimitAgreementDetailRelationshipId</a>

First included in: Main/HRPLimitAgreementAttestation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HRPLimitAgreementDetailRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="HRPLimitAgreementDetail.md" target="_blank">/core/operationsCommon/Tables/HumanResources/HumanResource/Main/HRPLimitAgreementDetail.cdm.json/HRPLimitAgreementDetail</a></td><td><a href="HRPLimitAgreementDetail.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_HRPLimitRequestRelationshipId name="Relationship_HRPLimitRequestRelationshipId">Relationship_HRPLimitRequestRelationshipId</a>

First included in: Main/HRPLimitAgreementAttestation (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_HRPLimitRequestRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="HRPLimitRequest.md" target="_blank">/core/operationsCommon/Tables/HumanResources/HumanResource/Main/HRPLimitRequest.cdm.json/HRPLimitRequest</a></td><td><a href="HRPLimitRequest.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
