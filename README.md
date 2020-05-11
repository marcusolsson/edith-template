# Site template for Edith

[![License MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)
[![PRs welcome!](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contribute)

This repository is a template that lets you get started with Edith using [GitHub Pages](https://pages.github.com/).

To use this template:

1. Click **Use this template** on the GitHub project page.
1. In **Repository name**, enter the name of your site.
1. Click **Create repository from template**

This template is built to be served as a [GitHub project page](https://help.github.com/en/github/working-with-github-pages/about-github-pages#types-of-github-pages-sites). This means that we need to configure Edith to add a prefix to all internal links.

1. In `gatsby-config.js`, change the `pathPrefix` property to the name of your repository:

   ```js
   module.exports = {
     siteMetadata: {
       title: "Site name",
     },
     plugins: ["gatsby-theme-edith"],
     pathPrefix: "/<repository-name>",
   }
   ```

1. Go to the **Actions** tab and wait for the workflow to finish.

1. Go to the **Settings** tab and scroll down to **GitHub Pages**.
1. In **Source**, click the drop-down menu and select `gh-pages`.

   It's already selected, but you need to select it anyways to trigger the publish.

Your site will be available at `https://<username>.github.io/<repository-name>`. Keep in mind that it can take up to 20 minutes for GitHub to publish your page.

## License

This starter is licensed under the [MIT License](LICENSE).
