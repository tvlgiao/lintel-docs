---
layout: default
title: Cart
permalink: /cart/
lead: Choose between a cart drawer and a cart page, and set up notes, gift wrapping, recommendations and the free shipping bar.
---

## Cart drawer or cart page

In **Theme settings > Cart**, set **Cart type**:

{% include figure.html src="cart/cart-drawer" alt="The cart drawer open on the right with a product line, recommendations, discount code and note fields and a checkout button" caption="The cart drawer." %}

- **Drawer**: adding a product opens a side panel with the cart. Shoppers can change quantities, remove items and go to checkout without leaving the page.
- **Page**: adding a product takes the shopper to the cart page.

The cart page at `/cart` is always available, whichever type you choose.

## Cart drawer settings

These are in **Theme settings > Cart**:

| Setting | Description |
| --- | --- |
| Show vendor | Shows the product vendor on cart lines. |
| Show cart note | Adds a note field for special instructions. |
| Show recommendations | Shows a "You may also like" row of up to six products. Lintel uses the collection with the handle `cart-upsell`; create that collection to choose the products. Without it, products come from all products. |
| Delivery estimate | Text under each cart line, such as "Ships in 2–3 business days". |
| Show bundle suggestion in cart drawer | Shows Bundle heading, Bundle text and a link (Bundle link, Bundle link label). The theme doesn't apply a discount; create one in **Discounts** if your bundle has a price offer. |
| Show gift wrapping option in cart drawer | A checkbox that adds the cart attribute "gift_wrap: yes" to the order. It doesn't add a charge. Turn it on only if you wrap orders. |
| Free shipping threshold | Shows a progress bar toward free shipping. |

## Free shipping progress bar

Set **Free shipping threshold** to the minimum order amount for free shipping, in your store's currency. For example, 50 in a USD store means $50.00. Shoppers paying in another currency see the amount converted at the current exchange rate, rounded up. Set it to 0 to hide the bar.

<div class="callout callout--warn"><p>The bar only shows progress. Free shipping itself must be set up in <strong>Settings &gt; Shipping and delivery</strong> or as a free shipping discount, with the same amount.</p></div>

## Cart page

Open the cart template in the theme editor (page selector **Cart**). The Cart section has these settings:

{% include figure.html src="cart/cart-page" alt="The Lintel cart page with a product line and an order summary with discount code, order note and checkout" caption="The cart page." %}

| Setting | Description |
| --- | --- |
| Show breadcrumb | Shows the breadcrumb trail. |
| Show free shipping progress bar | Shows the progress bar on the cart page. |
| Free shipping threshold | Leave at 0 to use the amount from Theme settings > Cart. |
| Show discount code input | Lets shoppers enter a discount code before checkout. |
| Show cart notes | Adds a note field. |
| Show accelerated checkout buttons | Shows dynamic checkout buttons such as Shop Pay, Apple Pay or PayPal, depending on your payment settings. |
| Show gift wrap toggle | Adds the cart attribute "gift_wrap: yes" to the order. |
| Show trust badges | Shows a row of reassurance messages. |
| Free shipping trust threshold | Text for the free shipping message in the trust row. |
| Returns window | Number of days for returns shown in the trust row. 0 hides it. |
| Show upsell products, Upsell collection, Products to show | Products suggested below the cart. |
| Empty cart message, Continue shopping URL | What shoppers see when the cart is empty. |

The cart page also accepts **Custom Liquid** blocks and app blocks.

## Subscriptions in the cart

Items bought with a subscription plan show the plan name in the cart drawer and on the cart page.
