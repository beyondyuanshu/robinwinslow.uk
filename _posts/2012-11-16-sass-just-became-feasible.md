---
title: Sass just became feasible
layout: post
tags:
  - development
  - CSS
  - front-end
---
 
<p>I've been interested in CSS pre-processors for a while. They solve the inherent CSS problem of repeatable code blocks, and thus enable <a href="http://semantic.gs/">grid systems</a> that don't <a href="http://webdesignernotebook.com/css/are-css-frameworks-evil/">litter markup with "styling" classes</a>.</p>&#13;
<p>It seems to me that <a href="http://lesscss.org/">LESS</a> and <a href="http://sass-lang.com/">Sass</a> always had one Achilles heel - debugging. Right clicking on an element that is styled incorrectly and inspecting it is absolutely essential to the process of styling a web page, and without that, these tools had no future. I now believe that this problem is behind us.</p>&#13;
<p><!-- more --></p>&#13;
<p>In addition to the <a href="http://stackoverflow.com/questions/9865302/less-sass-debugging-in-chrome-dev-tools-firebug">existing solutions</a>, Webkit now has <a href="http://trac.webkit.org/changeset/123768">built-in support</a> for Sass debugging, and the option is now included in Chrome Developer Tools. Read more about it on <a href="http://bricss.net/post/33788072565/using-sass-source-maps-in-webkit-inspector">bricss.net</a> or <a href="http://benfrain.com/add-sass-compass-debug-info-for-chrome-web-developer-tools/">benfrain.com</a>.</p>&#13;
<p>As a side-note - there is a bit of a <a href="http://stackoverflow.com/questions/8411066/less-vs-sass-vs">battle between LESS and Sass</a>. I always preferred LESS because it seemed more cross-platform, and closer to actual CSS. However this development seems to suggest that tools are being developed faster for Sass. So it's now looking to me as though Sass will prevail.</p> 