GitHub Profile Search
======================

GitHub user search allows to search for gitHub profiles by username.

Getting started:
----------------
*Run `git clone https://github.com/DovileSand/gitHub_profiles` in your chosen directory.
*Run `npm install` to install dependancies.


Usage:
------

*Navigate to main project folder and run `open public/index.html` in the command line, project will open in the default browser automatically.
*Project is deployed at `https://git-user-search-.herokuapp.com/`


Running tests:
--------------

*For testing with karma, navigate to the main project folder and run `karma start test/karma.conf.js`
*To run protractor test boot the following:
`webdriver-manager start`
`http-server`

While both above are running in the separate command line tabs, enter below to start protractor test:
`protractor test/e2e/conf.js`


Frameworks, utilities and libraries used:
------------------------------
*AngularJS
*Bower package manager
*Jasmine testing framework
*Karma plugin - adapter for Jasmine
*PhantomJS headless browser
*Protractor
*GitHub API
