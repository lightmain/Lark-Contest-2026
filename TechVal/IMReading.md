# IM 阅读结果

## 我与我自己的对话内容的最早的三条

```text
1. 2026-04-23 20:15
🙋开赛直播材料同步
同学们好，这是今天赛事直播的录屏和会议材料，请同学们查收哦：
1.  会议妙记[https://bytedance.larkoffice.com/minutes/obcn7xk3bg1olx8lb811fq4i](https://bytedance.larkoffice.com/minutes/obcn7xk3bg1olx8lb811fq4i)）申请请备注姓名+学校
2. 直播文档&赛事介绍文档：[https://bytedance.larkoffice.com/wiki/Eq0ywVPwdirCLakfBeucCwKWnoh](https://bytedance.larkoffice.com/wiki/Eq0ywVPwdirCLakfBeucCwKWnoh)
认领入口：[https://bytedance.larkoffice.com/sheets/Ehw0sK4DKhjtyttqiMecKG42nOc](https://bytedance.larkoffice.com/sheets/Ehw0sK4DKhjtyttqiMecKG42nOc)[https://bytedance.larkoffice.com/docx/KlW9dIlyzo17ccxl26Gc9TGsnig](https://bytedance.larkoffice.com/docx/KlW9dIlyzo17ccxl26Gc9TGsnig)
[https://bytedance.larkoffice.com/wiki/ZD3xwFgoYiZJD0kYSU4cn4OCnEe?pre_pathname=/drive/home/](https://bytedance.larkoffice.com/wiki/ZD3xwFgoYiZJD0kYSU4cn4OCnEe?pre_pathname=/drive/home/)，提交链接问卷链接🔗：[https://bytedance.larkoffice.com/share/base/form/shrcnzEu4HIkSVRpcU1EF0ZH8JC](https://bytedance.larkoffice.com/share/base/form/shrcnzEu4HIkSVRpcU1EF0ZH8JC)

2. 2026-04-24 12:41
@所有人 各位同学好，关于模型资源升级的后续进展来了～

【新资源已就绪】
- 新的 API Key 和 Endpoint ID 已配置完成，模型升级为 豆包2.0 Pro 版本，性能更强，处理复杂任务更丝滑，（1.6版本的EP仍可以通过原表单进行自助领取）。
- 后续，大家可以用新 Key 和新 EP 接入豆包 2.0 Pro 模型，也可以用已认领的个人 EP 接入 1.6 模型。大家可以根据任务需要，灵活选择。

【发放规则】
我们将通过多维表滚动发放，规则如下：
- 昨晚已完成问卷填写的同学，资源已分配，现在就可以去多维表自行领取
- 尚未填写问卷的同学，请尽快完成填写，提交后我们会陆续发放
🔗 问卷链接：[https://bytedance.larkoffice.com/share/base/form/shrcnzEu4HIkSVRpcU1EF0ZH8JC](https://bytedance.larkoffice.com/share/base/form/shrcnzEu4HIkSVRpcU1EF0ZH8JC)
-  问卷已简化，已领取的1.6版本EP无需重复提交。

【新API Key & EP的领取方式】
- 【新 API Key 和 Endpoint ID-领取链接】：[https://bytedance.larkoffice.com/base/SirHbPIqmaqLnZsHaCkcx7esnyc?table=tblsT5q43EP8tjKU&view=vewixQ9v8F](https://bytedance.larkoffice.com/base/SirHbPIqmaqLnZsHaCkcx7esnyc?table=tblsT5q43EP8tjKU&view=vewixQ9v8F)

【使用规范再强调 ⚠️】
- 严禁外泄：该 Key 与小组或个人绑定，请大家务必妥善保管，严禁以任何形式公开或分享给非参赛人员。 一旦发现违规使用，将直接影响参赛资格。
- 专用于竞赛： 所有资源仅限用于本次 AI 校园挑战赛 的开发，请勿用于任何与竞赛无关的个人或商业用途。
- 违规使用一经发现，将直接影响参赛资格，必要时追究相关责任。

「附：MCP服务」
- 如需MCP服务，可直接用 larksuite/cli
- [GitHub - larksuite/cli: The official Lark/Feishu CLI tool, maintained by the larksuite team — built ](https://github.com/larksuite/cli)

3. 2026-04-24 12:41
【重要通知】关于飞书 AI 校园挑战赛模型资源升级说明
@所有人 各位同学，晚上好～
首先，非常抱歉给大家带来了不佳的初体验。收到大家集中反馈的模型版本问题后，今晚项目组紧急召开了内部会议，现将最终解决方案同步如下：

1、新方案细节与说明：
- 模型版本升级，同时保留备用方案：
	- 主力模型升级： 我们将为大家启用版本最新、性能更强的 豆包 2.0 Pro 模型，以全力保障大家的开发体验。
	- 原有资源保留： 原提供的豆包 1.6 模型资源依然保留，作为 Pro 模型的备用方案。当遇到Pro资源并发过高而被限制时，大家可以随时切换回1.6模型，确保开发不中断。
- 关于使用方式： 为了充分发挥 Pro 模型的性能，避免因额度拆分过细导致单个用户遇到复杂任务就“熔断”，我们会将资源集中在共享接入点。这意味着每位同学在单任务上将获得比之前高得多的算力上限，处理复杂代码工程更丝滑。
- 关于并发风险（请大家特别留意）： 由于资源总量有限，在大家同时高并发调用的极端情况下，可能会短暂遇到请求失败。如果遇到调用失败，不用慌张，稍等一两分钟后重试即可恢复，如果等不及，也可以随时切回豆包 1.6 模型。我们也会实时监控资源池，尽最大努力保障稳定。


2、使用规范与安全红线（必读）：
- 严禁外泄： 我们后续将发放新的 API Key。该 Key 与小组或个人绑定，请大家务必妥善保管，严禁以任何形式公开或分享给非参赛人员。 一旦发现违规使用，将直接影响参赛资格。
- 专用于竞赛： 所有资源仅限用于本次 AI 校园挑战赛的开发，请勿用于任何与竞赛无关的个人或商业用途。

接下来，你需要做什么：
请大家耐心等待，技术同学正在连夜配置新的模型接入点。原有 API Key 已停用，新的Endpoint ID和API Key将于明天上午在群内分区发布。
届时，大家可以用新 Key 和新 EP 接入豆包 2.0 Pro 模型，也可以用已认领的个人 EP 接入 1.6 模型。大家可以根据任务需要，灵活选择。

再次为开营时版本沟通考虑不周向大家致歉，也提前祝大家打造出优秀的大赛作品！加油
```

