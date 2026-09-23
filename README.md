# ai-tech-portal

The **sortInc.** homepage — LLM &amp; applied AI engineering, Seoul.

🔗 **<https://sort-tech.github.io/ai-tech-portal/>**

## What this is

A single-file homepage. One `index.html`, no build step, no `node_modules`, no framework —
Tailwind via CDN and about 40 lines of vanilla JS for the scroll reveal and the project filter.
Served straight from GitHub Pages.

It covers what we build (LLM gateways with governance, knowledge graphs and RAG, multimodal
vision pipelines, digital twins, offline-first geospatial stacks), how we work, and links to
the public code behind it at [github.com/sort-tech](https://github.com/sort-tech).

## Run it locally

Open the file, or serve it:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Editing

Everything lives in [`index.html`](index.html). The edit points are listed in a comment at the
top of the file — display name, contact email and GitHub org. Sections are marked with banner
comments (`CAPABILITIES`, `OPEN SOURCE`, `WORK`, `STACK`, `PROCESS`, `ABOUT`, `CONTACT`).

Colours are Tailwind theme tokens in the inline `tailwind.config` block: `accent`, `accent2`
and the `ink` scale.

## License

© sortInc. Content and branding are not open source; the layout is yours to learn from.
