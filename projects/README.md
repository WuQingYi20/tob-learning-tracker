# 实践项目

按学习阶段完成的项目。

## Phase 1: Solidity 基础

| 项目 | 状态 | 描述 |
|------|------|------|
| 01-simple-storage | ⏳ | 基础存储合约 |
| 02-erc20 | ⏳ | ERC20 代币实现 |
| 03-erc721 | ⏳ | NFT 实现 |

## Phase 3: ToB 工具

| 项目 | 状态 | 描述 |
|------|------|------|
| slither-detector | ⏳ | 自定义 Slither 检测器 |
| echidna-tests | ⏳ | Echidna 属性测试 |

---

## 项目结构模板

每个 Foundry 项目：

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

## 质量标准

每个项目应该有：
- [ ] 完整的测试覆盖
- [ ] Slither 扫描无高危
- [ ] 清晰的 README
- [ ] 良好的代码注释
