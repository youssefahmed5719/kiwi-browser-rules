# Kiwi Browser rules

Signed content-blocking rules for Kiwi Browser, generated automatically. This repository holds data
only, and its history is replaced on each publish.

`v1/manifest.json` lists every file with its size and SHA-256 hash, and `v1/manifest.sig` is an
Ed25519 signature over that manifest. Kiwi rejects anything that does not verify.

## Licence and attribution

These rules are converted from [EasyList and EasyPrivacy](https://easylist.to) by The EasyList
authors, and are distributed under the
[Creative Commons Attribution-ShareAlike 3.0](https://creativecommons.org/licenses/by-sa/3.0/)
licence, the same licence as the source lists. The conversion drops filters WebKit cannot
represent and reformats the rest as WebKit content-blocker JSON.
