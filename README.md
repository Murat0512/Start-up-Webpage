# Startup_Files

This folder contains a simple landing page for a startup event. It uses Bootstrap, a Google Font, and a custom stylesheet, all linked from [index.html](index.html).

## What is used

- HTML: [index.html](index.html)
- Custom CSS: [style.css](style.css)
- Bootstrap 5.3.8 (CSS and JS bundle) via CDN
- Google Font: Montserrat via Google Fonts CDN
- Background image: `header.jpg` referenced in [style.css](style.css)

## How it is linked

- Bootstrap CSS is linked in the `<head>` of [index.html](index.html).
- Google Fonts is linked in the `<head>` of [index.html](index.html).
- Custom CSS is linked in the `<head>` of [index.html](index.html) as `style.css`.
- Bootstrap JS bundle is loaded at the end of the `<body>` in [index.html](index.html).
- The call-to-action button links to the Mailchimp signup page.

## Notes

- Keep `header.jpg` in the same folder so the background image loads correctly.
