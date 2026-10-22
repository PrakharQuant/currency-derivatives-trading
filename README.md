# 💱 Currency Derivatives Trading — A Quant Finance Career Guide

**Live site:** https://prakharquant.github.io/currency-derivatives-trading/

An educational GitHub Pages project that explains **currency (FX) derivatives trading as a career in quantitative finance**. It is a single-page static site (plain HTML/CSS/JS, zero dependencies) covering:

| Section | What you'll find |
|---|---|
| 🏗️ The Market | G10 majors, EM crosses, exotic pairs — how the ~$9.6T/day FX market is organized |
| 📦 Products | Forwards, NDFs, FX swaps & CCS, vanilla options, exotics (TKNs, accumulators), listed futures |
| 📖 Terminology Decoder | 35+ industry terms (pip, tom-next, swap points, CIP basis, risk reversal, butterfly, charm/vanna, XVA, carry…) filterable by category |
| 🧰 Key Skills | Stochastic calculus (Black-76/SABR/Heston), Python/C++, data engineering and macro intuition hiring managers weight |
| 🌍 Major Venues | CME/PHlx, EBS, LMAX, SGX FX, MCX, CFETS, KRX + clearing houses (LCH), benchmark fixes (WM/R), data vendors |
| 📊 Strategy Families | Carry & factors, macro/event-driven, stat-arb/RV, volatility trading, HFT market-making, structuring |
| 🪜 Career Path | QR → Quant/Vol Trader → Senior Researcher/PM → Desk Head/Founder, compensation snapshot, who hires, how to break in |
| 📚 Resources | Books, free tick datasets (Dukascopy, BIS survey), practice projects, regulatory notes (Dodd-Frank/EMIR/MiFID II) |

## 🚀 Deploy with GitHub Pages

1. Create a new repository named `currency-derivatives-trading` on GitHub.
2. Push this project to it:
   ```bash
   git init -b main
   git add .
   git commit -m "Currency derivatives quant career guide"
   git remote add origin https://github.com/<your-username>/currency-derivatives-trading.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Build and deployment → Source** and select **GitHub Actions**.
4. The included workflow (`.github/workflows/pages.yml`) builds and publishes automatically on every push to `main`.
5. Your site goes live at the URL shown in the Pages settings (Actions tab shows progress).

Alternatively, skip the workflow entirely: set Pages source to **Deploy from a branch → `main` / (root)**.

## 🗂️ Project structure

```
├── index.html                  # The full site (self-contained)
├── README.md                   # You are here
└── .github/workflows/pages.yml # GitHub Pages deploy workflow
```

---
Created by **Prakhar Gupta** · bestofprakhar@gmail.com · [LinkedIn](https://www.linkedin.com/in/prakhar-gupta-5b7250372/) · [X](https://x.com/PrakharQuant)
