
### Rust documentation

[Rust docs](https://www.rust-lang.org/learn)

[Rust by example](https://doc.rust-lang.org/stable/rust-by-example) includes example code blocks that can be run in the browser

### VS code extensions for Rust

`rust-analyzer`   For code completion, syntax highlighting etc...  

`CodeLLDB`   Debugger for Rust and C++  

To automatically format rust code on file save set `editor.formatOnSave` on save in settings, or to enable it only for rust files add the following to vscode's settings.json file:
```json
   "[rust]": {
        "editor.formatOnSave": true,
    }
```

### Clippy
A collection of rust lint tools

Installation:
```
rustup component add clippy
```
Running:
```
cargo clippy
```
[Clippy docs on github](https://github.com/rust-lang/rust-clippy)


### Tarpaulin
Tarpaulin is a code coverage reporting tool

Installation:
```
cargo install cargo-tarpaulin
```
Running:
```
cargo tarpaulin
```
[Tarpaulin docs on github](https://github.com/xd009642/tarpaulin)



