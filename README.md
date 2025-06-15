# NGO WORLDWIDE LTD Website

Official website for NGO WORLDWIDE LTD, hosted on GitHub Pages.

---

## Deployment

This project uses GitHub Actions to automatically deploy the website to GitHub Pages whenever changes are pushed to the `main` branch.

### Deployment Workflow

- The workflow file is located at `.github/workflows/deploy.yml`.
- When you push to the `main` branch, the workflow will:
  - Checkout the repository code
  - (Optional) Run build steps if configured
  - Deploy the contents of the specified folder (default `./public`) to GitHub Pages

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Alexanderk424/ngo-worldwide.git
   cd ngo-worldwide
