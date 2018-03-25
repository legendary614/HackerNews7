[![video](https://raw.githubusercontent.com/i18next/react-i18next/master/example/nextjs-locize/video_sample.png)](https://youtu.be/kw-GEQbgmSc)

[watch the video](https://youtu.be/kw-GEQbgmSc)

[relevant changes](https://github.com/i18next/react-i18next/commit/b5cd5c07f73d52d306fae4833203d9adc7edd839)

# Getting started

Build with [next.js](https://github.com/zeit/next.js/).

```bash
# npm install
# npm run dev
```

**open:**

auto detecting user language: [http://localhost:3000](http://localhost:3000)

german: [http://localhost:3000/?lng=de](http://localhost:3000/?lng=de)

english: [http://localhost:3000/?lng=en](http://localhost:3000/?lng=en)


## The idea behind the example

This example app shows how to integrate [react-i18next](https://github.com/i18next/react-i18next) with [Next](https://github.com/zeit/next.js) and locize backend.

## using with locize

We added our translation management [locize.com](http://locize.com).

- [i18next-locize-backend](https://github.com/locize/i18next-locize-backend)
- [i18next-node-locize-backend](https://github.com/locize/i18next-node-locize-backend)

You will find your project informations like projectId and apiKey on your locize projects settings. (Signup add a new project for testing).

Set projectId and apiKey in `/locize.json`.

**Plus:**

- Routing and separating translations into multiple files (lazy load them on client routing)
- Child components (pure or using translation hoc)

### Features of this example app

- Server-side language negotiation
- Full control and usage of i18next on express server using [i18next-express-middleware](https://github.com/i18next/i18next-express-middleware) which asserts no async request collisions resulting in wrong language renderings
- Support for save missing features to get untranslated keys automatically created `locales/{lng}/{namespace}.missing.json` -> never miss to translate a key
- Proper pass down on translations via initialProps
- Taking advantage of multiple translation files including lazy loading on client (no need to load all translations upfront)
- Use express to also serve translations for clientside
- In contrast to react-intl the translations are visible both during development and in production

### learn more

- [next.js](https://github.com/zeit/next.js)
- [react-i18next repository](https://github.com/i18next/react-i18next)
- [react-i18next documentation](https://react.i18next.com)

**Translation features:**

- [i18next repository](https://github.com/i18next/i18next)
- [i18next documentation](https://www.i18next.com)

**Translation management:**

- [locize](http://locize.com)
