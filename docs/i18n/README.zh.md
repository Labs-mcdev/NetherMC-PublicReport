# NetherMC 玩家举报与处罚申诉

[English](../../README.md) · **中文** · [日本語](README.ja-JP.md) · [हिन्दी](README.hi-IN.md)

> 各语言版本如有不一致或歧义，NetherMC 规则以英语版解释为准。规则措辞或翻译问题可通过 [Security and quality](https://github.com/SchemaFoxLabs/NetherMC/security) 中的 **Report a vulnerability** 反馈。

## 仓库用途

本仓库用于 Staff 离线时举报玩家违规，以及对可能误判的限制提出申诉。Staff 在线时优先使用游戏内举报。皮肤仅支持游戏内举报。

服务器／官网 bug、使用疑问和功能建议请提交至[主仓库](https://github.com/SchemaFoxLabs/NetherMC/issues/new/choose)。漏洞通过主仓库的[私密安全渠道](https://github.com/SchemaFoxLabs/NetherMC/security)报告。

## 快捷导航

- **[服务器与社区规则](https://github.com/SchemaFoxLabs/NetherMC/blob/main/docs/i18n/SERVER_RULES.zh.md)**
- **[提交玩家举报](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=player_report.yml)**
- **[提交无媒体证据举报](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=player_report_no_media.yml)** — CSAM Content 或 Illegal PlayerID
- **[提交处罚申诉](https://github.com/Labs-mcdev/NetherMC-PublicReport/issues/new?template=appeal.yml)**
- **[主仓库](https://github.com/SchemaFoxLabs/NetherMC)**

## 玩家举报

玩家举报必须提供有效的游戏内 **Report-ID**。Staff 使用对应游戏记录核对举报人与被举报人；仅持有编号不代表完成身份验证。

Streamer Mode 会隐藏聊天栏中的相关显示。使用以下指令查看举报记录：

```minecraft-command
/report-mylist
```

旧记录会定期清除。原编号不可用时，请前往事件发生的子服获取新编号：

```minecraft-command
/inforeport
```

仍需准确说明原事件时间和经过。新编号不会恢复已清除的记录。

按 **Report-ID → 事件背景 → 置信度及依据 → 脱敏证据** 组织内容。置信度越高，证据应越清晰完整。置信度是举报者自评，不直接决定处罚。

CSAM Content 或 Illegal PlayerID 使用无媒体表单。不要下载、复制、上传、转发或链接 CSAM；仅提供非图像定位信息。

## 处罚申诉

### Join Block

限制生效期间无法进入主大厅或任何子服。有权限的 `Author` 可解除限制。连接界面显示：

- `block reason`
- `block-ID`

### SubServer Block

限制生效期间无法进入受限子服。有权限的 `Author`、`Staff` 或 `Admin` 可解除限制。聊天栏显示：

- `block reason`
- `block-ID`
- `block-duration`

### Feature Block

限制生效期间无法使用受限功能，如 Ranked、公共聊天、私信或跨子服聊天。有权限的 `Author`、`Staff` 或 `Admin` 可解除限制。聊天栏显示：

- `disable reason`
- `disable-duration`

处罚时长以[服务器与社区规则](https://github.com/SchemaFoxLabs/NetherMC/blob/main/docs/i18n/SERVER_RULES.zh.md)为准。

申诉时提供限制类型、可选的 **Player ID**、受影响子服或功能、大致时间（**UTC−8**）、显示原因、申诉理由和可选的脱敏补充材料。如果不填写 Player ID，请在公开 Issue 中请求私密联系方式（如可用可使用 PM），仅通过该私密方式提供 ID。

## 隐私与处理

不要公开真实姓名、私人联系方式、凭据、私密账户资料、敏感标识或无关个人信息。截图应脱敏，同时保留复核所需上下文。

Staff 根据可用时间和证据处理提交。通常 **1–7 天**、繁忙时 **8–30 天**仅为初次处理或首次回复的参考。

提交补充资料前可咨询：`mc-contact@schemafoxlabs.com`。发送敏感证据前先询问适当方式。邮箱可能无法接收超过 **20 MiB** 的附件。
