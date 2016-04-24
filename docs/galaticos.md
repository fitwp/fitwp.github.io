---
layout: docs
title: Galaticos Documentation
description: Galaticos WordPress theme documentation
---

Welcome! First of all we want to thank you for purchasing our Galaticos WordPress Theme.

In the following sections we will explain how to set up and use Galaticos theme the easiest way possible. Although there're a lot of things written in this documentation, the theme itself is not hard to use. You can go to the Theme Options page and explore everything yourself. This file is more of a reference if you do not know what to do, or if you are not familiar with WordPress.

If you have any questions that are beyond the scope of this help file, please feel free to ask your questions at the [support forum](http://fitwp.com/envato-support/).

Best regards




## Resources

- **Online Documentation:** (this file) /galaticos/
- **Support Forum:** http://fitwp.com/envato-support/




## Theme Information

- **Theme Name:** Galaticos WordPress Theme
- **Author:** FitWP
- **Theme URL:** http://fitwp.com/themes/galaticos/
- **Author Website:** http://fitwp.com




## Files Included

The download package (`.zip`) that you get from ThemeForest contains the following files and folder:

- `galaticos.zip`: main theme file that need to be uploaded to host to install Galaticos theme
- `demo-content.xml`: demo content file, which contains all pages and posts from live preview website. It will help you to have a first look of how we use Galaticos theme
- `docs.html`: theme documentation (this file)
- `theme-options.txt`: theme option backup file. You'll need this to restore the default theme options that setup for demo website.
- `Plugins`:
	- `codecanyon-2751380-slider-revolution-responsive-wordpress-plugin.zip`: [Slider Revolution Responsive WordPress Plugin](http://codecanyon.net/item/slider-revolution-responsive-wordpress-plugin/2751380). Completed download package from Codecanyon.net. It's FREE for you to use with Galaticos theme
	- `home-page-slider.zip`: Demo slider that exported from our demo, but with placeholder images



## Installation


### Install Theme

After you download the `.zip` package from ThemeForest, unzip it. You'll see a file `galaticos.zip`, which is the main file that needed to upload and install.

**Notice**: If you download **Installable WordPress file** then that file is the zip file we use to upload and install.

You can either choose to upload and installl the theme using **FTP** or use **WordPress theme install** function.

### Upload and install using FTP

- Unzip `galaticos.zip`, you'll get a folder `galaticos`
- Use a FTP client like [FileZilla](http://filezilla-project.org/) and upload that folder to `wp-content/themes` folder on your host
- Go to `Appearance > Themes` and activate **Galaticos** theme

### Install theme using WordPress install function

- Go to `Appearance > Themes` and click **Add New**
- Select **Upload**
- Click **Browse** and select the `galaticos.zip` file
- Click **Install Now**
- When upload and installation progresses are completed, click **Activate**, or go to `Appearance > Themes` and activate **Galaticos** theme

![upload](http://docs.fitwp.com/whisper/wordpress-upload.png)




### Install plugins

After installing Galaticos, you'll see a notification in the top of the page that says the theme needs some plugins to function properly.

Galaticos theme **requires** follow plugins (all are free and available on WordPress.org):

- [Meta Box](http://wordpress.org/plugins/meta-box/)
- FitWP Shortcodes

Galaticos theme **recommends** follow plugins:

- [WooCommerce - excelling eCommerce](http://wordpress.org/plugins/woocommerce/)
- [WR MegaMenu](https://wordpress.org/plugins/wr-megamenu/)
- [Contact Form 7](http://wordpress.org/plugins/contact-form-7/)
- [MailPoet Newsletters](https://wordpress.org/plugins/wysija-newsletters/)
- [Slider Revolution Responsive WordPress](http://codecanyon.net/item/slider-revolution-responsive-wordpress-plugin/2751380) plugin ($18 on CodeCanyon, included in download package)

Galaticos is working perfectly with these plugins. It automatically adds more styles to them to make the design match the theme.

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


### Setup homepage and blog page

After install demo content, you'll see a page `Homepage`. This page will be used as the homepage of the website. To set it as homepage, please go to `Settings \ Reading`, under **Front page displays**, please chose **A static page (select below)** and select **Front Page** for **Front page** and **Full Width** page for **Posts page**.

![homepage](http://docs.fitwp.com/galaticos/homepage.png)




### Setup Menu

Although the theme is working now and it shows menu, but because we haven't created a menu for primary location, the theme will display all pages by default. As the number of pages is large, displaying all of them in the menu is a bad idea.



### Create or edit a menu

Following these steps to create a menu:

- Go to `Appearance > Menus`
- Select an existing to edit, or click **create a new menu**. **Note:**Select one of menu from menu list if you want to have same menu as in live preview.
- Select pages from the left meta box and click **Add to Menu**
- On the right, feel free to drag and drop menu items to organize them
- When you're done moving menu items, check **Primary Menu** for **Theme locations** at the bottom of the page
- Click **Save Menu**

![menu](http://docs.fitwp.com/galaticos/menu.png)


### Setup widget areas

Galaticos theme has 4 widget areas (sidebars) by default:

- **Blog Sidebar:** main website sidebar which will be displayed on all blog posts, archive pages, etc.
- **Page Sidebar:** will be displayed on all WordPress pages.
- **Shop Sidebar:** will be displayed on all WooCommerce pages: Products, Product category, Single Product, etc.
- **Home Sidebar:** will be displayed on Homepage template (we'll talk about this template later in **Page Templates** section).
- **Footer Sidebars:** there are 4 default sidebars for footer, each sidebar is a column in the footer. You can change number of columns in footer in Theme Options page (in that case number of footer sidebars will increased or decreased acccordingly).

To setup a sidebar, select it from the right by clicking its title or the arrow down. Then drag and drop widgets from the left to the sidebar area.

![sidebar](http://docs.fitwp.com/whisper/sidebar.png)

That's all! Now you have the website up with all *basic* elements!




## Theme Options

![theme options](http://docs.fitwp.com/galaticos/theme-options.png)

The Galaticos theme comes with unique, creative and easy-to-use Theme Options page. You can change all theme options in one place!

With Galaticos's advanced theme options panel, you can customize just about any part of your site quickly and easily. Every element on the site can have the color changed to your liking. Choose a color scheme for website, select fonts for all headings and body copy, change sizes, colors and line-heights of all fonts, select different footer column layouts, enable or disable several options, upload your own custom favicon, select from various site/page layouts, input custom CSS, set hundreds of other options to easily customize your site!

All options have full description so you can know what you are doing. Just click and save!

Let's go through each section.




### General

![general](http://docs.fitwp.com/galaticos/general-option.png)

This sections contains:

- **(1)**: favicon upload, allows you to upload favicon for you website
- **(2)**: touch icon, allows you to upload icon for mobile devices and tablets
- **(3)**: show comment on page
- **(4)**: backup - restore, allows you to backup Galaticos options and restore them later, or transfer the saved options between different installs.

Here are the explanations of some options that can help you understand and use them better:



### Favicon Upload

[Favicon](http://en.wikipedia.org/wiki/Favicon) (short for Favorite icon), also known as a shortcut icon, Web site icon, tab icon or bookmark icon, is a file containing one or more small icons, most commonly 16x16 pixels, associated with a particular Web site or Web page. Browsers that provide favicon support typically display a page's favicon in the browser's address bar (sometimes in the history as well) and next to the page's name in a list of bookmarks. Browsers that support a tabbed document interface typically show a page's favicon next to the page's title on the tab, and site-specific browsers use the favicon as a desktop icon.

This is how favicon appears:

![favicon](http://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Wikipedia_favicon_in_Firefox_on_KDE.png/250px-Wikipedia_favicon_in_Firefox_on_KDE.png)

Galaticos lets you upload favicon or enter favicon URL in the input box:

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

This option allows you to show/hide comments and comment form on pages. By default, Galaticos doesn't display comments and comment form on pages.

**Important**: In case this option is set to "ON", to display comments on pages, you still have to **allow comments** for pages when you edit pages.

![allow comments](http://docs.fitwp.com/glamo/allow-comments.png)

By default, this checkbox is checked (meaning comments are allowed on pages). But in case you want to show comments on all pages, except some specific pages, you can use this checkbox to hide comments for those pages only.



### Backup - Restore

Galaticos allows you to backup theme options and restore them later. You can also transfer the saved options data between different installs.

To backup theme options, just copy the text inside the text box and save it into a file on your computer. To import data, replace the data in the text box with the one from the saved file and click **Import Options** button.

After clicking **Import Options**, Galaticos will automatically setup all options and refresh the current theme options page, so you can see the options immediately.




### Design

This sections contains:

- **Color Scheme**: allows you to change color scheme of whole website
- **Layout**: allows you to change layout style and layout for whole website, for blog posts and pages
- **Typography**: allows you to change font family, styles, size, line height, color for body text and headings
- **Custom CSS**: allows you to add your custom CSS



### Color Scheme

Galaticos theme has **5 predefined color schemes** to choose from: blue, red, green, violet and orange. When you change color scheme of the theme, all links, button background and other elements will change their color or background accordingly.

The default color scheme is red, but you can select any from 5 colors here. After selecting, click **Save Changes** button to save your data. Now go to the frontend and check the colors of links, buttons, etc.

When you select **Color Scheme** section, you'll see the following options:

![color schemes](http://docs.fitwp.com/galaticos/design-color-schemes.png)

**(1)**: select built-in color scheme. These are 5 predefined color schemes. When you select one of them, your website elements will change color accordingly.

**(2)**: enable/disable custom color scheme. This option allow you create **custom color scheme**, and you can build unlimited color schemes here! Just enable this and you'll see options below.

**(3)**: primary color. This is primary color for your custom color scheme, used for links, overlay, button background on hover, badges, etc.



### Layout

This section helps you to select which layout will be use in whole website.

![layout](http://docs.fitwp.com/galaticos/design-layout.png)

**(1)**: sidebar layout **for blog, single posts and other archive pages**. You can select sidebar position here: `left`, `right` or `none` (don't display sidebar)

**(2)**: sidebar layout for **WooCommerce pages**. Same meaning as for blog above but only applied for WooCommerce pages: **shop page, single products, product tag archive, product category archive**.

**(3)**: sidebar layout **for pages**. Same meaning as for blog above.

Examples: [sidebar left](http://demo2.fitwp.com/galaticos/sidebar-left/) - [sidebar-right](http://demo2.fitwp.com/galaticos/sidebar-right/)

<div class="alert alert-info">These options is site-wide, meaning for whole website. But you still can set **custom layout for single post and page when edit** (We'll explore it later).</div>

By default: Galaticos uses **wide** layout style with **right** sidebar for both blog and pages.



### Typography

![typography](http://docs.fitwp.com/galaticos/design-typography.png)

This section helps you to customize fonts for **body text** and **headings** on your website. For each element, you can customize:

**(1)**: font family. Just select from the dropdown font family you like. Galaticos supports 3 normal fonts (Arial, Verdana and Times).

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

![custom css](http://docs.fitwp.com/galaticos/design-custom-css.png)

This section allows to enter custom CSS that will be output in the `</head>`. This will **overwrite** CSS of theme, so please be careful!

Custom CSS is useful when you want to adjust **small things** for your website. If you have to adjust a lot of things in website, please use [Child Themes](http://codex.wordpress.org/Child_Themes).




### Header

![header](http://docs.fitwp.com/galaticos/header.png)

This sections contains:

**(1)**: logo upload, allows you to upload logo for you website. You can either put the URL of the logo into the input box or upload the logo to Media Library. The live preview of the logo will appear below the inputs.

**(2)**: logo size. Specify logo size in **px** here. It will help you resize the logo to correct dimensions. By default, the good size is **201x39**.

**(3)**: logo margin. Specify logo margin in **px** here. This is useful when you upload logo with different size than recommended. You can *move* logo a little, adjust space to make it look good.

<div class="alert alert-info">You should **resize the logo to correct size** in Photoshop or any image editor before upload. It will keep your logo not resized and small size.</div>

**(4)**: sticky header. This option allow you to make the header sticky, i.e. always stays on the top of the website when scrolling.

**(5)**: show shop cart icon. This option allow you show a shop cart icon on header. This option effects only when WooCommerce plugin is installed.

**(6)**: show search icon. This option  allow you show search icon.

**(7)**: header scripts. Enter scripts or code you would like output to `&lt;head&gt;`. It can be:

- `<link>` tag for custom font (from Google Fonts maybe)
- Any meta tag: to show the designer, copyright, etc. in meta tag
- Google Analytics code
- Any Javascript code that need to be execute in `&lt;head&gt;`
- Anything else

<div class="alert alert-error">If you want to put custom CSS here, you're doing **wrong**. There's a section for **Custom CSS** under **Design**, use it instead.</div>




### Featured Title Area

![featured title area](http://docs.fitwp.com/galaticos/featured-title-area.png)

Featured Title Area is the highlighted area in the screenshot above. This area shows you an attractive title area with this information:

- **(1)**: Breadcrumbs
- **(2)**: Background image

Galaticos uses a **default image** for background and **show** breadcrumbs.

In theme options page, you can change the background image and show/hide breadcrumbs for whole website:

![featured title area](http://docs.fitwp.com/galaticos/options-featured-title-area.png)

**(1)**: show/hide breadcrumbs. Default is **OFF** (show breadcrumbs). If you want to hide breadcrumbs, just turn it on.

**(2)**: custom background image. You can either put the URL of the image into the input box or upload the image to Media Library. The live preview of the background will appear below the inputs.

<div class="alert alert-info">Tips: [Subtle Patterns](http://subtlepatterns.com/) is a good resource to find background patterns!</div>

<div class="alert alert-info">These options is site-wide, meaning for whole website. But you still can set **custom featured title area for single post and page when edit** (We'll explore it later).</div>




### Blog

![blog](http://docs.fitwp.com/galaticos/blog.png)

This section helps you to change the display options for posts in blog page (and other archive pages). This section contains:
**(1)**: Exclude categories
**(2)**: what type of post content will be displayed. Available options are `Post excerpt`, `Post content` or `Post content before more tag`.

To understand what those values mean, take a look at the screenshot bellow:

![post](http://docs.fitwp.com/whisper/post-content.png)

Where:

- **(A)**: Whole post content, this is what you enter in the editor.
- **(B)**: Post excerpt, which is optional hand-crafted summaries of your content. [Learn more about manual excerpt.](http://codex.wordpress.org/Excerpt). If you don't enter anything in the excerpt box, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
- **(C)**: The post content before `more` tag
- **(D)**: The `more` tag

Return to blog option: if you choose

- `Post excerpt`: Galaticos will get post excerpt and display it. **Remember**: if you don't enter excerpts for post, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
- `Post content`: Galaticos will get whole post content and display it. This is the default value.
- `Post content before more tag`: Galaticos will get only the post content before `more` tag and display it.

**(3)**: post content limit. Sometimes you enter a very long text for post excerpt or post content, display such long text in blog and archive pages is not good and harm your website beauty. So we need a way to truncate text to make it shorter. This option is created for that purpose.

Simply specify number of words will be display here. Post content or excerpt will be truncated to exact number of words. You should try changing this value and preview your blog to see what is best for you.

Default value is **55 words**.

<div class="alert">**Important**: this option affects only when you **NOT** choose `Post Content` from the Display option above</div>

**(4)**: readmore text. Default value is **Continue reading**.

**(5)**: Show Socials Sharing.


### Shop

This section give you options to customize shop page on your website.

![shop](http://docs.fitwp.com/galaticos/shop.png)

**(1)**: Default product image. This image will be used when product has no image to display as thumbnail.
**(2)**: Default Products View. Select the default view for products
**(3)**: Number of products. Set default number of products to display in the shop page.
**(4)**: Number of products. Set default number of products to display in the shop page
**(5)**: Show featured badge. Display a badge for featured products.If you choose show featured badge, on the shop page will display like this:

![featured badge](http://docs.fitwp.com/galaticos/featured-badge.png)

**(6)**: Show new badge. Display a badge for new products.
**(7)**: Badge display duration. The number of days a product will be set as new product, since the published date.


### Portfolio

This section give you options to customize portfolio page on your website.

![portfolio](http://docs.fitwp.com/galaticos/portfolio.png)

**(1)**: portfolio category view. Select the default view for Portfolio category page.

**(2)**: number of projects. Set number of Portfolio projects to display in the Portfolio category page

**(3)**: portfolio single view. Select the default view for Portfolio single page




### 404 page

This section give you 1 option to customize 404 page on your website.

![404 page](http://docs.fitwp.com/galaticos/testimonial.png)

**(1)**: Select background image for 404 page page.





### Footer

This section give you options to customize footer area on your website.

![footer-frontend](http://docs.fitwp.com/galaticos/footer-frontend.png)

**(1)**: footer ads. Allow Html and shortcode

**(2)**: footer widgets. Enable to display widgets in footer.

**(3)**: number of columns in footer. It also is the number of footer sidebars (widget areas). Default is **4**.

**(4)**: copyright text. You can enter text, HTML and **shortcodes** here. To make you easier to display copyright text, Galaticos has default shortcodes that you can enter here:

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

**(5)**: footer scripts. Enter scripts or code you would like output before `&lt;/body&gt;`. It can be Google Analytics code or any Javascript code.





## Customizer

Customizer is a feature of WordPress that allows us to tweak a theme's settings and see a preview of those changes in real time. And since version 2.0, Galaticos supports Customizer, which means you can change theme options and preview those changes in real time! You even don't need Theme Options page, unless you want something more advanced like footer scripts!

To start with Customizer, please go to **Appearance \ Customize**, you'll see the following screen:

![customizer](http://docs.fitwp.com/galaticos/customizer.png)

**(1)**: there are some sections that you can change and live preview it. These sections have `[Galaticos]` in their title.

**(2)**: click on each section title will show options for that section. These options are the same as in Theme Options, so it's easy to understand (please refer to Theme Options in this documentation to know exactly each detail).

**(3)**: this is the panel where you'll see your website in real time whenever you change anything.

Remember to click the **Save & Publish** on the top of left panel when you're done tweaking themes!





## Post/Page Display Settings

We've seen how to change featured title area, layout style, sidebar layout for whole website. Galaticos also supports customizing these things for specific posts and pages.

When you edit a page or a post, you'll see this meta box below the content editor:

![display settings](http://docs.fitwp.com/galaticos/display-settings-page.png)

This meta box contains 3 main parts:

1. **Featured Title Area Settings**
1. **Breadcrumb**
1. **Custom Layout Settings**

Each parts contains some settings as shown in the screenshot above. Let's go through it:



### Featured Title Area

This is the featured title area which is displayed in the frontend

![featured title area](http://docs.fitwp.com/galaticos/featured-title-area.png)

where:

- **(1)**: Breadcrumbs
- **(2)**: Background image
- **(3)**: Page title
- **(4)**: Page subtitle

Let's go back to the page display settings above, we have these settings:

**(1)**: hide featured title area. Check this box if you want to hide the featured title area. This option *should* be used in special pages like homepage.

**(2)**: hide text. Allow to hide both title and subtile.

**(3)**: custom title. Enter the custom page title here. By default Galaticos displays post/page title, but you can customize the real title shown in Featured Title Area. It is useful when you have a very long title.

**(4)**: subtitle. Enter subtitle for page here. Leave this empty if you don't want to show subtitle.

**(5)**: custom background. If you choose an image, it will be used as the background for Featured Tittle Area. If you do not, Galaticos will use default image set in **Theme Options**.

**(5)**: hide breadcrumbs. The theme already has settings to show/hide breadcrumbs side-wide. But if you want to hide breadcrumbs for a specific post/page, you can select this option.



### Breadcrumb

This part contains only 1 input field **(6)**, hide breadcrumbs. The theme already has settings to show/hide breadcrumbs side-wide. But if you want to hide breadcrumbs for a specific post/page, you can select this option.



### Custom Layout

In this part, you can change:

**(7)**: whether to use custom page layout. If you check this box, you're able to set custom layout style and sidebar layout below. If you don't, page will use default layout set in **Theme Options**.

**(8)**: custom sidebar layout. Choose custom sidebar layout for page. If you don't choose anything, Galaticos will use default sidebar layout set in **Theme Options**.




## Add/Edit Portfolio

When you add or edit a portfolio, you need to fill in some required information to make it displays correctly. Look at 3 meta boxes:

**(1)Portfolio Settings**: portfolio main information
**(2)Portfolio Categories**: portfolio categories
**(3)Featured Image**: portfolio featured image

![portfolio](http://docs.fitwp.com/galaticos/portfolio-setting.png)

In the **(1)** meta box, you have to:

- Select or upload portfolio images, these images will be used in the portfolio slider
- Clients: name of clients
- Skills

In the **(Portfolio categories)** meta box, you can select or create new categories for portfolio. Note that the categories will be used to **filter** portfolios in **Portfolios** archive page.

In the **(2)** meta box, simply select featured image for the portfolio as a normal post. You can choose the same image that you have uploaded in **(1)** meta box or a new one. This image will be used to display as portfolio thumbnail.


## Post Formats

[Post Formats](http://codex.wordpress.org/Post_Formats) is theme feature which is a piece of meta information that can be used by a theme to customize its presentation of a post.

In short, with a theme that supports Post Formats, a blogger can change how each post looks by choosing a Post Format from a radio-button list.

Galaticos theme supports the following post formats:

- `gallery` - A gallery of images, which will be displayed in a responsive image slider, powered by Flexslider.
- `link` - A link to another site.
- `image` - A single image, which will be shown above post title.
- `quote` - A quotation.
- `video` - A single video, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed above post title.
- `audio` - An audio file, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed using a powerful HTML5 audio player – jPlayer.

Each post format will have an icon near post title which tells you what post format is. Using post format in Galaticos lets you differentiate post from each other and make the blog page / single page looks more beautiful.

[See blog page](http://themes.fitwp.com/whisper/blog/) to see how post formats look.



### Setup Post Formats

When you edit a post, select a format you want to apply to that post on the **Format** meta box on the right:

![formats](http://docs.fitwp.com/whisper/post-formats-box.png)

When you choose a format, a corresponding meta box will appear **below** the content editor, here's the list of them:

![formats](http://docs.fitwp.com/whisper/post-formats-boxes.png)

All you need to do is just enter **all** information in the fields in these meta boxes. This information will be used to decorate the post. For example: gallery post format will uses uploaded images to show a slider above post title, a video post will display a video player above post title, etc.




## Page Templates

Galaticos has some build-in page templates that can help you create special pages easier:

- **Blog**: template to display blog posts
- **Portfolio**: display portfolios

When you edit a page, look at on the right, find **Page Attributes** meta box and select a template from the dropdown **Template**:

![page-templates](http://docs.fitwp.com/galaticos/page-templates.png)

For **Blog**,  **Portfolio** there's no configurations at all. After select page template from the meta box on the right, you just need to save the page and see it in action in the frontend.



## Widgets

Galaticos plays nicely with default WordPress widgets. Besides that the theme has some additional widgets that might be useful for you:




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

![twitter app](http://docs.fitwp.com/galaticos/twitter-app-token.png)

- Now you can copy the following fields for setting up Latest Tweets widget:
	+ API key  -> Consumer Key
	+ API secret -> Consumer Secret
	+ Access token -> Access token
	+ Access token secret -> Access token secret

These fields will be used in the tweets widget.

Now go to your website admin area, then `Appearance > Widgets`, drag and drop **[FitWP] Latest Tweets** widget into a sidebar that you want it to show there. You'll see these fields this:

![tweets](http://docs.fitwp.com/galaticos/widget-tweets.png)

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


### [FitWP] Social Feed

This widget shows items from the feed of creative social networks: Pinterest, Deviant Art, Flickr, Dribbble, Youtube, Instagram and Newsfeed (RSS). It uses `[social_feed]` shortcode to display items.

The configuration for this widget is simple:

- Choose a network that you want to display items from
- Enter your username
- And enter the number of items will be displayed




## Shortcodes

The Galaticos theme is bundled with powerful shortcodes that you can customize your page content in thousand ways!

With Galaticos Shortcode Generator, there is a shortcode for anything you need, and they allow you to create so many different page layouts. Users can quickly and easily built their own custom pages using all the various shortcodes that Galaticos includes. Just about any element you see on our demo is a shortcode that you can insert on any page. Several shortcodes have numerous options for customization. There are endless options to choose from! Easily create your own pages by using our shortcodes, tons of possibilities and we add more all the time!

Good samples of shortcodes are homepages and other pages in the live preview demo. They’re all created with shortcodes! No need to remember shortcode attributes, all is done via a friendly interface.

When you edit a post or a page, click on **Shortcodes** button above the content editor to show the shortcodes menu.

![shortcode menu](http://docs.fitwp.com/galaticos/shortcode-menu.png)

Select a shortcode from the menu, a popup will appear that lets you add more settings for shortcodes.

Each popup will have 3 parts:

- **Shortcode configuration** on the left: which lets you edit shortcode attributes
- **Shortcode preview** on the right: which show you preview of the shortcode
- **Insert button**: insert shortcode to the editor when you're done configuring it

Let's go one by one:



### Highlight

This shortcode highlights a word, sentence or any text in post content.

**Attributes:**

```
[highlight]Lorem ipsum dolor sit amet[/highlight]
[highlight background="pink"]Lorem ipsum dolor sit amet[/highlight]
[highlight custom_background="#c9c9c9"]Lorem ipsum dolor sit amet[/highlight]
```

- `background` (optional): Background color for highlighted text. Galaticos has built-in 24 colors for you to choose from (see the screenshot below). If you don't choose background color, Galaticos will use default color - yellow.
- `custom_background` (optional): custom background color. If you don't like any color from the predefined set, you can specify your custom background color here.

**Popup:**

![highlight](http://docs.fitwp.com/whisper/highlight.png)

**(1)**: choose background color for highlighted text.

**(2)**: custom background color.

**(3)**: this is a preview of shortcode, which will show you all shortcode attributes.

**(4)**: when you're done, click **Insert** button to insert shortcode to the editor.



### Superscript

Simply choose a text and select superscript, the text will be display<sup>like this</sup>. There's no config for this.



### Subscript

Simply choose a text and select subcript, the text will be display<sub>like this</sub>. There's no config for this.




### Button

This shortcode displays a beautiful button on your page. [See demo](http://demo2.fitwp.com/galaticos/button/).

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

![button](http://docs.fitwp.com/whisper/button.png)

In the popup, there're some advance options hidden by default. You need to click the **Advanced Button** to show them all.



### Box

Also called **alert box**, **information box** or **styled box**.

This shortcode displays an alert, success, error or information box with a close icon or not.

**Attributes:**

```
[box]Lorem ipsum dolor sitamet[/box]
[box type="success" close="1"]Lorem ipsum dolor sitamet[/box]
```

- `type` (optional): box type, can be empty (or `alert`), `success`, `error`, `info`. Default is empty.
- `close` (optional): display close icon (value `1`) or not. Default is `1`.

**Popup:**

![box](http://docs.fitwp.com/whisper/box.png)



### Toggles

These shortcodes will display a panel of content which can be hide/show when you click on the panel title. [See demo](http://demo2.fitwp.com/galaticos/accordion-and-toggle/).

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

![toggles](http://docs.fitwp.com/whisper/toggles.png)

In the popup, do add more toggle panel, just click the button **Add Toggle** and fill in the title and content.



### Accordions

These shortcodes will display a panel of content which can be hide/show when you click on the panel title. Similar to toggles, the difference here is when a panel is opened, other panels are closed (in toggles, they still can be opened). [See demo](http://demo2.fitwp.com/galaticos/accordion-and-toggle/).

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

![accordions](http://docs.fitwp.com/whisper/accordions.png)

In the popup, do add more accordion panel, just click the button **Add Accordion** and fill in the title and content.



### Tabs

These shortcodes will display tabs of content which can be switched when you click on the tab title. [See demo](http://demo2.fitwp.com/galaticos/tabs-shortcode/).

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

![tabs](http://docs.fitwp.com/whisper/tabs.png)

In the popup, do add more tab, just click the button **Add Tab** and fill in the title, content and select tab icon.



### Progress Bar

This shortcode will display a progress bar with title and percentage. [See demo](http://demo2.fitwp.com/galaticos/progress-bar-pie-chart-counter/).

**Attributes:**

```
[progress_bar text="Web Development" percent="80" type="block"]
```

- `type` (optional): can be empty or `block`. If empty, the label will display **above** the progress bar, while `block` will display the label **inside** the progress bar.
- `text`: text label
- `percent`: the percentage **without** `%`

**Popup:**

![progress bar](http://docs.fitwp.com/whisper/progress-bar.png)



### Promotion Box

This shortcode will display a promotion box that helps you to get people attraction and improve click through rate (CTR). It's also called **Call To Action** box.

**Attributes:**

```
[promo_box heading="We'll tell you why you should buy Galaticos!" text="We are constantly improving Galaticos for our beloved users." button1_text="Purchase Now" button1_link="#" button1_color="red" button1_nofollow="1"]

[promo_box type="two-buttons" heading="We'll tell you why you should buy Galaticos!" text="We are constantly improving Galaticos for our beloved users." button1_text="Purchase Now" button1_link="#" button1_color="red" button1_nofollow="1" button2_text="Learn More" button2_link="#" button2_color="green" button2_nofollow="1"]
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

![promotion box](http://docs.fitwp.com/whisper/promotion-box.png)



### Map

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

![map](http://docs.fitwp.com/whisper/map.png)




### Row

Galaticos theme comes with a 12-grid columns (960.gs). This shortcode lets you display content in a row and column.

**Attributes:**

```
[row background="http://demo2.fitwp.com/galaticos/wp-content/uploads/sites/3/2011/05/best-twitter-wallpaper.jpg" parallax="1" fluid="1" class="promotion"]
[column span="8"]Lorem ipsum dolor sitamet[/column]
[column span="4"][button link="#" color="black" type="rounded" size="small"]PURCHASE NOW[/button][/column]
[/row]
```

- `background` (optional): background of row.
- `parallax`: allow to on/off parallax
- `fluid`: display full width.
- `class` (optional): custom CSS class. It might be useful if you need to customize the look of the row content.

**Popup:**

![column](http://docs.fitwp.com/galaticos/shortcode-row.png)




### Column

This shortcode lets you display content in a column. [See demo](http://demo2.fitwp.com/galaticos/columns/).

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

![column](http://docs.fitwp.com/whisper/column.png)



### Icon

Galaticos has 140+ premium font icons from iconsweets2 that you can select from to make your content more attractive.

**Attribute:**

```
[icon class="serviceicon-tools" size="64"]
```

- `class`: icon class. You can use the popup to pick the icon, you don't need to remmember its class.
- `size`: icon size in `px` (but don't enter `px` here). Optional. If not specified, the icon will take the font size of current element.

**Popup:**

![icon](http://docs.fitwp.com/whisper/icon.png)




### Icon List

Galaticos has 140+ premium font icons from iconsweets2 that you can select from to make your content more attractive.

**Attribute:**

```
[list icon="gala-airplane64" icon_color="yellow"]%SELECTION%[/list]
```

- `icon`: you can choose icon from icon list.
- `icon_color`: icon color.

**Popup:**

![icon](http://docs.fitwp.com/galaticos/icon-list.png)




### Icon Box

Icon box is a way of displaying main information in a "box", which is usually used in homepage, landing pages.

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

![icon-box](http://docs.fitwp.com/whisper/icon-box.png)



### Testimonials

This shortcode allow you config type and number of testimonials.

**Attributes:**

```
[testimonials number="3" type="small"]
```

- `type`: `big` or `small`. Default is big.
- `number`: number of testimonials.

**Popup:**

![note-box](/galticos/shortcode-atestimonial.png)



### Portfolios

This shortcode display latest portfolios from your blog on your pages **in a grid**.

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

![portfolios](http://docs.fitwp.com/whisper/shortcode-portfolios.png)

In the popup, click **Advanced Button** to show more options for the shortcode.



### Posts

This shortcode display latest posts from your blog on your pages **in a grid**.

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

![posts](http://docs.fitwp.com/whisper/posts.png)

In the popup, click **Advanced Button** to show more options for the shortcode.



### Team Member

This displays a team member profile on your website.

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

![team-member](http://docs.fitwp.com/whisper/team-member.png)



### Clients

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

![clients](http://docs.fitwp.com/whisper/clients.png)

In the popup, when you need to add more client, just click **Add Client** button.




### Counter

This shortcode allow you config counter.

**Attributes:**

```
[counter number="5" icon="gala-airplane51"]counter[/counter]
```

- `number`: number of counter.
- `icon`: you can choose icon in icon list.


**Popup:**

![social-media](http://docs.fitwp.com/galaticos/counter.png)




### Pie Chart

This shortcode allow you config pie chart.

**Attributes:**

```
[pie_chart dimension="200" color="yellow" width="10" percent="100"]Chart 1[/pie_chart]
```

- `dimension`: pie dimension.
- `width`: bar width.
- `color`: color of line.
- `percent`: percentage of the pie chart.
- `width`: width of the line border.



**Popup:**

![social-media](http://docs.fitwp.com/galaticos/pie-chart.png)




### Pricing table

This shortcode allow you config pricing table. [See demo](http://demo2.fitwp.com/galaticos/tables/).

**Attributes:**

```
[pricing name="price-table" price="$50" link="http://demo2.fitwp.com/galaticos/" button="Purchase" highlight="1"]

Feature 1
Feature 2
[/pricing]
```

- `name`: name of item
- `price`: price of item.
- `link`: link when you click on button

**Popup:**

![pricing-table](http://docs.fitwp.com/galaticos/pricing-table.png)
