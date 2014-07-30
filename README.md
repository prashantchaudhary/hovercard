Hovercard
=========

A free light weight jQuery plugin that enables you to display information
related with the hovered label, link, or any html element of your choice.

See the [project page][1] for documentation, demonstration and examples. Released under the [MIT license][2].

Changelog:
----------

###Version 2.4 - 2012/04/12
* **Added Options:**
* `autoAdjust` The plugin's default functionality to auto adjust to the viewport edges can now be overridden.

###Version 2.3 - 2011/12/15
* Enhancement: The plugin now auto adjust on the edges of visible window/viewport!
* **Added Options:**
* `openOnTop`: Set 'openOnTop' to true if you want the hovercard to always open on left.
* `customCardJSON`: Provide a local json data with showCustomCard. Inherits plugin's social card format/styles.
* `delay`: Delay the hovercard appearance on hover.

###Version 2.2 - 2011/12/09
* Bug Fixes: zindex issue with IE7.

###Version 2.1 - 2011/11/22
* Enhancement: attribute 'data-hovercard'. You may now use data-hovercard attribute with your label/link etc to set the twitter or facebook usernames.
* **Added Options:**
* `showCustomCard`: You may now add your own custom data source and display the profile data using existing card format.

###Version 2.0 - 2011/11/08
* Bug Fixes: zindex issue.
* Enhancements: Supercool built in social profile cards like Twitter and Facebook!
* **Added Options:**
* `showTwitterCard`: displays a built in twitter card format for a twitter screenname. Maximum 150 twitter lookup per hour.
* `twitterScreenName`: twitter screen name for the hovercard. If no username/screenname is provided, hovercard attempts to look up for hovered text.
* `showFacebookCard`: displays a built in facebook card format for a facebook username/pages/events etc. Works best with Facebook pages.
* `facebookUserName`: facebook username/pages/events/groups for the hovercard. If no username is provided, hovercard attempts to look up for hovered text.

###Version 1.2 - 2011/09/30
* Enhancement: The hovercard now adjust (either open on left or right) in accordance to the view port.
* **Added Options:**
* `openOnLeft`: force hovercard to open on left. (eg: if the hovered name appear in the end of sentence)

###Version 1.1 - 2011/09/29
* Bug fixed: When using hovercard in hovercard, the inner hovercard shows up as well when parent hovercard opens.

###Version 1.0 - 2011/08/31
* Initial Release.

Installation:
-------------

```sh
git clone https://github.com/prashantchaudhary/hovercard.git
cd hovercard
```
You're ready yo use the **Hovercard**.

Features:
---------
 - Smoothly fades the name into a hovered card (in place).
 - Uses minimum `CSS` and no external Stylesheets to download.
 - Full control over `HTML` to be displayed.
 - Comes with built in Twitter and Facebook Hovercard.
 - Supports callback functions on hover in and hover out.
 - Auto adjust on the edges of viewport.

Usage:
------
Hovercard comes handy while displaying:

 - Person Biography.
 - Author and Price of a Book.
 - Loading related information with `AJAX`.
 - In Place Editing and more...
 
Author & Credits:
-----------------
[Prahsant Chaudhary][3]

An Entrepreneur, Web Developer and Co-founder [MrRightIndia][4] and [Kaaryaa][5].

  [1]: http://designwithpc.com/Plugins/Hovercard
  [2]: http://www.opensource.org/licenses/mit-license.php
  [3]: https://twitter.com/chaudharyp
  [4]: http://mrright.in
  [5]: http://kaaryaa.com
