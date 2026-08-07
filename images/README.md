# 宣传图片素材目录 (promo_assets)

请把聊天中收到的 6 张宣传截图，按以下文件名重命名后放入本目录：

| 文件名 | 内容 |
|--------|------|
| `01_ai_screenwriting_studio.png` | 系统公告：小说一键改编 / AI 剧组 |
| `02_model_lineup.png`            | 模型列表：Gemini 3.6 Flash / Grok-Video 3.5 / GPT Image 2 / GPT-5.6 Luna / Sora 2 |
| `03_deepseek_v4_flash.png`       | DeepSeek V4 Flash 模型页 |
| `04_inspiration_gallery.png`     | 灵感画廊：AI 作品 / 提示词 |
| `05_agent_universal_studios.png` | 环球影城第二季智能体 |
| `06_seedance_video.png`          | Seedance 1.5 Pro 视频生成 |

放入后，发布脚本 (promo_publish.py) 会自动读取 `daily_posts/image_assets.json`，
为每张图匹配英文文案，并按平台（Facebook / X / Dev.to）带图发布。

图片格式支持 png / jpg / jpeg / webp。
