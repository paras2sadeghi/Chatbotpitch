# FlashCARE Investor Pitch

Static investor pitch webpage for Vercel.

## Deploy

Repository:
https://github.com/paras2sadeghi/InvestorPitch.git

Vercel settings:
- Framework preset: Other
- Build command: leave empty
- Output directory: `.`

The site entry point is `index.html`. Keep the `assets` folder beside it.

## AI demo

The investor chatbot uses `api/chat.js`.

Add this Vercel environment variable before presenting the live demo:
- `OPENAI_API_KEY`

Optional:
- `OPENAI_MODEL` defaults to `gpt-4.1-mini`

If the key is missing, the page still works and shows a graceful demo-mode response.
