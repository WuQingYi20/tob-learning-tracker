# GitHub Labels 配置

在 repo 的 Issues > Labels 页面创建以下标签：

## 阶段标签
| Label | Color | Description |
|-------|-------|-------------|
| `phase-1` | `#0E8A16` | Solidity 基础 (Week 1-6) |
| `phase-2` | `#1D76DB` | 安全漏洞 (Week 7-12) |
| `phase-3` | `#5319E7` | ToB 工具链 (Week 13-18) |
| `phase-4` | `#D93F0B` | 实战输出 (Week 19-22) |

## 类型标签
| Label | Color | Description |
|-------|-------|-------------|
| `weekly-task` | `#FBCA04` | 每周任务 |
| `bug-pattern` | `#B60205` | 漏洞模式记录 |
| `ctf` | `#F9D0C4` | CTF 解题 |
| `project` | `#C2E0C6` | 实践项目 |
| `resource` | `#BFD4F2` | 有价值的资源 |

## 状态标签
| Label | Color | Description |
|-------|-------|-------------|
| `blocked` | `#E99695` | 卡住了 |
| `in-progress` | `#FEF2C0` | 进行中 |
| `review-needed` | `#D4C5F9` | 需要复习 |

---

## 快速创建脚本

用 GitHub CLI 批量创建：

```bash
# 安装 GitHub CLI: https://cli.github.com/

gh label create "phase-1" --color "0E8A16" --description "Solidity 基础 (Week 1-6)"
gh label create "phase-2" --color "1D76DB" --description "安全漏洞 (Week 7-12)"
gh label create "phase-3" --color "5319E7" --description "ToB 工具链 (Week 13-18)"
gh label create "phase-4" --color "D93F0B" --description "实战输出 (Week 19-22)"
gh label create "weekly-task" --color "FBCA04" --description "每周任务"
gh label create "bug-pattern" --color "B60205" --description "漏洞模式记录"
gh label create "ctf" --color "F9D0C4" --description "CTF 解题"
gh label create "project" --color "C2E0C6" --description "实践项目"
```
