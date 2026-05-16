# Bill's Cleaning Service Website

This repository contains the source code for the professional website of Bill's Cleaning Service.

## Features
- **Responsive Design:** Mobile-friendly layout using Tailwind CSS.
- **Service Sections:** Detailed breakdown of residential, deep, move-in/out, and commercial cleaning.
- **Interactive FAQ:** Common questions answered in an accordion format.
- **Booking Form:** Integrated contact form with validation and success feedback.
- **Localization:** Focused service area (Valparaiso, Chicago, Lockport, Joliet).

## Technology Stack
- **HTML5/JavaScript**
- **Tailwind CSS** (via CDN)
- **FontAwesome** (for iconography)

## Local Development
To view the website, simply open `index.html` in any modern web browser.

## Verification
Automated verification is performed using Playwright.
Tests are located in the `verification/` directory.
To run tests:
```bash
pytest verification/verify_site.py
```
