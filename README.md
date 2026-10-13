# handdrawn-knowledge-card

「鸿蒙手绘课堂」知识卡片 Skill：生成手绘涂鸦风、16:9、单主题色的课程知识卡片，包含版式选择、中文绘图提示词模板、风格规范和 5 张参考图。

## 给 WorkBuddy / Agent 的安装提示词

把下面整段复制到 WorkBuddy 对话框：

> 请从这个公开 GitHub 地址安装 Skill：
> https://github.com/wuhetu619-crypto/handdrawn-knowledge-card/tree/main/skills/handdrawn-knowledge-card
> 
> Skill 名称是 `handdrawn-knowledge-card`（鸿蒙手绘课堂知识卡片）。请获取该目录下完整内容，包含 `SKILL.md`、`references/` 和 `assets/`，安装到当前 Agent 的用户级 Skills 目录；如果可以执行 GitHub CLI，请执行：`gh skill install wuhetu619-crypto/handdrawn-knowledge-card skills/handdrawn-knowledge-card --dir ~/.workbuddy/skills`。如果当前环境不是 WorkBuddy，请改用该 Agent 的用户级 Skills 目录。安装后请验证 `SKILL.md` 能被识别，并告诉我实际安装路径。不要只复制 `SKILL.md`，不要遗漏参考文件和图片资源。

如果 WorkBuddy 不能直接从 GitHub 安装，也可以在 WorkBuddy 的「技能 → 添加技能 → 上传技能」中上传 [`releases/handdrawn-knowledge-card.zip`](releases/handdrawn-knowledge-card.zip)。

## 目录

- `skills/handdrawn-knowledge-card/`：可按 GitHub 路径安装的 Skill 源目录。
- `releases/handdrawn-knowledge-card.zip`：原始 Skill 压缩包的完整副本。

## 校验

原始 ZIP SHA-256：`ece1c1db0f6df5e7bfd64bdfadcbb31fe44e6bffdacfc9e4ad6249cc7643d16e`
