# Accessibility Audit Report

## Page Audited
`index.html`

## Issues Found & Resolved
1. **Missing Image Alt Attributes:**
   - *Issue:* `<img>` tag lacked a descriptive `alt` attribute.
   - *Fix:* Added `alt="Profile placeholder image"` so screen readers can describe the image.

2. **Heading Hierarchy Skipping:**
   - *Issue:* Heading structure skipped levels.
   - *Fix:* Structured headings sequentially (`<h1>` followed by `<h2>`).

3. **Non-descriptive Link Text:**
   - *Issue:* Generic link labels were present.
   - *Fix:* Used descriptive anchor text such as "Lamborghini Official Website".

4. **Missing HTML Language Attribute:**
   - *Issue:* `<html>` tag lacked a language specification.
   - *Fix:* Added `lang="en"` to the `<html>` root element.

## Final Lighthouse Score
**Accessibility Score:** 100 / 100