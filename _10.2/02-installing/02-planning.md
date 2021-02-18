---
title: "Limitations"
excerpt: "."
categories: installing
slug: planning
toc: true
---

## Limitations

* The Operator may be deployed into different namespaces, one per namespace.
* The Operator has limited support for IBM FHIR Server configuration.
* Bulk Data Access operations `$export`, `$import`, and `$status` are not supported.

*Schema upgrades require downtime:* The IBM FHIR Server requires downtime to complete upgrades of the IBM FHIR Server's relational data. During the upgrade Values tables are refreshed, updated and optimized for the workloads that the FHIR specification supports.