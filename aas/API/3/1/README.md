# AAS (Asset Administration Shell)

This is the sub-namespace reserved for the "Specification of the [Asset Administration Shell - Part 2: Application Programming Interfaces", Version 3.1 ](IDTA-01002-3-1)(https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/index.html).

The document 'Specification of the Asset Administration Shell - Part 2: Application Programming Interfaces', Version 3.1 (IDTA-01002-3-1)  defines the meaning of its content and the used identifiers.


## Introduction

The content of this area is defined in the "Specification of the Asset Administration Shell - Part 2: Application Programming Interfaces", Version 3.1 (IDTA-01002-3-1). 
Only identifiers that are defined in this document are allowed in this sub-namespace. 
The identifiers are used to denote the different operations of AAS interfaces.

## Status: `Accepted`

The content of the document and its identifiers have been accepted by the IDTA Coordination Board.


## GetAssetAdministrationShell (Operation)

[https://admin-shell.io/aas/API/GetAssetAdministrationShell/3/1](https://admin-shell.io/aas/API/GetAssetAdministrationShell/3/1): Returns the Asset Administration Shell


## PutAssetAdministrationShell (Operation)

[https://admin-shell.io/aas/API/PutAssetAdministrationShell/3/1](https://admin-shell.io/aas/API/PutAssetAdministrationShell/3/1): Updates the Asset Administration Shell


## GetAllSubmodelReferences (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodelReferences/3/1](https://admin-shell.io/aas/API/GetAllSubmodelReferences/3/1): Returns all Submodel References


## PostSubmodelReference (Operation)

[https://admin-shell.io/aas/API/PostSubmodelReference/3/1](https://admin-shell.io/aas/API/PostSubmodelReference/3/1): Creates a Submodel Reference at the Asset Administration Shell


## DeleteSubmodelReference (Operation)

[https://admin-shell.io/aas/API/DeleteSubmodelReference/3/1](https://admin-shell.io/aas/API/DeleteSubmodelReference/3/1): Deletes the Submodel Reference from the Asset Administration Shell


## GetAssetInformation (Operation)

[https://admin-shell.io/aas/API/GetAssetInformation/3/1](https://admin-shell.io/aas/API/GetAssetInformation/3/1): Returns the Asset Information


## PutAssetInformation (Operation)

[https://admin-shell.io/aas/API/PutAssetInformation/3/1](https://admin-shell.io/aas/API/PutAssetInformation/3/1): Updates the Asset Information


## GetSubmodel (Operation)

[https://admin-shell.io/aas/API/GetSubmodel/3/1](https://admin-shell.io/aas/API/GetSubmodel/3/1): Returns the Submodel


## GetAllSubmodelElements (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodelElements/3/1](https://admin-shell.io/aas/API/GetAllSubmodelElements/3/1): Returns all submodel elements including their hierarchy


## GetSubmodelElementByPath (Operation)

[https://admin-shell.io/aas/API/GetSubmodelElementByPath/3/1](https://admin-shell.io/aas/API/GetSubmodelElementByPath/3/1): Returns a specific submodel element from the Submodel at a specified path


## GetFileByPath (Operation)

[https://admin-shell.io/aas/API/GetFileByPath/3/1](https://admin-shell.io/aas/API/GetFileByPath/3/1): Returns a specific file content from the Submodel at a specified path


## PutSubmodel (Operation)

[https://admin-shell.io/aas/API/PutSubmodel/3/1](https://admin-shell.io/aas/API/PutSubmodel/3/1): Updates the Submodel


## PostSubmodelElement (Operation)

[https://admin-shell.io/aas/API/PostSubmodelElement/3/1](https://admin-shell.io/aas/API/PostSubmodelElement/3/1): Creates a new submodel element as a child of the submodel.


## PostSubmodelElementByPath (Operation)

[https://admin-shell.io/aas/API/PostSubmodelElementByPath/3/1](https://admin-shell.io/aas/API/PostSubmodelElementByPath/3/1): Creates a new submodel element at a specified path within the submodel elements hierarchy.


## PutSubmodelElementByPath (Operation)

[https://admin-shell.io/aas/API/PutSubmodelElementByPath/3/1](https://admin-shell.io/aas/API/PutSubmodelElementByPath/3/1): Updates an existing submodel element at a specified path within the submodel elements hierarchy


## PutFileByPath (Operation)

[https://admin-shell.io/aas/API/PutFileByPath/3/1](https://admin-shell.io/aas/API/PutFileByPath/3/1): Updates the file content of an existing submodel element at a specified path within the submodel elements hierarchy


## SetSubmodelElementValueByPath (Operation)

[https://admin-shell.io/aas/API/SetSubmodelElementValueByPath/3/1](https://admin-shell.io/aas/API/SetSubmodelElementValueByPath/3/1): Sets the value of the submodel element at a specified path according to the protocol-specific RAW-value payload


## DeleteSubmodelElementByPath (Operation)

[https://admin-shell.io/aas/API/DeleteSubmodelElementByPath/3/1](https://admin-shell.io/aas/API/DeleteSubmodelElementByPath/3/1): Deletes a submodel element at a specified path within submodel elements hierarchy


## InvokeOperationSync (Operation)

[https://admin-shell.io/aas/API/InvokeOperationSync/3/1](https://admin-shell.io/aas/API/InvokeOperationSync/3/1): Synchronously invokes an Operation at a specified path with a client timeout in ms


## InvokeOperationAsync (Operation)

[https://admin-shell.io/aas/API/InvokeOperationAsync/3/1](https://admin-shell.io/aas/API/InvokeOperationAsync/3/1): Asynchronously invokes an Operation at a specified path with a client timeout in ms


## GetOperationAsyncResult (Operation)

[https://admin-shell.io/aas/API/GetOperationAsyncResult/3/1](https://admin-shell.io/aas/API/GetOperationAsyncResult/3/1): Returns the OperationResult of an asynchronously invoked operation


##  GenerateSerializationByIds (Operation)

[https://admin-shell.io/aas/API/GenerateSerializationByIds/3/1](https://admin-shell.io/aas/API/GenerateSerializationByIds/3/1): Returns an appropriate serialization based on the specified format


## GetAllAASXPackageIds (Operation)

[https://admin-shell.io/aas/API/GetAllAASXPackageIds/3/1](https://admin-shell.io/aas/API/GetAllAASXPackageIds/3/1): Returns a list of available AASX packages at the server


## GetAASXByPackageId (Operation)

[https://admin-shell.io/aas/API/GetAASXByPackageId/3/1](https://admin-shell.io/aas/API/GetAASXByPackageId/3/1): Returns a specific AASX package from the server


## PostAASXPackage (Operation)

[https://admin-shell.io/aas/API/PostAASXPackage/3/1](https://admin-shell.io/aas/API/PostAASXPackage/3/1): Creates an AASX package at the server


## PutAASXByPackageId (Operation)

[https://admin-shell.io/aas/API/PutAASXByPackageId/3/1](https://admin-shell.io/aas/API/PutAASXByPackageId/3/1): Updates the AASX package at the server


## DeleteAASXByPackageId (Operation)

[https://admin-shell.io/aas/API/DeleteAASXByPackageId/3/1](https://admin-shell.io/aas/API/DeleteAASXByPackageId/3/1): Deletes a specific AASX package


## GetAllAssetAdministrationShellDescriptors (Operation)

[https://admin-shell.io/aas/API/GetAllAssetAdministrationShellDescriptors/3/1](https://admin-shell.io/aas/API/GetAllAssetAdministrationShellDescriptors/3/1): Returns all Asset Administration Shell Descriptors from an AAS Registry


## GetAssetAdministrationShellDescriptorById (Operation)

[https://admin-shell.io/aas/API/GetAssetAdministrationShellDescriptorById/3/1](https://admin-shell.io/aas/API/GetAssetAdministrationShellDescriptorById/3/1): Returns a specific Asset Administration Shell Descriptor from an AAS Registry


## PostAssetAdministrationShellDescriptor (Operation)

[https://admin-shell.io/aas/API/PostAssetAdministrationShellDescriptor/3/1](https://admin-shell.io/aas/API/PostAssetAdministrationShellDescriptor/3/1): Creates a new Asset Administration Shell Descriptor, i.e. registers an AAS at an AAS Registry


## PutAssetAdministrationShellDescriptorById (Operation)

[https://admin-shell.io/aas/API/PutAssetAdministrationShellDescriptorById/3/1](https://admin-shell.io/aas/API/PutAssetAdministrationShellDescriptorById/3/1): Updates an existing Asset Administration Shell Descriptor


## DeleteAssetAdministrationShellDescriptorById (Operation)

[https://admin-shell.io/aas/API/DeleteAssetAdministrationShellDescriptorById/3/1](https://admin-shell.io/aas/API/DeleteAssetAdministrationShellDescriptorById/3/1): Deletes an Asset Administration Shell Descriptor


## GetAllSubmodelDescriptors (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodelDescriptors/3/1](https://admin-shell.io/aas/API/GetAllSubmodelDescriptors/3/1): Returns all submodel descriptors


## GetSubmodelDescriptorById (Operation)

[https://admin-shell.io/aas/API/GetSubmodelDescriptorById/3/1](https://admin-shell.io/aas/API/GetSubmodelDescriptorById/3/1): Returns a specific submodel descriptor


## PostSubmodelDescriptor (Operation)

[https://admin-shell.io/aas/API/PostSubmodelDescriptor/3/1](https://admin-shell.io/aas/API/PostSubmodelDescriptor/3/1): Creates a new submodel descriptor


## PutSubmodelDescriptorById (Operation)

[https://admin-shell.io/aas/API/PutSubmodelDescriptorById/3/1](https://admin-shell.io/aas/API/PutSubmodelDescriptorById/3/1): Updates an existing submodel descriptor


## DeleteSubmodelDescriptorById (Operation)

[https://admin-shell.io/aas/API/DeleteSubmodelDescriptorById/3/1](https://admin-shell.io/aas/API/DeleteSubmodelDescriptorById/3/1): Deletes a submodel descriptor


## GetAllAssetAdministrationShells (Operation)

[https://admin-shell.io/aas/API/GetAllAssetAdministrationShells/3/1](https://admin-shell.io/aas/API/GetAllAssetAdministrationShells/3/1): Returns all Asset Administration Shells


## GetAssetAdministrationShellById (Operation)

[https://admin-shell.io/aas/API/GetAssetAdministrationShellById/3/1](https://admin-shell.io/aas/API/GetAssetAdministrationShellById/3/1): Returns a specific Asset Administration Shell


## GetAllAssetAdministrationShellsByAssetId (Operation)

[https://admin-shell.io/aas/API/GetAllAssetAdministrationShellsByAssetId/3/1](https://admin-shell.io/aas/API/GetAllAssetAdministrationShellsByAssetId/3/1): Returns all Asset Administration Shells that are linked to a globally unique asset identifier or to specific asset ids.


## GetAllAssetAdministrationShellsByIdShort (Operation)

[https://admin-shell.io/aas/API/GetAllAssetAdministrationShellsByIdShort/3/1](https://admin-shell.io/aas/API/GetAllAssetAdministrationShellsByIdShort/3/1):
Returns all Asset Administration Shells with a specific idShort


## PostAssetAdministrationShell (Operation)

[https://admin-shell.io/aas/API/PostAssetAdministrationShell/3/1](https://admin-shell.io/aas/API/PostAssetAdministrationShell/3/1): Creates a new Asset Administration Shell.


## PutAssetAdministrationShellById (Operation)

[https://admin-shell.io/aas/API/PutAssetAdministrationShellById/3/1](https://admin-shell.io/aas/API/PutAssetAdministrationShellById/3/1): Updates an existing Asset Administration Shell


## DeleteAssetAdministrationShellById (Operation)

[https://admin-shell.io/aas/API/DeleteAssetAdministrationShellById/3/1](https://admin-shell.io/aas/API/DeleteAssetAdministrationShellById/3/1): Deletes an Asset Administration Shell


## GetAllSubmodels (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodels/3/1](https://admin-shell.io/aas/API/GetAllSubmodels/3/1): Returns all Submodels


## GetSubmodelById (Operation)

[https://admin-shell.io/aas/API/GetSubmodelById/3/1](https://admin-shell.io/aas/API/GetSubmodelById/3/1): Returns a specific Submodel


## GetAllSubmodelsBySemanticId (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodelsBySemanticId/3/1](https://admin-shell.io/aas/API/GetAllSubmodelsBySemanticId/3/1): Returns all Submodels with a specific SemanticId


## GetAllSubmodelsByIdShort (Operation)

[https://admin-shell.io/aas/API/GetAllSubmodelsByIdShort/3/1](https://admin-shell.io/aas/API/GetAllSubmodelsByIdShort/3/1): Returns all Submodels with a specific idShort


## PostSubmodel (Operation)

[https://admin-shell.io/aas/API/PostSubmodel/3/1](https://admin-shell.io/aas/API/PostSubmodel/3/1): Creates a new Submodel.


## PutSubmodelById (Operation)

[https://admin-shell.io/aas/API/PutSubmodelById/3/1](https://admin-shell.io/aas/API/PutSubmodelById/3/1): Updates an existing Submodel


## DeleteSubmodelById (Operation)

[https://admin-shell.io/aas/API/DeleteSubmodelById/3/1](https://admin-shell.io/aas/API/DeleteSubmodelById/3/1): Deletes a Submodel


## GetAllConceptDescriptions (Operation)

[https://admin-shell.io/aas/API/GetAllConceptDescriptions/3/1](https://admin-shell.io/aas/API/GetAllConceptDescriptions/3/1): Returns all Concept Descriptions


## GetConceptDescriptionById (Operation)

[https://admin-shell.io/aas/API/GetConceptDescriptionById/3/1](https://admin-shell.io/aas/API/GetConceptDescriptionById/3/1): Returns a specific Concept Description


## GetAllConceptDescriptionsByIdShort (Operation)

[https://admin-shell.io/aas/API/GetAllConceptDescriptionsByIdShort/3/1](https://admin-shell.io/aas/API/GetAllConceptDescriptionsByIdShort/3/1): Returns all Concept Descriptions with a specific idShort


## GetAllConceptDescriptionsByIsCaseOf (Operation)

[https://admin-shell.io/aas/API/GetAllConceptDescriptionsByIsCaseOf/3/1](https://admin-shell.io/aas/API/GetAllConceptDescriptionsByIsCaseOf/3/1): Returns all Concept Descriptions with a specific IsCaseOf-reference


## GetAllConceptDescriptionsByDataSpecificationReference (Operation)

[https://admin-shell.io/aas/API/GetAllConceptDescriptionsByDataSpecificationReference/3/1](https://admin-shell.io/aas/API/GetAllConceptDescriptionsByDataSpecificationReference/3/1): Returns all Concept Descriptions with a specific dataSpecification reference


## PostConceptDescription (Operation)

[https://admin-shell.io/aas/API/PostConceptDescription/3/1](https://admin-shell.io/aas/API/PostConceptDescription/3/1): Creates a new Concept Description.


## PutConceptDescriptionById (Operation)

[https://admin-shell.io/aas/API/PutConceptDescriptionById/3/1](https://admin-shell.io/aas/API/PutConceptDescriptionById/3/1): Updates an existing Concept Description


## DeleteConceptDescriptionById (Operation)

[https://admin-shell.io/aas/API/DeleteConceptDescriptionById/3/1](https://admin-shell.io/aas/API/DeleteConceptDescriptionById/3/1): Deletes a Concept Description


## GetAllAssetAdministrationShellIdsByAssetLink (Operation)

[https://admin-shell.io/aas/API/GetAllAssetAdministrationShellIdsByAssetLink/3/1](https://admin-shell.io/aas/API/GetAllAssetAdministrationShellIdsByAssetLink/3/1): Returns a list of Asset Administration Shell ids based on Asset identifier key-value-pairs


## GetAllAssetLinksById (Operation)

[https://admin-shell.io/aas/API/GetAllAssetLinksById/3/1](https://admin-shell.io/aas/API/GetAllAssetLinksById/3/1): Returns a list of Asset identifier key-value-pairs based on an given Asset Administration Shell id


## PostAllAssetLinksById (Operation)

[https://admin-shell.io/aas/API/PostAllAssetLinksById/3/1](https://admin-shell.io/aas/API/PostAllAssetLinksById/3/1): Creates or updates all Asset identifier key-value-pairs linked to an Asset Administration Shell to edit discoverable content


## DeleteAllAssetLinksById (Operation)

[https://admin-shell.io/aas/API/DeleteAllAssetLinksById/3/1](https://admin-shell.io/aas/API/DeleteAllAssetLinksById/3/1): Deletes all Asset identifier key-value-pair linked to an Asset Administration Shell

##  SearchAllAssetAdministrationShellIdsByAssetLink (Operation)

[https://admin-shell.io/aas/API/SearchAllAssetAdministrationShellIdsByAssetLink/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#SearchAllAssetAdministrationShellIdsByAssetLink): Returns a list of Asset Administration Shell IDs linked to specific asset identifiers or the global asset ID

##  QueryAssetAdministrationShells (Operation)

[https://admin-shell.io/aas/API/QueryAssetAdministrationShells/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#QueryAssetAdministrationShells): Returns all Asset Administration Shells that conform to a certain input query.

##  QuerySubmodels (Operation)

[https://admin-shell.io/aas/API/QuerySubmodels/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#QuerySubmodels): Returns all Submodels that conform to a certain input query.
##  QueryAssetAdministrationShellDescriptors (Operation)

[https://admin-shell.io/aas/API/QueryAssetAdministrationShellDescriptors/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#QueryAssetAdministrationShellDescriptors): Returns all Asset Administration Shell Descriptors that conform to a certain input query.

##  QuerySubmodelDescriptors (Operation)

[https://admin-shell.io/aas/API/QuerySubmodelDescriptors/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#QuerySubmodelDescriptors): Returns all Submodel Descriptors that conform to a certain input query.

##  QueryConceptDescriptions(Operation)
 
[https://admin-shell.io/aas/API/QueryConceptDescriptions/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#QueryConceptDescriptions): Returns a list of Concept Descriptions based on an input query.

## CreateBulkAssetAdministrationShellDescriptors (Operation)

[https://admin-shell.io/aas/API/CreateBulkAssetAdministrationShellDescriptors/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#CreateBulkAssetAdministrationShellDescriptors): Creates multiple new Asset Administration Shell Descriptors, i.e., registers multiple Asset Administration Shells


## PutBulkAssetAdministrationShellDescriptorsById (Operation)

[https://admin-shell.io/aas/API/PutBulkAssetAdministrationShellDescriptorsById/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#PutBulkAssetAdministrationShellDescriptorsById): Updates multiple existing Asset Administration Shell Descriptors or creates them if they do not exist


## DeleteBulkAssetAdministrationShellDescriptorsById (Operation)

[https://admin-shell.io/aas/API/DeleteBulkAssetAdministrationShellDescriptorsById/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#DeleteBulkAssetAdministrationShellDescriptorsById): Deletes multiple Asset Administration Shell Descriptors, i.e., de-registers multiple Asset Administration Shells

## PostBulkSubmodelDescriptors (Operation)

[https://admin-shell.io/aas/API/PostBulkSubmodelDescriptors/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#PostBulkSubmodelDescriptors): Creates one or more new submodel descriptors, i.e., registers several submodels

## Bulk (Operation)

[https://admin-shell.io/aas/API/CreateBulkAssetAdministrationShellDescriptors/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#CreateBulkAssetAdministrationShellDescriptors): Creates multiple new Asset Administration Shell Descriptors, i.e., registers multiple Asset Administration Shells

## PutBulkSubmodelDescriptorsById (Operation)

[https://admin-shell.io/aas/API/PutBulkSubmodelDescriptorsById/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#PutBulkSubmodelDescriptorsById): Replaces one or more existing submodel descriptors, i.e., replaces registration information of several submodels

## DeleteBulkSubmodelDescriptorsById (Operation)

[https://admin-shell.io/aas/API/DeleteBulkSubmodelDescriptorsById/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces.html#DeleteBulkSubmodelDescriptorsById): Deletes one or more submodel descriptors, i.e., de-registers several submodels


##############
## CLASSES ###
##############

## Descriptor (Class)

[https://admin-shell.io/aas/API/DataTypes/Descriptor/3/1](https://admin-shell.io/aas/API/DataTypes/Descriptor/3/1): The self-describing information of a network resource.


## AssetAdministrationShellDescriptor (Class)

[https://admin-shell.io/aas/API/DataTypes/AssetAdministrationShellDescriptor/3/1](https://admin-shell.io/aas/API/DataTypes/AssetAdministrationShellDescriptor/3/1): Descriptor of an Asset Administration Shell


## SubmodelDescriptor (Class)

[https://admin-shell.io/aas/API/DataTypes/SubmodelDescriptor/3/1](https://admin-shell.io/aas/API/DataTypes/SubmodelDescriptor/3/1): A descriptor of a submodel


## Endpoint (Class)

[https://admin-shell.io/aas/API/DataTypes/Endpoint/3/1](https://admin-shell.io/aas/API/DataTypes/Endpoint/3/1): The endpoint description of a network resource


## ProtocolInformation (Class)

[https://admin-shell.io/aas/API/DataTypes/ProtocolInformation/3/1](https://admin-shell.io/aas/API/DataTypes/ProtocolInformation/3/1): The protocol information of a network resource endpoint


## Result (Class)

[https://admin-shell.io/aas/API/DataTypes/Result/3/1](https://admin-shell.io/aas/API/DataTypes/Result/3/1): The result object


## Message (Class)

[https://admin-shell.io/aas/API/DataTypes/Message/3/1](https://admin-shell.io/aas/API/DataTypes/Message/3/1): A message containing more information for the requester about a certain happening in the backend.


## MessageTypeEnum (Enumeration)

[https://admin-shell.io/aas/API/DataTypes/MessageTypeEnum/3/1](https://admin-shell.io/aas/API/DataTypes/MessageTypeEnum/3/1): The message type


## OperationRequest (Class)

[https://admin-shell.io/aas/API/DataTypes/OperationRequest/3/1](https://admin-shell.io/aas/API/DataTypes/OperationRequest/3/1): The operation request object


## OperationResult (Class)

[https://admin-shell.io/aas/API/DataTypes/OperationResult/3/1](https://admin-shell.io/aas/API/DataTypes/OperationResult/3/1): The operation’s invocation result object


## ExecutionState (Class)

[https://admin-shell.io/aas/API/DataTypes/ExecutionState/3/1](https://admin-shell.io/aas/API/DataTypes/ExecutionState/3/1): The operation’s invocation result state


## OperationHandle (Class)

[https://admin-shell.io/aas/API/DataTypes/OperationHandle/3/1](https://admin-shell.io/aas/API/DataTypes/OperationHandle/3/1): The returned handle of an operation’s asynchronous invocation used to request the current state of the operation’s execution.


## AssetLink (Class)

[https://admin-shell.io/aas/API/DataTypes/AssetLink/3/1](https://industrialdigitaltwin.io/aas-specifications/IDTA-01002/v3.1/specification/interfaces-payload.html#AssetLink): The returned handle of an operation’s asynchronous invocation used to request the current state of the operation’s execution.

## Contact

The entries of this sub-namespace have been created by the Workstream "Specification of the Asset Administration Shell" in the IDTA Working Group 'Open Technology'.
Contact via a [web form](https://industrialdigitaltwin.org/en/contact).


