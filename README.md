# <center>nonebot-plugin-getbapics</center>
## 使用方法
* 输入```/setu+[tag]+[x|X|*][num]+量词```使用
* tag自选， ```x``` ```X``` ```*```可选，num可选，量词可选```张``` ```个``` ```份```
* 输入 /setu open/close/开启/关闭 r18/ai 开启/关闭 获取r18/ai图功能
* 输入 /setu help|帮助 获取帮助
### 例子
* ```/setu```
* ```/setu 4```
* ```/setu 美游 x4张```
* ```/setu x4张```
* ```/setu 美游 x4个```
* ```/setu 美游 4张```
* ```/setu 美游 4```

## 环境变量
* `BAPICS_BLACK_LIST` : 黑名单群、用户
* `BAPICS_WHITE_LIST` : 白名单群、用户 
* `BAPICS_RULE` : 选择使用白名单模式或黑名单模式，默认为黑名单模式，值为 `blacklist` 或 `whitelist` 之一 
* `MAX_PICS` : 最大单次获取图片数量 


## 目前可公开的情报：
```
1. 支持群聊/私聊
2. API流量有限制，不要过于频繁调用
3. 图片过大可能发送时间较长，请耐心等待
4. adapter-red没有获取发送者id的功能，所以没写r18/ai鉴权
```
~由于4.的原因群炸了和我无关~
## TODO：

- [x] 多图发送功能
- [x] 自定义tag
- [ ] 指定画师获取setu
- [x] 允许开关是否发送AI图
- [x] 允许开关是否发送r18图功能
