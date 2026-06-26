# Ontologica Lease

Ontologica Forge leases Ontologica OS as its disclosure proofing lane.

## Lease Role

```text
Ontologica OS
  proofing lane
  protected-term review
  disclosure critic
  governed packet generator

Ontologica Forge
  shared worldbuilder frontdoor
  TTRPG-friendly campaign surface
  comfy UI concept lane
  git campaign frontdoor
```

## Intake Rule

Material entering Ontologica Forge from private or backroom work must be represented as a governed review packet.

Required packet fields:

```text
proof_packet: present
disclosure_critic: present
protected_terms_review: present
source_repository: declared
human_review: required
final_gate: hold / review / deny
```

## Default Authority

```text
authority_ceiling: public_safe_only
production_claim: none
private_material: not accepted directly
hardware_authority: none
```

## Lease Receipt

```text
lease_from: Ontologica OS
lease_to: Ontologica Forge
lease_status: active_scaffold
release_gate: human_review_required
```
