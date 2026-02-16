# VDI 2770 Paper 1 (Version 1.0)

This sub-namespace collects the identifiers defined in the VDI specification 2770 Paper 1.

## Introduction

The VDI2770-1 standardizes the documentation in regard to their metadata, classification and format. The idea is that manufacturer handover their documentation in this standardized manner, so that it gets easier for the operator to load the documentation for a component or a complete machine (asset) into their IT infrastructure and, subsequently, that is gets easier to find relevant documents during the operation phase of an asset. The central concepts of the specification are the entities of Document and DocumentVersion, that are described in an UML and XML specification.

## Status: `submitted`
See the Submodel Template 'Minimum requirements for the Handover documentation from the manufacturer to the operator based on the VDI 2770 specification'.



## ManufacturerDocumentation (Submodel Template)

[https://admin-shell.io/vdi/2770/1/0/ManufacturerDocumentation](https://admin-shell.io/vdi/2770/1/0/ManufacturerDocumentation) is the Submodel defining a set of manufacturer documentation to bring about information from manufacturer to operator of industrial equipment.

`superseded in Revision 1.1 by [https://admin-shell.io/vdi/2770/1/1/Documentation](https://admin-shell.io/vdi/2770/1/1/DocuDocumentation)'


## Document (SubmodelElementCollection)

Each SMC describes a Document, which is asscoated to the particular Asset Administration Shell

[https://admin-shell.io/vdi/2770/1/0/Document](https://admin-shell.io/vdi/2770/1/0/Document)


## Entity (Entity)

States, that the described Entity is an important entity for documentation of the superordinate Asset of the Asset Administration Shell.

[https://admin-shell.io/vdi/2770/1/0/Entity](https://admin-shell.io/vdi/2770/1/0/Entity)


## DocumentIdDomain (SubmodelElementCollection)

Set of information on the Document within a given domain, e.g. the providing organization.

[https://admin-shell.io/vdi/2770/1/0/DocumentIdDomain](https://admin-shell.io/vdi/2770/1/0/DocumentIdDomain)


## DocumentClassification (SubmodelElementCollection)

Set of information for describing the classification of the Document according to an well-identified ClassificationSystem.

[https://admin-shell.io/vdi/2770/1/0/Document
Classification](https://admin-shell.io/vdi/2770/1/0/DocumentClassification)


## DocumentVersion (SubmodelElementCollection)

Information elements of individual VDI 2770 DocumentVersion entities.

[https://admin-shell.io/vdi/2770/1/0/DocumentVersion](https://admin-shell.io/vdi/2770/1/0/DocumentVersion)


## Document/DocumentedEntity (Reference)

Identifies the Entity, which is subject to the Documentation.

[https://admin-shell.io/vdi/2770/1/0/Document/DocumentedEntity](https://admin-shell.io/vdi/2770/1/0/Document/DocumentedEntity)


## Document/RefersTo (Reference)

Forms a RefersTo-relationship to another Document. Typically, this other Document is a dependent document of the originating (main) document.

[https://admin-shell.io/vdi/2770/1/0/Document/RefersTo](https://admin-shell.io/vdi/2770/1/0/Document/RefersTo)


## Document/BasedOn (Reference)

Forms a BasedOn-relationship to another Document. Typically states, that this document bases on another document.

[https://admin-shell.io/vdi/2770/1/0/Document/BasedOn](https://admin-shell.io/vdi/2770/1/0/Document/BasedOn)


## Document/Affecting (Reference)

Forms an Affecting-relationship to another Document.

[https://admin-shell.io/vdi/2770/1/0/Document/Affecting](https://admin-shell.io/vdi/2770/1/0/Document/Affecting)


## Document/TranslationOf (Reference)

Forms a TranslationOf-relationship to another Document.

[https://admin-shell.io/vdi/2770/1/0/Document/TranslationOf](https://admin-shell.io/vdi/2770/1/0/Document/TranslationOf)


## Document/Comment (MultiLanguageProperty)

States a user-defined comment. Can be freely defined, even in multiple languages.

[https://admin-shell.io/vdi/2770/1/0/Document/Comment](https://admin-shell.io/vdi/2770/1/0/Document/Comment)


## DocumentIdDomain/DocumentDomainId (Property)

Identification of the Domain, e.g. the providing organization.

[https://admin-shell.io/vdi/2770/1/0/DocumentIdDomain/DocumentDomainId](https://admin-shell.io/vdi/2770/1/0/Document/IdDomainDocumentDomainId)


## DocumentIdDomain/DocumentId (Property)

Identification of the Document within a given domain, e.g. the providing organization.

[https://admin-shell.io/vdi/2770/1/0/DocumentIdDomain/DocumentId](https://admin-shell.io/vdi/2770/1/0/DocumentIdDomain/DocumentId)


## DocumentClassification/ClassId (Property)

Unique ID of the class of the Document within the ClassficationSystem of VDI2770:2018.

[https://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassId](https://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassId)


## DocumentClassification/ClassName (MultiLanguageProperty)

List of language-dependent names of the selected ClassID.

[https://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassName](https://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassName)


## DocumentClassification/ClassificationSystem (Property)

Identification of the classification system.

[https://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassificationSystem](https://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassificationSystem)


## DocumentVersion/Language (Property)

Each property codes one language identification according ISO 639-1 or ISO 639-2  of the languages used in the Document.

[https://admin-shell.io/vdi/2770/1/0/DocumentVersion/Language](https://admin-shell.io/vdi/2770/1/0/DocumentVersion/Language)


## DocumentVersion/DocumentVersionId (Property)

Unambigous identification of a DocumentVersion within a set of DocumentVersions of a Document.

[https://admin-shell.io/vdi/2770/1/0/DocumentVersion/DocumentVersionId](https://admin-shell.io/vdi/2770/1/0/DocumentVersion/DocumentVersionId)


## Description/Title (MLP)

List of language-dependent titles of the Document.

[https://admin-shell.io/vdi/2770/1/0/Description/Title](https://admin-shell.io/vdi/2770/1/0/Description/Title)


## DocumentDescription/Summary (MLP)

List of language-dependent summaries of the Document.

[
https://admin-shell.io/vdi/2770/1/0/DocumentDescription/Summary](
https://admin-shell.io/vdi/2770/1/0/DocumentDescription/Summary)


## DocumentDescription/KeyWords (MLP)

List of language-dependent keywords of the Document.

[
https://admin-shell.io/vdi/2770/1/0/DocumentDescription/KeyWords](
https://admin-shell.io/vdi/2770/1/0/DocumentDescription/KeyWords)


## LifeCycleStatus/SetDate (Property)

Date when the document was introduced into the AAS or set to its status. Format is YYYY-MM-dd.

[
https://admin-shell.io/vdi/2770/1/0/LifeCycleStatus/SetDate](
https://admin-shell.io/vdi/2770/1/0/LifeCycleStatus/SetDate)


## LifeCycleStatus/StatusValue (Property)

Each document version represents a point in time in the document life cycle. This status value refers to the milestones in the document life cycle. The following two values should be used for the application of

[https://admin-shell.io/vdi/2770/1/0/LifeCycleStatus/StatusValue](https://admin-shell.io/vdi/2770/1/0/LifeCycleStatus/StatusValue)


## Party/Role (Property)

Defined role of the organisation according to the following selection list: Author, Customer, Supplier, Manufacturer, Responsible.

[https://admin-shell.io/vdi/2770/1/0/Party/Role](https://admin-shell.io/vdi/2770/1/0/Party/Role)



## Organization/OrganizationName (Property)

Commonly used designation of the organisation providing the manufacturer information, that is, often, the manufacturer.

[https://admin-shell.io/vdi/2770/1/0/Organization/OrganizationName](https://admin-shell.io/vdi/2770/1/0/Organization/OrganizationName)


## Organization/OrganizationOfficialName (Property)

Official name of the organisation providing the manufacturer information, that is, often, the manufacturer.

[https://admin-shell.io/vdi/2770/1/0/Organization/OrganizationOfficialName](https://admin-shell.io/vdi/2770/1/0/Organization/OrganizationOfficialName)


## StoredDocumentRepresentation/DigitalFile (File)

MIME-Type, file name and file contents given by the File SubmodelElement.

[https://admin-shell.io/vdi/2770/1/0/StoredDocumentRepresentation/DigitalFile}(https://admin-shell.io/vdi/2770/1/0/StoredDocumentRepresentation/DigitalFile)


## StoredDocumentRepresentation/PreviewFile (File)

Provides a preview image of the Document, e.g. first page, in a commonly used image format and low resolution.

[https://admin-shell.io/vdi/2770/1/0/StoredDocumentRepresentation/PreviewFile](https://admin-shell.io/vdi/2770/1/0/StoredDocumentRepresentation/PreviewFile)





## Contact

This sub-namespace is proposed by [Sebastian Bader](https://github.com/sebbader). See also [Fraunhofer IAIS](https://iais.fraunhofer.de/) or contact via [email](mailto:contact@ids.fraunhofer.de).
