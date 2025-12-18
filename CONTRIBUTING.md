# 贡献指南 Contributing Guide

感谢您对本项目感兴趣！我们欢迎任何形式的贡献。

Thank you for your interest in this project! We welcome contributions of all kinds.

## 📝 如何贡献论文 How to Contribute Papers

### 方式一：通过 Pull Request (推荐)

1. **Fork 本仓库**
   - 点击页面右上角的 "Fork" 按钮

2. **克隆到本地**
   ```bash
   git clone https://github.com/YOUR_USERNAME/awesome-learn_from_videos-world_model.git
   cd awesome-learn_from_videos-world_model
   ```

3. **创建新分支**
   ```bash
   git checkout -b add-paper-name
   ```

4. **添加论文**
   - 打开 `README.md`
   - 找到对应的分类和年份
   - 按照格式添加论文信息（见下方格式说明）
   - 按时间倒序排列（最新的在最上面）

5. **提交更改**
   ```bash
   git add README.md
   git commit -m "Add: 论文标题"
   ```

6. **推送到 GitHub**
   ```bash
   git push origin add-paper-name
   ```

7. **创建 Pull Request**
   - 访问您 fork 的仓库页面
   - 点击 "New Pull Request"
   - 填写 PR 描述，说明添加的论文内容

### 方式二：通过 Issue

如果您不熟悉 Git 操作，可以直接[创建 Issue](../../issues/new)，提供以下信息：

- 论文标题
- 作者
- 发表时间
- 论文链接（arXiv、会议网站等）
- 代码链接（如果有）
- 简短描述（1-2句话）
- 所属分类（视频学习/世界模型）

我们会尽快帮您添加！

## ✍️ 论文格式 Paper Format

```markdown
- **论文标题**, 会议/期刊 年份. [[paper]](论文链接) [[code]](代码链接) [[website]](项目页面)
```

### 示例 Example

```markdown
- **Diffusion Policy: Visuomotor Policy Learning via Action Diffusion**, RSS 2023. [[paper]](https://arxiv.org/abs/2303.04137) [[code]](https://github.com/real-stanford/diffusion_policy) [[website]](https://diffusion-policy.cs.columbia.edu/)

- **RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control**, CoRL 2023. [[paper]](https://arxiv.org/abs/2307.15818) [[website]](https://robotics-transformer2.github.io/)

- **Genie: Generative Interactive Environments**, arXiv 2024. [[paper]](https://arxiv.org/abs/2402.15391) [[website]](https://sites.google.com/view/genie-2024/)
```

### 必需字段 Required

- ✅ 论文标题
- ✅ 发表会议/期刊或arXiv
- ✅ 年份
- ✅ `[[paper]]` 链接

### 可选字段 Optional

- `[[code]]` - 代码仓库（GitHub等）
- `[[website]]` - 项目主页
- `[[demo]]` - 演示视频（如果有单独的demo链接）

## 🏷️ 分类说明 Category Guidelines

### 🎬 从视频学习 Learn from Videos

适用于以下研究：
- 从人类演示视频中学习机器人策略
- 视频预训练模型用于机器人控制
- 视觉模仿学习
- 从大规模互联网视频学习
- 视频表示学习用于具身任务

### 🌍 世界模型 World Model

适用于以下研究：
- 环境动态建模
- 视觉预测模型
- 基于模型的强化学习
- 物理模拟学习
- 用于规划和决策的世界模型

### 交叉分类

如果论文同时涉及两个方向，请选择**最主要**的方向进行分类，或在描述中说明。

## 🤝 其他贡献方式 Other Ways to Contribute

### 改进文档

- 优化 README 结构
- 修正拼写/语法错误
- 改进描述的准确性
- 添加更多资源链接

### 补充内容

- 添加论文的中文解读
- 补充重要会议/期刊信息
- 推荐相关数据集
- 分享学习资源和教程

### 参与讨论

- 在 Issues 中讨论论文
- 分享学习心得
- 提出改进建议
- 帮助他人解答问题

## ❓ 需要帮助？ Need Help?

如有任何问题，欢迎：
- 📮 [创建 Issue](../../issues/new)
- 💬 在现有 Issue 中评论
- 📧 联系维护者

---

再次感谢您的贡献！🎉

Thank you again for your contribution! 🎉

