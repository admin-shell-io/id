# Asset Interfaces Description – Identifiers

This Submodel specifies an information model and a common representation for describing the interface(s) of an asset service or asset-related service. Based on this information, it is possible to initiate a connection to such a service and start to request or subscribe to served datapoints, and/or perform operations



## Introduction

The Asset Interfaces Description (AID) in version 1.0 supports the description of interfaces based on the following specific protocols: 
* Modbus
* HTTP
* MQTT
* OPC UA
* BACnet
  
Informative, the IO-Link protocol that is bridged to REST/HTTP and PROFINET is introduced in AID 1.2 in Annex B. Any other protocols and interfaces will be addressed in upcoming versions of the AID. 
The W3C Web of Things Thing Description (WoT TD) as an open, royalty-free standard is considered as a baseline for the content and structure of the definition of this Submodel template. The protocol-specific information is taken from the official WoT bindings that are maintained by the W3C or other SDOs like the OPC Foundation (e.g., OPC 10101 for OPC UA Binding).  
In addition to the protocol-specific information provided by the AID, it also provides the ability to reference external descriptors such as GSD, GSDML, IO Device Description, native WoT TD (as a supplement), etc. These external descriptors are not restricted to the protocols currently defined in AID.
As a complement to the AID, an Asset Interfaces Mapping Configuration (AIMC) Submodel can be used to map the received data from the asset services to a specific place within an AAS (e.g., an application-specific Submodel to monitor data). The principal scope and use of the AID Submodel in combination with an AIMC 



## Status: `Accepted`
The sub-namespace for Asset Interface Description and its identifiers have been finalized in the Taskforce `Asset Interface Description`.

## Versions: 1.0
This version is the first version to be officially published by IDTA Document `IDTA 02017 Asset Interfaces Description`.


## Interface (SMC)
This SubmodelElementCollection holds the information for EndpointMetadata, InteractionMetadata and ExternalDescriptor.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/Interface

### title (Property)
Provides a human-readable title.
https://www.w3.org/2019/wot/td#title

### created (Property)
Provides creation timestamp.
http://purl.org/dc/terms/created

### modified (Property)
Provides modification timestamp.
http://purl.org/dc/terms/modified

### support (Property)
Contact information.
https://www.w3.org/2019/wot/td#support

### EndpointMetadata (SMC)
Metadata of the interface endpoint.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/EndpointMetadata

### InteractionMetadata (SMC)
Metadata describing datapoints and functions.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/InteractionMetadata

### ExternalDescriptor (SMC)
Descriptor file references.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/ExternalDescriptor

---

## EndpointMetadata (SMC)
Holds information about the endpoint.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/EndpointMetadata

### base (Property)
Defines base URI.
https://www.w3.org/2019/wot/td#baseURI

### contentType (Property)
Defines content type.
https://www.w3.org/2019/wot/hypermedia#forContentType

### security (SML)
Security configuration.
https://www.w3.org/2019/wot/td#hasSecurityConfiguration

### modv_mostSignificantByte (Property)
Modbus byte order.
https://www.w3.org/2019/wot/modbus#hasMostSignificantByte

### modv_mostSignificantWord (Property)
Modbus word order.
https://www.w3.org/2019/wot/modbus#hasMostSignificantWord

### securityDefinitions (SMC)
Security scheme definitions.
https://www.w3.org/2019/wot/td#definesSecurityScheme

---

## InteractionMetadata (SMC)
Defines interaction affordances.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/InteractionMetadata

### properties (SMC)
Datapoint definitions.
https://www.w3.org/2019/wot/td#PropertyAffordance

### actions (SMC)
Function definitions.
https://www.w3.org/2019/wot/td#ActionAffordance

### events (SMC)
Event definitions.
https://www.w3.org/2019/wot/td#EventAffordance

---

## properties (SMC)
Collection of interaction properties.
https://www.w3.org/2019/wot/td#hasPropertyAffordance

---

## property_name (SMC)
Defines datapoint characteristics.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/PropertyDefinition

### key (Property)
Optional key.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/key

### title (Property)
Human-readable title.
https://www.w3.org/2019/wot/td#title

### observable (Property)
Observation indicator.
https://www.w3.org/2019/wot/td#isObservable

### forms (SMC)
Resource locations.
https://www.w3.org/2019/wot/td#hasForm

### type (Property)
Datatype indicator.
https://www.w3.org/1999/02/22-rdf-syntax-ns#type

### const (Property)
Constant value.
https://www.w3.org/2019/wot/json-schema#const

### enum (SML)
Restricted value list.
https://www.w3.org/2019/wot/json-schema#enum

### default (Property)
Default value.
https://www.w3.org/2019/wot/json-schema#default

### unit (Property)
Measurement unit.
https://schema.org/unitCode

### min_max (Range)
Numeric limits.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/minMaxRange

### lengthRange (Range)
String length range.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/lengthRange

### itemsRange (Range)
Array length limits.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/itemsRange

### items (SMC)
Array item schema.
https://www.w3.org/2019/wot/json-schema#items

### valueSemantics (Ref)
Semantic meaning.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/valueSemantics

---

## ExternalDescriptor (SMC)
Reference to external descriptors.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/ExternalDescriptor

### descriptorName (File)
Descriptor filename.
https://admin-shell.io/idta/AssetInterfacesDescription/1/0/externalDescriptorName


## Contact

This sub-namespace is proposed by [IDTA Working Group Nameplate for Asset Interface Description](https://github.com/admin-shell-io/submodel-templates/tree/main/published/Asset%20Interfaces%20Description). 
See also [IDTA Registered AAS Submodel Templates](https://industrialdigitaltwin.org/content-hub/teilmodelle#:~:text=Software%20Nameplate) or contact via email the [IDTA project manager for submodel templates](mailto:sudip.adhikari@idtwin.org) or [chair of the working group](mailto:sebastian.kaebisch@siemens.com).

