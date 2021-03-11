---
title: "Upgrading to IBM FHIR Server Operator v1.1.0"
excerpt: ""
categories: installing
slug: migrating-to-apicurio
toc: true
---

### Upgrading to IBM FHIR Server Operator v1.1.0

Starting with IBM FHIR Server Operator v1.1.0, the IBM FHIR Server configuration requires a separate datasource configuration from the fhir-server-config.json configuration file.

Before upgrading to IBM FHIR Server Operator v1.1.0, set the IBM_FHIR_SERVER_DATASOURCE secret key as described in [Define IBM FHIR Server configuration](inventory/ibmFhirServerOperator/README.md#1-define-ibm-fhir-server-configuration).

Until the IBM_FHIR_SERVER_DATASOURCE secret key is set, the IBM FHIR Server instance will not be functional.