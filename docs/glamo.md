---
layout: docs
title: Glamo Documentation
description: Glamo WordPress theme documentation
---

Welcome! First of all we want to thank you for purchasing our Glamo WordPress Theme.

In the following sections we will explain how to set up and use Glamo theme the easiest way possible. Although there're a lot of things written in this documentation, the theme itself is not hard to use. You can go to the Theme Options page and explore everything yourself. This file is more of a reference if you do not know what to do, or if you are not familiar with WordPress.




## Resources

- **Online Documentation:** (this file) /glamo/
- **Support Forum:** http://fitwp.com/envato-support/




## Theme Information

- **Theme Name:** Glamo WordPress Theme
- **Author:** FitWP
- **Theme URL:** http://fitwp.com/themes/glamo/
- **Author Website:** http://fitwp.com




## Files Included

The download package (`.zip`) that you get from ThemeForest contains the following files and folder:

- `glamo.zip`: main theme file that need to be uploaded to host to install Glamo theme
- `demo-content.xml`: demo content file, which contains all pages and posts from live preview website. It will help you to have a first look of how we use Glamo theme
- `demo-product.xml`: demo products file, which contains default products of Woocommerce
- `docs.html`: theme documentation (this file)
- `theme-options.txt`: theme option backup file. You'll need this to restore the default theme options that setup for demo website.
- `Plugins`:
	- `codecanyon-2751380-slider-revolution-responsive-wordpress-plugin.zip`: [Slider Revolution Responsive WordPress Plugin](http://codecanyon.net/item/slider-revolution-responsive-wordpress-plugin/2751380). Completed download package from Codecanyon.net. It's FREE for you to use with Glamo theme
	- `demo-slide.zip`: Slider for business, wedding, bakery page



## Installation




### Install Theme

After you download the `.zip` package from ThemeForest, unzip it. You'll see a file `glamo.zip`, which is the main file that needed to upload and install.

**Notice**: If you download **Installable WordPress file** then that file is the zip file we use to upload and install.

You can either choose to upload and installl the theme using **FTP** or use **WordPress theme install** function.

### Upload and install using FTP

- Unzip `glamo.zip`, you'll get a folder `glamo`
- Use a FTP client like [FileZilla](http://filezilla-project.org/) and upload that folder to `wp-content/themes` folder on your host
- Go to `Appearance > Themes` and activate **Glamo** theme

### Install theme using WordPress install function

- Go to `Appearance > Themes` and click **Add New**
- Select **Upload**
- Click **Browse** and select the `glamo.zip` file
- Click **Install Now**
- When upload and installation progresses are completed, click **Activate**, or go to `Appearance > Themes` and activate **Glamo** theme

![upload](http://docs.fitwp.com/whisper/wordpress-upload.png)




### Install plugins

After installing Glamo, you'll see a notification in the top of the page that says the theme needs some plugins to function properly.

Glamo theme **requires** follow plugins (all are free and available on WordPress.org):

- [Meta Box](http://wordpress.org/plugins/meta-box/)
- [WooCommerce - excelling eCommerce](http://wordpress.org/plugins/woocommerce/)

Glamo theme **recommends** follow plugins:

- [Contact Form 7](http://wordpress.org/plugins/contact-form-7/) plugin (free and available on WordPress.org)
- WR PageBuilder plugin (included in download package)
- [Slider Revolution Responsive WordPress](http://codecanyon.net/item/slider-revolution-responsive-wordpress-plugin/2751380) plugin ($18 on CodeCanyon, included in download package)

Glamo is working perfectly with these plugins. It automatically adds more styles to them to make the design match the theme.

To install these plugins:

- Click **Begin installing plugins**
- You'll be redirect to a page where all needed plugins are listed. Just click on **Install** below each plugin's name
- After installing, if it's required to activate the plugin, just activate

![plugins](http://docs.fitwp.com/glamo/install-plugins.png)




### Install demo content

If you are new to WordPress and have problems with setting up the theme you might want to import the demo content file that comes with the theme. The following actions will import some dummy posts and pages from the live preview:

- Go to `Tools > Import`
- Select **WordPress** from the list
- If you haven't installed the **WordPress import plugin**, a popup window will appears and ask you to install it. Just click **Install Now**. When the installation progress is completed, click **Activate Plugin & Run Importer**. If you have installed this plugin, skip to next step.
- Click **Browse** and select `demo-content.xml` file from the download package
- Click **Upload file and import**
- When you are asked to import author, you can create new author or import to existing author. You also should check the checkbox **Download and import file attachments**.

![import](http://docs.fitwp.com/glamo/import.png)

After completing all above steps, go to `Posts`, `Pages`, `Products`, `Collections` to see imported data.


>**Important:** Due to license of images, we have to remove images in distributed demo content and replace them with placeholers. All images get from [placehold.it](http://placehold.it/), if you have any download errors when import demo-content.xml, problem can be speed of internet connection. Don't worry about that, you can replace with your own images.



### Install demo products

Please follow above steps to import file `demo-product.xml` from download package.

<div class="alert">You should to add category image and description to have best display in Homepage, please go to `Products -> Category` and edit categories you want. You can see the detail guide in Building Homepage/ Featured Categories below.</div>



### Setup homepage and blog page

After install demo content, you'll see a page `Homepage`. This page will be used as the homepage of the website. To set it as homepage, please go to `Settings \ Reading`, under **Front page displays**, please chose **A static page (select below)** and select **Homepage** for **Front page** and **Blog** page for **Posts page**.

![homepage](http://docs.fitwp.com/glamo/homepage.png)




### Setup Menu

Although the theme is working now and it shows menu, but because we haven't created a menu for primary location, the theme will display all pages by default. As the number of pages is large, displaying all of them in the menu is a bad idea.



### Create or edit a menu

Following these steps to create a menu:

- Go to `Appearance > Menus`
- Select an existing to edit, or click **create a new menu**. **Note:** when you import theme data, WordPress automatically create a 3 menus for you: (**Menu Left**, **Menu Right**, **Main Menu**), so select one of them if you want to have same menu as in live preview.
- Select pages from the left meta box and click **Add to Menu**
- On the right, feel free to drag and drop menu items to organize them
- When you're done moving menu items, check **Main Menu** for **Theme locations** at the bottom of the page
- Click **Save Menu**

![menu](http://docs.fitwp.com/glamo/menu.png)

### Add Description And Icon To Menu Item

Follow these steps to show description for *one menu item* as live demo:

- Click to **Screen Options** tab at the top-right corner to open Screen Options panel.
- Select 2 checkboxes **CSS Classes** and **Description**.
- Click to **Screen Options** tab again to close options panel.
- Now you click to the menu item that you want to add description to, anoption panel for this item will show.
- Enter CSS class of icon in **CSS Classes (optional)** text field. You can find all icon classes in the [FontAwesome reference page](http://fortawesome.github.io/Font-Awesome/icons/). For each icon, you have to **enter `fa icon_class`** (where `icon_class` is provided in FontAwesome reference page, e.g. `fa fa-home`) to make it work.
- Enter a short description for that item in **Description** textarea
- After add icons or descriptions or both to all menu items, click **Save Menu** button.

![menu screen options](http://docs.fitwp.com/glamo/menu-screen-options.png)

<div class="alert alert-warning">Note that the menu icon and description are **optional**. You can use them to decorate your menus or leave them empty to use the default clean look.</div>

### Menu Locations

Glamo have 5 locations for Menu by default:

- **Primary Menu Left** and **Primary Menu Right** are used as default locations. They are used to display your menus **when you set Logo Position center** in Theme Options page (we'll talk about this later in Theme Options section).
- **Primary Menu** will be used when you **set Logo Position left or right** in Theme Options page.
- **Secondary Menu** is additional menu that display right bellow the logo. By default, there is no menus in this location.
- **Footer Menu** is used to display a small menu on footer.

Beside displaying menus on other locations, you can display them inside widget areas which we are going to talk about in next section.

You can create many styles of menu by combining menu and logo locations, these are some examples:

- Logo center + Primary Menu Left + Primary Menu Right

![logo center primary menu left right](http://docs.fitwp.com/glamo/logo-center-primary-menu.jpg)

- Logo left + Primary Menu

![logo center primary menu left right](http://docs.fitwp.com/glamo/logo-left-primary-menu.jpg)

- Logo center + Secondary Menu

![logo center primary menu left right](http://docs.fitwp.com/glamo/logo-center-secondmenu.jpg)




### Setup widget areas

Glamo theme has 8 widget areas (sidebars) by default:

- **Topbar Sidebar Left** and **Topbar Sidebar Right**: they are created to display small widgets in topbar of website.

<div class="alert alert-warning">**NOTE**: On mobiles and tablets, all widgets in Topbar Sidebars will be hidden, but [Glamo] Mini Cart.</div>

- **Header Sidebar**: will display widgets in header **only when set Logo Position `left` or `right` and no menu is set for `Primary Menu` location**.
- **Blog Sidebar:** main website sidebar which will be displayed on all blog posts, archive pages, etc.
- **Page Sidebar:** will be displayed on all WordPress pages.
- **Shop Sidebar:** will be displayed on all WooCommerce pages: Products, Product category, Single Product, etc.
- **Home Sidebar:** will be displayed on Homepage template (we'll talk about this template later in **Page Templates** section).
- **Footer Sidebars:** there are 4 default sidebars for footer, each sidebar is a column in the footer. You can change number of columns in footer in Theme Options page (in that case number of footer sidebars will increased or decreased acccordingly).

To setup a sidebar, select it from the right by clicking its title or the arrow down. Then drag and drop widgets from the left to the sidebar area.

![sidebar](http://docs.fitwp.com/whisper/sidebar.png)

That's all! Now you have the website up with all *basic* elements!




## Theme Options

![theme options](http://docs.fitwp.com/glamo/theme-options.png)

The Glamo theme comes with unique, creative and easy-to-use Theme Options page. You can change all theme options in one place!

With Glamo's advanced theme options panel, you can customize just about any part of your site quickly and easily. Every element on the site can have the color changed to your liking. Choose a color scheme for website, select fonts for all headings and body copy, change sizes, colors and line-heights of all fonts, select different footer column layouts, enable or disable several options, upload your own custom favicon, select from various site/page layouts, input custom CSS, set hundreds of other options to easily customize your site!

All options have full description so you can know what you are doing. Just click and save!

Let's go through each section.




### General

![general](http://docs.fitwp.com/glamo/general-option.png)

This sections contains:

- **(1)**: favicon upload, allows you to upload favicon for you website
- **(2)**: touch icon, allows you to upload icon for mobile devices and tablets
- **(3)**: load Bootstrap from CDN. Bootstrap is a part of Glamo theme and loaded within theme's stylesheet, but you can load it from CDN to save the bandwidth and improve performance.
- **(4)**: load FontAwesome Icons from CDN. FontAwesome is a part of Glamo theme and loaded within theme's stylesheet, but you can load it from CDN to save the bandwidth and improve performance.
- **(5)**: show comments on pages, allows you to show/hide comments and comment form on pages.
- **(6)**: enable or disable breadcrumb.
- **(7)**: when breadcrumb is enabled, this option will appear and let you choose which pages breadcrumb will be displayed.
- **(8)**: backup - restore, allows you to backup Glamo options and restore them later, or transfer the saved options between different installs.

Here are the explanations of some options that can help you understand and use them better:



### Favicon Upload

[Favicon](http://en.wikipedia.org/wiki/Favicon) (short for Favorite icon), also known as a shortcut icon, Web site icon, tab icon or bookmark icon, is a file containing one or more small icons, most commonly 16x16 pixels, associated with a particular Web site or Web page. Browsers that provide favicon support typically display a page's favicon in the browser's address bar (sometimes in the history as well) and next to the page's name in a list of bookmarks. Browsers that support a tabbed document interface typically show a page's favicon next to the page's title on the tab, and site-specific browsers use the favicon as a desktop icon.

This is how favicon appears:

![favicon](http://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Wikipedia_favicon_in_Firefox_on_KDE.png/250px-Wikipedia_favicon_in_Firefox_on_KDE.png)

Glamo lets you upload favicon or enter favicon URL in the input box:

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

This option allows you to show/hide comments and comment form on pages. By default, Glamo doesn't display comments and comment form on pages.

**Important**: In case this option is set to "ON", to display comments on pages, you still have to **allow comments** for pages when you edit pages.

![allow comments](http://docs.fitwp.com/glamo/allow-comments.png)

By default, this checkbox is checked (meaning comments are allowed on pages). But in case you want to show comments on all pages, except some specific pages, you can use this checkbox to hide comments for those pages only.



### Backup - Restore

Glamo allows you to backup theme options and restore them later. You can also transfer the saved options data between different installs.

To backup theme options, just copy the text inside the text box and save it into a file on your computer. To import data, replace the data in the text box with the one from the saved file and click **Import Options** button.

After clicking **Import Options**, Glamo will automatically setup all options and refresh the current theme options page, so you can see the options immediately.




### Design

This sections contains:

- **Color Scheme**: allows you to change color scheme of whole website
- **Layout**: allows you to change layout style and layout for whole website, for blog posts and pages
- **Typography**: allows you to change font family, styles, size, line height, color for body text and headings
- **Custom CSS**: allows you to add your custom CSS



### Color Scheme

Glamo theme has **5 predefined color schemes** to choose from: blue, red, green, violet and orange. When you change color scheme of the theme, all links, button background and other elements will change their color or background accordingly.

The default color scheme is red, but you can select any from 5 colors here. After selecting, click **Save Changes** button to save your data. Now go to the frontend and check the colors of links, buttons, etc.

When you select **Color Scheme** section, you'll see the following options:

![color schemes](http://docs.fitwp.com/glamo/design-color-schemes.png)

**(1)**: select built-in color scheme. These are 5 predefined color schemes. When you select one of them, your website elements will change color accordingly.

**(2)**: enable/disable custom color scheme. This option allow you create **custom color scheme**, and you can build unlimited color schemes here! Just enable this and you'll see options below.

**(3)**: primary color. This is primary color for your custom color scheme, used for links, overlay, button background on hover, badges, etc.

**(4)**: secondary color. This is the color used in button background, tag, etc.

**(5)**: this is just some examples of using custom colors to built your own color scheme. These are *real* example which are used to build 5 predefined color schemes. You should start with these values and adjust them.



### Layout

This section helps you to select which layout will be use in whole website.

![layout](http://docs.fitwp.com/glamo/design-layout.png)

**(1)**: site layout for **blog, single posts and other archive pages**. You can select sidebar position here: `left`, `right` or `none` (don't display sidebar).

**(2)**: sidebar layout for **pages**. Same meaning as for blog above.

<div class="alert alert-info">These options is site-wide, meaning for whole website. But you still can set **custom layout for single page when edit** (We'll explore it later).</div>

**(3)**: sidebar layout for **WooCommerce pages**. Same meaning as for blog above but only applied for WooCommerce pages: **shop page, single products, product tag archive, product category archive**.



### Typography

![typography](http://docs.fitwp.com/glamo/design-typography.png)

This section helps you to customize fonts for **body text** and **headings** on your website. For each element, you can customize:

**(1)**: font family. Just select from the dropdown font family you like. Glamo supports 3 normal fonts (Arial, Verdana and Times) and 2 Google Fonts (Audiowide and Roboto).

**(2)**: font size. Adjust font size for better look here. Just remember the unit for font size is **px**.

**(3)**: line height. Adjust line height for better look here. The unit for line height is also **px**.

<div class="alert alert-info">For better readability, good value for line height is about 1.4-1.5 x font size.</div>

**(4)**: font styles. You can choose **bold**, **italic**, **underline** or any combination of them.

**(5)**: font color. Click on the button, a color picker will appear and you can now select any color.

**Important**: before customize fonts, remember the default values for fonts. You should customize fonts around these values.

| Element   | Font Family | Font Size | Line Height | Styles | Color    |
| --------- | ----------- | --------- | ----------- | ------ | -----    |
| Body Text | Roboto      | 13px      | 20px        | None   | #3d3d3d  |
| Heading 1 | Audiowide   | 20px      | 20px        | None   | #414141  |
| Heading 2 | Audiowide   | 18px      | 20px        | None   | #414141  |
| Heading 3 | Audiowide   | 16px      | 20px        | None   | #414141  |
| Heading 4 | Audiowide   | 15px      | 20px        | None   | #414141  |
| Heading 5 | Audiowide   | 14px      | 20px        | None   | #414141  |
| Heading 6 | Audiowide   | 13px      | 20px        | None   | #414141  |



### Custom CSS

![custom css](http://docs.fitwp.com/glamo/design-custom-css.png)

This section allows to enter custom CSS that will be output in the `</head>`. This will **overwrite** CSS of theme, so please be careful!

Custom CSS is useful when you want to adjust **small things** for your website. If you have to adjust a lot of things in website, please use [Child Themes](http://codex.wordpress.org/Child_Themes).




### Header
![header](http://docs.fitwp.com/glamo/header-options.png)

This sections contains:

**(1)**: enabel/disable topbar. By default, topbar is enabled.

**(2)**: logo upload, allows you to upload logo for you website. You can either put the URL of the logo into the input box or upload the logo to Media Library. The live preview of the logo will appear below the input.

**(3)**: logo size. Specify logo size in **px** here. It will help you resize the logo to correct dimensions. By default, the good size is **180x180** (it is good if `Center` is set as logo position in the bellow option).

**(4)**: logo margin. Specify logo margin in **px** here. This is useful when you upload logo with different size than recommended. You can *move* logo a little, adjust space to make it look good.

<div class="alert alert-info">You should **resize the logo to correct size** in Photoshop or any image editor before upload. It will keep your logo not resized and small.</div>

**(5)**: Specify logo position. By default, logo position set as **center**.

<div class="alert alert-warning">**Note**: When logo position is not Center, Glamo will not use Primary Menu Left and Primary Menu Right locations to display menu, you need to place a menu to Primary Menu location if want to have menu displayed on header, or use Secondary Menu location instead.</div>

<div class="alert alert-info">**Tip**: Use this option with Topbar option and place Menus in locations, you can create 24 difference header styles. And with Color Scheme you are ready to build unique shops!</div>


**(6)**: header scripts. Enter scripts or code you would like output to `&lt;head&gt;`. It can be:

- `<link>` tag for custom font (from Google Fonts maybe)
- Any meta tag: to show the designer, copyright, etc. in meta tag
- Google Analytics code
- Any Javascript code that need to be execute in `<head>`
- Anything else

<div class="alert alert-error">If you want to put custom CSS here, you're doing **wrong**. There's a section for **Custom CSS** under **Design**, use it instead.</div>



### Shop
![shop options](http://docs.fitwp.com/glamo/shop-options.png)

This section contains only one option to set default image for products. This image will be used for products which don't have thumbnail.

You can paste image URL here or upload the image to Media Library by clicking the upload button (green button).



### Blog

![blog](http://docs.fitwp.com/glamo/blog-options.png)

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

- `Post excerpt`: Glamo will get post excerpt (**B**) and display it. **Remember**: if you don't enter excerpts for post, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
- `Post content`: Glamo will get whole post content (**A**) and display it. This is the default value.
- `Post content before more tag`: Glamo will get only the post content before `more` tag (**C**) and display it.

**(2)**: post content limit. Sometimes you enter a very long text for post excerpt or post content, display such long text in blog and archive pages is not good and harm your website beauty. So we need a way to truncate text to make it shorter. This option is created for that purpose.

Simply specify number of words will be display here. Post content or excerpt will be truncated to exact number of words. You should try changing this value and preview your blog to see what is best for you.

Default value is **55 words**.

<div class="alert">**Important**: this option affects only when you **NOT** choose `Post content before More tag` from the Display option above</div>

**(3)**: readmore text. Default value is **Continue reading**.




### Footer

This section give you options to customize footer area on your website.

![footer options](http://docs.fitwp.com/glamo/footer-options.png)

![footer](http://docs.fitwp.com/glamo/footer.png)

**(1)**: number of columns in footer. It also is the number of footer sidebars (widget areas). Default is 4.

**(2)**: copyright text. You can enter text, HTML and **shortcodes** here. To make you easier to display copyright text, Glamo has default shortcodes that you can enter here:

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

The default value for copyright text is **Copyright &copy;`[year]` `[site_link]`. All rights reserved.**

**(3)**: footer information. Specify some information about your website here, such as allowed payment methods.

**(4)**: footer scripts. Enter scripts or code you would like output before `</body>`. It can be Google Analytics code or any Javascript code.





## WooCommerce Settings

WooCommerce plugin almost works after activated, you just have to edit settings about image size to make sure products are displayed correctly with Glamo.

Here we will show you where to edit these settings.

![woocommerce settings](http://docs.fitwp.com/glamo/woocommerce-settings.png)


**(1)**: go to `WooCommerce > Settings` then click to `Products` tab, the fields we have to edit are located there.

**(2)**: change product image sizes as screenshot.

- Catalog Image: 231x266
- Single Product Image: 410x410
- Product Thumbnails: 50x50




## Page Display Settings

We've seen how to change featured title area, layout style, sidebar layout for whole website. Glamo also supports customizing these things for specific posts and pages.

When you edit a page, you'll see this meta box below the content editor:

![display settings](http://docs.fitwp.com/glamo/display-settings-page.png)

This meta box contains 2 main parts:

1. **Import slider**
1. **Display Settings**
1. **Layout Settings**

Each parts contains some settings as shown in the screenshot above. Let's go through it:

### Import slider

After setting up the page, you need to setup the slider for page like business, bakery, wedding to make it display the same as in live preview.

The download package contains exported slider (Revolution Slider) that help you easier to create sliders. Following the steps below:

**(1)**: Go to **Revolution Slider**.
**(2)**: Click **Import Slider** button.
**(3)**: When a popup appear, click **Browse** and select **demo-slide.zip** file.
**(4)**: Click **Import Slider** button to start import the selected slider.

![import slider](http://docs.fitwp.com/glamo/import-slider.png)





### Display Settings

**(1)**: Hide breadcrumb. If you enable Breadcrumb and allow it to be showed on pages in `Theme Options`, this option allow you to hide Breadcrumb on this page only when you enable it.

**(2)**: Hide page title. As posts, the title of page is showed at top of page content. If you want to hide the title of current page, just select this option.

This is useful if you want to setup landing pages or special pages.

**(3)**: This option allow you to remove spacing bettween header and content, content and footer. This option is useful for creating some special pages, such as homepage (when using pagebuilder - we will show you bellow), or insert a full-width slider / background image at the top of page.



### Layout Setitngs

By default, default layout of pages is set in `Theme Options > Design > Layout`, but in each page Glamo have Layout Settings to allow you to select difference layout and choose which sidebar will be showed within it.

**(4)**: enable/disable custom layout. By default, every pages use default layout. You can select a difference layout for current page when enable this option.

**(5)**: select a specific layout for current page. When you enable custom layout option, this option will be showed to allow you to select a difference layout for current page. There are 3 layouts you can choose: Sidebar left, Sidebar right or Full Content.

**(6)**: select a sidebar. By default, Glamo use `Page Sidebar` for pages, but you can choose another sidebar for a page if you want. When you enable custom layout option and select a layout which has sidebar (`Sidebar Left` or `Sidebar Right`), this options will appear and allow you to select difference sidebar for current page.



## Building Homepage

There are 3 ways to build a homepage in Glamo: use Homepage template which is provided by Glamo theme or use WR Pagebuilder plugin or use Visual  Composer Plugin .

This section will show you how we build our home page using page template `Homepage`, using WR Pagebuilder plugin and using Visual  Composer.




### Using Homepage template

We use Homepage template to build Demo 1.

![homepage](http://docs.fitwp.com/glamo/home.png)

When you add or edit a page, look at on the right, find Page Attributes meta box and select a template `Homepage` from the dropdown Template **(1)**, a meta box called Homepage Settings appear **(2)**.

![homepage template](http://docs.fitwp.com/glamo/homepage-template.png)

You can drag sections to change their order. Now let's go throught each section follow order in homepage.


### Slider

![section slider](http://docs.fitwp.com/glamo/section-slider.png)

**(1)**: enable/disable slider section.
**(2)**: which type of slider you want to use, default slider (collections slider - we'll show you how to add/edit collections later) or custom slider. If you choose custom slider, options **(3)** and **(4)** bellow will disappear and a text field will display for you to enter shortcode of any slider (like Revolution Slider, Layer slider, ... )
**(3)**: select 3 collections to display on section slider like on live demo.
**(4)**: select effect for collection slider


### Promotion

![section promotion](http://docs.fitwp.com/glamo/section-promotion.png)

**(1)**: enable/disable promotion section.
**(2)**: enter the content for this section, html and shortcodes are allowed.

<div class="alert">This section is similar to Custom Content section but it is displayed in the frontend with beautiful fonts to attract visitors.</div>


### Featured Products

![section featured products](http://docs.fitwp.com/glamo/section-featured-products.png)

**(1)**: enable/disable featured products section.
**(2)**: section title. It's "Featured Products" by default.
**(3)**: enter number of featured products will be displayed.


### Featured Categories

![section featured categories](http://docs.fitwp.com/glamo/section-featured-categories.png)

**(1)**: enable/disable featured categories section.
**(2)**: select product categories will be displayed. You should select a even number of categories to has the best view.

<div class="alert">In order to add or change product category image, please go to `Products -> Category` and edit categories you want.</div>

![Edit catergory image and description](http://docs.fitwp.com/glamo/edit-product-category.jpg)

**(1)**: Add description.
**(2)**: Upload image.
**(3)**: Click Update button.


### Recent Products

![section recent products](http://docs.fitwp.com/glamo/section-recent-products.png)

**(1)**: enable/disable recent products section.
**(2)**: section title. It's "Recent Products" by default.
**(3)**: intro message. It allow you to show a custom content before list of recent products (html and shortcodes are allowed)
**(4)**: enter number of featured products will be displayed.
**(5)**: enable/disable sidebar on this section.
**(6)**: select position for sidebar.

<div class="alert">If you enable sidebar on this section, the number of products should be 3, 6, 9... to has the best view. If you dont't, number of products should be 4, 8, 12... And remember to go to `Appearance > Widgets` to add or edit widgets in `Home Sidebar`.</div>


### Logos

![section logos](http://docs.fitwp.com/glamo/section-logos.png)

**(1)**: enable/disable logos section.
**(2)**: edit or delete uploaded logos.
**(3)**: add new logos to this section. Click the button **Select or Upload Images**, a modal window will display. There you can upload images or choose images from the Media Library.


### Custom Content

![section custom content](http://docs.fitwp.com/glamo/section-custom-content.png)

**(1)**: enable/disable custom content section.
**(2)**: enter the content for this section, html and shortcodes are allowed.




### Using WR Pagebuilder

Glamo supports building pages by using page builder plugins: **Visual  Composer** and **WR PageBuilder**.


We use this plugin to build demo 2 "Mobile". You can download sample data of Glamo Mobile demo here: [http://docs.fitwp.com/glamo/demo-mobile.zip](http://docs.fitwp.com/glamo/demo-mobile.zip).

If you want to build home page like "Mobile" demo, you should import demo-content-mobile.xml from demo-mobile.zip instead of demo-content.xml. After successful importing, you go to Pages, chose `Homepage` to edit. Remember to set that page as front page in `Setting -> Reading`.

We include a export of slider that we use in live demo "Mobile" in `demo-mobile.zip` file, you can import it in `Revolution Slider` in admin area.


<div class="alert alert-success">Although Glamo supports **both** WR Pagebuilder and Visual Composer plugins, but using them is **NOT** required. You still can use Glamo for a dedicated shop and it functions just well. But if you need more fancy pages or write beautiful blog posts, using page builder plugins is a good choice.</div>

Here we will show you how to use **WP PageBuilder** which included in Glamo theme to build a page.



### Open page builder

![open wr pagebuilder](http://docs.fitwp.com/glamo/ig-pagebuilder-open.png)

When add or edit pages, you will see 2 tabs `Classic Editor` and `Page Builder` right bellow page title, click to `Page Builder` to open page builder screen add start adding content.

**Note:** Before adding elements to page, you should know that WR PageBuilder organize content in a grid using rows and columns. Each row can contain some columns and each column can contain some elements.

Now let's see how to add rows, columns and elements to page content.


### Add Row

![WR pagebuilder add row](http://docs.fitwp.com/glamo/ig-pagebuilder-add-row.png)

**(1)**: Click the **Add Row** button to add new row.

**(2)**: You can drag and drop a row in vertical direction to change its order.

**(3)**: You can delete a row by clicking the recycle icon on the right side of the row. If that row contains elements, a alert box will appear and ask you to confirm that you want to delete that row and all elements inside it.

**(4)**: Edit row. When you click the Edit Row icon (above delete row icon), a modal box will appear with options to edit row, let's see what it is:

![wr pagebuilder edit row](http://docs.fitwp.com/glamo/ig-pagebuilder-row-options.png)

- **Width**: select the width of row, boxed or full width. By default it is boxed.
- **Background**: select background type of row: none, solid color, gradient, pattern or image, then set it up.
- **Border**: specify row border. It contain border with, border type and border color.
- **Padding**: edit padding of row in **px**. By default all values are set to 10px
- **CSS Class**: add css class to row. It is useful when you want to add special style to a row by using `Custom CSS` feature in `Theme Options`.
- **ID**: Set css id to row. As same purpose as **CSS Class**, you can add style to a row by adding ID to it.


### Add Columns

![ig pagebuilder add columns](http://docs.fitwp.com/glamo/ig-pagebuilder-add-columns.png)

There are 2 way to add columns into a row: add them manually or user pre-defined layout.

**(1)**: add columns manually by clicking the **Add Column** button on the right side of row. You can add maximum 12 columns.

**(2)**: you can resize column by clicking to 3 dots icon between columns and drag it to left or right side.

**(3)**: add column by using pre-defined layout. When you hover your mouse over the Add Row button, a list of pre-defined layout will appear, just click to a layout and you have a new row with columns inside.


### Add Elements

![ig pagebuilder add elements](http://docs.fitwp.com/glamo/ig-pagebuilder-add-elements.png)

Inside each row, you will see Add Element button at bottom, just click to it, a modal box appear, it contain all avaiable elements that supported by IG Pagebuilder plugin.

![ig pagebuilder elements](http://docs.fitwp.com/glamo/ig-pagebuilder-elements.png)

Select element you want to add by clicking it, a new modal box will appear. It allows you to setup the element with many options. After done, click **Save** button to add the configured element into column.


**Note:** To know in details how to setup/configure each elements, please see the WR PageBuilder documentation from included pakage or use online documentation [here](http://www.woorockets.com/docs/wr-pagebuilder-user-manual/).


### Using Visual Composer

<div class="alert alert-warning">**Note:** Visual Composer is **not** included in Glamo. To use Visual Composer, you have to [purchase the plugin at CodeCanyon](http://codecanyon.net/item/visual-composer-page-builder-for-wordpress/242431?ref=fitwp).</div>


We use this plugin to build demo 3 "Restaurant".  You can download sample data of Glamo Restaurant demo here: [http://docs.fitwp.com/glamo/demo-restaurant.zip](http://docs.fitwp.com/glamo/demo-restaurant.zip).

If you want to build home page like it, you should import demo-content-restaurant.xml instead of demo-content.xml. After successful importing, you go to Pages, chose `Homepage` to edit. Remember to set that page as front page in `Setting -> Reading`.

You can see the detail how to use Visual Composer in documentation which included in plugin package when you buy it or watch tutorial videos [here](http://vc.wpbakery.com/video-academy/).

We include a export of slider that we use in live demo "Restaurant" in `demo-restaurant.zip` file, you can import it in `Revolution Slider` in admin area.

<div class="alert alert-warning">**Important:** At this time, plugin WR Pagebuilder is not competible with Visual Composer, so please deactive WR Pagebuilder if you want to use Visual Composer.</div>



## Add/Edit Collection

Glamo has a custom post type called Collection to show photos as a slider (we talked about that slider above, in Homepage template section). When you add or edit a collection, you will see following options:

![collection](http://docs.fitwp.com/glamo/collection.png)

**(1)**: edit or delete image from gallery.

**(2)**: add new images to gallery. Click the button **Select or Upload Images**, a modal window will display. There you can upload images or choose images from the Media Library.

**(3)**: featured image. It is optional options, you can set the featured image for current collection here. Buy default, it use the first image from gallery.





## Post Format

[Post Formats](http://codex.wordpress.org/Post_Formats) is theme feature which is a piece of meta information that can be used by a theme to customize its presentation of a post.

In short, with a theme that supports Post Formats, a blogger can change how each post looks by choosing a Post Format from a radio-button list.

Glamo theme supports the following post formats:

- `gallery` - A gallery of images, which will be displayed in a responsive image slider, powered by Flexslider.
- `link` - A link to another site.
- `image` - A single image, which will be shown above post title.
- `quote` - A quotation.
- `video` - A single video, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed above post title.
- `audio` - An audio file, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed using a powerful HTML5 audio player provided by Wordpress as default player.

Using post format in Glamo lets you differentiate post from each other and make the blog page / single page looks more beautiful.

[See blog page](http://themes.fitwp.com/glamo/blog/) to see how post formats look.



### Setup Post Formats

When you edit a post, select a format you want to apply to that post on the **Format** meta box on the right:

![formats](http://docs.fitwp.com/whisper/post-formats-box.png)

When you choose a format, a corresponding meta box will appear **below** the content editor, here's the list of them:

![formats](http://docs.fitwp.com/whisper/post-formats-boxes.png)

All you need to do is just enter **all** information in the fields in these meta boxes. This information will be used to decorate the post. For example: gallery post format will uses uploaded images to show a slider above post title, a video post will display a video player above post title, etc.





## Widgets

Glamo plays nicely with default WordPress widgets. Besides that the theme has some additional widgets that might be useful for you:



### [FitWP] Flickr

This widgets displays list of photos which is get from a user or group on [Flickr](http://flickr.com).

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

![twitter app](http://docs.fitwp.com/glamo/twitter-app.png)

- Fill in all information needed for the app. The name and description can be anything, it does not have to be a certain name. You can leave the Callback URL field empty.
- After creating the app, go to **API Keys** tab then click **Create My Access Token** button at the bottom to generate the necessary codes. It usually take 10 - 15 seconds to generate these codes, you have to reload that page to see your code in **Your Access Token** seciton.

![twitter app](http://docs.fitwp.com/glamo/twitter-app-token.png)

- Now you can copy the following fields for setting up Latest Tweets widget:
	+ API key  -> Consumer Key
	+ API secret -> Consumer Secret
	+ Access token -> Access token
	+ Access token secret -> Access token secret

These fields will be used in the tweets widget.

Now go to your website admin area, then `Appearance > Widgets`, drag and drop **[FitWP] Latest Tweets** widget into a sidebar that you want it to show there. You'll see these fields this:

![tweets](http://docs.fitwp.com/glamo/widget-tweets.png)

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



### [Glamo] Account Links

This widget shows links to login page and register page. We created this widget with main purpose is help administrators display login link or register link or both in topbar easily.


### [Glamo] Social Links

This widget shows links (with icons) to your social network profiles. All you need to do is just enter URL to your social network profiles and optionally title for each link.


### [Glamo] Mini Cart

This widget shows the shopping cart in minimized size. We prefer you to use it instead of WooCommerce Cart widget when you want to show shopping in Topbar or Header Sidebar.
