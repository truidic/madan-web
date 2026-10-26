# Madan Musuvathi personal site

Publish these three root files (`index.html`, `style.css`, `CNAME`) to your GitHub Pages repository. `CNAME` sets the custom domain to `madan.musuvathi.com`.

1. Create a public repository named `<YOUR-GITHUB-USERNAME>.github.io` on GitHub.
2. Upload `index.html`, `style.css`, and `CNAME` at the repository root; commit to `main`.
3. In repository Settings > Pages, set Deploy from a branch, branch `main`, folder `/ (root)`.
4. In Settings > Pages, confirm custom domain `madan.musuvathi.com` and save.
5. In Cloudflare > musuvathi.com > DNS, create CNAME with Name `madan`, Target `<YOUR-GITHUB-USERNAME>.github.io`, Proxy status **DNS only**, TTL Auto. Replace any existing conflicting `madan` DNS records rather than adding a second one.
6. After the custom domain is active and certificate provisioned, enable Enforce HTTPS in GitHub Pages settings.

Keep the existing `musuvathi.com` and email records unchanged. Update the main page as needed; these starter claims follow the supplied CV.
