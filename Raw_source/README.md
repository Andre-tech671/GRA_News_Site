# Grace Andre Amidu - HTML Only News Site

## 🚀 Project Overview
Grace Andre Amidu is a **static HTML/CSS news website** branded as "The Carrier of Breaking News". It focuses on **Malawi-centric content** across News, Health, Sports, and Entertainment. Built with pure HTML (no JavaScript or frameworks), it uses inline CSS for styling. The site features a consistent black header with logo, purple title, blue tagline, and navigation across all pages.

**Goal**: Deliver engaging local stories (e.g., artist performances, health campaigns, sports leagues, environment initiatives). Copyright © 2026.

## ✨ Features
- **Multi-page navigation**: Home, About, News, Health, Sports, Entertainment, Contact.
- **Marquee scrolling headlines** on homepage linking to full articles.
- **Article teasers** on Index.html with images and "click here for more".
- **Centered images** (300x200px) for each article.
- **Social media icons**: WhatsApp (+265888151727), YouTube (@tiyanjaneamidu-eg1qq), Facebook (Grace Amidu Mw), Telegram (@gracemidoo).
- **Media support**: Images, audios (JUDAH.m4a, WINNER.m4a), videos (GIDE.mp4).
- **Inline styles**: Black header (padding 50px), purple h1, blue p, hr separators.

## 📁 File Structure
```
.
├── Index.html              # Homepage: Teasers + marquees
├── About.html              # Mission statement
├── News.html               # Environment article
├── Health.html             # Polio vaccination drive
├── Sports.html             # 3 sports articles (donations + leagues)
├── Entertainment.html      # 3 entertainment articles (performances + pageant)
├── Contact.html            # (Not analyzed; likely contact form)
├── AUDIOS/
│   ├── JUDAH.m4a
│   └── WINNER.m4a
├── IMAGES/                 # Note: Some src use "images/" (lowercase) – fix casing!
│   ├── BABY.jpeg
│   ├── deebo.jpeg
│   ├── FACEBOOK.jpg
│   ├── Logo.png
│   ├── LUVURI.jpeg
│   ├── MAYAMIKO.jpeg
│   ├── muluzi.jpeg
│   ├── MUM.jpg
│   ├── NORTH.jpeg
│   ├── ONESMUS.jpeg
│   ├── SUFFIX.jpeg
│   ├── TELEGRAM.jpg
│   ├── WAPP.jpg
│   └── YOUTUBE.jpg
└── VIDEOS/
    └── GIDE.mp4
```

## 📄 Page-by-Page Breakdown (How It Works)
All pages share identical **header/nav/footer** structure. Content is static articles with `<h2>`, `<p>`, `<center><img>`, `<hr>`.

### 1. **Index.html** (Home)
- Marquee teasers linking to category pages.
- Featured summaries:
  | Teaser | Links To | Image |
  |--------|----------|-------|
  | Emmie Deebo live in Balaka | Entertainment.html | deebo.jpeg |
  | Onesimus at BICC | Entertainment.html | ONESMUS.jpeg |
  | Mayamiko Chiwaula Miss Culture 2026 | Entertainment.html | MAYAMIKO.jpeg |
  | Polio vaccination 1.3M kids | Health.html | BABY.jpeg |
  | Saving environment with trees | News.html | muluzi.jpeg |
  | Suffix donates sports gear Chitipa | Sports.html | SUFFIX.jpeg |
- Social icons at bottom.

### 2. **About.html**
- `<h2>ABOUT US....</h2>`
- Mission: Dynamic platform for reliable stories on health/entertainment/news/sports. Inform, educate, inspire via responsible journalism.

### 3. **News.html**
- **SAVING ENVIRONMENT WITH TREES** (Writer: Chikondi Chiyemekeza)
  - Deforestation causes (charcoal/firewood), solutions (cookstoves, electricity, replanting).
  - Stats: Escom <10% grid, 400k stoves distributed, 6.4M seedlings.
  - Quote: Minister Atupele Muluzi.
  - Image: muluzi.jpeg.

### 4. **Health.html**
- **MALAWI VACCINATES OVER 1.3 MILLION CHILDREN IN EMERGENCY POLIO DRIVE**
  - Response to Blantyre case, WHO support, 100%+ coverage in some districts.
  - Quotes: Dr Charles Chilambula (preventable via vax/hygiene), Dr Charles Njuguna (coordinated effort).
  - Image: BABY.jpeg.

### 5. **Sports.html** (3 Articles, Writer: Vinjeru Betera Mkandawire)
- **SUFFIX DONATES SPORTS EQUIPMENT... Chitipa**: Musician Aubrey Ghambi (Suffix) donates to schools; quotes Patrick Simwayi/Kisa Masebo. Image: SUFFIX.jpeg.
- **LUVURI FC CROWNED CHAMPIONS NRFA DIVISION**: Final vs Moyale Reserves (3-3, 8-7 pens); goals details. Image: LUVURI.jpeg.
- **EMBANGWENI UNITED CROWNED... M’MBELWA LEAGUE**: 1-1 draw win, promoted to National Division (K7M prize). Image: NORTH.jpeg.

### 6. **Entertainment.html** (3 Articles)
- **Emmie Deebo Sets Balaka Ablaze...**: Live show energy, popular songs, girl empowerment. Image: deebo.jpeg.
- **ONESIMUS DELIVERS UNFORGETTABLE SHOW AT BICC**: Hits, band/dancers, fan interaction. Image: ONESMUS.jpeg.
- **MAYAMIKO CHIWAULA CROWNED MISS CULTURE MALAWI 2026**: Pageant with cultural dances/Q&A; quote on youth preserving culture. Image: MAYAMIKO.jpeg.

### 7. **Contact.html**
- Not read; likely contact details/form mirroring header.

## 🚀 How to Run
1. Open `Index.html` in any browser (Chrome/Firefox).
2. Navigate via links – fully static, no server needed.
3. Media loads from relative paths (fix casing: "IMAGES/" vs "images/").

## 🔧 Remake Suggestions (To Modernize)
Since you want to remake:
1. **Responsive Design**: Use CSS media queries/Flexbox/Grid; Bootstrap CDN.
2. **External CSS/JS**: Extract styles to `styles.css`; add smooth scrolling, audio players (HTML5 `<audio>` for JUDAH.m4a/WINNER.m4a, `<video>` for GIDE.mp4).
3. **Fix Issues**:
   - Image paths: Standardize to "IMAGES/" (case-sensitive on some FS).
   - Broken tags: e.g., social `<a>` missing `>`.
   - Accessibility: Proper `alt` texts, semantic HTML (`<header>`, `<nav>`, `<main>`, `<footer>`).
4. **Enhance**:
   - Single-Page App (SPA) with vanilla JS or React for dynamic content.
   - Search bar, categories sidebar.
   - Embed audios/videos on pages.
   - SEO: Meta tags, OpenGraph.
   - Deploy: GitHub Pages/Netlify.
5. **Content**: Add more articles, RSS feed, comments (Disqus).
6. **Tech Stack Upgrade**: HTML5 + Tailwind CSS + Alpine.js (lightweight).

## 📝 TODO for Remake
- [ ] Standardize paths/casing.
- [ ] Make mobile-responsive.
- [ ] Add audio/video embeds.
- [ ] External CSS/JS files.
- [ ] Test all links/images.

**Live Demo**: Open `Index.html` – experience the retro marquee vibe!
