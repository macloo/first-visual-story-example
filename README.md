# Disclaimer

This is the result of working through the instructional doc with the original template, which is: 

https://github.com/datadesk/baker-example-page-template 

This is the instructional doc I used: 

https://palewi.re/docs/first-visual-story/index.html 

I subbed in GitHub Desktop for all the command-line git parts. It worked fine. 


## baker-example-page-template

A demonstration of how to build and publish pages with the [baker](https://github.com/datadesk/baker) build tool.

The Los Angeles Times uses baker to create the static pages published at latimes.com/projects. The Times system relies on a private version of a repository much like this one. This simplified example publishes [staging](http://baker-example-page-template-staging.s3-website-us-east-1.amazonaws.com/baker-example-page-template/main/) and [production](http://baker-example-page-template-production.s3-website-us-east-1.amazonaws.com/baker-example-page-template/) versions to public buckets on Amazon S3. 

## Features

- 🔃 Live-updating local test server
- 🖨️ HTML templating with [Nunjucks](https://mozilla.github.io/nunjucks/)
- 🖌️ Extended CSS with [Sass](https://sass-lang.com/)
- 🗞️ JavaScript bundling with [Rollup](https://www.rollupjs.org/guide/en/) and [Babel](https://babeljs.io/) 
- 🔢 Data imports with [quaff](https://github.com/rdmurphy/quaff)
- 🥞 Dynamic page generation based on structured inputs
- 🏭 Automatic deployment of each branch to a staging environment on each `push` event via [GitHub Action](https://github.com/datadesk/baker-example-page-template/actions/workflows/deploy-stage.yml)
- 🌎 Push button deployment to the production environment on each `release` event via [GitHub Action](https://github.com/datadesk/baker-example-page-template/actions/workflows/deploy-prod.yml)
- 🔔 Slack messages that relay each deployment's status via [datadesk/notify-slack-on-build](https://github.com/datadesk/notify-slack-on-build) Github Action

## Requirements

* [Node.js](https://nodejs.org/en/) version 12, 14 or 16, though at minimum 12.20, 14.14, or 16.0.
* [Node Package Manager](https://www.w3schools.com/whatis/whatis_npm.asp)
* [git](https://git-scm.com/)

