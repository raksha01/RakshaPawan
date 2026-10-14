# Raksha & Pawan — Wedding Invitation

A responsive, mobile-friendly static wedding invitation website for GitHub Pages.

## Included files
- `index.html` — complete website, styling, animations, countdown, RSVP setup, and music control
- `assets/radha-krishna.jpeg` — opening image copied unchanged from the uploaded image
- `assets/couple-wedding.jpeg` and `assets/couple-candid.jpeg` — couple photos
- `assets/wedding-music.mp3` — optional; add your chosen licensed MP3 to enable background music

## Opening experience
The Radha-Krishna image is the full-screen opening screen. The image file itself is unchanged. When a visitor clicks **Enter the invitation**, the image receives a slow cinematic zoom, then the invitation fades in and the page scrolls smoothly into it. Reduced-motion settings are respected.

## Preview locally
Extract the ZIP and open `index.html` in a modern browser. For best results, preview using a simple local web server, though direct opening should work in most browsers.

## Customize before sharing
- Confirm all wedding details, especially venue/address and reception timing.
- Replace the Mehendi, Haldi, and Wedding ceremony placeholders.
- To enable music, add an MP3 named `wedding-music.mp3` inside `assets/`. Music is attempted after the visitor clicks the opening button; browser settings may require pressing Play.
- To enable WhatsApp RSVP, set `WHATSAPP_NUMBER` in `index.html` to digits only with country code, e.g. `919876543210`.

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and the entire `assets` folder to the repository root (keep the folder and filenames unchanged).
3. Open **Settings → Pages**.
4. Under build/deployment, select **Deploy from a branch**, choose branch `main` and folder `/(root)`, then Save.
5. Wait for GitHub Pages to publish and open the URL shown in the Pages settings.

The website will be public when published. Share only photos and contact details you are comfortable making public.
