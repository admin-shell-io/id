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

## Status: `Submitted`
The sub-namespace for SimulationModels and its identifiers have been finalized in the Taskforce Provision of simulation models.

## Versions: [1.0](1/0)
This version is the first version to be officially published by IDTA Document `Provision of simulation models 1.0`.

## Contact

This sub-namespace is proposed by [IDTA Working Group `Provision of simulation models`](https://github.com/admin-shell-io/submodel-templates/tree/main/development/Simulation/1/0). See also [IDTA Registered AAS Submodel Templates](https://industrialdigitaltwin.org/content-hub/teilmodelle#:~:text=Provision%20of%20simulation%20models) or contact via email the [IDTA project manager for submodel templates](mailto:sudip.adhikari@idtwin.org) or [chair of the working group](mailto:Markus.Kiele-Dunsche@lenze.com).
