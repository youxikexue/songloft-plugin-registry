# Songloft 插件源

Songloft 独立公开插件源仓库。在 Songloft 后台添加订阅源即可使用以下插件。

## 使用方式

1. Songloft → 设置 → JS 插件管理 → 插件商店 → 管理订阅源
2. 添加订阅源地址：

   ```
   https://raw.githubusercontent.com/youxikexue/songloft-plugin-registry/main/registry.json
   ```

3. 刷新即可看到插件，一键安装。

## 插件列表

| 插件 | 版本 | 说明 |
|------|------|------|
| LX音乐桥 | 2.5.2 | 连接 lxserver 与 MIOT 插件 |

## 目录结构

```text
registry.json
plugins/
  lxbridge/
    plugin.json     插件元数据
    manifest.json   版本与下载信息
    static/icon.svg 插件图标
```

## 发布流程

见项目 `03技术方案/技术方案.md`：构建并发布 Release 后，同步插件源元数据副本并推送本仓库。

## 许可证

各插件元数据与资源归各自作者所有；本仓库仅承载插件源的元数据与图标资源。
