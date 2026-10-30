# Daily Data Dealing

A responsive static blog starter for data science tutorials. Built with plain HTML, CSS, and JavaScript—no build step or paid framework required.

## Preview locally
Open `index.html` in a web browser.

## Customize
- Edit the site name, page copy, and contact email in `index.html`.
- Edit colors and layout in `styles.css`.
- Add, remove, or update posts in the `posts` array in `script.js`.
- The newsletter is a front-end demo only. Connect a newsletter provider before collecting email addresses.
- This static starter has no secure admin panel or database. Article updates are made by editing `script.js` and redeploying.

## Free deployment with Cloudflare Pages
1. Create a GitHub account and a new repository named `daily-data-dealing`.
2. Upload these files to the repository root and commit the changes.
3. Sign in to Cloudflare and open Workers & Pages: https://dash.cloudflare.com/
4. Create a Pages project and connect the GitHub repository.
5. For a plain HTML site, use no build command and set the output directory to `/` or the repository root as the setup screen specifies.
6. Deploy. Cloudflare gives you a `*.pages.dev` URL.
7. To connect a domain you own, open the project → Custom domains → Set up a domain and follow the DNS instructions. See https://developers.cloudflare.com/pages/configuration/custom-domains/

## Alternative: GitHub Pages
1. Upload the site files to a public GitHub repository.
2. Open repository Settings → Pages and select the publishing source/branch.
3. Save and open the published `https://USERNAME.github.io/REPOSITORY/` address.
4. For a custom domain you own, use Settings → Pages → Custom domain and configure the DNS records with your registrar.
   Docs: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## About domain names
Free hosting normally includes a provider subdomain (for example, `your-project.pages.dev`). A custom domain such as `daily-data-dealing.com` usually requires buying/renewing the domain. Check current availability and pricing with a registrar before choosing a name. A domain can be connected to free hosting without paying for hosting itself.
