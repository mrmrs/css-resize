# css-resize 0.0.6

Css module of single purpose classes for resize

#### Stats

202 | 16 | 16
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-resize
```

#### With Git

```
git clone https://github.com/tachyons-css/css-resize
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-resize";
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
<link rel="stylesheet" href="path/to/module/css/css-resize">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   RESIZE
*/
.resize-none { resize: none; }
.resize-both { resize: both; }
.resize-hor { resize: horizontal; }
.resize-ver { resize: vertical; }
@media screen and (min-width: 48em) {
 .resize-none-ns { resize: none; }
 .resize-both-ns { resize: both; }
 .resize-hor-ns { resize: horizontal; }
 .resize-ver-ns { resize: vertical; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .resize-none-m { resize: none; }
 .resize-both-m { resize: both; }
 .resize-hor-m { resize: horizontal; }
 .resize-ver-m { resize: vertical; }
}
@media screen and (min-width: 64em) {
 .resize-none-l { resize: none; }
 .resize-both-l { resize: both; }
 .resize-hor-l { resize: horizontal; }
 .resize-ver-l { resize: vertical; }
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
