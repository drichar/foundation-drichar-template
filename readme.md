# Front-End Start Point

Built with the official ZURB Template for use with [Foundation for Sites](http://foundation.zurb.com/sites). It has a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript concatenation
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## Installation

Requirements:

* NodeJS (0.12 or greater)
* Bower
* Git

### Local Development

```bash
git clone git@github.com:drichar/foundation-drichar-template.git projectname
cd projectname
npm install && bower install
```

Then run `npm start` to run Gulp. Flattened/processed files will be created in a folder called `dist`, which is rebuilt whenever watched files in `src` change. BrowserSync will serve files from `dist` at:

```
http://localhost:8000
```

To create compressed, production-ready assets, run `npm run build`.
