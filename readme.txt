=== ThemeFuse Extend User Profile ===
Contributors: themefusecom
Tags: author page, profile, user profile, extend user profile, add profile options, social profile options
Requires at least: 3.0
Tested up to: 3.2.1
Stable tag: 1.0.0

Perfect tool for webmasters to extend user profile options. With basic HTML knowledge it is posible to add more options to user profile (Ex: Social Networks links)


== Description ==

Perfect tool for webmasters to extend user profile options. With basic HTML knowledge it is posible to add more options to user profile (Ex: Social Networks links)

<code>
$meta = get_user_meta(get_the_author_meta( 'ID' ),'theme_fuse_extends_user_options',TRUE);
                
foreach( $meta as $key => $item )
{
    if ( $key == 'facebook' || $key == 'twitter' || $key == 'in') $tfuse_meta[$key] = $item;
}
</code>

Key Features:

- Standart Options (Facebook, Twitter, LinkedIN)
- Other options for your user profile page.


== Installation ==

1. Unpack the download-package
2. Upload all files to the /wp-content/plugins/ directory
3. Activate the plugin through the 'Plugins' menu in WordPress
4. Click the user -> user page for add/change facebook, twitter, LinkedIN or other options.


== Screenshots ==

1. ThemeFuse Extend User Profile Page
2. User Page
3. Footer js tabs
4. Plugin back end
5. 11 packed in backgrounds

== Changelog ==

= 1.0.0 =
* First release