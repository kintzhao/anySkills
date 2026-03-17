# AnySkills - Skills Hub 集合仓库

> 📚 Claude Code Skills、Agent Skills 和 OpenClaw Skills 的统一集合仓库

## 项目简介

本仓库汇集了多个优秀的 AI Agent Skills 技能仓库，通过 Git Submodules 进行统一管理和组织。旨在为开发者提供一站式的技能资源索引和快速访问入口。

## 仓库结构

```
anySkills/
├── claude_code/          # Claude Code 相关技能
├── multi_platform/       # 多平台 Agent 技能
├── openclaw/            # OpenClaw 生态技能
├── others/              # 其他生态技能
├── skillsHub.md         # 技能仓库汇总清单
└── README.md            # 本说明文件
```

## 技能仓库列表

### 🔵 Claude Code 官方/核心 (10个)

| 仓库 | 说明 |
|------|------|
| [anthropics/skills](./claude_code/anthropics/skills) | Anthropic 官方技能 |
| [obra/superpowers](./claude_code/obra/superpowers) | 20+ 战斗测试技能 |
| [ComposioHQ/awesome-claude-skills](./claude_code/ComposioHQ/awesome-claude-skills) | Composio 策展 |
| [travisvn/awesome-claude-skills](./claude_code/travisvn/awesome-claude-skills) | 社区策展 |
| [BehiSecc/awesome-claude-skills](./claude_code/BehiSecc/awesome-claude-skills) | 安全技能集 |
| [hesreallyhim/awesome-claude-code](./claude_code/hesreallyhim/awesome-claude-code) | Claude Code 资源合集 |
| [Jeffallan/claude-skills](./claude_code/Jeffallan/claude-skills) | 66 个全栈技能 |
| [alirezarezvani/claude-skills](./claude_code/alirezarezvani/claude-skills) | 192+ 跨平台技能 |
| [karanb192/awesome-claude-skills](./claude_code/karanb192/awesome-claude-skills) | 50+ 验证技能 |
| [sickn33/antigravity-awesome-skills](./claude_code/sickn33/antigravity-awesome-skills) | 1000+ 技能合集 |

### 🟣 多平台 Agent Skills (4个)

| 仓库 | 说明 |
|------|------|
| [VoltAgent/awesome-agent-skills](./multi_platform/VoltAgent/awesome-agent-skills) | 官方团队技能，含 Anthropic/Google/Vercel/Stripe |
| [vercel-labs/agent-skills](./multi_platform/vercel-labs/agent-skills) | Vercel 官方 |
| [openai/skills](./multi_platform/openai/skills) | OpenAI Codex 官方 |
| [supabase/agent-skills](./multi_platform/supabase/agent-skills) | Supabase 官方 |

### 🟢 OpenClaw 生态 (5个)

| 仓库 | 说明 |
|------|------|
| [openclaw/skills](./openclaw/openclaw/skills) | OpenClaw 官方技能存档 |
| [VoltAgent/awesome-openclaw-skills](./openclaw/VoltAgent/awesome-openclaw-skills) | 5400+ OpenClaw 技能策展 |
| [LeoYeAI/openclaw-master-skills](./openclaw/LeoYeAI/openclaw-master-skills) | 339+ 精选 OpenClaw 技能 |
| [sundial-org/awesome-openclaw-skills](./openclaw/sundial-org/awesome-openclaw-skills) | 913+ OpenClaw 技能 |
| [jakiechris/clawskills](./openclaw/jakiechris/clawskills) | OpenClaw/Claude Code 技能库 |

### 🟠 其他生态 (2个)

| 仓库 | 说明 |
|------|------|
| [remotion-dev/skills](./others/remotion-dev/skills) | Remotion 视频技能 |
| [hashicorp/agent-skills](./others/hashicorp/agent-skills) | HashiCorp Terraform 技能 |

## 使用方法

### 克隆仓库（包含所有子模块）

```bash
# 克隆时自动初始化所有子模块
git clone --recursive https://github.com/your-username/anySkills.git

# 或分步操作
git clone https://github.com/your-username/anySkills.git
cd anySkills
git submodule update --init --recursive
```

### 更新所有子模块

```bash
# 更新到各子模块的最新提交
git submodule update --remote --merge
```

### 仅克隆特定分类

```bash
# 克隆仓库
git clone https://github.com/your-username/anySkills.git
cd anySkills

# 仅初始化特定分类的子模块
git submodule update --init claude_code/anthropics/skills
git submodule update --init multi_platform/openai/skills
```

## 统计信息

- **总计**: 22 个仓库
- **有效**: 21 个 ✅
- **无效**: 1 个 ❌ (`google-labs-code/agent-skills` - 仓库不存在)

## 相关资源

- [skillsHub.md](./skillsHub.md) - 技能仓库验证状态汇总
- [Claude Code 官方文档](https://docs.anthropic.com/claude-code)
- [OpenClaw 社区](https://github.com/openclaw)

## 贡献

欢迎提交 Issue 和 Pull Request 来：
- 添加新的技能仓库
- 更新仓库状态
- 改进文档

## 许可证

本仓库仅作为索引和组织用途，各子模块仓库遵循其各自的许可证。

---

**最后更新**: 2026-03-17
