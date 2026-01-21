# Young Miko Fan Page (HTML + CSS Only)

This project is a **fan page layout** for **Young Miko** built with **only HTML + CSS** (no JavaScript).

## Key requirement we enforced

✅ The **mentee instructional comments match the mentor code 1:1**.  
That means:

- Same sections
- Same class names
- Same IDs for anchor navigation
- Same “open in new tab” attributes for external links
- Same gallery behavior (images display only; no <a> wrapper)

## New tab links (what to teach)

For external links we use:

- `target="_blank"` (open in new tab)
- `rel="noopener noreferrer"` (security best practice)

Applied to:

- Song “Listen” links
- Tour “Details” links
- Social media links

## Gallery rule

Gallery is **display only**:

- Use `<figure> + <img> + <figcaption>`
- **No `<a>`** around images
