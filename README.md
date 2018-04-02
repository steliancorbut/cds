# [Bootstrap - CDS](https://github.com/steliancorbut/cds)

## Preview

**[View Live Preview](http://cdsromania.ro/)**

## Download and Installation

To begin using this template, choose one of the following options to get started:
* [Download the latest release on Bootstrap CDS](https://github.com/steliancorbut/cds)
* Clone the repo: `git clone https://github.com/steliancorbut/cds.git`

## Usage

After download/unzip/installation, in resulted folder run:
- `npm install` for node_modules. (Node.js must exist)
- `npm install -g gulp` this will install Gulp.js globally (if you haven`t)
- `gulp` the default task that builds everything or `gulp vendor` to copy dependencies from node_modules to the vendor directory

to develop run
- `gulp dev` which will open up a preview of the index.html in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. 
You can view the `gulpfile.js` to see which tasks are included with the dev environment.

#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp sass` compiles SCSS files into CSS
- `gulp minify-css` minifies the compiled CSS file
- `gulp minify-js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory

## Copyright and License

Code released under the [MIT](https://github.com/steliancorbut/cds/blob/master/LICENSE) license.
