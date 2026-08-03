# Rust project template

My slightly opinionated template for Rust projects of any size.

[![GitHub Stars](https://img.shields.io/github/stars/lpireyn/rust-project-template)](https://github.com/lpireyn/rust-project-template)
[![GitHub Watchers](https://img.shields.io/github/watchers/lpireyn/rust-project-template)](https://github.com/lpireyn/rust-project-template)
[![GitHub Forks](https://img.shields.io/github/forks/lpireyn/rust-project-template)](https://github.com/lpireyn/rust-project-template)
[![GitHub Issues](https://img.shields.io/github/issues/lpireyn/rust-project-template)](https://github.com/lpireyn/rust-project-template/issues)
[![Common Changelog](https://common-changelog.org/badge.svg)](https://common-changelog.org)
[![Unlicense](https://img.shields.io/github/license/lpireyn/rust-project-template)](https://unlicense.org/)

## Features

- Cargo workspace with any number of crates -- libraries and/or binaries
- Readme
- Changelog
- Clippy configuration
- rustfmt configuration
- Git configuration
- EditorConfig configuration
- GitHub workflows

## Usage

The template is rooted in [`template`](template).

To use the template:

1. Create a directory for your project (no need to run `cargo new` or `cargo init`)
2. Copy the contents of the `template` directory recursively, including the hidden files, to your project directory
3. Rename/Remove the `tbd-lib` and/or the `tbd-bin` crate(s) in the `crates` directory
4. Review all the elements containing the `TBD:` string and modify them accordingly

## Changelog

See [`CHANGELOG.md`](CHANGELOG.md).

## License

This is free and unencumbered software released into the public domain.

See [`UNLICENSE`](UNLICENSE).
