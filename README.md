# blog_media

Static media for [vexpaer.github.io](https://vexpaer.github.io/).

The repository is deployed as a static Cloudflare Pages project. Keep existing
paths stable because posts link to assets by their `/media/...` URL path. The
deployable files live under `public/` in this repository.

## Cloudflare Pages settings

- Framework preset: None
- Production branch: `main`
- Build command: `exit 0`
- Build output directory: `public`

Do not enable Git LFS: Cloudflare Pages must receive the actual image files,
not LFS pointer files.
