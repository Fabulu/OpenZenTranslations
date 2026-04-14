# OpenZenTranslations — License Summary

This repository contains translations and community work derived from the [OpenZenTexts](https://github.com/Fabulu/OpenZenTexts) collection of free-licensed Chinese Zen primary texts. **Each file's authoritative license is the one declared in its TEI `<availability>` block (for translation XML) or per-user license preference (for community files).** This document summarizes the categories.

---

## Translation XML files (`xml-open-t/`)

Translations of OpenZen originals. Contributors are strongly encouraged to release translations under one of these permissive licenses to keep the collection commercially reusable end-to-end:

- **CC BY 4.0** ([https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)) — preferred for new translations. Allows commercial use; requires attribution.
- **CC0** ([https://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/)) — for translators who want to release into the public domain.
- **MIT License** — for contributions where MIT is preferred (e.g. when bundling with software).
- **CC BY-SA 4.0** — acceptable but adds share-alike obligations to derivative works.

A translation that uses **CC BY-SA 4.0 source text from Wikisource** verbatim or in close paraphrase may inherit share-alike obligations from the source. Translations that are independent re-renderings of public-domain originals (rather than derivative works of the Wikisource transcription) are not bound by the source text's license.

Each translation TEI file must carry its license declaration in `<availability>`. The Read Zen desktop app reads this and displays it to users.

---

## Community files (`community/`)

Per-user contributions live under `community/{kind}/{user}.{ext}`:

- **Personal translations** (`community/translations/{user}/...`) — each user controls the license of their own files. The user's preferred license is recorded in the TEI header of each translation, or in a per-user `LICENSE.md` if they prefer a uniform license.
- **Termbases, tags, collections, reviews, master-dates** — these are user-curated metadata. Each user is responsible for the license under which they share their contributions. By default, by submitting to this repository, contributors agree to permissive (CC BY 4.0 or compatible) terms; they can override this in their per-user files.

---

## Title index and shared metadata

- **`titles.jsonl`** — collection title index. Public domain (CC0).

---

## NOT derived from CBETA

This repository contains nothing derived from CBETA-encoded material. It exists specifically to provide a commercial-reuse-permitted alternative to the parallel CBETA-derived [Fabulu/CbetaZenTranslations](https://github.com/Fabulu/CbetaZenTranslations).

If you want to translate a text that is only available via CBETA (and not yet in [OpenZenTexts](https://github.com/Fabulu/OpenZenTexts)), use the parallel CBETA collection — but understand that CBETA's non-commercial terms may apply to your derivative work.

---

## Reporting a license issue

If you believe any file in this collection is mis-licensed or contaminated with material whose original source has more restrictive terms than declared, please open an issue. Contested files will be moved out of `xml-open-t/` until resolved.
