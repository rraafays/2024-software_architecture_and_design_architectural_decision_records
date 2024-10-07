---
parent: Decisions
nav_order: 100
title: ADR Template

# status: accepted
# date: 2024-10-01
# decision-makers: Raf, Veronica, Flinn
# consulted: Essam, Bassu
# informed: Essame, Veronica, Raf, Flinn
---
<!-- markdownlint-disable-next-line MD025 -->
# Headless Content Management System

## Context and Problem Statement

Currently, AML uses a legacy CMS system which is evident in the case study. This legacy CMS system is a limiting factor for AML. Switching to a headless CMS provides AML with far more options as well as ensuring that they have access to an admin panel without needing to create one from scratch.

## Considered Options

* Strapi
* Sanity
* WordPress VIP

## Decision Outcome

Chosen option: Strapi, because it is the only one of the options that is completely free, open source and also its user interface for its admin panel seems to be the most well-thought-out and user-friendly for non-technical users. Additionally, it is able to use a wide range of plugins which will make development of a proof of concept much easier than the other options considered.

### Consequences

* Good, because it is free open source software and perfectly achieves our goals of replacing a legacy content management system.
* Bad, because for the purpose of a proof of concept, a headless content management system may be too open-ended however this isn't necessarily bad

### Confirmation

This ADR will be confirmed by the success of the proof of concept itself as this is a core service / component of this system which is fundamental to its operation.

## More Information

Since I personally (Raf). Am experienced with Strapi, it is both a safe and trustworthy bet for our proof of concept and most importantly it fits the criteria of the client AML perfectly.
