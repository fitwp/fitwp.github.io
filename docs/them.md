---
layout: docs
title: TheM Documentation
description: Documentation for TheM WordPress theme
---

*Welcome! First of all we want to thank you for purchasing our TheM WordPress Theme.*

In the following sections we will show you how to set up and use TheM theme the easiest way possible. Although there're a lot of things written in this documentation, the theme itself is not very hard to use. This file is more of a reference if you do not know what to do, or if you are not familiar with WordPress.

## Files Included

The download package (`.zip`) that you get from ThemeForest contains the following files and folder:

- `them.zip`: Main theme file that need to be uploaded to host to install TheM theme
- `docs.html`: Theme documentation (this file)
- `them-demo-import.zip`: The plugin for demo import


## Installation

### Install theme

After you download the `.zip` package from ThemeForest, unzip it. You'll see a file `them.zip`, which is the main file that needed to upload and install. Then follow the steps below to install the theme.

Login to your WordPress dashboard and click on **Appearance > Themes**. Then click on the **Add New** button at the top.

![add theme](http://i.imgur.com/vt5vYby.png)

On the next screen, click on the **Upload Theme** button at the top.

![upload theme](http://i.imgur.com/8NfJfgU.png)

You will be prompted to choose the zip file that you downloaded earlier. Select the file and click **Install Now**.

![install theme](http://i.imgur.com/H1pryEI.png)

Once your theme is installed, you will see a success message along with the link to activate and preview the theme. Just click **Activate** link to complete the installation of the theme.

For more information, please read more our very detailed guide on [how to install a WordPress theme](http://fitwp.com/docs/install-wordpress-theme).


### Install plugins

After installing TheM, you'll see a notification in the top of the page that says the theme needs some plugins to function properly. These plugins adds more features to the theme such as portfolio, contact form, shop, ... which makes your blog more powerful.

TheM theme **requires** the following plugins:

- [Meta Box](https://metabox.io): Adds custom fields to projects (portfolio) and custom settings for pages.
- [MB Customizer](https://metabox.io/plugins/mb-customizer/): Manages theme options in the Customizer.
- **Contact Form 7**: Adds a contact form to your blog.
- **Jetpack**: Adds portfolio and infinite scroll to your blog. If you don't need these features, you can ignore this plugin.
- **WooCommerce**: Helps you to sell stuffs on your blog. You can ignore this plugin if you don't need a shop.

The following plugins are **recommended** if you want a better shop for your blog (you can ignore them if you don't want to):

- **YITH WooCommerce Wishlist**: Adds wishlist to your shop.
- **YITH WooCommerce Compare**: Adds compare feature to your shop.

To install these plugins:

- Click **Begin installing plugins** in the notification in the top of the page
- You'll be redirect to a page where all needed plugins are listed. Just click on **Install** below the plugins' names
- After installing, if it's required to activate the plugin, just activate them

![plugins](http://docs.fitwp.com/whisper/install-plugins.png)


### Configure plugins

To make sure the plugins work well with your blog, you should configure them a little bit as below:

**Jetpack**:

This plugin requires you to connect to WordPress.com to use its functionality. However, if you don't want to connect to WordPress.com, you can still use it freely by following these steps:

- Use a FTP software like FileZilla to connect to your host
- Open the file `wp-config.php` in the installed WordPress folder
- Add the following line at the beginning of the file, below `<?php`

```php
define( 'JETPACK_DEV_DEBUG', true);
```

For more information, please read [this guide](https://jetpack.com/support/development-mode/).

By default, TheM uses 2 modules of Jetpack: **Custom Content Types** and **Infinite Scroll**:

- If you want to show portfolio in your blog, then you need to activate **Custom Content Types** module.
- If you want to have infinite scroll for blog post, porfolio or shop, then you need to activate **Infinite Scroll** module.

Go to **Jetpack → Settings** and activate the modules you want to use.

![jetpack](http://i.imgur.com/ilqQQL0.png)

There are several useful modules that you might want to use. Just activate them and try! Jetpack is a very powerful plugin and one of the most popular plugin for WordPress. It's well developed and actively maintained by Automattic, the organization behind WordPress.

**WooCommerce**:

To make sure product images are displayed beautifully, we need to adjust WooCommerce settings.

Go to **WooCommerce → Settings** and click on the tab **Products**. Then click on **Display** link and change the image sizes as shown in this screenshot:

![woocommerce](http://i.imgur.com/QsgmIgr.png)

**YITH WooCommerce Compare**:

Go to **YITH Plugins → Compare** and set **Link or Button** option to **Link** as follows:

![compare](http://i.imgur.com/3MfUvlG.png)



### Import demo content

If you are new to WordPress and have problems with setting up the theme you might want to import the demo content. This will save you a little time at the beginning and give you an overview of how the theme works.

This step is optional. You should be able to customize the whole theme by following our documentation. In case you want a quick setup for the look just like our demo, please follow these steps:

 1. Download the demo import plugin [here](http://goo.gl)

 2. Go to **Plugins → Add New** in the dashboard, then click **Upload Plugin**

![upload](http://i.imgur.com/f326I3H.png)

 3. Choose the `.zip` file you downloaded in step 1 and click **Install Now**.

![install](http://i.imgur.com/zCJlsg0.png)

4. After installing the plugin, click **Activate** link to activate it.

5. Go to **Tools → Import Demo** and click **Import Demo Content** button.

It takes a couple of minutes to process all the content. After done, go to the frontend and enjoy the theme.


## Setup the homepage

The homepage of IndusPress has several sections that help you to show your content in an attractive way. You can drag and drop these sections to reorder them or remove them completely. It's fully customizable and extremely flexible for your website.


### Homepage overview

The homepage has 5 sections (see the screenshot):

1. Slider
2. Featured Posts
3. Featured Post
4. Instagram
5. Featured Post

![home](http://i.imgur.com/HF78OJL.jpg)


Each section represents itself a widget, which allows you to edit its configuration easily. You can also use WordPress widget management system to reorder them as you wish.

The homepage uses a specialized sidebar (called Homepage) to display its content. The widgets which can be configured in the Customizer or Widgets page in the dashboard.

### Create homepage

In order to build the homepage the same as in the demo, you need to create two pages, one for your homepage and one for your blog page. Go to **Pages → Add New** and create a page titled **Front Page** and a page titled **Blog**. You can also name these pages anything you like, but for the sake of website organization, we recommend using the name **Front Page** and **Blog**.

For the homepage, after you have given your page a title, select **Homepage** from the list of available **Templates** on the right as the following screenshot:

![home](http://i.imgur.com/YXXgwMV.png)

After creating a page and applying the homepage template, you should set it as the static front page by going to **Settings → Reading** and select **A static page (select below)** for **Front page** displays, and then select the page from the dropdown for **Front page** as follows:

![select pages](http://i.imgur.com/LB5uszG.png)

### Homepage sidebar and widgets

The content below the main menu (slider, featured posts, etc.) is the **Homepage** sidebar. We make several widgets for you to add your content to the homepage easier. You can add any other widget to the homepage if you want to (text widget, gallery widget).

To start adding content to **Homepage** sidebar, go to the **Dashboard → Appearance → Widgets**, you will see the **Homepage** sidebar as well as all available widgets:

![sidebar](http://i.imgur.com/9CHSfVp.png)

Another way to add and edit widgets is using the **Customizer**. Do that by clicking **Customizer** in the admin bar and select **Widgets**, then select **Homepage** section:

![customizer](http://i.imgur.com/YUc6983.png)

We will use the **Customizer** in the documentation as it allows you to view the changes in real-time without re-loading the page.

Now let’s go through the homepage widgets.

#### Slider

Slider are a collection of featured posts that are displayed in a special slider with an unique effect for text and image. You are able to select which posts to show in the slider as well as which elements to show. This is a good place if you want to highlight the best posts in your blog.

In the **Homepage** sidebar in the **Customizer**, click button **Add a Widget**, you will see a list of available widgets on the right where you can search for widgets and add them. Here we will search for **TheM: Featured Posts** widget and click on it to add to the **Homepage** sidebar.

![slider](http://i.imgur.com/B7rK7wp.png)

The widget has several options for you to adjust:

- **Number of posts**: the number of posts you want to show in the slider (e.g. the number of slides).
- **Category**: which category you want to get posts from. Select **All** if you want to show posts in all categories.
- **Tag**: which tag you want to get posts from. Select **All** if you want to show posts in all tags.
- **Show date**: do you want to show post date? Date will be rotated 90 degree to have a good effect. You should enable this for the slider.
- **Date format**: the date format. By default it takes WordPress settings in **Settings > General**.
- **Show excerpt**: do you want to show post excerpt in the slider? The post excerpt is taken from post excerpt and fallback to the post content.
- **Excerpt length**: the number of words of post excerpt you want to show in the slider. The recommended number is 40.
- **Show read more button**: do you want to show read more button?.
- **Read more text**: the read more text.
- **Display as slider**: check this to make featured posts displayed as a slider.
- **Slider speed (ms)**: the number of milliseconds between slides.

**Tip**: To select specific posts for the slider, you can create a specific tag and add it to the posts you want to show. Then in this widget, select that tag.

#### Grid of featured posts

Similar to slider, the grid of featured posts displays posts in a 3-column or 4-column grid. This is also a good place to highlight your posts.

The grid of featured posts uses exactly the same widget as the slider (**Featured Posts**). The only difference is you do not check the option to **Display as slider**.

**Note**: In order to have a best view, you should set the number of posts to 3 or 4.

#### Featured post

The **Featured Post** widget allows you to show a single post in the homepage beautifully. That's a good option to show the post that hightlights the main content of your blog.

To add the widget into the homepage, select **TheM: Featured Post** from the widget list:

![featured](http://i.imgur.com/iQLqcPD.png)

The widget has several options for you to adjust:

- **Select post**: select the post you want to show.
- **Thumbnail**: select position for the thumbnail. In the demo, we use this widget twice: one with thumbnail left and one with thumbnail right to give a good affect of view.
- **Show date**: do you want to show post date? Date will be rotated 90 degree to have a good effect. You should enable this.
- **Date format**: the date format. By default it takes WordPress settings in **Settings > General**.
- **Show excerpt**: do you want to show post excerpt? The post excerpt is taken from post excerpt and fallback to the post content.
- **Excerpt length**: the number of words of post excerpt you want to show. The recommended number is 40.
- **Show read more button**: do you want to show read more button?.
- **Read more text**: the read more text.

#### Instagram

The **Instagram** widget displays the latest images from your stream on Instagram or from any person or from any tag in a beautiful grid or carousel slider. It's quite flexible and gives your blog an impressive look.

To add the widget into the homepage, select **TheM: Instagram** from the widget list:

![instagram](http://i.imgur.com/UeEcaSd.png)

The widget has several options for you to adjust:

- **Title**: the title of the widget. It's usually not used in order to display the images more cleaner.
- **User ID**: your user ID. In order to get your user ID, click the link above this field **Authorize and get your Access Token and User ID here**. You will be redirected to Instagram to login if you haven't. Then you will be asked to authorize the app to access to your account. Don't worry, the app only sees your basic info like username and email. Then you will be redirected to a page where your user ID and access token are displayed.
- **Access token**: your access token that you will get in previous step.
- **Cache time**: the number of seconds that the widget cache the content from Instagram. This prevents continual sending requests to Instagram which might be blocked if the frequency is too low. A good option is 3600 (1 hour).
- **Number of images**: the number of images you want to show. If you don't show images as a carousel slider (the option below), then you should set this number to 4.
- **Other user ID**: use this option if you want to display images from an other person than yourself. To get other user's ID, click the link **Click here to get other person's ID** below the input.
- **Tag**: if you want to get images not from yourself, but from a tag in Instagram, then enter the tag here.
- **Display as carousel slider**: do you want to show images in a carousel slider (as displayed in the demo)? If not, images will be shown in a grid.


### Setup menu

Although the theme is working now and it shows menu, but because we haven't created a menu for primary location, the theme will display all pages by default. As the number of pages is large, displaying all of them in the menu is a bad idea.

Following these steps to create a menu:

- Go to `Appearance > Menus`
- Select an existing to edit, or click **create a new menu**. **Note:** when you import theme data, WordPress automatically create a menu **Main** for you, so select it if you want to have same menu as in live preview.
- Select pages from the left meta box and click **Add to Menu**
- On the right, feel free to drag and drop menu items to organize them
- When you're done moving menu items, check **Primary Menu** for **theme locations** at the bottom of the page
- Click **Save Menu**

![menu](http://docs.fitwp.com/whisper/menu.png)


### Setup widget areas

TheM theme has 6 widget areas (sidebars) by default:

- **Blog sidebar:** main website sidebar which will display on all blog posts, archive pages, etc.
- **Page sidebar:** will display on all pages (WordPress pages)
- **Footer sidebars:** there are 4 default sidebars for footer, each sidebar is a column in the footer. Later you can change number of columns in footer in **Theme Options** (we'll talk about this later).

To setup a sidebar, select it from the right by clicking its title or the arrow down. Then drag and drop widgets from the left to the sidebar area.

![sidebar](http://docs.fitwp.com/whisper/sidebar.png)

That's all! Now you have the website up with all *basic* elements!


## Theme Options


The TheM theme comes with unique, creative and easy-to-use Theme Options page. You can change all theme options in one place!

With TheM's advanced theme options panel, you can customize just about any part of your site quickly and easily. Every element on the site can have the color changed to your liking. Choose a boxed or wide skin, or change the website color scheme, select fonts for all headings and body copy, change sizes, colors and line-heights of all fonts, select different footer column layouts, enable or disable several options, advanced blog and portfolio options, upload your own custom favicon, upload custom backgrounds to the featured title area and background areas of the boxed version, select from various site/page layouts, input custom CSS, set hundreds of other options to easily customize your site!

All options have full description so you can know what you are doing. Just click and save!

Let's go through each section.


### General

![general](http://docs.fitwp.com/whisper/general.png)

This sections contains:

- **(1)**: this is the button which shows quick link to **Customizer**, a new feature that allows you to preview changes in real time. Please read more about Customizer in Customizer section in this docs.
- **(2)**: favicon upload, allows you to upload favicon for you website
- **(3)**: touch icon, allows you to upload icon for mobile devices and tablets
- **(4)**: show comments on pages, allows you to show/hide comments and comment form on pages
- **(5)**: backup - restore, allows you to backup TheM options and restore them later


### Favicon Upload

[Favicon](http://en.wikipedia.org/wiki/Favicon) (short for Favorite icon), also known as a shortcut icon, Web site icon, tab icon or bookmark icon, is a file containing one or more small icons, most commonly 16x16 pixels, associated with a particular Web site or Web page. Browsers that provide favicon support typically display a page's favicon in the browser's address bar (sometimes in the history as well) and next to the page's name in a list of bookmarks. Browsers that support a tabbed document interface typically show a page's favicon next to the page's title on the tab, and site-specific browsers use the favicon as a desktop icon.

This is how favicon appears:

![favicon](http://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Wikipedia_favicon_in_Firefox_on_KDE.png/250px-Wikipedia_favicon_in_Firefox_on_KDE.png)

TheM lets you upload favicon or enter favicon URL in the input box:

- If you have a favicon uploaded, or you store the favicon somewhere out of the Media Library, you can just **put the URL of the favicon into the input box**, or
- If you want to upload favicon for your website, **click the upload button** (the green one near input box) and upload it to Media Library as a normal image, then click **Select**.

<div class="alert">The favicon should be in one of the following format: `.ico`, `.png`, `.gif`. Usually we should use `.ico`.</div>

When you're done, you can click **Save Changes** button to save your data.


### Touch Icon

Touch icons are the favicons of mobile devices and tablets. Each mobile devices and tablets has its own standards for displaying the touch icon (read [this article](http://mathiasbynens.be/notes/touch-icons) to have a better understanding about touch icon and supported devices) and requires various icon sizes. But for best compatibility and simplicity, an **image with size 152x152 is enough**.

To specify a touch icon for you website, just do the same as for favicon: you can either put the URL of the touch icon into the input box or upload the icon to Media Library.

<div class="alert">The icon must be an PNG image</div>

When you're done, you can click **Save Changes** button to save your data.


### Show comments on pages

This option allows you to show/hide comments and comment form on pages. By default, TheM doesn't display comments and comment form on pages.

**Important**: In case this option is set to "ON", to display comments on pages, you still have to **allow comments** for pages when you edit pages.

![allow comments](http://docs.fitwp.com/whisper/allow-comments.png)

By default, this checkbox is checked (meaning comments are allowed on pages). But in case you want to show comments on all pages, except some specific pages, you can use this checkbox to hide comments for those pages only.


### Backup - Restore

TheM allows you to backup TheM options and restore them later. You can also transfer the saved options data between different installs.

To backup theme options, just copy the text inside the text box and save it into a file on your computer. To import data, replace the data in the text box with the one from the saved file and click **Import Options** button.

After clicking **Import Options**, TheM will automatically setup all options and refresh the current theme options page, so you can see the options immediately.


### Design

This sections contains:

- **Color Scheme**: allows you to change color scheme of whole website
- **Background**: allows you to select background pattern or image, and change how it appear
- **Layout**: allows you to change layout style and layout for whole website, for blog posts and pages
- **Typography**: allows you to change font family, styles, size, line height, color for body text and headings
- **Custom CSS**: allows you to add your custom CSS


### Color Scheme

![color schemes](http://docs.fitwp.com/whisper/color-schemes.png)

TheM theme has **4 predefined color schemes** to choose from: red, orange, blue and green. When you change color scheme of the theme, all links, icon boxes, button background and other elements will change their color or background accordingly.

The default color scheme is orange, but you can select any from 4 colors here. After selecting, click **Save Changes** button to save your data. Now go to the frontend and check the colors of links, buttons, etc.

When you select **Color Scheme** section, you'll see the following options:

![color schemes](http://docs.fitwp.com/whisper/design-color-schemes.png)

**(1)**: select built-in color scheme. These are 4 predefined color scheme. When you select one of them, your website elements will change color accordingly.

**(2)**: enable/disable custom color scheme. This option allow you create **custom color scheme**, and you can build unlimited color schemes here! Just enable this and you'll see options below.

**(3)**: primary color. This is primary color for your custom color scheme.

**(4)**: secondary color. This is the color used in gradient for pagination buttons or pricing table

**(5)**: tertiary color. This is the color used for borders of pagination buttons or pricing table

**(6)**: this is just some examples of using custom colors to built your own color scheme. These are *real* example which are used to build 4 predefined color schemes. You should start with these values and adjust them.


### Background

This section help you to select background pattern or image, and change how it appear.

<div class="alert">All the background options are applied **only in boxed layout** (we'll reveal how to change boxed or wide layout in the next section).</div>

![background](http://docs.fitwp.com/whisper/background.png)

**(1)**: select background pattern (background image). TheM has **5 predefined background patterns** for you to select from. These patterns are handy picked and match the theme design. If you don't have a background image, you can use one of them.

**(2)**: background color. If you don't want to use an image for background, you can set background as a solid color. You can also do this if you have a background image with some transparent parts and you want to fill those parts with a solid color.

**(3)**: background image. This is similar to the **(1)** option, but here you specify you own background image. You can paste image URL here or upload the image to Media Library by clicking the upload button (the green one).

<div class="alert alert-success">**Tips**: A lot of background patterns can be found at [Subtle Patterns](http://subtlepatterns.com/).</div>

**(4)**: background position X, can be `Left`, `Center` or `Right`.

**(5)**: background position Y, can be `Top`, `Center` or `Bottom`.

**(6)**: background repeat, can be `Repeat`, `Repeat Horizontally`, `Repeat Vertically` or `No Repeat`

**(7)**: background attachment, can be `Scroll` (will scroll when you scroll the content) or `Fixed` (will stay fixed when you scroll the content)

After done, click **Save Changes** button to save your data. Now go to the frontend and check the background.

<div class="alert alert-info">The options 4-7 are similar to CSS properties for background and a little technical. If you don't understand what they mean, just change the values, save and preview changes!</div>


### Layout

This section helps you to select which layout will be use in whole website.

![layout](http://docs.fitwp.com/whisper/layout.png)

**(1)**: layout style. You can choose either **boxed** or **wide** style. TheM theme allows you to change layout style of whole website to boxed or wide (full width). When you change layout style, it doesn’t affect style of your content, sidebar, header or footer. All these elements still keep their looks and feel.

The default style is wide (full width), which make you feel the website is wider, especially on large screens. But in boxed style, you can set background for website.

![boxed wide](http://docs.fitwp.com/whisper/boxed-wide.png)

**(2)**: sidebar layout **for blog, single posts and other archive pages**. You can select sidebar position here: `left`, `right` or `none` (don't display sidebar)

**(3)**: sidebar layout **for pages**. Same meaning as for blog above.

Examples: [sidebar left](http://themes.fitwp.com/whisper/page-sidebar-left/) - [sidebar-right](http://themes.fitwp.com/whisper/page-sidebar-right/)

<div class="alert alert-info">These options is site-wide, meaning for whole website. But you still can set **custom layout for single post and page when edit** (We'll explore it later).</div>

By default: TheM uses **wide** layout style with **right** sidebar for both blog and pages.


### Typography

![typography](http://docs.fitwp.com/whisper/typography.png)

This section helps you to customize fonts for **body text** and **headings** on your website. For each element, you can customize:

**(1)**: font family. Just select from the dropdown font family you like. TheM supports 3 normal fonts (Arial, Verdana and Times) and 1 Google Font (Open Sans).

**(2)**: font size. Adjust font size for better look here. Just remember the unit for font size is **px**.

**(3)**: line height. Adjust line height for better look here. The unit for line height is also **px**.

<div class="alert alert-info">For better readability, good value for line height is about 1.4-1.5 x font size.</div>

**(4)**: font styles. You can choose **bold**, **italic**, **underline** or any combination of them.

**(5)**: font color. Click on the button, a color picker will appear and you can now select any color.

**Important**: before customize fonts, remember the default values for fonts. You should customize fonts around these values.

| Element   | Font Family | Font Size | Line Height | Styles | Color |
| --------- | ----------- | --------- | ----------- | ------ | ----- |
| Body Text | Open Sans   | 12px      | 20px        | None   | #777  |
| Heading 1 | Open Sans   | 20px      | 20px        | None   | #444  |
| Heading 2 | Open Sans   | 18px      | 20px        | None   | #444  |
| Heading 3 | Open Sans   | 16px      | 20px        | None   | #444  |
| Heading 4 | Open Sans   | 15px      | 20px        | None   | #444  |
| Heading 5 | Open Sans   | 14px      | 20px        | None   | #444  |
| Heading 6 | Open Sans   | 13px      | 20px        | None   | #444  |


### Custom CSS

![custom css](http://docs.fitwp.com/whisper/custom-css.png)

This section allows to enter custom CSS that will be output in the `</head>`. This will **overwrite** CSS of theme, so please be careful!

Custom CSS is useful when you want to adjust **small things** for your website. If you have to adjust a lot of things in website, please use [Child Themes](http://codex.wordpress.org/Child_Themes).


### Header

![header](http://docs.fitwp.com/whisper/header.png)

This sections contains:

**(1)**: logo upload, allows you to upload logo for you website. You can either put the URL of the logo into the input box or upload the logo to Media Library. The live preview of the logo will appear below the inputs.

**(2)**: logo size. Specify logo size in **px** here. It will help you resize the logo to correct dimensions. By default, the good size is **201x39**.

**(3)**: logo margin. Specify logo margin in **px** here. This is useful when you upload logo with different size than recommended. You can *move* logo a little, adjust space to make it look good.

<div class="alert alert-info">You should **resize the logo to correct size** in Photoshop or any image editor before upload. It will keep your logo not resized and small size.</div>

**(4)**: header sidebar position. Since version 1.1, you can add more content to the header right space(above or below main navigation). The content is added using widgets. This option allows you to put those widgets allow or below main navigation.

<div class="alert alert-info">Please go to **Appearance \ Widgets** to add widgets to **Header Right** sidebar.</div>

**(5)**: sticky header. This option allow you to make the header sticky, i.e. always stays on the top of the website when scrolling.

**(6)**: header scripts. Enter scripts or code you would like output to `&lt;head&gt;`. It can be:

- `<link>` tag for custom font (from Google Fonts maybe)
- Any meta tag: to show the designer, copyright, etc. in meta tag
- Google Analytics code
- Any Javascript code that need to be execute in `&lt;head&gt;`
- Anything else

<div class="alert alert-error">If you want to put custom CSS here, you're doing **wrong**. There's a section for **Custom CSS** under **Design**, use it instead.</div>


### Featured Title Area

![featured title area](http://docs.fitwp.com/whisper/featured-title-area.png)

Featured Title Area is the highlighted area in the screenshot above. This area shows you an attractive title area with this information:

- **(1)**: Page title
- **(2)**: Page subtitle
- **(3)**: Background image
- **(4)**: Breadcrumbs

TheM uses a **default image** for background and **show** breadcrumbs.

In theme options page, you can change the background image and show/hide breadcrumbs for whole website:

![featured title area](http://docs.fitwp.com/whisper/options-featured-title-area.png)

**(1)**: show/hide breadcrumbs. Default is **OFF** (show breadcrumbs). If you want to hide breadcrumbs, just turn it on.

**(2)**: custom background image. You can either put the URL of the image into the input box or upload the image to Media Library. The live preview of the background will appear below the inputs.

<div class="alert alert-info">Tips: [Subtle Patterns](http://subtlepatterns.com/) is a good resource to find background patterns!</div>

<div class="alert alert-info">These options is site-wide, meaning for whole website. But you still can set **custom featured title area for single post and page when edit** (We'll explore it later).</div>


### Blog

![blog](http://docs.fitwp.com/whisper/blog.png)

This section helps you to change the display options for posts in blog page (and other archive pages). This section contains:

**(1)**: what type of post content will be displayed. Available options are `Post excerpt`, `Post content` or `Post content before more tag`.

To understand what those values mean, take a look at the screenshot bellow:

![post](http://docs.fitwp.com/whisper/post-content.png)

Where:

- **(A)**: Whole post content, this is what you enter in the editor.
- **(B)**: Post excerpt, which is optional hand-crafted summaries of your content. [Learn more about manual excerpt.](http://codex.wordpress.org/Excerpt). If you don't enter anything in the excerpt box, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
- **(C)**: The post content before `more` tag
- **(D)**: The `more` tag

Return to blog option: if you choose

- `Post excerpt`: TheM will get post excerpt and display it. **Remember**: if you don't enter excerpts for post, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
- `Post content`: TheM will get whole post content and display it. This is the default value.
- `Post content before more tag`: TheM will get only the post content before `more` tag and display it.

**(2)**: post content limit. Sometimes you enter a very long text for post excerpt or post content, display such long text in blog and archive pages is not good and harm your website beauty. So we need a way to truncate text to make it shorter. This option is created for that purpose.

Simply specify number of words will be display here. Post content or excerpt will be truncated to exact number of words. You should try changing this value and preview your blog to see what is best for you.

Default value is **55 words**.

<div class="alert">**Important**: this option affects only when you **NOT** choose `Post Content` from the Display option above</div>

**(3)**: readmore text. Default value is **Continue reading**.


### Footer

This section give you options to customize footer area on your website.

![footer](http://docs.fitwp.com/whisper/footer.png)

**(1)**: number of columns in footer. It also is the number of footer sidebars (widget areas). Default is **4**.

**(2)**: copyright text. You can enter text, HTML and **shortcodes** here. To make you easier to display copyright text, TheM has default shortcodes that you can enter here:

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

**(3)**: contact information. Specify phone number and email here.

**(4)**: footer scripts. Enter scripts or code you would like output before `&lt;/body&gt;`. It can be Google Analytics code or any Javascript code.


## Customizer

Customizer is a feature of WordPress that allows us to tweak a theme's settings and see a preview of those changes in real time. And since version 2.0, TheM supports Customizer, which means you can change theme options and preview those changes in real time! You even don't need Theme Options page, unless you want something more advanced like footer scripts!

To start with Customizer, please go to **Appearance \ Customize**, you'll see the following screen:

![customizer](http://docs.fitwp.com/whisper/customizer.png)

**(1)**: there are some sections that you can change and live preview it. These sections have `[TheM]` in their title.

**(2)**: click on each section title will show options for that section. These options are the same as in Theme Options, so it's easy to understand (please refer to Theme Options in this documentation to know exactly each detail).

**(3)**: this is the panel where you'll see your website in real time whenever you change anything.

Remember to click the **Save & Publish** on the top of left panel when you're done tweaking themes!


## Post/Page Display Settings

We've seen how to change featured title area, layout style, sidebar layout for whole website. TheM also supports customizing these things for specific posts and pages.

When you edit a page or a post, you'll see this meta box below the content editor:

![display settings](http://docs.fitwp.com/whisper/display-settings-page.png)

This meta box contains 3 main parts:

1. **Featured Title Area Settings**
1. **Slider Settings**
1. **Custom Layout Settings**

Each parts contains some settings as shown in the screenshot above. Let's go through it:


### Featured Title Area

This is the featured title area which is displayed in the frontend

![featured title area](http://docs.fitwp.com/whisper/featured-title-area.png)

where:

- **(1)**: Page title
- **(2)**: Page subtitle
- **(3)**: Background image
- **(4)**: Breadcrumbs

Let's go back to the page display settings above, we have these settings:

**(1)**: hide featured title area. Check this box if you want to hide the featured title area. This option *should* be used in special pages like homepage.

**(2)**: custom title. Enter the custom page title here. By default TheM displays post/page title, but you can customize the real title shown in Featured Title Area. It is useful when you have a very long title.

**(3)**: subtitle. Enter subtitle for page here. Leave this empty if you don't want to show subtitle.

**(4)**: custom background. If you choose an image, it will be used as the background for Featured Tittle Area. If you do not, TheM will use default image set in **Theme Options**.

**(5)**: hide breadcrumbs. The theme already has settings to show/hide breadcrumbs side-wide. But if you want to hide breadcrumbs for a specific post/page, you can select this option.


### Slider

This part contains only 1 input field **(6)**, where you can enter **shortcode for slider**. The slider will be shown below featured title area. See [this page](http://themes.fitwp.com/whisper/features/custom-slider/) for a demo.

TheM supports slider plugin which has shortcode **only**. These are some plugins tested with TheM:

- [Revolution Slider](http://codecanyon.net/item/slider-revolution-responsive-wordpress-plugin/2751380?rel=fitwp) (premium)
- [Meteor Sliders](http://wordpress.org/extend/plugins/meteor-slides/) (free)
- [Soliloquy Slider](http://wordpress.org/plugins/soliloquy-lite/) (free)

<div class="alert alert-success">When you buy TheM, you also **get a free copy of Revolution Slider plugin** – a very popular plugin at CodeCanyon.</div>

<div class="alert">Note: For sliders that does not support full-width, you should switch site layout style or change page layout style to boxed.</div>


### Custom Layout

In this part, you can change:

**(7)**: whether to use custom page layout. If you check this box, you're able to set custom layout style and sidebar layout below. If you don't, page will use default layout set in **Theme Options**.

**(8)**: custom layout style: boxed or wide. Choose custom layout style for page. If you don't choose anything, TheM will use default layout style set in **Theme Options**.

**(9)**: custom sidebar layout. Choose custom sidebar layout for page. If you don't choose anything, TheM will use default sidebar layout set in **Theme Options**.


## Add/Edit Portfolio

When you add or edit a portfolio, you need to fill in some required information to make it displays correctly. Look at 3 meta boxes:

- **Portfolio Settings**: portfolio main information
- **Portfolio Categories**: portfolio categories
- **Featured Image**: portfolio featured image

![portfolio](http://docs.fitwp.com/whisper/portfolio.png)

In the **(1)** meta box, you have to:

- Select which type of display the portfolio will be. See how they're different here: [default](http://themes.fitwp.com/whisper/portfolio/creativity-in-numbers/) and [simple](http://themes.fitwp.com/whisper/portfolio/light-house/).
- Select or upload portfolio images, these images will be used in the portfolio slider
- Project URL
- Testimonial: required only if you select display type `simple`.
- Testimonial Author: required only if you select display type `simple`.

In the **(2)** meta box, you can select or create new categories for portfolio. Note that the categories will be used to **filter** portfolios in **Portfolios** archive page (e.g. page with template **Portfolios** or **Portfolios Hexagon**).

In the **(3)** meta box, simply select featured image for the portfolio as a normal post. You can choose the same image that you have uploaded in **(1)** meta box or a new one. This image will be used to display as portfolio thumbnail.


## Post Formats

[Post Formats](http://codex.wordpress.org/Post_Formats) is theme feature which is a piece of meta information that can be used by a theme to customize its presentation of a post.

In short, with a theme that supports Post Formats, a blogger can change how each post looks by choosing a Post Format from a radio-button list.

TheM theme supports the following post formats:

- `gallery` - A gallery of images, which will be displayed in a responsive image slider, powered by Flexslider.
- `link` - A link to another site.
- `image` - A single image, which will be shown above post title.
- `quote` - A quotation.
- `video` - A single video, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed above post title.
- `audio` - An audio file, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed using a powerful HTML5 audio player – jPlayer.

Each post format will have an icon near post title which tells you what post format is. Using post format in TheM lets you differentiate post from each other and make the blog page / single page looks more beautiful.

[See blog page](http://themes.fitwp.com/whisper/blog/) to see how post formats look.


### Setup Post Formats

When you edit a post, select a format you want to apply to that post on the **Format** meta box on the right:

![formats](http://docs.fitwp.com/whisper/post-formats-box.png)

When you choose a format, a corresponding meta box will appear **below** the content editor, here's the list of them:

![formats](http://docs.fitwp.com/whisper/post-formats-boxes.png)

All you need to do is just enter **all** information in the fields in these meta boxes. This information will be used to decorate the post. For example: gallery post format will uses uploaded images to show a slider above post title, a video post will display a video player above post title, etc.


### Portfolio Formats

In TheM, post formats is not only used for posts, but also for portfolios. This is used to display the portfolio icon, like this:

![formats](http://docs.fitwp.com/whisper/formats-icons.png)

When you edit a portfolio, simply select a format you want to apply to that post on the **Format** meta box on the right:

![formats](http://docs.fitwp.com/whisper/post-formats-box.png)

That's all! There's no meta box for you to enter more information like for post (because the format is used to show icon only!).


## Page Templates

TheM has some build-in page templates that can help you create special pages easier:

- **Blog**: template to display blog posts
- **Blox Boxes**: display blog posts in boxed style
- **Contact**: template for contact page
- **Contact Without Map**: template for contact page but without Google Maps
- **Portfolio**: display portfolios
- **Portfolio Hexagon**: display portfolios in creative hexagon style

When you edit a page, look at on the right, find **Page Attributes** meta box and select a template from the dropdown **Template**:

![page-templates](http://docs.fitwp.com/whisper/page-templates.png)

For **Blog**, **Blog Boxes**, **Portfolio**, **Portfolio Hexagon**, there's no configurations at all. After select page template from the meta box on the right, you just need to save the page and see it in action in the frontend.

For **Contact** and **Contact Without Map**, there're some options as below.



### Contact Page

There is a special case for contact page. When you select **Contact** from the **Page Attributes** dropdown, a meta box will appear that lets you enter your contact info:

![contact](http://docs.fitwp.com/whisper/contact.png)

**(1)**: contact form shortcode. If you don't want to use default contact form (maybe you need more information from users like Country, Postcode, etc.), you can use a form plugin like Contact Form 7 or Ninja Forms, Gravity Forms. Those plugins provide shortcode for each form, and you just need to paste the shortcode into this field.

**(2)**: your contact email

**(3)**: your phone number

**(4)**: your address. When you enter the address in the text field, you'll see a list of suggested address that Google Maps found. Simply select one of them, then the map will show the correct area.

If you don't see your address in the suggested list, click the **Find Address** button **(5)**, Google Maps will try its geolocation service to find your address on the map.

**(5)**: when the map displays correct area, you can drag, zoom the map to find your exact location. Then **click** on the map to place a marker. You then can also **drag and drop** the marker to another location if you want.

**(6)**: search for your location in case you don't see list of suggested location from Google Maps.

When you entered all information, save the page and see it in the frontend.

**Note**: You also should enter page content in the editor, this content will be display on the Contact Page as well.



### Contact Page Without Map

This page template is similar to Contact Page above and has same options. The difference is there's no Google Maps on this page, and thus no options for maps.



## Widgets

TheM plays nicely with default WordPress widgets. Besides that the theme has some additional widgets that might be useful for you:




### TheM - Tweets

Before you use the Tweets widget, you have to create a Twitter app. Following these steps:

- Go to [https://dev.twitter.com/apps](https://dev.twitter.com/apps) and click **Create a new application** button.

![twitter-app](http://docs.fitwp.com/whisper/twitter-app.png)

- Fill in all information needed for the app. The name and description can be anything, it does not have to be a certain name. You can leave the Callback URL field empty.
- After creating the app, click **Create My Access Token** button to generate the necessary codes.
- Now go to app Dashboard and selec **OAuth tool** tab and copy the following fields:
	+ Consumer key
	+ Consumer secret
	+ Access token
	+ Access token secret

These fields will be used in the tweets widget.

Now go to your website admin area, then `Appearance > Widgets`, drag and drop **TheM - Tweets** widget into a sidebar that you want it to show there. You'll see these fields like this:

![tweets](http://docs.fitwp.com/whisper/tweets.png)

You also need to enter **Cache time** (2) - which is the time your tweets will be temporarily stored in WordPress cache, **Twitter username** (3) and **Number of tweets** (4).

After filling all information, just click **Save**.



### TheM - Social Links

This widget shows links (with icons) to your social network profiles. It's exactly the same as `[social]` shortcode. All you need to do is just enter URL to your social network profiles and optionally title for each link.



### TheM - Social Feed

This widget shows items from the feed of creative social networks: Pinterest, Deviant Art, Flickr, Dribbble, Youtube, Instagram and Newsfeed (RSS). It uses `[social_feed]` shortcode to display items.

The configuration for this widget is simple:

- Choose a network that you want to display items from
- Enter your username
- And enter the number of items will be displayed



### TheM - Recent Posts

This widgets replaces default WordPress recent posts widget. It displays recent posts in much more beautiful way and gives
you more control to what will be shown.

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



### TheM - Tabs

This widgets displays popular posts, recent posts and recent comments in a tabbed widget. Each tab has its own options. For popular posts and recent posts, the options are similar to the Recent Posts widget above.

Note that popular posts is counted based on number of comments.
