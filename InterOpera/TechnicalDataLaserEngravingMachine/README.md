# Technical Data for Laser Engraving Machine

This sub-namespace collects the identifiers defined in the submodel "Technical Data for Laser Engraving Machine", which is under development in the [InterOpera](https://interopera.de/teilmodellprojekte/) project.

## Introduction

A standardized information model of technical data of industrial equipment has been provided by the existing IDTA Submodel “Generic Frame for Technical Data for Industrial Equipment in Manufacturing”. This submodel template specifies the basic data structure by using a set of SubmodelElements and defines the necessary general properties to describe the manufacturer information. For specific types of products, the asset-specific technical data is intended to be capsuled in the SubmodelElementCollections (SMC) “GuidelineSpecificProperties” within the SMC “TechnicalProperties”. The asset-specific technical properties have to be defined by the manufacturer. Interoperability cannot be ensured if different manufacturers have different descriptions of technical properties for the same product type. The purpose of this submodel template is to standardize the possible-applicable technical properties of LEM.
The properties are defined based on the existing standards and common practices at enterprises so that a far-reaching acceptance can be achieved. The defined properties are included in the SMC “TechnicalProperties” of the IDTA existing IDTA Submodel “Generic Frame for Technical Data for Industrial Equipment in Manufacturing” V1.2. Therefore, this template is an extension of the existing template for LEM. Only the technical properties related to LEM are defined in this sub-namespace, which have not been included in the exsiting dictionaries, aka. ECLASS and IEC CDD.

## Status: `Submitted`
The submodel "Technical Data for Laser Engraving Machine" is under development. Its specification will be released soon.

## AdditionalAxis (Property)

rotation axis <br/>
https://admin-shell.io/InterOpera/TechnicalDataLaserEngravingMachine/1/0/AdditionalAxis

## BeamDiameter (Property)

physical size of the beam perpendicular to the direction of beam propagation <br/>
https://admin-shell.io/InterOpera/TechnicalDataLaserEngravingMachine/1/0/BeamDiameter

## BeamDivergence (Property)

Expansion of a laser beam over a certain distance <br/>
https://admin-shell.io/InterOpera/TechnicalDataLaserEngravingMachine/1/0/BeamDivergence

## BeamQuality (Property)

Indicator of the deviation between the actual beam profile of a laser and the ideal beam profile <br/>
https://admin-shell.io/InterOpera/TechnicalDataLaserEngravingMachine/1/0/BeamQuality

## MarkingMaterial (Property)

suitable marking materials <br/>
https://admin-shell.io/InterOpera/TechnicalDataLaserEngravingMachine/1/0/MarkingMaterial

## OperatingMode (Property)

Type of laser output, its value could be pulsed or continuous wave (cw) <br/>
https://admin-shell.io/InterOpera/TechnicalDataLaserEngravingMachine/1/0/OperatingMode

## PulseEnergy (Property)

maximum energy of a laser pulse <br/>
https://admin-shell.io/InterOpera/TechnicalDataLaserEngravingMachine/1/0/PulseEnergy

## ScanningField (Property)

maximum range for deflection of the laser beam by the scanner unit <br/>
https://admin-shell.io/InterOpera/TechnicalDataLaserEngravingMachine/1/0/ScanningField

## ScannerSpeed (Property)

Maximum marking speed of the beam deflection and positioning unit (scanner) <br/>
https://admin-shell.io/InterOpera/TechnicalDataLaserEngravingMachine/1/0/ScannerSpeed

## WorkspaceXY (Property)

maximum size of the working plane based on the traverse paths of the X/Y positioning axes <br/>
https://admin-shell.io/InterOpera/TechnicalDataLaserEngravingMachine/1/0/WorkspaceXY


## Contact

This sub-namespace is proposed by the [InterOpera](https://interopera.de/) Project. An overview and the details of all the InterOpera submodels can be found on the project website. [Dachuan Shi](mailto:dachuan.shi@ipa.fraunhofer.de) and [Olga Meyer](mailto:olga.meyer@ipa.fraunhofer.de) can be contacted for any questions regarding this sub-namespace and the InterOpera project.
