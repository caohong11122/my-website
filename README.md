# 商图工坊

女裤电商主图与详情图工作台。

网页：https://caohong11122.github.io/my-website/

GitHub Pages 从 main 分支根目录发布。仓库仅包含静态前端与示例素材，无 API 密钥、访问令牌、账号数据或私有生成图片。

## 生图后端

生图由 config.js 中配置的独立服务提供，GitHub Pages 不运行 Node.js 服务。当前后端通过临时 Cloudflare Quick Tunnel 连接本机，需要本机与隧道保持运行；隧道地址改变时更新 config.js。后端停止后网页仍可打开和编辑，生图不可用。

参考网页链接仅保存，参考图片可参与生图。各设备项目保存在各自浏览器，可导出 JSON 备份。
