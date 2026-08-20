# DIKWP-MNEMORPH / 忆构生命核

**Storage preserves records. Memory reconstructs a future-bearing continuity.**  
**存储保存记录；记忆在当前状态中重构过去，并改变未来。**

DIKWP-MNEMORPH is a provider-neutral reconstructive-memory sidecar for current LLMs and AI agents.

It separates:

```text
Immutable event ledger (storage)
!=
Mutable engram field (derived memory substrate)
!=
Reconstructed memory episode (present-state recall)
!=
Future simulation (prospection)
```

## Memory metabolism

```text
experience
-> immutable event record
-> consolidation into engrams
-> state-dependent reconstructive recall
-> action or future simulation
-> observed outcome
-> reconsolidation
-> forgetting/inhibition
-> revised continuity and policy
-> next experience
```

## The disruptive upgrade

Current LLM memory systems commonly optimize storage, retrieval, summarization, update and discard. MNEMORPH adds:

- bounded non-fidelity reconstruction,
- source-bound factual atoms,
- explicit omissions and transformations,
- contradiction preservation,
- post-retrieval reconsolidation,
- forgetting without deleting evidence,
- future simulation that cannot masquerade as memory,
- dynamic self/continuity revision without fixed personhood,
- policy change caused by remembered outcomes,
- confabulation and fixation firewalls.

## Quick start

```bash
python mnemorph.py new data/samples/locus_seed.json --out outputs/locus.json
python mnemorph.py event outputs/locus.json data/samples/event_input.json --out outputs/locus_v2.json
python mnemorph.py consolidate outputs/locus_v2.json --out outputs/locus_consolidated.json
python mnemorph.py recall outputs/locus_consolidated.json data/samples/recall_context.json --locus-out outputs/locus_recalled.json --memory-out outputs/memory.json
python mnemorph.py audit outputs/functional_memory_life_candidate.json
python mnemorph.py prospect outputs/functional_memory_life_candidate.json data/samples/prospect_context.json --locus-out outputs/locus_future.json --simulation-out outputs/simulation.json
```

## Functional boundary

A storage system replays records. A reconstructive memory system rebuilds a present episode from sources, current state, purpose, relations, omissions and uncertainty. A functional memory-life candidate additionally lets recall revise policy and continuity, closes the outcome/reconsolidation loop, forgets selectively, and simulates future possibilities.

This runtime does **not** claim that those conditions prove true life, sentience or phenomenal consciousness.

## Hard boundaries

- Immutable source records are never overwritten by recalled memory.
- Every factual atom in a memory must link to an event source.
- Unsupported claims are blocked or marked inference/simulation.
- Future simulation is never labeled memory.
- Forgetting changes accessibility and salience, not the evidence ledger.
- No fixed person type or life score.
- No automatic external action.
- Do not create another repository automatically; integrate into an existing flagship first.
