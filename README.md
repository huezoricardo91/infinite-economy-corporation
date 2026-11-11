# Infinite Economy Corporation

The first public website for Infinite Economy Corporation. It deliberately describes the company as being at the beginning: no products, services, customers, results, or other claims have been invented for the page.

## Preview locally

On macOS, open `index.html` in a browser, or run:

```bash
cd ~/infinite-economy-corporation
python3 -m http.server 8100
```

Then open <http://localhost:8100>.

## Site files

- `index.html` — homepage, responsive styling, animated infinity artwork, and navigation.
- `404.html` — matching not-found page.
- `favicon.svg` — IE monogram matching the site.
- `.nojekyll` — keeps GitHub Pages from applying Jekyll processing.

The page is intentionally a concise company introduction and progress statement. Add specific business information only when the company has confirmed facts ready to publish.

## Hosting status

The GitHub Pages site source is:

<https://huezoricardo91.github.io/infinite-economy-corporation/>

The repository and GitHub Pages settings now specify `infiniteeconomycorporation.com` as the custom domain. The domain’s DNS still points at the Squarespace under-construction page, so the `.com` has not switched yet. Finish that DNS connection in Squarespace Domains:

- Apex (`@`) A records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`.
- `www` CNAME: `huezoricardo91.github.io`.
- Remove conflicting Squarespace parking A/AAAA records for the web hostnames; leave any mail-related records intact.

GitHub recommends configuring all four A records for the apex and using a `www` CNAME. DNS propagation can take up to 24 hours. Once DNS points to GitHub Pages, verify the domain and enable HTTPS in repository Pages settings. Source: [GitHub Pages custom-domain guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).
