<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/caffeine-projects/vlatte/main/docs/brand/readme-header-1200x400-dark.png">
  <img src="https://raw.githubusercontent.com/caffeine-projects/vlatte/main/docs/brand/readme-header-1200x400.png" alt="vlatte: Mock HTTP and gRPC servers for Go tests." width="600">
</picture>

## VLatte

**Mock HTTP and gRPC servers for Go tests, and a CLI that serves them from files.**

VLatte starts real servers that answer the way you tell them to. Start one in a
Go test, or run the `vlatte` CLI to serve mocks from YAML or JSON files.

- **HTTP and gRPC**, with no gRPC service implementation to write: unary and
  every kind of streaming call.
- **Matchers** on any part of a request: JSON path, JSON Schema, XPath, regex,
  globs and more.
- **Templated replies**, sequences, scenarios for stateful flows, and webhooks.
- **Proxying and recording** of a real service to play it back later.
- **Fault injection:** latency, slow bandwidth, connection resets and malformed
  answers.
- **An admin API** to manage mocks while a server runs, also served over MCP.
- **A CLI and a Docker image** to run mock servers outside Go.

### Install

#### Go library

```sh
go get github.com/caffeine-projects/vlatte
```

#### Homebrew

```sh
brew install caffeine-projects/tap/vlatte
```

#### Go install

```sh
go install github.com/caffeine-projects/vlatte/cmd/vlatte@latest
```

#### Docker

```sh
docker pull ghcr.io/caffeine-projects/vlatte:v0.1.0-rc.1
```

**[Documentation](https://caffeine-projects.github.io/vlatte/)** ·
[Repository](https://github.com/caffeine-projects/vlatte) ·
[Go reference](https://pkg.go.dev/github.com/caffeine-projects/vlatte)
