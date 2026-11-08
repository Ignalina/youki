# nordisk-libcontainer

This is a temporary fork of youki's `libcontainer` 0.7.0. It carries only one
change: the `SeccompBackend` trait from youki PR
[#3873](https://github.com/youki-dev/youki/pull/3873).

We are hoping to get the trait into youki itself. When it lands there, this
crate will be deprecated, and heimdall-youki will depend on youki's own
`libcontainer` again.

All credit for libcontainer goes to the youki maintainers:
[github.com/youki-dev/youki](https://github.com/youki-dev/youki).

Its user is [nordisk-heimdall-youki](https://crates.io/crates/nordisk-heimdall-youki).

## Licence

Apache-2.0, the same as youki (see `LICENSE`). Copyright 2021 youki team.
