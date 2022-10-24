# token floor ask events

## **reservoir.token\_floor\_ask\_events**

该表包含有关于每个NFT代币地板价变化的记录.

查询的示例可以在这里找到:

[https://dune.com/queries/1302852/2232169](https://dune.com/queries/1302852/2232169)

[https://dune.com/queries/1302854/2232173](https://dune.com/queries/1302854/2232173)

| **列名** | **类型**  | **说明**                                                                                                 |
|-----------------|-----------|-----------------------------------------------------------------------------------------------------------------|
| id              | bigint    | 内部代币属性ID                                                                                     |
| kind            | string    | 事件类型（新订单、到期、出售、取消、余额变化、批准变化、引导、重新验证、重新定价） |
| contract        | string    | 合约地址                                                                                                |
| token\_id       | string    | 集合中的代币ID                                                                               |
| order\_id       | string    | 相关的请求ID                                                                                             |
| maker           | string    | 相关的制作者钱包地址                                                                             |
| price           | decimal   | 相关的请求价格 (本地货币)                                                                          |
| previous\_price | decimal   | 前一天的请求底价 (本地货币)                                                                          |
| nonce           | string    | 制作者的订单nonce值                                                                                    |
| valid\_from     | bigint    | 相关的有效请求开始                                                                                   |
| valid\_until    | bigint    | 相关的有效请求到期                                                                             |
| source          | string    | 订单来源 (e.g. opensea.io)                                                                           |
| tx\_hash        | string    | 相关的交易哈希值                                                                                     |
| tx\_timestamp   | bigint    | 相关的交易时间戳                                                                               |   
| created\_at     | timestamp | 记录事件的时间戳                                                                                |
