## 基本资料

项目名称：ToEarnFun

项目立项日期：2022年5月

## 项目整体简介

![logo](./assets/toearnfun-log.svg)

ToEarnFun是一款fit to earn的Web3的智能健身应用程序。相对于其它只有Social-Fi和Game-Fi元素的x-to-earn应用，它能够与真实的智能健身设备连接，依靠硬件芯片的加密技术，保证付出的汗水得到公平的回报。ToEarnFun的入门用户无需购买加密货币，只需要购买应用适配的智能健身设备，即可马上fit to earn，大大降低普通用户进入web3世界的门槛。

项目有以下特点：

- 简单易上手。
- 健身锻炼+GameFi
- 硬件级防作弊技术。
- 完全去中心实现。
- 可持续的变现方式。
- 灵活手续费模式。
- 社区驱动发展。
- 跨链互操作。

我们将实现以下几个应用场景：

- 促进健身器材生产销售。
- 健身锻炼+GameFi。
- VFE交易市场。
- 公益赛事挑战。

更多详细内容请[点击此处](./docs/README_CN.md)。
我们也做了一份中文版的PPT，[点击此处](./docs/toearnfun-ppt.pdf)。

## Architecture

![Architecture](./assets/toearnfun-architecture.png)

## 黑客松期间计划完成的事项

- 请团队在报名那一周 git clone 这个代码库并创建团队目录，在 readme 里列出黑客松期间内打算完成的代码功能点。并提交 PR 到本代码库。例子如下 (这只是一个 nft 项目的例子，请根据团队项目自身定义具体工作)：

**区块链端**

- `pallet-VFE`
  - [x] 创建VFE类型
  - [x] 器材厂商注册
  - [x] 厂商账本管理者地址更换
  - [x] 厂商充值保证金
  - [x] 厂商提现保证金
  - [x] 注册健身器材
  - [x] VFE绑定器材
  - [x] VFE解绑器材
  - [x] VFE实例铸造
  - [x] VFE实例转账
  - [x] 锻炼上报
  - [ ] 能量恢复

**客户端**

- 智能跳绳 端
  - [x] 加密算法接口
  - [x] 蓝牙通信协议

- App 端
  - [ ] 初始化账户及钱包
  - [ ] 绑定健身器材
  - [ ] 我的VFE
  - [ ] 训练报告
  - [ ] 我的资产

## 黑客松期间所完成的事项 (6月22日初审前提交)

- 6月22日前，在本栏列出黑客松期间最终完成的功能点。
- 把相关代码放在 `src` 目录里，并在本栏列出在黑客松期间打完成的开发工作/功能点。我们将对这些目录/档案作重点技术评审。
- 放一段不长于 **5 分钟** 的产品 DEMO 展示视频, 命名为 `团队目录/docs/demo.mp4`。初审时这视频是可选，demo day 这是计分项。

## Demo Video

https://drive.google.com/file/d/1hpaKNFYQhYxkj0dNOEaRD81jcSrm66h3/view?usp=sharing

## 队员信息

| 名字                                         | 角色        | 简介                                                                                |
|----------------------------------------------|-----------|-----------------------------------------------------------------------------------|
| [Mai zhiquan](https://github.com/zhiquan911) | 项目经理    | 从事多年区块链开源技术开发，创建过openwallet等优秀框架。目前全身心投入到Web3的建设中。 |
| [Doxin Liang](https://github.com/metadex003) | 区块链开发  | Substrate进阶课程优秀毕业生，拥有6年的区块链相关开发经验。                            |
| [Arrom](https://github.com/shenzhen-arrom)   | 移动端开发  | 参加过波卡和以太坊组织的几届黑客松。                                                 |
| [Fany](https://github.com/fanyinghao)        | Web前端开发 | 拥有多年Dapp开发经验。                                                               |

