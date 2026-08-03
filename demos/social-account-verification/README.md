# 社媒账号认证与数据同步 Demo

该单文件静态原型用于讨论和验证社媒账号绑定、认证审核与状态反馈。

## 覆盖场景

- Instagram、TikTok、YouTube、Twitch、X、Facebook 多平台账号管理。
- 模拟 OAuth 授权与人工截图认证。
- 认证状态、历史记录、驳回原因与重新提交。
- 报名资格拦截及账号选择。
- 运营端审核通过、驳回、冲突提示与通知同步。
- 空态、错误态和异常恢复路径。

## 运行方式

直接用浏览器打开 [`index.html`](index.html)，或在仓库根目录运行 `python -m http.server 8000` 后访问 `/demos/social-account-verification/`。

OAuth 地址和主页链接只用于模拟展示或手动点击；页面不会自动请求外部服务。所有身份、邮箱、账号、时间及审核记录均为示例数据。
