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

 1. Get the demo import plugin from the download package on ThemeForest

 2. Go to **Plugins → Add New** in the dashboard, then click **Upload Plugin**

![upload](http://i.imgur.com/f326I3H.png)

 3. Choose the `.zip` file you downloaded in step 1 and click **Install Now**.

![install](http://i.imgur.com/zCJlsg0.png)

4. After installing the plugin, click **Activate** link to activate it.

5. Go to **Tools → Import Demo** and click **Import Demo Content** button.

It takes a couple of minutes to process all the content. After done, go to the frontend and enjoy the theme.

#### Important:

The demo import plugin has a large file size (50 MB), because we **already included all the images**. So when you install, you get the exact demo as you see.

However, as the file size is big, some hosts may disallow to upload. To fix the problem, follow these steps:

1. Unzip the file `them-demo-import.zip` to `them-demo-import` folder
2. Use a FTP client software ([FileZilla](https://filezilla-project.org/) works great for us) and upload that folder to `wp-content/plugins`

![filezilla](https://i.imgur.com/K4LQHuG.png)

3. Then go to your **Dashboard → Plugins** and activate the plugin.

4. Go to **Tools → Import Demo** and click **Import Demo Content** button.



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

### Section: Featured Content as Creative Slider

Slider are a collection of featured posts that are displayed in a special slider with an unique effect for text and image. You are able to select which posts to show in the slider as well as which elements to show. This is a good place if you want to highlight the best posts in your blog.

In the **Homepage** sidebar in the **Customizer**, click button **Add a Widget**, you will see a list of available widgets on the right where you can search for widgets and add them. Here we will search for **TheM: Featured Posts** widget and click on it to add to the **Homepage** sidebar.

![slider](http://i.imgur.com/7udjMtF.png)

The widget has several options for you to adjust:

Option|Description
---|---
Number of posts|The number of posts you want to show in the slider (e.g. the number of slides).
Category|Which category you want to get posts from. Select **All** if you want to show posts in all categories.
Tag|Which tag you want to get posts from. Select **All** if you want to show posts in all tags.
Show date|Do you want to show post date? Date will be rotated 90 degree to have a good effect. You should enable this for the slider.
Date format|The date format. By default it takes WordPress settings in **Settings > General**.
Show excerpt|Do you want to show post excerpt in the slider? The post excerpt is taken from post excerpt and fallback to the post content.
Excerpt length|The number of words of post excerpt you want to show in the slider. The recommended number is 40.
Show read more button|Do you want to show read more button?.
Read more text|The read more text.
Display as|Choose which format you want to show the featured content. There are 4 styles that you can select from: creative slider (as shown in demo Creative, full width slider - in demo Travel/Girl, single post slider - in demo Lifestyle/Minimal, grid - in demo Creative/Food)
Slider speed (ms)|The number of milliseconds between slides.
Hide these posts in the home page|Whether to exclude these posts in the post list in the homepage to remove duplication?

**Tip**: To select specific posts for the slider, you can create a specific tag and add it to the posts you want to show. Then in this widget, select that tag.

### Section: Featured Content as Grid

Similar to creative slider, the grid of featured posts displays posts in a 3-column or 4-column grid. This is also a good place to highlight your posts.

The grid of featured posts uses exactly the same widget as the slider (**Featured Posts**). The only difference is you do not check the option to **Display as slider**.

**Note**: In order to have a best view, you should set the number of posts to 3 or 4.

### Section: Featured post

The **Featured Post** widget allows you to show a single post in the homepage beautifully. That's a good option to show the post that hightlights the main content of your blog.

To add the widget into the homepage, select **TheM: Featured Post** from the widget list:

![featured](http://i.imgur.com/iQLqcPD.png)

The widget has several options for you to adjust:

Option|Description
---|---
Select post|Select the post you want to show.
Thumbnail|Select position for the thumbnail. In the demo, we use this widget twice: one with thumbnail left and one with thumbnail right to give a good affect of view.
Show date|Do you want to show post date? Date will be rotated 90 degree to have a good effect. You should enable this.
Date format|The date format. By default it takes WordPress settings in **Settings > General**.
Show excerpt|Do you want to show post excerpt? The post excerpt is taken from post excerpt and fallback to the post content.
Excerpt length|The number of words of post excerpt you want to show. The recommended number is 40.
Show read more button|Do you want to show read more button?.
Read more text|The read more text.

### Section: Instagram

The **Instagram** widget displays the latest images from your stream on Instagram or from any person or from any tag in a beautiful grid or carousel slider. It's quite flexible and gives your blog an impressive look.

To add the widget into the homepage, select **TheM: Instagram** from the widget list:

![instagram](http://i.imgur.com/UeEcaSd.png)

The widget has several options for you to adjust:

Option|Description
---|---
Title|The title of the widget. It's usually not used in order to display the images more cleaner.
User ID|Your user ID. In order to get your user ID, click the link above this field **Authorize and get your Access Token and User ID here**. You will be redirected to Instagram to login if you haven't. Then you will be asked to authorize the app to access to your account. Don't worry, the app only sees your basic info like username and email. Then you will be redirected to a page where your user ID and access token are displayed.
Access token|Your access token that you will get in previous step.
Cache time|The number of seconds that the widget cache the content from Instagram. This prevents continual sending requests to Instagram which might be blocked if the frequency is too low. A good option is 3600 (1 hour).
Number of images|The number of images you want to show. If you don't show images as a carousel slider (the option below), then you should set this number to 4.
Other user ID|Use this option if you want to display images from an other person than yourself. To get other user's ID, click the link **Click here to get other person's ID** below the input.
Tag|If you want to get images not from yourself, but from a tag in Instagram, then enter the tag here.
Display as carousel slider|Do you want to show images in a carousel slider (as displayed in the demo)? If not, images will be shown in a grid.

## Theme options

After done installing and setup the theme, you might want to customize the theme to fit your needs. All the theme customization are location in *Customizer → Theme Options*. You can change all theme options in one place and preview the changes in real-time! There are various options for the theme and they'll be explained in the sections below

### General options

![favicon](http://i.imgur.com/FHj5yOZ.png)

The general options is located under *General* section. There is only 1 option for the website site icon. The site icon is an icon associated with a website or webpage intended to be used when you bookmark the web page. Web browsers use them in the URL bar, on tabs, and elsewhere to help identify a website visually. Also, it is used as application icon of mobile device.

To add a site icon, follow these steps:

1. Click the Add a Site Icon button.
1. Click the Choose File button to select the desired icon.
1. Click the Upload Image button.
1. Crop your image. You can use the Preview section on the right to see what your image will look like in its final form.
1. Click the Crop Image button.
1. That's it! You're shiny new Site Icon is ready to go!

### Header options

#### Top bar

The top bar is divided into 2 parts: the top bar left and top bar right. Each part can have the following content:

- Social icons
- Functional icons (search, cart, mobile menu icons)
- A custom menu
- Custom text

By default top bar left displays social links and top bar right displays functional icons. To change which is displayed in the top bar left, please go to *Customizer → Theme Options → Header* and you will see the options as follows:

![header options](http://i.imgur.com/K2lXvNs.png)

Simply select which type of content you want to display for each part of the top bar.

If you want to display text , simply select **Text** option and enter the text in the input below. Note that you can enter HTML here, so it's good for you to display a welcome text with a link or something.

If you want to display social links in the top bar, then you need to create a custom menu for social links and set it to display here. To do that, follow these steps:

- Go to **Customizer > Menu** and click the button **Add a Menu**.
- Click the button **Add Items** and select **Custom Links** in the list.
- Enter link to your social profile and click **Add to Menu**.
- Repeate the process to add more links to your social profiles in other social networks.
- When you're done, check the checkbox **Social Links Menu** in the section **Menu locations** to make it display in the top bar.

![social menu](http://i.imgur.com/0Qn4al9.png)

If you want to display a custom menu in the top bar, then you need to create a custom menu and set it to display here. To do that, follow these steps:

- Go to *Customizer → Menu* and click the button **Add a Menu**.
- Click the button **Add Items** and select **Custom Links** in the list.
- Enter link to your social profile and click **Add to Menu**.
- Repeate the process to add more links to your social profiles in other social networks.
- When you're done, check the checkbox **Top Bar Left/Right Menu** in the section **Menu locations** to make it display in the top bar.

![top bar menu](http://i.imgur.com/wplleaO.png)

**Note**: when you set a menu for social links, these links will be displayed in the footer and **About me** widget as well as in the mobile menu.

#### Logo

By default, TheM display the site title but you can change that to display site logo. The site logo feature requires WordPress 4.5, so you need to upgrade your WordPress to version 4.5 if you have an older version. If you couldn't upgrade, then the only option for you is displaying the site title.

In order to add logo to your site, go to *Customizer → Theme Options → Header* and click the button **Select logo** to upload the logo or select from the Media Library.

![header options](http://i.imgur.com/K2lXvNs.png)

You also can choose the logo position below as center (default), left or right.

When choosing the position left or right, you have an option to minimize the main menu to the toggle icon like in the [Minimal demo](http://demo3.fitwp.com/them4/)

#### Main menu

Although the theme is working now and it shows menu, but because we haven't created a menu for primary location, the theme will display all pages by default. As the number of pages is large, displaying all of them in the menu is a bad idea.

Following these steps to create a menu (here we will use the WordPress Dashboard instead of the Customizer because this allow us to add mega menu as described in the next section):

- Go to *Appeance → Menus*
- Select an existing to edit, or click **Add a menu**. **Note:** when you import the demo, you already have a menu **Main**, so select it if you want to have same menu as in the demo.
- Click **Add items** to add items to the menu
- When you're done adding menu items, check **Primary Menu** for **Theme locations** at the bottom of the page

![menu](http://i.imgur.com/aZHKqtb.png)

#### Mega menu

One of the best feature of TheM is mega menu. The mega menu allows you to display custom content in the menu, not only links. You can choose to display custom text or post list in the menu.

In order to use mega menu, you need to use the WordPress Dashboard, not the Customizer. Go to *Appearannce → Menus* and follow the steps below:

Click on a top-level menu item to edit it, you will see an checkbox for **Enable mega menu?** This option allows you to display its submenu items in a mega menu:

![mega](http://i.imgur.com/2i0Orz6.png)

Then add a **Custom Link** as a submenu item for this item, you will see the following options:

![submenu](http://i.imgur.com/Xo7RPIX.png)

Let's break it out:

Option|Description
---|---
Layout|The layout of this submenu item.
Item type|The type of the content of this submenu item. It has 2 options: **Text** which displays a custom text (similar to text widget in WordPress) or **Posts** which displays a list of posts.

If you choose item type **Text**, you will see an option for the **Content**. Simply enter the content you want to display. HTML and shortcodes are allowed. (See the screenshot above)

If you choose item type **Posts**, then you will see more options like this:

![submenu posts](http://i.imgur.com/0sW8Ebb.png)

Option|Description
---|---
Number Of Posts|How many posts you want to displayed. It should be fit to your layout, e.g. if you choose layout 3/4, then you should set the number of posts 3.
Category|You can choose to display posts from all categories, or a specific category
Tag|You can choose to display posts from all tags, or a specific tag
Show Date|Whether or not show post date
Date Format|Date format. Click the [?] link for a full list of supported date formats
Show Excerpt|Whether or not show post excerpt
Excerpt Length|The number of words of post content will be displayed

After done editing, click **Save Menu** and see it in action in the front end.

#### Mobile menu

There is also 1 option for the mobile menu here. The mobile menu is displayed when you click on the toggle icon on the top bar (if you choose top bar left / right dislays functional icons, or you can see it on mobile devices). The option allows you to select which type of content will be displayed in the mobile menu: the main menu and social icons or widgets.

If you choose the main menu and social icons then all items of the main menu and social icons will be displayed in the mobile menu.

If you choose widgets then you need to go to *Customizer → Widgets* and you will see a new sidebar **Mobile**. Simply add new widgets to this sidebar and they'll displayed in the mobile menu.


### Footer options

The footer of TheM is simple and has only 2 parts: the **social links** and **copyright text**. The social links is automatically pulled from the **Social Links** menu that we have covered in the section [#top-bar](Top bar) above. Please read this to understand how to setup the social links menu.

Go to *Customizer → Theme Options → Footer* to start customizing the footer.

![footer options](http://i.imgur.com/pFIVJr3.png)

Options|Description
---|---
Hide social links|Whether to hide social links
Footer text|The footer copyright text. You can enter HTML and shortcodes here.
Footer background|Upload or select an existing image from the Media Library for for the footer background.
Footer background position|Where do you want the footer background image align?
Footer background size (width height)|Enter CSS for background size
Footer background repeat|Do you want the background image repeated?
Show go to top button|Do you want to show go to top button?

### Blog options

The blog options is located in *Customizer → Theme Options → Blog*. There are several options as follows:

![blog options](http://i.imgur.com/3P8LvjQ.png)

Options|Description
---|---
Blog sidebar layout|The sidebar layout for the blog (left, right or no sidebar)
Hide post thumbnail on blog archive page|Do you want to hide post thumbnails on the blog page? See [Minimal demo](http://demo3.fitwp.com/them4/)
Content display on blog archive page|What type of post content will be displayed. Available options are Post excerpt, Post content or Post content before more tag. To understand what those values mean, take a look at the screenshot bellow:

![post content](http://i.imgur.com/VaeOhBI.png)

Where:

- (A): Whole post content, this is what you enter in the editor.
- (B): Post excerpt, which is optional hand-crafted summaries of your content. [Learn more about manual excerpt](http://codex.wordpress.org/Excerpt). If you don’t enter anything in the excerpt box, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
(C): The post content before more tag
(D): The more tag

Return to blog option: if you choose

- Post excerpt: The theme will get post excerpt and display it. Remember: if you don’t enter excerpts for post, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
- Post content: The theme will get whole post content and display it. This is the default value.
- Post content before more tag: The theme will get only the post content before more tag and display it.

Options|Description
---|---
Post content limit (words)|The number of words of the post content will be displayed in the blog page.
Read more text|The read more text
Pagination style|The pagination style. The theme supports 4 pagination style: next/prev style (see [Travel demo](http://demo3.fitwp.com/them2/), numeric style, infinite scroll (see [Minimal demo](http://demo3.fitwp.com/them4/), load more button (see [Creative demo](http://demo3.fitwp.com/blog/category/discovery/). Note that if you choose infinite scroll or load more button style, you need to install the Jetpack plugin and activate the Infinite scroll module.
Pagination load more text|The load more text for the load more button. Only applied if you choose load more button style.
Hide related posts on single post|This option allows you to hide related posts on single post. It's useful if you use another related posts plugin.

### Color options

TheM allows you to change the color scheme and colors of some elements to have an unique look and feeld. There is no limit to pick colors in TheM.

To start customizing the colors, please go to *Customizer → Theme Options → Colors* and you'll see the following options:

![color options](http://i.imgur.com/wVfOm36.png)

To change the color scheme of the theme, you need to adjust 2 colors:

Options|Description
---|---
Primary color|The primary color for the theme, which is used for links, buttons, social icons. Default is black.
Secondary color|The secondary color for the post meta, categories, post date. Default is gray.

To personalize the theme, TheM add the following options for you to customize the top bar, the primary menu and some elements, all are self-explained by their name:

- Top bar background color
- Top bar text color
- Top bar link color
- Top bar link hover color
- Primary menu link color
- Recent posts heart icon color

### Typography options

One of the coolest features of the TheM theme is custom typography. This feature allows you to select custom fonts, font sizes, font styles for various elements on the website without touching code. TheM supports all Google Fonts (more than 700 fonts) which is the largest free collection of fonts available on the Internet.

To start using custom fonts for TheM, please go to the *Customizer → Theme Options → Typography* and you’ll see the following screenshot:

![font options](http://i.imgur.com/ARhLlK4.png)

TheM allows you to change typography for:

- Body text (post content, post summary)
- Headings (H1, H2, …, H6 tags)
- Top bar
- Primary menu
- Post title

These are the main elements of the website and for each element, TheM sets up a necessary group of settings to adjust such as:

- Font family: which can be selected from 700+ fonts from Google Fonts. To see how they look, you can simply select them and see the changes in real-time or go to http://google.com/fonts and search for the font name.
- Font weight: normal, bold, extra bold, etc. Some fonts have only some weights, so make sure you preview the result.
- Font size: in pixels. Leave it blank to use the default value.
- Line height: in pixels. Leave it blank to use the default value.
- Text transform: UPPERCASE, lowercase, Capitalize
- Letter spacing: in pixels. Leave it blank to use the default value.

Note that some elements don't have all the above settings. We add only the settings with a serious consideration that those settings are really needed for the elements.

If you want to change typography for other elements or custom the fonts more deeply, please see the documentation for custom CSS in the Design options section.

### Portfolio options

TheM has a built-in portfolio section which shows your projects in a beautiful masonry grid with a filter. This is a great way to show to your visitors what you have done in the past by highlighting previous projects.

The settings for portfolio are simple and put in **Customizer  → Theme Options → Portfolio**:

![portfolio settings](http://i.imgur.com/Wz0zeGP.png)

There are only 2 options:

- Portfolio archive page title: The title for portfolio archive page (at http://yourdomain.com/portfolio). By default it's just "Archive" which is useless. Enter something meaningful here like "Portfolio", "Our works", "Recent Projects", etc.
- Number of projects per page: The number of projects shown in 1 page in the archive page. Note that by default if you choose pagination style Next/Prev links or numeric links (in the **Customizer  → Theme Options → Blog** section), then all portfolios are get and organized in a masonry layout. In these cases, this option is not applied. It's only applied if you choose pagination style Infinite scroll or Load more button where some projects are loaded when scrolling or clicking the button.

### WooCommerce options

TheM supports [WooCommerce](https://wordpress.org/plugins/woocommerce) plugin - the best and most popular e-commerce plugin for WordPress. Essentially, you do not need to do anything. TheM smoothly integrates with WooCommerce and setup everything for you.

To change the options of TheM for WooCommerce, please go to **Customizer  → Theme Options → WooCommerce**:

![woocommerce settings](http://i.imgur.com/VTH8HQu.png)

There are only 1 option for the number of products shown on shop page. This option overwrites default WordPress/WooCommerce options which makes you can customize the shop page better.


## Add/Edit Portfolio

TheM has a built-in portfolio section which shows your projects in a beautiful masonry grid with a filter. This is a great way to show to your visitors what you have done in the past by highlighting previous projects.

To start using portfolio, please install the [Jetpack](http://jetpack.me) plugin. This is a very popular plugin made by Automattic, the company behind WordPress. It allows you to create portfolio, testimonials, add related posts and many more.

Creating a portfolio project is as simple as creating a post. Go to *Portfolio → Add New* and add new project title, content and set featured image as follows:

![add portfolio](http://i.imgur.com/ryDRly4.png)

In the portfolio project content, you can put anything about the project such as project description, client name, date, etc. Remember to use HTML elements and custom CSS classes to style the content beautifully.

Do not forget to add project types on the right. It's used to filter the projects in the portfolio page.

After finishing adding basic content for projects, please fill in all the information about the project in the **Project Settings** meta box:

![edit project](http://i.imgur.com/Lh7nuNZ.png)

Now go to the frontend and view all projects at http://yourdomain.com/portfolio/


## Custom sidebar for page content

You already see how to setup the homepage with a custom sidebar and widgets. This is a very flexible way to add and organize content to a special page like the homepage.

This section shows you how to do the same for other pages, not just only homepage.

Basically it requires 3 steps:

### Create a custom sidebar

To create a new custom sidebar, go to *Appearance → Sidebars*:

![sidebars](http://i.imgur.com/WuV1wdn.png)

On this page, you will see a list of created sidebar. If you want to create a new sidebar, simply enter new sidebar name in the input box. Click **Add more** button if you want to add multiple sidebars. Then click **Save changes** to submit the changes.

Finishing this step, you will see all custom sidebars listed in the beginning of the page.

### Add widgets to the sidebar

After creating custom sidebars, go to *Appearance → Widgets* and you will see new sidebars listed as a widgetized area.

![widgets](http://i.imgur.com/XMiZlsn.png)

Now you can drag and drop any widget to the new sidebar. There's nothing different between custom sidebar and normal WordPress sidebar.

### Assign sidebar to a page

After done adding widgets to the new custom sidebar, now go to edit a page that you want to use the custom sidebar for its content.

On the right of the editing page, you will see a box **Custom sidebar content** where you can select a custom sidebar for the page content:

![sidebar content](http://i.imgur.com/dMfYxea.png)

After selecting the sidebar, go to the frontend and you will see the widgets of that sidebar is added below the main content of the page.



## Widgets

TheM plays nicely with default WordPress widgets. Besides that the theme has some additional widgets that might be useful for you. In order to add widgets to your website, simply go to *Customizer → Widgets* or *Appearance → Widgets* and select widgets begin with **TheM** to your website. All the options of the widgets are self-explained.

### TheM: About

This widget shows your personal information in a beautiful format. To start using it, just drag and drop the **TheM: About** widget into the primary sidebar or any sidebar you want to show (we recommend Primary sidebar and Mobile sidebar). This widget has the following options:

![about widget](http://i.imgur.com/WW3pxtK.png)

Options|Description
---|---
Title|The widget title
Image|Your image. Click the **Select** button to upload or choose an image from the Media Library
Intro|Intro text about yourself
Show social links from Social Links menu|Display links to your social profiles. Links are get from Social Links Menu.
Social links|If you don't check the checkbox for "Show social links from Social Links menu", then you can enter custom links in each input below.
Signature|Your signature in text. It will be displayed beautifully with a custom Google Font
Signature Image|If you don't want to display signature with text, then upload your signature image here. Click the **Select** button to upload or choose an image from the Media Library.

### TheM: Featured Blocks

This widget shows 3 featured blocks in a grid which you can use to display links to your most favourite content. See [Girl demo](http://demo3.fitwp.com/them6/) to understand how we use it.

This widget has the following options for each block:

![block](http://i.imgur.com/Mo5ynBf.png)

Options|Description
---|---
Image|The block background image. Click the **Select** button to upload or choose an image from the Media Library
Text|The text displayed in the center of the block (with white background)
Link|Where do you want the block link to?

### TheM: Featured Post

This widget displays a specific post in an attractive way. It's very useful when you want to highlight a post in the homepage. See [Creative demo](http://demo3.fitwp.com/) to understand how it works.

The widget has the following options:

![featured post](http://i.imgur.com/cWQnUrz.png)

Options|Description
---|---
Select post|Select the post you want to feature
Thumbnail|Select the thumbnail position. See [Creative demo](http://demo3.fitwp.com/) to understand how it works.
Show date|Do you want to show post date? We recommend enable this.
Date format|The date format. See [this link](http://codex.wordpress.org/Formatting_Date_and_Time) for a full list of supported date formats
Show excerpt|Whether or not show post excerpt
Excerpt length|The number of words of post content will be displayed
Show read more button|Whether or not show read more button
Read more text|The read more text


### TheM: Featured Posts

This is the most important widget in TheM. It displays your featured posts in the home page flexibly. All our demos use this widget to show featured posts.

We already talked about this widget when we setup the homepage above. Here are some more details for you.

![featured posts](http://i.imgur.com/XTJsSmO.png)

The widget has several options for you to adjust:

Option|Description
---|---
Number of posts|The number of posts you want to show
Category|Which category you want to get posts from. Select **All** if you want to show posts in all categories.
Tag|Which tag you want to get posts from. Select **All** if you want to show posts in all tags.
Show date|Do you want to show post date?
Date format|The date format. By default it takes WordPress settings in *Settings → General*. See [this link](http://codex.wordpress.org/Formatting_Date_and_Time) for a full list of supported date formats.
Show excerpt|Do you want to show post excerpt? The post excerpt is taken from post excerpt and fallback to the post content.
Excerpt length|The number of words of post excerpt you want to show. The recommended number is 40.
Show read more button|Do you want to show read more button?.
Read more text|The read more text.
Display as|Choose which format you want to show the featured content. There are 4 styles that you can select from: creative slider (as shown in demo [Creative](http://demo3.fitwp.com/them4/), full width slider - in demo [Travel](http://demo3.fitwp.com/them2)/[Girl](http://demo3.fitwp.com/them6), single post slider - in demo [Lifestyle](http://demo3.fitwp.com/them5)/[Minimal](http://demo3.fitwp.com/them4/), grid - in demo [Creative](http://demo3.fitwp.com)/[Food](http://demo3.fitwp.com/them3/)
Slider speed (ms)|The number of milliseconds between slides.
Hide these posts in the home page|Whether to exclude these posts in the post list in the homepage to remove duplication?

**Tip**: To select specific posts for the slider, you can create a specific tag and add it to the posts you want to show. Then in this widget, select that tag.

### TheM: Flickr

This widget displays your recent images from Flicker. It has the following options:

![flickr](http://i.imgur.com/QAB8chC.png)


Option|Description
---|---
Title|The widget title
Flickr ID|Your Flickr ID. [Get it here](http://idgettr.com/)
Type|Get images from User or Group
Number of photos|Number of photos you want to show
Display|Display latest images or random images
Size|Select image sizes


### TheM: Instagram

This widget displays the recent images from your Instagram account or someone's account. It has the following options:

![instagram options](http://i.imgur.com/qyBc61i.png)

Option|Description
---|---
Title|The widget title
User ID|Your user ID. [Get it here](http://9webtools.com/instagram-token)
Access token|Your access token. [Get it here](http://9webtools.com/instagram-token)
Cache time (seconds)|The number of seconds the widget store images in the cache.
Number of images|Number of images you want to show
Other user ID|Another person's Instagram ID. Use this option if you want to display images from another account. Get another person's ID [here](http://jelled.com/instagram/lookup-user-id)
Tag|Use this to fetch recent images tagged with a specific tag.
Display as carousel slider?|Do you want to display images in a carousel? See [Creative demo](http://demo3.fitwp.com).

### TheM: Recent Posts

This widget simply displays recent posts in the sidebar. It has the following options:

![recent posts](http://i.imgur.com/nD1pQ9X.png)

Option|Description
---|---
Title|The widget title
Number of posts|The number of posts you want to show
Category|Which category you want to get posts from. Select **All** if you want to show posts in all categories.
Display first post big|Whether or not to show first post bigger than others. See [Food demo](http://demo3.fitwp.com/them3/)
Show date|Do you want to show post date?
Date format|The date format. By default it takes WordPress settings in *Settings → General*. See [this link](http://codex.wordpress.org/Formatting_Date_and_Time) for a full list of supported date formats.
Show like number|Do you want to show like number? See [Food demo](http://demo3.fitwp.com/them3/)

### TheM: Latest Tweets

Before you use the Tweets widget, you have to create a Twitter app. Go to https://dev.twitter.com/apps and click **Create a new application** button.

![twitter app](http://i.imgur.com/IEqljdM.png)

Fill in all information needed for the app. The name and description can be anything, it does not have to be a certain name. You can leave the Callback URL field empty.
After creating the app, click **Create My Access Token** button to generate the necessary codes. Now go to app **Dashboard** and selec **Keys and Access Token** tab and copy the following fields:

- Consumer key
- Consumer secret
- Access token
- Access token secret

These fields will be used in the tweets widget.

![app](http://i.imgur.com/sytKLv2.png)

Now go to your website admin area, then *Appearance → Widgets*, drag and drop **TheM: Latest Tweets** widget into a sidebar that you want it to show there. You'll see these fields like this:

![tweets](http://i.imgur.com/nYl5T8P.png)

You also need to enter **Cache time** - which is the time your tweets will be temporarily stored in WordPress cache, Twitter **username** and **Number of tweets**.

After filling all information, just click Save.
