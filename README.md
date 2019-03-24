# Pollination OpenAPI Specification
[![Build Status](https://travis-ci.org/ladybug-tools-in2/energy-model-schema.svg?branch=master)](https://travis-ci.org/ladybug-tools-in2/energy-model-schema)

## Energy Model Schema

## Links

- [Reference Documentation (ReDoc)](https://ladybug-tools-in2.github.io/energy-model-schema/)
- OpenAPI Raw Files: [JSON](https://ladybug-tools-in2.github.io/energy-model-schema/openapi.json) [YAML](ladybug-tools-in2.github.io/energy-model-schema/openapi.yaml)

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
Deploys docs to GitHub Pages. You don't need to run this manually thanks to [Travis CI](https://travis-ci.org/ladybug-tools-in2/energy-model-schema).
