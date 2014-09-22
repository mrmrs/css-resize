# CSS RESIZE

  Mobile-first classes for css-resize.
  Set the desired css-resize on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-resize
```
View on [npm](https://www.npmjs.org/package/css-resize)


## File Size

750B resize.css
594B resize.min.css

## The Code
```
.resize-none { resize: none; }
.resize-both { resize: both; }
.resize-hor  { resize: horizontal; }
.resize-ver  { resize: vertical; }

@media screen and (min-width: 48em) {
  .resize-none-ns { resize: none; }
  .resize-both-ns { resize: both; }
  .resize-hor-ns  { resize: horizontal; }
  .resize-ver-ns  { resize: vertical; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .resize-none-m { resize: none; }
  .resize-both-m { resize: both; }
  .resize-hor-m  { resize: horizontal; }
  .resize-ver-m  { resize: vertical; }
}

@media screen and (min-width: 64em)  {
  .resize-none-l { resize: none; }
  .resize-both-l { resize: both; }
  .resize-hor-l  { resize: horizontal; }
  .resize-ver-l  { resize: vertical; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

