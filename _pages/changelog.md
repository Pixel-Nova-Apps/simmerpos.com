---
layout: page
title: Changelog
include_in_header: true
---

# Changelog

<div class="feature-release">
  <h2>⭐️ New Feature: Ticket printing - 12.14.2024 🚀</h2>

  <p><strong>Print tickets to the kitchen, bar and more!</strong></p>

  <p>Simmer currently supports the following printers with <strong>Server Direct Print</strong>:</p>

  <ul>
    <li>Epson TM-DT series</li>
    <li>Epson TM-i series</li>
    <li>Epson TM-T88VI</li>
  </ul>

  <h3>Coming soon:</h3>

  <ul>
    <li>Star Micronics printer support.</li>
    <li>Print directly to the POS connected printer.</li>
  </ul>

  <p>📖 View the <a href="/printer">printer support page</a> for more information.</p>
</div>

### 12.13.2024 - Ticket status renamings and KDS ticket time

The **Closed** ticket status has been renamed to **Paid**. It is now possible to have **Paid** but incomplete tickets that are in the **Sent** or **Ready** kitchen status.

We've added the ticket time to the KDS display. You can now see the time the ticket was sent to the kitchen screen. 

### 12.10.2024 - Bug fixes

Fixed a bug where single variant modifiers were not being displayed on the modifier App Block within Shopify Admin.

### 11.25.2024 - Improved ticket status updates

Ticket status updates are now faster due to an improved API call.

### 11.19.2024 - Modifier fix

Fixed a bug where modifiers were not always being displayed in desired order.

### 11.18.2024 - Improvements and fixes

You can now see modifier pricing (e.g +$1.00) on the product screen.

The POS tile can now be added directly from POS (previously it was only possible from the Admin).

### 11.15.2024 - Product screen bug fix

Fixed a bug where having a large number of variants would disapear off the screen. They now wrap to the next line.

### 11.14.2024 - Workflow improvements

Simmer will now automatically create a new ticket if no current ticket is selected. This will save time if you forget to create a new ticket before trying to add a product.

When you click **add to cart** Simmer will only show the confirmation modal if there are products already in the cart. And you now have the option to clear the cart or leave the cart as is.

We really appreciate all the feedback we've received from merchants. Please keep it coming!

<div class="feature-release">
  <h2>⭐️ New Feature: Kitchen Displays (KDS) - 11.07.2024 🚀</h2>

  <p><strong>Transform any device into a powerful kitchen display system!</strong></p>

  <p>You can now create kitchen displays from the Simmer dashboard! For V1 of kitchen displays we've focused on maximizing the range of devices that can be used. Kitchen displays will work on any device with a web browser including:</p>
  <ul>
      <li>📱 iPads</li>
      <li>💻 Chromebooks</li>
      <li>📺 Smart TVs</li>
      <li>💻 Laptops</li>
  </ul>

  <p>You'll also be able to create a POS tile using the Link feature.</p>

  <h3>Getting Started</h3>
  <ol>
      <li>Head to the Simmer dashboard</li>
      <li>Click <strong>Add display</strong></li>
      <li>Label your display and select the location</li>
  </ol>

  <p>📖 View the <a href="/kitchen-display">KDS support page</a> for more information.</p>
</div>

### 10.03.2024 - Ticket filters

Added filters to the Tickets screen to keep the open tickets screen cleaner. There are now three filters: Open, Closed and Canceled.

### 10.02.2024

Simmer is born!
