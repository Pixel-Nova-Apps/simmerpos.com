---
layout: page
title: Restaurant ticket printer for Shopify
include_in_header: false
---

<nav class="breadcrumbs">
  <a href="/">Home</a> &gt; <a href="/support/">Support</a> &gt; Kitchen ticket printer
</nav>

# Supported printers

Simmer currently supports the following printers with **Server Direct Print**:

- Epson TM-DT series, 
- Epson TM-i series
- Epson TM-T88VI

If you are unsure if your printer supports **Server Direct Print**, please contact <a href="mailto:simmer@pixelnova.co.nz">simmer@pixelnova.co.nz</a>.

Star Micronics printer support is coming soon.

# Setting up a ticket printer

## Create a ticket printer

### 1. Add printer from the Simmer dashboard:

<img src="/assets/epson-admin/add-printer.png" alt="Add printer" class="support-image">

### 2. Give your printer a name and select the Shopify location you want to use it in:

<img src="/assets/epson-admin/create-printer.png" alt="Create printer" class="support-image">

### 3. Use the printer's credentials in the following guide on how to configure the printer:

<img src="/assets/epson-admin/printer-credentials.png" alt="credentials printer" class="support-image">

## Configure the Epson printer

<div class="note-box">
<strong>Note:</strong> The instructions are for Epson TM-m30III. The interface may vary slightly for other Epson printers.
</div>

### 1. Navigate to your printer's LAN address:

Your printer should print out a receipt with your printer's LAN address upon turning it on.

Enter the IP address into your browser to navigate to the printer's settings page, e.g `http://192.168.1.100`. (replace with your printer's actual IP address).

<img src="/assets/epson-admin/setup-receipt-example.jpeg" alt="Printer LAN address" class="support-image-small">

### 2. Click **Advanced Settings**

<img src="/assets/epson-admin/1.png" alt="Advanced Settings" class="support-image-large">

### 3. Click **Administrator Login** (top right)

<img src="/assets/epson-admin/2.png" alt="Administrator Login" class="support-image-large">

### 4. Enter Printer Serial No. to login

<img src="/assets/epson-admin/epson-serial-number.png" alt="Printer Serial No." class="support-image-large">

<img src="/assets/epson-admin/3.png" alt="Printer Serial No." class="support-image-large">

### 5. Click **TM-i Settings** (opens in new tab)

<img src="/assets/epson-admin/4.png" alt="TM-i Settings" class="support-image-large">

### 6. Click **Server Direct Print**

<img src="/assets/epson-admin/5.png" alt="Server Direct Print" class="support-image-large">

### 7. Enable **Server Direct Print**

<img src="/assets/epson-admin/6-1.png" alt="Enable Server Direct Print" class="support-image-large">

### 8. Populate Server 1 with URL, ID, and Password

<img src="/assets/epson-admin/6-2.png" alt="Enable Server Direct Print" class="support-image-large">

### 9. Click **Apply & Restart**

<img src="/assets/epson-admin/6-3.png" alt="Enable Server Direct Print" class="support-image-large">

### 10. Click **OK**

<img src="/assets/epson-admin/7.png" alt="Enable Server Direct Print" class="support-image-large">

## Print tickets

You can now print tickets from the Simmer POS tile by going to the ticket and clicking **Send**:

<img src="/assets/epson-admin/send-to-printer.png" alt="Send to printer" class="support-image-large">

