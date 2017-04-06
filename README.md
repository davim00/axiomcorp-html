# Axiom Corporate Theme HTML

In order to more easily and quickly prototype a design for a Wordpress theme outside of an active Wordpress installation, this set of HTML files is built to offer a foundation for writing the CSS/SASS, HTML and JavaScript. The basic structure of the templates is based on [_s](https://github.com/Automattic/_s) by Automattic, with content and post/page formats pulled from the Wordpress [Theme Unit Test](https://codex.wordpress.org/Theme_Unit_Test).

## Getting Started

Currently the project is a collection of static HTML, SASS, CSS and JS files, which can be downloaded with the clone or download button on the project page. A Gruntfile has been included to automate compilation of files and live updating the web browser.

### Prerequisites for Grunt Functionality

To make use of the Gruntfile, you must have [Grunt](https://gruntjs.com/) set up on your system along with the following plugins:

```
grunt-contrib-watch
grunt-contrib-concat
grunt-contrib-uglify
grunt-contrib-sass
grunt-autoprefixer
```
Other plugins can be used or substituted at your own discretion provided the appropriate edits are made to the Gruntfile. An excellent guide to installing and setting up Grunt for front-end development can be found here: [Grunt for People Who Think Things Like Grunt are Weird and Hard](https://24ways.org/2013/grunt-is-not-weird-and-hard/).

### Using the Project

To begin editing the files for theme creation, download or clone the project to a local directory. Start up Grunt inside the project folder (if using Grunt), then open an HTML file in the browser that is equipped with the LiveReload extension. If set up properly, the file will automatically refresh whenever changes are made to the project files.

## Built With

* [_s](https://github.com/Automattic/_s) - Wordpress theme framework by Automattic
* [Theme Unit Test](https://codex.wordpress.org/Theme_Unit_Test) - Sample content data for testing Wordpress themes
* [Bootstrap](https://getbootstrap.com) - CSS and JavaScript library for creating responsive web layouts

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/davim00/axiomcorp-html/tags).

## Authors

* **Matt Davis** - *Initial work* - [davim00](https://github.com/davim00)

## License

This project is licensed under the GNU GPLv3 - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* All the good folks at Automattic, who's work has made it easier to build Wordpress themes the Wordpress way.
* The Twitter Bootstrap team, for also making my life so much easier
