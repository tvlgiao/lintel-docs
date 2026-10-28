---
layout: default
title: Color schemes and dark mode
permalink: /colors/
lead: Every color in Lintel comes from a color scheme. Each scheme has a light palette and a dark palette, so dark mode works on every section.
---

## How color schemes work

Open **Theme settings > Colors**. Each preset includes six color schemes, and you can add, edit or remove schemes there. A scheme is a set of colors for text, backgrounds, buttons and accents. Sections and some features (the search overlay, the cart drawer) each use one scheme.

{% include figure.html src="colors/editor-colors" alt="The Colors panel in theme settings with the default mode, the light and dark switcher and six color scheme swatches" caption="Theme settings > Colors." %}

- **Default color scheme** is used by the page background, the cart drawer, search, and every section that has **Inherit global color scheme** turned on.
- To give a section its own colors, select the section, turn off **Inherit global color scheme**, then choose a **Color scheme**.

## Colors in a scheme

Each scheme has a **Light mode** and a **Dark mode** group with the same colors:

| Color | Used for |
| --- | --- |
| Background | Section background. In light mode you can also set a **Background gradient**. |
| Surface | Cards, panels and input fields that sit on the background. |
| Text | Headings and body text. |
| Secondary text | Captions, helper text and less important details. |
| Border | Dividers and field borders. |
| Accent / Accent hover | Links and highlights, and their hover state. |
| Button background / Button text | Primary buttons. |
| Outline button | Border and text of secondary buttons. |
| Focus ring | The ring around a control reached with the keyboard. If it has less than 3:1 contrast with the background or surface, Lintel uses the text color instead. |
| Sale badge / Sale badge text | Sale badges on products. |
| Rating star | Star ratings. |

<div class="callout"><p>Keep text readable. Aim for a contrast ratio of at least 4.5:1 between <strong>Text</strong> and <strong>Background</strong>, and between <strong>Button text</strong> and <strong>Button background</strong>, in both palettes.</p></div>

## Light and dark mode

<div class="shots">
{% include figure.html src="colors/home-light" alt="The Bisque home page in light mode" caption="Light mode." %}
{% include figure.html src="colors/home-dark" alt="The same Bisque home page in dark mode, with dark section backgrounds" caption="Dark mode." %}
</div>

| Setting | Description |
| --- | --- |
| Default mode | **Auto (system)** follows the shopper's device setting. **Light** or **Dark** shows that mode first. |
| Show light/dark switcher | Adds a light/dark button to the header and mobile menu. The shopper's choice is remembered on their device. With the switcher off, every shopper sees the default mode. |

When the storefront is in dark mode, every section switches to the **Dark mode** palette of its scheme. Images aren't changed, so check that logos and images with transparent backgrounds look good on both palettes. You can upload a separate logo for small screens in **Theme settings > Logo**.

## Tips

- Start from the preset's schemes and change one or two colors at a time.
- Use one scheme for most sections and one or two contrasting schemes for emphasis, such as a newsletter band.
- Preview dark mode in the theme editor by setting **Default mode** to **Dark** temporarily, or by using the switcher on the preview.
