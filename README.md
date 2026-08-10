# Shaheen Sardar — Premium Cloud & DevOps Portfolio

A responsive static portfolio built with HTML, CSS and JavaScript.

## Included

- `index.html`
- `styles.css`
- `script.js`
- `assets/`

## Important replacements before publishing

1. Replace this placeholder in `index.html`:

   `https://www.linkedin.com/in/YOUR-LINKEDIN-USERNAME/`

   with your exact LinkedIn profile URL.

2. Add your real resume file here:

   `assets/Shaheen-Sardar-Resume.pdf`

3. Certifications section updated to include completed AWS, Huawei Cloud, Linux/DevOps and additional technical credentials.

## Local preview

From PowerShell inside this folder:

```powershell
python -m http.server 8000
```

Then open:

`http://localhost:8000`

## Recommended AWS deployment

GitHub → GitHub Actions → Amazon S3 → CloudFront → Route 53 + ACM HTTPS
