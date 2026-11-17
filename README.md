# Total Repair Services website

Cinematic scroll-video website for Total Repair Services.

- `index.html` is the whole site (HTML, CSS and JS in one file).
- `media/` holds the scroll video in three segments plus the poster image.
- `js/` has GSAP, ScrollTrigger and Lenis (smooth scrolling), bundled locally.
- `fonts/` has Anton and Montserrat, `img/` has the logo and photos.

To preview locally, serve the folder with a server that supports range requests (for example `npx http-server`), because the video scrubbing needs them. Opening index.html straight from disk will not scrub the video.

Still to do: connect the contact form to email or a CRM (it currently only shows the confirmation message).
