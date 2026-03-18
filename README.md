# Amazon Clone 🛒

Another front-end project where I tried to recreate Amazon's homepage using just HTML and CSS. After doing the Spotify clone, I wanted to challenge myself with something that has more layout complexity — and Amazon's navbar alone kept me busy for a while.

---

## What's in it

- Full top navbar with logo, delivery address, search bar, language selector, account/cart sections
- Hover border effect on all navbar items (that subtle white border you see on the real site)
- Secondary panel with "ALL" menu, quick links, and deals banner
- Hero section with the Amazon India redirect message and background image
- Shop section with 8 product category cards laid out in a responsive flex wrap grid
- Full footer — "Back to top" bar, four link columns, logo, and copyright strip

---

## Built with

- HTML5
- CSS3 (Flexbox, background-image, hover states)
- Font Awesome 6 (via CDN)

Zero JavaScript. Everything is static.

---

## Project structure

```
amazon-clone/
├── INDEX.HTML
├── STYLE.CSS
└── images/
    ├── amazon_logo2.webp
    ├── amazon_icon.png
    ├── amazn_main.jpg
    ├── box_img_1.jpg
    ├── boximage2.jpg
    ├── box3_img.jpg
    ├── box4image.jpg
    ├── box5img.jpg
    ├── box6_img.jpg
    ├── box7.jpg
    └── box8.jpg
```

---

## How to run

Clone it and open `INDEX.HTML` directly in your browser — no setup needed.

```bash
git clone https://github.com/your-username/amazon-clone.git
cd amazon-clone
open INDEX.HTML
```

---

## What I worked on

The navbar was the most interesting part to build. Getting all those sections — search bar, address, cart, account — to sit correctly in one row with consistent spacing took a fair bit of tweaking with flexbox. The search bar with the dropdown on the left and icon on the right was also a fun little challenge.

The shop section cards use `flex-wrap` so they flow into a 4-column grid naturally, which was cleaner than trying to do a fixed grid manually.

---

## Disclaimer

This is a personal learning project. All Amazon branding, logos, and imagery belong to Amazon.com, Inc. Not affiliated with or endorsed by Amazon in any way.

---

## Author

Made by **Mahish** — building clones one site at a time 🚀
