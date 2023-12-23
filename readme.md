# Easy Responsive Video

Easy Responsive Video is a WordPress plugin that adapts `oEmbed` video to full width while maintaining aspect ratio.

## Description

Automatically adapt your embedded videos to the full width of their containers while maintaining the correct aspect ratio.

This is a simple filter that scans each embed in your posts, pages and custom post types, reads the width and height on the `iframe` and adds a style attribute including CSS `width`, `height` and `aspect-ratio` properties.

Currently supporting YouTube, Vimeo, WordPress/VideoPress and DailyMotion.

## Motivation

I'm the devloper for the film writer [Vern](https://outlawvern.com) and had been using the plugin [Fluid Video Embeds](https://wordpress.org/plugins/fluid-video-embeds/) for years. After noticing a large number of errors in the server logs I discovered it was no longer maintained. The other solutions I found wrapped the `iframe` in a div and used CSS tricks to scale and maintain aspect ratio, and many required changing the links to shortcodes. I wanted a simple solution that would work with both Classic editor URLs as well as modern embed Blocks. This is my solution.
