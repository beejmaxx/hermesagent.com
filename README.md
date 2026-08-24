# hermesagent.com

A small, independent landing page for technical work on reliable agent systems.

The site deliberately avoids presenting Hermes as a company or product. It links to
existing, reviewable engineering work and includes an explicit non-affiliation note.

## Local preview

Serve the directory with any static HTTP server, for example:

```sh
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

The directory is ready for a Cloudflare Pages direct upload. No build command is
required; the output directory is the repository root.
