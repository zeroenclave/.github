<p align="center">
  <a href="https://zeroenclave.com"><img src="https://zeroenclave.com/img/icon-128.png" width="96" height="96" alt="Zero Enclave"></a>
</p>

<h1 align="center">Zero Enclave</h1>

<p align="center">
  <strong>Private by design.</strong><br>
  Encrypted photo and video vault for iPhone.<br>
  Local only · zero knowledge · open source
</p>

<p align="center">
  <a href="https://zeroenclave.com">Website</a> ·
  <a href="https://zeroenclave.com/en/open-source">Open source</a> ·
  <a href="mailto:support@zeroenclave.com">Contact</a>
</p>

---

Photos and videos are encrypted on the device before they are stored. There is no account, no server and no tracking; only the master password or the recovery key opens the vault.

| | |
|---|---|
| Key derivation | Argon2id, 64 MiB (RFC 9106) |
| Key separation | HKDF-SHA256 (RFC 5869) |
| File encryption | AES-256-GCM, per-file keys, 1 MiB segments (NIST SP 800-38D) |
| Core | Rust with the RustCrypto libraries, Swift app via UniFFI |
| License | GPLv3; name and logo excluded |

**Status:** coming to the App Store in December 2026. The source code is published with the first release.

**Security issues:** please report them privately to support@zeroenclave.com.
