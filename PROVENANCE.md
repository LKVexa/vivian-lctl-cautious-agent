# Provenance

This repository was split from VIVIAN-LCTL-Agent-Team-1.0.0 on 2026-10-04.
The display name is **Cautious**; its original policy identifier is `player_cautious`.
The policy triple and Python execution adapter were copied without modification.
The standalone runner, tests, examples and these repository documents are new.

The source package used the native compiler supplied by
`BOTTLE_ROCKET_5.0.1_VM_110K_RC`. Its source authority is frozen at 4.7.0 within
the 5.0.1 maintenance RC. `brim_ref.py` is preserved unchanged from that scaffold.

| Artifact | SHA-256 |
| --- | --- |
| `player_cautious.lctlc` | `29c5443123bc6dc104b7d9f3e7f66c26d00bde44332e379be43605f42189b2e7` |
| `player_cautious.brir` | `3db4677375194ce77634b50860d85cafee136368e3d1145719bd346ccd0dbd5b` |
| `player_cautious.brimg` | `5d10c93736d69b20a31311c7e736de5ba43cd0a2f1b94a97988ca32c81d3401a` |
| `brim_ref.py` | `333b8bcf2c876efb6aec1373f24aa21da83e26036fecedd5bdcb99f10cae3056` |
| `runtime.py` | `04ba038237bf1416869483dfd0f37d3ae51deb486ff8305e6d32e406235343a3` |

Conceptual references used in the original team implementation:

- Giacomo Bonanno, *Game Theory* (2015), supplied PDF `1512.06808v1.pdf`:
  explicit players/actions/preferences, declared utility assumptions, and
  distinctions among strategic concepts.
- *Understanding Harness Engineering*, supplied PDF: bounded execution,
  provenance, explicit handoffs, and independent acceptance checks.
- `awesome-ai-agents-main.zip`: a catalogue of agent project descriptions,
  used as design context. AutoGen/crewAI and LangGraph informed coordination;
  Agent Argue and Quorum informed evidence/critique separation. Their code was
  not imported and these policies are not copies of those projects.

The six strategies, the coordination reward model, and the staged BRIM handoff
are implementation choices, not guarantees attributed to those references.
The original PDFs, catalogue archive, full scaffold archive, private logs,
backups, machine paths and model-training files are not redistributed here.
