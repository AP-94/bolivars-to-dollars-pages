# GitHub Pages Setup for Bolivars to Dollars

This repository contains the Terms of Use and Privacy Policy pages for the Bolivars to Dollars app.

## Files

- `index.md` - Home page
- `terms.md` - Terms and Conditions
- `privacy.md` - Privacy Policy
- `_config.yml` - Jekyll configuration

## Setup Instructions

1. **Create a new GitHub repository** named `YOUR_USERNAME.github.io` (replace `YOUR_USERNAME` with your actual GitHub username)

2. **Upload these files** to the repository:
   - `_config.yml`
   - `index.md`
   - `terms.md`
   - `privacy.md`

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on **Settings**
   - In the left sidebar, click on **Pages**
   - Under "Build and deployment", select **Deploy from a branch**
   - Select the branch (usually `main` or `master`)
   - Click **Save**

4. **Wait for deployment:**
   - GitHub will deploy your site (may take up to 10 minutes)
   - Your site will be available at `https://YOUR_USERNAME.github.io`

5. **Verify:**
   - Visit `https://YOUR_USERNAME.github.io/terms` for Terms of Use
   - Visit `https://YOUR_USERNAME.github.io/privacy` for Privacy Policy

## Updating the Site

To update any page:
1. Edit the corresponding `.md` file
2. Commit the changes
3. Push to GitHub
4. Wait for GitHub Pages to deploy (up to 10 minutes)

## Custom Domain (Optional)

If you want to use a custom domain:
1. Purchase a domain from a registrar
2. Create a `CNAME` file in the repository root with your domain name
3. Configure DNS records at your registrar
4. Update GitHub Pages settings to use the custom domain

For more information, see: [GitHub Pages Documentation](https://docs.github.com/en/pages)
