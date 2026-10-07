# Notes

## Status

Base language frozen: `spec/maro.yaml` + `out/maro.json` (seed 202).

## Tooling

The pipeline commands (run with the toolkit interpreter):

- `conlang grow --words words.json` — grow the lexicon to cover the text.
- `conlang translate --glosses the_quiet_morning_maro.tsv --sentences the_quiet_morning_sentences.csv --out the_quiet_morning_maro.csv`
- `conlang validate-translation --csv the_quiet_morning_maro.csv`
- `conlang extras --workspace . --csv the_quiet_morning_maro.csv`

Port from a sibling: `conlang translate --port-from <source_gloss.csv> --source-model <source.json> …`.
