# 数字货币量化交易基础（2）

在上篇文章里，我简单介绍了一下如何获取火币网的数字货币行情，得到了很多的读者反馈：

+ 火币在国内被封了，无法访问
+ 太简单了，没有更加深入的介绍数字货币的量化交易

为了响应大家的要求，我趁着假期严肃的研究了一下，先将相关的研究成果分享出来。

本文包括如下几个部分：

+ 我应该关注那些数字货币？
+ 为什么需要数字货币交易所？
+ 数字货币的交易所是怎么运作的？
+ 如何选择交易所？
+ 如何进行数字货币的程序化交易？
+ 有哪些量化交易策略可以使用？

## 我应该关注哪些数字货币？

这个问题其实非常简单，只需要关注目前最主流的几个就行。

1. 比特币（BTC）
2. 莱特币（LTC）
3. 以太币（ETH）
4. 比特币现金（BCH）
5. 瑞波币（XPR）

## 为什么需要数字货币交易所？

这是一个非常好的问题。数字货币的重大创新中，最核心的一条就是去中心化。即数字货币的运行，不需要一个中心化的组织来管理。

但为了达到去中心化的目的，数字货币也必须要付出一定的代价。这个代价包括：

1、转账确认的速度慢

+ 比特币的安全确认时间大约是1小时
+ 莱特币的安全确认时间大约是10-15分钟
+ 以太币的安全确认时间大约是5-10分钟

这样的速度是没有办法满足很多用户需求的。

2、对用户使用的要求高

要能安全的使用数字货币进行支付和转账，你需要了解好多好多的概念，比如钱包地址、区块、确认、分叉等。
这些都增加了普通用户使用数字货币的复杂度。

数字货币交易所可以部分的解决这些问题，后面我细细讲解。

## 数字货币的交易所是怎么运作的？

数字货币交易所是一个完全中心化运作的组织，方便用户进行数字货币的交易，是一个交易中介。

交易所提供的服务主要包括：

1. 资产的管理，包括账户管理，账户下面的资金及数字货币资产管理。
2. 交易服务，包括订单的管理、交易撮合、交易的结算等。
3. 资讯服务，包括提供市场的行情、成交信息、订单队列等。

有一些交易所还会提供一些增值的服务，比如数字货币的期货交易，杠杆交易，融资或融币的交易。

交易所提供的交易品种包括：
1、法币与数字货币之间的交易，如：
+ BTC-USD，比特币与美元间的交易
+ BTC-EUR，比特币与欧元间的交易

2、数字货币之间的交易，如：
+ BTC-BCH，比特币与比特币现金之间的交易
+ BTC-LTC，比特币与莱特币之间的交易

对于一个普通用户而言，交易所会为用户创建一个虚拟账户，用户可以

1. 把资金从银行转账到交易所账户，简称充值。或者将资金从交易所账户转账到银行，简称提现。
2. 将数字货币从钱包转账到交易所账户，简称充币。或者将数字货币从交易所账户转账到钱包，简称提币。
3. 在交易所内部，使用交易所账户买卖数字货币。

为什么很多国家要加强对数字货币交易所的监管呢？
道理非常简单，你往交易所转入的都是真金白银，交易所只是给你开了个虚拟账户。交易所全凭着自己的信誉来获得你的信任。
如果交易所突然跑路了，网站打不开了，你的资金和数字货币资产可就都没有了。

在中国为了防范金融风险，直接取缔了所有私营的数字货币交易所，也是非常合理的。

## 如何选择交易所？

我的选择标准是，选择主流的、交易量大的、流动性好的交易所。

由于国内的交易所已经全部取缔了，因此你只能使用境外交易所提供的服务。推荐几个：

1. Bitfinex（www.bitfinex.com）
2. Bitstamp（www.bitstamp.net）
3. Bittrex（www.bittrex.com）
4. GDAX（www.gdax.com）

## 如何进行数字货币的程序化交易？

