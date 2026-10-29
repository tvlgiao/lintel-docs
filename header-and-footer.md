---
layout: default
title: Header and footer
permalink: /header-and-footer/
lead: The announcement bar, header, mega menus, mobile navigation and footer.
---

## Announcement bar

The Announcement bar section sits in the header group. Add one **Announcement** block per message (Text, Link, Open link in a new tab).

{% include figure.html src="theme-settings/announcement-bar" alt="The announcement bar above the Savile header with the text Made in a small circle of mills and a close button" caption="The announcement bar above the header." %}

| Setting | Description |
| --- | --- |
| Show | Shows or hides the bar. The bar appears only when it has at least one Announcement block. |
| Auto-rotate announcements | Moves to the next announcement automatically. |
| Rotation speed (seconds) | Time each announcement stays on screen. |
| Show previous / next arrows | Lets shoppers move between announcements. |
| Allow visitors to dismiss | Adds a close button. |
| Accessibility label | Name read by screen readers for the announcement region. |

## Header

Choose the menu in **Menu** (create menus in **Online Store > Navigation**).

{% include figure.html src="header-and-footer/header" alt="Lintel header: logo on the left, menu in the centre, theme mode, search, account and cart icons on the right" caption="The header on a desktop screen." %}

{% include figure.html src="header-and-footer/mega-menu" alt="The Shop menu open as a dropdown below the header on the Products page" caption="A menu item with child links opens a dropdown." %}

| Setting | Description |
| --- | --- |
| Layout mode | **Balanced** or **Logo centered**. |
| Logo width (px) / Logo height (px) | Maximum logo size on desktop. The logo keeps its aspect ratio; the height also sets the header height. |
| Logo width, mobile (px) / Logo height, mobile (px) | Maximum logo size on mobile. |
| Show country/region selector | Appears only when your store sells in more than one country. |
| Show language selector | Appears only when your store has more than one language. |

More header options (transparent header, sticky header, search style, cart count) are in **Theme settings > Header**. See [Theme settings]({{ '/theme-settings/#header' | relative_url }}).

### Mega menu

Add a **Mega menu** block to the header to turn a top-level menu item into a large dropdown panel.

| Setting | Description |
| --- | --- |
| Menu item trigger | The exact text of the top-level menu item that opens this mega menu. Matching ignores upper and lower case. |
| Mega menu link list | Optional. Overrides the menu item's child links for the panel columns. |
| Show thumbnails | Shows the linked collection or product image next to each link. |
| Promotional image, Image ratio, Promotional heading, Promotional subheading, Promotional link, Promotional button label | A promotional banner inside the panel. |
| Featured collection, Number of products | Products shown inside the panel. |

Add one Mega menu block for each top-level item that should open a panel. Other menu items open a standard dropdown.

## Mobile navigation bar

On phones, Lintel can show a fixed bar at the bottom of the screen with up to five tabs. Set it up in **Theme settings > Navigation**. See [Theme settings]({{ '/theme-settings/#navigation' | relative_url }}).

<div class="shots">
{% include figure.html src="header-and-footer/mobile-menu" alt="The mobile menu drawer with collections, pages, a theme switch, account and cart" caption="The mobile menu drawer." mobile=true %}
{% include figure.html src="index/home-lintel-mobile" alt="A phone screen with the bottom navigation bar: Home, Search, Cart and Account" caption="The mobile navigation bar along the bottom." mobile=true %}
</div>

## Footer

The footer is built from blocks, each one a column.

{% include figure.html src="header-and-footer/footer" alt="Lintel footer with brand text, social icons, link columns, a contact column, payment icons and Powered by Shopify" caption="The footer with its brand text, menus and payment icons." %}

| Block | Settings |
| --- | --- |
| Menu column | Heading, Menu, Collapse on mobile, Column width (desktop) |
| Links list | Heading, Collapse on mobile, Column width (desktop), and **Link** blocks (Label, Link) |
| Text column | Render shop name as brand logo, Heading, Text, Show social media icons inside this column, Show Follow on Shop button, Column width (desktop) |
| Image | Image, Image width, Alt text, Link, Column width (desktop) |
| Call to action | Heading, Text, Button label, Button link, Button style, Column width (desktop) |
| Newsletter | Heading, Newsletter text, Column width (desktop) |

Footer section settings:

| Setting | Description |
| --- | --- |
| Content alignment | **Left** or **Center**. |
| Desktop column layout | **Brand-weighted**, **Equal width** or **Auto-fit**. |
| Block spacing | **Compact**, **Comfortable** or **Spacious**. |
| Mobile menu style | **Accordion**, **Two-column grid** or **Stacked**. |
| Show divider above bottom bar | Adds a line above the bottom bar. |
| Show copyright, Custom copyright text | The copyright line. |
| Show social media links | Uses the accounts in **Theme settings > Social media**. |
| Show payment icons | Shows the payment methods enabled in your store. |
| Show country/region selector, Show language selector | Localization selectors in the bottom bar. |
| Bottom bar layout | **Spread**, **Centered** or **Stacked**. |
