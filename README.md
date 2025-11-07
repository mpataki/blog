# Blog

Personal blog built with Astro and deployed to AWS.

## Tech Stack

- **Framework**: Astro
- **Styling**: Tailwind CSS
- **Content**: Markdown/MDX with content collections
- **Hosting**: AWS S3 + CloudFront
- **Deployment**: GitHub Actions (OIDC)
- **Infrastructure**: Terraform (in mp-aws-infra repo)

## Development

```bash
npm install          # Install dependencies
npm run dev          # Start dev server at localhost:4321
npm run build        # Build for production
npm run preview      # Preview production build
```

## Deployment

Automatically deployed via GitHub Actions when pushing to `main` branch.

Site: https://blog.matpataki.com
