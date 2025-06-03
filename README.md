# Personal Homepage

This is my personal homepage built with Hugo and the Hugo Profile theme, deployed on GitHub Pages.

## How to Update the Site

1. Edit content in the `data/sections/` directory to update sections like About, Publications, etc.
2. Edit social links in `data/social.yaml`
3. Test locally with `hugo server -D`
4. Commit and push changes to the main branch:
   ```
   git add .
   git commit -m "Updated content"
   git push
   ```
5. GitHub Actions will automatically build and deploy the site.

## Important Files

- `hugo.toml` - Main configuration file
- `data/sections/*.yaml` - Content for each section
- `data/social.yaml` - Social media links
- `data/sections_order.yaml` - Order of sections on the page
- `static/images/profile.jpg` - Profile picture (replace with your own)

## Deployment

The site is automatically deployed using GitHub Actions. See `.github/workflows/hugo.yml` for details. 