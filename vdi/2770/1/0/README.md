# VDI 2770 Paper 1 (Version 1.0)

This sub-namespace collects the identifiers defined in the VDI specification 2770 Paper 1.

## Introduction

The VDI2770-1 standardizes the documentation in regard to their metadata, classification and format. The idea is that manufacturer handover their documentation in this standardized manner, so that it gets easier for the operator to load the documentation for a component or a complete machine (asset) into their IT infrastructure and, subsequently, that is gets easier to find relevant documents during the operation phase of an asset. The central concepts of the specification are the entities of Document and DocumentVersion, that are described in an UML and XML specification.

## Status: `submitted`
See the Submodel Template 'Minimum requirements for the Handover documentation from the manufacturer to the operator based on the VDI 2770 specification'.



## ManufacturerDocumentation (Submodel Template)

[http://admin-shell.io/vdi/2770/1/0/ManufacturerDocumentation](http://admin-shell.io/vdi/2770/1/0/ManufacturerDocumentation) is the Submodel defining a set of manufacturer documentation to bring about information from manufacturer to operator of industrial equipment.


## Document (SubmodelElementCollection)

This SubmodelElementCollection holds the information for a VDI2770 Document entity.

[http://admin-shell.io/vdi/2770/1/0/Document](http://admin-shell.io/vdi/2770/1/0/Document)


## DocumentId/Id (Property)

Identification of the Document within a given domain, e.g. the providing organisation.

[http://admin-shell.io/vdi/2770/1/0/DocumentId/Id](http://admin-shell.io/vdi/2770/1/0/DocumentId/Id)



## DocumentId/isPrimary (Property)

True, if the DocumentId is the primary document id of the document.

[http://admin-shell.io/vdi/2770/1/0/DocumentId/Id](http://admin-shell.io/vdi/2770/1/0/DocumentId/Id)


## DocumentClassification/ClassId (Property)

Unique ID of the class of the Document within the ClassficationSystem of VDI2770:2018.

[http://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassId](http://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassId)


## DocumentClassification/ClassName (Property)

List of language-dependent names of the selected ClassID.
If the DocumentClassificationSystem is set to “VDI2770:2018” then the given names of ClassificationSystem of VDI2770:2018 need be used.

[http://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassName](http://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassName)



## DocumentClassification/ClassName (Property)

List of language-dependent names of the selected ClassID.
If the DocumentClassificationSystem is set to “VDI2770:2018” then the given names of ClassificationSystem of VDI2770:2018 need be used.

[http://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassificationSystem](http://admin-shell.io/vdi/2770/1/0/DocumentClassification/ClassificationSystem)


## Document/ReferencedObject (Property)

List of IDs for an object to which the document refers.

[http://admin-shell.io/vdi/2770/1/0/Document/ReferencedObject](http://admin-shell.io/vdi/2770/1/0/Document/ReferencedObject)



## DocumentVersion (SubmodelElementCollection)

Information elements of individual VDI 2770-1 DocumentVersion entities.

[http://admin-shell.io/vdi/2770/1/0/DocumentVersion](http://admin-shell.io/vdi/2770/1/0/DocumentVersion)


## DocumentVersion/DocumentVersionId (Property)

Unambigous identification of a DocumentVersion within a set of DocumentVersions of a Document.

[http://admin-shell.io/vdi/2770/1/0/DocumentVersion/DocumentVersionId](http://admin-shell.io/vdi/2770/1/0/DocumentVersion/DocumentVersionId)


## Description/Title (MLP)

List of language-dependent titles of the Document.

[http://admin-shell.io/vdi/2770/1/0/Description/Title](http://admin-shell.io/vdi/2770/1/0/Description/Title)

## DocumentDescription/Summary (MLP)

List of language-dependent summaries of the Document.

[
http://admin-shell.io/vdi/2770/1/0/DocumentDescription/Summary](
http://admin-shell.io/vdi/2770/1/0/DocumentDescription/Summary)


## DocumentDescription/KeyWords (MLP)

List of language-dependent keywords of the Document.

[
http://admin-shell.io/vdi/2770/1/0/DocumentDescription/KeyWords](
http://admin-shell.io/vdi/2770/1/0/DocumentDescription/KeyWords)


## LifeCycleStatus/SetDate (Property)

Date when the document was introduced into the AAS or set to its status. Format is YYYY-MM-dd.

[
http://admin-shell.io/vdi/2770/1/0/LifeCycleStatus/SetDate](
http://admin-shell.io/vdi/2770/1/0/LifeCycleStatus/SetDate)


## LifeCycleStatus/StatusValue (Property)

Each document version represents a point in time in the document life cycle. This status value refers to the milestones in the document life cycle. The following two values should be used for the application of

[http://admin-shell.io/vdi/2770/1/0/LifeCycleStatus/StatusValue](http://admin-shell.io/vdi/2770/1/0/LifeCycleStatus/StatusValue)


## Party/Role (Property)

Defined role of the organisation according to the following selection list: Author, Customer, Supplier, Manufacturer, Responsible.

[http://admin-shell.io/vdi/2770/1/0/Party/Role](http://admin-shell.io/vdi/2770/1/0/Party/Role)



## Organization/OrganizationName (Property)

Commonly used designation of the organisation providing the manufacturer information, that is, often, the manufacturer.

[http://admin-shell.io/vdi/2770/1/0/Organization/OrganizationName](http://admin-shell.io/vdi/2770/1/0/Organization/OrganizationName)


## Organization/OrganizationOfficialName (Property)

Official name of the organisation providing the manufacturer information, that is, often, the manufacturer.

[http://admin-shell.io/vdi/2770/1/0/Organization/OrganizationOfficialName](http://admin-shell.io/vdi/2770/1/0/Organization/OrganizationOfficialName)




## StoredDocumentRepresentation/DigitalFile (File)

MIME-Type, file name and file contents given by the File SubmodelElement.

http://admin-shell.io/vdi/2770/1/0/StoredDocumentRepresentation/DigitalFile






## Contact

This sub-namespace is proposed by [Sebastian Bader](https://github.com/sebbader). See also [Fraunhofer IAIS](https://iais.fraunhofer.de/) or contact via [email](mailto:contact@ids.fraunhofer.de).