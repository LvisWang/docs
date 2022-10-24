# 集合

## **reservoir.集合**

该表包含有关于每个NFT集合的信息记录.

查询的示例可以在这里找到:

[https://dune.com/queries/1302781/2232054](https://dune.com/queries/1302781/2232054)

[https://dune.com/queries/1302788/2232065](https://dune.com/queries/1302788/2232065)

| **列名**            | **类型**  | **说明**                             |
|----------------------------|-----------|---------------------------------------------|
| id                         | string    | 内部集合ID                      |
| slug                       | string    | 集合标题                             |
| name                       | string    | 集合名称                             |
| description                | string    | 集合说明                      |
| token\_count               | bigint    | 集合中的代币ID           |
| contract                   | string    | 合约地址                            |
| day1\_rank                 | bigint    | 前1日的排名                 |
| day7\_rank                 | bigint    | 前7日的排名              |
| day30\_rank                | bigint    | 前30日的排名             |
| all\_time\_rank            | bigint    | 所有时间的排名                            |
| day1\_volume               | decimal   | 前1日的交易量            |
| day7\_volume               | decimal   | 前7日的交易量         |
| day30\_volume              | decimal   | 前30日的交易量        |
| all\_time\_volume          | decimal   | 所有时间的交易量                       |
| day1\_volume\_change       | double    | 前1日的交易量变化     |
| day7\_volume\_change       | double    | 前7日的交易量变化  |
| day30\_volume\_change      | double    | 前30日的交易量变化 |
| floor\ask\_value           | decimal   | 当前的出售底价 (本地货币)  |
| day1\_floor\_sale\_value   | decimal   | 前1日的出售底价        |
| day7\_floor\_sale\_value   | decimal   | 前7日的出售底价                 |
| day30\_floor\_sale\_value  | decimal   | 前30日的出售底价                |
| day1\_floor\_sale\_change  | double    | 前1日的出售底价变化   |
| day7\_floor\_sale\_change  | double    | 前7日的出售底价变化     |
| day30\_floor\_sale\_change | double    | 前30日的出售底价变化    |
| created\_at                | timestamp | 创建集合的时间戳        |
| updated\_at                | timestamp | 更新集合的时间戳        |                                                               |
