---
layout: docs
title: WooCommerce Delivery Time Slots Docs
description: WooCommerce Delivery Time Slots WordPress plugin documentation
---

*Welcome! First of all we want to thank you for purchasing our WooCommerce Delivery Time Slots.*

In the following sections we will show you how to set up and use the plugin the easiest way possible. Although there're a lot of things written in this documentation, the plugin itself is not very hard to use. You can go to the plugin settings page and discover everything yourself. This file is more of a reference if you do not know what to do, or if you are not familiar with WordPress.

If you have any questions that are beyond the scope of this help file, please feel free to ask your questions at the support ticket system.

## Files included

The download package (.zip) that you get from CodeCanyon contains the following files and folder:

- `woocommerce-delivery-time-slots`: main plugin file that need to be uploaded to host to install.
- `docs.html`: the documentation file (copy of this page)
- `Licensing`: folder of license terms.

## Installation

After download the .zip package from CodeCanyon, unzip it and you will see a file `woocommerce-delivery-time-slots`.

Go to your WordPress **Dashboard**, then click to **Plugins -> Add New** menu on the left.

![add new plugin](http://i.imgur.com/2QCWdJm.png)

In the next page, select the `woocommerce-delivery-time-slots` file and click **Install Now**

![upload plugin](http://i.imgur.com/ajcmwE5.png)

After uploading the plugin, click **Activate Now** link to activate the plugin.

## Upgrade

If you have an old version of the plugin, please follow the steps below to update it to the latest version:

- Download the .zip package from CodeCanyon, unzip it and you will see a file `woocommerce-delivery-time-slots`.
- Unzip the `woocommerce-delivery-time-slots` to get `woocommerce-delivery-time-slots` folder.
- Upload `woocommerce-delivery-time-slots` folder to the `/wp-content/plugins/` directory, overwrite old plugin files

## Configuration

All the plugin settings are merged into WooCommerce's settings. To see them, please go to **WooCommerce -> Settings** and click the **Shipping tab**.

You will see all settings in the bottom of this page.

Below are descriptions of all the settings:

### Required

This option make the delivery time mandatory field. Customer must enter delivery time to make order.

### Disable for shipping methods

This option allows you to disable the date, time picker for specific shipping methods. Note that, the field is still shown in the checkout page, but when people select a shipping method which is marked as disabled in this option, the input doesn't show date, time picker for them to select.

### Label

This is the text label appeared above the input on the checkout page. By default it's **Delivery Time**, but you can change it to anything.

### Date format

Format a date into a string value with a specified format. The format can be combinations of the following:

- `d` - day of month (no leading zero)
- `dd` - day of month (two digit)
- `o` - day of the year (no leading zeros)
- `oo` - day of the year (three digit)
- `D` - day name short
- `DD` - day name long
- `m` - month of year (no leading zero)
- `mm` - month of year (two digit)
- `M` - month name short
- `MM` - month name long
- `y` - year (two digit)
- `yy` - year (four digit)
- `@` - Unix timestamp (ms since 01/01/1970)
- `!` - Windows ticks (100ns since 01/01/0001)
- `'...'` - literal text
- `''` - single quote
- anything else - literal text

There are also a number of predefined standard date formats available:

- `ATOM` = `yy-mm-dd` (Same as RFC 3339/ISO 8601)
- `COOKIE` = `D, dd M yy`
- `ISO_8601` = `yy-mm-dd`
- `RFC_822` = `D, d M y` (See RFC 822)
- `RFC_850` = `DD, dd-M-y` (See RFC 850)
- `RFC_1036` = `D, d M y` (See RFC 1036)
- `RFC_1123` = `D, d M yy` (See RFC 1123)
- `RFC_2822` = `D, d M yy` (See RFC 2822)
- `RSS` = `D, d M y` (Same as RFC 822)
- `TICKS` = `!`
- `TIMESTAMP` = `@`
- `W3C` = `yy-mm-dd` (Same as ISO 8601)

**Default**: `mm/dd/yy`

### Language

The plugin supports most languages in the world. You just need to select them from the dropdown box in the settings page.

With the selected language, all text in the date time picker will be translated, such as text for prev, next, today, week days, etc.

You also can set custom text for all buttons, month names, etc. Just in case the auto translation is not as good as expected.

### Restrict dates

This is the most powerful weapon the plugin supports. With this feature, you're able to provide shipping to customers in only some certain days/months.

All you need to do is enter your rules into the textarea box.

**You have to following this guide:**

- You can enter **only one rule per line**
- Each rule must be a single date or a single date range
- Date must be formatted in USA format, e.g. `mm/dd/yyyy`
- Date range must be formatted: `mm/dd/yyyy - mm/dd/yyyy` (e.g. `fromDate - toDate`)
- You can use stars (*) for day, month or year, which means any day, any month or any year

Examples:

**Single date**

Format | Meaning
--- | ---
`5/12/2013` | No shipping on May 12th, 2013
`1/1/*` | No shipping on January 1st of any year (New Year)
`8/*/2013` | No shipping in October, 2013
`*/1/2014` | No shipping on first day of any month of 2014
`12/*/*` | No shipping in December of any year
`*/1/*` | No shipping on first day of any month of any year
`*/*/2013` | No shipping in 2013 at all

**Date range**

Date range is just combination of from date and to date. Each date in the range must be well-formatted as single date.

Format | Meaning
--- | ---
`5/12/2013 - 6/1/2013` | No shipping from May 12th, 2013 to June 1st, 2013
`12/24/* - 1/1/*` | No shipping from December 24th to January 1st of **next year**
`6/*/* - 8/*/*` | No shipping from June to October of any year
`*/1/* - */5/*` | No shipping on first 5 days of any month of any year
`8/*/* - 12/1/*` | No shipping from August to December 1st of any year
`1/15/* - 2/*/*` | No shipping from January 15th to February
`*/25/* - */1/*` | No shipping from 25th to 1st day of **next month**

### Restrict by week days

Beside restricting dates by rules above, you can restrict by week days. Just select which days you don't want to provide shipping from the checkbox list and save.

### Disable shipping in the next XXX days

You can disable datetime picker for some days, counting from today.

For ex.:

- `0`: disable today
- `1`: disable today and tomorrow

If you don't enter any value, the plugin will disables all past days, e.g. before today.

### Enable shipping only in the next XXX days

Similar to the option above, you can enable datetime picker for only some days, counting from today.

For ex.:

- `0`: enable today
- `1`: enable today and tomorrow

If you don't enter any value, the plugin will enable all days.

### Show time slots

Check this box to allow users to pick time for delivery.

### Time slots

Time slots are the time you can delivery goods to customer. It can be a time range (from 2PM to 3PM), or arbitrary time (this afternoon, tomorrow morning).

This options allows you to define any kind of time slots for delivery by simple entering your text in the input box. You can add as many as you want time slots. For example:

- 8AM - 12AM
- 2PM - 4PM

or

- In the afternoon, after 5PM
- In the next day


### Limit by number of shipments per day

Some stores offer a limited number of shipments per day, due to their limited resources. This option can help you do this.

The option **Max. Number Of Shipments Per Day** allows you enter the maximum number of shipments per day that your store can support. And the next option **Notification For Exceeded Shipments** is the notification that people see when the number of shipments for a *specific day* exceeds limit set by the option above.

### Themes

Now you can choose any theme from 21 themes available. It's helpful when you want the calendar matches your theme color.

## Shortcodes

### Showing input for entering shipping time

By default the plugin shows the input for entering shipping time on the **Checkout page**, but you might want to display it on other pages as well.

To do that, you can use the shortcode `[wdts_field]`. This shortcode doesn't have any attributes. So, use the code follow to insert the shortcode to your page template:

```php
<?php echo do_shortcode( '[wdts_field]' ); ?>
```

### Showing picked shipping time

To show picked shipping time of an order, please use the shortcode `[wdts_shipping_time id="ORDER_ID"]`. This shortcode requires order ID (please replace with yours).

To show shipping time in your template, please use the following code:

```php
<?php echo do_shortcode( '[wdts_shipping_time id="ORDER_ID"]' ); ?>
```

## Display time picker field in other pages than checkout

To place the date picker field in another page, for example the cart page, you need to overwrite the WooCommerce template file in your theme. These are the basic steps:

- Create a folder `woocommerce/cart` in your theme. You can bypass this step if your theme already has this folder.
- Copy the file `templates/cart/cart-totals.php` from WooCommerce's folder and paste it into the `woocommerce/cart` folder you've just created above
- Open the new copied file and put the following code inside that file:

```php
<?php echo do_shortcode( '[wdts_field]' ); ?>
```

Then preview in the front end. You might want to move the line to an appropriate place.

To understand about the WooCommerce template, please read [this documentation](https://docs.woothemes.com/document/template-structure/)

## Email

By default, the shipping time is attached to default WooCommerce email sent to admin. But if your theme is using custom email template, then the new template might overwrite WooCommerce's template.

To fix that, please find file `woocommerce/emails/email-addresses.php` in your theme and add the following code to the place where you want the shipping time to appear:

```php
<?php if ( $delivery_time = get_post_meta( $order->id, '_delivery_date', true ) ) : ?>
	<?php
	$option = wdts_option();
	$label = $option['label'];
	?>
	<h3><?php echo $label; ?></h3>
	<p class="text"><?php echo do_shortcode( "[wdts_shipping_time id='" . $order->id . "']" ); ?></p>
<?php endif; ?>
```
