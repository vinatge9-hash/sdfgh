# Niyantri Coffee - Website

This repository contains a five-page website for Niyantri Coffee:
- index.html (Home)
- menu.html (Menu)
- cart.html (Cart with PayPal integration)
- about.html (About the brand and location in Hyderabad, India)
- contact.html (Contact form and placeholder address in Hyderabad)

Key implementation notes:
- Theme: warm coffee color palette using Tailwind CSS classes.
- The site uses a full-width main content and a gentle load animation.
- PayPal integration is included on the cart page with a sandbox client-id.
- Placeholder image syntax is used: src="https://images.unsplash.com/photo-1525451031984-340d39c36aa8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHw0fHxkZXNjcmlwdGlvbnxlbnwwfDB8fHwxNzU2NzE0MzIxfDA&ixlib=rb-4.1.0&q=80&w=1080".
- Fonts: two font families are prepared via preload placeholders and are applied using inline font-family styling per section (Playfair Display for hero or headings, Inter for body).
- All icons are inline SVGs styled with Tailwind classes.
- The homepage includes a testimonials section.
- The menu page lists all menu items with static HTML blocks (no templating).

How to run:
- Open the pages in a browser. Tailwind is loaded via CDN for this demo; in production, compile Tailwind with your build process.
- The PayPal button on the cart uses the sandbox client-id (sb).

Notes on default location: Hyderabad, India is used as the placeholder location for addresses on the contact/about pages.
