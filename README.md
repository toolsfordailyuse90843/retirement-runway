# 📉 Retirement Runway

**Retirement Runway** is a sleek, privacy-focused, single-file retirement planning calculator built specifically for professionals in Ontario, Canada. It bridges the gap between traditional market investing (TFSA/RRSP/Stocks) and defined-benefit pension plans like **OMERS** and **HOOPP**.

---

## ✨ Features

* **Interactive Sliders:** Instantly model changes to your age, retirement timeline, expected monthly lifestyle spending, portfolio balance, and monthly contributions.
* **Ontario Pension Integration:** Built-in calculation formulas for **OMERS** and **HOOPP** defined benefit plans, accounting for salaries, credited service years, YMPE thresholds, contribution rates, bridge benefits, and early-retirement penalties.
* **Solo & Partner Modeling:** Easily switch between single-person planning and dual-income household scenarios with synchronized retirement timelines.
* **Dynamic Gap & Milestone Analysis:** Automatically calculates your projected portfolio growth against required funds, highlighting whether you're ahead or behind, and testing if you can achieve financial independence early.
* **Adaptive Light / Dark Mode:** Clean, distraction-free aesthetic styled with Fraunces and DM Sans typography that respects your system's color scheme preferences.
* **100% Client-Side & Private:** Runs entirely within your browser using vanilla JavaScript and CSS with zero external dependencies, cookies, tracking, or backend servers.

---

## 🚀 Quick Start / Hosting

This project is a single self-contained HTML file, making it exceptionally easy to host:

1. Clone or download this repository.
2. Ensure the main file is named `index.html`.
3. Host it anywhere static web pages are supported (e.g., **GitHub Pages**, Vercel, Netlify).

### Enabling GitHub Pages
1. Go to your repository on GitHub and click on **Settings**.
2. In the left sidebar, click on **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Set the branch to `main` (or `master`) and the folder to `/ (root)`, then click **Save**.
5. Your calculator will be live within a minute at `https://<your-username>.github.io/<repository-name>/`.

---

## 🧮 How It Works

* **Projected Portfolio:** Calculates compound growth of your current portfolio plus monthly contributions at your expected rate of return.
* **Required Portfolio:** Adjusts your lifestyle spending for inflation up to your retirement age, subtracts expected lifetime pension income, and divides by your chosen safe withdrawal rate.
* **Assumptions:** Fully adjustable return rates, inflation rates, and withdrawal rates via the expandable "How is this calculated?" drawer.

---

## 📄 License

This is an open-source planning aid provided for educational and informational purposes. It does not constitute formal financial advice.
