---
title: "Experience API Technical Usage Notes"
description: This page contains technical usage notes for the Experience API.   
keywords:
- experience api
- technical usage notes
- storage providers
- supported storage providers
- storage agnostic
- storage agnostic api
- storage agnostic api notes
- storage agnostic api usage notes
- storage agnostic api technical usage notes
---
# Experience API Technical Usage Notes

This page offers technical usage notes for the Experience API.

## Storage providers

The Experience API is storage-agnostic. This means that the API can be used with any storage provider that is supported by Adobe GenStudio for Performance Marketing. The API returns the same shape, regardless of the underlying storage provider.

The following storage providers are supported by the Experience API:

* Amazon S3 (Simple Storage Service)
* Adobe Experience Manager (AEM)

## Rate limits

The following rate limits are enforced by the Experience API. Rate limits are enforced by the API gateway.

* List endpoint: 20 req/min/org
* GET endpoints (assets, template): 60 req/min/org