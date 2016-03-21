# static-bootstrap

Bootstrap for static site with gulp + jade + minify + uglify

## Setup

## Structure

```
project
|-- _includes <-- Include files - http://jade-lang.com/reference/includes
    |-- footer.jade
    |-- navbar.jade
|-- _layouts <-- Layout files - http://jade-lang.com/reference/extends
    |-- default.jade
|-- _mixins <-- Mixin files - http://jade-lang.com/reference/mixins
|-- _site <-- Your jade files to site
    |-- contact.jade
    |-- features.jade
    |-- index.jade
|-- assets
    |-- images
    |-- javascripts
        |-- example.js
    |-- stylesheets
        |-- example.css
|-- dist <-- Folder with compiled files
|-- .editorconfig <-- Indentation  styles - http://editorconfig.org
|-- .gitignore
|-- gulpfile.js
|-- package.json
```

### Installation

[Install NodeJS](https://nodejs.org/en)

```bash
[sudo] npm install
```

## Launching

Compile files

```bash
gulp dist
```

Watch files

```bash
gulp watch
```

Preview compiled files

```bash
npm run preview
```

## Licence
[Licence](https://github.com/danielrohers/static-bootstrap/blob/master/LICENSE)
