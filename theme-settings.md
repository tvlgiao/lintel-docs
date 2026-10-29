---
layout: default
title: Theme settings
permalink: /theme-settings/
lead: Global settings that apply to the whole store. Open them in the theme editor with the paint brush icon (Theme settings).
---

Setting names below match the labels in the theme editor.

## Logo

| Setting | Description |
| --- | --- |
| Image | Your logo. Its display size is set in the Header section (Logo width and Logo height). |
| Favicon | The small icon shown in browser tabs. Use a square image. |
| Mobile logo | Optional logo used on small screens. |
| Logo text | Text shown when no logo image is set. |
| Default social media image | Image used when a page is shared on social media and has no image of its own. |

## SEO

| Setting | Description |
| --- | --- |
| Home page meta description | Description search engines may show for your home page. |
| Default meta description | Used on pages that have no description of their own. |

## Colors

See [Color schemes and dark mode]({{ '/colors/' | relative_url }}) for a full guide.

| Setting | Description |
| --- | --- |
| Default mode | **Auto (system)**, **Light** or **Dark**. The mode shoppers see first. Auto follows the shopper's device setting. |
| Show light/dark switcher | Adds a light/dark button to the header and mobile menu. A shopper's choice is remembered on their device. |
| Default color scheme | Sections set to inherit use this scheme, and so do the page background, cart drawer and search. |
| Color schemes | Six schemes, each with a light and a dark palette. |

## Typography

See [Typography and layout]({{ '/typography/' | relative_url }}).

{% include figure.html src="theme-settings/panel-typography" alt="The Typography group in theme settings: heading font, heading letter spacing and size scale, body font and line height" caption="Theme settings > Typography." mobile=true %}

| Setting | Description |
| --- | --- |
| Heading font | Font for headings, chosen from the Shopify font library. |
| Heading letter spacing | Spacing between heading letters. |
| Heading size scale | Scales all heading sizes up or down. |
| Body font | Font for body text, buttons and forms. |
| Body line height | Line height of body text. |

## Layout

{% include figure.html src="theme-settings/panel-layout" alt="The Layout group in theme settings: maximum page width and minimum page margin" caption="Theme settings > Layout." mobile=true %}

| Setting | Description |
| --- | --- |
| Maximum page width | **Narrow (90rem)** or **Wide (110rem)**. |
| Minimum page margin | The space between content and the edge of the screen. |

## Buttons

{% include figure.html src="theme-settings/panel-buttons" alt="The Buttons group in theme settings: border radius, vertical and horizontal padding, font size, uppercase text and letter spacing" caption="Theme settings > Buttons." mobile=true %}

| Setting | Description |
| --- | --- |
| Border radius | Roundness of button corners. |
| Vertical padding / Horizontal padding | Space inside buttons. |
| Font size | **Small**, **Regular** or **Medium**. |
| Uppercase text | Shows button labels in capital letters. |
| Letter spacing | Spacing between button label letters. |

## Motion

| Setting | Description |
| --- | --- |
| Reveal sections on scroll | Sections fade in as they scroll into view. |
| Enable subtle transitions | Short hover and state transitions. |

Lintel turns animations off for shoppers whose device asks for reduced motion, whatever these settings are.

## Cart

See [Cart]({{ '/cart/' | relative_url }}).

{% include figure.html src="theme-settings/panel-cart" alt="The Cart group in theme settings: cart type drawer or page, show vendor, cart note, recommendations, delivery estimate and bundle suggestion" caption="Theme settings > Cart." mobile=true %}

| Setting | Description |
| --- | --- |
| Cart type | **Drawer** opens a side panel when a product is added. **Page** goes to the cart page. |
| Show vendor | Shows the product vendor on cart lines. |
| Show cart note | Lets shoppers add a note to their order. |
| Show recommendations | Shows up to six products in the cart drawer, from the collection with the handle `cart-upsell` (or all products when that collection doesn't exist). |
| Delivery estimate | Text shown under each cart line, such as "Ships in 2–3 business days". Leave blank to hide. |
| Show bundle suggestion in cart drawer | Shows your Bundle heading, Bundle text and a link (Bundle link, Bundle link label) under the cart items. The theme doesn't apply a discount, so set up any bundle offer in **Discounts** first. |
| Show gift wrapping option in cart drawer | Adds a gift wrapping checkbox. When checked, the order gets the cart attribute "gift_wrap: yes". |
| Free shipping threshold | Minimum order amount for free shipping, in your store currency. Set to 0 to hide the progress bar. |

## Collection and search

| Setting | Description |
| --- | --- |
| Search overlay color scheme | Color scheme of the search overlay. |
| Enable predictive search | Shows products, collections, articles and pages as the shopper types. |
| Popular search 1–4 | Search terms shown as shortcuts in the search overlay and on the search page. |

## Social media

Add the URLs of your accounts: **X (Twitter)**, **Facebook**, **Instagram**, **Pinterest**, **TikTok** and **YouTube**. Icons appear in the footer and, where enabled, in other sections.

## Product cards

{% include figure.html src="theme-settings/panel-product-cards" alt="The Product cards group in theme settings: image ratio, text alignment, align rows across cards, and sale and new badges" caption="Theme settings > Product cards." mobile=true %}

| Setting | Description |
| --- | --- |
| Image ratio | Image shape on every product card: Adapt to image, Portrait (3:4), Square (1:1), Landscape (4:3), Landscape wide (3:2) or Widescreen (16:9). Sections can override it. |
| Text alignment | **Left** or **Center**. |
| Align rows across cards | Lines up titles, prices, ratings and swatches across a row of cards. |
| Show sale and new badges | Shows badges on product cards. The sold out label always shows. |
| Sale badge style | **Percentage** or **Text**. |

## Header

{% include figure.html src="theme-settings/panel-header" alt="The Header group in theme settings: transparent on home page, sticky header, search icon, search opens as, account row and cart item count" caption="Theme settings > Header." mobile=true %}

| Setting | Description |
| --- | --- |
| Transparent on home page | Makes the header transparent over hero sections on the home page. |
| Enable sticky header | Keeps the header visible while scrolling. |
| Show search icon | Shows the search icon in the header. |
| Search opens as | **Overlay** or **Drawer**. Applies when predictive search is on. |
| Show account row in the menu drawer | Adds an account link to the mobile menu. The account icon in the header always shows. |
| Show cart item count | Shows the number of items on the cart icon. |

## Navigation

The mobile navigation bar is a fixed bar at the bottom of the screen on phones (768px wide or less).

{% include figure.html src="theme-settings/panel-navigation" alt="The Navigation group in theme settings: show mobile navigation bar, hide on scroll down, and the settings of each tab" caption="Theme settings > Navigation." mobile=true %}

| Setting | Description |
| --- | --- |
| Show mobile navigation bar | Turns the bar on or off. |
| Hide on scroll down | Hides the bar while the shopper scrolls down and shows it again on scroll up. |
| Tab 1–5: Show this tab | Shows or hides the tab. |
| Tab 1–5: Tab label | Leave blank to use the translated default for the tab's icon. |
| Tab 1–5: Icon | Home, Search, Cart, Account, Heart, Menu, Phone, Email, Map pin, Info, Question, Chevron right or Arrow right. |
| Tab 1–5: Link | Leave blank to use the default action: the Search tab opens search, the Cart tab opens the cart and the Account tab opens the customer account. |

## Newsletter popup

{% include figure.html src="theme-settings/newsletter-popup" alt="The newsletter popup over the Lintel home page with a heading, short text, an email field, a Subscribe button and No thanks" caption="The newsletter popup." %}

| Setting | Description |
| --- | --- |
| Show popup | Turns the popup on. |
| Heading, Text, Image, Button label, Success message | Popup content. |
| Trigger | **Time delay**, **Scroll depth** or **Either delay or scroll**. |
| Delay before showing | Seconds before the popup appears (time delay). |
| Scroll depth (%) | Page scroll percentage that triggers the popup. |
| Days before showing again | How long the popup stays hidden after a shopper closes it. |
| Show "No thanks" link | Adds a link to dismiss the popup. |

Sign-ups are added to your Shopify customers as email subscribers, like the Newsletter section.

## Cookie consent

{% include figure.html src="theme-settings/cookie-consent" alt="The cookie banner along the bottom of the Bisque home page with Reject all, Manage preferences and Accept all buttons" caption="The cookie banner, shown to visitors in regions where Shopify asks for consent." %}

| Setting | Description |
| --- | --- |
| Show banner | Shows a consent banner driven by Shopify's Customer Privacy API. |
| When to show the banner | **Auto (geo-based)** shows it only to visitors in regions where consent is required. **Always show** shows it to every visitor on their first visit. |
| Banner position | **Bottom bar (full width)** or **Bottom-left card**. |
| Banner message | Leave blank to use the translated default. |
| Cookie / privacy policy page | Optional page linked from the banner. |
| Show "Reject all" button | Required in the EU and recommended elsewhere. |

<div class="callout">
<p>The banner helps you collect consent, but you are responsible for your store's privacy compliance. Review Shopify's <strong>Settings &gt; Customer privacy</strong> as well.</p>
</div>
