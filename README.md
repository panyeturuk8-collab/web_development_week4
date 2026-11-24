# SpendWise Dashboard Shell

A responsive static layout shell for the **SpendWise** personal finance capstone project, built with HTML5, CSS Grid, and Flexbox without JavaScript or layout `position: absolute`.

## Project Structure

- **`index.html`**: Defines the semantic dashboard structure, including the navigation sidebar, top header with summary metrics, and six category cards (*Food & Groceries*, *Transport*, *Rent & Housing*, *Entertainment*, *Savings*, and *Utilities*).
- **`style.css`**: Implements the page and card grid layouts, Flexbox alignment inside the header, sidebar items, and cards, `:root` CSS custom properties, responsive single-column collapse below `768px`, card hover/focus micro-interactions (`200ms`), and dark-theme variable overrides under `@media (prefers-color-scheme: dark)`.
- **`README.md`**: Documents the layout architecture, styling tokens, responsiveness rules, and verification steps.

## Verification

1. Open `index.html` in a browser and open **DevTools**.
2. Toggle the **Device Toolbar** and test viewports below **768px** (such as mobile portrait) to verify the layout collapses into a single column.
3. Hover and `Tab` through category cards to confirm the smooth `200ms` lift and shadow micro-interaction on both `:hover` and `:focus-visible`.
4. Test dark mode in OS/browser appearance settings to confirm `@media (prefers-color-scheme: dark)` updates the `:root` custom properties.
