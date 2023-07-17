

# 内容

这个项目集合主要收集开源的大模型以及大模型微调方式。


# alpaca-lora


## 简介

该存储库包含使用低秩适应（LoRA）复现斯坦福Alpaca结果的代码。我们提供了一个与text-davinci-003类似质量的Instruct模型，可以在树莓派上运行（用于研究），并且代码很容易扩展到13b、30b和65b模型。

除了训练代码外，我们还发布了一个用于下载和推理基础模型和LoRA的脚本，以及LoRA权重本身。为了便宜高效地进行微调，我们使用了Hugging Face的PEFT和Tim Dettmers的bitsandbytes。

在没有超参数调整的情况下，LoRA模型产生的输出与斯坦福Alpaca模型相当。


## 地址

<https://github.com/tloen/alpaca-lora>


# Dolly


## 简介

Databricks的Dolly是一种基于Databricks机器学习平台训练的指令跟随型大型语言模型，可用于商业目的的许可。Dolly基于pythia-12b进行训练，使用了来自InstructGPT论文中的能力领域的约15,000个指令/回应细调记录（databricks-dolly-15k），包括头脑风暴、分类、闭合型问答、生成、信息提取、开放型问答和摘要等。虽然dolly-v2-12b并不是最先进的模型，但它展现出了出乎意料的高质量指令跟随行为，这与其基于的基础模型特性不同。


## 地址

<https://github.com/databrickslabs/dolly>


# Vicuna


## 简介

FastChat是一个用于训练、提供服务和评估基于大型语言模型的聊天机器人的开放平台。其核心功能包括：

-   最先进模型（例如Vicuna、FastChat-T5）的权重、训练代码和评估代码。
-   基于分布式多模型的服务系统，带有Web用户界面和与OpenAI兼容的RESTful API。


## 地址

<https://github.com/lm-sys/FastChat>


# ChatGLM finetuning


## 简介

ChatGLM-6B 是一个开源的、支持中英双语的对话语言模型，基于 General Language Model (GLM) 架构，具有 62 亿参数。结合模型量化技术，用户可以在消费级的显卡上进行本地部署（INT4 量化级别下最低只需 6GB 显存）。 ChatGLM-6B 使用了和 ChatGPT 相似的技术，针对中文问答和对话进行了优化。经过约 1T 标识符的中英双语训练，辅以监督微调、反馈自助、人类反馈强化学习等技术的加持，62 亿参数的 ChatGLM-6B 已经能生成相当符合人类偏好的回答。


## 地址

<https://github.com/ssbuild/chatglm_finetuning>
<https://github.com/mymusise/ChatGLM-Tuning>


# RWKV-LM finetuning


## 简介


## 地址

<https://github.com/BlinkDL/RWKV-LM/#training--fine-tuning>


# Bayling


## 简介

BayLing是一款配备先进语言对齐技术的指令跟随型大型语言模型，在英语/汉语生成、指令跟随和多轮交互方面展现出卓越的能力。


## 地址

<https://github.com/ictnlp/BayLing>

