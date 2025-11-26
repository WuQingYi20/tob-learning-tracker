# 工具笔记

记录 ToB 工具链的学习笔记和常用命令。

## Slither

### 安装
```bash
pip install slither-analyzer
```

### 常用命令
```bash
# 基本扫描
slither .

# 指定 detector
slither . --detect reentrancy-eth

# 输出 JSON
slither . --json output.json

# 排除误报
slither . --triage-mode
```

### 笔记
- [Slither 基础](./slither-basics.md)
- [编写 Detector](./slither-detector.md)
- [SlithIR 理解](./slithir.md)

---

## Echidna

### 安装
```bash
# macOS
brew install echidna

# Docker
docker pull trailofbits/echidna
```

### 常用命令
```bash
# 基本运行
echidna . --contract TestContract

# 指定配置
echidna . --config echidna.yaml
```

### 笔记
- [Echidna 基础](./echidna-basics.md)
- [编写 Invariants](./echidna-invariants.md)

---

## Foundry

### 常用命令
```bash
# 编译
forge build

# 测试
forge test
forge test -vvvv  # 详细输出
forge test --match-test testXxx  # 指定测试

# 部署
forge create

# Gas 报告
forge test --gas-report
```
