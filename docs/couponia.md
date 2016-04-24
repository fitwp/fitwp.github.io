Welcome! First of all we want to thank you for purchasing our Couponia WordPress Theme.

In the following sections we will explain how to set up and use Couponia theme the easiest way possible. Although there're a lot of things written in this documentation, the theme itself is not hard to use. You can go to the Theme Options page and explore everything yourself. This file is more of a reference if you do not know what to do, or if you are not familiar with WordPress.



## Files Included

The download package (`.zip`) that you get from ThemeForest contains the following files and folder:

- `couponia.zip`: main theme file that need to be uploaded to host to install Couponia theme
- `demo-content.xml`: demo content file, which contains all pages and posts from live preview website. It will help you to have a first look of how we use Couponia theme
- `theme-options.txt`: theme option backup file. You'll need this to restore the default theme options that setup for demo website.
- `Documentation`: this folder the offline version of the theme's documentation
- `docs.html`: the online version of this documentation



## Get Started

Couponia is the best solution for selling coupons or any kind of goods. It can be used as coupon website (such as groupon.com) and also as online store. Modern, simple and unique design. It will amaze your clients and users. Huge amount of demo homepages, and lost of features will help you to make your website really unique. It also can support different layouts (boxed and wide) with background images and patterns. Many header layouts, 15+ product thumbnail layouts, quick view support, different sliders, 18 color schemes and more. Just pick it up and make it yours. Everything build under latest bootstrap 3 framework.

### What is deal product

This is important definition for this theme. The couponia is a ecommerce Wordpress theme that requires the Woocommerce plugin has to be installed to works. So in fact, a deal product is a Woocommerce product, but it is **On Sale** and **scheduled to the end date**. You can see the bellow image to understand what make a deal product:

![deal product settings](http://docs.fitwp.com/couponia/images/deal-product-settings.png)


## Installation


### Install Theme

After you download the `.zip` package from ThemeForest, unzip it. You'll see a file `couponia.zip`, which is the main file that needed to upload and install.

**Notice**: If you download **Installable WordPress file** then that file is the zip file we use to upload and install.

You can either choose to upload and installl the theme using **FTP** or use **WordPress theme install** function.

### Upload and install using FTP

- Unzip `couponia.zip`, you'll get a folder `couponia`
- Use a FTP client like [FileZilla](http://filezilla-project.org/) and upload that folder to `wp-content/themes` folder on your host
- Go to `Appearance > Themes` and activate **Couponia** theme

### Install theme using WordPress install function

- Go to `Appearance > Themes` and click **Add New**
- Select **Upload**
- Click **Browse** and select the `couponia.zip` file
- Click **Install Now**
- When upload and installation progresses are completed, click **Activate**, or go to `Appearance > Themes` and activate **Couponia** theme

![upload](http://docs.fitwp.com/couponia/images/wordpress-upload.png)




### Install plugins

After installing Couponia, you'll see a notification in the top of the page that says the theme needs some plugins to function properly.

Couponia theme **requires** follow plugins (all are free and available on WordPress.org):

- [Meta Box](http://wordpress.org/plugins/meta-box/)
- FitWP Shortcodes
- [WooCommerce - excelling eCommerce](http://wordpress.org/plugins/woocommerce/)

Couponia theme **recommends** follow plugins:

- [YITH WooCommerce Wishlist](http://wordpress.org/plugins/yith-woocommerce-wishlist/)
- [Contact Form 7](http://wordpress.org/plugins/contact-form-7/)
- [MailPoet Newsletters](https://wordpress.org/plugins/wysija-newsletters/)

Couponia is working perfectly with these plugins. It automatically adds more styles to them to make the design match the theme.

To install these plugins:

- Click **Begin installing plugins**
- You'll be redirect to a page where all needed plugins are listed. Just click on **Install** below each plugin's name
- After installing, if it's required to activate the plugin, just activate

![plugins](http://docs.fitwp.com/couponia/images/install-plugins.png)


### Config plugins

After plugins are installed. You need change change some options to make it work perfectly with the theme. They are image sizes of products.

- Go to Woocommerce > Settings > Products > Display, under the Product Images section, you will found Catalog Images, Single Product Images, and Product Thumbnails.
- Catalog Image is for your images on the shop page and homepage. Single Product Image is for your images on the single product pages. Product Thumbnail is for your smaller product thumbnails for widgets.
- Change the size of Catalog Image to 360 x 270, Single Product Image to 800 x 600, Product Thumbnail to 180 x 180.


![WC Settings](http://docs.fitwp.com/couponia/images/woocommerce-settings.png)



### Install demo content

If you are new to WordPress and have problems with setting up the theme you might want to import the demo content file that comes with the theme. The following actions will import some dummy posts and pages from the live preview:

- Go to `Tools > Import`
- Select **WordPress** from the list
- If you haven't installed the **WordPress import plugin**, a popup window will appears and ask you to install it. Just click **Install Now**. When the installation progress is completed, click **Activate Plugin & Run Importer**. If you have installed this plugin, skip to next step.
- Click **Browse** and select `demo-content.xml` file from the download package
- Click **Upload file and import**
- When you are asked to import author, you can create new author or import to existing author. You also should check the checkbox **Download and import file attachments**.

![import](http://docs.fitwp.com/couponia/images/import.png)

After completing all above steps, go to `Posts`, `Pages`, `Products` to see imported data.


>**Important:** Due to license of images, we have to remove images in distributed demo content and replace them with placeholers. All images get from [placehold.it](http://placehold.it/), if you have any download errors when import demo-content.xml, problem can be speed of internet connection. Don't worry about that, you can replace with your own images.


### Setup homepage and blog page

After install demo content, you'll see a page `Homepage`. This page will be used as the homepage of the website. To set it as homepage, please go to `Settings \ Reading`, under **Front page displays**, please chose **A static page (select below)** and select **Front Page** for **Front page** and **Full Width** page for **Posts page**.

![homepage](http://docs.fitwp.com/couponia/images/homepage.png)



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

![menu](http://docs.fitwp.com/couponia/images/menu.png)


### Setup widget areas

Couponia theme has 10 widget areas (sidebars) by default:

- **Blog Sidebar:** main website sidebar which will be displayed on all blog posts, archive pages, etc.
- **Page Sidebar:** will be displayed on all WordPress pages.
- **Shop Sidebar:** will be displayed on all WooCommerce pages: Products, Product category, Single Product, etc.
- **Deals Sidebar:** will be displayed on pages which use **Deals** template.
- **Home Sidebar:** will be displayed on **Homepage** template
- **Header Sidebar:** will display on right/left side of header when you select header's layout is **Layout 2** and logo position is not center in the Theme Options panel.
- **Footer Sidebars:** there are 4 default sidebars for footer, each sidebar is a column in the footer. You can change number of columns in footer in Theme Options page (in that case number of footer sidebars will increased or decreased acccordingly).

To setup a sidebar, select it from the right by clicking its title or the arrow down. Then drag and drop widgets from the left to the sidebar area.

![sidebar](http://docs.fitwp.com/couponia/images/sidebar.png)

That's all! Now you have the website up with all *basic* elements!




## Theme Options

![theme options](http://docs.fitwp.com/couponia/images/theme-options.png)

The Couponia theme comes with unique, creative and easy-to-use Theme Options page. You can change all theme options in one place!

With Couponia's advanced theme options panel, you can customize just about any part of your site quickly and easily. Every element on the site can have the color changed to your liking. Choose a color scheme for website, select fonts for all headings and body copy, change sizes, colors and line-heights of all fonts, select different footer column layouts, enable or disable several options, upload your own custom favicon, select from various site/page layouts, input custom CSS, set hundreds of other options to easily customize your site!

All options have full description so you can know what you are doing. Just click and save!

Let's go through each section.




### General

![general](http://docs.fitwp.com/couponia/images/general-option.png)

This sections contains:

- **(1)**: favicon upload, allows you to upload favicon for you website
- **(2)**: touch icon, allows you to upload icon for mobile devices and tablets
- **(3)**: show comment on pages
- **(4)**: show advanced search form right bellow the menu.
- **(5)**: change the background color of advanced search form.
- **(6)**: show breadcrumb after the menu. If advanced search is enabled, breadcrumb will display bellow it.
- **(7)**: backup - restore, allows you to backup Couponia options and restore them later, or transfer the saved options between different installs.

Here are the explanations of some options that can help you understand and use them better:



### Favicon Upload

[Favicon](http://en.wikipedia.org/wiki/Favicon) (short for Favorite icon), also known as a shortcut icon, Web site icon, tab icon or bookmark icon, is a file containing one or more small icons, most commonly 16x16 pixels, associated with a particular Web site or Web page. Browsers that provide favicon support typically display a page's favicon in the browser's address bar (sometimes in the history as well) and next to the page's name in a list of bookmarks. Browsers that support a tabbed document interface typically show a page's favicon next to the page's title on the tab, and site-specific browsers use the favicon as a desktop icon.

This is how favicon appears:

![favicon](http://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/Wikipedia_favicon_in_Firefox_on_KDE.png/250px-Wikipedia_favicon_in_Firefox_on_KDE.png)

Couponia lets you upload favicon or enter favicon URL in the input box:

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

This option allows you to show/hide comments and comment form on pages. By default, Couponia doesn't display comments and comment form on pages.

**Important**: In case this option is set to "ON", to display comments on pages, you still have to **allow comments** for pages when you edit pages.

![allow comments](http://docs.fitwp.com/couponia/images/allow-comments.png)

By default, this checkbox is checked (meaning comments are allowed on pages). But in case you want to show comments on all pages, except some specific pages, you can use this checkbox to hide comments for those pages only.



### Backup - Restore

Couponia allows you to backup theme options and restore them later. You can also transfer the saved options data between different installs.

To backup theme options, just copy the text inside the text box and save it into a file on your computer. To import data, replace the data in the text box with the one from the saved file and click **Import Options** button.

After clicking **Import Options**, Couponia will automatically setup all options and refresh the current theme options page, so you can see the options immediately.




### Design

This sections contains:

- **Color Scheme**: allows you to change color scheme of whole website
- **Background**: setup background for whole site
- **Layout**: allows you to change layout style and layout for whole website, blog posts, pages, shop...
- **Typography**: allows you to change font family, styles, size, line height, color for body text and headings
- **Custom CSS**: allows you to add your custom CSS



### Color Scheme

Couponia theme has **17 predefined color schemes** to choose. When you change color scheme of the theme, all links, button background and other elements will change their color or background accordingly.

The default color scheme is green, but you can select any from 17 colors here. After selecting, click **Save Changes** button to save your data. Now go to the frontend and check the colors of links, buttons, etc.

When you select **Color Scheme** section, you'll see the following options:

![color schemes](http://docs.fitwp.com/couponia/images/design-color-schemes.png)

- **(1)**: select built-in color scheme. These are 17 predefined color schemes. When you select one of them, your website elements will change color accordingly.
- **(2)**: enable/disable custom color scheme. This option allow you create **custom color scheme**, and you can build unlimited color schemes here! Just enable this and you'll see options below.
- **(3)**: primary color. This is primary color for your custom color scheme.


### Background

This section contains options which help you to setup background for your website.

<div class="alert">Background only displays when you select layout style as `box`. We will talk about layouts in next section.</div>

![background](http://docs.fitwp.com/couponia/images/design-background.png)

- **(1)**: select background pattern image. It is pre-provided image which is repeatable.
- **(2)**: select background color.
- **(3)**: upload your own background image.
- **(4)**: select custom background's horizontal position.
- **(5)**: select custom background's vertical position.
- **(6)**: select custom background's repeat property.
- **(7)**: select custom background's attachment property.

### Layout

This section helps you to select which layout will be use in whole website.

![layout](http://docs.fitwp.com/couponia/images/design-layout.png)

- **(1)**: select layout style. You can choose either **boxed** or **wide** style. Couponia theme allows you to change layout style of whole website to boxed or wide (full width). When you change layout style, it doesn’t affect style of your content, sidebar, header or footer. All these elements still keep their looks and feel.
- **(2)**: select layout **for blog, single posts and other archive pages**. You can select sidebar position here: `left`, `right` or `none` (don't display sidebar)
- **(3)**: select layout for **WooCommerce pages**. Same meaning as for blog above but only applied for WooCommerce pages: **shop page, single products, product tag archive, product category archive**.
- **(4)**: select layout for **Deals** template pages. Same meaning as for shop above but only applied for pages which use page template **Deals**.
- **(5)**: select layout **for pages**. Same meaning as for blog above but only applied for normal pages.

<div class="alert alert-info">These options is site-wide, meaning for whole website. But you still can set **custom layout for single post and page when edit** (We'll explore it later).</div>

By default: Couponia uses **wide** layout style with **left** sidebar for both blog and pages.



### Typography

![typography](http://docs.fitwp.com/couponia/images/design-typography.png)

This section helps you to customize fonts for **body text** and **headings** on your website. For each element, you can customize:

**(1)**: font family. Just select from the dropdown font family you like. Couponia supports 3 normal fonts (Arial, Verdana and Times).

**(2)**: font size. Adjust font size for better look here. Just remember the unit for font size is **px**.

**(3)**: line height. Adjust line height for better look here. The unit for line height is also **px**.

<div class="alert alert-info">For better readability, good value for line height is about 1.4-1.5 x font size.</div>

**(4)**: font styles. You can choose **bold**, **italic**, **underline** or any combination of them.

**(5)**: font color. Click on the button, a color picker will appear and you can now select any color.

**Important**: before customize fonts, remember the default values for fonts. You should customize fonts around these values.

| Element   | Font Family | Font Size | Line Height | Styles | Color   |
| --------- | ----------- | --------- | ----------- | ------ | ------- |
| Body Text | Open Sans   | 14px      | 20px        | None   | #666666 |
| Heading 1 | Lato        | 36px      | 40px        | None   | #4d4d4d |
| Heading 2 | Lato        | 30px      | 33px        | None   | #4d4d4d |
| Heading 3 | Lato        | 24px      | 26px        | None   | #4d4d4d |
| Heading 4 | Lato        | 18px      | 19px        | None   | #4d4d4d |



### Custom CSS

![custom css](http://docs.fitwp.com/couponia/images/design-custom-css.png)

This section allows to enter custom CSS that will be output in the `</head>`. This will **overwrite** CSS of theme, so please be careful!

Custom CSS is useful when you want to adjust **small things** for your website. If you have to adjust a lot of things in website, please use [Child Themes](http://codex.wordpress.org/Child_Themes).




### Header

![header](http://docs.fitwp.com/couponia/images/header.png)

This sections contains:

- **(1)**: logo upload, allows you to upload logo for you website. You can either put the URL of the logo into the input box or upload the logo to Media Library. The live preview of the logo will appear below the inputs.
- **(2)**: logo size. Specify logo size in **px** here. It will help you resize the logo to correct dimensions. By default, the good size is **201x39**.
- **(3)**: logo margin. Specify logo margin in **px** here. This is useful when you upload logo with different size than recommended. You can *move* logo a little, adjust space to make it look good.

 <div class="alert alert-info">You should **resize the logo to correct size** in Photoshop or any image editor before upload. It will keep your logo not resized and small size.</div>

- **(4)**: sticky header. This option allow you to make the header sticky, i.e. always stays on the top of the website when scrolling.
- **(5)**: select header's layout. You can choose either **Layout 1** or **Layout 2**.

 ![Header layout 1](http://docs.fitwp.com/couponia/images/header-layout1.png)

 <div class="text-center">Header Layout 1</div>

 ![Header layout 1](http://docs.fitwp.com/couponia/images/header-layout2.png)

 <div class="text-center">Header Layout 2</div>

- **(6)**: Logo position. Select position of the logo
- **(7)**: Menu color. Select background color for the menu. You can choose either Dark, Light or Primary Color.
- **(8)**: Menu extra. Select what do you want to display on the right side of the menu. You can select nothing to reject it or choose either **Search Form** or **Cart and User Links**.
- **(9)**: header scripts. Enter scripts or code you would like output to `&lt;head&gt;`. It can be:

 - `<link>` tag for custom font (from Google Fonts maybe)
 - Any meta tag: to show the designer, copyright, etc. in meta tag
 - Google Analytics code
 - Any Javascript code that need to be execute in `&lt;head&gt;`
 - Anything else

<div class="alert alert-error">If you want to put custom CSS here, you're doing **wrong**. There's a section for **Custom CSS** under **Design**, use it instead.</div>



### Blog

This section contains options which help you to change something about displaying posts archive pages (blog, category, tag, date)

![blog](http://docs.fitwp.com/couponia/images/blog.png)


- **(1)**: what type of post content will be displayed. Available options are `Post excerpt`, `Post content` or `Post content before more tag`.

 To understand what those values mean, take a look at the screenshot bellow:

 ![post](http://docs.fitwp.com/couponia/images/post-content.png)

 Where:

 - **(A)**: Whole post content, this is what you enter in the editor.
 - **(B)**: Post excerpt, which is optional hand-crafted summaries of your content. [Learn more about manual excerpt.](http://codex.wordpress.org/Excerpt). If you don't enter anything in the excerpt box, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
 - **(C)**: The post content before `more` tag
 - **(D)**: The `more` tag

 Return to blog option: if you choose

 - `Post excerpt`: Couponia will get post excerpt and display it. **Remember**: if you don't enter excerpts for post, WordPress will auto generate excerpt from post content by taking a number of words from the beginning of post content and removing all HTML tags from it.
 - `Post content`: Couponia will get whole post content and display it. This is the default value.
 - `Post content before more tag`: Couponia will get only the post content before `more` tag and display it.

- **(2)**: post content limit. Sometimes you enter a very long text for post excerpt or post content, display such long text in blog and archive pages is not good and harm your website beauty. So we need a way to truncate text to make it shorter. This option is created for that purpose.

 Simply specify number of words will be display here. Post content or excerpt will be truncated to exact number of words. You should try changing this value and preview your blog to see what is best for you.

 Default value is **55 words**.

 <div class="alert">**Important**: this option affects only when you **NOT** choose `Post Content` from the Display option above</div>

- **(3)**: readmore text. Default value is **Continue reading**.


### Shop

This section give you options to customize shop page.

![shop](http://docs.fitwp.com/couponia/images/shop.png)

- **(1)**: Default product image. This image will be used when product has no image to display as thumbnail.
- **(2)**: Product hover. Select what will be displayed when you hover mouse over a product on the shop page. You can choose either **Select** (disable), **Show Quick View Button** or **Show Secondary Image**.
- **(3)**: Default Products View. Select the default view for products
- **(4)**: Number of products. Set default number of products to display in the shop page.
- **(5)**: Single deal images display. Select how to show images (gallery) of a deal product. You can choose either **Slider** or **Gallery**.
- **(6)**: Show featured badge. Display a badge for featured products.
- **(7)**: Show new badge. Display a badge for new products.
- **(8)**: Badge display duration. The number of days a product will be set as new product, since the published date.



### Footer

This section give you options to customize footer area on your website.

![footer-frontend](http://docs.fitwp.com/couponia/images/footer.png)

- **(1)**: number of columns in footer. It also is the number of footer sidebars (widget areas). Default is **4**.
- **(2)**: copyright text. You can enter text, HTML and **shortcodes** here. To make you easier to display copyright text, Couponia has default shortcodes that you can enter here:
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

- **(3)**: Footer right info. This information will be displayed on the right side of **Footer Copyright Text**. You can enter text, HTML and shortcodes here.
- **(4)**: footer scripts. Enter scripts or code you would like output before `&lt;/body&gt;`. It can be Google Analytics code or any Javascript code.



## Post/Page Display Settings

We've seen how to change featured title area, layout style, sidebar layout for whole website. Couponia also supports customizing these things for specific posts and pages.

When you edit a page or a post, you'll see this meta box below the content editor:

![display settings](http://docs.fitwp.com/couponia/images/display-settings.png)

- **(1)**: hide the page title. Select this box if you want to hide the title of this page.
- **(2)**: whether to use custom page layout. If you check this box, you're able to set custom layout style and sidebar layout below. If you don't, page will use default layout set in **Theme Options**.
- **(3)**: custom layout style for this page. You can select **Box** or **Wide** layout for this page and it will overide the default option in **Theme Options**.
- **(4)**: custom sidebar layout. Choose custom sidebar layout for page. If you don't choose anything, Couponia will use default sidebar layout set in **Theme Options**.



## Post Formats

[Post Formats](http://codex.wordpress.org/Post_Formats) is theme feature which is a piece of meta information that can be used by a theme to customize its presentation of a post.

In short, with a theme that supports Post Formats, a blogger can change how each post looks by choosing a Post Format from a radio-button list.

Couponia theme supports the following post formats:

- `gallery` - A gallery of images, which will be displayed in a responsive image slider, powered by Flexslider.
- `link` - A link to another site.
- `image` - A single image, which will be shown above post title.
- `quote` - A quotation.
- `video` - A single video, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed above post title.
- `audio` - An audio file, which can be any video from Youtube, Video or other video websites. Support URL or embed code. The video will be displayed using a powerful HTML5 audio player – jPlayer.

Each post format will have an icon near post title which tells you what post format is. Using post format in Couponia lets you differentiate post from each other and make the blog page / single page looks more beautiful.



### Setup Post Formats

When you edit a post, select a format you want to apply to that post on the **Format** meta box on the right:

![formats](http://docs.fitwp.com/couponia/images/post-formats-box.png)

When you choose a format, a corresponding meta box will appear **below** the content editor, here's the list of them:

![formats](http://docs.fitwp.com/couponia/images/post-formats-boxes.png)

All you need to do is just enter **all** information in the fields in these meta boxes. This information will be used to decorate the post. For example: gallery post format will uses uploaded images to show a slider above post title, a video post will display a video player above post title, etc.




## Page Templates

Couponia has some build-in page templates that can help you create special pages easier:

- **Deals**: template to display deal products.
- **Homepage**: template to display sections with normal products and deal products are inside.

When you edit a page, look at on the right, find **Page Attributes** meta box and select a template from the dropdown **Template**:

![page-templates](http://docs.fitwp.com/couponia/images/page-templates.png)

Width **Deals** template, there's no configurations at all. After select page template from the meta box on the right, you just need to save the page and see it in action in the frontend.

Width **Homepage** template, after select it, you will see sections and the default editor will be hidden. Each section will has it own options to config how to display on the frontend. They are described very detail, just following it you can create your own homepage.

![homepage-sections](http://docs.fitwp.com/couponia/images/homepage-sections.png)



## Widgets

Couponia plays nicely with default WordPress widgets. Besides that the theme has some additional widgets that might be useful for you:

### [Couponia] Cart & Account

This widget have no option. It was built to display shopping cart and sign up/sign in link to the header sidebar, as you can see on the live demo.


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

![twitter app](http://docs.fitwp.com/couponia/images/twitter-app.png)

- Fill in all information needed for the app. The name and description can be anything, it does not have to be a certain name. You can leave the Callback URL field empty.
- After creating the app, go to **API Keys** tab then click **Create My Access Token** button at the bottom to generate the necessary codes. It usually take 10 - 15 seconds to generate these codes, you have to reload that page to see your code in **Your Access Token** seciton.

![twitter app](http://docs.fitwp.com/couponia/images/twitter-app-token.png)

- Now you can copy the following fields for setting up Latest Tweets widget:
	+ API key  -> Consumer Key
	+ API secret -> Consumer Secret
	+ Access token -> Access token
	+ Access token secret -> Access token secret

These fields will be used in the tweets widget.

Now go to your website admin area, then `Appearance > Widgets`, drag and drop **[FitWP] Latest Tweets** widget into a sidebar that you want it to show there. You'll see these fields this:

![tweets](http://docs.fitwp.com/couponia/images/widget-tweets.png)

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




## Shortcodes

The Couponia theme is bundled with powerful shortcodes that you can customize your page content in thousand ways!

With Couponia Shortcode Generator, there is a shortcode for anything you need, and they allow you to create so many different page layouts. Users can quickly and easily built their own custom pages using all the various shortcodes that Couponia includes. Just about any element you see on our demo is a shortcode that you can insert on any page. Several shortcodes have numerous options for customization. There are endless options to choose from! Easily create your own pages by using our shortcodes, tons of possibilities and we add more all the time!

Good samples of shortcodes are homepages and other pages in the live preview demo. They’re all created with shortcodes! No need to remember shortcode attributes, all is done via a friendly interface.

When you edit a post or a page, click on **Shortcodes** button above the content editor to show the shortcodes menu.

![shortcode menu](http://docs.fitwp.com/couponia/images/shortcode-menu.png)

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

- `background` (optional): Background color for highlighted text. Couponia has built-in 24 colors for you to choose from (see the screenshot below). If you don't choose background color, Couponia will use default color - yellow.
- `custom_background` (optional): custom background color. If you don't like any color from the predefined set, you can specify your custom background color here.

**Popup:**

![highlight](http://docs.fitwp.com/couponia/images/highlight.png)

**(1)**: choose background color for highlighted text.

**(2)**: custom background color.

**(3)**: this is a preview of shortcode, which will show you all shortcode attributes.

**(4)**: when you're done, click **Insert** button to insert shortcode to the editor.



### Superscript

Simply choose a text and select superscript, the text will be display<sup>like this</sup>. There's no config for this.



### Subscript

Simply choose a text and select subcript, the text will be display<sub>like this</sub>. There's no config for this.


### Drop cap

Simply choose a text and select Drop Cap, the text will begin with a first letter in very big size. There's no config for this. You will see an option to select the color for that big letter.


### Tooltip

This shortcode will display a link with tooltip when hover mouse over it.

```
[tooltip link="#" position="top" text="Tooltip content here"]Anchor Text[/button]
```

**Attributes:**

- `position`: select the position of the tooltip
- `Tooltip Text`: enter the content of tooltip
- `Link`: enter link of this text


### Button

This shortcode displays a beautiful button on your page. [See demo](http://demo2.fitwp.com/couponia/button/).

**Attributes:**

```
[button link="#" color="pink" background="pink"]Click me[/button]
[button link="#" color="pink" icon="fa fa-star" background="pink"]Click me[/button]
[button link="#" color="pink" icon="fa fa-star" icon_position="right" align="left" full="1" background="pink" target="_blank" nofollow="1" id="myid" class="myclass"]Click me[/button]
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

![button](http://docs.fitwp.com/couponia/images/button.png)

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

![box](http://docs.fitwp.com/couponia/images/box.png)


### Accordions

These shortcodes will display a panel of content which can be hide/show when you click on the panel title. Similar to toggles, the difference here is when a panel is opened, other panels are closed (in toggles, they still can be opened). [See demo](http://demo2.fitwp.com/couponia/accordion-and-toggle/).

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

![accordions](http://docs.fitwp.com/couponia/images/accordions.png)

In the popup, do add more accordion panel, just click the button **Add Accordion** and fill in the title and content.



### Tabs

These shortcodes will display tabs of content which can be switched when you click on the tab title. [See demo](http://demo2.fitwp.com/couponia/tabs-shortcode/).

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

![tabs](http://docs.fitwp.com/couponia/images/tabs.png)

In the popup, do add more tab, just click the button **Add Tab** and fill in the title, content and select tab icon.



### Progress Bar

This shortcode will display a progress bar with title and percentage. [See demo](http://demo2.fitwp.com/couponia/progress-bar-pie-chart-counter/).

**Attributes:**

```
[progress_bar text="Web Development" percent="80" type="block"]
```

- `type` (optional): can be empty or `block`. If empty, the label will display **above** the progress bar, while `block` will display the label **inside** the progress bar.
- `text`: text label
- `percent`: the percentage **without** `%`

**Popup:**

![progress bar](http://docs.fitwp.com/couponia/images/progress-bar.png)



### Promotion Box

This shortcode will display a promotion box that helps you to get people attraction and improve click through rate (CTR). It's also called **Call To Action** box.

**Attributes:**

```
[promo_box heading="We'll tell you why you should buy Couponia!" text="We are constantly improving Couponia for our beloved users." button1_text="Purchase Now" button1_link="#" button1_color="red" button1_nofollow="1"]

[promo_box type="two-buttons" heading="We'll tell you why you should buy Couponia!" text="We are constantly improving Couponia for our beloved users." button1_text="Purchase Now" button1_link="#" button1_color="red" button1_nofollow="1" button2_text="Learn More" button2_link="#" button2_color="green" button2_nofollow="1"]
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

![promotion box](http://docs.fitwp.com/couponia/images/promotion-box.png)



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

![map](http://docs.fitwp.com/couponia/images/map.png)




### Row

Couponia theme comes with a 12-grid columns (960.gs). This shortcode lets you display content in a row and column.

**Attributes:**

```
[row background="http://demo2.fitwp.com/couponia/wp-content/uploads/sites/3/2011/05/best-twitter-wallpaper.jpg" parallax="1" fluid="1" class="promotion"]
[column span="8"]Lorem ipsum dolor sitamet[/column]
[column span="4"][button link="#" color="black" type="rounded" size="small"]PURCHASE NOW[/button][/column]
[/row]
```

- `background` (optional): background of row.
- `parallax`: allow to on/off parallax
- `fluid`: display full width.
- `class` (optional): custom CSS class. It might be useful if you need to customize the look of the row content.

**Popup:**

![column](http://docs.fitwp.com/couponia/images/shortcode-row.png)




### Column

This shortcode lets you display content in a column. [See demo](http://demo2.fitwp.com/couponia/columns/).

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

![column](http://docs.fitwp.com/couponia/images/column.png)



### Icon

Couponia has 140+ premium font icons from iconsweets2 that you can select from to make your content more attractive.

**Attribute:**

```
[icon class="serviceicon-tools" size="64"]
```

- `class`: icon class. You can use the popup to pick the icon, you don't need to remmember its class.
- `size`: icon size in `px` (but don't enter `px` here). Optional. If not specified, the icon will take the font size of current element.

**Popup:**

![icon](http://docs.fitwp.com/couponia/images/icon.png)




### Icon Box

Icon box is a way of displaying main information in a "box", which is usually used in homepage, landing pages.

**Attributes:**

```
[icon_box type="big" url="http://google.com" title="Configure" icon="serviceicon-tools"]Lorem ipsum dolor sit amet.[/icon_box]
[icon_box type="hex" url="http://google.com" title="Support" icon="serviceicon-group"]Lorem ipsum dolor sit amet.[/icon_box]
[icon_box type="small" title="Design" icon="serviceicon-brush"]Lorem ipsum dolor sit amet.

<a class="more-link" href="#">Continue reading <span>&gt;</span></a>[/icon_box]
```

- `icon`: icon class. Same as for icon shortcode above. Just pick from the popup, or manually enter it if you remember ;)
- `icon_psoition`: select the position of the icon.
- `title`: icon box title (heading)
- `url`: URL that the icon box links to.
- `more_text`: enter the anchor text for the more link.

<div class="alert">You always **can** enter HTML into shortcode content. In the 3rd example above, you see how we used a link with class `more-link` and a `span` tag inside it to make a beautiful readmore link.</div>

<div class="alert">You should use icon box within `[column]` shortcode to make the icon box same width.</div>



### Testimonials

This shortcode allow you config type and number of testimonials.

**Attributes:**

```
[testimonial name="Blake Abraham" avatar_author="http://demo2.fitwp.com/couponia/wp-content/uploads/sites/10/2015/05/gamer_chick_50x50.jpg"]Neque orci porta maecenas odio hendrerit senectus sociosqu convallis nam[/testimonial]
```

- `name`: the testimonial's author name.
- `avatar_author`: the avatar link of the author.
- `type`: select style for displaying a single testimonial: normal or color.


### Team Member

This displays a team member profile on your website.

**Attributes:**

```
[team_member name="Mathew Parkson" job="Senior Manager" photo="http://themes.fitwp.com/whisper/wp-content/uploads/sites/3/2013/12/team-1.jpg" phone="+00 123 4567" email="mathewp@business.com"]It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.[/team_member]
```

- `name`: member name
- `job`: the job name
- `photo`: URL to member's image. You should use Media Library to upload image and then paste image URL here.
- Content of the shortcode: member's biography
- Social URLs: the URL to the social media of this member
