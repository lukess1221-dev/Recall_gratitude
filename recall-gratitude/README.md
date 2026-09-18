# Recall Gratitude

A complete, static website ready for GitHub Pages. No installation or build step is needed.

## Publish on GitHub Pages

1. Unzip `recall-gratitude-website.zip`.
2. Create a GitHub repository (a public repository works with GitHub Free).
3. Upload everything **inside** the extracted `recall-gratitude` folder into the repository root. `index.html` must be at the top level, alongside `assets`, `new-page`, and the other page folders. Do not upload the ZIP itself.
4. Commit the files to the `main` branch.
5. In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select **main** and **/(root)**, then save. GitHub will display the published address when deployment is complete.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

All paths are relative, so the site works at both a GitHub project URL and a custom domain. To use recallgratitude.com, configure the custom domain in GitHub Pages and update its DNS after reviewing the new site. No domain changes have been made for you.

## Included

- Home, About, Contact Us, Terms & Conditions, and Privacy Policy.
- Original Recall logo, unchanged, with a softer blue-and-gold site palette.
- Original founder video, stored locally rather than streamed from Squarespace.
- Full original legal policy text, preserved without rewriting.
- Responsive layouts, mobile navigation, keyboard focus styling, and required contact fields.
- An `/about/` alias repairs the old website’s broken Learn more destination.

## Contact form

The contact form prepares an email to info@recallgratitude.com in the visitor's configured email app. The visitor must send it there. It does not submit to a server or display a false sent confirmation. A direct email link is also provided. Automatic form delivery would require connecting a form service or backend.

## Editing

Edit each page’s `index.html` to change text. Shared colors and layout are in `assets/style.css`; menu and contact-form behavior are in `assets/site.js`. The primary color values are defined at the start of the stylesheet.

The original policy wording, including any original placeholders and inconsistencies, has been retained as requested. Squarespace platform credits and its empty cart were omitted.

## Preview

From this folder, run `python3 -m http.server 4173`, then open http://localhost:4173. To preview without a server, open `index.html`; some browsers may show a directory listing for links to page folders, so a local server is recommended.
