# Dedepie

A little website with one question.

Open `index.html` in a browser, or deploy the folder as-is (no build step). On
Vercel: import the repo, leave every setting on its default, deploy.

## Make it yours

Everything personal is in one place near the top of `index.html`:

```js
window.LOVE = {
  her: "Dedepie",
  from: "",        // your name; leave empty to sign as "me"
  reasons: [ ... ] // the cards she swipes through
}
```

## Files

- `index.html`: the whole site
- `her.webp`, `her-square.webp`: her photo (polaroid and heart)
- `og.jpg`: the preview image shown when the link is shared on WhatsApp and elsewhere

Once she says yes, her phone remembers it, so opening the link again goes
straight to the certificate. "Watch it again" resets that.
