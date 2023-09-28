# ratatui-async-template

<img width="757" alt="image" src="https://github.com/ratatui-org/ratatui-async-template/assets/1813121/f5c872fa-2c78-41af-82cd-717bdf7d0c1e">

### Features

- Uses [tokio](https://tokio.rs/) for async events
- Logs [tracing](https://github.com/tokio-rs/tracing)
- [better-panic](https://github.com/mitsuhiko/better-panic)
- [color-eyre](https://github.com/eyre/color-eyre)
- [human-panic](https://github.com/rust-cli/human-panic)
- Clap for command line argument parsing
- `Component` trait with
  [`App`](https://github.com/ratatui-org/ratatui-async-template/blog/main/src/components/app.rs)
  component as an example

### Usage

To generate a template locally:

```
$ cargo install cargo-generate
$ cargo generate --git https://github.com/ratatui-org/ratatui-async-template
```
