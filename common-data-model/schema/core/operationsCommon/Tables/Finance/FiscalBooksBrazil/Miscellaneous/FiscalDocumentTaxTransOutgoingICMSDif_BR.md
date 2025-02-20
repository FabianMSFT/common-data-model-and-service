---
title: FiscalDocumentTaxTransOutgoingICMSDif_BR in Miscellaneous - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Destination state sales tax amount in Miscellaneous(FiscalDocumentTaxTransOutgoingICMSDif_BR)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FiscalDocumentTaxTransOutgoingICMSDif_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Destination state sales tax amount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|
|[FiscalDocument](#FiscalDocument)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|
|[FiscalDocumentDate](#FiscalDocumentDate)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|
|[FiscalDocumentLine](#FiscalDocumentLine)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|
|[FiscalDocumentTaxTrans](#FiscalDocumentTaxTrans)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|
|[ICMSDifIssuerTaxAmount](#ICMSDifIssuerTaxAmount)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|
|[ICMSDifRecipientTaxAmount](#ICMSDifRecipientTaxAmount)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|
|[DataAreaId](#DataAreaId)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|
|[Relationship_FiscalDocumentRelationshipId](#Relationship_FiscalDocumentRelationshipId)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|
|[Relationship_FiscalDocumentLineRelationshipId](#Relationship_FiscalDocumentLineRelationshipId)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|
|[Relationship_FiscalDocumentTaxTransRelationshipId](#Relationship_FiscalDocumentTaxTransRelationshipId)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="FiscalDocumentTaxTransOutgoingICMSDif_BR.md" target="_blank">Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FiscalDocumentTaxTransOutgoingICMSDif_BR/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocument name="FiscalDocument">FiscalDocument</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocument attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocumentDate name="FiscalDocumentDate">FiscalDocumentDate</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>date</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentDate attribute are listed below.</summary>

**is.dataFormat.date**  
**means.measurement.date**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.date**  
</details>

### <a href=#FiscalDocumentLine name="FiscalDocumentLine">FiscalDocumentLine</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#FiscalDocumentTaxTrans name="FiscalDocumentTaxTrans">FiscalDocumentTaxTrans</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FiscalDocumentTaxTrans attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ICMSDifIssuerTaxAmount name="ICMSDifIssuerTaxAmount">ICMSDifIssuerTaxAmount</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSDifIssuerTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#ICMSDifRecipientTaxAmount name="ICMSDifRecipientTaxAmount">ICMSDifRecipientTaxAmount</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ICMSDifRecipientTaxAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

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

### <a href=#Relationship_FiscalDocumentRelationshipId name="Relationship_FiscalDocumentRelationshipId">Relationship_FiscalDocumentRelationshipId</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FiscalDocument_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocument_BR.cdm.json/FiscalDocument_BR</a></td><td><a href="../Transaction/FiscalDocument_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentLineRelationshipId name="Relationship_FiscalDocumentLineRelationshipId">Relationship_FiscalDocumentLineRelationshipId</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FiscalDocumentLine_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocumentLine_BR.cdm.json/FiscalDocumentLine_BR</a></td><td><a href="../Transaction/FiscalDocumentLine_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_FiscalDocumentTaxTransRelationshipId name="Relationship_FiscalDocumentTaxTransRelationshipId">Relationship_FiscalDocumentTaxTransRelationshipId</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_FiscalDocumentTaxTransRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Transaction/FiscalDocumentTaxTrans_BR.md" target="_blank">/core/operationsCommon/Tables/Finance/FiscalBooksBrazil/Transaction/FiscalDocumentTaxTrans_BR.cdm.json/FiscalDocumentTaxTrans_BR</a></td><td><a href="../Transaction/FiscalDocumentTaxTrans_BR.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Miscellaneous/FiscalDocumentTaxTransOutgoingICMSDif_BR (this entity)  

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
