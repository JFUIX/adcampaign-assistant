<div align="center">

# Ad Campaign Assistant

**Plan smarter creative tests. Make clearer sense of campaign data.**

A lightweight AI-assisted marketing prototype for campaign ideation and structured review of campaign screenshots or performance notes.

[Overview](#about-the-project) · [Problem](#problem-it-addresses) · [Features](#key-features) · [Tech stack](#technology-stack) · [Screenshots](#screenshots) · [Live demo](#live-demo)

</div>

---

## About the Project

Ad Campaign Assistant brings two early-stage marketing workflows into one simple interface: planning a campaign and reviewing campaign information.

The planning flow collects a product or service, target audience, objective, budget range, and selected platforms. It then helps organize creative angles, headline options, ad formats, landing-page considerations, and a testing checklist.

The review flow accepts campaign screenshots and/or written notes, organizes visible metrics and comment themes, and surfaces possible explanations, missing context, and useful next steps.

## Problem It Addresses

Campaign planning and performance reviews can become fragmented across briefs, notes, screenshots, and spreadsheets. This prototype explores a lightweight way to structure the first round of thinking, keep creative testing intentional, and distinguish visible evidence from assumptions.

It is a decision-support starting point, not an advertising platform or a source of guaranteed performance predictions.

## Key Features

### Campaign Planner
- Collects product/service, audience, campaign objective, budget range, and platforms
- Suggests creative angles and headline variations through the configured AI integration
- Organizes ad-format and landing-page considerations
- Produces a practical testing checklist

### Campaign Data Review
- Accepts screenshots and/or pasted campaign notes
- Organizes visible numbers and comment themes
- Highlights possible explanations and data gaps
- Suggests follow-up questions and next steps
- Avoids treating limited comments or incomplete screenshots as proof of broad public opinion

## Technology Stack

- **HTML5** — application structure and forms
- **CSS3** — responsive interface and light/dark color schemes
- **JavaScript** — client-side interactions and workflow logic
- **External AI integration** — generation depends on the Claude access integration available in the hosting environment

The interface is contained in a single `index.html` file.

## Screenshots

### Campaign Planner

![Campaign planner interface](screenshots/campaign-planner.svg)

### Campaign Data Review

![Campaign data review interface](screenshots/data-review.svg)

## Live Demo

[Open Ad Campaign Assistant](https://jfuix.github.io/adcampaign-assistant/)

The static page can load independently, but AI generation requires the external Claude integration to be available in the hosting environment. Availability may differ between environments and visitors.

## Run Locally

```bash
git clone https://github.com/JFUIX/adcampaign-assistant.git
cd adcampaign-assistant
```

Open `index.html` in a modern browser. The interface can be explored locally; AI generation works only when the required integration is configured and accessible.

## Project Status & Limitations

**Status:** Prototype.

- It does not connect directly to Meta, Google, TikTok, or other advertising accounts.
- It does not fetch live campaign metrics.
- Analysis is limited to the screenshots and text supplied by the user.
- AI generation depends on an external Claude integration and is not guaranteed to work in a standalone local session.
- Suggestions are hypotheses and starting points to test, not performance forecasts or guarantees.
- Users should verify extracted metrics and review recommendations before acting on them.

## Credits

Designed and developed by [JFUIX](https://github.com/JFUIX).
