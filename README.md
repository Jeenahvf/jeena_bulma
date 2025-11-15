## What is Bulma?

Bulma is a modern CSS framework built on **Flexbox**. It makes building responsive layouts super easy, without touching JavaScript. Everything is ready-to-use with simple CSS classes.

## Getting Started

### Using CDN
Add this in your `<head>` to start quickly:

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/bulma@0.9.4/css/bulma.min.css"
/>
````

### Using NPM

Install via npm:

```bash
npm install bulma
```

Then import it in your project:

```scss
@import "bulma/bulma";
```


## Core Ideas

* **Flexbox Layouts:** All components use Flexbox for alignment.
* **Responsive:** Works on mobile, tablet, desktop, and bigger screens.
* **Modifiers:** Easy to change colors, sizes, and states using classes like:

  * `.is-primary`, `.is-info` for colors
  * `.is-small`, `.is-large` for sizes
  * `.is-active`, `.is-loading` for states


## Common Components

### Layout

* **Container:** Wrap content neatly.
* **Section:** Create page sections.
* **Columns:** Easy grid layouts.
* **Hero:** Big banners with titles/subtitles.

### Elements

* **Button:** `<button class="button is-primary">Click Me</button>`
* **Title / Subtitle:** `<h1 class="title">Main</h1>`
* **Box:** `<div class="box">Content here</div>`
* **Tags:** `<span class="tag is-warning">New</span>`
* **Table:** `<table class="table is-striped is-hoverable">...</table>`

### Forms

* Text input, textarea, selects, checkboxes, radios.
* Add icons or buttons easily with `has-icons-left` or `has-addons`.

### Navbar & Cards

* Navbar: `<nav class="navbar">...</nav>`
* Cards: `<div class="card">...</div>`

## Helpers & Utilities

Bulma comes with handy helpers:

* **Spacing:** `m-2`, `p-3`, `mt-4`
* **Text:** `.has-text-centered`, `.has-text-weight-bold`
* **Flex:** `.is-flex`, `.is-justify-content-center`
* **Visibility:** `.is-hidden-mobile`, `.is-hidden-desktop`


## Customizing Bulma

You can override variables with Sass before importing:

```scss
$primary: #4a65f6;
@import "bulma/bulma";
```

## Resources

* Official site: [https://bulma.io](https://bulma.io)
* Documentation: [https://bulma.io/documentation](https://bulma.io/documentation)

readme.md
