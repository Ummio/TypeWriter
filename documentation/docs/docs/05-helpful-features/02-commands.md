---
difficulty: 简单
---

# 命令

TypeWriter 插件提供了一些实用的命令。以下是这些命令的列表:

:::tip[参数类型]
某些参数是可选的 `[]`，某些是必需的 `<>`。\
条目参数接受条目标识符和条目名称。
:::

| 命令名称                                        | 描述                                   | 权限                           |
| --------------------------------------------- | -------------------------------------- | ------------------------------ |
| `/tw connect`                                 | 连接到 TypeWriter 面板                  | typewriter.connect             |
| `/tw clearChat`                              | 以 TypeWriter 的方式清除你的聊天记录      | typewriter.clearChat           |
| `/tw cinematic <start/stop> <pageName> [player]` | 为指定玩家播放选定的过场动画             | typewriter.cinematic.start/stop |
| `/tw reload`                                 | 重新加载插件                             | typewriter.reload              |
| `/tw facts [player]`                         | 获取指定玩家的所有事实                    | typewriter.facts               |
| `/tw facts set <factEntry> <value> [player]` | 设置指定玩家的事实                       | typewriter.facts.set           |
| `/tw facts reset`                            | 重置指定玩家的所有事实                    | typewriter.facts.reset         |
| `/tw trigger <entry> [player]`               | 为指定玩家触发一个条目                    | typewriter.trigger             |
| `/tw assets clean`                           | 清理所有未使用的资源                      | typewriter.assets.clean        |
| `/tw fire <entry> [player]`                  | 触发一个火焰触发器事件条目                | typewriter.fire                |
| `/tw manifest inspect [player]`              | 检查玩家的活动清单                       | typewriter.manifest.inspect    |
| `/tw quest track <questEntry> [player]`      | 开始跟踪玩家的任务                       | typewriter.quest.track         |
| `/tw untrack [player]`                       | 取消跟踪玩家的任务                       | typewriter.quest.untrack       |
| `/tw roadNetwork edit <roadNetworkEntry>`    | 编辑道路网络                            | typewriter.roadNetwork.edit    |
