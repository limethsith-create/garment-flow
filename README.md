# GarmentFlow

Garment wholesale sales tracker — PWA that installs on any Android phone.

## Deploy to Vercel (3 steps)

### 1. Push to GitHub
```bash
cd garment-flow
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/garment-flow.git
git branch -M main
git push -u origin main
```

### 2. Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **"Add New Project"**
3. Import your `garment-flow` repo
4. Framework Preset: select **"Other"** (it's a static site, no build step needed)
5. Click **Deploy**

That's it. Vercel will give you a URL like `garment-flow.vercel.app`.

### 3. Install on Android
1. Open your Vercel URL in Chrome on your phone
2. Tap the **three dots menu** (top right)
3. Tap **"Add to Home screen"** or **"Install app"**
4. It now appears as an app icon on your home screen

## Features
- Product catalogue with photos
- Sales tracking (offered vs accepted quantities)
- Buyer directory with order history
- Dashboard with revenue charts
- Excel export (Sales, Products, Buyers, Summary sheets)
- Works offline (service worker caches everything)
- Data stored on-device via IndexedDB

## Currency
Default is USD ($). To change, search for `formatCurrency` in `index.html` and update the symbol.
