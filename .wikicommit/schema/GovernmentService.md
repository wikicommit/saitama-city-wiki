---
wikicommit:
  base: https://schema.org/GovernmentService
  provenance: init-theme
  granularity:
    - Create a new page for each administrative service or counter procedure the municipality offers as an independent subject (resident registration changes, waste collection, permit applications)
    - Use WikiLink [[GovernmentService/slug]] for incidental mentions of a service within another entity's page
    - Prefer schema:HowTo when the source's substance is an ordered set of steps the resident performs; use this type for the service itself — who provides it, who it serves, and through which counter or channel
    - Use schema:Organization for the department or office that provides the service, and link it from provider rather than creating a service page per office
title: ""
type: "schema:GovernmentService"
lang: ""
sources: []
tags: []

properties:
  description: ""
  provider: "[[Organization/slug]]"
  serviceType: ""
  areaServed: "[[AdministrativeArea/slug]]"
  availableChannel: ""
---

(2-3 paragraph overview of the service)

## Eligibility & Scope
(who the service is for, what it covers, area served)

## How to Use
(counters, channels, required documents, fees; link to [[HowTo/slug]] for step-by-step procedures)
