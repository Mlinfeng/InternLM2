# 第六节 作业


## 基础作业

1. 完成 Lagent Web Demo 使用，并在作业中上传截图。
 -后端配置
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/ae3149a2-806a-48aa-a1e3-335b8a9cf29d)
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/56638716-af2c-442a-9cb2-2af6d1539469)
- Web Demo运行
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/d831ca48-f2df-4072-994f-6e0e6fc2090e)



2. 完成 AgentLego 直接使用部分，并在作业中上传截图。
- 配置中
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/46623071-d919-483f-a55d-fcd6df645eac)
- 标记图
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/6afe8b69-cc32-446d-b3c1-b6cb613a90c6)



## 进阶作业

1. 完成 AgentLego WebUI 使用，并在作业中上传截图。
  - 配置中
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/b35ca5ad-a175-4852-b95b-265bf5c91052)
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/b6d1fe59-ef73-46f7-bb85-cc5195712e4a)
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/6b55c6ea-dc59-4f5e-89dc-d55d62b012e2)


- ssh -CNg -L 7860:127.0.0.1:7860 -L 23333:127.0.0.1:23333 root@ssh.intern-ai.org.cn -p 43304
2. 使用 Lagent 或 AgentLego 实现自定义工具并完成调用，并在作业中上传截图。文档可见：
## 2.1  [用 Lagent 自定义工具](lagent.md#2-用-lagent-自定义工具)
   - 使用 LMDeploy 部署
   - ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/c11d910d-92e8-455c-b550-243f17425e99)
   -  LMDeploy api_server启动成功
   -  ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/709f1a1a-e03e-4477-b14d-b279ae28038b)
   -  启动 Lagent Web Demo-成功
   -  ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/be387ad1-d29b-4ac6-b5b9-955835bc0684)
   -  本地映射：
   -  ssh -CNg -L 7860:127.0.0.1:7860 -L 23333:127.0.0.1:23333 root@ssh.intern-ai.org.cn -p 47708
   -  Lagent Web Demo 访问
   -  ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/d44c5b3a-f60a-41af-8666-c7a77bd24a28)

## 2.2 用 Lagent 自定义工具
   - [用 AgentLego 自定义工具]
   - 申请和风天气API Key
   - ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/818b3e63-53af-422f-8c7a-d6f879e4cb0f)
   - 如2.1一样启动api，和demo之后，进行本地映射
   - ssh -CNg -L 7860:127.0.0.1:7860 -L 23333:127.0.0.1:23333 root@ssh.intern-ai.org.cn -p 47708
   - Lagent Web Demo 访问-成功
   - ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/287de950-2299-42f5-b9cb-2f999d5da082)





## 大作业选题

### 算法方向

1. 在 Lagent 或 AgentLego 中实现 RAG 工具，实现智能体与知识库的交互。
2. 基于 Lagent 或 AgentLego 实现工具的多轮调用，完成复杂任务。如：智能体调用翻译工具，再调用搜索工具，最后调用生成工具，完成一个完整的任务。
3. ...

### 应用方向

1. 基于 Lagent 或 AgentLego 实现一个客服智能体，帮助用户解决问题。
2. 基于 Lagent 或 AgentLego 实现一个智能体，实现艺术创作，如生成图片、视频、音乐等。

