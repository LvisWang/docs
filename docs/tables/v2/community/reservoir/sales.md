# 出售

## **reservoir.出售**

该表包含有关于每笔出售的信息记录

查询的示例可以在这里找到:

[https://dune.com/queries/1302771/2232036](https://dune.com/queries/1302771/2232036)

[https://dune.com/queries/1302775/2232040](https://dune.com/queries/1302775/2232040)

| **列名**      | **类型**  | **说明**                                   |
|----------------------|-----------|---------------------------------------------------|
| id                   | string    | 内部出售ID                                  |
| contract             | string    | 合约地址                                  |
| token\_id            | string    | 集合中的代币ID                 |
| order\_id            | string    | 相关订单ID                               |
| order\_kind          | string    | 协议名称 (e.g. seaport)                      |
| order\_side          | string    | 订单类型 (请求 / 拍卖)                            |
| order\_source        | string    | 列表来源 (e.g. opensea.io)           |
| from                 | string    | 制作者的钱包地址                              |
| to                   | string    | 接受者的钱包地址                              |
| price                | decimal   | 出售价格 (本地货币)                      |
| usd\_price           | string    | 出售价格(美元)                                 |
| currency\_address    | string    | 本次出售使用的货币地址           |
| currency\_symbol     | string    | 本次出售使用的货币代码            |
| currency\_price      | decimal   | 出售价格                                        |
| amount               | string    | 出售的货币数量                             |
| fill\_source         | string    | 订单执行的地方                       |
| aggregator\_source   | string    | 集合来源 (e.g. reservoir)                |
| wash\_trading\_score | int      | 内部洗涤交易评分 (基于过去的出售) |
| is\_primary          | boolean   | 交易铸造了吗？                                     |
| tx\_hash             | string    | 相关的交易哈希值                       |
| tx\_log\_index       | int       | 相关的交易日志索引                  |
| tx\_batch\_index     | int       | 相关的交易批次索引                |
| tx\_timestamp        | bigint    | 相关的交易时间戳                  |
| created\_at          | timestamp | 记录出售的时间戳                   |
| updated\_at          | timestamp | 更新出售的时间戳                    |                                                               |
