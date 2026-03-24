# Grace Amidu News | Live Global News Portal

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A modern, high-performance **Single Page Application (SPA)** built for **Grace Andre Amidu Digital**. This platform serves as a "Carrier of Breaking News," utilizing real-time satellite data feeds to deliver news from Africa, the USA, and the global stage without page reloads.

## 🚀 Architectural Overview

The project has been refactored from a traditional multi-page HTML structure into a **Client-Side Rendered (CSR)** architecture.

  * **SPA Engine:** Logic-driven content switching via `app.js`.
  * **Dynamic Data Layer:** Integration with the **NewsData.io API** for live global headlines.
  * **UI Framework:** Built on **Bootstrap 5.3** with a customized "CNN-style" aesthetic.
  * **State Handling:** Real-time "Breaking News" ticker and category-based filtering (Africa, World, Sports, Entertainment).

---

## 📂 Project Structure

```text
.
├── index.html          # Main Application Shell (SPA Container)
├── assets/
│   ├── css/
│   │   └── style.css   # Custom "CNN" Branding & UI Overrides
│   ├── js/
│   │   └── app.js      # Core Logic: API Fetching & DOM Injection
│   ├── images/         # Brand Assets (Logo, Favicons)
│   ├── audio/          # Local Media (JUDAH.m4a, WINNER.m4a)
│   └── video/          # Featured Media (GIDE.mp4)
└── README.md           # Documentation
```

-----

## 🛠️ Features

  * **Live Satellite Ticker:** A persistent, high-visibility breaking news bar with CSS-accelerated animations.
  * **Hero Stage:** An automated "Top Story" section that highlights the most critical global headline with high-resolution imagery.
  * **Category Switching:** Instantaneous filtering between **Africa**, **USA & World**, **Sports**, and **Entertainment** using asynchronous JavaScript.
  * **Responsive Design:** Fully optimized for mobile, tablet, and desktop viewing.
  * **Media Integration:** Dedicated slots for localized audio broadcasts and video reporting.

-----

## ⚙️ Installation & Setup

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/grace-amidu-news.git
    ```

2.  **API Configuration:**

      * Sign up at [NewsData.io](https://newsdata.io/) to get an API Key.
      * Open `assets/js/app.js`.
      * Replace `const API_KEY = '...'` with your unique key.

3.  **Launch:**

      * Since this is a client-side application, simply open `index.html` in any modern web browser or use a "Live Server" extension in VS Code.

-----

## 👨‍💻 Technical Stack

  * **Frontend:** HTML5, CSS3 (Variables & Keyframes), JavaScript (ES6+).
  * **Styling:** Bootstrap 5.3, FontAwesome 6.0.
  * **API:** RESTful API Integration via `Fetch`.

-----

## 📝 Author

**Andre Philip Nyanjahia** *Principal Full-Stack Engineer & Solutions Architect* ---
