# StudyNest — Assignment Lab 2

A simple student dashboard built **only with HTML and CSS**. No frameworks, JavaScript, or dependencies.

## Lab 2 requirements

1. **Responsive breakpoints:** mobile 1 column, tablet 2 columns (`min-width: 640px`), desktop 3 columns (`min-width: 1024px`).
2. **Component library:** labelled text input, select dropdown, textarea, interactive buttons, success/info alert, CSS-only modal using `:target`.
3. **Automatic dark mode:** `@media (prefers-color-scheme: dark)`.
4. **Accessibility:** semantic headings, labels, focus indicators, skip link, readable contrast, responsive content. Lighthouse score must be *measured*, not assumed.

## Run

Open `index.html` in Chrome. No installation needed.

## Publish to a NEW GitHub repo

1. Create a new public repo on GitHub (example: `assignment-lab2-studynest`).
2. Extract the ZIP, then upload `index.html`, `style.css` and `README.md` into the **root** of that repository (not an extra nested folder).
3. Commit the uploaded files.
4. Open repository **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**; select **main** and **/(root)** and click **Save**.
5. Wait a few minutes, then open the URL shown in Pages settings.

## Verify the assignment

1. In Chrome, open the GitHub Pages site.
2. Press **F12**, go to **Lighthouse**, select **Accessibility**, choose **Mobile** and run **Analyze page load**.
3. Confirm the Accessibility score is **above 90**, or fix the warnings and rerun. Take a screenshot of the score for evidence.
4. In Chrome DevTools use the device toolbar (**Ctrl+Shift+M**) to check phone, tablet and desktop layouts.
5. Use device system settings to confirm the light/dark theme.
6. Click **How it works** / **Open modal** and verify the CSS-only dialog opens and closes.

> This is a front-end demonstration. Form validation is done by the browser; no task data is saved to a server. Modal is CSS only, so it cannot provide all advanced focus-management features of a scripted dialog.
