# Prompt Engineering Techniques

提示工程技术。

对于 Azure OpenAI GPT 模型，目前有两个不同的 API，提示工程可以在其中发挥作用：

- 聊天补全 API。[**Chat Completion**]
- 补全 API。[Completion]

每种 API 要求以不同的格式输入数据，这反过来又会影响整体的提示设计。 **聊天补全 API** 支持 ChatGPT 和 GPT-4 模型。 这些模型旨在接收存储在字典数组中的[类似聊天的特定脚本](https://learn.microsoft.com/zh-cn/azure/cognitive-services/openai/how-to/chatgpt)格式的输入。

从技术上讲，ChatGPT 模型可与任一 API 一起使用，但强烈建议对这些模型使用聊天补全 API。 

## System message

系统消息。

## Few-shot learning

少样本学习。

## Non chat scenarios

非聊天场景。

## Start with clear instructions

从明确的说明开始。

## Repeat instructions at the end

在末尾重复指令。

## Prime the output

引导输出。

## Add clear syntax

添加明确的语法。

## Break the task down

分解任务。

## Use of affordances

使用可供性。

## Chain of thought prompting

思维链提示。

## Specifying the output structure

指定输出结构。

## Temperature and Top_p parameters

温度和Top_p参数。

## Provide grounding context

提供基础上下文。
