# github-forge-sandbox

[![CI](https://github.com/thmsgo18/github-forge-sandbox/actions/workflows/ci.yml/badge.svg)](https://github.com/thmsgo18/github-forge-sandbox/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Tiny math helpers — a sandbox repository used to exercise a professional GitHub workflow.

## Features

- `add(a, b)` — returns the sum of two numbers
- Zero dependencies, ES modules

## Getting started

### Prerequisites

- Node.js 20 or later

### Installation

```bash
git clone https://github.com/thmsgo18/github-forge-sandbox.git
cd github-forge-sandbox
npm install
```

### Usage

```bash
node -e "import('./src/math.js').then(m => console.log(m.add(2, 3)))"
```

## Running tests

```bash
npm test
```

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) for the workflow and conventions.

## License

Distributed under the MIT License. See [LICENSE](LICENSE).
