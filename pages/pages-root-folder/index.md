---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header.png
  logo: false
widget1:
  title: "Who we are"
  url: '/trust/'
  image: widget-1-302x182.jpg
  text: 'About the Impact Open Source Software Trust'
widget2:
  title: "IMPACT OSS"
  url: '/impactoss/'  
  text: 'About the software'
  video: video_teaser.png
widget3:
  title: "News"
  url: '/blog/'
  image: widget-github-303x182.jpg
  text: 'Latest news'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /get-involved/
  text: Get involved
  style: info
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/262605219?title=0&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
  <a class="close-reveal-modal">&#215;</a>
</div>
