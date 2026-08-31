# deploy/ — 部署

> 部署配置与发布 SQL，子目录按需增设（`docker/`、`sql/`、`nginx/` 等）。

## 通用顺序

数据库 → 中间件 → 后端 → 前端 → 验收（用 [docs/plan 验收指南](../docs/plan/README.md) 账号）。

## 约定

- 发布 SQL（全量 + 版本增量）建议放 `deploy/sql/`，与开发期增量 [sql/](../sql/README.md) 分开。
- 配置与密钥走环境变量，不入库、不入镜像。
- 各环境的构建 / 启动细节随部署方案写入对应子目录。
