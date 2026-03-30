# Stefan din Sud — Blog personal

Blog generat cu [Hugo](https://gohugo.io/) și tema [PaperMod](https://github.com/adityatelange/hugo-PaperMod).

## Cum să adaugi un articol nou

1. Mergi în folderul `content/posts/`
2. Click **Add file** → **Create new file**
3. Numele fișierului: `titlul-articolului.md`
4. Conținutul:

```markdown
---
title: "Titlul articolului"
date: 2026-04-01
draft: false
tags: ["istorie", "reflecții"]
categories: ["Personal"]
summary: "O scurtă descriere a articolului."
---

Textul articolului aici.

## Subtitlu

Alt paragraf.
```

5. Click **Commit changes** → site-ul se actualizează automat în ~2 minute.

## Cum să adaugi imagini

1. Urcă imaginea în folderul `static/images/` (creează-l dacă nu există)
2. Referențiaz-o în articol: `![Descriere](/images/nume-imagine.jpg)`

## Structura proiectului

```
├── hugo.yaml              # Configurare site
├── content/
│   ├── about.md           # Pagina "Despre"
│   ├── archives.md        # Pagina "Arhivă"
│   └── posts/             # Articolele tale
│       └── primul-gand.md # Primul articol
├── static/                # Fișiere statice (imagini, etc.)
└── .github/workflows/     # Deploy automat
```
