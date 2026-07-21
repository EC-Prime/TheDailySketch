Typography

Bring in a serif display font for headlines/masthead (something like Playfair Display) and a serif body font (like Lora) via Google Fonts
Differentiate font sizes across the hierarchy: h1 masthead > feature h2 > secondary h2 > small article h3 > body text
Add letter-spacing to small uppercase text (date line, captions) for that editorial feel

Masthead

Add a date/location line above or below the h1 (e.g. "TUESDAY, 21 JULY 2026 · JOHANNESBURG")
Add a double border or thick rule under the masthead to separate it from content

Feature article

Add a drop cap on the first letter of the opening paragraph (::first-letter)
Add a thin vertical divider between the feature column and the cover image column

Secondary article

Add a top rule separating it from the feature article above
Keep the same right-hand divider treatment as the feature article for visual consistency

Small articles

Replace any card-style borders with a single top rule above each heading (mimics column breaks rather than boxed widgets)
Slightly mute the body text color compared to the feature/secondary text for visual hierarchy

Cover image

Add a thin border or frame around the figure
Add a figcaption with a small photo credit/caption line
Make sure the image fills its grid cell properly (object-fit: cover, full height/width) rather than floating at a fixed size

Page-level polish

Give the page a background color slightly off pure white (warm off-white reads more "newsprint")
Center the whole layout on the page with a max-width so it doesn't stretch full-bleed on wide screens
Add generous but consistent padding around the whole layout

Responsiveness (not in the original tests, but expected for a portfolio piece)

Add a media query that collapses the grid to a single column on small screens, reordering areas so the image and text stack sensibly

Repo-level (outside the code entirely)

Write a README with project description, a screenshot, and a live demo link
Enable GitHub Pages so there's a clickable live version
Use a clear, descriptive final commit message rather than something generic

Want me to leave it here, or talk through the trickiest bit (the drop cap or the responsive collapse) conceptually before you write it?