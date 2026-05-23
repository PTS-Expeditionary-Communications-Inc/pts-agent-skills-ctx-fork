# PTS Fork — Attribution & Audit Trail

**Upstream:** [`muratcankoylan/agent-skills-for-context-engineering`](https://github.com/muratcankoylan/agent-skills-for-context-engineering)
**Forked:** 2026-05-23
**Pinned commit (audited):** `61f38ffc0ff3ae83adcf2fe011f3b751105add6d`
**Layer 7 audit JSON:** `aiops01:/var/lib/paladin/audit/external-repos/muratcankoylan_agent-skills-for-context-engineering-61f38ffc-20260523.json`

## Purpose
This fork exists for PTS internal use under the audit + supply-chain controls of [plan v3](https://github.com/wright8488/pts-ai-systems/blob/main/docs/project_thin_client_migration_v3.md).

## Branch model
- `main` — tracks upstream; do NOT consume directly without re-audit
- `pts-customizations` — pinned at the audited SHA + PTS-specific changes; this is what we consume

## Re-audit cadence
Upstream sync requires re-running `scripts/audit/external-repo-audit.sh muratcankoylan/agent-skills-for-context-engineering` on aiops01 and updating the pinned SHA + new audit JSON.

## Upstream license
See upstream LICENSE.
