m365architect.in — professional portfolio + article website

RECOMMENDED HOSTING: CLOUDFLARE PAGES (FREE)
For this static HTML website and hand-written article pages, Cloudflare Pages is a good free host. It supports custom domains and automatic deployments from a Git repository. Current Free plan documentation lists 500 builds per month and up to 100 custom domains per project:
https://developers.cloudflare.com/pages/platform/limits/

DEPLOY
1. Create a free Cloudflare account at https://dash.cloudflare.com/
2. Open Workers & Pages > Create > Pages > Connect to Git.
3. Connect a GitHub account and create/select a repository for this website.
4. For a plain HTML site, leave the build command blank and set the build output directory to `/` (or the repository root, as requested by the current setup wizard).
5. Deploy. Cloudflare gives you a temporary `pages.dev` address.
6. In the Pages project, open Custom domains and add `m365architect.in` and optionally `www.m365architect.in`.
7. Follow the exact DNS instructions Cloudflare displays. If the domain DNS is not already managed by Cloudflare, it may ask you to add records at your domain registrar or move DNS management to Cloudflare.
8. Wait for DNS and certificate provisioning, then test HTTPS and both domain variants.

ALTERNATIVE: GITHUB PAGES
GitHub Pages supports custom domains for sites in public repositories on GitHub Free:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages
Create a public repository, upload the website files, enable Settings > Pages > Deploy from a branch, select main and root, then configure the custom domain. Follow GitHub's current DNS instructions.

IF YOU WANT A VISUAL ARTICLE EDITOR
WordPress.com is easier for writing and managing posts from a dashboard. Its free plan includes unlimited posts and pages, but the free plan uses a wordpress.com subdomain and does not include connecting your own custom domain. To use m365architect.in as the primary domain, budget for a paid plan:
https://wordpress.com/support/plan-features/
https://wordpress.com/pricing/

RECOMMENDATION
- Keep Cloudflare Pages if you want to keep ongoing hosting costs at zero and are comfortable adding articles as files.
- Choose WordPress.com paid if you want to write and publish articles from a browser-based editor without editing HTML.
- Your existing domain registration/renewal remains a separate cost; “free hosting” does not make the domain itself free.

IMPORTANT BEFORE PUBLISHING
- Review the phone number and email address in your CV and website because they will be public.
- The CV is included as a downloadable file.
- Replace any details you do not want publicly visible.
- Use only customer-approved screenshots and anonymise tenant IDs, domains, email addresses, IPs and other confidential information.
- The contact links open email/phone apps; this static site does not have a server-side contact form.
