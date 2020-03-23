# Sub-Namespace for DataSpecifications

see [Details of the Asset Administration Shell - Part 1 - Version 2.0]() Section 5.2.2:


*'<AAS Unique Concept Identifier>'* ::= ('<Namespace>' | '<Namespace Qualifier>')"/"'<AAS Concept Identifier>'


'<Namespace>' ::= ( '<AAS Namespace>'|'<Data Specification Namespace>' )


'<AAS Namespace>' ::= '<Shell-Namespace>'"/aas/"'<Version>'
'<Data Specification Namespace>' ::='<Shell-Namespace>'"/DataSpecifications/"'<idShort of Data Specification>'/'<Version>'
'<Shell-Namespace>' ::= "http://admin-shell.io/"
'<Version>' ::= '<Digit>'/'<Digit>'
'<Digit>' ::= 1 | 2 | 3 | 4 | 5 | 6 | …

'<Namespace Qualifier>' ::= '<AAS Namespace Qualifier>'| Data Specification Qualifier>'
'<AAS Namespace Qualifier>' ::= "AAS:"
'<Data Specification Qualifier>' ::= defined per Data Specification

'<AAS Concept Identifier>' ::= '<AAS Class Name>'[('<AAS Attribute>'|'<AAS Enumeration>')]
'<AAS Attribute>' ::= "/"'<AAS Attribute Name>'[{"/"'<AAS Attribute Name>'}*]
'<AAS Enumeration>' ::= [{"/"'<AAS Attribute Name>'}*]"/"'<AAS Enumeration Value>'


## todo