---
layout: default
title: Search
permalink: /search/
lead: Predictive search in the header, popular searches and the search results page.
---

## Predictive search

With **Enable predictive search** on (**Theme settings > Collection and search**), results appear as the shopper types: products, collections, pages and blog articles. Shoppers can move through results with the arrow keys and press Enter to open one, or press Enter in the field to see all results.

{% include figure.html src="search/predictive" alt="The search overlay with the query chair and five matching products with images and prices" caption="Predictive search shows results as the shopper types." %}

| Setting | Where | Description |
| --- | --- | --- |
| Show search icon | Theme settings > Header | Shows the search icon in the header. |
| Search opens as | Theme settings > Header | **Overlay** or **Drawer**. The drawer slides in from the side, the same width as the cart drawer. |
| Search overlay color scheme | Theme settings > Collection and search | Color scheme of the search overlay. |
| Popular search 1–4 | Theme settings > Collection and search | Up to four search terms shown as shortcuts. |

Predictive search uses Shopify's search. To tune results, for example with synonyms or product boosts, use the **Shopify Search & Discovery** app.

## Search results page

Open the search template in the theme editor (page selector **Search**). The **Search results** section has these settings:

{% include figure.html src="search/results" alt="The search results page: 30 results for chair, with tabs for products, pages and articles" caption="The search results page." %}

| Setting | Description |
| --- | --- |
| Show breadcrumb | Shows the breadcrumb trail. |
| Heading (empty state), Intro text (empty state) | Shown before the shopper has searched. |
| Results per page | Number of results before pagination. |
| Card style, Image ratio, Show quick add button, Show vendor, Show secondary image on hover, Show star rating | Product card options. |

Search results can be filtered and sorted with the filters you set up in the Search & Discovery app.

## Popular searches

Popular search terms appear as chips when the search page is empty or has no results. Add a **Popular search** block (Label, URL (optional)) for each chip. Without blocks, the page uses the four **Popular search** terms from Theme settings > Collection and search.
