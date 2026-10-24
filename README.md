# Logan Jones Applications — App Support

A simple, mobile-friendly support page for all Logan Jones Applications apps. No dependencies, JavaScript, or build step.

## Publish on GitHub Pages

1. Create a GitHub repository and upload all HTML files and `.nojekyll` to the root of its `main` branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select **main** and **/ (root)**, then click **Save**.
5. Once deployment finishes, GitHub displays the published URL in **Settings → Pages**. It will typically be `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

Use that URL as the **Support URL** for each app in App Store Connect.

## MDM Assign privacy policy

`mdm-assign-privacy.html` contains the MDM Assign privacy policy and is linked from the support page. Include this file when uploading the site.

Use `https://ljones517.github.io/app-support/mdm-assign-privacy.html` as MDM Assign’s **Privacy Policy URL** in App Store Connect.

## CasperWatch privacy policy

`casperwatch-privacy.html` contains the CasperWatch privacy policy and is linked from the support page. Include this file when uploading the site.

Use `https://ljones517.github.io/app-support/casperwatch-privacy.html` as CasperWatch’s **Privacy Policy URL** in App Store Connect.

## Edit or preview

Open any HTML file in a browser to preview it. Each page includes its own styling. The support email is `ljones@ljlabs.org`; update both the visible address and the `mailto:` link on all pages if it changes.
