# tracing-measureme

A [`tracing`] layer for generating timing reports using [`measureme`]

[Documentation][docs-rs] | [Crate][crates-io]

## Overview

[`tracing`] is a framework for instrumenting Rust programs in a scoped
and structured way. [`tracing-measureme`] provides a way to record the time
that a [`Span`] takes using [`measureme`] and outputting it using the format specified
by [`measureme`] which can be read by different tools that can be found in the [measureme repository][`measureme`].

### License

This project is either licensed under [MIT] or [Apache-2.0]

[`tracing`]: https://github.com/tokio-rs/tracing
[`measureme`]: https://github.com/rust-lang/measureme
[`Span`]: https://docs.rs/tracing/0.1/tracing/span/index.html
[docs-rs]: https://docs.rs/tracing-measureme
[crates-io]: https://crates.io/crates/tracing-measureme
[MIT]: https://github.com/Stupremee/tracing-measureme/tree/master/LICENSE-MIT
[Apache-2.0]: https://github.com/Stupremee/tracing-measureme/tree/master/LICENSE-APACHE
