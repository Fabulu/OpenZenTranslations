# OpenZenTranslations

Translations and community work derived from the [OpenZenTexts](https://github.com/Fabulu/OpenZenTexts) collection of free-licensed Chinese Zen primary texts.

[![Support on Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20this%20project-ff5e5b?logo=ko-fi&logoColor=white)](https://ko-fi.com/readzen)

This is the **commercial-reuse-permitted** companion to the CBETA-derived [CbetaZenTranslations](https://github.com/Fabulu/CbetaZenTranslations). It exists so that translators, scholars, and publishers can produce English (and other-language) translations of Chinese Zen texts without inheriting the CBETA non-commercial restrictions.

## Project status

This repository is in its early stages. There are currently **2 translation files** (both for the Gateless Barrier / Wumenguan), contributed by one user. Most community subdirectories are scaffolded but empty. Contributions are welcome.

## What's in here

```
xml-open-t/                              <- canonical/shared translated TEI XML
  ws/
    gateless-barrier/                    <- (scaffolded, no shared translations yet)

community/                               <- per-user community contributions
  translations/{user}/{collection}/{id}/ <- personal translations (2 XML files exist)
  termbases/{user}.jsonl                 <- personal terminology
  collections/{user}.jsonl               <- personal Scholar collections
  reviews/{user}.jsonl                   <- personal review state
  tags/{user}.jsonl                      <- personal tagging
  tag-vocabularies/{user}.json           <- personal tag vocabularies
  master-dates/{user}.jsonl              <- personal master metadata

titles.jsonl                             <- title index for the collection
LICENSE.md                               <- collection-level licensing summary
```

The directory structure mirrors [CbetaZenTranslations](https://github.com/Fabulu/CbetaZenTranslations) so the [Read Zen](https://github.com/Fabulu/ReadZen) desktop app can read either repository with the same code path. The differences are:

- The XML originals folder is `xml-open-t/` (not `xml-p5t/`) to make accidental cross-cloning impossible
- File identifiers use the OpenZen scheme (e.g. `ws.gateless-barrier`) rather than CBETA's (e.g. `T48n2005`)
- License terms are **commercial-reuse-permitted** by design -- see [`LICENSE.md`](LICENSE.md)

## Contributing

The easiest way to contribute translations is through the [Read Zen](https://github.com/Fabulu/ReadZen) desktop app, which handles file formatting and placement automatically.

To contribute manually, add your translation as a TEI XML file at:

```
community/translations/{your-username}/{collection}/{text-id}/{text-id}.xml
```

## License

Each translated TEI file declares its own license in its `<teiHeader>/<fileDesc>/<publicationStmt>/<availability>` block. By default, contributors are encouraged to release new translations under permissive licenses (CC BY 4.0, CC0, MIT, or similar) to keep the whole collection commercially reusable, but the per-file declaration is authoritative.

See [`LICENSE.md`](LICENSE.md) for details.

## Related repositories

| Repository | Description |
|---|---|
| [OpenZenTexts](https://github.com/Fabulu/OpenZenTexts) | Open-licensed Chinese Zen source texts (commercial use OK) |
| [CbetaZenTexts](https://github.com/Fabulu/CbetaZenTexts) | CBETA Chinese Zen source texts (non-commercial) |
| [CbetaZenTranslations](https://github.com/Fabulu/CbetaZenTranslations) | Translations of CBETA texts (non-commercial) |
| [Read Zen](https://github.com/Fabulu/ReadZen) | Desktop app for reading and translating Zen texts |
