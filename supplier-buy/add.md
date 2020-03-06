# 入参

* url:```https://2858y3h397.qicp.vip/cxwx/supplierEnt/supplierEntsave```
* type:POST
* params:

| 字段  | 类型        | 是否必填 |
| ----- | ----------- | -------- |
| token | string      | 是       |
| bean  | SupplierEnt | 否       |



# 出参

| 字段    | 类型    | 值                     |
| ------- | ------- | ---------------------- |
| status  | Integer | 1 成功<br />其他值失败 |
| message | string  | status的描述信息       |

# 示例

* 请求

>{
>"token":123456,
>"name": "岑溪市超达石业有限公司2",
>"supplierEndId": "03567AA13E1446C68B3AE3CD50232A31",
>"name1": "03567AA13E1446C68B3AE3CD50232A31",
>"legalPerson": "test",
>"contacts": "test",
>"mobile": "13800138000",
>"remark": "test"
>}

* 响应

>{
>  "state" : 1,
>  "message" : "OK",
>  "data" : null
>}