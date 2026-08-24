---
wikicommit:
  base: https://schema.org/AdministrativeArea
  provenance: init-theme
  granularity:
    - Create a new page for each administrative division that serves as an independent reference point (the city itself, its wards, and comparable government-jurisdiction areas)
    - Use WikiLink [[AdministrativeArea/slug]] when a ward or municipality is mentioned only to locate something else; record the containing ward of a facility as that facility's containedInPlace, not as a new page
    - Prefer schema:Place over this type for non-jurisdictional locations (buildings, shrines, parks, stations) even when they lend their name to a surrounding area
    - Do not create a page for an administrative division mentioned only as part of a postal address with no independent facts about the division itself stated in the source
title: ""
type: "schema:AdministrativeArea"
lang: ""
sources: []
tags: []

properties:
  description: ""
  containedInPlace: "[[AdministrativeArea/slug]]"
  containsPlace: "[[Place/slug]]"
  address: ""
  url: ""
---

(2-3 paragraph overview of the administrative area)

## Geography & Boundaries
(location within the wider municipality, adjacent areas, notable terrain)

## History
(establishment, boundary changes, mergers, historical background)

## Notable Places & Organizations
(major facilities and organizations located within this area)
