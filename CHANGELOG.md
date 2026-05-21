# Changelog

All notable changes to Gemini Security Skills are documented here.

## 2.0.0 - 2026-05-21

Added 12 new cyber security automation skills focused on driving security
workflows through Gemini with guardrails and evidence-backed output:

- `gemini-tool-orchestrator`: Natural-language pipelines over nmap, nuclei,
  ffuf, semgrep, trivy, and other CLI tools with stage-gated execution.
- `ai-redteam`: LLM and agent red-teaming for prompt injection, jailbreak,
  tool abuse, agent hijack, and RAG poisoning with defensive deliverables.
- `threat-intel-fusion`: Multi-source IOC fusion, STIX normalization,
  KEV/EPSS-aware prioritization, and actor profiling.
- `cloud-security-automation`: AWS/Azure/GCP CSPM and IaC scanning with
  least-privilege diffs and drift-and-fix workflows.
- `detection-engineering`: Sigma/YARA/KQL/SPL rule authoring with ATT&CK
  coverage and tested-by-default discipline.
- `kubernetes-security`: Cluster hardening, admission control, runtime
  defense, and signed-image supply chain.
- `purple-team-automation`: Adversary emulation tied to detection validation
  and coverage scoring.
- `osint-recon-automation`: Passive recon and exposure monitoring with
  asset graphs and snapshot diffs.
- `api-security-automation`: REST/GraphQL/gRPC testing across OWASP API
  Top 10 with HAR-backed reproductions.
- `forensics-triage`: DFIR across disk, memory, network, cloud, and
  identity with defensible timelines and chain of custody.
- `bug-bounty-workflow`: Scope-aware bounty engagement with deduplication
  and high-signal reporting.
- `smart-contract-audit`: Solidity/Vyper/Move audit with invariants,
  economic review, and MEV/oracle/bridge coverage.

Changed:

- Updated `gemini-extension.json` to version `2.0.0` with an expanded
  description covering the full skill catalog (24 skills total).
- Updated `README.md` and `docs/skill-catalog.md` to group skills by domain.

## 1.0.0 - 2026-05-09

Initial repository release.

Added:

- Created 12 Agent Skills for Gemini CLI:
  `go-programming`, `python-programming`, `assembly-programming`,
  `offensive-security`, `exploit-development`,
  `malware-reverse-engineering`, `devsecops`, `soc-operations`,
  `cybersecurity-partner`, `prompt-enhancement`, `multilingual`, and
  `claude-mythos-emulation`.
- Added `gemini-extension.json` for Gemini CLI extension installation.
- Added top-level `skills/` directory for extension-bundled Agent Skills.
- Added root-level skill folders for direct copy compatibility.
- Added repository banner at `assets/banner.svg`.
- Added install, usage, catalog, workflow, safety, troubleshooting, and
  maintenance documentation.

Security posture:

- Cyber security skills are scoped to authorized, defensive, educational, and
  lab-based use.
- Offensive and exploit-development skills include explicit guardrails against
  unauthorized access, stealth, persistence, credential theft, destructive
  actions, malware improvement, and weaponization.

Validation:

- Validated all root-level skills.
- Validated all extension-bundled skills under `skills/`.
- Validated `gemini-extension.json` as JSON.
- Checked local Markdown links.

