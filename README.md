# Rust project template

My slightly opinionated template for Rust projects of any size.

## Features

- Cargo workspace with any number of crates -- libraries and/or binaries
- Readme
- Changelog
- Clippy configuration
- rustfmt configuration
- Git configuration
- EditorConfig configuration

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
