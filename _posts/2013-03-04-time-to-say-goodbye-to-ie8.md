---
title: What you can do if you stop supporting IE8
description: The arguments for dropping support for IE8 in your website
tags:
    - development
    - front-end
layout: post
---

Try visiting this site in IE8. Go on, I dare ya. Alright, I'll tell you - it looks almost completely unstyled.

In recent years we have said goodbye to widespread support for first [IE6](http://www.ie6countdown.com/) and then [IE7](http://theie7countdown.com/) (not Microsoft led).

Google [dropped support for IE8](http://www.computerworld.com/s/article/9231316/Google_to_drop_support_for_IE8_on_Nov._15) back in November,
[37signals also](http://37signals.com/svn/posts/3097-developing-for-old-browsers-is-almost-a-thing-of-the-past).
There are a [plethora](http://www.smashingmagazine.com/2011/11/03/%E2%80%9Cbut-the-client-wants-ie-6-support%E2%80%9D/) of 
[articles](http://www.rickwhittington.com/blog/should-my-website-support-internet-explorer-7/) out
[there](http://j.eremy.net/are-you-still-supporting-ie7/) imploring people to drop support for Internet Explorer.

IE8 usage
---

According the [theie8countdown.com](http://theie8countdown.com/), global usage is at 24%. On this blog, it's at 1.5%,
and on my company's website, [Arena Blinds](http://www.arena-blinds.com), (used by much less tech-savvy people) it's at 15%.

So if you were bold (like this site), you could probably drop support completely and effect less than 1/5 of your visitors.
And those visitors would quickly upgrade their browsers.

Advantages
---

Dropping comes with significant advantages:

 - Use [practically all of the CSS selectors](http://kimblim.dk/css-tests/selectors/)
 - Use HTML5 semantic elements without a [shim](https://code.google.com/p/html5shim/)
 - Use [much more of HTML5](http://people.mozilla.com/~prouget/ie9/) confidently
 - Use one @fontface format - the [Web Open Font Format](http://en.wikipedia.org/wiki/Woff)
   as all signicant browsers [now support it](http://caniuse.com/#search=woff).
 - Use Data URIs bigger than 32kb (e.g. fonts)

These three points will effect your debugging time for front-end development dramatically.

Consider it.
