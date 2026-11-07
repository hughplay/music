# RESONANCE — 音乐的底层逻辑

一个面向理工科研究者的交互式中文乐理网站：从声波、频谱与听觉感知出发，逐步理解音程、调律、和弦、节奏、调性与音乐认知。

## 在线访问

https://hughplay.github.io/music/

首次发布时需要在仓库 [Settings → Pages](https://github.com/hughplay/music/settings/pages) 中将 Source 设为 **Deploy from a branch**，分支选 **main**，目录选 **/(root)**，然后保存。

## 课程内容

8 个循序渐进的章节，配有可交互的听觉和可视化实验：

- 声波、谐波与傅里叶分析
- 音高与缺失基频
- 八度与协和
- 纯律和十二平均律
- 和弦与和声构造
- 节拍与节奏型
- 调性、期待与终止式
- 非谐波音色与音乐感知前沿

## 本地运行

网站是单文件静态站点，直接下载 `index.html` 并使用现代浏览器打开即可。声音实验需要用户主动点击播放，部分浏览器还需要允许声音输出。

## 技术

纯 HTML / CSS / JavaScript，使用浏览器 Web Audio API 和 SVG 可视化，无需构建步骤或服务端。

## 隐私

学习进度保存在当前浏览器中，不会自动同步到 GitHub。
