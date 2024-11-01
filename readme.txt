=== tgStatistics ===
Contributors: WebPajooh
Tags: Telegram, Channel, Statistics
Requires at least: 3.7
Tested up to: 4.8.1
Stable tag: 3.3.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Statistics about your telegram channel

== Description ==

You can show your channel members count in your website, with a function or shortcode. the function can be used in template codes, and shortcode can be used in your posts.

== Installation ==

1. Upload `tgStatistics.zip` to the `/wp-content/plugins/` directory and extract it.
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Create a new bot with @BotFather, your token code is required for the next step.
4. Place `<?php tgStatistics($botAPI, $channelUsername); ?>` in your templates, or use the shortcode [tgstatistics] with two fields (botapi and username).