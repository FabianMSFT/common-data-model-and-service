---
title: LedgerIndirectTaxSection1DeclTrans_RU in Transaction - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Indirect tax declaration transactions (indirect VAT) in Transaction(LedgerIndirectTaxSection1DeclTrans_RU)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/Finance/Ledger/Transaction/LedgerIndirectTaxSection1DeclTrans_RU.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerIndirectTaxSection1DeclTrans_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indirect tax declaration transactions (indirect VAT)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|
|[BranchId](#BranchId)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|
|[BudgetReceiptClassCode](#BudgetReceiptClassCode)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|
|[JournalId](#JournalId)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|
|[LineNum](#LineNum)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|
|[VATAmount](#VATAmount)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|
|[DataAreaId](#DataAreaId)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|
|[Relationship_Branches_RURelationshipId](#Relationship_Branches_RURelationshipId)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|
|[Relationship_LedgerIndirectTaxDeclJournalTable_RURelationshipId](#Relationship_LedgerIndirectTaxDeclJournalTable_RURelationshipId)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|
|[Relationship_LedgerIndirectTaxDeclJournalTrans_RURelationshipId](#Relationship_LedgerIndirectTaxDeclJournalTrans_RURelationshipId)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|
|[Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId](#Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|
|[Relationship_CompanyRelationshipId](#Relationship_CompanyRelationshipId)||<a href="LedgerIndirectTaxSection1DeclTrans_RU.md" target="_blank">Transaction/LedgerIndirectTaxSection1DeclTrans_RU</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[LedgerIndirectTaxSection1DeclTrans_RU/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#BranchId name="BranchId">BranchId</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BranchId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BudgetReceiptClassCode name="BudgetReceiptClassCode">BudgetReceiptClassCode</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BudgetReceiptClassCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#JournalId name="JournalId">JournalId</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the JournalId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNum name="LineNum">LineNum</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNum attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#VATAmount name="VATAmount">VATAmount</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the VATAmount attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#DataAreaId name="DataAreaId">DataAreaId</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

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

### <a href=#Relationship_Branches_RURelationshipId name="Relationship_Branches_RURelationshipId">Relationship_Branches_RURelationshipId</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_Branches_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../APARShared/Group/Branches_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/APARShared/Group/Branches_RU.cdm.json/Branches_RU</a></td><td><a href="../../APARShared/Group/Branches_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerIndirectTaxDeclJournalTable_RURelationshipId name="Relationship_LedgerIndirectTaxDeclJournalTable_RURelationshipId">Relationship_LedgerIndirectTaxDeclJournalTable_RURelationshipId</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerIndirectTaxDeclJournalTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetHeader/LedgerIndirectTaxDeclJournalTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/WorksheetHeader/LedgerIndirectTaxDeclJournalTable_RU.cdm.json/LedgerIndirectTaxDeclJournalTable_RU</a></td><td><a href="../WorksheetHeader/LedgerIndirectTaxDeclJournalTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_LedgerIndirectTaxDeclJournalTrans_RURelationshipId name="Relationship_LedgerIndirectTaxDeclJournalTrans_RURelationshipId">Relationship_LedgerIndirectTaxDeclJournalTrans_RURelationshipId</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_LedgerIndirectTaxDeclJournalTrans_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../WorksheetLine/LedgerIndirectTaxDeclJournalTrans_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/WorksheetLine/LedgerIndirectTaxDeclJournalTrans_RU.cdm.json/LedgerIndirectTaxDeclJournalTrans_RU</a></td><td><a href="../WorksheetLine/LedgerIndirectTaxDeclJournalTrans_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId name="Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId">Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PaymentOrderBudgetReceiptClassTable_RURelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.cdm.json/PaymentOrderBudgetReceiptClassTable_RU</a></td><td><a href="../../Bank/Main/PaymentOrderBudgetReceiptClassTable_RU.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CompanyRelationshipId name="Relationship_CompanyRelationshipId">Relationship_CompanyRelationshipId</a>

First included in: Transaction/LedgerIndirectTaxSection1DeclTrans_RU (this entity)  

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
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
