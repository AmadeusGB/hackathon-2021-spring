# 2021 春季 Polkadot / Substrate 黑客松

## 重要时间表

|日期 | 事项|
|----|-----|
| 2 月 11 日* |截止参赛报名 |
| 3 月 15 日* |截止提交参赛项目 |
| 3 月 20 - 21 日 | 上海黑客松周末 |

- 截止报名时间点： **2 月 11 日 23:59**
- 截止提交参赛项目时间点： **3 月 15 日 23:59**

- [报名链接](https://shimo.im/forms/gphHCQHpkXYcwKGP/fill)
- [参赛类别](./docs/categories.md)

## Workshop 及 Office Hour 时间表

|日期     | 类别 | 主讲者 | 事项 |
|--------|------|------|-------|
|2月7日  | Office Hour | Jimmy (Parity) | 答疑 |
|2月8日  | Workshop[技术] | Jimmy (Parity) | 参赛任务涉及到的Substrate技术领域和内容 |
|2月18日 | Workshop[技术] | 陈锡亮 (Acala) | 如何利用 ORML 实现多币种支持和 NFT |
|2月21日 | Office Hour | Junius (Parity) | 答疑 |
|2月23日 | Workshop[技术] | 吴逸飞 | Offchain Workers 入门 |
|2月26日 | Workshop[技术] | Aten (Patract Labs) | 如何更轻松的开发 WASM 合约 |
|2月28日 | Office Hour | Maggie (Parity) | 答疑 |
|3月3日  | Workshop[技术] | 郭斌 | 如何在 ARM 架构下运行 Substrate |
|3月7日  | Office Hour | Kaichao (Parity) | 答疑 |
|3月9日  | Workshop[生态] | SNZ | 如何选择波卡生态的投资赛道 |
|3月14日 | Office Hour | Jimmy (Parity) | 答疑 |
|3月15日 | Workshop[生态] | 肖晓 (Hashkey) | 投资波卡生态项目的5个纬度 |
|3月17日 | Office Hour | Junius (Parity) | 答疑 |
|3月18日 | Workshop[生态] | Helena (Parity) | Parity 与 Web3 基金会将如何支持开发者加入波卡生态 |

- Workshop 及 Office Hour 为上述日期的 19:00 - 20:00 (UTC +8 / 中国时间)
- 到这里 [实时收听 Workshop 及 Office Hour](https://parity.link/asia-hackathon-wo) (用[腾讯会议](https://meeting.tencent.com/))
- 到我们 [B 站频道](https://space.bilibili.com/67358318/channel/detail?cid=168675) 观看过往录播

## 提交参赛项目信息

**3 月 15 日提交参赛项目信息** 时，请包括以下信息：

* 演示开始前，每队必须在 Substrate Hackathon 的 GitHub 组织下新建仓库，并以任一开源协议将本次参赛的全部相关代码上传到该仓库以供审阅。请各队事先联系工作人员加入 GitHub 的 Substrate Hackathon 组织。
* 每个团队至少提交一件作品, 作品内容包括但不限于：相关代码、项目介绍文档、项目 Demo、未来 3 个月项目规划、队员信息 。 提交时，需同时具备 **中英文内容**。
* 提交一段不长于 **8 分钟的产品 DEMO 展示视频**。
* 参赛作品若出现剽窃其他作品行为，取消参赛资格。
* 作品初步提交时间需在规定时间内（3月15日晚上19:00 - 24:00），其他时间提交无效。

更多详情，[请看这里](docs/01-announcement.md#a-代码提交3月15日)

## 项目提交流程

1. fork 这个代码仓库，到你们团队成员 repo 里。
2. 先在 `teams` 内生成一个目录，以你们团队名称命名，里面先放个空档案，或 readme 简单介绍团队。提交一个 PR 进来。目的是预留一个目录作为你们团队空间。
3. 之后，所有参赛项目相关代码都放在你们的团队名称里的目录里进行。可以是这种目录形式：

    ```
    teams
      L 撒亚人战队    // 撒亚人也学 Substrate 了 😉
        L substrate // substrate 相关代码
        L ui        // 前端相关代码
        L docs      // 这里放所有文档，项目资料，规划，demo 链接, ppt (链接)
        L 。。。其他档案
    ```

4. 到截止日 3月15日 时，提交一个 PR 进来本 repo 里，团队只可改修改他们目录里的档案。这样也可保持各团队们的参赛项目直到 3月15日 时保密性。

5. 我们 3月16日 merge PR。评委们会以 3月16日前最后一个 PR 成果来评分。

## 官方宣发


1. [首届 Parity 官方 Substrate 开发者黑客马拉松报名开始](./docs/01-announcement.md)
2. [Polkadot Hackathon 豪华评审团19位导师公布](./docs/02-judges.md)

## 联络

对黑客松有任何疑问，可以下方法联系我们:

* [Github 讨论区](https://github.com/ParityAsia/hackathon-2021-spring/discussions)

* email: hackathon.asia@parity.io

* 扫码进入微信参赛群：

    ![group-qr-code](assets/misc/01-group-qr-code.png)

    或添加 Jessie 女仕微信（yikuailianxi）

## 其他

### 合法合规性

本次黑客松为符合国内法规，我们不会触碰以下任何有关题目

- 和发币 (Initial Coin Offering) 相关。
- 和数字资产交易相关
- 任何币价的讨论 (Decentralized Exchange 主题可讨论技术，不涉及币价)
- 和博彩相关和有博彩成分的游戏

### 参赛项目协议 (License)

所有参赛项目协议必须选用其中一个开源软件项目协议。下面有对主流协议的介绍 (包括 GPLv3, Apache License 2.0, BSD, MIT License)。如果真不知道怎么选，可考虑使用 MIT License。这协议给予其他开发者很大的自由度。

参考链接

- [主流开源协议介绍 - 英文](https://www.freecodecamp.org/news/how-open-source-licenses-work-and-how-to-add-them-to-your-projects-34310c3cf94/)
- [主流开源协议介绍 - 中文](https://www.runoob.com/w3cnote/open-source-license.html)
