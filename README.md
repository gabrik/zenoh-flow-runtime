# Eclipse Zenoh-Flow Runtime

[![Join the chat at https://gitter.im/atolab/zenoh-flow](https://badges.gitter.im/atolab/zenoh-flow.svg)](https://gitter.im/atolab/zenoh-flow?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Zenoh-Flow provides a zenoh-based dataflow programming framework for computations that span from the cloud to the device.

:warning: **This software is still in alpha status and should _not_ be used in production. Breaking changes are likely to happen and the API is not stable.**

-----------
## Description

Zenoh-Flow single runtime

-----------

### Runtime
First, let's build an example runtime to run the examples
```bash
cargo build --release -p runtime
```

This will create the runtime binary in `./target/release/runtime`
