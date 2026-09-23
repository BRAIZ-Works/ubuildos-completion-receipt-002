# Follow-Up Prioritizer™ v1.0.0

Day-1 proof release for the UBuildOS™ 30-Day Public Campaign.

## Product identity
- Product SemVer: `1.0.0`
- Frozen product package: `FOLLOW_UP_PRIORITIZER_v1.0.0_PRE_IQA.zip`
- Frozen product SHA-256: `9077a29629218d6345303d2a79f7cc4f45a12e6cabce8bef0a0b91616c3712bf`

The product bytes remain frozen and unchanged.

## Current public presentation package
- Public-package SemVer: `1.0.1`
- Package: `FOLLOW_UP_PRIORITIZER_PUBLIC_PACKAGE_v1.0.1.zip`
- SHA-256: `f3ee4fad9565987d383017ef69cdad8f64437a82e99741106b442941b589de39`
- Change scope: presentation-only repair to carousel Slide 2 headline overflow.
- Slides 1, 3, 4, and 5 are preserved.
- Product/application functionality is unchanged.

## What this is
A small local browser app that turns five synthetic follow-ups into a deterministic ordered queue and shows the reasons behind every rank.

## What this is not
This is not a CRM, autonomous sales agent, production scoring system, or claim that the bundled weights are universally optimal. v1.0.0 does not add/edit/remove records in the UI, persist data, connect to external systems, or use real customer data.

## Measured evidence
- 5 synthetic input records
- 5 ranked outputs
- 2 overdue promised follow-ups
- visible ranking reasons on 5/5 records
- deterministic repeatability: PASS
- runtime external dependencies: 0
- Fresh Independent QA: PASS

No revenue-lift, conversion-lift, production-scale, or universal-optimality claim is made.

## UBuildOS™ value
The app is intentionally narrow. The broader proof is the release system behind it: define a bounded problem, build a working proof, expose how it works, test it, independently review it, freeze exact bytes, publish the evidence, live-review it, repair the presentation layer safely when needed, and make the result inspectable.

## Live review
A live owner review was performed. The product operated as the intended narrow proof, and the review exposed a real UX limitation: the interface is mostly demonstrative rather than editable. That finding is preserved for v1.1.0 instead of mutating frozen v1.0.0.

Preserved v1.1.0 improvement set:
- add follow-up
- edit/remove follow-ups
- true reset to original sample data
- embedded user guide
- live usability regression test

## Run it
Open `app/index.html` from the downloaded frozen product ZIP in a modern browser.

No network connection, account, API, database, or installation is required.

## Release evidence
See:
- `verification.md`
- `independent_review_record.md`
- `lessons_learned.md`
- `live_review_record.md`
- `production_metrics.md`
- `what_this_is.md`
- `public_claims.md`
- `methodology.md`
- `security_privacy.md`
- `recovery.md`
