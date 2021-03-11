---
title: "Upgrading to IBM FHIR Server Operator"
excerpt: ""
categories: installing
slug: upgrading
toc: true
---

### Upgrading to IBM FHIR Server Operator

Starting with IBM FHIR Server Operator, the IBM FHIR Server configuration requires a separate datasource configuration from the fhir-server-config.json configuration file.

Before upgrading to IBM FHIR Server Operator, set the IBM_FHIR_SERVER_DATASOURCE secret key as described in [Define IBM FHIR Server configuration](inventory/ibmFhirServerOperator/README.md#1-define-ibm-fhir-server-configuration).

Until the IBM_FHIR_SERVER_DATASOURCE secret key is set, the IBM FHIR Server instance will not be functional.