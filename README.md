# AOW — Art of War Crypto Intelligence
## PWA · Deploy to Phone in 5 Minutes

### Step 1 — Deploy to Vercel (Free)
1. Go to vercel.com → Sign up free
2. Click "Add New Project"
3. Choose "Upload" (no GitHub needed)
4. Drag the entire AOW-PWA folder into the upload area
5. Click Deploy
6. Vercel gives you a URL like: aow-xyz.vercel.app

### Step 2 — Install on iPhone
1. Open Safari on your iPhone
2. Go to your Vercel URL
3. Tap the Share button (box with arrow)
4. Tap "Add to Home Screen"
5. Name it "AOW" → tap Add
6. AOW icon appears on your home screen ✓

### Step 3 — Install on Android
1. Open Chrome on your Android
2. Go to your Vercel URL
3. Tap the 3-dot menu
4. Tap "Add to Home Screen" or "Install App"
5. AOW icon appears on your home screen ✓

### Live Data Sources (all free, no API key)
- Prices: api.coingecko.com (refreshes every 60s)
- Fear & Greed: api.alternative.me/fng (free, no key)
- BTC Dominance + Market Cap: api.coingecko.com/api/v3/global

### Files
- index.html  — Full PWA app (single file, no build needed)
- manifest.json — App name, icon, install config
- sw.js        — Service worker (offline support)
- vercel.json  — Vercel routing config
- icon-192.svg — Home screen icon (small)
- icon-512.svg — Home screen icon (large)

### Next Steps to Monetize
1. Add user login (Auth0 free tier)
2. Add subscription paywall (Stripe)
3. Submit to App Store as React Native app
4. Charge $29/month
