# Elemental Cipher — Canonical Ledger

Repository: `DavidWise01/archon`  
Policy: append-only artifacts, source-preserving encodings, factual and symbolic namespaces kept separate.

## Boundary 034 — Argon closure (2026-11-08)

- [Interactive hydrogen-to-argon cipher laboratory](argon-cipher-020.html)
- Corrected canonical token: `..||..|....||` (one terminal bar removed at user's direction).
- Count of dots: **8**; count of bars: **5**.
- Declared scoring rule: dot `.` = 1, bar `|` = 2.
- Calculated cipher weight: **8 × 1 + 5 × 2 = 18**.
- User-assigned symbolic correspondence: **cipher 18 → argon closure**.
- Independent chemical fact: **argon's atomic number is 18** (18 protons). In this corrected assignment the cipher weight and chemical atomic number coincide; the rule definitions remain distinct.
- The token is preserved byte-for-byte as an identity-bearing artifact; the score alone cannot reconstruct its original order or run lengths.
- First 18 chemical elements covered, hydrogen (Z=1) to argon (Z=18), including shell populations and a compact semantic action per element.
- Shell populations are pedagogical Bohr-like summaries, not true electron orbital pictures or a claim of physical transformation between elements.
- Periodic closure sequence: helium (2), neon (10), argon (18).

## Natural invariant

`identity = (raw token, parsing rule, computed score, assigned semantic referent, provenance)`

`C(token) = count('.') + 2 × count('|')`

Distinct tokens may have identical scores. No score equivalence permits automatic identity-merging.

## Next natural test

Find minimal distinct cipher strings with value 18; classify collisions between score and structure. Then continue to potassium (Z=19) and calcium (Z=20) under their own atomic numbers.

## Correction history — 2026-11-08

The initial transcription `..||..|....|||` has 8 dots and 6 bars, giving 20. The user explicitly corrected it by deleting the last `|`. The authoritative token is now `..||..|....||` with 8 dots and 5 bars, giving 18. The prior token is retained here solely as the historical correction record, not the active cipher. The existing HTML laboratory was rebuilt in place by explicit user request; Git history retains the previous revision. Its path retains `020` for link continuity, but its visible title, default token and parser now say 018.
