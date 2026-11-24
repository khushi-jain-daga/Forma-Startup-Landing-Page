# Forma — Startup Landing Page

Experiment 02: a responsive landing page prototype for Forma, a fictional team-workspace startup.

## Student

- **Name:** Khushi Jain Daga
- **Roll number:** 23bcon1665

The website shows the student attribution in the top navigation and footer.

## Project description

Forma presents a calm, premium workspace concept using a sage, cream, and forest-green palette. The page includes a product dashboard demo, feature overview, illustrative customer perspective, pricing plans, and an early-access form.

## Technologies

- HTML5
- CSS3
- Bootstrap 5.3.6 (bundled locally)
- Vanilla JavaScript
- Browser `localStorage` for demo form entries

No package installation, API key, or external service is required.

## Features

- Responsive navigation and layout
- Interactive task dashboard with live completion counts and progress
- Monthly/yearly pricing switch
- Pricing-plan selection from calls to action
- Validated demo form with local-only storage and feedback
- Persistent student attribution in the navigation and footer

This is an academic prototype. Product, testimonials, and prices are illustrative; the form does not send email or collect payments.

## Architecture

See [architecture.svg](architecture.svg) for the project flow:

1. Business requirements and design planning
2. Semantic HTML and Bootstrap responsive layout
3. Custom CSS styling
4. JavaScript interactions and local storage
5. Responsive landing page verification

## Project files

```text
index.html
style.css
script.js
architecture.svg
assets/
  bootstrap.min.css
  bootstrap.bundle.min.js
screenshots/   (currently empty; no screenshots were available)
```

## Run locally

Open `index.html` directly in a modern browser, or start a local server from this directory:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Verification

The page was opened and checked in a browser at viewport widths of 320, 390, 576, 768, and 1440 pixels. The student label remained visible without overlapping the brand or navigation toggle, and no horizontal overflow was detected. The mobile navigation, task counters, and yearly pricing switch were also exercised.

## Academic notes

**Objective:** Build a responsive startup landing page using Bootstrap, HTML, CSS, and JavaScript.

**Limitations:** Forma is fictional. Form entries stay in the current browser's local storage; there is no backend, email delivery, payment processing, or real SaaS service.

**Concepts demonstrated:** Bootstrap grid and breakpoints, semantic HTML, DOM events, form validation, and browser local storage.
