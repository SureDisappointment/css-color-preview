<h1 align="center">
  <img src="./assets/icon.png" alt="CSS Color Preview" height="128" />
</h1>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=luie.css-color-preview"><img src="https://vsmarketplacebadges.dev/version-short/luie.css-color-preview.svg" alt="version" /></a>
  <a href="https://marketplace.visualstudio.com/items?itemName=luie.css-color-preview"><img src="https://vsmarketplacebadges.dev/downloads-short/luie.css-color-preview.svg" alt="downloads" /></a>
</p>

<p align="center">
  Preview colors for CSS files in Visual Studio Code.
</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/d619d658-ddb1-4116-8bf1-c00876cbe873" alt="Preview" />
</p>

## Custom File Patterns

By default, Color Preview works with standard CSS files (css, scss, sass, less, postcss).

You can configure the extension to support additional file patterns, such as CSS-in-JS files:

```json
"cssColorPreview.additionalFilePatterns": [
  "**/*.css.ts",
  "**/*.styles.ts",
  "**/*.styled.tsx"
]
```

## Acknowledgements:

- [OKLCH Preview](https://github.com/dotnize/oklch-preview) by dotnize, which this extension was forked from.

## License

[MIT](LICENSE)
