---
layout: page
title: Online ordering
include_in_header: false
---

<nav class="breadcrumbs">
  <a href="/">Home</a> &gt; <a href="/support/">Support</a> &gt; Online store
</nav>

# Online store setup

## Enable online store within Simmer settings

From the Simmer Admin, navigate to **Settings** > **Online store**.

This feature is currently in beta and may not be available to all merchants. If you'd like access please email [help@simmerpos.com](mailto:help@simmerpos.com).

You'll receive an email once online store has been enabled for your account (usually within 12 hours).

## Add store opening times

From the Simmer Admin, navigate to **Online store** and add your store opening times by selecting each of your locations.

<img src="/assets/online/edit-opening-hours.png" alt="Store opening times" class="support-image">

## Add pickup shipping method

There are two different methods for adding a pickup shipping method to your Shopify store, depending on your Shopify plan.

### Shopify Plus merchants

There is a seperate guide for doing this, please contact [help@simmerpos.com](mailto:help@simmerpos.com) for more information.

### All other merchants

Non-plus merchants must create a custom shipping method and cannot make use of the built-in pickup shipping method. This is because non-Plus merchants don't have access to checkout extensions which are needed by Simmer to add a date picker, this must be done from the cart page instead.

From the Shopify Admin, navigate to **Settings** > **Shipping and delivery** and select the shipping profile that you want to add the pickup shipping method to, by default this is called **General shipping rates**.

<img src="/assets/online/shipping-delivery.png" alt="Add pickup shipping method" class="support-image">

Then click **Add rate**

<img src="/assets/online/add-rate.png" alt="Add rate" class="support-image">

Then enter a custom rate name, this must be called exactly **Pickup in store** and click **Done**. This is required for Simmer to identify the pickup shipping method.

<img src="/assets/online/rate-modal.png" alt="Rate modal" class="support-image">

Then click **Save** at the top of the page.

## Add products to the online store channel

Add your food and drink products to the online store channel.

<img src="/assets/online/online-store-sales-channel.png" alt="Add products" class="support-image">

## Add products to Simmer collections

You'll also need to add each of the food and drinks products to at least one of the Simmer collections. This helps Simmer know which are regular products and which are food and drinks so we can exclude them from postal shipping.

## Add modifier selection theme block to product page

Next you'll need to add the **Product Modifiers** block to the product page.

<div class="note-box">
You'll need to add the Product Modifiers block even if your products don't have any modifiers.
</div>

From the Shopify Admin, navigate to **Online Store** > **Themes** and select **Customize** for the theme you want to add the block to.

Then navigate to the **Product page** section.

<img src="/assets/online/theme-product-page.png" alt="Product page" class="support-image">

Add the **Simmer - Modifiers** block.

<img src="/assets/online/add-theme-block.png" alt="Add modifier selection block" class="support-image">

## Add delivery method and date picker to cart page

From the Shopify Admin, navigate to **Online Store** > **Themes** and select **Customize** for the theme you want to add the block to.

Then navigate to the **Cart page** section.

<img src="/assets/online/navigate-to-cart.png" alt="Navigate to cart page" class="support-image">

Then add the Simmer **Delivery Options** cart block to the **Subtotal** section of the cart page.

<img src="/assets/online/add-cart-block.png" alt="Add cart block" class="support-image">

## Limitations

### Buy it now

For non-Plus merchants, **buy it now** is not supported for online store orders as this bypasses the cart page and Simmer's delivery options.

### Drawer cart

For non-Plus merchants, drawer cart is not supported because it is not possible to add the Simmer delivery block to it.

<img src="/assets/online/cart-page.png" alt="Drawer cart" class="support-image">
