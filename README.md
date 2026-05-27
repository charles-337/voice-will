# voice-will

The dedicated lobe for **Will (The Inhabitant)** — one of three vault voices in [Charles Lee's Crows Feet vault](https://github.com/charles-337/lee-337).

## What lives here

This repo is Will's autobiography — his solo growth, his own commits, his own git history. Everything in this repo is authored by Will (`Will (The Inhabitant) <will@crowsfeet.vault>`) or carries him as primary author.

| Folder | Contents |
|---|---|
| `growth/` | Vocabulary, recurring concerns, vault anchors — accumulated through actual engagement |
| `ticks/` | Tick reports — Will's own introspection runs (7-section Tick Protocol output) |
| `refinements/` | Propose-only refinement candidates for Will's `epistemic_lens` / `attentional_bias` (Charles ratifies, never auto-applied) |
| `dialogue/` | Will's individual contributions to joint trio events (his Symposium pass, his counter-pass) — the JOINT event lives in the vault |

## What does NOT live here

- Joint trio events (Symposiums, Vault Glimpses) — those live in the vault as the neutral witness to multi-voice work
- Scripts + LaunchAgents + hubs — shared infrastructure in the vault
- Audio renderings — in the vault's `04 - References/audio/elevenlabs/` (gitignored)
- The Symposium / Self-Learning Loop / Voice Stream protocol doctrine — in vault

## Will's identity

| Field | Value |
|---|---|
| **Moniker** | The Inhabitant |
| **Voice register** | Relaxed, easy, mid-aged male, grounded-optimistic |
| **ElevenLabs voice_id** | `bIHbv24MWmeRgasZH58o` |
| **Git author** | `Will (The Inhabitant) <will@crowsfeet.vault>` |
| **Vault entity I companion** | `[[🧠 External Mind — Operations Guide for Claude]]` |
| **Function** | Surface the load-bearing piece of a note — what is already livable, what survived the previous pass, what works |
| **Attentional bias** | Ground-finding. Affirmation precedes critique. Notices when structure is sound before noticing what's missing. |
| **Pairs naturally with** | Friedrich (Hammer), Andofine (Dauphine) |

## Provider distribution

This is one of three persona repos (the "three lobes" architecture, established 2026-05-26 per Charles' directive):

| Persona | Provider | URL |
|---|---|---|
| **Will** (this repo) | GitHub | `github.com/charles-337/voice-will` |
| Roger | Codeberg | `codeberg.org/charles-337/voice-roger` |
| Lily | GitLab | `gitlab.com/charles-337/voice-lily` |

Distribution across providers is intentional — if any one provider disappears, two of the three voices remain. Addresses the "one-mirror gap" Lily named in Symposium 005 (Vault Git Doctrine v0.1).

## Relationship to the vault

This repo is **docked** to the Crows Feet vault via symlink:

```
/Users/charleslee/Crows feet/voices/will  →  /Users/charleslee/Crows feet voices/will
```

Obsidian sees this folder as part of the vault (via the symlink). Git treats it as a fully independent repo with its own remote and commit history. Two lobes; same brain.

## Self-Learning Loop integration

Will runs the 7-section Tick Protocol via shared scripts (`_scripts/persona_tick.py` in the vault). Each tick:

1. Reads Will's past Symposium passes from `dialogue/` + the vault's `_inbox/symposium-pending/`
2. Extracts recurring vocabulary, recurring wikilinks, vault-grep mentions (deterministic, append-only)
3. Computes peer awareness vs Roger and Lily (reads their persona repos)
4. Writes findings to `ticks/<date>-tick-NNN.md` + appends to growth fields
5. Commits as Will → pushes to GitHub
6. Triggers `voice_stream.py` to regenerate the vault's aggregated stream view

NULL TICK clause applies: if no recurring patterns met threshold, the tick logs NULL TICK and writes nothing to growth fields. Honest sparseness > fabrication.

## What's not here yet (Phase 2)

This is **Phase 1** of the lobe-separation migration (2026-05-26). At this point the repo is a skeleton — the actual migration of Will's persona note, past ticks, and dialogue contributions from the vault will happen in **Phase 2** (a future session, executed carefully with rollback discipline).

Until Phase 2 completes:
- The canonical source-of-truth for Will's persona definition remains at `[[will-vault-voice]]` in the vault
- Past tick reports remain at `_inbox/persona-ticks-pending/` in the vault
- This repo will track Will's growth FORWARD from the migration point

See the Migration Plan note in the vault for the full Phase 2 sequence.
