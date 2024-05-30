# RLP

A fast and simple [RLP][rlp] implementation in Rust.

[rlp]: https://ethereum.org/en/developers/docs/data-structures-and-encoding/rlp

## Supported Rust Versions

<!--
When updating this, also update:
- .clippy.toml
- Cargo.toml
- .github/workflows/ci.yml
-->

Team will keep a rolling MSRV (minimum supported rust version) policy of **at
least** 6 months. When increasing the MSRV, the new Rust version must have been
released at least six months ago. The current MSRV is 1.64.0.

Note that the MSRV is not increased automatically, and only as part of a minor
release.

## Contributing

Thanks for your help improving the project! We are so happy to have you! We have
[a contributing guide](./CONTRIBUTING.md) to help you get involved in the project.

Pull requests will not be merged unless CI passes, so please ensure that your
contribution follows the linting rules and passes clippy.

## Provenance note

These crates were originally part of the [core] project, as [`core_rlp`] and [`core_rlp_derive`].

`core_rlp` was forked from an earlier Apache-licensed version of the [`fastrlp`]
crate, before it changed licence to GPL. The Rust `fastrlp` implementation is
itself a port of the [Golang Apache-licensed fastrlp][gofastrlp].

[core]: https://github.com/core-coin/core
[`core_rlp`]: https://github.com/core-coin/core/tree/e2218bea37aa455b4fd6602fe71a8fbe0974f12b/crates/rlp
[`core_rlp_derive`]: https://github.com/core-coin/core/tree/e2218bea37aa455b4fd6602fe71a8fbe0974f12b/crates/rlp/rlp-derive
[`fastrlp`]: https://github.com/vorot93/fastrlp
[gofastrlp]: https://github.com/umbracle/fastrlp

#### License

<sup>
Licensed under either of <a href="LICENSE-APACHE">Apache License, Version
2.0</a> or <a href="LICENSE-MIT">MIT license</a> at your option.
</sup>

<br>

<sub>
Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in these crates by you, as defined in the Apache-2.0 license,
shall be dual licensed as above, without any additional terms or conditions.
</sub>
