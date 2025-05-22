# Inspection Documents of Steel Products

## Introduction

This submodel template aims to standardize the representation and storage of inspection data for steel products within the steel manufacturing and supply industry, specifically adhering to the DIN EN 10204:2004 and DIN EN 10168:2004 standards. DIN EN 10204:2004 defines the various types of inspection documents supplied to the customer, while DIN EN 10168:2004 specifies the required document contents for inspection documents of metallic products. 
This template is designed for stakeholders such as steel manufacturers, suppliers, and customers, to facilitate seamless exchange and direct usability of inspection data. It covers the entire lifecycle of steel products from production to delivery, ensuring consistency and reliability in data handling.
The submodel will manage comprehensive inspection documents, including detailed information about the manufacturer and customer, order data, product specifications, mechanical test results, chemical analysis, and validation information. By providing a uniform structure for data related to steel product inspections, this submodel enhances traceability, data interoperability, and compliance across the supply chain, ensuring added value and efficiency for both suppliers and customers.


## Status: `<Submitted>`
The status of this subnamespace. It can be `Submitted`, `Under Review`, `Refinement Required`, `Accepted`, `Revoked` or `Not Accepted`. The requester can only set the status `Submitted`, all others are managed by the Coordination Board.



## InspectionDocumentsOfSteelProducts (Submodel)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/InspectionDocumentsOfSteelProducts/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/InspectionDocumentsOfSteelProducts/1/0)
Submodel containing the Inspection Documents of Steel Products regarding to order data, product data, mechanical tests and chemical tests. 

### AdditionalProductRequirements (MLP)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/AdditionalProductRequirements/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/AdditionalProductRequirements/1/0)
AdditionalProductRequirements contain additional information about the product, which are not included in the ProductDescription property.

### CEImage (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CEImage/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CEImage/1/0)
The CE image as base64 encoded png file.

### CEMarking (SMC)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CEMarking/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CEMarking/1/0)
The CE marking, with which the manufacturer declares that the product complies with the applicable requirements.

### CENotifiedBodyNumber (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CENotifiedBodyNumber/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CENotifiedBodyNumber/1/0)
The identification number of the Notified body. Refer to https://eur-lex.europa.eu/LexUriServ/LexUriServ.do?uri=CELEX:31993L0068:en:HTML and https://ec.europa.eu/growth/tools-databases/nando/index.cfm?fuseaction=notifiedbody.main.

### CENumber (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CENumber/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CENumber/1/0)
The declaration of conformance document number.

### CEYear (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CEYear/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CEYear/1/0)
The year when the declaration of conformance was issued.

### Consignee (Value)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Consignee/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Consignee/1/0)
Consignee is the receiver of the product.

### ConsigneeOfCertificate (Value)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/ConsigneeOfCertificate/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/ConsigneeOfCertificate/1/0)
ConsigneeOfCertificate is the receiver of the inspection documents.

### Customer (SMC)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Customer/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Customer/1/0)
Customer is the purchaser of the product.

### CustomerRole (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CustomerRole/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/CustomerRole/1/0)
Describes the role of the customer listed in the “Customer” SMC. Allowed Values are [Purchaser](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Purchaser/1/0), [Consignee](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Consignee/1/0) and [ConsigneeOfCertificate](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/ConsigneeOfCertificate/1/0).

### DateOfIssue (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/DateOfIssue/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/DateOfIssue/1/0)
The DateOfIssue refers to the specific date when an inspection document is officially approved as meeting the defined specifications or standards.

### DeliveryNoteNumber (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/DeliveryNoteNumber/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/DeliveryNoteNumber/1/0)
A DeliveryNoteNumber is a unique identifier assigned to a specific delivery note, which is a document accompanying a shipment of goods.

### DirectionOfSample (MLP)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/DirectionOfSample/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/DirectionOfSample/1/0)
DirectionOfSample refers to the orientation or specific alignment of a sample taken from a steel product.

### ElongationAfterFractureIndividualValues (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/ElongationAfterFractureIndividualValues/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/ElongationAfterFractureIndividualValues/1/0)
ElongationAfterFractureIndividualValues refers to the specific measured values of elongation or strain observed in individual samples until the point of breakage during a tensile test.

### ElongationAfterFractureMean (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/ElongationAfterFractureMean/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/ElongationAfterFractureMean/1/0)
The ElongationAfterFractureMean refers to the average percentage of elongation or strain a steel product undergoes until the point of fracture during a tensile test.

### HardnessIndividualValues (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/HardnessIndividualValues/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/HardnessIndividualValues/1/0)
HardnessIndividualValues refer to the specific measured hardness values obtained from individual tests conducted.

### HardnessMean (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/HardnessMean/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/HardnessMean/1/0)
HardnessMean refers to the average hardness value obtained from multiple measurements or tests conducted.

### HardnessTest (SMC)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/HardnessTest/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/HardnessTest/1/0)
The SMC HardnessTest describes a type of mechanical test performed to evaluate the resistance of a steel product to indentation or penetration by another object.

### HardnessTestingMethod (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/HardnessTestingMethod/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/HardnessTestingMethod/1/0)
The HardnessTestingMethod refers to the specific technique or procedure used to assess the hardness of a steel product. 

### LocationOfSample (MLP)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/LocationOfSample/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/LocationOfSample/1/0)
The LocationOfSample specifies the location for the sample collection.

### Manufacturer (SMC)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Manufacturer/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Manufacturer/1/0)
Manufacturer is the producer of the product.

### ManufacturerOrderNumber (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/ManufacturerOrderNumber/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/ManufacturerOrderNumber/1/0)
ManufacturerOrderNumber is the identifier of the order determined by the manufacturer who receives the order.

### MassFraction_Al (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Al/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Al/1/0)
Mass fraction of aluminum in the alloy, measured during chemical analysis.

### MassFraction_Be (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Be/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Be/1/0)
Mass fraction of beryllium in the alloy, measured during chemical analysis.

### MassFraction_C (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_C/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_C/1/0)
Mass fraction of carbon in the alloy, measured during chemical analysis.

### MassFraction_Cr (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Cr/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Cr/1/0)
Mass fraction of chromium in the alloy, measured during chemical analysis.

### MassFraction_Cu (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Cu/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Cu/1/0)
Mass fraction of copper in the alloy, measured during chemical analysis.

### MassFraction_Mn (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Mn/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Mn/1/0)
Mass fraction of manganese in the alloy, measured during chemical analysis.

### MassFraction_Mo (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Mo/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Mo/1/0)
Mass fraction of molybdenum in the alloy, measured during chemical analysis.

### MassFraction_N (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_N/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_N/1/0)
Mass fraction of nitrogen in the alloy, measured during chemical analysis.

### MassFraction_Nb (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Nb/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Nb/1/0)
Mass fraction of niobium in the alloy, measured during chemical analysis.

### MassFraction_Ni (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Ni/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Ni/1/0)
Mass fraction of nickel in the alloy, measured during chemical analysis.

### MassFraction_P (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_P/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_P/1/0)
Mass fraction of phosphorus in the alloy, measured during chemical analysis.

### MassFraction_Pb (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Pb/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Pb/1/0)
Mass fraction of lead in the alloy, measured during chemical analysis.

### MassFraction_S (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_S/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_S/1/0)
Mass fraction of sulfur in the alloy, measured during chemical analysis.

### MassFraction_Si (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Si/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Si/1/0)
Mass fraction of silicon in the alloy, measured during chemical analysis.

### MassFraction_Ta (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Ta/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Ta/1/0)
Mass fraction of tantalum in the alloy, measured during chemical analysis.

### MassFraction_Ti (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Ti/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_Ti/1/0)
Mass fraction of titanium in the alloy, measured during chemical analysis.

### MassFraction_V (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_V/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_V/1/0)
Mass fraction of vanadium in the alloy, measured during chemical analysis.

### MassFraction_W (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_W/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MassFraction_W/1/0)
Mass fraction of tungsten in the alloy, measured during chemical analysis.

### MaterialAdditionalInformation (MLP)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MaterialAdditionalInformation/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MaterialAdditionalInformation/1/0)
The MaterialAdditionalInformation provides supplementary details about the material, adding to the material’s short name code symbols.

### MechanicalTest (SMC)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MechanicalTest/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/MechanicalTest/1/0)
The MechanicalTest Submodelcollection refers to procedures or assessments conducted to evaluate the mechanical properties, characteristics, or performance of a steel product.

### NotchImpactStrengthIndividualValues (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NotchImpactStrengthIndividualValues/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NotchImpactStrengthIndividualValues/1/0)
NotchImpactStrengthIndividualValues refer to the specific measured values of notch impact strength obtained from individual tests conducted on samples using a notch impact test. This value is the total energy required per unit cross-sectional area.

### NotchImpactStrengthMean (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NotchImpactStrengthMean/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NotchImpactStrengthMean/1/0)
NotchImpactStrengthMean refers to the average value of the notch impact strength obtained from multiple tests conducted on samples using a notch impact test. This value is the total energy required per unit cross-sectional area.

### NotchImpactWorkIndividualValues (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NotchImpactWorkIndividualValues/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NotchImpactWorkIndividualValues/1/0)
NotchImpactWorkIndividualValues refer to the specific measured values of notch impact strength obtained from individual tests conducted on samples using a notch impact test. This value is the total energy required.

### NotchImpactWorkMean (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NotchImpactWorkMean/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NotchImpactWorkMean/1/0)
NotchImpactWorkMean refers to the average value of the notch impact strength obtained from multiple tests conducted on samples using a notch impact test. This value is the total energy required.

### NotchImpactTest (SMC)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NotchImpactTest/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NotchImpactTest/1/0)
The SMC NotchImpactTest describes a mechanical test used to assess the toughness and impact resistance of a steel product.

### NumberOfPieces (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NumberOfPieces/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/NumberOfPieces/1/0)
Refers to the ordered amount of pieces of the product.

### OrderData (SMC)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/OrderData/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/OrderData/1/0)
OrderData contains relevant information of the order.

### OrderDate (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/OrderDate/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/OrderDate/1/0)
An OrderDate refers to the specific date on which the order was placed.

### OriginatorOfDocument (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/OriginatorOfDocument/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/OriginatorOfDocument/1/0)
The OriginatorOfDocument refers to the individual, entity, or source responsible for making the StatementOfCompliance.

### ProductData (SMC)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/ProductData/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/ProductData/1/0)
ProductData contains relevant information of the ordered product.

### Purchaser (Value)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Purchaser/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Purchaser/1/0)
Purchaser is the buyer of the product who has placed the order and who receives the invoice.

### PurchaserArticleNumber (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/PurchaserArticleNumber/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/PurchaserArticleNumber/1/0)
PurchaserArticleNumber ist the identifier of the product determined by the customer.

### SampleShape (MLP)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/SampleShape/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/SampleShape/1/0)
The SampleShape refers to the physical form or geometry of a steel product used for testing, analysis, or experimentation.

### SampleType (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/SampleType/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/SampleType/1/0)
Describes the specific notch impact test specimen type.

### SampleWidth (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/SampleWidth/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/SampleWidth/1/0)
SampleWidth refers to the width dimension of a sample.

### StatementOfCompliance (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/StatementOfCompliance/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/StatementOfCompliance/1/0)
The StatementOfCompliance refers to a formal declaration confirming that a steel product complies with specified requirements, regulations, standards, or contractual obligations.

### SteelmakingProcess (MLP)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/SteelmakingProcess/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/SteelmakingProcess/1/0)
The SteelmakingProcess refers to the metallurgic process, e.g. the basic oxygen process or the electric furnace process.

### TensileStrengthIndividualValues (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TensileStrengthIndividualValues/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TensileStrengthIndividualValues/1/0)
TensileStrengthIndividualValues refers to the specific measured values of tensile strength obtained from individual tests conducted on a steel product.

### TensileStrengthMean (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TensileStrengthMean/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TensileStrengthMean/1/0)
The TensileStrengthMean refers to the average value of the tensile strength of a steel product, which describes the stress a material can withstand while being stretched or pulled before breaking.

### TensileTest (SMC)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TensileTest/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TensileTest/1/0)
The SMC TensileTest refers to a mechanical test commonly performed to assess the strength and ductility of a steel product, in which the steel product is subjected to a controlled pulling force until breakage.

### TestTemperature (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TestTemperature/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TestTemperature/1/0)
The TestTemperature refers to the specific temperature at which a test or experiment is conducted.

### TheoreticalMass (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TheoreticalMass/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TheoreticalMass/1/0)
The TheoreticalMass typically denotes the calculated or predicted mass of a steel product based on theoretical models, formulas or equations. 

### TypeOfInspectionDocument (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TypeOfInspectionDocument/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts//1/0TypeOfInspectionDocument)
The TypeOfInspectionDocument property specifies according to EN 10204, whether the products meet the requirements on the basis of specific or unspecific tests. 

### TypeOfInspectionDocument/2.1 (Value)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TypeOfInspectionDocument/2.1/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TypeOfInspectionDocument/2.1/1/0)
The TypeOfInspectionDocument type 2.1 is specified in EN 10204 as "Declaration of compliance with the order". 

### TypeOfInspectionDocument/2.2 (Value)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TypeOfInspectionDocument/2.2/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TypeOfInspectionDocument/2.2/1/0)
The TypeOfInspectionDocument type 2.2 is specified in EN 10204 as "Test report". 

### TypeOfInspectionDocument/3.1 (Value)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TypeOfInspectionDocument/3.1/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TypeOfInspectionDocument/3.1/1/0)
The TypeOfInspectionDocument type 3.1 is specified in EN 10204 as "Inspection certificate 3.1".  

### TypeOfInspectionDocument/3.2 (Value)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TypeOfInspectionDocument/3.2/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/TypeOfInspectionDocument/3.2/1/0)
The TypeOfInspectionDocument type 3.2 is specified in EN 10204 as "Inspection certificate 3.2". 

### Validation (SMC)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Validation/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/Validation/1/0)
Validation contains data of the confirmation of compliance of the product.

### YieldOrProofStrengthInidivualValues (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/YieldOrProofStrengthInidivualValues/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/YieldOrProofStrengthInidivualValues/1/0)
YieldOrProofStrengthIndividualValues refers to the specific measured values of yield strength or proof strength obtained from individual tests conducted on a steel product.

### YieldOrProofStrengthMean (Property)
[https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/YieldOrProofStrengthMean/1/0](https://admin-shell.io/idta/InspectionDocumentsOfSteelProducts/YieldOrProofStrengthMean/1/0)
The YieldOrProofStrengthMean refers to the average yield of proof strength of a steel product, which describes the stress at which a steel product begins to deform plastically.


## Versions: [1.0](.)
This version is the first version to be officially published by IDTA Document **`IDTA 2032-1-0 Inspection Documents for Steel Products`**


## Contact

This sub-namespace is proposed by **IDTA Working Group Inspection Documents for Steel Products**. See also **[IDTA Registered AAS Submodel Templates](https://industrialdigitaltwin.org/content-hub/teilmodelle#:~:text=Inspection%20Documents TBD)** or contact via email the [IDTA project manager for submodel templates](mailto:sudip.adhikari@idtwin.org) or [chair of the working group](mailto:christian.keilig@iwu.fraunhofer.de).

This Submodel was created under the lead of [Fraunhofer IWU](iwu.fraunhofer.de).

