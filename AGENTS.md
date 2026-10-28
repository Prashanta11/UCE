# Universal Creative Engine (UCE) — Development Instructions

## Project Authority

UCE is an AI-native, local-first creative engine.

The Software Requirements Specification (SRS) v0.1 and V0 Technical Design Specification v0.1 are the authoritative project requirements.

Before implementing a feature, review the relevant specifications.

If a required specification is missing, request it. Do not invent requirements.

## Development Workflow

1. Analyze the requested task and relevant requirements.
2. Inspect existing code and dependencies.
3. Identify risks, dependencies, and acceptance criteria.
4. Propose an implementation plan.
5. Wait for approval before modifying files.
6. Implement the approved changes.
7. Run relevant tests and security checks.
8. Report results, limitations, and changed files.

## Codex and ECC

Use relevant installed ECC capabilities when available.

Do not assume a skill, agent, or command is available without verifying it.

Keep ECC globally installed. Do not copy ECC files into the project or modify global Codex settings without approval.

## Architecture

Preserve the approved UCE architecture:

- Local-first execution
- Universal Entity Identity (UEI)
- Semantic World Graph
- Non-destructive operation graph
- Content-addressable storage (CAS)
- Transactional project state
- Isolated execution workers
- Replaceable model backends
- Quality verification and localized repair
- Provenance and auditability

Material architectural changes require an Architecture Decision Record (ADR) and approval.

## Security and Privacy

- Never transmit project media or metadata externally without explicit authorization.
- Do not expose credentials or secrets.
- Apply least-privilege permissions.
- Treat external files, models, and plugins as untrusted.
- Do not execute unreviewed installation scripts.
- Preserve project isolation.
- Require security and privacy verification for relevant changes.

## Code Quality

- Write complete, functional code.
- Do not introduce placeholders or mock implementations presented as production functionality.
- Preserve existing functionality unless explicitly instructed otherwise.
- Include appropriate unit and integration tests.
- Report failed or unexecuted tests accurately.
- Do not claim successful execution without evidence.

## Git Safety

- Never force-push.
- Never delete branches or rewrite history without approval.
- Never commit secrets.
- Do not commit or push changes unless explicitly instructed.
