JS Scratch Pad
==

A simple template for creating ES2015 JavaScript with React JS.

Uses Browserify.

`npm install`

Building and watching
---

Building is started via shell scripts that are driven by npm.

Make sure that the files in `./build` have execute permissions

`chmod u+x ./build/*.sh`

---

`npm run build` builds the app code only to `dist/bundle.js`

`npm run build-vendor` build the vendor (react) code only to `dist/vendor.js`

`npm run watch` builds the app code only to `dist/bundle.js` but watches for further changes.
