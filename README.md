# Mohsen — Landing Page

A responsive one-page landing site built while learning HTML and CSS. It's a personal/portfolio-style page with a header and mega menu, a hero ("landing") section, and a series of content sections: articles, gallery, features, testimonials, team members, services, skills progress bars, "how it works" steps, an event countdown, pricing plans, top videos, stats, a discount request form, and a footer.

## Live Demo

[_Click Here](https://zzmozz.github.io/html-css-landing-page/)

## Built With

- **HTML5** — semantic page structure
- **CSS3** — custom styles in [`css/master.css`](css/master.css)
- **[Font Awesome](https://fontawesome.com/)** — icons (`css/all.min.css` + `webfonts/`)
- **[Google Fonts](https://fonts.google.com/specimen/Cairo)** — Cairo font family

No build tools, frameworks, or JavaScript are used — it's plain static HTML/CSS.

## Project Structure

```
.
├── index.html      # single-page site markup
├── css/
│   ├── master.css  # custom page styles
│   └── all.min.css # Font Awesome
├── imgs/           # images used across all sections
└── webfonts/       # Font Awesome font files
```

## Running Locally

No build step is required. Either:

- Open `index.html` directly in a browser, or
- Serve the folder with a local static server, e.g.:
  ```
  npx serve .
  ```

## Status

This was built as a learning exercise for HTML/CSS fundamentals (layout, flexbox/grid, responsive design, and styling components like nav menus, cards, and progress bars). Content such as names, testimonials, and Lorem Ipsum text is placeholder.
