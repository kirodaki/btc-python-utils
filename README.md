# Python Bitcoin Utils
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A clean and well-documented Python library for working with the Bitcoin protocol.
It provides low-level tools for key and address management, transaction creation (including SegWit and Taproot), full script support with all opcodes, and raw block parsing.
Designed for developers who want to understand and experiment with the internals of Bitcoin — from keys to scripts and transactions — while keeping the codebase simple, readable, and extensible.
Currently in early development; API and features may evolve with future releases.

# Installation

```bash
git clone https://github.com/kirodaki/btc-python-utils
cd btc-python-utils
```
Then install dependencies and set up the package:
```bash
pip install -r requirements.txt
```

```bash
python setup.py
```
**To update the package, run the update.bat file. It will install the latest version.**

# Development Environment Setup
```bash
You can set up your development environment with:

git clone https://github.com/kirodaki/btc-python-utils
cd btc-python-utils
virtualenv -p python3 venv
. venv/bin/activate
python -m pip install -e ".[dev]"
pre-commit install
```



# Donations & Sponsorship

If you find this project useful, consider supporting future development:
- **BTC**: bc1q8grhtxdw37npcdadm7xa848vquqgurj9ecvpex
- **ERC20**: 0x2d19c72fb8b3a7cdc7fa4970b5c777966f547854

**Thank you!🙏**
