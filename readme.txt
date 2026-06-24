=== Easy Responsive Video ===
Contributors: clubside
Plugin link: https://github.com/clubside/vern-responsive-video
Tags: video, responsive, oembed
Tested up to: 7.0
Requires at least: 5.0
Requires PHP: 7.0
Stable tag: 1.4.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Easy Responsive Video adapts oEmbed video to full width while maintaining aspect ratio.

== Description ==

Automatically adapt your embedded videos to the full width of their containers while maintaining the correct aspect ratio.

This plugin scans each embed in your posts, pages, and custom post types, reads the width and height on the `<iframe>`, and adds a modern inline `style` attribute using CSS `width`, `height`, and `aspect-ratio`.

Currently supports YouTube, Vimeo, WordPress/VideoPress, and Dailymotion.

== Features ==

* No wrapper `<div>` elements
* No CSS files added to your theme
* No JavaScript
* Works with Classic Editor and Block Editor
* Uses modern `aspect-ratio` CSS for accurate scaling
* Supports any aspect ratio (4:3, 16:9, 2.35:1, etc.)
* Zero configuration required

== Installation ==

1. Visit `Plugins > Add New`
2. Search for `Easy Responsive Video`
3. Install Easy Responsive Video once it appears
4. Activate Easy Responsive Video from your Plugins page.

= Manually =

1. Upload the `vern-responsive-video` folder to the `/wp-content/plugins/` directory
2. Activate the Easy Responsive Video plugin through the 'Plugins' menu in WordPress

== Screenshots ==

1. Example of a responsive video using aspect-ratio.

== Changelog ==

= 1.4.0 [Jun 24, 2026] =

* Verified compatibility with WordPress 7.0.
* Added guardrail against malformed HTML.
* Expanded RegEx to detect alternate HTML attribute formats.

= 1.3.0 [Feb 12, 2024] =

* Disabled direct file access.

= 1.2.0 [Feb 11, 2024] =

* Verified compatibility with WordPress 6.4.3.

= 1.1.0 [Dec 23, 2023] =

* Reworked provider identification.
* Added support for Vimeo, WordPress/VideoPress, and Dailymotion.

= 1.0.0 [Dec 22, 2023] =

* Initial Release
