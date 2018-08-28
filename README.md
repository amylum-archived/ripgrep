ripgrep
=========

[![Build Status](https://img.shields.io/travis/com/amylum/ripgrep.svg)](https://travis-ci.com/amylum/ripgrep)
[![GitHub release](https://img.shields.io/github/release/amylum/ripgrep.svg)](https://github.com/amylum/ripgrep/releases)
[![MIT Licensed](https://img.shields.io/badge/license-MIT-green.svg)](https://tldrlegal.com/license/mit-license)

This is my package repo for [ripgrep](https://github.com/BurntSushi/ripgrep)

The `upstream/` directory is taken directly from upstream. The rest of the repository is my packaging scripts for compiling a distributable build.

## Usage

To build a new package, update the submodule and run `make`. This launches the docker build container and builds the package.

To start a shell in the build environment for manual actions, run `make manual`.

## License

The ripgrep upstream code is dual licensed under the Unlicense and MIT. My packaging code is MIT licensed.

