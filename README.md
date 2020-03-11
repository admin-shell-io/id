# Asset Administration Shell Identifiers

The Asset Administration Shell itself only defines the structure and syntax of the Industry 4.0 Component. Content, its features, attributes and values need to be semantically defined. It is not in scope of the Platform Industry 4.0 to define and/or maintain such domain-specific entities itself. Therefore, definitions and terms from external vocabulary providers are recommended, for instance [eCl@ss]() or [IEC CDD]().

While many attributes, porperties and values are defined in such vocabularies, there is a significant chance that some necessary entities are still missing. The 'Asset Administration Shell Identifiers' is preliminary approach to provide a first, lightweight location to register new identifiers. This is done by relying on the [admin-shell.io](http://admin-shell.io) domain as a common namespace.

## Identifier Scheme and Description

The identifiers are encoded as URIs, in the HTTP scheme. The following pattern is used:

http(s)://admin-shell.io/<subnamespace>/<ShortId>/




## Registering Process

There are two possible processes to request identifiers:

1. Work with the Github
- Fork the [GitHub Repo](https://github.com/sebbader/id/)
- Add a new folder with the subnamespace as its name
- Create a README following the template in https://github.com/sebbader/id/template/README.txt
- Create a Pull Request from your forked repository to the original

2. Contact the [Coordination Board for Submodels](mailto:coordination-board@admin-shell.io)
- Explain the purpose of the new identifier(s)
- Attach the filled [template](https://github.com/sebbader/id/template/README.txt)
