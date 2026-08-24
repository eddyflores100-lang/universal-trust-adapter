# ⚠️ This repository has moved

**This repo is no longer maintained here.**

The canonical Universal Trust Adapter (UTA) repository is now at:

## 👉 **[alicelabs-llc/universal-trust-adapter](https://github.com/alicelabs-llc/universal-trust-adapter)**

This `eddyflores100-lang` account was a personal workspace during early development.
The project has graduated to the AliceLabs LLC organization for long-term maintenance.

### What stays the same

- **NPM packages** are unchanged: `@marketnow/uts`, `@marketnow/trust-core`, `agent-trust-card`, `marketnow-mcp`
- **Tarballs on NPM** are byte-identical (same SHA-256)
- **Test vectors** are now at `alicelabs-llc/universal-trust-adapter/main/marketnow/docs/atc-spec/test-vectors/`
- **Conformance runner** is at `alicelabs-llc/universal-trust-adapter/blob/main/tests/test.mjs`

### What changes

- All new issues, PRs, and stars should go to the new repo
- The canonical URLs in published Dev.to articles will be updated to point to `alicelabs-llc`
- This repo will be archived (read-only) but not deleted, so old links still work

### Why move?

1. **Public visibility**: The new repo is in the AliceLabs LLC org, which is publicly accessible
2. **Long-term maintenance**: Future development will happen under the org
3. **Consistency**: Other AliceLabs projects (marketnow, sam-gov-types, security-toolkit) already live there

If you cloned this repo before, you can update your remote:

```bash
git remote set-url origin https://github.com/alicelabs-llc/universal-trust-adapter.git
git pull origin main
```

— Edison Flores, AliceLabs LLC

