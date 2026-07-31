## 2026-03-15 to 2026-03-27 - Archival UX Lessons
**Learning:** Sensitive digital archives require high-density, accessible layout structures. Inline scroll HTML spans in headings break standard Markdown parsers; use clean Markdown headings with standalone target anchors, direct `tel:`/`sms:` links, underlined access keys (`<u>A</u>`), and list dual-platform shortcuts.
**Action:** Keep headings clean of nested inline HTML tags, highlight key letters, and dual-format helplines.

## 2026-03-28 - Semantic Archive Downloads & Landmarks
**Learning:** Primary download actions in README documents should use HTML anchors with explicit file-size/format labels, descriptive `download` names, and underlined `accesskey` labels. Wrapping quick-navigation arrays in `<nav>` landmarks with `aria-hidden` emoji spans provides screen-reader users with clean, discoverable structural landmarks without redundant audible clutter.
**Action:** Replace plain Markdown links for primary CTAs and navigation panels with semantic `<nav>` wrappers and fully annotated HTML anchors.

## 2026-03-29 - Accessible Crisis Helplines & Global Top-Return Navigation
**Learning:** Standard inline markdown links (`[]()`) for brief visual actions (like "Call 988" or "Text HOME") fail to provide screen reader users with necessary context. Standardizing support links as fully qualified HTML anchor elements with explicit `aria-label` tags prevents ambiguous screen-reader announcements. Furthermore, integrating an interactive global top-return link utilizing a classic underlined accesskey (e.g., `accesskey="t"` for "Back to <u>t</u>op") creates a cohesive, keyboard-first navigation loop.
**Action:** Always provide explicit, context-rich ARIA labels for short interactive visual actions and provide dedicated back-to-top accesskey shortcuts.

## 2026-03-30 - Native Tooltip Enhancements & Contextual Discoverability
**Learning:** Native `title` attributes on semantic HTML elements complement robust `aria-label` tags by offering descriptive, on-hover desktop tooltips. This is extremely helpful for explaining keyboard `accesskey` shortcuts (e.g., "Shortcut: A") and download size details to mouse-based users, bridging the gap between keyboard-first landmarks and modern visual pointer interfaces.
**Action:** Always enrich primary accesskeys and download links with descriptive `title` attributes to serve both screen-reader and pointer-device users.
