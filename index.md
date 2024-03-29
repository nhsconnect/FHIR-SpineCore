---
title: Introduction to Spine Core FHIR API Framework
keywords: homepage
tags: [overview]
sidebar: overview_sidebar
permalink: index.html
toc: false
summary: A brief introduction to getting started with FHIR&reg; APIs for national Spine services.
---

{% include important.html content="The content on this page is now out of date.  For up-to-date information, see the [API catalogue filtered for FHIR APIs](https://digital.nhs.uk/developer/api-catalogue?filter=fhir). " %}

# Introduction #

Traditionally, the "Spine" has provided national services through a range of messaging standards including ebXML and SOAP messages. Many of these interfaces are being migrated to make use of HL7 FHIR standards. This documentation covers the common capabilities in the Spine for managing and processing national FHIR APIs.

There are two main classes of APIs that are covered by this guidance:

- FHIR APIs for national NHS Digital services such as [Visitors and Migrants](http://developer.nhs.uk/apis/vandm), [National Opt-Out](), the [National Record Locator Service](https://developer.nhs.uk/apis/nrls/) and [Reasonable Adjustments](https://developer.nhs.uk/apis/reasonable-adjustments/)
- FHIR APIs in external systems brokered through the Spine Secure Proxy such as [GP Connect](https://developer.nhs.uk/apis/gpconnect/).

This specification covers the common functionality for all the above nationally defined APIs processed through the Spine.

{% include note.html content="This specification does not cover FHIR 'messaging', or the transfer of FHIR 'documents', for information on national standards for this, refer to the [ITK3 specifications](https://nhsconnect.github.io/ITK3-FHIR-Messaging-Distribution/) and the [Transfer of Care Specifications](https://developer.nhs.uk/transfer-care-specification-versions/)." %}

