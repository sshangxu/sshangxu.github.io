# Shang Xu — academic homepage

Public website: https://sshangxu.github.io/

This is a static academic homepage. It requires no package installation or build step.

## Update the website

1. Open `index.html` on GitHub and click the pencil icon.
2. Edit the biography, paper list, or office hours. Each paper is one `<li>` inside `<ol class="papers">`.
3. Commit the change to `main`. GitHub Pages publishes it automatically.

Replace `Shang-Xu-CV.pdf` to update the CV. Replace `shang-xu.jpg` to update the photo, keeping the filenames unchanged.

The revised geometric-attention paper is hosted directly as `Geometric-State-Space-revised.pdf`. Its title and **Revised PDF** links open this file; the separate arXiv link remains available. Replace this PDF to publish future revisions without changing the links. The November 17, 2026 homepage update uses the 25-page manuscript *Geometric State Space, Memory Representation and Architectures* by Shang Xu and Pengcheng Wang, while the corresponding arXiv replacement is processing.

The photo and CV were copied from Shang Xu's existing public website, https://www.shang-xu.com/, on November 17, 2026. The existing CV is reproduced unchanged. The paper list additionally includes the October 2026 geometric-attention preprint verified on arXiv. Contact details and office hours are carried over from the existing homepage, public CV, and GitHub profile.

## Hosting

In **Settings → Pages**, select **Deploy from a branch**, then **main** and **/ (root)**. No custom workflow, paid service, or dependency is needed.

The existing custom domain has not been changed. To connect `shang-xu.com` later, configure the domain in GitHub Pages and update DNS at the domain provider following GitHub's current documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Local preview

Open `index.html` in a browser, or run `python3 -m http.server 8000` from this folder and open http://localhost:8000.
