## 使用方式
```javascript
var message = new Message();
// 消息类型：普通提示信息；默认展示3000ms
message.showMessage("消息内容", "info", 3000);
// 消息类型：成功提示信息；默认展示3000ms
message.showMessage("消息内容", "success", 3000);
// 消息类型：警告提示信息；默认展示3000ms
message.showMessage("消息内容", "warning", 3000);
// 消息类型：错误提示信息；默认展示3000ms
message.showMessage("消息内容", "error", 3000);
