---
title: "newspaper_hadiqat-al-akhbar: read me"
author: Till Grallert
ORCID: orcid.org/0000-0002-5739-8094
date: 2021-05-17
---

[![DOI](https://zenodo.org/badge/120906354.svg)](https://zenodo.org/badge/latestdoi/120906354) [![ORCID](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0002-5739-8094) [![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This repository contains bibliographic metadata for the first 357 issues of the weekly newspaper *Ḥadīqat al-Akhbār* published by Khalīl al-Khūrī in Beirut between 1858 and 1865. Digital facsimiles are not publicly available online. Local facsimiles have been added from #142 onwards.

# current state/ to do

- **done**: for some unknown reason, `<biblStruct>` carry two Julian dates from issue #142 onwards. The second one is erroneous and doesn't regularly change between issues.

# some technical details

This repository contains a single [TEI XML][source] file containing one `<biblStruct>` for each issue. This file is produced through automatic iteration making use of [this code](https://www.github.com/OpenArabicPE/generate_metadata-through-iteration) and manual validation against the digital facsimiles of the microfilm copies held at Staatsbibliothek zu Berlin.

The TEI is then [automatically converted](https://www.github.com/OpenArabicPE/convert_tei-to-mods) to [MODS XML][mods] for integration into reference management software etc (such as Zotero).


[source]: metadata/hadiqat-al-akhbar.TEIP5.xml
[mods]: metadata/hadiqat-al-akhbar.MODS.xml