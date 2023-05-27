# Awesome OSCAL
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome community resources, [maybe not quite production ready](https://gitter.im/usnistgov-OSCAL/Lobby?at=6075cc8f2e5574669b34555d), for increasing the adoption of the [Open Security Controls Assessment Language, OSCAL](https://pages.nist.gov/OSCAL).

Before contributing, please review the [Contribution Guidelines](https://github.com/oscal-club/awesome-oscal/blob/master/CONTRIBUTING.md).

## Content

- [Australian Cyber Security Centre's Information Security Manual in OSCAL](https://www.cyber.gov.au/ism/oscal): OSCAL-based security catalogs and profiles for the Australian Cyber Security Centre's Information Security Manual controls.

- [Center for Internet Security's ](https://github.com/CISecurity/CISControls_OSCAL/): the Center for Internet Security's Critical 18 Security controls as an OSCAL catalog, also with their controls related to other catalogs of security controls in the draft OSCAL mapping format.

- [CMS Acceptable Risk Safeguards](https://github.com/CMSgov/ars-machine-readable): the tailored profiles and catalog of adapted NIST SP 800-53 controls used by the Centers for Medicare and Medicaid Services in OSCAL format. Perhaps the first OSCAL content released by a US government agency other than NIST, separate of collaboration with FedRAMP.

- [Fathom5 SP 800-171 Catalog](https://github.com/FATHOM5/oscal/tree/main/content/SP800-171/oscal-content): the community-maintained version(s) of the NIST SP 800-171 catalog created by Fathom5.

## Tools

- [Alex Koderman's oscal4neo4j](https://github.com/Agh42/oscal4neo4j): a collection of scripts in Neo4j's Cypher query language to load OSCAL catalog data in JSON format into its graph database, potentially for use with [the Red Team Project's Security Control Knowledge Graph](https://gitlab.com/redteam-project/sckg).

- [Brian Ruf's OSCAL-GUI](https://github.com/brian-ruf/OSCAL-GUI): an example PHP web interface developed by [@brian-ruf](https://github.com/brian-ruf) of former FedRAMP fame. It has core presentation logic, file import, format conversion, and working profile resolution.

- [CivicActions's compliance-io](https://github.com/CivicActions/compliance-io): a library for composable functions for conversion from OpenControl to OSCAL.

- [CivicAction's oscal-component-definitions](https://github.com/CivicActions/oscal-component-definitions): a public collection of OSCAL component definitions for commonly used cloud services, software, security controls, and privacy controls.

- [CivicAtions's ssp-toolkit](https://github.com/CivicActions/ssp-toolkit): a suite of command line utilities in Python to mediate the creation of system security plans in NIST RMF 800-53 Revision 4 in OpenControl format. It can now export SSPs to OSCAL.

- [Control Plane's collie](https://github.com/controlplaneio/collie) a project demonstrating how infrastructure provisioned by cloud infrastructure controllers can be simultaneously secured and validated for compliance with Kyverno policies and OSCAL documents, leveraging Lula for validation.

- [Defense Unicorn's bigbang-oscal-component-generator](https://github.com/defenseunicorns/bigbang-oscal-component-generator): a CLI utility and Golang libraries to merge together individual OSCAL YAML components into a unified OSCAL YAML component definition, focused primarily on the specific needs of [Platform One's Big Bang](https://repo1.dso.mil/platform-one/big-bang/bigbang).

- [Defense Unicorn's Lula](https://github.com/defenseunicorns/lula): a Command Line Interface tool that will consume OSCAL component-definition files to configure and drive execution of automated control validation for Kubernetes utilizing the [Kyverno](https://kyverno.io/) policy management system.

- [Defense Unicorn's go-oscal](https://github.com/defenseunicorns/go-oscal): a Golang library to generate OSCAL data types.

- [DRTConfidence](https://www.drtconfidence.com): GRC Platform supporting all OSCAL artifacts (catalog, profile, ssp, sap, sar, poa&m) with FedRAMP extensions and validations implemented out of the box. Available in a FedRAMP JAB High authorized Government Cloud Center.

- [EasyDynamics OSCAL REST API Draft Standard](https://github.com/EasyDynamics/oscal-rest): an emerging standard for REST APIs to encourage all tool vendors to make a conformant API surface to reduce future churn in supporting heterogenous APIs for OSCAL-friendly tools and services.

- [EasyDynamics OSCAL React Library](https://github.com/EasyDynamics/oscal-react): a fully featured React component library for rendering all the OSCAL object models in JSON format with a developer-friendly API and a clean (but customizable) React-based UI.

- [EasyDynamics OSCAL REST API Service](https://github.com/EasyDynamics/oscal-rest-service): an initial Java-based implementation of some the OSCAL REST API listed above. It persists data as files in local directories.

- [EasyDynamics OSCAL Editor Deployment](https://github.com/EasyDynamics/oscal-editor-deployment): an integrated application, with the REST API service and React-based frontend (mentioned above), packaged as a simple Docker deployment of both open-source projects. It allows both viewing, and for some OSCAL document types and scenarios, editing file content and saving it to a properly configured Docker volume.

- [GSA's OSCAL Tools](https://github.com/GSA?q=oscal-&type=&language=&sort=): a collection of open-source tools provided by GSA teams to interoperate between OSCAL data (with required FedRAMP Extensions) and Word (DOCX) formats for SSPs, SARs, and SAPs.

- [GoComply's FedRAMP Utility](https://github.com/GoComply/fedramp): a tool that uses oscalkit (see below) to stamp in OSCAL data to the FedRAMP Word (DOCX) system security plan templates.

- [GoComply's oscalkit](https://github.com/GoComply/oscalkit): a Golang-based software development kit and command-line utility for operating on OSCAL data models. 

- [GovReady's GovReady-Q](https://github.com/GovReady/govready-q): an open source, web-based self-service GRC tool to automate security assessments and compliance from [@gregelin](https://github.com/gregelin) and the GovReady crew. It focuses on import and export of OSCAL data models.

- [Hidayatullah Ahsan's ValidateOscalDocuments](https://github.com/hahsan-ti/ValidateOscalDocuments): a C# library and console application to validate OSCAL XML documents.

- [IBM Compliance Trestle](https://github.com/IBM/compliance-trestle): an opinionated command-line tooling platform for managing compliance as code, using continuous integration and NIST's OSCAL standard.

- [John Jediny's OSCAL Static Site Playground](https://github.com/JJediny/oscal-static-site-playground): a static web application, using Gatsby and the US Web Design System, with hosting on the Federalist platform, to host a modern responsive application with OSCAL data models in JSON format dropped in place.

- [MITRE's InSpec OSCAL Plugin](https://github.com/mitre/inspec-oscal/tree/develop): an InSpec plugin developed by MITRE and open-source contributors to prototype the use of InSpec profiles with variables and configuration data embedded, in OSCAL components, SSPs, and other document instances.

- [mocolicious OSCAL-Examples](https://github.com/mocolicious/OSCAL-Examples): a collection of different front-end web applications leveraging OSCAL, mainly to show off different development workflows and environments. Current development status or community use is unclear.

- [NREL Cyber's oscal](https://github.com/NREL-CYBER/oscal): a library of types and utility functions for using the OSCAL JSON object models conveniently with Typescript applications.

- [NREL Cyber's oscal-atoms](https://github.com/NREL-CYBER/oscal-atoms): a library for Atomic components for interacting with oscal-cache (see below).

- [NREL Cyber's oscal-cache](https://github.com/NREL-CYBER/oscal-cache): a libray with a collection of stores, commands and queries for OSCAL application cache.

- [OMB'S OPAL](https://github.com/EOP-OMB/opal): OSCAL Policy Administration Library (OPAL) provides a simple web application from the US government's Office of Management and Budget for managing system security plans, using the OSCAL standard to inform its data models.

- [Project SledgeHammer](https://github.com/sunstonesecure-robert/sledgehammer): a project by Robert Ficcaglia and members of the Kubernetes Policy Working Group with an example of using OSCAL and SBOMs (SPDX at this time) as generated with Open Policy Agent (OPA) policies for Kubernetes clusters.

- [RedHat's OpenControl Database](https://github.com/RedHatGov/ocdb): a web application that demonstrates RedHat technologies' conformance to different compliance standards (i.e. NIST 800-53 Revisiion 5) and configuration baselines (i.e. DISA STIG for RedHat Enterprise Linux 7), supporting the export of various artifacts in OSCAL format with GoComply's library.

- [RegScale](https://regscale.com/oscal): RegScale Community Edition is a free to use, real-time Governance, Risk and Compliance (GRC) platform that deploys in any environment, integrating with security and compliance tools via API to keep compliance documentation continuously up to date.  GRC staff can work in the UI, engineers can write to the API, and OSCAL v1.0 content is automatically generated on demand.

- [Risk Redux's Control Freak](https://github.com/risk-redux/control_freak): a delightful Ruby on Rails application using the NIST 800-53 control catalogs in OSCAL JSON format to make the controls easily searchable.

- [SHR Group's iac2oscal](https://gitlab.com/shrgroup/oss/compliance-as-code/iac2oscal): a collection of Infrastructure-as-Code examples (primarily Ansible and Terraform) and how to link them to OSCAL component models for more tightly integrated Infrastructure-as-Code and Documentation-as-Code.

- [SHR Group's oscal-cli container](https://github.com/SHRGroup/oscal-cli): a GitHub repo with supporting GitHub Actions workflow that checks for new releases of [the NIST OSCAL Team's Java-based `oscal-cli` tool](https://github.com/SHRGroup/oscal-cli) and bundles the released application into an OCI container for each new release based on tags.

- [SHR Group's pyOSCAL](https://gitlab.com/shrgroup/oss/python/pyoscal): Python library to convert OSCAL content into python objects, developed by the clever [@mruge](https://github.com/mruge).  [pyOSCAL-Builder](https://gitlab.com/shrgroup/oss/python/pyoscal-builder) automatically generates pyOSCAL dynamically from the lastes NIST OSCAL Metaschema.

- [SHR Group's OSCAL Diagram Exmaples](https://gitlab.com/shrgroup/oss/compliance-as-code/example-diagrams): a collection of documentation and diagrams for advanced OSCAL use cases, primarily showing how to interrelate data inside OSCAL component definitions.

- [Wendell Piez's OSCAL Profile Import Examiner](https://wendellpiez.github.io/XMLjellysandwich/oscal/import-examiner/): [XMLJellySandwich]((https://github.com/wendellpiez/XMLjellysandwich)): a web-based, in-browser XSLT transform system leveraging SaxonJS. [@wendellpiez](https://github.com/wendellpiez) has focused one demo on validating an OSCAL profile in XML form by validating upstream catalog references.

## Articles and Blog Posts

- [Bill Weber's "The Future of SCAP Is the Missing Gap in OSCAL"](https://www.billweber.io/2022/05/13/the-future-of-scap-is-the-missing-gap-in-oscal/)

- [Bill Weber's "Tired of Following the Compliance Herd?"](https://www.billweber.io/2022/05/01/tired-of-following-the-compliance-herd/)

- [EasyDynamics "Innovating Security Compliance Through Open Standards"](https://blogs.easydynamics.com/2021/07/07/innovating-security-compliance-through-open-standards/)

- [EasyDynamics "DevSecComp(liance)Ops with OSCAL"](https://blogs.easydynamics.com/2022/03/18/devseccomplianceops-with-oscal/)

- [Greg Elin's "An Orientation to OSCAL in the DevSecOps Pipeline"](https://medium.com/@gregelin/an-orientation-to-oscal-in-the-devsecops-pipeline-b51e45f8503b)

- [IBM's "Compliance Automated Standard Solution (COMPASS), Part 1: Personas and Roles"](https://dzone.com/articles/compass-compliance-part-1)

- [IBM's "Compliance Automated Standard Solution (COMPASS), Part 2: Trestle SDK"](https://dzone.com/articles/compliance-automated-standard-solution-compass-part-2-trestle-sdk)

- [IBM's "Compliance Automated Standard Solution (COMPASS), Part 3: Artifacts and Personas"](https://dzone.com/articles/compliance-automated-standard-solution-compass-part-3-artifacts-and-personas)

- [Šimon Lukašík's "GoComply with OSCAL & FedRAMP :: Introduction to OSCAL"](http://isimluk.com/posts/2020/12/gocomply-with-oscal-fedramp-introduction-to-oscal/)

- [Šimon Lukašík's "GoComply with OSCAL & FedRAMP :: Introduction to oscalkit"](http://isimluk.com/posts/2020/12/gocomply-with-oscal-fedramp-introduction-to-oscalkit/)

- [Šimon Lukašík's "GoComply with OSCAL & FedRAMP :: Introduction to Metaschema"](http://isimluk.com/posts/2020/12/gocomply-with-oscal-fedramp-introduction-to-metaschema/)

## Presentations and Talks

- [Andrew Martin and Control Plane's "Avoiding IAC Potholes with Policy + Cloud Controllers"](https://www.youtube.com/watch?v=cvoWlwftbEE&list=PLj6h78yzYM2NQ-Zi_k5qVmZyxSmLBzM6V&index=47) from Cloud Native Security Con North America 2023

- [Robert Ficcaglia's "12 Essential Requirements for Policy Enforcement and Governance with OSCAL"](https://www.youtube.com/watch?v=7pbIVjSluMs&list=PLj6h78yzYM2NQ-Zi_k5qVmZyxSmLBzM6V&index=52) from Cloud Native Security Con North America 2023

## Other Resources

- [Brad Hards ISM OSCAL Catalog](https://github.com/bradh/ism-oscal): a community developer's collection of [the Australian Government's Information Security Manual security controls](https://www.cyber.gov.au/acsc/view-all-content/ism) in the form of an OSCAL catalog and profiles (including Essential 8).

- [oscal-diagrams](https://github.com/cyght-io/oscal-diagrams): Automatically generated diagrams for visualizing the OSCAL data models.
