# Ánima

A interactive game to choose, it has 3 endings inspired by greek mythology.

## About

You are a soul who has just died. Standing on the banks of the River Styx, you must face judgment before the gods of the underworld — Charon, Persephone, and Hades — who will determine your eternal fate through philosophical questions about the life you lived.

Your answers to their questions will lead you to one of three possible endings:
- **The Elysian Fields** — the good ending
- **The Asphodel Meadows** — the neutral
- **Tartarus** — the bad ending

## Structure

```
anima/
├── index.html             
├── css/
│   ├── story-theme.css     
│   ├── base.css           
│   ├── components.css     
│   ├── layouts.css        
│   └── animations.css      
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
