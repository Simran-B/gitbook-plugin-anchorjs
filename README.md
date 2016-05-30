# Anchor.js for Gitbook

Adds deep links to headlines.

```js
{
  "plugins": ["anchorjs"]
}
```

The deep links to page sections are initially-hidden and pop into view on hover.
Design and behavior can adjusted in `book.json`:

```
{
  "pluginsConfig": {
    "anchorjs": {
      "icon": "#",
      "placement": "left",
      "visible": "always"
    }
  }
}


See [anchor.js](https://github.com/bryanbraun/anchorjs) docs for details.
