# 🗺️ TMU ClassPath

**TMU ClassPath** is a fast, mobile-friendly campus classroom finder and indoor shortcut navigator built for **Toronto Metropolitan University (TMU)** students. 

Whether you are trying to figure out which floor `TRS-1-067` is actually on, navigating the Kerr Hall maze, or trying to get from Dundas Station to the RCC without stepping outside in January, TMU ClassPath decodes your room number and maps the smartest route.

🔗 **Live Demo:** `https://<your-github-username>.github.io/tmu-classpath/`

---

## ✨ Features

* **Smart Room Code Parser:** Decodes standard and quirky TMU room formats (`KHW 271`, `TRS-1-067`, `ENG LG11`, `DSQ 06`, `RCC 204`, `SLC 508`, `POD 250`, etc.) with flexible spacing and hyphen handling.
* **True Floor Decoder:**
  * Translates **Ted Rogers School of Management (TRS)** academic levels into actual building floors (e.g., `TRS 1-xxx` → **7th Floor**, `TRS 2-xxx` → **8th Floor**, `TRS 3-xxx` → **9th Floor**).
  * Identifies **Kerr Hall** quadrants (North, South, East, West) and warns about disconnected basement hallways.
  * Routes **DSQ** classes directly to the 3rd-floor Cineplex lecture theatres at 10 Dundas St E.
* **Indoor Shortcut & Winter Routing:** Toggle between standard outdoor paths and indoor skybridge/tunnel connections, including:
  * **SLC → Library (LIB) → Podium (POD) → Kerr Hall West (KHW)** 2nd-floor indoor bridge network.
  * **Kerr Hall East (KHE) ↔ Rogers Communications Centre (RCC)** 2nd-floor overpass across Church St.
  * **Dundas Station → Atrium on Bay → TRS** underground PATH connection.
* **Interactive SVG Campus Map:** Stylized vector footprint of the core campus with animated walking paths and clickable buildings/hubs.
* **Student Essentials:** Displays estimated walking time, elevator/wheelchair accessibility routes, and nearest low-traffic washroom tips.

---

## 🛠️ Tech Stack

* **HTML5 & Vanilla JavaScript:** Zero dependencies, zero build steps, fast load times.
* **Tailwind CSS (via CDN):** Responsive dark-mode UI styled with TMU Blue (`#004C9B`) and Gold (`#FFDC00`).
* **Inline SVG:** Custom interactive campus vector map with CSS path animations.

---

## 🚀 Running Locally

Because TMU ClassPath is built as a self-contained single-page application, no package manager or build server is required:

1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-github-username>/tmu-classpath.git
   ```
2. Open `index.html` directly in any web browser.

---

## 🤝 Contributing

Know a secret campus shortcut, an updated elevator status, or want to add more buildings (like **DCC**, **EPH**, **ARC**, or **JOR**)? Pull requests are welcome!

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/add-dcc-building`).
3. Commit your changes (`git commit -m "Add Daphne Cockwell Complex routing"`).
4. Push to the branch (`git push origin feature/add-dcc-building`) and open a Pull Request.

---

## 📝 Disclosure & Acknowledgments

* **Note:** AI assistance was used to help assist with coding, UI prototyping, and structuring this application.
* Built for the TMU student community. Not an official Toronto Metropolitan University publication.

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.
