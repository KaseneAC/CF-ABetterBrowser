This CloudFlare app adds a simple text message at the top of your website if the visitor's browser version is too old.

If the visitor is using Internet Explorer 6 or 7 (any version lower than 8), the message will appear, with a link to [WhatBrowser.org](http://www.whatbrowser.org/). The version limit is configurable. 

There are links to four different modern browsers at WhatBrowser.org, including the most recent version of user's current browser.

![Example](/images/apps/abetterbrowser/example.png "What it looks like")

Note: Internet Explorer 9's [Compatibility view](http://windows.microsoft.com/en-US/internet-explorer/products/ie-9/features/compatibility-view) will trigger the message, since the browser pretends to be an earlier version of Internet Explorer.

*This app was inspired by ABetterBrowser.org, though it's since been updated to point to WhatBrowser.org for a smoother user experience.*

## Styling the message
You can style the message however you want! All you need to do is add styles with id *#cloudflare-old-browser*. View sourcecode for more details.
Additionaly it adds class *cloudflare-old-browser-body* to document's body, if you'd like to push website's content down, so it won't be blocked by this message.


## Contribute your translation
This app is opensource, so you are able to add a translation in your language simply by forking the repository at GitHub.


## Sourcecode
You may view sourcecode of this app at [GitHub](https://github.com/xPaw/CF-ABetterBrowser).
