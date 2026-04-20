# api-sandbox Homebrew Tap

Public Homebrew tap for [`api-sandbox`](https://pypi.org/project/api-sandbox/).

Install directly:

```bash
brew install digitalapicraft/api-sandbox-cli/api-sandbox
```

Or tap once, then install by name:

```bash
brew tap digitalapicraft/api-sandbox-cli https://github.com/digitalapicraft/api-sandbox-cli
brew install api-sandbox
```

Verify:

```bash
sdb --help
```

What this installs:

- public package: `api-sandbox`
- installed binary: `sdb`
- customer CLI for API publishers and consumers

Start here after install:

- [PyPI package](https://pypi.org/project/api-sandbox/)
- [Public install guide](https://github.com/digitalapicraft/api-sandbox/blob/main/docs/runbooks/public-cli-install.md)
- [Publisher quickstart](https://github.com/digitalapicraft/api-sandbox/blob/main/docs/runbooks/publisher-quickstart.md)
- [Consumer quickstart](https://github.com/digitalapicraft/api-sandbox/blob/main/docs/runbooks/consumer-quickstart.md)
- [Product explainer](https://github.com/digitalapicraft/api-sandbox/blob/main/docs/runbooks/product-explainer.md)

Formula source of truth:

- rendered from the public PyPI release
- maintained in the private product repo
- committed here under `Formula/api-sandbox.rb`
