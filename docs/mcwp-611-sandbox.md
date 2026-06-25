# MCWP-611 Sandbox

Research POC for [codeowners-plus](https://github.com/multimediallc/codeowners-plus) selective approval dismissal on MetaMask Mobile.

- **Sandbox repo:** `consensys-test/metamask-mobile-codeowners`
- **Extension trial reference:** [MetaMask/experimental-codeowners-plus](https://github.com/MetaMask/experimental-codeowners-plus)
- **Production repo:** unchanged — [MetaMask/metamask-mobile](https://github.com/MetaMask/metamask-mobile)

## Phases

| Phase | Mode | Owners | Token |
|-------|------|--------|-------|
| A | Smoke (`fail_check=false`) | Individual GitHub users | `GITHUB_TOKEN` |
| B | Decisive Option A (`fail_check=true`, `approval=false`) | `@consensys-test/*` org teams | `CODEOWNERS_PLUS_TOKEN` |

## Branch protection (Phase B)

- Dismiss stale approvals on push: **OFF**
- Require review from Code Owners (native): **OFF**
- Required status check: **Run Codeowners Plus**
