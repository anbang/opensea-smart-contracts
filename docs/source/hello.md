# Opensea Solidity 合约源码概览

这里介绍 Opensea 的源码分析

## 媒体资料

- 官网: https://opensea.io/
- Github: https://github.com/ProjectOpenSea
- [Github 上所有的合约相关仓库](https://github.com/orgs/ProjectOpenSea/repositories?q=&type=all&language=solidity&sort=)
  - Seaport: https://github.com/ProjectOpenSea/seaport
  - operator-filter-registry: https://github.com/ProjectOpenSea/operator-filter-registry
  - seadrop: https://github.com/ProjectOpenSea/seadrop
  - seaport-order-validator: https://github.com/ProjectOpenSea/seaport-order-validator
  - 0x-fee-wrapper: https://github.com/ProjectOpenSea/0x-fee-wrapper
  - meta-transactions: https://github.com/ProjectOpenSea/meta-transactions
  - marketplace-benchmarks: https://github.com/ProjectOpenSea/marketplace-benchmarks
- 官方说明文档:
  - Seaport: https://docs.opensea.io/v2.0/reference/seaport-overview

## Seaport 核心合约的资料

- 仓库:https://github.com/ProjectOpenSea/seaport
- 文档: https://github.com/ProjectOpenSea/seaport/blob/main/docs/SeaportDocumentation.md
- 接口: https://github.com/ProjectOpenSea/seaport/blob/main/contracts/interfaces/SeaportInterface.sol
- 完整接口文档: https://docs.opensea.io/v2.0/reference/seaport-overview
- 已部署的合约地址:
  - Seaport 1.1: [0x00000000006c3852cbEf3e08E8dF289169EdE581](https://etherscan.io/address/0x00000000006c3852cbEf3e08E8dF289169EdE581#code)
  - ConduitController: [0x00000000F9490004C11Cef243f5400493c00Ad63](https://etherscan.io/address/0x00000000F9490004C11Cef243f5400493c00Ad63#code)
- 部署文档:
  - https://github.com/ProjectOpenSea/seaport/blob/main/docs/Deployment.md
- 流程图:
  - [精简版](https://github.com/ProjectOpenSea/seaport#diagram)
  - [完整版](https://github.com/ProjectOpenSea/seaport/tree/main/diagrams)
- 审计报告:
  - https://github.com/trailofbits/publications/blob/master/reviews/SeaportProtocol.pdf
- 相关解读
  - https://www.theblockbeats.info/news/30718
  - https://www.panewslab.com/zh/articledetails/sk465e369t44.html
