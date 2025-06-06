| PFP               | Title                           | Description          | Author                        | Discussion | Status | Type                                     | Date                  |
|-------------------|---------------------------------|----------------------|-------------------------------|------------|--------|------------------------------------------|-----------------------|
| 1 | PFP Purpose and Guidelines  | Describes PFP processes for the Polygon Community Treasury | Kaitlin Beegle | [Forum](TODO)  | Continuous | Governance | 2025-06-06
---

# PFP-1: Polygon Funding Proposal (PFP) Framework

## Abstract

The Community Treasury is an independent, in-protocol fund that is transparently and openly governed.

Funded via a dedicated POL token emission stream, the Treasury exists to provide direct investment in services, technologies, and initiatives that are critical for the sustainable development of the Polygon ecosystem.

Polygon Funding Proposals (PFPs) are public documents that describe the policies, strategies, and mechanisms that govern the Treasury.

## Rationale

At maturity, the Polygon ecosystem will be self-sustaining and decentralized. The Treasury exists to provide economic support during early-stage network growth to foundational use cases that support this vision.

The Treasury is funded directly by the protocol, as outlined in the [Polygon 2.0 whitepaper](https://polygon.technology/papers/pol-whitepaper) and implemented in [PIP-17](https://github.com/maticnetwork/Polygon-Improvement-Proposals/blob/main/PIPs/PIP-17.md). This ensures that the Treasury is a wholly independent fund with all allocations sent on-chain.

PFPs provide documentation as to the present state of Treasury governance and operations as well as a versioned history of changes.

## Specification

A PFP is a formal proposal proposing changes to the Community Treasury’s governance processes \- anyone can submit a PFP, which is the first step towards building consensus.

### PFP Types

Two `PFP Types` are distinguished:

* `Governance`  
  * Proposals introducing or improving new or existing processes or policies which govern the Community Treasury  
* `Funding`  
  * Proposals introducing or amending a strategic request for funds

Please note that `PFP Types` are intended as broad classifications of the distinct kinds of Proposals which may exist.

The creation, acceptance, and implementation of either type of PFP may be subject to additional governance requirements in this or other PFPs.

### PFP Status & Workflow

PFPs are dynamic documents that exist in perpetuity.  The following statuses approximately describe their position in the PFP lifecycle.

#### `Proposed` Status

A `Proposed` PFP is one which has been put forth for community consideration.  It is actively seeking consensus and is therefore likely to be changed and modified, pending community feedback.

To propose a PFP, a PR should be opened against the [PFP repo](https://github.com/0xPolygon/Polygon-Funding-Proposals).  The PFP Author must also ensure that the PFP is posted in the [Community Forum](https://forum.polygon.technology/c/community-treasury/94) for feedback and suggestions. While the Proposal remains in the `Proposed` state, its Author is responsible for properly socializing the proposal and building consensus.  This may include: gathering relevant feedback from key stakeholders; incorporating changes; ensuring consistency between the PFP Forum post and repo, and; responding to community questions, ideas, and suggestions.

Once PFP Editors (see: [PFP Editors](https://github.com/0xPolygon/Polygon-Funding-Proposals/edit/main/PFPs/PFP-01.md#pfp-editors)) determine that the PFP draft is complete as-is, and that it represents a relevant and good-faith proposal that is possible to implement, they will merge it into the repo.  At this point in time, the document may still be considered `Proposed` and changes are allowed. By merging, PFP Editors are indicating that the proposal itself is thorough enough to be catalogued in the repo itself; they are not indicating that consensus has been reached.

At this time, PFPs can remain in the `Proposed` state for an indefinite period of time. At a minimum, they should remain `Proposed` for ***at least two (2) weeks*** to ensure that community stakeholders have had enough time to reasonably review, raise issue, or provide feedback.

#### `Accepted` & `Rejected` Statuses

PFPs should remain `Proposed` until they are deemed final and complete.  Once this has occured- and the proposal has been publicly available for at least 2 weeks- it may be ready for a final consensus decision.

Consensus is the process of determining momentum for a final decision to be reached.

`Accepted` PFPs are those which have achieved consensus to become policy, or else have been deemed final and correct.

`Rejected` PFPs are those which have received significant pushback or opposition, and/or are otherwise unable to become network policy at this point in time.

* Occasionally, the conditions under which a PFP was rejected change, and it may be appropriate to re-consider a proposal that was previously rejected.  
  * In these instances, which are rare, the original PFP must maintain its `Rejected` status and a new PFP must be proposed.  
  * PFP Editors are able to determine whether or not conditions are appropriate for a previously failed PFP to be re-considered.

A PFP is declared `Accepted` or `Rejected` via a process of *soft consensus, which requires that all relevant community feedback be generally assessed.  In this process, there is always a bias towards accepting a proposal.  Proposals are only rejected in instances where substantive, significant, and unresolved opposition to the proposal is raised.* 

The decision to declare a PFP `Accepted` or `Rejected` falls to PFP Editors via a process of *soft consensus*, which requires that they review all relevant feedback and render a decision.

At this time, there is no 'hard consensus' (e.g., on-chain or off-chain voting) method for determining if PFPs are `Accepted` or `Rejected`.  Given the nature of PFPs, there is a bias towards an `Accepted` status, barring any significant and/or critical feedback against the given proposal.

#### `Active` Status

`Active` refers to proposals which represent current, in-progress network policy.  These are the PFPs which actively define current network priorities, policies, governance obligations, and/or funding strategies.

Proposals which are `Accepted` but not `Active` should be understood as future policies or strategies that have not yet been implemented or executed upon.

#### Additional PFP Status Types

`Archived` proposals are those which were formally `Active` but no longer are. This may be because the scope of funding described in the proposal was fully executed, or because the given strategy or governance process has been replaced with a different, distinct proposal.

`Deprecated` proposals are those that no longer represent current network policy or strategy, but were not necessarily replaced or updated.  They may represent out-of-date processes, tools, or strategies that are no longer relevant.

`Continuous` proposals are those proposals that fundamentally define a key aspect of Treasury policy or governance and are therefore both changeable AND final.  Whenever a proposal is pushed to a `Continuous` PFP, it follows the same guidelines and requirements as all newly-proposed PFPs. 

### PFP Roles & Resources

#### The Polygon Community Forum

The [Polygon Community Forum](https://forum.polygon.technology/) is the primary place for discussion amongst the Polygon Community.  Ideas, feedback, discussion, or additional documentation about the Treasury- including projects it has or may fund, its governance, and/or its operations- are also located here, tagged under the `Community Treasury` category.

Though all PFPs must have a corresponding post in the Forum, not all Forum posts must become PFPs.  Anyone is able to post questions, comments, or ideas in the Forum.

#### PFP Authors

PFP Authors serve as the primary champion(s) of a given proposal. They are responsible for ensuring the completeness and correctness of a proposal.  If accepted, they are also responsible for leading the implementation and execution of the PFP.

#### PFP Editors

PFP editors are responsible for ensuring that PFP submissions are properly structured and advanced through designated statuses. They are responsible for ensuring that submissions are logically and reasonably structured and will check the PFP for correct language.  All PFPs must be written in professional English.

If the PFP is not ready or acceptable in its current form, Editors will work with Authors to provide updates and review changes.  Once the PFP meets the minimum requirements, PFP Editors will merge the PFP into the repo and give it a number.

PFP Editors are additionally responsible with maintaining the PFP repo, updating documentation, linking out relevant resources, and updating PFP statuses.

PFP Editors are key operators in the Polygon ecosystem who often have extensive knowledge about a relevant area of Polygon operations. As such, they may offer feedback on the content or quality of the PFP, but they may NOT unilaterally block the progression of a PFP with which they may personally disagree and/or oppose.

##### Designated Editors

The current PFP Editors are comprised of:

* [Kaitlin Beegle](https://github.com/kaitlin-beegle)  
* [Harry Rook](https://github.com/hrook1)  
* [Mattie Fairchild](https://github.com/ScavieFae)

Currently, PFP Editors are solely responsible for managing their membership via Github repo permissions.

### PFP Header & Template

At a minimum, all PFPs ***must*** contain the following:

**Title:** The Title of the PFP should be concise and accurately explain the purpose of the PFP.

**Status:** 1 of 7 statuses for the PFP, described above.

**Abstract:** A short (\~200 word) summary of the proposal.

**Specification:** The specification should provide the reader an in-depth understanding of the proposal.

Additional guidance is available in the [README](https://github.com/0xPolygon/Polygon-Funding-Proposals/blob/main/README.md).

## Document History 

As this PFP is continuous, a true history of changes is available in the repo.  Significant versions include: 
  * Version 1, published 2024-04-11

## Copyright

All copyrights and related rights in this work are waived under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/legalcode).
