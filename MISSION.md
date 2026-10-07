# Mission: translate *The Quiet Morning* into Maro

**Maro** is a constructed language produced by the `conlang` toolkit — a seeded base (inventory and syllable shapes) generated and then deliberately extended. This project translates the fixed 111-sentence English story *The Quiet Morning* into Maro.

## Success measures

- All **111 sentences** translated in `the_quiet_morning_maro.csv` (`index,english,maro`).
- Every form legal under Maro's inventory and phonotactics; untranslatable items quarantined as `[slot]`.

## Sources of truth

- The model `out/maro.json`; the frozen spec `spec/maro.yaml`.
- The toolkit — the `conlang` package.
