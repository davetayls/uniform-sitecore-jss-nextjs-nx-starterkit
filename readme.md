# Uniform - Sitecore JSS - Next.js starter kit

This repo contains both the starter kit with content items and required configuration files.

You can also use this kit to start a vanilla project, simply remove everything from `/src/components` and adjust the Sitecore site name from `uniform-jss-kit` to whatever you want and get cracking.

## Docs

1. [Tutorial for Deploy part of this starter kit](https://docs.uniform.dev/sitecore/deploy/getting-started/sitecore-jss-nextjs-tutorial)

2. [Uniform for Sitecore docs](https://docs.uniform.dev/sitecore/deploy/introduction/)

## Pre-requisites
1. Sitecore 9.x-10.x instance available with Sitecore JSS installed and configured
1. "Uniform for Sitecore" installed and configured on your Sitecore instance. Check out the docs.
1. Install the Sitecore package with items from `/sitecore/App_Data/packages` folder.

## Getting started with the app

> Check out official docs for more scenarios and [tutorial](https://docs.uniform.dev/sitecore/deploy/getting-started/sitecore-jss-nextjs-tutorial).

### TL;DR version

1. Add `NPM_TOKEN` environment variable with the value we provided you with.
1. `npm install`
1. `jss setup` and follow the steps Sitecore JSS requires and use the API key you created during the Pre-requisites step above.
1. `jss deploy config` to deploy the application config from `/sitecore/config` folder into your Sitecore instance.
1. Configure `.env` file according to your environment specifics (see `.env-example` file).
1. `npm run build` to build the app.
1. `npm run dev` to start development server.
1. `npm start` to start the app in connected mode.
1. `npm run export` to run static export.
