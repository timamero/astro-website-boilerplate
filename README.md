# Astro Boilerplate

## Tech Stack

| Technology | Purpose            |
| ---------- | ------------------ |
| AstroJS    | Frontend Framework |
| ESLint     | Linting            |
| Stylelint  | CSS Linting        |
| Prettier   | Formatting         |
| Netlify    | Deployment         |
| AstroSEO   | SEO Plugin         |
| Decap CMS  | Content Management |

## Getting Started

### Install packages

`npm run install`

### Next, set up Netlify continuous deployment

1. Connect your repository

   `netlify init`

2. Select Create & configure a new site.
3. Select Team.
4. Input site name.
5. Confirm build command (npm run build).
6. Confirm directory to deploy.
7. Confirm creation of netlify.toml.

### Then, configure Decap CMS

1. Follow steps to enable [Identity](https://docs.netlify.com/security/secure-access-to-sites/identity/) and [Git Gateway](https://docs.netlify.com/security/secure-access-to-sites/git-gateway/#setup-and-settings)
2. [Set registration preferences (optional)](https://docs.netlify.com/security/secure-access-to-sites/identity/registration-login/)

### Resources for installing tech stack

- [Install and set up Astro](https://docs.astro.build/en/install-and-setup/)
- [eslint-plugin-astro](https://github.com/ota-meshi/eslint-plugin-astro)
- [prettier-plugin-astro](https://github.com/withastro/prettier-plugin-astro)
- [Get VSCode, eslint & prettier working with Astro](https://patheticgeek.dev/blog/astro-prettier-eslint-vscode)
- [stylelint-config-html](https://github.com/ota-meshi/stylelint-config-html)
- [stylelint: Getting started](https://stylelint.io/user-guide/get-started)
- [Netlify](https://docs.netlify.com/cli/get-started/)
- [astro-seo](https://github.com/jonasmerlin/astro-seo)
- [Decap CMS & Astro](https://docs.astro.build/en/guides/cms/decap-cms/)
- [netlify-identity-widget](https://github.com/netlify/netlify-identity-widget)
- [Configure Decap CMS](https://decapcms.org/docs/configure-decap-cms/)
- [netlifydocs: Reconnect after changing repository permissions](https://docs.netlify.com/security/secure-access-to-sites/git-gateway/#reconnect-after-changing-repository-permissions)

## Development References and Resources

- [Responsive navbar tutorial using HTML CSS & JS](https://www.youtube.com/watch?v=HbBMp6yUXO0)
- [Material Design Color Chart](https://htmlcolorcodes.com/color-chart/material-design-color-chart/)
