# Elemental Cipher — Canonical Ledger

Repository: `DavidWise01/archon`  
Policy: append-only artifacts, source-preserving encodings, factual and symbolic namespaces kept separate.

## Boundary 034 — Argon closure (2026-11-08)

- [Interactive hydrogen-to-argon cipher laboratory](argon-cipher-020.html)
- User-supplied exact token: `..||..|....|||`
- Count of dots: **8**; count of bars: **6**.
- Declared scoring rule: dot `.` = 1, bar `|` = 2.
- Calculated cipher weight: **8 × 1 + 6 × 2 = 20**.
- User-assigned symbolic correspondence: **cipher 20 → argon closure**.
- Independent chemical fact: **argon's atomic number is 18** (18 protons); chemical atomic number 20 refers to calcium.
- The token is preserved byte-for-byte as an identity-bearing artifact; the score alone cannot reconstruct its original order or run lengths.
- First 18 chemical elements covered, hydrogen (Z=1) to argon (Z=18), including shell populations and a compact semantic action per element.
- Shell populations are pedagogical Bohr-like summaries, not true electron orbital pictures or a claim of physical transformation between elements.
- Periodic closure sequence: helium (2), neon (10), argon (18).

## Natural invariant

`identity = (raw token, parsing rule, computed score, assigned semantic referent, provenance)`

`C(token) = count('.') + 2 × count('|')`

Distinct tokens may have identical scores. No score equivalence permits automatic identity-merging.

## Next natural test

Find minimal distinct cipher strings with value 20; classify collisions between score and structure. Then continue to chemical potassium (Z=19) and calcium (Z=20) without conflating them with the user-assigned argon cipher label.
