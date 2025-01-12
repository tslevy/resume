# Résumé Template
The purpose of this project is to make as easy as possible for less-technical people to create and host a professional resume on GitHub Pages.

## Getting started

All the content for the site can be editing using either the `_data` files or the `index.md` file.

### Configuring settings

In `settings.yml`, you can edit the following:

- Title of site (appears in browser tab)
- Site description (appears in search results and social previews)
- Font (from Google Fonts)
- Accent color (from Pico themes)

### Adding personal information

In `personal.yml`,  you can edit the following:

- Name and headline
- Contact information (phone number only appears in print, not on live website, though it is still visible in page source)

### Adding work and school content

Use `work.yml` and `school.yml` to add items for these sections. See the format included as a comment in those files. Links are optional.

### Changing headings and adding additional content

Use `index.md` to edit everything else. This is a regular markdown file that includes all the headings and additional sections at the bottom. Use GitHub-flavored markdown to format content. The header, work, and school sections are imported when the site builds.

## Work with site preview using the GitHub Codespaces remote dev environment
This project is configured to work with Codespaces. This allows you work on variations of the site in a remote development environment in your browser so you can try things out without publishing directly to the live, `main` branch for edit you make.

To use this option, create a codespace from the `Code` menu button.

This will launch a "virtual computer" running a temporary version of the site. Make changes and view them in the simple browser. When done, push your changes to GitHub. Then stop the codespace.

For more information, see the [GitHub documentation](https://docs.github.com/en/codespaces/developing-in-a-codespace/creating-a-codespace-for-a-repository).

## Credit and license
This project was created using the [GitHub Pages gem for Jekyll](https://github.com/github/pages-gem) and [Pico CSS](https://picocss.com/).

Favicon is `Soft Ice Cream` from [Twemoji](https://twemoji.twitter.com/), licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).
