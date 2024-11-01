Show Authors in Page Lists (WordPress Plugin)
=========================

Allows developers to display author names within wp_list_pages-generated page lists.

**DESCRIPTION**

This plugin allows developers to display author names within `wp_list_pages`-generated page lists.

Tags: wp_list_pages, author, plugin, function

**INSTALLATION**

After installing and activating, use the parameter `showauthors=1` to display an author name beside each permalinked page title the `wp_list_pages` function generates: e.g., `<?php wp_list_pages( 'title_li=&showauthors=1' ); ?>`. To disable the parameter for a particular string/list, set `showauthors` to "0": e.g., `<?php wp_list_pages( 'title_li=&showauthors=0' ); ?>`.

**LINKS**

For feedback and help, visit: http://getsatisfaction.com/studio_hyperset/products/studio_hyperset_wordpress_plugins

To learn about other Studio Hyperset WordPress plugins, visit http://studiohyperset.com/#solutions

**DEVELOPER NOTES**

This plugin assumes (a) most developers want to drive traffic to site pages, vs. author pages, and (b) links to author pages will appear on these site pages. As such, the names the plugin generates appear unpermalinked.

Additionally, even with the plugin installed and the `showauthors=1` parameter enabled,all lists will be organized per pages rather than per authors. Alphabetically ordering a list by ascending `post_title` (that is, `sort_order=ASC&sort_column=post_title`) -- the default method -- will result in a list like the following, regardless of author name:

* John Doe, Title A One Here
* Zach James, Title B Two Here
* Alan Adams, Title C Three Here
* &tc.

As demand warrants, future builds may include these additional functionalities.

**CHANGELOG**

- 1.0 (6/19/11) - Initial release
