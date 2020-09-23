---
description: Configure your user log-in options.
---

# Authentication

### Allow Email Password Registration

Check this box to enable user registration via email.

### Authentication Providers

Choose which authentication providers users can log in from. We currently offer:

* Twitter
  * First, apply for a developer account at [developer.twitter.com](http://developer.twitter.com/) \(the approval process normally takes about a day\)
  * Then, [follow these instructions](https://developer.twitter.com/en/docs/authentication/guides/log-in-with-twitter) to generate the keys.
* [GitHub](https://docs.github.com/en/developers/apps/creating-an-oauth-app)
  * Callback URL: `https://{your-forem-url.com}/users/auth/github`
* [Facebook](https://developers.facebook.com/docs/apps)

Apple and Google are coming soon.

In order to use these providers, you need to add their respective keys. You can create keys for these providers by visiting their developer portals, linked above.

