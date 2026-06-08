# Dana Krystelle — Personal Brand Site

Static multi-page site for Dana Krystelle ("The Big in the Little"). Built by KAL Studio.
No build step — plain HTML/CSS/JS served as-is.

## Structure

| File | Page |
|------|------|
| `index.html` | Home |
| `services.html` | Services |
| `work.html` | Work (landscape + reels) |
| `speaking.html` | Speaking |
| `teaching.html` | Resources |
| `about.html` | About |
| `contact.html` | Contact |
| `styles.css` | Shared styles (source of truth) |
| `script.js` | Scroll fade-up animation |
| `dana-headshot.jpeg` | Headshot |

> Note: CSS and JS are currently inlined into each HTML file so the pages
> render standalone. `styles.css` / `script.js` are the source of truth but
> are not yet linked. See "Linking external assets" before going live if you
> want browser caching.

## Hosting

Deployed via GitHub Pages, custom domain managed through Namecheap.
The `CNAME` file (added automatically when the custom domain is set in
repo Settings → Pages) holds the live domain. `.nojekyll` keeps Pages
from running the files through Jekyll.

## Still to do (client to provide)

- Client logos for "Trusted By"
- Real past speaking events + dates
- Behind-the-scenes / stage / about photos
- Showreel + case-study video
- Real testimonials (currently placeholder names)
- Metrics (subscribers, views, engagement)
- Connect the contact + newsletter forms to a real service (Formspree / Tally)
