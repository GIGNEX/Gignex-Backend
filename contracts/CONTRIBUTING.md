# Contributing to Gignex Soroban Contracts

Thank you for contributing to the core logic of the Gignex Protocol!

## Development Guidelines

1. **Rust Standards**: Ensure all code is formatted using `cargo fmt` and passes `cargo clippy`.
2. **Security First**: Smart contract code requires rigorous scrutiny. Avoid `unwrap()` and prefer robust error handling with custom error types.
3. **Tests**: All new features or bug fixes must include unit tests. Use the Soroban test environment features to simulate auth and cross-contract calls.
4. **Gas Optimization**: Be mindful of storage vectors and computation complexity. Soroban meters both CPU instructions and ledger reads/writes.

## Submitting a PR
1. Open an issue first if proposing significant architectural changes.
2. Ensure `cargo test` passes locally.
3. Submit a PR describing your changes, with references to the issue.
