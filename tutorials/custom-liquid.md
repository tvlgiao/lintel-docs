---
layout: default
title: Add a Custom Liquid section or block
permalink: /tutorials/custom-liquid/
lead: Insert your own HTML, Liquid or a third-party embed code on any page, without editing theme files.
---

<div class="callout">
<p><strong>Support status:</strong> The <strong>Custom Liquid</strong> section and the <strong>Custom Liquid</strong> blocks are part of Lintel and are supported. The code you paste into them is your own; we can't write, debug or maintain it. For complex features, hire a <a href="https://www.shopify.com/partners/directory">Shopify Partner</a>.</p>
</div>

<div class="callout callout--warn">
<p><strong>Duplicate your theme first.</strong> In <strong>Online Store &gt; Themes</strong>, select <strong>⋯ &gt; Duplicate</strong> and test your code on the copy. Broken HTML in a Custom Liquid field can break the layout of the page it's on.</p>
</div>

## Where you can add custom Liquid

- **Custom Liquid section:** add it to any page with **Add section > Custom Liquid**. It has one setting, **Liquid**.
- **Custom Liquid block:** available in the **Product**, **Featured product**, **Collection**, **Cart** and **Article** sections, so you can place code between other blocks, for example under the add to cart button.

## Add a Custom Liquid section

1. In the theme editor, open the page where you want the code.
2. Select **Add section** and choose **Custom Liquid**.
3. Paste your code in the **Liquid** field.
4. Drag the section to where you want it, then select **Save**.

## Example: a shipping message on product pages

In a product template, add a **Custom Liquid** block to the Product section and paste:

{% raw %}
```liquid
{% if product.tags contains 'made-to-order' %}
  <p>Made to order. Ships in 4–6 weeks.</p>
{% endif %}
```
{% endraw %}

Tag your made-to-order products with `made-to-order`, and the message appears only on those products.

## Example: embed a third-party widget

Paste the embed code the service gives you (for example a booking or chat widget) into a Custom Liquid section. If the service offers a Shopify app with app blocks, prefer the app: app blocks are easier to manage and are removed cleanly when you uninstall the app.

## Good practice

- Keep the code short. Larger features belong in an app or a custom section built by a developer.
- Write text in your own words, and add `alt` text to any image.
- Don't load scripts you don't trust; they run on every visit to that page.
- After a theme update, check pages with custom code.
