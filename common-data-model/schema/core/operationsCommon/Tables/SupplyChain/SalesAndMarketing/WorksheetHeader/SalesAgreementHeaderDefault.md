---
title: SalesAgreementHeaderDefault in WorksheetHeader - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Release sales order defaulting policy in WorksheetHeader(SalesAgreementHeaderDefault)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesAgreementHeaderDefault.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SalesAgreementHeaderDefault/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Release sales order defaulting policy</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[Campaign](#Campaign)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CampaignDataAreaId](#CampaignDataAreaId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CommissionCustomerGroup](#CommissionCustomerGroup)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CommissionCustomerGroupDataAreaId](#CommissionCustomerGroupDataAreaId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CommissionSalesGroup](#CommissionSalesGroup)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CommissionSalesGroupDataAreaId](#CommissionSalesGroupDataAreaId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CustomerInvoiceAccount](#CustomerInvoiceAccount)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CustomerInvoiceAccountDataAreaId](#CustomerInvoiceAccountDataAreaId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CustomerMethodOfPayment](#CustomerMethodOfPayment)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CustomerMethodOfPaymentDataAreaId](#CustomerMethodOfPaymentDataAreaId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CustomerPaymentSpec](#CustomerPaymentSpec)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CustomerPaymentSpecDataAreaId](#CustomerPaymentSpecDataAreaId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[CustomerRequisitionNumber](#CustomerRequisitionNumber)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[EntryCertificateRequired_W](#EntryCertificateRequired_W)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[FixedExchangeRate](#FixedExchangeRate)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[IssueOwnEntryCertificate_W](#IssueOwnEntryCertificate_W)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[PdsExcludeFromRebate](#PdsExcludeFromRebate)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[SalesAgreementHeader](#SalesAgreementHeader)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[SalesPool](#SalesPool)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[SalesPoolDataAreaId](#SalesPoolDataAreaId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[SalesUnit](#SalesUnit)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[SalesUnitDataAreaId](#SalesUnitDataAreaId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[WorkerSalesResponsible](#WorkerSalesResponsible)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[ReportingCurrencyFixedExchRate](#ReportingCurrencyFixedExchRate)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[Relationship_CampaignRelationshipId](#Relationship_CampaignRelationshipId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[Relationship_CommissionCustomerGroupRelationshipId](#Relationship_CommissionCustomerGroupRelationshipId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[Relationship_CommissionSalesGroupRelationshipId](#Relationship_CommissionSalesGroupRelationshipId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[Relationship_CustPaymModeSpecRelationshipId](#Relationship_CustPaymModeSpecRelationshipId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[Relationship_CustPaymModeTableRelationshipId](#Relationship_CustPaymModeTableRelationshipId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[Relationship_DefaultCustomerInvoiceAccountRelationshipId](#Relationship_DefaultCustomerInvoiceAccountRelationshipId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[Relationship_SalesAgreementHeaderRelationshipId](#Relationship_SalesAgreementHeaderRelationshipId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[Relationship_SalesPoolRelationshipId](#Relationship_SalesPoolRelationshipId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|
|[Relationship_SalesUnitRelationshipId](#Relationship_SalesUnitRelationshipId)||<a href="SalesAgreementHeaderDefault.md" target="_blank">WorksheetHeader/SalesAgreementHeaderDefault</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[SalesAgreementHeaderDefault/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#Campaign name="Campaign">Campaign</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Campaign attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CampaignDataAreaId name="CampaignDataAreaId">CampaignDataAreaId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CampaignDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionCustomerGroup name="CommissionCustomerGroup">CommissionCustomerGroup</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionCustomerGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionCustomerGroupDataAreaId name="CommissionCustomerGroupDataAreaId">CommissionCustomerGroupDataAreaId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionCustomerGroupDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionSalesGroup name="CommissionSalesGroup">CommissionSalesGroup</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionSalesGroup attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CommissionSalesGroupDataAreaId name="CommissionSalesGroupDataAreaId">CommissionSalesGroupDataAreaId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CommissionSalesGroupDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerInvoiceAccount name="CustomerInvoiceAccount">CustomerInvoiceAccount</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerInvoiceAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerInvoiceAccountDataAreaId name="CustomerInvoiceAccountDataAreaId">CustomerInvoiceAccountDataAreaId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerInvoiceAccountDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerMethodOfPayment name="CustomerMethodOfPayment">CustomerMethodOfPayment</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerMethodOfPayment attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerMethodOfPaymentDataAreaId name="CustomerMethodOfPaymentDataAreaId">CustomerMethodOfPaymentDataAreaId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerMethodOfPaymentDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentSpec name="CustomerPaymentSpec">CustomerPaymentSpec</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentSpec attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentSpecDataAreaId name="CustomerPaymentSpecDataAreaId">CustomerPaymentSpecDataAreaId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentSpecDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerRequisitionNumber name="CustomerRequisitionNumber">CustomerRequisitionNumber</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerRequisitionNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EntryCertificateRequired_W name="EntryCertificateRequired_W">EntryCertificateRequired_W</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EntryCertificateRequired_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#FixedExchangeRate name="FixedExchangeRate">FixedExchangeRate</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FixedExchangeRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#IssueOwnEntryCertificate_W name="IssueOwnEntryCertificate_W">IssueOwnEntryCertificate_W</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IssueOwnEntryCertificate_W attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#PdsExcludeFromRebate name="PdsExcludeFromRebate">PdsExcludeFromRebate</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsExcludeFromRebate attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#SalesAgreementHeader name="SalesAgreementHeader">SalesAgreementHeader</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sales agreement</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesAgreementHeader attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.readOnly**  
**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sales agreement</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#SalesPool name="SalesPool">SalesPool</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPool attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesPoolDataAreaId name="SalesPoolDataAreaId">SalesPoolDataAreaId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesPoolDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnit name="SalesUnit">SalesUnit</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnit attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#SalesUnitDataAreaId name="SalesUnitDataAreaId">SalesUnitDataAreaId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SalesUnitDataAreaId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#WorkerSalesResponsible name="WorkerSalesResponsible">WorkerSalesResponsible</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the WorkerSalesResponsible attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#ReportingCurrencyFixedExchRate name="ReportingCurrencyFixedExchRate">ReportingCurrencyFixedExchRate</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ReportingCurrencyFixedExchRate attribute are listed below.</summary>

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

</details>

### <a href=#Relationship_CampaignRelationshipId name="Relationship_CampaignRelationshipId">Relationship_CampaignRelationshipId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CampaignRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Main/smmCampaignTable.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Main/smmCampaignTable.cdm.json/smmCampaignTable</a></td><td><a href="../Main/smmCampaignTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CommissionCustomerGroupRelationshipId name="Relationship_CommissionCustomerGroupRelationshipId">Relationship_CommissionCustomerGroupRelationshipId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CommissionCustomerGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CommissionCustomerGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/CommissionCustomerGroup.cdm.json/CommissionCustomerGroup</a></td><td><a href="../Group/CommissionCustomerGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CommissionSalesGroupRelationshipId name="Relationship_CommissionSalesGroupRelationshipId">Relationship_CommissionSalesGroupRelationshipId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CommissionSalesGroupRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/CommissionSalesGroup.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/CommissionSalesGroup.cdm.json/CommissionSalesGroup</a></td><td><a href="../Group/CommissionSalesGroup.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustPaymModeSpecRelationshipId name="Relationship_CustPaymModeSpecRelationshipId">Relationship_CustPaymModeSpecRelationshipId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustPaymModeSpecRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/CustPaymModeSpec.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/CustPaymModeSpec.cdm.json/CustPaymModeSpec</a></td><td><a href="../../../Finance/Bank/Group/CustPaymModeSpec.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_CustPaymModeTableRelationshipId name="Relationship_CustPaymModeTableRelationshipId">Relationship_CustPaymModeTableRelationshipId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_CustPaymModeTableRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Finance/Bank/Group/CustPaymModeTable.md" target="_blank">/core/operationsCommon/Tables/Finance/Bank/Group/CustPaymModeTable.cdm.json/CustPaymModeTable</a></td><td><a href="../../../Finance/Bank/Group/CustPaymModeTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_DefaultCustomerInvoiceAccountRelationshipId name="Relationship_DefaultCustomerInvoiceAccountRelationshipId">Relationship_DefaultCustomerInvoiceAccountRelationshipId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_DefaultCustomerInvoiceAccountRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Common/Customer/Main/CustTable.md" target="_blank">/core/operationsCommon/Tables/Common/Customer/Main/CustTable.cdm.json/CustTable</a></td><td><a href="../../../Common/Customer/Main/CustTable.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesAgreementHeaderRelationshipId name="Relationship_SalesAgreementHeaderRelationshipId">Relationship_SalesAgreementHeaderRelationshipId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesAgreementHeaderRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="SalesAgreementHeader.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/WorksheetHeader/SalesAgreementHeader.cdm.json/SalesAgreementHeader</a></td><td><a href="SalesAgreementHeader.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesPoolRelationshipId name="Relationship_SalesPoolRelationshipId">Relationship_SalesPoolRelationshipId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesPoolRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/SalesPool.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/SalesPool.cdm.json/SalesPool</a></td><td><a href="../Group/SalesPool.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_SalesUnitRelationshipId name="Relationship_SalesUnitRelationshipId">Relationship_SalesUnitRelationshipId</a>

First included in: WorksheetHeader/SalesAgreementHeaderDefault (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_SalesUnitRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../Group/smmSalesUnit.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/SalesAndMarketing/Group/smmSalesUnit.cdm.json/smmSalesUnit</a></td><td><a href="../Group/smmSalesUnit.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>
