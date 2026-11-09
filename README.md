# AppSec Portfolio

A responsive cybersecurity portfolio website for presenting web application security work, case studies, methodology, and contact details. Built with plain HTML, CSS, and JavaScript so it is easy to customize and host.

## Run locally

Open `index.html` in a browser, or run a static server:

```bash
python -m http.server 8000
```

Visit `http://localhost:8000`.

## Make it yours

Update the visible placeholders in `index.html` before publishing:

- `[YOUR CITY]`
- `YOUR.EMAIL@example.com`
- About copy and skill list
- Project cards: link to your actual labs, reports, write-ups, repositories, or authorized assessments

The cards are illustrative project concepts, not claims that assessments were performed. List only experience and tools you can confidently discuss. Sanitize reports: remove client names, credentials, personal data, and details outside your authorization.

## Structure

- `index.html` — accessible page content and sections
- `styles.css` — responsive design and reduced-motion support
- `script.js` — mobile navigation toggle

## Security notes

This static starter does not collect data or make requests to target applications. Before adding a contact form or analytics, review collected data, retention, consent, and provider security. For production, serve over HTTPS and configure appropriate response headers at the hosting layer.

## License

MIT. See `LICENSE`.
