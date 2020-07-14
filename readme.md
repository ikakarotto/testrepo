# 該系統依賴mongodb以及redis, 部署時需指定redis和mongodb地址

### 容器變量
|變量名稱    |變量參考值|
|--------    |----------|
|MONGODB_URI | mongodb://192.168.10.121:27017 |
|REDIS_HOST  | 192.168.10.122 |
|REDIS_PORT  | 6379 |

### 運行容器
參考 [run.sh](./run.sh).
