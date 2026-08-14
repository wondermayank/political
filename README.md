# BharatTantra — Indian Polity & Civil Services Explainer

A 16-page glassmorphism website explaining India's political system and civil
services, from Gram Panchayat to President, and from board exams to IAS/IPS.

## How to view it
Just open `index.html` in any browser. No build step, no server needed —
it's plain HTML/CSS/JS. (Google Fonts load from the internet, so an internet
connection is needed for the exact typography; the layout works offline too.)

## Structure
```
index.html                     → Homepage
political/index.html           → Political System hub
political/lok-sabha.html
political/rajya-sabha.html
political/prime-minister.html
political/chief-minister-mla.html
political/president-governor.html
political/parties-elections.html
political/council-of-ministers.html
political/local-governance.html
education/index.html           → Civil Services hub
education/exam-ladder.html
education/upsc-cse.html
education/ias-ips-allocation.html
education/sdm-state-services.html
education/other-services.html
assets/style.css               → Design system (colors, type, components)
assets/main.js                 → Nav toggle + scroll reveal animation
assets/img/                    → Hero images go here
```

## About the hero images
Every hero section is coded to load an image named **Hero1.png, Hero2.png,
Hero3.png…** from `assets/img/`, as requested. I can't generate real photos
in this environment, so right now that folder is empty and the hero sections
fall back gracefully to a soft purple-to-blue gradient panel (so nothing
looks broken).

To finish it: drop your own images into `assets/img/` using these exact
names, and each hero will pick it up automatically:

| File | Used on |
|---|---|
| `Hero1.png` | Homepage |

If you want a unique photo on every page (not just the homepage), tell me
and I'll wire up `Hero2.png` … `Hero16.png` across the other 15 pages the
same way — currently only the homepage hero references an image; the
sub-pages use text + the ladder/card layout instead, to keep the page
weight light.

## Design system
- **Theme**: light glassmorphism — white base, frosted glass cards,
  soft purple (`#7C3AED`, `#A78BFA`, `#C4B5FD`) + blue (`#60A5FA`, `#B9D9DC`)
- **Type**: Sora (headings), Inter (body), JetBrains Mono (labels, ranks)
- **Signature motif**: "The Ladder" — a numbered rung diagram, used because
  the actual content (political hierarchy, exam hierarchy) is a real
  sequence, not decoration
- All colors/spacing live in `assets/style.css` as CSS variables at the top
  — edit those to retheme the whole site at once.
