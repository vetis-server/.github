# Vetis Server

Vetis Server is a Rust-focused ecosystem for building lightweight, modular, and high-performance web services. The organization brings together a core HTTP server, runtime adapters, feature crates, templates, and supporting utilities that let developers assemble a stack that matches their runtime and deployment needs.

The projects here are designed to stay small, composable, and fast without sacrificing flexibility. Whether you need a minimal request server, static file serving, proxying, WebSocket support, scripting, or runtime-specific integrations, the Vetis ecosystem is structured to provide the pieces you need.

## Core projects

- [vetis](https://github.com/vetis-server/vetis) — A blazingly fast, minimalist HTTP server built for modern Rust applications.
- [vetis-server](https://github.com/vetis-server/vetis-server) — Server-side components and supporting modules that complement the core framework.
- [vetis-templates](https://github.com/vetis-server/vetis-templates) — Templates for bootstrapping a Vetis web server project.
- [vetis-contrib](https://github.com/vetis-server/vetis-contrib) — Logging, observability, and authentication modules for Vetis applications.

## Runtime adapters

- [vetis-tokio](https://github.com/vetis-server/vetis-tokio) — Tokio runtime support for Vetis.
- [vetis-compio](https://github.com/vetis-server/vetis-compio) — Compio runtime support for Vetis.
- [vetis-smol](https://github.com/vetis-server/vetis-smol) — smol runtime support for Vetis.
- [vetis-glommio](https://github.com/vetis-server/vetis-glommio) — Glommio runtime support for Vetis.

## Features and integrations

- [vetis-static](https://github.com/vetis-server/vetis-static) — Static file serving with caching and multi-runtime support.
- [vetis-flash](https://github.com/vetis-server/vetis-flash) — Fast static-content serving utilities built on top of Vetis.
- [vetis-proxy](https://github.com/vetis-server/vetis-proxy) — HTTP proxy support for forwarding requests to upstream services.
- [vetis-rev-proxy](https://github.com/vetis-server/vetis-rev-proxy) — Reverse proxy capabilities for Vetis applications.
- [vetis-ws](https://github.com/vetis-server/vetis-ws) — WebSocket support for interactive client-server communication.
- [vetis-wt](https://github.com/vetis-server/vetis-wt) — WebTransport support for modern transport-level features.
- [vetis-rhai](https://github.com/vetis-server/vetis-rhai) — Rhai scripting integration for extensibility.

## Additional projects

- [front](https://github.com/vetis-server/front) — Front-end or application-facing tooling associated with the Vetis ecosystem.
- [onfire](https://github.com/vetis-server/onfire) — Experimental project within the organization.

## Why Vetis

Vetis is built for developers who want:

- small, explicit building blocks instead of heavyweight frameworks
- support for multiple async runtimes without rewriting application code
- modular feature crates that can be added when needed
- a fast path for building web services in Rust

## Getting started

1. Review the core server in [vetis](https://github.com/vetis-server/vetis).
2. Pick the runtime adapter that matches your stack: [vetis-tokio](https://github.com/vetis-server/vetis-tokio), [vetis-compio](https://github.com/vetis-server/vetis-compio), [vetis-smol](https://github.com/vetis-server/vetis-smol), or [vetis-glommio](https://github.com/vetis-server/vetis-glommio).
3. Add the feature modules you need, such as [vetis-static](https://github.com/vetis-server/vetis-static), [vetis-proxy](https://github.com/vetis-server/vetis-proxy), or [vetis-ws](https://github.com/vetis-server/vetis-ws).
4. Use [vetis-templates](https://github.com/vetis-server/vetis-templates) to start new projects with a sensible base.

## Contributing

This organization is open to contributions across the ecosystem. If you want to improve a crate, add a feature, or fix a bug:

- open an issue in the relevant repository
- work from a feature branch
- submit a pull request with a clear explanation and any relevant tests

## Organization

- [.github](https://github.com/vetis-server/.github) — GitHub configuration and organization-level community files

