# css-background-clip

Functional CSS for background-clip

## Filesize

| File | Size |
|------|------|
| `dist/background-clip.css` | 769 bytes |
| `dist/background-clip.min.css` | 593 bytes (162 Gzipped) |

## Install

```sh
npm install css-background-clip
```

## Usage

### Import

```css
@import "css-background-clip";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-background-clip/dist/background-clip.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-background-clip/dist/background-clip.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.bg-clip-bb` | `background-clip: border-box;` |
| `.bg-clip-pb` | `background-clip: padding-box;` |
| `.bg-clip-cb` | `background-clip: content-box;` |
| `.bg-clip-bb-s` | `background-clip: border-box;` |
| `.bg-clip-pb-s` | `background-clip: padding-box;` |
| `.bg-clip-cb-s` | `background-clip: content-box;` |
| `.bg-clip-bb-m` | `background-clip: border-box;` |
| `.bg-clip-pb-m` | `background-clip: padding-box;` |
| `.bg-clip-cb-m` | `background-clip: content-box;` |
| `.bg-clip-bb-l` | `background-clip: border-box;` |
| `.bg-clip-pb-l` | `background-clip: padding-box;` |
| `.bg-clip-cb-l` | `background-clip: content-box;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.bg-clip-bb-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/background-clip.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/background-clip.css` — formatted
- `dist/background-clip.min.css` — minified

## License

MIT
