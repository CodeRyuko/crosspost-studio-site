# TikTok Information Site

Replace `[CONTACT EMAIL]` and `[EFFECTIVE DATE]`, then host this directory as a static HTTPS site. Configure its Privacy Policy and Terms URLs in the TikTok developer application.

If TikTok supplies a URL-signature verification filename and contents, place that exact file at the documented site root without changing either value. Deploy it, confirm it is publicly retrievable at the exact HTTPS URL, and then complete verification in TikTok for Developers. Never commit Client Secrets or tokens to this directory.

Desktop Sandbox redirect URI: `http://127.0.0.1:*/tiktok/oauth/callback/`.
