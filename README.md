# libpanic_unwind

Rust's panic unwinding crates implemented out-of-tree for use in `#[no_std]` or `xargo`-sysroot
environments. All dependencies, aside from `libpanic_unwind`'s dependency on `libunwind`,
are set as optional so that they can be pulled from the sysroot if needed.