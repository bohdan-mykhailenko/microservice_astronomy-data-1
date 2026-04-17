# Astronomy Data Microservice API

Small Rust microservice that exposes an HTTP API for astronomy data.

## Stack Used

- [Rust](https://www.rust-lang.org/)
- [Axum](https://docs.rs/axum/latest/axum/) (web framework)
- [Tokio](https://tokio.rs/) (async runtime)
- [Serde](https://serde.rs/) + [Serde JSON](https://docs.rs/serde_json/latest/serde_json/) (serialization)
- [`libtad-rs`](https://crates.io/crates/libtad-rs) (astronomy data service client)

## API

- `GET /api/v1/astro_position` - returns astronomy position-related data from the service layer.
