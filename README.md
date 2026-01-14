# My Custom Skills

> 我创建的 skills 和收集到的优秀 skills

这是我的自定义 Claude Code Skills 仓库，用于统一管理所有自定义技能。

## 目录结构

```
my-skills/
├── .claude-plugin/
│   └── marketplace.json          # Skill marketplace 配置文件
├── skills/                       # Skills 目录
│   ├── end-to-end-process-design/  # 端到端流程设计 skill
│   │   ├── SKILL.md              # Skill 主文件
│   │   ├── references/           # 参考文档
│   │   └── assets/               # 输出模板
│   └── planning-with-files/      # Manus 风格的文件式规划 skill
│       ├── SKILL.md
│       ├── templates/            # 任务规划模板
│       └── scripts/              # 辅助脚本
├── README.md                     # 本文件
└── .gitignore                    # Git 忽略规则
```

## 已安装的 Skills

### 1. End-to-End Process Design (端到端流程设计)
基于迈克尔·哈默的业务流程再造方法论，帮助组织诊断流程问题、消除浪费、重新设计工作流程。

**触发方式**：
- 关键词：流程优化、端到端流程、BPR、业务流程再造、消除浪费、跨部门协调
- 场景：流程卡住、部门壁垒、依赖英雄员工、准备引入AI

**核心功能**：
- 流程诊断与问题识别
- 基于六大原则的流程重新设计
- 实施路线图规划
- 流程所有者设置

### 2. Planning with Files (Manus 风格的文件式规划)
基于 Manus AI（Meta 以 20 亿美元收购）的工作方式，使用持久化 markdown 文件作为"磁盘上的工作记忆"。

**触发方式**：
- 手动调用：`/planning-with-files`
- 自动触发：复杂的多步骤任务（>5 个工具调用）
- 适用场景：研究任务、构建项目、多步骤任务

**核心功能**：
- 自动创建 `task_plan.md` 追踪任务阶段
- 使用 `findings.md` 存储研究发现
- 通过 `progress.md` 记录会话日志
- 钩子系统：任务前重读计划、文件修改后提醒更新
- 错误日志：避免重复失败

**三文件模式**：
```
task_plan.md  → 追踪阶段和进度（checkboxes）
findings.md   → 存储研究和发现（而非塞入上下文）
progress.md   → 会话日志和测试结果
```

**原作者**: [Ahmad Othman Ammar Adi](https://github.com/OthmanAdi/planning-with-files)
**许可证**: MIT

## 添加新 Skill

1. 将新 skill 目录放入 `skills/` 文件夹
2. 更新 `.claude-plugin/marketplace.json`，在 `skills` 数组中添加新路径
3. 重启 Claude Code 以加载新 skill

## 版本管理

建议使用 Git 管理这个仓库：

```bash
cd /Users/yangshan/.claude/plugins/marketplaces/my-skills
git init
git add .
git commit -m "Initial commit: Add end-to-end-process-design skill"
```

## 与官方 Skills 的关系

- **官方 Skills**: `/Users/yangshan/.claude/plugins/marketplaces/anthropic-agent-skills/`
- **自定义 Skills**: `/Users/yangshan/.claude/plugins/marketplaces/my-skills/` (本仓库)

两者相互独立，互不影响。Claude Code 会自动扫描 marketplaces 下的所有仓库。

## 备份与分享

打包 skill 用于分享：

```bash
cd skills/end-to-end-process-design
# 使用 skill-creator 的打包脚本
python3 /path/to/skill-creator/scripts/package_skill.py .
```

生成的 `.skill` 文件可以分享给其他人使用。
