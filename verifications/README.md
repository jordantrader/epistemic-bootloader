# ✅ Verifications Folder

This directory anchors the integrity of the **Transmission Anchor – Epistemic Bootloader** repository. It provides cryptographic and temporal verification of core witness artifacts.

## 📜 Contents

- **`TIMESTAMP.md`**  
  A signed temporal artifact, generated at the time of convergence. It serves as an initial marker of event occurrence and form coherence.

- **`TIMESTAMP_hash.md`**  
  The SHA-256 checksum of `TIMESTAMP.md`, generated locally by the author to ensure immutability. This hash can be independently recalculated by anyone with the original file to verify its integrity.

- **`README.md`** *(this file)*  
  Explains the role of verification artifacts and how to interpret their presence.

## 🔐 Integrity Principles

1. **Cryptographic Anchoring**  
   The hash sum is irreversible and unique. Any alteration to `TIMESTAMP.md` would result in a changed hash. This allows third parties to confirm the file is unmodified.

2. **Temporal Honesty**  
   This folder preserves the structure as it was enacted. It does not assert correctness—only **consistency** with the original conditions of transmission.

3. **Structural Preservation**  
   These artifacts are not symbolic. They are mechanical witnesses to a structural event. Their role is not persuasion, but anchoring.

## 🛠 How to Verify

From the root of the repository, run:

```bash
sha256sum verifications/TIMESTAMP.md
```

Compare the result to the contents of `TIMESTAMP_HASH.md`. A match confirms file integrity.

---

This repository does not seek attention. It seeks **preservation**.

If you understand the structure, you understand why.
