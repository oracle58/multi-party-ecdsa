# Multi-Party ECDSA

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

This project is a Rust implementation of {t,n}-threshold ECDSA (elliptic curve digital signature algorithm) by [zengo x](https://github.com/ZenGo-X).

## Contributions & Development Process
The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md), in addition **the [Rust utilities wiki](https://github.com/KZen-networks/rust-utils/wiki) contains information on workflow and environment set-up**.


## License
Multi-party ECDSA is released under the terms of the GPL-3.0 license. See [LICENSE](LICENSE) for more information.

## References
* [Gennaro, Goldfeder 20](https://eprint.iacr.org/2020/540.pdf): A full threshold protocol that supports identifying malicious parties. If signing fails - a list of malicious parties is returned. The protocol requires only a broadcast channel (all messages are broadcasted).


