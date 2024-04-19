# 第3课作业

## 基础作业 - 完成下面两个作业

### 1. 在[茴香豆 Web 版](https://openxlab.org.cn/apps/detail/tpoisonooo/huixiangdou-web)中创建自己领域的知识问答助手

运行 ***conda*** 命令，激活 `InternLM2_Huixiangdou`  ***python*** 虚拟环境:

```bash
conda activate InternLM2_Huixiangdou

```

环境激活后，命令行左边会显示当前（也就是 `InternLM2_Huixiangdou`）的环境名称，如下图所示:

- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/a4ad2d45-7c54-4db4-bdb7-8be283891285)

- 后续教程所有操作都需要在该环境下进行，重启开发机或打开新命令行后要重新激活环境!!!。
- 
- 根据教程文档搭建 `茴香豆技术助手`，针对问题"茴香豆怎么部署到微信群？"进行提问
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/6f9756ac-91c3-489e-b7ab-75a5786e4e0e)

- ssh -CNg -L 7860:127.0.0.1:7860 root@ssh.intern-ai.org.cn -p 44377
- Gradio网页端搭建
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/e0f402e7-1bf5-42c1-aed4-2ad87ce6d5d8)
- 邪门
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/09791a87-8ffc-4b58-9065-e1bdbf24694d)




## 笔记
 - 茴香豆是一款基于检索增强生成（RAG）技术的零代码领域知识助手，旨在提供快速准确的知识问答服务。它由书生葡语团队开发，适用于智能客服及群聊场景，如微信群、飞书群等，以及用于个人知识领域的助手创建。
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/0b252666-42e0-4477-ad04-2e253e97fe8d)

- RAG技术，全称为retrible augmented generation，结合检索和生成过程，以提高语言模型在特定任务上的性能。它包括三个基本组成部分：索引、检索、和生成。这种技术解决了传统大模型在知识密集任务处理中的挑战，如生成幻觉、过时知识缺失、以及缺乏透明的推理过程。
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/bcd12596-945c-4f1e-8c93-e65f1563e0fc)

 - 茴香豆的工作流涵盖预处理、拒答和应答三个阶段。预处理部分筛选和转换用户输入，拒答工作流通过对问询与数据库中示例问题的比较来给出问题的相关性得分，应答流程则是由大模型根据问询和检索到的知识内容生成答案。此外，茴香豆通过多来源检索、混合模型和安全评估等方式保证回答的准确性。
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/5b4cef11-0093-47b3-b375-f72340f50ce3)

 - 茴香豆支持多种文件格式，包括Markdown、PDF、Word、TXT、Powerpoint等，并且可以与多种即时通讯软件或交流社群兼容。它也支持本地或远端大模型的调用，既提高了灵活性，又保证了信息的安全性。更重要的是，它遵循BSD three clause的开源协议，可免费商用。
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/da71c656-10c8-4dfd-b053-9add7ef1dd91)
 - 茴香豆作为一个基于RAG技术的领域知识助手，具有开源免费、部署成本低、安全性高和扩展性强等优点。它适用于多种应用场景，特别是在知识更新迅速或用户需求复杂的场合，能够有效提升知识问答的效率和准确性。
![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/ad9c0bdc-ad88-4078-9458-86f28fc84c7f)
