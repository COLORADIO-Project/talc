# A fork of the [Talc Dynamic Memory Allocator](https://github.com/SFBdragon/talc) supporting Wasm's `custom-page-sizes` proposal

See the [original Talc repository](https://github.com/SFBdragon/talc) for extensive documentation.

This repository has a lot of the documentation and benchmarking of the original repository ripped out. This repository is only intended to be used until the original repository gains support for Wasm's `custom-page-sizes` proposal. This version of the repository is largely untested.

To support 1-byte-pages, select the `1-byte-pages` feature of this crate. This implementation is only meant to work for our use case. See the [discussion in an issue on the original repository](https://github.com/SFBdragon/talc/issues/42) for more context.

## Getting started

- [The original `talc` README](https://github.com/SFBdragon/talc/blob/master/talc/README.md)
- [The original `talc` README for WebAssembly](https://github.com/SFBdragon/talc/blob/master/talc/README_WASM.md)
