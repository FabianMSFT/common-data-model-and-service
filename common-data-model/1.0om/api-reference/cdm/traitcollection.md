---
title: Trait Collection | Microsoft Docs
description: API reference for CdmTraitCollection.
author: miroslavplese

ms.reviewer: deonhe 
ms.topic: article
ms.date: 10/18/2019
ms.author: miplese
---

# Trait Collection

A trait collection extends [Collection](collection.md) and adds additional behaviors specific to trait collections.

```csharp
public class CdmTraitCollection extends CdmCollection<CdmTraitReferenceBase>
```

## Constructors
|Name|Description|
|---|---|
|**CdmTraitCollection(CdmCorpusContext, [CdmObject](cdmobject.md))**<br/>*ctx*: The corpus context.<br/>*owner*: The object that contains this collection.|Initializes a new instance of the [CdmTraitCollection](traitcollection.md) class.|

## Methods
|Name|Description|Return Type|SDK|
|---|---|---|---|
|**Add([CdmTraitReferenceBase](traitreferencebase.md))**<br/>*trait*: The trait to add to the collection.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Adds the specified trait to the collection. Returns the trait that was added to the collection.|[CdmTraitReferenceBase](traitreferencebase.md)|1.0|
|**Add([CdmTraitDefinition](trait.md), bool)**<br/>*traitDefinition*: The trait definition to use to create the trait reference.<br/>*simpleRef [optional]*: A boolean that denotes whether the trait reference is simple named or not. The default value is false.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates a trait reference based on the specified trait definition and adds it to the collection. Returns the trait reference that was added to the collection.|[CdmTraitReferenceBase](traitreferencebase.md)|1.0|
|**Add([CdmTraitGroupDefinition](traitgroup.md), bool)**<br/>*traitGroupDefinition*: The trait group definition to use to create the trait group reference.<br/>*simpleRef [optional]*: A boolean that denotes whether the trait group reference is simple named or not. The default value is false.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates a trait group reference based on the specified trait group definition and adds it to the collection. Returns the trait group reference that was added to the collection.|[CdmTraitReferenceBase](traitreferencebase.md)|1.2|
|**Add(string, bool)**<br/>*name*: The name of the trait to add to the collection.<br/>*simpleRef [optional]*: A boolean that denotes whether the trait reference is simple named or not. The default value is false.<br/><br/>*append(...) in Python, push(...) in TypeScript.*|Creates a trait with the specified name and adds it to the collection. Returns the trait that was added to the collection.|[CdmTraitReferenceBase](traitreferencebase.md)|1.0|
|**AddRange(IEnumerable\<[CdmTraitDefinition](trait.md)>)**<br/>*traitList*: The list of trait definitions to use to create trait references that will be added to the collection.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of trait definitions to the collection, after converting them to trait references first.|void|1.0|
|**AddRange(IEnumerable\<[CdmTraitGroupDefinition](traitgroup.md)>)**<br/>*traitGroupList*: The list of trait group definitions to use to create trait group references that will be added to the collection.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of trait group definitions to the collection, after converting them to trait group references first.|void|1.0|
|**AddRange(IEnumerable\<[CdmTraitReferenceBase](traitreferencebase.md)>)**<br/>*traitList*: The list of trait reference base objects to add to the collection.<br/><br/>*addAll(...) in Java, extend(...) in Python, concat(...) in TypeScript.*|Adds the elements of the specified list of trait reference base objects to the collection.|void|1.0|
|**Insert(int, [CdmTraitReferenceBase](traitreferencebase.md))**<br/>*index*: The index to insert the trait reference at.<br/>*trait*: The trait reference to add to the collection.<br/><br/>*add(...) in Java.*|Inserts the trait reference into the collection at the specified index.|void|1.0|
|**Remove([CdmTraitDefinition](trait.md), bool)**<br/>*traitDefToRemove*: The trait whose reference we want to remove from the collection.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.|Removes the trait reference with the same name as the specified trait definition from the collection. If there are multiple matches, this method will remove the first trait that's from a property. If there aren't any traits from properties and *onlyFromProperty* is false, then this method will remove the last trait that isn't from a property. Returns true if the operation is successful, false otherwise.|bool|1.0|
|**Remove([CdmTraitGroupDefinition](traitgroup.md), bool)**<br/>*traitGroupDefToRemove*: The trait group whose reference we want to remove from the collection.<br/>|Removes the trait group reference with the same name as the specified trait group definition from the collection. Returns true if the operation is successful, false otherwise.|bool|1.2|
|**Remove(string, bool)**<br/>*traitName*: The name of the trait to remove from the collection. <br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.|Removes the trait with the specified name from the collection. If there are multiple matches, this method will remove the first trait that's from a property. If there aren't any traits from properties and *onlyFromProperty* is false, then this method will remove the last trait that isn't from a property. Returns true if the operation is successful, false otherwise.|bool|1.0|
|**Remove([CdmTraitReferenceBase](traitreferencebase.md), bool)**<br/>*traitToRemove*: The trait to remove from the collection.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.|Removes the trait with the same name as the specified trait from the collection. If there are multiple matches, this method will remove the first trait that's from a property. If there aren't any traits from properties and *onlyFromProperty* is false, then this method will remove the last trait that isn't from a property. Returns true if the operation is successful, false otherwise.|bool|1.0|
|**RemoveAt(int)**<br/>*index*: The index of the trait to remove.|Removes the trait at the specified index from the collection.|void|1.0|
|**IndexOf([CdmTraitDefinition](trait.md), bool)**<br/>*traitDefinition*: The trait whose reference we want the index of.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.<br/><br/>*index(...) in Python.*|Returns the index of the trait reference with the same name as the specified trait definition. If there are multiple matches, this method will return the index of the first trait that's from a property. If there aren't any traits from properties and *onlyFromProperty* is false, then this method will return the index of the last trait that isn't from a property.|int|1.0|
|**IndexOf([CdmTraitGroupDefinition](trait.md), bool)**<br/>*traitGroupDefinition*: The trait group whose reference we want the index of.<br/>*index(...) in Python.*|Returns the index of the trait group reference with the same name as the specified trait group definition.|int|1.2|
|**IndexOf(string, bool)**<br/>*traitName*: The trait name associated with the trait reference we want the index of.<br/>*onlyFromProperty [optional]*: A boolean that denotes whether this method should only be applied for traits that originate from properties. The default value is false.<br/><br/>*index(...) in Python.*|Returns the index of the trait reference with the specified name. If there are multiple matches, this method will return the index of the first trait that's from a property. If there aren't any traits from properties and *onlyFromProperty* is false, then this method will return the index of the last trait that isn't from a property.|int|1.0|
|**IndexOf([CdmTraitReferenceBase](traitreferencebase.md), bool)**<br/>*trait*: The trait we want the index of.<br/>*onlyFromProperty*: A boolean that denotes whether this method should only be applied for traits that originate from properties.<br/><br/>*index(...) in Python.*|Returns the index of the trait reference with the same name as the specified trait. If there are multiple matches, this method will return the index of the first trait that's from a property. If there aren't any traits from properties and *onlyFromProperty* is false, then this method will return the index of the last trait that isn't from a property.|int|1.0|
|**Clear()**|Empties the collection.|void|1.0|
|**ToTraitRefs()**<br/>|Returns a new collection consisting of only the trait references found in this collection.|IEnumerable\<[CdmTraitReference](traitreference.md)>|1.2|
|**ToTraitGroupRefs()**<br/>|Returns a new collection consisting of only the trait group references found in this collection.|IEnumerable\<[CdmTraitGroupReference](traitgroupreference.md)>|1.2|
