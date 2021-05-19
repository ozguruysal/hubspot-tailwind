# Hubspot Tailwind CSS Starter

Starter project for building HubSpot themes with Tailwind CSS and Webpack.

### Install

Run `yarn` or `npm install` to install dependencies

### Scripts
- `start` : Builds project with webpack, uploads to your `defaultPortal` specified in `hubspot.config.yml` and watches for changes via [`@hubspot/webpack-cms-plugins/HubSpotAutoUploadPlugin`](https://www.npmjs.com/package/@hubspot/webpack-cms-plugins).
- `build` : Clears `/dist` contents and builds project into `/dist`.
- `deploy` : Clears `/dist` contents, builds project into `/dist`, and uploads to via [`@hubspot/cms-cli`](https://www.npmjs.com/package/@hubspot/cms-cli).
- `upload`: Uploads the `/dist` contents to your `defaultPortal` specified in `hubspot.config.yml`.
