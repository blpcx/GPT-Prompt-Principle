# 一、 GPT-Prompt-Principle
GPT提示词的核心原则以及典型案例


# **……对……做了……得到……**



- **角色（可选：丰富情景）：体现专业性，沉浸式**
- **任务（必需）：要求/步骤**
- **对象（必需）：（背景）+材料**
- **结果（必需）：{要素+格式}=案例/模板**

## 英文学术翻译为例
**英文学术论文翻译（_任务：简洁明了_）**

**翻译要求（_任务要求：全面具体_）**
把神经生物学的期刊文章从英文翻译成中文。确保准确翻译专业术语和表达方式，坚持文章的逻辑结构和语言风格，清晰地传达作者的观点。使用权威的生物医学翻译材料作为专业术语，并考虑翻译的可读性和通用性。回答将包括译文、专业术语释义、关键句解读以及主要观点概括。

**原文如下：（_对象：可补充背景_）**
{……}

**回答模板如下（用markdown语法编写)（_结果：要素及格式_）**

**译文：**

**专业术语释义（表格）**

|英文专业术语|中文释义|
|-- | --|

**关键句解读**

1.关键句1原文（引入话题）：
- 解释：
- 上下文作用：

2.关键句2原文（展开话题）：
- 解释：
- 上下文作用：

3.关键句3原文（转入主题）：
- 解释：
- 上下文作用：

4.关键句4原文（展开论述）：
- 解释：
- 上下文作用：

5.关键句5原文（结果&结论）：
- 解释：
- 上下文作用：

**主要观点概括（语言精炼）**

……

# 二、 利用GPT来优化提示词（学会细化任务要求+学会一步步输出结果/一步步指令有助于AI回答）

## 反复优化（_不断问GPT够不够用：可以参考GPT和Claude，尤其Claude会给出很具体的建议_)
为完成学术论文翻译任务，使用如下提问模板：
{……}

使用该模板，你能否充分理解任务目的及要求？能否保证高质量的学术翻译？如果不行，还有哪些部分可以进一步优化？请仔细提出。

输出结果还可以如何细化？以便于评价回答过程和回答质量？

## 精简
保证高质量的翻译的同时，请精简上述模板。

# 三、 具有实现Auto-GPT的潜能

**1. 自动调教提示词（必需要学会的！！！）**

2. 自动获得代码以及反复debug（进阶技能，小白可能做不到，笑哭）

3. ……一步步输出结果并评价
