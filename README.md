# vikunja

Vikunja 待办/任务管理：任务增删改查、项目与看板桶、标签、指派、评论、关联、附件、保存筛选器、团队与分享、通知、订阅、Webhook、时间跟踪、数据导入、实例管理；并附通用 API 直通工具兜底

HologramAgent 插件，随 SDK `1.0.1` 的示例插件拆分而来。

## 构建

```bash
hmapdev build
```

产物 `dist/vikunja_bundle.hmap` 经 `plugin_install` 安装。

## 自动更新

本仓库地址登记在 `plg.json` 的 `repo` 字段，安装后随产物写入
`plugin.json` 的 `repository` 字段 —— 内核的 `plugin_update` 靠它
从本仓库拉最新源码并重编安装。
