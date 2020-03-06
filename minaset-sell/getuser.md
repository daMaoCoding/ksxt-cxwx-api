# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/mineral/getuser```
* type:GET
* params:

| 字段  | 类型    | 是否必填 |
| ----- | ------- | -------- |
| token | string  | 是       |
| bean  | Mineral | 否       |



# 出参

| 字段    | 类型       | 值                          |
| ------- | ---------- | --------------------------- |
| status  | string     | 1 成功<br />其他表示失败    |
| message | string     | 对status的描述              |
| data    | JsonObject | List`<Mineral>`的列表字符串 |
| code    | string     | 0                           |

