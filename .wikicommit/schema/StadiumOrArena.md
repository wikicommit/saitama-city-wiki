---
wikicommit:
  base: https://schema.org/StadiumOrArena
  provenance: generate-interactive
  granularity:
    - Create a new page for each stadium, arena, ballpark or comparable sports venue named as an independent subject
    - Prefer schema:Place for a park or complex that merely contains a venue; the venue itself gets this type
    - A venue named only as the location of a single match or event is an incidental mention — use WikiLink [[StadiumOrArena/slug]] in body text instead of creating a page
    - Record the containing ward or park as containedInPlace, not as a separate page for the venue
    - Naming-rights names change; record the current name as title and note previous or concurrent names in the body rather than creating separate pages
title: ""
type: "schema:StadiumOrArena"
lang: ""
sources: []
tags: []

properties:
  description: ""
  address: ""
  containedInPlace: "[[AdministrativeArea/slug]]"
  maximumAttendeeCapacity: ""
  url: ""
---

(2-3 paragraph overview of the venue)

## Facilities & Access
(capacity, structure, location within the city, how to reach)

## History & Use
(opening, renovations, resident teams, notable events hosted)
