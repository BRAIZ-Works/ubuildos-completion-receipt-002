# Follow-Up Prioritizer™ v1.0.0

Day-1 proof release for the UBuildOS™ 30-Day Public Campaign.

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
- exact frozen package SHA-256: `9077a29629218d6345303d2a79f7cc4f45a12e6cabce8bef0a0b91616c3712bf`

No revenue-lift, conversion-lift, production-scale, or universal-optimality claim is made.

## UBuildOS™ value
The app is intentionally narrow. The broader proof is the release system behind it: define a bounded problem, build a working proof, expose how it works, test it, independently review it, freeze exact bytes, publish the evidence, and make the result inspectable.

## Live review
A live owner review was performed. The product operated as the intended narrow proof, and the review exposed a real UX limitation: the interface is mostly demonstrative rather than editable. That finding is preserved for v1.1.0 instead of mutating frozen v1.0.0.

Preserved v1.1.0 improvement set:
- add follow-up
- edit/remove follow-ups
- true reset to original sample data
- embedded user guide
- live usability regression test

## Run it
Open `app/index.html` from the downloaded ZIP in a modern browser.

No network connection, account, API, database, or installation is required.

## Release evidence
See:
- `verification.md`
- `independent_review_record.md`
- `production_metrics_audit_public.xlsx`
- `lessons_learned.md`
- `live_review_record.md`
- `public_claims.md`
- `methodology.md`
- `security_privacy.md`
- `recovery.md`
