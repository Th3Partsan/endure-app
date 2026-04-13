# ENDURE 🛡️
### *Quality Clothing. Durability Scored. Value Proven.*

> A mobile-first web app that curates clothing brands meeting strict durability and price-to-quality standards. No fast fashion. No fluff. Just brands built to last.

![ENDURE App Preview](preview.png)

---

## 🌐 Live Demo
**[▶ Open ENDURE App](https://YOUR-USERNAME.github.io/endure-app/)**
*(Replace with your GitHub Pages URL after deployment)*

---

## 📱 Features

| Feature | Description |
|---|---|
| 🛡️ **Durability Scores** | Every brand rated 0–100 across 5 weighted criteria |
| ⚖️ **Cost-Per-Wear** | CPW calculated and compared against category averages |
| 🔬 **Material Breakdown** | Visual fiber/fabric composition per brand |
| 🔗 **Direct Brand Links** | One tap to each brand's official website |
| 🔀 **Brand Comparison** | Side-by-side comparison tool for any 2 brands |
| 📋 **Selection Criteria** | Full 7-pillar methodology — fully transparent |
| ❤️ **Save Brands** | Wishlist / saved brands list |
| 📱 **PWA-Ready** | Add to Home Screen on iOS & Android |

---

## 🏷️ Curated Brands (v1.0)

| Brand | Category | Score | Key Differentiator |
|---|---|---|---|
| **Patagonia** | Outdoor / Fleece | 96/100 | Free lifetime repairs, B-Corp certified |
| **Filson** | Heritage / Work | 94/100 | 125+ yr heritage, Tin Cloth, USA-made |
| **Icebreaker** | Merino Wool | 88/100 | ZQ-certified merino, natural odor resistance |
| **Red Wing Shoes** | Heritage Footwear | 97/100 | Goodyear welt, resoleable, USA-made |
| **Levi's 501** | Denim | 87/100 | 14oz denim, copper rivets, 150yr heritage |
| **Carhartt** | Workwear | 91/100 | 12oz duck canvas, triple-stitch, best CPW |
| **Arc'teryx** | Technical Outerwear | 95/100 | Gore-Tex Pro, ReBird™ repair program |
| **Uniqlo (Select)** | Basics | 85/100 | Supima cotton, HeatTech, best value/$ |

---

## 📐 Brand Selection Criteria (7 Pillars)

1. **Material Quality Threshold** — Minimum fiber integrity, tensile strength, pilling resistance
2. **Construction Standards** — Double/triple stitching, bar-tacking, YKK zippers, seam strength ≥200N
3. **Expected Lifespan** — Outerwear 7+ yrs, Denim 5+ yrs, Footwear resoleable or 10+ yr build
4. **Price-to-Value Ratio** — Cost-Per-Wear must beat category median by 30%+
5. **Repairability & Brand Support** — Repair services, replacement parts, no planned obsolescence
6. **Transparency & Traceability** — Published factory list, clear material composition
7. **Community Validation** — 4.0+ long-term owner rating, <15% major defects within 3 years

### Score Weighting
```
Material Quality    ████████████  30%
Construction        ██████████    25%
Price-to-Value      ████████      20%
Repairability       ██████        15%
Community Score     ████          10%
```

---

## 🗂️ Project Structure

```
endure-app/
├── index.html          # Main app (single-file, zero dependencies)
├── README.md           # This file
├── LICENSE             # MIT License
├── .gitignore          # Git ignore rules
└── preview.png         # App screenshot (optional)
```

---

## 🚀 Deployment

### GitHub Pages (Recommended — Free & Instant)

1. **Fork or clone** this repository
2. Go to your repo → **Settings** → **Pages**
3. Under *Source*, select **Deploy from a branch**
4. Choose **`main`** branch → **`/ (root)`** folder
5. Click **Save**
6. Your app will be live at:
   ```
   https://YOUR-USERNAME.github.io/endure-app/
   ```
   *(Takes ~60 seconds to deploy)*

### Local Development
```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/endure-app.git
cd endure-app

# Open directly in browser (no server needed)
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## 📲 Install as Mobile App (PWA)

**iPhone / iPad (Safari):**
1. Open the GitHub Pages URL in Safari
2. Tap **Share** → **Add to Home Screen**
3. Tap **Add** — ENDURE appears as a native-looking app icon

**Android (Chrome):**
1. Open the URL in Chrome
2. Tap **⋮** → **Add to Home Screen**
3. Tap **Add**

---

## 🤝 Contributing

Want to nominate a brand or update a score? Open an issue or pull request!

**To add a brand:**
1. Verify it meets all 7 criteria
2. Add its data object to the `brands` const in `index.html`
3. Add a card to the Home and Compare screens
4. Submit a PR with evidence/sources for the durability claims

**Brand data structure:**
```javascript
brandId: {
  name: "Brand Name",
  sub: "Category · Est. YEAR · Location",
  emoji: "🏷️",
  bg: "linear-gradient(135deg, #color1, #color2)",
  score: 90,           // 0–100
  price: "$$",         // $, $$, $$$, $$$$
  cpw: "$0.10/wear",
  lifespan: "8–12 yrs",
  repairs: "Yes",
  resale: "70%",
  tags: [{t:"Tag Name", c:"green|blue|purple|"}],
  materials: [{name:"Fabric", pct:80, color:"#hex"}],
  why: [{icon:"🔩", text:"Reason it qualifies..."}],
  scores: [{n:"Material Quality", v:90, w:30}, ...],
  url: "https://brand-website.com"
}
```

---

## 📜 License

MIT License — free to use, modify, and distribute. See [LICENSE](LICENSE).

---

## ⚠️ Disclaimer

ENDURE is an independent editorial project. Brand scores reflect our methodology and community data. We are not affiliated with, sponsored by, or endorsed by any of the listed brands. All external links go to official brand websites.

---

*Built with zero dependencies — pure HTML, CSS, and JavaScript.*
*Inspired by the philosophy: buy once, buy right.*
