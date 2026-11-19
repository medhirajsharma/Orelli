# Orelli Coffee — Official Website

Artisanal specialty coffee roasted in small batches and nitrogen-sealed in 100% recyclable aluminium capsules compatible with Nespresso® Original machines.

---

## 🌟 Key Features

- **Interactive Product Catalog**: 5 signature blends (Bold Dark, Smooth Caramel, Fruity Bright, Vanilla Creamy, Decaf Smooth).
- **In-Card Pack Selectors**: Instant toggle between 10, 30, and 55 pods with real-time price & per-capsule calculation.
- **Custom Pack Builder**: Interactive custom box builder (20, 30, 50 capsules) with live progress bar, auto-fill, and bundle discount.
- **Full Shopping Cart Experience**: Slide-over cart drawer, quantity adjusters, coupon code engine (`WELCOME10`), and free shipping meter (orders > ₹999).
- **Dual Checkout Options**:
  - Direct Indian **WhatsApp Order** link with pre-formatted message.
  - Interactive **Instant Checkout modal** with UPI, Net Banking, and COD simulation.
- **Modals & Extras**: Starter Kits bundle, Corporate wholesale quote form, FAQs modal, Light/Dark mode toggle, and responsive mobile navigation.
- **Zero Build Dependencies**: Pure HTML5, Tailwind CSS (via CDN), and Vanilla JavaScript. Runs directly in any browser and hosts effortlessly on GitHub Pages.

---

## 🚀 How to Host on GitHub Pages (Git पर होस्ट कैसे करें)

### Step 1: Commit and Push your changes

```bash
git add .
git commit -m "feat: complete website ready for GitHub Pages hosting"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

*(Note: Replace `<your-username>` and `<your-repo-name>` with your actual GitHub username and repository name)*

### Step 2: Enable GitHub Pages in Repository Settings

1. Open your repository on **GitHub.com**.
2. Go to **Settings** (top tab) &rarr; **Pages** (in the left sidebar under *Code and automation*).
3. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` and folder `/ (root)`.
4. Click **Save**.
5. Wait 1-2 minutes. GitHub will provide your live website link:
   ```
   https://<your-username>.github.io/<your-repo-name>/
   ```

---

## 💻 Local Preview (लोकल कैसे चलाएं)

Simply double-click `index.html` or run:

```bash
python -m http.server 8000
```
Then visit `http://localhost:8000/` in your browser.
