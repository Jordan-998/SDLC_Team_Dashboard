# GitHub Issue 模板使用说明

## 文件结构
```
.github/
└── ISSUE_TEMPLATE/
    ├── epic.md      # Epic 模板 — 对应 Milestone
    ├── story.md     # User Story 模板
    └── task.md      # Task 模板 — 看板最小单元
```

## 使用方式
将整个 `.github/` 文件夹复制到你的 GitHub 仓库根目录，推送后，
点击 "New Issue" 时会自动出现模板选择界面。

## 层级关系
```
Milestone（Epic）
  └── Story Issue  [label: story]
        └── Task Issue  [label: task]
```

## 标签清单（需手动在仓库中创建）
| 标签 | 颜色 | 用途 |
|------|------|------|
| `epic` | #7F77DD | Epic 级别 |
| `story` | #378ADD | User Story |
| `task` | #1D9E75 | 实现任务 |
| `bug` | #E24B4A | 缺陷 |
| `chore` | #888780 | 日常维护 |
| `spike` | #BA7517 | 技术调研 |
| `P0` | #E24B4A | 最高优先级 |
| `P1` | #BA7517 | 高优先级 |
| `P2` | #639922 | 普通优先级 |
| `S` | #9FE1CB | 小任务 |
| `M` | #85B7EB | 中任务 |
| `L` | #F5C4B3 | 大任务 |
