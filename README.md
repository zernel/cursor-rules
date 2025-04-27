# Cursor Rules 项目模板

本项目用于作为新项目的初始化模板，clone 后可直接复制 `.cursor` 和 `docs` 目录，快速搭建项目的基础文档和规则体系。

## 目录结构说明

- `.cursor/`：存放项目规则、错误记录、经验总结等自动化和 AI 辅助相关文件。
  - `rules/`：建议存放规则文件、错误文档（error-documentation.mdc）、经验总结（lessons-learned.mdc）等。
- `docs/`：存放项目核心文档，包括需求、架构、技术方案、开发上下文等。
  - `product_requirement.md`：产品需求文档（PRD），说明项目目标、核心需求、解决的问题。
  - `architecture.md`：系统架构文档，描述系统组件、关系、依赖、整体流程。
  - `technical.md`：技术方案与开发环境说明，包含技术选型、开发环境、关键技术决策等。
  - `active_context.md`：当前开发上下文，记录当前关注点、最新决策、变更、下一步计划。

## 使用方法

1. 克隆本项目：
   ```bash
   git clone <本项目地址> your-new-project
   cd your-new-project
   ```
2. 复制 `.cursor` 和 `docs` 目录到你的新项目根目录：
   ```bash
   cp -r .cursor docs <你的新项目目录>
   ```
3. 按照 `docs/` 目录下各模板文件的说明，补充完善你的项目文档。

## 推荐工作流

- 所有项目相关的需求、架构、技术、开发上下文等信息，均应记录在 `docs/` 目录下对应文件。
- 详细的文档结构和内容模板请参考 `docs/` 目录下的各文件说明。