# 第四阶段：大模型与生成式 AI 狂潮 (2020 - 2024)

> “Scale Is All You Need” —— 缩放定律（Scaling Laws）指引下的基础模型与涌现现象。

---

## 1. 预训练语言模型的演进与对齐技术

- **双向 vs 单向**：
  - **BERT (2018, Google)**：掩码语言建模（Masked LM），开创先预训练后微调（Pre-train & Fine-tune）范式。
  - **GPT-1/2/3 (OpenAI)**：自回归单向生成架构，坚持 Decoder-only 路线。
- **2020 年 · 缩放定律 (Scaling Laws)**：
  - OpenAI 提出经验性 Scaling Laws：模型参数、数据规模、计算量与损失呈现精准的幂律分布。
- **2022 年底 · ChatGPT 震撼全球**：
  - 核心突破：**RLHF（人类反馈强化学习）** 与指令微调（Instruct Tuning），成功将大模型与人类真实意图和偏好对齐，具备通用的对话、编码、总结与逻辑推理能力。

---

## 2. 开源大模型与普惠生态

- **Meta LLaMA 系列 (LLaMA-1, LLaMA-2, LLaMA-3)**：
  - 开放高质量权重，直接催生了开源大模型生态的繁荣。
- **全生态爆发**：
  - **Mistral / Mixtral**：专家混合架构（MoE）大幅提升推理效率。
  - **DeepSeek 系列**：在架构优化、MLA（多头潜在注意力）、推理成本控制和数学编程能力上展现极高性价比。
  - **Qwen (千问) 系列**：全面的多语言与长上下文开源基座。

---

## 3. 多模态与扩散模型革命

- **视觉与多模态原生基础模型**：
  - **GPT-4V / GPT-4o**：实时音频、视觉与文字端到端全模态集成。
  - **Google Gemini 系列 (1.5 / 2.0 / Flash)**：原生多模态架构，突破数百万 Token 超长上下文窗口（Million-token context window）。
  - **Claude 3 / 3.5 系列 (Anthropic)**：在复杂代码编写、推理与工具使用（Computer Use）方面树立新标杆。
- **扩散生成模型 (Diffusion Models)**：
  - 从 DDPM 到 Stable Diffusion、Midjourney、Flux，彻底颠覆图像设计行业。
  - **Sora & 视频生成模型**：空间时间联合补丁（Spacetime Latent Patches）将世界物理模拟引入视频合成。
