# MCWP-611 Sandbox

Research POC for selective approval dismissal on MetaMask Mobile.

**Sandbox:** `consensys-test/metamask-mobile-codeowners`

## Current test (2-team dismissal)

| Team | Path | Approver |
|------|------|----------|
| `sdlc-team-2` | `app/component-library/**` | jluque0101 |
| `release-team` | `.github/**` | alucardzom |

**Test PR:** open `mcwp611-2team-dismissal` branch PR.

### Steps

1. jluque0101 and alucardzom each approve the PR.
2. Confirm `Run Codeowners Plus` is green.
3. Push a commit touching **only** `app/component-library/**`.
4. Expected: only jluque0101's approval is dismissed; alucardzom's remains valid.

## References

- Extension trial: https://github.com/MetaMask/experimental-codeowners-plus
- codeowners-plus: https://github.com/multimediallc/codeowners-plus
