# Masorah Repository Topology

## Source
This repository is treated as the canonical parsed MAM/Tanakh source currently under inspection.

## Proposed topology
Do not duplicate the Tanakh blindly into thousands of repositories.

1. One canonical corpus repository remains the source of truth.
2. Every book is addressable.
3. Every chapter receives a deterministic path.
4. Every verse receives a deterministic path/record.
5. A verse becomes a separate deep-dive repository only when evidence, grammar, Masorah, manuscript comparison, or research complexity requires independent work.
6. All derived records retain provenance back to the canonical corpus and source event.

## Identity
book -> chapter -> verse -> token/feature -> evidence -> derivation -> verification

## Safety rule
No extracted interpretation is treated as verified merely because an agent generated it. Source, evidence, derivation, conflicts, and verification status remain separate.

## Current status
ARCHITECTURE_DEFINED
DATA_NOT_MODIFIED
REPOSITORY_SPLIT_NOT_EXECUTED

## Next automation target
Generate a machine-readable index of all 24 books, chapters, verses, and available parsed features from the existing corpus. Then identify candidate deep-dive units from evidence density and research requirements.
