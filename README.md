# chaoran-huang.com

Source for my personal domain, served via **GitHub Pages** at [www.chaoran-huang.com](https://www.chaoran-huang.com) (see [`CNAME`](CNAME)).

Right now this is a lightweight landing page and the canonical home for my **[resume](https://www.chaoran-huang.com/resume.pdf)**. The heavier content lives on two subdomains:

- **[portfolio.chaoran-huang.com](https://portfolio.chaoran-huang.com)** — portfolio, projects, and photography.
- **[learn.chaoran-huang.com](https://learn.chaoran-huang.com/docs)** — long-form engineering notes (NLP, ML, systems).

## What's here

| File | Purpose |
| --- | --- |
| `index.html` | the landing page |
| `resume.pdf` | current resume (linked from everywhere else) |
| `CNAME` | custom-domain config for GitHub Pages |

## Local preview

It's plain static HTML — open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Any push to `main` deploys automatically through GitHub Pages.
