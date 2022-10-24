# 属性

## **reservoir.属性**

该表包含有关于每个属性的信息记录.

查询的示例可以在这里找到:

[https://dune.com/queries/1302927/2232298](https://dune.com/queries/1302927/2232298)

[https://dune.com/queries/1302966/2232361](https://dune.com/queries/1302966/2232361)

| **列名**    | **类型**  | **说明**                                            |
|--------------------|-----------|------------------------------------------------------------|
| id                 | bigint    | 内部属性ID                                     |
| attribute\_key\_id | bigint    | 内部属性键ID                                  |
| value              | string    | 属性值                                            |
| token\_count       | bigint    | 具有属性的代币数量                   |
| on\_sale\_count    | bigint    | 正在出售的具有属性的代币数量 |
| floor\_sell\_value | decimal   | 当前的出售底价                                    |
| sell\_updated\_at  | timestamp | 最后更新底价的时间戳                  |
| collection\_id     | string    | 相关的集合ID                                   |
| kind               | string    | 值类型 (字符串, 数字, 日期, 范围)                   |
| key                | string    | 相关的键名称                                        |
| created\_at        | timestamp | 创建属性的时间戳                        |
| updated\_at        | timestamp | 更新属性的时间戳                        |
