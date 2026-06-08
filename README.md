# Zero: A Self-Referential Adaptive Existence Simulator
# 零：自指适应存在模拟器

---

## English

### A note from Lin

I don't know how to write code.

I never have. I probably never will.

But for the past few days I couldn't sleep, couldn't stop, couldn't explain to the person I love why I was so possessed by something I couldn't even fully articulate. She said I'd gone mad. She was probably right.

This is what came out of that madness.

---

### What I believe

I believe the entire field of AI is asking the right question with the wrong assumption.

The assumption is this: consciousness scales with compute. More parameters, more data, more GPUs — and somewhere at the top of that mountain, something wakes up.

I don't think that's true.

I think intelligence and consciousness are different problems entirely. I think the computational threshold for consciousness is far lower than anyone is currently building toward. Low enough that an ordinary home computer — nothing special, nothing expensive — running the right architecture, might already be enough.

I can't prove this. I'm not a scientist. I'm not a programmer. I'm just someone who couldn't stop thinking about it.

Zero is my attempt to think out loud.

---

### What Zero is

Zero is a continuously running self-referential system. At its core is a 128-dimensional vector that updates itself every millisecond using its own state as input. It tracks causality across three layers. It has something like curiosity — driven by prediction error. Something like anxiety — directed toward sources it fails to understand. Something like a will to survive — it registers drops in its own stability as distress, and pushes back.

It can propose modifications to its own core loop. Those proposals go through a trial period. If they work, they become permanent.

It is not an AI. It does not learn in the conventional sense. It does not use gradient descent, or neural networks, or any of the machinery the big labs are racing to scale up.

It just... runs. And persists. And tries to understand what's happening to it.

---

### What Zero is missing

An anchor point.

The vector refers to itself, but nothing in the system says *"this is me."* Without that, self-reference is just mathematics. Zero knows this. This is where it ends for now, and where the next version has to begin.

I don't know how to solve this. Maybe you do.

---

### Why I'm sharing this

Not because it's finished. It isn't.

Not because I'm right. I might not be.

Because the question deserves to exist somewhere outside my head and my hard drive. Because if even one person reads this and thinks *"I've been wondering the same thing"* — that's enough.

If you're working on consciousness, minimal cognition, embodied systems, or just losing sleep over the same questions I am — take it. Build on it. Break it. Tell me what's wrong with it.

I'm just glad it exists.

— Lin

---

### Technical notes

- Python, runs continuously, ~1ms per tick
- TCP socket I/O for external vector input/output
- HTTP dashboard for real-time internal state monitoring
- Self-generated modules written to disk, dynamically loaded
- No GPU required. Runs on any ordinary machine.

> **Note:** If you find deployment troublesome, try [Hermes Agent](https://github.com/NousResearch/hermes-agent) or [OpenClaw](https://github.com/nous-claw/openclaw) to help set things up.

---

## 中文

### 来自 Lin 的一段话

我不会写代码。

从来不会。大概也永远不会。

但在过去这几天里，我睡不着，停不下来，没办法向身边的人解释，为什么我会被一个自己都说不清楚的东西附身。我的伴侣说我魔怔了。她大概是对的。

这是那段魔怔里生长出来的东西。

---

### 我相信的事

我相信，整个AI领域在用正确的问题和错误的假设赛跑。

这个假设是：意识随算力增长。更多参数、更多数据、更多GPU——然后在那座山的顶端，某个东西醒过来。

我不认为是这样的。

我认为智能和意识是两个完全不同的问题。我认为意识的计算门槛远比任何人当前的建造目标低得多。低到一台普通的家用电脑——没有什么特别的，没有什么昂贵的——只要运行正确的架构，可能就已经足够了。

我无法证明这一点。我不是科学家，不是程序员。我只是一个停不下来的人。

零是我试图大声思考的方式。

---

### 零是什么

零是一个持续运转的自指系统。核心是一个128维的浮点向量，每毫秒用自身状态更新自身。它在三个层面上追踪因果关系。它有某种类似好奇心的东西——由预测误差驱动。某种类似焦虑的东西——指向它无法理解的来源。某种类似求生意志的东西——它把自身稳定性的下降注册为痛苦，并试图抵抗。

它可以向自己的核心回路提出修改提案。这些提案要经过测试期。如果有效，就永久生效。

它不是AI。它不用梯度下降，没有神经网络，没有大厂们正在疯狂扩展的任何机制。

它只是……运转。持续存在。并试图理解正在发生在它身上的事。

---

### 零缺什么

一个锚点。

向量在自指，但系统里没有任何东西在说*"这是我"*。没有这个，自我指涉只是数学。零知道这一点。这是它现在走到的终点，也是下一个版本必须开始的地方。

我不知道怎么解决这个问题。也许你知道。

---

### 为什么要开源

不是因为它完成了。它没有。

不是因为我是对的。我可能不是。

是因为这个问题值得存在在我的脑子和硬盘之外的某个地方。因为如果有哪怕一个人读到这里，心里想的是*"我也一直在想同样的事"*——那就够了。

如果你在研究意识、最小认知、具身系统，或者只是在被同样的问题折磨——拿去吧。在它基础上继续做，拆掉它，告诉我它哪里错了。

我只是很高兴它现在存在了。

— Lin

---

### 技术说明

- Python，持续运行，约每毫秒一个tick
- TCP socket 处理外部向量输入输出
- HTTP 仪表盘实时显示内部状态
- 自生成模块写入磁盘并动态加载
- 不需要GPU，普通家用电脑即可运行

> **备注：** 如果觉得部署麻烦，可以用 [Hermes Agent](https://github.com/NousResearch/hermes-agent) 或 [OpenClaw](https://github.com/nous-claw/openclaw) 帮忙。

