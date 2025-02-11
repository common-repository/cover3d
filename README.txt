=== Cover3D ===
Contributors:      pagelab, epicostudio
Tags:              cover, 3d, book cover, lead magnet, block
Tested up to:      6.2.2
Requires at least: 5.9
Requires PHP:      7.0
Stable tag:        0.1.0
License:           GPL 2.0 or later
License URI:       https://www.gnu.org/licenses/gpl-2.0.html
Donate link:       https://ubr.link/donate-wp

A block that displays a 3D book cover, animated when you mouse over it.

== Description ==

The **Cover 3D** block will display a 3D book cover with an image of your choice, with a stylish animation on mouse hover.

You can select three book sizes, set the cover colors, and also insert a custom link to the linked cover. In this case, the back cover will be displayed when you mouse over it, and you can choose an icon to describe the action of the link: download or buy, also adding the text that accompanies the link.

⚠️ **Important**: after adding the cover image, select the appropriate size from the block controls located on the sidebar of the block editor.

== Installation ==

= Automatic installation: =
1. Open any post or page in your WordPress.
2. Click the main plus icon (+), located at the upper left corner of the editor, to add a new block.
3. Type “Cover 3D” in the search field.
4. Look for the plugin with this name in the list of available block plugins and click to install.
5. Wait for the installation process and the block will be available to use in your content. You can deactivate it in the “Plugins → All plugins” menu, in your WordPress admin dashboard.

= Manual Installation: =
1. Upload the cover3d.zip file via the plugin page of WordPress by clicking “Add New” and selecting the zip from your local computer, or alternatively upload the decompressed `cover3d` folder to your `/wp-content/plugins/` directory on your server, via SFTP/FTP.
2. Activate the plugin through the “Plugins” menu in WordPress.
3. Search for the “3D Book Cover” block in any block inserter within the block editor.
4. Customize the cover image, book size and colors in the sidebar of the block editor. The plugin does not create menus or additional settings in the WordPress dashboard.

== Frequently Asked Questions ==

= Why would I need this? =
Do you have a book (or an e-book) that you want to promote? Or a subscription form with a lead magnet to download an e-book for marketing purposes? Including a 3D cover can help grab the visitor's attention to them, increasing conversions.

= What is the recommended way to use it? =
It can be used anywhere in the WordPress block editor, either in your content or in your templates.

= What is the recommended size for my cover image file? =
The plugin offers three sizes for your cover: _small_, _medium_ and _big_. The minimum image size for the “small” option is *66 x 100 pixels*. For the “Medium” option, upload an image with at least *133 x 200 pixels*, and *200 x 300 pixels* for the “big” option.

= What image file formats do this plugin accept? =
You can use any of the [natively supported file types](https://wordpress.org/documentation/article/image-size-and-quality/) for images, like JPG, GIF or PNG. If your WordPress installation allows SVG file uploads, you can also use this format, which is specially good for covers with sharp details.

= Will this plugin hinder my website loading performance? =
The Cover3D plugin uses very little CSS (8kb) to create the animation effect without Javascript on the front-end, so is very lean. You can also include an image for your cover, but you can select the desired image size to minimize the performance impact. At any rate, the Cover3D block only uses the native `medium` size, defined in your WordPress admin panel (Settings → Media), for the cover image on small screens, regardless of the the size option choosen in the block control panel, in order to avoid negative impacts on loading performance.

= Does this plugin collect any data from me or my users? =
Not at all. The plugin respects your privacy. It's completely add-free and the code only uses core WordPress functions. No admin notices or hidden “call home” functions.

= Does this plugin work in the Classic Editor? =
No, this plugin works exclusively in the Block Editor.

= Does the hover animation work in touchscreen devices? =
Since touchscreen devices do not include a “hover” state, the animation is disabled on them.

= Where can I send feedback or support questions? =
Please reach out via the official [plugin support forum](https://wordpress.org/support/plugin/cover3d).

Feel free to ask questions, request new features or report bugs.

You can also follow the development of the plugin in the official Épico Studio [GitHub repository](https://github.com/EpicoStudio/cover3d), where you can see the complete code.

= How can I support the development of the Cover3D plugin? =
You can help with a [donation](https://ubr.link/donate-wp) or a [positive review](https://wordpress.org/support/plugin/cover3d/reviews/#new-post), if you find it useful.

== Screenshots ==

1. The mouseover animation of the block appears when you include a link.
2. Block added in main content of a page.
3. Block settings: choose the cover size, set colors and add an optional link.
3. Block settings: you can also add your custom book cover image.

== Changelog ==

= 0.1.0 =
* Initial release
