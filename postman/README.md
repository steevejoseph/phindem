So this is the directory for Postman related things:

The collection in postman called IG Basic Display contains mostly info from [this Getting Started](https://developers.facebook.com/docs/instagram-basic-display-api/getting-started) guide on the INstagram API:

Most of the pertinent info form completing that is [here](https://developers.facebook.com/apps/933969550330511/instagram/basic-display/?business_id=2450856925170792)

Heroku is [here](https://dashboard.heroku.com/apps/phindem/deploy/github)

[An overview](https://developers.facebook.com/docs/instagram-api/overview#pages) of the Instagram Graph API that I didn't get to previously.

[Getting the public info (name, followers, following count) of an Instagram user](https://www.instagram.com/saucemejor/?__a=1)
[A tool for getting the Instagram user ID given an Instagram username](https://commentpicker.com/instagram-user-id.php)

[A VSCode extension for Postman integration](https://marketplace.visualstudio.com/items?itemName=eridem.vscode-postman)

[Guide for getting long-lived (60 days) for IG Basic Display API](https://developers.facebook.com/docs/instagram-basic-display-api/guides/long-lived-access-tokens)
[Guide for getting long-lived (60 days) for FB Graph API](https://developers.facebook.com/docs/facebook-login/access-tokens/refreshing/)

TODO: learn to use pm.\* API

NOTE: to run test suite, Auth flow 1/2 has to be run manually from a browser.

Then, the value of code must be put into the IG_AUTH_CODE env var in the postman collection.
