# Roast & Co. Coffee Website

A responsive coffee shop website built with plain HTML, CSS and JavaScript. No frameworks, no build step, and no installs: just open `index.html`.

**Live site:** https://ronywaswa.github.io/YOUR-REPOSITORY-NAME/

## Features

- Responsive layout that works on phones, tablets and desktops
- Mobile hamburger menu and a sticky header that highlights the current section
- Menu with category filters (All, Hot, Cold, Bakery)
- Order panel with item totals and a "Send order on WhatsApp" button
- Contact form with simple validation
- Sections that fade in as you scroll
- All cafe details (name, phone, email, address, hours) set in one place

## Getting started

1. Download or clone the repository:
   ```
   git clone https://github.com/ronyWaswa/YOUR-REPOSITORY-NAME.git
   ```
2. Open the folder in VS Code.
3. Right-click `index.html` and choose **Open with Live Server** (install the Live Server extension first), or double-click the file to open it in your browser.

## Customize it

Open `index.html`, press **Ctrl+F**, search for `var CAFE_NAME`, and edit the settings at the top of the script:

```js
var CAFE_NAME = "Roast & Co.";
var EMAIL = "waswarony70@gmail..com";
var PHONE = "0790626555";
var ADDRESS = "01300 Kutus-Kerugoya Road, Kutus Kirinyaga, Kenya";
var HOURS = "Open Monday to Saturday, 7:00 AM to 10:00 PM";
var CURRENCY "KES";
var WHATSAPP = "254790626555";
```


## Project structure

```
.
├── index.html   # the whole site: HTML, CSS and JavaScript
└── README.md    # this file
```

## Deploy with GitHub Pages

1. Push the files to your GitHub repository.
2. Go to **Settings > Pages**.
3. Under **Source**, choose **Deploy from a branch**, select **main** and **/ (root)**, then click **Save**.
4. After a minute or two the site is live at `https://ronywaswa.github.io/YOUR-REPOSITORY-NAME/`.

## Built with

- HTML5
- CSS3 (Grid, Flexbox, media queries)
- JavaScript (no libraries)
- Google Fonts: Fraunces and DM Sans

## Author

Made by Rony Waswa. Questions or suggestions? Open an issue on this repository.
