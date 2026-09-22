# k-note-image

Public image assets used by `nano-tani/k-note-editor` for Threads posts.

The repository is intentionally separate from the private content repository. Threads fetches media from the public raw URL, for example:

`https://raw.githubusercontent.com/nano-tani/k-note-image/main/tarot/temperance.png`

The tarot directory contains all 78 cards. Use the same raw URL pattern with
the filename below:

- Major Arcana: `fool`, `magician`, `high-priestess`, `empress`, `emperor`, `hierophant`, `lovers`, `chariot`, `strength`, `hermit`, `wheel-of-fortune`, `justice`, `hanged-man`, `death`, `temperance`, `devil`, `tower`, `star`, `moon`, `sun`, `judgement`, `world`
- Minor Arcana: `wands-*`, `cups-*`, `swords-*`, and `pentacles-*`, using `ace` through `ten`, then `page`, `knight`, `queen`, and `king`

For example:

`https://raw.githubusercontent.com/nano-tani/k-note-image/main/tarot/wands-ace.png`

Parent-post visual with three cards face down:

`https://raw.githubusercontent.com/nano-tani/k-note-image/main/tarot/parent-three-card-back.png`

Additional parent-post variations:

- `https://raw.githubusercontent.com/nano-tani/k-note-image/main/tarot/parent-three-card-back-row.png`
- `https://raw.githubusercontent.com/nano-tani/k-note-image/main/tarot/parent-three-card-back-diagonal.png`
- `https://raw.githubusercontent.com/nano-tani/k-note-image/main/tarot/parent-three-card-back-semicircle.png`

Reversed-position cards are exact 180-degree rotations of the upright cards and
are stored separately under `tarot/reversed/`. For example:

`https://raw.githubusercontent.com/nano-tani/k-note-image/main/tarot/reversed/temperance.png`

Do not put access tokens, drafts, post text, or private data here.
