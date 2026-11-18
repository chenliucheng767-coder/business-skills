# 团队业务 Skill 仓库

存放团队业务同学生产、复用的 skill。

## 目录

| Skill | 用途 |
|---|---|
| [business-skill-builder](skills/business-skill-builder/SKILL.md) | 把业务方法变成 skill：从零生成、已有 skill 查漏补缺、效果不好时调整 |

## 安装

把需要的 skill 文件夹复制到自己的 Codex skills 目录：

```bash
git clone git@github.com:chenliucheng767-coder/business-skills.git
cp -R business-skills/skills/business-skill-builder ~/.codex/skills/
```

重启 Codex 后，说“帮我把我的工作方法做成 skill”即可使用。

## 新增 skill

1. 先写业务方法文档（模板见 `skills/business-skill-builder/references/method-template.md`）
2. 用 business-skill-builder 生成 skill，并用真实案例验收
3. 放到 `skills/<skill-name>/` 下提交

案例中的店铺、供应商、价格、客户信息提交前必须脱敏。
