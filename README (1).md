# AL-Amine.io — publish guide

This folder is the finished website AND an installable app (PWA). Upload the whole folder to any HTTPS web host.

## Files
- index.html — the whole website
- manifest.webmanifest, sw.js, icons/ — make it installable as an app and work offline
- robots.txt

## 1. Publish the website (free, easiest first)
**Option A — Netlify Drop (no account setup tricks):**
1. Unzip this file. 2. Go to https://app.netlify.com/drop (use a computer, or "Desktop site" in your phone browser). 3. Drag the unzipped folder in. 4. You get a free https link. Open it and test it.

**Option B — Cloudflare Pages or GitHub Pages:** upload the same files. Both are free.

The install features only work on the https link, not on a file opened from your phone storage.

## 2. Use your own name (al-amine.io)
1. Buy the domain from a domain seller (a .io domain is paid every year; prices vary).
2. In Netlify: Domain management → Add a domain → follow the DNS records it shows you, and enter them at the seller.
3. HTTPS turns on automatically after DNS updates (can take from minutes to a day).
Do not tell customers the domain works until you have opened it yourself.

## 3. The app on phones
**Free, works today (Android and iPhone):** open your https link.
- Android (Chrome): tap the "Install app" button on the site, or menu → Install app.
- iPhone (Safari only): Share → Add to Home Screen.
It then opens full-screen with the AL icon, like an app.

**Real Android app file (APK/AAB), free tool:** go to https://www.pwabuilder.com, enter your live https link, choose "Package for Stores" → Android. Download the files. The APK can be installed directly; the AAB is for Google Play (a Google Play developer account has a one-time fee; check the current price).

**Real iPhone App Store app:** needs an Apple Developer account (paid yearly) and a Mac or a cloud build service. PWABuilder can also prepare the iOS project. Until then, Add to Home Screen is the iPhone option.

## 4. Change prices or text later
Open index.html in a text editor. Prices are in the block marked CONFIG and the PR list near the top of the script. Upload the folder again. If phones keep showing the old version, change "alamine-v1" to "alamine-v2" in sw.js before uploading.

## 5. Check before you share
- Open the link on a phone, switch languages, order a service, confirm WhatsApp opens with your message.
- Not included: accounts, online payments, file uploads, admin area, real testimonials. Payments are done by MTN MoMo as written on the page.
