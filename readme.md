# Campaign Boilerplate

All the campaign page essentials, ready to go.

## Getting Started

#### Install

from terminal...

```
$ cd your-working-dir
$ git clone https://github.com/ishiiprints/Campaign-boiler new-page-name
$ cd new-page-name
$ npm install
$ npm run start
$ code .
```

* Go to your working directory,
* Clone this repo into a new folder called "new-page-name"
* Install project dependencies
* Start up Gulp
* Open the directory in Visual Code Editor.

Additionally, you can rename the project in 'package.json'.

#### Build

* HTML - views/your-html.html
* JS - js/script.js
* CSS - css/style.css
* SASS - sass/style.scss
* Additional scripts can be included in index.html eg; Cloudinary.

#### Dist

Once you're happy with your campaign page, prepare it for the CMS.

1.  Create a copy of your-html.html, and rename as a new territory specific file, eg: UK.html.
2.  Copy and Paste the contents of css/style.css into style tags atop the page.
3.  Copy and Paste the contents of js/script.js into script tags at the bottom of the page.
4.  Prepare your layout XML with all the extra scripts included in index.html (jquery not required)
5.  Test out on test12.
