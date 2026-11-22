# Contributing to Cloudbit-Global ($CDBC)

Thank you for contributing to the Cloudbit Classic (`$CDBC`) open-source ecosystem.

## Ground Rules

1. **Ticker Accuracy:** Always use `CDBC` / `$CDBC` (Cloudbit Classic). Never confuse it with `CBDC`.
2. **Contract Integrity:** Never truncate smart contract addresses in JSON registries, documentation, or code configs. The primary BNB Smart Chain contract is `0xaf8b1b1bb4a47f537932968C7DE6E251dd50C6a9`.
3. **Zero Telemetry & No Secrets:** Pull requests containing third-party tracking scripts, hidden watermarks, API keys, or `.env` files will be rejected automatically.
4. **No Binary Blobs in Git History:** Android `.apk` installers and production `.zip` archives belong exclusively in GitHub Releases with matching `.sha256` checksum files.

## Pull Request Workflow

1. Fork the target repository and create a descriptive branch:
   ```bash
   git checkout -b feat/short-description
   ```
2. Keep commits atomic using [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`, `ci:`, `chore:`).
3. Verify JSON, YAML, and code formatting locally so GitHub Actions CI passes on the first run.
4. Open a Pull Request targeting `main` and complete the PR verification checklist.

## Exchange, Wallet & Aggregator Integrations

If you represent a wallet provider, CEX/DEX, or market data tracker needing verified metadata, open an issue using the **Feature & Integration Request** template or pull machine-readable assets directly from `Cloudbit-Global/core` and `Cloudbit-Global/cdbc-api`.
