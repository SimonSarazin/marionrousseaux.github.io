---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: UT5A8884.JPG
widget1:
  title: ""
  url: 'Praticienne en Médecine Traditionnelle Chinoise'
  image: UT5A8877.JPG
  text: ' .'
widget2:
  title: "Marion Rousseaux - Praticienne en Médecine Traditionnelle Chinoise"
  url: ''
  text: 'marion.rousseaux@gmail.com<br><br> 0782752983'
  video: ''
widget3:
  title: ""
  url: ''
  image: 
  text: ''
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
  url: mailto:marion.rousseaux@gmail.com
  text: Envoyer un mail ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
