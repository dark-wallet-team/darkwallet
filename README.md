# Darkwallet

[![Repository](https://img.shields.io/badge/repo-dark--wallet--team%2Fdarkwallet-181717?logo=github)](https://github.com/dark-wallet-team/darkwallet)
[![Branch](https://img.shields.io/badge/branch-develop-0A7B83)](https://github.com/dark-wallet-team/darkwallet/tree/develop)
[![License](https://img.shields.io/badge/license-COPYRIGHT-blue)](./COPYRIGHT)
[![Status](https://img.shields.io/badge/status-legacy%20codebase-orange)](https://github.com/dark-wallet-team/darkwallet)

Darkwallet is a privacy-focused Bitcoin wallet codebase maintained in this repository by `dark-wallet-team`. This fork preserves the original project, keeps the source available for research and maintenance, and provides a clean base for documentation and restoration work.

## Features

- Browser-extension wallet architecture
- Client-side key and identity handling
- Privacy-oriented project design
- AngularJS-based frontend and background service model
- Legacy test and build tooling for restoration work

## Installation

Clone the repository:

```bash
git clone git@github-dark-wallet-team:dark-wallet-team/darkwallet.git
cd darkwallet
```

Install development dependencies:

```bash
npm install
npm install -g grunt-cli bower
bower install
```

## Usage

Load the project as an unpacked extension in a Chromium-based browser:

1. Open the browser extensions page.
2. Enable Developer mode.
3. Click `Load unpacked`.
4. Select the repository root.

Useful development commands:

```bash
grunt build
npm test
```

Note: this is a legacy extension codebase and may require compatibility fixes for current browser versions.

## Project Structure

| Path | Purpose |
| --- | --- |
| `src/js/backend` | Background process logic and services |
| `src/js/frontend` | AngularJS controllers, directives, and UI logic |
| `src/js/model` | Wallet models and storage-related code |
| `src/js/util` | Shared utility modules |
| `src/html` | Extension HTML views, modals, and partials |
| `src/sass` | Source stylesheets |
| `test` | Karma-based test suite |

## License

License and copyright details are provided in [COPYRIGHT](./COPYRIGHT).
```
