# UserChrom

## basic setup

Create directory 'chrome' inside of profile directory.

(Find the profile directory by going to `about:profiles`.)

`toolkit.legacyUserProfileCustomizations.stylesheets` enable this in about:config

Copy your .css into the chrome folder

Restart firefox

### also in `about:config` enable

```
devtools.debugger.remote-enabled
devtools.chrome.enabled
toolkit.legacyUserProfileCustomizations.stylesheets
layers.acceleration.force-enabled
gfx.webrender.all
gfx.webrender.enabled
layout.css.backdrop-filter.enabled
svg.context-properties.content.enabled
```

## tools

Also, to find the class or id of browser elements, go web developer mode, browser toolbox, click inspect icon...

## Examples and Sources:

https://github.com/Godiesc/Chameleons-Beauty/blob/00833559c0530f5f6ac31c17b060588239a45ec6/chrome/components/ch_contextual-menu.css#L33-L67

preatonfox...

https://firefoxcss-store.github.io/

https://github.com/sagars007/starry-fox
