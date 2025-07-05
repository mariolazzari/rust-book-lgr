# Ultimate Rust tutorial 

Rust programming [book](https://doc.rust-lang.org/book/)

## Getting started

[docs](https://doc.rust-lang.org/stable/book/ch01-00-getting-started.html)

### Installation

[docs](https://doc.rust-lang.org/stable/book/ch01-01-installation.html)

```sh
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```

### Hello world

[docs](https://doc.rust-lang.org/stable/book/ch01-02-hello-world.html)

```rust
fn main() {
    println!("Hello, world!");
}
```

### Cargo

[docs](https://doc.rust-lang.org/stable/book/ch01-03-hello-cargo.html)

```sh
cargo new hello-cargo
cargo build
cargo run
cargo check
```

## Programming a guess game

[docs](https://doc.rust-lang.org/stable/book/ch02-00-guessing-game-tutorial.html)

```sh
cargo new guessing_game
cd guessing_game
cargo add rand
cargo build
cargo add colored
```