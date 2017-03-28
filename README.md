Teegee Tool
---

Teegee Tool `tgtool` is a utility tool written in rust lang specifically for 
[TeegeeCraft]. Provides helpful utilities for managing minecraft servers. 
Licensed under the [MIT] license

# Cloning
> Ensure that you have [git] installed.

Run:
* `git clone https://github.com/kinggoesgaming/tgtool.git` or 
* (if you have SSH setup) `git clone git@github.com:kinggoesgaming/tgtool.git`.

# Installing Rust
TeegeeTool is written in [rust]. In order to [build](#building) the tool you need to install the rust toolchain.
1. Go to the rust [website][rust] and follow the instructions given.
2. Open Command Prompt (Windows) or Terminal (macOS/ Linux) and type 
`rustup default stable`

# Building
> Ensure that you have [rust] installed. See 
[Installing Rust](#installing-rust) section.

Run:
* `cd tgtool`
* `cargo build --release`

The binary file will be located in the `target/release` directory named `tgtool(.exe)`

[TeegeeCraft]: http://teegeecraft.net
[MIT]: LICENSE
[git]: https://git-scm.com/download/
[rust]: https://www.rust-lang.org/en-US/install.html
