# Publish Confirm #
* Contributors:      pluginkollektiv
* Tags:              publish, posts, confirm, confirmation, dialogue
* Donate link:       https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=LG5VC9KXMAYXJ
* Requires at least: 3.9
* Tested up to:      4.3
* Stable tag:        trunk
* License:           GPLv2 or later
* License URI:       http://www.gnu.org/licenses/gpl-2.0.html


Extra confirmation dialogue for the publish button to avoid accidental publishing.


## Description ##
Accidentally published a WordPress post too early once too often, instead of saving it as a draft? The WordPress plugin *Publish Confirm* implements an extra confirmation dialogue between your click on the *Publish* button and its actual processing. Simple and effective—never publish by accident again!

Once a post has been published, the confirmation dialogue will not appear anymore for that post.


### Memory Usage ###
* Back-end: ~ 0.02 MB
* Front-end: ~ 0.01 MB


### Languages ###
* English
* Deutsch
* Русский


### Credits ###
* Author: [Sergej Müller](https://sergejmueller.github.io/)
* Maintainers: [pluginkollektiv](http://pluginkollektiv.org/)


## Installation ##
* If you don’t know how to install a plugin for WordPress, [here’s how](http://codex.wordpress.org/Managing_Plugins#Installing_Plugins).


## Frequently Asked Questions ##
### Does _Publish Confirm_ work for posts and pages? ###
Yes, it does.

### And Custom Post Types? ###
Yup.

### Is there any way to change the default dialogue message into something else? ###
The message text in the publishing dialogue can be changed via PHP filter from a custom plugin or your theme’s functions.php:

`add_filter(
    'publish_confirm_message',
    function( $msg ) {
        return "You’re about to send this out into the world.\nHave you added a kitten pic?";
    }
);`


## Changelog ##
### 0.0.6 / 22.04.2015 ###
* WordPress 4.2 support
* Russian translation

### 0.0.5 ###
* No confirmation dialogue for scheduled posts

### 0.0.4 ###
* Publish confirmation for post drafts

### 0.0.3 ###
* *Publish Confirm* goes wordpress.org
