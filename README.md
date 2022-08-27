# libfdu
A universal SDK for FDU.

## Building
You need **[Rust](https://www.rust-lang.org) Nightly** installed:

```shell
$ rustup default nightly
```

Build the library by running:

```shell
$ cargo build
```

or 

```shell
$ cargo build --release
```

You will find the library files `*.dll & *.dll.lib`, `*.dylib`, or `*.so` in the `target/debug` or `target/release` directory, and C header is `bindings.h` in the project root directory.


## Contribution
You can contribute to the project by opening an issue or creating a pull request.

To get familiar with the library, you are encouraged to read the comments in the source code directly.