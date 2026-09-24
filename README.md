# Kotoba language packs

Downloadable dictionary databases for the Kotoba vocabulary widget app. Each [release](../../releases) contains SQLite databases compressed with raw DEFLATE; the app verifies each one against a SHA-256 checksum before installing it.

| Pack | Contents |
|---|---|
| `ja-full-<date>.sqlite.deflate` | Every JMdict entry (Japanese–English) |
| `zh-full-<date>.sqlite.deflate` | Every CC-CEDICT entry (Chinese–English) with HSK levels |

## Licences and attribution

The dictionary data is distributed under **[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)**.

- **JMdict**: property of the [Electronic Dictionary Research and Development Group](https://www.edrdg.org/), used in conformance with the Group's [licence](https://www.edrdg.org/edrdg/licence.html) (CC BY-SA 4.0). JSON conversion by [jmdict-simplified](https://github.com/scriptin/jmdict-simplified).
- **JLPT word lists**: Jonathan Waller, [tanos.co.uk](http://www.tanos.co.uk/jlpt/) (CC BY); JMdict mapping by [stephenmk/yomitan-jlpt-vocab](https://github.com/stephenmk/yomitan-jlpt-vocab) (CC BY-SA 4.0).
- **Furigana**: [JmdictFurigana](https://github.com/Doublevil/JmdictFurigana) (CC BY-SA 4.0).
- **CC-CEDICT**: published by [MDBG](https://www.mdbg.net/chinese/dictionary?page=cc-cedict) (CC BY-SA 4.0), based on CEDICT by Paul Andrew Denisowski.
- **HSK word lists**: [complete-hsk-vocabulary](https://github.com/drkameleon/complete-hsk-vocabulary) by drkameleon (MIT); official pinyin from [hsk-vocabulary](https://github.com/clem109/hsk-vocabulary) by clem109 (MIT).
- **Example sentences**: the [Tatoeba Project](https://tatoeba.org) (CC BY 2.0 FR).
