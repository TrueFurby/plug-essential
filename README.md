Plug Essential
==========

![preview](website/static/preview.png)

Plug Essential is a browser javascript plugin for plug.dj website.

Features
---------
### Current
- Autowoot
- Autojoin
- Advanced userlist
    * Colors by rank
    * Font style by relationship
    * Chat mention link
    * Video response by background
- Detailed user information
    * Language
    * Join date
    * DJ points
    * Listener points
    * Curator points
    * Score
- Top video from history
- Shortcut buttons for DJ booth (lock/unlock booth, skip dj)
    
### Planned
- User filter for userlist
- Estimated time until playing

How to use
---------
    
Add this piece of code to a bookmark and run it in plug.dj room:

```javascript
javascript: (function () {
    var src = "http://plug.phoenixlair.com";
    $('head').append('<link rel="stylesheet" type="text/css" id="plug-essential-css" href="'+src+'/plug_essential.css" />');
    $('body').append('<script id="plug-essential" src="'+src+'/plug_essential.js"></script>');
}());
```
