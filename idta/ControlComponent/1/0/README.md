# Control Component Type and Instance

The Control Component (CC) concept supports the engineering, deployment and orchestration of service-based and component-oriented industry 4.0 automation solutions. The term component in this document refers to a "modular, deployable, and replaceable part of a system that encapsulates implementation and exposes a set of interfaces" (IEV 741-01-11). In general, a physical device, machine or module can be considered as a component as well as software components, e.g. a function block. Both, the control and the component aspect are meant to be understood in an abstract manner and from a cybernetical viewpoint of the orchestration (process control) of industrial production processes.

## Introduction

There are two specifications defining how control component information should be modelled as Submodels:
- The `Control Component Type` Submodel to describe control component types and
- the `Control Component Instance` Submodel to describe their instances.

Thus, this sub-namespace covers concepts and its semantic ids for  both submodel templates.

## Status: `Submitted`
The sub-namespace for Control Component Type and Instance and its identifiers have been finalized in the respective Taskforce.

## Identifiers specific for Control Component Types

### ControlComponent/Type (Submodel)
[https://admin-shell.io/idta/ControlComponent/Type/1/0](https://admin-shell.io/idta/ControlComponent/Type/1/0)
A ControlComponentType Submodel

### ControlComponent/Type/Interfaces (SMC)
[https://admin-shell.io/idta/ControlComponent/Type/Interfaces/1/0](https://admin-shell.io/idta/ControlComponent/Type/Interfaces/1/0)
Collection of references to control interfaces supported by the component type, e.g. to elements of the Interface Metadata SMC of the Asset Interface Description submodel, the MTP submodel or OPC UA Server Datasheet submodel.

### ControlComponent/Type/Interface (Ref)
[https://admin-shell.io/idta/ControlComponent/Type/Interface/1/0](https://admin-shell.io/idta/ControlComponent/Type/Interface/1/0)
Reference to a single control interface. 

### ControlComponent/Type/Errors (SMC)
[https://admin-shell.io/idta/ControlComponent/Type/Errors/1/0](https://admin-shell.io/idta/ControlComponent/Type/Errors/1/0)
Collection of all possible error codes that may appear in components of this type.

### ControlComponent/Type/ErrorCode (MLP)
[https://admin-shell.io/idta/ControlComponent/Type/ErrorCode/1/0](https://admin-shell.io/idta/ControlComponent/Type/ErrorCode/1/0)
Semantic description of the error code in multiple languages. 


## Identifiers specific for Control Component Instances

### ControlComponent/Instance (Submodel)
[https://admin-shell.io/idta/ControlComponent/Instance/1/0](https://admin-shell.io/idta/ControlComponent/Instance/1/0) 
A ControlComponentInstance Submodel.

### ControlComponent/Instance/Endpoints (SMC)
[https://admin-shell.io/idta/ControlComponent/Instance/Endpoints/1/0](https://admin-shell.io/idta/ControlComponent/Instance/Endpoints/1/0)
Collection of references to control endpoints supported by the instance of the component.

### ControlComponent/Instance/Endpoint (SMC)
[https://admin-shell.io/idta/ControlComponent/Instance/Endpoint/1/0](https://admin-shell.io/idta/ControlComponent/Instance/Endpoints/1/0)
A reference to a control endpoint.

### ControlComponent/Instance/Type (Ref)
[https://admin-shell.io/idta/ControlComponent/Instance/Type/1/0](https://admin-shell.io/idta/ControlComponent/Instance/Type/1/0)
Reference between the component instance and its respective ControlComponentType Submodel.

## Common identifiers for both Control Component Types and Instances

### ControlComponent/Skills (SMC)
[https://admin-shell.io/idta/ControlComponent/Skills/1/0](https://admin-shell.io/idta/ControlComponent/Skills/1/0)
Collection of skills offered by the component type or instance.

### ControlComponent/Skill (SMC)
[https://admin-shell.io/idta/ControlComponent/Skill/1/0](https://admin-shell.io/idta/ControlComponent/Skill/1/0)
Contains the basic information to call (request the execution of) a skill, e.g. its signature.

### ControlComponent/Skill/Name (Property)
[https://admin-shell.io/idta/ControlComponent/Skill/Name/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Name/1/0)
Name used to select the skill via its interface.

### DisplayName (MLP)
[https://admin-shell.io/idta/ControlComponent/Skill/DisplayName/1/0](https://admin-shell.io/idta/ControlComponent/Skill/DisplayName/1/0)
Name to display the skill, e.g. in an HMI or GUI.

### ControlComponent/Skill/Disabled (Property)
[https://admin-shell.io/idta/ControlComponent/Skill/Disabled/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Disabled/1/0)
Boolean property that defines if the skill is (currently) disabled, e.g. not licensed, tested, suitable.

### ControlComponent/Skill/Modes (SMC)
[https://admin-shell.io/idta/ControlComponent/Skill/Modes/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Modes/1/0)
Collection of operation, operating, operational or execution modes (depending on the standard), in which the skill is available/allowed to execute.

### ControlComponent/Skill/Mode (Property)
[https://admin-shell.io/idta/ControlComponent/Skill/Mode/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Mode/1/0)
Name of the operation, operating, operational or execution modes (depending on the standard), in which the skill is available/allowed to execute.

### ControlComponent/Skill/Parameters (SMC)
[https://admin-shell.io/idta/ControlComponent/Skill/Parameters/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Parameters/1/0)
Collection of parameters used for the configuration of the skill.

### ControlComponent/Skill/Parameter (SMC)
[https://admin-shell.io/idta/ControlComponent/Skill/Parameter/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Parameter/1/0)
Parameter used for the configuration of the skill.

### ControlComponent/Skill/Parameter/Name (Property)
[https://admin-shell.io/idta/ControlComponent/Skill/Parameter/Name/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Parameter/Name/1/0)
Name of the parameter.

### ControlComponent/Skill/Parameter/Direction (Property)
[https://admin-shell.io/idta/ControlComponent/Skill/Parameter/Direction/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Parameter/Direction/1/0)
Indicates whether the parameter is an input (In) or an output (Out) of the skill. An InOut parameter can be set from outside and can also be changed from skill itself. 

### ControlComponent/Skill/Parameter/Type (Property)
[https://admin-shell.io/idta/ControlComponent/Skill/Parameter/Type/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Parameter/Type/1/0)
Data type as string used to interpret the parameter. 

### ControlComponent/Skill/Parameter/Values (SMC)
[https://admin-shell.io/idta/ControlComponent/Skill/Parameter/Values/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Parameter/Values/1/0)


### ControlComponent/Skill/Errors (SMC)
[https://admin-shell.io/idta/ControlComponent/Skill/Errors/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Errors/1/0)
Collection of references to the error codes of the component that may be triggered by this skill.

### ControlComponent/Skill/Uses (SMC)
[https://admin-shell.io/idta/ControlComponent/Skill/Uses/1/0](https://admin-shell.io/idta/ControlComponent/Skill/Uses/1/0)
Collection of references to other skills, that this skill uses.

## Versions: [1.0](1/0)
This version is the first version to be officially published by the IDTA Documents `IDTA 020015-1-0 Control Component Type` and `IDTA 020016-1-0 Control Component Instance`.

## Contact

This sub-namespace is proposed by [IDTA Working Group ControlComponentType and ControlComponentInstance](https://github.com/admin-shell-io/submodel-templates/tree/main/development/Control%20Component%20Type%20and%20Control%20Component%20Instance/1/0). See also [IDTA Registered AAS Submodel Templates](https://industrialdigitaltwin.org/content-hub/teilmodelle) or contact via email the [IDTA project manager for submodel templates](mailto:sudip.adhikari@idtwin.org) or [chair of the working group](mailto:daniel.porta@dfki.de).
