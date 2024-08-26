# NoMoreWalls

[![Fetch Status](https://github.com/peasoft/NoMoreWalls/actions/workflows/fetch.yml/badge.svg)](https://github.com/peasoft/NoMoreWalls/actions/workflows/fetch.yml) [![Stars](https://img.shields.io/github/stars/peasoft/NoMoreWalls?style=flat)](https://github.com/peasoft/NoMoreWalls/stargazers) [![Watchers](https://img.shields.io/github/watchers/peasoft/NoMoreWalls?style=flat)](https://github.com/peasoft/NoMoreWalls/watchers) [![Forks](https://img.shields.io/github/forks/peasoft/NoMoreWalls?style=flat)](https://github.com/peasoft/NoMoreWalls/forks) [![Repo size](https://img.shields.io/github/repo-size/peasoft/NoMoreWalls)](https://github.com/peasoft/NoMoreWalls/commits) ![Vistors](https://visitor-badge.laobi.icu/badge?page_id=peasoft.NoMoreWalls) [![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu) [![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/peasoft/NoMoreWalls/blob/master/LICENSE.md) [![暮光计划](https://img.shields.io/badge/link-暮光计划--向戒网瘾学校宣战-red.svg)](https://proj3ctaurora.tilda.ws/)

自动抓取合并互联网上的公开节点。

## 公告

[NoMoreWalls 的终极形态是肉身。](https://peasoft.github.io/2024/08/05/run.html)

由于 [BootCDN/Staticfile 已被病毒公司收购](https://www.52pojie.cn/thread-1944970-1-1.html)，我们拦截了这些网站。

如果您访问部分网站时遇到问题，可以将 `病毒网站` 分类切换为 `DIRECT`，但是您需要**自行承担一切安全风险，包括但不限于广告骚扰，账号被盗，设备中毒**等，请三思而后行！！！

知乎在中国大陆境内因未知原因只能获取乱码内容，无法正常浏览，因此我们将其加入了广告拦截列表以节省流量。何时移除取决于网站何时恢复正常，我们会密切关注这一情况。

为防止失联，我们建立了镜像：<https://peasoft.github.io/NWalls.html>

警报：Clash 死了！[最后的遗照](https://github.com/doreamon-design/clash)

受此影响，MetaCubeX 团队宣布放弃 Clash.Meta，改入游戏行业并发布了第一款基于 YS 二开的游戏：[mihomo](https://github.com/MetaCubeX/mihomo)。我试过了，很好玩（

为推动国产游戏(?)发展，本项目现已适配 mihomo 专用订阅，支持更多节点！详见下方 Clash 使用说明。

## Google Play 下载服务器已调整

Google Play 的**国内**下载服务器已完成部署，国行机下载软件时可以不过代理直连，非国行机仍然走国外服务器但也可直连。下载时将 `🐟 漏网之鱼` 切换成 `DIRECT` 即可享受**直连**的快感！

如果此问题有变化，我们会在此更新，请及时关注。

我们新增了 `snippets` 文件夹来存放从 `list.yml` 中拆分出的配置片段，用于将本项目提供的一些配置整合到你自己的配置中。

此项目现已添加“反 996 许可证”，请各位使用者**不要违法违规要求别人加班，自觉遵守《中华人民共和国劳动法》及其它法律法规**！

## 使用方法

注意：加速链接可能会失效，如果无法更新订阅，请把所有链接从上到下每个试一遍！你可以在电脑浏览器上安装油猴脚本 [Github 增强 - 高速下载](https://greasyfork.org/zh-CN/scripts/412245)，在目录浏览点开 `list.txt`，然后在 `Raw` 按钮边上找到最新的加速链接。

添加 Base64 订阅：
- [原始链接](https://raw.githubusercontent.com/peasoft/NoMoreWalls/master/list.txt)
- [GhProxy.cn](https://ghproxy.cn/https://raw.githubusercontent.com/peasoft/NoMoreWalls/master/list.txt)
- [GhProxy.com](https://mirror.ghproxy.com/https://raw.githubusercontent.com/peasoft/NoMoreWalls/master/list.txt)

以下链接可能不是最新：
- [JsDelivr 反代（zzko.cn）](https://cdn.jsdelivr.us/gh/peasoft/NoMoreWalls@master/list.txt)
- [JsDelivr Fastly CDN](https://fastly.jsdelivr.net/gh/peasoft/NoMoreWalls@master/list.txt)
- [JsDelivr Cloudflare CDN](https://testingcf.jsdelivr.net/gh/peasoft/NoMoreWalls@master/list.txt)
- [JsDelivr GCore CDN](https://gcore.jsdelivr.net/gh/peasoft/NoMoreWalls@master/list.txt)

以下加速链接可能无效：
- [KKGithub](https://raw.kkgithub.com/peasoft/NoMoreWalls/master/list.txt)

或添加 Clash 订阅：（重磅：本项目同时提供 Meta 专用订阅，支持更多节点！要使用 Meta 专用订阅，**强烈建议将链接最后的 `.yml` 替换成 `.meta.yml`**。如果 Meta 提示解析错误，请**更新 Meta 至最新版本**！）
- [原始链接](https://raw.githubusercontent.com/peasoft/NoMoreWalls/master/list.yml)
- [GhProxy.cn](https://ghproxy.cn/https://raw.githubusercontent.com/peasoft/NoMoreWalls/master/list.yml)
- [GhProxy.com](https://mirror.ghproxy.com/https://raw.githubusercontent.com/peasoft/NoMoreWalls/master/list.yml)

以下链接可能不是最新：
- [JsDelivr 反代（zzko.cn）](https://cdn.jsdelivr.us/gh/peasoft/NoMoreWalls@master/list.yml)
- [JsDelivr Fastly CDN](https://fastly.jsdelivr.net/gh/peasoft/NoMoreWalls@master/list.yml)
- [JsDelivr Cloudflare CDN](https://testingcf.jsdelivr.net/gh/peasoft/NoMoreWalls@master/list.yml)
- [JsDelivr GCore CDN](https://gcore.jsdelivr.net/gh/peasoft/NoMoreWalls@master/list.yml)

以下加速链接可能无效：
- [KKGithub](https://raw.kkgithub.com/peasoft/NoMoreWalls/master/list.yml)

## 免责声明

订阅节点仅作学习交流使用，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。**做出违法行为需要承担法律责任，侥幸逃脱是不可能的**！~~为阻止违法行为，本项目随时可以停止运行~~ 本项目可以采取各种技术手段来尽力阻止违法行为。

## 开发提示

由于本仓库的完整 Commit 历史极大（见页顶 repo size），如果要克隆本仓库，请使用：

```bash
git clone https://github.com/peasoft/NoMoreWalls.git --depth=1
```

如果本地仓库长期未更新，请删除仓库并重新克隆来同步最新更改，不要使用 `git pull`。

## 一些题外话

各位看一看：

- **[油罐车事件是最好的照妖镜，上赶着带节奏都是谁请大家记下来。](https://www.bilibili.com/video/BV1p1421b7Ki)私有化愈发严重影响的是所有中国人的切身利益，必须用公有平衡私有我们才有发展的前途。**

上方事件的严重性已经远超下面的事情了。

- **[【独家恢复】我们的教育弄虚作假，到底是为了什么](https://peasoft.github.io/2023/08/26/cnedu.html)：如此视频，为何惨遭删除？我们恢复了这段视频，只为让更多人可以看清现实。**
- **[最流氓的软件可以流氓到什么程度？](https://www.zhihu.com/question/29129310)我翻开其他网页一查，歪歪斜斜的每页上都写着“危险网页”几个字。我横竖睡不着，仔细看了半夜，才从字缝里看出字来，满本都写着两个字是“霸权”！**
- **[百度？百毒！](https://user.guancha.cn/main/content?id=100552)魏则西去世3周年：害死他的百度广告和莆田系医院**
- **[《满江红》的行为艺术](https://www.bilibili.com/video/BV11v4y1t7Gw/)：秦桧竟是我自己？**
- **[「 深蓝洞察 」2022 年度最“不可赦”漏洞](https://mp.weixin.qq.com/s/P_EYQxOEupqdU0BJMRqWsw)：知名互联网厂商(TMD并夕夕)持续挖掘新的安卓 OEM 相关漏洞，在其公开发布的 App 中实现对目前市场主流手机系统的漏洞攻击**（[具体分析](https://mp.weixin.qq.com/s/kiLvnJSDZpYRHI_XiUx9gg)）~~现已被工信部提名~~
- **[暑假学校敢补课？举报！](https://www.bilibili.com/video/BV1Vk4y1K79B)**
- **[逃离戒网瘾学校？我们找到办法了](https://www.bilibili.com/video/BV1Mg4y1A7bE)：希望你永远用不到。**
- **[一学校扔掉学生百余份外卖](https://www.bilibili.com/video/BV1a14y1S7n6)：涉嫌违法！**
- **[没收违法所得的合法性与合理性基础欠缺——简评承德程序员事件](https://www.dehenglaw.com/CN/tansuocontent/0008/029562/7.aspx?MID=0902)**
- **[【BootCDN/Staticfile投毒分析】供应链投毒后，我们的选择还剩下哪些？](https://www.52pojie.cn/thread-1944970-1-1.html)**
- 未完待续……

## Star History

<a href="https://star-history.com/#peasoft/NoMoreWalls">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=peasoft/NoMoreWalls&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=peasoft/NoMoreWalls" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=peasoft/NoMoreWalls" />
  </picture>
</a>
