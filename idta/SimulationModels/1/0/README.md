# Provision of simulation models

With the AAS submodel 'Simulation', simulation models from 'Suppliers' can be made available across manufacturers for use by an 'Integrator'. 
The integrator can thus pursue various simulation goals in the evaluation of solutions, which are described in the AAS submodel. 
A minimal model is described with a minimal set of basic features, which addresses all components and partial solutions. 
Thus, already available models can be found and integrated more easily. In a further step it is considered how a component-specific standardization must look like, in order to make also a manufacturer-spreading simple exchange of simulation models for partial solutions possible. E.g. using the example of drive components / solutions.


## Introduction

The submodel template `Provision of simulation models` allows the interoperable provision of simulation model files for an asset via the asset administration shell. The submodel enables this for a wide range of simulation model types and simulation purposes. It contains information about the type of model, how to use the model, and the areas of application.
The main underlying class of models for this sub-model are DAEs, models described by differential algebraic equations. However, models of other types, such as CAD, FMEA, etc., can also be described. FEM type models are not considered, they are covered by another submodel, actually under development. The models described by this submodel may be provided in ASCII or binary form to be used with a specific simulation software (e.g. Matlab/Simulink, Virtuos, etc.), as source code (e.g. C, Modelica, etc.), or in a model exchange format such as FMI.
It describes rudimentarily the content of the model.
Assets, where you can provide simulation models via AAS, can be passive parts, active devices, subsystems, machines or even production plants. When using this submodel template, it is requiered that the asset for which I want to provide a simulation model has an AAS. That is, if there are no AAS yet, I must first define the asset-ID and create an AAS. A submodel can then be added to this AAS.
In the first step, the submodel supports searching and finding, as well as requesting simulation model files from manufacturers or distributors.
In further steps, the submodel will also support the automatic integration of a model into a specific simulation environment, up to an automatic generation of an overall simulation based on structural descriptions of a system containing different components. As it is possible with e.g. the submodel candidate for a bill of material (BoM).

![SMTSim](https://user-images.githubusercontent.com/1814815/199018518-0d985525-c853-4a2a-9970-42af7f0fc035.jpg)


## Status: `Submitted`
The sub-namespace for SimulationModels and its identifiers have been finalized in the Taskforce Provision of simulation models.


## SimulationModels (Submodel)

[https://admin-shell.io/idta/SimulationModels/1/0/SimulationModels](https://admin-shell.io/idta/SimulationModels/1/0/SimulationModels)

The Submodel may provide one or more simulation models, a service to generate a specific model, or access to an open or specific query.

### SimulationModel (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/SimulationModel](https://admin-shell.io/idta/SimulationModels/1/0/SimulationModel)
Feature collection to provide or request simulation models. Models can be described by objective and content.

### Summary (MLP)
[https://admin-shell.io/idta/SimulationModels/1/0/Summary](https://admin-shell.io/idta/SimulationModels/1/0/Summary)
Summary of the contents of the simulation model in text form. 

### SimPurpose (SMC)
[https://admin-shell.io/idta/SimulationModels/1/0/SimPurpose](https://admin-shell.io/idta/SimulationModels/1/0/SimPurpose) This characteristic describes the simulation purpose or suitability for different simulation goals. 

### TypeOfModel (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/TypeOfModel](https://admin-shell.io/idta/SimulationModels/1/0/TypeOfModel) List of modeling approaches used for the model

### ScopeOfModel (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/ScopeOfModel](https://admin-shell.io/idta/SimulationModels/1/0/ScopeOfModel) List of basic physical characteristics which are represented by the model.

### LicenseModel (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/LicenseModel](https://admin-shell.io/idta/SimulationModels/1/0/LicenseModel) If a simulation model usage will be charged and how it will be charged. 

### EngineeringDomain (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/EngineeringDomain](https://admin-shell.io/idta/SimulationModels/1/0/EngineeringDomain) List of engineering disciplines supported or mapped with the model.  

### Environment (SMC)
[https://admin-shell.io/idta/SimulationModels/1/0/Environment](https://admin-shell.io/idta/SimulationModels/1/0/Environment) Information about prerequisite environments or dependencies of underlying components on the target system. 

### RefSimDocumentation (File)
[https://admin-shell.io/idta/SimulationModels/1/0/RefSimDocumentation](https://admin-shell.io/idta/SimulationModels/1/0/RefSimDocumentation) Simulation Documentation Documentation of example simulations of the model can be supplied. This includes a solver setup and sample circuit and sample results. e.g. zip file, PDF, html, ... -

### ModelFile (SMC)
[https://admin-shell.io/idta/SimulationModels/1/0/ModelFile](https://admin-shell.io/idta/SimulationModels/1/0/ModelFile) Providing versions of the simulation model and with characteristics to distinguish them. 

### ParamMethod (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/ParamMethod](https://admin-shell.io/idta/SimulationModels/1/0/ParamMethod) Indicates whether the model must be parameterized and if so, which method is required.

### ParamFile (File)
[https://admin-shell.io/idta/SimulationModels/1/0/ParamFile](https://admin-shell.io/idta/SimulationModels/1/0/ParamFile) File for parameterization of the model. As parameter file or parameter documentation (e.g. pdf). 

### InitStateMethod (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/InitStateMethod](https://admin-shell.io/idta/SimulationModels/1/0/InitStateMethod) Describes the state variables of the simulation model that must be initialized to start the simulation. For initial value problems, these quantities describe the system state at the start of the simulation. In this case, the system is in a state of equilibrium. Alternatively, a simulation model may include a method to determine consistent initial values at this step, e.g., at an operating point. 

### InitStateFile (File)
[https://admin-shell.io/idta/SimulationModels/1/0/InitStateFile](https://admin-shell.io/idta/SimulationModels/1/0/InitStateFile) File for parameterization of the model. As parameter file or parameter documentation (e.g. pdf). 

### DefaultSimTime (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/DefaultSimTime](https://admin-shell.io/idta/SimulationModels/1/0/DefaultSimTime) Predefined simulation period in seconds.

### SimModManufacturerInformation (SMC)
[https://admin-shell.io/idta/SimulationModels/1/0/SimModManufacturerInformation](https://admin-shell.io/idta/SimulationModels/1/0/SimModManufacturerInformation) Provide access to  simulation support service provided by the distributor via mail or phone.

### Ports (SMC)
[https://admin-shell.io/idta/SimulationModels/1/0/Ports](https://admin-shell.io/idta/SimulationModels/1/0/Ports) Interfaces of the model. This includes inputs, outputs as well as acausal connections (e.g. mechanical connections). In addition, it is specified here whether the model provides binary interfaces (e.g. for visualization).


### PosSimPurpose (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/PosSimPurpose](https://admin-shell.io/idta/SimulationModels/1/0/PosSimPurpose)

List of simulation purposes for which the model is intended

### NegSimPurpose (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/NegSimPurpose](https://admin-shell.io/idta/SimulationModels/1/0/NegSimPurpose)

List of simulation purposes for which the model is explicitly not suitable. 


### OperatingSystem (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/OperatingSystem](https://admin-shell.io/idta/SimulationModels/1/0/OperatingSystem)

### ToolEnvironment (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/ToolEnvironment](https://admin-shell.io/idta/SimulationModels/1/0/ToolEnvironment)

### DependencyEnvironment (MLP)

[https://admin-shell.io/idta/SimulationModels/1/0/DependencyEnvironment](https://admin-shell.io/idta/SimulationModels/1/0/DependencyEnvironment)

### VisualizationInformation (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/VisualizationInformation](https://admin-shell.io/idta/SimulationModels/1/0/VisualizationInformation)

### SimulationTool (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/SimulationTool](https://admin-shell.io/idta/SimulationModels/1/0/SimulationTool)

## SimulationTool (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/SimulationTool](https://admin-shell.io/idta/SimulationModels/1/0/SimulationTool)

Contains properties of the model with regarding to concrete simulation tools.

### SimToolName (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/SimToolName](https://admin-shell.io/idta/SimulationModels/1/0/SimToolName) Name of the simulation tool including version.

### DependencySimTool (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/DependencySimTool](https://admin-shell.io/idta/SimulationModels/1/0/DependencySimTool) Dependencies of Simulation Tools.

### Compiler (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/Compiler](https://admin-shell.io/idta/SimulationModels/1/0/Compiler) Name of necessary compiler including version

### SolverAndTolerances (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/SolverAndTolerances](https://admin-shell.io/idta/SimulationModels/1/0/SolverAndTolerances) Useful settings of the simulation environment. Includes e.g. solver settings. 


### StepSizeControlNeeded (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/StepSizeControlNeeded](https://admin-shell.io/idta/SimulationModels/1/0/StepSizeControlNeeded) Whether the model requires adaptive step size

### FixedStepSize (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/FixedStepSize](https://admin-shell.io/idta/SimulationModels/1/0/FixedStepSize) Fixed integration step size, if there is no adaptive step size

### StiffSolverNeeded (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/StiffSolverNeeded](https://admin-shell.io/idta/SimulationModels/1/0/StiffSolverNeeded) Rigid integrator recommended.

### SolverIncluded (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/SolverIncluded](https://admin-shell.io/idta/SimulationModels/1/0/SolverIncluded) Solver is integrated in the model (e.g. FMU for co-simulation).

### TestedToolSolverAlgorithm (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/TestedToolSolverAlgorithm](https://admin-shell.io/idta/SimulationModels/1/0/TestedToolSolverAlgorithm) List of validated tool-solver combinations.


### SolverAlgorithm (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/SolverAlgorithm](https://admin-shell.io/idta/SimulationModels/1/0/SolverAlgorithm) validated solver.

### ToolSolverFurtherDescription (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/ToolSolverFurtherDescription](https://admin-shell.io/idta/SimulationModels/1/0/ToolSolverFurtherDescription) Further tool- and solver-specific information.

### Tolerance (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/Tolerance](https://admin-shell.io/idta/SimulationModels/1/0/Tolerance) (relative) tolerance for theadaptive step size.


### ModelFileType (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/ModelFileType](https://admin-shell.io/idta/SimulationModels/1/0/ModelFileType) Designation of the exchange format of the model. E.G.: FMI 1.0, Co-Simulation, Platform / Source - Code. FMI 2.0.2, Model Exchange, Source - Code, S-function, Version 2, 64bit, mex - Format / or C-Code, Modelica 3, encoded, VHDL

### ModelFileVersion (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/ModelFileVersion](https://admin-shell.io/idta/SimulationModels/1/0/ModelFileVersion) Provision of a version of the simulation model with information to distinguish the versions. The versions are primarily intended for bug fixes without content changes


### ModelVersionId (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/VersionId](https://admin-shell.io/idta/SimulationModels/1/0/ModelVersionId)

Version number of the model from the vendor.

### ModelPreviewImage (File)

[https://admin-shell.io/idta/SimulationModels/1/0/ModelPreviewImage](https://admin-shell.io/idta/SimulationModels/1/0/ModelPreviewImage)

Image file to represent the model in user interfaces, e.g. in a search.

### DigitalFile (File)

[https://admin-shell.io/idta/SimulationModels/1/0/DigitalFile](https://admin-shell.io/idta/SimulationModels/1/0/DigitalFile)

Deployment of the model file

### ModelFileReleaseNotesTxt (MLP)

[https://admin-shell.io/idta/SimulationModels/1/0/ModelFileReleaseNotesTxt](https://admin-shell.io/idta/SimulationModels/1/0/ModelFileReleaseNotesTxt)

contains information about this release

### ModelFileReleaseNotesFile (File)

[https://admin-shell.io/idta/SimulationModels/1/0/ModelFileReleaseNotesFile](https://admin-shell.io/idta/SimulationModels/1/0/ModelFileReleaseNotesFile) release notes link or file


### SimModManufacturerInformation/Phone (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/SimModManufacturerInformation/Phone](https://admin-shell.io/idta/SimulationModels/1/0/SimModManufacturerInformation/Phone) Phone number including type


### PortsConnector (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/PortsConnector](https://admin-shell.io/idta/SimulationModels/1/0/PortsConnector)

List of ports of the model. These include a name, a description, a list of variables, and a list of ports. 

### BinaryConnector (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/BinaryConnector](https://admin-shell.io/idta/SimulationModels/1/0/BinaryConnector)
List of Binary interfaces (binaryType) based on the FMI 3.0 standard (https://fmi-standard.org/Docs/3.0-dev/#definition-of-types). At this point the name (e.g. "Binary interface visualization") and the description (e.g. "Interface for binary transfer of visualization information") are specified. 


### PortConnectorName (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/PortConnectorName](https://admin-shell.io/idta/SimulationModels/1/0/PortConnectorName)

Name of the Connector Port.

### PortConDescription (MLP)

[https://admin-shell.io/idta/SimulationModels/1/0/PortConDescription](https://admin-shell.io/idta/SimulationModels/1/0/PortConDescription)

Description of the Connector Port. 

### Variable (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/Variable](https://admin-shell.io/idta/SimulationModels/1/0/Variable)

List of variables of the port. 


### VariableName (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/VariableName](https://admin-shell.io/idta/SimulationModels/1/0/VariableName) Name of the variable. 

### Range (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/Range](https://admin-shell.io/idta/SimulationModels/1/0/Range) Range of values for the variable (e.g. [min, max], [min, max[, ]min, max], ]min, max[, {val1, val2, ...}). 


### VariableType (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/VariableType](https://admin-shell.io/idta/SimulationModels/1/0/VariableType) Type of the variable (e.g. Real, Integer, Boolean, String or Enum).

### VariableDescription (MLP)

[https://admin-shell.io/idta/SimulationModels/1/0/VariableDescription](https://admin-shell.io/idta/SimulationModels/1/0/VariableDescription) Description of the variable. 

### UnitList (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/UnitList](https://admin-shell.io/idta/SimulationModels/1/0/UnitList) The most common units can be selected here. If "others" is selected, a free text can be entered. 

### UnitDescription (MLP)

[https://admin-shell.io/idta/SimulationModels/1/0/UnitDescription](https://admin-shell.io/idta/SimulationModels/1/0/UnitDescription) Text field for missing units of the list.


### VariableCausality (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/VariableCausality](https://admin-shell.io/idta/SimulationModels/1/0/VariableCausality) The causality of the variable: input to inputs, output to ouputs, acausal connections (e.g. mechanical connection) do not have causality.

### VariablePrefix (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/VariablePrefix](https://admin-shell.io/idta/SimulationModels/1/0/VariablePrefix) Prefix for acausal variable. Potential variables are set equal when connecting (no prefix). Stream variables are connected according to Kirchhoff's law, i.e. the sum of the variables equals zero. The bi-directional flow of matter is described with "stream" (e.g. for enthalpy). 


### BinaryConName (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/BinaryConName](https://admin-shell.io/idta/SimulationModels/1/0/BinaryConName) Binary interface name. 

### BinaryConDescription (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/BinaryConDescription](https://admin-shell.io/idta/SimulationModels/1/0/BinaryConDescription) Binary interface description. 

## Versions: [1.0](.)
This version is the first version to be officially published by IDTA Document `Provision of simulation models 1.0`.

## Contact

This sub-namespace is proposed by [IDTA Working Group `Provision of simulation models`](https://github.com/admin-shell-io/submodel-templates/tree/main/development/simulation/1/0). See also [IDTA Registered AAS Submodel Templates](https://industrialdigitaltwin.org/content-hub/Teilmodelle#:~:text=Provision%20of%20simulation%20models) or contact via email the [IDTA project manager for submodel templates](mailto:sudip.adhikari@idtwin.org) or [chair of the working group](mailto:Markus.Kiele-Dunsche@lenze.com).
