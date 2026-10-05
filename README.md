# TechNotes – Accessibility Enhancement (Week 3)
- `before/` – original page with deliberate accessibility flaws
- `after/` – remediated page (WCAG 2.1 AA, semantic HTML, ARIA, keyboard support)

## How to audit
Open each `index.html` in Chrome, run Lighthouse (Accessibility) and the WAVE extension, record scores in the report.

## Key fixes
Semantic landmarks, one h1 and logical headings, skip link, real `<button>`/`<a>` elements, labelled inputs,
`aria-expanded`, `aria-live` status, `aria-invalid` + `aria-describedby` errors, visible focus, AA contrast, `lang` attribute.
