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
    <div class="date">January 2026</div>
    <ul>
      <li class="feature-release">
        <strong>⭐️ Default Modifiers 🚀</strong><br><br>
        <strong>Happy New Year! 🎉</strong><br>
        It is now possible set default modifier variants on products. These will be selected by default when the product loads in POS or the online store.<br>
        Checkout the updated 'Simmer: Modifiers' block within Shopify Admin 'Products' to see it in action.
      </li>
      <li>
        <strong>Add customer name to ticket name for online orders:</strong>
        The customer name is now included in the created Simmer ticket for online orders. <strong>Note</strong> this requires accepting the updated access scopes via Shopify Admin.
      </li>
      <li>
        <strong>Delivery Options theme block changes:</strong>
        <ul>
          <li>
            <strong>Auto-select location based on customer geolocation in online store:</strong>
            Delivery options can now be sorted and auto-selected based on the customer's device geolocation.<br>
            To make use of this feature you will need to enable it via the "Delivery Options" theme block settings and update your location opening hours.
          </li>
          <li>
            <strong>Delivery options available on Product templates:</strong>
            Delivery options can now be included in product templates as well as the cart template, giving merchants more flexibilty for their online store.
          </li>
        </ul>
      </li>
      <li>
        <strong>Modifier select theme block - Fix min/max required validations:</strong>
        The minimum and maximum modifier count validation is now correctly enforced, previously there were situations where it was possible to add products to the cart and ignore these limits.
      </li>
      <li>
        <strong>Sortable product modifiers:</strong>
        Added the ability to manually sort product modifier sets.<br>
        Go to the 'Simmer: Modifiers' block within Shopify Admin 'Products' to find out more.
      </li>
      <li>
        <strong>Minor speed improvements:</strong>
        Adding products to tickets is now no longer UI blocking, so you don't have to wait around for it to complete anymore.
      </li>
    </ul>

  </div>

  <div class="changelog-item">
    <div class="date">December 2025</div>
    <ul>
      <li class="feature-release">
        <strong>⭐️ Product folder sorting 🚀</strong><br><br>
        It is now possible to sort folders within the product grid via drag and drop.<br>
        Go to 'Products and folders' in the Simmer dashboard to find out more.
      </li>
      <li>
        <strong>Location based billing:</strong>
        Updated billing to ensure activation of individual POS locations on the device.
      </li>
      <li>
        <strong>Group line items by product tag:</strong>
        Line items on printed tickets can now be grouped by their product tags.
        Go to 'Displays and printers' in the Simmer dashboard to find out more.
      </li>
      <li>
        <strong>Fix folder unpin tile:</strong>
        The pinned folder feature was not showing the unpin folder tile in some situations.
      </li>
      <li>
        <strong>Show modifier min/max in POS:</strong>
        Minimum and maximum modifier advice is now shown on the POS to provide guidance when taking orders.
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">November 2025</div>
    <ul>
      <li>
        <strong>Group line items when printing:</strong>
        Similar line items can now be grouped on the printed tickets.<br>
        Go to 'Displays and printers' in the Simmer dashboard to find out more.
      </li>
      <li>
        <strong>Ticket improvements:</strong>
        The sent at date now appears on all printed tickets regardless of ticket method (e.g takeout).
      </li>
      <li>
        <strong>Completion of hosting migration:</strong>
        Simmer has moved to a new hosting provider to increase performance and scalability of the app. This was a pretty big undertaking, took multiple weeks of planning and was managed with zero downtime. Back to building features!
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">October 2025</div>
    <ul>
      <li>
        <strong>Printed ticket line item grouping:</strong>
        There's now an option to group line items on the printed tickets. E.g 4 x Flat white. The grouping is done when the variant and modifiers match. To enable this go to the Simmer admin then Displays and printers. There's now a "Group line items" checkbox for each printer.
      </li>
      <li>
        <strong>Print multiple ticket copies:</strong>
        Added the ability to set the number of ticket copies to print. This is useful if you want to print multiple copies of a ticket from the same printer for different prep areas.
      </li>
      <li>
        <strong>Delivery method and pickup time on order notes:</strong>
        The delivery method and pickup time are now added to the order notes in the Simmer POS extension.
      </li>
      <li>
        <strong>Print multiple ticket copies:</strong>
        Added the ability to set the number of ticket copies to print. This is useful if you want to print multiple copies of a ticket from the same printer for different prep areas.
      </li>
      <li>
        <strong>Fixes and improvements:</strong>
        <ul>
          <li>If your internet connection is interupted Simmer will no longer wait 30 seconds to try again, it will do so after 10 seconds.</li>
          <li>Added a dedicated page with deep links to theme block installation within the Simmer admin.</li>
          <li>Updated billing page to allow activation of individual POS locations.</li>
          <li>Fixed issue with the Horizon theme and online ordering.</li>
          <li>Fixed issue with modifier selection and the Dawn theme.</li>
          <li>Added preventative measures for stopping $0 checkouts when bots try to purchase standalone modifiers.</li>
          <li>Fixed issue with min/max modifiers values. You can now set the min and max to the same value e.g when selecting a milk type for a coffee you can enforce a single selection.</li>
        </ul>
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">September 2025</div>
    <ul>
      <li class="feature-release">
        <strong>⭐️ Customer displays 🚀</strong><br><br>
        Customer displays are now available. This means your customers can view a screen to see when their order is ready.<br>
        Go to 'Displays and printers' in the Simmer dashboard to find out more.
      </li>
      <li class="feature-release">
        <strong>⭐️ Table management 🚀</strong><br><br>
        Table management is now available. This allows you to manage table, buzzers and flags from within the Simmer dashboard.<br>
        Tables are location aware, meaning you can have different tables for different locations.<br>
        Tables can be grouped into different areas for example 'inside' and 'outside'.<br>
        Go to 'Table management' in the Simmer dashboard to find out more.
      </li>
      <li>
        <strong>Improvements to grid layout:</strong>
        Android devices will now show 5 items per row instead of 4. This is Android only because POS app can load full screen whereas on iOS they load within a modal/popup.
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">August 2025</div>
    <ul>
      <li class="feature-release">
        <strong>⭐️ Location aware product grids 🚀</strong><br><br>
        Product grids are now location aware, meaning you can have different grids for different locations.<br>
        To keep things simple, the default grid will be shared across all locations, and you can override each location with its own set of products and folders if needed.<br>
        Go to 'Products and folders' in the Simmer dashboard to find out more.
      </li>
      <li class="feature-release">
        <strong>⭐️ QR code scanning for dine-in tickets 🚀</strong><br><br>
        Your customers can now scan a QR code at their table to place an order via your Shopify store. You'll need online store enabled for this feature to work.<br>
        Go to 'Online Store' in the Simmer dashboard to find out more.
      </li>
      <li>
        <strong>More speed improvements:</strong>
        The ticket screens and switching between product variants are now much faster.
      </li>
      <li>
        <strong>Out of stock modifiers:</strong>
        Modifiers will now show in red if out of stock and selecting them will show a warning banner.<br>
        Go to 'Settings' in the Simmer dashboard and enable the 'Inventory checks' option.
      </li>
      <li>
        <strong>Table management:</strong>
        Table management is now available. This allows you to manage table, buzzers and flags from within the Simmer dashboard.<br>
        Tables are location aware, meaning you can have different tables for different locations.<br>
        Tables can be grouped into different areas for example 'inside' and 'outside'.<br>
        Go to 'Table management' in the Simmer dashboard to find out more.
      </li>
      <li>
        <strong>Bug fixes and tweaks:</strong>
        <ul>
          <li>The search feature no longer shows duplicate results if products exist in multiple folders.</li>
          <li>Fixed a bug where apostrophes in variant titles were causing issues with the ticket page.</li>
          <li>Reversed the sort order on the KDS 'ready' tab to make it easier to find recently used tickets.</li>
        </ul>
      </li>
      <li>
        <strong>Huge speed improvements:</strong>
        You may have noticed already but the app load times are now almost instant, same with switching folders and viewing products. This is due to a complete rewrite of the the way Simmer manages your products and folders. <br>
        More improvements coming soon!
      </li>
      <li>
        <strong>Kitchen display improvements:</strong>
        <ul>
          <li>There's now a tab showing all tickets that are in the ready state. </li>
          <li>The kitchen display is now paginated so you can see up to 50 tickets on each page. This will improve the performance of the kitchen display.</li>
        </ul>
      </li>
      <li>
        <strong>Improved format of ticket titles:</strong>
        Ticket titles now include the Shopify order number to make it easier to look up orders placed via your online store.
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">July 2025</div>
    <ul>
      <li class="feature-release">
        <strong>⭐️ Online orders are here - fully integrated with KDS and printing! 🚀</strong><br><br>
        After months of development and three major iterations, we've finally nailed it and we couldn't be more excited to share this with you!<br>
        You can now receive online orders directly through your Shopify store and have them automatically appear as tickets on your Simmer Kitchen Display System (KDS) and print out on your connected printers. No manual entry, no missed orders, just seamless service from click to kitchen.<br>
        Your customers will love it too. When they add a Simmer product to their cart, they'll see a pickup option with a date and time picker built right in. It's all the Shopify goodness you're used to, now supercharged with Simmer's smart order handling.<br>
        To get started, head to the Simmer Admin and click on Online Store. Since this feature is hot off the press, just shoot us a quick email and we'll activate it and walk you through setup.<br>
        Let's get those online orders flowing!
      </li>
      <li>
        <strong>Better KDS error handling:</strong>
        When a KDS error occurs it will now show a more user-friendly error message and will automatically recover from the error. For example, if the Shopify API is offline it will warn you, but recover as soon as it's back.
      </li>
      <li>
        <strong>Out of stock product warnings in POS:</strong>
        There's now an option to show out of stock warnings in the Simmer POS extension. This is useful if you want to prevent staff from adding out of stock products to a ticket.<br>
        Go to 'Settings' in the Simmer dashboard and enable the 'Inventory checks' option.
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">June 2025</div>
    <ul>
      <li>
        <strong>Complete all items on KDS tickets:</strong>
        There's now an option on KDS to mark all items on a ticket as complete. This is useful if you have a large number of items on a ticket and want to mark them all as complete at once.
      </li>
      <li>
        <strong>Quick-add improvement:</strong>
        If there's no current ticket selected but you try rapidly adding items using the quick add feature it will now prevent you from accidentally creating multiple tickets.
      </li>
      <li>
        <strong>Returning to Simmer before checkout now remembers the current ticket:</strong>
        If you "Add to cart" from Simmer and then return to Simmer without checking out, the current ticket will now be remembered and you can continue adding items to the ticket.
      </li>
      <li>
        <strong>Modifiers block improvements:</strong>
        The modifiers block within the Shopify product page is now paginated to improve performance and to prevent merchants from running into modifier limits.
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">May 2025</div>
    <ul>
      <li>
        <strong>Kitchen display ready button now optional:</strong>
        It is now possible to disable the ready button on a per kitchen display basis. You can do this by going to 'KDS and printers' in the Simmer dashboard and either editing or adding a new kitchen display.
      </li>
      <li>
        <strong>Folder pinning is now lockable:</strong>
        You can now lock the folder pinning setting so that it cannot be changed by staff. You can enable this by going to Simmer within the Shopify admin and then going to Settings.
      </li>
      <li>
        <strong>Ticket printing improvements:</strong>
        Ticket printing for very busy merchants (1000+ tickets per day) is now more reliable as the printer will now only receive 5 tickets per request to the server. This prevents the printer from running out of memory and acting erratically.
      </li>
      <li>
        <strong>Quick add products:</strong>
        It is now possible to add products to tickets from the product grid by tapping the product. This is a quick way to add items to the ticket without having to navigate to the product details screen.<br>
        Go to 'Settings' in the Simmer dashboard and enable the 'Quick add' option.<br>
        Quick adding will only work for products that have a single variant and no modifier options.
      </li>
      <li>
        <strong>Improved layout of Star Micronics printed tickets:</strong>
        The formatting of the Star Micronics printed tickets has been updated to match the Epson printer layout. You'll notice subtle differences in font size and spacing.
      </li>
      <li>
        <strong>Preserve customer assigned to cart:</strong>
        Simmer now preserves the customer assigned to the cart when adding tickets to the POS cart
      </li>
      <li>
        <strong>Improved KDS login and fixed folder pinning bug:</strong>
        We've made it easier to log in to multiple KDS on the same device without getting "Incorrect PIN" errors. We've also fixed a bug where folder pinning was not working in certain cases.
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">April 2025</div>
    <ul>
      <li>
        <strong>Checkboxes added to KDS:</strong>
        We've added a checkbox next to each item on KDS. This makes it easier to mark items as ready and discover the feature.
      </li>
      <li>
        <strong>Option to print new items only:</strong>
        It is now possible to only print new items on a ticket. To enable this go to 'KDS and printers' in the Simmer dashboard, and either edit or add a new printer, then select the option to only print new items.
      </li>
      <li>
        <strong>KDS improvements:</strong>
        KDS has been rewritten to be faster and more responsive. You'll no longer see the entire page refresh when you update a ticket or new tickets appear which reduces the chance of missing the "Ready" button and or when marking items as ready.
      </li>
      <li>
        <strong>Ticket auto-sending:</strong>
        In a step towards being able to accept online orders it is now possible to enable ticket auto-sending. This means that you no longer have to manually send tickets to KDS or printers and can auto-send upon payment completion. For businesses that accept payment after service this will not apply, and is an optional feature.
      </li>
      <li>
        <strong>Folder pinning:</strong>
        Folders can now be pinned as the main folder shown when you load Simmer. This allows businesses that offer different items at different times of a day a more refined workflow.<br>
        You can pin and upin a folder by using the pin tile at the bottom of the product grid.
      </li>
      <li>
        <strong>Staff attribution and minor improvements:</strong>
        There's now an option to set staff attribution to line items added to the POS cart via Simmer. You can do this by going to the Simmer Admin app then Settings.<br>
        Minor improvements to the way Simmer handles Shopify API outages and errors.<br>
        We are still working on the online store feature!
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">March 2025</div>
    <ul>
      <li>
        <strong>Search improvements, tiles and ticket screen updates:</strong>
        The search feature now has the option to search by products assigned to Simmer collections or your entire Shopify store. The default is to only search Simmer collections as this was the most common request.<br>
        Grid tiles in Simmer can now show multiple lines of text. This will allow products with longer names to be displayed more clearly.<br>
        The total ticket price is now displayed on the ticket screen in addition to the ticket preview.
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">February 2025</div>
    <ul>
      <li class="feature-release">
        <strong>⭐️ New feature: Printer and KDS filtering 🚀</strong><br><br>
        You can now filter which products are printed to each printer or displayed on each KDS. If you have a kitchen and bar printer you can tag products as 'kitchen' or 'bar' and they will only be printed to the relevant printer. Same with KDS.<br>
        To set this up go to 'KDS and printers' in the Simmer dashboard, and either edit or add a new printer or KDS, then select the tags you want to filter by.
      </li>
      <li>
        <strong>Total ticket price and component updates:</strong>
        You'll now be able to see the total ticket price on the current ticket preview on the main screen.<br>
        We've also updated the POS components to use the latest Shopify UI library. You'll notice a few slight visual changes.
      </li>
      <li>
        <strong>Workflow improvements:</strong>
        It is now possible to create a ticket directly from the main screen. If there is no current ticket you will see a button to <strong>Create ticket</strong>.<br>
        And there's now a direct link from the current ticket shown on the main grid to the ticket details screen which means you can now add the ticket name or table number within a single tap.<br>
        We've also improved the way the ticket information is displayed on the main screen.
      </li>
      <li>
        <strong>Barcode scanning:</strong>
        You can now scan barcodes from any screen and it will take you to the matching product. If you don't have a barcode scanner you can use the device camera to scan barcodes by going to the <strong>search tile</strong>, then clicking <strong>scan</strong>.
      </li>
      <li>
        <strong>Print locally using AirPrint on iOS or system print dialog on Android:</strong>
        Simmer now supports the new Shopify POS Print API which allows printing to local AirPrint (iOS) or system print dialog (Android) printers. To add a local printer go to the <strong>KDS and printers</strong> section in the Simmer dashboard, select <strong>Add printer</strong> and select the printer type <strong>Local printer (iOS/Android)</strong>.
      </li>
      <li>
        <strong>Add to cart performance improvements:</strong>
        Simmer now uses a new Shopify API for adding items to the POS cart. This will massively improve the performance of adding items to the cart, especially when there are a large number of products.
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">January 2025</div>
    <ul>
      <li><strong>Happy New Year! 🎉</strong></li>
      <li>
        <strong>Workflow improvements:</strong>
        It's now possible to view the current ticket from the product screen. From the product screen click <strong>View</strong> in the ticket section to quickly view the current ticket, the back button will take you back to the product screen.<br>
        Note that you'll only be able to view the current ticket if there is a ticket open.
      </li>
      <li>
        <strong>Kitchen display item status & printed ticket improvements:</strong>
        You can now mark each item on a ticket as ready by clicking the item title. This will put a line through the item so you can easily see which items are ready.<br>
        The printed ticket now has additional space at the top for ticket holders.
      </li>
      <li>
        <strong>Star Micronics printer support:</strong>
        Simmer now supports Star Micronics printers with CloudPRNT. Learn how to set up your Star Micronics printer <a href="/printer-star">here</a>.
      </li>
      <li>
        <strong>Minor fixes:</strong>
        <ul>
          <li>Minor bug fix on the Admin product block where all products were being displayed if there were no products in the modifiers collection.</li>
          <li>Tweak to the 'copy' button in the Admin app where it now display a message if copying is not supported by your browser.</li>
          <li>Simmer's support email address is now help@simmerpos.com. Please update your records.</li>
          <li>The KDS now displays an empty state when there are no tickets in the kitchen and minor improvement to the way folders are displayed in the Admin.</li>
        </ul>
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">December 2024</div>
    <ul>
      <li class="feature-release">
        <strong>⭐️ New feature: Product grid folders 🚀</strong><br><br>
        You can now create folders in the product grid. This allows you to group products together and make it easier to find them.<br>
        To create folders, visit the Simmer Dashboard and select <strong>Add a folder</strong>. This will create collection within Shopify that you can use to assign products to.<br>
        Folders will be displayed at the top of the product grid.
      </li>
      <li class="feature-release">
        <strong>⭐️ New feature: Ticket printing 🚀</strong><br><br>
        <strong>Print tickets to the kitchen, bar and more!</strong><br>
        Simmer currently supports the following printers with <strong>Server Direct Print</strong>:<br>
        <ul>
          <li>Epson TM-DT series</li>
          <li>Epson TM-i series</li>
          <li>Epson TM-T88VI</li>
        </ul>
        <strong>Coming soon:</strong><br>
        <ul>
          <li>Star Micronics printer support.</li>
          <li>Print directly to the POS connected printer.</li>
        </ul>
        📖 View the <a href="/printer">printer support page</a> for more information.
      </li>
      <li>
        <strong>Apostrophe in product title fix:</strong>
        Fixed a bug where an apostrophe in a product title would cause an issue where it would not be possible to add the product to the ticket.
      </li>
      <li>
        <strong>Ticket creation double tap fix:</strong>
        It was possible to create multiple tickets by double tapping the <strong>Create ticket</strong> button. This has been fixed as Simmer now disables the button after it has been clicked once.
      </li>
      <li>
        <strong>Ticket and KDS UI tweaks and fixes:</strong>
        The layout of the ticket information has been improved. The ticket name/table number is now shown in the title bar and the ticket information is now shown in a more readable format.<br>
        Fixed a UI glitch where a an empty bullet point was showing in the KDS display for single variant products.
      </li>
      <li>
        <strong>Ticket status renamings and KDS ticket time:</strong>
        <strong>Closed</strong> ticket status has been renamed to <strong>Paid</strong>. It is now possible to have <strong>Paid</strong> but incomplete tickets that are in the <strong>Sent</strong> or <strong>Ready</strong> kitchen status.<br>
        We've added the ticket time to the KDS display. You can now see the time the ticket was sent to the kitchen screen.
      </li>
      <li>
        <strong>Bug fixes:</strong>
        Fixed a bug where single variant modifiers were not being displayed on the modifier App Block within Shopify Admin.
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">November 2024</div>
    <ul>
      <li class="feature-release">
        <strong>⭐️ New feature: Kitchen Displays (KDS) 🚀</strong><br><br>
        <strong>Transform any device into a powerful kitchen display system!</strong><br>
        You can now create kitchen displays from the Simmer dashboard! For V1 of kitchen displays we've focused on maximizing the range of devices that can be used. Kitchen displays will work on any device with a web browser including:<br>
        <ul>
            <li>📱 iPads</li>
            <li>💻 Chromebooks</li>
            <li>📺 Smart TVs</li>
            <li>💻 Laptops</li>
        </ul>
        You'll also be able to create a POS tile using the Link feature.<br>
        <strong>Getting Started</strong><br>
        <ol>
            <li>Head to the Simmer dashboard</li>
            <li>Click <strong>Add display</strong></li>
            <li>Label your display and select the location</li>
        </ol>
        📖 View the <a href="/kitchen-display">KDS support page</a> for more information.
      </li>
      <li>
        <strong>Improved ticket status updates:</strong>
        Ticket status updates are now faster due to an improved API call.
      </li>
      <li>
        <strong>Modifier fix:</strong>
        Fixed a bug where modifiers were not always being displayed in desired order.
      </li>
      <li>
        <strong>Improvements and fixes:</strong>
        You can now see modifier pricing (e.g +$1.00) on the product screen.<br>
        The POS tile can now be added directly from POS (previously it was only possible from the Admin).
      </li>
      <li>
        <strong>Product screen bug fix:</strong>
        Fixed a bug where having a large number of variants would disapear off the screen. They now wrap to the next line.
      </li>
      <li>
        <strong>Workflow improvements:</strong>
        Simmer will now automatically create a new ticket if no current ticket is selected. This will save time if you forget to create a new ticket before trying to add a product.<br>
        When you click <strong>add to cart</strong> Simmer will only show the confirmation modal if there are products already in the cart. And you now have the option to clear the cart or leave the cart as is.<br>
        🙏 We really appreciate all the feedback we've received from merchants. Please keep it coming!
      </li>
    </ul>
  </div>

  <div class="changelog-item">
    <div class="date">October 2024</div>
    <ul>
      <li class="feature-release">
        <strong>⭐️ Simmer is born! 🚀</strong><br><br>
        Hello world! 👋
      </li>
      <li>
        <strong>Ticket filters:</strong>
        Added filters to the Tickets screen to keep the open tickets screen cleaner. There are now three filters: Open, Closed and Canceled.
      </li>
    </ul>
  </div>
</div>
