# poseidon-zig

Poseidon hash implementation in Zig

_This is currently a work-in-progress_

Currently, this is allocation-free - hoping to keep it this way while work on this continues. This
contains only a minimal implementation with a chosen default configuration (Poseidon-128)
for 128-bits of security. 

## Test

```sh
zig test src/main.zig
```

## Disclaimer

This code has not been audited and may contain bugs

## References

- [Paper](https://eprint.iacr.org/2019/458.pdf)
- [Original reference implementation](https://extgit.iaik.tugraz.at/krypto/hadeshash)
- [arnaucube's poseidon-rs](https://github.com/arnaucube/poseidon-rs)
