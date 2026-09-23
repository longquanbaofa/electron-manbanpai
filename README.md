# 美超 · 慢半拍 — 下载

给 ChatGPT 语音通话加可调延时的桌面应用（Windows / macOS）。

本仓库**只用来分发安装包**，不放源代码。

## 下载

到 [**Releases**](https://github.com/longquanbaofa/electron-manbanpai/releases) 页面下载最新版：

| 系统 | 文件 |
| --- | --- |
| Windows 10 / 11（64 位） | `MeiChao-ManBanPai-Setup-<版本>.exe` |
| macOS · Apple 芯片（M 系列） | `MeiChao-ManBanPai-<版本>-arm64.dmg` |
| macOS · Intel 芯片 | `MeiChao-ManBanPai-<版本>-x64.dmg` |

## 装完第一次打开

- 就是一个 ChatGPT 窗口，正常登录一次即可，之后不用再登。
- 没有花钱买代码签名证书，所以系统会拦一下（正常现象）：
  - **Windows**：弹「已保护你的电脑」→ 点 **更多信息** → **仍要运行**
  - **macOS**：提示「无法验证开发者」→ 到 **系统设置 → 隐私与安全性** 点 **仍要打开**

## 怎么用

先在 ChatGPT 里正常发起语音通话，按 `⌘,`（Windows 是 `Ctrl+,`）打开设置，
打开「启用探针」，给「下行」或「上行」选一个秒数。关掉设置窗会变成悬浮球，随时能调。
设置页左上角的 `?` 里有完整使用指南。

---

源代码在另一个仓库（不公开分发）。当前处于测试阶段（beta）。
