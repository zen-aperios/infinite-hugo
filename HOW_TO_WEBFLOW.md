# Infinite Hugo Webflow Setup

## 1) Add Assets

Head:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/zen-aperios/infinite-hugo@main/infinite-hugo.min.css" />
```

Footer (before `</body>`):

```html
<script src="https://cdn.jsdelivr.net/npm/gsap@3.12.5/dist/gsap.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/zen-aperios/infinite-hugo@main/infinite-hugo.min.js"></script>
```

## 2) Add Markup

Embed the structure from `index.html` (`#infinite`, `#world`, `#overlay`, `#tile-templates`).

## 3) Publish

Publish and hard refresh.

## 4) Pin Version (cache-safe)

```html
<script src="https://cdn.jsdelivr.net/gh/zen-aperios/infinite-hugo@<commit>/infinite-hugo.min.js"></script>
```
