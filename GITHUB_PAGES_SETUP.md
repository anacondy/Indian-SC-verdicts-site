# GitHub Pages Setup Instructions

This document provides instructions for enabling GitHub Pages for this repository.

## Automatic Deployment

A GitHub Actions workflow has been configured to automatically deploy the site to GitHub Pages whenever changes are pushed to the `main` branch.

## Required Steps

To enable GitHub Pages, a repository administrator needs to:

1. **Navigate to Repository Settings**
   - Go to the repository on GitHub
   - Click on "Settings" tab

2. **Enable GitHub Pages**
   - In the left sidebar, click on "Pages"
   - Under "Build and deployment", select:
     - **Source**: GitHub Actions
   - The site will be automatically deployed using the workflow in `.github/workflows/deploy-pages.yml`

3. **Verify Deployment**
   - Once the PR is merged to `main`, the workflow will run automatically
   - Check the "Actions" tab to see the deployment progress
   - Once completed, the site will be live at: `https://anacondy.github.io/Indian-SC-verdicts-site/`

## Workflow Details

The deployment workflow (`.github/workflows/deploy-pages.yml`) will:
- Trigger on every push to the `main` branch
- Deploy all files in the repository root to GitHub Pages
- The `index.html` will be served as the main page

## Troubleshooting

If the site doesn't deploy:
1. Ensure GitHub Pages is enabled in repository settings
2. Check the Actions tab for any workflow errors
3. Verify the workflow has the necessary permissions (already configured in the workflow file)
4. Make sure the repository is public (or GitHub Pages is enabled for private repos in your plan)

## Manual Testing

You can also test the site locally by:
- Opening the `index.html` file in a web browser
- Running a local web server: `python3 -m http.server 8080`
