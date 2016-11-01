# css-background-clip 1.0.6

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

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-background-clip
```

ssh:
```
git clone git@github.com:tachyons-css/css-background-clip.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-background-clip";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-background-clip@1.0.6/css/css-background-clip.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-background-clip">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

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

ISC

