# Attribution

## Licences

- **Deck content** (word list, sentences, translations, meanings, grammar) - [CC BY-SA 4.0](LICENSE). Each sentence, translation and meaning also keeps its source's licence.
- **Pictures** - [Irasutoya's terms](https://www.irasutoya.com/p/terms.html): free, no credit required, not the main content of a work, and at most 20 per commercial work. The deck holds 1500, so it must stay free.
- **Audio** - each file keeps its source's licence.
- **Note type** - GPL-3.0-only, from [Anki Miner Note](https://github.com/0xzerolight/anki_miner_note), a fork of [Lapis](https://github.com/donkuri/lapis).

Each release attaches `credits.tsv`: one row per card, with the source, author and licence of its sentence, meaning, audio and picture.

## Sources

| Source | Supplies | Licence |
|---|---|---|
| [FrequencyWords](https://github.com/hermitdave/FrequencyWords), by Hermit Dave | The word ranking (2018 Romanian counts) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [Tatoeba](https://tatoeba.org) | 1468 sentences and their translations | [CC BY 2.0 FR](https://creativecommons.org/licenses/by/2.0/fr/) |
| [Wiktionary](https://en.wiktionary.org), via [kaikki.org](https://kaikki.org/dictionary/Romanian/) | 14 sentences; all meanings and grammar | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [OPUS](https://opus.nlpl.eu) corpora, below | 6 sentences and their translations | Per corpus |
| [Lingua Libre](https://lingualibre.org) and [Wikimedia Commons](https://commons.wikimedia.org) | 1130 word recordings | Per file, mostly [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [dots.tts-soar](https://huggingface.co/dots-studio/dots.tts-soar), by dots-studio | Synthetic audio: 370 words and every sentence | [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) |
| Mihai, from [OHF-Voice voice-datasets](https://github.com/OHF-Voice/voice-datasets) | The synthetic voice | [CC0](https://creativecommons.org/publicdomain/zero/1.0/) |
| [いらすとや](https://www.irasutoya.com), by みふねたかし | Every picture | [Irasutoya's terms](https://www.irasutoya.com/p/terms.html) |

| OPUS corpus | Provider | Licence |
|---|---|---|
| [ELRC Romanian literature](https://object.pouta.csc.fi/OPUS-ELRC-491-Romanian_literature/v1/moses/en-ro.txt.zip) | [ELRC-SHARE](https://elrc-share.eu) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [SETimes](https://object.pouta.csc.fi/OPUS-SETIMES/v2/moses/en-ro.txt.zip) | Nikola Ljubešić | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) |
| [Wikimedia translations](https://object.pouta.csc.fi/OPUS-wikimedia/v20260327/moses/en-ro.txt.zip) | Wikimedia Foundation | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [Tilde MODEL](https://object.pouta.csc.fi/OPUS-TildeMODEL/v2018/moses/en-ro.txt.zip) | Tilde | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

## Changes

- Text is copied as in its source, apart from Unicode normalisation (ş -> ș, ţ -> ț, spacing).
- Recordings are trimmed, loudness-normalised and re-encoded as MP3.
