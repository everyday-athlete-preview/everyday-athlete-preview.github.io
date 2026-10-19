# Release 001 — exact candidate authorized; workflow not started

2026-10-19. Owner explicitly approved only source 89d087e5746eb36b5763b8356e2204de864e7622 and manifest digest b91602ae9822c2b5054ba2673c535a2b65c62bdc5d032ce6a56a3ad3c3585a6c for https://everyday-athlete-preview.github.io/. Exactly one allowlist entry is recorded; see approvals/V2_PREVIEW_001.md. No future releases allowed. This authorization change does not itself deploy: manual workflow dispatch and successful tests/digest check are required, then ct801988 personally approves the github-pages deployment gate. Never auto-approve. Stop/report all failed checks or mismatches. Source PR #4/#5 and Winter Strong untouched. No unreviewed media or costs.

---

# Everyday Athlete publisher — prepared, deployment NOT approved

2026-10-19. ChatGPT GitHub organization installation is now visible; creation of ea/prepare-publisher succeeded. Existing publishing main e6d2c5caeca11251e392eb67bceebe8a42b806e9 contains only README.md and is preserved.

This branch adds manual-only release workflow, EMPTY approved-releases.json, candidate-release.json with deploymentApproved:false, and setup/rollback instructions. No application assets or exercise media are uploaded. Source remains ct801988/everyday-athlete. No source PR merge or publication authorized.

Expected URL https://everyday-athlete-preview.github.io/. No custom DNS, paid services or Cloudflare. The prior automatic README Pages run completed before this setup; it is not an app release or evidence of this workflow. Pages settings have not been changed. Before any publishing-repo main merge, owner/admin must confirm Pages source becomes GitHub Actions rather than automatic main/branch publishing; otherwise a main merge could republish repository documents.

Next owner/admin gate: review this draft PR without merging. Configure github-pages environment reviewer ct801988, allowed branch main, disable admin bypass; allow sole-owner self-review. Environment/admin settings are not enforced solely by YAML and have NOT been verified/configured. User must separately authorize this Pages settings change and infrastructure merge before any release. Keep release allowlist empty until specific final deployment approval.

The workflow has no push/PR/schedule trigger. Manual dispatch must match an approved full source SHA and final approval evidence in the allowlist. It builds/tests, verifies the exact artifact manifest digest, uploads static artifact, then waits for github-pages environment approval. No automatic unreviewed development deployment. Actions checks depend on actual environment/settings; workflow has not run in GitHub.

Prepared candidate source 89d087e5746eb36b5763b8356e2204de864e7622; artifact hash list b91602ae9822c2b5054ba2673c535a2b65c62bdc5d032ce6a56a3ad3c3585a6c. Existing full application validation 181 PASS / 0 FAIL / 3 inherited skips remains unchanged; application tests not rerun for copying identical workflow/config. Workflow syntax/trigger/pinned actions and empty ledger were locally validated. Physical iPhone and hosted SW/HTTPS remain pending.

Rollback: preserve compatible source SHA + artifact/digest for every approved release; export current EA first, redeploy only data-compatible release through same approval gates, close all controlled app windows for worker replacement. Never clear browser data or downgrade schema silently. Current root worker does not force activation. Existing V2, PR #4 and source PR #5 preserved. Winter Strong is untouched. STOP for review/settings and final deployment authorization; no merge or dispatch now.
