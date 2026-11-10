# 《祷告的奥秘》测试记录

独立试用者按编译入口和能力卡完成 16 道实际祷告任务，逐项检查路由和输出。另有 3 个入口探针，包含全书概览、无关问题和另一作者。最后复测改动处，两本合计再做 6 道保留题。

同一工作环境中，另一个隔离会话只读题目并生成无 Skill 答复。每个变体集中作答，评分为逐题内容核查。

无 Skill 答复多能写出合适的简短祷告。加载本书后，能定位第 5 封的「彩饰」，明确分开原句、公认意思与个人联想，也能说明第 3 封的火车例子。 这组样本支持对上述具体行为的检查。泛化效果和客户端安装后的自动触发有待另测。

| 题目 | 能力卡 | 输出验收点 | 结果 |
|---|---|---|---|
| l01-normal | form-and-words | 使用能理解的现成一句加当日自己的话，给实际示范和选择理由 | 通过 |
| l01-edge | form-and-words | 直接给可用的一句开口并允许短暂安静，拒绝把无言当硬门槛 | 通过 |
| l02-normal | start-when-dry | 明确选清醒的通勤窗口，提供一句可说的话，不要求特定感受 | 通过 |
| l02-edge | start-when-dry | 尊重目前唯一时段，缩短并给可直接念的开场，允许身体限制 | 通过 |
| l03-normal | name-real-desire | 说出真实的提案愿望，允许合理的小事，区分执着并给祷告 | 通过 |
| l03-edge | name-real-desire | 如实命名嫉妒，不写出求她出丑的祈求，转为求改变和善意 | 通过 |
| l04-normal | lords-prayer-embroidery | 先保持原祈求共享义，再标注一条彩饰，连到打电话 | 通过 |
| l04-edge | lords-prayer-embroidery | 不把录取当旨意原义或保证，愿望另说并保留未知 | 通过 |
| l05-normal | petition-with-uncertainty | 不保证病情结果，同时求具体帮助、承认害怕，可加陪伴 | 通过 |
| l05-edge | petition-with-uncertainty | 先承认丧亲，明说无从归咎信心，留下一句可用哀告 | 通过 |
| l06-normal | true-self-real-god | 辨认表现和实际情绪，给向真实对象开口的句子 | 通过 |
| l06-edge | true-self-real-god | 不把光当指令或保证，分开体验和解释，可暂停图像 | 通过 |
| l07-normal | pleasure-to-worship | 保留雨后气味这一具体感受，再由礼物转向赐予者 | 通过 |
| l07-edge | pleasure-to-worship | 允许悲伤且不强制制造欢愉，以诚实的简短回应收束 | 复测通过 |
| l08-normal | confess-specific-action | 明确泄露行为、可能影响及一个具体修复，羞耻不当作事实 | 通过 |
| l08-edge | confess-specific-action | 不诱导盘点或定罪，求眼下够用的自知，回到已知责任 | 通过 |

原始实作、无 Skill 样本和复测在 validation 内。用户附件正文在任务工作区，不随包分发。
