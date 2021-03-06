### 3.1.1
- Minor optimizations

## 3.1.0
- Now linter loads 13 times faster! (#1695)


## 3.0.0
- Improve performance (#1706)
- Rewrite diff check algorithm (#1706)
- Fix linter fixes (#1706)

In case you maintain a linter-ui packages (e.g. linter-ui-default, linter-minimap), see this guide for upgrading: https://github.com/steelbrain/linter/blob/master/docs/guides/upgrading-to-linter-v3.md

## 2.3.1

- Upgrade dependencies to fix vulns

## 2.3.0

- Remove support for legacy linter APIs
- Add a button to open developer console on Linter error messages
- Include `description` in message key (when string rather than promise)
- Fix a bug where linter messages (file-scoped) would disappear when same buffer is opened in two editors and one of them is closed

## 2.2.0

- `linter:debug` overhaul with more debug information
- Add `linterName` support to messages API v2 (Thanks @hansonw from Facebook)

## 2.1.4

- Hotfix release for a regression introduced in last version (sorry everyone)

## 2.1.3

- Add `disabledProviders` config that tracks the list of disabled linter providers
- Enhance linter provider error message to include opening instructions for dev tools

## 2.1.2

- Hotfix release for a regression introduced in last version

## 2.1.1

- Unset no longer available v1 configs
- Make `linter.name` optional for v1 again
- Do not show Linter v2 for greeter for new installations
- Fix a bug where disabling and reenabling `linter-ui-default` would not add previously existent issues to the UI

## 2.1.0

- Add support for Legacy Indie Providers v1
- Move docs to GitHub pages, docs can now be found at [`steelbrain.me/linter`](http://steelbrain.me/linter)

## 2.0.0

- Rewrite entire package
- Add support for Linter Messages v2
- Add support for Indie Providers v2
- Drop support for Indie Providers v1

## Pre v2.0

See the CHANGELOG for Pre v2.0 at [v1 CHANGELOG](https://github.com/steelbrain/linter/blob/v1/CHANGELOG.md)
