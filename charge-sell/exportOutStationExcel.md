# 入参

* url：```https://2858y3h397.qicp.vip/cxwx/receiveEntRecharge/exportOutStationExcel```
* type:GET
* params:

| 字段          | 类型    | 是否必填 |
| ------------- | ------- | -------- |
| token         | string  | 是       |
| receiveEntId1 | string  | 是       |
| startTime1    | string  | 是       |
| endTime1      | string  | 是       |
| pageSize      | Integer | 否       |
| pageNumber    | Integer | 否       |

# 出参

>返回excel文件
>
>

# 示例

* 请求

>`https://2858y3h397.qicp.vip/cxwx/receiveEntRecharge/exportOutStationExcel?token=123456&receiveEntId1=&startTime1=2020-01-01&endTime1=2020-03-07&pageSize=10&pageNumber=1`
>
>

* 响应

>返回下载的excel文件
>
>