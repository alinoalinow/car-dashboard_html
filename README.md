# Car Dashboard UI


Live demo → [your-username.github.io/car-dashboard](https://your-username.github.io/car-dashboard)

---

## Preview

> Dark, responsive dashboard with real-time gauges, system status, media player, and navigation shortcuts.

---

## Features

- **Speed & RPM** — live gauge with color-coded progress bar
- **Battery range** — tracks remaining km with low-battery warnings
- **Engine temperature** — status indicator with overheat alerts
- **System status** — Engine, Battery, Tires, Brakes health at a glance
- **Climate controls** — dual-zone temperature adjustment (driver + passenger)
- **Media player** — play/pause with track info
- **Navigation** — Home, Work, and Nearby shortcuts
- **Simulate driving** — sliders to test all states in real time
- **Fully responsive** — works on desktop, tablet, and mobile

---

## Tech stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, CSS Grid, Flexbox) |
| Logic | Vanilla JavaScript (no libraries) |
| Hosting | GitHub Pages |



## File structure

```
car-dashboard/
├── index.html      # Everything — HTML, CSS, JS in one file
└── README.md       # This file
```

---

## Customization

All design tokens are CSS variables at the top of the file — easy to retheme:

```css
:root {
  --accent: #378ADD;   /* change to your brand color */
  --green:  #4ade80;
  --bg1:    #111111;
  /* ... */
}
```

---

## License

MIT — free to use, modify, and distribute.

---

Built with HTML, CSS, and JavaScript. No frameworks were harmed in the making of this dashboard.
