# PocketGull Homebrew Tap Higher-Order Standards

Inherits global higher-order skills from `~/.gemini/config/skills/shared-constitution.json`.

## Repository Invariants
- **Cryptographic Provenance:** Every formula/cask must pin verified immutable `sha256` digests and exact tagged release URLs from approved GitHub repositories.
- **Typography & Security Hygiene:** Publish only verified `v4.0+` PocketGull font archives cleanly without credentials, deprecated prototype paths, or unverified post-install hooks.
- **Exit Gate:** Verify cask syntax (`brew audit` / Ruby syntax check) cleanly before committing.
