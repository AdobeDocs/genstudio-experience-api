---
title: GenStudio Experience API overview
description: Retrieve approved GenStudio Experiences, assets, and templates through a storage-agnostic REST API for Adobe GenStudio for Performance Marketing.
hideBreadcrumbNav: true
keywords:
  - GenStudio Experience API
  - GenStudio for Performance Marketing
  - experience API
  - approved experiences
  - storage-agnostic API
  - Adobe OAuth Server-to-Server
  - REST API
---

<Superhero slots="heading, text" background="rgb(176, 226, 220)" textColor="navy" />

# GenStudio Experience API

Retrieve approved GenStudio Experiences and deliver Experience data and assets to your applications at scale.

The GenStudio Experience API is a storage-agnostic public REST API for Adobe GenStudio for Performance Marketing. Use it to read approved Experiences, list and filter Experience summaries, download assets through pre-signed URLs, and retrieve frozen HTML templates. All endpoints return the same response shape regardless of whether Experiences are stored in Amazon S3 or Adobe Experience Manager (AEM).

## What is the GenStudio Experience API?

The GenStudio Experience API lets your server-side applications:

* **Get a full Experience** — Retrieve a single Experience by ID, including fields, variants, and asset URLs.
* **List Experiences** — Return a paginated, filterable list of Experience summaries by brand, campaign, channel, product, audience, persona, language, and date range.
* **Deliver Experience assets** — Obtain a short-lived pre-signed URL for an asset or rendition, including web-optimized or original binary output.
* **Retrieve Experience templates** — Access the HTML template captured at experience creation time, via direct response or redirect.

## Why choose the GenStudio Experience API?

* **Storage-agnostic contract** — Integrate once; the API returns consistent JSON whether the backing store is S3 or AEM. For supported storage providers and rate limits, see [usage notes](getting-started/usage-notes/index.md).
* **Efficient reads** — Support for conditional requests and cursor-based pagination on list calls.
* **Enterprise-ready auth** — OAuth Server-to-Server flow aligned with Adobe Developer Console projects.

## Discover

<DiscoverBlock slots="heading, link, text"/>

### Get started

[Authentication](getting-started/index.md)

Set up OAuth Server-to-Server credentials and call the API securely from your backend.

<DiscoverBlock slots="link, text"/>

[API reference](api/index.md)

Explore endpoints, request parameters, response schemas, and examples.

<Resources slots="heading, link"/>

#### More GenStudio resources

* [GenStudio for Performance Marketing Experience Selector](https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/ext-guide/apps/experience-selector)
* [GenStudio for Performance Marketing Extensibility Guide](https://experienceleague.adobe.com/en/docs/genstudio-for-performance-marketing/ext-guide/home)

## Ready to try it?

Start with [Authentication](getting-started/index.md), then use the [API reference](api/index.md) to call `https://genstudio.adobe.io` endpoints in your environment.
