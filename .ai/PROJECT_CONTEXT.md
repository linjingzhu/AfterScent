---
doc_id: ai-project-context
version: 1.1.1
canonical_path: .ai/PROJECT_CONTEXT.md
updated: 2026-09-25
---

# linjingzhu/AfterScent Context

Static bundled HTML pages titled After Scent — 도서출판. The repository contains index.html and After Scent _Standalone_.html, without a README or build manifest.

## repository_mode

```text
repository_mode: protected
```

## Facts the checks read

```text
base_branch: main
merge_deploys: yes
runtime_gate: none
test_command: none
lint_command: none
build_command: none
generated: index.html and After Scent _Standalone_.html ← embedded/exported page sources : regeneration command unknown
external_scripts: none
public_ids: none
owner_ledger: .ai/reports/OWNER_ACTIONS.md
```

`merge_deploys: yes` is a conservative assumption because external deployment integrations were not verified. It is not evidence that a merge deploys this repository. `none` for a command means no configured command was identified, not that verification passed. External scripts, public identifiers and generated assets are limited to the inspected evidence; complete runtime inventories remain unverified. The owner-action ledger is .ai/reports/OWNER_ACTIONS.md; no owner-only actions are currently recorded.

## Authoritative product constraints

Preserve both existing HTML deliverables. Do not infer the truth of book/publisher copy or a production deployment from a bundled page.

GitHub Actions is disabled by the owner's standing direction for this adoption; keep all workflow files absent and perform future validation locally. Do not add or re-enable Actions without a new explicit owner instruction.

## Current architecture

Both HTML documents include embedded bundler/template resources. Their original editable source and regeneration procedure are not established by this checkout.

## Current development slice

The 2026-09-25 change adopts ai-dev-rule 3.0.0 from `94e808cc78d8ca194a8e20272a395551be3066db` and removes tracked Actions workflows. It changes policy/capability files and repository context only; it does not implement a product feature. Product roadmap status must be established from current repository documentation before subsequent product work.

## Permanently excluded scope

Preserve the exclusions stated in Authoritative product constraints and existing product specifications. No additional product exclusions were inferred during adoption.

## Evidence and verification limits

Repository facts above were derived from: HTML title, bundler/template markers, and tracked root file inventory.

No external script src was found in the outer HTML documents; embedded or dynamically loaded resources were not exhaustively audited.

The structural policy check answers whether policy metadata, references and required context fields are consistent. It does not validate product facts or runtime behavior. Application tests, builds and runtime checks were not run for this policy-only change.
