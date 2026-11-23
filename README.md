# Project-Landing-Page

A simple design for a landing page

# Landing Page

A static landing page built for The Odin Project's Landing Page assignment, recreating a design mockup with HTML, CSS. It has a header with navigation links, a hero section with a sign-up button, an info section with four image cards, a customer quote, a call-to-action banner, and a footer.

# What i practiced

- Flexbox for every section's layout: justify-content, align-items, flex-direction, gap
- Grouping elements in containers so they move together
- Matching colors, font sizes, and spacing to a mockup
- Using Google Fonts (Roboto) and a CSS reset

# What was hard

Captions next to their images: in the info section, the text sat beside each image instead of under it. Every image and every caption was a separate flex item in the same row, so flexbox lined them all up side by side. Wrapping each image and its caption in their own container made each pair one flex item, and inside it I could stack them in a column.

Quote author stuck on the left: the author line was a block element, so its box already took the full width and only the text sat on the left. Putting it in a flex container made it a flex item, which is only as wide as its content, so justify-content: flex-end could push it right.

# Limits

The page isn't responsive. The assignments targets a tablet width only.

# Credits

CSS reset based on Josh W. Comeau's "A Modern CSS Reset". Design mockup from The Odin Project
