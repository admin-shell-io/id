# Nameplate for Software in Manufacturing

In the context of Industrie 4.0, software as an asset becomes increasingly important. 
For an effective and efficient use and management of software in manufacturing value networks, in smart manufacturing, and in smart products, it is necessary to gather relevant information in a uniform representation, as a `nameplate for software`. 
This supports use cases like updates, patch management, license management, audits, etc. This Submodel template specifies a basic set of SubmodelElements in order to describe the necessary information.

## Introduction

Software becomes more and more an essential part in manufacturing value networks, in smart manufacturing, and in smart products. 
For an effective and efficient use and management of such software, it is necessary to gather relevant information in a uniform representation. 
Use cases like updates, patch management, license management, audits, etc. rely on information regarding identification, sources and features of software. 
This information shall be provided in a consistent manner in form of a `nameplate for software`, derived and specialized from a common digital nameplate as defined. 

![image](https://user-images.githubusercontent.com/1814815/199588949-afe2aaa2-1734-4fd8-a256-5763be7fd9ee.png)

## Status: `Submitted`
The sub-namespace for Software Nameplate and its identifiers have been finalized in the Taskforce `Nameplate for Software in Manufacturing`.

## SoftwareNameplate (Submodel)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate) Submodel containing the nameplate information for software asset and associated product classificatons.

### Version (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/Version](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/Version) The complete version information consisting of Major Version, Minor Version, Revision and Build Number.

### VersionName (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/VersionName](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/VersionName) The name this particular version is given.

### VersionInfo (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/VersionInfo](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/VersionInfo) Provides a textual description of most relevant characteristics of the version of the software.

### ReleaseDate (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/ReleaseDate](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/ReleaseDate) The moment in time, when this version of the software was made publicly available.

### ReleaseNotes (MultiLanguageProperty)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/ReleaseNotes](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/ReleaseNotes) contains information about this release.

### BuildDate (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/BuildDate](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/BuildDate) The moment in time, when this particular build of software was created.

### InstallationURI (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallationURI](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallationURI) The name this particular version is given.

### InstallerType (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallerType](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallerType) Indicates the type of installation package.

### InstallationChecksum (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallationChecksum](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallationChecksum) provides the checksum for the software available at InstallationURI.

### InstanceName (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstanceName](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstanceName) The name of the software instance.

### InstalledVersion (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledVersion](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledVersion) The complete version information consisting of Major Version, Minor Version, Revision and Build Number.

### InstallationDate (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallationDate](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallationDate) Date of Installation.

### InstallationPath (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallationPath](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallationPath) Indicates the path to the installed instance of the software.

### InstallationSource (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallationSource](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstallationSource) Indicates the processor architecture this instance is installed on.

### InstalledArchitecture (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledArchitecture](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledArchitecture) Indicates the processor architecture this instance is installed on.

### InstalledOS (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledOS](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledOS) Indicates the operating system this instance is installed on.

### InstalledOnHost (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledOnHost](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledOnHost) Indicates the host system in case of a virtual environment.

### InstalledModules (SMC)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledModules](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledModules) Collection of installed modules.

### ConfigurationPaths (SMC)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/ConfigurationPaths](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/ConfigurationPaths) Indicates the path to the configuration information.

### SLAInformation (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/SLAInformation](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/SLAInformation) Indicates the actual service level agreements.

### InventoryTag (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InventoryTag](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InventoryTag) Specifies an information used for inventory of the software

### InstalledModule (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledModule](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/InstalledModule) The name of a particular module installed

### ConfigurationPath (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/ConfigurationPaths](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/ConfigurationPath) Indicates the path to the configuration.

### TypeOfConfiguration (Property)

[https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/TypeOfConfiguration](https://admin-shell.io/idta/SoftwareNameplate/1/0/SoftwareNameplate/TypeOfConfiguration) Indicates the type of configuration (e.g. general configuration, user configuration).

## Versions: [1.0](.)
This version is the first version to be officially published by IDTA Document `IDTA 2007-1-0 Nameplate for Software in Manufacturing`.

## Contact

This sub-namespace is proposed by [IDTA Working Group Nameplate for Software in Manufacturing](https://github.com/admin-shell-io/submodel-templates/tree/main/development/Software%20Nameplate/1/0). See also [IDTA Registered AAS Submodel Templates](https://industrialdigitaltwin.org/content-hub/teilmodelle#:~:text=Software%20Nameplate) or contact via email the [IDTA project manager for submodel templates](mailto:sudip.adhikari@idtwin.org) or [chair of the working group](mailto:martin.wollschlaeger@tu-dresden.de).
