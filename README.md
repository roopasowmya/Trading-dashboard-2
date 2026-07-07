# Trading Command Center

A single-page dashboard: live world clocks (India/UK/US), Forex session status (Sydney, Tokyo, London, New York), and custom countdown timers.

It's one static file (`index.html`) — no build step, no dependencies.

## Deploy from your phone (no laptop needed)

### 1. Push to GitHub from your phone
1. Open **github.com** in your phone browser and log in.
2. Tap **+** (top right) → **New repository**. Name it e.g. `trading-command-center`. Create it.
3. On the new repo page, tap **Add file → Upload files**.
4. Upload `index.html` (and this `README.md`) from your phone's downloads.
5. Scroll down, tap **Commit changes**.

### 2. Deploy on Vercel
1. Open **vercel.com** and log in with your GitHub account.
2. Tap **Add New → Project**.
3. Select the `trading-command-center` repo you just created.
4. Leave settings as default (it's a static site, no framework/build command needed) and tap **Deploy**.
5. Vercel gives you a live URL like `trading-command-center.vercel.app` — open that on your laptop, no code needed there.

Any time you edit `index.html` on GitHub (mobile web editor works fine) and commit, Vercel auto-redeploys.
