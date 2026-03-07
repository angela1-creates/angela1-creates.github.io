# Angela Wan — Portfolio

Personal portfolio site for Angela Wan — designer, artist, and builder from San Jose, CA.

**Live site:** https://angela1-creates.github.io

Built with HTML + Tailwind CSS. No build step — deploys directly via GitHub Pages.

---

## Structure

```
angela1-creates.github.io/
├── index.html                        ← main portfolio (all sections)
├── README.md
├── assets/
│   └── images/
│       ├── angela.jpg                ← profile photo (optional)
│       ├── digital-1.jpg             ← art gallery images
│       ├── digital-2.jpg
│       ├── digital-3.jpg
│       ├── oil-1.jpg
│       ├── watercolor-1.jpg
│       ├── colorpencil-1.jpg
│       ├── charcoal-1.jpg
│       ├── oilpastel-1.jpg
│       └── ceramics-1.jpg
└── projects/
    ├── historical-place-stories/
    │   ├── index.html                ← project overview page
    │   └── comic/
    │       └── index.html            ← Kai StoryLens comic storyboard
    └── endometriosis/
        └── index.html                ← endometriosis awareness project page
```

---

## Adding Artwork

1. Export your artwork as `.jpg` or `.png`
2. Name the files to match the list above (e.g. `digital-1.jpg`)
3. Place them in `assets/images/`
4. `git add assets/images/ && git commit -m "Add artwork" && git push`

The gallery in `index.html` will automatically display them.

---

## Sections

| Section | Description |
|---|---|
| Home | Hero with name, tagline, bio |
| Projects | 6 project cards linking to project pages or GitHub |
| Art | Masonry gallery with medium filters + fullscreen lightbox |
| Experiments | AI design, vibe coding, interaction concepts |
| Performance | Guzheng + Musical Theater |
| Community | True Crime Club, Calcolor, AYM, Theater |
| Learning | Georgetown, Brown, JHU CTY + lab skills |
| About | Bio + interest tags |
| Contact | Email, LinkedIn, GitHub |

---

## Deploy

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

GitHub Pages serves `index.html` automatically from the `main` branch root.

---

*Designed & built by Angela Wan · Class of 2028 · Archbishop Mitty High School*
