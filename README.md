# लिखो · Likho

**Indian script writing practice.**

Likho started as a project for people who grew up speaking an Indian language at home but never learned to write the script. You already know the sounds — Likho helps you connect them to the characters.

The core loop is simple: see a prompt, draw the character, reveal the answer, grade yourself honestly. Spaced repetition schedules your next review automatically and saves to your browser.

Free, open source, no account needed. Works in any browser.

🌐 **[ilina03.github.io/likho](https://ilina03.github.io/likho)**

---

## Features

- **Drawing canvas** — draw characters with mouse or finger
- **Spaced repetition (SRS)** — Again / Hard / Good / Easy grades, SM-2 algorithm, progress saves to localStorage
- **Browse mode** — grid view of all characters in a deck, click any to jump to it
- **Flip cards** — tap to reveal romanization, description, and example word
- **Trace in browse** — practice drawing while browsing, ghost character as guide
- **Diacritics decks** — vowel signs / matras for all languages
- **Devanagari grid guide** — shirorekha line at 28% for Hindi/Urdu
- **Dravidian center guide** — crosshair for Malayalam, Telugu, Tamil
- **RTL canvas** — right-to-left baseline guide for Urdu
- **Nastaliq / Naskh toggle** — Urdu font preference saved to browser
- **Reference modal** — full alphabet reference available during study
- **Progress tracker** — cards seen, due today, overall percentage bar
- **Reset button** — clears SRS history with confirmation
- **Keyboard shortcuts** — Space to reveal, 1/2/3/4 to grade, arrow keys in browse
- **Responsive** — works on desktop and mobile
- **No backend** — pure HTML/CSS/JS, zero dependencies, zero tracking

---

## How to use

### As a learner
1. Go to [ilina03.github.io/likho](https://ilina03.github.io/likho)
2. Pick your language
3. Start with **Vowels → browse** to see all characters
4. Use **trace** to practice drawing while browsing
5. Hit **study** when you're ready for SRS flashcards
6. Come back daily — the algorithm tracks what you need to review

### Keyboard shortcuts (study mode)
| Key | Action |
|---|---|
| `Space` | Reveal answer |
| `?` | Don't know — auto-grades Again |
| `1` | Again |
| `2` | Hard |
| `3` | Good |
| `4` | Easy |

### Keyboard shortcuts (browse / flip mode)
| Key | Action |
|---|---|
| `←` / `→` | Previous / Next card |
| `Space` | Flip card |

---

## Structure

```
index.html              ← landing page
hindi/
  index.html            ← Hindi (Devanagari)
malayalam/
  index.html            ← Malayalam
telugu/
  index.html            ← Telugu
tamil/
  index.html            ← Tamil
urdu/
  index.html            ← Urdu (Nastaliq/Naskh, RTL)
```

Each language is a single self-contained HTML file. No build tools, no dependencies, no server. Drop in a folder and it works.

---

## Contributing

If you're a native speaker and spot an error in romanizations, vowel descriptions, or word translations — please open an issue or PR. Accurate content matters more than anything else in this app.

---

## Built with

Pure HTML, CSS, and JavaScript. No frameworks, no build step, no tracking, no ads.

Fonts: [Crimson Pro](https://fonts.google.com/specimen/Crimson+Pro) · [Noto Nastaliq Urdu](https://fonts.google.com/noto/specimen/Noto+Nastaliq+Urdu) · [Noto Naskh Arabic](https://fonts.google.com/noto/specimen/Noto+Naskh+Arabic)

---

## Support

Likho is free and always will be. If you find it useful and want to help cover the cost of keeping it running and eventually getting it on the app stores, a small tip is appreciated — but never expected.

☕ **[buymeacoffee.com/ilina03](https://buymeacoffee.com/ilina03)**

---

## License

GNU General Public License v3.0.

You are free to use, modify, and distribute this software. If you distribute a modified version, you must also make the source code available under GPL-3.0.