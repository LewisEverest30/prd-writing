# prd-writing

产品组 PRD 写作 Skill。全量版维护当前完整定义；每个大版本定稿后，增量版向开发说明相对上一已交付大版本的变化。两种任务按需加载对应说明。

## 安装

从 [GitHub 仓库](https://github.com/LewisEverest30/prd-writing) 下载，将包含 `SKILL.md` 和 `references/` 的目录放入 Skill 安装位置。安装后的结构为：

```text
~/.agents/skills/prd-writing/
├── SKILL.md
└── references/
    ├── full-prd.md
    └── incremental-prd.md
```

如果下载的仓库目录不是 `prd-writing`，安装时将目录改为该名称。更新时重新下载并替换安装目录，随后开启新会话。

## 使用

在任务中说明要写「全量版 PRD」或「vX 增量版 PRD」。Skill 会按任务读取相应参考文件。具体项目的现行规范和业务事实优先；遇到版本规则冲突，先列出差异并确认。
