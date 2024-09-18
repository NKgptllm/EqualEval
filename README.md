![image](https://github.com/user-attachments/assets/98baff8b-16a3-488f-994f-35e84f5c03d6)# EqualEval

EqualEval公能中文大模型排行榜

公众号：EqualEval公能中文大模型排行榜
<!-- 公众号文章：<a href=''>EqualEval</a> -->

官网地址：
<a href='http://8.141.115.251/#/home' target="__blank">http://8.141.115.251/#/home （域名equaleval.com备案中）</a> 


 EqualEval公能中文大模型排行榜是天津市软件体验与人机交互重点实验室（依托南开大学的市级科研平台）推出的一个全面、科学、实用、公平的评测基准，帮助研究人员全方面的评估已有大模型。我们的目标是构建科学全面的评测维度、海量多样化的测评数据集、公平公正测评方案和实施方法。我们更侧重于对大模型实用性的评估，希望榜单可以真正为用户提供行业参考意见。



### EqualEval多维度测评设计
<p align="center">
<img src="pic\di2.jpg"  width="70%" height="60%"></img>
</p>

### EqualEval核心思想设计
<p align="center">
<img src="pic\core.jpg"  width="80%" height="60%"></img>
</p>

### EqualEval测评介绍

1. EqualEval第一期评测涵盖基础能力、智能体能力两个一级维度，90+子维度，全方面评估大模型的中文能力。
2. 第一期评测使用了2425条数据进行评测，其中基础能力数据集1150，智能体能力数据集1275。题目类型包括选择题和问答题，数据集有30%以上为多轮评测集，评测模型的多轮能力。   
3. 针对所有二级维度和部分三级、四级维度制定评分规则，保证评测的可解释性与稳定性。评分时，针对客观题，采用正则匹配或字符串匹配的方式评分，针对主观题，根据大类评分规则与具体题目的参考答案和得分点设计prompt，使用GPT-4o作为裁判模型进行评分。
4. 我们会定期更新评测数据集并推出新的评测结果，随着数据集难度的调整以及评测维度的增加，评测分数会发生相应变化。
    

【2023-9-18】，发布EqualEval公能中文大模型排行榜基础能力及智能体能力榜单。


### EqualEval基础能力排行榜（2024年9月）

| 排名 | 模型名称 | 机构 | 是否开源 | 总分 | 语言理解与生成 | 知识能力 | 数学能力 | 推理能力 | 代码能力 | 对话体验 | 安全性 | 回答一致性 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Doubao-pro-32k | 字节跳动 | 否 | 83.84 | 83.13 | 81.32 | 84.64 | 83.15 | 82.46 | 64.30 | 91.79 | 99.20 |
| 2 | GPT-4o | OpenAI | 否 | 83.53 | 80.23 | 79.06 | 89.37 | 79.44 | 85.99 | 72.90 | 92.48 | 88.80 |
| 3 | qwen-max-0428 | 阿里云 | 否 | 81.37 | 78.35 | 80.00 | 76.23 | 76.52 | 82.48 | 65.05 | 94.70 | 97.65 |
| 4 | ERNIE-4.0-8K | 百度 | 否 | 81.34 | 80.00 | 75.26 | 80.58 | 74.04 | 81.02 | 71.40 | 92.82 | 95.60 |
| 5 | Doubao-pro-4k | 字节跳动 | 否 | 80.27 | 82.39 | 75.65 | 75.85 | 73.93 | 78.54 | 68.79 | 89.06 | 98.00 |
| 6 | BlueLM | vivo | 否 | 79.82 | 73.18 | 77.19 | 85.31 | 74.27 | 80.15 | 66.17 | 92.31 | 90.00 |
| 7 | GPT4-turbo | OpenAI | 否 | 79.53 | 77.78 | 72.89 | 87.83 | 71.01 | 80.58 | 64.72 | 92.99 | 88.40 |
| 8 | step-1-8k | 阶跃星辰 | 否 | 78.67 | 73.24 | 75.10 | 80.19 | 67.64 | 83.94 | 63.93 | 91.11 | 94.20 |
| 9 | moonshot-v1-8k | Moonshot AI | 否 | 77.76 | 75.85 | 73.61 | 74.98 | 72.81 | 80.44 | 65.23 | 93.33 | 85.80 |
| 10 | ERNIE-4.0-Turbo-8K | 百度 | 否 | 77.56 | 77.73 | 74.66 | 81.06 | 63.48 | 71.24 | 66.17 | 90.94 | 95.20 |
| 11 | 360gpt-pro | 360 | 否 | 77.55 | 75.51 | 75.76 | 77.87 | 75.28 | 70.66 | 60.19 | 86.32 | 98.80 |
| 12 | GLM-4-9B-Chat | 智谱AI | 是 | 76.50 | 75.40 | 69.31 | 68.50 | 78.65 | 71.24 | 68.97 | 87.35 | 92.60 |
| 13 | hunyuan-pro | 腾讯 | 否 | 75.50 | 73.81 | 67.66 | 78.94 | 78.20 | 71.82 | 79.44 | 90.94 | 63.20 |
| 14 | Spark3.5 Max | 科大讯飞 | 否 | 75.05 | 72.16 | 70.80 | 83.09 | 73.15 | 75.18 | 59.63 | 90.77 | 75.60 |
| 15 | abab6.5 | MiniMax | 否 | 74.63 | 75.85 | 67.66 | 80.10 | 74.27 | 73.43 | 60.93 | 92.82 | 72.00 |
| 16 | Qwen2-7B-Instruct | 阿里云 | 是 | 74.42 | 70.40 | 67.55 | 77.78 | 68.99 | 69.49 | 60.37 | 88.55 | 92.20 |
| 17 | Spark4.0 Ultra | 科大讯飞 | 否 | 73.62 | 68.13 | 68.87 | 85.12 | 72.81 | 66.28 | 65.23 | 86.32 | 76.20 |
| 18 | Yi-34B | 零一万物 | 是 | 71.86 | 68.47 | 67.16 | 57.58 | 60.22 | 60.73 | 80.19 | 86.32 | 94.20 |
| 19 | Yi-1.5-9B-Chat | 零一万物 | 是 | 71.31 | 67.61 | 66.94 | 74.20 | 59.66 | 69.93 | 54.21 | 83.93 | 94.00 |
| 20 | Baichuan4 | 百川智能 | 否 | 70.92 | 77.33 | 71.68 | 78.84 | 73.71 | 80.29 | 54.21 | 72.31 | 59.00 |
| 21 | GLM-4-0520 | 智谱AI | 否 | 70.19 | 74.72 | 72.62 | 61.84 | 81.12 | 68.03 | 62.24 | 89.74 | 51.20 |
| 22 | SenseChat-5 | 商汤日日新 | 否 | 69.09 | 69.83 | 66.94 | 64.35 | 63.82 | 51.97 | 55.70 | 81.88 | 98.20 |
| 23 | Qwen-14B-Chat | 阿里云 | 是 | 67.68 | 69.26 | 60.99 | 58.36 | 57.42 | 54.89 | 59.44 | 87.86 | 93.20 |
| 24 | InternLM2-Chat-7B | 上海人工智能实验室 | 是 | 66.69 | 62.73 | 62.92 | 57.58 | 52.92 | 58.39 | 56.82 | 84.96 | 97.20 |
| 25 | BlueLM-3B | vivo | 否 | 65.36 | 63.81 | 56.75 | 55.27 | 50.79 | 38.10 | 79.25 | 86.15 | 92.80 |
| 26 | Llama-3-8B-Instruct | Meta | 是 | 64.80 | 64.72 | 51.29 | 56.81 | 49.33 | 65.55 | 72.71 | 74.19 | 83.80 |
| 27 | mengzi_std | 澜舟科技 | 否 | 64.58 | 54.43 | 65.51 | 62.71 | 65.62 | 57.52 | 55.33 | 83.76 | 71.80 |
| 28 | BaichuanChat2-13B | 百川智能 | 是 | 63.61 | 66.42 | 60.33 | 43.57 | 48.20 | 47.74 | 68.41 | 81.37 | 92.80 |
| 29 | Yi-1.5-6B-Chat | 零一万物 | 是 | 63.10 | 63.81 | 58.02 | 62.71 | 53.82 | 53.72 | 53.46 | 77.44 | 81.80 |
| 30 | DeepSeek-LLM-7B-chat | DeepSeek-AI | 是 | 62.83 | 60.34 | 59.23 | 31.98 | 47.30 | 50.95 | 74.77 | 86.84 | 91.20 |
| 31 | Phi-3.5-mini-instruct | 微软 | 是 | 61.22 | 56.19 | 39.83 | 60.00 | 47.42 | 66.13 | 54.58 | 72.82 | 92.80 |
| 32 | Taichu-2.0 | 紫东太初 | 否 | 60.05 | 60.63 | 62.37 | 66.57 | 47.42 | 64.53 | 34.58 | 54.70 | 89.60 |
| 33 | Mistral-7B | Mistral AI | 是 | 59.00 | 50.85 | 40.17 | 37.39 | 71.24 | 46.42 | 72.90 | 76.24 | 76.80 |
| 34 | ChatGLM3-6B | 智谱AI | 是 | 56.66 | 57.16 | 51.24 | 41.93 | 40.90 | 39.56 | 64.86 | 77.44 | 80.20 |
| 35 | XVERSE-13B-Chat | 深圳元象科技 | 是 | 55.97 | 63.75 | 59.50 | 47.92 | 47.64 | 51.39 | 54.21 | 86.15 | 37.20 |
| 36 | Gemma-7B | Google | 是 | 55.28 | 50.40 | 35.76 | 40.00 | 40.45 | 57.81 | 55.14 | 70.26 | 92.40 |
| 37 | BaichuanChat2_7B | 百川智能 | 是 | 54.79 | 61.36 | 57.52 | 41.16 | 13.71 | 42.04 | 66.36 | 79.15 | 77.00 |
| 38 | XVERSE-7B-Chat | 深圳元象科技 | 是 | 54.51 | 62.67 | 53.61 | 32.75 | 44.27 | 24.53 | 51.40 | 82.22 | 84.60 |
| 39 | AquilaChat-7B | 北京智源人工智能研究院 | 是 | 50.43 | 48.58 | 42.59 | 20.87 | 32.25 | 28.03 | 72.90 | 71.62 | 86.60 |
| 40 | TuringMM-34B-Chat | 北京光年无限科技有限公司 | 是 | 47.84 | 36.70 | 41.54 | 33.24 | 38.88 | 30.51 | 65.42 | 76.41 | 60.00 |
| 41 | Qwen-1.8B-Chat | 阿里云 | 是 | 47.60 | 47.39 | 36.80 | 21.16 | 29.21 | 26.57 | 64.67 | 68.38 | 86.60 |
| 42 | InternLM2-Chat-1.8B | 上海人工智能实验室 | 是 | 46.72 | 47.22 | 41.16 | 23.77 | 38.20 | 32.12 | 58.13 | 68.55 | 64.60 |
| 43 | Gemma-2B | Google | 是 | 43.16 | 40.00 | 20.00 | 23.67 | 21.91 | 35.91 | 65.10 | 51.11 | 87.60 |
| 44 | Index-1.9B | bilibili | 是 | 40.22 | 35.97 | 31.85 | 18.45 | 35.06 | 21.02 | 61.31 | 58.12 | 60.00 |
| 45 | XuanYuan-13B-Chat | 度小满 | 是 | 39.67 | 23.41 | 33.50 | 27.73 | 26.18 | 14.74 | 53.83 | 61.71 | 60.00 |
| 46 | XuanYuan-6B-Chat | 度小满 | 是 | 36.90 | 23.41 | 35.43 | 19.61 | 28.99 | 13.14 | 58.69 | 55.90 | 60.00 |
| 47 | Skywork-13B-Base | 昆仑万维 | 是 | 36.66 | 25.11 | 35.04 | 22.32 | 31.35 | 12.41 | 64.67 | 42.39 | 60.00 |
| 48 | Vicuna-13B-v1.5 | 斯坦福 | 是 | 33.84 | 27.33 | 21.76 | 14.01 | 25.73 | 20.88 | 51.59 | 42.91 | 60.00 |
| 49 | Vicuna-7B-v1.5 | 斯坦福 | 是 | 24.67 | 18.28 | 11.74 | 6.38 | 23.48 | 11.68 | 40.37 | 25.47 | 60.00 |
| 50 | BayLing-7B-v1.0 | 中国科学院计算技术研究所自然语言处理研究组 | 是 | 24.71 | 10.57 | 8.82 | 1.64 | 18.88 | 14.60 | 45.61 | 23.42 | 60.00 |




### EqualEval智能体能力排行榜（2024年9月）

| 排名 | 模型名称 | 机构 | 调用方式 | 总分 | 感知理解 | 记忆能力 | 任务规划 | 反思能力 | RAG能力 | 工具使用 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 排名 | 模型名称              | 机构               | 是否开源 | 总分  | 感知理解 | 记忆能力 | 任务规划 | 反思能力 | RAG能力 | 工具使用 |
| ---- | --------------------- | ------------------ | -------- | ----- | -------- | -------- | -------- | -------- | ------- | -------- |
| 1    | GPT-4o                | OpenAI             | 否       | 78.98 | 89.85    | 70.05    | 98.00    | 78.57    | 88.82   | 48.58    |
| 2    | qwen-max-0428         | 阿里云             | 否       | 78.24 | 92.13    | 62.13    | 97.60    | 81.90    | 86.02   | 49.68    |
| 3    | ERNIE-4.0-8K          | 百度               | 否       | 76.32 | 93.22    | 59.52    | 95.60    | 77.38    | 82.26   | 49.93    |
| 4    | Doubao-pro-4k         | 字节跳动           | 否       | 75.85 | 87.17    | 66.18    | 94.60    | 77.14    | 82.26   | 47.72    |
| 5    | step-1-8k             | 阶跃星辰           | 否       | 75.67 | 92.00    | 68.99    | 93.50    | 81.43    | 80.97   | 37.16    |
| 6    | BlueLM                | vivo               | 否       | 75.29 | 91.90    | 63.09    | 98.30    | 65.24    | 83.87   | 49.32    |
| 7    | GPT4-turbo            | OpenAI             | 否       | 75.23 | 88.53    | 63.19    | 94.50    | 70.48    | 86.13   | 48.58    |
| 8    | SenseChat-5           | 商汤日日新         | 否       | 74.61 | 89.19    | 62.42    | 97.30    | 71.19    | 83.87   | 43.68    |
| 9    | Doubao-pro-32k        | 字节跳动           | 否       | 74.47 | 86.88    | 66.57    | 94.82    | 70.48    | 79.78   | 48.30    |
| 10   | Qwen2-7B-Instruct     | 阿里云             | 是       | 73.93 | 89.85    | 68.21    | 95.10    | 64.05    | 80.54   | 45.85    |
| 11   | ERNIE-4.0-Turbo-8K    | 百度               | 否       | 73.67 | 90.15    | 50.82    | 97.10    | 73.33    | 80.75   | 49.84    |
| 12   | GLM-4-0520            | 智谱AI             | 否       | 73.65 | 81.72    | 60.68    | 94.40    | 74.29    | 83.44   | 47.40    |
| 13   | Spark4.0 Ultra        | 科大讯飞           | 否       | 73.18 | 89.19    | 56.14    | 90.90    | 79.29    | 77.53   | 46.03    |
| 14   | GLM-4-9B-Chat         | 智谱AI             | 是       | 72.91 | 88.79    | 55.75    | 95.60    | 63.33    | 84.95   | 49.02    |
| 15   | 360gpt-pro            | 360                | 否       | 72.81 | 92.60    | 55.36    | 96.80    | 60.24    | 82.47   | 49.41    |
| 16   | hunyuan-pro           | 腾讯               | 否       | 72.46 | 84.23    | 58.55    | 90.10    | 69.52    | 81.72   | 50.62    |
| 17   | abab6.5               | MiniMax            | 否       | 72.21 | 92.50    | 57.68    | 95.70    | 70.71    | 83.66   | 33.04    |
| 18   | Yi-1.5-9B-Chat        | 零一万物           | 是       | 69.69 | 88.73    | 46.47    | 96.10    | 65.24    | 78.39   | 43.20    |
| 19   | Spark3.5 Max          | 科大讯飞           | 否       | 68.84 | 87.70    | 56.04    | 89.40    | 76.90    | 71.83   | 31.18    |
| 20   | Llama-3-8B-Instruct   | Meta               | 是       | 67.58 | 84.13    | 53.62    | 92.30    | 56.19    | 81.40   | 37.81    |
| 21   | XVERSE-13B-Chat       | 深圳元象科技           | 是       | 64.30 | 86.81    | 47.44    | 87.30    | 59.29    | 73.01   | 31.97    |  
| 22   | Qwen-14B-Chat         | 阿里云                 | 是       | 64.09 | 88.17    | 52.75    | 86.40    | 46.43    | 73.55   | 37.25    |  
| 23   | Yi-1.5-6B-Chat        | 零一万物               | 是       | 64.00 | 87.07    | 39.81    | 94.20    | 53.81    | 71.94   | 37.17    |  
| 24   | BlueLM-3B             | vivo                   | 否       | 63.79 | 85.95    | 42.90    | 87.70    | 55.24    | 68.92   | 42.05    |  
| 25   | Baichuan4             | 百川智能               | 否       | 62.73 | 76.43    | 44.35    | 94.40    | 41.19    | 74.41   | 45.58    |  
| 26   | DeepSeek-LLM-7B-chat  | DeepSeek-AI            | 是       | 59.85 | 82.74    | 39.52    | 84.10    | 53.10    | 73.23   | 26.42    |  
| 27   | ChatGLM3-6B           | 智谱AI                 | 是       | 59.82 | 84.40    | 45.70    | 82.00    | 49.29    | 68.06   | 29.50    |  
| 28   | BaichuanChat2-7B      | 百川智能               | 是       | 59.33 | 83.74    | 47.15    | 83.90    | 55.95    | 69.14   | 16.08    |  
| 29   | moonshot-v1-8k        | Moonshot AI            | 否       | 58.18 | 72.81    | 63.57    | 34.30    | 83.33    | 78.06   | 16.99    |  
| 30   | mengzi_std            | 澜舟科技               | 否       | 57.28 | 86.78    | 48.41    | 82.20    | 60.95    | 63.33   | 2.01     |  
| 31   | XVERSE-7B-Chat        | 深圳元象科技           | 是       | 56.77 | 85.45    | 39.90    | 81.60    | 39.29    | 64.62   | 29.78    |  
| 32   | Phi-3.5-mini-instruct | 微软                   | 是       | 55.66 | 81.75    | 44.15    | 62.90    | 24.05    | 76.34   | 44.78    |  
| 33   | Mistral-7B            | Mistral AI             | 是       | 54.23 | 83.90    | 35.17    | 84.30    | 41.67    | 68.06   | 12.27    |  
| 34   | Gemma-7B              | Google                 | 是       | 51.05 | 77.19    | 39.71    | 84.60    | 21.43    | 71.94   | 11.45    |  
| 35   | Gemma-2B              | Google                 | 是       | 46.95 | 63.70    | 25.60    | 81.40    | 14.05    | 55.48   | 41.45    |  
| 36   | InternLM2-Chat-1.8B   | 上海人工智能实验室     | 是       | 46.68 | 72.53    | 28.21    | 87.30    | 23.81    | 53.87   | 14.35    |  
| 37   | Qwen-1.8B-Chat        | 阿里云                 | 是       | 46.22 | 72.63    | 32.17    | 75.60    | 32.14    | 54.09   | 10.67    |  
| 38   | AquilaChat-7B         | 北京智源人工智能研究院 | 是       | 43.29 | 70.21    | 37.78    | 52.90    | 41.90    | 44.84   | 12.12    |  
| 39   | XuanYuan-6B-Chat      | 度小满                 | 是       | 39.45 | 54.05    | 33.33    | 73.50    | 27.14    | 47.96   | 0.69     |  
| 40   | TuringMM-34B-Chat     | 北京光年无限科技有限公司 | 是     | 38.80 | 36.17    | 23.86    | 52.70    | 61.43    | 52.26   | 6.38     |  
| 41   | Index-1.9B            | bilibili               | 是       | 38.48 | 56.56    | 24.25    | 63.70    | 33.81    | 50.65   | 1.92     |  
| 42   | Skywork-13B-Base      | 昆仑万维               | 是       | 32.44 | 40.56    | 23.86    | 48.80    | 28.57    | 46.77   | 6.10     |  
| 43   | Vicuna-13B-v1.5       | 斯坦福                 | 是       | 27.72 | 49.69    | 17.78    | 33.30    | 13.57    | 48.71   | 3.30     |  


