# Hitendra B. Singh — Personal Branding Website

A responsive, static executive portfolio website built with HTML, CSS and vanilla JavaScript. It has no runtime dependencies and can be deployed directly to Vercel.

## Run locally

Requirements: Node.js 18 or later.

```bash
npm install
npm run dev
```

Open http://localhost:3000.

`npm run build` performs a deployment-readiness check. There is no bundling step because this is a dependency-free static site.

## Deploy to GitHub and Vercel

1. Extract the ZIP.
2. Review and update the content and placeholders described below.
3. Create a GitHub repository and push the project files to its root.
4. In Vercel, choose **Add New → Project**, import the repository and deploy.
5. No build command or environment variables are required. Vercel can serve the static files directly.

## Personalise before publishing

Search the project for `YOUR_EMAIL@example.com` and replace it with the professional email address you want to publish. Replace the generic LinkedIn URL with your exact profile URL. Review the CV at `cv.html`, add your complete employment history, accurate dates, verified achievements and credential details. The CV page is deliberately an editable HTML document; visitors can use their browser's Print → Save as PDF if they need a PDF copy.

The current contact form uses a `mailto:` link and opens the visitor's default email application. It does not store or transmit form data to a server. For a server-backed form, connect a form provider or deploy a serverless function and configure spam protection.

## Update website content

- Main page: `index.html`
- Styles and responsive layout: `styles.css`
- Navigation and contact form interaction: `script.js`
- Downloadable profile page: `cv.html`
- Favicon: `assets/favicon.svg`

## Notes

- Project descriptions are intentionally high-level. Add only details that are accurate and approved for public disclosure.
- No profile photograph has been fabricated; the hero visual is an abstract CSS illustration.
- External Google Fonts are used for typography. System fonts remain as fallbacks.
