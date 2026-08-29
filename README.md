# rusty_err

> **This repository has moved.** `rusty_err` now lives at
> [`crates/rusty_err`](https://github.com/Rusty-Mill/rusty_mill/tree/main/crates/rusty_err)
> in the [`rusty_mill`](https://github.com/Rusty-Mill/rusty_mill) monorepo, with full commit
> history preserved. This repository is kept for historical reference and is no longer
> developed; please open issues and pull requests against `rusty_mill` instead.

A `#![no_std]` + `alloc` sovereign error trait, context extension, and
`#[derive(Error)]` proc-macro for the **Rusty Mill** ecosystem — a
`no_std`-safe alternative to `thiserror` + `anyhow`.

## Status
Active — early (0.1.0), single maintainer (baileyrd).

## Getting started
```bash
git clone https://github.com/baileyrd/rusty_err
cd rusty_err
cargo build --workspace
```

## Architecture
See [ARCHITECTURE.md](./ARCHITECTURE.md) for boundaries, key decisions, and data flow.

## Development
```bash
cargo test --workspace
cargo clippy --workspace --all-targets
```

## Contributing
See [CONTRIBUTING.md](./CONTRIBUTING.md).

## Security
See [SECURITY.md](./SECURITY.md) to report a vulnerability.

## License
MIT OR Apache-2.0
