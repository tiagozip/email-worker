worker that connects **your own domain** to [mail.estrogen.delivery](https://mail.estrogen.delivery), for free. it receives mail for your domain (via Email Routing) and sends mail as your domain (via Email Sending), bridging both to estrogen mail.

## deploy

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/tiagozip/email-worker-template)

1. click the button. It clones this Worker into your account.
2. when asked for **`RELAY_CONFIG`**, paste the single value from the mail app (Settings → Domains).
3. in the Cloudflare dashboard for your domain, set the **Email Routing** catch-all to **Send to a Worker → this worker**, and enable **Email Sending** for the domain.
4. back in the app, paste the Worker URL and verify.
