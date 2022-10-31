# Provision of simulation models

With the AAS submodel ""Simulation"", simulation models from ""Suppliers"" can be made available across manufacturers for use by an ""Integrator"". 
The integrator can thus pursue various simulation goals in the evaluation of solutions, which are described in the AAS submodel. 
A minimal model is described with a minimal set of basic features, which addresses all components and partial solutions. 
Thus, already available models can be found and integrated more easily. In a further step it is considered how a component-specific standardization must look like, in order to make also a manufacturer-spreading simple exchange of simulation models for partial solutions possible. E.g. using the example of drive components / solutions."


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

### SimulationModels/SimulationModel (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/SimulationModels/SimulationModel](https://admin-shell.io/idta/SimulationModels/1/0/SimulationModels/SimulationModel)
Feature collection to provide or request simulation models. Models can be described by objective and content.

## SimulationModel (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel)

Feature collection to provide or request simulation models. Models can be described by objective and content.

### SimulationModel/summary (MLP)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/summary](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/summary)
Summary of the contents of the simulation model in text form. 

### SimulationModel/simPurpose (SMC)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/simPurpose](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/simPurpose) This characteristic describes the simulation purpose or suitability for different simulation goals. 

### SimulationModel/typeOfModel (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/typeOfModel](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/typeOfModel) List of modeling approaches used for the model

### SimulationModel/scopeOfModel (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/scopeOfModel](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/scopeOfModel) List of basic physical characteristics which are represented by the model.

### SimulationModel/licenseModel (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/licenseModel](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/licenseModel) If a simulation model usage will be charged and how it will be charged. 

### SimulationModel/engineeringDomain (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/engineeringDomain](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/engineeringDomain) List of engineering disciplines supported or mapped with the model.  

### SimulationModel/environment (SMC)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/environment](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/environment) Information about prerequisite environments or dependencies of underlying components on the target system. 

### SimulationModel/refSimDocumentation (File)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/refSimDocumentation](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/refSimDocumentation) Simulation Documentation Documentation of example simulations of the model can be supplied. This includes a solver setup and sample circuit and sample results. e.g. zip file, PDF, html, ... -

### SimulationModel/modelFile (SMC)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/modelFile](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/modelFile) Providing versions of the simulation model and with characteristics to distinguish them. 

### SimulationModel/paramMethod (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/paramMethod](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/paramMethod) Indicates whether the model must be parameterized and if so, which method is required.

### SimulationModel/paramFile (File)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/paramFile](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/paramFile) File for parameterization of the model. As parameter file or parameter documentation (e.g. pdf). 

### SimulationModel/initStateMethod (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/initStateMethod](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/initStateMethod) Describes the state variables of the simulation model that must be initialized to start the simulation. For initial value problems, these quantities describe the system state at the start of the simulation. In this case, the system is in a state of equilibrium. Alternatively, a simulation model may include a method to determine consistent initial values at this step, e.g., at an operating point. 

### SimulationModel/initStateFile (File)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/initStateFile](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/initStateFile) File for parameterization of the model. As parameter file or parameter documentation (e.g. pdf). 

### SimulationModel/defaultSimTime (Property)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/defaultSimTime](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/defaultSimTime) Predefined simulation period in seconds.

### SimulationModel/simModManufacturerInformation (SMC)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/simModManufacturerInformation](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/simModManufacturerInformation) Provide access to  simulation support service provided by the distributor via mail or phone.

### SimulationModel/ports (SMC)
[https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/ports](https://admin-shell.io/idta/SimulationModels/1/0/simulationModel/ports) Interfaces of the model. This includes inputs, outputs as well as acausal connections (e.g. mechanical connections). In addition, it is specified here whether the model provides binary interfaces (e.g. for visualization).


## simPurpose (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/simPurpose](https://admin-shell.io/idta/SimulationModels/1/0/simPurpose)

This characteristic describes the simulation purpose or suitability for different simulation goals.

### simPurpose/posSimPurpose (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/simPurpose/posSimPurpose](https://admin-shell.io/idta/SimulationModels/1/0/simPurpose/posSimPurpose)

List of simulation purposes for which the model is intended

### simPurpose/negSimPurpose (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/simPurpose/negSimPurpose](https://admin-shell.io/idta/SimulationModels/1/0/simPurpose/negSimPurpose)

List of simulation purposes for which the model is explicitly not suitable. 


## environment (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/environment](https://admin-shell.io/idta/SimulationModels/1/0/environment)

Information about prerequisite environments or dependencies of underlying components on the target system.

### environment/operatingSystem (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/environment/operatingSystem](https://admin-shell.io/idta/SimulationModels/1/0/environment/operatingSystem)

### environment/toolEnvironment (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/environment/toolEnvironment](https://admin-shell.io/idta/SimulationModels/1/0/environment/toolEnvironment)

### environment/dependencyEnvironment (MLP)

[https://admin-shell.io/idta/SimulationModels/1/0/environment/dependencyEnvironment](https://admin-shell.io/idta/SimulationModels/1/0/environment/dependencyEnvironment)

### environment/visualizationInformation (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/environment/visualizationInformation](https://admin-shell.io/idta/SimulationModels/1/0/environment/visualizationInformation)

### environment/simulationTool (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/environment/simulationTool](https://admin-shell.io/idta/SimulationModels/1/0/environment/simulationTool)

## simulationTool (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/simulationTool](https://admin-shell.io/idta/SimulationModels/1/0/simulationTool)

Properties of the model with regarding to concrete simulation tools.

### simulationTool/simToolName (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/simulationTool/simToolName](https://admin-shell.io/idta/SimulationModels/1/0/simulationTool/simToolName) Name of the simulation tool including version.

### simulationTool/dependencySimTool (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/simulationTool/dependencySimTool](https://admin-shell.io/idta/SimulationModels/1/0/simulationTool/dependencySimTool) Dependencies of Simulation Tools.

### simulationTool/compiler (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/simulationTool/compiler](https://admin-shell.io/idta/SimulationModels/1/0/simulationTool/compiler) Name of necessary compiler including version

### simulationTool/solverAndTolerances (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/simulationTool/solverAndTolerances](https://admin-shell.io/idta/SimulationModels/1/0/simulationTool/solverAndTolerances) Useful settings of the simulation environment. Includes e.g. solver settings. 


## solverAndTolerances (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances](https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances)

Useful settings of the simulation environment. Includes e.g. solver settings.

### solverAndTolerances/stepSizeControlNeeded (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances/stepSizeControlNeeded](https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances/stepSizeControlNeeded) Whether the model requires adaptive step size

### solverAndTolerances/fixedStepSize (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances/fixedStepSize](https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances/fixedStepSize) Fixed integration step size, if there is no adaptive step size

### solverAndTolerances/stiffSolverNeeded (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances/stiffSolverNeeded](https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances/stiffSolverNeeded) Rigid integrator recommended.

### solverAndTolerances/solverIncluded (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances/solverIncluded](https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances/solverIncluded) Solver is integrated in the model (e.g. FMU for co-simulation).

### solverAndTolerances/testedToolSolverAlgorithm (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances/testedToolSolverAlgorithm](https://admin-shell.io/idta/SimulationModels/1/0/solverAndTolerances/testedToolSolverAlgorithm) List of validated tool-solver combinations.


## testedToolSolverAlgorithm (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/testedToolSolverAlgorithm](https://admin-shell.io/idta/SimulationModels/1/0/testedToolSolverAlgorithm)

List of validated tool-solver combinations.

### testedToolSolverAlgorithm/solverAlgorithm (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/testedToolSolverAlgorithm/solverAlgorithm](https://admin-shell.io/idta/SimulationModels/1/0/testedToolSolverAlgorithm/solverAlgorithm) validated solver.

### testedToolSolverAlgorithm/toolSolverFurtherDescription (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/testedToolSolverAlgorithm/toolSolverFurtherDescription](https://admin-shell.io/idta/SimulationModels/1/0/testedToolSolverAlgorithm/toolSolverFurtherDescription) Further tool- and solver-specific information.

### testedToolSolverAlgorithm/tolerance (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/testedToolSolverAlgorithm/tolerance](https://admin-shell.io/idta/SimulationModels/1/0/testedToolSolverAlgorithm/tolerance) (relative) tolerance for theadaptive step size.

## modelFile (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/modelFile](https://admin-shell.io/idta/SimulationModels/1/0/modelFile)

Providing versions of the simulation model and with characteristics to distinguish them.

### modelFile/modelFileType (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/modelFile/modelFileType](https://admin-shell.io/idta/SimulationModels/1/0/modelFile/modelFileType) Designation of the exchange format of the model. E.G.: FMI 1.0, Co-Simulation, Platform / Source - Code. FMI 2.0.2, Model Exchange, Source - Code, S-function, Version 2, 64bit, mex - Format / or C-Code, Modelica 3, encoded, VHDL

### modelFile/modelFileVersion (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/modelFile/modelFileVersion](https://admin-shell.io/idta/SimulationModels/1/0/modelFile/modelFileVersion) Provision of a version of the simulation model with information to distinguish the versions. The versions are primarily intended for bug fixes without content changes

## modelFileVersion (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/modelFileVersion](https://admin-shell.io/idta/SimulationModels/1/0/modelFileVersion)

For further information please read the SMT Spec

### modelFileVersion/modelVersionId (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/PVersionId](https://admin-shell.io/idta/SimulationModels/1/0/modelFileVersion/modelVersionId)

Version number of the model from the vendor.

### modelFileVersion/modelPreviewImage (File)

[https://admin-shell.io/idta/SimulationModels/1/0/modelFileVersion/modelPreviewImage](https://admin-shell.io/idta/SimulationModels/1/0/modelFileVersion/modelPreviewImage)

Image file to represent the model in user interfaces, e.g. in a search.

### modelFileVersion/digitalFile (File)

[https://admin-shell.io/idta/SimulationModels/1/0/modelFileVersion/digitalFile](https://admin-shell.io/idta/SimulationModels/1/0/modelFileVersion/digitalFile)

Deployment of the model file

### modelFileVersion/modelFileReleaseNotesTxt (MLP)

[https://admin-shell.io/idta/SimulationModels/1/0/modelFileVersion/modelFileReleaseNotesTxt](https://admin-shell.io/idta/SimulationModels/1/0/modelFileVersion/modelFileReleaseNotesTxt)

contains information about this release

### modelFileVersion/modelFileReleaseNotesFile (File)

[https://admin-shell.io/idta/SimulationModels/1/0/modelFileVersion/modelFileReleaseNotesFile](https://admin-shell.io/idta/SimulationModels/1/0/modelFileVersion/modelFileReleaseNotesFile) release notes link or file


## simModManufacturerInformation (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/simModManufacturerInformation](https://admin-shell.io/idta/SimulationModels/1/0/simModManufacturerInformation)

Provide access to simulation support service provided by the distributor via mail or phone.

### simModManufacturerInformation/phone (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/simModManufacturerInformation/phone](https://admin-shell.io/idta/SimulationModels/1/0/simModManufacturerInformation/phone) Phone number including type

## phone (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/phone](https://admin-shell.io/idta/SimulationModels/1/0/phone) Phone number including type

### phone/availableTime (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/phone/availableTime](https://admin-shell.io/idta/SimulationModels/1/0/phone/availableTime) 
Specification of the available time window

## ports (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/ports](https://admin-shell.io/idta/SimulationModels/1/0/ports)

Interfaces of the model. This includes inputs, outputs as well as acausal connections (e.g. mechanical connections). In addition, it is specified here whether the model provides binary interfaces (e.g. for visualization).

### ports/portsConnector (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/ports/portsConnector](https://admin-shell.io/idta/SimulationModels/1/0/ports/portsConnector)

List of ports of the model. These include a name, a description, a list of variables, and a list of ports. 

### ports/binaryConnector (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/ports/binaryConnector](https://admin-shell.io/idta/SimulationModels/1/0/ports/binaryConnector)
List of Binary interfaces (binaryType) based on the FMI 3.0 standard (https://fmi-standard.org/docs/3.0-dev/#definition-of-types). At this point the name (e.g. "Binary interface visualization") and the description (e.g. "Interface for binary transfer of visualization information") are specified. 

## portsConnector (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/portsConnector](https://admin-shell.io/idta/SimulationModels/1/0/portsConnector)

List of ports of the model. These include a name, a description, a list of variables, and a list of ports.

### portsConnector/portConnectorName (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/portsConnector/portConnectorName](https://admin-shell.io/idta/SimulationModels/1/0/portsConnector/portConnectorName)

Name of the Connector Port.

### portsConnector/portConDescription (MLP)

[https://admin-shell.io/idta/SimulationModels/1/0/portsConnector/portConDescription](https://admin-shell.io/idta/SimulationModels/1/0/portsConnector/portConDescription)

Description of the Connector Port. 

### portsConnector/variable (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/portsConnector/variable](https://admin-shell.io/idta/SimulationModels/1/0/portsConnector/variable)

List of variables of the port. 

## variable (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/variable](https://admin-shell.io/idta/SimulationModels/1/0/variable) Variable of PortsConnector

### variable/variableName (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/variable/variableName](https://admin-shell.io/idta/SimulationModels/1/0/variable/variableName) Name of the variable. 
### variable/range (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/variable/range](https://admin-shell.io/idta/SimulationModels/1/0/variable/range) Range of values for the variable (e.g. [min, max], [min, max[, ]min, max], ]min, max[, {val1, val2, ...}). 


### variable/variableType (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/variable/variableType](https://admin-shell.io/idta/SimulationModels/1/0/variable/variableType) Type of the variable (e.g. Real, Integer, Boolean, String or Enum).

### variable/variableDescription (MLP)

[https://admin-shell.io/idta/SimulationModels/1/0/variable/variableDescription](https://admin-shell.io/idta/SimulationModels/1/0/variable/variableDescription) Description of the variable. 

### variable/unitList (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/variable/unitList](https://admin-shell.io/idta/SimulationModels/1/0/variable/unitList) The most common units can be selected here. .. If "others" is selected, a free text can be entered. 

### variable/unitDescription (MLP)

[https://admin-shell.io/idta/SimulationModels/1/0/variable/unitDescription](https://admin-shell.io/idta/SimulationModels/1/0/variable/unitDescription) Text field for missing units of the list 


### variable/variableCausality (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/variable/variableCausality](https://admin-shell.io/idta/SimulationModels/1/0/variable/variableCausality) The causality of the variable: input to inputs, output to ouputs, acausal connections (e.g. mechanical connection) do not have causality.

### variable/variablePrefix (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/variable/variablePrefix](https://admin-shell.io/idta/SimulationModels/1/0/variable/variablePrefix) Prefix for acausal variable. Potential variables are set equal when connecting (no prefix). Stream variables are connected according to Kirchhoff's law, i.e. the sum of the variables equals zero. The bi-directional flow of matter is described with "stream" (e.g. for enthalpy). 


### variable/ (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/variable/](https://admin-shell.io/idta/SimulationModels/1/0/variable/) For further information please read the SMT Spec


## binaryConnector (SMC)

[https://admin-shell.io/idta/SimulationModels/1/0/binaryConnector](https://admin-shell.io/idta/SimulationModels/1/0/binaryConnector) Binary interfaces (binaryType) based on the FMI 3.0 standard (https://fmi-standard.org/docs/3.0-dev/#definition-of-types). At this point the name (e.g. "Binary interface visualization") and the description (e.g. "Interface for binary transfer of visualization information") are specified.

### binaryConnector/binaryConName (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/binaryConnector/binaryConName](https://admin-shell.io/idta/SimulationModels/1/0/binaryConnector/binaryConName) Binary interface name. 

### binaryConnector/binaryConDescription (Property)

[https://admin-shell.io/idta/SimulationModels/1/0/binaryConnector/binaryConDescription](https://admin-shell.io/idta/SimulationModels/1/0/binaryConnector/binaryConDescription) Binary interface description. 

## Versions: [1.0](.)
This version is the first version to be officially published by IDTA Document `Provision of simulation models 1.0`.

## Contact

This sub-namespace is proposed by [IDTA Working Group `Provision of simulation models`](https://github.com/admin-shell-io/submodel-templates/tree/main/development/Simulation/1/0). See also [IDTA Registered AAS Submodel Templates](https://industrialdigitaltwin.org/content-hub/teilmodelle#:~:text=Provision%20of%20simulation%20models) or contact via email the [IDTA project manager for submodel templates](mailto:sudip.adhikari@idtwin.org) or [chair of the working group](mailto:Markus.Kiele-Dunsche@lenze.com).
