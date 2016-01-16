[b]Add Favicon Support[/b]

Version: 1.0 Date: 2008-08-08
Compatibility: SMF 1.1.5; 2.0 Beta 3.1 or later

This modification adds the header tags necessary to enable display of a favicon.ico icon on your site. The favicon.ico is a small 16x16 pixel image that appears in the URL bar in some browsers and is shown in the bookmarks in most browsers. Your icon must be named favicon.ico and should be placed in your website root directory.

Many browsers detect these icons automatically. This modification adds two meta tags to the head section of your forum's pages to aid the browsers that do not auto-detect. (The second tag supports some obsolete browsers.) Here are the lines that are added:

[code]
  <link rel="shortcut icon" href="/favicon.ico" type="image/x-icon" />
  <link rel="icon" href="/favicon.ico" type="image/x-icon" />
[/code]

[b]What is a favicon?[/b]

"A favicon (short for "Favorites icon"), also known as a page icon, is an icon associated with a particular website or webpage. A web designer can create such an icon, and many graphical web browsers such as recent versions of Internet Explorer, Firefox, Mozilla, Opera, Safari, and Konquerorcan then make use of them. Browsers that support favicons may display them in the browser's URL bar, next to the site's name in lists of bookmarks, and next to the page's title in a tabbed document interface." source: [url=http://antifavicon.com/]antifavicon.com[/url]


[b]Useful Links[/b]

[url=http://en.wikipedia.org/wiki/Favicon.ico]Favicon.ico at Wikipedia[/url]

[url=http://www.thesitewizard.com/archive/favicon.shtml]What is Favicon.ico and How to Create a Favicon Icon for Your Website[/url] This site also contains detailed information of various aspects of these icons.

[url=http://antifavicon.com/]An easy to use on-line favicon generator[/url] generates icons such as these:

    [img]http://antifavicon.com/ex1.png[/img] [img]http://antifavicon.com/ex2.png[/img] [img]http://antifavicon.com/ex3.png[/img] [img]http://antifavicon.com/ex4.png[/img] [img]http://antifavicon.com/ex5.png[/img] [img]http://antifavicon.com/ex6.png[/img] [img]http://antifavicon.com/ex7.png[/img] [img]http://antifavicon.com/ex8.png[/img] [img]http://antifavicon.com/ex9.png[/img]

The online favicon generator generates your custom icon from text and colors that you choose yourself. When you are satisfied with your icon, just right click and save the image as favicon.ico.

[b]Support[/b]

You may get support or submit questions and comments in the modification's [url=http://www.simplemachines.org/community/index.php?topic=255428.0]support topic[/url] at the SMF site.

[b]Donations[/b]

[table][tr][td][url=https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=1400104][img]https://www.paypal.com/en_US/i/btn/btn_donateCC_LG.gif[/img][/url][/td][td]      [/td][td]If you like my modification packages, please donate to support their continued development. Any amount will be greatly appreciated. Thank you![/td][/tr][/table]

[size=1]Copyright (c) 2008 by Deprecated (at) Earthlink (dot) net. All rights reserved. Redistribution prohibited except at SimpleMachines.org[/size]