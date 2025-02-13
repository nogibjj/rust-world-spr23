# A Repo of Rust Exploring in Spring 2023
[![Rustfmt](https://github.com/mianwu515/rust-world-spr23/actions/workflows/rustfmt.yml/badge.svg)](https://github.com/mianwu515/rust-world-spr23/actions/workflows/rustfmt.yml)
[![Clippy](https://github.com/mianwu515/rust-world-spr23/actions/workflows/lint.yml/badge.svg)](hhttps://github.com/mianwu515/rust-world-spr23/actions/workflows/lint.yml)
[![Build binary release](https://github.com/mianwu515/rust-world-spr23/actions/workflows/release.yml/badge.svg)](https://github.com/mianwu515/rust-world-spr23/actions/workflows/release.yml)

- Build weekly Rust projects into this Repo

![Rust](https://blog.logrocket.com/wp-content/uploads/2020/09/best-rust-http-client.png)

## Introduction
- _Cargo.toml_ file and _./src/_ are created with command `cargo init --name "[project name]"`
- In the _./src/_ directory, there are two files (_main.rs_ and _lib.rs_)
    -  The `main` function is in the _main.rs_ file.
    -  Most logics and self-defined functions are in the _lib.rs_ file.

## Usage and reproduce
- Open Codespaces
    - set up your own CPU/GPU choice
    - Run ```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh``` to install [Rust](https://rustup.rs/) if you haven't installed one
- `cd` into each project
    * Run `cargo run -- --help`
    * Edit and run `make format` to format code

- use df to get a full summary of disk filesystem
```bash
df -h # df means "disk filesystem"; it's used to get a full summary of available and used disk space usage of the file system on the Linux system. "-h" means human-readable
```

* [rust-cli-example](https://github.com/nogibjj/hello-rust)
* [rust-new-project-template](https://github.com/noahgift/rust-new-project-template)
* [rust-tutorial-spring2023](https://nogibjj.github.io/rust-tutorial/)