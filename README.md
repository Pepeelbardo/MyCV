# Jose Luis Sarabia — Online CV

Personal CV / portfolio page built as part of the HyperionDev Software
Engineering bootcamp, deployed with GitHub Pages for **Practical Task 2**.

## About this project

A single-page online CV that introduces me professionally while showing a
bit more personality than a traditional resume: background, skills,
education, work experience, and a couple of projects I've built during the
bootcamp.

## Live site

https://Pepeelbardo.github.io/MyCV

## Project structure

```
index.html                    Main page (required by GitHub Pages)
vendor/bootstrap/              Bootstrap 5.3.3 CSS & JS (self-hosted, no CDN)
vendor/bootstrap-icons/        Bootstrap Icons 1.11.3 (self-hosted, no CDN)
```

Bootstrap and Bootstrap Icons are vendored locally inside the repo instead
of loaded from a CDN, so the page doesn't depend on a third-party service
being up.

## Tech

- HTML5
- CSS3 (embedded in `index.html`)
- [Bootstrap 5](https://getbootstrap.com/) for layout and components
- [Bootstrap Icons](https://icons.getbootstrap.com/)

## Deployment

Hosted for free with [GitHub Pages](https://pages.github.com/), served
directly from the `main` branch of this public repository.
