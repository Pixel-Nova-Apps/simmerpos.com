---
layout: page
title: Changelog
include_in_header: true
---

<!-- # Up next

<div class="changelog">

<div class="feature-release up-next">
  <div class="date">Soon!</div>
  <h2>Online orders</h2>

  <p>Simmer will soon support online orders. This will allow you to create tickets from your online store and have them show up in the Simmer extension, on KDS and print to your printer.</p>

  <p>Please email <a href="mailto:help@simmerpos.com">help@simmerpos.com</a> if you'd like early access or to be notified when this feature is released.</p>
</div>

</div> -->

# Changelog

<div class="changelog">

  <div class="changelog-item">
    <div class="date">Nov 12</div>
    <h2>Ticket improvements</h2>
    <p>The sent at date now appears on all printed tickets regardless of ticket method (e.g takeout).</p>
  </div>

  <div class="changelog-item">
    <div class="date">Nov 11</div>
    <h2>Completion of hosting migration</h2>
    <p>Simmer has moved to a new hosting provider to increase performance and scalability of the app. This was a pretty big undertaking, took multiple weeks of planning and was managed with zero downtime. Back to building features!</p>
  </div>

  <div class="changelog-item">
    <div class="date">Oct 27</div>
    <h2>Printed ticket line item grouping</h2>
    <p>There's now an option to group line items on the printed tickets. E.g 4 x Flat white. The grouping is done when the variant and modifiers match. To enable this go to the Simmer admin then Displays and printers. There's now a "Group line items" checkbox for each printer.</p>
  </div>

  <div class="changelog-item">
    <div class="date">Oct 14</div>
    <h2>Print multiple ticket copies</h2>
    <p>Added the ability to set the number of ticket copies to print. This is useful if you want to print multiple copies of a ticket from the same printer for different prep areas.</p>
  </div>

   <div class="changelog-item">
    <div class="date">Oct 13</div>
    <h2>Delivery method and pickup time on order notes</h2>
    <p>The delivery method and pickup time are now added to the order notes in the Simmer POS extension.</p>
  </div>

   <div class="changelog-item">
    <div class="date">Oct 12</div>
    <h2>Print multiple ticket copies</h2>
    <p>Added the ability to set the number of ticket copies to print. This is useful if you want to print multiple copies of a ticket from the same printer for different prep areas.</p>
  </div>

   <div class="changelog-item">
    <div class="date">Oct 10</div>
    <h2>Fixes and improvements</h2>
    <p>If your internet connection is interupted Simmer will no longer wait 30 seconds to try again, it will do so after 10 seconds.</p>
    <p>Added a dedicated page with deep links to theme block installation within the Simmer admin.</p>
    <p>Updated billing page to allow activation of individual POS locations.</p>
    <p>Fixed issue with the Horizon theme and online ordering.</p>
    <p>Fixed issue with modifier selection and the Dawn theme.</p>
    <p>Added preventative measures for stopping $0 checkouts when bots try to purchase standalone modifiers.</p>
    <p>Fixed issue with min/max modifiers values. You can now set the min and max to the same value e.g when selecting a milk type for a coffee you can enforce a single selection.</p>
  </div>

  <div class="feature-release">
    <div class="date">Sept 12</div>
    <h2>⭐️ Customer displays 🚀</h2>
    <p>Customer displays are now available. This means your customers can view a screen to see when their order is ready.</p>
    <p>Go to 'Displays and printers' in the Simmer dashboard to find out more.</p>
  </div>

  <div class="changelog-item">
    <div class="date">Sept 11</div>
    <h3>Improvements to grid layout</h3>
    <p>Android devices will now show 5 items per row instead of 4. This is Android only because POS app can load full screen whereas on iOS they load within a modal/popup.</p>
  </div>

  <div class="feature-release">
    <div class="date">Sept 1</div>
    <h2>⭐️ Table management 🚀</h2>
    <p>Table management is now available. This allows you to manage table, buzzers and flags from within the Simmer dashboard.</p>
    <p>Tables are location aware, meaning you can have different tables for different locations.</p>
    <p>Tables can be grouped into different areas for example 'inside' and 'outside'.</p>
    <p>Go to 'Table management' in the Simmer dashboard to find out more.</p>
  </div>

  <div class="changelog-item">
    <div class="date">Aug 20</div>
    <h3>More speed improvements</h3>
    <p>The ticket screens and switching between product variants are now much faster.</p>
  </div>

  <div class="changelog-item">
    <div class="date">Aug 18</div>
    <h3>Out of stock modifiers</h3>
    <p>Modifiers will now show in red if out of stock and selecting them will show a warning banner.</p>
    <p>Go to 'Settings' in the Simmer dashboard and enable the 'Inventory checks' option.</p>
  </div>

  <div class="changelog-item">
    <div class="date">Aug 17</div>
    <h3>Bug fixes and tweaks</h3>
    <p>The search feature no longer shows duplicate results if products exist in multiple folders.</p>
    <p>Fixed a bug where apostrophes in variant titles were causing issues with the ticket page.</p>
    <p>Reversed the sort order on the KDS 'ready' tab to make it easier to find recently used tickets.</p>
  </div>

  <div class="changelog-item">
    <div class="date">Aug 13</div>
    <h3>Huge speed improvements</h3>
    <p>You may have noticed already but the app load times are now almost instant, same with switching folders and viewing products. This is due to a complete rewrite of the the way Simmer manages your products and folders. </p>
    <p>More improvements coming soon!</p>
  </div>

  <div class="feature-release">
    <div class="date">Aug 8</div>
    <h2>⭐️ Location aware product grids 🚀</h2>
    <p>Product grids are now location aware, meaning you can have different grids for different locations.</p>
    <p>To keep things simple, the default grid will be shared across all locations, and you can override each location with its own set of products and folders if needed.</p>
    <p>Go to 'Products and folders' in the Simmer dashboard to find out more.</p>
  </div>

  <div class="changelog-item">
    <div class="date">Aug 5</div>
    <h3>Kitchen display improvements</h3>
    <p>There's now a tab showing all tickets that are in the ready state. </p>
    <p>The kitchen display is now paginated so you can see up to 50 tickets on each page. This will improve the performance of the kitchen display.</p>
  </div>

  <div class="feature-release">
    <div class="date">Aug 3</div>
    <h2>⭐️ QR code scanning for dine-in tickets 🚀</h2>
    <p>Your customers can now scan a QR code at their table to place an order via your Shopify store. You'll need online store enabled for this feature to work.</p>
    <p>Go to 'Online Store' in the Simmer dashboard to find out more.</p>
  </div>

  <div class="changelog-item">
    <div class="date">Aug 1</div>
    <h3>Improved format of ticket titles</h3>
    <p>Ticket titles now include the Shopify order number to make it easier to look up orders placed via your online store.</p>
  </div>

  <div class="changelog-item">
    <div class="date">July 30</div>
    <h3>Better KDS error handling</h3>
    <p>When a KDS error occurs it will now show a more user-friendly error message and will automatically recover from the error. For example, if the Shopify API is offline it will warn you, but recover as soon as it's back.</p>
  </div>

  <div class="changelog-item">
    <div class="date">July 29</div>
    <h3>Out of stock warnings in POS</h3>
    <p>There's now an option to show out of stock warnings in the Simmer POS extension. This is useful if you want to prevent staff from adding out of stock products to a ticket.</p>
    <p>Go to 'Settings' in the Simmer dashboard and enable the 'Inventory checks' option.</p>
  </div>

<div class="feature-release">
  <div class="date">July 16</div>
  <h2>⭐️ Online orders are here - fully integrated with KDS and printing! 🚀</h2>

  <p>After months of development and three major iterations, we’ve finally nailed it and we couldn’t be more excited to share this with you!</p>

  <p>You can now receive online orders directly through your Shopify store and have them automatically appear as tickets on your Simmer Kitchen Display System (KDS) and print out on your connected printers. No manual entry, no missed orders, just seamless service from click to kitchen.</p>

  <p>Your customers will love it too. When they add a Simmer product to their cart, they’ll see a pickup option with a date and time picker built right in. It’s all the Shopify goodness you’re used to, now supercharged with Simmer’s smart order handling.</p>

  <p>To get started, head to the Simmer Admin and click on Online Store. Since this feature is hot off the press, just shoot us a quick email and we’ll activate it and walk you through setup.</p>

  <p>Let’s get those online orders flowing!</p>

</div>

<div class="changelog-item">
  <div class="date">June 12</div>
  <h3>Complete all items on KDS tickets</h3>
  <p>There's now an option on KDS to mark all items on a ticket as complete. This is useful if you have a large number of items on a ticket and want to mark them all as complete at once.</p>
</div>

<div class="changelog-item">
  <div class="date">June 11</div>
  <h3>Quick-add improvement</h3>
  <p>If there's no current ticket selected but you try rapidly adding items using the quick add feature it will now prevent you from accidentally creating multiple tickets.</p>
</div>

<div class="changelog-item">
  <div class="date">June 6</div>
  <h3>Returning to Simmer before checkout now remembers the current ticket</h3>
  <p>If you "Add to cart" from Simmer and then return to Simmer without checking out, the current ticket will now be remembered and you can continue adding items to the ticket.</p>
</div>

<div class="changelog-item">
  <div class="date">June 5</div>
  <h3>Modifiers block improvements</h3>
  <p>The modifiers block within the Shopify product page is now paginated to improve performance and to prevent merchants from running into modifier limits.</p>
</div>

<div class="changelog-item">
  <div class="date">May 27</div>
  <h3>Kitchen display ready button now optional</h3>
  <p>It is now possible to disable the ready button on a per kitchen display basis. You can do this by going to 'KDS and printers' in the Simmer dashboard and either editing or adding a new kitchen display.</p>
</div>

<div class="changelog-item">
  <div class="date">May 26</div>
  <h3>Folder pinning is now lockable</h3>
  <p>You can now lock the folder pinning setting so that it cannot be changed by staff. You can enable this by going to Simmer within the Shopify admin and then going to Settings.</p>
</div>

<div class="changelog-item">
  <div class="date">May 22</div>
  <h3>Ticket printing improvements</h3>
  <p>Ticket printing for very busy merchants (1000+ tickets per day) is now more reliable as the printer will now only receive 5 tickets per request to the server. This prevents the printer from running out of memory and acting erratically.</p>
</div>

<div class="changelog-item">
  <div class="date">May 21</div>
  <h3>Quick add products</h3>
  <p>It is now possible to add products to tickets from the product grid by tapping the product. This is a quick way to add items to the ticket without having to navigate to the product details screen.</p>
  <p>Go to 'Settings' in the Simmer dashboard and enable the 'Quick add' option.</p>
  <p>Quick adding will only work for products that have a single variant and no modifier options.</p>
</div>

<div class="changelog-item">
  <div class="date">May 16</div>
  <h3>Improved layout of Star Micronics printed tickets</h3>
  <p>The formatting of the Star Micronics printed tickets has been updated to match the Epson printer layout. You'll notice subtle differences in font size and spacing.</p>
</div>

<div class="changelog-item">
  <div class="date">May 15</div>
  <h3>Preserve customer assigned to cart</h3>
  <p>Simmer now preserves the customer assigned to the cart when adding tickets to the POS cart.</p>
</div>

<div class="changelog-item">
  <div class="date">May 7</div>
  <h3>Improved KDS login and fixed folder pinning bug</h3>
  <p>We've made it easier to log in to multiple KDS on the same device without getting "Incorrect PIN" errors. We've also fixed a bug where folder pinning was not working in certain cases.</p>
</div>

<div class="changelog-item">
  <div class="date">Apr 28</div>
  <h3>Checkboxes added to KDS</h3>
  <p>We've added a checkbox next to each item on KDS. This makes it easier to mark items as ready and discover the feature.</p>
</div>

<div class="changelog-item">
  <div class="date">Apr 24</div>
  <h3>Option to print new items only</h3>
  <p>It is now possible to only print new items on a ticket. To enable this go to 'KDS and printers' in the Simmer dashboard, and either edit or add a new printer, then select the option to only print new items.</p>
</div>

<div class="changelog-item">
  <div class="date">Apr 21</div>
  <h3>KDS improvements</h3>
  <p>KDS has been rewritten to be faster and more responsive. You'll no longer see the entire page refresh when you update a ticket or new tickets appear which reduces the chance of missing the "Ready" button and or when marking items as ready.</p>
</div>

<div class="changelog-item">
  <div class="date">Apr 18</div>
  <h3>Ticket auto-sending</h3>
  <p>In a step towards being able to accept online orders it is now possible to enable ticket auto-sending. This means that you no longer have to manually send tickets to KDS or printers and can auto-send upon payment completion. For businesses that accept payment after service this will not apply, and is an optional feature.</p>
</div>

<div class="changelog-item">
  <div class="date">Apr 17</div>
  <h3>Folder pinning</h3>
  <p>Folders can now be pinned as the main folder shown when you load Simmer. This allows businesses that offer different items at different times of a day a more refined workflow.</p>

  <p>You can pin and upin a folder by using the pin tile at the bottom of the product grid.</p>
</div>

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
