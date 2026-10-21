# 第三阶段：深度学习革命与感知突破 (2011 - 2020)

> 算力（GPU）、数据（ImageNet）与深度架构的三位一体，彻底释放连接主义的威力。

---

## 1. 计算机视觉大爆发：从 AlexNet 到 ResNet

- **2012 年 · AlexNet 与 ImageNet 历史时刻**：
  - Alex Krizhevsky, Ilya Sutskever 和 Geoffrey Hinton 设计的 **AlexNet** 在 ImageNet 大赛中以远超第二名传统特征工程模型的断层优势夺冠。
  - 核心突破：CUDA GPU 并行加速计算、ReLU 激活函数、Dropout 正则化。
- **深度扩展与残差连接**：
  - **VGGNet (2014)**：标准化小卷积核（3x3）堆叠。
  - **GoogLeNet / Inception (2014)**：多尺度特征提取。
  - **ResNet 残差网络 (2015, 何恺明等人)**：通过残差学习（Skip Connection）解决了超深网络（100+ 层）梯度消失与退化问题，在视觉识别任务中全面超越人类感知准确率。

---

## 2. 深度强化学习：DeepMind 与围棋奇迹

- **2013/2015 年 · DQN (Deep Q-Network)**：
  - DeepMind 结合深度学习与强化学习，在 Atari 2600 经典游戏上实现端到端自主掌控，超越人类玩家水平。
- **2016 年 · AlphaGo 击败世界围棋冠军**：
  - AlphaGo 结合蒙特卡洛树搜索（MCTS）与策略网络/价值网络，以 4:1 战胜李世石。
  - 后续的 **AlphaGo Zero** 与 **AlphaZero** 实现无人类先验、自对弈从零进化。

---

## 3. 生成模型的新视角：GAN 与 VAE

- **2013 年 · 变分自编码器 (VAE)**：
  - 结合概率图模型与自编码器，给出严谨的隐空间采样与推断。
- **2014 年 · 生成对抗网络 (GAN)**：
  - Ian Goodfellow 提出博弈论思想的生成器 (Generator) 与判别器 (Discriminator) 互相对抗架构，图像生成逼真度实现飞跃（StyleGAN, BigGAN 等）。

---

## 4. 统一架构的诞生：Transformer 纪元开启

- **2017 年 · 《Attention Is All You Need》**：
  - Google 研究团队提出 **Transformer** 架构，完全抛弃了此前 NLP 依赖的循环神经网络（RNN/LSTM）与卷积结构。
  - 引入**自注意力机制（Self-Attention）**，具备天然的高并发吞吐能力和捕获超长上下文依赖的能力，成为后续所有大语言模型、视觉模型乃至多模态架构的共同基石。
