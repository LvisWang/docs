# 代币

## **reservoir.代币**

该表包含有关于每个NFT代币的信息记录.

查询的示例可以在这里找到:

[https://dune.com/queries/1303052/2232521](https://dune.com/queries/1303052/2232521)

[https://dune.com/queries/1303064/2232571](https://dune.com/queries/1303064/2232571)

| **列名**         | **类型**  | **说明**                    |
|-------------------------|-----------|------------------------------------|
| id                      | string    | 内部代币ID                  |
| contract                | string    | 合约地址                   |
| token\_id               | string    | 集合中的代币地址  |
| name                    | string    | NFT名称                           |
| description             | string    | NFT说明                    |                                                                                         |
| collection\_id          | string    | 相关的集合ID           |
| owner                   | string    | 拥有者的钱包地址               |
| floor\_ask\_id          | string    | 底部请求ID                       |
| floor\_ask\_value       | bigint    | 底部请求值                   |
| floor\_ask\_maker       | string    | 底部请求制作者的钱包地址     |
| floor\_ask\_valid\_from | bigint    | 底部请求列表的开始时间       |
| floor\_ask\_valid\_to   | bigint    | 底部请求列表的结束时间         |
| floor\_ask\_source      | string    | 底部请求来源(e.g. opensea.io) |
| last\_sale\_value       | bigint    | 相关的交易时间戳   |   
| last\_sale\_timestamp   | bigint    | 相关的交易时间戳   |   
| created\_at             | timestamp | 创建代币的时间戳    |
| updated\_at             | timestamp | 更新代币的时间戳   |                                                                          |
