# 请求

## **reservoir.请求**

该表包含有关于每个列表信息的记录.

查询的示例可以在这里找到:

[https://dune.com/queries/1302885/2232229](https://dune.com/queries/1302885/2232229)

[https://dune.com/queries/1302904/2232257](https://dune.com/queries/1302904/2232257)

| **列名**     | **类型**  | **说明**                              |
|---------------------|-----------|----------------------------------------------|
| id                  | string    | 内部订单ID                            |
| kind                | string    | 协议名称 (e.g. seaport)                 |
| status              | string    | 订单状态 (活跃的, 不活跃的)              |
| contract            | string    | 合约地址                             |
| token\_id           | string    | 集合中的代币ID            |
| maker               | string    | 制作者的钱包地址                         |
| taker               | string    | 接受者的钱包地址                        |
| price               | decimal   | 当前的价格 (本地货币)          |
| start\_price        | bigint    | 列表的初始价格 (用于荷兰拍卖)     |
| end\_price          | bigint    | 列表的结束价格 (用于荷兰拍卖)       |
| currency\_address   | string    | 货币地址                             |
| currency\_symbol    | string    | 货币代码                              |
| currency\_price     | decimal   | 货币价格                               |
| dynamic             | boolean   | 是荷兰拍卖                            |
| quantity            | bigint    | 列表的代币数量              |
| quantity\_filled    | bigint    | 执行的代币数量             |
| quantity\_remaining | bigint    | 剩余的代币数量                   |
| valid\_from         | bigint    | 列表开始时间                          |
| valid\_until        | bigint    | 列表结束时间                             |
| nonce               | string    | 制作者订单的nonce值                 |
| source              | string    | 列表的来源 (e.g. opensea.io)      |
| fee\_bps            | bigint    | 列表费用                                  |
| expiration          | bigint    | 相关的交易哈希值                  |
| raw\_data           | string    | 原始订单数据（每个来源的格式会有所不同） |
| created\_at         | timestamp | 创建列表的时间戳            |
| updated\_at         | timestamp | 更新列表的时间戳            |
