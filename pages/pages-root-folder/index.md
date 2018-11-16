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
<div style="padding:56.25% 0 0 0;position:relative;">
  <div class="embed-video" data-video="262605219" data-video-source="vimeo"></div>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
