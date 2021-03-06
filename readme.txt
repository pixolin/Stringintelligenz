=== Stringintelligenz ===
Contributors: glueckpress, elbmedien, tfrommen, kau-boy, benjaminbirkenhake
Tags: german, l10n, translation
Requires at least: 4.7
Tested up to: 4.7
Stable tag: 0.2.2
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Open language for WordPress in German

== Description ==

**Stringintelligenz** is a localization feature project that aims to bring inclusive language to German locales in WordPress.

This plugin swaps the German language packs for WordPress core with a set of language files containing a gender-sensitive translation of WordPress.

The most prominent change you will see after activating **Stringintelligenz** (and only if German is your site language or user language) is the admin menu item “Profile” instead of “Benutzer”. Happy exploring!

== Installation ==

1. Install the plugin through the WordPress “Plugins” screen directly, or upload the plugin files to `/wp-content/plugins/stringintelligenz`.
2. Activate the plugin through the “Plugins” screen in WordPress.
   No settings to configure, but make sure you run default German (`de_DE`) as your site language.


== Frequently Asked Questions ==

= Will the plugin override my language packs for WordPress? =

No, your installation remains fully intact. The plugin will load its own language files. When you decide to deactivate it, WordPress will look just as before you installed the plugin.

= Will the plugin make all of my website gender-sensitive in German? =

No, this plugin only targets WordPress core. German translations of other plugins or themes remain unchanged. That’s why you may see inconsitent translations here and there. If you activate the plugin, and you still see a generic masculinum like “Benutzer” or “Autor”, it likely comes from another plugin or theme.

= Does this plugin introduce “genderized” word endings? =

We generally try to use alternative phrasing wherever possible instead. Word endings with a “gender star” could be found in version 0.1.0, mostly on the word `Autor*in`. We found it particularly hard to come up with an alternative so far. (The single-word string `Author` is [used widely across multiple contexts](https://wordpress.org/support/topic/author-ohne-kontext/) in WordPress.)
Currently, the plugin uses female and male gender with a slash: `Autor/-in`.

= Can I use this plugin for client sites? =

Absolutely! We’d love to hear feedback from people who use WordPress, but don’t build with it on a daily basis. If you find the plugin appropriate to use on a client site, please let us know how your client received the language.

= How long will this plugin be maintained? =

At least until its general goal of inclusive language in WordPress core is reflected by default German language packs.

= I dig the code, who wrote this? =

After this plugin had started out as a fork of [Bernhard Kau’s](https://profiles.wordpress.org/kau-boy/) [Backend Localization](https://wordpress.org/plugins/kau-boys-backend-localization/) plugin, [Thorsten Frommen](https://profiles.wordpress.org/tfrommen/) has written the current OOP version.

= How can I contribute? =

The easiest way for you to contribute would be to just post your suggestions over in the [plugin forums](https://wordpress.org/support/plugin/stringintelligenz/#new-post). We monitor these forums closely and will definitely reply to any suggestions you make.

Contributing strings directly can get a bit tricky technically, but if you’re up for it, just shoot Caspar (@glueckpress) a message via [WordPress Slack](https://make.wordpress.org/chat/) or [German WordPress Slack](https://dewp.slack.com/).


== Screenshots ==

1. User list: renamed to “Profile”.
2. A woman labeled as a developer in German.
3. Stringintelligenz applied to the same label.


== Changelog ==

= 0.2.1 =
* Support für eigene Profilsprache (neu in WordPress 4.7), danke @tfrommen!

= 0.2.1 =
* String-Update von WordPress 4.7
* Beidnennung mit Schrägstrich im Singular gemäß Duden-Empfehlung verkürzt: `Autor/-in` anstatt `Autorin/Autor`

= 0.2.0 =
* [Profilname anstatt Zugangsname](https://github.com/glueckpress/stringintelligenz/issues/8)
* [neutrale Rollenbezeichnungen](https://github.com/glueckpress/stringintelligenz/issues/17)
* Beidnennung mit Schrägstrich statt Gender-Star
* [geringfügige Fehlerkorrekturen](https://github.com/glueckpress/stringintelligenz/issues/16)
* String-Update von WordPress 4.6.1
* Projekt-Ziel „WordPress 4.7“ entfernt

= 0.1.0 =
* … und jedem Anfang wohnt ein Zauber inne.


== Upgrade Notice ==

= 0.2.0 =
Beidnennung mit Schrägstrich („Autorin/Autor“) anstatt Gender-Sterne;  „Zugangsname“ heisst jetzt „Profilname“; funktionale Rollennamen. Feedback? Schreib’ uns im [Forum](https://wordpress.org/support/plugin/stringintelligenz/)!
