## 2026-03-15 to 2026-03-27 - Archival UX Lessons
**Learning:** Sensitive digital archives require high-density, accessible layout structures. Inline scroll HTML spans in headings break standard Markdown parsers; use clean Markdown headings with standalone target anchors, direct `tel:`/`sms:` links, underlined access keys (`<u>A</u>`), and list dual-platform shortcuts.
**Action:** Keep headings clean of nested inline HTML tags, highlight key letters, and dual-format helplines.

## 2026-03-28 - Semantic Archive Downloads & Landmarks
**Learning:** Primary download actions in README documents should use HTML anchors with explicit file-size/format labels, descriptive `download` names, and underlined `accesskey` labels. Wrapping quick-navigation arrays in `<nav>` landmarks with `aria-hidden` emoji spans provides screen-reader users with clean, discoverable structural landmarks without redundant audible clutter.
**Action:** Replace plain Markdown links for primary CTAs and navigation panels with semantic `<nav>` wrappers and fully annotated HTML anchors.
