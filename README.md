## Practicing Rust Programming Language

### Install Rust
Use Rustup a installer and version management tool.
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

To keep Rust up to date, use the following command
```
rustup update
```

### Cargo : The Rust build tool and package manager

**cargo build** : To build your project

**cargo run** : To run your project

**cargo test** : To test your project

**cargo doc** : Build documentation for your project

**cargo publish** : Publish a library or package to cargo.io

**cargo --version** : To check that you have installed Rust and Cargo.
<hr>

## Generating a new project

```
cargo new hello-world
```
Use this command to generate a new project and build below files inside the directory
```
hello-rust
    - Cargo.toml
    - src
        - main.rs
```

## Adding dependencies
You can add dependencies in the Cargo.toml file to your project.
```
cargo build
```

Or simply run **cargo add ferris-says@0.2**

And then run below command to install the dependencies
```
cargo build
```
This will create cargo.lock file which has exact same dependencies we are using.

## Resources to learn Rust
https://www.rust-lang.org/learn

https://doc.rust-lang.org/book/

