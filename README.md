# CSS BACKGROUND CLIP

  Mobile-first classes for css-background-clip.
  Set the desired css-background-clip on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-background-clip
```
or download the css on github and include in your project.

## File Size


## The Code
```
.bg-clip-bb { background-clip: border-box; }
.bg-clip-pb { background-clip: padding-box; }
.bg-clip-cb { background-clip: content-box; }

@include break(not-small) {
  .bg-clip-bb-ns { background-clip: border-box; }
  .bg-clip-pb-ns { background-clip: padding-box; }
  .bg-clip-cb-ns { background-clip: content-box; }
}

@include break(medium) {
  .bg-clip-bb-m { background-clip: border-box; }
  .bg-clip-pb-m { background-clip: padding-box; }
  .bg-clip-cb-m { background-clip: content-box; }
}

@include break(large) {
  .bg-clip-bb-l { background-clip: border-box; }
  .bg-clip-pb-l { background-clip: padding-box; }
  .bg-clip-cb-l { background-clip: content-box; }
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

