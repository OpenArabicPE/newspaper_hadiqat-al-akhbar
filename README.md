---
title: "newspaper_hadiqat-al-akhbar: read me"
author: Till Grallert
date: 2018-02-09 14:16:26 +0200
---


This repository contains bibliographic metadata for the first 357 issues of the weekly newspaper *Ḥadīqat al-Akhbār* published by Khalīl al-Khūrī in Beirut between 1858 and 1865. Digital facsimiles are not publicly available. 

# current state

- 2018-02-09: released complete metadata as TEI and MODS XML

# some technical details

This repository contains a single [TEI XML][source] file containing one `<biblStruct>` for each issue. This file is produced through automatic iteration making use of [this code](https://www.github.com/OpenArabicPE/generate_metadata-through-iteration) and manual validation against the digital facsimiles of the microfilm copies held at Staatsbibliothek zu Berlin.

The TEI is then [automatically converted](https://www.github.com/OpenArabicPE/convert_tei-to-mods) to [MODS XML][mods] for integration into reference management software etc (such as Zotero).


[source]: metadata/hadiqat-al-akhbar.TEIP5.xml
[mods]: metadata/hadiqat-al-akhbar.MODS.xml