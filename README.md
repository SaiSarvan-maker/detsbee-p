# Detsbee Guide

A responsive, static publishing site that explains the Detsbee social discovery app and links to the live app at [detsbee-1.vercel.app](https://detsbee-1.vercel.app/).

## Run locally

Open `index.html` in a browser, or serve this directory with any static HTTP server. There is no build step or dependency installation.

## Deploy

### Vercel

Import this repository into Vercel and use the **Other** framework preset. Leave the build command and output directory empty (the site is static and `index.html` is at the repository root). `vercel.json` includes basic security headers.

### GitHub Pages

In repository settings, enable Pages and deploy from the `main` branch root. The site uses relative asset paths and works from a repository subpath.

## App destination

The guide currently links to `https://detsbee-1.vercel.app/`. Update the `href` values in `index.html` if the production app URL changes.

## Content accuracy

The guide describes the current product behavior: one completed response per invitation link; the recipient can answer without an account; each answer can be Shared, Private, Skip, or Decline; the creator sees shared responses only. Shared Ground uses normalized exact text matches, not semantic or personality analysis. No AI question generation is claimed.
