# AAS (Asset Administration Shell)

This is the sub-namespace resevered for the Asset Administration Shell Metamodel. 

## Introduction

The Metamodel itself is defined in the 'Details of the Asset Administration Shell - Part 1'. Only classes, attributes and named entities used in this model are allowed in this sub-namespace. The Metamodel is the core resource for the structure of the Asset Administration Shell and provides the frame for all further specifications. The following entities are defined in the Metamodel but also serve as an example how to use the 'Asset Administration Shell Identifiers' in general.

## Status: `Accepted`
The sub-namespace AAS and its identifiers have been accepted by the Coordination Board.



## AccessControl
 Access Control defines the local access control policy administration point. Access Control has the major task to define the access permission rules.

 [http://admin-shell.io/aas/2/0/AccessControl](http://admin-shell.io/aas/2/0/AccessControl) The AccessControl class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControl/accessPermissionRule
 Access permission rules of the AAS describing the rights assigned to (already authenticated) subjects to access elements of the AAS.

 [http://admin-shell.io/aas/2/0/AccessControl/accessPermissionRule](http://admin-shell.io/aas/2/0/AccessControl/accessPermissionRule) The attribute accessPermissionRule of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControl/defaultEnvironmentAttributes
 Reference to a submodel defining default environment attributes, i.e. attributes that are not describing the asset itself. The submodel is of kind=Type. At the same type the values of these environment attributes need to be accessible when evaluating the access permission rules. This is realized as a policy information point.

 [http://admin-shell.io/aas/2/0/AccessControl/defaultEnvironmentAttributes](http://admin-shell.io/aas/2/0/AccessControl/defaultEnvironmentAttributes) The attribute defaultEnvironmentAttributes of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControl/defaultPermissions
 Reference to a submodel defining the default permissions for the AAS.

 [http://admin-shell.io/aas/2/0/AccessControl/defaultPermissions](http://admin-shell.io/aas/2/0/AccessControl/defaultPermissions) The attribute defaultPermissions of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControl/defaultSubjectAttributes
 Reference to a submodel defining the default subjects attributes for the AAS that can be used to describe access permission rules.

 [http://admin-shell.io/aas/2/0/AccessControl/defaultSubjectAttributes](http://admin-shell.io/aas/2/0/AccessControl/defaultSubjectAttributes) The attribute defaultSubjectAttributes of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControl/selectableEnvironmentAttributes
 Reference to a submodel defining which environment attributes can be accessed via the permission rules defined for the AAS, i.e. attributes that are not describing the asset itself. Default: reference to the submodel referenced via defaultEnvironmentAttributes

 [http://admin-shell.io/aas/2/0/AccessControl/selectableEnvironmentAttributes](http://admin-shell.io/aas/2/0/AccessControl/selectableEnvironmentAttributes) The attribute selectableEnvironmentAttributes of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControl/selectablePermissions
 Reference to a submodel defining which permissions can be assigned to the subjects.

 [http://admin-shell.io/aas/2/0/AccessControl/selectablePermissions](http://admin-shell.io/aas/2/0/AccessControl/selectablePermissions) The attribute selectablePermissions of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControl/selectableSubjectAttributes
 Reference to a submodel defining the authenticated subjects that are configured for the AAS. They are selectable by the access permission rules to assign permissions to the subjects.

 [http://admin-shell.io/aas/2/0/AccessControl/selectableSubjectAttributes](http://admin-shell.io/aas/2/0/AccessControl/selectableSubjectAttributes) The attribute selectableSubjectAttributes of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControlPolicyPoints
 Container for access control policy points.

 [http://admin-shell.io/aas/2/0/AccessControlPolicyPoints](http://admin-shell.io/aas/2/0/AccessControlPolicyPoints) The AccessControlPolicyPoints class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControlPolicyPoints/policyAdministrationPoint
 The access control administration policy point of the AAS.

 [http://admin-shell.io/aas/2/0/AccessControlPolicyPoints/policyAdministrationPoint](http://admin-shell.io/aas/2/0/AccessControlPolicyPoints/policyAdministrationPoint) The attribute policyAdministrationPoint of the AccessControlPolicyPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControlPolicyPoints/policyDecisionPoint
 The access control policy decision point of the AAS.

 [http://admin-shell.io/aas/2/0/AccessControlPolicyPoints/policyDecisionPoint](http://admin-shell.io/aas/2/0/AccessControlPolicyPoints/policyDecisionPoint) The attribute policyDecisionPoint of the AccessControlPolicyPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControlPolicyPoints/policyEnforcementPoint
 The access control policy enforcement point of the AAS.

 [http://admin-shell.io/aas/2/0/AccessControlPolicyPoints/policyEnforcementPoint](http://admin-shell.io/aas/2/0/AccessControlPolicyPoints/policyEnforcementPoint) The attribute policyEnforcementPoint of the AccessControlPolicyPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessControlPolicyPoints/policyInformationPoints
 The access control policy information points of the AAS.

 [http://admin-shell.io/aas/2/0/AccessControlPolicyPoints/policyInformationPoints](http://admin-shell.io/aas/2/0/AccessControlPolicyPoints/policyInformationPoints) The attribute policyInformationPoints of the AccessControlPolicyPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessPermissionRule
 Table that defines access permissions per authenticated subject for a set of objects (referable elements).

 [http://admin-shell.io/aas/2/0/AccessPermissionRule](http://admin-shell.io/aas/2/0/AccessPermissionRule) The AccessPermissionRule class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## AccessPermissionRule/permissionsPerObject
 Set of object-permission pairs that define the permissions per object within the access permission rule.

 [http://admin-shell.io/aas/2/0/AccessPermissionRule/permissionsPerObject](http://admin-shell.io/aas/2/0/AccessPermissionRule/permissionsPerObject) The attribute permissionsPerObject of the AccessPermissionRule class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AccessPermissionRule/targetSubjectAttributes
 Target subject attributes that need to be fulfilled by the accessing subject to get the permissions defined by this rule.

 [http://admin-shell.io/aas/2/0/AccessPermissionRule/targetSubjectAttributes](http://admin-shell.io/aas/2/0/AccessPermissionRule/targetSubjectAttributes) The attribute targetSubjectAttributes of the AccessPermissionRule class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AdministrativeInformation
 Every Identifiable may have administrative information. Administrative information includes for example  Information about the version of the element  Information about who created or who made the last change to the element  Information about the languages available in case the element contains text, for translating purposed also themmaster or default language may be definedIn the first version of the AAS metamodel only version information as defined by IEC 61360 is defined. In later versions additional attributes may be added.

 [http://admin-shell.io/aas/2/0/AdministrativeInformation](http://admin-shell.io/aas/2/0/AdministrativeInformation) The AdministrativeInformation class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## AdministrativeInformation/revision
 Revision of the element. Constraint AASd-005: A revision requires a version. This means, if there is no version there is no revision neither.

 [http://admin-shell.io/aas/2/0/AdministrativeInformation/revision](http://admin-shell.io/aas/2/0/AdministrativeInformation/revision) The attribute revision of the AdministrativeInformation class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AdministrativeInformation/version
 Version of the element.

 [http://admin-shell.io/aas/2/0/AdministrativeInformation/version](http://admin-shell.io/aas/2/0/AdministrativeInformation/version) The attribute version of the AdministrativeInformation class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AnnotatedRelationshipElement
 An annotated relationship element is an relationship element that can be annotated with additional data elements.

 [http://admin-shell.io/aas/2/0/AnnotatedRelationshipElement](http://admin-shell.io/aas/2/0/AnnotatedRelationshipElement) The AnnotatedRelationshipElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## AnnotatedRelationshipElement/annotation
 Annotations that hold for the relationships between the two elements.

 [http://admin-shell.io/aas/2/0/AnnotatedRelationshipElement/annotation](http://admin-shell.io/aas/2/0/AnnotatedRelationshipElement/annotation) The attribute annotation of the AnnotatedRelationshipElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Asset
 An Asset describes meta data of an asset that is represented by an AAS. The asset may either represent an asset type or an asset instance. The asset has a globally unique identifier plus – if needed – additional domain specific (proprietary) identifiers.

 [http://admin-shell.io/aas/2/0/Asset](http://admin-shell.io/aas/2/0/Asset) The Asset class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Asset/assetIdentificationModel
 A reference to a Submodel that defines the handling of additional domain specific (proprietary) Identifiers for the asset like e.g. serial number etc.

[http://admin-shell.io/aas/2/0/Asset/assetIdentificationModel](http://admin-shell.io/aas/2/0/Asset/assetIdentificationModel) The attribute assetIdentificationModel of the Asset class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Asset/billOfMaterial
 Bill of material of the Asset represented by a submodel of the same AAS. This submodel contains a set of entities describing the material used to compose the composite I4.0 Component.

 [http://admin-shell.io/aas/2/0/Asset/billOfMaterial](http://admin-shell.io/aas/2/0/Asset/billOfMaterial) The attribute billOfMaterial of the Asset class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Asset/kind
 Denotes whether the Asset of of kind 'Type' or 'Instance'.

 [http://admin-shell.io/aas/2/0/Asset/kind](http://admin-shell.io/aas/2/0/Asset/kind) The attribute assetKind of the Asset class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## AssetAdministrationShell
 Describes the Administration Shell for Assets, Products, Components, e.g. Machines

[http://admin-shell.io/aas/2/0/AssetAdministrationShell](http://admin-shell.io/aas/2/0/AssetAdministrationShell) The AssetAdministrationShell class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/asset

The asset the AAS is representing.

[http://admin-shell.io/aas/2/0/AssetAdministrationShell/asset](http://admin-shell.io/aas/2/0/AssetAdministrationShell/asset) The attribute asset of the AssetAdministrationShell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/conceptDictionary
 An AAS max have one or more concept dictionaries assigned to it. The concept dictionaries typically contain only descriptions for elements that are also used within the AAS (via HasSemantics).

 [http://admin-shell.io/aas/2/0/AssetAdministrationShell/conceptDictionary](http://admin-shell.io/aas/2/0/AssetAdministrationShell/conceptDictionary) The attribute conceptDictionary of the AssetAdministrationShell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/derivedFrom
 This relation connects instances of AAS with their respective types. Refer to Asset Kind for further information of instance and type kinds.

 [http://admin-shell.io/aas/2/0/AssetAdministrationShell/derivedFrom](http://admin-shell.io/aas/2/0/AssetAdministrationShell/derivedFrom) The attribute derivedFrom of the AssetAdministrationShell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/security
 Definition of the security relevant aspects of the AAS.

 [http://admin-shell.io/aas/2/0/AssetAdministrationShell/security](http://admin-shell.io/aas/2/0/AssetAdministrationShell/security) The attribute security of the AssetAdministrationShell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/submodel
 Points from the Admin Shell to the Submodels that describe the Admin Shell of a given Asset

 [http://admin-shell.io/aas/2/0/AssetAdministrationShell/submodel](http://admin-shell.io/aas/2/0/AssetAdministrationShell/submodel) The attribute submodel of the AssetAdministrationShell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetAdministrationShell/view
 Points to the differents views associated to the Administration Shell via the Submodels.

 [http://admin-shell.io/aas/2/0/AssetAdministrationShell/view](http://admin-shell.io/aas/2/0/AssetAdministrationShell/view) The attribute view of the AssetAdministrationShell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetKind
 Enumeration for denoting whether an element is a type or an instance.

 [http://admin-shell.io/aas/2/0/AssetKind](http://admin-shell.io/aas/2/0/AssetKind) The AssetKind class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## AssetKind/ASSET_INSTANCE
 Concrete, clearly identifiable component of a certain type.

 [http://admin-shell.io/aas/2/0/AssetKind/ASSET_INSTANCE](http://admin-shell.io/aas/2/0/AssetKind/ASSET_INSTANCE) The NamedIndividual ASSET_INSTANCE of the AssetKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## AssetKind/ASSET_TYPE
 hardware or software element which specifies the common attributes shared by all instances of the type.

 [http://admin-shell.io/aas/2/0/AssetKind/ASSET_TYPE](http://admin-shell.io/aas/2/0/AssetKind/ASSET_TYPE) The NamedIndividual ASSET_TYPE of the AssetKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## BasicEvent
A basic event.

 [http://admin-shell.io/aas/2/0/BasicEvent](http://admin-shell.io/aas/2/0/BasicEvent) The BasicEvent class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## BasicEvent/observed
 Reference to the data or other elements that are being observed.

 [http://admin-shell.io/aas/2/0/BasicEvent/observed](http://admin-shell.io/aas/2/0/BasicEvent/observed) The attribute observed of the BasicEvent class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Blob
 A BLOB is a data element that represents a file that is contained with its source code in the value attribute.

 [http://admin-shell.io/aas/2/0/Blob](http://admin-shell.io/aas/2/0/Blob) The Blob class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## BlobCertificate
 Certificate provided as BLOB.

 [http://admin-shell.io/aas/2/0/BlobCertificate](http://admin-shell.io/aas/2/0/BlobCertificate) The BlobCertificate class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## BlobCertificate/blobCertificate
 Certificate as BLOB.

 [http://admin-shell.io/aas/2/0/BlobCertificate/blobCertificate](http://admin-shell.io/aas/2/0/BlobCertificate/blobCertificate) The attribute blobCertificate of the BlobCertificate class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## BlobCertificate/containedExtension
 Extensions contained in the certificate.

 [http://admin-shell.io/aas/2/0/BlobCertificate/containedExtension](http://admin-shell.io/aas/2/0/BlobCertificate/containedExtension) The attribute containedExtension of the BlobCertificate class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## BlobCertificate/lastCertificate
 Denotes whether this certificate is the certificated that fast added last.

 [http://admin-shell.io/aas/2/0/BlobCertificate/lastCertificate](http://admin-shell.io/aas/2/0/BlobCertificate/lastCertificate) The attribute lastCertificate of the BlobCertificate class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Capability
 A capability is the implementation-independent description of the potential of an asset to achieve a certain effect in the physical or virtual world.

 [http://admin-shell.io/aas/2/0/Capability](http://admin-shell.io/aas/2/0/Capability) The Capability class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Certificate
 A technical certificate proofing the identity through cryptographic measures.

 [http://admin-shell.io/aas/2/0/Certificate](http://admin-shell.io/aas/2/0/Certificate) The Certificate class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## ConceptDescription
 The semantics of a property or other elements that may have a semantic description is defined by a concept description. The description of the concept should follow a standardized schema (realized as data specification template).

 [http://admin-shell.io/aas/2/0/ConceptDescription](http://admin-shell.io/aas/2/0/ConceptDescription) The ConceptDescription class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## ConceptDescription/content


[http://admin-shell.io/aas/2/0/ConceptDescription/content](http://admin-shell.io/aas/2/0/ConceptDescription/content) The attribute content of the ConceptDescription class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ConceptDescription/isCaseOf
 Global reference to an external definition the concept is compatible to or was derived from.

 [http://admin-shell.io/aas/2/0/ConceptDescription/isCaseOf](http://admin-shell.io/aas/2/0/ConceptDescription/isCaseOf) The attribute isCaseOf of the ConceptDescription class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ConceptDictionary
 A dictionary contains elements that can be reused. The concept dictionary contains concept descriptions. Typically a concept description dictionary of an AAS contains only concept descriptions of elements used within submodels of the AAS.

 [http://admin-shell.io/aas/2/0/ConceptDictionary](http://admin-shell.io/aas/2/0/ConceptDictionary) The ConceptDictionary class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## ConceptDictionary/conceptDescription
 The semantics of a property or other elements that may have a semantic description is defined by a concept description. The description of the concept should follow a standardized schema (realized as data specification template).

 [http://admin-shell.io/aas/2/0/ConceptDictionary/conceptDescription](http://admin-shell.io/aas/2/0/ConceptDictionary/conceptDescription) The attribute conceptDescription of the ConceptDictionary class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Constraint
 A constraint is used to further qualify an element.

 [http://admin-shell.io/aas/2/0/Constraint](http://admin-shell.io/aas/2/0/Constraint) The Constraint class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## DataElement
 A data element is a submodel element that is not further composed out of other submodel elements. A data element is a submodel element that has a value. The type of value differs for different subtypes of data elements.

 [http://admin-shell.io/aas/2/0/DataElement](http://admin-shell.io/aas/2/0/DataElement) The DataElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## DataSpecification
 Element that can have data specification templates. A template defines the additional attributes an element may or shall have.

 [http://admin-shell.io/aas/2/0/DataSpecification](http://admin-shell.io/aas/2/0/DataSpecification) The DataSpecification class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.


## DataSpecificationContent
DataSpecificationContent contains the additional attributes to be added to the element
instance that references the data specification template and meta information about the template itself.

 [http://admin-shell.io/aas/2/0/DataSpecificationContent](http://admin-shell.io/aas/2/0/DataSpecificationContent) The DataSpecificationContent class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.


## Entity
 An entity is a submodel element that is used to model entities.

 [http://admin-shell.io/aas/2/0/Entity](http://admin-shell.io/aas/2/0/Entity) The Entity class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Entity/entityType
 Describes whether the entity is a co-managed entity or a self-managed entity.

 [http://admin-shell.io/aas/2/0/Entity/entityType](http://admin-shell.io/aas/2/0/Entity/entityType) The attribute entityType of the Entity class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Entity/statement
 Describes statements applicable to the entity by a set of submodel elements, typically with a qualified value.

 [http://admin-shell.io/aas/2/0/Entity/statement](http://admin-shell.io/aas/2/0/Entity/statement) The attribute statement of the Entity class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## EntityType
 Enumeration for denoting whether an entity is a self-managed entity or a co-managed entity.

 [http://admin-shell.io/aas/2/0/EntityType](http://admin-shell.io/aas/2/0/EntityType) The EntityType class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## EntityType/CO_MANAGED_ENTITY
 For co-managed entities there is no separate AAS. Co-managed entities need to be part of a self-managed entity.

 [http://admin-shell.io/aas/2/0/EntityType/CO_MANAGED_ENTITY](http://admin-shell.io/aas/2/0/EntityType/CO_MANAGED_ENTITY) The NamedIndividual CO_MANAGED_ENTITY of the EntityType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## EntityType/SELF_MANAGED_ENTITY
 Self-Managed Entities have their own AAS but can be part of the bill of material of a composite self-managed entity. The asset of an I4.0 Component is a self-managed entity per definition.

 [http://admin-shell.io/aas/2/0/EntityType/SELF_MANAGED_ENTITY](http://admin-shell.io/aas/2/0/EntityType/SELF_MANAGED_ENTITY) The NamedIndividual SELF_MANAGED_ENTITY of the EntityType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Event
 An event.

 [http://admin-shell.io/aas/2/0/Event](http://admin-shell.io/aas/2/0/Event) The Event class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## EventElement
 Defines the necessary information for sending or receiving events.

 [http://admin-shell.io/aas/2/0/EventElement](http://admin-shell.io/aas/2/0/EventElement) The EventElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## EventMessage
 Defines the necessary information of an event instance sent out or received.

 [http://admin-shell.io/aas/2/0/EventMessage](http://admin-shell.io/aas/2/0/EventMessage) The EventMessage class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## File
 A File is a data element that represents a file via its path description.

 [http://admin-shell.io/aas/2/0/File](http://admin-shell.io/aas/2/0/File) The File class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## File/value

todo

## File/mimeType

todo



## Formula
 

 [http://admin-shell.io/aas/2/0/Formula](http://admin-shell.io/aas/2/0/Formula) The Formula class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Formula/dependsOn
 A formula may depend on referable or even external global elements - assumed that can be referenced and their value may be evaluated - that are used in the logical expression.

 [http://admin-shell.io/aas/2/0/Formula/dependsOn](http://admin-shell.io/aas/2/0/Formula/dependsOn) The attribute dependsOn of the Formula class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## HasDataSpecification
 Element that can have be extended by using data specification templates. A data specification template defines the additional attributes an element may or shall have. The data specifications used are explicitly specified with their id.

 [http://admin-shell.io/aas/2/0/HasDataSpecification](http://admin-shell.io/aas/2/0/HasDataSpecification) The HasDataSpecification class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## HasDataSpecification/dataSpecification
 Global reference to the data specification template used by the element.

 [http://admin-shell.io/aas/2/0/HasDataSpecification/dataSpecification](http://admin-shell.io/aas/2/0/HasDataSpecification/dataSpecification) The attribute dataSpecification of the HasDataSpecification class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## HasKind
 An element with a kind is an element that can either represent a type or an instance. Default for an element is that it is representing an instance.

 [http://admin-shell.io/aas/2/0/HasKind](http://admin-shell.io/aas/2/0/HasKind) The HasKind class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## HasKind/kind
 ModelingKind of the element: either type or instance.

 [http://admin-shell.io/aas/2/0/HasKind/kind](http://admin-shell.io/aas/2/0/HasKind/kind) The attribute kind of the HasKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## HasSemantics
 Element that can have a semantic definition. Identifier of the semantic definition of the element. It is called semantic id of the element. The semantic id may either reference an external global id or it may reference a referable model element of kind=Type that defines the semantics of the element.

 [http://admin-shell.io/aas/2/0/HasSemantics](http://admin-shell.io/aas/2/0/HasSemantics) The HasSemantics class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## HasSemantics/semanticId
 Points to the Expression Semantic of the Submodels

 [http://admin-shell.io/aas/2/0/HasSemantics/semanticId](http://admin-shell.io/aas/2/0/HasSemantics/semanticId) The attribute semanticId of the HasSemantics class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Identifiable
 An element that has a globally unique identifier.

 [http://admin-shell.io/aas/2/0/Identifiable](http://admin-shell.io/aas/2/0/Identifiable) The Identifiable class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Identifiable/administration
 Administrative information of an identifiable element.

 [http://admin-shell.io/aas/2/0/Identifiable/administration](http://admin-shell.io/aas/2/0/Identifiable/administration) The attribute administration of the Identifiable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Identifiable/identification
 The globally unique identification of the element.

 [http://admin-shell.io/aas/2/0/Identifiable/identification](http://admin-shell.io/aas/2/0/Identifiable/identification) The attribute identification of the Identifiable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## IdentifiableElements
 Enumeration of all identifiable elements within an asset administration shell that are not identifiable

 [http://admin-shell.io/aas/2/0/IdentifiableElements](http://admin-shell.io/aas/2/0/IdentifiableElements) The IdentifiableElements class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## IdentifiableElements/ASSET_ADMINISTRATION_SHELL
 

 [http://admin-shell.io/aas/2/0/IdentifiableElements/ASSET_ADMINISTRATION_SHELL](http://admin-shell.io/aas/2/0/IdentifiableElements/ASSET_ADMINISTRATION_SHELL) The IdentifiableElements ASSET_ADMINISTRATION_SHELL of the IdentifiableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## IdentifiableElements/ASSET
 

 [http://admin-shell.io/aas/2/0/IdentifiableElements/ASSET](http://admin-shell.io/aas/2/0/IdentifiableElements/ASSET) The IdentifiableElements ASSET of the IdentifiableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## IdentifiableElements/CONCEPT_DESCRIPTION
 

 [http://admin-shell.io/aas/2/0/IdentifiableElements/CONCEPT_DESCRIPTION](http://admin-shell.io/aas/2/0/IdentifiableElements/CONCEPT_DESCRIPTION) The IdentifiableElements CONCEPT_DESCRIPTION of the IdentifiableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## IdentifiableElements/SUBMODEL
 

 [http://admin-shell.io/aas/2/0/IdentifiableElements/SUBMODEL](http://admin-shell.io/aas/2/0/IdentifiableElements/SUBMODEL) The IdentifiableElements SUBMODEL of the IdentifiableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Identifier
 Used to uniquely identify an entity by using an identifier.

 [http://admin-shell.io/aas/2/0/Identifier](http://admin-shell.io/aas/2/0/Identifier) The Identifier class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Identifier/id
 A globally unique identifier which might not be a URI. Its type is defined in idType.

 [http://admin-shell.io/aas/2/0/Identifier/id](http://admin-shell.io/aas/2/0/Identifier/id) The attribute id of the Identifier class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Identifier/idType
 Type of the Identifier, e.g. IRI, IRDI etc. The supported Identifier types are defined in the enumeration 'IdentifierType'.

 [http://admin-shell.io/aas/2/0/Identifier/idType](http://admin-shell.io/aas/2/0/Identifier/idType) The attribute idType of the Identifier class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## IdentifierType
 Enumeration of different types of Identifiers for global identification

 [http://admin-shell.io/aas/2/0/IdentifierType](http://admin-shell.io/aas/2/0/IdentifierType) The IdentifierType class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## IdentifierType/CUSTOM
 Custom identifiers like GUIDs (globally unique Identifiers)

 [http://admin-shell.io/aas/2/0/IdentifierType/CUSTOM](http://admin-shell.io/aas/2/0/IdentifierType/CUSTOM) The IdentifierType CUSTOM of the IdentifierType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## IdentifierType/IRDI
 IRDI according to ISO29002-5 as an Identifier scheme for properties and classifications.

 [http://admin-shell.io/aas/2/0/IdentifierType/IRDI](http://admin-shell.io/aas/2/0/IdentifierType/IRDI) The IdentifierType IRDI of the IdentifierType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## IdentifierType/IRI
 IRI. Should only be used if unicode symbols are used that are not allowed in URI.

 [http://admin-shell.io/aas/2/0/IdentifierType/IRI](http://admin-shell.io/aas/2/0/IdentifierType/IRI) The IdentifierType IRI of the IdentifierType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Key
 A key is a reference to an element by its id.

 [http://admin-shell.io/aas/2/0/Key](http://admin-shell.io/aas/2/0/Key) The Key class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Key/index
 The index attribute states the position of each key instance in the sequence of all other related keys.

 [http://admin-shell.io/aas/2/0/Key/index](http://admin-shell.io/aas/2/0/Key/index) The attribute index of the Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Key/idType
 

 [http://admin-shell.io/aas/2/0/Key/idType](http://admin-shell.io/aas/2/0/Key/idType) The attribute idType of the Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Key/local
 Denotes if the key references a model element of the same AAS (=true) or not (=false). In case of local = false the key may reference a model element of another AAS or an entity outside any AAS that has a global unique id.

 [http://admin-shell.io/aas/2/0/Key/local](http://admin-shell.io/aas/2/0/Key/local) The attribute local of the Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Key/type
 

 [http://admin-shell.io/aas/2/0/Key/type](http://admin-shell.io/aas/2/0/Key/type) The attribute type of the Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Key/value

todo


## KeyElements
 Enumeration of different key value types within a key. Contains KeyElements, ReferableElements, and IdentifiableElements.

 [http://admin-shell.io/aas/2/0/KeyElements](http://admin-shell.io/aas/2/0/KeyElements) The KeyElements class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## KeyElements/FRAGMENT_REFERENCE
 

 [http://admin-shell.io/aas/2/0/KeyElements/FRAGMENT_REFERENCE](http://admin-shell.io/aas/2/0/KeyElements/FRAGMENT_REFERENCE) The KeyElements FRAGMENT_REFERENCE of the KeyElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## KeyElements/GLOBAL_REFERENCE
 reference to an element not belonging to an asset administration shell

 [http://admin-shell.io/aas/2/0/KeyElements/GLOBAL_REFERENCE](http://admin-shell.io/aas/2/0/KeyElements/GLOBAL_REFERENCE) The KeyElements GLOBAL_REFERENCE of the KeyElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## KeyType
 Enumeration of different key value types within a key. Contains IdentifierType and LocalKeyType.

 [http://admin-shell.io/aas/2/0/KeyType](http://admin-shell.io/aas/2/0/KeyType) The KeyType class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## LocalKeyType
 Enumeration of different key value types within a key.

 [http://admin-shell.io/aas/2/0/LocalKeyType](http://admin-shell.io/aas/2/0/LocalKeyType) The LocalKeyType class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## LocalKeyType/FRAGMENT_ID_LOCAL_KEY_TYPE
 Identifier of a fragment within a file

 [http://admin-shell.io/aas/2/0/LocalKeyType/FRAGMENT_ID_LOCAL_KEY_TYPE](http://admin-shell.io/aas/2/0/LocalKeyType/FRAGMENT_ID_LOCAL_KEY_TYPE) The LocalKeyType FRAGMENT_ID_LOCAL_KEY_TYPE of the LocalKeyType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## LocalKeyType/IDSHORT_LOCAL_KEY_TYPE
 idShort of a referable element

 [http://admin-shell.io/aas/2/0/LocalKeyType/IDSHORT_LOCAL_KEY_TYPE](http://admin-shell.io/aas/2/0/LocalKeyType/IDSHORT_LOCAL_KEY_TYPE) The LocalKeyType IDSHORT_LOCAL_KEY_TYPE of the LocalKeyType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ModelingKind
 Enumeration for denoting whether an element is a type or an instance.

 [http://admin-shell.io/aas/2/0/ModelingKind](http://admin-shell.io/aas/2/0/ModelingKind) The ModelingKind class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## ModelingKind/INSTANCE
 Concrete, clearly identifiable component of a certain template.

 [http://admin-shell.io/aas/2/0/ModelingKind/INSTANCE](http://admin-shell.io/aas/2/0/ModelingKind/INSTANCE) The NamedIndividual INSTANCE of the ModelingKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ModelingKind/TEMPLATE
 Software element which specifies the common attributes shared by all instances of the template.

 [http://admin-shell.io/aas/2/0/ModelingKind/TEMPLATE](http://admin-shell.io/aas/2/0/ModelingKind/TEMPLATE) The NamedIndividual TEMPLATE of the ModelingKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## MultiLanguageProperty
 A property is a data element that has a multi language value.

 [http://admin-shell.io/aas/2/0/MultiLanguageProperty](http://admin-shell.io/aas/2/0/MultiLanguageProperty) The MultiLanguageProperty class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## ObjectAttributes
 A set of data elements that describe object attributes. These attributes need to refer to a data element within an existing submodel.

 [http://admin-shell.io/aas/2/0/ObjectAttributes](http://admin-shell.io/aas/2/0/ObjectAttributes) The ObjectAttributes class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## ObjectAttributes/objectAttribute
 A data elements that further classifies an object.

 [http://admin-shell.io/aas/2/0/ObjectAttributes/objectAttribute](http://admin-shell.io/aas/2/0/ObjectAttributes/objectAttribute) The attribute objectAttribute of the ObjectAttributes class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Operation
 An operation is a submodel element with input and output variables.

 [http://admin-shell.io/aas/2/0/Operation](http://admin-shell.io/aas/2/0/Operation) The Operation class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Operation/inoutputVariable
Parameter that is input and output of the operation.

[http://admin-shell.io/aas/2/0/Operation/inoutputVariable](http://admin-shell.io/aas/2/0/Operation/inoutputVariable) The attribute inoutputVariable of the Operation class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Operation/inputVariable
Input parameter of the operation.

[http://admin-shell.io/aas/2/0/Operation/inputVariable](http://admin-shell.io/aas/2/0/Operation/inputVariable) The attribute inputVariable of the Operation class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Operation/outputVariable
Output parameter of the operation.

[http://admin-shell.io/aas/2/0/Operation/outputVariable](http://admin-shell.io/aas/2/0/Operation/outputVariable) The attribute outputVariable of the Operation class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## OperationVariable
An operation variable is a submodel element that is used as input or output variable of an operation.

[http://admin-shell.io/aas/2/0/OperationVariable](http://admin-shell.io/aas/2/0/OperationVariable) The OperationVariable class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Permission
 Description of a single permission.

 [http://admin-shell.io/aas/2/0/Permission](http://admin-shell.io/aas/2/0/Permission) The Permission class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Permission/kindOfPermission
 Description of the kind of permission. Possible kind of permission also include the denial of the permission.

 [http://admin-shell.io/aas/2/0/Permission/kindOfPermission](http://admin-shell.io/aas/2/0/Permission/kindOfPermission) The attribute kindOfPermission of the Permission class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Permission/permission
 Reference to a property that defines the semantics of the permission.

 [http://admin-shell.io/aas/2/0/Permission/permission](http://admin-shell.io/aas/2/0/Permission/permission) The attribute permission of the Permission class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PermissionKind
 Enumeration of the kind of permissions that is given to the assignment of a permission to a subject.

 [http://admin-shell.io/aas/2/0/PermissionKind](http://admin-shell.io/aas/2/0/PermissionKind) The PermissionKind class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## PermissionKind/ALLOW
 Allow the permission given to the subject.

 [http://admin-shell.io/aas/2/0/PermissionKind/ALLOW](http://admin-shell.io/aas/2/0/PermissionKind/ALLOW) The PermissionKind ALLOW of the PermissionKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PermissionKind/DENY
 Explicitly deny the permission given to the subject.

 [http://admin-shell.io/aas/2/0/PermissionKind/DENY](http://admin-shell.io/aas/2/0/PermissionKind/DENY) The PermissionKind DENY of the PermissionKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PermissionKind/NOT_APPLICABLE
 The permission is not applicable to the subject.

 [http://admin-shell.io/aas/2/0/PermissionKind/NOT_APPLICABLE](http://admin-shell.io/aas/2/0/PermissionKind/NOT_APPLICABLE) The PermissionKind NOT_APPLICABLE of the PermissionKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PermissionKind/UNDEFINED
 It is undefined whether the permission is allowed, not applicable or denied to the subject.

 [http://admin-shell.io/aas/2/0/PermissionKind/UNDEFINED](http://admin-shell.io/aas/2/0/PermissionKind/UNDEFINED) The PermissionKind UNDEFINED of the PermissionKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PermissionsPerObject
 Table that defines access permissions for a specified object. The object is any referable element in the AAS. Additionally object attributes can be defined that further specify the kind of object the permissions apply to.

 [http://admin-shell.io/aas/2/0/PermissionsPerObject](http://admin-shell.io/aas/2/0/PermissionsPerObject) The PermissionsPerObject class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## PermissionsPerObject/object
 Element to which permission shall be assigned.

 [http://admin-shell.io/aas/2/0/PermissionsPerObject/object](http://admin-shell.io/aas/2/0/PermissionsPerObject/object) The attribute object of the PermissionsPerObject class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PermissionsPerObject/objectPermission
 Permissions assigned to the object. The permissions hold for all subjects as specified in the access permission rule.

 [http://admin-shell.io/aas/2/0/PermissionsPerObject/objectPermission](http://admin-shell.io/aas/2/0/PermissionsPerObject/objectPermission) The attribute objectPermission of the PermissionsPerObject class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PermissionsPerObject/targetObjectAttributes
 Target object attributes that need to be fulfilled so that the access permissions apply to the accessing subject.

 [http://admin-shell.io/aas/2/0/PermissionsPerObject/targetObjectAttributes](http://admin-shell.io/aas/2/0/PermissionsPerObject/targetObjectAttributes) The attribute targetObjectAttributes of the PermissionsPerObject class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PolicyAdministrationPoint
 Definition of a security administration point (PDP).

 [http://admin-shell.io/aas/2/0/PolicyAdministrationPoint](http://admin-shell.io/aas/2/0/PolicyAdministrationPoint) The PolicyAdministrationPoint class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## PolicyAdministrationPoint/externalAccessControl
 Endpoint to an external access control defining a policy administration point to be used by the AAS.

 [http://admin-shell.io/aas/2/0/PolicyAdministrationPoint/externalAccessControl](http://admin-shell.io/aas/2/0/PolicyAdministrationPoint/externalAccessControl) The attribute externalAccessControl of the PolicyAdministrationPoint class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PolicyAdministrationPoint/localAccessControl
 The policy administration point of access control as realized by the AAS itself.

 [http://admin-shell.io/aas/2/0/PolicyAdministrationPoint/localAccessControl](http://admin-shell.io/aas/2/0/PolicyAdministrationPoint/localAccessControl) The attribute localAccessControl of the PolicyAdministrationPoint class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PolicyDecisionPoint
 Defines the security policy decision points (PDP). 

 [http://admin-shell.io/aas/2/0/PolicyDecisionPoint](http://admin-shell.io/aas/2/0/PolicyDecisionPoint) The PolicyDecisionPoint class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## PolicyDecisionPoint/externalPolicyDecisionPoint
 If externalPolicyDecisionPoints True then Endpoints to external available decision points taking into consideration for access control for the AAS need to be configured.

 [http://admin-shell.io/aas/2/0/PolicyDecisionPointPoint/externalPolicyDecisionPoint](http://admin-shell.io/aas/2/0/PolicyDecisionPoint/externalPolicyDecisionPoint) The attribute externalPolicyDecisionPoint of the PolicyDecisionPoint class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PolicyEnforcementPoint
 Defines the security policy enforcement points (PEP).

 [http://admin-shell.io/aas/2/0/PolicyEnforcementPoint](http://admin-shell.io/aas/2/0/PolicyEnforcementPoint) The PolicyEnforcementPoint class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## PolicyEnforcementPoint/externalPolicyEnforcementPoint
 If externalPolicyDecisionPoints True then Endpoints to external available decision points taking into consideration for access control for the AAS need to be configured.

 [http://admin-shell.io/aas/2/0/PolicyEnforcementPoint/externalPolicyEnforcementPoint](http://admin-shell.io/aas/2/0/PolicyEnforcementPoint/externalPolicyEnforcementPoint) The attribute externalPolicyEnforcementPoint of the PolicyEnforcementPoint class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PolicyInformationPoints
 Defines the security policy information points (PIP). Serves as the retrieval source of attributes, or the data required for policy evaluation to provide the information needed by the policy decision point to make the decisions.

 [http://admin-shell.io/aas/2/0/PolicyInformationPoints](http://admin-shell.io/aas/2/0/PolicyInformationPoints) The PolicyInformationPoints class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## PolicyInformationPoints/externalInformationPoint
 Endpoints to external available information points taking into consideration for access control for the AAS.

 [http://admin-shell.io/aas/2/0/PolicyInformationPoints/externalInformationPoint](http://admin-shell.io/aas/2/0/PolicyInformationPoints/externalInformationPoint) The attribute externalInformationPoint of the PolicyInformationPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## PolicyInformationPoints/internalInformationPoint
 References to submodels defining information used by security access permission rules.

 [http://admin-shell.io/aas/2/0/PolicyInformationPoints/internalInformationPoint](http://admin-shell.io/aas/2/0/PolicyInformationPoints/internalInformationPoint) The attribute internalInformationPoint of the PolicyInformationPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Property
 A property is a data element that has a single value.

 [http://admin-shell.io/aas/2/0/Property](http://admin-shell.io/aas/2/0/Property) The Property class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Property/category
The following categories are defined for properties and multi-language properties: CONSTANT, PARAMETER, and VARIABLE.

[http://admin-shell.io/aas/2/0/Property/category](http://admin-shell.io/aas/2/0/Property/category) The attribute category of the Property class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.



## Property/value
The value of the property instance.

 [http://admin-shell.io/aas/2/0/Property/value](http://admin-shell.io/aas/2/0/Property/value) The attribute value of the Property class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.


## Property/valueId
 Reference to the global unqiue id of a coded value.

 [http://admin-shell.io/aas/2/0/Property/valueId](http://admin-shell.io/aas/2/0/Property/valueId) The attribute valueId of the Property class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Qualifiable
 Additional qualification of a qualifiable element.

 [http://admin-shell.io/aas/2/0/Qualifiable](http://admin-shell.io/aas/2/0/Qualifiable) The Qualifiable class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Qualifiable/qualifier
 Additional qualification of a qualifiable element.

 [http://admin-shell.io/aas/2/0/Qualifiable/qualifier](http://admin-shell.io/aas/2/0/Qualifiable/qualifier) The attribute qualifier of the Qualifiable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Qualifier
 A qualifier is a type-value pair that makes additional statements w.r.t. the value of the element.

 [http://admin-shell.io/aas/2/0/Qualifier](http://admin-shell.io/aas/2/0/Qualifier) The Qualifier class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Qualifier/qualifierType
 The qualifier type describes the type of the qualifier that is applied to the element.

 [http://admin-shell.io/aas/2/0/Qualifier/qualifierType](http://admin-shell.io/aas/2/0/Qualifier/qualifierType) The attribute qualifierType of the Qualifier class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Qualifier/qualifierValue
 The qualifier value is the value of the qualifier.

 [http://admin-shell.io/aas/2/0/Qualifier/qualifierValue](http://admin-shell.io/aas/2/0/Qualifier/qualifierValue) The attribute qualifierValue of the Qualifier class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Qualifier/qualifierValueId
 Reference to the global unqiue id of a coded value.

 [http://admin-shell.io/aas/2/0/Qualifier/qualifierValueId](http://admin-shell.io/aas/2/0/Qualifier/qualifierValueId) The attribute qualifierValueId of the Qualifier class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Range
 An element that is referable by its idShort. This id is not globally unique. This id is unique within the name space of the element.

 [http://admin-shell.io/aas/2/0/Range](http://admin-shell.io/aas/2/0/Range) The Range class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Range/max
 The maximum value of the range.

 [http://admin-shell.io/aas/2/0/Range/max](http://admin-shell.io/aas/2/0/Range/max) The attribute max of the Range class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Range/min
 The minimum value of the range.

 [http://admin-shell.io/aas/2/0/Range/min](http://admin-shell.io/aas/2/0/Range/min) The attribute min of the Range class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Referable
 An element that is referable by its idShort. This id is not globally unique. This id is unique within the name space of the element.

 [http://admin-shell.io/aas/2/0/Referable](http://admin-shell.io/aas/2/0/Referable) The Referable class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Referable/category
 The category is a value that gives further meta information w.r.t. to the class of the element. It affects the expected existence of attributes and the applicability of constraints.

 [http://admin-shell.io/aas/2/0/Referable/category](http://admin-shell.io/aas/2/0/Referable/category) The attribute category of the Referable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Referable/description
 Description or comments on the element. The description can be provided in several languages.

 [http://admin-shell.io/aas/2/0/Referable/description](http://admin-shell.io/aas/2/0/Referable/description) The attribute description of the Referable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Referable/idShort
 Identifying string of the element within its name space.

 [http://admin-shell.io/aas/2/0/Referable/idShort](http://admin-shell.io/aas/2/0/Referable/idShort) The attribute idShort of the Referable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Referable/parent
 Reference to the next referable parent element of the element. Constraint AASd-004: Add parent in case of non-identifiable elements.

 [http://admin-shell.io/aas/2/0/Referable/parent](http://admin-shell.io/aas/2/0/Referable/parent) The attribute parent of the Referable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements
 Enumeration of all referable elements within an asset administration shell. Contains IdentifiableElements

 [http://admin-shell.io/aas/2/0/ReferableElements](http://admin-shell.io/aas/2/0/ReferableElements) The ReferableElements class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/ACCESS_PERMISSION_RULE
 

 [http://admin-shell.io/aas/2/0/ReferableElements/ACCESS_PERMISSION_RULE](http://admin-shell.io/aas/2/0/ReferableElements/ACCESS_PERMISSION_RULE) The ReferableElements ACCESS_PERMISSION_RULE of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/ANNOTATED_RELATIONSHIP_ELEMENT
 

 [http://admin-shell.io/aas/2/0/ReferableElements/ANNOTATED_RELATIONSHIP_ELEMENT](http://admin-shell.io/aas/2/0/ReferableElements/ANNOTATED_RELATIONSHIP_ELEMENT) The ReferableElements ANNOTATED_RELATIONSHIP_ELEMENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/BASIC_EVENT
 

 [http://admin-shell.io/aas/2/0/ReferableElements/BASIC_EVENT](http://admin-shell.io/aas/2/0/ReferableElements/BASIC_EVENT) The ReferableElements BASIC_EVENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/BLOB
 

 [http://admin-shell.io/aas/2/0/ReferableElements/BLOB](http://admin-shell.io/aas/2/0/ReferableElements/BLOB) The ReferableElements BLOB of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/CAPABILITY
 

 [http://admin-shell.io/aas/2/0/ReferableElements/CAPABILITY](http://admin-shell.io/aas/2/0/ReferableElements/CAPABILITY) The ReferableElements CAPABILITY of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/CONCEPT_DICTIONARY
 

 [http://admin-shell.io/aas/2/0/ReferableElements/CONCEPT_DICTIONARY](http://admin-shell.io/aas/2/0/ReferableElements/CONCEPT_DICTIONARY) The ReferableElements CONCEPT_DICTIONARY of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/DATA_ELEMENT
 

 [http://admin-shell.io/aas/2/0/ReferableElements/DATA_ELEMENT](http://admin-shell.io/aas/2/0/ReferableElements/DATA_ELEMENT) The ReferableElements DATA_ELEMENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/ENTITY
 

 [http://admin-shell.io/aas/2/0/ReferableElements/ENTITY](http://admin-shell.io/aas/2/0/ReferableElements/ENTITY) The ReferableElements ENTITY of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/EVENT
 

 [http://admin-shell.io/aas/2/0/ReferableElements/EVENT](http://admin-shell.io/aas/2/0/ReferableElements/EVENT) The ReferableElements EVENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/MULTI_LANGUAGE_PROPERTY
 Property with a value that can be provided in multiple languages.

 [http://admin-shell.io/aas/2/0/ReferableElements/MULTI_LANGUAGE_PROPERTY](http://admin-shell.io/aas/2/0/ReferableElements/MULTI_LANGUAGE_PROPERTY) The ReferableElements MULTI_LANGUAGE_PROPERTY of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/OPERATION
 

 [http://admin-shell.io/aas/2/0/ReferableElements/OPERATION](http://admin-shell.io/aas/2/0/ReferableElements/OPERATION) The ReferableElements OPERATION of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/PROPERTY
 

 [http://admin-shell.io/aas/2/0/ReferableElements/PROPERTY](http://admin-shell.io/aas/2/0/ReferableElements/PROPERTY) The ReferableElements PROPERTY of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/RANGE
 

 [http://admin-shell.io/aas/2/0/ReferableElements/RANGE](http://admin-shell.io/aas/2/0/ReferableElements/RANGE) The ReferableElements RANGE of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/REFERENCE_ELEMENT
 

 [http://admin-shell.io/aas/2/0/ReferableElements/REFERENCE_ELEMENT](http://admin-shell.io/aas/2/0/ReferableElements/REFERENCE_ELEMENT) The ReferableElements REFERENCE_ELEMENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/RELATIONSHIPT_ELEMENT
 

 [http://admin-shell.io/aas/2/0/ReferableElements/RELATIONSHIPT_ELEMENT](http://admin-shell.io/aas/2/0/ReferableElements/RELATIONSHIPT_ELEMENT) The ReferableElements RELATIONSHIPT_ELEMENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/SUBMODEL_ELEMENT_COLLECTION
 Collection of Submodel Elements

 [http://admin-shell.io/aas/2/0/ReferableElements/SUBMODEL_ELEMENT_COLLECTION](http://admin-shell.io/aas/2/0/ReferableElements/SUBMODEL_ELEMENT_COLLECTION) The ReferableElements SUBMODEL_ELEMENT_COLLECTION of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/SUBMODEL_ELEMENT
 

 [http://admin-shell.io/aas/2/0/ReferableElements/SUBMODEL_ELEMENT](http://admin-shell.io/aas/2/0/ReferableElements/SUBMODEL_ELEMENT) The ReferableElements SUBMODEL_ELEMENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## ReferableElements/VIEW
 

 [http://admin-shell.io/aas/2/0/ReferableElements/VIEW](http://admin-shell.io/aas/2/0/ReferableElements/VIEW) The ReferableElements VIEW of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Reference
 Reference to either a model element of the same or another AAs or to an external entity. A reference is an ordered list of keys, each key referencing an element. The complete list of keys may for example be concatenated to a path that then gives unique access to an element or entity.

 [http://admin-shell.io/aas/2/0/Reference](http://admin-shell.io/aas/2/0/Reference) The Reference class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Reference/key
Unique reference in its name space.

[http://admin-shell.io/aas/2/0/Reference/key](http://admin-shell.io/aas/2/0/Reference/key) The key attribute of the Reference class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## ReferenceElement
 A reference element is a data element that defines a logical reference to another element within the same or another AAS or a reference to an external object or entity.

 [http://admin-shell.io/aas/2/0/ReferenceElement](http://admin-shell.io/aas/2/0/ReferenceElement) The ReferenceElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## ReferenceElement/value
Reference to any other referable element of the same of any other AAS or a reference to an external object or entity.

[http://admin-shell.io/aas/2/0/ReferenceElement/value](http://admin-shell.io/aas/2/0/ReferenceElement/value) The value attribute of the ReferenceElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.


## RelationshipElement
 

 [http://admin-shell.io/aas/2/0/RelationshipElement](http://admin-shell.io/aas/2/0/RelationshipElement) The RelationshipElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## RelationshipElement/first
First element in the relationship taking the role of the subject.

[http://admin-shell.io/aas/2/0/RelationshipElement/first](http://admin-shell.io/aas/2/0/RelationshipElement/first) The attribute first of the RelationshipElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## RelationshipElement/second
 Second element in the relationship taking the role of the object.

[http://admin-shell.io/aas/2/0/RelationshipElement/second](http://admin-shell.io/aas/2/0/RelationshipElement/second) The attribute second of the RelationshipElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Security
 Container for security relevant information of the AAS.

 [http://admin-shell.io/aas/2/0/Security](http://admin-shell.io/aas/2/0/Security) The Security class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## Security/accessControlPolicyPoints
 Access control policy points of the AAS.

 [http://admin-shell.io/aas/2/0/Security/accessControlPolicyPoints](http://admin-shell.io/aas/2/0/Security/accessControlPolicyPoints) The attribute accessControlPolicyPoints of the Security class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Security/certificate
 Certificates of the AAS.

 [http://admin-shell.io/aas/2/0/Security/certificate](http://admin-shell.io/aas/2/0/Security/certificate) The attribute certificate of the Security class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Security/requiredCertificateExtension
 Certificate extensions as required by the AAS.

 [http://admin-shell.io/aas/2/0/Security/requiredCertificateExtension](http://admin-shell.io/aas/2/0/Security/requiredCertificateExtension) The attribute requiredCertificateExtension of the Security class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## SubjectAttributes
 A set of data elements that further classifies a specific subject.

 [http://admin-shell.io/aas/2/0/SubjectAttributes](http://admin-shell.io/aas/2/0/SubjectAttributes) The SubjectAttributes class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## SubjectAttributes/subjectAttribute
 A data element that further classifies a specific subject.

 [http://admin-shell.io/aas/2/0/SubjectAttributes/subjectAttribute](http://admin-shell.io/aas/2/0/SubjectAttributes/subjectAttribute) The attribute subjectAttribute of the SubjectAttributes class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## Submodel
 A Submodel defines a specific aspect of the asset represented by the AAS. A submodel is used to structure the virtual representation and technical functionality of an Administration Shell into distinguishable parts. Each submodel refers to a well-defined domain or subject matter. Submodels can become standardized and thus become submodels types. Submodels can have different life-cycles.

 [http://admin-shell.io/aas/2/0/Submodel](http://admin-shell.io/aas/2/0/Submodel) The Submodel class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.


## Submodel/submodelElement
 A submodel consists of zero or more submodel elements.

 [http://admin-shell.io/aas/2/0/Submodel/submodelElement](http://admin-shell.io/aas/2/0/Submodel/submodelElement) The attribute submodelElement of the Submodel class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## SubmodelElement
 A submodel element is an element suitable for the description and differentiation of assets.

 [http://admin-shell.io/aas/2/0/SubmodelElement](http://admin-shell.io/aas/2/0/SubmodelElement) The SubmodelElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## SubmodelElementCollection
 A submodel element collection is a set or list of submodel elements.

 [http://admin-shell.io/aas/2/0/SubmodelElementCollection](http://admin-shell.io/aas/2/0/SubmodelElementCollection) The SubmodelElementCollection class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## SubmodelElementCollection/allowDuplicates
 If allowDuplicates=true then it is allowed that the collection contains the same element several times. Default = false

 [http://admin-shell.io/aas/2/0/SubmodelElementCollection/allowDuplicates](http://admin-shell.io/aas/2/0/SubmodelElementCollection/allowDuplicates) The attribute allowDuplicates of the SubmodelElementCollection class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## SubmodelElementCollection/ordered
 If ordered=false then the elements in the property collection are not ordered. If ordered=true then the elements in the collection are ordered. Default = false

 [http://admin-shell.io/aas/2/0/SubmodelElementCollection/ordered](http://admin-shell.io/aas/2/0/SubmodelElementCollection/ordered) The attribute ordered of the SubmodelElementCollection class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.

## View
A view is a collection of referable elements w.r.t. to a specific viewpoint of one or more
stakeholders.

 [http://admin-shell.io/aas/2/0/View](http://admin-shell.io/aas/2/0/View) The View class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 2.0'.

## View/containedElement
 Referable elements that are contained in the view.

 [http://admin-shell.io/aas/2/0/View/containedElement](http://admin-shell.io/aas/2/0/View/containedElement) The attribute containedElement of the View class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 2.0'.





## Contact

This subnamespace was created by the [Plattform Industrie 4.0](http://www.plattform-i40.de/). The [Coordination Board Submodels](mailto:coordination-board@admin-shell.io) maintains these identifiers.