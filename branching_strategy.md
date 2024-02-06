# Teco Branching Strategy

## Git Flow

**Main**: Only used for production code

**Hotfix**: Created from Main, enables quick fixes without cherry picking

**Develop**: Stores all features upon completion

**Feature**: Each task is a feature branch, which is created and merged ideally upon feature completion.

**Release**: Used to collect features from develop, to distribute to testing/staging and main

<img src="./Branhces.png" width="600px">

### Advantages:

- **Single responsibility principle**: Every branch only has one purpose

- **Master is always deployable**

- **Developers have less to wory about**: There is no way for a half-finished feature to make it into a release on accident (git trunk..)

- **Allows feedback and test in intermediary branch before master**

### Disadvantages:
- Lots of branches to manage
- Could get tedious to manage if releases happen very often.


##