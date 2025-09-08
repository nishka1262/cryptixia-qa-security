# 🔒 Security Checklist

- [ ] No private keys committed (`.env`, `.secret`, `mnemonic.txt` not in repo).
- [ ] `.gitignore` includes sensitive files (node_modules, .env, private keys).
- [ ] Contract deployments use testnet accounts (not mainnet keys).
- [ ] API keys stored in environment variables, not code.
- [ ] Access tokens revoked after testing.
- [ ] Dependencies checked (`npm audit` / `yarn audit` run).
- [ ] Smart contracts linted (`forge fmt`, `forge test` pass).
- [ ] No hardcoded secrets in frontend/backend.
- [ ] Verified wallet interactions are limited to testnet.
