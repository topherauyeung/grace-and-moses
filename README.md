# Grace & Moses Wedding Website

## Dev environment
To set up a convenient dev environment run this at the root:

```bash
    npm install .
    npm install -g gulp
```

Then run

```
    gulp
```

Gulp is a javascript task runner. It compiles sass, lints the compiled css, and sets up a livereload server so you can save your fingers from pressing ⌘+r

* Once you add & commit files you are ready to publish run:
```bash
git push -u origin master
```

## Rake tasks

Start sass development - watches the sass folder and updates css/i.css with every file change
```bash
rake sass
```

Start sass - output is minified to css/i.css
```bash
rake minify
```

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

