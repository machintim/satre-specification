(standard)=

# A Standard Architecture for TREs

<!-- What this document intends to do (and what it doesn't), the level of detail we aim for contrasted with other technical standards -->

The SATRE standard has been developed based on the following principles:

- TREs should be as as easy as possible for end-users to use (_e.g._ researchers) whilst still remaining secure.
- TRE deployments should be offered that support data of different levels of sensitivity (_e.g._ through a tiered system of technical controls and policies).
- TREs conforming to the standard should be interoperable and provide a familiar end-user experience.
- The standard will be managed and updated following an open, community-driven process, and will not be tied to a single vendor or implementation.

The SATRE standard is based around the idea of capabilities, some of which are required and some of which are optional.
Any particular TRE implementation should be able to score itself against each capability as either "supported", "partially supported" or "unsupported" (see {ref}`evaluation` for details).
The capabilities are grouped into the following broad categories:

- information governance
- computing technology
- data management
- information security

In addition to these capabilities, any organisation running a TRE will need to consider:

- legal requirements — particularly around data protection and contract management
- relationship management — engagement with internal and external stakeholders as well as the wider public

<!-- ## Required TRE features

> Crowdsourced list of functionality from TRE developers survey that were considered the most important/ <u>essential components in order to define a software as a TRE</u>. Each of these should be described in prose and where appropriate examples of these features present in existing TRE implementations provided. Where features vary across existing TREs this should be highlighted. -->

<!-- ### Feature A
### Feature B
## Optional TRE features

Also crowdsourced from the survey, but this time all the features that were considered less important and/or are not needed in order to simply define something as a TRE (for example this might include something like HPC-connectability).

### Feature X
### Feature Y -->

## TRE capabilities

There might be good reasons why any particular TRE does not possess one or more of the capabilities listed in this specification, but we think all TREs should aspire to meet them in the long-term.

### Information governance

#### Compliance, monitoring and reporting

#### Policy regulation and management

#### Quality management

- Internal audit and reporting

#### Risk management

#### Project and study management

#### Researcher accreditation

- Training management
- Training delivery

### Computing technology

#### End user computing

- User interface (eg. terminal, desktop, notebook, webapp etc.)
- Software tools

#### Compute beyond the desktop

- High performance computing
- Accelerators (GPU, FPGA, ASIC, xPU)
- Cluster computing (SLURM, Kubernetes etc.)
- Databases (both SQL and noSQL)

#### Data analytics

#### Network management

#### Application lifecycle management

#### Infrastructure lifecycle management

- Capacity management
- Deployment management
- Configuration management

### Data management

#### Data lifecycle management

#### Identity and access management

#### Management of outputs

#### Recording available datasets

### Information security

#### Vulnerability management

#### Security testing

#### Data encryption

#### Physical security

#### Availability management
<!-- JR: not sure what this means -->

## Roles

A TRE conforming to the SATRE standard should provide a broadly similar experience for stakeholders operating in each of these defined roles.
There is not necessarily a one-to-one mapping between roles and people.
One person can have multiple roles.

### TRE users

The researchers working on projects that involve logging into a TRE to access data.
The document will explain that user experience of the platform and associated documentation should feel similar across TREs conforming to SATRE standard.

### TRE administration roles

The IT and related professionals who will be responsible for deploying and managing instances of a TRE conforming to the SATRE standard.
The document will explain that SATRE conforming TREs should have documentation and infrastructure deployment code/apps that conform to software engineering best practices, which are also defined here, making them "simple" for an IT professional to follow; troubleshooting steps included.

These roles cover managing TRE computing infrastructure, but also administering the TRE itself (e.g. managing users and projects).

### TRE developer roles

The software engineers responsible for developing and maintaining TRE software, including adding functionality, bug fixes and general maintenance.
The document will explain recommended practices suitable for developing a software of this complexity and reference learnings from existing TRE developers.

### TRE governance roles

Roles that uphold the governance of TREs.
Such governance responsibilities typically involve establishing policies and procedures to ensure the responsible use of data, protecting the privacy and confidentiality of research participants, and promoting transparency and accountability in research activities.
Typical roles might include data custodians, ethicists, an independent board or a lay panel.

## Architecture

Includes diagrams of how the TRE features connect together, but remains a high level description that doesn't specify which exact technologies a TRE developer should use.
This can also offer an explanation of how people from different roles interact/experience these features.

## Conclusion

Benefits of adopting this standard for developing a TRE. 
Benefits of existing TRE efforts working to conform to this standard (users and admin roles as well as developers).