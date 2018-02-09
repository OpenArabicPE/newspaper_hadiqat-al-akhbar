---
title: "journal_al-jinan: read me"
author: Till Grallert
date: 2018-02-06 12:44:47 +0200
---

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1167878.svg)](https://doi.org/10.5281/zenodo.1167878)

This repository contains bibliographic metadata for the journal *al-Jinān* published by Buṭrus al-Bustānī in in Beirut between 1875 and 1885. Digital facsimiles of the copies held at the Princeton University Library are available from HathiTrust. 

# current state

- 2018-02-06: released complete metadata as TEI and MODS XML

# some technical details

This repository contains a single [TEI XML][source] file containing one `<biblStruct>` for each issue. This file is produced through automatic iteration making use of [this code](https://www.github.com/OpenArabicPE/generate_metadata-through-iteration) and manual validation against the digital facsimiles.

The TEI is then [automatically converted](https://www.github.com/OpenArabicPE/convert_tei-to-mods) to [MODS XML][mods] for integration into reference management software etc (such as Zotero).


[source]: tei/al-jinan.TEIP5.xml
[mods]: metadata/al-jinan.MODS.xml