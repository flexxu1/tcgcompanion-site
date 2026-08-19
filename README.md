# tcgcompanion-site

Public hosting for the TCGCompanion browser extension's privacy policy.

**Live URL:** https://flexxu1.github.io/tcgcompanion-site/privacy-policy.html

This repository is public **on purpose** and contains exactly one page. The extension's
source lives in a separate private repository; nothing here exposes it.

Why a separate repo rather than GitHub Pages on the code repo: Pages only serves from
public repositories on the free plan, and the code repo is private. Pointing Pages at the
code repo's `docs/` would also publish the internal shippability audit and release notes.

The page is deliberately self-contained — no external stylesheet, font or script. A privacy
policy that loads third-party assets is making a request on the reader's behalf, which is
the opposite of what this one claims about the product.

Source of truth is `site/privacy-policy.html` in the extension repo. Copy it here; do not
edit this copy directly, or the two will drift and the Chrome Web Store treats any
discrepancy between the policy and actual behaviour as a violation.
