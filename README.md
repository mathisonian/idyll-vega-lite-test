# idyll-vega-lite-test

See it live: https://mathisonian.github.io/idyll-vega-lite-test/index.html

## Installation

- Make sure you have `idyll` installed (`npm i -g idyll`).
- Clone this repo and run `npm install`.

## Developing a post locally

Run `idyll`.

## Building a post for production

Run `idyll build --no-minify`. The output will appear in the top-level `build` folder. To change the output location, change the `output` option in `package.json`.

_The no minify flag must be used because of a current bug minifying the vega-lite component_


## Deploying

Make sure your post has been built, then deploy the docs folder via any static hosting service.

## Dependencies

You can install custom dependencies by running `npm install <package-name> --save`. Note that any collaborators will also need download the package locally by running `npm install` after pulling the changes.
