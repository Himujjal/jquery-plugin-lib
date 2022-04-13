# A JQuery plugin library to be used for internal Spiralyze purposes

## Installation

You can directly use this library as a CDN in the HTML head:

```html
<script src="https://raw.githubusercontent.com/Himujjal/jquery-plugin-lib/master/dist/index.js"></script>
<link href="https://raw.githubusercontent.com/Himujjal/jquery-plugin-lib/master/dist/index.css"/>
```

## Publishing

Use git to publish the package

## Development

```
git clone https://github.com/Himujjal/jquery-plugin-lib
cd jquery-plugin-lib
npm i
npm run dev
```

Then open the file [test/index.html](./test/index.html) in your browser through the file manager.

The development server will automatically create a dev server. Edit the files in the `src` folder.

## How to import raw text as strings?

Use the `bundle-text:` prefix in the imports. ([Parcel inlining](https://parceljs.org/features/bundle-inlining/))

e.g.

```js
import text from 'bundle-text:./randomtext.htmlx';
```

NOTE: Don't use `.ext` prefix for such files. Here `.htmlx` prefix is used.

