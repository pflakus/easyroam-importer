# easyroam-importer

![License](https://img.shields.io/github/license/pflakus/easyroam-importer)

A CLI tool to simplify setting up eduroam WiFi profiles on Linux systems generated through [easyroam](https://easyroam.de).

## Installation

Use Rust's `cargo` to install the application:

```bash
cargo install easyroam-importer
```

## Roadmap

- [ ] Document the steps to generate the .p12 certificate file from the easyroam website
- [ ] Generate private key, client and root cert files from a `.p12`-file
    - [ ] Document requirements derived from using `openssl` crate
- [ ] Print network profile configs and/or instructions to import for:
    - [ ] NetworkManager
    - [ ] netctl
    - [ ] wpa_supplicant
