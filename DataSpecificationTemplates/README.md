# Sub-Namespace for DataSpecifications

see [Details of the Asset Administration Shell - Part 1 - Version 2.0]() Section 5.2.2:

<Namespace> ::= ( <AAS Namespace>|<Data Specification Namespace> )
<Namespace Qualifier> ::= <AAS Namespace Qualifier>| Data Specification Qualifier>
<AAS Namespace> ::= <Shell-Namespace>"/aas/"<Version>
<Data Specification Namespace> ::=<Shell-Namespace>"/DataSpecifications/"<idShort of Data Specification>/<Version>
<Shell-Namespace> ::= "http://admin-shell.io/"
<Version> ::= <Digit>/<Digit>
<Digit> ::= 1 | 2 | 3 | 4 | 5 | 6 | …