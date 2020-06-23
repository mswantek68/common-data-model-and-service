---
title: EcoResDistinctProductVariant - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Product variants

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResDistinctProductVariant.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResDistinctProductVariant/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Products</td></tr><tr><td>en</td><td>Product variants</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[RecId](#RecId)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[DisplayProductNumber](#DisplayProductNumber)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[InstanceRelationType](#InstanceRelationType)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[PdsCWProduct](#PdsCWProduct)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[ProductType](#ProductType)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[SearchName](#SearchName)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[ServiceType](#ServiceType)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[EngChgProductOwnerId](#EngChgProductOwnerId)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[EngChgProductType](#EngChgProductType)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[EngChgDisplayProductName](#EngChgDisplayProductName)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[EngChgNumOfVersions](#EngChgNumOfVersions)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[ProductMaster](#ProductMaster)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[RetaiTotalWeight](#RetaiTotalWeight)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|
|[Relationship_EcoResProductMasterRelationshipId](#Relationship_EcoResProductMasterRelationshipId)||<a href="EcoResDistinctProductVariant.md" target="_blank">Main/EcoResDistinctProductVariant</a>|

### <a href=#RecId name="RecId">RecId</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RecId attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[EcoResDistinctProductVariant/(resolvedAttributes)/RecId](#RecId)</td><td>attribute</td><td></td></tr></table>

**is.readOnly**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#DisplayProductNumber name="DisplayProductNumber">DisplayProductNumber</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr></table>

#### Traits

<details>
<summary>List of traits for the DisplayProductNumber attribute are listed below.</summary>

</details>

### <a href=#InstanceRelationType name="InstanceRelationType">InstanceRelationType</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the InstanceRelationType attribute are listed below.</summary>

**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#PdsCWProduct name="PdsCWProduct">PdsCWProduct</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PdsCWProduct attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProductType name="ProductType">ProductType</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.integer**  
</details>

### <a href=#SearchName name="SearchName">SearchName</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the SearchName attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#ServiceType name="ServiceType">ServiceType</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ServiceType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#EngChgProductOwnerId name="EngChgProductOwnerId">EngChgProductOwnerId</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EngChgProductOwnerId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#EngChgProductType name="EngChgProductType">EngChgProductType</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EngChgProductType attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#EngChgDisplayProductName name="EngChgDisplayProductName">EngChgDisplayProductName</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>unknown</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EngChgDisplayProductName attribute are listed below.</summary>

**is.nullable**  
The attribute value may be set to NULL.  

</details>

### <a href=#EngChgNumOfVersions name="EngChgNumOfVersions">EngChgNumOfVersions</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the EngChgNumOfVersions attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.integer**  
</details>

### <a href=#ProductMaster name="ProductMaster">ProductMaster</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>int64</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ProductMaster attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.dataFormat.big**  
**is.dataFormat.integer**  
**is.dataFormat.big**  
</details>

### <a href=#RetaiTotalWeight name="RetaiTotalWeight">RetaiTotalWeight</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Total weight</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetaiTotalWeight attribute are listed below.</summary>

**is.dataFormat.integer**  
**is.readOnly**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Total weight</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.dataFormat.integer**  
</details>

### <a href=#Relationship_EcoResProductMasterRelationshipId name="Relationship_EcoResProductMasterRelationshipId">Relationship_EcoResProductMasterRelationshipId</a>

First included in: Main/EcoResDistinctProductVariant (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_EcoResProductMasterRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="EcoResProductMaster.md" target="_blank">/core/operationsCommon/Tables/SupplyChain/ProductInformationManagement/Main/EcoResProductMaster.cdm.json/EcoResProductMaster</a></td><td><a href="EcoResProductMaster.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>