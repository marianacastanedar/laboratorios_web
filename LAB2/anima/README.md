# Ánima

A "Choose Your Own Adventure" interactive narrative built with HTML and CSS, inspired by Greek mythology.

## About

You are the soul of a young poet and artist who has just died. Standing on the banks of the River Styx, you must face judgment before the gods of the underworld — Charon, Persephone, and Hades — who will determine your eternal fate through philosophical questions about the life you lived.

Your answers to their questions will lead you to one of three possible endings:
- **The Elysian Fields** — for souls who lived with authenticity and wisdom
- **The Asphodel Meadows** — for ordinary souls with lives of uncertainty
- **Tartarus** — the abyss beneath everything

## Structure

```
anima/
├── index.html              ← Start here
├── css/
│   ├── story-theme.css     ← Design tokens and variables
│   ├── base.css            ← Reset and global styles
│   ├── components.css      ← Buttons, cards, dialogue
│   ├── layouts.css         ← Grid structure and backgrounds
│   └── animations.css      ← Keyframes and transitions
└── paginas/
    ├── caronte.html
    ├── caronte-belleza.html
    ├── caronte-virtud.html
    ├── persefone-sacrificio.html
    ├── persefone-arte.html
    ├── persefone-mentira.html
    ├── persefone-verdad.html
    ├── final-eliseo.html
    ├── final-asfodelos.html
    └── final-tartaro.html
```

## How to Run

### With NGINX (recommended)
```bash
sudo mkdir -p /var/www/html/adventure
sudo cp -r ./* /var/www/html/adventure/
sudo chmod -R 755 /var/www/html/adventure
```
Then open: `http://localhost/adventure/`

### Without a server
Open `index.html` directly in your browser.

## Tech Stack
- HTML5
- CSS3 (Grid, Flexbox, custom properties, keyframe animations)
- No JavaScript — navigation is done entirely through HTML anchor tags
- Google Fonts: Cinzel + Raleway

## Author
Developed by Mar — Universidad del Valle de Guatemala, 2026
