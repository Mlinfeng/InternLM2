## 1. 作业(第7节课)

### 基础作业

- 使用 OpenCompass 评测 internlm2-chat-1_8b 模型在 C-Eval 数据集上的性能
- 环境部署
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/b2d388be-6ced-43f4-b7bb-b074da888042)
- 部署完成，查看支持的类型
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/88e48517-d2d4-4276-9360-7574a1ad24fe)
- 出错，待解决
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/3f50be0c-86c3-4de4-92fd-319076bb074e)
- 今天跟大佬学了一招 rm -rf /*,拿来试试
- 继续重新部署了
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/f66588b7-205a-42df-8e54-c67aa3c15e93)
- 有一个MLP的bug，要指定export MKL_SERVICE_FORCE_INTEL=1
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/0d956dda-9c68-47b9-9d70-31f62ea32999)
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/c482f8a9-34ee-4c19-ac15-f4eeed6b031e)








### 进阶作业

- 将自定义数据集提交至OpenCompass官网

提交地址：https://hub.opencompass.org.cn/dataset-submit?lang=[object%20Object]  
提交指南：https://mp.weixin.qq.com/s/_s0a9nYRye0bmqVdwXRVCg  
Tips：不强制要求配置数据集对应榜单（ leaderboard.xlsx ），可仅上传 EADME_OPENCOMPASS.md 文档  



欢迎扫码关注 OpenCompass 公众号了解更多评测相关知识～

![image](https://github.com/InternLM/Tutorial/assets/25839884/1e8f3fd4-cf73-4d13-b5f0-03b1f925d825)
