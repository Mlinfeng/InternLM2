# 第五节课作业

## 基础作业
完成以下任务，并将实现过程记录截图：
- 配置 LMDeploy 运行环境
- -环境部署中：
- -![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/6b6ff795-74ae-441a-a734-1aa1f0d7ad0c)
- 环境部署成功
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/b89cd15b-d746-4c84-8f02-8760fd740e4a)


- 以命令行方式与 InternLM2-Chat-1.8B 模型对话
-![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/216a71ac-5b7b-4a93-aefa-e1b087ac138d)
  -ps:这一步好像有个坑，两个module需要安装sentencepiece，transformer
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/7f1e4c57-6c04-40db-9eba-62689745b7c6)

## 进阶作业

完成以下任务，并将实现过程记录截图：
- 设置KV Cache最大占用比例为0.4，开启W4A16量化，以命令行方式与模型对话。（优秀学员必做）
- 设置最大KV Cache缓存大小为0.4
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/e7043456-31b0-4569-92f9-30b162969990)
- W4A16量化开启中：
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/87242fc3-293b-4296-a3ad-b1ae4d1aeb04)

- 设置KV Cache最大占用比例为0.4，并开启W4A16量化
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/eee4ad68-c25f-4388-a4ed-143b2d354c1a)
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/d8dcd1cb-adf9-46d4-92b4-b6fdf9f277b5)



- 以API Server方式启动 lmdeploy，开启 W4A16量化，调整KV Cache的占用比例为0.4，分别使用命令行客户端与Gradio网页客户端与模型对话。（优秀学员必做）
- 调整KV Cache的占用比例为0.4
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/c3e543f5-02d8-4dd6-a8b4-b7efa353c260)
- 命令行运行
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/6cc6db6f-e4e7-477f-af8e-6c9269e15f36)


- 命令行客户端与模型对话
- ssh -CNg -L 23333:127.0.0.1:23333 root@ssh.intern-ai.org.cn -p 43304
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/e0d51c03-4346-4b8b-90d6-dd9e757b43c2)

- Gradio网页客户端与模型对话
- ssh -CNg -L 6006:127.0.0.1:6006 root@ssh.intern-ai.org.cn -p 43304
- 降低了到Gradio==3.50.2 gradio_client==0.6.1 才算是启动成功-(谢谢助教六一的帮助)
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/37241e34-5fe7-4021-8a16-e9a486434311)
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/3eb2a167-eb92-4a4a-af11-1939cbf17ed8)



- 使用W4A16量化，调整KV Cache的占用比例为0.4，使用Python代码集成的方式运行internlm2-chat-1.8b模型。
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/7154b058-9738-485b-bd3c-6865043e5f59)

- 使用 LMDeploy 运行视觉多模态大模型 llava gradio demo。（优秀学员必做）
- 命令行运行
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/07dbc5ee-eef3-4383-8508-d3ad81c2d4ff)
- gradio网页运行
- ssh -CNg -L 7860:127.0.0.1:7860 root@ssh.intern-ai.org.cn -p 43304
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/21dbc9fa-aa83-469a-97f5-6285d9a831cf)


- 将 LMDeploy Web Demo 部署到 [OpenXLab](../tools/openxlab-deploy/) 。（优秀学员必做）
