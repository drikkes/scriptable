# Scriptable
This widget for iOS is far from being original, and in fact I contributed very little to it. You'll need the [Scriptable](https://scriptable.app/) app in order to be able to run it.

## TerminalWidget
In [yaylinda](https://github.com/yaylinda/scriptable#terminalwidget)`s version of the widget, you'll find intructions on how to use it, like installing the [Cache.js](https://github.com/yaylinda/scriptable/blob/main/Cache.js) first. My script relies even more on the work of [arigata9](https://gist.github.com/arigata9/72232bffd445be081ce8b2a293b8bc0a), as he helped me with some of the customizations. He wrote the code for the streak counter showing in line 7, as well as the date format in line 1. 

![IMG_3750](https://user-images.githubusercontent.com/6489982/159166290-9db897ff-4287-45a9-815d-06107dc93646.jpg)

For the rest I changed the font and background colors and adjusted the language/metrics to my needs, the info showing remains more or less the same. After the initial 2 lines for login time and smartphone version that is:
- Line 1 shows the next event from my personal calendar
- Line 2 is for the next event from my work calendar
- Line 3 weather conditions (in Celsius)
- Line 4 is for location data
- Line 5 Basically a days counter (since there is no [Duolingo API](https://duckduckgo.com/?t=ffab&q=duolingo+api&ia=web) to use)
- Line 6 battery percentage and screen brightness

So my contibution only was the input for date besides time, the idea for the counter and copypasting it all together. That's it, feel free to also remix this material.
