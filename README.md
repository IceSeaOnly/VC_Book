# VC_Book
虚拟货币历史数据库

## 此项目保存了不同货币每天的分钟级数据变化情况，以文本的形式格式化存储，方便需要的朋友进行大数据分析。
### 每6小时更新一次数据

参数释义:

| Name | 含义 | 
| - | -: | 
| amount | 成交量|
| askAmount| 卖1量 |
| askPrice | 卖1价 |
| bidAmount | 买1量 |
| bidPrice | 买1价 |
| close | 收盘价,当K线为最晚的一根时，是最新成交价 |
| count | 成交笔数 |
| created | 本系统创建该条记录时间戳 |
| createdTime | 本系统创建该条记录时间 |
| high | 最高价 |
| low | 最低价 |
| open| 开盘价|
| vol | 成交额, 即 sum(每一笔成交价 * 该笔的成交量)|


数据来自 http://www.huobipro.com
