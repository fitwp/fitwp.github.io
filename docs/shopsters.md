---
layout: docs
title: Shopsters Documentation
description: Shopsters Wordpress theme documentation
---


*Welcome! First of all we want to thank you for purchasing our Shopsters WordPress Theme.*

In the following sections we will show you how to set up and use Shopsters theme the easiest way possible. Although there're a lot of things written in this documentation, the theme itself is not very hard to use. You can go to the Theme Options page and discover everything yourself. This file is more of a reference if you do not know what to do, or if you are not familiar with WordPress.

If you have any questions that are beyond the scope of this help file, please feel free to ask your questions at the support ticket system.


## Files included

The download package (.zip) that you get from ThemeForest contains the following files and folder:

- shopsters.zip: main theme file that need to be uploaded to host to install Shopsters theme.
- shopsters-child.zip: the basic child theme for Shopsters.
- Documentation: folder of documentation files.
- Plugins:
	- codecanyon-2751380-slider-revolution-responsive-wordpress-plugin.zip: Slider Revolution Responsive WordPress Plugin. Completed download package from Codecanyon.net. It's FREE for you to use with Shopsters theme.
	- codecanyon-242431-visual-composer-page-builder-for-wordpress.zip: Visual Composer plugin. Completed download package from Codecanyon.net. It's FREE for you to you with Shopster theme.
	- shopsters-demo-import.zip: a plugin which helps you to import the demo content by just 1 click.


## Installation

### Step 1: Install Theme

After you download the *.zip* package from ThemeForest, unzip it. You'll see a file *shopsters.zip*, which is the main file that needed to upload and install.

Notice: If you download Installable WordPress file then that file is the zip file we use to upload and install.

You can either choose to upload and installl the theme using FTP or use WordPress theme install function. Both of them result in the same thing.

**Upload and install using FTP**

- Unzip ` Shopsters.zip`, you'll get a folder `shopsters`
- Use a FTP client like FileZilla and upload that folder to ` wp-content/themes` folder on your host.
- Go to `Appearance > Themes` and activate Shopsters theme
Install theme using WordPress install function.

**Install theme using WordPress install function**

- Go to `Appearance > Themes` and click **Add New**
- Select **Upload**
- Click **Browse** and select the `Shopsters.zip `file
- Click **Install Now**


When upload and installation progresses are completed, click **Activate**, or go to` Appearance > Themes` and activate Shopsters theme.

![upload wordpress theme](http://i.imgur.com/XogVuZq.png)


### Step 2: Install plugins

After installing Shopsters, you'll see a notification in the top of the page that says the theme needs some plugins to function properly.

Shopsters theme requires follow plugins:

- Meta Box
- WooCommerce
- WPBakery Visual Composer
- Shopsters VC Addon

Shopsters theme recommends follow plugins:

- Slider Revolution ($18 on CodeCanyon, included in download package for free)

Shopsters is working perfectly with these plugins. It automatically adds more styles to them to make the design match the theme.
To install these plugins:

- Click Begin installing plugins
- You'll be redirect to a page where all needed plugins are listed. Just click on Install below each plugin's name
- After installing, if it's required to activate the plugin, just activate.

![install plugins](http://i.imgur.com/HDghdDA.png)


### Step 3: Config plugins

After finish installing plugins, you need to config image sizes for product.

- Go to `Woocommerce > Settings > Products > Display`, under the Product Images section, you will find Catalog Images, Single Product Images, and Product Thumbnails.
- Catalog Image is for your images on the shop page and for shortcodes. Single Product Image is for your images on the single product pages. Product Thumbnail is for your smaller product thumbnails for widgets.
- Change the size of Catalog Image to 263 x 300, Single Product Image to 555 x 633, Product Thumbnail to 180 x 180.

![woocommerce settings](http://i.imgur.com/2G7pfxp.png)


### Step 4: Install demo content plugin

Firstly, install all required and recommended plugins as we wrote above <a href="#toc8">Install Theme</a>. But they not all, there is still a plugin we have to install, it is `Shopsters Demo Import` plugin.

Now go to `Plugins > Add New` then click to **Upload Plugin** button on the top.

![upload plugin](http://i.imgur.com/aRt2H4r.png)

Click to button **Choose File** then select `shopsters-demo-import.zip` file in `Plugins` folder, then lick **Install Now** button. After finish installing plugin, click to **Active Plugin** on the next screen.

<div class="alert">**Note**: You have to disable plugin **WordPress Importer** before install and active **Shopsters Demo Import** to avoid error while installing it.</div>


### Step 5: Import demo content

Go to `Appearance > Import Demo`. You can select what content do you want to import or don't change anything to import all demo data. Finally, click **Import Demo Content** button to finish.

![1 click import demo](http://i.imgur.com/ecSxZek.png)


## Theme Options

The Shopsters theme comes with unique, creative and easy-to-use Theme Options page. You can change all theme options in one place!

With Shopsters's advanced theme options panel, you can customize just about any part of your site quickly and easily. Every element on the site can have the color changed to your liking. Choose a color scheme for website, select fonts for all headings and body copy, change sizes, colors and line-heights of all fonts, select different footer column layouts, enable or disable several options, upload your own custom favicon, select from various site/page layouts, input custom CSS, set hundreds of other options to easily customize your site!

All options have full description so you can know what you are doing. Just click and save!


## Page Templates

Shopsters has some build-in page templates that can help you create special pages easier:

- **Homepage**: template to display page content without header title.

When you edit a page, look at on the right, find **Page Attributes** meta box and select a template from the dropdown **Template**
Width **Homepage** template, there's no configurations at all. After select page template from the meta box on the right, you just need to save the page and see it in action in the frontend.


## Widgets

Shopsters plays nicely with default WordPress widgets. Besides that the theme has some additional widgets that might be useful for you:


### [FitWP] Flickr

This widget displays list of photos which is get from a user or group on [Flickr](http://flickr.com).

This widget has the following options:

- **Title**: widget title
- **Flickr ID**: this is ID (**not username**) of user or group on Flickr. You can go to [http://idgettr.com](http://idgettr.com/) to get the ID.
- **Type**: select type of above ID is `User` or `Group`
- **Number of photos**: how many photos you want to display
- **Display**: which photos you want to display, latest or random photos.
- **Size**: select size of photos


### [FitWP] Latest Tweets

Before you use this widget, you have to create a Twitter app. Following these steps:

- Go to [https://apps.twitter.com/](https://apps.twitter.com/) and click **Create New App** button.

![twitter app](http://i.imgur.com/tM1TlxW.png)

- Fill in all information needed for the app. The name and description can be anything, it does not have to be a certain name. You can leave the Callback URL field empty.
- After creating the app, go to **API Keys** tab then click **Create My Access Token** button at the bottom to generate the necessary codes. It usually take 10 - 15 seconds to generate these codes, you have to reload that page to see your code in **Your Access Token** seciton.

![twitter app](http://i.imgur.com/TvTw69t.png)

- Now you can copy the following fields for setting up Latest Tweets widget:
	+ API key  -> Consumer Key
	+ API secret -> Consumer Secret
	+ Access token -> Access token
	+ Access token secret -> Access token secret

These fields will be used in the tweets widget.

Now go to your website admin area, then `Appearance > Widgets`, drag and drop **[FitWP] Latest Tweets** widget into a sidebar that you want it to show there. You'll see these fields this:

![tweets](http://i.imgur.com/5UXsASa.png)

**(1)**: You also need to enter **Cache time**, which is the time your tweets will be temporarily stored in WordPress cache,

**(2)**: Twitter username which you want to get from

**(3)**: Number of tweets you want to get

After filling all information, just click **Save**.


### [FitWP] Recent Posts

This widget replaces default WordPress recent posts widget. It displays recent posts in much more beautiful way and gives you more control to what will be shown.

The widget has the following options:

- **Title**: widget title
- **Number Of Posts**: how many posts you want to displayed
- **Category**: you can choose to display posts from all categories, or a specific category or multiple categories
- **Show Comment Number**: whether or not show comment number
- **Show Thumbnail**: whether or not show thumbnail
- **Default Thumbnail**: if post doesn't have thumbnail, this default thumbnail will be used
- **Show Date**: whether or not show post date
- **Date Format**: date format. [See this link](http://codex.wordpress.org/Formatting_Date_and_Time) for a full list of supported date formats
- **Show Excerpt**: whether or not show post excerpt
- **Excerpt Length**: the number of words of post content will be displayed
- **Show Readmore Text**: whether or not show read more text
- **Readmore Text**: Read more text


### [FitWP] Tabs

This widget displays popular posts, recent posts and recent comments in a tabbed widget. Each tab has its own options. For popular posts and recent posts, the options are similar to the Recent Posts widget above.

Note that popular posts is counted based on number of comments.


### [FitWP] Social Links

This widget shows links (with icons) to your social network profiles. All you need to do is just enter URL to your social network profiles and optionally title for each link.
