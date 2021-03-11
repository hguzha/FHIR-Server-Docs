---
title: "Prerequisites"
excerpt: "Prerequisites for installing IBM FHIR Server."
categories: installing
slug: prerequisites
toc: true
---

## Prerequisites

Red Hat OpenShift Container Platform 4.5 or later installed on one of the following platforms:

* Linux x86_64

Connectivity to any of the following database systems:

* IBM Db2 11.5 or later
* PostgreSQL 12.1 or later

Connectivity to any of the following event streaming platforms (optional):

* Kafka 1.0 or higher

## Storage

* Storage for the database instance that the IBM FHIR Server connects to is outside the scope of this Operator.

## Resources Required

* Describe Minimum System Resources Required

    Minimum scheduling capacity:
    
    | Software        | Memory (GB) | CPU (cores) | Disk (GB) | Nodes |
    | --------------- | ----------- | ----------- | --------- | ----- |
    | IBM FHIR Server |     6       |     2       |    N/A    |   2   |
    | **Total**       |     6       |     2       |    N/A    |   2   |
    
    Recommended scheduling capacity:
    
    | Software        | Memory (GB) | CPU (cores) | Disk (GB) | Nodes |
    | --------------- | ----------- | ----------- | --------- | ----- |
    | IBM FHIR Server |     64      |     16      |    N/A    |   3   |
    | **Total**       |     64      |     16      |    N/A    |   3   |
    
    *Note:* There is an initContainer with the IBM FHIR Server called the IBM FHIR Server Schema Tool. This tool has a small memory footprint used on initialization of a pod and is accounted for in the above capacities.
