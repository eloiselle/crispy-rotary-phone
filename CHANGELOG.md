# 2.1.0

- Migrate to `css-minifier-webpack-plugin`

# 2.0.1

## Fixes

- Fix broken css linking in production build

# 2.0.0

## Breaking Changes

- drop redux
- remove counter example app
- simplify directory structure
- move `dll` dir to `.erb` dir
- fix icon/font import paths
- migrate to `react-refresh` from `react-hot-loader`
- migrate to webpack@5
- migrate to electron@11
- remove e2e tests and testcafe integration
- rename `app` dir to more conventional `src` dir
- rename `resources` dir to `assets`
- simplify npm scripts
- drop stylelint
- simplify styling of boilerplate app
- remove `START_HOT` env variable
- notarize support
- landing page boilerplate
- docs updates
- restore removed debugging support

# 1.4.0

- Migrate to `eslint-config-erb@2`
- Rename `dev` npm script to `start`
- GitHub Actions: only publish GitHub releases when on master branch

# 1.3.1

- Fix sass building bug ([#2540](https://github.com/electron-react-boilerplate/electron-react-boilerplate/pull/2540))
- Fix CI bug related to E2E tests and network timeouts
- Move automated dependency PRs to `next` ([#2554](https://github.com/electron-react-boilerplate/electron-react-boilerplate/pull/2554))
- Bump dependencies to patch semver

# 1.3.0

- Fixes E2E tests ([#2516](https://github.com/electron-react-boilerplate/electron-react-boilerplate/pull/2516))
- Fixes preload entrypoint ([#2503](https://github.com/electron-react-boilerplate/electron-react-boilerplate/pull/2503))
- Downgrade to `electron@8`
- Bump dependencies to latest semver

# 1.2.0

- Migrate to redux toolkit
- Lazy load routes with react suspense
- Drop support for azure-pipelines and use only github actions
- Bump all deps to latest semver
- Remove `test-e2e` script from tests (blocked on release of https://github.com/DevExpress/testcafe-browser-provider-electron/pull/65)
- Swap `typed-css-modules-webpack-plugin` for `typings-for-css-modules-loader`
- Use latest version of `eslint-config-erb`
- Remove unnecessary file extensions from ts exclude
- Add experimental support for vscode debugging
- Revert https://github.com/electron-react-boilerplate/electron-react-boilerplate/pull/2365 as default for users, provide as opt in option

# 1.1.0

- Fix #2402
- Simplify configs (https://github.com/electron-react-boilerplate/electron-react-boilerplate/pull/2406)

# 1.0.0

- Migrate to TypeScript from Flow ([#2363](https://github.com/electron-react-boilerplate/electron-react-boilerplate/pull/2363))
- Use browserslist for `@babel/preset-env` targets ([#2368](https://github.com/electron-react-boilerplate/electron-react-boilerplate/pull/2368))
- Use preload script, disable `nodeIntegration` in renderer process for [improved security](https://www.electronjs.org/docs/tutorial/security#2-do-not-enable-nodejs-integration-for-remote-content) ([#2365](https://github.com/electron-react-boilerplate/electron-react-boilerplate/pull/2365))
- Add support for azure pipelines ([#2369](https://github.com/electron-react-boilerplate/electron-react-boilerplate/pull/2369))
- Disable sourcemaps in production
