---
title: CredManBlockExclusionRuleEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Credit management rules setup in AccountsReceivable(CredManBlockExclusionRuleEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CredManBlockExclusionRuleEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit management rules setup</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CreditLimitThreshold](#CreditLimitThreshold)||<a href="CredManBlockExclusionRuleEntity.md" target="_blank">AccountsReceivable/CredManBlockExclusionRuleEntity</a>|
|[CustRelation](#CustRelation)||<a href="CredManBlockExclusionRuleEntity.md" target="_blank">AccountsReceivable/CredManBlockExclusionRuleEntity</a>|
|[GraceValue](#GraceValue)||<a href="CredManBlockExclusionRuleEntity.md" target="_blank">AccountsReceivable/CredManBlockExclusionRuleEntity</a>|
|[RiskGroupId](#RiskGroupId)||<a href="CredManBlockExclusionRuleEntity.md" target="_blank">AccountsReceivable/CredManBlockExclusionRuleEntity</a>|
|[TableGroupAll](#TableGroupAll)||<a href="CredManBlockExclusionRuleEntity.md" target="_blank">AccountsReceivable/CredManBlockExclusionRuleEntity</a>|
|[ValueType](#ValueType)||<a href="CredManBlockExclusionRuleEntity.md" target="_blank">AccountsReceivable/CredManBlockExclusionRuleEntity</a>|
|[RuleType](#RuleType)||<a href="CredManBlockExclusionRuleEntity.md" target="_blank">AccountsReceivable/CredManBlockExclusionRuleEntity</a>|
|[ReleaseSalesOrder](#ReleaseSalesOrder)||<a href="CredManBlockExclusionRuleEntity.md" target="_blank">AccountsReceivable/CredManBlockExclusionRuleEntity</a>|
|[RuleId](#RuleId)||<a href="CredManBlockExclusionRuleEntity.md" target="_blank">AccountsReceivable/CredManBlockExclusionRuleEntity</a>|
|[BackingTable_CredManBlockExclusionRuleRelationshipId](#BackingTable_CredManBlockExclusionRuleRelationshipId)||<a href="CredManBlockExclusionRuleEntity.md" target="_blank">AccountsReceivable/CredManBlockExclusionRuleEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CredManBlockExclusionRuleEntity.md" target="_blank">AccountsReceivable/CredManBlockExclusionRuleEntity</a>|

### <a href=#CreditLimitThreshold name="CreditLimitThreshold">CreditLimitThreshold</a>

First included in: AccountsReceivable/CredManBlockExclusionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CreditLimitThreshold attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustRelation name="CustRelation">CustRelation</a>

First included in: AccountsReceivable/CredManBlockExclusionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustRelation attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GraceValue name="GraceValue">GraceValue</a>

First included in: AccountsReceivable/CredManBlockExclusionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GraceValue attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RiskGroupId name="RiskGroupId">RiskGroupId</a>

First included in: AccountsReceivable/CredManBlockExclusionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RiskGroupId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TableGroupAll name="TableGroupAll">TableGroupAll</a>

First included in: AccountsReceivable/CredManBlockExclusionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TableGroupAll attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValueType name="ValueType">ValueType</a>

First included in: AccountsReceivable/CredManBlockExclusionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValueType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RuleType name="RuleType">RuleType</a>

First included in: AccountsReceivable/CredManBlockExclusionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RuleType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ReleaseSalesOrder name="ReleaseSalesOrder">ReleaseSalesOrder</a>

First included in: AccountsReceivable/CredManBlockExclusionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReleaseSalesOrder attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RuleId name="RuleId">RuleId</a>

First included in: AccountsReceivable/CredManBlockExclusionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RuleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CredManBlockExclusionRuleRelationshipId name="BackingTable_CredManBlockExclusionRuleRelationshipId">BackingTable_CredManBlockExclusionRuleRelationshipId</a>

First included in: AccountsReceivable/CredManBlockExclusionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CredManBlockExclusionRuleRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/Miscellaneous/CredManBlockExclusionRule.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/Miscellaneous/CredManBlockExclusionRule.cdm.json/CredManBlockExclusionRule</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/Miscellaneous/CredManBlockExclusionRule.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CredManBlockExclusionRuleEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
