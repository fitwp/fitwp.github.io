---
layout: docs
title: NOISE Documentation
description: Documentation for NOISE WordPress theme
permalink: /docs/noise
---

**Welcome! First of all we want to thank you for purchasing our Noise WordPress Theme.**</div>

In the following sections we will explain how to set up and use Noise theme the easiest way possible. Although there're a lot of things written in this documentation, the theme itself is not hard to use. You can go to the Theme Options page and explore everything yourself. This file is more of a reference if you do not know what to do, or if you are not familiar with WordPress.



## Files Included

The download package (`.zip`) that you get from ThemeForest contains the following files and folder:

- `noise-wp.zip`: main theme file that need to be uploaded to host to install Noise theme
- `demo-content.xml`: demo content file, which contains all pages and posts from live preview website. It will help you to have a first look of how we use Noise theme
- `theme-options.txt`: theme option backup file. You'll need this to restore the default theme options that setup for demo website.
- `docs.html`: theme documentation (this file)
- `PSD.zip`: zip file of all PSDs of Noise. You might want to use it to change the design




## Installation


### Install theme

After you download the `.zip` package from ThemeForest, unzip it. You'll see a file `noise.zip`, which is the main file that needed to upload and install.

You can either choose to upload and installl the theme using **FTP** or use **WordPress theme install** function.

**Upload and install using FTP**

- Unzip `noise.zip`, you'll get a folder `noise`
- Use a FTP client like [FileZilla](http://filezilla-project.org/) and upload that folder to `wp-content/themes` folder on your host
- Go to `Appearance > Themes` and activate **Noise** theme

**Install theme using WordPress install function**

- Go to `Appearance > Themes` and click **Add New**
- Select **Upload**
- Click **Browse** and select the `noise.zip` file
- Click **Install Now**
- When upload and installation progresses are completed, click **Activate**, or go to `Appearance > Themes` and activate **Noise** theme

![upload](http://docs.fitwp.com//whisper/wordpress-upload.png)




### Install plugins

After installing Noise, you'll see a notification in the top of the page that says the theme needs some plugins to function properly.

Noise theme **requires** the [Meta Box](http://wordpress.org/plugins/meta-box/) plugin (free and available on WordPress.org) and **recommends** [MailPoet Newsletters (formerly Wysija)](http://wordpress.org/plugins/wysija-newsletters/) (free and available on WordPress.org) and [WR PageBuilder plugin](https://wordpress.org/plugins/wr-pagebuilder/) (free and available on WordPress.org).

Noise is working perfectly with these plugins. It automatically adds more styles to them to make the design match the theme.

To install these plugins:

- Click **Begin installing plugins**
- You'll be redirect to a page where all needed plugins are listed. Just click on **Install** below each plugin's name
- After installing, if it's required to activate the plugin, just activate

![plugins](http://docs.fitwp.com//noise/install-plugins.png)




### Install demo content

If you are new to WordPress and have problems with setting up the theme you might want to import the demo content file that comes with the theme. The following actions will import some dummy posts and pages from the live preview:

- Go to `Tools > Import`
- Select **WordPress** from the list
- If you haven't installed the **WordPress import plugin**, a popup window will appears and ask you to install it. Just click **Install Now**. When the installation progress is completed, click **Activate Plugin & Run Importer**. If you have installed this plugin, skip to next step.
- Click **Browse** and select `demo-content.xml` file from the download package
- Click **Upload file and import**
- When you are asked to import author, you can create new author or import to existing author. You also should check the checkbox **Download and import file attachments**.

![import](http://docs.fitwp.com//whisper/import.png)

After completing all above steps, go to `Track`, `Artist`, `Album` to see imported data.



<div class="alert">**Important:** Due to license of images (http://www.shutterstock.com/), we have to remove images in distributed demo content and replace them with placeholers. You'll get a demo site looks like http://themes.fitwp.com/noise-demo/</div>





### Setup homepage and blog page

After install demo content, you'll see a page `Onepage`. This page will be used as the homepage of the website. To set it as homepage, please go to `Settings \ Reading`, under **Front page displays**, please chose **A static page (select below)** and select **Onepage** for **Front page** and **Blog** page for **Posts page**.

![homepage](http://docs.fitwp.com//noise/homepage.png)





### Restore Theme Options

To make your website looks exactly like the demo website, you need to import theme options.

In the download package, there's a file called `theme-options.txt`. Please open it with a text editor (like Notepad in Windows) and copy the content.

Then go to **Appearance \ Theme Options \ Backup and Restore**, you'll see this:

![backup](http://docs.fitwp.com//noise/backup.png)

Paste the content of `theme-options.txt` that you've just copied into the textarea **(1)**, then click button **(2)** to import the theme options.

That's all!





### Setup menu

Because we haven't created a menu for primary location, the theme will display WordPress pages by default, which is not correct.

Following these steps to assign a menu:

- Go to `Appearance > Menus`
- Select an existing to edit, or click **create a new menu**. **Note:** when you import theme data, WordPress automatically create a menu **Main** for you, so select it if you want to have same menu as in live preview.
- Select items in **Noise Sections** from the left meta box and click **Add to Menu**.
- On the right, feel free to drag and drop menu items to organize them.
- When you're done moving menu items, check **Primary Menu** for **theme locations** at the bottom of the page
- Click **Save Menu**

![menu](http://docs.fitwp.com//noise/menu.png)

<div class="alert">**Note 1:** This changes only order of menu items, not order of sections. To change order of sections, please go to Theme Options.</div>

<div class="alert">**Note 2:** If you use the imported menu (e.g. the **Main** menu which is automatically created), you have to **change the URL** of menu item. Currently they're pointed to section of demo website, and you have to change URL to your website.</div>

![menu](http://docs.fitwp.com//noise/menu-link.png)



### Setup widget areas

Noise theme has only 1 widget area (sidebar) for **Blog** page. By default, Noise works perfectly with all widgets, so you just need to drag and drop widgets from the left to the sidebar area. That's all.

![sidebar](http://docs.fitwp.com//whisper/sidebar.png)

To see options for each widgets, please read the **Widgets** section.

That's all! Now you have the website up with all *basic* elements!




## Theme Options

![theme options](http://docs.fitwp.com//noise/theme-options.png)

The Noise theme comes with unique, creative and easy-to-use Theme Options page. You can change all theme options in one place!

With Noise's advanced theme options panel, you can customize just about any part of your site quickly and easily. You can change options for each section on the site. Upload your own custom favicon, input custom CSS. Change title, subtitle for each section. Upload background for parallax effect, etc.

All options have full description so you can know what you are doing. Just click and save!

Let's go through each section.




### General


![general](http://docs.fitwp.com//noise/general_option.png)

This sections contains:

- **(1)**: under construction mode. If you active this, your website will be put under construction mode. Note that, if you enable construction mode, you have to create a page use template "Under Construction" to make this mode work correctly.
- **(2)**: autoplay, allow the player auto plays music when website is loaded
- **(3)**: enable autoplay a track when website is loaded. To use this option also enable autoplay option.
- **(4)**: select track plays when website is loaded.
- **(5)**: show or hide download button on expanded player
- **(6)**: number days that user can't vote a track twice times in this range.
- **(7)**: favicon upload, allows you to upload favicon for you website
- **(8)**: touch icon, allows you to upload icon for mobile devices and tablets

After changing settings, click **Save Changes**.



### Favicon Upload

[Favicon](http://en.wikipedia.org/wiki/Favicon) (short for Favorite icon), also known as a shortcut icon, Web site icon, tab icon or bookmark icon, is a file containing one or more small icons, most commonly 16x16 pixels, associated with a particular Web site or Web page. Browsers that provide favicon support typically display a page's favicon in the browser's address bar (sometimes in the history as well) and next to the page's name in a list of bookmarks. Browsers that support a tabbed document interface typically show a page's favicon next to the page's title on the tab, and site-specific browsers use the favicon as a desktop icon.

This is how favicon appears:

![favicon](http://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Wikipedia_favicon_in_Firefox_on_KDE.png/250px-Wikipedia_favicon_in_Firefox_on_KDE.png)

Noise lets you upload favicon or enter favicon URL in the input box:

- If you have a favicon uploaded, or you store the favicon somewhere out of the Media Library, you can just **put the URL of the favicon into the input box**, or
- If you want to upload favicon for your website, **click the upload button** (the green one near input box) and upload it to Media Library as a normal image, then click **Select**.

<div class="alert">The favicon should be in one of the following format: `.ico`, `.png`, `.gif`. Usually we should use `.ico`.</div>

When you're done, you can click **Save Changes** button to save your data.



### Touch Icon

Touch icons are the favicons of mobile devices and tablets. Each mobile devices and tablets has its own standards for displaying the touch icon (read [this article](http://mathiasbynens.be/notes/touch-icons) to have a better understanding about touch icon and supported devices) and requires various icon sizes. But for best compatibility and simplicity, an **image with size 152x152 is enough**.

To specify a touch icon for you website, just do the same as for favicon: you can either put the URL of the touch icon into the input box or upload the icon to Media Library.

<div class="alert">The icon must be an PNG image</div>

When you're done, you can click **Save Changes** button to save your data.




### Design

This sections contains:

- **Color Scheme**: allows you to change color scheme of whole website
- **Background**: allows you to select background pattern or image, and change how it appear
- **Custom CSS**: allows you to add your custom CSS




### Color Scheme
![color sheme](http://docs.fitwp.com//noise/black.jpg)
![color sheme](http://docs.fitwp.com//noise/blue.jpg)
![color sheme](http://docs.fitwp.com//noise/c1.jpg)
![color sheme](http://docs.fitwp.com//noise/c2.jpg)
![color sheme](http://docs.fitwp.com//noise/orange.jpg)
![color sheme](http://docs.fitwp.com//noise/red.jpg)
![color sheme](http://docs.fitwp.com//noise/violet.jpg)

Noise theme has **7 predefined color schemes** to choose from: black, red, blue, orange, violet, Blue sky deep and sapphire. When you change color scheme of the theme, all links, icon boxes, button background and other elements will change their color or background accordingly.

The default color scheme is black, but you can select any from 7 colors here. After selecting, click **Save Changes** button to save your data. Now go to the frontend and check the colors of links, buttons, etc.

When you select **Color Scheme** section, you'll see the following options:

![color sheme](http://docs.fitwp.com//noise/option-color-sheme.png)

**(1)**: select built-in color scheme. These are 7 predefined color scheme. When you select one of them, your website elements will change color accordingly.

**(2)**: enable/disable custom color scheme. This option allow you create **custom color scheme**, and you can build unlimited color schemes here! Just enable this and you'll see options below.

**(3)**: primary color. This is primary color for your custom color scheme.

**(4)**: secondary color. This is the color used in border, element's background color

**(5)**: this is just some examples of using custom colors to built your own color scheme. These are real example which are used to build 7 predefined color schemes. You should start with these values and adjust them

### Background

This section help you to select background pattern or image, and change how it appear.

![background](http://docs.fitwp.com//noise/background.png)

**(1)**: background color.

**(2)**: background image. You can paste image URL here or upload the image to Media Library by clicking the upload button (the green one).

**(3)**: background position X, can be `Left`, `Center` or `Right`.

**(4)**: background position Y, can be `Top`, `Center` or `Bottom`.

**(5)**: background repeat, can be `Repeat`, `Repeat Horizontally`, `Repeat Vertically` or `No Repeat`

**(6)**: background attachment, can be `Scroll` (will scroll when you scroll the content) or `Fixed` (will stay fixed when you scroll the content)

**(7)**: parallax pattern. This is used as an **overlay** of background image. It's for better eye catching effect. You can leave it empty if you don't like the effect.

<div class="alert alert-success">**Tips**: A lot of background patterns can be found at [Subtle Patterns](http://subtlepatterns.com/).</div>

After done, click **Save Changes** button to save your data. Now go to the frontend and check the background.

<div class="alert alert-info">The options 3-6 are similar to CSS properties for background and a little technical. If you don't understand what they mean, just change the values, save and preview changes!</div>




### Custom CSS

![custom css](http://docs.fitwp.com//noise/custom-css.png)

This section allows to enter custom CSS that will be output in the `</head>`. This will **overwrite** CSS of theme, so please be careful!

Custom CSS is useful when you want to adjust **small things** for your website. If you have to adjust a lot of things in website, please use [Child Themes](http://codex.wordpress.org/Child_Themes).




### Header

![header](http://docs.fitwp.com//noise/header.png)

This sections contains:

**(1)**: logo upload, allows you to upload logo for you website. You can either put the URL of the logo into the input box or upload the logo to Media Library. The live preview of the logo will appear below the inputs.

**(2)**: logo size. Specify logo size in **px** here. It will help you resize the logo to correct dimensions. By default, the good size is **200x40**.

<div class="alert alert-info">You should **resize the logo to correct size** in Photoshop or any image editor before upload. It will keep your logo not resized and small size.</div>

**(3)**: header scripts. Enter scripts or code you would like output to `&lt;head&gt;`. It can be:

- `<link>` tag for custom font (from Google Fonts maybe)
- Any meta tag: to show the designer, copyright, etc. in meta tag
- Google Analytics code
- Any Javascript code that need to be execute in `&lt;head&gt;`
- Anything else

<div class="alert alert-error">If you want to put custom CSS here, you're doing **wrong**. There's a section for **Custom CSS** under **Design**, use it instead.</div>





### Sections

This menu will let you reorder sections of Noise, as well as configure each section. Let's go to each submenu to see how it works.




### Order Sections

![order](http://docs.fitwp.com//noise/order.png)

Here you can look at all sections available for Noise. You can drag and drop each section to reorder them as you want.

<div class="alert">Note that you cannot disable sections here. Only reorder. Enable/disable sections will be different options in each section settings.</div>



### Opener

![opener](http://docs.fitwp.com//noise/opener.png)

Opener is the screen you see when the preloader finished (100%). It mimics the "Slide to Unlock" effect on iOS. This part allows you to configure the opener with the following options:

- **(1)**: enable/disable opener. If you don't like the opener at all, you can disable it here. **Note** the opener is shown only once when users first go to website, e.g. they don't have to "unlock" when they go throught all pages on the website.
- **(2)**: opener logo. This option allows you to select logo for opener page. You can paste image URL here or upload it by clicking the green button.
- **(3)**: unlock text. Put the text "Slide to Unlock" here.
- **(4)**: background image. You can paste image URL here or upload it by clicking the green button.




### Top Slider

![slider](http://docs.fitwp.com//noise/top-slider.png)

This is the configuration for the top slider. From version 2.2.1 theme sliders have three types for you are: Static Background, Slider Background and Video Background

This section has the following options:

- **(1)**: enable/disable slider. If you don't like the slider at all, you can disable it here.
- **(2)**: types of slider that you can use. with any types of slider you have other settings as following:

	##### Static Background

![slider](http://docs.fitwp.com//noise/slider-static-background.jpg)

This option help you can set background image for Top Slider and captions appear on it.

- **(1)**: background image. You can paste image URL here or upload it by clicking the green button.
- **(2)**: captions will be showed above slider, you can move to next caption by clicking arrow next or prev on slider.

	##### Slider Background

![slider](http://docs.fitwp.com//noise/slider-background.jpg)

This option help you can set a slider as background for Top Slider and captions appear on it.

- **(1)**: captions will be showed above slider, you can move to next caption by click arrow next or prev on slider.
- **(2)**: images will be showed in slider. You can paste image URL here or upload it by clicking the green button.

	##### Video Background

![slider](http://docs.fitwp.com//noise/slider-video.jpg)

This option help you can set a video as background for Top Slider and captions appear on it.

- **(1)**: your video Url, you can copy link on youtube then paste into this field.
- **(2)**: captions will be showed above video, you can move to next caption by click arrow next or prev on slider.






### Latest Tracks

![latest](http://docs.fitwp.com//noise/latest.png)

This section allows you to display **all** tracks of your website in a vertical slider.In the frontend you can scroll vertically to see all tracks. The configuration of this section is very simple:

- **(1)**: enable/disable the section. If you don't like the latest tracks section at all, you can disable it here.
- **(2)**: section title.
- **(3)**: title suffix. This is a small letter after the section title. It's used for a better eye-catching effect.
- **(4)**: subtitle.
- **(5)**: number of tracks you want to display on website. Please note that the larger number of tracks, the slower website!



### Like & Follow

![like](http://docs.fitwp.com//noise/like.png)

This section displays beautiful Facebook like and Twitter follow button in the frontend. It has the following options:

- **(1)**: enable/disable the section. If you don't like this section to be shown, you can disable it here.
- **(2)**: background image. You can paste image URL here or upload it by clicking the green button.
- **(3)**: message. This is the text that tells peole to like/follow you. You can put text in multiple lines, which will be displayed the same in the frontend.
- **(4)**: text displays on Facebook button.
- **(5)**: Facebook fanpage URL.
- **(6)**: text displays on Twitter button.
- **(7)**: Twitter username. Twitter is more easier than Facebook, you just need to put your Twitter username here.

<div class="alert">**Note:** Since version 1.1.1, NOISE does not use Facebook App ID, instead of that - Facebook Fanpage URL. It'll make you easier to setup the theme (don't need to create Facebook App)</div>



### Popular

![popular](http://docs.fitwp.com//noise/popular.png)

This section displays popular tracks (based on votes) in the latest week and in the latest month. The options for this section is very simple:

- **(1)**: enable/disable the section. If you don't like to display this section at all, you can disable it here.
- **(2)**: section title.
- **(3)**: title suffix. This is a small letter after the section title. It's used for a better eye-catching effect.
- **(4)**: subtitle.
- **(5)**: number of tracks to display.

Please see the screenshot in **Latest Tracks** section to know where these texts are displayed.



### Quotes

![testimonials](http://docs.fitwp.com//noise/testimonials.png)

This section allows you to display maximum 5 quotes in the frontend. It has the following options:

- **(1)**: enable/disable the section. If you don't like to display this section at all, you can disable it here.
- **(2)**: enable/disable sliding quotes automatically.
- **(3)**: background image. You can paste image URL here or upload it by clicking the green button.
- **(4)**: author name
- **(5)**: quote content

The (4) and (5) is repeated the same for all testimonials.




### Media

![gallery](http://docs.fitwp.com//noise/gallery.png)

This section displays photo and video galleries in the latest month. The options for this section is very simple:

- **(1)**: enable/disable the section. If you don't like to display this section at all, you can disable it here.
- **(2)**: section title.
- **(3)**: title suffix. This is a small letter after the section title. It's used for a better eye-catching effect.
- **(4)**: subtitle.
- **(5)**: number of photo galleries to display.
- **(6)**: number of video galleries to display

Please see the screenshot in **Latest Tracks** section to know where these texts **(2)**, **(3)**, **(4)** are displayed.




### Latest Tweets

![tweets](http://docs.fitwp.com//noise/tweets.png)

This sections display latest tweets in the frontend. It has the following options:

- **(1)**: enable/disable the section. If you don't like the latest tracks section at all, you can disable it here.
- **(2)**: background image. You can paste image URL here or upload it by clicking the green button.
- **(3)**: API keys from Twitter App. Please read below to know it.
- **(4)**: Twitter username
- **(5)**: number of tweets to displayed
- **(6)**: cache time (in seconds). Twitter limits number of requests to retrieve tweets in short time. To make sure we always get tweets, Noise has a feature that store tweets in local cache, which will reduce the chance of blocking by Twitter and also improve web performance.

Before you use the Tweets section, you have to create a Twitter app. Following these steps:

- Go to [https://dev.twitter.com/apps](https://dev.twitter.com/apps) and click **Create a new application** button.

![twitter-app](http://docs.fitwp.com//whisper/twitter-app.png)

- Fill in all information needed for the app. The name and description can be anything, it does not have to be a certain name. You can leave the Callback URL field empty.
- After creating the app, click **Create My Access Token** button to generate the necessary codes.
- Now go to app Dashboard and selec **API Keys** tab and copy the following fields:
	+ Consumer key
	+ Consumer secret
	+ Access token
	+ Access token secret

These are needed fields in theme options we've just talked about.



### Releases

![release](http://docs.fitwp.com//noise/release.png)

This section displays latest releases (album) in the latest month. The options for this section is very simple:

- **(1)**: enable/disable the section. If you don't like the latest tracks section at all, you can disable it here.
- **(2)**: section title.
- **(3)**: title suffix. This is a small letter after the section title. It's used for a better eye-catching effect.
- **(4)**: subtitle.
- **(5)**: number of releases (albums) to be displayed. Enter `-1` to show all.

Please see the screenshot in **Latest Tracks** section to know where these texts **(2)**, **(3)**, **(4)** are displayed.



### Subscribe

![subscribe](http://docs.fitwp.com//noise/subscribe.png)

This section displays a subscribe to newsletter form. The form itself is created by another plugin. We recommended **Send Poet** (formly WYSIJA) plugin, which you should installed in the beginning of this documentation. But you can use any other plugin which support **shortcode** like Gravity Forms.

This section has the following options:

- **(1)**: enable/disable the section. If you don't like the latest tracks section at all, you can disable it here.
- **(2)**: background image. You can paste image URL here or upload it by clicking the green button.
- **(3)**: form shortcode. Just paste the shortcode from the plugin here.
- **(4)**: form title.
- **(5)**: form description.




### Events

![events](http://docs.fitwp.com//noise/events.png)

This section displays upcoming and past events in the frontend. The options for this section is very simple:

- **(1)**: enable/disable the section. If you don't like to display this section at all, you can disable it here.
- **(2)**: section title.
- **(3)**: title suffix. This is a small letter after the section title. It's used for a better eye-catching effect.
- **(4)**: subtitle.
- **(5)**: number of events to be displayed. Enter `-1` to show all.

Please see the screenshot in **Latest Tracks** section to know where these texts **(2)**, **(3)**, **(4)** are displayed.




### Special Event

![countdown](http://docs.fitwp.com//noise/special-event.jpg)

This section displays an important event with countdown style in the frontend. It has the following options:

- **(1)**: enable/disable the section. If you don't like the latest tracks section at all, you can disable it here.
- **(2)**: types of background that you can use. with any type of setting you have other settings as description below.
- **(3)**: event title.
- **(4)**: event description.
- **(5)**: event time. You have to enter correct format of the date time: `yyyy-mm-dd h:i:s`

	##### Image option

	![countdown](http://docs.fitwp.com//noise/special-event-image.jpg)

	This option will show an image as background in section.

- **(1)**: background image. You can paste image URL here or upload it by clicking the green button.

	##### Video option

	![countdown](http://docs.fitwp.com//noise/special-event-video.jpg)

	This option will play a video as background in section.

- **(1)**: background video. You can paste video URL on youtube here.





### Artists

![artists](http://docs.fitwp.com//noise/artists.png)

This section displays all artists in a vertical slider in the frontend. The options for this section is very simple:

- **(1)**: enable/disable the section. If you don't like the latest tracks section at all, you can disable it here.
- **(2)**: section title.
- **(3)**: title suffix. This is a small letter after the section title. It's used for a better eye-catching effect.
- **(4)**: subtitle.
- **(5)**: choose which artists will be displayed.

Please see the screenshot in **Latest Tracks** section to know where these texts **(2)**, **(3)**, **(4)** are displayed.




### Blog Parallax

![blog_parallax](http://docs.fitwp.com//noise/blog_parallax.png)

This section displays some information to introduce about your blog.  It have options following:

- **(1)**: enable/disable the section. If you don't like the latest tracks section at all, you can disable it here.
- **(2)**: background image. You can paste image URL here or upload it by clicking the green button.
- **(3)**: blog's description.
- **(4)**: URL to your blog.
- **(5)**: text displays for the link to your blog.




### Latest News

![latest_news](http://docs.fitwp.com//noise/Latest_news.jpg)

This section displays three latest posts with image and excerpt. The options for this section is very simple:

- **(1)**: enable/disable the section. If you don't like the latest tracks section at all, you can disable it here.
- **(2)**: section title.
- **(3)**: title suffix. This is a small letter after the section title. It's used for a better eye-catching effect.
- **(4)**: subtitle.
- **(5)**: change "Read more" text on post that to show all post's description.



### Shop Section

![Shop_section](http://docs.fitwp.com//noise/shop-section.jpg)

This section displays some information to introduce about your shop page in the frontend. It has the following options:

- **(1)**: enable/disable the section. If you don't like this section to be shown, you can disable it here.
- **(2)**: background image. You can paste image URL here or upload it by clicking the green button.
- **(3)**: title. This is the text header.
- **(4)**: description. This is the text content.
- **(5)**: shop url. Link to shop page.
- **(6)**: content of button.



### Products

![Product_section](http://docs.fitwp.com//noise/products.jpg)

This section allows you to display products of your website in a vertical slider. In the frontend you can scroll vertically to see all products. The configuration of this section is very simple:

- **(1)**: enable/disable the section. If you don't like the products section at all, you can disable it here.
- **(2)**: section title and title suffix. This is a small letter after the section title. It's used for a better eye-catching effect.
- **(4)**: you can choose kind of products to show.
- **(5)**: number of products you want to display on website.

**Woocommerce Setting:** WooCommerce plugin almost works after activated, you just have to edit settings about image size to make sure products are displayed correctly with Noise.

Here we will show you where to edit these settings.
![woocommerce_setting](http://docs.fitwp.com//noise/woocommerce-setting.png)

You can import products sample of WooCommerce  follow these steps [here](http://docs.woothemes.com/document/importing-woocommerce-dummy-data/)




### Connect

![connect](http://docs.fitwp.com//noise/connect.png)

This section displays a Google Maps and links to your social profiles in the frontent. It has the following options:

- **(1)**: enable/disable the section. If you don't like to display this section at all, you can disable it here.
- **(2)**: contact section title.
- **(3)**: contact information. You can put address, phone, fax, ... in this textarea box. Put each info in one line to display them beautifully.
- **(4)**: contact email.
- **(5)**: address. Used for Google Maps.
- **(6)**: zoom level for Google Maps.
- **(7)**: list of links to your social profiles



### Custom Content

![custom](http://docs.fitwp.com//noise/custom-content.png)

This section displays custom content in your onepage page. Custom content can be HTML and you can also use shortcodes here. This is useful if you want to show kind of "About" text in your homepage.

It has the following options:

- **(1)**: enable/disable the section. If you don't like the latest tracks section at all, you can disable it here.
- **(2)**: section title.
- **(3)**: title suffix. This is a small letter after the section title. It's used for a better eye-catching effect.
- **(4)**: subtitle.
- **(5)**: custom content. You can enter any shortcodes here.



### Blog

![blog](http://docs.fitwp.com//noise/blog.png)

This part will show you all options for your blog. Although Noise is an "one-page" theme, you still can create multi-page for your website. Blog is one of that "multi-page".

This section has following options:

- **(1)**: blog layout. Noise supports 2 layout: left sidebar and right sidebar
- **(2)**: enable/disable blog header. Blog header here is similar to the Top Slider, it will have same background, but only 1 caption text. By choosing enable, you'll show the blog header in Blog page, disable - hide blog header.
- **(3)**: blog header caption.
- **(4)**: except length for blog posts.
- **(5)**: show/hide read more text.
- **(6)**: the read more text
- **(7)**: pagination style. Noise supports 3 pagination style: Ajax load (click on the button in the bottom of Blog page will load more posts via ajax), Next/Prev (go to next/prev pages), Numeric Buttons (display pages 1, 2, 3, ...)



### Footer

![footer](http://docs.fitwp.com//noise/footer.png)

This is the configuration part for footer. It has only 3 options:

**(1)**: footer logo. You can paste URL of the logo image in the text box, or click the green button to upload/select an image from the Media Library.

**(2)**: copyright text. You can enter text, HTML and **shortcodes** here. To make you easier to display copyright text, Noise has default shortcodes that you can enter here:

- `[year]`: display current year
- `[site_link]`: display link to your website with text is the website title. For example, if you have a website at `http://example.com` and title `Example`, this will display a link like this:

```html
<a href="http://example.com">Example</a>
```

- `[bloginfo]`: display blog information. This is the wrapper of [`bloginfo()`](http://look4wp.com/bloginfo) function. Default it will display blog name (e.g. website title), but you can use it with parameter `name` to display more information, for example:
	+ `[bloginfo name="name"]`: display blog name (default)
	+ `[bloginfo name="description"]`: display blog description (tagline)
	+ `[bloginfo name="version"]`: display WordPress version
	+ `[bloginfo name="rss2_url"]`: display RSS2 feed link
	+ `[bloginfo name="home"]`: display home link
	+ For more value of `name`, please see [`bloginfo()`](http://look4wp.com/bloginfo) function

The default value for copyright text is **Copyright &copy;`[year]` `[site_link]`. All rights reserved.**.

**(3)**: footer scripts. Enter scripts or code you would like output before `&lt;/body&gt;`. It can be Google Analytics code or any Javascript code.




### Backup - Restore

Noise allows you to backup Noise options and restore them later. You can also transfer the saved options data between different installs.

To backup theme options, just copy the text inside the text box and save it into a file on your computer. To import data, replace the data in the text box with the one from the saved file and click **Import Options** button.

After clicking **Import Options**, Noise will automatically setup all options and refresh the current theme options page, so you can see the options immediately.





## Add/Edit Album

Noise has some custom post types, one of them is "Album". When you add or edit an album, you need to fill in some required information to make it displays correctly. Look at 2 meta boxes:

- **Album Information**: album main information
- **Featured Image**: album featured image

![album](http://docs.fitwp.com//noise/album.png)

Let's go through each items:

- **(1)**: album released date. When click on that field, you'll see a popup that show date picker, just pick one date.
- **(2)**: composer name.
- **(3)**: album genre.
- **(4)**: iTunes link of the album, in case you want to sell it on iTunes. Leave empty if you don't want people to go to iTunes and buy it.
- **(5)**: Amazon link of the album, in case you want to sell it on Amazon. Leave empty if you don't want people to go to Amazon and buy it.
- **(6)**: Spotify link of the album, in case you want to sell it on Spotify. Leave empty if you don't want people to go to Spotify and buy it.
- **(7)**: album review. Maybe a short review of the album, how is it, etc.
- **(8)**: album featured image (cover image). Simply select featured image for the album as a normal post. This image will be used to display as album thumbnail.




## Add/Edit Artist

Another post type that Noise has is "Artist". When you add or edit an artist, you need to fill in some required information to make it displays correctly. Look at 2 meta boxes:

- **Artist Information**: artist main information
- **Featured Image**: artist featured image

![artist](http://docs.fitwp.com//noise/artist.png)

Let's go through each items:

- **(1)**: artist's full name.
- **(2)**: artist's nick name.
- **(3)**: date of birth. Just click on the text box, a date picker will be shown and you just need to select a date.
- **(4)**: place of birth
- **(5)**: occupation, like: singler, musician, etc.
- **(6)**: what's the artist best known for? You should put a paragraph here that highlights artist's career.
- **(7)**: synopsis. A paragraph for short introduction to artist.
- **(8)-(12)**: link to artist's social profiles.
- **(13)**: artist's images (gallery). You just need to click the button **Select or Upload Images**, a modal window will display. There you can upload artist's images or choose images from the Media Library. When uploaded, you can drag images to reorder them. These images will be display in a lightbox window in the frontend.
- **(14)**: artist's featured image. Simply select featured image for the artist as a normal post. This image will be used to display as a thumbnail in the frontend.




## Add/Edit Track

"Track" is main post type in Noise. When you add or edit an track, you need to fill in some required information to make it displays correctly. Look at 2 meta boxes:

- **Track Information**: track main information
- **Featured Image**: track featured image

![track](http://docs.fitwp.com//noise/track.png)

Let's go through each items:

- **(1)**: track description.
- **(2)**: track album. You just need to select album from the dropdown. Note that you have to create albums first.
- **(3)**: artist. Same here, you just need to select artist from the dropdown. Note that you have to create artists first.
- **(4)**: composer.
- **(5)**: track release date. Simply click on the text box, a date picker will be shown. You just need to select a date.
- **(6)**: track genre.
- **(7)**: track length.
- **(8)**: track upload. This is the **hotlink** (direct link) to the track. You can enter URL of the track here ot click on the button to upload track to Media Library. Note: you **must** provide direct link to the track for the player to play it in the frontend.
- **(9)**: SoundCloud URL of the track. If you upload track to SoundCloud, you can enter its URL here so people can play the song at SoundCloud right in your website using SoundCloud player.
- **(10)**: track lyrics.
- **(11)**: track images (gallery). You just need to click the button **Select or Upload Images**, a modal window will display. There you can upload track images or choose images from the Media Library. When uploaded, you can drag images to reorder them. These images will be display in a lightbox window in the frontend.
- **(12)**: track videos. If the track has videos (like live show videos, etc.), you can put video URLs here. Videos can be Youtube videos, Vimeo videos or self-hosted videos. For self-hosted videos, please click the "Upload" button to upload videos to Media Library. You can also add as many videos as you want by clicking the "+" button.
- **(13)**: track cover image (optional). This image will be used in extended player. If you don't set any image here, the first image in the gallery will be used.
- **(14)**: track featured image. Simply select featured image for the track as a normal post. This image will be used to display as a thumbnail in the frontend.




## Add/Edit Gallery

Noise allows you to show your photo gallery or video gallery. When you add or edit a gallery, you'll see the following options:

![gallery](http://docs.fitwp.com//noise/gallery-edit.png)

- **(1)**: gallery type: 'Photos' or 'Videos'. If you choose 'Photos', then you have to uploads images, otherwise, you have to upload videos.
- **(2)**: gallery images. Click the button **Select or Upload Images**, a modal window will display. There you can upload images or choose images from the Media Library. Note: you only to do this if you choose gallery type 'Photos'.
- **(3)**: gallery videos. If you choose gallery type 'Video', you can put video URLs here. Videos can be Youtube videos, Vimeo videos or self-hosted videos. For self-hosted videos, please click the "Upload" button to upload videos to Media Library. You can also add as many videos as you want by clicking the "+" button.
- **(4)**: gallery featured image. Simply select featured image for the gallery as a normal post. This image will be used to display as a thumbnail in the frontend.




## Add/Edit Event

Noise allows artists/singles to put their events on the website so fans can see and buy tickets. When you add or edit an event, please fill in the information below:

![event](http://docs.fitwp.com//noise/event.png)

- **(1)**: event date/time. Simply click on the text box, a date/time picker will popup and you just need to select correct date and time.
- **(2)**: event information (description).
- **(3)**: place of the event.
- **(4)**: event status. This can be "Cancel", "Sold Out", "Buy" and often used for tickets.
- **(5)**: buy link. If you choose event status "Buy", please enter the link to buy page here.
- **(6)**: event images. Click the button **Select or Upload Images**, a modal window will display. There you can upload images or choose images from the Media Library.
- **(7)**: event videos. You can put video URLs here. Videos can be Youtube videos, Vimeo videos or self-hosted videos. For self-hosted videos, please click the "Upload" button to upload videos to Media Library. You can also add as many videos as you want by clicking the "+" button.





## Post Formats

[Post Formats](http://codex.wordpress.org/Post_Formats) is theme feature which is a piece of meta information that can be used by a theme to customize its presentation of a post.

In short, with a theme that supports Post Formats, a blogger can change how each post looks by choosing a Post Format from a radio-button list.

Noise theme supports the following post formats:

- `gallery` - A gallery of images, which will be displayed in a responsive image slider, powered by Flexslider.
- `link` - A link to another site.
- `image` - A single image, which will be shown above post title.
- `quote` - A quotation.
- `video` - A single video, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed above post title.
- `audio` - An audio file, which can be any video from Youtube, Video or other video websites. The video will be displayed using a powerful HTML5 audio player – MediaElements.

Each post format will have an icon near post title which tells you what post format is. Using post format in Noise lets you differentiate post from each other and make the blog page / single page looks more beautiful.

[See blog page](http://themes.fitwp.com/noise/blog/) to see how post formats look.




### Setup Post Formats

When you edit a post, select a format you want to apply to that post on the **Format** meta box on the right:

![formats](http://docs.fitwp.com//whisper/post-formats-box.png)

When you choose a format, a corresponding meta box will appear **below** the content editor, here's the list of them:

![formats](http://docs.fitwp.com//noise/post-formats.png)

All you need to do is just enter **all** information in the fields in these meta boxes. This information will be used to decorate the post.




## Page Templates

Noise has 4 page templates:

- **Onepage**: displays one page layout (same as demo)
- **Blog**: displays blog posts.
- **Under Construction**: display under construction page.
- **Full Width Page**: build pages with full width.

When you edit a page, look at on the right, find **Page Attributes** meta box and select a template from the dropdown **Template**:

![page-templates](http://docs.fitwp.com//noise/page-templates.png)

View the page to see result!

Note: if you want to make the under construction page work (e.g. your site is under construction mode), after creating a page with page template **Under Construction**, please go to **General** tab in theme option and enable **Under Construction Mode**.

For **Under Construction** page template, you'll see this box below main editor:

![underconstruction](http://docs.fitwp.com//noise/underconstruction.png)

This page template needs following information:

- **(1)**: page heading, this will show a big notice to users.
- **(2)**: description, text to describe the construction mode.
- **(3)**: end date, i.e. when the website is done.
- **(4)**: background image. This allow you to upload or select any image in Media Library as background for construction page.


For **Full Width Template** page template, you can combine with WR PageBuilder to create many kind of defferent pages.

Here we will show you how to use WP PageBuilder to build a page.

**Open page builder**

![open wr pagebuilder](http://docs.fitwp.com//glamo/ig-pagebuilder-open.png)

When add or edit pages, you will see 2 tabs `Classic Editor` and `Page Builder` right bellow page title, click to `Page Builder` to open page builder screen add start adding content.

**Note:** Before adding elements to page, you should know that WR PageBuilder organize content in a grid using rows and columns. Each row can contain some columns and each column can contain some elements.

Now let's see how to add rows, columns and elements to page content.


** Add Row **

![WR pagebuilder add row](http://docs.fitwp.com//glamo/ig-pagebuilder-add-row.png)

**(1)**: Click the **Add Row** button to add new row.

**(2)**: You can drag and drop a row in vertical direction to change its order.

**(3)**: You can delete a row by clicking the recycle icon on the right side of the row. If that row contains elements, a alert box will appear and ask you to confirm that you want to delete that row and all elements inside it.

**(4)**: Edit row. When you click the Edit Row icon (above delete row icon), a modal box will appear with options to edit row, let's see what it is:

![wr pagebuilder edit row](http://docs.fitwp.com//glamo/ig-pagebuilder-row-options.png)

- **Width**: select the width of row, boxed or full width. By default it is boxed.
- **Background**: select background type of row: none, solid color, gradient, pattern or image, then set it up.
- **Border**: specify row border. It contain border with, border type and border color.
- **Padding**: edit padding of row in **px**. By default all values are set to 10px
- **CSS Class**: add css class to row. It is useful when you want to add special style to a row by using `Custom CSS` feature in `Theme Options`.
- **ID**: Set css id to row. As same purpose as **CSS Class**, you can add style to a row by adding ID to it.


** Add Columns **

![ig pagebuilder add columns](http://docs.fitwp.com//glamo/ig-pagebuilder-add-columns.png)

There are 2 way to add columns into a row: add them manually or user pre-defined layout.

**(1)**: add columns manually by clicking the **Add Column** button on the right side of row. You can add maximum 12 columns.

**(2)**: you can resize column by clicking to 3 dots icon between columns and drag it to left or right side.

**(3)**: add column by using pre-defined layout. When you hover your mouse over the Add Row button, a list of pre-defined layout will appear, just click to a layout and you have a new row with columns inside.


** Add Elements **

![ig pagebuilder add elements](http://docs.fitwp.com//glamo/ig-pagebuilder-add-elements.png)

Inside each row, you will see Add Element button at bottom, just click to it, a modal box appear, it contain all avaiable elements that supported by IG Pagebuilder plugin.

![ig pagebuilder elements](http://docs.fitwp.com//glamo/ig-pagebuilder-elements.png)

Select element you want to add by clicking it, a new modal box will appear. It allows you to setup the element with many options. After done, click **Save** button to add the configured element into column.


**Note:** To know in details how to setup/configure each elements, please use online documentation [here](http://www.woorockets.com/docs/wr-pagebuilder-user-manual/).



## Widgets

Noise plays nicely with default WordPress widgets. Besides that the theme has some additional widgets that might be useful for you:




### Noise - Featured Tracks

This widget allows you to display featured tracks in your sidebar. Featured tracks can be latest tracks or highest rated tracks.

This widget has the following options:

- **Title**: widget title
- **Number Of Tracks**: how many tracks do you want to display
- **Show Order Number**: this option shows order number before track icon (ie 1, 2, 3, ...)
- **Show Thumbnail**: whether or not display track thumbnails
- **Show Track Artist**: do you want to show artist name of tracks
- **Show Rating**: show how many votes tracks have
- **Order By**: order tracks (desending) by date (ie show latest tracks) or rating (show highest rated tracks)




### Noise - Tweets

Before you use the Tweets widget, you have to fill in all information for Twitter app in **Theme Options \ Section Latest Tweets**.

After that, go to `Appearance > Widgets`, drag and drop **Noise - Tweets** widget into a sidebar that you want it to show there. The widget has the following options:

- **Title**: widget title
- **Number of Tweets**: how many tweets you want to display

After filling all information, just click **Save**.




### Noise - Recent Posts

This widgets replaces default WordPress recent posts widget. It displays recent posts in much more beautiful way and gives you more control to what will be shown.

The widget has the following options:

- **Title**: widget title
- **Number Of Posts**: how many posts do you want to display
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



### Noise - Tabs

This widgets displays popular posts, recent posts and recent comments in a tabbed widget. Each tab has its own options. For popular posts and recent posts, the options are similar to the Recent Posts widget above.

Note that popular posts is counted based on number of comments.



## Custom image sizes

- **(1):Track Thumbnail (70x70): This type used in section : Popular track**

![custom img](http://docs.fitwp.com//noise/track-thumbnail.jpg)

- **(2):Track Preview (530x250)**

- **(3):Album Thubnail (1150x430): this type used in section: Latest releases**

![custom img](http://docs.fitwp.com//noise/album-thumbnail_1.jpg)

- **(4):Album Preview (525x200): this type used in section: Latest releases. When show an album's information**

![custom img](http://docs.fitwp.com//noise/album-preview.jpg)

- **(5):Player Expanded (240x280): this type used when show player expanded**

![custom img](http://docs.fitwp.com//noise/player-expanded.jpg)

- **(6):Artist Thumbnail (350x450): this type used in section : Artists**

![custom img](http://docs.fitwp.com//noise/artist-thumbnail.jpg)

- **(7):Blog Thumbnail (690x330): this type used in blog page**

![custom img](http://docs.fitwp.com//noise/blog-thumbnail.jpg)

- **(8):Widget Thumb (60x60): this type used in widgets from noise as: Noise-Artists, Noise-Recent Posts.**
