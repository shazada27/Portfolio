# Web Technologies Assignment 2 Explanation

## CSS Definition & Benefits
CSS (Cascading Style Sheets) is a stylesheet language used to describe the visual presentation and layout of HTML documents. It separates content from presentation, improving code maintainability, accelerating page loading through cached stylesheets, and enabling responsive multi-device design.

## CSS Rule Breakdown
In the external stylesheet rule `body { background-color: #090e17; }`:
- **Selector:** `body` (targets the HTML body element).
- **Property:** `background-color` (defines the background color).
- **Value:** `#090e17` (a dark hex color code).

## CSS Styling Methods
1. **Inline CSS:** Written directly inside an HTML element's `style` attribute (used in `index.html`). Highest specificity, best for quick overrides, but poor reusability.
2. **Embedded CSS:** Defined inside a `<style>` block in the HTML `<head>` (used in `information.html`). Applies to a single page.
3. **External CSS:** Written in a separate `.css` file linked via `<link>` (used in `registration.html`). Promotes modularity and site-wide reusability.

## Evolution of CSS
CSS1 (1996) introduced basic typography, margins, and colors. CSS2/2.1 (1998–2011) added positioning, media types, and absolute/relative layout structures. Modern CSS3+ is modularized, introducing Flexbox, Grid, CSS Variables, and advanced responsive animations.

## Browser Testing & Semantic HTML
Browser support ensures uniform layout rendering across rendering engines. This site was verified in **Google Chrome** and **Mozilla Firefox**. 
- **Semantic HTML Example:** `<article>` cleanly defines self-contained content.
- **Non-Semantic HTML Example:** `<div>` acts strictly as a generic container without structural meaning.