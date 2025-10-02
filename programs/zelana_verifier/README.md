# Zelana Verifier Crate

- Groth 16 verifier smart contract

## Creating a crate
1. Login
```
cargo login <your_api_key>
```

2. Insert in `Cargo.toml`
```toml
[package]
name = "zelana_verifier"
version = "0.1.0"
description = "ZK proof verifier smart contract"
edition = "2021"
license = "MIT"
repository = "https://github.com/Zelana-Labs/zelana-verifier"
readme = "README.md"
```

3. Create the crate 
```
cargo package
```

4. Run some tests on your crate using the `.crate file`


5. Publish
```
cargo publish
```