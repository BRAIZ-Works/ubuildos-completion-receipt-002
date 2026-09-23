# Lessons Learned — Day 1

## What worked
- A narrow problem produced an inspectable working proof quickly.
- Deterministic ranking and visible reasons made the behavior easy to verify.
- Synthetic-only data and zero runtime external dependencies kept the public proof boundary small.
- Private repository verification before public visibility protected the release path.

## What live review found
Static QA was not enough to reveal the main usability issue. The live owner review showed that v1.0.0 is primarily a demonstrator: the user can filter the queue, but cannot add, edit, or remove follow-ups.

## Preserved successor improvement
v1.1.0 should add editable inputs, add/edit/remove operations, a true sample-data reset, an embedded user guide, and live usability regression coverage while preserving deterministic/explainable ranking and the existing privacy/security boundary.

## Campaign lesson
Every later public release must include live review in addition to package/static verification. A release should state plainly what it is, what it is not, what was measured, and what UBuildOS™ contributed.
