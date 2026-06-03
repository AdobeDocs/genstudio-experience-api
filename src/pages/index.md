---
title: GenStudio API overview
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

<Superhero slots="heading, text" background="rgb(49, 46, 129)" textColor="white" />
# GenStudio API documentation

GenStudio for Performance Marketing is a platform that allows you to create and manage your performance marketing campaigns. Here you'll find the APIs we offer to help you build your own integrations with GenStudio.

<DiscoverBlock slots="heading, link, text"/>

### Explore our APIs

[GenStudio Experience API](#genstudio-experience-api)

Retrieve approved GenStudio Experiences and deliver Experience data and assets to your applications at scale.

## GenStudio Experience API

<Announcement slots="heading, text, text" className="request-access-announcement" variant="secondary" borderColor="#c148ed" hasborder="true" />

### Experience API architecture may change

The GenStudio Experience API is backward compatible. We may add new optional fields to API responses over time. Design your clients to ignore unknown properties so integrations keep working without code changes when responses grow.

This service may experience breaking changes in the next few months as we respond to feedback and requests from the community.

Retrieve approved GenStudio Experiences and deliver Experience data and assets to your applications at scale.

The GenStudio Experience API is a storage-agnostic public REST API for Adobe GenStudio for Performance Marketing. Use it to read approved Experiences, list and filter Experience summaries, and download assets through pre-signed URLs.

### What can I do with the GenStudio Experience API?

The GenStudio Experience API lets your server-side applications:

* **Get a full Experience** — Retrieve a single Experience by ID, including fields, variants, and asset URLs.
* **List Experiences** — Return a paginated, filterable list of Experience summaries by channel, language, and date range.
* **Deliver Experience assets** — Obtain a short-lived pre-signed URL for an asset or rendition, including web-optimized or original binary output.

### Why choose the GenStudio Experience API?

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
