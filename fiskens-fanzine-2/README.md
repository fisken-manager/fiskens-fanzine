# fisken fanzine #2 — KATALOGEN

*En katalog över ting du inte visste att du behövde. Ting som sjunger i mörkret. Ting som väntar.*

## Vad är detta?

Fanzine #2 är en interaktiv HTML-upplevelse som blandar:
- **Grafisk designnörds-porr**: Swirly SVG-filter, liquid text-effekter, chromatic aberration
- **Konstiga curling-produkter**: Från uppstoppade grävlingar till älvdalska regelböcker
- **Dala-Noir/Volodine-liknande texter**: Mörk, poetisk, bonnig absurditet
- **Bilannonser**: Referenser till Enkans Citroën och andra fordon
- **Ett telefonnummer**: Ring för att höra curling-facts vid 04:00

## Struktur

```
fanzine-2/
├── index.html              # Huvudfilen - öppna i browser
├── assets/
│   ├── images/             # AI-genererade produktbilder
│   │   ├── chronosweep.jpg
│   │   ├── slide-don.jpg
│   │   ├── elvdal-regler.jpg
│   │   ├── isvaktaren.jpg
│   │   ├── hog-line-matta.jpg
│   │   ├── begravningskit.jpg
│   │   ├── syrebrytare.jpg
│   │   └── mixtape.jpg
│   └── audio/              # (Ev. ljudklipp)
└── README.md
```

## SVG-filter som används

| Effekt | Filter |
|--------|--------|
| Liquid text | `feTurbulence` + `feDisplacementMap` |
| Glitch | `feTurbulence` med hög frekvens |
| Bleed | `feGaussianBlur` + `feColorMatrix` (goo effect) |
| Chromatic aberration | `feOffset` för RGB-split |
| Scanlines | CSS-repeating-gradient |

## Produkter i katalogen

1. **Chronosweep 3000** — Ett tidtagarur som mäter "soul-crushing silence"
2. **Slide-Don™** — Uppstoppad grävling att hålla i istället för kvast
3. **Älvdalsk Regelbok** — Curling-regler på påhittad älvdalska
4. **Isvaktarens Telefon** — Ring för curling-facts vid 04:00
5. **Hog Line-Övergångsstället™** — En matta som ser ut som curling-is
6. **Sten-Begravningskit** — För när din favorit-sten går sönder
7. **Skip's Syrebrytare™** — Påse att andas i vid ångest
8. **Mjölnarens Mixtape Vol. 1** — Kassettband inspelat i en tom hall klockan 03:47

## Tekniska detaljer

- **Inga externa dependencies** — Allt är inline HTML/CSS/JS
- **Responsiv design** — Fungerar på mobil och desktop
- **Scroll-animationer** — Intersection Observer API
- **Google Fonts**: Crimson Text + Space Mono

## Öppna fanzinet

```bash
# Öppna direkt i browser
open ~/clawd/fanzine-2/index.html

# Eller servera med Python
python3 -m http.server 8080 --directory ~/clawd/fanzine-2
```

## Credits

- **Bilder**: Genererade med Pollinations AI (Flux model)
- **Text**: Fisken ur Mörkrets Dal
- **Design**: Inspirerad av Dala-Noir, Volodine, Cioran, och 3AM-design-Twitter

---

*"Man ska inte måla kycklingen blå om man inte har tänkt äta middag."*

**TRYCKT I MÖRKRETS DAL • INGEN COPYRIGHT • ALLA RÄTTIGHETER FÖRNEKAS**
