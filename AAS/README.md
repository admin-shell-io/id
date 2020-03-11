# AAS (Asset Administration Shell)

This is the subnamespace resevered for the Asset Administration Shell Metamodel. 

## Introduction

The Metamodel itself is defined in the 'Details of the Asset Administration Shell - Part 1'. Only classes, attributes and named entities used in this model are allowed in this subnamespace. The Metamodel is the core resource for the structure of the Asset Administration Shell and provides the frame for all further specifications. The following entities are defined in the Metamodel but also serve as an example how to use the 'Asset Administration Shell Identifiers' in general.

## Status: `Accepted`
The subnamespace AAS and its identifiers have been accepted by the Coordination Board.


## AssetAdministrationShell
The Asset Administration Shell class. Inherits from HasDataSpecification and Identifiable.

[https://admin-shell.io/AAS/AssetAdministrationShell/2/0/](https://admin-shell.io/AAS/AssetAdministrationShell/2/0/) - The Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

[https://admin-shell.io/AAS/AssetAdministrationShell/1/0/](https://admin-shell.io/AAS/AssetAdministrationShell/1/0/) - The Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 1.0'.


## AssetAdministrationShell/asset
The reference to the AAS the AAS was derived from. Links to an Asset Reference and is mandatory for every AssetAdministrationShell instance.

[https://admin-shell.io/AAS/AssetAdministrationShell/asset/2/0/](https://admin-shell.io/AAS/AssetAdministrationShell/asset/2/0/) The attribute 'asset' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/conceptDictionary
An AAS max have one or more concept dictionaries assigned to it. The concept dictionaries typically contain only descriptions for elements that are also used within the AAS (via HasSemantics). Optional attribute linking to a ConceptDictionary.

[https://admin-shell.io/AAS/AssetAdministrationShell/conceptDictionary/2/0/](https://admin-shell.io/AAS/AssetAdministrationShell/conceptDictionary/2/0/) The attribute 'conceptDictionary' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/derivedFrom
The reference to the AAS the AAS was derived from. Optional (max 1) attribute linking to an AssetAdministrationShell reference.

[https://admin-shell.io/AAS/AssetAdministrationShell/derivedFrom/2/0/](https://admin-shell.io/AAS/AssetAdministrationShell/derivedFrom/2/0/) The attribute 'derivedFrom' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/security
Definition of the security relevant aspects of the AAS. Optional (max 1) attribute linking to an Security object.

[https://admin-shell.io/AAS/AssetAdministrationShell/security/2/0/](https://admin-shell.io/AAS/AssetAdministrationShell/security/2/0/) The attribute 'security' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/submodel
The asset of an AAS is typically described by one or more submodels. Temporarily no submodel might be assigned to the AAS. Links to an Submodel Reference.

[https://admin-shell.io/AAS/AssetAdministrationShell/submodel/2/0/](https://admin-shell.io/AAS/AssetAdministrationShell/submodel/2/0/) The attribute 'submodel' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/view
If needed stakeholder specific views can be defined on the elements of the AAS. Optional attribute which links to a View.

[https://admin-shell.io/AAS/AssetAdministrationShell/view/2/0/](https://admin-shell.io/AAS/AssetAdministrationShell/view/2/0/) The attribute 'view' of the Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.




## Contact

This subnamespace was created by the [Plattform Industrie 4.0](https://www.plattform-i40.de/). The [Coordination Board Submodels](mailto:coordination-board@admin-shell.io) maintains these identifiers.