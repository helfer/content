---
alias: emaig4uiki
path: /docs/reference/platform/integrations/algolia
layout: REFERENCE
description: Algolia is a hosted Search API that delivers instant results. Auto-sync your GraphQL data to Algolia search indices with this integration.
tags:
  - platform
  - integrations
  - algolia
  - data-management
related:
  further:
    - ahwoh2fohj
    - iaxohpee8o
    - naed3eecie
  more:
    - aroozee9zu
---

# Algolia Integration

## Collect the needed Credentials

In your [Algolia](https://algolia.com) settings, copy the Algolia App Id and create a new API key with **Add Records** and **Delete Records** enabled:

![](./algolia-settings.png)

## Activate the Algolia Integration

Enter the collected credentials in the Algolia integration popup in the Console:

![](./algolia-credentials.png)

## Create new Search Indices

* select the model that you want to define the index on
* enter the name of the search index. This name needs to be entered in your application as well!
* enter the query that defines the structure of the search index

![](./algolia-create-index.png)
