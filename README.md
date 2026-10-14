# Soren Technologies website

Static marketing site (HTML/CSS/JS, no build step).

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080 --directory .
```

## Free hosting

- **GitHub Pages**: push this folder to a repo and enable Pages on the root (or `/docs`).
- **Netlify / Cloudflare Pages**: connect the repo, publish directory = site root, no build command.

## Contact

Quotes and the contact form use `sorenspiller@proton.me`.

- Product **Request a Quote** buttons: `mailto:` with a product-specific subject.
- Contact form: posts to [FormSubmit](https://formsubmit.co) (`https://formsubmit.co/sorenspiller@proton.me`). On first submission, FormSubmit emails that address to confirm ownership—approve once. A direct mailto fallback is shown under the form.
