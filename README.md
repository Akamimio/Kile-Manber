# Kile Manber

Lightweight, offline-ready English arcade driving game. Dodge cars, collect stars, and beat your high score.

## Play
- Desktop: Left/Right arrows or A/D to steer; P or Space to pause.
- Touch: Use LEFT and RIGHT buttons.
- Avoid other cars. Collect stars for +75 points.

## GitHub Pages
1. Create a public GitHub repository named `kile-manber`.
2. Upload **all files and the `icons` folder** from this package to the repository root.
3. Go to **Settings > Pages > Build and deployment**. Select **Deploy from a branch**, **main**, **/(root)**, then Save.
4. Open `https://YOUR-USERNAME.github.io/kile-manber/` once Pages finishes deploying.
5. Check the page, controls, manifest and offline loading before packaging.

## Microsoft Store packaging
Use [PWABuilder](https://www.pwabuilder.com/) with the deployed HTTPS GitHub Pages URL. Choose Windows and generate the Windows package. Follow PWABuilder's current signing and submission guidance, then submit the package in Microsoft Partner Center. Store approval is not guaranteed.

## Tech
HTML5 Canvas, vanilla JavaScript, CSS, Web App Manifest, Service Worker. No external dependencies. Local best score saved on device.
