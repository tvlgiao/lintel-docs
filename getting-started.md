---
layout: default
title: Getting started
permalink: /getting-started/
lead: Install Lintel, pick a preset and find your way around the theme editor.
---

## Install the theme

1. In your Shopify admin, go to **Online Store > Themes**.
2. Open the Shopify Theme Store page for Lintel and select **Try theme** to preview it in your store, or **Buy theme** to purchase it.
3. Choose one of the four presets: **Lintel**, **Bisque**, **Neroli** or **Savile**. The theme is added to your theme library as an unpublished theme.
4. Select **Customize** to open the theme editor and set up your store.
5. When you're ready, select **Publish** from the theme library.

<div class="callout">
<p>Before you publish, keep your current theme in the theme library. You can switch back at any time from <strong>Online Store &gt; Themes</strong>.</p>
</div>

## Choose a preset

Every preset contains all of Lintel's features and the same page templates. Presets differ in theme settings: color schemes, heading and body fonts, button style, page margins, product image ratios and a few defaults such as the sale badge style. You can change any of these after installing, so pick the preset whose look is closest to your brand. The demo stores show each preset with its own sample content.

| Preset | Demo store |
| --- | --- |
{%- for store in site.demo_stores %}
| {{ store.name }} | [{{ store.url | remove: 'https://' }}]({{ store.url }}) |
{%- endfor %}

To switch presets later, add the theme again from the Theme Store and choose another preset. Your settings and content aren't copied between themes.

## The theme editor

The theme editor (**Online Store > Themes > Customize**) has three areas:

- **Sections** (left sidebar): the sections and blocks on the page you're viewing. Use the page selector at the top to edit other templates, such as a product page or a collection page.
- **Settings** (right sidebar): the settings of the section or block you selected.
- **Theme settings** (the paint brush icon): global settings that apply to the whole store.

Sections are grouped as follows:

- **Header** group: the announcement bar and the header.
- **Template**: the main content of the page, such as the product section on a product page.
- **Footer** group: the footer.

Select **Add section** to insert any of Lintel's sections. See [Sections]({{ '/sections/' | relative_url }}) for the full list.

## Theme settings groups

Theme settings are organized into these groups. Each one is described on the [Theme settings]({{ '/theme-settings/' | relative_url }}) page.

| Group | What it controls |
| --- | --- |
| Logo | Logo image, favicon, mobile logo, logo text and default social media image |
| SEO | Home page and default meta descriptions |
| Colors | Light and dark mode, the default color scheme and the color schemes |
| Typography | Heading and body fonts, heading size and spacing, body line height |
| Layout | Maximum page width and minimum page margin |
| Buttons | Button radius, padding, font size, uppercase text and letter spacing |
| Motion | Reveal-on-scroll animation and subtle transitions |
| Cart | Cart type (drawer or page), notes, recommendations, bundle suggestion, gift wrapping, free shipping threshold |
| Collection and search | Search overlay, predictive search and popular searches |
| Social media | Links to your social media accounts |
| Product cards | Image ratio, text alignment, row alignment and badges |
| Announcement bar | Default announcement text and link |
| Header | Transparent header, sticky header, search and cart icon options |
| Navigation | Mobile bottom navigation bar and its five tabs |
| Newsletter popup | Popup content, trigger and frequency |
| Cookie consent | Consent banner for Shopify's Customer Privacy API |

## Recommended setup order

1. **Logo** and **Colors** in theme settings.
2. **Header**: choose your menu and, if you like, add mega menus.
3. **Home page**: replace the preset images and text, remove sections you don't need.
4. **Product page**: open a product template and arrange the product blocks.
5. **Collection page**: set the layout and filters. Filters come from the Shopify Search & Discovery app.
6. **Cart**: choose drawer or page and set the free shipping threshold.
7. **Footer**: add menu columns, a newsletter column and social media links.
8. **Translations**: review the storefront text in **Online Store > Themes > ⋯ > Edit default theme content**.

## Theme updates

When a new version of Lintel is released, Shopify shows an update notice in your theme library. Updating creates a new copy of the theme with your settings and content carried over; edits you made to theme code files are not carried over. See the [release notes]({{ '/release-notes/' | relative_url }}).
