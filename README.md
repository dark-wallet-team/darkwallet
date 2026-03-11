# Darkwallet

[![Release](https://img.shields.io/badge/Release-0.8.0-2563eb)](https://github.com/dark-wallet-team/darkwallet)
[![License](https://img.shields.io/badge/License-AGPLv3-15803d)](./COPYRIGHT)
[![Project](https://img.shields.io/badge/Project-Bitcoin%20Wallet-0f766e)](https://github.com/dark-wallet-team/darkwallet)
[![Status](https://img.shields.io/badge/Status-Legacy%20Codebase-b45309)](https://github.com/dark-wallet-team/darkwallet)
[![Stack](https://img.shields.io/badge/Stack-AngularJS%20%7C%20Grunt%20%7C%20Bower-b45309)](https://github.com/dark-wallet-team/darkwallet)

Darkwallet is a privacy-focused Bitcoin wallet codebase maintained by `dark-wallet-team`. This repository preserves the original project and provides a clean base for documentation, compatibility work, and source maintenance.

## Features

- Legacy Bitcoin wallet architecture
- Client-side key and identity handling
- Privacy-oriented project design
- AngularJS frontend with background service logic
- Legacy build and test tooling for restoration work

## Installation

Clone the repository:

```bash
git clone git@github.com:dark-wallet-team/darkwallet.git
cd darkwallet
```

Install dependencies:

```bash
npm install
npm install -g grunt-cli bower
bower install
```

## Usage

This repository contains a legacy Bitcoin wallet codebase with browser-oriented application structure. For local inspection or restoration work, load it from the repository root and use the build commands below.

1. Open the extensions page.
2. Enable Developer mode.
3. Click `Load unpacked`.
4. Select the repository root.

Common commands:

```bash
grunt build
npm test
```

## Build By OS

| OS | Setup | Build |
| --- | --- | --- |
| Linux | Install `git`, `node`, and `npm` | `npm install && bower install && grunt build` |
| macOS | Install Git and Node.js | `npm install && bower install && grunt build` |
| Windows | Use PowerShell or Git Bash with Git and Node.js installed | `npm install && bower install && grunt build` |

Notes:

- On Windows, global packages may need an elevated shell.
- On modern browsers, this legacy codebase may require compatibility fixes before it loads correctly.

## Project Structure

| Path | Purpose |
| --- | --- |
| `src/js/backend` | Background process logic and services |
| `src/js/frontend` | AngularJS controllers, directives, and UI logic |
| `src/js/model` | Wallet models and storage-related code |
| `src/js/util` | Shared utility modules |
| `src/html` | Extension pages, partials, and modal views |
| `src/sass` | Source stylesheets |
| `test` | Karma-based test suite |

## Contributing

Contributions should stay focused on documentation, compatibility fixes, dependency cleanup, and test recovery. Keep larger refactors documented and scoped.

## License

This project is distributed under the terms described in [COPYRIGHT](./COPYRIGHT).
