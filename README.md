# AWS S3 Static Website Demo

A clean, 3-page static website demo designed for livestream presentations demonstrating static website hosting on Amazon S3 and automated CI/CD deployments using GitHub Actions with AWS OIDC.

## Pages
- `index.html` - Home page introducing the demo and architecture
- `about.html` - Explaining S3 static hosting & OIDC security
- `error.html` - Custom 404 error page for S3 Error Document configuration
- `css/styles.css` - Clean, responsive styling

## Architecture
- **Amazon S3**: Hosts static web files with static website hosting enabled.
- **GitHub Actions**: Automates deployment on push to `main`.
- **AWS OIDC Provider**: Eliminates long-lived AWS credentials by using OpenID Connect federated authentication.
