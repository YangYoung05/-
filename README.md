# [项目名：LingYuan & WenYan Monorepo]
**一句话**：本地 LLM 聊天（铃源） + 成语 30s 短视频生成（问言）。

- 🔹 亮点：离线优先、本地/云模型双通道；一键生成讲解文案+TTS+视频合成（9:16 预设）
- 🧩 技术：SwiftUI · AVFoundation ·（可选）DashScope/TTS · 简洁可读的架构
- 🏁 快速体验：
  ```bash
  # 铃源（本地 LLM 客户端）
  open lingyuan/LingYuan.xcodeproj   # Xcode 15+，Run 即可（如用本地模型，详见 lingyuan/README）

  # 问言（成语短视频生成）
  open wenyan/WenYan.xcodeproj       # 填入 API Key，Run → 生成示例视频
