# Animations

A collection of HTML / TypeScript animations — diagrams, explainers, and small interactive demos.

## List

| Animation | Description |
|-----------|-------------|
| [GC (Identify → Verify → Execute)](gc-animation/) | Multi-stage SVG animation: manifest tree, blob storage, and garbage-collection flow. |

## Adding a new animation

1. Create a new folder (e.g. `my-animation/`).
2. Put your `index.html` (and any `.ts`, assets) inside it.
3. Add a row to the table above and push.

No build step required for plain HTML; use a bundler in that folder if you need TypeScript.
