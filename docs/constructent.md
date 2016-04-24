---
layout: docs
title: Constructent Documentation
description: Constructent WordPress theme documentation
---

*Welcome! First of all we want to thank you for purchasing our Constructent WordPress Theme.*

In the following sections we will show you how to set up and use Constructent theme the easiest way possible. Although there're a lot of things written in this documentation, the theme itself is not very hard to use. You can go to the Theme Options page and discover everything yourself. This file is more of a reference if you do not know what to do, or if you are not familiar with WordPress.


## FILE INCLUDED

The download package (.zip) that you get from ThemeForest contains the following files and folder:

-  Constructent.zip: main theme file that need to be uploaded to host to install Constructent theme
-  demo-content.xml: demo content file, which contains all pages and posts from live preview website. It will help you to have a first look of how we use Constructent theme
-  docs.html: theme documentation (this file)
-  theme-options.txt: theme option backup file. You'll need this to restore the default theme options that setup for demo website.
-   Plugins:
    	- codecanyon-2751380-slider-revolution-responsive-wordpress-plugin.zip: Slider Revolution Responsive WordPress Plugin. Completed download package from Codecanyon.net. It's FREE for you to use with Constructent theme
    	- constructent-demo-import.zip: a plugin which helps you to import the demo content by just 1 click.
    	- home-page-slider.zip: Demo slider that exported from our demo, but with placeholder images

## INSTALLATION

### Step 1: Install Theme

After you download the *.zip* package from ThemeForest, unzip it. You'll see a file *constructent.zip*, which is the main file that needed to upload and install.

Notice: If you download Installable WordPress file then that file is the zip file we use to upload and install.

You can either choose to upload and installl the theme using FTP or use WordPress theme install function. Both of them result in the same thing.
###Upload and install using FTP

 -  Unzip ` Constructent.zip`, you'll get a folder ` Constructent`
 -   Use a FTP client like FileZilla and upload that folder to ` wp-content/themes` folder on your host.
 -   Go to `Appearance > Themes` and activate Constructent theme
Install theme using WordPress install function.

###Install theme using Wordpress install function

- Go to `Appearance > Themes` and click **Add New**
-  Select **Upload**
- Click **Browse** and select the `Constructent.zip `file
- Click **Install Now**


When upload and installation progresses are completed, click **Activate**, or go to` Appearance > Themes` and activate Constructent theme.

![upload wordpress theme](http://docs.fitwp.com/constructent/images/wordpress-upload.png)

### Step 2: Install plugins

After installing Constructent, you'll see a notification in the top of the page that says the theme needs some plugins to function properly.

Constructent theme requires follow plugins (all are free and available on WordPress.org):

-  Meta Box
-  FitWP Shortcodes

Constructent theme recommends follow plugins:

- WooCommerce - excelling eCommerce
- Contact Form 7
- Slider Revolution ($18 on CodeCanyon, included in download package for free)

Constructent is working perfectly with these plugins. It automatically adds more styles to them to make the design match the theme.
To install these plugins:

- Click Begin installing plugins
- You'll be redirect to a page where all needed plugins are listed. Just click on Install below each plugin's name
- After installing, if it's required to activate the plugin, just activate.

![install plugins](http://docs.fitwp.com/constructent/images/install-plugins.png)

### Step 3: Install demo content

If you are new to WordPress and have problems with setting up the theme you might want to import the demo content file that comes with the theme. The following actions will import some dummy posts and pages from the live preview:

- Go to `Tools > Import`
- Select `WordPress` from the list
- If you haven't installed the `WordPress import plugin`, a popup window will appears and ask you to install it. Just click `Install Now`. When the installation progress is completed, click `Activate Plugin & Run Importer`. If you have installed this plugin, skip to next step.
- Click `Browse` and select demo-content.xml file from the download package
- Click **Upload file and import**
- When you are asked to import author, you can create new author or import to existing author. You also should check the checkbox **Download and import file attachments**.
After completing all above steps, go to Posts, Pages, Products, Collections to see imported data.

![import demo data](http://docs.fitwp.com/constructent/images/import.png)

>**Important:** Due to license of images, we have to remove images in distributed demo content and replace them with placeholers. All images get from [placehold.it](http://placehold.it/), if you have any download errors when import demo-content.xml, problem can be speed of internet connection. Don't worry about that, you can replace with your own images or try to import again.


### Step 4: Import demo slider

After finish installing demo content, you should import the demo slider which is exported from our demo site. It is located in `Plugins` folder of download package. Go to `Revolution Slider` menu then select `Import Slider`. A modal window will appear, you just need to click to **Choose File** button then select the zip file `home_slider.zip` in `Plugins` folder. Finish importing slider by clicking on **Import Slider** button.



### Step 5: Setup homepage and blog page

After install demo content, you'll see a page **Homepage**. This page will be used as the homepage of the website. To set it as homepage, please go to `Settings \ Reading`, under **Front page displays**, please chose **A static page (select below)** and select **Front Page for Front ** page and **Full Width** page for **Posts page**.

![setup frontpage](http://docs.fitwp.com/constructent/images/homepage.png)

### Step 6: Setup Menu

Although the theme is working now and it shows menu, but because we haven't created a menu for primary location, the theme will display all pages by default. As the number of pages is large, displaying all of them in the menu is a bad idea.

![setup menu](http://docs.fitwp.com/constructent/images/menu.png)

Following these steps to create a menu:

-    Go to `Appearance > Menus`
-    Select an existing to edit, or click **Note**: Select one of menu from menu list if you want to have same menu as in live preview.
-    Select pages from the left meta box and click **Add to Menu** if you want to add more items to menu.
-    On the right, feel free to drag and drop menu items to organize them
-    When you're done moving menu items, check **Primary Menu for Theme locations** at the bottom of the page
-    Click **Save Menu**

### Step 7: Setup widget areas

Constructent theme has 4 widget areas (sidebars) by default:

- Blog Sidebar: main website sidebar which will be displayed on all blog posts, archive pages, etc.
- Page Sidebar: will be displayed on all WordPress pages.
- Shop Sidebar: will be displayed on all WooCommerce pages: Products, Product category, Single Product, etc.
-    Topbar Left:
-    Topbar Right:
-    Footer Sidebars: there are 4 default sidebars for footer, each sidebar is a column in the footer. You can change number of columns in footer in Theme Options page (in that case number of footer sidebars will increased or decreased acccordingly).

To setup a sidebar, select it from the right by clicking its title or the arrow down. Then drag and drop widgets from the left to the sidebar area.
That's all! Now you have the website up with all basic elements!



## 1 Click Install Demo Content

Above is 8 steps to install demo content manually. In this section, we will show you a easier way to import demo content. These are details steps:

### Step 1: Install Theme

Do the same thing as we wrote above <a href="#toc5">Install Theme</a>.

### Step 2: Install Plugins

Firstly, install all required and recommended plugins as we wrote above <a href="#toc8">Install Theme</a>. But they not all, there is still a plugin we have to install, it is `Constructent Demo Import` plugin.

Now go to `Plugins > Add New` then click to **Upload Plugin** button on the top.

![upload plugin](http://docs.fitwp.com/constructent/images/upload-plugin.png)

Click to button **Choose File** then select `constructent-demo-import.zip` file in `Plugins` folder.

![install demo content plugin](http://docs.fitwp.com/constructent/images/install-demo-content-plugin.png)

Click **Install Now** button. After finish installing plugin, click to **Active Plugin** on the next screen.

> **Note**: You have to disable plugin **WordPress Importer** before install and active **Constructent Demo Import** to avoid error while installing it.


### Step 3: Install Demo Content

Go to `Appearance > Import Demo`. You can select what content do you want to import or don't change anything to import all demo data. Finally, click **Import Demo Content** button to finish.

![1 click import demo](http://docs.fitwp.com/constructent/images/1-click-import-demo.png)


## THEME OPTION

The Constructent theme comes with unique, creative and easy-to-use Theme Options page. You can change all theme options in one place!

With Constructent's advanced theme options panel, you can customize just about any part of your site quickly and easily. Every element on the site can have the color changed to your liking. Choose a color scheme for website, select fonts for all headings and body copy, change sizes, colors and line-heights of all fonts, select different footer column layouts, enable or disable several options, upload your own custom favicon, select from various site/page layouts, input custom CSS, set hundreds of other options to easily customize your site!

All options have full description so you can know what you are doing. Just click and save!

Let's go through each section.

### General

![General Options](http://docs.fitwp.com/constructent/images/general-options.png)

This sections contains:

- **(1)**: favicon upload, allows you to upload favicon for you website
- **(2)**: touch icon, allows you to upload icon for mobile devices and tablets
- **(3)**: show comment on page
- **(4)**: backup - restore, allows you to backup Constructent options and restore them later, or transfer the saved options between different installs.

>**Note:** From WordPress version 4.3, you can setup favicon and touch icon in `Appearance > Customize`. The options (1) and (2) in theme is used if your website is running on older version of WordPress.

Here are the explanations of some options that can help you understand and use them better:

**Favicon Upload**

[Favicon](https://en.wikipedia.org/wiki/Favicon) (short for Favorite icon), also known as a shortcut icon, Web site icon, tab icon or bookmark icon, is a file containing one or more small icons, most commonly 16x16 pixels, associated with a particular Web site or Web page. Browsers that provide favicon support typically display a page's favicon in the browser's address bar (sometimes in the history as well) and next to the page's name in a list of bookmarks. Browsers that support a tabbed document interface typically show a page's favicon next to the page's title on the tab, and site-specific browsers use the favicon as a desktop icon.
This is how favicon appears

Constructent lets you upload favicon or enter favicon URL in the input box:

- If you have a favicon uploaded, or you store the favicon somewhere out of the Media Library, you can just put the URL of the favicon into the input box, or
- If you want to upload favicon for your website, click **the upload button** (the green one near input box) and upload it to **Media Library** as a normal image, then click **Select**.

The favicon should be in one of the following format: ` .ico, .png, .gif`. Usually we should use ` .ico.`


When you're done, you can click   **Save Changes**   button to save your data.

**Touch Icon**

Touch icons are the favicons of mobile devices and tablets. Each mobile devices and tablets has its own standards for displaying the touch icon (read this article to have a better understanding about touch icon and supported devices) and requires various icon sizes. But for best compatibility and simplicity, **an image with size 152x152 is enough**.

To specify a touch icon for you website, just do the same as for favicon: you can either put the URL of the touch icon into the input box or upload the icon to **Media Library**.
The icon must be PNG image

When you're done, you can click **Save Changes** button to save your data.

**Show comments on page**

This option allows you to show/hide comments and comment form on pages. By default, Constructent **doesn't** display comments and comment form on pages.

**Important**: In case this option is set to "ON", to display comments on pages, you still have to **allow comments** for pages when you edit pages.

By default, this checkbox is checked (meaning comments are allowed on pages). But in case you want to show comments on all pages, except some specific pages, you can use this checkbox to hide comments for those pages only.

**Backup - Restore**

Constructent allows you to backup theme options and restore them later. You can also transfer the saved options data between different installs.

To backup theme options, just copy the text inside the text box and save it into a file on your computer. To import data, replace the data in the text box with the one from the saved file and click **Import Options** button.

After clicking **Import Options**, Constructent will automatically setup all options and refresh the current theme options page, so you can see the options immediately.

### Design

This sections contains:

   - **Color Scheme**: allows you to change color scheme of whole website
   - **Layout**: allows you to change layout style and layout for whole website, for blog posts and pages
   -  **Typography**: allows you to change font family, styles, size, line height, color for body text and headings
   - **Custom CSS**: allows you to add your custom CSS


###Color Schemes

![Color Schemes](http://docs.fitwp.com/constructent/images/design-color-schemes.png)

Constructent theme has **5 predefined color schemes** to choose from: yellow (default), red, orange, green and blue. When you change color scheme of the theme, all links, button background and other elements will change their color or background accordingly.

The default color scheme is yellow, but you can select any from 5 colors here. After selecting, click **Save Changes** button to save your data. Now go to the frontend and check the colors of links, buttons, etc.

When you select **Color Scheme** section, you'll see the following options:

**(1)**: select built-in color scheme. These are 5 predefined color schemes. When you select one of them, your website elements will change color accordingly.

**(2)**: enable/disable custom color scheme. This option allow you create custom color scheme, and you can build unlimited color schemes here! Just enable this and you'll see options below.

**(3)**: primary color. This is primary color for your custom color scheme, used for links, overlay, button background on hover, badges, etc.


###Background

![Background](http://docs.fitwp.com/constructent/images/design-background.png)

This section allows you to setup background for whole site. But please remember, background only works with **Boxed** layout. (We will talk about layouts in next section)

When you select **Background** section, you'll see the following options:

**(1)**: background patterns. We have 5 predefined background patterns. They are repeatable images. You just need to select on of theme. If you don't like any, you can use option **(3)**.

**(2)**: Background color. Pick any color you want to be background color of whole site.

**(3)**: Background image. Upload any image you want to use, or you can pick it from list of uploaded images.

**(4)**: Background position in horizontal. You can leave it as default of select either left, center or right.

**(5)**: Background position in vertical. You can leave it as default of select either top, center or bottom.

**(6)**: Background repeat. You can leave it as default (repeat) or select either no repeat, repeat horizontally or repeat vertically.

**(7)**: Background attachment. You can select either scroll or fixed. The default is scroll.

###Layout

![Layouts](http://docs.fitwp.com/constructent/images/design-layout.png)

This section helps you to select which layout will be use in whole website.

**(1)**: select layout style for your website. You can select boxed or wide layout.

**(2)**: sidebar layout for **blog, single posts and other archive pages**. You can select sidebar position here: `left, right` or `none` (don't display sidebar).

**(3)**: sidebar layout **for pages**. Same meaning as for blog above.

**(4)**: sidebar layout for **WooCommerce pages**. Same meaning as for blog above but only applied for WooCommerce pages: **shop page, single products, product tag archive, product category archive**.

Examples: sidebar left - sidebar right

> These options is site-wide, meaning for whole website. But you still
> can set custom layout for single post and page when edit (We'll
> explore it later).

By default: Constructent uses **wide** layout style with **right** sidebar for both blog and pages.


###Typography

![Typography](http://docs.fitwp.com/constructent/images/design-typography.png)

This section helps you to customize fonts for **body text** and **headings** on your website. For each element, you can customize:

**(1)**: font family. Just select from the dropdown font family you like. Constructent supports 3 normal fonts (Arial, Verdana and Times).

**(2)**: font size. Adjust font size for better look here. Just remember the unit for font size is **px**.

**(3)**: line height. Adjust line height for better look here. The unit for line height is also **px**.

<div class="alert alert-info">For better readability, good value for line height is about 1.4-1.5 x font size.</div>

**(4)**: font styles. You can choose **bold**, **italic**, **underline** or any combination of them.

**(5)**: font color. Click on the button, a color picker will appear and you can now select any color.

**Important**: before customize fonts, remember the default values for fonts. You should customize fonts around these values.

| Element   | Font Family | Font Size | Line Height | Styles | Color   |
| --------- | ----------- | --------- | ----------- | ------ | ------- |
| Body Text | Ubuntu      | 14px      | 22px        | None   | #999999 |
| Heading 1 | Ubuntu      | 45px      | 72px        | None   | #261e4c |
| Heading 2 | Ubuntu      | 36px      | 58px        | None   | #261e4c |
| Heading 3 | Ubuntu      | 30px      | 48px        | None   | #261e4c |
| Heading 4 | Ubuntu      | 24px      | 38px        | None   | #261e4c |


###Custom CSS

![Custom CSS](http://docs.fitwp.com/constructent/images/design-custom-css.png)

This section allows to enter custom CSS that will be output in the ``. This will overwrite CSS of theme, so please be careful!

Custom CSS is useful when you want to adjust small things for your website. If you have to adjust a lot of things in website, please use [Child Themes](http://codex.wordpress.org/Child_Themes).


### Header

![Header](http://docs.fitwp.com/constructent/images/header.png)


This sections contains:

**(1)**: show or hide topbar. Turn on this option to show topbar.

**(2)**: logo upload, allows you to upload logo for you website. You can either put the URL of the logo into the input box or upload the logo to Media Library. The live preview of the logo will appear below the inputs.

**(3)**: logo size. Specify logo size in **px** here. It will help you resize the logo to correct dimensions.

**(4)**: logo margin. Specify logo margin in **px** here. This is useful when you upload logo with different size than recommended. You can *move* logo a little, adjust space to make it look good.

> You should **resize the logo to correct size** in Photoshop or any image editor before upload. It will keep your logo not resized and small size.

**(5)**: This option allow you to select type of header. Available options:

- Normal: header displays normally.
- Absolute: header will display over the right bellow section.
- Sticky: header will always stays on the top of the screen when scrolling.

**(6)**: If you select _Absolute_ header style, this option will be appear. It allows you to upload an alternative logo image. This option will be useful when you have a light version of logo. Because when header layout is set as absolute, its background will be a dark color.

**(7)**: If you select _Absolute_ header style, this option will be appear. It allows you to set background of header be transparent.

**(8)**: Menu hover. Easily select hover effect for menu items.

**(9)**: Turn it on if you want to show shop cart icon on your header, at the end of menu. Remember your site have to install **WooCommere** plugin if you want to make it work.

**(10)**: Turn it on if you want to show search icon at the end of menu.

**(11)**: header scripts. Enter scripts or code you would like output to `&lt;head&gt;`. It can be:

 - `<link>` tag for custom font (from Google Fonts maybe)
 - Any meta tag: to show the designer, copyright, etc. in meta tag
 - Google Analytics code
 - Any Javascript code that need to be execute in `&lt;head&gt;`

>If you want to put custom CSS here, you're doing **wrong**. There's a section for **Custom CSS** under **Design**, use it instead.


### Title Area

![Title Area](http://docs.fitwp.com/constructent/images/title-area.png)


This section contains:

**(1)**: Hide breadcrumb. Turn on this option if you don't want to show breadcrumbs in title area.

**(2)**: Turn off parallax. By default, title area has parallax effect when you scroll website. Turn on this option if you don't want that effect.

**(3)**: Custom backgorund. Upload background image for title area here. Title area only displays when has background image.


### Blog


This section contains options which help you to change something about displaying posts archive pages (blog, category, tag, date)

![blog](http://docs.fitwp.com/constructent/images/blog.png)

**(1)**: what type of post content will be displayed. Available options are `Post excerpt`, `Post content` or `Post content before more tag`.

 To understand what those values mean, take a look at the screenshot bellow:

 ![post](http://docs.fitwp.com/constructent/images/post-content.png)

 Where:

 - **(A)**: Whole post content, this is what you enter in the editor.
 - **(B)**: Post excerpt, which is optional hand-crafted summaries of your content. [Learn more about manual excerpt.](http://codex.wordpress.org/Excerpt). If you don't enter anything in the excerpt box, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
 - **(C)**: The post content before `more` tag
 - **(D)**: The `more` tag

 Return to blog option: if you choose

 - `Post excerpt`: Constructent will get post excerpt and display it. **Remember**: if you don't enter excerpts for post, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
 - `Post content`: Constructent will get whole post content and display it. This is the default value.
 - `Post content before more tag`: Constructent will get only the post content before `more` tag and display it.

**(2)**: post content limit. Sometimes you enter a very long text for post excerpt or post content, display such long text in blog and archive pages is not good and harm your website beauty. So we need a way to truncate text to make it shorter. This option is created for that purpose.

 Simply specify number of words will be display here. Post content or excerpt will be truncated to exact number of words. You should try changing this value and preview your blog to see what is best for you.

 Default value is **55 words**.

>**Important**: this option affects only when you **NOT** choose `Post Content` from the Display option above

**(3)**: readmore text. Default value is **Continue reading**.


### Footer

![Footer](http://docs.fitwp.com/constructent/images/footer.png)

This section give you options to customize footer area on your website.

**(1)**: enable or disable footer widgets area.

**(2)**: number of columns in footer. It also is the number of footer sidebars (widget areas). Default is **3**.

**(2)**: copyright text. You can enter text, HTML and **shortcodes** here. To make you easier to display copyright text, Constructent has default shortcodes that you can enter here:
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

**(4)**: footer scripts. Enter scripts or code you would like output before `&lt;/body&gt;`. It can be Google Analytics code or any Javascript code.



## Post/Page Display Settings

We've seen how to change featured title area, sidebar layout for whole website. Constructent also supports customizing these things for specific pages.

When you edit a page, you'll see this meta box below the content editor:

![display settings](http://docs.fitwp.com/constructent/images/display-settings.png)

- **(1)**: hide the title area. Select this box if you want to hide the title area on this page.
- **(2)**: Custom Title. Sometime you want to display different title instead of original page title, you can enter that title here.
- **(3)**: enter subtitle here. Subtitle will be displayed bellow the page title in title area.
- **(4)**: change default title area's background image.
- **(5)**: select this box if you want to hide breadcrumbs on current page.
- **(6)**: whether to use custom page layout. If you check this box, you're able to set custom layout style and sidebar layout below. If you don't, page will use default layout set in **Theme Options**.
- **(7)**: custom sidebar layout. Choose custom sidebar layout for page. If you don't choose anything, Constructent will use default sidebar layout set in **Theme Options**.
- **(8)**: you can enter custom CSS code here. It will be applied for current page only.



## Post Formats

[Post Formats](http://codex.wordpress.org/Post_Formats) is theme feature which is a piece of meta information that can be used by a theme to customize its presentation of a post.

In short, with a theme that supports Post Formats, a blogger can change how each post looks by choosing a Post Format from a radio-button list.

Constructent theme supports the following post formats:

- `gallery` - A gallery of images, which will be displayed in a responsive image slider, powered by Flexslider.
- `link` - A link to another site.
- `image` - A single image, which will be shown above post title.
- `quote` - A quotation.
- `video` - A single video, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed above post title.
- `audio` - An audio file, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed using a powerful HTML5 audio player – jPlayer.

Each post format will have an icon near post title which tells you what post format is. Using post format in Constructent lets you differentiate post from each other and make the blog page / single page looks more beautiful.



### Setup Post Formats

When you edit a post, select a format you want to apply to that post on the **Format** meta box on the right:

![formats](http://docs.fitwp.com/constructent/images/post-formats-box.png)

When you choose a format, a corresponding meta box will appear **below** the content editor, here's the list of them:

![formats](http://docs.fitwp.com/constructent/images/post-formats-boxes.png)

All you need to do is just enter **all** information in the fields in these meta boxes. This information will be used to decorate the post. For example: gallery post format will uses uploaded images to show a slider above post title, a video post will display a video player above post title, etc.




## Page Templates

Constructent has some build-in page templates that can help you create special pages easier:

- **Deals**: template to display deal products.
- **Homepage**: template to display sections with normal products and deal products are inside.

When you edit a page, look at on the right, find **Page Attributes** meta box and select a template from the dropdown **Template**:

![page-templates](http://docs.fitwp.com/constructent/images/page-templates.png)

Width **Homepage** template, there's no configurations at all. After select page template from the meta box on the right, you just need to save the page and see it in action in the frontend.


Width **Contact** template, after select it, you will see a new metabox appear. It contains options which allow you to enter contact information for contact page.

![Contact settings](http://docs.fitwp.com/constructent/images/contact-settings.png)


## Widgets

Constructent plays nicely with default WordPress widgets. Besides that the theme has some additional widgets that might be useful for you:


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

![twitter app](http://docs.fitwp.com/constructent/images/twitter-app.png)

- Fill in all information needed for the app. The name and description can be anything, it does not have to be a certain name. You can leave the Callback URL field empty.
- After creating the app, go to **API Keys** tab then click **Create My Access Token** button at the bottom to generate the necessary codes. It usually take 10 - 15 seconds to generate these codes, you have to reload that page to see your code in **Your Access Token** seciton.

![twitter app](http://docs.fitwp.com/constructent/images/twitter-app-token.png)

- Now you can copy the following fields for setting up Latest Tweets widget:
	+ API key  -> Consumer Key
	+ API secret -> Consumer Secret
	+ Access token -> Access token
	+ Access token secret -> Access token secret

These fields will be used in the tweets widget.

Now go to your website admin area, then `Appearance > Widgets`, drag and drop **[FitWP] Latest Tweets** widget into a sidebar that you want it to show there. You'll see these fields this:

![tweets](http://docs.fitwp.com/constructent/images/widget-tweets.png)

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


### [FitWP] Projects

This widget shows projects as thumbnails. All you need to do is enter number of projects you want to show then select which projects you want to show. You can choose either All projects, completed projects or under construction projects.
