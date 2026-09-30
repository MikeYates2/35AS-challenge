# 35th Anniversary Summit Challenge Deck

A single-page, mobile-first card deck for the 35th Anniversary Summit (Oct 2–3). It holds 100 micro challenges, 50 hot-take questions and 50 education questions. Tap **Flip a card** to draw a random card; **Shuffle** puts every card back in the deck.

Everything lives in `index.html`. To edit cards, change the `CHALLENGES`, `HOT_TAKES` or `EDUCATION` lists near the bottom of the file.

Deployed on Netlify with no build step (`netlify.toml` publishes the repo root).

## Home screen app

The first time someone opens the site on a phone, a guide shows how to add it to the home screen (Safari/Chrome on iPhone, Chrome on Android). Once added, it opens full screen with the 35 icon (`manifest.webmanifest`, `icons/`), and `sw.js` keeps a saved copy so it still opens with patchy wifi.
