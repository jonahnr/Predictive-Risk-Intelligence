# Parallax Operational Intelligence Engine Page

Standalone customer-facing web section for Parallax Data Lab. The page positions the offering as the intelligence engine behind predictive and directional operational digests, with the linked digest serving as the executive-facing output.

## Purpose

This page explains how operational signals become leadership attention items:

- Operational signal collection
- Pattern detection engine
- Predictive risk modeling
- Intervention prioritization
- Executive intelligence delivery

The copy is intentionally broader than worker safety so the page can apply across safety, compliance, quality, service, workflow, field operations, and other operational risk contexts.

## Files

- `index.html` - Page content, navigation, CTAs, section anchors, and expandable detail sections.
- `styles.css` - Parallax visual system, responsive layout, cards, bullets, and section styling.
- `script.js` - Canvas signal background, pointer-based motion, and reveal behavior.
- `assets/` - Local visual assets used by the page.

## Key Links

Primary digest CTA:

- `https://jonahnr.github.io/worker-safety-digest/`

Top navigation:

- Home: `https://parallax-data.webflow.io/`
- How We Help: `https://parallax-data.webflow.io/how-we-help`
- Intelligence Lab: `https://parallax-data.webflow.io/intelligence-lab`
- Our Offerings: `https://parallax-data.webflow.io/our-offerings`
- About: `https://parallax-data.webflow.io/about`

## Local Preview

From this folder, run:

```powershell
python -m http.server 8011
```

Then open:

```text
http://127.0.0.1:8011/index.html
```

## Section Anchors

The five flow cards near the top link directly to:

- `#signal-collection`
- `#pattern-detection`
- `#predictive-modeling`
- `#intervention-prioritization`
- `#executive-delivery`

Each section includes an expandable `What this can look like` breakout to help customers picture the inputs, logic, and outputs in their own operating environment.

## Design Notes

- Keep the page in the Parallax dark-blue, electric-blue, and gold visual language.
- Keep customer-facing copy focused on business clarity, operational risk movement, and executive attention.
- Avoid making this read like a separate dashboard product. It should support the digest as the underlying intelligence engine.
- Use clean bullets and structured lists instead of fake image-icon grids for the input/output examples.
