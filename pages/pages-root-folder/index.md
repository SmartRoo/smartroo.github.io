---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_splash.jpg
  
widget1:
  title: "For You"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: personal_use.jpg
  text: '
    <b>Driving score</b><br/>
    Shows how safe of a driver you are. It checks your speed, braking  and acceleration habits against your car model<br/> 
    <b>Connected cars</b><br/> 
    Access Internet, send and receive signals, sense the physical environment and interact with other vehicles or entities<br/>
    <b>Realtime Tracking</b><br/> 
    Locate your loved ones or make sure your precious car is where it should be
  '

widget2:
  title: "For your Business"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  image: business_use.jpg
  text: '
    **Fleet Management**<br/>
    View & track your assets in real time, enable alerts for mainternance etc<br/> 
    **Optimise Fuel Usage**<br/> 
    Track vehicle usage and routes, improve accountability<br/>
    **Occupational Safety**<br/> 
    Prevent overworking and optimise workloads
  '


widget3:
  title: "For your Enterprise"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: enterprise_use.jpg
  text: '
    **Consumer services, with revenue sharing**<br/>
    Reduce risks and costs, reward better behaviour<br/> 
    **Make them Smart**<br/> 
    Connected car packages, premium service<br/>
    **Digital Marketplace**<br/> 
    Integrate with technology parters and other business
  '
  
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
