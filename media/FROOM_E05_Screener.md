# FROOM E05 Screencast: Identity Changed First

[Watch the screencast](./FROOM_E05_Identity_Changed_First.mp4)

## What it shows

The screencast presents one illustrative workspace and three different
curated architectural views: Work First, Knowledge First, and People First.
Each view is framed around the same illustrative requirement: a member reads a
document.

It then shows three live runtime views returning `ALLOW`. The demonstrator
removes permission P1 from its mutable example identity; the three runtime
decisions then change to `DENY`. The processes are not restarted for this
change.

## How this relates to E05

E05 asks whether one fixed identity contract, room contract, and requirement
contract admit at least two valid, structurally non-equivalent configurations
that preserve the declared identity invariants and satisfy the requirements.

The screencast is **not an evaluation of that question**:

- The three architecture views are curated illustrations, not configurations
  independently constructed and evaluated under the E05 contracts.
- The runtime segment is a demonstrator of a shared example identity changing
  and runtime decisions responding; it is not the E05 evaluator or an
  independent implementation review.
- The `ALLOW`/`DENY` transition is limited to this demonstration and does not
  establish a general property of FROOM or of deployed systems.

E05 remains **NOT EVALUATED** and **Freeze Candidate = NO**. The video should
be read as an illustration of the research question, not as evidence that the
question has been answered.
