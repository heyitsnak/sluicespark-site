# sluicespark-site

Website and app policies for SluiceSpark LLC at https://sluicespark.com, served by GitHub Pages from the `main` branch root.
Plain HTML and one stylesheet; no build step, no cookies, no third-party scripts.

| Page | File |
|---|---|
| Home | `index.html` |
| Maple Hollow privacy policy | `privacy/maple-hollow.html` |
| Ana privacy policy | `privacy/ana.html` |
| Terms of service (both apps) | `terms.html` |

When an app starts collecting new data, update its policy and the "Last updated" date before that version ships.
The domain is registered at Porkbun. Its DNS has GitHub Pages' four A and four AAAA records on the root and `www` as a CNAME to `heyitsnak.github.io`; the MX and SPF records are Porkbun's email forwarding. `CNAME` holds the custom domain.
