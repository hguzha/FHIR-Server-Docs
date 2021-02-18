---
title: "Resources Required"
excerpt: "Uninstalling Event Streams."
categories: installing
slug: uninstalling
toc: true
---



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
