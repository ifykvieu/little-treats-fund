# Little Treats Fund ♡

A cute pastel family fundraising mini-site. Pure HTML/CSS/JavaScript; no backend required.

## Customize
Open `index.html` and find `EDIT YOUR DETAILS HERE`.
Update:
- `goal`, `raised`
- `bank`, `owner`, `number`, `memo`
- `items` (names, descriptions, prices, emoji, colors)
- `qr` (the image filename)

To add your real bank QR:
1. Save your bank QR image in this same folder, e.g. `my-qr.png`.
2. Change `qr: "qr-placeholder.svg"` to `qr: "my-qr.png"`.

## Publish with GitHub Pages
1. Sign in at https://github.com/ and create a new repository (e.g. `little-treats-fund`).
2. Choose **Public** if using GitHub Pages on a free GitHub account.
3. Upload `index.html`, `qr-placeholder.svg`, and your QR image if used.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose branch `main`, folder `/ (root)`, then **Save**.
7. Wait a few minutes. Your site URL will look like:
   `https://YOUR-USERNAME.github.io/little-treats-fund/`

## Privacy
A public repository exposes its files and website contents. Only publish bank details and QR code if you are comfortable sharing them publicly. Never publish passwords, OTPs, login credentials, or identity documents.

The fundraising progress is manual: update `raised` in CONFIG when you want to reflect new contributions. The site does not connect to your bank or verify transfers.
