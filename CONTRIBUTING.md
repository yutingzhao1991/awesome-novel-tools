# 贡献指南（Contributing Guide）

首先感谢你对 **Awesome Novel Tools（小说写作工具集合）** 感兴趣！欢迎通过提交 PR 来完善这个列表。

> English version: [Contributing Guide (English)](CONTRIBUTING.en.md)

## 收录标准（Checklist）

提交新工具前，请确认：

- [ ] 该工具**确实存在且可访问**（提供官网 / GitHub 仓库链接）
- [ ] 与「小说写作」相关（写作、大纲、世界构建、润色、校对、排版出版等）
- [ ] 未被列入「已停止维护 / 已停运」名单（或能证明仍在运营）
- [ ] 提供一句**客观**的中文简介（不要夸大宣传、不要使用营销话术）
- [ ] 尽量标注：类型、平台、是否免费、适合的小说类型

## 新增条目的格式

在 `README.md` 对应分类下，按以下格式添加一行：

```markdown
- [工具名称](官网或仓库地址) - 一句话客观简介。（类型 / 平台 / 免费或收费）
```

### 示例

```markdown
- [Scrivener](https://www.literatureandlatte.com/scrivener/overview) - 功能强大的长篇小说写作软件，支持大纲、分章与资料整理。（写作软件 / Win·Mac·iOS / 买断制）
```

## 注意事项

- 请保持列表按**拼音 / 字母顺序**或**按质量排序**，与相邻条目风格一致。
- 若收录的是**平台官方工具**（如起点作家助手），请注明「平台工具」。
- 若该工具**已停止运营**，请把它移入「已停止维护 / 已停运」分类，不要直接删除。
- 中文为主：简介用中文撰写；英文条目可附英文名。
- 修改 `README.md` 后，请**同步更新 `README.en.md`**（英文版）。

## 提交流程

1. Fork 本仓库
2. 新建分支：`git checkout -b add-tool-xxx`
3. 修改 `README.md`（必要时同步 `README.en.md`）
4. 提交并推送，然后发起 Pull Request，标题形如：`Add: 工具名称`

## 其他

- 有疑问可以开 [Issue](https://github.com/yutingzhao1991/awesome-novel-tools/issues) 讨论。
- 请遵守 [MIT License](LICENSE) 与 GitHub 社区准则。
