# Redirects

This repository contains a single `_redirects` file used for static site routing.

## _redirects Rule
`/*    /index.html   200`

This rule enables single-page app (SPA) behavior by redirecting all requests to `index.html`, ensuring proper routing on refresh and direct links.

## Usage

Upload the `_redirects` file to the root of your static site (e.g., Netlify, Vercel, S3 + CloudFront) to enable clean URL handling.