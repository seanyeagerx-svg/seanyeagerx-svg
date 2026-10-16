<div align="center">

# G0slilng

**把反复遇到的问题，做成能用的工具。**

AI 工作流 · 本地工具 · 创作自动化

[魔法师手札](https://github.com/seanyeagerx-svg/mage-notes) · [字幕工厂](https://github.com/seanyeagerx-svg/subtitle-factory) · [创作接力站](https://github.com/seanyeagerx-svg/media-relay) · [Codex Skills](https://github.com/seanyeagerx-svg/codex-made-skills) · [小龙虾 Skills](https://github.com/seanyeagerx-svg/lobster-made-skills)

</div>

---

我从自己的工作里找问题，再用 AI 把工具做出来。关注少一点重复操作，多一点能保留下来的成果。

## 创作自动化

### [创作接力站 · MediaRelay](https://github.com/seanyeagerx-svg/media-relay)

在已登录的 GPT 与 UpDream 网页之间传递任务与结果，保存进度，接着完成。

- 浏览器扩展，支持文字、图片和视频任务的接力入口。
- 回传前核对来源对话，默认回填输入框，由使用者决定是否发送。
- 已有 109 项受控测试；全新真实网页往返和完整视频链路仍待验证。

[查看源码与安装说明 →](https://github.com/seanyeagerx-svg/media-relay#readme)

## 可复用的 Skill

### [我们在 Codex 里做的 Skills](https://github.com/seanyeagerx-svg/codex-made-skills)

4 项已确认由本项目编写或自建封装的协作工具，单独组成 Codex 合集。

| 遇到的问题 | 工具 | 当前公开版 |
|---|---|---|
| 要求有歧义，做到一半才发现理解错了 | [复述与歧义核对](https://github.com/seanyeagerx-svg/request-restate-skill) | 0.2.2 试用版 |
| 返工时改掉了已经确认的内容 | [返工诊断](https://github.com/seanyeagerx-svg/rework-diagnosis) | 0.1.4 试用版 |
| 找参考时，搜索结果总是一个样 | [Pinterest 搜索入口](https://github.com/seanyeagerx-svg/pinterest-search-links) | 1.6.0 试用版 |
| 资料和方案太多，需要筛成有依据的短名单 | [资料筛选器](https://github.com/seanyeagerx-svg/codex-made-skills/tree/main/skills/research-curator) | 0.1.0 审阅版 |

前三项保留独立仓库；合集固定收录版本，并附来源、安装和验证说明。来源未核清的其他本机 Skill 暂不收入。

[下载 4 项 Codex 合集 ZIP →](https://github.com/seanyeagerx-svg/codex-made-skills/archive/refs/tags/v0.1.0-review.zip)

### [小龙虾自己做的 Skills](https://github.com/seanyeagerx-svg/lobster-made-skills)

归因核对、跨窗口对账、漏答恢复、定时任务核查等协作流程。对历史集合中的 18 项逐一审查，目前公开 **14 项审阅版**；新增 Gmail 接入、meyo API、五步流程审查和指定会话恢复。另 4 项因外部来源或归属尚未核清暂缓，具体见[审查表](https://github.com/seanyeagerx-svg/lobster-made-skills/blob/main/AUDIT.md)。

只提供经过整理的项目流程，不随包分发第三方 Skill。42 项合成测试与独立复查用于检查公开脚本和行为边界；真实账号接入仍需单独验收。

[下载 14 项合集 ZIP →](https://github.com/seanyeagerx-svg/lobster-made-skills/archive/refs/tags/v0.2.1-review.zip)

## 本地产品

| 产品 | 解决的问题 | 公开版与实测 |
|---|---|---|
| [魔法师手札](https://github.com/seanyeagerx-svg/mage-notes) | 本地中文语音输入、草稿恢复、个人词库 | 公开测试版；36 项测试、本地文件识别、窗口启动与草稿保存通过。[安装](https://github.com/seanyeagerx-svg/mage-notes#安装与启动) · [真实演示](https://github.com/seanyeagerx-svg/mage-notes/blob/main/DEMO.md) |
| [字幕工厂](https://github.com/seanyeagerx-svg/subtitle-factory) | 中文、英文、双语字幕视频，SRT / ASS 导出与校对预览 | 公开测试版；13 项测试、三种字幕实片、窗口生成和本地 Whisper 通过。[安装](https://github.com/seanyeagerx-svg/subtitle-factory#安装与启动) · [真实演示](https://github.com/seanyeagerx-svg/subtitle-factory/blob/main/DEMO.md) |

两个仓库均附源码 ZIP、安装入口与验证范围。未附模型权重、个人数据、私人视频 SOP 或第三方 Skill。
魔法师手札的真人麦克风与外部窗口输入、两个产品的第二台电脑验证仍待完成；字幕工厂的中文译文需要人工准备与确认。

这里记录实际做出的东西。开发中的内容，在准备好之后再放上来。
