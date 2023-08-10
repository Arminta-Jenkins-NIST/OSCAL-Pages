---
title: "Resources"
menu:
  primary:
    name: Resources
    weight: 40
sidenav:
  focusrenderdepth: 2
  inactiverenderdepth: 2
  activerenderdepth: 2
toc:
  enabled: true
aliases:
  - /resources/
  - /downloads/other-resources/
  
---
Download --> New Resource Page

## OSCAL Concepts
- Key [terminology](terminology/);
- The OSCAL [layers and models](layer/);
- [UUIDs usage](identifier-use);
- [Profile Resolution](processing/);
- OSCAL implementation [examples](examples/) ; and
- A discussion of how OSCAL [relates](relations-to-other/) to and draws inspiration from other documentary standards.

## OSCAL Releases
Official releases of the OSCAL Project are available on the project's [GitHub repository](https://github.com/usnistgov/OSCAL/releases). These releases align with the project's [roadmap](/contribute/roadmap/).


### Latest Release
Release Notes here

### 1.0.3
Release notes Here

### 1.0.2

### Latest Dev Version

You can also get the [latest development version](https://github.com/usnistgov/OSCAL/tree/develop) [ZIP](https://github.com/usnistgov/OSCAL/archive/refs/heads/develop.zip).

OSCAL uses version strings for releases based on the [semantic versioning v2.0.0](https://semver.org/spec/v2.0.0.html) specification. Please refer to the [versioning and branching documentation](https://github.com/usnistgov/OSCAL/blob/main/versioning-and-branching.md) for more information.

## OSCAL Content

- NIST [OSCAL Content Repository](https://github.com/usnistgov/oscal-content)
- Federal Risk and Authorization Management Program (FedRAMP) [Automation GitHub Repository](https://github.com/GSA/fedramp-automation)

## OSCAL Compatibility Commitment

The OSCAL Project team recognizes the impact of syntax changes on content and tool developers following an evolving language. As we develop OSCAL, the team will take care to minimize the impact of any necessary changes. Syntax changes to the OSCAL XML and JSON models will only occur where there is a compelling need to do so. To the greatest extend practical, OSCAL-based content produced today will be future compatible.

The OSCAL team can not anticipate all issues raised or feedback received. In some cases, changes to the OSCAL models will need to be made to address a compelling issue. In these instances, the OSCAL team will do everything practical to minimize the impact to early adopters, and document any changes where impacts are unavoidable in the [release notes](https://github.com/usnistgov/OSCAL/releases).

NIST encourages early adoption of released OSCAL content, tools, and schema. In general early adopters can count on the following, from the first milestone release to the first official 1.0.0 release of OSCAL:

- Any data element modeled in the milestone release will be modeled in the 1.0.0 release. Typically with the same syntax.
- All features available in a milestone release will be available in the 1.0.0 release.
- Deferred features, such as cryptographic validation, will be implemented while minimizing the impact to existing content. Most new features will be implemented as optional extensions with no impact to existing content.

## OSCAL Examples

To facilitate the OSCAL adoption in ways that allow the adopters to take full advange of OSCAL abilities of representing the security data and the automation of the security assessment and of the risk management with a maximum return on investment (ROI), the NIST OSCAL team published basic examples of OSCAL content instances in the NIST's OSCAL-content repository, the [examples](https://github.com/usnistgov/oscal-content/tree/main/examples) directory.

To properly understand the examples, interested parties are advised to also review the [OSCAL walkthrough tutorials](https://pages.nist.gov/OSCAL/learn/tutorials).

{{% callout note %}} More OSCAL examples supporting the use of the OSCAL models are developed and maintained by the community in the [OSCAL Club examples repository](https://github.com/oscal-club/examples) .{{% /callout %}}

### Validation

OSCAL examples need to always be formally *validated* to confirm their correctness and fitness for a risk management process and security automation. See [Well-formed Data Formats and Valid OSCAL](https://pages.nist.gov/OSCAL/concepts/layer/validation/) and [Validation of any OSCAL content instance](https://pages.nist.gov/OSCAL/tools/#validation) for more details on how to accomplish OSCAL content instance validation by applying the appropriate schema for the respective format. 

## OSCAL Tools

The [OSCAL models](/concepts/layer/) provide standardized formats for exchanging control, control implementation, and control assessment information in XML, JSON, and YAML, in support of interoperable security assessment automation and continuous monitoring. These formats allow this information to be exchanged between tools ensuring interoperability, and for individual tools, to process exchanged data, supporting analytics, user interaction, and security assessment automation where suitable.

{{% callout note %}} Tools supporting the use of the OSCAL models are instrumental for a broad adoption of OSCAL in support of interoperable security assessment automation.  The community maintains a list of known OSCAL tools in the [Awesome OSCAL](https://github.com/oscal-club/awesome-oscal) repository.{{% /callout %}}

The following types of tools are developed by NIST OSCAL team:
- commodity tooling for basic operations such as format validation, data conversion between supported formats
- application frameworks, tools and libraries