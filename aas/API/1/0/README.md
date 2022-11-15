# AAS (Asset Administration Shell)

This is the sub-namespace resevered for the Asset Administration Shell - Part 2 Interoperability at Runtime Version 1.0. Identifiers used in the release candidates are also available:
- [V1.0RC01](./RC01/)
- [V1.0RC02](./RC02/)
- [V1.0RC03](./RC03/)

The document 'Details of the Asset Administration Shell Part 2 - Interoperability at Runtime' [1] defines the meaning of its content and the used identifiers.


## Introduction

The content of this area is defined in the 'Details of the Asset Administration Shell -
Part 2'. Only identifiers that are defined in this document are allowed in this
sub-namespace. The identifiers are used to denote the different operations of
AAS interfaces.


## Status: `Submitted`


## GetAssetAdministrationShell (Operation)

[https://admin-shell.io/aas/API/GetAssetAdministrationShell/1/0](https://admin-shell.io/aas/API/GetAssetAdministrationShell/1/0): Returns the Asset Administration Shell


## PutAssetAdministrationShell (Operation)

[https://admin-shell.io/aas/API/PutAssetAdministrationShell/1/0](https://admin-shell.io/aas/API/PutAssetAdministrationShell/1/0): Updates the Asset Administration Shell


## GetAllSubmodelReferences (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodelReferences/1/0](https://admin-shell.io/aas/API/GetAllSubmodelReferences/1/0): Returns all Submodel References


## PostSubmodelReference (Operation)

[https://admin-shell.io/aas/API/PostSubmodelReference/1/0](https://admin-shell.io/aas/API/PostSubmodelReference/1/0): Creates a Submodel Reference at the Asset Administration Shell


## DeleteSubmodelReference (Operation)

[https://admin-shell.io/aas/API/DeleteSubmodelReference/1/0](https://admin-shell.io/aas/API/DeleteSubmodelReference/1/0): Deletes the Submodel Reference from the Asset Administration Shell


## GetAssetInformation (Operation)

[https://admin-shell.io/aas/API/GetAssetInformation/1/0](https://admin-shell.io/aas/API/GetAssetInformation/1/0): Returns the Asset Information


## PutAssetInformation (Operation)

[https://admin-shell.io/aas/API/PutAssetInformation/1/0](https://admin-shell.io/aas/API/PutAssetInformation/1/0): Updates the Asset Information


## GetSubmodel (Operation)

[https://admin-shell.io/aas/API/GetSubmodel/1/0](https://admin-shell.io/aas/API/GetSubmodel/1/0): Returns the Submodel


## GetAllSubmodelElements (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodelElements/1/0](https://admin-shell.io/aas/API/GetAllSubmodelElements/1/0): Returns all submodel elements including their hierarchy


## GetSubmodelElementByPath (Operation)

[https://admin-shell.io/aas/API/GetSubmodelElementByPath/1/0](https://admin-shell.io/aas/API/GetSubmodelElementByPath/1/0): Returns a specific submodel element from the Submodel at a specified path


## GetFileByPath (Operation)

[https://admin-shell.io/aas/API/GetFileByPath/1/0](https://admin-shell.io/aas/API/GetFileByPath/1/0): Returns a specific file content from the Submodel at a specified path


## PutSubmodel (Operation)

[https://admin-shell.io/aas/API/PutSubmodel/1/0](https://admin-shell.io/aas/API/PutSubmodel/1/0): Updates the Submodel


## PostSubmodelElement (Operation)

[https://admin-shell.io/aas/API/PostSubmodelElement/1/0](https://admin-shell.io/aas/API/PostSubmodelElement/1/0): Creates a new submodel element as a child of the submodel.


## PostSubmodelElementByPath (Operation)

[https://admin-shell.io/aas/API/PostSubmodelElementByPath/1/0](https://admin-shell.io/aas/API/PostSubmodelElementByPath/1/0): Creates a new submodel element at a specified path within the submodel elements hierarchy.


## PutSubmodelElementByPath (Operation)

[https://admin-shell.io/aas/API/PutSubmodelElementByPath/1/0](https://admin-shell.io/aas/API/PutSubmodelElementByPath/1/0): Updates an existing submodel element at a specified path within the submodel elements hierarchy


## PutFileByPath (Operation)

[https://admin-shell.io/aas/API/PutFileByPath/1/0](https://admin-shell.io/aas/API/PutFileByPath/1/0): Updates the file content of an existing submodel element at a specified path within the submodel elements hierarchy


## SetSubmodelElementValueByPath (Operation)

[https://admin-shell.io/aas/API/SetSubmodelElementValueByPath/1/0](https://admin-shell.io/aas/API/SetSubmodelElementValueByPath/1/0): Sets the value of the submodel element at a specified path according to the protocol-specific RAW-value payload


## DeleteSubmodelElementByPath (Operation)

[https://admin-shell.io/aas/API/DeleteSubmodelElementByPath/1/0](https://admin-shell.io/aas/API/DeleteSubmodelElementByPath/1/0): Deletes a submodel element at a specified path within submodel elements hierarchy


## InvokeOperationSync (Operation)

[https://admin-shell.io/aas/API/InvokeOperationSync/1/0](https://admin-shell.io/aas/API/InvokeOperationSync/1/0): Synchronously invokes an Operation at a specified path with a client timeout in ms


## InvokeOperationAsync (Operation)

[https://admin-shell.io/aas/API/InvokeOperationAsync/1/0](https://admin-shell.io/aas/API/InvokeOperationAsync/1/0): Asynchronously invokes an Operation at a specified path with a client timeout in ms


## GetOperationAsyncResult (Operation)

[https://admin-shell.io/aas/API/GetOperationAsyncResult/1/0](https://admin-shell.io/aas/API/GetOperationAsyncResult/1/0): Returns the OperationResult of an asynchronously invoked operation


##  GenerateSerializationByIds (Operation)

[https://admin-shell.io/aas/API/GenerateSerializationByIds/1/0](https://admin-shell.io/aas/API/GenerateSerializationByIds/1/0): Returns an appropriate serialization based on the specified format


## GetAllAASXPackageIds (Operation)

[https://admin-shell.io/aas/API/GetAllAASXPackageIds/1/0](https://admin-shell.io/aas/API/GetAllAASXPackageIds/1/0): Returns a list of available AASX packages at the server


## GetAASXByPackageId (Operation)

[https://admin-shell.io/aas/API/GetAASXByPackageId/1/0](https://admin-shell.io/aas/API/GetAASXByPackageId/1/0): Returns a specific AASX package from the server


## PostAASXPackage (Operation)

[https://admin-shell.io/aas/API/PostAASXPackage/1/0](https://admin-shell.io/aas/API/PostAASXPackage/1/0): Creates an AASX package at the server


## PutAASXByPackageId (Operation)

[https://admin-shell.io/aas/API/PutAASXByPackageId/1/0](https://admin-shell.io/aas/API/PutAASXByPackageId/1/0): Updates the AASX package at the server


## DeleteAASXByPackageId (Operation)

[https://admin-shell.io/aas/API/DeleteAASXByPackageId/1/0](https://admin-shell.io/aas/API/DeleteAASXByPackageId/1/0): Deletes a specific AASX package


## GetAllAssetAdministrationShellDescriptors (Operation)

[https://admin-shell.io/aas/API/GetAllAssetAdministrationShellDescriptors/1/0](https://admin-shell.io/aas/API/GetAllAssetAdministrationShellDescriptors/1/0): Returns all Asset Administration Shell Descriptors from an AAS Registry


## GetAssetAdministrationShellDescriptorById (Operation)

[https://admin-shell.io/aas/API/GetAssetAdministrationShellDescriptorById/1/0](https://admin-shell.io/aas/API/GetAssetAdministrationShellDescriptorById/1/0): Returns a specific Asset Administration Shell Descriptor from an AAS Registry


## PostAssetAdministrationShellDescriptor (Operation)

[https://admin-shell.io/aas/API/PostAssetAdministrationShellDescriptor/1/0](https://admin-shell.io/aas/API/PostAssetAdministrationShellDescriptor/1/0): Creates a new Asset Administration Shell Descriptor, i.e. registers an AAS at an AAS Registry


## PutAssetAdministrationShellDescriptorById (Operation)

[https://admin-shell.io/aas/API/PutAssetAdministrationShellDescriptorById/1/0](https://admin-shell.io/aas/API/PutAssetAdministrationShellDescriptorById/1/0): Updates an existing Asset Administration Shell Descriptor


## DeleteAssetAdministrationShellDescriptorById (Operation)

[https://admin-shell.io/aas/API/DeleteAssetAdministrationShellDescriptorById/1/0](https://admin-shell.io/aas/API/DeleteAssetAdministrationShellDescriptorById/1/0): Deletes an Asset Administration Shell Descriptor


## GetAllSubmodelDescriptors (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodelDescriptors/1/0](https://admin-shell.io/aas/API/GetAllSubmodelDescriptors/1/0): Returns all submodel descriptors


## GetSubmodelDescriptorById (Operation)

[https://admin-shell.io/aas/API/GetSubmodelDescriptorById/1/0](https://admin-shell.io/aas/API/GetSubmodelDescriptorById/1/0): Returns a specific submodel descriptor


## PostSubmodelDescriptor (Operation)

[https://admin-shell.io/aas/API/PostSubmodelDescriptor/1/0](https://admin-shell.io/aas/API/PostSubmodelDescriptor/1/0): Creates a new submodel descriptor


## PutSubmodelDescriptorById (Operation)

[https://admin-shell.io/aas/API/PutSubmodelDescriptorById/1/0](https://admin-shell.io/aas/API/PutSubmodelDescriptorById/1/0): Updates an existing submodel descriptor


## DeleteSubmodelDescriptorById (Operation)

[https://admin-shell.io/aas/API/DeleteSubmodelDescriptorById/1/0](https://admin-shell.io/aas/API/DeleteSubmodelDescriptorById/1/0): Deletes a submodel descriptor


## GetAllAssetAdministrationShells (Operation)

[https://admin-shell.io/aas/API/GetAllAssetAdministrationShells/1/0](https://admin-shell.io/aas/API/GetAllAssetAdministrationShells/1/0): Returns all Asset Administration Shells


## GetAssetAdministrationShellById (Operation)

[https://admin-shell.io/aas/API/GetAssetAdministrationShellById/1/0](https://admin-shell.io/aas/API/GetAssetAdministrationShellById/1/0): Returns a specific Asset Administration Shell


## GetAllAssetAdministrationShellsByAssetId (Operation)

[https://admin-shell.io/aas/API/GetAllAssetAdministrationShellsByAssetId/1/0](https://admin-shell.io/aas/API/GetAllAssetAdministrationShellsByAssetId/1/0): Returns all Asset Administration Shells that are linked to a globally unique asset identifier or to specific asset ids.


## GetAllAssetAdministrationShellsByIdShort (Operation)

[https://admin-shell.io/aas/API/GetAllAssetAdministrationShellsByIdShort/1/0](https://admin-shell.io/aas/API/GetAllAssetAdministrationShellsByIdShort/1/0):
Returns all Asset Administration Shells with a specific idShort


## PostAssetAdministrationShell (Operation)

[https://admin-shell.io/aas/API/PostAssetAdministrationShell/1/0](https://admin-shell.io/aas/API/PostAssetAdministrationShell/1/0): Creates a new Asset Administration Shell.


## PutAssetAdministrationShellById (Operation)

[https://admin-shell.io/aas/API/PutAssetAdministrationShellById/1/0](https://admin-shell.io/aas/API/PutAssetAdministrationShellById/1/0): Updates an existing Asset Administration Shell


## DeleteAssetAdministrationShellById (Operation)

[https://admin-shell.io/aas/API/DeleteAssetAdministrationShellById/1/0](https://admin-shell.io/aas/API/DeleteAssetAdministrationShellById/1/0): Deletes an Asset Administration Shell


## GetAllSubmodels (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodels/1/0](https://admin-shell.io/aas/API/GetAllSubmodels/1/0): Returns all Submodels


## GetSubmodelById (Operation)

[https://admin-shell.io/aas/API/GetSubmodelById/1/0](https://admin-shell.io/aas/API/GetSubmodelById/1/0): Returns a specific Submodel


## GetAllSubmodelsBySemanticId (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodelsBySemanticId/1/0](https://admin-shell.io/aas/API/GetAllSubmodelsBySemanticId/1/0): Returns all Submodels with a specific SemanticId


## GetAllSubmodelsByIdShort (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodelsByIdShort/1/0](https://admin-shell.io/aas/API/GetAllSubmodelsByIdShort/1/0): Returns all Submodels with a specific idShort


## PostSubmodel (Operation)

[https://admin-shell.io/aas/API/PostSubmodel/1/0](https://admin-shell.io/aas/API/PostSubmodel/1/0): Creates a new Submodel.


## PutSubmodelById (Operation)

[https://admin-shell.io/aas/API/PutSubmodelById/1/0](https://admin-shell.io/aas/API/PutSubmodelById/1/0): Updates an existing Submodel


## DeleteSubmodelById (Operation)

[https://admin-shell.io/aas/API/DeleteSubmodelById/1/0](https://admin-shell.io/aas/API/DeleteSubmodelById/1/0): Deletes a Submodel


## GetAllConceptDescriptions (Operation)

[https://admin-shell.io/aas/API/GetAllConceptDescriptions/1/0](https://admin-shell.io/aas/API/GetAllConceptDescriptions/1/0): Returns all Concept Descriptions


## GetConceptDescriptionById (Operation)

[https://admin-shell.io/aas/API/GetConceptDescriptionById/1/0](https://admin-shell.io/aas/API/GetConceptDescriptionById/1/0): Returns a specific Concept Description


## GetAllConceptDescriptionsByIdShort (Operation)

[https://admin-shell.io/aas/API/GetAllConceptDescriptionsByIdShort/1/0](https://admin-shell.io/aas/API/GetAllConceptDescriptionsByIdShort/1/0): Returns all Concept Descriptions with a specific idShort


## GetAllConceptDescriptionsByIsCaseOf (Operation)

[https://admin-shell.io/aas/API/GetAllConceptDescriptionsByIsCaseOf/1/0](https://admin-shell.io/aas/API/GetAllConceptDescriptionsByIsCaseOf/1/0): Returns all Concept Descriptions with a specific IsCaseOf-reference


## GetAllConceptDescriptionsByDataSpecificationReference (Operation)

[https://admin-shell.io/aas/API/GetAllConceptDescriptionsByDataSpecificationReference/1/0](https://admin-shell.io/aas/API/GetAllConceptDescriptionsByDataSpecificationReference/1/0): Returns all Concept Descriptions with a specific dataSpecification reference


## PostConceptDescription (Operation)

[https://admin-shell.io/aas/API/PostConceptDescription/1/0](https://admin-shell.io/aas/API/PostConceptDescription/1/0): Creates a new Concept Description.


## PutConceptDescriptionById (Operation)

[https://admin-shell.io/aas/API/PutConceptDescriptionById/1/0](https://admin-shell.io/aas/API/PutConceptDescriptionById/1/0): Updates an existing Concept Description


## DeleteConceptDescriptionById (Operation)

[https://admin-shell.io/aas/API/DeleteConceptDescriptionById/1/0](https://admin-shell.io/aas/API/DeleteConceptDescriptionById/1/0): Deletes a Concept Description


## GetAllAssetAdministrationShellIdsByAssetLink (Operation)

[https://admin-shell.io/aas/API/GetAllAssetAdministrationShellIdsByAssetLink/1/0](https://admin-shell.io/aas/API/GetAllAssetAdministrationShellIdsByAssetLink/1/0): Returns a list of Asset Administration Shell ids based on Asset identifier key-value-pairs


## GetAllAssetLinksById (Operation)

[https://admin-shell.io/aas/API/GetAllAssetLinksById/1/0](https://admin-shell.io/aas/API/GetAllAssetLinksById/1/0): Returns a list of Asset identifier key-value-pairs based on an given Asset Administration Shell id


## PostAllAssetLinksById (Operation)

[https://admin-shell.io/aas/API/PostAllAssetLinksById/1/0](https://admin-shell.io/aas/API/PostAllAssetLinksById/1/0): Creates or updates all Asset identifier key-value-pairs linked to an Asset Administration Shell to edit discoverable content


## DeleteAllAssetLinksById (Operation)

[https://admin-shell.io/aas/API/DeleteAllAssetLinksById/1/0](https://admin-shell.io/aas/API/DeleteAllAssetLinksById/1/0): Deletes all Asset identifier key-value-pair linked to an Asset Administration Shell


## Descriptor (Class)

[https://admin-shell.io/aas/API/DataTypes/Descriptor/1/0](https://admin-shell.io/aas/API/DataTypes/Descriptor/1/0): The self-describing information of a network resource.


## AssetAdministrationShellDescriptor (Class)

[https://admin-shell.io/aas/API/DataTypes/AssetAdministrationShellDescriptor/1/0](https://admin-shell.io/aas/API/DataTypes/AssetAdministrationShellDescriptor/1/0): Descriptor of an Asset Administration Shell


## SubmodelDescriptor (Class)

[https://admin-shell.io/aas/API/DataTypes/SubmodelDescriptor/1/0](https://admin-shell.io/aas/API/DataTypes/SubmodelDescriptor/1/0): A descriptor of a submodel


## Endpoint (Class)

[https://admin-shell.io/aas/API/DataTypes/Endpoint/1/0](https://admin-shell.io/aas/API/DataTypes/Endpoint/1/0): The endpoint description of a network resource.


## ProtocolInformation (Class)

[https://admin-shell.io/aas/API/DataTypes/ProtocolInformation/1/0](https://admin-shell.io/aas/API/DataTypes/ProtocolInformation/1/0): The protocol information of a network resource endpoint will be defined in DIN SPEC 16593-2.


## Result (Class)

[https://admin-shell.io/aas/API/DataTypes/Result/1/0](https://admin-shell.io/aas/API/DataTypes/Result/1/0): The result object


## Message (Class)

[https://admin-shell.io/aas/API/DataTypes/Message/1/0](https://admin-shell.io/aas/API/DataTypes/Message/1/0): A message containing more information for the requester about a certain happening in the backend.


## MessageTypeEnum (Enumeration)

[https://admin-shell.io/aas/API/DataTypes/MessageTypeEnum/1/0](https://admin-shell.io/aas/API/DataTypes/MessageTypeEnum/1/0): The message type


## OperationRequest (Class)

[https://admin-shell.io/aas/API/DataTypes/OperationRequest/1/0](https://admin-shell.io/aas/API/DataTypes/OperationRequest/1/0): The operation request object


## OperationResult (Class)

[https://admin-shell.io/aas/API/DataTypes/OperationResult/1/0](https://admin-shell.io/aas/API/DataTypes/OperationResult/1/0): The operation’s invocation result object


## ExecutionState (Class)

[https://admin-shell.io/aas/API/DataTypes/ExecutionState/1/0](https://admin-shell.io/aas/API/DataTypes/ExecutionState/1/0): The operation’s invocation result state


## OperationHandle (Class)

[https://admin-shell.io/aas/API/DataTypes/OperationHandle/1/0](https://admin-shell.io/aas/API/DataTypes/OperationHandle/1/0): The returned handle of an operation’s asynchronous invocation used to request the current state of the operation’s execution.



## Contact

The entries of this sub-namespace have been created by [Sebastian Bader](https://github.com/sebbader)
on behalf of the IDTA Working Group 'Asset Administration Shell'.
Contact via a [web form](https://www.plattform-i40.de/IP/Navigation/EN/ThePlatform/Contact/contact.html).




[1] S. Bader, B. Berres, B. Boss, A. Graf Gatterburg, M. Hoffmeister et al.
['Details of the Asset Administration Shell Part 2, Interoperability at Runtime – Exchanging Information via Application Programming Interfaces'](), Version 1.0,
Plattform Industrie 4.0, ZVEI, 2023 (to be published)
