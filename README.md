# Astronomy Data Microservice API

Small Rust microservice that exposes an HTTP API for astronomy data.

## Stack Used

- Rust
- Axum (web framework)
- Tokio (async runtime)
- Serde + Serde JSON (serialization)
- `libtad-rs` (astronomy data service client)

## API

- `GET /api/v1/astro_position` - returns astronomy position-related data from the service layer.
