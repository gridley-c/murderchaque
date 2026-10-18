# murderchaque.com

Static site served by GitHub Pages from `main` branch, repository root.

- **Stack:** plain HTML/CSS. `.nojekyll` disables the Jekyll build — files are served as-is.
- **Domain:** `murderchaque.com` via the `CNAME` file. DNS at GoDaddy (apex A records → GitHub, `www` CNAME → `gridley-c.github.io`).
- **Deploys:** push to `main` is the whole pipeline.
- **Maintained by:** the OpenClaw main agent (Cherrytree) on the Pi, via the `github-murderchaque` SSH host alias and the `murderchaque_deploy` key.
