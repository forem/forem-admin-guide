---
description: >-
  reCAPTCHA is used to prevent spam from hitting your report abuse page. This is
  an optional, but highly recommended protection against spam. More details
  here: https://www.google.com/recaptcha/about/
---

# Google reCAPTCHA

## Creating your reCAPTCHA App

1. First, visit the admin panel to create an app for your Forem: [https://www.google.com/recaptcha/admin/create](https://www.google.com/recaptcha/admin/create)
2. Fill out the appropriate fields:
   1. Label: **Your Forem name \(for ex. My Forem\)**
   2. reCAPTCHA Type: **reCAPTCHA v2**
      1. Choose the default, **"I'm not a robot" Checkbox**
   3. Domains: **your-domain.com**
3. Check the "Accept the Terms of Service" checkbox.

Before submitting, it should look like this:

![](../../../.gitbook/assets/image%20%281%29.png)

![](../../../.gitbook/assets/image.png)

Once you've clicked submit, you should see your site and secret keys:  


![](../../../.gitbook/assets/recaptcha-submit-example.png)

Please add them to your Forem's config section via /admin/config:

![](../../../.gitbook/assets/screen-shot-2020-10-08-at-9.54.03-am.png)

