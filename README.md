# eeia CLI

Command-line interface for the [EEIA](https://challenges.eeia.fr) Python coding challenges platform.

---

## Install

**macOS / Linux (install script)**
```sh
curl -fsSL https://raw.githubusercontent.com/ML-for-B-E/eeia-challenges-cli/main/install.sh | sh
```

**Homebrew**
```sh
brew install ML-for-B-E/eeia-challenges-cli/eeia
```

**Linux packages**

Download the `.deb` or `.rpm` from the [latest release](https://github.com/ML-for-B-E/eeia-challenges-cli/releases/latest):
```sh
sudo dpkg -i eeia_*.deb       # Debian / Ubuntu
sudo rpm -i eeia_*.rpm        # Fedora / RHEL
```

**Manual download**

Pre-built binaries for macOS (arm64/amd64) and Linux (arm64/amd64) are attached to every [release](https://github.com/ML-for-B-E/eeia-challenges-cli/releases).

---

## Getting started

```sh
eeia auth login
eeia challenge today
eeia challenge list
eeia submit 3 -f solution.py
eeia leaderboard
```

Run `eeia --help` or `eeia <command> --help` for full usage.
