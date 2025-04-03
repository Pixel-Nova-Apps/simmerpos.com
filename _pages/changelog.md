---
layout: page
title: Changelog
include_in_header: true
---

# Up next

<div class="changelog">

<div class="feature-release up-next">
  <div class="date">Soon!</div>
  <h2>Online orders</h2>

  <p>Simmer will soon support online orders. This will allow you to create tickets from your online store and have them show up in the Simmer extension, on KDS and print to your printer.</p>

  <p>Please email <a href="mailto:help@simmerpos.com">help@simmerpos.com</a> if you'd like early access or to be notified when this feature is released.</p>
</div>

</div>

# Changelog

<div class="changelog">

<div class="changelog-item">
  <div class="date">Apr 3</div>
  <h3>Staff attribution and minor improvements</h3>
  <p>There's now an option to set staff attribution to line items added to the POS cart via Simmer. You can do this by going to the Simmer Admin app then Settings.</p>

  <p>Minor improvements to the way Simmer handles Shopify API outages and errors.</p>

  <p>We are still working on the online store feature!</p>
</div>

<div class="changelog-item">
  <div class="date">Mar 9</div>
  <h3>Search improvements, tiles and ticket screen updates</h3>
  <p>The search feature now has the option to search by products assigned to Simmer collections or your entire Shopify store. The default is to only search Simmer collections as this was the most common request.</p>

  <p>Grid tiles in Simmer can now show multiple lines of text. This will allow products with longer names to be displayed more clearly.</p>

  <p>The total ticket price is now displayed on the ticket screen in addition to the ticket preview.</p>
</div>

<div class="changelog-item">
  <div class="date">Feb 28</div>
  <h3>Total ticket price and component updates</h3>

  <p>You'll now be able to see the total ticket price on the current ticket preview on the main screen.</p>

  <p>We've also updated the POS components to use the latest Shopify UI library. You'll notice a few slight visual changes.</p>
</div>

<div class="changelog-item">

  <div class="date">Feb 21</div>
  <h3>Workflow improvements</h3>

  <p>It is now possible to create a ticket directly from the main screen. If there is no current ticket you will see a button to <strong>Create ticket</strong>.</p>

  <p>And there's now a direct link from the current ticket shown on the main grid to the ticket details screen which means you can now add the ticket name or table number within a single tap.</p>

  <p>We've also improved the way the ticket information is displayed on the main screen.</p>
</div>

<div class="changelog-item">
  <div class="date">Feb 12</div>
  <h3>Barcode scanning</h3>

  <p>You can now scan barcodes from any screen and it will take you to the matching product. If you don't have a barcode scanner you can use the device camera to scan barcodes by going to the <strong>search tile</strong>, then clicking <strong>scan</strong>.</p>
</div>

<div class="changelog-item">
  <div class="date">Feb 11</div>
  <h3>Print locally using AirPrint on iOS or system print dialog on Android</h3>

  <p>Simmer now supports the new Shopify POS Print API which allows printing to local AirPrint (iOS) or system print dialog (Android) printers. To add a local printer go to the <strong>KDS and printers</strong> section in the Simmer dashboard, select <strong>Add printer</strong> and select the printer type <strong>Local printer (iOS/Android)</strong>.</p>
</div>

<div class="feature-release">
  <div class="date">Feb 10</div>
  <h2>⭐️ New feature: Printer and KDS filtering 🚀</h2>

  <p>You can now filter which products are printed to each printer or displayed on each KDS. If you have a kitchen and bar printer you can tag products as 'kitchen' or 'bar' and they will only be printed to the relevant printer. Same with KDS.</p>

  <p>To set this up go to 'KDS and printers' in the Simmer dashboard, and either edit or add a new printer or KDS, then select the tags you want to filter by.</p>
</div>

<div class="changelog-item">
  <div class="date">Feb 3</div>
  <h3>Add to cart performance improvements</h3>

  <p>Simmer now uses a new Shopify API for adding items to the POS cart. This will massively improve the performance of adding items to the cart, especially when there are a large number of products.</p>
</div>

<div class="changelog-item">
  <div class="date">Jan 21</div>
  <h3>Kitchen display item status & printed ticket improvements</h3>

  <p>You can now mark each item on a ticket as ready by clicking the item title. This will put a line through the item so you can easily see which items are ready.</p>

  <p>The printed ticket now has additional space at the top for ticket holders.</p>
</div>

<div class="changelog-item">
  <div class="date">Jan 20</div>
  <h3>Star Micronics printer support</h3>

  <p>Simmer now supports Star Micronics printers with CloudPRNT. Learn how to set up your Star Micronics printer <a href="/printer-star">here</a>.</p>
</div>

<div class="changelog-item">
  <div class="date">Jan 18</div>
  <h3>Minor fixes</h3>

  <p>Minor bug fix on the Admin product block where all products were being displayed if there were no products in the modifiers collection.</p>

  <p>Tweak to the 'copy' button in the Admin app where it now display a message if copying is not supported by your browser.</p>
</div>

<div class="changelog-item">
  <div class="date">Jan 14</div>
  <h3>Support improvements & UI tweaks</h3>

  <p>Simmer's support email address is now help@simmerpos.com. Please update your records.</p>

  <p>The KDS now displays an empty state when there are no tickets in the kitchen and minor improvement to the way folders are displayed in the Admin.</p>
</div>

<div class="changelog-item">
  <div class="date">Jan 13</div>
  <h3>Workflow improvements</h3>

  <p>Happy New Year! 🎉</p>

  <p>It's now possible to view the current ticket from the product screen. From the product screen click <strong>View</strong> in the ticket section to quickly view the current ticket, the back button will take you back to the product screen.</p>

  <p>Note that you'll only be able to view the current ticket if there is a ticket open.</p>
</div>

<div class="changelog-item">
  <div class="date">Dec 28</div>
  <h3>Apostrophe in product title fix</h3>

  <p>Fixed a bug where an apostrophe in a product title would cause an issue where it would not be possible to add the product to the ticket.</p>
</div>

<div class="changelog-item">
  <div class="date">Dec 23</div>
  <h3>Ticket creation double tap fix</h3>

  <p>It was possible to create multiple tickets by double tapping the <strong>Create ticket</strong> button. This has been fixed as Simmer now disables the button after it has been clicked once.</p>
</div>

<div class="feature-release">
  <div class="date">Dec 17</div>
  <h2>⭐️ New feature: Product grid folders 🚀</h2>

  <p>You can now create folders in the product grid. This allows you to group products together and make it easier to find them.</p>

  <p>To create folders, visit the Simmer Dashboard and select <strong>Add a folder</strong>. This will create collection within Shopify that you can use to assign products to.</p>

  <p>Folders will be displayed at the top of the product grid.</p>
</div>

<div class="changelog-item">
  <div class="date">Dec 16</div>
  <h3>Ticket and KDS UI tweaks and fixes</h3>

  <p>The layout of the ticket information has been improved. The ticket name/table number is now shown in the title bar and the ticket information is now shown in a more readable format.</p>

  <p>Fixed a UI glitch where a an empty bullet point was showing in the KDS display for single variant products.</p>
</div>

<div class="feature-release">
  <div class="date">Dec 15</div>
  <h2>⭐️ New feature: Ticket printing 🚀</h2>

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

<div class="changelog-item">
  <div class="date">Dec 13</div>
  <h3>Ticket status renamings and KDS ticket time</h3>

  <p><strong>Closed</strong> ticket status has been renamed to <strong>Paid</strong>. It is now possible to have <strong>Paid</strong> but incomplete tickets that are in the <strong>Sent</strong> or <strong>Ready</strong> kitchen status.</p>

  <p>We've added the ticket time to the KDS display. You can now see the time the ticket was sent to the kitchen screen.</p>
</div>

<div class="changelog-item">
  <div class="date">Dec 10</div>
  <h3>Bug fixes</h3>

  <p>Fixed a bug where single variant modifiers were not being displayed on the modifier App Block within Shopify Admin.</p>
</div>

<div class="changelog-item">
  <div class="date">Nov 25</div>
  <h3>Improved ticket status updates</h3>

  <p>Ticket status updates are now faster due to an improved API call.</p>
</div>

<div class="changelog-item">
  <div class="date">Nov 19</div>
  <h3>Modifier fix</h3>

  <p>Fixed a bug where modifiers were not always being displayed in desired order.</p>
</div>

<div class="changelog-item">
  <div class="date">Nov 18</div>
  <h3>Improvements and fixes</h3>

  <p>You can now see modifier pricing (e.g +$1.00) on the product screen.</p>

  <p>The POS tile can now be added directly from POS (previously it was only possible from the Admin).</p>
</div>

<div class="changelog-item">
  <div class="date">Nov 15</div>
  <h3>Product screen bug fix</h3>

  <p>Fixed a bug where having a large number of variants would disapear off the screen. They now wrap to the next line.</p>
</div>

<div class="changelog-item">
  <div class="date">Nov 14</div>
  <h3>Workflow improvements</h3>

  <p>Simmer will now automatically create a new ticket if no current ticket is selected. This will save time if you forget to create a new ticket before trying to add a product.</p>

  <p>When you click <strong>add to cart</strong> Simmer will only show the confirmation modal if there are products already in the cart. And you now have the option to clear the cart or leave the cart as is.</p>

  <p>🙏 We really appreciate all the feedback we've received from merchants. Please keep it coming! </p>
</div>

<div class="feature-release">
  <div class="date">Nov 7</div>
  <h2>⭐️ New feature: Kitchen Displays (KDS) 🚀</h2>

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

<div class="changelog-item">
  <div class="date">Oct 3</div>
  <h3>Ticket filters</h3>

  <p>Added filters to the Tickets screen to keep the open tickets screen cleaner. There are now three filters: Open, Closed and Canceled.</p>
</div>

<div class="changelog-item">
  <div class="date">Oct 2</div>
  <h3>Simmer is born!</h3>

  <p>Hello world!</p>
</div>

</div>
