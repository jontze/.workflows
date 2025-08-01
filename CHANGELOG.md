# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### 🚀 Features

- *(rust)* Add workflow to run linter and clippy
- *(rust)* Support working directories
- *(rust)* Support cache for workspaces
- *(rust)* Create build test workflow
- *(rust)* Create reusable test workflow
- *(rust)* Enable sparse registry index protocol
- *(rust)* Run test workflow optional with unit tests
- *(action)* Create composite action to setup conv-versioning in CI
- *(rust)* Create workflow to automate next version release
- *(rust_release)* Allow usage of a deploy key
- *(rust_release)* Use annotated tags with name as description
- *(action)* Make explicit version optinal and use latest version
- *(rust_release)* Use latest version of conventional versioning
- *(changelog)* Add workflow to generate changelog file
- *(changelog_gen)* Allow to specify branch for changelog_gen
- *(workflow)* Create generic single-platform image built
- *(workflows)* Build generic rust executables for multiple platforms
- *(workflows/binaries)* Allow to modify rentention days
- *(node)* Add test workflow for node.js based apps
- *(node)* Split test workflow into multiple jobs
- *(helm)* Add oci image publish workflow using flux

### 🐛 Bug Fixes

- Move re-usable workflows to subdirectory
- *(rust_build)* Use correct template syntax for inputs
- Add missing `cargo-edit` installation
- *(rust_release)* Disable interactive mode on `cargo-edit` install
- *(rust-release)* Checkout repo with tags
- *(rust_release)* Add fetch depth of 0
- *(rust_release)* Fetch tags via git cli
- *(rust_release)* Fix incorrect condition
- *(rust_release)* Use regular bools instead string bools
- *(rust_release)* Ignore ci version bump
- *(rust_release)* Create and push regular tag
- Remove skip-ci
- *(changelog)* Generate changelog with message that skips ci
- *(changelog)* Remove secret decleration that has conlficting name
- *(changelog)* Remove pull before creating and pushing commit
- *(changelog)* Make inputs with defaults optional
- *(workflows/binaries)* Upgrade to ubuntu 22 due to gh managed brownout
- *(helm)* Don't use reserved variable name for registry secret
- *(helm)* Always push and remove conditional push input

### 🚜 Refactor

- *(workflows/binaries)* Rename job to build rust binaries

### ⚙️ Miscellaneous Tasks

- *(github)* Add dependabot config
- *(rust_release)* Remove explicit tag fetching and just use depth
- *(rust_release)* Remove debug echo step
- Init git-cliff for changelog generation
- Update changelog [skip ci]
- Update changelog [skip ci]
- Update changelog [skip ci]
- Update changelog [skip ci]
- Update changelog [skip ci]
- Update changelog [skip ci]
- Update changelog [skip ci]
- Update changelog [skip ci]
- Update changelog [skip ci]

<!-- generated by git-cliff -->
