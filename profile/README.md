# Vetis Server

Vetis Server is a Rust-focused ecosystem for building lightweight, modular, and high-performance web services. The organization brings together a core HTTP server, runtime adapters, feature crates, and integration modules that can be combined to match the needs of a modern backend.

The projects here are designed to stay small, composable, and fast without sacrificing flexibility. Whether you need a minimal request server, static file serving, proxying, WebSocket support, scripting hooks, or observability and security integrations, Vetis offers a clean set of building blocks.

## Core projects

- [vetis](https://github.com/vetis-server/vetis) — A blazingly fast, minimalist HTTP server built for modern Rust applications.
- [vetis-server](https://github.com/vetis-server/vetis-server) — Server-side components and supporting modules that complement the core framework.
- [vetis-templates](https://github.com/vetis-server/vetis-templates) — Templates for bootstrapping a Vetis web server project.
- [vetis-contrib](https://github.com/vetis-server/vetis-contrib) — Shared contribution code and ecosystem utilities for Vetis projects.

## Runtime adapters

- [vetis-tokio](https://github.com/vetis-server/vetis-tokio) — Tokio runtime support for Vetis.
- [vetis-compio](https://github.com/vetis-server/vetis-compio) — Compio runtime support for Vetis.
- [vetis-smol](https://github.com/vetis-server/vetis-smol) — smol runtime support for Vetis.
- [vetis-glommio](https://github.com/vetis-server/vetis-glommio) — Glommio runtime support for Vetis.

## Features and integrations

- [vetis-auth](https://github.com/vetis-server/vetis-auth) — Authentication hooks and middleware for protecting Vetis services.
- [vetis-dns](https://github.com/vetis-server/vetis-dns) — DNS and host-resolution hooks for routing, upstream discovery, and network integration.
- [vetis-encode](https://github.com/vetis-server/vetis-encode) — Content-encoding and compression hooks for efficient response delivery.
- [vetis-static](https://github.com/vetis-server/vetis-static) — Static file serving with caching and multi-runtime support.
- [vetis-flash](https://github.com/vetis-server/vetis-flash) — Fast static-content serving utilities built on top of Vetis.
- [vetis-log](https://github.com/vetis-server/vetis-log) — Logging extensions for structured request and application logs.
- [vetis-matchers](https://github.com/vetis-server/vetis-matchers) — Request and response matchers for flexible route and response logic.
- [vetis-otel](https://github.com/vetis-server/vetis-otel) — OpenTelemetry integration for traces, metrics, and observability.
- [vetis-proxy](https://github.com/vetis-server/vetis-proxy) — HTTP proxy support for forwarding requests to upstream services.
- [vetis-rev-proxy](https://github.com/vetis-server/vetis-rev-proxy) — Reverse proxy capabilities for Vetis applications.
- [vetis-rewrite](https://github.com/vetis-server/vetis-rewrite) — URL rewrite hooks for adapting routing and request paths.
- [vetis-rhai](https://github.com/vetis-server/vetis-rhai) — Rhai scripting integration for extensibility.
- [vetis-ws](https://github.com/vetis-server/vetis-ws) — WebSocket support for interactive client-server communication.
- [vetis-wt](https://github.com/vetis-server/vetis-wt) — WebTransport support for modern transport-level features.

## Additional projects

- [front](https://github.com/vetis-server/front) — Front-end or application-facing tooling associated with the Vetis ecosystem.

## Why Vetis

Vetis is built for developers who want:

- small, explicit building blocks instead of heavyweight frameworks
- support for multiple async runtimes without rewriting application code
- modular feature crates that can be added when needed
- a fast path for building web services in Rust

## Getting started

1. Review the core server in [vetis](https://github.com/vetis-server/vetis).
2. Pick the runtime adapter that matches your stack: [vetis-tokio](https://github.com/vetis-server/vetis-tokio), [vetis-compio](https://github.com/vetis-server/vetis-compio), [vetis-smol](https://github.com/vetis-server/vetis-smol), or [vetis-glommio](https://github.com/vetis-server/vetis-glommio).
3. Add the feature modules you need, such as [vetis-static](https://github.com/vetis-server/vetis-static), [vetis-proxy](https://github.com/vetis-server/vetis-proxy), [vetis-dns](https://github.com/vetis-server/vetis-dns), [vetis-auth](https://github.com/vetis-server/vetis-auth), [vetis-log](https://github.com/vetis-server/vetis-log), or [vetis-otel](https://github.com/vetis-server/vetis-otel).
4. Use [vetis-templates](https://github.com/vetis-server/vetis-templates) to start new projects with a sensible base.

## Contributing

This organization is open to contributions across the ecosystem. If you want to improve a crate, add a feature, or fix a bug:

- open an issue in the relevant repository
- work from a feature branch
- submit a pull request with a clear explanation and any relevant tests

## Organization

- [.github](https://github.com/vetis-server/.github) — GitHub configuration and organization-level community files
