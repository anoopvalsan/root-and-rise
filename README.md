# Root & Rise

A responsive yoga centre website inspired by the supplied frosted-glass reference. Built with semantic HTML, CSS, and vanilla JavaScript. No build step or runtime dependencies.

## Preview

Run `python3 -m http.server 8080` in this directory and open http://localhost:8080.

## Hosting

Deploy with GitHub Pages from the `main` branch, root directory. `CNAME` sets `yoga.zedqhub.com`. Configure DNS as a CNAME record named `yoga` pointing to `anoopvalsan.github.io`.

## Features

Responsive layout, frosted glass panels, coordinated entrance motion, floating panels, reduced-motion support, practice detail dialogs, keyboard-accessible navigation, one-minute breathing exercise, FAQs, and a private enquiry composer with copy/download.

## Before accepting bookings

The owner has not provided contact details, actual class schedule, or pricing. Practice descriptions are proposed content. The enquiry composer clearly states that nothing is sent and no booking is made. Connect a verified contact or booking service before using this as a booking channel.

## Assets

Photography generated with the built-in ImageGen tool. Prompt: “Premium editorial yoga photography asset sheet, six studio photographs with identical light cool gray backgrounds: Indian woman in black yoga clothing standing in calm profile, seated lotus, warrior two, tree, camel, and rear-view mountain meditation at sunrise; realistic anatomy, natural soft lighting, no text or graphics.” Cropped and saved as six optimized WebP files in `assets/`. Logo drawn as SVG. Font: DM Sans via Google Fonts; system sans-serif fallback.

## November visual update

Replaced generic symbols with animated inline SVG lotus, meditation, tree pose, mudra and breath icons. Added transparent studio image cutouts and a stronger breathing pulse with a separate hover/focus ripple animation. Reduced-motion preferences disable movement.

Background extraction used the built-in ImageGen tool with this prompt: “Remove all light gray studio backgrounds behind the five women, preserve poses, faces, clothing, scale and positions; preserve the mountain photograph; keep the exact 1536×1024 canvas and six-cell layout; output genuine transparency.” Final transparent assets are `assets/*-cutout.webp`.
