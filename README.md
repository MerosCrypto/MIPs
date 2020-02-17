# Meros Improvement Proposals

Meros Improvement Proposals (MIPs) are various standards meant to improve the Meros platform.

### Categories

MIPs are separated into three different categories:

- Hard Fork
- Network
- Application

Hard Fork proposals introduce new consensus rules which will break compatibility with nodes which have yet to update.

Network proposals either add, remove, or modify network messages. They do not require nodes to update as Meros has a policy of supporting every protocol version since the last hard fork.

Application proposals do not change the consensus rules or network messages. Instead, they provide specifications to ensure compatibility between apps.

### Status

MIPs have the following statuses:

- Draft
- Finalized
- Rejected
- Accepted
- Abandoned
- Live
- Replaced

### Format

Proposals are formatted into several sections which thoroughly present the idea, the reasoning behind it, and its implementation. The sections are defined as follows:

- Metadata
- Abstract
- Motivation
- Specification
- Compatibility
- Security
- Test Vectors
- Implementation
- Copyright

The metadata section should contain the following:

````
```
MIP: Assigned MIP Number
Title: Proposal Title
Author(s): List of Authors
Category: Proposal Category
Created: Month Day, Year
Status: Proposal Status
```
````

The implementation section is not required.

### Copyright

Every submitted proposal must include the following disclaimer.

> Copyright and related rights waived via CC0.

This is in order to ensure that every proposal is to advance technology, not to solely benefit Meros or the original author.
