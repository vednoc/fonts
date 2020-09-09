+++
title = "Fonts"
+++

# Fonts

Serving free and open-source fonts from [Vercel][V]'s global CDN.


### How to use?

You can choose between two link types:
1. `font` — includes _regular_, _italic_, _bold_, and _bold italic_ styles;
2. `font-all` — includes _all_ possible styles for a specific font.

Add a link to the font you want to use, e.g.:

```html
<link rel="stylesheet"
      href="https://fonts.imma.link/to/inter.css">
</link>
```

And then add this to your CSS file:

```css
body {
    font-family: 'Inter', 'fallback fonts...', sans-serif;
}
```

Beware of case-sensitivity — font path is _always_ lowercase.


[V]: https://vercel.com
