# AnswerLM Domain Analyzer

AnswerLM is a single-page domain opportunity analyzer. It scores a domain, classifies the likely business category, recommends use cases, and adds a practical business-manager layer for turning the domain into a revenue test.

## Features

- Client-side domain scoring
- Domain normalization for URLs, subdomains, and common multi-part TLDs
- Keyword detection with overlap handling
- Category classification:
  - lead-gen
  - local-services
  - content
  - ecommerce
  - saas
  - brandable
- Business manager insights:
  - Hidden Business
  - Customer/Audience
  - First Offer To Test
  - First $1,000 Plan
  - 90-Day Value Builder
  - Strategic Risk
  - Manager Note
- Dark mode
- Feedback modal
- Beta signup section
- Plausible analytics hook

## Run Locally

Open `index.html` in a browser.

No build step is required.

## Deploy

This project can be hosted as a static site on GitHub Pages, Netlify, Vercel, or any basic static file host.

For GitHub Pages:

1. Push this folder to a GitHub repository.
2. In the repository settings, enable Pages.
3. Choose the branch and root folder that contain `index.html`.

## Notes

The app is currently a static HTML file with embedded CSS and JavaScript. Future production work should consider moving feedback and beta signup submissions to a backend or form service.
