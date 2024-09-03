# rav1d-rs

Safe bindings for [rav1d](https://github.com/memorysafety/rav1d), originally a fork of [dav1d-rs](https://github.com/rust-av/dav1d-rs).

## Building

Requires:
- A C compiler
- `nasm`, if the `asm` features are enabled

```
$ cargo build
```

## Examples

There is a basic CLI used to print packets from an `ivf` file:

```
$ cargo run --example print-ivf -- dav1d-test-data/8-bit/features/rgb.ivf
```

