This is the main repository [`page`](https://pages.github.com) that centralizes [`pages`](https://pages.github.com) from other Envidera Github repositories.

How it works?

- GitHub automatically maps each repository that has a `page` to a subpath of `https://<organization name>.github.io` or `https://<user name>.github.io`
- `https://dev.envidera.com` points its DNS CNAME to `https://envidera.github.io`
- `https://envidera.github.io` is configured with the custom domain `dev.envidera.com`
  - So, accessing `https://dev.envidera.com` will be mapped to the repository `page` at `https://github.com/envidera/envidera.github.io` (this repo)
  - Accessing `https://dev.envidera.com/repo1` will be mapped to the repository `page` at `https://github.com/envidera/repo1`

Cool ya!
