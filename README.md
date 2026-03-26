# clusterfuzz-fuzzbot-builder

`clusterfuzz-fuzzbot-builder` is a Dokker based GitHub Action that provides a build enviroment for Firedancer on Fuzzbot.

## What is included

The image setup installs:

- Ubuntu 24.04
- LLVM/Clang 19
- Rust nightly and `rust-src`

## How it works

1. `Dockerfile` builds the image used by the action
2. `scripts/setup.sh` installs the toolchain and other dependancies
