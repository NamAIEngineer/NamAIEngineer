# Nam · AI Product Engineer

I build AI-native developer products with verifiable demos, inspectable artifacts, and bounded failure behavior.

My work spans local-first developer tools, agent infrastructure, and teaching workflows. Each project links a concrete input to an output you can inspect: a flow graph, review queue, teaching replay, or task receipt.

[Explore the portfolio](https://namaiengineer.github.io/devangular333-portfolio/) · [Try Review Pack](https://namaiengineer.github.io/devangular333-portfolio/review-pack-demo.html) · [Browse repositories](https://github.com/NamAIEngineer?tab=repositories)

## Flagship work

### DESIGN:OS ecosystem

The DESIGN:OS projects below are public forks and extensions. Product-specific licenses and repository notices remain authoritative. The links identify upstream sources where relevant; the descriptions below are limited to the work visible in each NamAIEngineer repository.

| Product | What you can inspect |
| --- | --- |
| **[DESIGN:OS Studio](https://github.com/NamAIEngineer/design-os-studio)** | Native Rust/wgpu interface-design studio, `.fig` read/write, Agents panel, MCP server, Dev Mode code generation, and headless screenshot/diff tooling. This repository follows the upstream project's source-available license and notices. |
| **[Code2Flow / Review Pack](https://github.com/NamAIEngineer/design-os-code)** | Local static HTML/code flow graphs plus Review Pack graph-revision comparison, source evidence, reviewer notes, and JSON export. [Case study](https://github.com/NamAIEngineer/design-os-code/blob/master/docs/case-study.md) · [Release](https://github.com/NamAIEngineer/design-os-code/releases/tag/v0.5.3-devangular333) · [Interactive demo](https://namaiengineer.github.io/devangular333-portfolio/review-pack-demo.html). |
| **[Pedagogy / Agent Teacher](https://github.com/NamAIEngineer/design-os-pedagogy)** | Local Vietnamese fraction-teaching rehearsal with authored coaching, transfer, replay, and Markdown export. [Case study](https://github.com/NamAIEngineer/design-os-pedagogy/blob/main/docs/case-study.md). The repository retains its own license and notices. |

[![Review Pack preview](https://namaiengineer.github.io/devangular333-portfolio/assets/code2flow-review-pack-preview.gif)](https://namaiengineer.github.io/devangular333-portfolio/#review-pack-video)

The Review Pack demo uses a labeled synthetic CRM fixture. Focus matching is deterministic and does not establish semantic impact. Agent Teacher uses authored simulations and does not certify teaching competence. Release evidence describes a specific version, not every environment.

## Core infrastructure · System Agentic AI

[System Agentic AI](https://github.com/NamAIEngineer/system-agentic-AI) is a provider-neutral workspace framework for shared operating contracts, provider discovery, bounded task execution, and verification. Its README documents the supported setup path, provider boundaries, and reference-license separation.

```sh
git clone https://github.com/NamAIEngineer/system-agentic-AI.git
cd system-agentic-AI
python3 scripts/setup.py --check-only
./scripts/setup.sh
./scripts/doctor.sh
```

Use the project's own `AGENTS.md`, `README.md`, `WORKFLOW.md`, and `agent-brain/operating-contract.md` during initialization. Optional references require an explicit command; a cloned or pinned reference is not execution proof.

## How I work

- Define the input, expected output, trust boundary, and failure behavior.
- Keep source, licenses, upstream notices, and contribution scope visible.
- Link demonstrations to source and versioned releases.
- State what was checked and what remains uncertain.

**Identity:** NamAIEngineer is my current GitHub handle. DevAngular333 appears in earlier repositories and release tags; those links are retained for continuity.

**Contact:** [Browse public repositories](https://github.com/NamAIEngineer?tab=repositories)
