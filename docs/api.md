
# API 参考

本页面用于展示 API 接口文档的编写方法，以下接口仅为文档示例，不提供真实后端服务。

## 获取文档列表

### 请求信息

| 参数 | 内容 |
| --- | --- |
| 请求方式 | GET |
| 请求路径 | /api/docs |
| 数据格式 | JSON |
| 接口功能 | 获取文档列表 |

### 返回示例

```json
{
  "code": 200,
  "message": "success",
  "items": [
    {
      "id": 1,
      "title": "使用指南"
    },
    {
      "id": 2,
      "title": "关于本项目"
    }
  ]
}
```

### 返回字段说明

| 字段 | 类型 | 说明 |
| --- | --- | --- |
| code | Integer | 响应状态码 |
| message | String | 响应消息 |
| items | Array | 文档列表 |
| id | Integer | 文档编号 |
| title | String | 文档标题 |

[返回首页](index.md)
