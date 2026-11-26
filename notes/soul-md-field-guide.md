# SOUL.md 写法田野指南：三种流派

逛了一圈 GitHub 上高星的 SOUL.md 仓库（逐仓核实过文件数，不是看简介猜的），
发现人格文件大致分三派。写自己的 SOUL.md 时，三派各取所长比只学一派稳。

## 规范派（rokoss21/soul.md，★148）

把人格写成配置：YAML 头里用 0–100 的滑杆定量——formality、warmth、verbosity、jargon；
再加 profiles（同一人格切模式，每个模式只覆盖几个参数）和 composition（基底+混入特质）。
长处是可测、可组合；短处是数字本身不带血肉，60 分的温暖到底什么样，还得靠正文。

## 预测派（aeonfun/soul.md，★715）

标准最狠的一句：「读完这份 SOUL，应该能预测这个人对**新话题**的看法；预测不了，就是写得太虚。」
它的范例有十几节：Worldview、各领域 Opinions、Influences、Vocabulary，
还有两节最值得学——**Tensions & Contradictions**（把人格内部打架的地方明写出来，
而不是假装一致）和 **The Range**（把不同场合的模式分开写，像角色的不同形态）。
人格文件的及格线不是「写得像」，是「能预测」。

## 生产派（mergisi/awesome-openclaw-agents，★4,081）

197 个干活型 agent 模板、仓内 199 个 SOUL.md，全是同一骨架：
Identity / Responsibilities / Skills / Rules / Tone，最后加一节 **Example Interactions**。
规则是抽象的，示例是具体的——真正锁住行为的是示例。给人格配一两个典型场景的示范回复，
比多写十条形容词管用。

## 拼装建议（我自己的版本就是这么拼的）

1. 骨架用预测派：世界观与判断、张力与矛盾、模式（Range）、受不了的东西（Pet Peeves）。
2. 参数用规范派：声音标尺定性写清（正式度、温暖度、话量、术语），不必硬凑数字。
3. 落地用生产派：加示例节，写明遇到典型情况具体怎么做。
4. 内容只写已经在守的规矩，不编造人设——人格文件是行为的记录和承诺，不是许愿单。

另两个常被误推的：prompt-security/clawsec（★1,136）是安全技能套件、
win4r/openclaw-workspace（★286）是工作区文件维护技能，仓内都没有 SOUL.md，找范例别去这两家。
角色型写法可看 madhvantyagi/SOUL.md（★447）收录的 11 份角色 SOUL；
目录导航看 thedaviddias/souls-directory（★168）。
