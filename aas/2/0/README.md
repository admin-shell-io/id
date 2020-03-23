# AAS (Asset Administration Shell)

This is the sub-namespace resevered for the Asset Administration Shell Metamodel. 

## Introduction

The Metamodel itself is defined in the 'Details of the Asset Administration Shell - Part 1'. Only classes, attributes and named entities used in this model are allowed in this sub-namespace. The Metamodel is the core resource for the structure of the Asset Administration Shell and provides the frame for all further specifications. The following entities are defined in the Metamodel but also serve as an example how to use the 'Asset Administration Shell Identifiers' in general.

## Status: `Accepted`
The sub-namespace AAS and its identifiers have been accepted by the Coordination Board.



## Asset
An Asset describes meta data of an asset that is represented by an AAS. The asset may either represent an asset type or an asset instance. The asset has a globally unique identifier plus – if needed – additional domain specific (proprietary) identifiers.

[http://admin-shell.io/aas/2/0/Asset](http://admin-shell.io/aas/2/0/Asset) The Asset class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Asset/assetIdentificationModel
A reference to a Submodel that defines the handling of additional domain specific (proprietary) Identifiers for the asset like e.g. serial number etc.

[http://admin-shell.io/aas/2/0/Asset/assetIdentificationModel](http://admin-shell.io/aas/2/0/Asset/assetIdentificationModel) The attribute 'assetIdentificationModel' of the Asset class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Asset/billOfMaterial
Bill of material of the asaset represented by a submodel of the same AAS. This submodel contains a set of entities describing the material used to compose the composite I4.0 Component.

[http://admin-shell.io/aas/2/0/Asset/billOfMaterial](http://admin-shell.io/aas/2/0/Asset/billOfMaterial) The attribute 'billOfMaterial' of the Asset class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Asset/kind
Denotes whether the Asset of of kind “Type” or “Instance”.

[http://admin-shell.io/aas/2/0/Asset/kind](http://admin-shell.io/aas/2/0/Asset/kind) The attribute 'kind' of the Asset class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## AssetAdministrationShell
The Asset Administration Shell class. Inherits from HasDataSpecification and Identifiable.

[http://admin-shell.io/aas/2/0/AssetAdministrationShell](http://admin-shell.io/aas/2/0/AssetAdministrationShell/) - The Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## AssetAdministrationShell/asset
The reference to the AAS the AAS was derived from. Links to an Asset Reference and is mandatory for every AssetAdministrationShell instance.

[http://admin-shell.io/aas/2/0/AssetAdministrationShell/asset](http://admin-shell.io/aas/2/0/AssetAdministrationShell/asset) The attribute 'asset' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/conceptDictionary
An AAS max have one or more concept dictionaries assigned to it. The concept dictionaries typically contain only descriptions for elements that are also used within the AAS (via HasSemantics). Optional attribute linking to a ConceptDictionary.

[http://admin-shell.io/aas/2/0/AssetAdministrationShell/conceptDictionary](http://admin-shell.io/aas/2/0/AssetAdministrationShell/conceptDictionary) The attribute 'conceptDictionary' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/derivedFrom
The reference to the AAS the AAS was derived from. Optional (max 1) attribute linking to an AssetAdministrationShell reference.

[http://admin-shell.io/aas/2/0/AssetAdministrationShell/derivedFrom](http://admin-shell.io/aas/2/0/AssetAdministrationShell/derivedFrom) The attribute 'derivedFrom' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/security
Definition of the security relevant aspects of the AAS. Optional (max 1) attribute linking to an Security object.

[http://admin-shell.io/aas/2/0/AssetAdministrationShell/security](http://admin-shell.io/aas/2/0/AssetAdministrationShell/security) The attribute 'security' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/submodel
The asset of an AAS is typically described by one or more submodels. Temporarily no submodel might be assigned to the AAS. Links to an Submodel Reference.

[http://admin-shell.io/aas/2/0/AssetAdministrationShell/submodel](http://admin-shell.io/aas/2/0/AssetAdministrationShell/submodel) The attribute 'submodel' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/view
If needed stakeholder specific views can be defined on the elements of the AAS. Optional attribute which links to a View.

[http://admin-shell.io/aas/2/0/AssetAdministrationShell/view](http://admin-shell.io/aas/2/0/AssetAdministrationShell/view) The attribute 'view' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## DataSpecification
[http://admin-shell.io/aas/2/0/DataSpecification](http://admin-shell.io/aas/2/0/DataSpecification) The DataSpecification class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.



## DataSpecificationContent
[http://admin-shell.io/aas/2/0/DataSpecificationContent](http://admin-shell.io/aas/2/0/DataSpecificationContent) The DataSpecificationContent class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## DataSpecificationTemplate
[http://admin-shell.io/aas/2/0/DataSpecificationTemplate](http://admin-shell.io/aas/2/0/DataSpecificationTemplate) The DataSpecificationTemplate class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


##
[]() The attribute '' of the - class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


##
[]() The attribute '' of the - class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


##
[]() The attribute '' of the - class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


##
[]() The attribute '' of the - class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


##
[]() The attribute '' of the - class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## HasKind
An element with a kind is an element that can either represent a template (type) or an instance. Default for an element is that it is representing an instance.

[http://admin-shell.io/aas/2/0/HasKind](http://admin-shell.io/aas/2/0/HasKind) The HasKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## HasKind/kind
Kind of the element: either type or instance. Default Value = Instance

[http://admin-shell.io/aas/2/0/HasKind/kind](http://admin-shell.io/aas/2/0/HasKind/kind) The attribute 'kind' of the HasKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Identifiable
[http://admin-shell.io/aas/2/0/Identifiable](http://admin-shell.io/aas/2/0/Identifiable)


## Key
A key is a reference to an element by its id.

[http://admin-shell.io/aas/2/0/Key](http://admin-shell.io/aas/2/0/Key) The Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Key/idType
Type of the key value. In case of idType = idShort local shall be true. In case type=GlobalReference idType shall not be IdShort.

[http://admin-shell.io/aas/2/0/Key/idType](http://admin-shell.io/aas/2/0/Key/idType) The attribute 'idType' of the Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Key/local
Denotes if the key references a model element of the same AAS (=true) or not (=false). In case of local = false the key may reference a model element of another AAS or an entity outside any AAS that has a global unique id.

[http://admin-shell.io/aas/2/0/Key/local](http://admin-shell.io/aas/2/0/Key/local) The attribute 'local' of the Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Key/type
Denote which kind of entity is referenced. In case type = GlobalReference then the element is a global unique id. In all other cases the key references a model element of the same or of another AAS. The name of the model element is explicitly listed.

[http://admin-shell.io/aas/2/0/Key/type](http://admin-shell.io/aas/2/0/Key/type) The attribute 'type' of the Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Key/value
The key value, for example an IRDI if the idType=IRDI.

[http://admin-shell.io/aas/2/0/Key/value](http://admin-shell.io/aas/2/0/Key/value) The attribute 'value' of the Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Reference
Reference to either a model element of the same or another AAs or to an external entity. A reference is an ordered list of keys, each key referencing an element. The complete list of keys may for example be concatenated to a path that then gives unique access to an element or entity.

[http://admin-shell.io/aas/2/0/Reference](http://admin-shell.io/aas/2/0/Reference) The Reference class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Reference/key
Unique reference in its name space.

[http://admin-shell.io/aas/2/0/Reference/key](http://admin-shell.io/aas/2/0/Reference/key) The attribute 'key' of the Reference class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Submodel
A submodel defines a specific aspect of the asset represented by the AAS. A submodel is used to structure the digital representation and technical functionality of an Administration Shell into distinguishable parts. Each submodel refers to a well-defined domain or subject matter. Submodels can become standardized and thus become submodels types. Submodels can have different life-cycles.

[http://admin-shell.io/aas/2/0/Submodel](http://admin-shell.io/aas/2/0/Submodel) The Submodel class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Submodel/submodelElement
A submodel consists of zero or more submodel elements.

[http://admin-shell.io/aas/2/0/Submodel/submodelElement](http://admin-shell.io/aas/2/0/Submodel/submodelElement) The attribute 'submodelElement' of the Submodel class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## SubmodelElement
A submodel element is an element suitable for the description and differentiation of assets.

[http://admin-shell.io/aas/2/0/SubmodelElement](http://admin-shell.io/aas/2/0/SubmodelElement) The SubmodelElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## SubmodelElementCollection
A submodel element collection is a set or list of submodel elements.

[http://admin-shell.io/aas/2/0/SubmodelElementCollection](http://admin-shell.io/aas/2/0/SubmodelElementCollection) The SubmodelElementCollection class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## SubmodelElementCollection/allowDuplicates 
If allowDuplicates=true then it is allowed that the collection contains the same element several times.

[http://admin-shell.io/aas/2/0/SubmodelElementCollection/allowDuplicates](http://admin-shell.io/aas/2/0/SubmodelElementCollection/allowDuplicates) The attribute 'allowDuplicates' of the SubmodelElementCollection class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## SubmodelElementCollection/ordered
 If ordered=false then the elements in the property collection are not ordered. If ordered=true then the elements in the collection are ordered.

[http://admin-shell.io/aas/2/0/SubmodelElementCollection/ordered](http://admin-shell.io/aas/2/0/SubmodelElementCollection/ordered) The attribute 'ordered' of the SubmodelElementCollection class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## SubmodelElementCollection/value
Submodel element contained in the collection.

[http://admin-shell.io/aas/2/0/SubmodelElementCollection/value](http://admin-shell.io/aas/2/0/SubmodelElementCollection/value) The attribute 'value' of the SubmodelElementCollection class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.




## Contact

This subnamespace was created by the [Plattform Industrie 4.0](http://www.plattform-i40.de/). The [Coordination Board Submodels](mailto:coordination-board@admin-shell.io) maintains these identifiers.