## 直播地址

### 发布地址快速入门（推流地址）

标准的 RTMP 发布地址有两部分组成：**连接地址** `rtmp://yourcompany.com/appName` 及 **直播流名称** `streamName`。分别用来连接您的服务器上的对应的应用及校验直播流的信息。

### 新建发布地址

#### 单推流地址

部分供应商仅提供一个单独的推流地址，类似于 `rtmp://yourcompany.com/appName/streamName`。

对于这类地址，新建时请选择 **单推流地址** 这一方式。

#### 推流地址 + 推流码

部分供应商会在 **连接地址** 上使用复杂的 URLQuery 来提高安全性，类似 `rtmp://yourcompany.com/appName?user=User&token=Token&...`，并会同时提供 **直播流名称** `streamName`（也有称为推流码）。

对于这类地址，新建时请选择 **推流地址 + 推流码** 这一方式。


