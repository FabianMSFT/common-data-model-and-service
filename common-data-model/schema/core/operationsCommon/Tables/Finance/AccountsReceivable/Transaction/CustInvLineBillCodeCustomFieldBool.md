---
title: CustInvLineBillCodeCustomFieldBool in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Boolean in Transaction(CustInvLineBillCodeCustomFieldBool)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/AccountsReceivable/Transaction/CustInvLineBillCodeCustomFieldBool.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustInvLineBillCodeCustomFieldBool/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Base</td></tr><tr><td>en</td><td>Boolean</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[CustBillingCodeCustomField](#CustBillingCodeCustomField)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[CustCustomFieldSourceType](#CustCustomFieldSourceType)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[CustInvoiceLine](#CustInvoiceLine)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[CustInvoiceLineLineNum](#CustInvoiceLineLineNum)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[CustInvoiceLineParent](#CustInvoiceLineParent)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[CustInvoiceStandardLineTemplate](#CustInvoiceStandardLineTemplate)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[CustRecurrenceInvoice](#CustRecurrenceInvoice)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[DataAreaId](#DataAreaId)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[Relationship_CustBillingCodeCustomFieldRelationshipId](#Relationship_CustBillingCodeCustomFieldRelationshipId)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[Relationship_CustInvoiceLineRelationshipId](#Relationship_CustInvoiceLineRelationshipId)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[Relationship_CustInvoiceStandardLineTemplateRelationshipId](#Relationship_CustInvoiceStandardLineTemplateRelationshipId)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[Relationship_CustInvoiceTableRelationshipId](#Relationship_CustInvoiceTableRelationshipId)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[Relationship_CustRecurrenceInvoiceRelationshipId](#Relationship_CustRecurrenceInvoiceRelationshipId)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|
|[BoolValue](#BoolValue)||<a href="CustInvLineBillCodeCustomFieldBool.md" target="_blank">Transaction/CustInvLineBillCodeCustomFieldBool</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[CustInvLineBillCodeCustomFieldBool/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustBillingCodeCustomField name="CustBillingCodeCustomField">CustBillingCodeCustomField</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustBillingCodeCustomField attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustCustomFieldSourceType name="CustCustomFieldSourceType">CustCustomFieldSourceType</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustCustomFieldSourceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#CustInvoiceLine name="CustInvoiceLine">CustInvoiceLine</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceLine attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustInvoiceLineLineNum name="CustInvoiceLineLineNum">CustInvoiceLineLineNum</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceLineLineNum attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#CustInvoiceLineParent name="CustInvoiceLineParent">CustInvoiceLineParent</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceLineParent attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustInvoiceStandardLineTemplate name="CustInvoiceStandardLineTemplate">CustInvoiceStandardLineTemplate</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustInvoiceStandardLineTemplate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#CustRecurrenceInvoice name="CustRecurrenceInvoice">CustRecurrenceInvoice</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustRecurrenceInvoice attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

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

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

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

### <a href=#Relationship_CustBillingCodeCustomFieldRelationshipId name="Relationship_CustBillingCodeCustomFieldRelationshipId">Relationship_CustBillingCodeCustomFieldRelationshipId</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustBillingCodeCustomFieldRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Miscellaneous/CustBillingCodeCustomField.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Miscellaneous/CustBillingCodeCustomField.cdm.json/CustBillingCodeCustomField</a></td><td><a href="../Miscellaneous/CustBillingCodeCustomField.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustInvoiceLineRelationshipId name="Relationship_CustInvoiceLineRelationshipId">Relationship_CustInvoiceLineRelationshipId</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceLineRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/CustInvoiceLine.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/WorksheetLine/CustInvoiceLine.cdm.json/CustInvoiceLine</a></td><td><a href="../WorksheetLine/CustInvoiceLine.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustInvoiceStandardLineTemplateRelationshipId name="Relationship_CustInvoiceStandardLineTemplateRelationshipId">Relationship_CustInvoiceStandardLineTemplateRelationshipId</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceStandardLineTemplateRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/CustInvoiceStandardLineTemplate.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/WorksheetLine/CustInvoiceStandardLineTemplate.cdm.json/CustInvoiceStandardLineTemplate</a></td><td><a href="../WorksheetLine/CustInvoiceStandardLineTemplate.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustInvoiceTableRelationshipId name="Relationship_CustInvoiceTableRelationshipId">Relationship_CustInvoiceTableRelationshipId</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustInvoiceTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/CustInvoiceTable.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/WorksheetHeader/CustInvoiceTable.cdm.json/CustInvoiceTable</a></td><td><a href="../WorksheetHeader/CustInvoiceTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustRecurrenceInvoiceRelationshipId name="Relationship_CustRecurrenceInvoiceRelationshipId">Relationship_CustRecurrenceInvoiceRelationshipId</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustRecurrenceInvoiceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Worksheet/CustRecurrenceInvoice.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Worksheet/CustRecurrenceInvoice.cdm.json/CustRecurrenceInvoice</a></td><td><a href="../Worksheet/CustRecurrenceInvoice.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

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

### <a href=#BoolValue name="BoolValue">BoolValue</a>

First included in: Transaction/CustInvLineBillCodeCustomFieldBool (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BoolValue attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>
