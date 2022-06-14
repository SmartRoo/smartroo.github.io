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
    <br/><i>❖ Driving score</i><br/>
    Shows how safe of a driver you are. It checks your speed, braking  and acceleration habits against your car model<br/>     
    <br/><i>❖ Connected cars</i><br/> 
    Access Internet, send and receive signals, sense the physical environment and interact with other vehicles or entities<br/>   
    <br/><i>❖ Realtime Tracking</i><br/> 
    Locate your loved ones or precious car, have peace of mind
  '

widget2:
  title: "For your Business"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  image: business_use.jpg
  text: '
    <br/><i>❖ Fleet Management</i><br/>
    View & track your assets in real time, enable alerts for mainternance etc<br/> 
    <br/><i>❖ Optimise Fuel Usage</i><br/>
    Track vehicle usage and routes, improve accountability<br/>
    <br/><i>❖ Occupational Safety</i><br/>
    Prevent overworking and optimise workloads
  '


widget3:
  title: "For your Enterprise"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: enterprise_use.jpg
  text: '
    <br/><i>❖ Consumer Services & Revenue Sharing</i><br/>
    Reduce risks and costs, reward better behaviour<br/> 
    <br/><i>❖ Make them Smart</i><br/>
    Connected car packages, premium service<br/>
    <br/><i>❖ Digital Marketplace</i><br/> 
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

