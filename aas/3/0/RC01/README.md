# AAS (Asset Administration Shell)

This is the sub-namespace resevered for the Asset Administration Shell Metamodel.

## Introduction

The Metamodel itself is defined in the 'Details of the Asset Administration Shell - Part 1'. Only classes, attributes and named entities used in this model are allowed in this sub-namespace. The Metamodel is the core resource for the structure of the Asset Administration Shell and provides the frame for all further specifications. The following entities are defined in the Metamodel but also serve as an example how to use the 'Asset Administration Shell Identifiers' in general.

## Status: Accepted

The sub-namespace AAS and its identifiers have been accepted by the Coordination Board.

## AccessControl

Access Control defines the local access control policy administration point. Access Control has the major task to define the access permission rules.

 [https://admin-shell.io/aas/3/0/RC01/AccessControl](https://admin-shell.io/aas/3/0/RC01/AccessControl) The AccessControl class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessControl/accessPermissionRule

Access permission rules of the AAS describing the rights assigned to (already authenticated) subjects to access elements of the AAS.

 [http://admin-shell.io/aas/3/0/RC01/AccessControl/accessPermissionRule](http://admin-shell.io/aas/2/0/AccessControl/accessPermissionRule) The attribute accessPermissionRule of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessControl/defaultEnvironmentAttributes
 Reference to a submodel defining default environment attributes, i.e. attributes that are not describing the asset itself. The submodel is of kind=Type. At the same type the values of these environment attributes need to be accessible when evaluating the access permission rules. This is realized as a policy information point.

 [http://admin-shell.io/aas/3/0/RC01/AccessControl/defaultEnvironmentAttributes](http://admin-shell.io/aas/2/0/AccessControl/defaultEnvironmentAttributes) The attribute defaultEnvironmentAttributes of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessControl/defaultPermissions
 Reference to a submodel defining the default permissions for the AAS.

 [http://admin-shell.io/aas/3/0/RC01/AccessControl/defaultPermissions](http://admin-shell.io/aas/3/0/RC01/AccessControl/defaultPermissions) The attribute defaultPermissions of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessControl/defaultSubjectAttributes
 Reference to a submodel defining the default subjects attributes for the AAS that can be used to describe access permission rules.

 [http://admin-shell.io/aas/3/0/RC01/AccessControl/defaultSubjectAttributes](http://admin-shell.io/aas/3/0/RC01/AccessControl/defaultSubjectAttributes) The attribute defaultSubjectAttributes of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessControl/selectableEnvironmentAttributes
 Reference to a submodel defining which environment attributes can be accessed via the permission rules defined for the AAS, i.e. attributes that are not describing the asset itself. Default: reference to the submodel referenced via defaultEnvironmentAttributes

 [http://admin-shell.io/aas/3/0/RC01/AccessControl/selectableEnvironmentAttributes](http://admin-shell.io/aas/3/0/RC01/AccessControl/selectableEnvironmentAttributes) The attribute selectableEnvironmentAttributes of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessControl/selectablePermissions
 Reference to a submodel defining which permissions can be assigned to the subjects.

 [http://admin-shell.io/aas/3/0/RC01/AccessControl/selectablePermissions](http://admin-shell.io/aas/3/0/RC01/AccessControl/selectablePermissions) The attribute selectablePermissions of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessControl/selectableSubjectAttributes
 Reference to a submodel defining the authenticated subjects that are configured for the AAS. They are selectable by the access permission rules to assign permissions to the subjects.

 [http://admin-shell.io/aas/3/0/RC01/AccessControl/selectableSubjectAttributes](http://admin-shell.io/aas/3/0/RC01/AccessControl/selectableSubjectAttributes) The attribute selectableSubjectAttributes of the AccessControl class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessControlPolicyPoints
 Container for access control policy points.

 [http://admin-shell.io/aas/3/0/RC01/AccessControlPolicyPoints](http://admin-shell.io/aas/3/0/RC01/AccessControlPolicyPoints) The AccessControlPolicyPoints class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.'.

## AccessControlPolicyPoints/policyAdministrationPoint
 The access control administration policy point of the AAS.

 [http://admin-shell.io/aas/3/0/RC01/AccessControlPolicyPoints/policyAdministrationPoint](http://admin-shell.io/aas/3/0/RC01/AccessControlPolicyPoints/policyAdministrationPoint) The attribute policyAdministrationPoint of the AccessControlPolicyPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessControlPolicyPoints/policyDecisionPoint
 The access control policy decision point of the AAS.

 [http://admin-shell.io/aas/3/0/RC01/AccessControlPolicyPoints/policyDecisionPoint](http://admin-shell.io/aas/3/0/RC01/AccessControlPolicyPoints/policyDecisionPoint) The attribute policyDecisionPoint of the AccessControlPolicyPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessControlPolicyPoints/policyEnforcementPoint
 The access control policy enforcement point of the AAS.

 [http://admin-shell.io/aas/3/0/RC01/AccessControlPolicyPoints/policyEnforcementPoint](http://admin-shell.io/aas/3/0/RC01/AccessControlPolicyPoints/policyEnforcementPoint) The attribute policyEnforcementPoint of the AccessControlPolicyPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessControlPolicyPoints/policyInformationPoints
 The access control policy information points of the AAS.

 [http://admin-shell.io/aas/3/0/RC01/AccessControlPolicyPoints/policyInformationPoints](http://admin-shell.io/aas/3/0/RC01/AccessControlPolicyPoints/policyInformationPoints) The attribute policyInformationPoints of the AccessControlPolicyPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessPermissionRule
 Table that defines access permissions per authenticated subject for a set of objects (referable elements).

 [http://admin-shell.io/aas/3/0/RC01/AccessPermissionRule](http://admin-shell.io/aas/3/0/RC01/AccessPermissionRule) The AccessPermissionRule class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessPermissionRule/permissionsPerObject
 Set of object-permission pairs that define the permissions per object within the access permission rule.

 [http://admin-shell.io/aas/3/0/RC01/AccessPermissionRule/permissionsPerObject](http://admin-shell.io/aas/3/0/RC01/AccessPermissionRule/permissionsPerObject) The attribute permissionsPerObject of the AccessPermissionRule class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AccessPermissionRule/targetSubjectAttributes
 Target subject attributes that need to be fulfilled by the accessing subject to get the permissions defined by this rule.

 [http://admin-shell.io/aas/3/0/RC01/AccessPermissionRule/targetSubjectAttributes](http://admin-shell.io/aas/3/0/RC01/AccessPermissionRule/targetSubjectAttributes) The attribute targetSubjectAttributes of the AccessPermissionRule class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AdministrativeInformation
 Every Identifiable may have administrative information. Administrative information includes for example  Information about the version of the element  Information about who created or who made the last change to the element  Information about the languages available in case the element contains text, for translating purposed also themmaster or default language may be definedIn the first version of the AAS metamodel only version information as defined by IEC 61360 is defined. In later versions additional attributes may be added.

 [http://admin-shell.io/aas/3/0/RC01/AdministrativeInformation](http://admin-shell.io/aas/3/0/RC01/AdministrativeInformation) The AdministrativeInformation class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AdministrativeInformation/revision
 Revision of the element. Constraint AASd-005: A revision requires a version. This means, if there is no version there is no revision neither.

 [http://admin-shell.io/aas/3/0/RC01/AdministrativeInformation/revision](http://admin-shell.io/aas/3/0/RC01/AdministrativeInformation/revision) The attribute revision of the AdministrativeInformation class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AdministrativeInformation/version
 Version of the element.

 [http://admin-shell.io/aas/3/0/RC01/AdministrativeInformation/version](http://admin-shell.io/aas/3/0/RC01/AdministrativeInformation/version) The attribute version of the AdministrativeInformation class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AnnotatedRelationshipElement
 An annotated relationship element is an relationship element that can be annotated with additional data elements.

 [http://admin-shell.io/aas/3/0/RC01/AnnotatedRelationshipElement](http://admin-shell.io/aas/3/0/RC01/AnnotatedRelationshipElement) The AnnotatedRelationshipElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AnnotatedRelationshipElement/annotation
 Annotations that hold for the relationships between the two elements.

 [http://admin-shell.io/aas/3/0/RC01/AnnotatedRelationshipElement/annotation](http://admin-shell.io/aas/3/0/RC01/AnnotatedRelationshipElement/annotation) The attribute annotation of the AnnotatedRelationshipElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Asset
 An Asset describes meta data of an asset that is represented by an AAS. The asset may either represent an asset type or an asset instance. The asset has a globally unique identifier plus – if needed – additional domain specific (proprietary) identifiers.

 [http://admin-shell.io/aas/3/0/RC01/Asset](http://admin-shell.io/aas/3/0/RC01/Asset) The Asset class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetInformation
 In AssetInformation identifying meta data of the asset that is represented by an AAS is defined. The asset may either represent an asset type or an asset instance. The asset has a globally unique identifier plus – if needed – additional domain specific (proprietary) identifiers. However, to support the corner case of very first phase of lifecycle where a stabilised/constant global asset identifier does not already exist, the corresponding attribute “globalAssetId” is optional.

 [https://admin-shell.io/aas/3/0/RC01/AssetInformation](https://admin-shell.io/aas/3/0/RC01/AssetInformation) The AssetInformation class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetInformation/assetKind
 Denotes whether the Asset of of kind 'Type' or 'Instance'.
 
 [https://admin-shell.io/aas/3/0/RC01/AssetInformation/assetKind](https://admin-shell.io/aas/3/0/RC01/AssetInformation/assetKind) The attribute assetKind of the AssetInformation class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetInformation/globalAssetId
 Reference to either an Asset object or a global reference to the asset the AAS is representing. This attribute is required as soon as the AAS is exchanged via partners in the life cycle of the asset. In a first phase of the life cycle the asset might not yet have a global id but already an internal identifier. The internal identifier would be modelled via “externalAssetId”.

 [https://admin-shell.io/aas/3/0/RC01/AssetInformation/globalAssetId](https://admin-shell.io/aas/3/0/RC01/AssetInformation/globalAssetId) The attribute globalAssetId of the AssetInformation class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetInformation/externalAssetId
 Additional domain specific external, typically proprietary Identifier for the asset like e.g. serial number etc.
 
 [https://admin-shell.io/aas/3/0/RC01/AssetInformation/externalAssetId](https://admin-shell.io/aas/3/0/RC01/AssetInformation/externalAssetId) The attribute externalAssetId of the AssetInformation class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetInformation/billOfMaterial
 A reference to a Submodel that defines the bill of material of the asset represented by the AAS. This submodel contains a set of entities describing the material used to compose the composite I4.0 Component.
 
 [https://admin-shell.io/aas/3/0/RC01/AssetInformation/billOfMaterial](https://admin-shell.io/aas/3/0/RC01/AssetInformation/billOfMaterial) The attribute billOfMaterial of the AssetInformation class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetInformation/thumbnail
 Thumbnail of the asset represented by the asset administration shell.
 
 [https://admin-shell.io/aas/3/0/RC01/AssetInformation/thumbnail](https://admin-shell.io/aas/3/0/RC01/AssetInformation/thumbnail) The attribute thumbnail of the AssetInformation class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.
 
## AssetAdministrationShell
 Describes the Administration Shell for Assets, Products, Components, e.g. Machines

 [http://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell](http://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell) The AssetAdministrationShell class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetAdministrationShell/assetInformation
 Meta information about the asset the AAS is representing.
 
 [https://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell/assetInformation](https://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell/assetInformation) The attribute assetInformation of the AssetAdministrationShell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetAdministrationShell/derivedFrom
 This relation connects instances of AAS with their respective types. Refer to Asset Kind for further information of instance and type kinds.

 [http://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell/derivedFrom](http://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell/derivedFrom) The attribute derivedFrom of the AssetAdministrationShell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetAdministrationShell/security
 Definition of the security relevant aspects of the AAS.

 [http://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell/security](http://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell/security) The attribute security of the AssetAdministrationShell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetAdministrationShell/submodel
 Points from the Admin Shell to the Submodels that describe the Admin Shell of a given Asset

 [http://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell/submodel](http://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell/submodel) The attribute submodel of the AssetAdministrationShell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetAdministrationShell/view
 Points to the differents views associated to the Administration Shell via the Submodels.

 [http://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell/view](http://admin-shell.io/aas/3/0/RC01/AssetAdministrationShell/view) The attribute view of the AssetAdministrationShell class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetKind
 Enumeration for denoting whether an element is a type or an instance.

 [http://admin-shell.io/aas/3/0/RC01/AssetKind](http://admin-shell.io/aas/3/0/RC01/AssetKind) The AssetKind class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetKind/INSTANCE
 Concrete, clearly identifiable component of a certain type.

 [http://admin-shell.io/aas/3/0/RC01/AssetKind/INSTANCE](http://admin-shell.io/aas/3/0/RC01/AssetKind/INSTANCE) The NamedIndividual INSTANCE of the AssetKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## AssetKind/TYPE
 hardware or software element which specifies the common attributes shared by all instances of the type.

 [http://admin-shell.io/aas/3/0/RC01/AssetKind/TYPE](http://admin-shell.io/aas/3/0/RC01/AssetKind/TYPE) The NamedIndividual TYPE of the AssetKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## BasicEvent
 A basic event.

 [http://admin-shell.io/aas/3/0/RC01/BasicEvent](http://admin-shell.io/aas/3/0/RC01/BasicEvent) The BasicEvent class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## BasicEvent/observed
 Reference to the data or other elements that are being observed.

 [http://admin-shell.io/aas/3/0/RC01/BasicEvent/observed](http://admin-shell.io/aas/3/0/RC01/BasicEvent/observed) The attribute observed of the BasicEvent class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Blob
 A BLOB is a data element that represents a file that is contained with its source code in the value attribute.

 [http://admin-shell.io/aas/3/0/RC01/Blob](http://admin-shell.io/aas/3/0/RC01/Blob) The Blob class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Blob/mimeType
 Mime type of the content of the BLOB. The mime type states which file extension the file has. Valid values are e.g. 'application/json', 'application/xls', 'image/jpg' The allowed values are defined as in RFC2046.
 [https://admin-shell.io/aas/3/0/RC01/Blob/mimeType](https://admin-shell.io/aas/3/0/RC01/Blob/mimeType) The attribute mimeType of the Blob class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Blob/value
 The value of the BLOB instance of a blob data element.
 
 [https://admin-shell.io/aas/3/0/RC01/Blob/value](https://admin-shell.io/aas/3/0/RC01/Blob/value) The attribute value of the Blob class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## BlobCertificate
 Certificate provided as BLOB.

 [http://admin-shell.io/aas/3/0/RC01/BlobCertificate](http://admin-shell.io/aas/3/0/RC01/BlobCertificate) The BlobCertificate class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## BlobCertificate/blobCertificate
 Certificate as BLOB.

 [http://admin-shell.io/aas/3/0/RC01/BlobCertificate/blobCertificate](http://admin-shell.io/aas/3/0/RC01/BlobCertificate/blobCertificate) The attribute blobCertificate of the BlobCertificate class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## BlobCertificate/containedExtension
 Extensions contained in the certificate.

 [http://admin-shell.io/aas/3/0/RC01/BlobCertificate/containedExtension](http://admin-shell.io/aas/3/0/RC01/BlobCertificate/containedExtension) The attribute containedExtension of the BlobCertificate class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## BlobCertificate/lastCertificate
 Denotes whether this certificate is the certificated that fast added last.

 [http://admin-shell.io/aas/3/0/RC01/BlobCertificate/lastCertificate](http://admin-shell.io/aas/3/0/RC01/BlobCertificate/lastCertificate) The attribute lastCertificate of the BlobCertificate class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Capability
 A capability is the implementation-independent description of the potential of an asset to achieve a certain effect in the physical or virtual world.

 [http://admin-shell.io/aas/3/0/RC01/Capability](http://admin-shell.io/aas/3/0/RC01/Capability) The Capability class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Category
 A Category specifies the nature of a Property or a MultiLanguageProperty.

 [http://admin-shell.io/aas/3/0/RC01/Category](http://admin-shell.io/aas/3/0/RC01/Category) The Category class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Category/CONSTANT
 A constant property is a property with a value that does not change over time. In eCl@ss this kind of category has the category 'Coded Value'.

 [http://admin-shell.io/aas/3/0/RC01/Category/CONSTANT](http://admin-shell.io/aas/3/0/RC01/Category/CONSTANT) The NamedIndividual CONSTANT of the Category class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Category/PARAMETER
 A parameter property is a property that is once set and then typically does not change over time. This is for example the case for configuration parameters.

 [http://admin-shell.io/aas/3/0/RC01/Category/PARAMETER](http://admin-shell.io/aas/3/0/RC01/Category/PARAMETER) The NamedIndividual PARAMETER of the Category class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Category/VARIABLE
 A variable property is a property that is calculated during runtime, i.e. its value is a runtime value.

 [http://admin-shell.io/aas/3/0/RC01/Category/VARIABLE](http://admin-shell.io/aas/3/0/RC01/Category/VARIABLE) The NamedIndividual VARIABLE of the Category class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Certificate
 A technical certificate proofing the identity through cryptographic measures.

 [http://admin-shell.io/aas/3/0/RC01/Certificate](http://admin-shell.io/aas/3/0/RC01/Certificate) The Certificate class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Certificate/policyAdministrationPoint
 The access control administration policy point of the AAS.
 
 [https://admin-shell.io/aas/3/0/RC01/Certificate/policyAdministrationPoint](https://admin-shell.io/aas/3/0/RC01/Certificate/policyAdministrationPoint) The attribute policyAdministrationPoint of the Certificate as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ConceptDescription
 The semantics of a property or other elements that may have a semantic description is defined by a concept description. The description of the concept should follow a standardized schema (realized as data specification template).

 [http://admin-shell.io/aas/3/0/RC01/ConceptDescription](http://admin-shell.io/aas/3/0/RC01/ConceptDescription) The ConceptDescription class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ConceptDescription/content
 Link from a ConceptDescription to its explaining DataSpecificationContent.
 
 [https://admin-shell.io/aas/3/0/RC01/ConceptDescription/content](https://admin-shell.io/aas/3/0/RC01/ConceptDescription/content) The attribute content of the ConceptDescription as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ConceptDescription/isCaseOf
 Global reference to an external definition the concept is compatible to or was derived from.

 [http://admin-shell.io/aas/3/0/RC01/ConceptDescription/isCaseOf](http://admin-shell.io/aas/3/0/RC01/ConceptDescription/isCaseOf) The attribute isCaseOf of the ConceptDescription class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Constraint
 A constraint is used to further qualify an element.

 [http://admin-shell.io/aas/3/0/RC01/Constraint](http://admin-shell.io/aas/3/0/RC01/Constraint) The Constraint class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataElement
 A data element is a submodel element that is not further composed out of other submodel elements. A data element is a submodel element that has a value. The type of value differs for different subtypes of data elements.

 [http://admin-shell.io/aas/3/0/RC01/DataElement](http://admin-shell.io/aas/3/0/RC01/DataElement) The DataElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationContent
 DataSpecificationContent contains the additional attributes to be added to the element instance that references the data specification template and meta information about the template itself.

 [http://admin-shell.io/aas/3/0/RC01/DataSpecificationContent](http://admin-shell.io/aas/3/0/RC01/DataSpecificationContent) The DataSpecificationContent class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360
 Data Specification Template for defining Property Descriptions conformant to IEC 61360.

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360) The DataSpecificationIEC61360 class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/datatype
 

 [ https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/dataType]( https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/dataType) The attribute dataType of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/definition


 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/definition](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/definition) The attribute definition of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/levelType


 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/levelType](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/levelType) The attribute levelType of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/preferredName
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/preferredName](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/preferredName) The attribute preferredName of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/shortName
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/shortName](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/shortName) The attribute shortName of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/sourceOfDefinition


 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/sourceOfDefinition](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/sourceOfDefinition) The attribute sourceOfDefinition of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/symbol
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/symbol](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/symbol) The attribute symbol of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/unit
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/unit](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/unit) The attribute unit of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/unitId
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/unitId](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/unitId) The attribute unitId of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/valueFormat
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/valueFormat](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/valueFormat) The attribute valueFormat of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/value


 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/value](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/value) The attribute value of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/valueList


 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/valueList](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataSpecificationIEC61360/valueList) The attribute valueList of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationIEC61360/valueId
 The Type 'ValueList' lists all the allowed values for a concept description for which the allowed values are listed in an enumeration. The value list is a set of value reference pairs.

 [http://admin-shell.io/aas/3/0/RC01/DataSpecificationIEC61360/valueId](http://admin-shell.io/aas/3/0/RC01/DataSpecificationIEC61360/valueId) The attribute valueId of the DataSpecificationIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit
 Data Specification Tempate for Physical Units.

 [ https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/) The DataSpecificationPhysicalUnit class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit/conversionFactor
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/conversionFactor](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/conversionFactor) The attribute conversionFactor of the DataSpecificationPhysicalUnit class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit/definition
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/definition](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/definition) The attribute definition of the DataSpecificationPhysicalUnit class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit/dinNotation

 
 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/dinNotation](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/dinNotation) The attribute dinNotation of the DataSpecificationPhysicalUnit class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit/eceCode
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/eceCode](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/eceCode) The attribute eceCode of the DataSpecificationPhysicalUnit class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit/eceName
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/eceName](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/eceName) The attribute eceName of the DataSpecificationPhysicalUnit class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit/nistName
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/nistName](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/nistName) The attribute nistName of the DataSpecificationPhysicalUnit class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit/siName
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/siName](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/siName) The attribute siName of the DataSpecificationPhysicalUnit class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit/siNotation
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/siNotation](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/siNotation) The attribute siNotation of the DataSpecificationPhysicalUnit class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit/supplier
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/supplier](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/supplier) The attribute supplier of the DataSpecificationPhysicalUnit class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit/unitName
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/unitName](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/unitName) The attribute unitName of the DataSpecificationPhysicalUnit class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataSpecificationPhysicalUnit/unitSymbol
 

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/unitSymbol](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationPhysicalUnit/3/0/RC01/unitSymbol) The attribute unitSymbol of the DataSpecificationPhysicalUnit class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360
 Enumeration of all IEC 61360 defined data types.

 [https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataTypeIEC61360](https://admin-shell.io/DataSpecificationTemplates/DataSpecificationIEC61360/3/0/RC01/DataTypeIEC61360) The DataTypeIEC61360 class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/BOOLEAN_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/BOOLEAN_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/BOOLEAN_IEC6360_DATATYPE) The DataTypeIEC61360 BOOLEAN_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/DATE_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/DATE_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/DATE_IEC6360_DATATYPE) The DataTypeIEC61360 DATE_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/RATIONAL_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/RATIONAL_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/RATIONAL_IEC6360_DATATYPE) The DataTypeIEC61360 RATIONAL_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/RATIONAL_MEASURE_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/RATIONAL_MEASURE_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/RATIONAL_MEASURE_IEC6360_DATATYPE) The DataTypeIEC61360 RATIONAL_MEASURE_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/REAL_COUNT_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/REAL_COUNT_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/REAL_COUNT_IEC6360_DATATYPE) The DataTypeIEC61360 REAL_COUNT_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/REAL_CURRENCY_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/REAL_CURRENCY_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/REAL_CURRENCY_IEC6360_DATATYPE) The DataTypeIEC61360 REAL_CURRENCY_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/REAL_MEASURE_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/REAL_MEASURE_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/REAL_MEASURE_IEC6360_DATATYPE) The DataTypeIEC61360 REAL_MEASURE_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/STRING_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/STRING_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/STRING_IEC6360_DATATYPE) The DataTypeIEC61360 STRING_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/STRING_TRANSLATABLE_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/STRING_TRANSLATABLE_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/STRING_TRANSLATABLE_IEC6360_DATATYPE) The DataTypeIEC61360 STRING_TRANSLATABLE_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/TIMESTAMP_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/TIMESTAMP_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/TIMESTAMP_IEC6360_DATATYPE) The DataTypeIEC61360 TIMESTAMP_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/TIME_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/TIME_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/TIME_IEC6360_DATATYPE) The DataTypeIEC61360 TIME_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## DataTypeIEC61360/URL_IEC6360_DATATYPE
 

 [http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/URL_IEC6360_DATATYPE](http://admin-shell.io/aas/3/0/RC01/DataTypeIEC61360/URL_IEC6360_DATATYPE) The DataTypeIEC61360 URL_IEC6360_DATATYPE of the DataTypeIEC61360 class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Entity
 An entity is a submodel element that is used to model entities.

 [http://admin-shell.io/aas/3/0/RC01/Entity](http://admin-shell.io/aas/3/0/RC01/Entity) The Entity class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Entity/entityType
 Describes whether the entity is a co-managed entity or a self-managed entity.

 [http://admin-shell.io/aas/3/0/RC01/Entity/entityType](http://admin-shell.io/aas/3/0/RC01/Entity/entityType) The attribute entityType of the Entity class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Entity/externalAssetId
 Reference to an identifier key value pair representing an external identifier of the asset represented by the asset administration shell.

 [http://admin-shell.io/aas/3/0/RC01/Entity/externalAssetId](http://admin-shell.io/aas/3/0/RC01/Entity/externalAssetId) The attribute externalAssetId of the Entity class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Entity/globalAssetId
 Reference to the asset the entity is representing.

 [http://admin-shell.io/aas/3/0/RC01/Entity/globalAssetId](http://admin-shell.io/aas/3/0/RC01/Entity/globalAssetId) The attribute globalAssetId of the Entity class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Entity/statement
 Describes statements applicable to the entity by a set of submodel elements, typically with a qualified value.

 [http://admin-shell.io/aas/3/0/RC01/Entity/statement](http://admin-shell.io/aas/3/0/RC01/Entity/statement) The attribute statement of the Entity class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## EntityType
 Enumeration for denoting whether an entity is a self-managed entity or a co-managed entity.

 [http://admin-shell.io/aas/3/0/RC01/EntityType](http://admin-shell.io/aas/3/0/RC01/EntityType) The EntityType class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## EntityType/CO_MANAGED_ENTITY
 For co-managed entities there is no separate AAS. Co-managed entities need to be part of a self-managed entity.

 [http://admin-shell.io/aas/3/0/RC01/EntityType/CO_MANAGED_ENTITY](http://admin-shell.io/aas/3/0/RC01/EntityType/CO_MANAGED_ENTITY) The NamedIndividual CO_MANAGED_ENTITY of the EntityType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## EntityType/SELF_MANAGED_ENTITY
 Self-Managed Entities have their own AAS but can be part of the bill of material of a composite self-managed entity. The asset of an I4.0 Component is a self-managed entity per definition.

 [http://admin-shell.io/aas/3/0/RC01/EntityType/SELF_MANAGED_ENTITY](http://admin-shell.io/aas/3/0/RC01/EntityType/SELF_MANAGED_ENTITY) The NamedIndividual SELF_MANAGED_ENTITY of the EntityType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.
## Extension
 Single extension of an element.

 [https://admin-shell.io/aas/3/0/RC01/Extension](https://admin-shell.io/aas/3/0/RC01/Extension) The Extension class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.
## Extension/name
 An extension of the element.

 [https://admin-shell.io/aas/3/0/RC01/Extension/name](https://admin-shell.io/aas/3/0/RC01/Extension/name) The attribute name of the Extension class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Extension/valueType
 Type of the value of the extension.

 [https://admin-shell.io/aas/3/0/RC01/Extension/valueType](https://admin-shell.io/aas/3/0/RC01/Extension/valueType) The attribute valueType of the Extension class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.
## Extension/value
 Value of the extension.

 [https://admin-shell.io/aas/3/0/RC01/Extension/value](https://admin-shell.io/aas/3/0/RC01/Extension/value) The attibute value of the Extension class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Extension/refersTo
 Reference to an element the extension refers to.

 [https://admin-shell.io/aas/3/0/RC01/Extension/refersTo](https://admin-shell.io/aas/3/0/RC01/Extension/refersTo) The attribute refersTo Extension class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Event
 

 [http://admin-shell.io/aas/3/0/RC01/Event](http://admin-shell.io/aas/3/0/RC01/Event) The Event class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## EventElement
 Defines the necessary information for sending or receiving events.

 [http://admin-shell.io/aas/3/0/RC01/EventElement](http://admin-shell.io/aas/3/0/RC01/EventElement) The EventElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## EventMessage
 Defines the necessary information ofv an event instance sent out or received.

 [http://admin-shell.io/aas/3/0/RC01/EventMessage](http://admin-shell.io/aas/3/0/RC01/EventMessage) The EventMessage class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## File
 A File is a data element that represents a file via its path description.

 [http://admin-shell.io/aas/3/0/RC01/File](http://admin-shell.io/aas/3/0/RC01/File) The File class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## File/mimeType
 Mime type of the content of the File.
 
 [https://admin-shell.io/aas/3/0/RC01/File/mimeType](https://admin-shell.io/aas/3/0/RC01/File/mimeType) The attribute mimeType of the File class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'. 

## File/value
 Path and name of the referenced file (with file extension). The path can be absolute or relative.
 
 [https://admin-shell.io/aas/3/0/RC01/File/value](https://admin-shell.io/aas/3/0/RC01/File/value) The attribute value of the File class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'. 

## Formula
 

 [http://admin-shell.io/aas/3/0/RC01/Formula](http://admin-shell.io/aas/3/0/RC01/Formula) The Formula class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Formula/dependsOn
 A formula may depend on referable or even external global elements - assumed that can be referenced and their value may be evaluated - that are used in the logical expression.

 [http://admin-shell.io/aas/3/0/RC01/Formula/dependsOn](http://admin-shell.io/aas/3/0/RC01/Formula/dependsOn) The attribute dependsOn of the Formula class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## HasExtensions
 Element that can be extended by proprietary extensions.
 
 [https://admin-shell.io/aas/3/0/RC01/HasExtensions](https://admin-shell.io/aas/3/0/RC01/HasExtensions) The HasExtensions class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'. 
 
## HasExtensions/extension
 An extension of the element.
 
 [https://admin-shell.io/aas/3/0/RC01/HasExtensions/extension](https://admin-shell.io/aas/3/0/RC01/HasExtensions/extension) The attribute extension of the HasExtensions class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.
 
## HasDataSpecification
 Element that can have be extended by using data specification templates. A data specification template defines the additional attributes an element may or shall have. The data specifications used are explicitly specified with their id.

 [http://admin-shell.io/aas/3/0/RC01/HasDataSpecification](http://admin-shell.io/aas/3/0/RC01/HasDataSpecification) The HasDataSpecification class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## HasDataSpecification/dataSpecification
 Global reference to the data specification template used by the element.

 [http://admin-shell.io/aas/3/0/RC01/HasDataSpecification/dataSpecification](http://admin-shell.io/aas/3/0/RC01/HasDataSpecification/dataSpecification) The attribute dataSpecification of the HasDataSpecification class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## HasKind
 An element with a kind is an element that can either represent a type or an instance. Default for an element is that it is representing an instance.

 [http://admin-shell.io/aas/3/0/RC01/HasKind](http://admin-shell.io/aas/3/0/RC01/HasKind) The HasKind class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## HasKind/kind
 ModelingKind of the element: either type or instance.

 [http://admin-shell.io/aas/3/0/RC01/HasKind/kind](http://admin-shell.io/aas/3/0/RC01/HasKind/kind) The attribute kind of the HasKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## HasSemantics
 Element that can have a semantic definition. Identifier of the semantic definition of the element. It is called semantic id of the element. The semantic id may either reference an external global id or it may reference a referable model element of kind=Type that defines the semantics of the element.

 [http://admin-shell.io/aas/3/0/RC01/HasSemantics](http://admin-shell.io/aas/3/0/RC01/HasSemantics) The HasSemantics class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## HasSemantics/semanticId
 Points to the Expression Semantic of the Submodels

 [http://admin-shell.io/aas/3/0/RC01/HasSemantics/semanticId](http://admin-shell.io/aas/3/0/RC01/HasSemantics/semanticId) The attribute semanticId of the HasSemantics class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Identifiable
 An element that has a globally unique identifier.

 [http://admin-shell.io/aas/3/0/RC01/Identifiable](http://admin-shell.io/aas/3/0/RC01/Identifiable) The Identifiable class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Identifiable/administration
 Administrative information of an identifiable element.

 [http://admin-shell.io/aas/3/0/RC01/Identifiable/administration](http://admin-shell.io/aas/3/0/RC01/Identifiable/administration) The attribute administration of the Identifiable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Identifiable/identification
 The globally unique identification of the element.

 [http://admin-shell.io/aas/3/0/RC01/Identifiable/identification](http://admin-shell.io/aas/3/0/RC01/Identifiable/identification) The attribute identification of the Identifiable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifiableElement
 Enumeration of all identifiable elements within an asset administration shell that are not identifiable

 [http://admin-shell.io/aas/3/0/RC01/IdentifiableElement](http://admin-shell.io/aas/3/0/RC01/IdentifiableElement) The IdentifiableElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifiableElement/ASSET
 

 [http://admin-shell.io/aas/3/0/RC01/IdentifiableElement/ASSET](http://admin-shell.io/aas/3/0/RC01/IdentifiableElement/ASSET) The IdentifiableElement ASSET of the IdentifiableElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifiableElement/ASSET_IDENTIFIABLE_ELEMENT
 

 [http://admin-shell.io/aas/3/0/RC01/IdentifiableElement/ASSET_IDENTIFIABLE_ELEMENT](http://admin-shell.io/aas/3/0/RC01/IdentifiableElement/ASSET_IDENTIFIABLE_ELEMENT) The IdentifiableElement ASSET_IDENTIFIABLE_ELEMENT of the IdentifiableElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifiableElement/CONCEPT_DESCRIPTION
 

 [http://admin-shell.io/aas/3/0/RC01/IdentifiableElement/CONCEPT_DESCRIPTION](http://admin-shell.io/aas/3/0/RC01/IdentifiableElement/CONCEPT_DESCRIPTION) The IdentifiableElement CONCEPT_DESCRIPTION of the IdentifiableElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifiableElement/SUBMODEL
 

 [http://admin-shell.io/aas/3/0/RC01/IdentifiableElement/SUBMODEL](http://admin-shell.io/aas/3/0/RC01/IdentifiableElement/SUBMODEL) The IdentifiableElement SUBMODEL of the IdentifiableElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Identifier
 Used to uniquely identify an entity by using an identifier.

 [http://admin-shell.io/aas/3/0/RC01/Identifier](http://admin-shell.io/aas/3/0/RC01/Identifier) The Identifier class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Identifier/id
 A globally unique identifier which might not be a URI. Its type is defined in idType.

 [http://admin-shell.io/aas/3/0/RC01/Identifier/id](http://admin-shell.io/aas/3/0/RC01/Identifier/id) The attribute id of the Identifier class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Identifier/idType
 Type of the Identifier, e.g. IRI, IRDI etc. The supported Identifier types are defined in the enumeration 'IdentifierType'.

 [http://admin-shell.io/aas/3/0/RC01/Identifier/idType](http://admin-shell.io/aas/3/0/RC01/Identifier/idType) The attribute idType of the Identifier class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifierType
 Enumeration of different types of Identifiers for global identification

 [http://admin-shell.io/aas/3/0/RC01/IdentifierType](http://admin-shell.io/aas/3/0/RC01/IdentifierType) The IdentifierType class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifierType/CUSTOM
 Custom identifiers like GUIDs (globally unique Identifiers)

 [http://admin-shell.io/aas/3/0/RC01/IdentifierType/CUSTOM](http://admin-shell.io/aas/3/0/RC01/IdentifierType/CUSTOM) The IdentifierType CUSTOM of the IdentifierType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifierType/IRDI
 IRDI according to ISO29002-5 as an Identifier scheme for properties and classifications.

 [http://admin-shell.io/aas/3/0/RC01/IdentifierType/IRDI](http://admin-shell.io/aas/3/0/RC01/IdentifierType/IRDI) The IdentifierType IRDI of the IdentifierType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifierType/IRI
 IRI. Should only be used if unicode symbols are used that are not allowed in URI.
 
 [http://admin-shell.io/aas/3/0/RC01/IdentifierType/IRI](http://admin-shell.io/aas/3/0/RC01/IdentifierType/IRI) The IdentifierType IRI of the IdentifierType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifierKeyValuePair
 An IdentifierKeyValuePair describes a generic identifier as key-value pair.
 
 [https://admin-shell.io/aas/3/0/RC01/IdentifierKeyValuePair](https://admin-shell.io/aas/3/0/RC01/IdentifierKeyValuePair) The IdentifierKeyValuePair class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifierKeyValuePair/key
 Key of the identifier.
 
 [https://admin-shell.io/aas/3/0/RC01/IdentifierKeyValuePair/key](https://admin-shell.io/aas/3/0/RC01/IdentifierKeyValuePair/key) The key attribute of the IdentifierKeyValuePair as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifierKeyValuePair/value
 The value of the identifier with the corresponding key.
 
 [https://admin-shell.io/aas/3/0/RC01/IdentifierKeyValuePair/value](https://admin-shell.io/aas/3/0/RC01/IdentifierKeyValuePair/value) The value attribute of the IdentifierKeyValuePair as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## IdentifierKeyValuePair/externalSubjectId
 The (external) subject the key belongs to or has meaning to.
 
 [https://admin-shell.io/aas/3/0/RC01/IdentifierKeyValuePair/externalSubjectId](https://admin-shell.io/aas/3/0/RC01/IdentifierKeyValuePair/externalSubjectId) The externalSubjectId attribute of the IdentifierKeyValuePair as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Key
 A key is a reference to an element by its id.

 [http://admin-shell.io/aas/3/0/RC01/Key](http://admin-shell.io/aas/3/0/RC01/Key) The Key class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Key/idType
 Type of the key value. In case of idType = idShort local shall be true. In case type=GlobalReference idType shall not be IdShort.

 [http://admin-shell.io/aas/3/0/RC01/Key/idType](http://admin-shell.io/aas/3/0/RC01/Key/idType) The attribute idType of the Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Key/type
 Denote which kind of entity is referenced. In case type = GlobalReference then the element is a global unique id. In all other cases the key references a model element of the same or of another AAS. The name of the model element is explicitly listed.

 [http://admin-shell.io/aas/3/0/RC01/Key/type](http://admin-shell.io/aas/3/0/RC01/Key/type) The attribute type of the Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Key/value
 The key value, for example an IRDI if the idType=IRDI.

 [http://admin-shell.io/aas/3/0/RC01/Key/value](http://admin-shell.io/aas/3/0/RC01/Key/value) The attribute value of the Key class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## KeyElement
 Enumeration of different key value types within a key. Contains KeyElements, ReferableElements, and IdentifiableElements.

 [http://admin-shell.io/aas/3/0/RC01/KeyElement](http://admin-shell.io/aas/3/0/RC01/KeyElement) The KeyElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## KeyElement/FRAGMENT_REFERENCE
 

 [http://admin-shell.io/aas/3/0/RC01/KeyElement/FRAGMENT_REFERENCE](http://admin-shell.io/aas/3/0/RC01/KeyElement/FRAGMENT_REFERENCE) The KeyElement FRAGMENT_REFERENCET of the KeyElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## KeyElement/GLOBAL_REFERENCE
 reference to an element not belonging to an asset administration shell

 [http://admin-shell.io/aas/3/0/RC01/KeyElement/GLOBAL_REFERENCE](http://admin-shell.io/aas/3/0/RC01/KeyElement/GLOBAL_REFERENCE) The KeyElement GLOBAL_REFERENCE of the KeyElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## KeyType
 Enumeration of different key value types within a key. Contains IdentifierType and LocalKeyType.

 [http://admin-shell.io/aas/3/0/RC01/KeyType](http://admin-shell.io/aas/3/0/RC01/KeyType) The KeyType class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## LevelType
 Enumeration of different level types within a DataSpecificationIEC61360. Contains Min, Max, Nom, and Typ.

 [https://admin-shell.io/aas/3/0/RC01/LevelType](https://admin-shell.io/aas/3/0/RC01/LevelType) The LevelType class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## LevelType/MIN
 MIN according to IEC 61360 as an Identifier scheme for minimal levels.

 [https://admin-shell.io/aas/3/0/RC01/LevelType/MIN](https://admin-shell.io/aas/3/0/RC01/LevelType/MIN) The MIN of the LevelType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## LevelType/MAX
 MAX according to IEC 61360 as an Identifier scheme for maximal levels.

 [https://admin-shell.io/aas/3/0/RC01/LevelType/MAX](https://admin-shell.io/aas/3/0/RC01/LevelType/MAX) The MAX of the LevelType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## LevelType/NOM
 NOM according to IEC 61360 as an Identifier scheme for nominal levels.

 [https://admin-shell.io/aas/3/0/RC01/LevelType/NOM](https://admin-shell.io/aas/3/0/RC01/LevelType/NOM) The NOM of the LevelType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## LevelType/TYP
 TYP according to IEC 61360 as an Identifier scheme for typical levels.

 [https://admin-shell.io/aas/3/0/RC01/LevelType/TYP](https://admin-shell.io/aas/3/0/RC01/LevelType/TYP) The TYP of the LevelType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## LocalKeyType
 Enumeration of different key value types within a key.

 [http://admin-shell.io/aas/3/0/RC01/LocalKeyType](http://admin-shell.io/aas/3/0/RC01/LocalKeyType) The LocalKeyType class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## LocalKeyType/FRAGMENT_ID
 Identifier of a fragment within a file

 [http://admin-shell.io/aas/3/0/RC01/LocalKeyType/FRAGMENT_ID](http://admin-shell.io/aas/3/0/RC01/LocalKeyType/FRAGMENT_ID) The LocalKeyType FRAGMENT_ID of the LocalKeyType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## LocalKeyType/IDSHORT
 idShort of a referable element

 [http://admin-shell.io/aas/3/0/RC01/LocalKeyType/IDSHORT](http://admin-shell.io/aas/3/0/RC01/LocalKeyType/IDSHORT) The LocalKeyType IDSHORT of the LocalKeyType class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ModelingKind
 Enumeration for denoting whether an element is a type or an instance.

 [http://admin-shell.io/aas/3/0/RC01/ModelingKind](http://admin-shell.io/aas/3/0/RC01/ModelingKind) The ModelingKind class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ModelingKind/INSTANCE
 Concrete, clearly identifiable component of a certain template.

 [http://admin-shell.io/aas/3/0/RC01/ModelingKind/INSTANCE](http://admin-shell.io/aas/3/0/RC01/ModelingKind/INSTANCE) The NamedIndividual INSTANCE of the ModelingKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ModelingKind/TEMPLATE
 Software element which specifies the common attributes shared by all instances of the template.

 [http://admin-shell.io/aas/3/0/RC01/ModelingKind/TEMPLATE](http://admin-shell.io/aas/3/0/RC01/ModelingKind/TEMPLATE) The NamedIndividual TEMPLATE of the ModelingKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## MultiLanguageProperty
 A property is a data element that has a multi language value.

 [http://admin-shell.io/aas/3/0/RC01/MultiLanguageProperty](http://admin-shell.io/aas/3/0/RC01/MultiLanguageProperty) The MultiLanguageProperty class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## MultiLanguageProperty/value
 The value of the property instance.
 
 [https://admin-shell.io/aas/3/0/RC01/MultiLanguageProperty/value](https://admin-shell.io/aas/3/0/RC01/MultiLanguageProperty/value) The attribute value of the MultiLanguageProperty class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## MultiLanguageProperty/valueId
 Reference to the global unqiue id of a coded value.
 
 [https://admin-shell.io/aas/3/0/RC01/MultiLanguageProperty/valueId](https://admin-shell.io/aas/3/0/RC01/MultiLanguageProperty/valueId) The attribute valueId of the MultiLanguageProperty class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ObjectAttributes
 A set of data elements that describe object attributes. These attributes need to refer to a data element within an existing submodel.

 [http://admin-shell.io/aas/3/0/RC01/ObjectAttributes](http://admin-shell.io/aas/3/0/RC01/ObjectAttributes) The ObjectAttributes class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ObjectAttributes/objectAttribute
 A data elements that further classifies an object.

 [http://admin-shell.io/aas/3/0/RC01/ObjectAttributes/objectAttribute](http://admin-shell.io/aas/3/0/RC01/ObjectAttributes/objectAttribute) The attribute objectAttribute of the ObjectAttributes class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Operation
 An operation is a submodel element with input and output variables.

 [http://admin-shell.io/aas/3/0/RC01/Operation](http://admin-shell.io/aas/3/0/RC01/Operation) The Operation class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Operation/inoutputVariable
 Parameter that is input and output of the operation.

 [http://admin-shell.io/aas/3/0/RC01/Operation/inoutputVariable](http://admin-shell.io/aas/3/0/RC01/Operation/inoutputVariable) The attribute inoutputVariable of the Operation class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Operation/inputVariable
 Input parameter of the operation.

 [http://admin-shell.io/aas/3/0/RC01/Operation/inputVariable](http://admin-shell.io/aas/3/0/RC01/Operation/inputVariable) The attribute inputVariable of the Operation class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Operation/outputVariable
 Output parameter of the operation.

 [http://admin-shell.io/aas/3/0/RC01/Operation/outputVariable](http://admin-shell.io/aas/3/0/RC01/Operation/outputVariable) The attribute outputVariable of the Operation class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## OperationVariable
 

 [http://admin-shell.io/aas/3/0/RC01/OperationVariable](http://admin-shell.io/aas/3/0/RC01/OperationVariable) The OperationVariable class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## OperationVariable/value
 Describes the needed argument for an operation via a submodel element of kind=Template.

 [http://admin-shell.io/aas/3/0/RC01/OperationVariable/value](http://admin-shell.io/aas/3/0/RC01/OperationVariable/value) The attribute value of the OperationVariable class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Permission
 Description of a single permission.

 [http://admin-shell.io/aas/3/0/RC01/Permission](http://admin-shell.io/aas/3/0/RC01/Permission) The Permission class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Permission/kindOfPermission
 Description of the kind of permission. Possible kind of permission also include the denial of the permission.

 [http://admin-shell.io/aas/3/0/RC01/Permission/kindOfPermission](http://admin-shell.io/aas/3/0/RC01/Permission/kindOfPermission) The attribute kindOfPermission of the Permission class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Permission/permission
 Reference to a property that defines the semantics of the permission.

 [http://admin-shell.io/aas/3/0/RC01/Permission/permission](http://admin-shell.io/aas/3/0/RC01/Permission/permission) The attribute permission of the Permission class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PermissionKind
 Enumeration of the kind of permissions that is given to the assignment of a permission to a subject.

 [http://admin-shell.io/aas/3/0/RC01/PermissionKind](http://admin-shell.io/aas/3/0/RC01/PermissionKind) The PermissionKind class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PermissionKind/ALLOW
 Allow the permission given to the subject.

 [http://admin-shell.io/aas/3/0/RC01/PermissionKind/ALLOW](http://admin-shell.io/aas/3/0/RC01/PermissionKind/ALLOW) The PermissionKind ALLOW of the PermissionKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PermissionKind/DENY
 Explicitly deny the permission given to the subject.

 [http://admin-shell.io/aas/3/0/RC01/PermissionKind/DENY](http://admin-shell.io/aas/3/0/RC01/PermissionKind/DENY) The PermissionKind DENY of the PermissionKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PermissionKind/NOT_APPLICABLE
 The permission is not applicable to the subject.

 [http://admin-shell.io/aas/3/0/RC01/PermissionKind/NOT_APPLICABLE](http://admin-shell.io/aas/3/0/RC01/PermissionKind/NOT_APPLICABLE) The PermissionKind NOT_APPLICABLE of the PermissionKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PermissionKind/UNDEFINED
 It is undefined whether the permission is allowed, not applicable or denied to the subject.

 [http://admin-shell.io/aas/3/0/RC01/PermissionKind/UNDEFINED](http://admin-shell.io/aas/3/0/RC01/PermissionKind/UNDEFINED) The PermissionKind UNDEFINED of the PermissionKind class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PermissionsPerObject
 Table that defines access permissions for a specified object. The object is any referable element in the AAS. Additionally object attributes can be defined that further specify the kind of object the permissions apply to.

 [http://admin-shell.io/aas/3/0/RC01/PermissionsPerObject](http://admin-shell.io/aas/3/0/RC01/PermissionsPerObject) The PermissionsPerObject class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PermissionsPerObject/object
 Element to which permission shall be assigned.

 [http://admin-shell.io/aas/3/0/RC01/PermissionsPerObject/object](http://admin-shell.io/aas/3/0/RC01/PermissionsPerObject/object) The attribute object of the PermissionsPerObject class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PermissionsPerObject/Permission
 Permissions assigned to the object. The permissions hold for all subjects as specified in the access permission rule.

 [http://admin-shell.io/aas/3/0/RC01/PermissionsPerObject/Permission](http://admin-shell.io/aas/3/0/RC01/PermissionsPerObject/Permission) The attribute Permission of the PermissionsPerObject class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PermissionsPerObject/targetObjectAttributes
 Target object attributes that need to be fulfilled so that the access permissions apply to the accessing subject.

 [http://admin-shell.io/aas/3/0/RC01/PermissionsPerObject/targetObjectAttributes](http://admin-shell.io/aas/3/0/RC01/PermissionsPerObject/targetObjectAttributes) The attribute targetObjectAttributes of the PermissionsPerObject class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PolicyAdministrationPoint
 Definition of a security administration point (PDP).

 [http://admin-shell.io/aas/3/0/RC01/PolicyAdministrationPoint](http://admin-shell.io/aas/3/0/RC01/PolicyAdministrationPoint) The PolicyAdministrationPoint class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PolicyAdministrationPoint/externalAccessControl
 Endpoint to an external access control defining a policy administration point to be used by the AAS.

 [http://admin-shell.io/aas/3/0/RC01/PolicyAdministrationPoint/externalAccessControl](http://admin-shell.io/aas/3/0/RC01/PolicyAdministrationPoint/externalAccessControl) The attribute externalAccessControl of the PolicyAdministrationPoint class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PolicyAdministrationPoint/localAccessControl
 The policy administration point of access control as realized by the AAS itself.

 [http://admin-shell.io/aas/3/0/RC01/PolicyAdministrationPoint/localAccessControl](http://admin-shell.io/aas/3/0/RC01/PolicyAdministrationPoint/localAccessControl) The attribute localAccessControl of the PolicyAdministrationPoint class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PolicyDecisionPoint
 Defines the security policy decision points (PDP). 

 [http://admin-shell.io/aas/3/0/RC01/PolicyDecisionPoint](http://admin-shell.io/aas/3/0/RC01/PolicyDecisionPoint) The PolicyDecisionPoint class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PolicyEnforcementPoint
 Defines the security policy enforcement points (PEP).

 [http://admin-shell.io/aas/3/0/RC01/PolicyEnforcementPoint](http://admin-shell.io/aas/3/0/RC01/PolicyEnforcementPoint) The PolicyEnforcementPoint class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PolicyEnforcementPoint/externalPolicyDecisionPoint
 If externalPolicyDecisionPoints True then Endpoints to external available decision points taking into consideration for access control for the AAS need to be configured.

 [http://admin-shell.io/aas/3/0/RC01/PolicyEnforcementPoint/externalPolicyDecisionPoint](http://admin-shell.io/aas/3/0/RC01/PolicyEnforcementPoint/externalPolicyDecisionPoint) The attribute externalPolicyDecisionPoint of the PolicyEnforcementPoint class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PolicyEnforcementPoint/externalPolicyEnforcementPoint
 If externalPolicyEnforcementPoint True then an Endpoint to external available enforcement point taking needs to be configured for the AAS.

 [http://admin-shell.io/aas/3/0/RC01/PolicyEnforcementPoint/externalPolicyEnforcementPoint](http://admin-shell.io/aas/3/0/RC01/PolicyEnforcementPoint/externalPolicyEnforcementPoint) The attribute externalPolicyEnforcementPoint of the PolicyEnforcementPoint class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PolicyInformationPoints
 Defines the security policy information points (PIP). Serves as the retrieval source of attributes, or the data required for policy evaluation to provide the information needed by the policy decision point to make the decisions.

 [http://admin-shell.io/aas/3/0/RC01/PolicyInformationPoints](http://admin-shell.io/aas/3/0/RC01/PolicyInformationPoints) The PolicyInformationPoints class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PolicyInformationPoints/externalInformationPoint
 Endpoints to external available information points taking into consideration for access control for the AAS.

 [http://admin-shell.io/aas/3/0/RC01/PolicyInformationPoints/externalInformationPoint](http://admin-shell.io/aas/3/0/RC01/PolicyInformationPoints/externalInformationPoint) The attribute externalInformationPoint of the PolicyInformationPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## PolicyInformationPoints/internalInformationPoint
 References to submodels defining information used by security access permission rules.

 [http://admin-shell.io/aas/3/0/RC01/PolicyInformationPoints/internalInformationPoint](http://admin-shell.io/aas/3/0/RC01/PolicyInformationPoints/internalInformationPoint) The attribute internalInformationPoint of the PolicyInformationPoints class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Property
 A property is a data element that has a single value.

 [http://admin-shell.io/aas/3/0/RC01/Property](http://admin-shell.io/aas/3/0/RC01/Property) The Property class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Property/category
 The following categories are defined for properties and multi-language properties: CONSTANT, PARAMETER, and VARIABLE.
 
 [https://admin-shell.io/aas/3/0/RC01/Property/category](https://admin-shell.io/aas/3/0/RC01/Property/category) The attribute category of the Property class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Property/value
 The value of the property instance.
 
 [https://admin-shell.io/aas/3/0/RC01/Property/value](https://admin-shell.io/aas/3/0/RC01/Property/value) The attribute value of the Property class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Property/propertyValueId
 Reference to the global unqiue id of a coded value.

 [http://admin-shell.io/aas/3/0/RC01/Property/propertyValueId](http://admin-shell.io/aas/3/0/RC01/Property/propertyValueId) The attribute propertyValueId of the Property class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Qualifiable
 Additional qualification of a qualifiable element.

 [http://admin-shell.io/aas/3/0/RC01/Qualifiable](http://admin-shell.io/aas/3/0/RC01/Qualifiable) The Qualifiable class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Qualifiable/qualifier
 Additional qualification of a qualifiable element.

 [http://admin-shell.io/aas/3/0/RC01/Qualifiable/qualifier](http://admin-shell.io/aas/3/0/RC01/Qualifiable/qualifier) The attribute qualifier of the Qualifiable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Qualifier
 A qualifier is a type-value pair that makes additional statements w.r.t. the value of the element.

 [http://admin-shell.io/aas/3/0/RC01/Qualifier](http://admin-shell.io/aas/3/0/RC01/Qualifier) The Qualifier class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Qualifier/type
 The qualifier type describes the type of the qualifier that is applied to the element.

 [http://admin-shell.io/aas/3/0/RC01/Qualifier/type](http://admin-shell.io/aas/3/0/RC01/Qualifier/type) The attribute type of the Qualifier class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Qualifier/value
 The qualifier value is the value of the qualifier.

 [http://admin-shell.io/aas/3/0/RC01/Qualifier/value](http://admin-shell.io/aas/3/0/RC01/Qualifier/value) The attribute value of the Qualifier class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Qualifier/valueId
 Reference to the global unqiue id of a coded value.

 [http://admin-shell.io/aas/3/0/RC01/Qualifier/valueId](http://admin-shell.io/aas/3/0/RC01/Qualifier/valueId) The attribute valueId of the Qualifier class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Range
 An element that is referable by its idShort. This id is not globally unique. This id is unique within the name space of the element.

 [http://admin-shell.io/aas/3/0/RC01/Range](http://admin-shell.io/aas/3/0/RC01/Range) The Range class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Range/max
 The maximum value of the range.

 [http://admin-shell.io/aas/3/0/RC01/Range/max](http://admin-shell.io/aas/3/0/RC01/Range/max) The attribute max of the Range class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Range/min
 The minimum value of the range.

 [http://admin-shell.io/aas/3/0/RC01/Range/min](http://admin-shell.io/aas/3/0/RC01/Range/min) The attribute min of the Range class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Referable
 An element that is referable by its idShort. This id is not globally unique. This id is unique within the name space of the element.

 [http://admin-shell.io/aas/3/0/RC01/Referable](http://admin-shell.io/aas/3/0/RC01/Referable) The Referable class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Referable/category
 The category is a value that gives further meta information w.r.t. to the class of the element. It affects the expected existence of attributes and the applicability of constraints.

 [http://admin-shell.io/aas/3/0/RC01/Referable/category](http://admin-shell.io/aas/3/0/RC01/Referable/category) The attribute category of the Referable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Referable/description
 Description or comments on the element. The description can be provided in several languages.

 [http://admin-shell.io/aas/3/0/RC01/Referable/description](http://admin-shell.io/aas/3/0/RC01/Referable/description) The attribute description of the Referable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Referable/displayName
 Display name. Can be provided in several languages.

[https://admin-shell.io/aas/3/0/RC01/Referable/displayName](https://admin-shell.io/aas/3/0/RC01/Referable/displayName) The attribute displayName of the Referable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Referable/idShort
 Identifying string of the element within its name space.

 [http://admin-shell.io/aas/3/0/RC01/Referable/idShort](http://admin-shell.io/aas/3/0/RC01/Referable/idShort) The attribute idShort of the Referable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Referable/parent
 Reference to the next referable parent element of the element. Constraint AASd-004: Add parent in case of non-identifiable elements.

 [http://admin-shell.io/aas/3/0/RC01/Referable/parent](http://admin-shell.io/aas/3/0/RC01/Referable/parent) The attribute parent of the Referable class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements
 Enumeration of all referable elements within an asset administration shell. Contains IdentifiableElements

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements](http://admin-shell.io/aas/3/0/RC01/ReferableElements) The ReferableElements class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/ACCESS_PERMISSION_RULE
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/ACCESS_PERMISSION_RULE](http://admin-shell.io/aas/3/0/RC01/ReferableElements/ACCESS_PERMISSION_RULE) The ReferableElements ACCESS_PERMISSION_RULE of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/ANNOTATED_RELATIONSHIP_ELEMENT
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/ANNOTATED_RELATIONSHIP_ELEMENT](http://admin-shell.io/aas/3/0/RC01/ReferableElements/ANNOTATED_RELATIONSHIP_ELEMENT) The ReferableElements ANNOTATED_RELATIONSHIP_ELEMENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/BASIC_EVENT
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/BASIC_EVENT](http://admin-shell.io/aas/3/0/RC01/ReferableElements/BASIC_EVENT) The ReferableElements BASIC_EVENTT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/BLOB
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/BLOB](http://admin-shell.io/aas/3/0/RC01/ReferableElements/BLOB) The ReferableElements BLOB of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/CAPABILITY

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/CAPABILITY](http://admin-shell.io/aas/3/0/RC01/ReferableElements/CAPABILITY) The ReferableElements CAPABILITY of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/CONCEPT_DICTIONARY
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/CONCEPT_DICTIONARY](http://admin-shell.io/aas/3/0/RC01/ReferableElements/CONCEPT_DICTIONARY) The ReferableElements CONCEPT_DICTIONARY of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/DATA_ELEMENT
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/DATA_ELEMENT](http://admin-shell.io/aas/3/0/RC01/ReferableElements/DATA_ELEMENT) The ReferableElements DATA_ELEMENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/ENTITY
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/ENTITY](http://admin-shell.io/aas/3/0/RC01/ReferableElements/ENTITY) The ReferableElements ENTITY of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/EVENT
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/EVENT](http://admin-shell.io/aas/3/0/RC01/ReferableElements/EVENT) The ReferableElements EVENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElement/MULTI_LANGUAGE_PROPERTY
 Property with a value that can be provided in multiple languages.

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/MULTI_LANGUAGE_PROPERTY](http://admin-shell.io/aas/3/0/RC01/ReferableElements/MULTI_LANGUAGE_PROPERTY) The ReferableElements MULTI_LANGUAGE_PROPERTY of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/OPERATION
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/OPERATION](http://admin-shell.io/aas/3/0/RC01/ReferableElements/OPERATION) The ReferableElements OPERATION of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/PROPERTY
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/PROPERTY](http://admin-shell.io/aas/3/0/RC01/ReferableElements/PROPERTY) The ReferableElements PROPERTY of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/RANGE
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/RANGE](http://admin-shell.io/aas/3/0/RC01/ReferableElements/RANGE) The ReferableElements RANGE of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/REFERENCE_ELEMENT
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/REFERENCE_ELEMENT](http://admin-shell.io/aas/3/0/RC01/ReferableElements/REFERENCE_ELEMENT) The ReferableElements REFERENCE_ELEMENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/RELATIONSHIPT_ELEMENT
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/RELATIONSHIPT_ELEMENT](http://admin-shell.io/aas/3/0/RC01/ReferableElements/RELATIONSHIPT_ELEMENT) The ReferableElements RELATIONSHIPT_ELEMENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/SUBMODEL_ELEMENT_COLLECTION
 Collection of Submodel Elements

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/SUBMODEL_ELEMENT_COLLECTION](http://admin-shell.io/aas/3/0/RC01/ReferableElements/SUBMODEL_ELEMENT_COLLECTION) The ReferableElements SUBMODEL_ELEMENT_COLLECTION of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/SUBMODEL_ELEMENT
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/SUBMODEL_ELEMENT](http://admin-shell.io/aas/3/0/RC01/ReferableElements/SUBMODEL_ELEMENT) The ReferableElements SUBMODEL_ELEMENT of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferableElements/VIEW
 

 [http://admin-shell.io/aas/3/0/RC01/ReferableElements/VIEW](http://admin-shell.io/aas/3/0/RC01/ReferableElements/VIEW) The ReferableElements VIEW of the ReferableElements class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Reference
 Reference to either a model element of the same or another AAs or to an external entity. A reference is an ordered list of keys, each key referencing an element. The complete list of keys may for example be concatenated to a path that then gives unique access to an element or entity.

 [http://admin-shell.io/aas/3/0/RC01/Reference](http://admin-shell.io/aas/3/0/RC01/Reference) The Reference class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Reference/key
 Unique reference in its name space.
 
 [https://admin-shell.io/aas/3/0/RC01/Reference/key](https://admin-shell.io/aas/3/0/RC01/Reference/key) The attribute key of the Reference class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## ReferenceElement
 A reference element is a data element that defines a logical reference to another element within the same or another AAS or a reference to an external object or entity.

 [http://admin-shell.io/aas/3/0/RC01/ReferenceElement](http://admin-shell.io/aas/3/0/RC01/ReferenceElement) The ReferenceElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## RelationshipElement
 

 [http://admin-shell.io/aas/3/0/RC01/RelationshipElement](http://admin-shell.io/aas/3/0/RC01/RelationshipElement) The RelationshipElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## RelationshipElement/first
 First element in the relationship taking the role of the subject.

 [http://admin-shell.io/aas/3/0/RC01/RelationshipElement/first](http://admin-shell.io/aas/3/0/RC01/RelationshipElement/first) The attribute first of the RelationshipElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## RelationshipElement/second
 Second element in the relationship taking the role of the object.

 [http://admin-shell.io/aas/3/0/RC01/RelationshipElement/second](http://admin-shell.io/aas/3/0/RC01/RelationshipElement/second) The attribute second of the RelationshipElement class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Security
 Container for security relevant information of the AAS.

 [http://admin-shell.io/aas/3/0/RC01/Security](http://admin-shell.io/aas/3/0/RC01/Security) The Security class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Security/accessControlPolicyPoints
 Access control policy points of the AAS.

 [http://admin-shell.io/aas/3/0/RC01/Security/accessControlPolicyPoints](http://admin-shell.io/aas/3/0/RC01/Security/accessControlPolicyPoints) The attribute accessControlPolicyPoints of the Security class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Security/certificate
 Certificates of the AAS.

 [http://admin-shell.io/aas/3/0/RC01/Security/certificate](http://admin-shell.io/aas/3/0/RC01/Security/certificate) The attribute certificate of the Security class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Security/requiredCertificateExtension
 Certificate extensions as required by the AAS.

 [http://admin-shell.io/aas/3/0/RC01/Security/requiredCertificateExtension](http://admin-shell.io/aas/3/0/RC01/Security/requiredCertificateExtension) The attribute requiredCertificateExtension of the Security class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## SubjectAttributes
 A set of data elements that further classifies a specific subject.

 [http://admin-shell.io/aas/3/0/RC01/SubjectAttributes](http://admin-shell.io/aas/3/0/RC01/SubjectAttributes) The SubjectAttributes class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## SubjectAttributes/subjectAttribute
 A data element that further classifies a specific subject.

 [http://admin-shell.io/aas/3/0/RC01/SubjectAttributes/subjectAttribute](http://admin-shell.io/aas/3/0/RC01/SubjectAttributes/subjectAttribute) The attribute subjectAttribute of the SubjectAttributes class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Submodel
 A Submodel defines a specific aspect of the asset represented by the AAS. A submodel is used to structure the virtual representation and technical functionality of an Administration Shell into distinguishable parts. Each submodel refers to a well-defined domain or subject matter. Submodels can become standardized and thus become submodels types. Submodels can have different life-cycles.

 [http://admin-shell.io/aas/3/0/RC01/Submodel](http://admin-shell.io/aas/3/0/RC01/Submodel) The Submodel class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## Submodel/submodelElement
 A submodel consists of zero or more submodel elements.

 [http://admin-shell.io/aas/3/0/RC01/Submodel/submodelElement](http://admin-shell.io/aas/3/0/RC01/Submodel/submodelElement) The attribute submodelElement of the Submodel class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## SubmodelElement
 A submodel element is an element suitable for the description and differentiation of assets.

 [http://admin-shell.io/aas/3/0/RC01/SubmodelElement](http://admin-shell.io/aas/3/0/RC01/SubmodelElement) The SubmodelElement class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## SubmodelElementCollection
 A submodel element collection is a set or list of submodel elements.

 [http://admin-shell.io/aas/3/0/RC01/SubmodelElementCollection](http://admin-shell.io/aas/3/0/RC01/SubmodelElementCollection) The SubmodelElementCollection class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## SubmodelElementCollection/allowDuplicates
 If allowDuplicates=true then it is allowed that the collection contains the same element several times. Default = false

 [http://admin-shell.io/aas/3/0/RC01/SubmodelElementCollection/allowDuplicates](http://admin-shell.io/aas/3/0/RC01/SubmodelElementCollection/allowDuplicates) The attribute allowDuplicates of the SubmodelElementCollection class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## SubmodelElementCollection/ordered
 If ordered=false then the elements in the property collection are not ordered. If ordered=true then the elements in the collection are ordered. Default = false

 [http://admin-shell.io/aas/3/0/RC01/SubmodelElementCollection/ordered](http://admin-shell.io/aas/3/0/RC01/SubmodelElementCollection/ordered) The attribute ordered of the SubmodelElementCollection class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## SubmodelElementCollection/value
 Submodel element contained in the collection.
 
 [https://admin-shell.io/aas/3/0/RC01/SubmodelElementCollection/value](https://admin-shell.io/aas/3/0/RC01/SubmodelElementCollection/value)The attribute value of the SubmodelElementCollection class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.

## View
 Different views associated to the Administration Shell via the Submodels

 [http://admin-shell.io/aas/3/0/RC01/View](http://admin-shell.io/aas/3/0/RC01/View) The View class as defined in Details of the 'Asset Administration Shell - Part 1 - Version 3.0RC01'.

## View/containedElement
 Referable elements that are contained in the view.

 [http://admin-shell.io/aas/3/0/RC01/View/containedElement](http://admin-shell.io/aas/3/0/RC01/View/containedElement) The attribute containedElement of the View class as defined in 'Details of the Asset Administration Shell - Part 1 - Version 3.0RC01'.





## Contact

This subnamespace was created by the [Plattform Industrie 4.0](http://www.plattform-i40.de/). The [Coordination Board Submodels](mailto:coordination-board@admin-shell.io) maintains these identifiers.
