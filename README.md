# ameenomar.com

Personal site for Ameen Omar · Hijrah Life. Static HTML, no build step.

## How it deploys

Netlify (project `ameenomar`) watches the `main` branch. Any commit to `main`, whether pushed or edited on GitHub, goes live on https://ameenomar.com within about a minute.

## Files

- `index.html`: the whole page (styles inline)
- `ameen-omar.jpg`: the photo
- `netlify.toml`: redirects (`/readytohijrah` to the quiz, hijrahlife.com to ameenomar.com)
