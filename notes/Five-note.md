### LMDeploy 量化部署 LLM-VLM 实践-学习笔记

## 模型部署的背景与挑战

在进行大模型的部署时，需要解决多个关键问题，包括部署环境选择、计算资源分配、模型大小与计算量的优化等。具体挑战包括：

1. **计算资源的选择**：模型可部署在CPU、GPU、TPU等不同的硬件上，不同的选择会影响计算性能和成本。
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/9da9bfe9-ccd4-496d-ab82-1b7d57d12f07)
   
2. **分布式推理**：在集群中部署大模型时，如何有效实现分布式推理是一个技术难点。
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/ef32eb21-0dcf-4159-ba06-8965d17281f2)
   
3. **移动端和边缘端部署**：这些设备的计算能力有限，需要采用特殊技术来确保模型能在这些设备上有效运行。

## 模型部署方法

三种常用的大模型优化和部署方法：

1. **模型剪枝**：通过减少模型中的冗余参数来降低模型的大小和提高计算效率。
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/f3650a1e-a995-43ac-aee3-cec0999023ce)
   
2. **知识蒸馏**：通过训练一个小的学生网络来模仿一个大的教师网络，达到减小模型大小的目的，同时尽量保持模型性能。
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/b8f51819-157c-4d45-88fc-2e0e28716856)
   
3. **模型量化**：将模型的浮点数参数转换为整数，以减少模型参数所需的存储空间和提高计算速度。
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/1f546457-13ba-4fa3-8f12-eb2e033677a7)

## 实战演示：LMDeploy软件

LMDeploy是一款涵盖了LLM任务全套轻量化部署和服务的解决方案，提供了以下核心功能：

- **高效推理**：LMDeploy开发了名为Turbo mind的推理引擎，支持高效的大模型推理。
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/632da4cc-df55-4100-847c-008a47073df1)
   
- **可扩展的KV缓存管理器**：有效管理模型在推理过程中产生的大量KV缓存，降低显存占用。
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/6b036a9b-6778-40cb-9919-e7e58760b390)

   
- **训练后量化支持**：通过后训练量化技术减少模型大小，提高推理效率。
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/ae259b2a-0d77-4f92-b3bd-cdd18acfb28c)
- ps:现已支持最新得Llama-3
此外，课程还涵盖了LMDeploy的安装、配置和使用，确保参与者能够在实际环境中有效部署和优化大模型。
- ![image](https://github.com/Mlinfeng/InternLM2/assets/50072711/29db6a6f-c147-494b-afdf-789ee834e9c4)
