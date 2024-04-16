### 第二堂课学习笔记

### 0. 作业
- 使用 `InternLM2-Chat-1.8B` 模型生成 300 字的小故事
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/2be82762-64b9-4e30-bb2c-95b454d49f52)
- 熟悉 `huggingface` 下载功能，使用 `huggingface_hub` python 包，下载 `InternLM2-Chat-7B` 的 `config.json` 文件到本地（需截图下载过程）
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/3e1faa79-048a-4252-a9f5-f9044b61ac96)


- 完成 的 `图文创作` （需截图）
  后台运行图
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/5f3cc9c2-0f87-4c60-ac59-7b4d974f27e0)
前端展示
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/f97053a0-b689-4f5c-b0ed-a4a15f02fba5)

`浦语·灵笔2- `视觉问答` 部署
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/1225655e-96e1-40d7-87c6-3e8141325db5)
`浦语·灵笔2- `视觉问答` 部署结果：
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/ebbb2be6-a9d0-46fe-8530-8e800adc9452)
- 完成 `Lagent` 工具调用 `数据分析` Demo 部署（需截图）
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/bd47aa8d-83c5-410f-aba8-ecbf1f0c6c80)


### 1. 部署和使用 `InternLM2-Chat-1.8B` 模型进行智能对话
- **配置环境**：使用 `Intern Studio` 创建和配置开发机，安装必要的软件包。
- **下载模型**：创建文件夹，下载 `InternLM2-Chat-1.8B` 模型。
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/a6c48e0b-9027-424a-bdb7-cb7eb48c9ffb)

- **运行 Demo**：运行 `cli_demo.py` 文件以启动模型。

![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/2be82762-64b9-4e30-bb2c-95b454d49f52)


### 2. 部署 `八戒-Chat-1.8B` 模型
- **模型介绍**：`八戒-Chat-1.8B` 是基于 `InternLM2-Chat-1.8B` 模型的优秀成果，专注于猪八戒角色。
- **环境配置和运行**：配置环境后，下载和运行 `Chat-八戒` Demo。
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/6c35b1fc-92d2-4f94-9d8e-b471e1eb1807)

ssh连接：
ssh -CNg -L 6006:127.0.0.1:6006 root@ssh.intern-ai.org.cn -p 38970
### 3. 使用 `Lagent` 运行 `InternLM2-Chat-7B` 模型
- **Lagent 介绍**：轻量级智能体框架，可将大型语言模型转化为多种类型的智能体。
- **环境配置和模型运行**：调整资源配置后，下载 Lagent 并运行 `InternLM2-Chat-7B` 模型。
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/bd47aa8d-83c5-410f-aba8-ecbf1f0c6c80)

### 4. 部署 `浦语·灵笔2` 模型
- **模型介绍**：图文多模态大模型，具有出色的图文写作和图像理解能力。
- **环境配置和运行**：选择更高的资源配置，下载并运行 `InternLM-XComposer`。

### 5. 附录和作业
- **附录**：提供了额外的技术参考，包括 `pip` 和 `conda` 的换源方法，模型下载方法，软链接清除方法，以及终端的清除方法。
- **作业**：指向一个单独的文档，包含课程作业。

这份文档非常详细，涵盖了从基础环境配置到运行多种大型模型的完整步骤。通过实践这些步骤，可以深入了解大模型的部署和应用。
