---
layout: default
title: Add custom CSS in the theme editor
permalink: /tutorials/custom-css/
lead: Change how something looks without editing theme files, using Shopify's Custom CSS fields.
---

<div class="callout">
<p><strong>Support status:</strong> The Custom CSS fields are a Shopify feature that works with Lintel and is supported. The CSS you write is your own; we can't write or debug it for you. For complex styling work, hire a <a href="https://www.shopify.com/partners/directory">Shopify Partner</a>.</p>
</div>

<div class="callout callout--warn">
<p><strong>Duplicate your theme first.</strong> In <strong>Online Store &gt; Themes</strong>, select <strong>⋯ &gt; Duplicate</strong> and try your CSS on the copy.</p>
</div>

## Where to add CSS

Shopify adds two **Custom CSS** fields to the theme editor:

- **For one section:** select the section, scroll to the bottom of its settings and open **Custom CSS**. The CSS applies to that section only.
- **For the whole store:** open **Theme settings** and find **Custom CSS**. The CSS applies to every page.

Custom CSS stays in place when you update the theme.

## Example: hide the eyebrow text in one section on mobile

Select a **Rich text** section and add this to its Custom CSS:

```css
@media (max-width: 749px) {
  .eyebrow { display: none; }
}
```

In a section's Custom CSS field, Shopify scopes your rules to that section, so other sections aren't affected. Some CSS, such as `@import` and `@font-face`, isn't allowed in these fields, and each field has a size limit.

## Example: larger product titles on cards

Add this to the **Theme settings** Custom CSS:

```css
.product-card__title {
  font-size: 1.125rem;
}
```

## Find the right selector

1. Open your store in Chrome, Edge, Firefox or Safari.
2. Right-click the element and choose **Inspect**.
3. Look at the class names on the element and use one in your rule.

Class names can change between theme versions. After updating Lintel, check that your custom CSS still works.

## Keep it accessible

- Don't remove the focus ring (`outline`) from links and buttons; keyboard users need it.
- Don't hide content with `display: none` if shoppers still need it on that screen size.
- Check text contrast if you change colors. Most color changes are better made in [color schemes]({{ '/colors/' | relative_url }}).
