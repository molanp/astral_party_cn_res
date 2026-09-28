# 星引擎 Party 美术资源

资源概览

1. char_names.json 35 角色 id->中文名
2. map_names.json 24 地图 id->中文名
3. char*art/<id名>/ 角色美术, 文件按分类前缀命名, manifest.json 记录来源:
   rolephoto=立绘 profilephoto=头像 bust=半身 card/card2/thincard=卡面
   levelup=升级/好感图 standing=局内立绘 story=角色故事图
   emoji*<id>_<n>.png=静态表情 emoji_dyn_<id>\_<n>.apng=动态表情(透明,见下方章节)
   - account*avatars/ account_frames/ player_photos/
     目录名统一用"纯名字"(如 125*摩西), 不含称号后缀, 避免同角色分裂成两个文件夹。
4. map_art/<id名>/ 34 PNG 地图预览图(preview)+场景图(scene) + manifest.json
5. card_art/ 游戏内卡牌美术(道具, 非角色) + manifest.json:
   handcard/<id>.png 手牌/技能卡正面 (id 1xxxx/2xxxx, \_sfw=内容和谐版)
   cardback/<id>.png 卡背 (id 75xxx)
   cardback_item/<id>.png 卡背道具图 (另一 bundle, 与 cardback 同 id 不同用途)

## 资源更新

运行 `extract_all.py`

For Windows

# 版权

美术资源的版权属于<吉星派对>开发团队所有，本仓库仅作美术资源的展示
