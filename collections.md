---
layout: default
title: Collections and filtering
permalink: /collections/
lead: The Collection section controls collection pages, including layouts with sidebars, filters, sorting and pagination.
---

Open a collection template in the theme editor (page selector **Collections > Default collection**) to edit it.

## Display

| Setting | Description |
| --- | --- |
| Show breadcrumb | Shows the breadcrumb trail above the title. |
| Show hero | Shows the collection title area. |
| Show image | Shows the collection image in the hero. |
| Description | **Above grid**, **Below grid** or **Hidden**. |

## Layouts and sub-collections

| Layout | What shoppers see |
| --- | --- |
| Product grid (default) | Products only. |
| Sub-collections grid, then products | Cards for child collections, then the products. |
| Sub-collections only (hub page) | Only the child collection cards. Good for top-level categories. |
| Left sidebar — Categories + filters | A sidebar with the category tree and the filters. |
| Left sidebar — Categories (filters in drawer) | A sidebar with the category tree; filters open in a drawer. |
| Two sidebars — Categories + filters + grid | One sidebar for categories, one for filters. |
| Left sidebar — Global menu | A sidebar with the whole category menu. |

**Category menu** is the menu Lintel reads to find a collection's sub-collections and to build the breadcrumb. Nest collection links in that menu (in **Online Store > Navigation**) to define your category tree. If the current collection isn't in the menu, the page uses the standard product grid.

<div class="callout"><p>To use a different layout for some collections, create an alternate collection template, set its layout, and assign it in the collection's <strong>Theme template</strong> setting.</p></div>

## Grid

| Setting | Description |
| --- | --- |
| Products per page | Number of products before pagination. |
| Desktop columns | Number of columns on large screens. |
| Mobile columns | **1 column** or **2 columns**. |
| Grid density | **Airy**, **Balanced** or **Dense** spacing. |
| Show grid toggle | Lets shoppers switch between 4, 3 or 2 columns or a list view. |
| Show result count | Shows the number of products. |

## Product cards

| Setting | Description |
| --- | --- |
| Card style | **Editorial** or **Commerce**. |
| Image ratio | **Use theme setting** or a ratio for this section. |
| Show quick add button | Adds products without leaving the page. Products with options open a picker. |
| Show vendor | Shows the vendor on cards. |
| Show secondary image on hover | Shows the product's second image on hover. |
| Show star rating | Shows ratings from a reviews app. |

## Filtering and sorting

Filters come from Shopify. Install the free **Shopify Search & Discovery** app and choose your filters there, for example availability, price, product type, vendor, tags and product options such as size and color. Lintel shows each filter in a matching style: checkboxes, a price range or a yes/no toggle.

| Setting | Description |
| --- | --- |
| Enable filtering | Shows filters. |
| Filter mode | **Drawer**, **Sidebar** or **None**. |
| Enable sorting | Shows the sort menu. |

Shopify allows filtering on collections with up to 5,000 products. Applied filters appear above the grid, each with a button to remove it.

## Pagination

| Option | Behavior |
| --- | --- |
| Numbered pagination | Page numbers with previous and next links. |
| View more button | A button that loads the next page below the current products. |
| Infinite scroll | The next page loads as the shopper nears the end of the grid. |

Set this in the Collection section's **Pagination** setting.

## Promotion tiles

Add **Promotion tile** blocks to insert editorial cards into the product grid.

| Setting | Description |
| --- | --- |
| Grid position | Slot where the tile appears (1 = before the first product). Positions beyond the product count appear at the end. |
| Image | A 3:4 image matches product cards. |
| Heading, Subheading, Button label, Link | Tile content. Leave Link blank for a tile that isn't clickable. |
| Text color | **Light (white text)** or **Dark (themed text)**. |
| Text alignment | **Left**, **Center** or **Right**. |
| Text background | The wash behind the text. Keep it at 55% or more so the text stays readable over any photo. |

## Collections list page

The page at `/collections` uses the **List collections** section. See [Template sections]({{ '/sections/#template-sections' | relative_url }}).
