# Easy Responsive Video

Easy Responsive Video is a lightweight WordPress plugin that adapts `oEmbed` videos to the full width of their containers while maintaining the correct aspect ratio.

## Description

This plugin automatically scans embedded videos in your posts, pages, and custom post types, reads the `width` and `height` attributes on the `<iframe>`, and adds a modern inline `style` attribute using CSS `aspect-ratio`, `width`, and `height`.

### Why it’s different

Most responsive video plugins wrap the iframe in a `<div>` and use CSS padding hacks. This can:

- break theme spacing
- interfere with block editor alignment
- require extra CSS files
- cause layout shifts

**Easy Responsive Video does none of that.**

- No wrappers
- No CSS files
- No JavaScript
- No shortcodes
- Works with Classic Editor and Block Editor
- Uses modern `aspect-ratio` CSS for clean, native responsiveness

Currently supports YouTube, Vimeo, WordPress/VideoPress, and Dailymotion.

## Motivation

I'm the developer for the film writer [Vern](https://outlawvern.com) and had been using the plugin [Fluid Video Embeds](https://wordpress.org/plugins/fluid-video-embeds/) for years. After noticing a large number of errors in the server logs, I discovered it was no longer maintained.

The other solutions I found wrapped the `iframe` in a div and used CSS tricks to scale and maintain aspect ratio, and many required changing the links to shortcodes. I wanted a simple solution that would work with both Classic editor URLs as well as modern embed Blocks.

This is my solution.
