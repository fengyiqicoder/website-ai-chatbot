# Free AI chatbot for a website

A small business page with a free AI chatbot, added with one script tag. It answers visitors from the page and sends anything else to email.

**Live demo:** https://fengyiqicoder.github.io/website-ai-chatbot/

The tag is at the bottom of `index.html`:

```html
<script async src="https://onetagai.com/widget.js"
  data-key="YOUR_ONETAG_KEY"
  data-title="Ask Juniper Walks"
  data-greeting="Hi! Ask me about walks, prices or booking."
  data-color="#2f6b4f"
  data-system="You are the assistant for Juniper Walks... If the page does not say, ask them to email hello@example.com."
></script>
```

Get a free key at [onetagai.com](https://onetagai.com) (1,000,000 tokens a month, no card). All options: [onetagai.com/docs#widget](https://onetagai.com/docs#widget).

The key in this repo is a public demo key with a small shared quota. Use your own on your site.
