# Asset Administration Shell Identifiers

The Asset Administration Shell itself only defines the structure and syntax of the Industry 4.0 Component. Content, its features, attributes and values need to be semantically defined. It is not in scope of the Platform Industry 4.0 to define and/or maintain such domain-specific entities itself. Therefore, definitions and terms from external vocabulary providers are recommended, for instance [eCl@ss](https://www.eclasscontent.com/) or [IEC CDD](https://cdd.iec.ch/).

While many attributes, properties and values are defined in such vocabularies, there is a significant chance that some necessary entities are still missing. The 'Asset Administration Shell Identifiers' is preliminary approach to provide a first, lightweight location to register new identifiers. This is done by relying on the [admin-shell.io](https://admin-shell.io) domain as a common namespace.

The Coordination Board of the Plattform Industry 4.0 is maintaining the Asset Administration Shell Identifiers and ensures the continuity and stability of the identifiers. As such, it is in the authority of the Coordination Board to accept, revise, adjust or decline requested identifiers.


## Identifier Scheme and Description

The identifiers are encoded as URIs, in the HTTP scheme. The following pattern is used:

http(s)://admin-shell.io/`<sub-namespace>`[/`<version>`[/`<revision>`]]/`<ShortId>`[/`<AttributeShortId>`[/`<ValueShortId>`]]

It is recommended to use the qualified names for the sub-namespace and the ShortId. Especially should the subnamespace indicate the domain or use case it is intended to be used. Existing sub-namespaces can only be extended (a) by the organization which originally suggested it, (b) with their explicit consent, or (c) by the Coordination Board.



## Registering Process

There are two possible processes to request identifiers:

1. Work with the GitHub Repository
- Fork the [GitHub Repo](https://github.com/admin-shell-io/id/)
- Add a new folder with the sub-namespace as its name
- Create a README following the template in https://github.com/admin-shell-io/id/blob/master/templates/README.md
- Create a Pull Request from your forked repository to the original

2. Contact the [Coordination Board for Submodels](mailto:coordination-board@admin-shell.io)
- Explain the purpose of the new identifier(s)
- Attach the filled [template](https://github.com/admin-shell-io/id/blob/master/templates/README.md)

The request will be processed as soon as possible. However, no guaranteed process time can be given.


## Self-Registering Identifiers

In order to speed up the declarations even further, the [sandbox](sandbox/) sub-namespace serves as a quick approach to self-assign preliminary identifiers. Pull Requests to this directory will be accepted without any in depth evaluation and as quick as possible. Note that identifiers in this sub-namespace might change/be erased without further notification and at any time.


## Guidelines

Only organizations can suggest Asset Administration Shell Identifiers, requests from individuals cannot be regarded. Please take care that your organization is there for the next years.

Add contact information. Only requests with at least two valid and responding email addresses will be regarded. In case the contact person changes, please update the according information in the respective README or inform the Coordination Board.

Use Asset Administration Shell Identifiers only for Industry 4.0 related topics. This offer is not intended for any identifiers but has a strong focus on Industry 4.0 and the Asset Administration Shell.

Asset Administration Shell Identifiers are intended to stay. Please think about really necessary terms and entities and restrict them to a minimal set.
