# npmdoc-node-red-dashboard

#### basic api documentation for  [node-red-dashboard (v2.3.8)](https://github.com/node-red/node-red-dashboard#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-red-dashboard.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-red-dashboard) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-red-dashboard.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-red-dashboard)

#### A set of dashboard nodes for Node-RED

[![NPM](https://nodei.co/npm/node-red-dashboard.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-red-dashboard)

- [https://npmdoc.github.io/node-npmdoc-node-red-dashboard/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-red-dashboard/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-red-dashboard/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-red-dashboard/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-red-dashboard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-red-dashboard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/node-red/node-red-dashboard/issues"
    },
    "contributors": [
        {
            "name": "Andrei Tatar"
        },
        {
            "name": "Dave Conway-Jones"
        },
        {
            "name": "Joe Pavitt"
        },
        {
            "name": "Nick O'Leary"
        },
        {
            "name": "Dan Cunnington"
        },
        {
            "name": "Laurence Stant"
        }
    ],
    "dependencies": {
        "serve-static": "^1.11.2",
        "socket.io": "^1.7.3"
    },
    "description": "A set of dashboard nodes for Node-RED",
    "devDependencies": {
        "angular": "~1.5.11",
        "angular-animate": "~1.5.11",
        "angular-aria": "~1.5.11",
        "angular-chart.js": "^1.0.3",
        "angular-material": "^1.1.1",
        "angular-material-icons": "^0.7.1",
        "angular-messages": "~1.5.11",
        "angular-mocks": "~1.5.11",
        "angular-route": "~1.5.11",
        "angular-sanitize": "~1.5.11",
        "angular-touch": "~1.5.11",
        "angularjs-color-picker": "^2.7.2",
        "chart.js": "~2.3.0",
        "d3": "^3.5.17",
        "font-awesome": "^4.7.0",
        "gulp": "^3.9.1",
        "gulp-angular-templatecache": "^2.0.0",
        "gulp-clean-css": "^3.0.4",
        "gulp-concat": "^2.6.1",
        "gulp-header": "^1.8.8",
        "gulp-html-replace": "^1.6.2",
        "gulp-html-src": "^1.0.0",
        "gulp-htmlmin": "^3.0.0",
        "gulp-if": "^2.0.2",
        "gulp-insert-lines": "0.0.4",
        "gulp-jscs": "^4.0.0",
        "gulp-jshint": "^2.0.4",
        "gulp-manifest": "^0.1.1",
        "gulp-remove-html": "^1.3.0",
        "gulp-resources": "^0.5.0",
        "gulp-uglify": "^2.1.2",
        "gulp-util": "^3.0.8",
        "jquery": "^2.2.4",
        "jshint": "^2.9.4",
        "justgage": "^1.2.2",
        "less": "^2.7.2",
        "moment": "^2.18.1",
        "sprintf-js": "^1.0.3",
        "streamqueue": "^1.1.1",
        "svg-morpheus": "^0.3.0",
        "tinycolor2": "^1.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a270d7c6542075de1dc39cf7567c14db69b00dfd",
        "tarball": "https://registry.npmjs.org/node-red-dashboard/-/node-red-dashboard-2.3.8.tgz"
    },
    "gitHead": "991d95a5429404de61c6756369753fdbda9d584a",
    "homepage": "https://github.com/node-red/node-red-dashboard#readme",
    "keywords": [
        "node-red"
    ],
    "license": "Apache-2.0",
    "main": "none",
    "maintainers": [
        {
            "name": "dceejay"
        }
    ],
    "name": "node-red-dashboard",
    "node-red": {
        "version": ">=0.14.0",
        "nodes": {
            "ui_base": "nodes/ui_base.js",
            "ui_button": "nodes/ui_button.js",
            "ui_dropdown": "nodes/ui_dropdown.js",
            "ui_switch": "nodes/ui_switch.js",
            "ui_slider": "nodes/ui_slider.js",
            "ui_numeric": "nodes/ui_numeric.js",
            "ui_text_input": "nodes/ui_text_input.js",
            "ui_date_picker": "nodes/ui_date_picker.js",
            "ui_colour_picker": "nodes/ui_colour_picker.js",
            "ui_form": "nodes/ui_form.js",
            "ui_text": "nodes/ui_text.js",
            "ui_gauge": "nodes/ui_gauge.js",
            "ui_chart": "nodes/ui_chart.js",
            "ui_audio": "nodes/ui_audio.js",
            "ui_toast": "nodes/ui_toast.js",
            "ui_ui_control": "nodes/ui_ui_control.js",
            "ui_template": "nodes/ui_template.js",
            "ui_link": "nodes/ui_link.js",
            "ui_tab": "nodes/ui_tab.js",
            "ui_group": "nodes/ui_group.js"
        }
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/node-red/node-red-dashboard.git"
    },
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "version": "2.3.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
