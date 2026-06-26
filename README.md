# Ontologica Forge

Ontologica Forge is the shared worldbuilder frontdoor for TTRPG-friendly campaign surfaces, comfy UI concepts, and git-backed campaign review flows.

It is a public-facing place for playable, readable, and reviewable worldbuilding artifacts. It is not the backroom builder lane and not the physical tabletop OS.

## Role

```text
Ontologica Forge
  shared worldbuilder frontdoor
  TTRPG-friendly campaign surface
  comfy UI concept lane
  git campaign frontdoor
  public-safe worldbuilding packets
```

## What Belongs Here

Ontologica Forge may contain:

- campaign-facing vocabulary
- worldbuilder UI concepts
- TTRPG-style flow sketches
- public-safe campaign packet examples
- git-backed campaign review concepts
- noncanonical play/demo surfaces
- public diagrams and release notes
- frontdoor documentation for builders and reviewers

## What Does Not Belong Here

Ontologica Forge must not directly publish:

- private Tessera embodiment kernels
- actuator or hardware authority paths
- private tabletop runtime internals
- private campaign source corpora
- private branch/worktree topology
- private scoring, routing, or merge logic
- real private manifests or receipts
- production release process

## Relationship To The Ecosystem

```text
Ontologica OS
  decides what can be safely said or moved

Ontologica Forge
  shows public-safe worldbuilder and campaign frontdoor surfaces

tessera-builder
  prepares backroom builder packets and implementation candidates

Tessera
  houses the physical tabletop OS and embodied kernels
```

## Intake Gate

Material entering Ontologica Forge from private or backroom work must arrive as a governed review packet:

```text
proof_packet: present
disclosure_critic: present
protected_terms_review: present
source_repository: declared
human_review: required
final_gate: hold / review / deny
```

## Current Status

```text
status: scaffolded_public_frontdoor
authority_ceiling: public_safe_only
production_claim: none
```
