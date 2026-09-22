# Sustainability Tools

A collection of lightweight, browser-based tools for sustainability
reporting and communications. No backend, no build step, no dependencies —
each tool is a single HTML file that runs entirely client-side.

## Tools

### CSRD / ESRS Report Draft Generator
`csrd-generator/index.html`

A structured first-draft generator for CSRD sustainability statements,
organized by ESRS topical standard (General Disclosures, E1–E5, S1–S4, G1).
Users fill in a form per standard; the tool compiles the inputs into a
formatted report with a cover page, flags missing required fields, and
exports to PDF via the browser's print function.

**What it does:**
- Covers a representative set of commonly reported disclosure requirements
  per ESRS topical standard
- Tracks completion progress across all 11 sections
- Generates a formatted report view with a designed cover page
- Exports to PDF via print (no external PDF library required)

**What it isn't:** a compliance filing tool. It does not cover the full
mandatory datapoint set under CSRD (which runs to hundreds of items), and
output has not undergone assurance. It's a working first draft, meant to
be reviewed by a qualified sustainability or assurance professional before
publication — the tool states this directly in the generated report.

**Live demo:** [add your GitHub Pages link here once enabled]

## Roadmap

Planned additions: a GRI-aligned report generator, a B Corp Impact
Assessment draft tool.

## Tech

Vanilla HTML/CSS/JS. No frameworks, no build step, no backend — each tool
is a single file that can be opened directly or hosted via GitHub Pages.

---
Built by [Luchi López Noriega](https://github.com/thislucha)
