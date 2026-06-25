graphic-ad-design
<img width="1024" height="1536" alt="微信图片_20260625202647_835_46" src="https://github.com/user-attachments/assets/f8d94f30-7f74-4b88-a428-b7c835b667af" />
<img width="1024" height="1536" alt="微信图片_20260625152305_834_46" src="https://github.com/user-attachments/assets/a09934b3-ae3f-4407-931d-d9b9e9cf4352" />
<img width="1024" height="1536" alt="微信图片_20260624110832_814_46" src="https://github.com/user-attachments/assets/a768327a-2a70-4fbc-bdbe-aad337d0d6d6" />
平面广告设计 skill：广告调研、创意简报、GPT 研究与 Image2 出图迭代。
这个仓库里的核心工作流写在 SKILL.md，README.md 主要给人看，方便快速理解这个 skill 能做什么、怎么用、以及和 GPT / Image2 怎么配合。
适用场景
适合下面这些任务：
搜集广告灵感
调研竞品广告并提炼方案
做海报、传单、社媒广告、门店宣传图
把参考图转成新的广告创意
为 gpt-image-2 / Image2 写生成或编辑提示词
把调研、文案、版式、视觉方向整理成可执行的广告简报
你会得到什么
使用这个 skill 时，Codex 通常会输出：
一份清晰的广告创意简报
2 到 4 条可选创意方向
适合投放场景的文案层级
能直接喂给 Image2 的生成或编辑提示词
最终的可读性和落地检查建议
开始前先确认的内容
如果信息足够，直接进入方案；如果不够，优先补齐这些：
行业或品类
产品 / 服务名称
目标人群
投放渠道
尺寸或比例
必须出现的内容
不能出现的内容
品牌色、品牌字气、参考图
标准工作流
1. 明确目标
先确定这张广告的任务是什么：
拉新
到店
转化
活动报名
品牌曝光
2. 用 GPT 做调研
先让 GPT 做研究，再做视觉：
看竞品怎么说
看同类广告怎么排版
找出高频视觉套路
抽取可复用的卖点和证明方式
识别容易踩坑的表达和画面
3. 写创意简报
把调研结果压缩成一页简报：
目标受众
核心痛点
一句话主张
证据点
CTA
必须出现项
禁止项
尺寸和比例
4. 生成多个方案
建议至少给 2 到 4 个方向：
产品优先
痛点解决
情绪氛围
促销转化
品牌信任
5. 接 Image2 / gpt-image-2
把选中的方向变成图像提示词：
让模型生成广告视觉底图
保留文字安全区
避免在图里写最终文案、价格、二维码、电话
用编辑模式迭代构图、光影、留白和主体清晰度
6. 最后检查
出图前再看一遍：
3 秒能不能看懂是什么
主卖点是不是足够明显
文案层级是否清楚
CTA 是否明确
画面是否可读、可裁切、可投放
推荐使用方式
可以直接这样调用这个 skill：
Use $graphic-ad-design to research ad inspiration, build a creative brief, and generate polished print or social ad concepts.
也可以直接说：
搜集干洗店广告灵感
调研某个品类广告并提炼方案
给我做一版海报创意简报
把这张参考图改成更像广告的方案
给我一组适合 Image2 的出图提示词
与 GPT 和 Image2 的配合建议
GPT 负责什么
GPT 更适合做这些事：
研究和归纳
对比不同广告套路
提炼主张和文案层级
生成多个创意方向
做方案评审和修改建议
Image2 负责什么
Image2 更适合做这些事：
生成视觉底图
迭代构图和氛围
处理主体、背景、留白
做基于参考图的视觉变体
最稳的组合方式
先用 GPT 研究和定方向
再把方向转成 Image2 提示词
用 Image2 出图
回到 GPT 做点评
再做窄范围修改
最后把正式文案和品牌元素放到排版层
目录说明
SKILL.md：给 Codex 读取的主流程和触发说明
agents/openai.yaml：UI 展示用信息
<img width="1152" height="1152" alt="a3bb59eea2c220cce50498c6ee020cb5" src="https://github.com/user-attachments/assets/75c0e9fa-7707-4627-bfdc-ab012b3ed27d" />


references/research-and-brief.md：调研和创意简报模板
references/image2-prompts.md：Image2 / gpt-image-2 提示词模板
references/design-rubric.md：广告评审和修改清单
一句话总结
这个 skill 的目标不是“随便出一张图”，而是把广告从调研、策略、文案、视觉到出图迭代串成一个完整流程。
