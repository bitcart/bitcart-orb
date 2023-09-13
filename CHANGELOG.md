# Changelog

All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

## 2.1.1

Update build-ubuntu machine version

## 2.1.0

Disable nirvati for now

## 1.10.0

Publish to multiple docker registries

## 1.9.0

New command to do uploads to codecov, fixed functional tests due to deprecation of codecov python uploader

## 1.8.4

Fix permission issues when installing Fulcrum

## 1.8.3

Fix pip install not working in some cases

## 1.8.2

More reliable usage of pip for pre-commit jobs

## 1.8.1

Fix validate-plugins job not working in some cases

## 1.8.0

Added new docker-go executor.

New commands: install-bitcart-cli and validate-plugins.

New job: validate-plugins

## 1.7.1

Fix pre-commit setup without pip

## 1.7.0

Remove arm32 from list of build platforms

## 1.6.0

Python 3.8 is now the default for all jobs

## 1.5.0

Added new python-node executor and command to install node.js package dependencies

## 1.4.0

Fixed lint job pre-commit data directories caching and allowed to disable it

## 1.3.0

Made functional tests not flaky

## 1.2.0

Added job for running functional tests and commands to install Fulcrum and upload test results

## 1.1.2

Fix pre-commit installation failures

## 1.1.1

Fix lint job

## 1.1.0

Added new docker-python executor and lint job

## 1.0.4

Move BUILD_PLATFORMS env var to executors

## 1.0.3

Bugfix for docker buildx qemu enabling (now works always and is fast)

## 1.0.2

Bugfix for docker buildx qemu enabling (via multiarch/qemu-user-static)

## 1.0.1

Bugfix for docker buildx qemu enabling (via tonistiigi/binfmt)

## 1.0.0

Initial Release
