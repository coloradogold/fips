# FIO Improvements Proposals (FIPs)
FIPs describe proposed changes to the FIO Protocol.

## Contributing
### Review FIPs
Everyone is encouraged to review existing FIPs and provide feedback.
### Proposing a FIP
#### FIP Process
The proposal and development process for a FIP includes:

* To propose a FIP, fork this repository and create a pull request for your FIP with status *Draft*. The FIP number can remain undetermined at this stage. See Successful FIP includes below for what a FIP should include.
* Repo custodians will review the FIP PR and comment. Once comments have been addressed, the FIP will be merged to Master with the status *Draft*.
* Reach out to the community and solicit feedback on your FIP.
* Once you have updated your FIP based on community feedback, create another pull request with all of the updates along with a request to update the status to *Accepted*.
* Once repo custodians accept your FIP, you can code your solution and submit pull requests to the relevant repo.
* After the code has been merged and deployed to Mainnet, the status will be changed to *Final*.
### Discussing a FIP
Create an issue describing the FIP or section of a FIP you would like to open up for discussion.

## FIP Type
* Core - improvements requiring a consensus fork
* Functionality - adds or modifies functionality without need for consensus fork
* RFC - Describes a design issue, or provides general guidelines or information to the FIO community, but does not propose a new feature.

## FIP Status
* Draft - a FIP that is open for consideration.
* Accepted - a FIP that is planned for immediate adoption. Changes may still be made as required by development.
* Final - a FIP that has been adopted, coded, merged, and deployed by the block producers on FIO mainnet.
* Deferred - a FIP that is not being considered for immediate adoption. May be reconsidered in the future.

## Successful FIP includes
### Preamble
Each EIP must begin with an RFC 822 style header preamble, preceded and followed by three hyphens (---). This header is also termed “front matter” by Jekyll. The headers must appear in the following order. All other headers are required.
```
---
fip: FIP number
title: FIP title
status: FIP status
type: FIP type
author: a list of the author’s or authors’ name(s) and/or username(s), or name(s) and email(s)
created: FIP create date
updated: FIP update date
---
```
### Abstract
A short (~200 word) description of the technical issue being addressed.

### Motivation
An explanation of why the existing protocol specification is inadequate to address the problem that the FIP solves.

### Specification
Detailed definition of what is being changed, e.g. actions, API end-points, processing logic, exception handling, fees, etc.

### Rationale
The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made.

### Implementation
Initially this section should include technical implementation strategy, such how this change made (contracts, core, etc.), how will the specification be accomplished in code, how will the code be tested/deployed. Before development beings, create a master ticket in the fio repo to track progress on development towards this FIP.

### Backwards Compatibility
All FIPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The FIP must explain how the author proposes to deal with these incompatibilities.

### Future considerations
This section may include proposals for how the new functionality could be enhanced in the future.
