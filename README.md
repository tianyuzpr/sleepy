# sleepy

> 欢迎来到 Sleepy Project 的主仓库!

一个用于 ~~*视奸*~~ 查看个人在线状态 (以及正在使用软件) 的 Flask 应用，让他人能知道你不在而不是故意吊他/她

[**功能**](#功能) / [**演示**](#preview) / [**部署**](#部署--更新) / [**服务端配置**](#服务器配置) / [**使用**](#使用) / [**Client**](#client) / [**API**](#api) / [**关于**](#关于)

## 功能

- [x] 自行设置在线状态 *(活着 / 似了 等, 也可 **[自定义](./setting/README.md#status_listjson)** 状态列表)*
- [x] 实时更新设备使用状态 *(包括 是否正在使用 / 打开的应用名, 通过 **[client](./client/README.md)** 主动推送)*
- [x] 美观的展示页面 [见 [Preview](#preview)]
- [x] 开放的 Query / Metrics [接口](./doc/api.md), 方便统计
- [x] 支持 HTTPS (需要自行配置 SSL 证书)

> [!TIP]
> **最新 开发进度 / TODOs 见: [Discord][link-dc]** / [Telegram][link-tg] / [QQ][link-qq]<br/>
> 如有 Bug / 建议, 可发 issue (**[Bug][link-issue-bug]** / **[Feature][link-issue-feature]**) 或选择上面的联系方式 *(注明来意)*.

### Preview

演示站: [sleepy.wyf9.top](https://sleepy.wyf9.top)

**开放预览站**: [sleepy-preview.wyf9.top](https://sleepy-preview.wyf9.top)

<details>

<summary>展开更多</summary>

**HuggingFace** 部署预览: [wyf9-sleepy.hf.space](https://wyf9-sleepy.hf.space)

**Vercel** 部署预览: [sleepy-vercel.wyf9.top](https://sleepy-vercel.wyf9.top)

**开发服务器**: [请在 Discord 服务器查看][link-dc]

</details>

## 部署 / 更新

请移步 **[部署教程](./doc/deploy.md)** 或 **[更新教程](./doc/update.md)** *(多图警告)*

## 客户端

搭建完服务端后，你可在 **[`/client`](./client/README.md)** 找到客户端 (用于**手动更新状态**/**自动更新设备打开应用**)

*目前已有 [Windows](./client/README.md#windevice), [Linux](./client/README.md#linux), [IOS / MacOS](./client/README.md#iosmacos), [Android](./client/README.md#autoxjsscript), [油猴脚本](./client/README.md#browserscript) 等客户端*

## API

详细的 API 文档见 [doc/api.md](./doc/api.md).

<!-- ## 插件系统

(普通用户看这个) **[doc/plugin.md](./doc/plugin.md)**

(插件开发看这个) **[doc/plugin-dev/README.md](./doc/plugin-dev/README.md)** -->

## Star History

[![Star History Chart (如无法加载图片可点击查看)](https://api.star-history.com/svg?repos=sleepy-project/sleepy&type=Date)](https://star-history.com/#sleepy-project/sleepy&Date)

## 贡献者

> [!WARNING]
> 在提交代码前, 请先查阅 **[贡献准则](https://github.com/sleepy-project/.github/blob/main/CODE_OF_CONDUCT.md)** 和 **[贡献指南](./CONTRIBUTING.md)**

<!-- readme: contributors -start -->
<table>
	<tbody>
		<tr>
            <td align="center">
                <a href="https://github.com/wyf9">
                    <img src="https://avatars.githubusercontent.com/u/72241996?v=4" width="100;" alt="wyf9"/>
                    <br />
                    <sub><b>wyf9</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/kmizmal">
                    <img src="https://avatars.githubusercontent.com/u/175951556?v=4" width="100;" alt="kmizmal"/>
                    <br />
                    <sub><b>kmizmal</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/ntkrnl32">
                    <img src="https://avatars.githubusercontent.com/u/197464182?v=4" width="100;" alt="ntkrnl32"/>
                    <br />
                    <sub><b>NT | Krnl32</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/gongfuture">
                    <img src="https://avatars.githubusercontent.com/u/60888755?v=4" width="100;" alt="gongfuture"/>
                    <br />
                    <sub><b>洛初</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/NiuFuyu855">
                    <img src="https://avatars.githubusercontent.com/u/103884299?v=4" width="100;" alt="NiuFuyu855"/>
                    <br />
                    <sub><b>NiuFuyu</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/NoSetViolin">
                    <img src="https://avatars.githubusercontent.com/u/130219679?v=4" width="100;" alt="NoSetViolin"/>
                    <br />
                    <sub><b>阿梓喵_あずにゃん</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/pwnInt">
                    <img src="https://avatars.githubusercontent.com/u/194147583?v=4" width="100;" alt="pwnInt"/>
                    <br />
                    <sub><b>pwnint</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/wan0ge">
                    <img src="https://avatars.githubusercontent.com/u/82034747?v=4" width="100;" alt="wan0ge"/>
                    <br />
                    <sub><b>Elegy233</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/EndCredits">
                    <img src="https://avatars.githubusercontent.com/u/64133324?v=4" width="100;" alt="EndCredits"/>
                    <br />
                    <sub><b>对乙酰氨基酚</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/RikkaNekoo">
                    <img src="https://avatars.githubusercontent.com/u/98643870?v=4" width="100;" alt="RikkaNekoo"/>
                    <br />
                    <sub><b>Rikka Shiina</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/LeiSureLyYrsc">
                    <img src="https://avatars.githubusercontent.com/u/162931251?v=4" width="100;" alt="LeiSureLyYrsc"/>
                    <br />
                    <sub><b>Murasame Noa</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/Detritalw">
                    <img src="https://avatars.githubusercontent.com/u/89017417?v=4" width="100;" alt="Detritalw"/>
                    <br />
                    <sub><b>Detrital</b></sub>
                </a>
            </td>
		</tr>
		<tr>
            <td align="center">
                <a href="https://github.com/SliverKeigo">
                    <img src="https://avatars.githubusercontent.com/u/112426853?v=4" width="100;" alt="SliverKeigo"/>
                    <br />
                    <sub><b>SliverKeigo</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/ddaodan">
                    <img src="https://avatars.githubusercontent.com/u/40017293?v=4" width="100;" alt="ddaodan"/>
                    <br />
                    <sub><b>ddaodan</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/nuym">
                    <img src="https://avatars.githubusercontent.com/u/102905510?v=4" width="100;" alt="nuym"/>
                    <br />
                    <sub><b>四月櫻花 洇染成殤</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/VanillaNahida">
                    <img src="https://avatars.githubusercontent.com/u/151599587?v=4" width="100;" alt="VanillaNahida"/>
                    <br />
                    <sub><b>香草味的纳西妲喵</b></sub>
                </a>
            </td>
		</tr>
	<tbody>
</table>
<!-- readme: contributors -end -->

## 关于

非常感谢 **ZMTO** *(原名 VTEXS)* 的 **「开源项目免费 VPS 计划」** 对项目提供的算力支持！

> **[Link](https://console.zmto.com/?affid=1566)** *(使用此链接获得 10% 优惠)* <!-- 谁都不许改 affid -->

---

本项目灵感由 Bilibili UP [@WinMEMZ](https://space.bilibili.com/417031122) 而来: **[site](https://maao.cc/sleepy/)** / **[blog](https://www.maodream.com/archives/192/)** / **[repo: `maoawa/sleepy`](https://github.com/maoawa/sleepy)**, 并~~部分借鉴~~使用了前端代码, 在此十分感谢。

[`templates/steam-iframe.html`](./templates/steam-iframe.html) 来自 repo **[gamer2810/steam-miniprofile](https://github.com/gamer2810/steam-miniprofile).**

---

对智能家居 / Home Assistant 感兴趣的朋友，一定要看看 WinMEMZ 的 [sleepy 重生版](https://maao.cc/project-sleepy/): **[maoawa/project-sleepy](https://github.com/maoawa/project-sleepy)!**

感谢 [@1812z](https://github.com/1812z) 的 B 站视频推广~ **([BV1LjB9YjEi3](https://www.bilibili.com/video/BV1LjB9YjEi3))**

---

[link-dc]: https://sleepy.siiway.top/t/dc
[link-tg]: https://sleepy.siiway.top/t/tgc
[link-qq]: https://sleepy.siiway.top/t/qq
[link-issue-bug]: https://sleepy.siiway.top/t/bug
[link-issue-feature]: https://sleepy.siiway.top/t/feature
