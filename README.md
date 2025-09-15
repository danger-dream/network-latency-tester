# 网络延迟一键检测工具

🚀 **简单易用的网络延迟检测工具**，一键测试多个知名网站的连接延迟。

## 更新内容
- 增加更多测试站点
- 执行运行，不需要选择测试类型
- 不再输出文件

## 🚀 快速开始

### 一键运行
```bash
bash <(wget -qO- https://raw.githubusercontent.com/danger-dream/network-latency-tester/main/latency.sh)
```

## ✨ 功能特性

- 🎯 **交互界面** - 友好的菜单选择
- 🌐 **完整测试** - 多个知名网站、API接口
- 📊 **美观输出** - 彩色表格和统计
- 💾 **自动保存** - 结果保存到文件

## 📋 测试网站
### 完整测试
```bash
declare -A FULL_SITES=(
  ["Apple"]="apple.com"
	["Amazon"]="amazon.com"
	["Google"]="google.com"
  ["YouTube"]="youtube.com"
	["YouTubeImg"]="i.ytimg.com"
  ["Microsoft"]="microsoft.com"
	["Bing"]="bing.com"
  ["Twitter"]="twitter.com"
  ["ChatGPT"]="api.oaipro.com"
	["Claude"]="api.anthropic.com"
	["Gemini"]="generativelanguage.googleapis.com"
 	["Grok"]="api.x.ai"
  ["Steam"]="steampowered.com"
  ["Netflix"]="netflix.com"
  ["Disney"]="disneyplus.com"
  ["Instagram"]="instagram.com"
  ["Telegram"]="tg.d1ss.eu.org"
	["TelegramWeb"]="web.telegram.org"
  ["Dropbox"]="dropbox.com"
  ["OneDrive"]="onedrive.live.com"
  ["Mega"]="mega.io"
  ["Twitch"]="twitch.tv"
  ["Pornhub"]="pornhub.com"
  ["Facebook"]="facebook.com"
  ["TikTok"]="tiktok.com"
	["NodeSeek"]="www.nodeseek.com"
	["LinuxDo"]="linux.do"
	["Cloudflare"]="cloudflare.com"
	["LowEndTalk"]="lowendtalk.com"
	["GitHub"]="github.com"
	["GithubuSercontent"]="release-assets.githubusercontent.com"
	["Cursor"]="api2.cursor.sh"
)
```

## 📊 延迟等级

| 等级 | 延迟 | 适用场景 |
|------|------|----------|
| 🟢 优秀 | < 50ms | 游戏、视频通话 |
| 🟡 良好 | 50-150ms | 网页浏览、视频 |
| 🔴 较差 | > 150ms | 基础使用 |

## 🔧 系统要求

- Linux/macOS/WSL
- bash
- ping 和 curl 命令

## 📄 许可证

MIT License

---

⭐ 如果对您有帮助，请给个 Star！
