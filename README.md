# css-background-clip 0.0.7

Css module of single purpose classes for background clip

#### Stats

206 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-background-clip
```

#### With Git

```
git clone https://github.com/tachyons-css/css-background-clip
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-background-clip";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-background-clip">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   BACKGROUND CLIP
*/
.bg-clip-bb { background-clip: border-box; }
.bg-clip-pb { background-clip: padding-box; }
.bg-clip-cb { background-clip: content-box; }
@media screen and (min-width: 48em) {
 .bg-clip-bb-ns { background-clip: border-box; }
 .bg-clip-pb-ns { background-clip: padding-box; }
 .bg-clip-cb-ns { background-clip: content-box; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .bg-clip-bb-m { background-clip: border-box; }
 .bg-clip-pb-m { background-clip: padding-box; }
 .bg-clip-cb-m { background-clip: content-box; }
}
@media screen and (min-width: 64em) {
 .bg-clip-bb-l { background-clip: border-box; }
 .bg-clip-pb-l { background-clip: padding-box; }
 .bg-clip-cb-l { background-clip: content-box; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

