# Project

This imported repository is a single static `index.html` page. It redirects visitors to `https://www.google.com` and appends the incoming URL fragment (`#...`) to that destination.

## Run locally on Replit

The **Start application** workflow serves the repository at port 5000 using Python's built-in static file server. There are no dependencies or build steps. For a manual run, use:

```sh
python3 -m http.server 5000 --bind 0.0.0.0
```

## Publish

Use a static deployment. Its build command copies only `index.html` into `dist/`, which is the public directory. No dependencies or secrets are required.