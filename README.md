# Static Boilerplate

Simple Boilerplate I use for static projects of mine.
Based on [Google's Web Starter Kit](https://github.com/google/web-starter-kit/blob/master/docs/install.md)

[DEMO HERE](http://excerebrose.github.com/static-boilerplate) and [Personal website](http://harjyotsingh.com)
## Setup
- Fork the repository
- `yarn install`
- Update [manifest.json](./app/manifest.json) and [manifest.webapp](./app/manifest.webapp) to your project name and description
- Update humans.txt
- Update CNAME to point to your custom domain name
- Replace [icons](./app/images/touch) and [favicon](./app/favicon)

## To Run
- `gulp serve` for local webserver
- `gulp deploy` to deploy to Github Pages (remember to update branch name in [Gulpfile](./gulpfile.babel.js))
