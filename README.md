# todos-serverless-dynamodb-local

- 参考：[Serverless 架构应用开发：使用 serverless-offline 在本地部署与调试](https://www.phodal.com/blog/serverless-architecture-development-serverless-offline-localhost-debug-test/)

## 安装

- `npm install -g serverless`
- `serverless dynamodb install`，如需单独启动 dynamodb，使用 `sls dynamodb start`
- 服务启动： `serverless offline start` 或者 `sls offline start`

- 测试数据写入： `curl -X POST -H "Content-Type:application/json" http://localhost:3000/dev/todos --data '{ "text": "Learn Serverless" }'`
- 查询：`http://localhost:3000/dev/todos`

## 文档

- [serverless-dynamodb-local](https://www.npmjs.com/package/serverless-dynamodb-local)
