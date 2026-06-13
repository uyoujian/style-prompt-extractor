# Style Prompt Extractor

提取参考图的视觉风格，反推为可复用的中文 AI 绘画提示词模板。剥离原图的具体角色/文字/情节，只保留美学灵魂。

## 用法

将本 skill 放入你的 agent 的 skills 路径后，上传一张参考图，即可获得一段中文 Prompt：

```
[在此处替换为您想要生成的主体内容]，置于……（覆盖构图/光影/色彩/材质等 15 维度的连贯中文描述）
```

适用于 GPT-Image、Nano Banana（Gemini）、Midjourney、Flux、Stable Diffusion。

## 覆盖维度

- 画面风格 · 构图 · 分镜 · 光影 · 色调 · 材质 · 情绪
- 渲染参数 · 时代感 · 透视 · 信息密度 · 动态 · 后期 · 符号特征

详见 [SKILL.md](SKILL.md)。
