# Octra WebCLI v0.04.08 — Full Setup & Settings Guide

This guide walks through:

- Installing Octra WebCLI from scratch
- Updating an existing installation
- Launching the wallet interface
- Importing wallets
- Updating RPC and Explorer settings

⚠️ **Important Update**

Version **0.04.08** fixes a derivation issue where some seed phrases previously generated different addresses.

If you created wallets with older versions of WebCLI or wallet-gen, you should:

- Update to **v0.04.08**
- Re-import your wallet from the seed phrase if necessary

---

## Updating an Existing Installation

# 1. Go to the latest repository:
```
git clone https://github.com/octra-labs/webcli
cd webcli
```
# 2. Git pull

```bash
git pull
```
This will download the latest updates from the repository
# Then run the setup again.

Linux / macOS
```
./setup.sh
```

If permission is denied:
```
chmod +x setup.sh
./setup.sh
```

Windows
```
setup.bat
```

# 4. start the wallet
Run the wallet client:
```
./octra_wallet
```


---

# 5. A Migration Note

If you created wallets with earlier WebCLI versions:

Update to v0.04.08

Restart the WebCLI

Re-import your wallet using the seed phrase

This will restore correct wallet addresses, indexes, and derivation paths.



