## v0.4.0

### Breaking changes
- [\#334](https://github.com/arkworks-rs/snark/pull/334) Outlining linear combinations is now specified via the optimization goal interface.

### Features

### Improvements
- [\#325](https://github.com/arkworks-rs/snark/pull/325) Reduce memory consumption during inlining

### Bug fixes
- [\#340](https://github.com/arkworks-rs/snark/pull/340) Compile with `panic='abort'` in release mode, for safety of the library across FFI boundaries.

## v0.1.0

This tag corresponds to the old `zexe` codebase.
After this release, all of the code has been split up into
more modular repositories in the github organization `arkworks-rs`.
See #320 for guides in migration of old codebases.
