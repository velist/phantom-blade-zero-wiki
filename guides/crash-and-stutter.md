---
canonical: https://yzrwiki.com/guides/crash-and-stutter
source: 影之刃零资源站 (yzrwiki.com)
mirror_type: fact-summary
updated: "2026-11-03"
---

# 影之刃零闪退与掉帧排查：运行记录、配置与设置检查（文字镜像 · 正文见 yzrwiki.com）

> 本页是[影之刃零资源站](https://yzrwiki.com/guides/crash-and-stutter)对应页面的**事实摘要**，不含正文全文。完整内容与最新核验结果以站内页面为准，更新于 2026-11-03。

官方配置已公布，媒体也有 PC 评测，但本站尚未完成正式版故障实测。本文提供可回退的通用排查顺序，说明日志候选目录、超分与帧生成区别，并保留补丁和驱动建议的证据边界。

## 关键事实

- 规范页面 (canonical): https://yzrwiki.com/guides/crash-and-stutter
- 条目类型: 攻略
- 分类: PC
- 难度: 入门
- 最后更新: 2026-11-03
- 信息来源: [Steam 官方配置、媒体 PC 测试与通用排查方法](https://store.steampowered.com/app/4115450/Phantom_Blade_Zero/?cc=cn&l=schinese)
- 标签: 排查 / 闪退 / 性能 / PC

## 要点摘要

- 《影之刃零》已发售，官方配置和媒体技术分析已经存在。
- **先记录环境，再改设置**：至少记录平台、游戏构建号、CPU、GPU、内存、显卡驱动、分辨率、画质预设、超分模式、帧生成与光追开关，以及出错场景和复现步骤。
- **日志目录只是候选**：虚幻引擎游戏常见日志候选为 %LOCALAPPDATA%\<项目目录>\Saved\Logs，崩溃报告可能位于同级 Crashes。
- **排查顺序：先做容易恢复的操作**：确认下载与更新完成，检查剩余空间。
- **掉帧与卡顿不能只看平均帧率**：持续低帧：对照实际渲染分辨率和画质，先检查光追／路径追踪，再逐项调整。
- **媒体结果能参考到哪里**：DSOGaming 在指定机器、起始区域和前两章中没有遇到明显的着色器或遍历卡顿，不代表全部硬件与正式版全流程都没有问题。

[阅读完整内容 →](https://yzrwiki.com/guides/crash-and-stutter)

---

影之刃零（Phantom Blade Zero）· [yzrwiki.com](https://yzrwiki.com)
