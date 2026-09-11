# Folio Generator

[![CI](https://github.com/AnderCMD/Generador-de-folios/actions/workflows/ci.yml/badge.svg)](https://github.com/AnderCMD/Generador-de-folios/actions/workflows/ci.yml)
[![Wallaby.js](https://img.shields.io/badge/wallaby.js-powered-blue.svg?style=for-the-badge&logo=github)](https://wallabyjs.com/oss/)

[![JS npm](https://img.shields.io/npm/v/folio-generator-js?label=JS%20npm&logo=npm&color=cb3837)](https://www.npmjs.com/package/folio-generator-js)
[![JS downloads](https://img.shields.io/npm/dm/folio-generator-js?label=JS%20downloads&logo=npm&color=cb3837)](https://www.npmjs.com/package/folio-generator-js)
[![TS npm](https://img.shields.io/npm/v/folio-generator-ts?label=TS%20npm&logo=npm&color=3178c6)](https://www.npmjs.com/package/folio-generator-ts)
[![TS downloads](https://img.shields.io/npm/dm/folio-generator-ts?label=TS%20downloads&logo=npm&color=3178c6)](https://www.npmjs.com/package/folio-generator-ts)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A robust library to generate sequential alphanumeric codes (folios) like `A00001`, `A00002`, ..., `Z99999`, `AA00001`.

This repository contains production-ready implementations in:

-   [**JavaScript**](Languages/JavaScript) — [`folio-generator-js`](https://www.npmjs.com/package/folio-generator-js)
-   [**TypeScript**](Languages/TypeScript) — [`folio-generator-ts`](https://www.npmjs.com/package/folio-generator-ts)

## Features

-   **Sequential Generation**: Automatically increments numbers and letters (e.g., `A00001` -> `A00002`).
-   **Configurable Format**: Custom padding (e.g., 3 digits) and separators (e.g., `A-001`).
-   **Collision Handling**: Robust logic to check against a database and skip existing folios.
-   **Type Safety**: Full type support in TypeScript.
-   **Production Ready**: Comprehensive tests and strict validation, actively used in production projects.
-   **Zero Dependencies**: No runtime dependencies in either package.

## Usage

Please refer to the specific package directory for detailed installation and usage instructions:

-   [JavaScript Documentation](Languages/JavaScript/README.md)
-   [TypeScript Documentation](Languages/TypeScript/README.md)

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to submit issues, feature requests, and pull requests.

## Security

If you discover a security vulnerability, please follow the process described in [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
