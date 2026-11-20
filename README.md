# email-creatives

Static host for HTML email creatives used in ActiveCampaign "import from URL".

## Adding a new email

1. Add a file at `emails/<yyyy-mm-dd>-<slug>.html`.
2. Optionally add a link to it on `index.html`.
3. Commit and push to `main`. Coolify should auto-deploy on push.

Email files should stay email-safe: table layout, inline CSS, max-width 600px.
