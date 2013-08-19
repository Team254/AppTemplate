#Team 254 Web App Template

This is a template for web apps made by Team 254. It is designed such that those web apps match the style of the Team 254 website.

###Limitations

* **Drop-down menus in the nav bar are not supported.** This is because the web app template has a special "flexheader" which allows it not to overflow even when the app title is positioned to the left of it. The main site has a more absolutely positioned header which allows for drop down menus. The flexheader is squeezed into place using an `overflow:hidden` command. Because most browsers cannot apply `overflow-x:hidden` and `overflow-y:none`, the drop-downs are considered overflow and are hidden.
