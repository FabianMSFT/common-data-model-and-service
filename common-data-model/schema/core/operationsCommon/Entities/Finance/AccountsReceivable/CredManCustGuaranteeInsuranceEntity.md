---
title: CredManCustGuaranteeInsuranceEntity in AccountsReceivable - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Insurance and guarantees in AccountsReceivable(CredManCustGuaranteeInsuranceEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/CredManCustGuaranteeInsuranceEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Insurance and guarantees</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[CustAccount](#CustAccount)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[GuaranteeInsurance](#GuaranteeInsurance)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[GuaranteeInsuranceType](#GuaranteeInsuranceType)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[GuarantorInsurer](#GuarantorInsurer)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[InsuranceCoverageType](#InsuranceCoverageType)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[GuaranteeNumber](#GuaranteeNumber)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[ValidFrom](#ValidFrom)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[ValidTo](#ValidTo)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[Value](#Value)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[IncreaseCreditLimitPercent](#IncreaseCreditLimitPercent)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[IncludeInExposure](#IncludeInExposure)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[BackingTable_CredManCustGuaranteeInsuranceRelationshipId](#BackingTable_CredManCustGuaranteeInsuranceRelationshipId)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="CredManCustGuaranteeInsuranceEntity.md" target="_blank">AccountsReceivable/CredManCustGuaranteeInsuranceEntity</a>|

### <a href=#CustAccount name="CustAccount">CustAccount</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GuaranteeInsurance name="GuaranteeInsurance">GuaranteeInsurance</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuaranteeInsurance attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GuaranteeInsuranceType name="GuaranteeInsuranceType">GuaranteeInsuranceType</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuaranteeInsuranceType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GuarantorInsurer name="GuarantorInsurer">GuarantorInsurer</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuarantorInsurer attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#InsuranceCoverageType name="InsuranceCoverageType">InsuranceCoverageType</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InsuranceCoverageType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#GuaranteeNumber name="GuaranteeNumber">GuaranteeNumber</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the GuaranteeNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidFrom name="ValidFrom">ValidFrom</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidFrom attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ValidTo name="ValidTo">ValidTo</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ValidTo attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Value name="Value">Value</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Value attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncreaseCreditLimitPercent name="IncreaseCreditLimitPercent">IncreaseCreditLimitPercent</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncreaseCreditLimitPercent attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IncludeInExposure name="IncludeInExposure">IncludeInExposure</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IncludeInExposure attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_CredManCustGuaranteeInsuranceRelationshipId name="BackingTable_CredManCustGuaranteeInsuranceRelationshipId">BackingTable_CredManCustGuaranteeInsuranceRelationshipId</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_CredManCustGuaranteeInsuranceRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/AccountsReceivable/WorksheetLine/CredManCustGuaranteeInsurance.md" target="_blank">/core/operationsCommon/Tables/Finance/AccountsReceivable/WorksheetLine/CredManCustGuaranteeInsurance.cdm.json/CredManCustGuaranteeInsurance</a></td><td><a href="../../../Tables/Finance/AccountsReceivable/WorksheetLine/CredManCustGuaranteeInsurance.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/CredManCustGuaranteeInsuranceEntity (this entity)  

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
