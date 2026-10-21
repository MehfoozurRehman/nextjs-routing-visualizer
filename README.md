# nextjs-routing-visualizer

A planned tool for visualizing how Next.js App Router routes map to files. This repository currently holds only the project scaffolding.

**Status:** Stub. The repository contains a README, a license, editor settings and an icon font folder, with no source code and no `package.json`.

## The problem

Next.js routing is defined by folder and file names, which makes the route tree hard to see at a glance. The project name points at a visual map of that tree. The code does not yet show how it would be built.

## What it does

Nothing yet. The repository has no application code, so no features can be verified.

## How it's built

- No stack is committed. There is no `package.json`, no framework dependency and no source directory.
- `public/fonts` contains Font Awesome icon files, and `.vscode/` contains editor settings. Neither is part of the application.

## Running it locally

There is nothing to run yet.

## What's left

- Choose the stack and add a `package.json`. A Next.js app is the obvious starting point, given the name.
- Build the route scanner: read the `app/` directory and produce a tree of routes, segments and special files.
- Build the view that draws the tree.
- Add a sample Next.js project to test the scanner against.
- Remove the Font Awesome files if no UI uses them.

## License

See `LICENSE`.
