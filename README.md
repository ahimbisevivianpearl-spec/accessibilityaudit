
# Week 2 Competency Evidence — Accessibility Audit

### Issue 1: Missing Image Alt Text
* **Who is Affected:** Screen reader users (visually impaired).
* **The Barrier:** Screen readers cannot describe images without alt text.
* **Practical Recommendation:** Add `alt="description"` attributes to all images.

### Issue 2: Low Color Contrast
* **Who is Affected:** Visually impaired and colorblind users.
* **The Barrier:** Light text on light backgrounds is impossible to read.
* **Practical Recommendation:** Use high-contrast colors matching WCAG standards.

### Issue 3: Unlabeled Form Inputs
* **Who is Affected:** Screen reader users.
* **The Barrier:** Users don't know what to type in a text box if it lacks a label.
* **Practical Recommendation:** Add `<label>` elements to all form fields.

### Issue 4: Missing Keyboard Focus
* **Who is Affected:** Keyboard-only users.
* **The Barrier:** Users cannot see which element is currently highlighted when using the Tab key.
* **Practical Recommendation:** Add visible CSS outline styles on `:focus`.

### Issue 5: Broken Heading Hierarchy
* **Who is Affected:** Screen reader users.
* **The Barrier:** Skipping heading levels (e.g., H1 to H4) makes page layout confusing.
* **Practical Recommendation:** Use headings sequentially (H1, H2, H3).