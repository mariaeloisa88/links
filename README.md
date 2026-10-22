# My Links Page

A simple, free, and privacy-conscious landing page that brings all my online profiles, blogs, shop, and projects together in one place.

One page. One QR code. All my links.

Live View: [Click here](https://mariaeloisa88.github.io/links/)

## Purpose

I wanted a single QR code that opens a webpage containing clickable links to my online destinations. Instead of generating and managing a separate QR code for every platform, I can share one code that leads people to all my links.

## Features

- Free static website hosting through GitHub Pages
- One landing page for multiple online destinations
- Clickable links to external websites
- Mobile-friendly layout
- No visitor accounts required
- No database or custom visitor-data collection
- No third-party analytics, tracking scripts, or external libraries
- Easy to update by editing the HTML file
- Compatible with static QR codes generated using [Honest QR Code](https://honestqrcode.com/)

## Built With

- HTML5
- CSS3
- GitHub Pages
- [Honest QR Code](https://honestqrcode.com/) for QR code generation

## How It Works

1. GitHub Pages hosts the static landing page.
2. Visitors scan the QR code using their phone's camera.
3. The QR code opens the landing page.
4. Visitors select the link they want to open.
5. Each link directs them to its actual destination.

The QR code contains the landing page URL directly. It does not depend on a paid QR redirection service.

## Project Structure

```text
links/
├── index.html
└── README.md
```

- `index.html` contains the landing page and its styling.
- `README.md` documents the project.

## Updating Links

To add, remove, or change a destination:

1. Open `index.html`.
2. Edit the relevant link label or URL.
3. Commit the changes to the repository.
4. Wait for GitHub Pages to publish the update.

As long as the landing page URL remains unchanged, the existing QR code will continue to point to the page.

## Privacy Considerations

This project does not intentionally collect visitor information or use a database, analytics scripts, or custom tracking code.

The landing page is publicly accessible. GitHub operates the hosting infrastructure and may process or retain technical information, such as server logs, according to its own policies.

Only publish information and links intended for public access.

## Cost

The project is designed to run without a paid QR code subscription, a custom domain, or a database. GitHub Pages availability and usage remain subject to GitHub's current plan terms and limits.

## Future Improvements

Possible enhancements, if they become useful:

- Add more online destinations
- Improve accessibility and visual customization
- Add a custom domain
- Create downloadable QR code assets for different uses

The goal is to keep the project simple and maintainable rather than add features without a real need.

---

Built to solve a personal problem first. Shared in case it helps someone else.
