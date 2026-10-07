# Maro

A generated language (`conlang` toolkit), translating *The Quiet Morning*.

## Regenerate

    conlang generate --spec spec/maro.yaml --out out/maro.json

## Translate

    conlang translate --workspace . --glosses the_quiet_morning_maro.tsv \
      --sentences the_quiet_morning_sentences.csv --out the_quiet_morning_maro.csv
    conlang validate-translation --csv the_quiet_morning_maro.csv
