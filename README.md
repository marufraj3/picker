# ALZEENA Comment Picker

A browser-side giveaway picker for ALZEENA's winter giveaways. Comments are loaded manually from Facebook-export JSON files; this app no longer connects to Facebook or uses access tokens.

## Features
- ALZEENA logo, Hind Siliguri font, dark-purple winter style, snow and winner celebration.
- Upload several JSON comment-export files at once, or load the bundled sample file.
- Choose one entry per person or one entry per comment.
- Draw and reroll winners; previously confirmed winners remain excluded.
- Winner popup with profile name/photo and original comment link when present.
- Branded shareable PNG winner card.
- Comment JSON is parsed locally in the browser; it is not sent to a server.

## Run locally
From this directory, run:

```bash
python3 -m http.server 8000 --bind 0.0.0.0
```

Then open `http://localhost:8000`.
