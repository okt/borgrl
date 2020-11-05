[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)

## borgrl

A rougelike written in Rust as a means of learning the language. 
Feel free to look about. 



### Compilation
To build a release build for WASM. 
```
cargo build --release --target wasm32-unknown-unknown
```

To build a release for the `wasm/` hosted website presentaion.
```
wasm-bindgen target/wasm32-unknown-unknown/release/borgrl.wasm --out-dir wasm --no-modules --no-typescript
```
