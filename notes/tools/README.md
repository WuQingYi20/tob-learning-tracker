# Tools Notes

Recording learning notes and common commands for ToB toolchain.

## Slither

### Installation
```bash
pip install slither-analyzer
```

### Common Commands
```bash
# Basic scan
slither .

# Specify detector
slither . --detect reentrancy-eth

# Output JSON
slither . --json output.json

# Exclude false positives
slither . --triage-mode
```

### Notes
- [Slither Basics](./slither-basics.md)
- [Writing Detectors](./slither-detector.md)
- [Understanding SlithIR](./slithir.md)

---

## Echidna

### Installation
```bash
# macOS
brew install echidna

# Docker
docker pull trailofbits/echidna
```

### Common Commands
```bash
# Basic run
echidna . --contract TestContract

# Specify config
echidna . --config echidna.yaml
```

### Notes
- [Echidna Basics](./echidna-basics.md)
- [Writing Invariants](./echidna-invariants.md)

---

## Foundry

### Common Commands
```bash
# Build
forge build

# Test
forge test
forge test -vvvv  # Verbose output
forge test --match-test testXxx  # Specific test

# Deploy
forge create

# Gas report
forge test --gas-report
```
