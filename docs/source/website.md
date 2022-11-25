# 网页功能

- Create a Collection

## Create a Collection

- 网址: https://opensea.io/collection/create
- 属性: 中心化操作
- 结果: https://opensea.io/collection/anbang-collection

```
Logo image      : 合集的LOGO 350 x 350      (核心显示)
Featured image  : 合集精选图  600 x 400     (主页/类别页/活动推广页)
Banner image    : Banner图   1400 x 350     (合集主页顶部Banner区域显示)

Name            : 合集的名字
URL             : 合集的 URL    在 OpenSea 上自定义合集的 URL。只能包含小写字母、数字 和 -
Description     : 合集的介绍    使用 Markdown 语法，一共 1000 个字符

Category        合集所属的分类:
                Opensea 首页有 Browse by category，可以按照分类浏览NFT合集
                https://opensea.io/category/collectibles

Links
    - 你的网站
    - Medium
    - Telegram

Creator fees    : 版税      每次交易都会收一定比例的税，可以不设置；如果设置可以多地址瓜分
                    0xBB83214561E9690ff36639299494726944AA30Fc 1%
                    0x5dC61e930533136AbE35C1b442823259D6c07694 2%
Blockchain      : 选择合集所在的链  (Polygon)
Payment tokens  : 支持的Token列表  (ETH Polygon / Matic / USDC Polygon)
Display theme   : 显示主题         (合集内，NFT图片的显示方式)
Explicit & sensitive content    : 敏感内容标记
                    允许色情和敏感内容，但是不会被搜索出来；如果不标记，发现后会被删除
```

## Edit My Collection

- 网址: https://opensea.io/collection/xxxxxxx/edit
- 属性: 中心化操作

```
Social Connections      : 链接社交媒体
    - Twitter
    - Discord
    - Instagram
Collaborators           : 添加合作者
    - 可以在本合集上传NFT的地址
```

## Create New Item

- 网址: https://opensea.io/collection/anbang-collection/assets/create

## 属性页面

- 创作者收益: https://opensea.io/collection/anbang-collection/payouts

## Sell

- Fixed Price : 固定价格
- Timed Auction : 拍卖

### Fixed Price 签名内容

只能设置下面两个属性

- Set a price: 1 Matic
- Set duration: 1 Month

下面是预览

```
More options

Summary     上架是免费的。一经售出，将扣除以下费用。
Listing price   1 MATIC     挂单价格
Service Fee     2.5%        服务费
Creator Fee     3%          创作者费用（常说的版税）

Total potential earnings    0.945 MATIC     预估的最终收益
```

签名消息如下

```
offerer:        0xBB83214561E9690ff36639299494726944AA30Fc
offer:
    0:
        itemType        :   3
        token           :   0xA604060890923Ff400e8c6f5290461A83AEDACec
        identifierOrCriteria    :   84814189278733858855919475402523828762082208136572947867894469165638202949633
        startAmount             :   1
        endAmount               :   1

consideration:
    0:                  预期收益
        itemType:0
        token:0x0000000000000000000000000000000000000000
        identifierOrCriteria:0
        startAmount:945000000000000000
        endAmount:945000000000000000
        recipient:0xBB83214561E9690ff36639299494726944AA30Fc
    1:                  平台收益
        itemType:0
        token:0x0000000000000000000000000000000000000000
        identifierOrCriteria:0
        startAmount:25000000000000000
        endAmount:25000000000000000
        recipient:0x0000a26b00c1F0DF003000390027140000fAa719
    2:                  创作者1 的收益
        itemType:0
        token:0x0000000000000000000000000000000000000000
        identifierOrCriteria:0
        startAmount:10000000000000000
        endAmount:10000000000000000
        recipient:0xBB83214561E9690ff36639299494726944AA30Fc
    3:                  创作者2 的收益
        itemType:0
        token:0x0000000000000000000000000000000000000000
        identifierOrCriteria:0
        startAmount:20000000000000000
        endAmount:20000000000000000
        recipient:0x5dC61e930533136AbE35C1b442823259D6c07694

startTime   : 1669364098
endTime     : 1671956098
orderType   : 1
zone        : 0x0000000000000000000000000000000000000000
zoneHash    : 0x0000000000000000000000000000000000000000000000000000000000000000
salt        : 24446860302761739304752683030156737591518664810215442929814746464000893001823
conduitKey  : 0x0000007b02230091a7ed01230072f7006a004d60a8d4e71d599b8104250f0000
counter     : 0
```

### Timed Auction 拍卖

两种拍卖方式

- Sell to highest bidder : 卖给最高出价者
- Sell with declining price : 以下跌的价格出售(荷兰拍)

#### Sell to highest bidder

只能设置下面两个属性

- Set a price: 1 ETH
- Set duration: 7 Days

下面是预览

```
More options

Summary     上架是免费的。一经售出，将扣除以下费用。
Listing price   1 ETH       挂单价格
Service Fee     2.5%        服务费
Creator Fee     3%          创作者费用（常说的版税）

Total potential earnings    0.945 ETH     预估的最终收益
```

签名消息如下

```
offerer     :0xBB83214561E9690ff36639299494726944AA30Fc
offer:
    0:
        itemType:3
        token:0xA604060890923Ff400e8c6f5290461A83AEDACec
        identifierOrCriteria:84814189278733858855919475402523828762082208136572947867894469165638202949633
        startAmount:1
        endAmount:1
consideration:
    0:
        itemType:1
        token:0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619
        identifierOrCriteria:0
        startAmount:945000000000000000
        endAmount:945000000000000000
        recipient:0xBB83214561E9690ff36639299494726944AA30Fc
startTime:1669365228
endTime:1670574828
orderType:3
zone:0x110b2B128A9eD1be5Ef3232D8e4E41640dF5c2Cd
zoneHash:0x0000000000000000000000000000000000000000000000000000000000000000
salt:24446860302761739304752683030156737591518664810215442929817021064316783470848
conduitKey:0x0000007b02230091a7ed01230072f7006a004d60a8d4e71d599b8104250f0000
counter:0
```

#### Sell with declining price

能设置下面 3 个属性

- Set a price:
  - Starting price: 10 ETH
  - Ending price: 1 ETH
- Set duration: 7 Days

下面是预览

```
More options

Summary     上架是免费的。一经售出，将扣除以下费用。
Listing price   10 ETH       挂单价格
Service Fee     2.5%        服务费
Creator Fee     3%          创作者费用（常说的版税）

Total potential earnings    9.45 ETH     预估的最终收益
```

前面消息如下

```
offerer:0xBB83214561E9690ff36639299494726944AA30Fc
offer:
    0:
        itemType:3
        token:0xA604060890923Ff400e8c6f5290461A83AEDACec
        identifierOrCriteria:84814189278733858855919475402523828762082208136572947867894469165638202949633
        startAmount:1
        endAmount:1
consideration:
    0:
        itemType:1
        token:0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619
        identifierOrCriteria:0
        startAmount:9450000000000000000
        endAmount:945000000000000000
        recipient:0xBB83214561E9690ff36639299494726944AA30Fc
    1:
        itemType:1
        token:0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619
        identifierOrCriteria:0
        startAmount:250000000000000000
        endAmount:25000000000000000
        recipient:0x0000a26b00c1F0DF003000390027140000fAa719
    2:
        itemType:1
        token:0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619
        identifierOrCriteria:0
        startAmount:100000000000000000
        endAmount:10000000000000000
        recipient:0xBB83214561E9690ff36639299494726944AA30Fc
    3:
        itemType:1
        token:0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619
        identifierOrCriteria:0
        startAmount:200000000000000000
        endAmount:20000000000000000
        recipient:0x5dC61e930533136AbE35C1b442823259D6c07694
startTime:1669365422
endTime:1669970222
orderType:1
zone:0x0000000000000000000000000000000000000000
zoneHash:0x0000000000000000000000000000000000000000000000000000000000000000
salt:24446860302761739304752683030156737591518664810215442929815699357387149085795
conduitKey:0x0000007b02230091a7ed01230072f7006a004d60a8d4e71d599b8104250f0000
counter:0
```

## 固定价格上链
