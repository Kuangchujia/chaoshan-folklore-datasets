# Chaoshan Folklore Datasets · Index

**[简体中文](README.zh.md) ｜ English**

[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--7650--833X-a6ce39.svg)](https://orcid.org/0009-0002-7650-833X) [![OpenAlex](https://img.shields.io/badge/OpenAlex-A5151908354-ff6f00.svg)](https://openalex.org/A5151908354) [![Site](https://img.shields.io/badge/site-chaoshanwiki.com-blue.svg)](https://chaoshanwiki.com) [![Data: CC BY 4.0](https://img.shields.io/badge/Data-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> **This repository is an index, not a data repository. No CSV, JSON, archive or image file of any dataset is stored here.**
> Each dataset is published and versioned on Zenodo; this repository records only what exists, which version, under which licence, at which DOI, and which page on the website explains it. Download and cite from Zenodo. Always cite the **concept DOI** — it follows the collection to its latest version.

---

## I. The datasets at a glance

| # | Dataset | Coverage | Status · version | Zenodo concept DOI | Licence | Website | Source |
|:--:|:---|:---|:---|:---|:---|:---|:---|
| 1 | **Chaoshan Intangible Cultural Heritage List Dataset**<br>Shantou municipal register, batches 6–8 | **139** entries: batch 6 — 29 (doc 汕府〔2019〕6号), batch 7 — 58 (doc 汕府〔2022〕47号), batch 8 — 52 (doc 汕府〔2024〕63号)<br>10 categories; 22 fields<br>72 food entries, grouped by craft into 11 groups<br>33 entries already carry a corresponding page on the site | **Published**<br>v1.0 · 2026-10-23 | [10.5281/zenodo.23584608](https://doi.org/10.5281/zenodo.23584608) | CC BY 4.0 | — (none yet; see §III, item 1) | Three documents issued by the Shantou Municipal People's Government, transcribed item by item<br>OSF mirror [osf.io/n29q3](https://osf.io/n29q3/) |
| 2 | **Yingge dossier**<br>The Chaoshan war-dance, as performed by named teams | To be fixed once the material has been checked item by item | **Preparing** | — | CC BY 4.0 (intended) | [Yingge section, 8 pages](https://chaoshanwiki.com/yingge/what/) | Pages of the site's Yingge section and field records |
| 3 | **Chaoshan temple fairs and festival calendar** | To be fixed once the material has been checked item by item | **Planning** | — | CC BY 4.0 (intended) | [Festival calendar](https://chaoshanwiki.com/god-parade/) | Pages of the site's festival-calendar section |
| 4 | **Chaoshan traditional crafts** | To be fixed once the material has been checked item by item | **Planning** | — | CC BY 4.0 (intended) | — | The register above already lists 98 items under "traditional crafts"; this dataset would go below the name to processes and transmission, and is not meant to repeat the register |

**"Published" means one thing here: the Zenodo record is public.** It does not mean the register is complete, that it has been revised, or that a page for it exists on the website.

Rows 2–4 are not datasets yet. Their coverage is written as "to be fixed" rather than guessed, because a scope declared before the material has been checked is a promise, not a description. They stay in this table so that work in progress has a fixed place to be declared instead of appearing without notice.

---

## II. Index or data — who holds what

| Layer | Holds | Does not hold |
|:---|:---|:---|
| **The website** — chaoshanwiki.com | What the dataset is, how each item was checked, what it leaves out. Written to be read. | No archive files |
| **This repository** — GitHub | One row per dataset: coverage, version, licence, concept DOI, website page, source document. | **No data files of any kind** |
| **Zenodo** | The release itself: the archive, its checksums, `CITATION.cff`, `LICENSES.md`, `CHANGELOG`. | No page-by-page explanation |

Because no copy is kept here, there is no way for a "GitHub version" and a "Zenodo version" to drift apart. The authoritative file set is one, and it is on Zenodo. If files were ever served from this repository, that statement would stop being true; this repository does not serve them.

Two consequences worth stating, since both are the usual way this kind of index goes wrong:

- **No second home for data.** Uploading the same archive here as a convenience would create two release points with two dates and eventually two contents.
- **No silent replacement.** A correction goes out as a new Zenodo version; the version DOI of the old release keeps resolving, so a citation made last year still lands where it was meant to.

---

## III. How the four links hold together

| Step | What happens | Where it lands |
|:--:|:---|:---|
| 1 | Say what the dataset is, how it was checked, what it excludes | A page on the website |
| 2 | List version, licence, DOI and the corresponding website page | The table in §I of this file |
| 3 | Keep the released files and give a citable version record | Zenodo |
| 4 | On update, change all three in one pass; keep the old version; never swap it out quietly | Website, this table, Zenodo |

**State of the loop, 2026-10-23**

1. **Website page — missing for dataset 1.** The site's `/dataset/` page documents a different work: a manifest of the site's own pages. It is not a page about this register, so the row reads "—" rather than borrowing that link.
2. **This index** — the table above.
3. **Zenodo** — concept DOI `10.5281/zenodo.23584608`; the v1.0 release is record `23584609`; mirror on OSF at `osf.io/n29q3` (DOI `10.17605/OSF.IO/N29Q3`).
4. **Synchronisation rule** — a new release means: a new Zenodo version (the previous version DOI stays resolvable), a new version number and date in this table, and the website page updated in the same pass. The old row is not rewritten to look like the new one; what changed is recorded under §VIII.

---

## IV. Why only concept DOIs are cited

Every Zenodo record carries two identifiers:

| Identifier | Level | Behaviour |
|:---|:---|:---|
| **Concept DOI** | collection | **permanently points to the latest version of that collection** |
| Version DOI | record | fixed to one version; when a new version is released it **does not follow along** |

This index therefore publishes **concept DOIs only**. When a dataset gains a new version, the same string keeps working and never stalls at an old release.

---

## V. Scope and limits

- **Transcription, not interpretation.** What is recorded is what the gazettes print: item category, serial number, item name, and the unit that declares or protects it. No ranking, no assessment of authenticity or value, no statement about any individual.
- **Defects in the source are recorded, not repaired.** Batch 7 serials 1–9 are missing in the original; they were filled by table row order, and each such line says so in `note`. Batch 8 serials 36–37 use half-width parentheses in the original and are copied as printed.
- **The food flag and its grouping are the author's.** 72 entries are marked as food and arranged into 11 groups by craft. The gazettes do not classify them this way.
- **Three source documents, three different formats.** Batch 6 came as a PDF with a text layer, batch 7 as a compound `.doc`, batch 8 as an HTML table; merged cells were filled from the row above.
- **English titles are working translations** and claim no exclusivity.
- Nothing in this series concerns fortunes, auspicious dates, or advice of any kind.

---

## VI. Author and licence

| Item | Address |
|:---|:---|
| **Author** | Chujia Kuang (邝楚嘉 / pen name Jiayan Yide 嘉言一得) |
| **ORCID iD** | [0009-0002-7650-833X](https://orcid.org/0009-0002-7650-833X) |
| **OpenAlex** | [A5151908354](https://openalex.org/A5151908354) |
| **Website** | <https://chaoshanwiki.com> |
| **Other line of work** (calendar and historical astronomy) | <https://kuangchujia.com> · index <https://github.com/Kuangchujia/chinese-calendar-datasets> |
| **OSF mirror** | <https://osf.io/n29q3/> |

- **The data** is released under **Creative Commons Attribution 4.0 International (CC BY 4.0)**. The source gazettes are administrative documents and are not subject to copyright under Article 5 of the Copyright Law of the People's Republic of China; the transcription, structuring and checking records built on top of them are offered under CC BY 4.0.
- **This repository** — the index and its README — is likewise CC BY 4.0; `LICENSE` holds the licence text.
- **A different layer, not to be carried across.** Prose on the website is CC BY-SA 4.0 and its images are all rights reserved. The data licence does not extend to the site's prose, and the site's text licence does not extend to the data.

---

## VII. Sibling index

The author maintains a second, unrelated series on Chinese calendrics and historical astronomy — same author identity, same conventions for versioning, licensing and citation, different subject matter, kept in its own repository: [chinese-calendar-datasets](https://github.com/Kuangchujia/chinese-calendar-datasets) · <https://kuangchujia.com>. The two are deliberately not merged.

---

## VIII. Revision history

| Date | Version | Notes |
|:---|:---|:---|
| 2026-10-23 | 1.0.0 | Repository created. Dataset 1 (Shantou register of intangible cultural heritage, batches 6–8, v1.0) indexed with its concept DOI `10.5281/zenodo.23584608` and its OSF mirror. Rows 2–4 entered as preparing or planning, with no DOI and no version. Stated as a rule that this repository holds no data files. |
