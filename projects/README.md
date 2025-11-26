# Practice Projects

Projects completed by learning phase.

## Phase 1: Solidity Basics

| Project | Status | Description |
|---------|--------|-------------|
| 01-simple-storage | ⏳ | Basic storage contract |
| 02-erc20 | ⏳ | ERC20 token implementation |
| 03-erc721 | ⏳ | NFT implementation |

## Phase 3: ToB Tools

| Project | Status | Description |
|---------|--------|-------------|
| slither-detector | ⏳ | Custom Slither detector |
| echidna-tests | ⏳ | Echidna property tests |

---

## Project Structure Template

Each Foundry project:

```
project-name/
├── src/
│   └── Contract.sol
├── test/
│   └── Contract.t.sol
├── script/
│   └── Deploy.s.sol
├── foundry.toml
└── README.md
```

## Quality Standards

Each project should have:
- [ ] Complete test coverage
- [ ] Slither scan with no high severity issues
- [ ] Clear README
- [ ] Good code comments
