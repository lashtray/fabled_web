# CLAUDE.md

This is the **fabled.co** marketing / landing website — a separate project from the main Fabled app (located at `../app`).

## What this is

A minimal static landing page for [fabled.co](https://fabled.co). It exists primarily so Fabled has a public web presence at its own domain — required for the Apple Developer Program organization enrollment and similar account verifications.

## Structure

```
fabled_web/
  public/         # Netlify publish directory — only this folder is served
    index.html    # The landing page
  netlify.toml    # Points Netlify to public/ as the publish directory
  CLAUDE.md       # This file — not served (lives outside public/)
```

## Deployment

Hosted on [Netlify](https://netlify.com), pointed at the domain **fabled.co**.

To deploy: drag-and-drop the `public/` folder into Netlify, or connect this repo and set publish directory to `public`.

## Design principles

- No details about the product — just the name and "coming soon"
- Dark, minimal aesthetic consistent with the app
- Contact email: hello@fabled.co

## Main app

The main Fabled platform lives at `../app` (Next.js + Supabase). See that project's `CLAUDE.md` for its architecture and conventions.
