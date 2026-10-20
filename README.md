# akashdeep.os

A small, responsive, no-build personal blog for writing about science, thinking, business, and related ideas.

## How to publish it for free

The project is plain HTML, CSS, and JavaScript, so it works on GitHub Pages, Cloudflare Pages, Netlify, or any static host. The simplest route is:

1. Create a free GitHub account (if you do not already have one).
2. Create a **public** repository, ideally named `your-username.github.io`.
3. Upload all files in this folder.
4. In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. GitHub will give you a free address like `https://your-username.github.io`.

GitHub Pages is free for public repositories. A custom domain is optional and usually costs money; `akashdeep.os` is the brand name used inside the site, not a domain purchase.

## How to add a piece

Open `posts.js`, copy one post object, and update its title, date, category, reading time, excerpt, and link. For a full article, copy `post.html`, rename it (for example `my-first-essay.html`), replace the article text, and update that post's `url`.

The current posts are deliberately labeled **EXAMPLE** so they are easy to replace. The newsletter form is a visual placeholder until an email service is chosen; it does not collect addresses yet.
