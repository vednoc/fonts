+++
title = "Documentation"
template = "pages/docs.html"
+++

# Documentation

Work in progress!

---

## Getting started

You can choose between two link types:
1. `font` — includes `4` of the default font styles
    - Regular, _Italic_, __Bold__, and ___Bold Italic___ styles.
2. `font-all` — includes default and extra styles for a specific font
    - <u>Note</u>: Some of the fonts do _not_ have extra styles.


### Quick start

Add a link to font(s) you want to use in page `<head>`, e.g.:

```html
<link rel="stylesheet"
      href="https://fonts.imma.link/to/inter.css">
```

And then add this to your CSS file:

```css
body {
    font-family: 'Inter', 'fallback fonts...', sans-serif;
}
```

Beware of case-sensitivity — font path is _always_ lowercase.


### Save bandwidth on mobile devices

By using a conditional media query, you can choose when to load custom fonts,
thus making the load time faster on mobile devices.

```html, hl_lines=2
<link rel="stylesheet"
      media="screen and (min-width: 720px)"
      href="https://fonts.imma.link/to/inter.css">
```

---

## Font list

Fonts with WIP documentation. All [available fonts][1].


[1]: https://github.com/vednoc/fonts/tree/main/static/to
