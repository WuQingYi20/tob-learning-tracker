# CTF 解题记录

## Ethernaut

| # | 名称 | 状态 | 难度 | 笔记 |
|---|------|------|------|------|
| 0 | Hello Ethernaut | ⏳ | ⭐ | |
| 1 | Fallback | ⏳ | ⭐ | |
| 2 | Fallout | ⏳ | ⭐ | |
| 3 | Coin Flip | ⏳ | ⭐⭐ | |
| 4 | Telephone | ⏳ | ⭐ | |
| 5 | Token | ⏳ | ⭐⭐ | |
| 6 | Delegation | ⏳ | ⭐⭐ | |
| 7 | Force | ⏳ | ⭐⭐ | |
| 8 | Vault | ⏳ | ⭐⭐ | |
| 9 | King | ⏳ | ⭐⭐ | |
| 10 | Re-entrancy | ⏳ | ⭐⭐⭐ | |
| ... | ... | ... | ... | |

## Damn Vulnerable DeFi

| # | 名称 | 状态 | 关键漏洞 | 笔记 |
|---|------|------|----------|------|
| 1 | Unstoppable | ⏳ | | |
| 2 | Naive Receiver | ⏳ | | |
| 3 | Truster | ⏳ | | |
| 4 | Side Entrance | ⏳ | | |
| 5 | The Rewarder | ⏳ | | |
| ... | ... | ... | ... | |

---

## 解题模板

每道题创建一个文件夹：

```
ethernaut/
└── 01-fallback/
    ├── README.md      # 题目分析 + 思路
    ├── Solution.sol   # 解题合约（如需要）
    └── exploit.js     # 攻击脚本
```

### README.md 模板

```markdown
# Ethernaut - Level X: [Name]

## 题目要求
...

## 分析
...

## 漏洞
...

## 解法
...

## 学到了什么
...
```
