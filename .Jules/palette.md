## 2026-06-25 - The "Caring Archive" & Accessible Dual-Access
**Learning:** Sensitive static archives benefit from the "README-as-UI" pattern, pairing technical metadata with proactive emotional support. Providing an "Engagement Choice" (Preview vs. Download) improves UX by allowing verification before download, provided "Preview" links are explicitly labeled (e.g., via ARIA) for their new-tab behavior to maintain screen-reader predictability.
**Action:** Use "README-as-UI" for archives and always offer labeled dual-access (Preview/Download) for primary assets.

## 2026-06-25 - GitHub Anchor Slugification & Navigation
**Learning:** GitHub's automatic anchor generation for headers with emojis (e.g., `## ⚠️ Content Warning`) strips the emoji and most punctuation. Internal navigation links must match these stripped slugs (e.g., `#content-warning` instead of `#-content-warning`) to be functional.
**Action:** Always verify internal README links by manually testing or confirming against GitHub's slugification rules.
