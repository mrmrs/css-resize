# css-resize

Functional CSS for resize

## Filesize

| File | Size |
|------|------|
| `dist/resize.css` | 785 bytes |
| `dist/resize.min.css` | 555 bytes (164 Gzipped) |

## Install

```sh
npm install css-resize
```

## Usage

### Import

```css
@import "css-resize";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-resize/dist/resize.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-resize/dist/resize.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.resize-none` | `resize: none;` |
| `.resize-both` | `resize: both;` |
| `.resize-hor` | `resize: horizontal;` |
| `.resize-ver` | `resize: vertical;` |
| `.resize-none-s` | `resize: none;` |
| `.resize-both-s` | `resize: both;` |
| `.resize-hor-s` | `resize: horizontal;` |
| `.resize-ver-s` | `resize: vertical;` |
| `.resize-none-m` | `resize: none;` |
| `.resize-both-m` | `resize: both;` |
| `.resize-hor-m` | `resize: horizontal;` |
| `.resize-ver-m` | `resize: vertical;` |
| `.resize-none-l` | `resize: none;` |
| `.resize-both-l` | `resize: both;` |
| `.resize-hor-l` | `resize: horizontal;` |
| `.resize-ver-l` | `resize: vertical;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.resize-none-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/resize.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/resize.css` — formatted
- `dist/resize.min.css` — minified

## License

MIT
