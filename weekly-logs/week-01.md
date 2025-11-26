# Week 1: Solidity 基础入门

> 📅 日期：[填写]
> 
> ⏱️ 预计投入：15-20 小时

---

## 🎯 本周目标

掌握 Solidity 基本语法，能在 Remix 中编写简单合约

## 📋 任务清单

### 学习 (Cyfrin Updraft - Solidity Course)
- [ ] Section 1: Simple Storage - 全部完成
- [ ] Section 2: Storage Factory - 开始

### 概念理解
- [ ] 变量类型：uint, int, bool, address, bytes
- [ ] 可见性：public, private, internal, external
- [ ] 数据位置：storage, memory, calldata
- [ ] 函数：view, pure, payable

### 实践
- [ ] 在 Remix 中部署第一个合约
- [ ] 与合约交互（读写状态变量）
- [ ] 尝试修改示例代码，观察效果

### 阅读
- [ ] [Solidity Docs - Introduction](https://docs.soliditylang.org/en/latest/introduction-to-smart-contracts.html)

## 📝 每日计划

| 日期 | 时间 | 内容 |
|------|------|------|
| 周一 | 2h | Cyfrin 课程 Section 1.1 - 1.3 |
| 周二 | 2h | Cyfrin 课程 Section 1.4 - 1.6 |
| 周三 | 2h | Cyfrin 课程 Section 1.7 - 完成 |
| 周四 | 2h | Remix 实践 + 复习 |
| 周五 | 2h | Section 2 开始 |
| 周六 | 3h | 继续 Section 2 + 自由练习 |
| 周日 | 2h | 写周报 + 下周计划 |

## 💡 Tips

- 不要只看视频，每个概念都要在 Remix 里试一试
- 遇到不懂的先记下来，不要卡太久
- Cyfrin 课程可以 1.25x 倍速看

## ✅ 完成标志

能独立写出一个简单的存储合约：
```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract SimpleStorage {
    uint256 public favoriteNumber;
    
    function store(uint256 _number) public {
        favoriteNumber = _number;
    }
    
    function retrieve() public view returns (uint256) {
        return favoriteNumber;
    }
}
```
