# CRS Reports Archive

Markdown and PDF versions of Congressional Research Service (CRS) reports, maintained as an
open-access reference archive that is also machine-readable.

CRS produces nonpartisan policy research for members of Congress and their staff.
CRS products cover the full range of federal policy—tax, appropriations, defense, health,
housing, immigration, and more. They are among the most useful policy documents the
federal government produces, and they are U.S. government works not subject to
copyright.

This archive preserves individual reports as clean, readable markdown files suitable for
research, citation, and use with AI tools. Each file includes a metadata header
(title, report number, version, date, authors, and source URL) and the full report
body. Due to the text-only limitations of Markdown files, graphics are not included.
Users will see conversion-inserted placeholders, e.g.:

	| Figure 1. ESF Credit Operations with Foreign Countries
	|
	|

---

## Organization

Files are first organized by format: <br>
`/markdown/`<br>
`/pdf/`

Within each parent folder, files are organized by CRS product type:<br>
`/in-focus/`     — CRS In Focus (IF): 2-page reference products<br>
`/insights/`     — CRS Insights (IN): short, event-driven products<br>
`/reports/`      — CRS Reports (R): full-length comprehensive reports<br>
`/sidebars/`     — CRS Sidebars (LSB): brief legislative updates<br>

File naming convention: `[REPORTNUMBER]v[VERSION]-title-in-kebab-case.md`  
Example: `IN12609v1-some-report-title.md`

Each file includes a version number. Unlike a typical Git workflow, updated versions
of a report are not committed over the existing file—both versions are retained, with
versioning reflected in the filename.

---

## Source and methodology

Reports are sourced from [Congress.gov](https://www.congress.gov) and
[crsreports.congress.gov](https://crsreports.congress.gov). HTML versions are
converted to Markdown using a purpose-built browser extension. PDF versions are downloaded
directly from congress.gov. 

---

## Related

This archive supports [*What Congress Should Be Reading*](https://crsreports.substack.com?utm_source=github-crs-readme),
a free Substack newsletter covering newly released CRS products with plain-language
synopses and commentary.

---

## A note on CRS report access

CRS reports have been publicly available on Congress.gov since 2018. Prior to that,
access was uneven—reports circulated through member offices, think tanks, and
third-party aggregators, but there was no official public repository. This archive
is a small contribution to the ongoing project of making congressional research
genuinely accessible.
