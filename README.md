# OpenZenTranslations

Translations and community work derived from the [OpenZenTexts](https://github.com/Fabulu/OpenZenTexts) collection of free-licensed Chinese Chan/Zen primary texts.

This is the **commercial-reuse-permitted** companion to the CBETA-derived [Fabulu/CbetaZenTranslations](https://github.com/Fabulu/CbetaZenTranslations). It exists so that translators, scholars, and publishers can produce English (and other-language) translations of Chinese Zen texts without inheriting the CBETA non-commercial restrictions that apply to the parallel CBETA collection.

## What's in here

```
xml-open-t/                        ← canonical/shared translated TEI XML
  ws/
    gateless-barrier/              ← (translations land here as they are produced)

community/                         ← per-user community contributions
  translations/{user}/             ← personal translations
  termbases/{user}.json            ← personal terminology
  collections/{user}.jsonl         ← personal Scholar collections
  reviews/{user}.jsonl             ← personal review state
  tags/{user}.jsonl                ← personal tagging
  tag-vocabularies/{user}.json     ← personal tag vocabularies
  master-dates/{user}.jsonl        ← personal master metadata

titles.jsonl                       ← title index for the collection
LICENSE.md                         ← collection-level licensing summary
README.md                          ← this file
```

The directory structure mirrors [Fabulu/CbetaZenTranslations](https://github.com/Fabulu/CbetaZenTranslations) so the [Read Zen](https://github.com/Fabulu/ReadZen) desktop app can read either repository with the same code path. The differences are:

- The XML originals folder is `xml-open-t/` (not `xml-p5t/`) to make accidental cross-cloning impossible
- File identifiers use the OpenZenTexts scheme (e.g. `ws.gateless-barrier`) rather than CBETA's (e.g. `T48n2005`)
- License terms are **commercial-reuse-permitted** by design — see [`LICENSE.md`](LICENSE.md)

## Companion repositories

- [Fabulu/OpenZenTexts](https://github.com/Fabulu/OpenZenTexts) — the source originals this collection translates
- [Fabulu/ReadZen](https://github.com/Fabulu/ReadZen) — the desktop reader/translator
- [Fabulu/CbetaZenTexts](https://github.com/Fabulu/CbetaZenTexts) and [Fabulu/CbetaZenTranslations](https://github.com/Fabulu/CbetaZenTranslations) — the parallel CBETA-derived collection (non-commercial only)

## License

Each translated TEI file declares its own license in its `<teiHeader>/<fileDesc>/<publicationStmt>/<availability>` block. By default, contributors are encouraged to release new translations under permissive licenses (CC BY 4.0, CC0, MIT, or similar) to keep the whole collection commercially reusable, but the per-file declaration is authoritative.

See [`LICENSE.md`](LICENSE.md) for details.
