---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Commit to excellence, reap the rewards"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'As a dedicated fitness expert, my mission is to inspire you towards a transformative and vibrant lifestyle. Recognising that every individual brings their own unique strengths and challenges, I craft personalised fitness regimes tailored to your specific health and wellness aspirations. Let me empower you to make informed choices, paving your path towards achieving your ultimate fitness goals.'
widget2:
  title: Everything"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: '<em>Feeling Responsive</em> is heavily customizable.<br/>1. Cardio Fitness<br/>2. Circuit Training<br/>3. Muscle Building<br/>4. Boxing<br/>'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Meet the trainer"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: 'Embrace intensity in training and relish every moment of life! As a mother to two driven teenage lads, they ignite my determination to consistently reach for greatness in all life's endeavours.<br/>With an extensive background in business management and over half a decade in personal training, my sights are now set on establishing a legacy – a thriving business that ensures a secure future for my family.<br/>Passionate about enjoying the lighter moments, indulging occasionally, while also maintaining peak fitness and health – because life is all about striking the perfect balance!'
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
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
