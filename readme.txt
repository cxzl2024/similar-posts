=== Similar Posts - Best Related Posts Plugin for WordPress ===
Contributors: shareaholic
Tags: related posts, similar posts, connected posts, related posts widget, linked posts
Requires at least: 4.0
Tested up to: 5.9
Requires PHP: 5.2
Stable tag: 3.1.6

Displays a list of related posts similar to the current one based on content, title and/or tags. Works with all themes and is very customizable!


== Description ==

Similar Posts displays a list of posts that are similar or related to the current posts. The list can be customised in **many ways**. Similarity is judged according to a post's title, content, and tags and you can adjust the balance of factors to fit your own site.

**Few Notable Options**

* complete control over the display & layout of displayed posts
* over 30 tags for display template customization
* matching of current post's category, tags, content and author
* post excluding by author, ID, category, tags and custom fields
* output in posts, widgets and RSS
* over 50 options available

If you need a plugin that does all the Related Posts compute processing in the cloud, please check out our other [Related Posts & Products WordPress plugin](https://shrlc.com/yPInQlI).

[Shareaholic Blog](https://www.shareaholic.com/blog) | [Privacy](https://www.shareaholic.com/privacy/) | [Terms](https://www.shareaholic.com/terms/)

== Installation ==

Follow the usual routine;

1. Open WordPress admin, go to Plugins, click Add New
2. Enter "Similar Posts" in search and hit Enter
3. Plugin will show up as the first on the list, click "Install Now"
4. Activate & go to Settings - Similar Posts to configure

Or if needed, upload manually;

1. Download the plugin.
2. Unzip it and upload to _wp-content/plugin/_
3. Open WordPress admin - Plugins and click "Activate" next to the plugin
4. Activate & go to Settings - Similar Posts to configure


== Frequently Asked Questions ==

= Who is this plugin for? =

For anyone who want to keep visitors longer on their site by giving them more quality, related content when and where they need it - below the article they're currently reading.

= It's not working!!! Arrrrrrrrr =

Read the <a href="https://wordpress.org/support/plugin/similar-posts/">support forum</a> rules (no seriously, read them) and then if needed open new a thread.


== Screenshots ==

1. General options screen
2. Output options screen
3. Filter options screen
4. Placement options screen
5. Miscellaneous options screen
6. Index options secreen


== ChangeLog ==
= 3.1.6 (13-October-2021) =
* To use WP Template Conditionals in Similar Posts widget settings or Admin:
    + Require `manage_options` and `unfiltered_html` user capability. Note: In WordPress Multisite, only Super Admins have the `unfiltered_html` capability.
    + Check whether file editing is allowed per `DISALLOW_FILE_EDIT` constant
* Show educational warning before allowing use of WP Template Conditionals

= 3.1.5 (20-JULY-2021) =
* Support for WordPress 5.8+
* Fixed compatibility issues with PHP 7.4

= 3.1.4 (15-MARCH-2021) =
* Support for WordPress 5.7+

= 3.1.3 (07-April-2020) =
* Support for WordPress 5.4+

= 3.1.2 (06-November-2019) =
* Support for WordPress 5.3+

= 3.1.1 (02-May-2019) =
* Support for WordPress 5.2

= 3.1.0 (16-February-2019) =
* Fixed compatibility issues with PHP 7.2
* Addressed PHP warnings
* Algorithm updated to prefer newer posts over older ones
* General admin panel cleanup

= 3.0.2 (15-February-2019) =
* Support for WordPress 5.1

= 3.0.1 (06-December-2018) =
* Support for WordPress WordPress 5.0

= 3.0.0 (03-May-2018) =
* Minor update

= 2.8.1 (03-May-2018) =
* Minor update

= 2.8 (03-May-2018) =
* Minor update
  
= 2.75 (27-July-2017) =
* Minor update

= 2.71 (02-April-2017) =
* Minor update

= 2.71 (13-September-2016) =
* no longer requires any additional plugins
* fixed all notices and errors
* fully compatible with the latest version of WP  

= 2.6.2.0 =
* fixed a problem with the stemming algorithm and overused words
* introduced a first stab at fuzzy matching
* new {imagealt} output tag -- rather like {imagesrc}
* {excerpt} can now trim to whole sentences
* content filter can now take parameter string
* widget can now take parameter string
* output can be appended to posts & feeds

= 2.6.1.3 =
* fix - german language stemmer was crashing if mb_string fucntions not available

= 2.6.1.2 =
* fix - german language stemmer file now in utf8

= 2.6.1.1 =
* fix to italian language stemmer for PHP4

= 2.6.1.0 =
* the current post can be marked manually
* widgets now honour the option to show no output if list is empty
* fixed a bug with finding the right language files

= 2.6.0.1 =
* bug fix: installation code was failing on some systems

= 2.6.0.0 =
* version bump to indicate compatibility with WP 2.6
* fix to really include attachments
* new parameter for {imagesrc} to append a suffix to the image name, e.g. to get the thumbnail for attachments

= 2.5.0.11 =
* new option to include attachments
* {php} tag now accepts nested tags
* new output tag {authorurl} -- permalink to archive of author's posts
* fix for numeric locale issue

= 2.5.0.10 =
* new option to select algorithm for term extraction
* new manual links option
* fix for page selection in old versions of WP
* fix for faulty tags in Cyrillic

= 2.5.0.9 =
* new option to match the current post's author
* extended options for snippet and excerpt output tags

= 2.5.0.7 =
* new option to show by status, i.e., published/private/draft/future
* {categorynames} and {categorylinks} apply 'single_cat_name' filter
* fixes bug in WP pre-2.2 causing installation to fail

= 2.5.0 =
* CJK digrams
* {image} has new post, link, and default parameters
* new {imagesrc} tag
* fix to empty category bug
* excluded posts bug fix
* fix for intermittent bug with 'omit current post' option

= 2.5b28 =
* improvements to Similar Posts matching
* experiment with Chinese/Korean/Japanese matching

= 2.5b27 =
* fixed bug with bulk indexing of tags

= 2.5b26 =
* reverted thumbnail serving (speed)
* fix current post after extra query

= 2.5b25 =
* option to sort output, group templates
* removed 'trim_before' option added more logical 'divider'
* {date:raw}, {commentdate:raw}, etc.
* fix for {image} resizing when <img > and not <img />
* {image} now serves real thumbnails

= 2.5b24 =
* fix for recursive replacement by content filter
* fix to {gravatar} to allow for 'identicon' etc.
* fix to {commenter} to allow trimming
* fix a warning in safe mode
* fix for unsanitised WP tags

= 2.5b23 =
* new option to filter on custom fields
* nested braces in {if}; condition now taggable
* improved bug report feature
* better way to omit user comments

= 2.5b22 =
* restored automatic indexing on installation
* moved indexing menu under settings
* show_pages option can now show only pages
* fix for upgraders who had utf8 selected but no mbstring

= 2.5b20 =
* optimised indexing for speed and memory use

= 2.5b19 =
* fixing some extended character issues

= 2.5b18 =
* fix output filter bug
* add conditional tag {if:condition:yes:no}

= 2.5b16 =
* fix for {php}

= 2.5b15 =
* fix more or less obscure bugs, add 'include posts' setting

= 2.5b14 =
* fix file-encoding, installation error, etc.

= 2.5b12 =
* fix serious bug for WP < 2.3

= 2.5b11 =
* some widget fixes

= 2.5b10 =
* fix for non-creation of table

= 2.5b9 =
* clarifying installation instructions


== Upgrade Notice ==

= 3.1.6 =
We update this plugin regularly so we can make it better for you. Update to the latest version for all of the available features and improvements. Thank you for using the Similar Posts plugin!

The plugin **no longer requires** the latest version of the Post-Plugin Library. If you are upgrading from a version older than v2.6.2.0 first deactivate the plugin, then delete the plugin folder from your server. If you have the Similar Posts Feed plugin installed you must deactivate it before installing Similar Posts (which now does the same job).
