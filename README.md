# Age-verification service — integration source

An age-verification service codebase containing an Express backend, browser flow source and example integrations for Node.js and PHP.

**Status:** Legacy integration/reference codebase. Existing Go.cam-related attribution does not imply certification of this repository or its owner.

## Scope

- TypeScript backend source and generated JavaScript application files.
- Twig views and Sass/browser-side build source.
- Node.js and PHP iframe/redirect integration examples.
- Gulp build/watch scripts and benchmark notebooks.

## Technology

TypeScript, Express, Twig.

## Architecture and source map

- `source/backend/app/` — backend source
- `source/frontend/` — browser and style source
- `app/` — compiled application and views
- `script/gulpfile.js` — build pipeline
- `example/` — integration examples
- `LICENSE` — existing license terms

## Local development

Requires Node.js and npm. The package declares:

```sh
npm install
npm run build
npm run startDev
```

`npm run startProd` runs the compiled backend; `npm run watch` starts the Gulp watchers. Build helpers live in `script/gulpfile.js`. Confirm Gulp/toolchain availability and backend configuration before running. These commands were not executed in this documentation review.

## Configuration and limitations

Review backend configuration and required external services before testing. The original README refers to Go.cam and third-party certification pages; those references are not evidence that this copy is certified or authored entirely from scratch. Generated files coexist with source, so validate the build pipeline before changing either.

## Portfolio relevance

A reference for understanding web integration boundaries and JavaScript/PHP client examples; distinguish upstream code from local changes.

## Documentation next steps

Capture screenshots using synthetic data, document a reproducible test run, and record which integrations have been verified. Keep credentials and deployment-specific configuration outside version control.
