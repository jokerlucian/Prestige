# Prestige Tattoos Oakham

Static website. No build step: open `index.html` or deploy the folder as is (Cloudflare Pages, Netlify, GitHub Pages).

- Images are hosted on Cloudinary (cloud `dmywrbnwy`, folder `prestige`).
- The quote form posts to Web3Forms. Replace the hidden `access_key` value (see WEB3_KEY in the generator). The key is created at web3forms.com with the email `prestigetattoos@outlook.com`.
- `_redirects` keeps the old Shopify addresses working (Cloudflare Pages and Netlify).
