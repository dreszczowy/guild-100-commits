# Foundry Setup for Base

```bash
curl -L https://foundry.paradigm.xyz | bash
foundryup
```

Then in foundry.toml:
```toml
[rpc_endpoints]
base = "https://mainnet.base.org"
base_sepolia = "https://sepolia.base.org"
```

Useful for testing and deploying contracts on Base.
