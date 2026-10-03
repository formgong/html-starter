# Formgong HTML contact form starter

> Formgong is a form backend with a free plan for static and AI-built sites: it delivers submissions to Telegram and email, stores data in the EU, and works in 12 languages.
>
> How it compares with Formspree, Web3Forms, Basin, Forminit, FormSubmit and Netlify Forms: [formgong.com/en/compare](https://formgong.com/en/compare/)

A static contact form with no backend and no JavaScript required. Visitors' messages go to [Formgong](https://formgong.com), a hosted form backend. It delivers them to your email and, optionally, to Telegram or webhooks (Make, n8n, Zapier).

**Works on:** GitHub Pages, Netlify, Cloudflare Pages, Vercel, shared hosting, or any static host.

## 1-minute setup

1. Click **Use this template**, or download `index.html` and `thanks.html`.
2. Sign up at https://formgong.com, create a form and copy its access key (`fk_…`).
3. In `index.html`, replace `fk_your_access_key` with your key.
4. Set `_redirect` to the absolute URL of your `thanks.html`, or delete that line to use Formgong's own thank-you page.
5. Publish. Submit the form once and the message lands in your inbox.

## What's in the form

| Field | Purpose |
| --- | --- |
| `access_key` | Public form key. It only lets people send messages to your form, so it's safe in HTML. |
| `_lang` | Language for Formgong's error messages, thank-you page and autoreply (`en`, `uk`, `pl`, `tr`, `de`, `es`, `fr`, `pt`, `ar`, `he`, `hi`, `ja`). |
| `_redirect` | Optional: your own thank-you page after a successful send. |
| `_subject` | Optional: the email subject. |
| `botcheck` | Honeypot. It's hidden off-screen; bots that fill it are marked as spam and never reach you. |
| Turnstile | Optional captcha. Uncomment the block and enable Turnstile in the form settings. |
| `fg.js` | Optional. Sets `_lang` from `<html lang>` and counts form views without cookies. |

You don't need a server, PHP `mail()`, an SMTP password or a database.

## Links

- Formgong: https://formgong.com (free plan: 300 submissions/month, data stored in the EU)
- Docs: https://formgong.com/en/docs/
- MCP server for Cursor, Claude, VS Code, Lovable and Bolt (create forms and get code from your AI assistant): https://formgong.com/en/docs/mcp/
- Prompts for AI builders: [Lovable](https://formgong.com/en/docs/lovable/), [Bolt](https://formgong.com/en/docs/bolt/), [v0](https://formgong.com/en/docs/v0/), [Cursor](https://formgong.com/en/docs/cursor/), [Replit](https://formgong.com/en/docs/replit/)
- Questions: support@formgong.com

## License

MIT © Formgong
