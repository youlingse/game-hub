# 游戏集

个人小游戏大厅，使用 GitHub Pages 发布。

## 更新游戏目录

以后新增游戏时，只需要编辑 `games.json` 并提交。首页会自动读取它生成游戏卡片。

每个游戏对象至少包含：

```json
{
  "id": "game-id",
  "title": "游戏名称",
  "shortTitle": "卡片短标题",
  "description": "一句话介绍",
  "type": "游戏类型",
  "tags": ["标签"],
  "url": "https://example.github.io/game/",
  "accent": "#f4b35e",
  "posterBg": "#3a3020",
  "posterLine": "rgba(244,179,94,.44)",
  "posterHalo": "rgba(244,179,94,.08)",
  "number": "04 / NEW GAME"
}
```

如果 `games.json` 加载失败，首页仍会使用内置的三款游戏目录作为备用数据。
