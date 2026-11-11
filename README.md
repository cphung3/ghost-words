# Ghost Words website

Public home, privacy-policy draft and support information for Ghost Words by
Word Fragment. Game source is maintained separately in a private repository.

Buildless HTML/CSS. GitHub Pages publishes `main` from `/`.

- Home: https://cphung3.github.io/ghost-words/
- Privacy: https://cphung3.github.io/ghost-words/privacy/
- Support: https://cphung3.github.io/ghost-words/support/

The policy remains a draft until the publisher confirms the responsible
person/company, working public email, effective date and final disclosures.
Do not use it as the final Google Play policy while it is marked as a draft.

No JavaScript, analytics, advertising scripts, remote fonts or forms are used.
Brand artwork is retained for this site; publication grants no general
redistribution license.

The playful cream, violet, mint, peach and yellow theme retains the mint Haunted G
logo. The homepage includes Classic, local Quick Match and Prove It screenshots,
with links to the original-size PNGs. These are actual development captures;
appearance may change before release.

The Classic rules example uses native HTML disclosure: add T to CAR to reveal
why completing CART loses the round. It works with keyboard and touch without
JavaScript. Headings use Fredoka and body text uses Nunito, both self-hosted
variable fonts from [Google Fonts](https://github.com/google/fonts). Their
SIL Open Font Licenses are included in `assets/fonts/`.

Authoring source lives in the game checkout's `website/` folder. Rebuild with
`python Tools/Website/build_site.py`, then publish only that folder's contents.
`site.json` is public configuration and must never contain credentials.
