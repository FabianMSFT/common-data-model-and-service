---
title: smmOpportunityMaintenancePolicyEntity in SalesAndMarketing - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Opportunity maintenance policies in SalesAndMarketing(smmOpportunityMaintenancePolicyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/SupplyChain/SalesAndMarketing/smmOpportunityMaintenancePolicyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Opportunity maintenance policies</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[SalesQuotationOpportunityCreationRule](#SalesQuotationOpportunityCreationRule)||<a href="smmOpportunityMaintenancePolicyEntity.md" target="_blank">SalesAndMarketing/smmOpportunityMaintenancePolicyEntity</a>|
|[SalesQuotationOpportunityModificationRule](#SalesQuotationOpportunityModificationRule)||<a href="smmOpportunityMaintenancePolicyEntity.md" target="_blank">SalesAndMarketing/smmOpportunityMaintenancePolicyEntity</a>|
|[ProjectQuotationOpportunityCreationRule](#ProjectQuotationOpportunityCreationRule)||<a href="smmOpportunityMaintenancePolicyEntity.md" target="_blank">SalesAndMarketing/smmOpportunityMaintenancePolicyEntity</a>|
|[ProjectQuotationOpportunityModificationRule](#ProjectQuotationOpportunityModificationRule)||<a href="smmOpportunityMaintenancePolicyEntity.md" target="_blank">SalesAndMarketing/smmOpportunityMaintenancePolicyEntity</a>|
|[BackingTable_smmParametersTableRelationshipId](#BackingTable_smmParametersTableRelationshipId)||<a href="smmOpportunityMaintenancePolicyEntity.md" target="_blank">SalesAndMarketing/smmOpportunityMaintenancePolicyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="smmOpportunityMaintenancePolicyEntity.md" target="_blank">SalesAndMarketing/smmOpportunityMaintenancePolicyEntity</a>|

### <a href=#SalesQuotationOpportunityCreationRule name="SalesQuotationOpportunityCreationRule">SalesQuotationOpportunityCreationRule</a>

First included in: SalesAndMarketing/smmOpportunityMaintenancePolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationOpportunityCreationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesQuotationOpportunityModificationRule name="SalesQuotationOpportunityModificationRule">SalesQuotationOpportunityModificationRule</a>

First included in: SalesAndMarketing/smmOpportunityMaintenancePolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesQuotationOpportunityModificationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectQuotationOpportunityCreationRule name="ProjectQuotationOpportunityCreationRule">ProjectQuotationOpportunityCreationRule</a>

First included in: SalesAndMarketing/smmOpportunityMaintenancePolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectQuotationOpportunityCreationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ProjectQuotationOpportunityModificationRule name="ProjectQuotationOpportunityModificationRule">ProjectQuotationOpportunityModificationRule</a>

First included in: SalesAndMarketing/smmOpportunityMaintenancePolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProjectQuotationOpportunityModificationRule attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_smmParametersTableRelationshipId name="BackingTable_smmParametersTableRelationshipId">BackingTable_smmParametersTableRelationshipId</a>

First included in: SalesAndMarketing/smmOpportunityMaintenancePolicyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_smmParametersTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/smmParametersTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Parameter/smmParametersTable.cdm.json/smmParametersTable</a></td><td><a href="../../../Tables/SupplyChain/SalesAndMarketing/Parameter/smmParametersTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: SalesAndMarketing/smmOpportunityMaintenancePolicyEntity (this entity)  

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
