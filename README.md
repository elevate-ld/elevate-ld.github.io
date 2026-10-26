# Elevate L&D Consulting website

Upload everything in this folder to a GitHub repo to publish it with GitHub Pages.

    index.html              <- main website
    part107/index.html      <- FAA Part 107 Prep
    secplus/index.html      <- Security+ Prep
    excel-reference/index.html <- Excel for Accounting

## Publish
1. Create a free GitHub organization (e.g. elevate-ld) so your personal username isn't in the URL.
2. In that organization, create a repo named exactly: <org-name>.github.io  (e.g. elevate-ld.github.io)
3. Upload all files and folders (Add file -> Upload files; drag the whole folder contents).
4. Settings -> Pages -> Source: Deploy from a branch -> main / root -> Save.
5. Your site goes live at https://<org-name>.github.io in a minute or two.

## Connect the contact form
Open index.html, find SETTINGS near the bottom, and fill in:
- FORM_URL: your Google Form share link (embeds the form; responses go to Google Sheets)
- EMAIL: your business email (shown on the page; also powers the built-in form if FORM_URL is blank)
