# BEP - BEL Enhancement Proposals

BEL enhancement proposals will be developed and posted here for public consumption.  Any changes to the BEL Language or aspects highly pertinent to the BEL language such as BEL Nanopubs need to be proposed here.

The main focus of this is for the BEL Language enhancements or deprecations and community-wide standards such as the BEL Nanopub JSONSchema. It is not necessarily for the BEL.bio API as that is an implementation of a BEL API, though well constructed BEPs detailing enhancements for the BEL.bio API will be appreciated by the BEL.bio maintainers.

Please copy the template provided and fill out the relevant sections.  While the BEP is in Draft mode - please add it to the Draft directory. When it is approved, it will be moved to the Published directory.

If you have questions or need help updating a proposal, please add an issue to this project with your contact information.  Someone will contact you to help you write your proposal or edit a proposal.

Anyone can submit a BEP or propose edits to a BEP in DRAFT mode even if you are not the creator of the BEP.  The creator of the BEP will decide what edits to include.

## Tutorial

[Submitting a BEP Proposal Tutorial](https://github.com/belbio/bep/blob/master/BEP-Proposal-Tutorial.pdf)

If you are uncomfortable with creating a BEP using Github Pull Requests, you can send the BEP to me whayes at biodati dot com, and I will add it for you.

## BEP Types

There are three kinds of BEP:

A Standards Track BEP describes a new feature or implementation for BEL. It may also describe an interoperability standard that will be supported outside the standard BEL functionality.

An Informational BEP describes a BEL design issue, or provides general guidelines or information to the BEL community, but does not propose a new feature. Informational BEPs do not necessarily represent a BEL community consensus or recommendation, so users and implementers are free to ignore Informational BEPs or follow their advice.

A Process BEP describes a process surrounding BEL, or proposes a change to (or an event in) a process. Process BEPs are like Standards Track BEPs but apply to areas other than the BEL language itself. They may propose an implementation, but not to BEL's codebase; they often require community consensus; unlike Informational BEPs, they are more than recommendations, and users are typically not free to ignore them. Examples include procedures, guidelines, changes to the decision-making process, and changes to the tools or environment used in BEL development. Any meta-BEP is also considered a Process BEP.


## Parts of a BEP

Preamble -- Header containing meta-data about the BEP, including the BEP number, a short descriptive title (limited to a maximum of 44 characters), the names, and optionally the contact info for each author, etc.

Abstract -- a short (~200 word) description of the technical issue being addressed.

Rationale and Goals -- The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made.

It should clearly explain why the existing language specification is inadequate to address the problem that the BEP solves. BEP submissions without sufficient motivation may be rejected outright. It should also describe alternate designs that were considered and related work.

The rationale should provide evidence of consensus within the community and discuss important objections or concerns raised during discussion.

Use Cases -- share how the new language feature will be used. For example, adding a populationAbundance() function would allow capturing population level changes due to environment or treatment. Consumers would be the EPA, Toxicologists, Microbiome biologists, etc.

Specification -- The technical specification should describe the syntax and semantics of any new language feature.

Backwards Compatibility -- All BEPs that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The BEP must explain how the author proposes to deal with these incompatibilities. BEP submissions without a sufficient backwards compatibility treatise may be rejected outright.

Reference Implementation -- The reference implementation must be completed before any BEP is given status "Final", but it need not be completed before the BEP is accepted. While there is merit to the approach of reaching consensus on the specification and rationale before writing code, the principle of "rough consensus and running code" is still useful when it comes to resolving many discussions of BEL Language and API details.


## Acknowledgements

Thanks to Python and their [Python Enhancement Proposal (PEP)](https://legacy.python.org/dev/PEPs/PEP-0001/) process for providing a lot of the ideas behind the BEP process.
