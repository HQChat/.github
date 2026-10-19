# HQChat

An end-to-end encrypted messenger with post-quantum key agreement. Every key
exchange uses HQC-256, a KEM double ratchet with prekeys provides forward
secrecy, and the server moves ciphertext it cannot read.

Free for every account. There is no paid tier, no subscription and no in-app
purchase.

- **[HQCHAT](https://github.com/HQChat/HQCHAT)**: the whole thing. The macOS
  and iOS apps, the server, the Rust core and the infrastructure that deploys it.
- **[hqchat.app](https://hqchat.app)**: the website, the crypto write-up and
  [support](https://hqchat.app/support).

The server and infrastructure are AGPL-3.0 and free to self-host. The apps are
published so their encryption claims can be checked against the code, not so
they can be reused ([licensing](https://github.com/HQChat/HQCHAT/blob/main/LICENSING.md)).

Found a vulnerability? Report it privately through a
[security advisory](https://github.com/HQChat/HQCHAT/security/advisories/new),
not a public issue.
