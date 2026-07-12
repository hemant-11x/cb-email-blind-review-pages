# Encrypted Campaign Builder review page

This public repository contains only the encrypted browser shell for an
internal Campaign Builder email review. It does not contain the passphrase,
plaintext research, email variants, candidate identities, answer key, or
reviewer submissions.

The payload is encrypted with AES-256-GCM using a PBKDF2-SHA256 derived key.
Completed reviews are submitted to a separate private repository.
