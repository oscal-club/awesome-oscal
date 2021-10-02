# Awesome OSCAL
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome community resources, [maybe not quite production ready](https://gitter.im/usnistgov-OSCAL/Lobby?at=6075cc8f2e5574669b34555d), for increasing the adoption of the [Open Security Controls Assessment Language, OSCAL](https://pages.nist.gov/OSCAL).

Before contributing, please review the [Contribution Guidelines](https://github.com/oscal-club/awesome-oscal/blob/master/CONTRIBUTING.md).

## Tools

- [Brian Ruf's OSCAL-GUI](https://github.com/brian-ruf/OSCAL-GUI): An example PHP web interface developed by [@brian-ruf](https://github.com/brian-ruf) of former FedRAMP fame. It has core presentation logic, file import, format conversion, and working profile resolution.

- [EasyDynamics OSCAL REST API Draft Standard](https://github.com/EasyDynamics/oscal-rest): an emerging standard for REST APIs to encourage all tool vendors to make a conformant API surface to reduce future churn in supporting heterogenous APIs for OSCAL-friendly tools and services.

- [EasyDynamics OSCAL React Library](https://github.com/EasyDynamics/oscal-react): a fully featured React component library for rendering all the OSCAL object models in JSON format with a developer-friendly API and a clean (but customizable) React-based UI.

- [GSA's OSCAL Tools](https://github.com/GSA?q=oscal-&type=&language=&sort=): A collection of open-source tools provided by GSA teams to interoperate between OSCAL data (with required FedRAMP Extensions) and Word (DOCX) formats for SSPs, SARs, and SAPs.

- [GoComply's FedRAMP Utility](https://github.com/GoComply/fedramp): a tool that uses oscalkit (see below) to stamp in OSCAL data to the FedRAMP Word (DOCX) system security plan templates.

- [GoComply's oscalkit](https://github.com/GoComply/oscalkit): a Golang-based software development kit and command-line utility for operating on OSCAL data models. 

- [GovReady's GovReady-Q](https://github.com/GovReady/govready-q): An open source, web-based self-service GRC tool to automate security assessments and compliance from [@gregelin](https://github.com/gregelin) and the GovReady crew. It focuses on import and export of OSCAL data models.

- [IBM Compliance Trestle](https://github.com/IBM/compliance-trestle): An opinionated command-line tooling platform for managing compliance as code, using continuous integration and NIST's OSCAL standard.

- [John Jediny's OSCAL Static Site Playground](https://github.com/JJediny/oscal-static-site-playground): a static web application, using Gatsby and the US Web Design System, with hosting on the Federalist platform, to host a modern responsive application with OSCAL data models in JSON format dropped in place.

- [mocolicious OSCAL-Examples](https://github.com/mocolicious/OSCAL-Examples): A collection of different front-end web applications leveraging OSCAL, mainly to show off different development workflows and environments. Current development status or community use is unclear.

- [OMB'S OPAL](https://github.com/EOP-OMB/opal): OSCAL Policy Administration Library (OPAL) provides a simple web application from the US government's Office of Management and Budget for managing system security plans, using the OSCAL standard to inform its data models.

- [NREL Cyber's oscal](https://github.com/NREL-CYBER/oscal): a library of types and utility functions for using the OSCAL JSON object models conveniently with Typescript applications.

- [NREL Cyber's oscal-atoms](https://github.com/NREL-CYBER/oscal-atoms): a library for Atomic components for interacting with oscal-cache (see below).

- [NREL Cyber's oscal-cache](https://github.com/NREL-CYBER/oscal-cache): A libray with a collection of stores, commands and queries for OSCAL application cache.

- [Risk Redux's Control Freak](https://github.com/risk-redux/control_freak): a delightful Ruby on Rails application using the NIST 800-53 control catalogs in OSCAL JSON format to make the controls easily searchable.

- [SHR Group's iac2oscal](https://gitlab.com/shrgroup/oss/compliance-as-code/iac2oscal): A collection of Infrastructure-as-Code examples (primarily Ansible and Terraform) and how to link them to OSCAL component models for more tightly integrated Infrastructure-as-Code and Documentation-as-Code.

- [SHR Group's pyOSCAL](https://gitlab.com/shrgroup/oss/python/pyoscal): Python library to convert OSCAL content into python objects, developed by the clever [@mruge](https://github.com/mruge).  [pyOSCAL-Builder](https://gitlab.com/shrgroup/oss/python/pyoscal-builder) automatically generates pyOSCAL dynamically from the lastes NIST OSCAL Metaschema.

- [SHR Group's OSCAL Diagram Exmaples](https://gitlab.com/shrgroup/oss/compliance-as-code/example-diagrams): a collection of documentation and diagrams for advanced OSCAL use cases, primarily showing how inter-relate data inside OSCAL component definitions.

- [Wendell Piez's OSCAL Profile Import Examiner](https://wendellpiez.github.io/XMLjellysandwich/oscal/import-examiner/): [XMLJellySandwich]((https://github.com/wendellpiez/XMLjellysandwich)) is a web-based, in-browser XSLT transform system leveraging SaxonJS. [@wendellpiez](https://github.com/wendellpiez) has focused one demo on validating an OSCAL profile in XML form by validating upstream catalog references.

## Blog Posts

- [EasyDynamics "Innovating Security Compliance Through Open Standards"](https://blogs.easydynamics.com/2021/07/07/innovating-security-compliance-through-open-standards/)

- [Šimon Lukašík's "GoComply with OSCAL & FedRAMP :: Introduction to OSCAL"](http://isimluk.com/posts/2020/12/gocomply-with-oscal-fedramp-introduction-to-oscal/)

- [Šimon Lukašík's "GoComply with OSCAL & FedRAMP :: Introduction to oscalkit"](http://isimluk.com/posts/2020/12/gocomply-with-oscal-fedramp-introduction-to-oscalkit/)

- [Šimon Lukašík's "GoComply with OSCAL & FedRAMP :: Introduction to Metaschema"](http://isimluk.com/posts/2020/12/gocomply-with-oscal-fedramp-introduction-to-metaschema/)

## Other Resources

- [Brad Hards ISM OSCAL Catalog](https://github.com/bradh/ism-oscal): a community developer's collection of [the Australian Government's Information Security Manual security controls](https://www.cyber.gov.au/acsc/view-all-content/ism) in the form of an OSCAL catalog and profiles (including Essential 8).
