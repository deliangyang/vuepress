---
sidebar: auto
---

# Hello VuePress

```json
{
  "test": 1
}
```
:tada: :100:
```sql
CREATE TABLE `room_admin` (
  `room_id` int(11) NOT NULL COMMENT '房间id',
  `user_id` int(11) NOT NULL COMMENT '用户id',
  `create_time` bigint(20) DEFAULT NULL COMMENT '创建时间',
  PRIMARY KEY (`room_id`,`user_id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COMMENT='房间管理员'
```

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |