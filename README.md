# pinball-scoreboard

A responsive Svelte 5 dashboard for tracking pinball metrics.

## Recommended Tools

For the best experience, install these VS Code extensions:

- **Svelte for VS Code** (Official syntax highlighting and error checking)
- **Prettier - Code formatter** (Automatically cleans up code on save)
- **Pretty TypeScript Errors** (Makes error popups easier to read)

## Developing

This project uses **Deno** for dependency management and running tasks.

Once you've cloned the project, install the dependencies:

```bash
deno install
```

Start the development server:

```bash
deno task dev

# or start the server and open the app in a new browser tab automatically
deno task dev --open
```

## Building

To create a production version of your app (static HTML for GitHub Pages):

```bash
deno task build
```

You can preview the production build locally to ensure everything works before deploying:

```bash
deno task preview
```

> **Note:** This project is configured with `@sveltejs/adapter-static` for deployment to GitHub Pages.
