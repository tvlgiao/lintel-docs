---
layout: default
title: Edit theme code files
permalink: /tutorials/edit-theme-code/
lead: How to make a code change safely, and what it means for support and updates.
---

<div class="callout callout--warn">
<p><strong>Support status: not supported.</strong> Changes to theme code files are outside our support policy. We can't help with themes whose code has been changed, beyond pointing you to the original file. For code changes, we recommend hiring a <a href="https://www.shopify.com/partners/directory">Shopify Partner</a>.</p>
</div>

## Before you start

1. **Duplicate the theme.** In **Online Store > Themes**, select **⋯ > Duplicate** on Lintel. Edit the copy, never your live theme.
2. **Check whether a setting already does it.** See [Theme settings]({{ '/theme-settings/' | relative_url }}), [Custom CSS]({{ '/tutorials/custom-css/' | relative_url }}) and [Custom Liquid]({{ '/tutorials/custom-liquid/' | relative_url }}). These survive theme updates; code edits don't.
3. **Reword text without code** in **⋯ > Edit default theme content**.

## Open the code editor

1. In **Online Store > Themes**, on your duplicated theme, select **⋯ > Edit code**.
2. Files are grouped into folders such as **layout**, **sections**, **snippets**, **assets**, **config** and **locales**.
3. After editing, select **Save**. Each file keeps a version history: select **Older versions** at the top of the file to roll back.

## Example: change a storefront word

You don't need code for this. Use **Edit default theme content** instead of editing files in the **locales** folder; that change survives theme updates.

## Updating a theme with code changes

When you update Lintel from the theme library, Shopify creates a new copy of the latest version with your theme settings and content. **Code edits are not carried over.** Keep a list of every file you changed, and what you changed, so you or your developer can apply the changes again.

## Getting back to the original

If something breaks, publish your untouched original theme from the theme library, or add a fresh copy of Lintel from the Theme Store.
