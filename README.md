# poseidon-zig

Poseidon hash implementation in Zig

_This is currently a work-in-progress_

Currently, this is allocation-free - hoping to keep it this way as I work on this. This
contains only a minimal implementation with a chosen default configuration for 128-bits
of security (Poseidon-128)

_Disclaimer: This code has not been audited and may contain bugs._

## References:

- [Paper](https://eprint.iacr.org/2019/458.pdf)
- [Original reference implementation](https://extgit.iaik.tugraz.at/krypto/hadeshash)
- [arnaucube's poseidon-rs](https://github.com/arnaucube/poseidon-rs)
