[![CI](https://github.com/iddm/redis-custom-allocator/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/redis-custom-allocator/actions/workflows/ci.yml)
[![Crates](https://img.shields.io/crates/v/redis-custom-allocator.svg)](https://crates.io/crates/redis-custom-allocator)
[![Docs](https://docs.rs/redis-custom-allocator/badge.svg)](https://docs.rs/redis-custom-allocator)
[![License](https://img.shields.io/badge/license-RSALv2_or_SSPLv1-blue?style=flat&logo=license)](./LICENSE)

# Custom redis allocator for Rust.

This crate provides a drop-in replacement for the standard
(nightly-only) [Allocator](https://doc.rust-lang.org/std/alloc/trait.Allocator.html)
trait in Rust.

The reason it is provided it to stabilise the code base of the projects
requiring and using the custom allocator and to avoid using the nightly
code.

# MSRV (Minimally-Supported Rust Version)

The `MSRV` is `1.70`.

# LICENSE

[License](./LICENSE)
