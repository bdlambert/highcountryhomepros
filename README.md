# High Country Home Pros

Production website for [highcountryhomepros.com](https://highcountryhomepros.com) — construction & handyman services in the NC High Country.

- Plain static site: `index.html`, `privacy-policy.html`, `assets/`
- Deployed on [Render](https://render.com) as a Static Site (`render.yaml`): no build step, publish directory is the repo root.
- Every push to `main` triggers an automatic redeploy.
- Managed via Claude — ask Claude to make changes; it edits these files and pushes to `main`.
