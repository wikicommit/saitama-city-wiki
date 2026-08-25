---
wikicommit:
  base: https://schema.org/Report
  provenance: generate-interactive
  granularity:
    - Create a new page for a report published by a government body or organization as a single-instance work — a statistical yearbook edition, a census result summary, a survey report, a white paper — with a fixed publication date and a publisher that will not change
    - Do not use this type for a continuously-updated resource that has no meaningful publication date of its own (an official procedure page, a departmental index page); those are not works and generally need no page of their own
    - Prefer schema:ScholarlyArticle for academic papers and schema:Book for commercially published volumes; use this type for the institutional report genre that neither covers
    - Each edition of a recurring report series is its own page (e.g. the 令和2年版 and 令和3年版 of the same yearbook are two pages), since each has its own publication date, coverage period and figures. Link sibling editions from the body rather than merging them
    - Use WikiLink [[Report/slug]] when another page cites the report as the origin of a figure or claim
    - The report's own title is written verbatim in the language the publisher uses, not translated
    - publisher is the issuing body — WikiLink it as [[Organization/slug]] (or [[AdministrativeArea/slug]] for a municipality that already has a page) when that body is an independent subject; contentLocation is the area the report describes
title: ""
type: "schema:Report"
lang: ""
sources: []
tags: []

properties:
  description: ""
  publisher: "[[Organization/slug]]"
  datePublished: ""
  reportNumber: ""
  temporalCoverage: ""
  contentLocation: "[[Place/slug]]"
---

(2-3 paragraph overview of what the report covers and why it matters)

## Contents
(the report's structure — chapters, sections, what each covers)

## Key Findings
(the headline figures and conclusions the report itself states)
