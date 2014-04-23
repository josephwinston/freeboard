freeboard
==========

**free·board** (noun) *\ˈfrē-ˌbȯrd\*

1. the distance between the waterline and the main deck or weather deck of a ship or between the level of the water and the upper edge of the side of a small boat.
2. the act of freeing data from below the "waterline" and exposing it to the world.
3. a damn-sexy, open source real-time dashboard builder/viewer for IOT and other web mashups.

### Demo
http://freeboard.github.io/freeboard

### Screenshots
![Weather](https://raw.github.com/Freeboard/branding/master/screenshots/freeboard-screenshot-1.jpg)

### How to Use

Freeboard can be run entirely from a local hard drive. Simply download/clone the repository and open index.html. You may run into issues with CORS when accessing JSON based APIs if you load from your local hard-drive in this case you can switch to using JSONP or load index.html and run from a local or remote web server.

### Building Plugins

See http://freeboard.github.io/freeboard/docs/plugin_example.html for info on how to build plugins for freeboard.

### Testing Plugins

Just edit index.html and add a link to your javascript file near the end of the head.js script loader, like:

```javascript
...
"path/to/my/plugin/file.js",
$(function()
{ //DOM Ready
    freeboard.initialize(true);
});
```

### Copyright 

Copyright © 2013 Jim Heising (https://github.com/jheising)<br/>Copyright © 2013 Bug Labs, Inc. (http://buglabs.net)<br/>Licensed under the **MIT** license.
