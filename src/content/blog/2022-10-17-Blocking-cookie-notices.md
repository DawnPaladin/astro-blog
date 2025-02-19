---
title: "How to block every cookie notice on the internet"
pubDate: 'Oct 17 2022'
tags: [guides browser-plugins]
description: Making the internet 70% less annoying
published: true
---

So this is something I just recently figured out. Many of you may have already installed [uBlock Origin](https://ublockorigin.com/) in your web browsers. If you haven't, I recommend you do so—blocking ads makes your computer more secure and speeds up your internet experience.

If you have uBlock Origin installed, click on it—it's the red shield icon near the top-right of your browser.

<img src="{{ '/assets/2022-10-17/ublock.png' | absolute_url }}" alt="uBlock Origin config panel" />

Click the gears icon near the lower-right corner. This will open a new tab in your browser where you can change which filter lists uBlock Origin uses. Scroll down a bit. In the "Annoyances" section, enable **"EasyList Cookie"**. Then click the "Update now" button at the top of the screen.

<img src="{{ '/assets/2022-10-17/filter-list.png' | absolute_url }}" alt="uBlock Origin filter list" />

This should remove all (or nearly all) of the "PLEASE ACCEPT OUR COOKIES" messages that plague the internet. 😎️🏖️

If you have an Android phone, you can do the same thing there. First, install [Firefox for Android](https://play.google.com/store/apps/details?id=org.mozilla.firefox). Once it's installed, tap the three-dot menu in the corner, then tap Add-ons, then Add-ons Manager. 

<img src="{{ '/assets/2022-10-17/firefox-addons.jpg' | absolute_url }}" alt="Firefox for Android menu" />

Find uBlock Origin in the list and click the + button to install it. 

<img src="{{ '/assets/2022-10-17/firefox-addons-ublock.jpg' | absolute_url }}" alt="Firefox for Android addons list" />

uBlock Origin will appear at the top of the add-ons list. Tap it, then tap Settings. This will take you to the filter list. Expand "Annoyances", check the "EasyList Cookie" checkbox, and hit the "Reload"-style icon at the top of the page. You're done!

## Bonus feature: Bypass paywalls

Some sites try to track their visitors and rate-limit them to a handful of articles per month. You can block these trackers with the Bypass Paywalls Clean filter.

Right-click on [this link](https://gitlab.com/magnolia1234/bypass-paywalls-clean-filters/-/raw/main/bpc-paywall-filter.txt) and copy the link address. Then go to the Filter Lists screen in uBlock Origin, click "Import" at the bottom, and paste the link into the box. Click "Apply Changes" at the top. Enjoy.