# Rust Live Training

## Launch Codespaces

* rustc --version
* An alternative is (Rust Up): `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
* hello world: `cargo new hello`

```
tree
.
├── hello
│   ├── Cargo.toml
│   └── src
│       └── main.rs
├── LICENSE
├── Makefile
└── README.md

```

## Local

### ASDF
Install Rust via asdf

- Install asdf https://asdf-vm.com/
- Install Rust 
  - https://github.com/asdf-community/asdf-rust
  - `asdf install rust latest` or 
  - list all the version `asdf list-all rust` then
  - `asdf install rust <version>`

### Look into RUSTUP
Look into Rustup https://rustup.rs/

# Make a new project
- Run `cargo new project_name`