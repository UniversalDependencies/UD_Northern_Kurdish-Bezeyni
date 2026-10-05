# UD Northern Kurdish-Bezeyni

## Summary

UD Northern Kurdish-Bezeyni is a treebank of Northern Kurdish (Bezeyni, ISO 639-3: kmr) annotated in Universal Dependencies. It is intended to support parsing, linguistic research, and language technology development for Northern Kurdish. The treebank covers the Turin variety of Bezeyni, as documented in Celebi (2021).

## Language

- **Language:** Northern Kurdish
- **ISO 639-3:** kmr
- **Variety:** Bezeyni
- **Family:** Indo-European -> Iranian -> Kurdish

## Treebank details

- **Treebank name:** UD Northern Kurdish-Bezeyni
- **Repository name:** UD_Northern_Kurdish-Bezeyni
- **Genre:** grammar examples
- **License:** CC BY-SA 4.0
- **Data provider:** Cemile Celebi
- **UD annotation:** Hiwa
- **Contributors:**
  - Cemile Celebi (data collection and linguistic analysis)
  - Hiwa (UD annotation and treebank preparation)
  - [Future contributor placeholder]
- **Contact:** hiwa@example.com
- **Data source:** Celebi, Cemile (2021). Zur Frage des grammatischen Genus im Bezeyni-Kurdischen: Eine empirische Untersuchung am Beispiel der Turin-Varietaet. Unpublished MA thesis, Goethe-Universitaet Frankfurt. Data collected from 8 Bezeyni native-speaker women from Turin village, Haymana district, Ankara province, Turkey.
- **Annotation guidelines:** Universal Dependencies guidelines, with language-specific decisions for Northern Kurdish Bezeyni documented in the repository.
- **Splits:** train / dev / test

## Statistics

| Split | Sentences | Tokens |
|---|---:|---:|
| Train | 119 | 600 |
| Dev   | 26 | 149 |
| Test  | 25 | 140 |
| **Total** | **170** | **889** |

## Data splits

- kmr_bezeyni-ud-train.conllu - training data (119 sentences, 602 tokens)
- kmr_bezeyni-ud-dev.conllu   - development data (26 sentences, 147 tokens)
- kmr_bezeyni-ud-test.conllu  - test data (25 sentences, 140 tokens)

## Acknowledgments

The linguistic data in this treebank was collected and analyzed by Cemile Celebi as part of her MA thesis at Goethe-Universitaet Frankfurt (2021). The UD annotation was carried out by Hiwa. We thank the eight Bezeyni native-speaker women from Turin village who provided the original language data.

## Known issues

- The treebank is under active development.
- Some constructions may require further annotation consistency checks.
- Future releases may revise lemmas, features, or dependency relations.

## Changelog

- **2026-10-05:** Corrected train/dev/test split. Previously all three files contained the same 170 sentences; now the splits are genuinely disjoint. Regenerated statistics.
- **2026-10-05:** Initial preparation for UD submission.

## Citation

If you use this treebank, please cite both the treebank and the original data source:
@misc{ud_northern_kurdish_bezeyni,
title = {UD Northern Kurdish-Bezeyni},
author = {Hiwa and Celebi, Cemile},
year = {2026},
howpublished = {Universal Dependencies},
note = {Northern Kurdish (kmr), Bezeyni variety},
url = {https://github.com/UniversalDependencies/UD_Northern_Kurdish-Bezeyni}
}

@mastersthesis{celebi2021bezeyni,
author = {Celebi, Cemile},
title = {Zur Frage des grammatischen Genus im Bezeyni-Kurdischen: Eine empirische Untersuchung am Beispiel der Turin-Varietaet},
school = {Goethe-Universitaet Frankfurt},
year = {2021},
type = {Unpublished Master's thesis},
address = {Frankfurt am Main, Germany}
}


## License

This treebank is released under the Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0). See LICENSE.md for the full license text.
