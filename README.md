# Lintel theme documentation

Public documentation, support policy and contact form for the Lintel Shopify theme by PapaThemes,
served by GitHub Pages at <https://lintel.papathemes.com>.

It is a plain Jekyll site. GitHub Pages builds it from the `main` branch root; no Actions workflow is needed.

## Edit content

- Pages are Markdown files in the repository root (`getting-started.md`, `sections.md`, …) and `tutorials/`.
- The sidebar menu is `_data/nav.yml`.
- Layout and styles: `_layouts/default.html`, `assets/css/site.css`.
- Setting names must match the theme editor labels exactly (`forma-shopify-theme/locales/en.default.schema.json`
  in the theme repository). Write in American English.

Push to `main` and GitHub Pages rebuilds the site in about a minute.

## Owner settings (in `_config.yml`)

| Key | What it does |
| --- | --- |
| `support_response_time` | The reply time shown on /support/, /contact/, the home page and the FAQ. Currently "within 2 business days". |
| `support_request_url` | The Zendesk "Submit a request" page that /contact/ and /support/ link to. |

The support page also says "Monday to Friday, excluding public holidays" (`support.md`); change it there if your hours differ.

## Support requests (Zendesk)

/contact/ and /support/ link to the PapaThemes Zendesk request form (`support_request_url` in `_config.yml`).
The form fields, file attachments and the auto-reply are configured in Zendesk, not in this repository.
/contact/ lists what merchants should include; keep it in step with the Zendesk form.

## Custom domain (DNS)

GitHub Pages serves this repository at `lintel.papathemes.com` (see `CNAME`). In the DNS for `papathemes.com`, add:

| Type | Name | Value |
| --- | --- | --- |
| CNAME | `lintel` | `tvlgiao.github.io` |

When the record resolves and GitHub has issued the certificate, turn on **Settings > Pages > Enforce HTTPS**.

## Build locally (optional)

```sh
gem install jekyll webrick kramdown-parser-gfm
jekyll serve
```

Then open http://localhost:4000.
