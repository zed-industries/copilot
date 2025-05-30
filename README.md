# copilot

This repository extracts the Copilot language server from [copilot.vim](https://github.com/github/copilot.vim) and packages it into a tarball.

## Deprecation Notice

As of Zed v0.180.x (2025-04-02) Zed [switched](https://github.com/zed-industries/zed/pull/27401) from copilot.vim to using [@github/copilot-language-server](https://github.com/github/copilot-language-server-release).

As of 2025-05-30 this repo has been archived.

Note, just as with copilot.vim, copilot-language-server is governed by [GitHub Copilot Product Specific Terms](https://github.com/customer-terms/github-copilot-product-specific-terms).
It is not open source and the [npm package](https://www.npmjs.com/package/@github/copilot-language-server) only contains minimified and obsfucated javascript; GitHub has made no other source available.

## Publishing

To publish a new release of the Copilot language server, create a new git tag e.g. `v1.2.3` and push it. A draft release will be created automatically. Once you publish it, Zed users will download the updated server the first time they use Copilot.
