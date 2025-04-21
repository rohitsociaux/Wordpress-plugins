=== Advanced Filter for Posts ===
Contributors: rohit
Donate link: https://informationtechnologyhouses.in/contact/
Tags: filter, ajax, search, categories, tags
Requires at least: 3.0.1
Tested up to: 6.8
Stable tag: 1.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

AJAX-powered post filtering with grid/list views, category/tag filters, and search.

== Description ==

Advanced Filter for Posts is a powerful WordPress plugin that enhances post filtering with:
- AJAX-based instant search results
- Category and tag filtering
- Grid or list view options
- Customizable display settings
- SEO-friendly URLs
- No page reloads during filtering

**Shortcode Usage:**
`[wp_advanced_filter post_type="post" posts_per_page="6" categories="category" tags="post_tag" hide_tags="no" hide_categories="no" default_view="grid" show_search="yes" order="DESC"]`

**Shortcode Parameters:**
- `post_type`: Content type to filter (default: "post")
- `posts_per_page`: Number of items per page (default: 6)
- `categories`: Taxonomy for categories (default: "category")
- `tags`: Taxonomy for tags (default: "post_tag")
- `hide_tags`: Hide tag filter (default: "no")
- `hide_categories`: Hide category filter (default: "no")
- `default_view`: Initial display ("grid" or "list")
- `show_search`: Show search field (default: "yes")
- `order`: Post show order by ("ASC or DESC ")
== Installation ==

1. Upload the plugin files to `/wp-content/plugins/advanced-filter-for-posts`
2. Activate the plugin through 'Plugins' menu
3. Add the shortcode to any page/post:
   `[wp_advanced_filter]` (with optional parameters)
4. Or use the widget in Appearance > Widgets

== Frequently Asked Questions ==

= How do I change the number of displayed posts? =
Use the `posts_per_page` parameter in the shortcode, for example:
`[wp_advanced_filter posts_per_page="10"]`

= Can I use this with custom post types? =
Yes, specify your post type in the shortcode:
`[wp_advanced_filter post_type="your_custom_post_type"]`

= How to switch between grid and list views? =
Use the `default_view` parameter:
`[wp_advanced_filter default_view="list"]`

== Screenshots ==

1. Grid view with search and filters
2. List view alternative display
3. Mobile responsive layout
4. Admin settings panel

== Changelog ==

= 1.0.1 =
* Initial release
* AJAX filtering system
* Grid/List view toggle
* Customizable shortcode parameters
* Widget implementation
* Mobile-responsive design

== Upgrade Notice ==

= 1.0.1 =
First stable release with complete filtering functionality and shortcode customization options.
