# 🖱️ Computer Use —— Codex 电脑操控插件（含 HyperFrames）

让 Codex 直接操控你本地 Mac 上的应用：自动点击、输入、滚动、拖拽、按键、设置数值，替你完成需要「动手操作 App 界面」的任务。本仓库还**附带了 HyperFrames 视频插件**。

---

## 📦 安装（在新电脑上使用）

1. 点本页右上角绿色 **`Code` → `Download ZIP`**，下载后解压
2. 打开「终端」，进入解压出来的文件夹，运行：
   ```bash
   bash restore.sh
   ```
3. **重启 Codex** 即可生效

> 脚本只是把插件复制到 `~/.codex/plugins/`，**不含任何密钥或凭证**，放心使用。
>
> ⚠️ Computer Use 第一次运行会向系统申请「辅助功能 / 屏幕录制」权限，按提示在「系统设置 → 隐私与安全性」里给 Codex 打勾即可。

---

## 🚀 怎么用

安装并重启后，在 Codex 输入框里打 `/`，再输入命令名调用。

### 核心命令

| 命令 | 能干嘛 |
|------|-------|
| **`/computer-use`** | 控制本地 Mac 应用：读取并操作 App 界面——点击、输入、滚动、拖拽、按键、设置值。适合那些没有 API、只能靠「手动点」完成的任务。 |

**示例**：
```
/computer-use 帮我打开「备忘录」，新建一条便签，把这段文字粘进去
/computer-use 在这个 App 里把设置项 X 改成 Y
```

### 附带的 HyperFrames 命令（用 HTML 做视频）

本仓库也打包了 HyperFrames 插件，装完后这些命令也能用（详细说明见 **hyperframes** 仓库）：

| 命令 | 能干嘛 |
|------|-------|
| **`/hyperframes`** | 用 HTML 做视频：动画、标题卡、字幕、配音、音频可视化、转场 |
| **`/website-to-hyperframes`** | 给个网址，自动截取网站做成宣传视频 / 产品短片 |
| **`/hyperframes-cli`** | HyperFrames 命令行工具（init / lint / preview / render / tts 等） |
| **`/hyperframes-registry`** | 安装并接入 registry 里的区块和组件 |
| **`/gsap`** | GSAP 动画写法参考 |

---

有问题随时问 🎉
