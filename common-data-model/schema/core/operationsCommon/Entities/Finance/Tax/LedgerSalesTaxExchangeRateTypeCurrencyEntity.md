---
title: LedgerSalesTaxExchangeRateTypeCurrencyEntity in Tax - Common Data Model | Microsoft Docs
description: undefined
author: llawwaii

ms.reviewer: deonhe
ms.topic: article
ms.date: 8/7/2020
ms.author: weiluo
---

# Currency exchange rate types for sales tax in Tax(LedgerSalesTaxExchangeRateTypeCurrencyEntity)

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Currency exchange rate types for sales tax</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Currency](#Currency)||<a href="LedgerSalesTaxExchangeRateTypeCurrencyEntity.md" target="_blank">Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity</a>|
|[ExchangeRateTypeRecId](#ExchangeRateTypeRecId)||<a href="LedgerSalesTaxExchangeRateTypeCurrencyEntity.md" target="_blank">Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity</a>|
|[LedgerRecId](#LedgerRecId)||<a href="LedgerSalesTaxExchangeRateTypeCurrencyEntity.md" target="_blank">Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity</a>|
|[TransactionType](#TransactionType)||<a href="LedgerSalesTaxExchangeRateTypeCurrencyEntity.md" target="_blank">Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity</a>|
|[Ledger](#Ledger)||<a href="LedgerSalesTaxExchangeRateTypeCurrencyEntity.md" target="_blank">Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity</a>|
|[ExchangeRateType](#ExchangeRateType)||<a href="LedgerSalesTaxExchangeRateTypeCurrencyEntity.md" target="_blank">Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity</a>|
|[BackingTable_LedgerSalesTaxExchangeRateTypeCurrencyRelationshipId](#BackingTable_LedgerSalesTaxExchangeRateTypeCurrencyRelationshipId)||<a href="LedgerSalesTaxExchangeRateTypeCurrencyEntity.md" target="_blank">Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="LedgerSalesTaxExchangeRateTypeCurrencyEntity.md" target="_blank">Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity</a>|

### <a href=#Currency name="Currency">Currency</a>

First included in: Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Currency attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateTypeRecId name="ExchangeRateTypeRecId">ExchangeRateTypeRecId</a>

First included in: Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateTypeRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LedgerRecId name="LedgerRecId">LedgerRecId</a>

First included in: Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LedgerRecId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#TransactionType name="TransactionType">TransactionType</a>

First included in: Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the TransactionType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Ledger name="Ledger">Ledger</a>

First included in: Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Ledger attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ExchangeRateType name="ExchangeRateType">ExchangeRateType</a>

First included in: Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ExchangeRateType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#BackingTable_LedgerSalesTaxExchangeRateTypeCurrencyRelationshipId name="BackingTable_LedgerSalesTaxExchangeRateTypeCurrencyRelationshipId">BackingTable_LedgerSalesTaxExchangeRateTypeCurrencyRelationshipId</a>

First included in: Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the BackingTable_LedgerSalesTaxExchangeRateTypeCurrencyRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Miscellaneous/LedgerSalesTaxExchangeRateTypeCurrency.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Miscellaneous/LedgerSalesTaxExchangeRateTypeCurrency.cdm.json/LedgerSalesTaxExchangeRateTypeCurrency</a></td><td><a href="../../../Tables/Finance/Ledger/Miscellaneous/LedgerSalesTaxExchangeRateTypeCurrency.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: Tax/LedgerSalesTaxExchangeRateTypeCurrencyEntity (this entity)  

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
