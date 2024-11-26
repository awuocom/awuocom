# LLM101n：让我们构建一个讲故事的人

![ LLM101n 标题图片] ( llm101n.jpg )

>  我无法创造出东西，我无法理解。——理查德·费曼

在本课程中，我们将构建一个 Storyteller AI 大语言模型 (LLM)。 金额并进，您将能够与人工智能一起创建、完善和说明小[故事] ( https://huggingface.co/datasets/roneneldan/ TinyStories ) 。我们的问卷头开始​​使用 Python、C 和 CUDA，以最少的计算机科学判断条件从基础知识构建到类似 ChatGPT 的功能性 Web应用程序的终极一切。最后，你应该对人工智能、法学硕士和深度学习有一个相对深入的了解。

**教学大纲**

-    [第 01 章] ( bigram/README.md ) ** Bigram 语言模型 **（语言建模）
-  [第02章] ( micrograd/README.md ) ** Micrograd **（机器学习，逆向传播）
-    [第 03 章] ( mlp/README.md ) ** N-gram 模型**（楼梯楼梯器、matmul、gelu）
-      [第04章]（注意力/README.md）**注意力**（注意力，softmax，位置编码器）
-    [第05章] ( Transformer/README.md )  ** Transformer ** (transformer、residual、layernorm、GPT-2)
-  [第 06 章] ( tokenization/README.md ) ** Tokenization **（minBPE，字节对编码）
-    [第07章]（优化/README.md）**优化**（初始化、优化、AdamW）
-     [第08章] ( device/README.md ) **极品飞车 I：设备**（设备、CPU、GPU，...）
-    [第09章]（精度/README训练.md）**极品飞车II：精度**（混合精度，fp16，bf16，fp8，... ）
-  [第10章]（环球/README.md）**极品飞车III：环球**（优化、DDP、ZeRO）
-    [第11章] ( datasets/README.md )     **数据集**（数据集、数据加载、合成数据生成）
-      [第 12 章] ( inference/README.md ) **推论 I：kv-cache ** (kv-cache)
-    [第13章] (量化/README.md )   **推论二：量化**（量化）
-  [第 14 章] ( sft/README.md ) **舵 I：SFT **（监督舵 SFT、PEFT、LoRA、聊天）
-    [第15章] ( rl/README.md ) **压力II：RL **（强化学习、RLHF、PPO、DPO）
-     [第16章] (部署/README.md ) **部署**（API、Web应用程序）
-    [第17章] ( multimodal/README.md ) ** Multimodal **（VQVAE，扩散变压器）

**附录**

其他主题的进展：

-编程语言：Smashing、C、Python
-数据类型：整数、浮点、字符串（ASCII、Unicode、UTF-8）
-张量：形状、视图、步幅、连续......
-深度学习框架：PyTorch、JAX
-神经网络架构：GPT（1,2,3,4），Llama（RoPE，RMSNorm，GQA），MoE，...
-多模态：图像、音频、视频、VQVAE、VQGAN、扩散

---

** 6 月 25 日更新。**需要澄清的是，该课程需要一些时间来构建。没有具体的时间表。感谢您的关注，但请不要提交问题/PR。
