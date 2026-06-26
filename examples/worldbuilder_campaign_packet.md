# Worldbuilder Git Campaign Packet Example

Status: `synthetic_public_example`

Authority ceiling: `public_safe_only`

This packet is a noncanonical example of how Ontologica Forge can present a TTRPG-friendly worldbuilder and git campaign frontdoor without importing private campaign corpora, private runtime internals, hardware authority, or production release machinery.

## Purpose

Show the public shape of a worldbuilder / git campaign packet.

## Source Material

```text
source_repository: synthetic_demo
campaign_material: synthetic_demo_only
private_material_included: false
```

## Public Summary

A worldbuilder packet turns campaign-facing material into a reviewable public shape:

```text
campaign idea
  -> public scene beat
  -> public table-facing prompt
  -> public git review note
  -> protected terms check
  -> hold for human review
```

## Public Fields

| Field | Meaning |
| --- | --- |
| `packet_id` | Public synthetic packet identifier. |
| `campaign_surface` | Public worldbuilder surface type. |
| `table_use` | How a player/operator might understand the packet. |
| `git_review_note` | Public review posture for repo-backed campaign flow. |
| `recommended_gate` | Hold, review, or deny. |

## Synthetic Packet

```yaml
packet_id: forge_worldbuilder_campaign_packet_001
status: synthetic_public_example
authority_ceiling: public_safe_only
campaign_surface: ttrpg_comfy_ui_scene_seed
table_use: public-facing campaign prompt sketch
git_review_note: candidate scene packet for review, not canonical campaign truth
protected_terms_review:
  private_campaign_corpus: absent
  private_runtime_internals: absent
  private_hardware_paths: absent
  private_branch_topology: absent
  real_private_receipts: absent
disclosure_critic: required
recommended_gate: hold_for_review
```

## What This Does Not Do

This packet does not grant canon authority, campaign runtime authority, hardware authority, production release authority, or git promotion authority.

It does not disclose private campaign corpora, private runtime internals, hardware paths, private branch/worktree topology, private scoring/routing/merge logic, or real private receipts.

## Ontologica Forge Use

Ontologica Forge may use packets like this as public-facing examples of worldbuilder and git campaign review posture after Ontologica OS proofing.
