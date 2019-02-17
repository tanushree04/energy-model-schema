# pollination OpenAPI Specification
[![Build Status](https://travis-ci.org/pollination/api.svg?branch=master)](https://travis-ci.com/pollination/api)

## Links

- [Reference Documentation (ReDoc)](https://pollination.github.io/api/)
- OpenAPI Raw Files: [JSON](https://pollination.github.io/api/openapi.json) [YAML](https://pollination.github.io/api/openapi.yaml)

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server.

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
