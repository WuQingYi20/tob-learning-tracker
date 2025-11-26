# Week 1: Solidity Basics Introduction

> 📅 Date: [Fill in]
>
> ⏱️ Estimated Time: 15-20 hours

---

## 🎯 This Week's Goal

Master Solidity basic syntax, able to write simple contracts in Remix

## 📋 Task Checklist

### Learning (Cyfrin Updraft - Solidity Course)
- [ ] Section 1: Simple Storage - Complete all
- [ ] Section 2: Storage Factory - Start

### Concept Understanding
- [ ] Variable types: uint, int, bool, address, bytes
- [ ] Visibility: public, private, internal, external
- [ ] Data location: storage, memory, calldata
- [ ] Functions: view, pure, payable

### Practice
- [ ] Deploy first contract in Remix
- [ ] Interact with contract (read/write state variables)
- [ ] Try modifying example code, observe effects

### Reading
- [ ] [Solidity Docs - Introduction](https://docs.soliditylang.org/en/latest/introduction-to-smart-contracts.html)

## 📝 Daily Plan

| Day | Time | Content |
|-----|------|---------|
| Monday | 2h | Cyfrin Course Section 1.1 - 1.3 |
| Tuesday | 2h | Cyfrin Course Section 1.4 - 1.6 |
| Wednesday | 2h | Cyfrin Course Section 1.7 - Complete |
| Thursday | 2h | Remix Practice + Review |
| Friday | 2h | Section 2 Start |
| Saturday | 3h | Continue Section 2 + Free Practice |
| Sunday | 2h | Write Weekly Report + Plan Next Week |

## 💡 Tips

- Don't just watch videos, try every concept in Remix
- If you don't understand something, note it down first, don't get stuck too long
- Cyfrin course can be watched at 1.25x speed

## ✅ Completion Criteria

Able to independently write a simple storage contract:
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
