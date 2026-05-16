# 🌾 Haybarn Installer

An independent derived distribution of [DuckDB](https://duckdb.org) by [Query Farm](https://query.farm).

> Not affiliated with or endorsed by the DuckDB Foundation. DuckDB is a trademark of the DuckDB Foundation.


## Install

```bash
curl -fsSL https://query-farm-haybarn.github.io/install | sh
```

Installs the latest release to `~/.haybarn/cli/latest/haybarn` and symlinks it into `~/.local/bin` if available.

### Supported platforms

| OS | Architecture |
|---|---|
| Linux | x86_64, arm64 |
| macOS | x86_64, arm64 |


## Usage

```bash
# Install latest
curl -fsSL https://query-farm-haybarn.github.io/install | sh

# Install a specific version
HAYBARN_VERSION=haybarn-v1.5.2-rc7 curl -fsSL https://query-farm-haybarn.github.io/install | sh

# Download and inspect before running
curl -o install.sh https://query-farm-haybarn.github.io/install
sh install.sh
```

After install, add Haybarn to your PATH by appending to your shell profile (`~/.bashrc`, `~/.zshrc`, etc.):

```bash
export PATH="$HOME/.haybarn/cli/latest":$PATH
```


## Releases

See [github.com/Query-farm-haybarn/haybarn/releases](https://github.com/Query-farm-haybarn/haybarn/releases) for all available versions.
