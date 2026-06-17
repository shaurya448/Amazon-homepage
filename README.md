# Amazon Homepage Clone

A static front-end clone of the Amazon.com homepage, built using only raw HTML and CSS — no frameworks, no JavaScript, no build tools.

## Overview

This project recreates the visual layout of Amazon's homepage, including the navigation bar, category panel, hero banner, product showcase grid, sign-in prompt, and multi-column footer.

## Features

- **Top Navbar** — logo, delivery location, search bar with category dropdown, language selector, account menu, orders, and cart
- **Category Panel** — hamburger menu, today's deals, Prime Video, registry, customer service, gift cards, and sell options
- **Hero Banner** — full-width promotional image
- **Product Showcase Grid** — eight content boxes covering home essentials, gaming, new arrivals, fashion, kitchen appliances, and more
- **Sign-In Prompt** — call-to-action panel for personalized recommendations
- **Footer** — back-to-top link, four-column link panel (company info, affiliate programs, payment products, help), language/currency/region selector, legal links, and copyright notice
- Icons powered by **Font Awesome**

## Project Structure

```
.
├── index.html      # Page markup and structure
└── style.css       # All styling and layout
```

## Tech Stack

- HTML5
- CSS3 (Flexbox-based layout, with positioning for fine-tuned placement)
- [Font Awesome](https://fontawesome.com/) (via CDN) for icons

## Getting Started

### Option 1: Open directly
Open `index.html` in any web browser.

### Option 2: Use Live Server (VS Code)
1. Install the **Live Server** extension in VS Code.
2. Right-click `index.html` in the file explorer.
3. Select **Open with Live Server**.

## Assets Required

This project references several local image files that are not included in this repository. To view the page as intended, add the following images to your project root (or update the paths in `index.html` to match your own assets):

- `amazon logo.png`
- `usflag.png`
- `header.jpg`
- `content1.jpg` through `content30.jpg`

## Notes

- This is a static, non-functional UI clone built for learning and practicing HTML/CSS layout techniques (Flexbox, relative positioning, hover effects).
- Buttons, dropdowns, and links are present for visual completeness only and are not wired to any backend or real functionality.
- Layout uses fixed pixel widths in places, so it is best viewed on larger desktop screens; it is not currently responsive for mobile devices.

## Future Improvements

- Make the layout responsive using media queries or a CSS Grid/Flexbox refactor
- Replace relative-positioning hacks with cleaner Flexbox/Grid-based alignment
- Add real interactivity (search functionality, cart logic) with JavaScript
- Optimize and self-host images instead of relying on absolute root paths

## License

This project is for educational and portfolio purposes only. Amazon, its logo, and related trademarks belong to Amazon.com, Inc. This is an unofficial fan-made clone, not affiliated with or endorsed by Amazon.