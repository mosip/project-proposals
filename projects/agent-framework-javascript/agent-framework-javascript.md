# Project Name

This is still up for debate. Until then, the working title is _Agent Framework JavaScript_.

# Preferred Maturity Level

Considering the fact that the project has been adopted by various companies and governments, and powers a number of production use cases, the _impact_ stage seems appropriate. However, the project does not fulfill the "is commonly used in enterprise production environments".

Therefore, the project is estimated to be in the _growth_ stage, approaching the _impact_ stage.

# Project Description

Aries Framework JavaScript has evolved significantly since its inception as a Hyperledger Aries project. Initially, it heavily relied on Hyperledger standards such as DIDComm, Indy, and AnonCreds. However, with advancements in verifiable credential technology and the emergence of new standards, the framework underwent multiple refactoring and modularization processes to maintain interoperability.

This allowed for the inclusion of non-Hyperledger standards like W3C Verifiable Credentials with Data Integrity Proofs, DIF Presentation Exchange, OpenID4VC, and SD-JWT integration. As industry requirements shifted towards greater modularity, it became apparent that a unified framework may be better.

The future direction for Aries Framework JavaScript involves adopting a compartmentalized approach consisting of single-purpose libraries designed to work together seamlessly, building on what is already out there. This transition will take considerable effort and will, therefore, be gradual.

In order to expand the framework's support for standards beyond the Hyperledger ecosystem, a reassessment of its governance was necessary. The OpenWallet Foundation (OWF) has been considered a potential steward due to its commitment to promoting interoperability without directly developing or maintaining standard protocols.

![afj-high-level-arch.png](./afj-high-level-arch.png)

> **NOTE<sup>1<sup>:** In addition to the [Aries Framework JavaScript repository](https://github.com/hyperledger/aries-framework-javascript), we propose moving the [Aries Framework JavaScript Extensions](https://github.com/hyperledger/aries-framework-javascript-ext) repository too, due to its tight relationship with the framework.
>
> **NOTE<sup>2<sup>:** Another Hyperledger project that is tightly related to the framework is [Aries Mobile Agent React Native (a.k.a. Bifold)](https://github.com/hyperledger/aries-mobile-agent-react-native). This project is maintained by a different set of people and is therefore not included in this proposal.

# Alignment with the OpenWallet Foundation Mission

The objective is to promote interoperability by supporting numerous standards, as was outlined earlier. As a Hyperledger project, all components have been open source from the beginning.

Maintainers will persist in collaborating with Standards Development Organizations (SDOs) across ecosystems, as done previously.

# Code of Conduct

Both Hyperledger and the OpenWallet Foundation follow the [Linux Foundation's Europe Policies](https://8112310.fs1.hubspotusercontent-na1.net/hubfs/8112310/Exhibit%20B%20--%20Linux%20Foundation%20Europe%20Policies.pdf)

# TAC Sponsor

- Tracy Kuhrt
- Stavros Kounis

# Project License

The project has an Apache 2.0 license: [Aries Framework JavaScript - License)](https://github.com/hyperledger/aries-framework-javascript%23license)

# Source Control

The project is hosted in GitHub and includes the following repositories:

- The framework [Aries Framework JavaScript)](https://github.com/hyperledger/aries-framework-javascript%23license)
- The framework's extensions: [Aries Framework JavaScript Extensions](https://github.com/hyperledger/aries-framework-javascript-ext%23license)

# Issue Tracker

The issues are tracked using GitHub's Issues feature in the corresponding repository. For issues that span across multiple repositories, GitHub's Projects feature may be used.

# External Dependencies

Please see [Aries Framework JavaScript - Dependency Licenses](./dependency-licensing-overview.md)

# Release Methodology

All proposed repositories have continuous deployment/delivery pipelines built using [GitHub Actions](https://github.com/features/actions). The individual packages follow the [_semantic versioning_](https://semver.org/) method, ensuring consistency and safety. Whenever a pull request is merged into the `main` branch that doesn't cause a _major_, _minor_ or _patch_ version increase, an _alpha_ version is released.

# Initial Maintainers

| name               | Github                                                     | Organization    |
| ------------------ | ---------------------------------------------------------- | --------------- |
| Berend Sliedrecht  | [@berendsliedrecht](https://github.com/berendsliedrecht)   | Animo Solutions |
| Jakub Kočí         | [@jakubkoci](https://github.com/jakubkoci)                 | Absa Group      |
| James Ebert        | [@JamesKEbert](https://github.com/JamesKEbert)             | Indicio         |
| Karim Stekelenburg | [@karimStekelenburg](https://github.com/karimStekelenburg) | Animo Solutions |
| Timo Glastra       | [@TimoGlastra](https://github.com/TimoGlastra)             | Animo Solutions |
| Ariel Gentile      | [@genaris](https://github.com/genaris)                     | 2060.io         |
| Jan Rietveld       | [@janrtvld](https://github.com/janrtvld)                   | Animo Solutions |
|                    |                                                            |                 |

# Proposed Project Governance

The current governance model under Hyperledger is community-based. This means that decisions are made democratically, with the aim of community consensus. In cases where no clear consensus is established, active contributors may be granted a louder voice.

This approach has proven effective and will be continued as the chosen governance model.

# Links to Documented Governance Practices

> Work in progress. The intake form has been submitted.

# Financial Sponsorship

Hyperledger has covered infrastructure related costs. Besides that, None.

# Infrastructure

- GitHub repositories
- CI (GitHub actions)
- Bug Tracking (GitHub Issues and GitHub Projects)
- Communication channels (Discord)
- Mailing list
- Video conference (Zoom)
