# 996 Coin

996 Coin is a cryptocurrency developed by the HCC Community (see hashcashfaucet.com)
This repository contains the core node, CLI tools, wallet tooling, and Qt desktop wallet sources.

## Project Status

This project is in active fork/customization state. Some codebase and build-system elements still reflect upstream Bitcoin PoS ancestry while chain parameters and network identity have been customized for 996-Coin.

That means this repository should currently be treated as a development fork, not as a polished end-user release.

## Important Note

This project is derived from upstream Bitcoin Core / Bitcoin PoS lineage. As with many cryptocurrency forks, inherited naming, comments, scripts, and documentation may still exist in parts of the codebase. Ongoing cleanup and verification are expected parts of development.

Do not assume all documentation, filenames, or build artifacts are fully rebranded until they have been reviewed.

## Build Targets

The repository currently contains source/build logic for:

- daemon
- CLI RPC client
- transaction utility
- wallet utility
- Qt GUI wallet

Depending on platform and build method, output binaries may still use inherited upstream naming until renamed in code and packaging.

## Building

Build instructions are not yet fully refreshed for 996-Coin.

Until project-specific instructions are finalized, review the existing platform build files and upstream-style documentation in:

- `doc/`
- `depends/`
- `build_msvc/`
- `contrib/`

If you are contributing build instructions, prefer documenting:

- tested OS version
- compiler/toolchain version
- dependency installation steps
- exact build commands
- resulting binary names
- known warnings or failures

## Configuration

Default configuration naming and datadir conventions may still reflect upstream ancestry in parts of the codebase. These should be verified before release packaging or public distribution.

## Contributing

Contributions should be made through branches and pull requests unless direct branch coordination has been explicitly agreed by the project maintainers.

Recommended contribution flow:

1. create a feature or audit branch
2. make scoped changes
3. test locally where possible
4. open a pull request with a clear summary
5. include notes on build/test status

## Security

This repository may contain inherited security contact or upstream project references that are no longer valid for 996-Coin. Verify all security/reporting contact paths before publishing releases.

## License

This project inherits from Bitcoin Core lineage and is distributed under the MIT software license unless otherwise noted in specific files.

See `COPYING` for details.