---
layout: default
title: Whisper WordPress Theme Documentation
permalink: /whisper
published: true
---

## Files Included

The download package (`.zip`) that you get from ThemeForest contains the following files and folder:

- `whisper.zip`: main theme file that need to be uploaded to host to install Whisper theme
- `demo-content.xml`: demo content file, which contains all pages and posts from live preview website. It will help you to have a first look of how we use Whisper theme
	- Slider
		- `codecanyon-2751380-slider-revolution-responsive-wordpress-plugin.zip`: [Slider Revolution Responsive WordPress Plugin](http://codecanyon.net/item/slider-revolution-responsive-wordpress-plugin/2751380). **Completed** download package from Codecanyon.net. It's **FREE** for you to use with Whisper theme.
		- `home-slider-1.zip`: slider for homepage version 1
		- `home-slider-2.zip`: slider for homepage version 2
		- `home-slider-3.zip`: slider for homepage version 3
	- Resource
		- HTML.zip: HTML version of the theme
		- PSD.zip: PSD files for design customization
- `docs.html`: Theme documentation (this file)


## Installation

### Install theme

After you download the `.zip` package from ThemeForest, unzip it. You'll see a file `whisper.zip`, which is the main file that needed to upload and install.

You can either choose to upload and installl the theme using **FTP** or use **WordPress theme install** function.

**Upload and install using FTP**

- Unzip `whisper.zip`, you'll get a folder `whisper`
- Use a FTP client like [FileZilla](http://filezilla-project.org/) and upload that folder to `wp-content/themes` folder on your host
- Go to `Appearance > Themes` and activate **Whisper** theme

**Install theme using WordPress install function**

- Go to `Appearance > Themes` and click **Add New**
- Select **Upload**
- Click **Browse** and select the `whisper.zip` file
- Click **Install Now**
- When upload and installation progresses are completed, click **Activate**, or go to `Appearance > Themes` and activate **Whisper** theme

![upload](http://fitwp.github.io/docs/whisper/wordpress-upload.png)


### Install plugins

After installing Whisper, you'll see a notification in the top of the page that says the theme needs some plugins to function properly.

Whisper theme **requires** the [Meta Box](http://wordpress.org/plugins/meta-box/) plugin (free and available on WordPress.org) and **FitWP Shortcodes** (a plugin that help you to build custom content with shortcodes, made by us - the FitWP Team) and **recommends** the [Revolution Slider](http://codecanyon.net/item/slider-revolution-responsive-wordpress-plugin/2751380?ref=fitwp) (a premium plugin that helps you to create stunning sliders, bundled with the theme) and [Pricing Tablle](http://wordpress.org/plugins/pricing-table/) plugin (if you want to use pricing table on your website).

Whisper is working perfectly with these plugins. It automatically adds more styles to them to make the design match the theme.

To install these plugins:

- Click **Begin installing plugins**
- You'll be redirect to a page where all needed plugins are listed. Just click on **Install** below each plugin's name
- After installing, if it's required to activate the plugin, just activate

![plugins](http://fitwp.github.io/docs/whisper/install-plugins.png)


### Install demo content

If you are new to WordPress and have problems with setting up the theme you might want to import the demo content file that comes with the theme. The following actions will import some dummy posts and pages from the live preview:

- Go to `Tools > Import`
- Select **WordPress** from the list
- If you haven't installed the **WordPress import plugin**, a popup window will appears and ask you to install it. Just click **Install Now**. When the installation progress is completed, click **Activate Plugin & Run Importer**. If you have installed this plugin, skip to next step.
- Click **Browse** and select `demo-content.xml` file from the download package
- Click **Upload file and import**
- When you are asked to import author, you can create new author or import to existing author. You also should check the checkbox **Download and import file attachments**.

![import](http://fitwp.github.io/docs/whisper/import.png)

After completing all above steps, go to `Posts` and `Pages` to see imported posts and pages. There are some special pages that you should pay attention to such as: **Homepage** (3 versions), **Blog** (2 versions), **Portfolios** (2 versions), **Contact**.


### Setup the homepage

- Go to `Settings > Reading`
- For **Front page displays**, select **A static page (select below)**
- Choose either **Home version 1**, **Home version 2**, **Home version 3** from the dropdown for **Front page**
- Click **Save Changes**

![homepage](http://fitwp.github.io/docs/whisper/setup-homepage.png)


### Setup homepage slider

After setting up the homepage, you need to setup the slider for homepage to make it display the same as in live preview.

The download package contains exported 3 sliders (Revolution Slider) that help you easier to create sliders. You can choose whatever slider to import (no need to import all except you want to have 3 homepage versions exactly the same as in live preview). Following the steps below:

- Go to `Revolution Slider`
- Click **Import Slider** button
- When a popup appear, click **Browse** and select `home-slider-1.zip` file
- Click **Import Slider** button to start import the selected slider

![import slider](http://fitwp.github.io/docs/whisper/import-slider.png)

One problem with Revolution Slider is it doesn't import images correctly. So we have to fix the URL to these images:

- You're still on the main page of Revolution Slider, click **Edit Slides**
- Choose first slide to edit and click **Edit Slide**
- Select **Image 1** from the list of layers and then click on **Change Image Source** (this button appears only when you select **Image 1** layer)
- Choose correct image from the Media Library as shown in the screenshot below and then click **Insert**
- Click **Update Slide**

![fix](http://fitwp.github.io/docs/whisper/fix-revolution-slider.png)

**Repeat the steps below for other slides**

<div class="alert">**Important:** We're going through the steps to set up slider for homepage **the same** as in live preview. If you want to make your own slider, follow the **documentation of Revolution Slider** included in download package!</div>

Now the homepage is working perfectly!


### Setup menu

Although the theme is working now and it shows menu, but because we haven't created a menu for primary location, the theme will display all pages by default. As the number of pages is large, displaying all of them in the menu is a bad idea.

Following these steps to create a menu:

- Go to `Appearance > Menus`
- Select an existing to edit, or click **create a new menu**. **Note:** when you import theme data, WordPress automatically create a menu **Main** for you, so select it if you want to have same menu as in live preview.
- Select pages from the left meta box and click **Add to Menu**
- On the right, feel free to drag and drop menu items to organize them
- When you're done moving menu items, check **Primary Menu** for **theme locations** at the bottom of the page
- Click **Save Menu**

![menu](http://fitwp.github.io/docs/whisper/menu.png)


### Setup widget areas

Whisper theme has 6 widget areas (sidebars) by default:

- **Blog sidebar:** main website sidebar which will display on all blog posts, archive pages, etc.
- **Page sidebar:** will display on all pages (WordPress pages)
- **Footer sidebars:** there are 4 default sidebars for footer, each sidebar is a column in the footer. Later you can change number of columns in footer in **Theme Options** (we'll talk about this later).

To setup a sidebar, select it from the right by clicking its title or the arrow down. Then drag and drop widgets from the left to the sidebar area.

![sidebar](http://fitwp.github.io/docs/whisper/sidebar.png)

That's all! Now you have the website up with all *basic* elements!


## Theme Options

![theme options](http://fitwp.github.io/docs/whisper/theme-options.png)

The Whisper theme comes with unique, creative and easy-to-use Theme Options page. You can change all theme options in one place!

With Whisper's advanced theme options panel, you can customize just about any part of your site quickly and easily. Every element on the site can have the color changed to your liking. Choose a boxed or wide skin, or change the website color scheme, select fonts for all headings and body copy, change sizes, colors and line-heights of all fonts, select different footer column layouts, enable or disable several options, advanced blog and portfolio options, upload your own custom favicon, upload custom backgrounds to the featured title area and background areas of the boxed version, select from various site/page layouts, input custom CSS, set hundreds of other options to easily customize your site!

All options have full description so you can know what you are doing. Just click and save!

Let's go through each section.


### General

![general](http://fitwp.github.io/docs/whisper/general.png)

This sections contains:

- **(1)**: this is the button which shows quick link to **Customizer**, a new feature that allows you to preview changes in real time. Please read more about Customizer in Customizer section in this docs.
- **(2)**: favicon upload, allows you to upload favicon for you website
- **(3)**: touch icon, allows you to upload icon for mobile devices and tablets
- **(4)**: show comments on pages, allows you to show/hide comments and comment form on pages
- **(5)**: backup - restore, allows you to backup Whisper options and restore them later


### Favicon Upload

[Favicon](http://en.wikipedia.org/wiki/Favicon) (short for Favorite icon), also known as a shortcut icon, Web site icon, tab icon or bookmark icon, is a file containing one or more small icons, most commonly 16x16 pixels, associated with a particular Web site or Web page. Browsers that provide favicon support typically display a page's favicon in the browser's address bar (sometimes in the history as well) and next to the page's name in a list of bookmarks. Browsers that support a tabbed document interface typically show a page's favicon next to the page's title on the tab, and site-specific browsers use the favicon as a desktop icon.

This is how favicon appears:

![favicon](http://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Wikipedia_favicon_in_Firefox_on_KDE.png/250px-Wikipedia_favicon_in_Firefox_on_KDE.png)

Whisper lets you upload favicon or enter favicon URL in the input box:

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

This option allows you to show/hide comments and comment form on pages. By default, Whisper doesn't display comments and comment form on pages.

**Important**: In case this option is set to "ON", to display comments on pages, you still have to **allow comments** for pages when you edit pages.

![allow comments](http://fitwp.github.io/docs/whisper/allow-comments.png)

By default, this checkbox is checked (meaning comments are allowed on pages). But in case you want to show comments on all pages, except some specific pages, you can use this checkbox to hide comments for those pages only.


### Backup - Restore

Whisper allows you to backup Whisper options and restore them later. You can also transfer the saved options data between different installs.

To backup theme options, just copy the text inside the text box and save it into a file on your computer. To import data, replace the data in the text box with the one from the saved file and click **Import Options** button.

After clicking **Import Options**, Whisper will automatically setup all options and refresh the current theme options page, so you can see the options immediately.


### Design

This sections contains:

- **Color Scheme**: allows you to change color scheme of whole website
- **Background**: allows you to select background pattern or image, and change how it appear
- **Layout**: allows you to change layout style and layout for whole website, for blog posts and pages
- **Typography**: allows you to change font family, styles, size, line height, color for body text and headings
- **Custom CSS**: allows you to add your custom CSS


### Color Scheme

![color schemes](http://fitwp.github.io/docs/whisper/color-schemes.png)

Whisper theme has **4 predefined color schemes** to choose from: red, orange, blue and green. When you change color scheme of the theme, all links, icon boxes, button background and other elements will change their color or background accordingly.

The default color scheme is orange, but you can select any from 4 colors here. After selecting, click **Save Changes** button to save your data. Now go to the frontend and check the colors of links, buttons, etc.

When you select **Color Scheme** section, you'll see the following options:

![color schemes](http://fitwp.github.io/docs/whisper/design-color-schemes.png)

**(1)**: select built-in color scheme. These are 4 predefined color scheme. When you select one of them, your website elements will change color accordingly.

**(2)**: enable/disable custom color scheme. This option allow you create **custom color scheme**, and you can build unlimited color schemes here! Just enable this and you'll see options below.

**(3)**: primary color. This is primary color for your custom color scheme.

**(4)**: secondary color. This is the color used in gradient for pagination buttons or pricing table

**(5)**: tertiary color. This is the color used for borders of pagination buttons or pricing table

**(6)**: this is just some examples of using custom colors to built your own color scheme. These are *real* example which are used to build 4 predefined color schemes. You should start with these values and adjust them.


### Background

This section help you to select background pattern or image, and change how it appear.

<div class="alert">All the background options are applied **only in boxed layout** (we'll reveal how to change boxed or wide layout in the next section).</div>

![background](http://fitwp.github.io/docs/whisper/background.png)

**(1)**: select background pattern (background image). Whisper has **5 predefined background patterns** for you to select from. These patterns are handy picked and match the theme design. If you don't have a background image, you can use one of them.

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

![layout](http://fitwp.github.io/docs/whisper/layout.png)

**(1)**: layout style. You can choose either **boxed** or **wide** style. Whisper theme allows you to change layout style of whole website to boxed or wide (full width). When you change layout style, it doesn’t affect style of your content, sidebar, header or footer. All these elements still keep their looks and feel.

The default style is wide (full width), which make you feel the website is wider, especially on large screens. But in boxed style, you can set background for website.

![boxed wide](http://fitwp.github.io/docs/whisper/boxed-wide.png)

**(2)**: sidebar layout **for blog, single posts and other archive pages**. You can select sidebar position here: `left`, `right` or `none` (don't display sidebar)

**(3)**: sidebar layout **for pages**. Same meaning as for blog above.

Examples: [sidebar left](http://themes.fitwp.com/whisper/page-sidebar-left/) - [sidebar-right](http://themes.fitwp.com/whisper/page-sidebar-right/)

<div class="alert alert-info">These options is site-wide, meaning for whole website. But you still can set **custom layout for single post and page when edit** (We'll explore it later).</div>

By default: Whisper uses **wide** layout style with **right** sidebar for both blog and pages.


### Typography

![typography](http://fitwp.github.io/docs/whisper/typography.png)

This section helps you to customize fonts for **body text** and **headings** on your website. For each element, you can customize:

**(1)**: font family. Just select from the dropdown font family you like. Whisper supports 3 normal fonts (Arial, Verdana and Times) and 1 Google Font (Open Sans).

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

![custom css](http://fitwp.github.io/docs/whisper/custom-css.png)

This section allows to enter custom CSS that will be output in the `</head>`. This will **overwrite** CSS of theme, so please be careful!

Custom CSS is useful when you want to adjust **small things** for your website. If you have to adjust a lot of things in website, please use [Child Themes](http://codex.wordpress.org/Child_Themes).


### Header

![header](http://fitwp.github.io/docs/whisper/header.png)

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

![featured title area](http://fitwp.github.io/docs/whisper/featured-title-area.png)

Featured Title Area is the highlighted area in the screenshot above. This area shows you an attractive title area with this information:

- **(1)**: Page title
- **(2)**: Page subtitle
- **(3)**: Background image
- **(4)**: Breadcrumbs

Whisper uses a **default image** for background and **show** breadcrumbs.

In theme options page, you can change the background image and show/hide breadcrumbs for whole website:

![featured title area](http://fitwp.github.io/docs/whisper/options-featured-title-area.png)

**(1)**: show/hide breadcrumbs. Default is **OFF** (show breadcrumbs). If you want to hide breadcrumbs, just turn it on.

**(2)**: custom background image. You can either put the URL of the image into the input box or upload the image to Media Library. The live preview of the background will appear below the inputs.

<div class="alert alert-info">Tips: [Subtle Patterns](http://subtlepatterns.com/) is a good resource to find background patterns!</div>

<div class="alert alert-info">These options is site-wide, meaning for whole website. But you still can set **custom featured title area for single post and page when edit** (We'll explore it later).</div>


### Blog

![blog](http://fitwp.github.io/docs/whisper/blog.png)

This section helps you to change the display options for posts in blog page (and other archive pages). This section contains:

**(1)**: what type of post content will be displayed. Available options are `Post excerpt`, `Post content` or `Post content before more tag`.

To understand what those values mean, take a look at the screenshot bellow:

![post](http://fitwp.github.io/docs/whisper/post-content.png)

Where:

- **(A)**: Whole post content, this is what you enter in the editor.
- **(B)**: Post excerpt, which is optional hand-crafted summaries of your content. [Learn more about manual excerpt.](http://codex.wordpress.org/Excerpt). If you don't enter anything in the excerpt box, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
- **(C)**: The post content before `more` tag
- **(D)**: The `more` tag

Return to blog option: if you choose

- `Post excerpt`: Whisper will get post excerpt and display it. **Remember**: if you don't enter excerpts for post, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
- `Post content`: Whisper will get whole post content and display it. This is the default value.
- `Post content before more tag`: Whisper will get only the post content before `more` tag and display it.

**(2)**: post content limit. Sometimes you enter a very long text for post excerpt or post content, display such long text in blog and archive pages is not good and harm your website beauty. So we need a way to truncate text to make it shorter. This option is created for that purpose.

Simply specify number of words will be display here. Post content or excerpt will be truncated to exact number of words. You should try changing this value and preview your blog to see what is best for you.

Default value is **55 words**.

<div class="alert">**Important**: this option affects only when you **NOT** choose `Post Content` from the Display option above</div>

**(3)**: readmore text. Default value is **Continue reading**.


### Footer

This section give you options to customize footer area on your website.

![footer](http://fitwp.github.io/docs/whisper/footer.png)

**(1)**: number of columns in footer. It also is the number of footer sidebars (widget areas). Default is **4**.

**(2)**: copyright text. You can enter text, HTML and **shortcodes** here. To make you easier to display copyright text, Whisper has default shortcodes that you can enter here:

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

Customizer is a feature of WordPress that allows us to tweak a theme's settings and see a preview of those changes in real time. And since version 2.0, Whisper supports Customizer, which means you can change theme options and preview those changes in real time! You even don't need Theme Options page, unless you want something more advanced like footer scripts!

To start with Customizer, please go to **Appearance \ Customize**, you'll see the following screen:

![customizer](http://fitwp.github.io/docs/whisper/customizer.png)

**(1)**: there are some sections that you can change and live preview it. These sections have `[Whisper]` in their title.

**(2)**: click on each section title will show options for that section. These options are the same as in Theme Options, so it's easy to understand (please refer to Theme Options in this documentation to know exactly each detail).

**(3)**: this is the panel where you'll see your website in real time whenever you change anything.

Remember to click the **Save & Publish** on the top of left panel when you're done tweaking themes!


## Post/Page Display Settings

We've seen how to change featured title area, layout style, sidebar layout for whole website. Whisper also supports customizing these things for specific posts and pages.

When you edit a page or a post, you'll see this meta box below the content editor:

![display settings](http://fitwp.github.io/docs/whisper/display-settings-page.png)

This meta box contains 3 main parts:

1. **Featured Title Area Settings**
1. **Slider Settings**
1. **Custom Layout Settings**

Each parts contains some settings as shown in the screenshot above. Let's go through it:


### Featured Title Area

This is the featured title area which is displayed in the frontend

![featured title area](http://fitwp.github.io/docs/whisper/featured-title-area.png)

where:

- **(1)**: Page title
- **(2)**: Page subtitle
- **(3)**: Background image
- **(4)**: Breadcrumbs

Let's go back to the page display settings above, we have these settings:

**(1)**: hide featured title area. Check this box if you want to hide the featured title area. This option *should* be used in special pages like homepage.

**(2)**: custom title. Enter the custom page title here. By default Whisper displays post/page title, but you can customize the real title shown in Featured Title Area. It is useful when you have a very long title.

**(3)**: subtitle. Enter subtitle for page here. Leave this empty if you don't want to show subtitle.

**(4)**: custom background. If you choose an image, it will be used as the background for Featured Tittle Area. If you do not, Whisper will use default image set in **Theme Options**.

**(5)**: hide breadcrumbs. The theme already has settings to show/hide breadcrumbs side-wide. But if you want to hide breadcrumbs for a specific post/page, you can select this option.


### Slider

This part contains only 1 input field **(6)**, where you can enter **shortcode for slider**. The slider will be shown below featured title area. See [this page](http://themes.fitwp.com/whisper/features/custom-slider/) for a demo.

Whisper supports slider plugin which has shortcode **only**. These are some plugins tested with Whisper:

- [Revolution Slider](http://codecanyon.net/item/slider-revolution-responsive-wordpress-plugin/2751380?rel=fitwp) (premium)
- [Meteor Sliders](http://wordpress.org/extend/plugins/meteor-slides/) (free)
- [Soliloquy Slider](http://wordpress.org/plugins/soliloquy-lite/) (free)

<div class="alert alert-success">When you buy Whisper, you also **get a free copy of Revolution Slider plugin** – a very popular plugin at CodeCanyon.</div>

<div class="alert">Note: For sliders that does not support full-width, you should switch site layout style or change page layout style to boxed.</div>


### Custom Layout

In this part, you can change:

**(7)**: whether to use custom page layout. If you check this box, you're able to set custom layout style and sidebar layout below. If you don't, page will use default layout set in **Theme Options**.

**(8)**: custom layout style: boxed or wide. Choose custom layout style for page. If you don't choose anything, Whisper will use default layout style set in **Theme Options**.

**(9)**: custom sidebar layout. Choose custom sidebar layout for page. If you don't choose anything, Whisper will use default sidebar layout set in **Theme Options**.


## Add/Edit Portfolio

When you add or edit a portfolio, you need to fill in some required information to make it displays correctly. Look at 3 meta boxes:

- **Portfolio Settings**: portfolio main information
- **Portfolio Categories**: portfolio categories
- **Featured Image**: portfolio featured image

![portfolio](http://fitwp.github.io/docs/whisper/portfolio.png)

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

Whisper theme supports the following post formats:

- `gallery` - A gallery of images, which will be displayed in a responsive image slider, powered by Flexslider.
- `link` - A link to another site.
- `image` - A single image, which will be shown above post title.
- `quote` - A quotation.
- `video` - A single video, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed above post title.
- `audio` - An audio file, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed using a powerful HTML5 audio player – jPlayer.

Each post format will have an icon near post title which tells you what post format is. Using post format in Whisper lets you differentiate post from each other and make the blog page / single page looks more beautiful.

[See blog page](http://themes.fitwp.com/whisper/blog/) to see how post formats look.


### Setup Post Formats

When you edit a post, select a format you want to apply to that post on the **Format** meta box on the right:

![formats](http://fitwp.github.io/docs/whisper/post-formats-box.png)

When you choose a format, a corresponding meta box will appear **below** the content editor, here's the list of them:

![formats](http://fitwp.github.io/docs/whisper/post-formats-boxes.png)

All you need to do is just enter **all** information in the fields in these meta boxes. This information will be used to decorate the post. For example: gallery post format will uses uploaded images to show a slider above post title, a video post will display a video player above post title, etc.


### Portfolio Formats

In Whisper, post formats is not only used for posts, but also for portfolios. This is used to display the portfolio icon, like this:

![formats](http://fitwp.github.io/docs/whisper/formats-icons.png)

When you edit a portfolio, simply select a format you want to apply to that post on the **Format** meta box on the right:

![formats](http://fitwp.github.io/docs/whisper/post-formats-box.png)

That's all! There's no meta box for you to enter more information like for post (because the format is used to show icon only!).




Page Templates
==============

Whisper has some build-in page templates that can help you create special pages easier:

- **Blog**: template to display blog posts
- **Blox Boxes**: display blog posts in boxed style
- **Contact**: template for contact page
- **Contact Without Map**: template for contact page but without Google Maps
- **Portfolio**: display portfolios
- **Portfolio Hexagon**: display portfolios in creative hexagon style

When you edit a page, look at on the right, find **Page Attributes** meta box and select a template from the dropdown **Template**:

![page-templates](http://fitwp.github.io/docs/whisper/page-templates.png)

For **Blog**, **Blog Boxes**, **Portfolio**, **Portfolio Hexagon**, there's no configurations at all. After select page template from the meta box on the right, you just need to save the page and see it in action in the frontend.

For **Contact** and **Contact Without Map**, there're some options as below.



Contact Page
------------

There is a special case for contact page. When you select **Contact** from the **Page Attributes** dropdown, a meta box will appear that lets you enter your contact info:

![contact](http://fitwp.github.io/docs/whisper/contact.png)

**(1)**: contact form shortcode. If you don't want to use default contact form (maybe you need more information from users like Country, Postcode, etc.), you can use a form plugin like Contact Form 7 or Ninja Forms, Gravity Forms. Those plugins provide shortcode for each form, and you just need to paste the shortcode into this field.

**(2)**: your contact email

**(3)**: your phone number

**(4)**: your address. When you enter the address in the text field, you'll see a list of suggested address that Google Maps found. Simply select one of them, then the map will show the correct area.

If you don't see your address in the suggested list, click the **Find Address** button **(5)**, Google Maps will try its geolocation service to find your address on the map.

**(5)**: when the map displays correct area, you can drag, zoom the map to find your exact location. Then **click** on the map to place a marker. You then can also **drag and drop** the marker to another location if you want.

**(6)**: search for your location in case you don't see list of suggested location from Google Maps.

When you entered all information, save the page and see it in the frontend.

**Note**: You also should enter page content in the editor, this content will be display on the Contact Page as well.



Contact Page Without Map
------------------------

This page template is similar to Contact Page above and has same options. The difference is there's no Google Maps on this page, and thus no options for maps.





Widgets
=======

Whisper plays nicely with default WordPress widgets. Besides that the theme has some additional widgets that might be useful for you:




Whisper - Tweets
----------------

Before you use the Tweets widget, you have to create a Twitter app. Following these steps:

- Go to [https://dev.twitter.com/apps](https://dev.twitter.com/apps) and click **Create a new application** button.

![twitter-app](http://fitwp.github.io/docs/whisper/twitter-app.png)

- Fill in all information needed for the app. The name and description can be anything, it does not have to be a certain name. You can leave the Callback URL field empty.
- After creating the app, click **Create My Access Token** button to generate the necessary codes.
- Now go to app Dashboard and selec **OAuth tool** tab and copy the following fields:
	+ Consumer key
	+ Consumer secret
	+ Access token
	+ Access token secret

These fields will be used in the tweets widget.

Now go to your website admin area, then `Appearance > Widgets`, drag and drop **Whisper - Tweets** widget into a sidebar that you want it to show there. You'll see these fields like this:

![tweets](http://fitwp.github.io/docs/whisper/tweets.png)

You also need to enter **Cache time** (2) - which is the time your tweets will be temporarily stored in WordPress cache, **Twitter username** (3) and **Number of tweets** (4).

After filling all information, just click **Save**.



Whisper - Social Links
----------------------

This widget shows links (with icons) to your social network profiles. It's exactly the same as `[social]` shortcode. All you need to do is just enter URL to your social network profiles and optionally title for each link.



Whisper - Social Feed
----------------------

This widget shows items from the feed of creative social networks: Pinterest, Deviant Art, Flickr, Dribbble, Youtube, Instagram and Newsfeed (RSS). It uses `[social_feed]` shortcode to display items.

The configuration for this widget is simple:

- Choose a network that you want to display items from
- Enter your username
- And enter the number of items will be displayed



Whisper - Recent Posts
----------------------

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



Whisper - Tabs
----------------------

This widgets displays popular posts, recent posts and recent comments in a tabbed widget. Each tab has its own options. For popular posts and recent posts, the options are similar to the Recent Posts widget above.

Note that popular posts is counted based on number of comments.




Shortcodes
==========

The Whisper theme is bundled with powerful shortcodes that you can customize your page content in thousand ways!

With Whisper Shortcode Generator, there is a shortcode for anything you need, and they allow you to create so many different page layouts. Users can quickly and easily built their own custom pages using all the various shortcodes that Whisper includes. Just about any element you see on our demo is a shortcode that you can insert on any page. Several shortcodes have numerous options for customization. There are endless options to choose from! Easily create your own pages by using our shortcodes, tons of possibilities and we add more all the time!

Good samples of shortcodes are homepages and other pages in the live preview demo. They’re all created with shortcodes! No need to remember shortcode attributes, all is done via a friendly interface.

When you edit a post or a page, click on **Shortcodes** button above the content editor to show the shortcodes menu.

![shortcode menu](http://fitwp.github.io/docs/whisper/shortcode-menu.png)

Select a shortcode from the menu, a popup will appear that lets you add more settings for shortcodes.

Each popup will have 3 parts:

- **Shortcode configuration** on the left: which lets you edit shortcode attributes
- **Shortcode preview** on the right: which show you preview of the shortcode
- **Insert button**: insert shortcode to the editor when you're done configuring it

Let's go one by one:



Highlight
---------

This shortcode highlights a word, sentence or any text in post content. [See demo](http://themes.fitwp.com/whisper/shortcodes/highlight/).

**Attributes:**

```
[highlight]Lorem ipsum dolor sit amet[/highlight]
[highlight background="pink"]Lorem ipsum dolor sit amet[/highlight]
[highlight custom_background="#c9c9c9"]Lorem ipsum dolor sit amet[/highlight]
```

- `background` (optional): Background color for highlighted text. Whisper has built-in 24 colors for you to choose from (see the screenshot below). If you don't choose background color, Whisper will use default color - yellow.
- `custom_background` (optional): custom background color. If you don't like any color from the predefined set, you can specify your custom background color here.

**Popup:**

![highlight](http://fitwp.github.io/docs/whisper/highlight.png)

**(1)**: choose background color for highlighted text.

**(2)**: custom background color.

**(3)**: this is a preview of shortcode, which will show you all shortcode attributes.

**(4)**: when you're done, click **Insert** button to insert shortcode to the editor.



Superscript
-----------

Simply choose a text and select superscript, the text will be display<sup>like this</sup>. There's no config for this. [See demo](http://themes.fitwp.com/whisper/shortcodes/superscript-and-subscript/).



Subscript
-----------

Simply choose a text and select subcript, the text will be display<sub>like this</sub>. There's no config for this. [See demo](http://themes.fitwp.com/whisper/shortcodes/superscript-and-subscript/).



Dropcap
-------

This shortcode displays a letter (usually the first letter of the paragraph) bigger and colored to get attraction from users. [See demo](http://themes.fitwp.com/whisper/shortcodes/dropcaps/).

**Attributes:**

```
[dropcap]L[/dropcap]orem ipsum dolor sit amet
[dropcap type="color"]L[/dropcap]orem ipsum dolor sit amet
```

- `type` (optional): empty (default) or `color`, which will display dropcap in gray square or in colored square.

**Popup:**

![dropcap](http://fitwp.github.io/docs/whisper/dropcap.png)



Divider
-------

This shortcode displays a beautiful horizontal line (divider). [See demo](http://themes.fitwp.com/whisper/shortcodes/divider/).

**Attributes:**

```
[divider]
[divider type="icon"]
```

- `type` (optional): divider type, empty (default) or `icon`. If not specified or empty, the shortcode will show a simple horizontal line. If `icon` - horizontal line with an icon.

**Popup:**

![divider](http://fitwp.github.io/docs/whisper/divider.png)



Button
------

This shortcode displays a beautiful button on your page. [See demo](http://themes.fitwp.com/whisper/shortcodes/buttons/).

**Attributes:**

```
[button link="#" color="pink" background="pink"]Click me[/button]
[button link="#" color="pink" icon="serviceicon-power" background="pink"]Click me[/button]
[button link="#" color="pink" icon="serviceicon-power" icon_position="right" align="left" full="1" background="pink" target="_blank" nofollow="1" id="myid" class="myclass"]Click me[/button]
```

- `link` (required): button URL
- `color` (required): button color name. You can choose from 24 predefined colors (see popup below)
- `size` (optional): button size, can be `small`, `medium` (default) or `large`
- `icon` (optional): button icon. You can select from 140+ premium font icons from iconsweets2 (see popup below).
- `icon_position` (optional): icon position, can be `left` (default) or `right`.
- `align` (optional): you want to float the button to the `left`, `right`, `center` or `none` (default)?
- `full` (optional): display the button full-width (block) (value `1`) or not (empty). Default is empty.
- `background` (optional): if you don't like the 24 predefined button colors, you can choose custom background and custom text color. This option is for custom background color.
- `text_color` (optional): custom text color for button.
- `target` (optional): link target, can be empty (default) - open link in same window or `_blank` - open in new window.
- `nofollow` (optional): link will be nofollowed (value `1`) or not (empty). Default is empty.
- `id` (optional): button ID, in case you want a custom HTML ID attribute for the button. It is useful when you need it for CSS or Javascript.
- `class` (optional): button CSS, in case you want a custom HTML CSS attribute for the button. It is useful when you need it for CSS or Javascript.

**Popup:**

![button](http://fitwp.github.io/docs/whisper/button.png)

In the popup, there're some advance options hidden by default. You need to click the **Advanced Button** to show them all.



Box
---

Also called **alert box**, **information box** or **styled box**.

This shortcode displays an alert, success, error or information box with a close icon or not. [See demo](http://themes.fitwp.com/whisper/shortcodes/information-boxes/).

**Attributes:**

```
[box]Lorem ipsum dolor sitamet[/box]
[box type="success" close="1"]Lorem ipsum dolor sitamet[/box]
```

- `type` (optional): box type, can be empty (or `alert`), `success`, `error`, `info`. Default is empty.
- `close` (optional): display close icon (value `1`) or not. Default is `1`.

**Popup:**

![box](http://fitwp.github.io/docs/whisper/box.png)



Toggles
-------

These shortcodes will display a panel of content which can be hide/show when you click on the panel title. [See demo](http://themes.fitwp.com/whisper/shortcodes/toggles-accordions-tabs/).

This is a combination of 2 shortcodes: `[toggles]` and `[toggle]`. `[toggles]` is a wrapper and doesn't have any attributes, while `[toggle]` is a shortcode to display each panel and has the following attributes:

**Attributes:**

```
[toggles]
[toggle title="1st panel"]Lorem ipsum dolor sitamet[/toggle]
[toggle title="2nd panel"]Lorem ipsum dolor sitamet[/toggle]
[/toggles]
```

- `title`: panel title.

**Popup:**

![toggles](http://fitwp.github.io/docs/whisper/toggles.png)

In the popup, do add more toggle panel, just click the button **Add Toggle** and fill in the title and content.



Accordions
----------

These shortcodes will display a panel of content which can be hide/show when you click on the panel title. Similar to toggles, the difference here is when a panel is opened, other panels are closed (in toggles, they still can be opened). [See demo](http://themes.fitwp.com/whisper/shortcodes/toggles-accordions-tabs/).

This is a combination of 2 shortcodes: `[accordions]` and `[accordion]`. `[accordions]` is a wrapper and doesn't have any attributes, while `[accordion]` is a shortcode to display each panel and has the following attributes:

**Attributes:**

```
[accordions]
[accordion title="1st panel"]Lorem ipsum dolor sitamet[/accordion]
[accordion title="2nd panel"]Lorem ipsum dolor sitamet[/accordion]
[/accordions]
```

- `title`: panel title.

**Popup:**

![accordions](http://fitwp.github.io/docs/whisper/accordions.png)

In the popup, do add more accordion panel, just click the button **Add Accordion** and fill in the title and content.



Tabs
----

These shortcodes will display tabs of content which can be switched when you click on the tab title. [See demo](http://themes.fitwp.com/whisper/shortcodes/toggles-accordions-tabs/).

This is a combination of 2 shortcodes: `[tabs]` and `[tab]`. `[tabs]` is a wrapper, while `[tab]` is a shortcode to display each tab content.

**Attributes:**

```
[tabs]
[tab title="1st tab" icon="serviceicon-user2"]Lorem ipsum dolor sitamet[/tab]
[tab title="2nd tab" icon="serviceicon-home"]Lorem ipsum dolor sitamet[/tab]
[/tabs]

[tabs type="vertical"]
[tab title="1st tab" icon="serviceicon-user2"]Lorem ipsum dolor sitamet[/tab]
[tab title="2nd tab" icon="serviceicon-home"]Lorem ipsum dolor sitamet[/tab]
[/tabs]
```

For `[tabs]`:

- `type` (optional): tabs style, can be empty (or `horizontal`) or `vertical`. Default is empty.

For `[tab]`:

- `title`: tab title.
- `icon` (optional): tab icon. You don't need to remmember icon name, just select from the list of icons (see popup below).

**Popup:**

![tabs](http://fitwp.github.io/docs/whisper/tabs.png)

In the popup, do add more tab, just click the button **Add Tab** and fill in the title, content and select tab icon.



Progress Bar
------------

This shortcode will display a progress bar with title and percentage. [See demo](http://themes.fitwp.com/whisper/shortcodes/progress-bar/).

**Attributes:**

```
[progress_bar text="Web Development" percent="80" type="block"]
```

- `type` (optional): can be empty or `block`. If empty, the label will display **above** the progress bar, while `block` will display the label **inside** the progress bar.
- `text`: text label
- `percent`: the percentage **without** `%`

**Popup:**

![progress bar](http://fitwp.github.io/docs/whisper/progress-bar.png)



Promotion Box
-------------

This shortcode will display a promotion box that helps you to get people attraction and improve click through rate (CTR). It's also called **Call To Action** box. [See demo](http://themes.fitwp.com/whisper/shortcodes/promo-box/).

**Attributes:**

```
[promo_box heading="We'll tell you why you should buy Whisper!" text="We are constantly improving Whisper for our beloved users." button1_text="Purchase Now" button1_link="#" button1_color="red" button1_nofollow="1"]

[promo_box type="two-buttons" heading="We'll tell you why you should buy Whisper!" text="We are constantly improving Whisper for our beloved users." button1_text="Purchase Now" button1_link="#" button1_color="red" button1_nofollow="1" button2_text="Learn More" button2_link="#" button2_color="green" button2_nofollow="1"]
```

- `type` (optional): promotion box type. Can be empty (displays 1 button) or `two-buttons` (displays 2 buttons).
- `heading`: box heading text
- `text`: box text content
- `button1_text`: button 1 text
- `button1_link`: button 1 link
- `button1_color`: button 1 color, you can choose from 24 predefined colors (see popup below)
- `button1_nofollow` (optional): set this value to `1` if you want the button link is nofollowed
- `button2_text` (optional): button 2 text
- `button2_link` (optional): button 2 link
- `button2_color` (optional): button 2 color, you can choose from 24 predefined colors (see popup below)
- `button2_nofollow` (optional): set this value to `1` if you want the button link is nofollowed

Note all the attributes for 2nd button are used only when you choose the promotion box type `two-buttons`.

**Popup:**

![promotion box](http://fitwp.github.io/docs/whisper/promotion-box.png)



Map
---

This shortcode will display a Google Maps in your pages. [See demo](http://themes.fitwp.com/whisper/shortcodes/google-maps/).

**Attributes:**

```
[map map_type="satellite" marker_title="Hanoi" info_window="This is Hanoi" zoom="14" scrollwheel="1" address="Hanoi, Vietnam" width="100%" height="400px" controls="zoom,pan,scale"]

[map type="latlng" map_type="satellite" marker_title="Hanoi" info_window="This is Hanoi" zoom="14" scrollwheel="1" latitude="10.0" longtitude="0.10" width="100%" height="400px" controls="zoom,pan,scale"]
```

- `type` (option): display map using address or latitude and longtitude. Values can be empty (use address) or `latlng` (use latitude and longtitude).
- `map_type` (optional): Google Maps type, can be road map (empty value), `satellite`, `terrain` or `hybrid`. [Learn more about Google Map types](https://developers.google.com/maps/documentation/javascript/maptypes).
- `address`: map address, used only when you set `type` empty.
- `latitude`: latitude, used only when you set `type` to `latlng`.
- `longtitude`: longtitude, used only when you set `type` to `latlng`.
- `width` (optional): map width. You can set it using `%` or `px`. Default value is `100%` which means the map is displayed full width.
- `height` (optional): map height. You can set it using `%` or `px`. Default value is `400px`.
- `marker_title` (optional): the marker title when you move the mouse over the marker.
- `info_window` (optional): the info window content when you click on the marker.
- `zoom` (optional): map zoom level, default is 8.
- `scrollwheel` (optional): allow scrollwheel when seeing the map. Values can be empty (no scrollwheen - default) or `1`.
- `controls` (optional): a comma-separated list of map controls. Each control can be one of the following value: `zoom,pan,scale,map_type,street_view,rotate,overview`. [Learn more about Google Maps controls](https://developers.google.com/maps/documentation/javascript/controls).

**Popup:**

![map](http://fitwp.github.io/docs/whisper/map.png)



Column
------

Whisper theme comes with a 12-grid columns (960.gs). This shortcode lets you display content in a column.

**Attributes:**

```
[column span="3" class="myclass" total="12"]Lorem ipsum dolor sitamet[/column]
```

- `span`: number of span columns. Can be from 1 to 12.
- `class` (optional): custom CSS class. It might be useful if you need to customize the look of the column content.
- `total` (optional): total column of the grid. By default it's 12. But if you need to display a nested grid, you should set this value to total column of the nested grid.

<div class="alert alert-error">WordPress does not support nested shortcode with **same name**, so if you want to display nested column (grid), you have to use HTML, like this:</div>

```
<div class="grid_8">
[column span="3" class="myclass" total="8"]Lorem ipsum dolor sitamet[/column]
[column span="5" class="myclass" total="8"]Lorem ipsum dolor sitamet[/column]
</div>
```

Note that in this example the `total` equals to number of columns of the `div`.

**Popup:**

![column](http://fitwp.github.io/docs/whisper/column.png)



Icon
----

Whisper has 140+ premium font icons from iconsweets2 that you can select from to make your content more attractive. [See list of icons](http://themes.fitwp.com/whisper/shortcodes/icon/).

**Attribute:**

```
[icon class="serviceicon-tools" size="64"]
```

- `class`: icon class. [See this](http://themes.fitwp.com/whisper/shortcodes/icon/) for list of icon classes. If you use the popup to pick the icon, you don't need to remmember its class.
- `size`: icon size in `px` (but don't enter `px` here). Optional. If not specified, the icon will take the font size of current element.

**Popup:**

![icon](http://fitwp.github.io/docs/whisper/icon.png)



Icon Box
--------

Icon box is a way of displaying main information in a "box", which is usually used in homepage, landing pages. [See demo](http://themes.fitwp.com/whisper/shortcodes/icon-box/).

**Attributes:**

```
[icon_box type="big" url="http://google.com" title="Configure" icon="serviceicon-tools"]Lorem ipsum dolor sit amet.[/icon_box]
[icon_box type="hex" url="http://google.com" title="Support" icon="serviceicon-group"]Lorem ipsum dolor sit amet.[/icon_box]
[icon_box type="small" title="Design" icon="serviceicon-brush"]Lorem ipsum dolor sit amet.

<a class="more-link" href="#">Continue reading <span>&gt;</span></a>[/icon_box]
```

- `type`: `big`, `hex`, `small`, `simple`. Type of icon box. See demo to know how they look like.
- `title`: icon box title (heading)
- `icon`: icon class. Same as for icon shortcode above. Just pick from the popup, or manually enter it if you remember ;)
- `url`: URL that the icon box links to. This parameter is **not** available for `small` type.

<div class="alert">You always **can** enter HTML into shortcode content. In the 3rd example above, you see how we used a link with class `more-link` and a `span` tag inside it to make a beautiful readmore link.</div>

<div class="alert">You should use icon box type `hex` and `small` within `[column]` shortcode to make the icon box same width. This is **NOT** applied to `big` type as it always takes 25% width.</div>

**Popup:**

![icon-box](http://fitwp.github.io/docs/whisper/icon-box.png)



Note Box
--------

Note box is an other way to display important information such as headlines. It's very similar to `[promo_box]` shortcode but needs a different config. [See demo](http://themes.fitwp.com/whisper/shortcodes/note-box/).

**Attributes:**

```
[note type="icon"]<h1>Lorem ipsum <span class="text-color">dolor</span> sit amet.</h1>
<p>This is awesome</p>[/note]
```

- `type`: empty (no icon) or `icon`. Display note box with icon or not. Default is empty.

<div class="alert">You always **can** (and you **should**) enter HTML into shortcode content. In the example above, you see how we used `h1`, `p` tags.</div>

<div class="alert">Use `text-color` CSS class to highlight text in note box (as in the example above)</div>

**Popup:**

![note-box](http://fitwp.github.io/docs/whisper/note-box.png)



Social Media
------------

This shortcode helps you to display links to social media networks. It shows an icon of that network. Whisper supports 60 social networks! [See demo](http://themes.fitwp.com/whisper/shortcodes/social-media-links-and-icons/).

**Attributes:**

```
[social class="pixons-wordpress" url="WordPress" title="http://wordpress.com/fitwp"]
```

- `class`: social icon class. You don't need to remember this, just click on the icon in the popup to select which social network you like.
- `url`: URL to your social network profile.

<div class="alert alert-success">You might want to copy the shortcodes to widget to show your social network profiles in sidebar, footer, etc. (same as we did in the demo).</div>

**Popup:**

![social-media](http://fitwp.github.io/docs/whisper/social-media.png)



Social Feed
-----------

This shortcode shows items from the feed of creative social networks: Pinterest, Deviant Art, Flickr, Dribbble, Youtube, Instagram and Newsfeed (RSS). [See demo](http://themes.fitwp.com/whisper/shortcodes/social-feed/).

**Attributes:**

```
[social_feed network="pinterest" username="fitwp" limit="16"]
```

- `network`: name of the network that you want to fetch items from
- `username`: your username on that network.
- `limit`: number of items will be displayed

<div class="alert">For newsfeed (RSS) `username` **must** be the RSS link of the feed.</div>

**Popup:**

![social-feed](http://fitwp.github.io/docs/whisper/social-feed.png)



Team Member
-----------

This displays a team member profile on your website. [See demo](http://themes.fitwp.com/whisper/shortcodes/team-member/).

**Attributes:**

```
[team_member name="Mathew Parkson" position="Senior Manager" photo="http://themes.fitwp.com/whisper/wp-content/uploads/sites/3/2013/12/team-1.jpg" phone="+00 123 4567" email="mathewp@business.com"]It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.[/team_member]
```

- `name`: member name
- `position`: member position
- `photo`: URL to member's image. You should use Media Library to upload image and then paste image URL here.
- `phone`: phone number
- `email`: email address
- Content of the shortcode: member's biography

**Popup:**

![team-member](http://fitwp.github.io/docs/whisper/team-member.png)



Clients
-------

This shortcode displays a list of your clients in a carousel slider. [See demo](http://themes.fitwp.com/whisper/shortcodes/clients/).

This shortcode actually contains 2 shortcodes: `[clients]` is a wrapper and `[client]` is the shortcode that contains each client's information.

**Attributes:**

```
[clients title=Our Clients]
[client name="FitWP" url="http://fitwp.com" image="http://fitwp.com/avatar"]Building premium WordPress themes.[/client]
[client name="Deluxe Blog Tips" url="http://dbt.com" image="http://dbt.com/avatar"]WordPress tips.[/client]
[/clients]
```

For `[clients]`:

- `title` (optional): the title of the carousel slider.

For `[client]`:

- `name`: client's name
- `url`: client's URL
- `image`: client's image
- The content of the shortcode: client's description

<div class="alert alert-success">Althought this shortcode is called **Clients**, you can use it to display **testimonials**!</div>

**Popup:**

![clients](http://fitwp.github.io/docs/whisper/clients.png)

In the popup, when you need to add more client, just click **Add Client** button.



Posts
-----

This shortcode display latest posts from your blog on your pages **in a grid**. [See demo](http://themes.fitwp.com/whisper/shortcodes/posts/).

**Attributes:**

```
[posts title_wrap="1" title="Blog Posts" number="3" category="company-news" content_limit="25" more="Continue Reading" total_columns="12"]
[posts title_wrap="1" title="Blog Posts" number="3" content_limit="30" more="Read more" total_columns="9"]
```

- `title_wrap`: show a title for the shortcode or not? Value can be empty (not display) or `1` (display).
- `title`: the title of the shortcode. Used only when `title_wrap` is set to `1`
- `number`: number of blog posts to show
- `category`: **slug** (*not* name or ID) of category where do you want to get posts from. If empty, then posts will be get from all categories.
- `content_limit`: number of words of post content will be displayed.
- `more`: read more link text
- `total_columns`: the total columns of all blog posts will display. This value is used to calculate the column of each post.

For example: if you want to display 2 blog posts in a grid 8 columns (like page content), each post will be 4 columns, then use:

```
[posts title_wrap="1" title="Blog Posts" number="2" content_limit="30" more="Read more" total_columns="8"]
```

If you want to display 4 posts, each post is 3 columns, then total columns is 12:

```
[posts title_wrap="1" title="Blog Posts" number="4" content_limit="30" more="Read more" total_columns="12"]
```

**Popup:**

![posts](http://fitwp.github.io/docs/whisper/posts.png)

In the popup, click **Advanced Button** to show more options for the shortcode.



Portfolios
----------

Similar to `[posts]` shortcode, this shortcode display latest portfolios from your blog on your pages **in a grid**. [See demo](http://themes.fitwp.com/whisper/shortcodes/portfolios/).

**Attributes:**

```
[portfolios title_wrap="1" title="My Works" number="3" format_icon="1" total_columns="9"]
```

- `title_wrap`: show a title for the shortcode or not? Value can be empty (not display) or `1` (display).
- `title`: the title of the shortcode. Used only when `title_wrap` is set to `1`
- `number`: number of blog posts to show
- `format_icon`: show post format icon (value `1`) or not (empty value). Default is empty.
- `total_columns`: the total columns of all postfolios will display. This value is used to calculate the column of each post.

For example: if you want to display 2 postfolios in a grid 8 columns (like page content), each postfolio will be 4 columns, then use:

```
[portfolios title_wrap="1" title="My Works" number="2" format_icon="1" total_columns="8"]
```

If you want to display 4 portfolios, each post is 3 columns, then total columns is 12:

```
[portfolios title_wrap="1" title="My Works" number="4" total_columns="12"]
```

**Popup:**

![portfolios](http://fitwp.github.io/docs/whisper/shortcode-portfolios.png)

In the popup, click **Advanced Button** to show more options for the shortcode.



Posts/Portfolios Tab
--------------------

This shortcode displays tabs of posts and portfolios. [See demo](http://themes.fitwp.com/whisper/shortcodes/post-portfolio-tab/).

This shortcode doesn't contains any parameters, just use it:

```
[post_portfolio_tab]
```




Credits
=======

1. Nivo Slider
1. prettyPhoto Lightbox
1. Iconmoon application – <a href="http://icomoon.io/">http://icomoon.io/</a>
1. iconsweets2-  <a href="http://www.iconsweets2.com/">http://www.iconsweets2.com/</a>
1. Magnifier shapes icons – <a href="http://www.shapes4free.com/photoshop-custom-shapes/zoom-magnifier-photoshop-shapes/">http://www.shapes4free.com/photoshop-custom-shapes/zoom-magnifier-photoshop-shapes/</a>
1. Quicksand plugin
1. jQuery Easing
1. carouFredSel
1. HTML5shiv
1. jQuery placeholder
1. Tweetable plugin
1. Big buck bunny video – <a href="http://vimeo.com/1084537">http://vimeo.com/1084537</a>
1. jPlayer Plugin for jQuery JavaScript Library by Mark J Panaghiston
1. Images:
	1. Jean-Maurice Damour – <a href="http://www.behance.net/JeanMauriceDamour?">http://www.behance.net/JeanMauriceDamour?</a>
	1. Gorm Haraldsson – <a href="http://gormelito.deviantart.com/">http://gormelito.deviantart.com/</a>
	1. Kevin Roodhorst – <a href="http://www.behance.net/kevinroodhorst">http://www.behance.net/kevinroodhorst</a>
	1. Rogier de Boeve – <a href="http://www.behance.net/rdbok">http://www.behance.net/rdbok</a>
	1. Julien Renault – <a href="http://www.behance.net/julienrenault">http://www.behance.net/julienrenault</a>
