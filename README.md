# Material Card blog

Built with Jekyll, this blog theme uses Google's [Material Design Lite](https://getmdl.io) framework. Its primary aim is to be fast, responsive and light. With all external resources minified and gzipped, the homepage weighs under 500KB and loads near instantly while maintaining a beautiful design. Subsequent page loads will be faster.

![Screenshot](/screenshot.png)

A live demo is available [here](https://zogthealien.tk/material-card-blog/).

This theme is a stripped down fork of my personal blog, available [here](https://zogthealien.tk/blog/).

# Features
* Easy to set up
* Material Design
* Colors can be changed on a per-post, per-page basis and will be implemented consistently throughout
* < 500KB

# How to use this theme
* Fork this repository while logged into your Github account and rename as required
* `git pull` into your local environment
* Delete all boilerplate posts in the \_posts directory
* Add your own posts in the format `YYYY-MM-DD-title-of-post.markdown`
* Modify site branding in index.html and header.html
* `git push` back to Github
* Enable Github Pages in repository settings
* Done!

# Variables for post
Every page or post can be configured to use custom colors and authors. The variables used for this are defined in each post's front matter. `color` is for the background color, `textcolor` and `author` are self explanatory. You can also use `title`, and `date` to override defaults set by the post's filename. Jekyll supports more variables but these are the only ones currently implemented.

As for usage, here's an example front matter that you will prefix a blog post with.

```markdown
---
layout: post
color: "#dead00"
textcolor: white
author: Google
---
```

# Reporting Issues and Pull Requests
Please use the Github Issue Tracker for this, I'd love to hear any and all feedback. Pull requests are also welcome.

# To be implemented
* Reduce post padding for mobile
* Tagging and category system
* Comments
