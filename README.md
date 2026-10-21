# Amex Tracker – home-screen wrapper

This small site gives Amex Tracker a proper app icon and opens it full-screen.
Your data and your Apps Script link are **not** stored here. Each phone asks for the link once and keeps it on that phone.

## Put it on GitHub Pages (free, about 10 minutes)
1. Sign up at github.com (free).
2. Click **+ → New repository**. Name it `amex-tracker`, choose **Public**, then click **Create repository**.
3. Click **uploading an existing file**. Drag in **everything in this folder** (including `icon-options`), then click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, set **main / (root)**, then click **Save**.
5. Wait 1–2 minutes. Your site will be at `https://YOUR-USERNAME.github.io/amex-tracker/`.

## Install on each phone
- **Android (Chrome):** open the site, then tap ⋮ → **Install app** (or **Add to Home screen** → **Install**).
- **iPhone (Safari):** open the site, then tap Share → **Add to Home Screen** → **Add**.
- Open the new icon. On the first launch, paste your working Apps Script link (the `a/~/…/exec` one) and tap **Connect**.

## Change the icon
The default is option A. To switch, copy the 5 files from `icon-options/B` or `icon-options/C` into the main folder, overwriting the old ones, and commit.
Then remove and re-add the home-screen icon on each phone.

## Change the Apps Script link later
Open `https://YOUR-USERNAME.github.io/amex-tracker/#reset` and paste the new link.
