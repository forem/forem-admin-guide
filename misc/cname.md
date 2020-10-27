# CNAME

### Setting up DNS

To set up your Forem on your own custom domain, you'll need to add a new CNAME record in your Domain Name Systems \(DNS\).  You can manage DNS at your domain registrar, but we also recommend [Cloudflare](https://cloudflare.com), which provides a free plan.

Here are instructions on [how to add a CNAME record at Cloudflare](https://support.cloudflare.com/hc/en-us/articles/360020615111-Configuring-a-CNAME-setup).

### Instructions

Every DNS provider is a bit different, but you'll be setting the Type, Value, Host, and TTL.

* **Type** is a CNAME \(_not_ an A record, TXT record, etc\)
* **Value** is your Forem Cloud subdomain
* * It will look like `forem-742342330b2c53.forem.cloud`
* **Host** is the subdomain you intend to use
  * For `www.your-forem.com` insert `www`
  * For `community.your-forem.com` insert `community`
* **TTL** is the "time to live"
  * Feel free to leave the default value \(typically 1 hour\)

### Re: APEX domains

Currently, we are not able to support APEX domains, such as `https://your-forem.com`.  If this is a hard requirement and you're not able to use `https://www.your-forem.com` or an equivalent, please contact the Forem account management team.

For Cloudflare users, we recommend forwarding APEX domain traffic to the `www` version.  Here are instructions:

* **Important:** you must only use Cloudflare for DNS, and not their additional services
* To "pause" Cloudflare on your domain, [follow these instructions](https://support.cloudflare.com/hc/en-us/articles/203118044-How-do-I-temporarily-deactivate-Cloudflare-#h_8654c523-e31e-4f40-a3c7-0674336a2753)
* To configure the redirect,[ follow these instructions](https://community.cloudflare.com/t/redirect-example-com-to-www-example-com/78348)

