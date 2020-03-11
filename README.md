# AAS (Asset Administration Shell)

This is the subnamespace resevered for the Asset Administration Shell Metamodel. 

## Introduction

The Metamodel itself is defined in the 'Details of the Asset Administration Shell - Part 1'. Only classes, attributes and named entities used in this model are allowed in this subnamespace. The Metamodel is the core resource for the structure of the Asset Administration Shell and provides the frame for all further specifications. The following entities are defined in the Metamodel but also serve as an example how to use the 'Asset Administration Shell Identifiers' in general.


## AssetAdministrationShell
The Asset Administration Shell class. Inherits from HasDataSpecification and Identifiable.

[https://admin-shell.io/AAS/AssetAdministrationShell/2/0/](https://admin-shell.io/AAS/AssetAdministrationShell/2/0/) The Asset Administration Shell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


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
# Asset Administration Shell Identifiers

The Asset Administration Shell itself only defines the structure and syntax of the Industry 4.0 Component. Content, its features, attributes and values need to be semantically defined. It is not in scope of the Platform Industry 4.0 to define and/or maintain such domain-specific entities itself. Therefore, definitions and terms from external vocabulary providers are recommended, for instance [eCl@ss]() or [IEC CDD](). 

While many attributes, properties and values are defined in such vocabularies, there is a significant chance that some necessary entities are still missing. The 'Asset Administration Shell Identifiers' is preliminary approach to provide a first, lightweight location to register new identifiers. This is done by relying on the [admin-shell.io](http://admin-shell.io) domain as a common namespace.

The Coordination Board of the Plattform Industry 4.0 is maintaining the Asset Administration Shell Identifiers and ensures the contiuity and stability of the identifiers. As such, it is in the authority of the Coordination Board to accept, revise, adjust or decline requested identifiers. 


## Identifier Scheme and Description

The identifiers are encoded as URIs, in the HTTP scheme. The following pattern is used:

http(s)://admin-shell.io/'<subnamespace>'/'<ShortId>'/'<version>'/'<revision>'/

It is recommended to use the qualified names for the subnamespace and the ShortId. Especially should the subnamespace indicate the domain or use case it is intended to be used. Exisiting 



## Registering Process

There are two possible processes to request identifiers:

1. Work with the Github
- Fork the [GitHub Repo](https://github.com/sebbader/id/)
- Add a new folder with the subnamespace as its name
- Create a README following the template in https://github.com/sebbader/id/template/README.txt
- Create a Pull Request from your forked repository to the original

2. Contact the [Coordination Board for Submodels](mailto:coordination-board@admin-shell.io)
- Explain the purpose of the new identifier(s)
- Attach the filled [template](https://github.com/sebbader/id/template/README.txt)

The request will be processed as soon as possible. However, no guaranteed process time can be given. 


## Guidelines

Only organizations can suggest Asset Administration Shell Identifiers, requests from individuals cannot be regarded. Please take care that your organization is there for the next years. 

Add contact information. Only requests with at least two valid and responding email addresses will be regarded. In case the contact person changes, please update the according information in the repsective README or inform the Coordination Board. 

Use Asset Administration Shell Identifiers only for Industry 4.0 related topics. This offer is not intended for any identifiers but has a strong focus on Industry 4.0 and the Asset Administration Shell.

Asset Administration Shell Identifiers are intended to stay. Please think about really necessary terms and entities and restrict them to a minimal set.