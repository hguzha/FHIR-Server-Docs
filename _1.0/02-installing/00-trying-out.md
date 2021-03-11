---
title: "Installing IBM FHIR Server"
excerpt: "Install a basic deployment to try out IBM Event Streams."
categories: installing
slug: trying-out
toc: true
---

* The IBM FHIR Server operator can be installed in an on-line cluster through the OpenShift CLI. 
* Multiple instances of the IBM FHIR Server operator may be deployed into different namespaces, one per namespace.

## Prerequisites

Red Hat OpenShift Container Platform 4.5 or later installed on one of the following platforms:

* Linux x86_64

Connectivity to any of the following database systems:

* IBM Db2 11.5 or later
* PostgreSQL 12.1 or later

Connectivity to any of the following event streaming platforms (optional):

* Kafka 1.0 or higher

## Limitations

* The Operator may be deployed into different namespaces, one per namespace.
* The Operator has limited support for IBM FHIR Server configuration.


*Schema upgrades require downtime:* The IBM FHIR Server requires downtime to complete upgrades of the IBM FHIR Server's relational data. During the upgrade Values tables are refreshed, updated and optimized for the workloads that the FHIR specification supports.